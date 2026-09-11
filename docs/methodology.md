# Scan methodology

Shared rules for every dated target scan in this directory. Scan files record only what is new on their date; carryover rows verified unchanged are not repeated.

## Selection criteria

A target is not marked **GO** merely because an issue is open. It must also be reproducible or source-verifiable, fit the contributor's stack, have a bounded patch, and have no visible owner or competing pull request. A target was rejected when any of the following applied:

- an open PR or prepared branch already existed;
- the issue author or another contributor had clearly claimed it;
- a maintainer had reserved the work or requested design first;
- repository policy would auto-close an unassigned PR;
- the issue was untriaged and expected behavior was ambiguous;
- the fix appeared to be in current `main` already;
- the report belonged to Web3/crypto (excluded entirely; belongs in the separate web3 ledger);
- the patch would be mainly churn, docs trivia, or difficult to validate locally;
- the work would refile an issue this account has already been auto-closed from.

## Pre-flight checklist (per target, before claiming)

- [ ] Refresh issue state, assignees, comments, and cross-referenced PRs via the core API.
- [ ] Re-read the repo's contribution and AI-assistance policy.
- [ ] Reproduce on the exact upstream default branch, not only the latest release.
- [ ] Post a concise, human-reviewed claim/approach comment only where etiquette calls for it (comment approval gate applies).
- [ ] Keep the patch bounded; add a failing-first regression where tests exist.
- [ ] Run the narrow test, formatter/linter/type checker, then the feasible package suite.
- [ ] Link the issue with the repository's required keyword and disclose AI assistance where required.
- [ ] Never compete with a PR that appears after this scan.

## Scan mechanics

Bulk issue discovery uses the core `repos/{owner}/{repo}/issues?labels=bug` endpoint, not the search API: the search endpoint trips its secondary rate limit after ~2 rapid calls. Competing-PR detection uses per-issue timeline `cross-referenced` events; a foreign-repo cross-reference that 404s when resolved as a PR is noise, not an open competitor.
