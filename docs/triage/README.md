# Non-Web3 OSS Triage Memory

Canonical conversational gateway and operational memory for autonomous agents scanning, triaging, implementing, and tracking upstream non-Web3 OSS contributions.

## Single source of truth

- `triage.json` is the canonical agent context.
- Read `triage.json` before proposing, claiming, implementing, or submitting a new target.
- Use `do_not_duplicate` and `do_not_refile` as hard exclusion signals unless new upstream information materially changes the situation.
- Re-check live GitHub state before acting because issue state, reviews, CI, mergeability, assignees, and competing work can change.
- Update `triage.json` after every meaningful outcome so future agents inherit the result.

## What `triage.json` contains

- Agent operating rules and selection criteria.
- Pre-flight checks and scan mechanics.
- Complete pull-request history: merged, open, and closed-not-merged attempts.
- Issue-level history and relationships to pull requests.
- Refile and duplication exclusions.
- Repository-level contribution history, focus areas, and competing work.

This directory is intentionally operational rather than portfolio-facing. The root `README.md` remains the public contribution ledger.
