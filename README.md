# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-6-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-2-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/non-web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/non-web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Non-Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**16 external items** as of 10 Sep 2026: **6 open PRs**, **1 closed**, **2 merged**, **9 pipeline / skip**.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API.

crewAIInc/crewAI#7361 opened for #7351. Snapshot now **6 open / 2 merged / 1 closed / 9 pipeline**.

- First merge: [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667), [@dyc3](https://github.com/dyc3), 8 Sep 2026
- Latest open: [crewAIInc/crewAI#7361](https://github.com/crewAIInc/crewAI/pull/7361), 10 Sep 2026

---

## Features

- Open PRs on other orgs, with one-line fix, diff size, and status
- Closed-not-merged rows (author or maintainer close)
- Pipeline / skip list so the same bug is not raced twice
- Next-up row when a target is free (no competing PR)
- Merged section for **other people's** repos only
- Web3 work is tracked separately and not duplicated here

---

## Open pull requests

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [#7361](https://github.com/crewAIInc/crewAI/pull/7361) | Async `CancelledError` in `_aexecute_core()` now emits `TaskFailedEvent` before re-raise so `EventListener.execution_spans` is popped and retained Task/Agent/Crew graphs can GC. Closes #7351. +132/−1, 2 files. Regression tests for span cleanup + event emission. Asked maintainers to apply required `llm-generated` label (no self-label permission). | Open; `require-issue` green; CodeRabbit pending; label request posted | 10 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8314](https://github.com/TanStack/router/pull/8314) | Fix retain-then-strip search middleware so Link/`buildLocation` without `search` omits stripped defaults (active matching vs empty URL). Closes #8309. Regression tests + changeset. | Open; just filed | 10 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11235](https://github.com/better-auth/better-auth/pull/11235) | Coalesce `$sessionSignal` bursts so overlapping notifies do not cancel in-flight `/get-session` (leading + one trailing). Closes #11160. Focus/poll paths unchanged. Regression tests in `session-refresh.test.ts`. | Open; just filed | 10 Sep 2026 |
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433. `search(["tenant","acme"])` no longer leaks sibling `acme-corp`. Exact-or-descendant match; empty prefix still returns everything on InMemoryStore; `:` rejected in labels. Postgres `= path OR LIKE path:%` plus segment-aware `listNamespaces`. Closes #2721. +337/−62, 8 files. Patch changeset for checkpoint + checkpoint-postgres. | Open; PR title lint + Socket Security green; CI lint/format/build in progress; changeset-bot will bump 10 packages | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions. Junction only if every column is an FK column (pure join table still `through`). SQLite/Cockroach now pass `columns` into `SchemaForPull`. Closes #6253. +212/−6, 7 files. Targets `rc5`. Changelog line in `1.0.0-rc.5.md`. | Open; no labels; no CI checks yet; issue #6253 still open | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns **400** for malformed JSON on GET `?payload=` and JSON POST bodies (`SyntaxError`), instead of an unhandled 500. Action is not invoked. Patch changeset for `@tanstack/start-server-core`. Unit tests for both shapes. +114/−4, 3 files. Covers Shape 2 of #8237 (Shape 1 is already in #8220). | Open; CodeRabbit clean; first-time-contributor CI waiting on maintainer | 7 Sep 2026 |

Files for #2803: `libs/checkpoint/src/store/base.ts`, `libs/checkpoint/src/store/memory.ts`, `libs/checkpoint/src/tests/namespace.test.ts`, `libs/checkpoint-postgres/src/store/index.ts`, `libs/checkpoint-postgres/src/store/modules/search-operations.ts`, `libs/checkpoint-postgres/src/store/modules/utils.ts`, `libs/checkpoint-postgres/src/store/modules/utils.test.ts`, `.changeset/namespace-segment-boundary.md`.

Files for #6258: `drizzle-kit/src/cli/commands/pull-common.ts`, `drizzle-kit/src/dialects/sqlite/ddl.ts`, `drizzle-kit/src/dialects/cockroach/ddl.ts`, `drizzle-kit/tests/other/relations-to-typescript.test.ts`, `drizzle-kit/tests/postgres/pull.test.ts`, `drizzle-kit/tests/postgres/mocks.ts`, `changelogs/drizzle-kit/1.0.0-rc.5.md`.

Files for #8285: `packages/start-server-core/src/server-functions-handler.ts`, `packages/start-server-core/tests/server-functions-handler-invalid-json.test.ts`, `.changeset/clear-json-payload-400.md`.

Files for #7361: `lib/crewai/src/crewai/task.py`, `lib/crewai/tests/telemetry/test_task_cancellation_span_cleanup.py`.

## Next contribution scan

Deep non-Web3 scan refreshed on 10 Sep 2026. CrewAI #7351 moved Open PR → [#7361](https://github.com/crewAIInc/crewAI/pull/7361). Remaining short queue:

1. **GO after policy check (comment posted):** [vercel/next.js#98417](https://github.com/vercel/next.js/issues/98417) — proposed: keep existing `eslint` when it already satisfies `eslint-config-next` peer; only bump when below range; prefer lowest satisfying major. Waiting on maintainer confirmation before coding. Comment: https://github.com/vercel/next.js/issues/98417#issuecomment-5608267483
2. **GO after design:** [better-auth/better-auth#11160](https://github.com/better-auth/better-auth/issues/11160) — coalesce `$sessionSignal` bursts so `fetchSession` does not cancel in-flight `/get-session` work; confirm coalescing approach with maintainers first.

See the full [10 Sep scan](docs/scan-2026-09-10.md) (and prior [9 Sep scan](docs/scan-2026-09-09.md)). Research rows do not change the contribution counts above until a PR is opened.

## Closed (not merged)

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11174](https://github.com/vitest-dev/vitest/pull/11174) | Browser-mode `define` double-stringify. Parse via `deleteDefineConfig` clone so `FOO: JSON.stringify("BAR")` is `'BAR'` not `'"BAR"'`. Vite `config.define` left intact. Closes #11164. +17/−3, 4 files. | Closed ~28s after open by github-actions. AgentScan `bot` label; account flagged as likely LLM/agent. **Not merged.** Issue #11164 still open. Do not refile from this account. Do not reply to the auto-close comment from an agent. | 8 Sep 2026 |

Files for #11174: `packages/vitest/src/node/plugins/testConfig.ts`, `test/e2e/fixtures/config/browser-define/basic.test.ts`, `test/e2e/fixtures/config/browser-define/vitest.config.ts`, `test/e2e/test/config/browser-configs.test.ts`.

## Pipeline / not opened yet

| Repo | Target | Why waiting |
| --- | --- | --- |
| [TanStack/router](https://github.com/TanStack/router) | [#8280](https://github.com/TanStack/router/issues/8280) | Non-OK `application/json` server-fn responses resolve `undefined` on the client. Exact one-branch fix, but [#8283](https://github.com/TanStack/router/pull/8283) claimed it the same day. Do not compete. |
| [TanStack/router](https://github.com/TanStack/router) | [#8237](https://github.com/TanStack/router/issues/8237) Shape 1 | Missing `x-tsr-serverFn` header returns unhandled 500. Already owned by [#8220](https://github.com/TanStack/router/pull/8220). This ledger's #8285 only covers Shape 2 (malformed JSON). |
| [TanStack/query](https://github.com/TanStack/query) | [#11320](https://github.com/TanStack/query/issues/11320) | Server-side `gcTime` schedules a GC timer that pins the SSR async context. Already owned by [#11321](https://github.com/TanStack/query/pull/11321). Skip. |
| [TanStack/query](https://github.com/TanStack/query) | [#11327](https://github.com/TanStack/query/issues/11327) | Falsy query errors disable `retryOnMount`. Already owned by [#11328](https://github.com/TanStack/query/pull/11328). Skip. |
| [TanStack/query](https://github.com/TanStack/query) | [#11391](https://github.com/TanStack/query/issues/11391) | Broadcast client `added` message overwrites resolved data in other tabs. Already owned by [#11392](https://github.com/TanStack/query/pull/11392). Skip. |
| [TanStack/form](https://github.com/TanStack/form) | [#2337](https://github.com/TanStack/form/issues/2337) | Unguarded `startsWith` for form-group membership. Already owned by [#2338](https://github.com/TanStack/form/pull/2338). Skip. |
| [TanStack/virtual](https://github.com/TanStack/virtual) | [#1251](https://github.com/TanStack/virtual/issues/1251) | `VirtualizerController` never applies updated options after construction. Already owned by [#1253](https://github.com/TanStack/virtual/pull/1253). Skip. |
| [colinhacks/zod](https://github.com/colinhacks/zod) | [#6560](https://github.com/colinhacks/zod/issues/6560) | `toJSONSchema` `io: "input"` drops checks after a non-transforming `.pipe()`. Competing patch already exists. Skip. |
| [vitejs/vite](https://github.com/vitejs/vite) | [#23450](https://github.com/vitejs/vite/issues/23450) | `server.proxy` `fetch()` drops multiple `Set-Cookie` headers. Another contributor already diagnosed it as `http-proxy-3` collapsing via `Object.fromEntries`. Do not race. |

## Merged (upstream)

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | Regression test: `/phone-number/verify` OpenAPI `requestBody` stays present after the `.and(z.record())` intersection (closes #8122). Generator already fixed on `main`; this locks the reported endpoint. +53/−0, 1 file (`packages/better-auth/src/plugins/open-api/open-api.test.ts`). No changeset (tests only). | **Merged** by [@bytaesu](https://github.com/bytaesu) on 9 Sep 2026 ([`874752f`](https://github.com/better-auth/better-auth/commit/874752f4fd2ba3117cf6a360c29b5be5d10d230d)). LGTM, then merge queue into `main`. | 8 Sep 2026 |
| [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Nursery port of [unicorn/better-dom-traversing](https://github.com/sindresorhus/eslint-plugin-unicorn/blob/main/docs/rules/better-dom-traversing.md). Prefer `.firstChild` / `.firstElementChild` / `.closest()` / merged `.querySelector()` over positional DOM walks. `props.children` ignored. Fixes unsafe. Closes #11641. +1972/−0, 17 files, 7 commits. Patch changeset for `@biomejs/biome` (13 packages). | **Merged** by [@dyc3](https://github.com/dyc3) on 8 Sep 2026 ([`e997900`](https://github.com/biomejs/biome/commit/e997900c3eaf9d5efaf1ca12a067a962e1a04d0b)). First-time-contributor CI was waiting maintainer approval; Carson approved the review, then merged to `main`. | 8 Sep 2026 |

Files for #11208: `packages/better-auth/src/plugins/open-api/open-api.test.ts`.

Files for #11667: `.changeset/better-dom-traversing.md`, `crates/biome_js_analyze/src/lint/nursery/use_better_dom_traversing.rs`, `crates/biome_js_analyze/tests/specs/nursery/useBetterDomTraversing/{invalid.js,valid.js,valid.jsx}` + snaps, `crates/biome_rule_options/src/use_better_dom_traversing.rs`, `crates/biome_rule_options/src/lib.rs`, `crates/biome_configuration/src/analyzer/linter/rules.rs`, `crates/biome_configuration/src/generated/linter_options_check.rs`, `crates/biome_diagnostics_categories/src/categories.rs`, `crates/biome_cli/src/execute/migrate/eslint_any_rule_to_biome.rs`, `packages/@biomejs/backend-jsonrpc/src/workspace.ts`, `packages/@biomejs/biome/configuration_schema.json`, plus `AnyJsExpression::is_optional_chain` in the JS syntax crate.

---

## How to read this

| Column | Meaning |
| --- | --- |
| Open | Waiting on a maintainer review or CI |
| Merged | Landed on the upstream default branch |
| Closed (not merged) | Closed by the author or a maintainer; not landed |
| Pipeline | Known target, not opened (next, crowded, skip, or already claimed) |

---

## Stack

| Layer | What |
| --- | --- |
| Surface | This GitHub README |
| Scope | TypeScript / Python / Rust library bugs outside Web3 (TanStack Start, Router, Query, Form, Virtual, Vitest, Vite, Zod, better-auth, drizzle-kit, langgraphjs, Biome, CrewAI) |
| Process | Search open PRs first. Skip if claimed. Fork + PR when the issue is free. |
| Sibling | [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions) |

---

## License

MIT. See [LICENSE](LICENSE).

---

Last updated: 10 Sep 2026