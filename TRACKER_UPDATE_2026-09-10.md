# Tracker Update — 10 September 2026

Reconciled from current upstream GitHub PR and issue states.

## Confirmed updates

- **pnpm/pnpm #14754 — MERGED**. Fixes `pnpm run "/pattern/" --no-bail` cancelling sibling scripts. Merge time: 10 Sep 2026 07:16:07 UTC.
- **pnpm/pnpm #14756 — MERGED**. Preserves existing dependency range operators and supported `npm:` / `jsr:` prefix behavior during versioned updates. Merge time: 10 Sep 2026 10:11:49 UTC.
- **pnpm/pnpm #14753 — MERGED**. Honors `lockfile:false` / `--no-lockfile` with `devEngines.packageManager.onFail=download`; reviewer follow-up was resolved and the PR then merged. Merge commit: `b84813b5a5fd59b3547934919e34e99a2693b1f0`; merge time: 10 Sep 2026 11:29:39 UTC. The final upstream update was recorded at 11:30:04 UTC.
- **pnpm/pnpm #14718 — CLOSED / completed** through #14754.
- **pnpm/pnpm #14728 — CLOSED / completed** through #14753.
- **pnpm/pnpm #14745 — CLOSED / completed** through #14756.
- **webpack/webpack #22026 — OPEN**. The original ESM/contenthash reproduction no longer reproduces on current main; no PR was opened by `devtechedge`.
- **webpack/webpack #22032 — OPEN**. Separate contributor's proposed `RuntimeModule.updateHash` change; not a `devtechedge` contribution.

## Reconciled totals

The published ledger contains **18 verified external upstream PR rows**: **9 open**, **5 merged**, and **4 closed without merge**, plus **9 pipeline / skip records**.

The previous snapshot was **10 open / 4 merged / 4 closed without merge**. The only newly verified ledger transition after that snapshot is **pnpm/pnpm #14753: OPEN → MERGED**, so the total PR count remains 18 while the open/merged split changes to 9/5.

## Counting policy

Issue comments and investigations are not counted as PRs. Other contributors' PRs are excluded from `devtechedge` totals. A contribution counts as merged only when the upstream PR itself is reported as merged.
