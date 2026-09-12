# Non-Web3 OSS Triage Memory

Operational memory for evaluating future upstream non-Web3 OSS contribution opportunities.

This directory is intentionally more detailed than the public-facing README. It records prior attempts, current PR state, competing work, maintainer feedback, and explicit refile/duplication guidance so coding agents can avoid repeating work and focus on fresh opportunities.

## Data file

- `triage.json` — canonical operational memory containing pull-request history, issue-level history, repository-level targeting notes, competing work, and refile/duplication guidance.

## Intended agent workflow

1. Read the relevant `triage.json` records before proposing a new issue or PR.
2. Treat `do_not_duplicate` and `do_not_refile` as hard exclusion signals unless new upstream information materially changes the situation.
3. Re-check GitHub before acting because open PR state, mergeability, reviews, CI, and competing work can change.
4. Update `triage.json` after every meaningful outcome so future agents inherit the result.
5. Keep `triage.json` as the single source of truth; do not recreate separate PR, issue, or repository state files.
