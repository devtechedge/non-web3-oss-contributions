# Non-Web3 OSS Triage Memory

Operational memory for evaluating future upstream non-Web3 OSS contribution opportunities.

This directory is intentionally more detailed than the public-facing README. It records prior attempts, current PR state, competing work, maintainer feedback, and explicit refile/duplication guidance so coding agents can avoid repeating work and focus on fresh opportunities.

## Data files

- `prs.json` — upstream pull-request history and current operational state.
- `issues.json` — issue-level history, attempted approaches, duplicates, and refile guidance.
- `repositories.json` — repository-level targeting notes and contribution history.

## Intended agent workflow

1. Read relevant triage records before proposing a new issue or PR.
2. Treat `do_not_duplicate` and `do_not_refile` as hard exclusion signals unless new upstream information materially changes the situation.
3. Re-check GitHub before acting because open PR state, mergeability, reviews, CI, and competing work can change.
4. Update the triage records after every meaningful outcome so future agents inherit the result.
