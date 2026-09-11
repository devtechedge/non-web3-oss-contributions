# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Languages](https://img.shields.io/badge/TypeScript%20%2B%20Python-library%20fixes-blue)](https://github.com/devtechedge)
[![Open PRs](https://img.shields.io/badge/open%20PRs-10-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-7-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged)

## Status

**22 external upstream PRs** as of 12 Sep 2026, 5 closed without merge. First merge [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667) on 8 Sep; latest merge [brianc/node-postgres#3772](https://github.com/brianc/node-postgres/pull/3772) on 11 Sep.

## Merged pull requests

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer sets `_ending`, so later `ECONNRESET`/`EPIPE` errors are not swallowed for the connection lifetime. Regression + integration tests. | 11 Sep 2026 |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | Honor `lockfile: false` with `devEngines.packageManager.onFail: download`: skip project env-lockfile sync, keep package-manager download/switch. Rust + TypeScript + tests + changeset. | 10 Sep 2026 |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` keeps the manifest's existing `^`/`~` operator and supported `npm:` / `jsr:` prefixes. | 10 Sep 2026 |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer kills sibling scripts after the first failure. | 10 Sep 2026 |
| [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | Move `ModelTest.create_test()` to the calling thread so `execution_time` / `time_machine` use cannot race across workers. | 10 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | `test(open-api): lock in requestBody for /phone-number/verify`. | 9 Sep 2026 |
| [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Add `useBetterDomTraversing` nursery rule ported from `eslint-plugin-unicorn`. | 8 Sep 2026 |

## Open pull requests

| Repo | PR | What | Opened |
| --- | --- | --- | --- |
| [astral-sh/ruff](https://github.com/astral-sh/ruff) | [#28542](https://github.com/astral-sh/ruff/pull/28542) | PYI002 diagnostic reworded to name the stub-file context so it no longer reads as a false claim about tests referencing neither target. Message-only; behavior unchanged. | 12 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11261](https://github.com/better-auth/better-auth/pull/11261) | Widen email/deletion callback `user` typing to `User & Record<string, any>` so `user.additionalFields` is visible in callback params. Type-level regression + changeset. | 11 Sep 2026 |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#7361](https://github.com/crewAIInc/crewAI/pull/7361) | Async `CancelledError` now emits `TaskFailedEvent` before re-raise so execution spans pop and retained Task/Agent/Crew graphs can GC. Regression tests. | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7201](https://github.com/livekit/agents/pull/7201) | Public `SpeechHandle.hold_interruptions()` context manager + demote realtime uninterruptible log to debug. Unit tests. | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7199](https://github.com/livekit/agents/pull/7199) | Cancel false-interruption resume timer on non-empty interim/preflight STT while paused. Maintainer confirmed a semantics conflict on the issue; awaiting their call. | 10 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8314](https://github.com/TanStack/router/pull/8314) | Fix retain-then-strip search middleware so Link/`buildLocation` without `search` omits stripped defaults. Regression tests + changeset. | 10 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11235](https://github.com/better-auth/better-auth/pull/11235) | Coalesce `$sessionSignal` bursts so overlapping notifies do not cancel in-flight `/get-session`. Regression tests. | 10 Sep 2026 |
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433: prefix-scoped search no longer leaks sibling namespaces; exact-or-descendant matching in memory and Postgres stores. Changeset. | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions; junction only when every column is an FK column. | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns 400 for malformed JSON on GET/POST action payloads instead of an unhandled 500. Unit tests + changeset. | 7 Sep 2026 |

## Closed (not merged)

| Repo | PR | What | Outcome |
| --- | --- | --- | --- |
| [nodejs/undici](https://github.com/nodejs/undici) | [#5796](https://github.com/nodejs/undici/pull/5796) | Fix `fetch({ redirect: 'follow' })` hanging when a large 3xx redirect body pins the only keep-alive socket. | Closed 10 Sep 2026, no reason exposed |
| [pallets/jinja](https://github.com/pallets/jinja) | [#2268](https://github.com/pallets/jinja/pull/2268) | `indent(..., first=True)` honor `blank=False` on empty first line. | Rejected by maintainer as AI junk; do not refile #2176 |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11174](https://github.com/vitest-dev/vitest/pull/11174) | Browser-mode `define` double-stringify fix. | Auto-closed ~28s after open (AgentScan flag); do not refile |
| [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) | [#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855) | `no-meaningless-void-operator` skip AssignmentExpression. | Auto-closed ~28s after open (AgentScan flag); do not refile |
| [Kludex/starlette](https://github.com/Kludex/starlette) | [#3533](https://github.com/Kludex/starlette/pull/3533) | `URL.include_query_params` stringified list/tuple values instead of repeated params. | Closed by author: competing PRs already covered it |

## Skipped targets

Previously vetted and skipped so the same bug is not raced again (verified 12 Sep 2026): [TanStack/router #8280](https://github.com/TanStack/router/issues/8280) and [#8237 Shape 1](https://github.com/TanStack/router/issues/8237) (covered by competing PRs), [WordPress/Requests #1084](https://github.com/WordPress/Requests/issues/1084), [pydantic-ai #7771](https://github.com/pydantic/pydantic-ai/issues/7771) and [prettier #19985](https://github.com/prettier/prettier/issues/19985) (already fixed upstream), [requests-cache #1177](https://github.com/requests-cache/requests-cache/issues/1177) (LLM-free request), [webpack #22026](https://github.com/webpack/webpack/issues/22026) (not reproducible on main) and [#22032](https://github.com/webpack/webpack/pull/22032) (another contributor's PR).

## Ongoing work

- Current queue, gates, and skip ledger: [11 Sep scan](docs/scan-2026-09-11.md); earlier: [10 Sep](docs/scan-2026-09-10.md), [9 Sep](docs/scan-2026-09-09.md). Selection criteria and checklist: [methodology](docs/methodology.md).
- Waiting on maintainer confirmation before coding: [vercel/next.js#98417](https://github.com/vercel/next.js/issues/98417); queue resumes at [mswjs/msw#2401](https://github.com/mswjs/msw/issues/2401).

A contribution counts as merged only when the upstream repository reports the PR as merged. Issue comments and other contributors' PRs are not counted.

## License

MIT
