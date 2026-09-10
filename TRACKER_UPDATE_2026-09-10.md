# Tracker Update — 10 September 2026

## Newly confirmed since the previous reconciliation

- **pnpm/pnpm #14754 — MERGED**: fixes `pnpm run "/pattern/" --no-bail` cancelling sibling scripts. Merge commit: `16a06e3dbbc8dec80628fd853b73079e3e4d7cfb`.
- **pnpm/pnpm #14756 — MERGED**: preserves dependency range operators and supported registry-prefix behavior during versioned updates. Merge commit: `0c2694b42f358166fc6a055503ea956182949057`.
- **pnpm/pnpm #14753 — OPEN**: honors `lockfile:false` / `--no-lockfile` when `devEngines.packageManager.onFail=download`. Reviewer comments were resolved; PR remains open.

## Related issue outcomes

- **pnpm/pnpm #14718 — CLOSED, completed** via #14754.
- **pnpm/pnpm #14745 — CLOSED, completed** via #14756.
- **webpack/webpack #22026 — OPEN**: original reproduction is not reproducible on current main; no PR was opened by `devtechedge`.
- **webpack/webpack #22032 — OPEN**: separate contributor's broader `RuntimeModule.updateHash` proposal; not a `devtechedge` contribution.

## Tracker classification after reconciliation

- External PRs: **22**
- Open: **10**
- Merged: **5**
- Closed, not merged: **4**
- Pipeline / skipped: **9**

The tracker counts only external PRs in its PR totals. Issue comments, investigations, already-fixed issues, and other contributors' PRs are not counted as `devtechedge` PRs.
