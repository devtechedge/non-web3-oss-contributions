# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-4-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/non-web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/non-web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Non-Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**14 external items** as of 8 Sep 2026: **4 open PRs**, **0 closed**, **0 merged**, **10 pipeline / skip**.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API. No upstream merges yet.

---

## Features

- Open PRs on other orgs, with one-line fix, diff size, and status
- Closed-not-merged rows (author or maintainer close)
- Pipeline / skip list so the same bug is not raced twice
- Next-up row when a target is free (no competing PR)
- Merged section reserved for **other people's** repos only
- Web3 work is tracked separately and not duplicated here

---

## Open pull requests

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433. `search(["tenant","acme"])` no longer leaks sibling `acme-corp`. Exact-or-descendant match; empty prefix still returns everything on InMemoryStore; `:` rejected in labels. Postgres `= path OR LIKE path:%` plus segment-aware `listNamespaces`. Closes #2721. +337/−62, 8 files. Patch changeset for checkpoint + checkpoint-postgres. | Open; PR title lint + Socket Security green; CI lint/format/build in progress; changeset-bot will bump 10 packages | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions. Junction only if every column is an FK column (pure join table still `through`). SQLite/Cockroach now pass `columns` into `SchemaForPull`. Closes #6253. +212/−6, 7 files. Targets `rc5`. Changelog line in `1.0.0-rc.5.md`. | Open; no labels; no CI checks yet; issue #6253 still open | 8 Sep 2026 |
| [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | Regression test: `/phone-number/verify` OpenAPI `requestBody` stays present after the `.and(z.record())` intersection (closes #8122). Generator already fixed on `main`; this locks the reported endpoint. +58/−0, 1 file (`open-api.test.ts`). No changeset (tests only). | Open; title + `devtools` label ok; CI/E2E/changeset workflows waiting first-time-contributor approval; review requested from Bekacru | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns **400** for malformed JSON on GET `?payload=` and JSON POST bodies (`SyntaxError`), instead of an unhandled 500. Action is not invoked. Patch changeset for `@tanstack/start-server-core`. Unit tests for both shapes. +114/−4, 3 files. Covers Shape 2 of #8237 (Shape 1 is already in #8220). | Open; CodeRabbit clean; first-time-contributor CI waiting on maintainer | 7 Sep 2026 |

Files for #2803: `libs/checkpoint/src/store/base.ts`, `libs/checkpoint/src/store/memory.ts`, `libs/checkpoint/src/tests/namespace.test.ts`, `libs/checkpoint-postgres/src/store/index.ts`, `libs/checkpoint-postgres/src/store/modules/search-operations.ts`, `libs/checkpoint-postgres/src/store/modules/utils.ts`, `libs/checkpoint-postgres/src/store/modules/utils.test.ts`, `.changeset/namespace-segment-boundary.md`.

Files for #6258: `drizzle-kit/src/cli/commands/pull-common.ts`, `drizzle-kit/src/dialects/sqlite/ddl.ts`, `drizzle-kit/src/dialects/cockroach/ddl.ts`, `drizzle-kit/tests/other/relations-to-typescript.test.ts`, `drizzle-kit/tests/postgres/pull.test.ts`, `drizzle-kit/tests/postgres/mocks.ts`, `changelogs/drizzle-kit/1.0.0-rc.5.md`.

Files for #8285: `packages/start-server-core/src/server-functions-handler.ts`, `packages/start-server-core/tests/server-functions-handler-invalid-json.test.ts`, `.changeset/clear-json-payload-400.md`.

## Closed (not merged)

_None yet._

## Pipeline / not opened yet

| Repo | Target | Why waiting |
| --- | --- | --- |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#11164](https://github.com/vitest-dev/vitest/issues/11164) | **Next.** Browser-mode `define` double-stringifies (`JSON.stringify("BAR")` becomes `""BAR""` in Vitest 5). Zero comments, zero PRs, repro exists. Not opened yet. |
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

_None yet._ This section is for merges into **other people's** repos only (not `devtechedge/*`).

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
| Scope | TypeScript framework / library bugs outside Web3 (TanStack Start, Router, Query, Form, Virtual, Vitest, Vite, Zod, better-auth, drizzle-kit, langgraphjs) |
| Process | Search open PRs first. Skip if claimed. Fork + PR when the issue is free. |
| Sibling | [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions) |

---

## License

MIT. See [LICENSE](LICENSE).

---

Last updated: 8 Sep 2026
