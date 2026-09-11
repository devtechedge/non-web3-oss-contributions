# Tracker Update — 11 September 2026

Reconciled from current upstream GitHub PR and issue states.

## Confirmed updates

- **brianc/node-postgres #3772 — MERGED**. Stops `Connection.sync()` from setting `_ending` so extended-query Sync is not treated as disconnect and later `ECONNRESET`/`EPIPE` errors are no longer swallowed for the connection lifetime. Fixes #3769. Merge commit: `9683053c1eac7f4a1f8910df0d7abdb5f0cb25a7`; merge time: 11 Sep 2026 13:06:54 UTC, merged by `brianc`. The commit was reworked to be SSH-signed plus DCO-signed at the maintainer's request before merge. The final upstream update (merge close-out reply) was recorded at 16:08:22 UTC.
- **brianc/node-postgres #3769 — CLOSED / completed** through #3772.
- All other open ledger rows re-verified unchanged: crewAI #7361, livekit/agents #7201 and #7199, TanStack/router #8314 and #8285, better-auth #11235, langgraphjs #2803, drizzle-orm #6258 (all still open, none merged).

## Reconciled totals

The published ledger contains **20 verified external upstream PR rows**: **8 open**, **7 merged**, and **5 closed without merge**, plus **9 pipeline / skip records**.

The previous snapshot was **9 open / 6 merged / 5 closed without merge**. The only newly verified ledger transition after that snapshot is **brianc/node-postgres #3772: OPEN → MERGED**, so the total PR count remains 20 while the open/merged split changes to 8/7.

## Counting policy

Issue comments and investigations are not counted as PRs. Other contributors' PRs are excluded from `devtechedge` totals. A contribution counts as merged only when the upstream PR itself is reported as merged.
