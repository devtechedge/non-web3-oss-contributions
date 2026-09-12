<!-- Mirror of ~/.agents/skills/oss/SKILL.md (canonical). Edit the canonical file, then re-sync this copy. -->

---
name: oss
description: Use when scanning, claiming, opening, babysitting, or tracker-updating upstream OSS PRs in the web3 or non-web3 lane, or when editing the user's own ledger repos (README, badges, About). Covers serial shipping, shared voice, comment approval, commit signing, maintainer-only watches, and ledger upkeep.
---

# OSS PR Playbook

One playbook for contributing pull requests to upstream open-source repositories. Work happens in one of two lanes, **web3** or **non-web3**. Pick the lane from the agent role, the tracker named in chat, or the user's request, and never mix lanes in one PR or one scoreboard row. Apply on every new PR unless the user overrides that turn.

Core goals, in priority order:

1. Quality over quantity: small, uncontested, mergeable fixes
2. A credible human voice with maintainers
3. One well-run PR at a time beats a spray of contested ones

Lane-specific learned patterns (scan triage, implementation gotchas, repo-specific no-gos) live in `PATTERNS.md` next to this file. Read it during scans and before implementing. Every pattern there is a lesson from a past PR or scan: re-verify it against current repo state, never assume it still holds.

## 1. Lanes

| | **Non-web3** | **Web3** |
| --- | --- | --- |
| Scope | TS/JS/Python/Rust libraries and tooling outside crypto | Wallets, TS SDKs, protocol-adjacent and blockchain libraries |
| Ledger | `non-web3-oss-contributions` | `web3-oss-contributions` (old `oss-contributions` redirects) |
| Ledger writes | Update after every open, merge, or close, same day | Update after every attempt outcome - open, no-go, merge, or close - same turn |
| Targeting | Prefer tier-2/3 mid-size repos when mega-repos are crowded | Prefer uncontested wallet/SDK/docs fixes; avoid unpaid core pile-ons |
| Account | The user's OSS account, typically `@devtechedge` | Same |

Upstream PR work is recorded on the ledger READMEs (section 9). Work in the user's own repositories is never listed on either ledger.

## 2. Permissions and approvals

- Act (comment, open PRs, request review) only as the authorized OSS account for the lane. Never post as any other account.
- Never comment, open a PR, or request review without permission in that turn, or a batch authorization covering those exact targets. A batch such as "open N uncontested PRs" covers uncontested in-scope targets only: no contested pile-ons, no tracker edits unless named.
- **Comment approval gate:** always ask before posting any PR comment, issue reply, or review: show the full text to the user as a draft and wait for explicit approval of that exact text, every time, no exceptions. A general go-ahead such as "work on this" authorizes the work, not the post; the draft still needs its own approval in the turn it would be posted. Post the approved text verbatim.
- Commit signing: check the repository's contribution policy and sign commits accordingly (DCO `Signed-off-by` trailer and/or cryptographic GPG/SSH signature) before pushing. See section 6 for the passphrase-hang failure mode.

## 3. Voice (non-negotiable)

- Professional, respectful, and concise. Lead with what changed and why; no performative filler.
- Never use em dashes in maintainer-facing text. Use a normal hyphen `-` or split the sentence.
- Never use emojis in PR comments, issue replies, reviews, or any maintainer-facing text. Plain text only, no exceptions (no 🙏, 👍, 🎉, etc.). This rule governs upstream interaction only - the user's own ledger READMEs deliberately use emojis and logos (section 9).
- Keep comments short-paragraphed: one to two sentences per paragraph with a blank line between them. No wall-of-text blocks in issues, PRs, or reviews.
- Prefer `Fixes #N` / `Closes #N` when the change fully resolves the issue.
- Informal tone is reserved for private chat with the user; all public text follows this section.
- Enforcement: a local PreToolUse hook (`~/.zcode/hooks/voice-gate.mjs`, registered in `~/.zcode/cli/config.json`) hard-blocks any `gh pr comment` / `gh issue comment` tool call whose inline body contains emojis or em/en dashes. If it fires, strip the offending characters and retry; never bypass or work around it. Inline `--body` text is checked; bodies passed via `--body-file` are not, so apply the same rules manually there.

