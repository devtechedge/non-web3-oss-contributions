# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-9-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-6-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/non-web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/non-web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Non-Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**20 external PRs** as of 11 Sep 2026 (IST): **9 open**, **6 merged**, **5 closed (not merged)**. Plus **9 pipeline / skip** rows.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API.

**10 Sep day scoreboard: 10 upstream PRs opened** (serial). One of those ([typescript-eslint#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855)) was auto-closed by AgentScan ~28s after open - same class of automation flag as vitest #11174. Do not refile that issue from this account.

- First merge: [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667), 8 Sep 2026
- Latest merge: [pnpm/pnpm#14753](https://github.com/pnpm/pnpm/pull/14753), 10 Sep 2026 at 11:29:39 UTC
- Latest PR activity: [pnpm/pnpm#14753](https://github.com/pnpm/pnpm/pull/14753) merged at 11:29:39 UTC; final upstream update recorded at 11:30:04 UTC
- Preference: prefer **tier-2 / tier-3** reputable mid-size repos when mega-repo queues are crowded

---

## Features

- Open PRs on other orgs, with one-line fix, diff size, and status
- Closed-not-merged rows (author or maintainer close)
- Pipeline / skip list so the same bug is not raced twice
- Next-up row when a target is free (no competing PR)
- Merged section for **upstream repos only**
- Web3 work is tracked separately and not duplicated here

## Open pull requests

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#7361](https://github.com/crewAIInc/crewAI/pull/7361) | Async `CancelledError` in `_aexecute_core()` now emits `TaskFailedEvent` before re-raise so `EventListener.execution_spans` is popped and retained Task/Agent/Crew graphs can GC. Closes #7351. +132/−1, 2 files. Regression tests for span cleanup + event emission. Asked maintainers to apply required `llm-generated` label (no self-label permission). | Open; `require-issue` green; waiting maintainer `llm-generated` label | 10 Sep 2026 |
| [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer sets `_ending` (extended-query Sync is not disconnect), so later `ECONNRESET`/`EPIPE` are not swallowed for the connection lifetime. Closes #3769. Unit regressions + real-backend integration tests in `test/integration/gh-issues/3772-tests.js` (TCP-proxy reset); both fail pre-patch, pass after. | Open; CI 12/12 green | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7201](https://github.com/livekit/agents/pull/7201) | Public `SpeechHandle.hold_interruptions()` context manager + demote realtime uninterruptible `input_speech_started` log to debug. Closes #7191. Unit tests included. | Open; CLA signed | 10 Sep 2026 |
| [livekit/agents](https://github.com/livekit/agents) | [#7199](https://github.com/livekit/agents/pull/7199) | Cancel false-interruption resume timer on non-empty interim/preflight STT while paused (VAD end_of_speech race). Re-arm only when not speaking. Closes #7198. +3 regressions; 12/12 in file. | Open; CLA signed; Devin Review clean | 10 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8314](https://github.com/TanStack/router/pull/8314) | Fix retain-then-strip search middleware so Link/`buildLocation` without `search` omits stripped defaults (active matching vs empty URL). Closes #8309. Regression tests + changeset. | Open; awaiting maintainer | 10 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11235](https://github.com/better-auth/better-auth/pull/11235) | Coalesce `$sessionSignal` bursts so overlapping notifies do not cancel in-flight `/get-session` (leading + one trailing). Closes #11160. Focus/poll paths unchanged. Regression tests in `session-refresh.test.ts`. | Open; Greptile P1 addressed; Vercel deploy needs team authorize | 10 Sep 2026 |
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433. `search(["tenant","acme"])` no longer leaks sibling `acme-corp`. Exact-or-descendant match; empty prefix still returns everything on InMemoryStore; `:` rejected in labels. Postgres `= path OR LIKE path:%` plus segment-aware `listNamespaces`. Closes #2721. +337/−62, 8 files. Patch changeset for checkpoint + checkpoint-postgres. | Open; PR title lint + Socket Security green; CI in progress; changeset-bot will bump 10 packages | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions. Junction only if every column is an FK column (pure join table still `through`). SQLite/Cockroach now pass `columns` into `SchemaForPull`. Closes #6253. +212/−6, 7 files. Targets `rc5`. | Open; no labels; no CI checks yet; issue #6253 still open | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns **400** for malformed JSON on GET `?payload=` and JSON POST bodies (`SyntaxError`), instead of an unhandled 500. Action is not invoked. Patch changeset for `@tanstack/start-server-core`. Unit tests for both shapes. +114/−4, 3 files. Covers Shape 2 of #8237 (Shape 1 is already in #8220). | Open; CodeRabbit clean; first-time-contributor CI waiting on maintainer | 7 Sep 2026 |

Files for #2803: `libs/checkpoint/src/store/base.ts`, `libs/checkpoint/src/store/memory.ts`, `libs/checkpoint/src/tests/namespace.test.ts`, `libs/checkpoint-postgres/src/store/index.ts`, `libs/checkpoint-postgres/src/store/modules/search-operations.ts`, `libs/checkpoint-postgres/src/store/modules/utils.ts`, `libs/checkpoint-postgres/src/store/modules/utils.test.ts`, `.changeset/namespace-segment-boundary.md`.

Files for #6258: `drizzle-kit/src/cli/commands/pull-common.ts`, `drizzle-kit/src/dialects/sqlite/ddl.ts`, `drizzle-kit/src/dialects/cockroach/ddl.ts`, `drizzle-kit/tests/other/relations-to-typescript.test.ts`, `drizzle-kit/tests/postgres/pull.test.ts`, `drizzle-kit/tests/postgres/mocks.ts`, `changelogs/drizzle-kit/1.0.0-rc.5.md`.

Files for #8285: `packages/start-server-core/src/server-functions-handler.ts`, `packages/start-server-core/tests/server-functions-handler-invalid-json.test.ts`, `.changeset/clear-json-payload-400.md`.

Files for #7361: `lib/crewai/src/crewai/task.py`, `lib/crewai/tests/telemetry/test_task_cancellation_span_cleanup.py`.

## Merged pull requests

| Repo | PR | What | Status | Merged |
| --- | --- | --- | --- | --- |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | Honor `lockfile: false` when `devEngines.packageManager.onFail: download`: skip project env-lockfile sync, keep package-manager download/switch, use global persistence when required. Rust v12 + TypeScript v11 + regression/e2e tests + changeset. Closes #14728. 3 commits, +240/−18, 9 files. | **Merged** | 10 Sep 2026 11:29:39 UTC |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` keeps the manifest's existing `^`/`~` operator and supported `npm:` / `jsr:` prefix behavior. Closes #14745. | **Merged** | 10 Sep 2026 10:11:49 UTC |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer kills sibling scripts after the first failure. Closes #14718. | **Merged** | 10 Sep 2026 07:16:07 UTC |
| [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | Move `ModelTest.create_test()` to the calling thread before the concurrent pool so `execution_time` / `time_machine` use cannot race across workers; keep creation inside the engine-adapter cleanup scope. Closes #6039. 3 commits, +24/−23, 1 file. | **Merged** | 10 Sep 2026 00:40:59 UTC |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | `test(open-api): lock in requestBody for /phone-number/verify`. Regression test merged upstream. | **Merged** | 9 Sep 2026 08:19:43 UTC |
| [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Add `useBetterDomTraversing` nursery rule ported from `eslint-plugin-unicorn`. Targeted tests passed. | **Merged** | 8 Sep 2026 16:58:53 UTC |

## Closed (not merged)

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [nodejs/undici](https://github.com/nodejs/undici) | [#5796](https://github.com/nodejs/undici/pull/5796) | Fix `fetch({ redirect: 'follow' })` hanging when a large 3xx redirect body pins the only keep-alive socket in a connection-limited `Agent`. Remember `this.willFollow`, discard followed 3xx body chunks without pausing so the connection drains and returns to the pool. Regression test uses `Agent({ connections: 1 })` and a 128 KiB 301 body; 2 files, +46/−1, 1 commit. | Closed **without merge** on 10 Sep 2026 at 00:48 UTC. No PR comments/review comments were returned; closure reason is not exposed by the available GitHub data. | 10 Sep 2026 |
| [pallets/jinja](https://github.com/pallets/jinja) | [#2268](https://github.com/pallets/jinja/pull/2268) | `indent(..., first=True)` honor `blank=False` on empty first line. Aimed at #2176. | Closed not merged by [@ThiefMaster](https://github.com/ThiefMaster); title marked **Rejected AI junk**. Do not refile #2176 from this account without a clear maintainer-welcome signal. | 10 Sep 2026 |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11174](https://github.com/vitest-dev/vitest/pull/11174) | Browser-mode `define` double-stringify. Parse via `deleteDefineConfig` clone so `FOO: JSON.stringify("BAR")` is `'BAR'` not `'"BAR"'`. Vite `config.define` left intact. Closes #11164. +17/−3, 4 files. | Closed ~28s after open by github-actions. AgentScan `bot` label; account flagged as likely LLM/agent. **Not merged.** Issue #11164 still open. Do not refile from this account. | 8 Sep 2026 |
| [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) | [#12855](https://github.com/typescript-eslint/typescript-eslint/pull/12855) | `no-meaningless-void-operator` skip AssignmentExpression (`void (x = 1)`). Aimed at #12852. | Closed ~28s after open by github-actions. AgentScan automation signal; **not merged.** Do not refile #12852 from this account. | 10 Sep 2026 |
| [Kludex/starlette](https://github.com/Kludex/starlette) | [#3533](https://github.com/Kludex/starlette/pull/3533) | `URL.include_query_params` stringified list/tuple values instead of emitting repeated params. | Closed by author (`devtechedge`): competing open PRs [#3529](https://github.com/Kludex/starlette/pull/3529) and [#3531](https://github.com/Kludex/starlette/pull/3531) already covered it. **Not merged.** | 9 Sep 2026 |

Files for #11174: `packages/vitest/src/node/plugins/testConfig.ts`, `test/e2e/fixtures/config/browser-define/basic.test.ts`, `test/e2e/fixtures/config/browser-define/vitest.config.ts`, `test/e2e/test/config/browser-configs.test.ts`.

## Pipeline / not opened yet

| Repo | Target | Why waiting |
| --- | --- | --- |
| [TanStack/router](https://github.com/TanStack/router) | [#8280](https://github.com/TanStack/router/issues/8280) | Non-OK `application/json` server-fn responses resolve `undefined` on the client. Competing PR #8283 exists; do not compete. |
| [TanStack/router](https://github.com/TanStack/router) | [#8237](https://github.com/TanStack/router/issues/8237) Shape 1 | Missing `x-tsr-serverFn` header returns unhandled 500. Already owned by #8220; #8285 covers Shape 2 only. |
| [WordPress/Requests](https://github.com/WordPress/Requests) | [#1084](https://github.com/WordPress/Requests/issues/1084) | Investigated; protocol-sensitive trim review did not justify a behavior-changing PR, and the upstream connection did not permit posting the verification comment. |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | [#7771](https://github.com/pydantic/pydantic-ai/issues/7771) | Public `BaseDurabilityCapability` export was already fixed upstream; skip duplicate work. |
| [requests-cache](https://github.com/requests-cache/requests-cache) | [#1177](https://github.com/requests-cache/requests-cache/issues/1177) | Explicitly skipped: issue context asked LLMs not to be involved; later PR #1188 was closed as not viable by the maintainer. |
| [webpack/webpack](https://github.com/webpack/webpack) | [#22026](https://github.com/webpack/webpack/issues/22026) | Original ESM/contenthash reproduction is fixed on current main; no `devtechedge` PR was opened. |
| [webpack/webpack](https://github.com/webpack/webpack) | [#22032](https://github.com/webpack/webpack/pull/22032) | Other contributor's open broader `RuntimeModule.updateHash` proposal; not a `devtechedge` contribution. |
| [astral-sh/ruff](https://github.com/astral-sh/ruff) | [#27324](https://github.com/astral-sh/ruff/issues/27324) | Diagnostic-only patch prepared; publication pending a writable Ruff fork/branch. |
| [prettier/prettier](https://github.com/prettier/prettier) | [#19985](https://github.com/prettier/prettier/issues/19985) | Liquid tag alone on a line reflowed into the neighbouring paragraph under `proseWrap: always`. Already fixed upstream by [fisker's #19838](https://github.com/prettier/prettier/pull/19838) (merged 15 Aug 2026) three weeks before the issue was filed; closed 10 Sep 2026 via test-only [#20020](https://github.com/prettier/prettier/pull/20020). Investigation comments only - no `devtechedge` PR. Do not chase. |

## Next contribution scan

10 Sep day goal (**10/10 opens**) is done. Prefer **tier-2 / tier-3** reputable mid-size libraries for the next hunt when mega-repo queues are crowded.

Still waiting (do not code yet):

1. **GO after policy check (comment posted):** [vercel/next.js#98417](https://github.com/vercel/next.js/issues/98417) — keep existing `eslint` when it already satisfies `eslint-config-next` peer; only bump when below range; prefer lowest satisfying major. Waiting on maintainer confirmation. Comment: https://github.com/vercel/next.js/issues/98417#issuecomment-5608267483

See [10 Sep scan](docs/scan-2026-09-10.md) and [9 Sep scan](docs/scan-2026-09-09.md). Research rows do not change contribution counts until a PR is opened.

## Counting policy

A contribution counts as **merged** only when the upstream repository reports the PR as merged. An open PR remains **open** even when its linked issue is closed. Issue comments, investigations, already-fixed issues, duplicate efforts, and other contributors' PRs do not count as `devtechedge` PRs.

## License

MIT License