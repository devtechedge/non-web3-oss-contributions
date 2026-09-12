# ⚙️ Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull request by [@devtechedge](https://github.com/devtechedge). Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

![Total](https://img.shields.io/badge/upstream%20items-26-black?logo=git&logoColor=white) ![Open PRs](https://img.shields.io/badge/open%20PRs-14-blue?logo=github&logoColor=white) ![Merged](https://img.shields.io/badge/merged-7-brightgreen?logo=git&logoColor=white) ![Closed](https://img.shields.io/badge/closed%20not%20merged-5-red?logo=git&logoColor=white)

## 📊 Status

**26 external upstream PRs** as of 12 Sep 2026

## ✅ Merged pull requests

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| <img src="https://github.com/brianc.png?size=40" width="18" /> [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer sets `_ending`, so later `ECONNRESET`/`EPIPE` errors are not swallowed for the connection lifetime. Regression + integration tests. | 11 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | Honor `lockfile: false` with `devEngines.packageManager.onFail: download`: skip project env-lockfile sync, keep package-manager download/switch. Rust + TypeScript + tests + changeset. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` keeps the manifest's existing `^`/`~` operator and supported `npm:` / `jsr:` prefixes. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer kills sibling scripts after the first failure. | 10 Sep 2026 |
| <img src="https://github.com/SQLMesh.png?size=40" width="18" /> [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | Move `ModelTest.create_test()` to the calling thread so `execution_time` / `time_machine` use cannot race across workers. | 10 Sep 2026 |
| <img src="https://github.com/better-auth.png?size=40" width="18" /> [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | `test(open-api): lock in requestBody for /phone-number/verify`. | 9 Sep 2026 |
| <img src="https://github.com/biomejs.png?size=40" width="18" /> [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Add `useBetterDomTraversing` nursery rule ported from `eslint-plugin-unicorn`. | 8 Sep 2026 |

## 🔀 Open pull requests

| Repo | PR | What | Opened |
| --- | --- | --- | --- |
| <img src="https://github.com/ratatui.png?size=40" width="18" /> [ratatui/ratatui](https://github.com/ratatui/ratatui) | [#2771](https://github.com/ratatui/ratatui/pull/2771) | `portable-atomic` feature forwards to `ratatui-widgets`; the `Block` shadow now cfg-switches its `Arc` import to `portable_atomic_util`, so no_std targets without atomic pointers (thumbv6m / RP2040) compile with the documented feature. Fixes #2767. | 12 Sep 2026 |
| <img src="https://github.com/SQLMesh.png?size=40" width="18" /> [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6059](https://github.com/SQLMesh/sqlmesh/pull/6059) | `create_external_models` quotes column names whose unquoted form the dialect would case-fold (postgres `"ID"` was written as `ID` and loaded back as `id`), so the generated `external_models.yaml` describes the table again. Fixes #6058. | 12 Sep 2026 |
| <img src="https://github.com/project-akri.png?size=40" width="18" /> [project-akri/akri](https://github.com/project-akri/akri) | [#850](https://github.com/project-akri/akri/pull/850) | Config device plugin reports used virtual slots as `Unhealthy` from `ListAndWatch`, so kubelet no longer selects slots still held during the reclaim grace period and pod recreation no longer spams `UnexpectedAdmissionError` pods. Closes #849. | 12 Sep 2026 |
| <img src="https://github.com/vercel.png?size=40" width="18" /> [vercel/next.js](https://github.com/vercel/next.js) | [#98593](https://github.com/vercel/next.js/pull/98593) | `@next/codemod upgrade` keeps the project's `eslint` specifier when it already satisfies the `eslint-config-next` peer range (`^9` stays `^9` instead of being pinned to 10.10.0); when a bump is required it pins the highest release of the lowest satisfying major. New `resolveEslintUpgradeTarget` helper + decision-table unit tests. Closes #98417. Competing PR #98556 implements the same semantics. | 12 Sep 2026 |
| <img src="https://github.com/astral-sh.png?size=40" width="18" /> [astral-sh/ruff](https://github.com/astral-sh/ruff) | [#28542](https://github.com/astral-sh/ruff/pull/28542) | PYI002 diagnostic reworded to name the stub-file context so it no longer reads as a false claim about tests referencing neither target. Message-only; behavior unchanged. | 12 Sep 2026 |
| <img src="https://github.com/better-auth.png?size=40" width="18" /> [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11261](https://github.com/better-auth/better-auth/pull/11261) | Widen email/deletion callback `user` typing to `User & Record<string, any>` so `user.additionalFields` is visible in callback params. Type-level regression + changeset. | 11 Sep 2026 |
| <img src="https://github.com/crewAIInc.png?size=40" width="18" /> [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#7361](https://github.com/crewAIInc/crewAI/pull/7361) | Async `CancelledError` now emits `TaskFailedEvent` before re-raise so execution spans pop and retained Task/Agent/Crew graphs can GC. Regression tests. | 10 Sep 2026 |
| <img src="https://github.com/livekit.png?size=40" width="18" /> [livekit/agents](https://github.com/livekit/agents) | [#7201](https://github.com/livekit/agents/pull/7201) | Public `SpeechHandle.hold_interruptions()` context manager + demote realtime uninterruptible log to debug. Unit tests. | 10 Sep 2026 |
| <img src="https://github.com/livekit.png?size=40" width="18" /> [livekit/agents](https://github.com/livekit/agents) | [#7199](https://github.com/livekit/agents/pull/7199) | Cancel false-interruption resume timer on non-empty interim/preflight STT while paused. Maintainer confirmed a semantics conflict on the issue; awaiting their call. | 10 Sep 2026 |
| <img src="https://github.com/TanStack.png?size=40" width="18" /> [TanStack/router](https://github.com/TanStack/router) | [#8314](https://github.com/TanStack/router/pull/8314) | Fix retain-then-strip search middleware so Link/`buildLocation` without `search` omits stripped defaults. Regression tests + changeset. | 10 Sep 2026 |
| <img src="https://github.com/better-auth.png?size=40" width="18" /> [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11235](https://github.com/better-auth/better-auth/pull/11235) | Coalesce `$sessionSignal` bursts so overlapping notifies do not cancel in-flight `/get-session`. Regression tests. | 10 Sep 2026 |
| <img src="https://github.com/langchain-ai.png?size=40" width="18" /> [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433: prefix-scoped search no longer leaks sibling namespaces; exact-or-descendant matching in memory and Postgres stores. Changeset. | 8 Sep 2026 |
| <img src="https://github.com/drizzle-team.png?size=40" width="18" /> [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions; junction only when every column is an FK column. | 8 Sep 2026 |
| <img src="https://github.com/TanStack.png?size=40" width="18" /> [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns 400 for malformed JSON on GET/POST action payloads instead of an unhandled 500. Unit tests + changeset. | 7 Sep 2026 |

## 🚫 Closed (not merged)

| Repo | PR | What | Outcome |
| --- | --- | --- | --- |
| <img src="https://github.com/nodejs.png?size=40" width="18" /> [nodejs/undici](https://github.com/nodejs/undici) | [#5796](https://github.com/nodejs/undici/pull/5796) | Fix `fetch({ redirect: 'follow' })` hanging when a large 3xx redirect body pins the only keep-alive socket. | Closed 10 Sep 2026, no reason exposed |
| <img src="https://github.com/pallets.png?size=40" width="18" /> [pallets/jinja](https://github.com/pallets/jinja) | [#2268](https://github.com/pallets/jinja/pull/2268) | `indent(..., first=True)` honor `blank=False` on empty first line. | Rejected by maintainer as AI junk; do not refile #2176 |
| <img src="https://github.com/vitest-dev.png?size=40" width="18" /> [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11174](https://github.com/vitest-dev/vitest/pull/11174) | Browser-mode `define` double-stringify fix. | Auto-closed ~28s after open (AgentScan flag); do not refile |
| <img src="https://github.com/typescript-eslint.png?size=40" width="18" /> [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) | [#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855) | `no-meaningless-void-operator` skip AssignmentExpression. | Auto-closed ~28s after open (AgentScan flag); do not refile |
| <img src="https://github.com/Kludex.png?size=40" width="18" /> [Kludex/starlette](https://github.com/Kludex/starlette) | [#3533](https://github.com/Kludex/starlette/pull/3533) | `URL.include_query_params` stringified list/tuple values instead of repeated params. | Closed by author: competing PRs already covered it |

## 🎯 Issue claims

- Opened 12 Sep with an explicit override of the design gate: [vercel/next.js#98593](https://github.com/vercel/next.js/pull/98593) for [#98417](https://github.com/vercel/next.js/issues/98417) after the approach comment went unanswered; competing PR [#98556](https://github.com/vercel/next.js/pull/98556) implements the same semantics.

## 📄 License

MIT