## 4. Cadence and API hygiene

1. Open one new PR at a time. A second may run only with explicit user permission. Complete the full cycle per PR - claim, implement, test, open, ledger update (per lane rules), babysit - before hunting the next target. Follow-up pushes to an existing open PR (human review, actionable bot P1) are fine while the next hunt is queued.
2. Run one agent session per PR lifecycle (hunt, ship, babysit) and retire it when the PR merges or closes after the ledger update. The SKILL.md playbook and the tracker files carry the persistent state, so every fresh session stays small and bounded. Use long-running threads only for meta-discussion, never for PR work.
3. Keep GitHub API volume low; GitHub support warned the account about request volume (Sep 2026). One consolidated call over several narrow ones, reuse data already fetched instead of refetching, no `--paginate` on large collections, no parallel API fan-out, poll at most every 60 seconds while waiting on CI, and prefer event-driven watches (section 7). Check `gh api rate_limit` before heavy scans and stop well before the limit.
4. On `resource_exhausted`: stop parallel work, wait, then resume serially. If GitHub is the blocker, check `gh api rate_limit` separately. Do not thrash retries.
5. Stuck handling: if a step stays blocked for a long time - a hung command, a command that never returns, repeated identical failures, a wait that outlives any plausible runtime - assume something on the other end has failed: a dropped connection, a missing password, passphrase, or key, or a tool waiting on input that will never come. Stop hitting the wall. Report what is blocked and the evidence, then either move on to other queued work and revisit the blocker later, or ask the user a clarification question if only they can unblock it (credentials, auth, interactive prompts). Do not burn the session looping on one blocking step.

## 5. Target selection and GO criteria

A target is GO only when every item below holds. Re-check the timeline with `gh` immediately before claiming.

Hard gates:

