# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-9-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-7-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/non-web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/non-web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Non-Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**22 external PRs** as of 12 Sep 2026 (IST): **10 open**, **7 merged**, **5 closed (not merged)**. **0 pipeline rows** - all 8 pipeline rows were discarded on 12 Sep 2026 (none are openable from this account).

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API.

**10 Sep day scoreboard: 10 upstream PRs opened** (serial). One of those ([typescript-eslint#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855)) was auto-closed by AgentScan ~28s after open - same class of automation flag as vitest #11174. Do not refile that issue from this account.

- First merge: [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667), 8 Sep 2026
- Latest merge: [brianc/node-postgres#3772](https://github.com/brianc/node-postgres/pull/3772), 11 Sep 2026 at 13:06:54 UTC
- Latest PR activity: [astral-sh/ruff#28542](https://github.com/astral-sh/ruff/pull/28542) opened 12 Sep; [brianc/node-postgres#3772](https://github.com/brianc/node-postgres/pull/3772) merged 11 Sep at 13:06:54 UTC; [livekit/agents#7199](https://github.com/livekit/agents/pull/7199) maintainer reply on the semantics 11 Sep (author reply posted 18:45 UTC)
- 12 Sep batch: the 11 Sep scan's entire top-5 was closed out with **zero PRs opened** (3 permanent skips, 2 parked on maintainer design replies) - see [Next contribution scan](#next-contribution-scan)
- Preference: prefer **tier-2 / tier-3** reputable mid-size repos when mega-repo queues are crowded

---

## Features

- Open PRs on other orgs, with one-line fix, diff size, and status
- Closed-not-merged rows (author or maintainer close)
- Discarded / skip list so the same bug is not raced twice
- Next-up row when a target is free (no competing PR)
- Merged section for **upstream repos only**
- Web3 work is tracked separately and not duplicated here

## Open pull requests

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [astral-sh/ruff](https://github.com/astral-sh/ruff) | [#28542](https://github.com/astral-sh/ruff/pull/28542) | PYI002 diagnostic reworded from "`if` test must be a simple comparison against `sys.platform` or `sys.version_info`" to name the stub-file context, so it no longer reads as a false claim about tests that reference neither target (the confusion in #27324). Message-only; behavior unchanged. `PYI002.pyi.snap` updated. | Open; awaiting CI / maintainer | 12 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11261](https://github.com/better-auth/better-auth/pull/11261) | Email and deletion callbacks in the core options were typed with the base `User`, hiding `user.additionalFields` from callback params even though fields arrive at runtime. Widened `user` to `User & Record<string, any>` across `sendVerificationEmail`, `sendResetPassword`, `onPasswordReset`, `onExistingUserSignUp`, change-email and delete-account callbacks (existing file pattern; the literal's inferred field types cannot thread back into callbacks in the same options object). Closes #11192. Type-level regression in `types.test.ts`. Patch changeset. | Open; PR title lint + Socket green; typecheck and targeted suites green locally; Greptile reviewed with one low-severity test-coverage note; Vercel authorize checks non-actionable | 11 Sep 2026 |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#7361](https://github.com/crewAIInc/crewAI/pull/7361) | Async `CancelledError` in `_aexecute_core()` now emits `TaskFailedEvent` before re-raise so `EventListener.execution_spans` is popped and retained Task/Agent/Crew graphs can GC. Closes #7351. +132/−1, 2 files. Regression tests for span cleanup + event emission. Asked maintainers to apply required `llm-generated` label (no self-label permission). | Open; `require-issue` green; waiting maintainer `llm-generated` label | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7201](https://github.com/livekit/agents/pull/7201) | Public `SpeechHandle.hold_interruptions()` context manager + demote realtime uninterruptible `input_speech_started` log to debug. Closes #7191. Unit tests included. | Open; CLA signed | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7199](https://github.com/livekit/agents/pull/7199) | Cancel false-interruption resume timer on non-empty interim/preflight STT while paused (VAD end_of_speech race). Re-arm only when not speaking. Closes #7198. +3 regressions; 12/12 in file. | Open; CLA signed; maintainer [longcw](https://github.com/longcw) confirmed on #7198 that interim transcripts intentionally do not clear the false-interruption timer, which conflicts with this PR's approach; close or a narrower fix offered 11 Sep, awaiting maintainer's call | 10 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8314](https://github.com/TanStack/router/pull/8314) | Fix retain-then-strip search middleware so Link/`buildLocation` without `search` omits stripped defaults (active matching vs empty URL). Closes #8309. Regression tests + changeset. | Open; awaiting maintainer | 10 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11235](https://github.com/better-auth/better-auth/pull/11235) | Coalesce `$sessionSignal` bursts so overlapping notifies do not cancel in-flight `/get-session` (leading + one trailing). Closes #11160. Focus/poll paths unchanged. Regression tests in `session-refresh.test.ts`. | Open; Greptile P1 addressed; Vercel deploy needs team authorize | 10 Sep 2026 |
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433. `search(["tenant","acme"])` no longer leaks sibling `acme-corp`. Exact-or-descendant match; empty prefix still returns everything on InMemoryStore; `:` rejected in labels. Postgres `= path OR LIKE path:%` plus segment-aware `listNamespaces`. Closes #2721. +337/−62, 8 files. Patch changeset for checkpoint + checkpoint-postgres. | Open; PR title lint + Socket Security green; CI in progress; changeset-bot will bump 10 packages | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions. Junction only if every column is an FK column (pure join table still `through`). SQLite/Cockroach now pass `columns` into `SchemaForPull`. Closes #6253. +212/−6, 7 files. Targets `rc5`. | Open; no labels; no CI checks yet; issue #6253 still open | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns **400** for malformed JSON on GET `?payload=` and JSON POST bodies (`SyntaxError`), instead of an unhandled 500. Action is not invoked. Patch changeset for `@tanstack/start-server-core`. Unit tests for both shapes. +114/−4, 3 files. Covers Shape 2 of #8237 (Shape 1 is already in #8220). | Open; CodeRabbit clean; first-time-contributor CI waiting on maintainer | 7 Sep 2026 |

Files for #2803: `libs/checkpoint/src/store/base.ts`, `libs/checkpoint/src/store/memory.ts`, `libs/checkpoint/src/tests/namespace.test.ts`, `libs/checkpoint-postgres/src/store/index.ts`, `libs/checkpoint-postgres/src/store/modules/search-operations.ts`, `libs/checkpoint-postgres/src/store/modules/utils.ts`, `libs/checkpoint-postgres/src/store/modules/utils.test.ts`, `.changeset/namespace-segment-boundary.md`.

Files for #6258: `drizzle-kit/src/cli/commands/pull-common.ts`, `drizzle-kit/src/dialects/sqlite/ddl.ts`, `drizzle-kit/src/dialects/cockroach/ddl.ts`, `drizzle-kit/tests/other/relations-to-typescript.test.ts`, `drizzle-kit/tests/postgres/pull.test.ts`, `drizzle-kit/tests/postgres/mocks.ts`, `changelogs/drizzle-kit/1.0.0-rc.5.md`.

Files for #8285: `packages/start-server-core/src/server-functions-handler.ts`, `packages/start-server-core/tests/server-functions-handler-invalid-json.test.ts`, `.changeset/clear-json-payload-400.md`.

Files for #7361: `lib/crewai/src/crewai/task.py`, `lib/crewai/tests/telemetry/test_task_cancellation_span_cleanup.py`.

Files for #11261: `packages/core/src/types/init-options.ts`, `packages/better-auth/src/types/types.test.ts`, `.changeset/soft-planets-listen.md`.

## Merged pull requests

| Repo | PR | What | Status | Merged |
| --- | --- | --- | --- | --- |
| [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer sets `_ending` (extended-query Sync is not disconnect), so later `ECONNRESET`/`EPIPE` are not swallowed for the connection lifetime. Closes #3769. Unit regressions + real-backend integration tests in `test/integration/gh-issues/3772-tests.js` (TCP-proxy reset); both fail pre-patch, pass after. Merge commit `9683053`. SSH-signed and DCO-signed per maintainer request. | **Merged** | 11 Sep 2026 13:06:54 UTC |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | Honor `lockfile: false` when `devEngines.packageManager.onFail: download`: skip project env-lockfile sync, keep package-manager download/switch, use global persistence when required. Rust v12 + TypeScript v11 + regression/e2e tests + changeset. Closes #14728. 3 commits, +240/−18, 9 files. | **Merged** | 10 Sep 2026 11:29:39 UTC |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` keeps the manifest's existing `^`/`~` operator and supported `npm:` / `jsr:` prefix behavior. Closes #14745. | **Merged** | 10 Sep 2026 10:11:49 UTC |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer kills sibling scripts after the first failure. Closes #14718. | **Merged** | 10 Sep 2026 07:16:07 UTC |
| [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | Move `ModelTest.create_test()` to the calling thread before the concurrent pool so `execution_time` / `time_machine` use cannot race across workers; keep creation inside the engine-adapter cleanup scope. Closes #6039. 3 commits, +24/−23, 1 file. | **Merged** | 10 Sep 2026 00:40:59 UTC |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | `test(open-api): lock in requestBody for /phone-number/verify`. Regression test merged upstream. | **Merged** | 9 Sep 2026 08:19:43 UTC |
| [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Add `useBetterDomTraversing` nursery rule ported from `eslint-plugin-unicorn`. Targeted tests passed. | **Merged** | 8 Sep 2026 16:58:53 UTC |

## Closed (not merged)

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [nodejs/undici](https://github.com/nodejs/undici) | [#5796](https://github.com/nodejs/undici/pull/5796) | Fix `fetch({ redirect: 'follow' })` hanging when a large 3xx redirect body pins the only keep-alive socket in a connection-limited `Agent`. Remember `this.willFollow`, discard followed 3xx body chunks without pausing so the connection drains and returns to the pool. Regression test uses `Agent({ connections: 1 })` and a 128 KiB 301 body; 2 files, +46/−1, 1 commit. | Closed **without merge** on 10 Sep 2026 at 00:48 UTC. No PR comments/review comments were returned; closure reason is not exposed by the available GitHub data. | 10 Sep 2026 |
| [pallets/jinja](https://github.com/pallets/jinja) | [#2268](https://github.com/pallets/jinja/pull/2268) | `indent(..., first=True)` honor `blank=False` on empty first line. Aimed at #2176. | Closed not merged by [@ThiefMaster](https://github.com/ThiefMaster); title marked **Rejected AI junk**. Do not refile #2176 from this account without a clear maintainer-welcome signal. | 10 Sep 2026 |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11174](https://github.com/vitest-dev/vitest/pull/11174) | Browser-mode `define` double-stringify. Parse via `deleteDefineConfig` clone so `FOO: JSON.stringify("BAR")` is `'BAR'` not `'"BAR"'`. Vite `config.define` left intact. Closes #11164. +17/−3, 4 files. | Closed ~28s after open by github-actions. AgentScan `bot` label; account flagged as likely LLM/agent. **Not merged.** Issue #11164 still open. Do not refile from this account. | 8 Sep 2026 |
| [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) | [#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855) | `no-meaningless-void-operator` skip AssignmentExpression (`void (x = 1)`). Aimed at #12852. | Closed ~28s after open by github-actions. AgentScan automation signal; **not merged.** Do not refile #12852 from this account. | 10 Sep 2026 |
| [Kludex/starlette](https://github.com/Kludex/starlette) | [#3533](https://github.com/Kludex/starlette/pull/3533) | `URL.include_query_params` stringified list/tuple values instead of emitting repeated params. | Closed by author (`devtechedge`): competing open PRs [#3529](https://github.com/Kludex/starlette/pull/3529) and [#3531](https://github.com/Kludex/starlette/pull/3531) already covered it. **Not merged.** | 9 Sep 2026 |

Files for #11174: `packages/vitest/src/node/plugins/testConfig.ts`, `test/e2e/fixtures/config/browser-define/basic.test.ts`, `test/e2e/fixtures/config/browser-define/vitest.config.ts`, `test/e2e/test/config/browser-configs.test.ts`.

## Discarded pipeline rows

The pipeline was emptied on 12 Sep 2026: none of its rows are openable from this account. Rows are kept here so the same bug is not raced again.

| Repo | Target | Discarded because |
| --- | --- | --- |
| [TanStack/router](https://github.com/TanStack/router) | [#8280](https://github.com/TanStack/router/issues/8280) | Competing open PR [#8283](https://github.com/TanStack/router/pull/8283) covers it (re-verified open 12 Sep 2026). Do not compete. |
| [TanStack/router](https://github.com/TanStack/router) | [#8237](https://github.com/TanStack/router/issues/8237) Shape 1 | Owned by open PR [#8220](https://github.com/TanStack/router/pull/8220) (re-verified open 12 Sep 2026); #8285 covers Shape 2 only. |
| [WordPress/Requests](https://github.com/WordPress/Requests) | [#1084](https://github.com/WordPress/Requests/issues/1084) | Investigation concluded a behavior-changing PR was not justified, and the upstream connection did not permit posting the verification comment. |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | [#7771](https://github.com/pydantic/pydantic-ai/issues/7771) | Public `BaseDurabilityCapability` export already fixed upstream. |
| [requests-cache](https://github.com/requests-cache/requests-cache) | [#1177](https://github.com/requests-cache/requests-cache/issues/1177) | Explicitly skipped: issue context asked LLMs not to be involved; later PR #1188 was closed as not viable by the maintainer. |
| [webpack/webpack](https://github.com/webpack/webpack) | [#22026](https://github.com/webpack/webpack/issues/22026) | Original ESM/contenthash reproduction fixed on current main. |
| [webpack/webpack](https://github.com/webpack/webpack) | [#22032](https://github.com/webpack/webpack/pull/22032) | Another contributor's open broader `RuntimeModule.updateHash` proposal; not a `devtechedge` contribution. |
| [prettier/prettier](https://github.com/prettier/prettier) | [#19985](https://github.com/prettier/prettier/issues/19985) | Already fixed upstream by [fisker's #19838](https://github.com/prettier/prettier/pull/19838) (merged 15 Aug 2026) before the issue was filed; closed 10 Sep 2026 via test-only [#20020](https://github.com/prettier/prettier/pull/20020). Do not chase. |

## Next contribution scan

**Batch closure (12 Sep 2026):** none of the five top-of-queue targets can be implemented as PRs from this account, confirmed and closed out the same day. [anyio#1094](https://github.com/agronholm/anyio/issues/1094) is skipped - not reproducible on `master` (instrumented harness verified 12 Sep; the owner's fix [#1092](https://github.com/agronholm/anyio/pull/1092), released in 4.13.0, plausibly already resolved it). [apscheduler#1083](https://github.com/agronholm/apscheduler/issues/1083) and [apscheduler#1095](https://github.com/agronholm/apscheduler/issues/1095) are skipped on owner design gates (DB-resilience steered to v4; requested misfire semantics confirmed not intended). [crawlee#2815](https://github.com/apify/crawlee/issues/2815) and [msw#2748](https://github.com/mswjs/msw/issues/2748) are parked indefinitely on maintainer design replies: an approach comment is posted on #2815 (no reply as of 12 Sep evening IST) and the msw regression was refiled as [mswjs/interceptors#835](https://github.com/mswjs/interceptors/issues/835) (0 comments as of 12 Sep evening IST). Per the design-gate rule, do not code on either until a maintainer answers. The actionable queue now starts at item 6 of the 11 Sep scan ([mswjs/msw#2401](https://github.com/mswjs/msw/issues/2401)).

11 Sep scan complete: **16 GO / 9 WAIT** targets across tier-2 / tier-3 non-web3 repos, all live-verified the same day (state, assignee, comment-thread claims, cross-referenced PRs). Top of the queue was [anyio#1094](https://github.com/agronholm/anyio/issues/1094), [apscheduler#1083](https://github.com/agronholm/apscheduler/issues/1083), [apscheduler#1095](https://github.com/agronholm/apscheduler/issues/1095), [crawlee#2815](https://github.com/apify/crawlee/issues/2815), [msw#2748](https://github.com/mswjs/msw/issues/2748) - all five now dispositioned above. See the [11 Sep scan](docs/scan-2026-09-11.md) for the full queue, gates, and skip ledger.

Key finding: fresh bug clusters in typeorm and sqlalchemy are heavily PR-raced right now (every checked issue already had 1-2 open competing PRs), which reinforces the tier-2 / tier-3 preference. Bulk issue discovery should use the core `repos/{}/issues?labels=bug` endpoint; the search API trips its secondary rate limit after ~2 rapid calls.

Still waiting (do not code yet):

1. **GO after policy check (comment posted):** [vercel/next.js#98417](https://github.com/vercel/next.js/issues/98417) — keep existing `eslint` when it already satisfies `eslint-config-next` peer; only bump when below range; prefer lowest satisfying major. Waiting on maintainer confirmation. Comment: https://github.com/vercel/next.js/issues/98417#issuecomment-5608267483

See [11 Sep scan](docs/scan-2026-09-11.md), [10 Sep scan](docs/scan-2026-09-10.md) and [9 Sep scan](docs/scan-2026-09-09.md). Research rows do not change contribution counts until a PR is opened.

## Counting policy

A contribution counts as **merged** only when the upstream repository reports the PR as merged. An open PR remains **open** even when its linked issue is closed. Issue comments, investigations, already-fixed issues, duplicate efforts, and other contributors' PRs do not count as `devtechedge` PRs.

## License

MIT License