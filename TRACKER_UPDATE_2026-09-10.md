# Tracker Update — 10 September 2026

Reconciled from current upstream GitHub PR and issue states.

## Confirmed updates

- **pnpm/pnpm #14754 — MERGED**. Fixes `pnpm run "/pattern/" --no-bail` cancelling sibling scripts. Merge commit: `16a06e3dbbc8dec80628fd853b73079e3e4d7cfb`.
- **pnpm/pnpm #14756 — MERGED**. Preserves existing dependency range operators and supported `npm:` / `jsr:` prefix behavior during versioned updates. Merge commit: `0c2694b42f358166fc6a055503ea956182949057`.
- **pnpm/pnpm #14753 — OPEN**. Honors `lockfile:false` / `--no-lockfile` with `devEngines.packageManager.onFail=download`; reviewer follow-up is resolved and the PR remains open.
- **pnpm/pnpm #14718 — CLOSED / completed** through #14754.
- **pnpm/pnpm #14745 — CLOSED / completed** through #14756.
- **webpack/webpack #22026 — OPEN**. The original ESM/contenthash reproduction no longer reproduces on current main; no PR was opened by `devtechedge`.
- **webpack/webpack #22032 — OPEN**. Separate contributor's proposed `RuntimeModule.updateHash` change; not a `devtechedge` contribution.

## Reconciled totals

The published ledger contains **18 verified external upstream PR rows**: **10 open**, **4 merged**, and **4 closed without merge**, plus **9 pipeline / skip records**. The prior headline of 19/12/3/4 was stale and inconsistent with the actual listed rows; it has been corrected rather than preserving an incorrect total.

## Counting policy

Issue comments and investigations are not counted as PRs. Other contributors' PRs are excluded from `devtechedge` totals. A contribution counts as merged only when the upstream PR itself is reported as merged.