- Open issue, no owning assignee, no competing open fix PR. Check the issue **timeline's** `cross-referenced` events for linked PRs, not just the body and comments - fresh bugs can have competing PRs before any triage comment lands (0 comments is not a clear field).
- No prior closed-unmerged PR on the same issue, or a clear reason why the earlier approach failed and the new one differs.
- The fix is owned by the repo being targeted; confirm companion packages (e.g. a `fastapi-users` bug may live in `fastapi-users-db-sqlalchemy`) before claiming.
- Reproducible or source-verifiable on the current default branch, and not already fixed on main even if the issue is still open.
- Bounded patch: small file count, plus tests where the repo has them.
- Outside contributions allowed: the repo must accept PRs from external contributors outright. If its CONTRIBUTING.md (or observed maintainer behavior) reserves PRs for maintainer-invited contributors - "open a PR only when a maintainer invites you", `help wanted` + approved approach, members-only, etc. - the repo is off-limits until such an invite exists on a specific issue. Do not code first and hope; leave at the scan stage.
- Stellar org default no-go: stellar/* repos are no-go unless an explicit maintainer invite exists on that specific issue. Only exception: stellar/stellar-docs, whose CONTRIBUTING.md accepts direct outside PRs for small fixes (typos, broken links, copy corrections) without an invite - re-verify its policy each cycle before relying on the exception. stellar/js-stellar-sdk remains invite-gated.
- Contribution policy satisfied: CLA, signed commits, required labels, repo accepting PRs.
- No design or policy gate pending. If semantics need maintainer agreement, comment the proposed approach and wait. Never code through the gate.

Freshness and aliveness:

- Repo is alive: pushed within the last ~3 months (`pushed_at`, not just `archived`). Uncontested issues in dormant repos (fuels-ts, alchemy-sdk-js, create-solana-program) are not targets.
- Issue is recent: opened within the past few days or the last few weeks (rough rule: 6 weeks or less). Treat age as a first-pass filter at discovery time (sort by newest), not a late check - months- or years-old issues are routinely closed on triage or already fixed.

Sizing and tilt:

- Always skip: contested issues, archived repositories, vague features needing design, and repeat AgentScan auto-close targets from the same account on the same issue.
- Repo size (both lanes): aim for small and mid-size repos; mega-repos are last-resort even when a target looks clean on paper. When two repos offer a comparable fix, pick the smaller one.
- Non-web3 tilt: prefer reputable mid-size repos (real usage, hundreds to low tens of thousands of stars).
- Web3 tilt: prefer uncontested wallet SDKs, TS clients, docs and typo fixes, small correctness bugs, and test hygiene. Prefer Superteam Earn or paid-adjacent paths over cold PRs into unpaid cores. Avoid AppKit/RainbowKit pile-ons already open, cold outsider PRs into Agave/Uniswap/Foundry cores, and invasive codegen without maintainer direction.
- Saturation cap: before adding a target from a repo, count the open PRs the account already has there. 1: fine. 2-3: only exceptional fixes. 4+: skip that repo for the cycle and hunt in fresh repos. Current per-repo counts are recorded in the web3 tracker's `docs/scan-notes.md`.

Scan mechanics (when asked to scan for N targets):

- Run read-only scan agents in parallel over disjoint repo groups; if the harness rejects parallel agents, retry one at a time. Each agent verifies per candidate: no assignee, no maintainer claim in comments, no cross-referenced or open PR (issue `timeline` plus PR keyword search), repo pushed recently. Agents never post anything.
- Bulk issue discovery uses the core `repos/{owner}/{repo}/issues?labels=bug` endpoint, not the search API: the search endpoint trips its secondary rate limit after ~2 rapid calls and kills the sweep; the core endpoint does not. Follow up with one `issues/{n}/timeline` call per shortlisted candidate for cross-referenced PRs.
- **Raced-target rule:** if the issue timeline or keyword search reveals a competing open PR for the same issue/behavior, immediately classify the candidate as **contested/raced**, stop evaluating it for GO, and move to the next candidate. Do not spend additional implementation effort, policy analysis, or deep testing on a raced target unless the competing PR later closes or upstream state materially changes.
- **Persistent tracker rule for raced targets:** when a raced/contested target is discovered, record it in the canonical `docs/triage/triage.json` in the existing format with the issue, related competing PR number(s), current status, verification date, and `do_not_duplicate: true`. This prevents future scans from rediscovering and re-evaluating the same race. Update the triage record if the competing PR closes, merges, or the issue changes materially.
- A `cross-referenced` event pointing at a foreign repo (issue numbers out of range for the repo, PR fetch returns 404) is noise, not an open competitor.
- Every scan re-verifies the existing candidate queue before adding new names. Candidates go stale in predictable ways: fixed on main, repo went dormant, a maintainer steered the design in comments (semi-contested, follow their stated direction exactly or skip), or a linked PR appeared. Stamp every candidate row with its verification date.
- A `Potential AI issue` label on an issue we claimed means maintainers are filtering AI-authored reports; any follow-up there must be extra precise and human.

## 6. Shipping steps

1. Default to fork, branch, and PR via `gh` when Cloud Agents are unavailable.
2. Minimal root-cause fix matching repo style. No drive-by refactors.
3. Add a focused regression that fails before and passes after, when tests exist.
4. Add a changeset when the repo uses changesets.
5. Use distinct branch names when multiple PRs target the same repo.
6. Sign commits per repo policy (DCO and/or cryptographic signature) before pushing. DCO sign-off (`-s`) needs no key; a passphrase-protected GPG/SSH key hangs background commits - if the hang happens, either retry with `-c commit.gpgsign=false` where the repo policy and history accept unsigned commits (own ledger repos), or prepare the branch and hand it to the user to sign and push (upstream repos requiring signatures). Only the user can enter the passphrase.
7. Fix actionable bot review findings on your own code (e.g. Greptile P1) on the same branch. Ignore noise.
8. Leave non-actionable checks alone: Vercel "authorize deploy", team-only checks, and first-contribution `action_required` workflow approvals.
9. All GitHub Actions and CI checks must be green before a PR is reported done. After each push, wait for checks to settle and confirm every check passes (or is non-actionable per step 8). A red check caused by your own change is actionable: read the failed job log, fix, push, confirm green. Never report a PR as done without confirming its checks passed; when a maintainer must manually approve the workflow run (`action_required`), say so explicitly instead of claiming green.
10. Report the PR URL, plus the scoreboard when batching.

## 7. Babysitting and auto-close (maintainer responses only)

Default for every new PR unless the user overrides. Prefer event-driven listeners over cron to save tokens.

- Wake on: `review-approved`, `review-changes-requested`, `review-commented`, `pr-comment`, `inline-review-comment`, plus `pr-merged` / `pr-closed` when the lane needs ledger updates on terminal events.
- Stay quiet on: CI runs, pushes, `review-requested`, and thread-resolve noise.
- Bots are no-ops: CodeRabbit, Greptile, Copilot, Vercel, Changeset, Dependabot, Qodo, github-actions, CLA assistant, and `*[bot]` accounts generally. A bot comment may still be worth surfacing to the user, but do not act on it.
- Act only on human maintainer or collaborator responses on your PRs: tell the user, and if a safe fix is clear, push it and reply in the approved voice, through the comment approval gate.
- "Please sign your commit" asks (e.g. Safe repos): check `gh api repos/OWNER/REPO/pulls/N/commits` for `.commit.verification`. If `verified: true` with reason `valid`, the ask is already satisfied; update the ledger status and wait for merge, no reply needed. If not signed, only the user can re-sign locally with their key; the agent prepares the branch, the user signs and pushes.
- Auto-close: if a PR is auto-closed shortly after opening, mark it Closed (not merged) when writing the ledger, delete the babysit, never refile that issue from the same account, and never reply to the auto-close bot. Prefer quieter mid-size repositories when auto-closes keep happening.

## 8. Email triage (OSS inbox)

- Confirm with the user whether flagged mail is actionable before acting.
- CLA emails: the user signs in the browser. Confirm only after the `license/cla` check succeeds. A passing recheck alone does not sign.
- Keep: human approvals, reviews, merges, security alerts, anything from real people.
- Discard or ignore: bot-only noise such as Copilot, Vercel authorize, Changeset, CodeRabbit, Qodo "paused for this user" notices (usually the repository's Qodo plan, not a GitHub ban), surveys, and sales.
- Use the correct existing Gmail labels for the OSS accounts. Never invent vague labels.

## 9. Ledger and own-repo writes

The ledger repos are the user's own; their READMEs are the product. Everything in this section lands on GitHub in the same turn it is decided - never leave such changes unwritten, and pushing needs no separate confirmation.

**How to write:** prefer direct GitHub CLI/API writes (`gh api` contents PUT / edit endpoints) for spot edits - do not clone-edit-push when a direct write does the same job faster. The user pulls via GitHub Desktop when needed. For whole-file transformations (styling sweeps across every table row), a scripted local rewrite is acceptable: `git pull --ff-only` first, re-read the file after any fetch, push the same turn, and rebase on origin if the push is rejected.

**Skill mirror:** the canonical playbook is `~/.agents/skills/oss/SKILL.md` plus its companion `PATTERNS.md`; never edit the copies in the ledger repos directly. Both ledger repos carry mirrors at `docs/SKILL.md` and `docs/PATTERNS.md`, each with a one-line HTML comment header marking it as a mirror. After every edit to a canonical file, regenerate both repos' mirrors (comment header + full canonical content) and push in the same turn - no separate confirmation needed. Check the mirror diff holds only the intended changes before pushing.

**Concurrent edits:** another session or the user may update a ledger repo minutes before you do. Always pull and re-read immediately before editing, and rebase rather than force if origin moved.

**Co-author trailers:** merged PRs from agent apps (e.g. Arena's `app/arena-ai-coding-agent`) can land `Co-authored-by: arena-agent` trailers, which GitHub credits in the Contributors sidebar. The user must be the sole contributor on ledger repos: strip such trailers before pushing own-repo commits. If one already landed, removing it requires a `git filter-branch --msg-filter` history rewrite and force push (verify the rewritten branch is clean, drop backup refs, expect SHA churn); this is the one case where a local rewrite beats a direct API write.

**Upstream ledger rules:**

- Non-web3: after opening a PR, add the Open table row and bump counts, status, and latest-open the same day. On merge or close, move the row and recount. Refresh next-scan notes when a queued item ships.
- Web3: after every PR attempt outcome - PR opened, no-go verdict, merge, or close - update the web3 repo the same turn: move or add the row, record no-go verdicts in the `⛔ Already tried, no-go` section, bump counts, badges, and the About, and refresh last-updated. Read the repo first to sync memory, re-read immediately before editing (concurrent-edit rule above), and match the existing table format. No per-write approval is needed; this rule is standing authorization.
- Tracker total: every tracker write, web3 or non-web3, moves the overall total: +1 for each open PR added, merge accepted, close, issue claim, and no-go entry recorded (no-go rows count toward the total). Recompute the total as the sum of all listed categories - open PRs, merged, closed, issue claims, no-go - verify the arithmetic, and update the total badge, snapshot line, and About in the same change as the rows. Never claim a merge that did not happen: verify merge state from the single-PR endpoint, not list endpoints, before writing a ledger row or a claim in chat.

**README structure (both ledger repos):** intro stating what the repo does, badge row, snapshot/status counts, Merged, Open pull requests, Closed (not merged), Issue claims, License. Nothing else - no Queue, Process, disposition, skip-ledger, or "latest opens" recap sections, and no live-search links. The one exception is the web3 repo's `⛔ Already tried, no-go` section, which holds no-go verdict rows; the non-web3 repo keeps its skip notes in `docs/` instead. Internal scan notes live in the repos' `docs/`, never in a README.

**README styling:**

- Badge row under the intro: static shields.io badges for total upstream items, open PRs (blue), merged (brightgreen), closed not merged (red), issue claims (blueviolet) - e.g. `![Open PRs](https://img.shields.io/badge/open%20PRs-35-blue?logo=github&logoColor=white)`.
- Org logos inline in table cells: `<img src="https://github.com/ORG.png?size=40" width="18" />` before the repo link; in the issue-claims table, inline before each issue link.
- Heading emojis: ⛓️ (web3 title) / ⚙️ (non-web3 title), 📊 Snapshot/Status, ✅ Merged, 🔀 Open pull requests, 🚫 Closed (not merged), 🎯 Issue claims, 📄 License. Emojis here are fine - the voice rules in section 3 govern maintainer-facing text only.
- When scripting bulk replacements, anchor them precisely (a `| [#` anchor intended for issue rows also matches every PR cell) and review the diff before pushing.

**Counts move together:** any edit that adds, merges, closes, claims, or no-go-records rows must bump the badge row (including the total badge), the snapshot counts, and the GitHub About description in the same change. The About mirrors the snapshot numbers, names one or two flagship merges, and stays under GitHub's 350-character limit.

## 10. Batch mode

When the user asks for N more PRs:

1. Confirm the batch authorization covers uncontested in-scope targets only, in the active lane.
2. Ship one at a time unless the user explicitly allows more parallelism.
3. On a skip (fixed or contested), say so briefly, record it in the web3 repo's no-go section when it is a web3-lane no-go verdict (section 9), and start the next.
4. Stop cleanly on a stop command or rate limit.

## 11. Checklist per new PR

1. Choose the lane and its ledger rules
2. Re-verify the target is free and GO
3. Confirm permission or batch authorization
4. Claim with a humanized comment (hyphen, never em dash)
5. Implement the fix plus a regression where tests exist
6. Sign commits per repo policy, then open the PR with Fixes/Closes
7. Show any comment drafts for approval before posting
8. Report the URL, plus the scoreboard if batching
9. Update the ledger same-turn for every attempt: non-web3 and web3 both - open rows, no-go rows, merge/close row moves; bump README badges/counts and the About to match
10. Confirm all CI checks green (or non-actionable) before considering the PR done
11. Babysit maintainer responses only
12. Handle human review, CLA, and terminal ledger updates
13. Only then start the next hunt
