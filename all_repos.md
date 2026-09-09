# Complete Repository Portfolio for @devtechedge

Total Repositories: 50

---

## 1. web3-oss-contributions
- **URL:** https://github.com/devtechedge/web3-oss-contributions
- **Language:** Not specified
- **Topics:** blockchain, ethereum, ethers, rainbowkit, safe, solana, stellar, thirdweb, typescript, wagmi, walletconnect, web3
- **Description:** Public ledger of upstream Web3 pull requests and issue claims. Own-repo work is excluded. Merged: anza-xyz/kit #2032 (getPatternMatchCodec docs) and thirdweb-dev/js #8938 (useTokenQuery). Snapshot 9 Sep 2026: 9 open PRs, 2 merged, 2 closed, 4 Drips claims. TypeScript library bugs, adapters, wallet SDKs. Claim first, then fork + PR.


### README.md

`markdown
# Web3 OSS contributions

Public ledger of **upstream** Web3 pull requests and issue claims by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Non-Web3 work lives in [non-web3-oss-contributions](https://github.com/devtechedge/non-web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-9-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-2-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged+-user%3Adevtechedge)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**17 external items** as of 9 Sep 2026: **9 open PRs**, **2 merged**, **2 closed (not merged)**, **4 issue claims** waiting on maintainer assignment.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API. First upstream merge: [thirdweb-dev/js#8938](https://github.com/thirdweb-dev/js/pull/8938). Latest: [anza-xyz/kit#2032](https://github.com/anza-xyz/kit/pull/2032).

---

## Features

- Open PRs on other orgs, with one-line fix and status
- Closed-not-merged rows (author or maintainer close)
- Issue claims that stay claims until a maintainer assigns
- Pipeline / skip list so the same bug is not raced twice
- Merged section reserved for **other people's** repos only

---

## Open pull requests

| Repo | PR | What | Status | Opened |
| --- | --- | --- | --- | --- |
| [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1426](https://github.com/safe-global/safe-core-sdk/pull/1426) | Keep `TransactionOptions.nonce = 0` in `createTxOptions` / `createLegacyTxOptions` (truthiness was dropping it). Unit tests + patch changeset for `@safe-global/protocol-kit` (fixes #1425). Targets `development`. | Open; CLA signed | 7 Sep 2026 |
| [reown-com/appkit](https://github.com/reown-com/appkit) | [#5767](https://github.com/reown-com/appkit/pull/5767) | `createNamespaces` uses `caipNetworkId` instead of `${chainNamespace}:${id}` so Stellar/Neo3/Solana aliases are not advertised as WC chain ids (fixes #5552). Patch changeset for `@reown/appkit-utils`. | Open | 7 Sep 2026 |
| [wevm/wagmi](https://github.com/wevm/wagmi) | [#5240](https://github.com/wevm/wagmi/pull/5240) | `reconnect()` no longer strands on `reconnecting` when `isAuthorized()` rejects; `.catch` + `finally` guard (fixes #5233). Patch changeset for `@wagmi/core` added. | Open; changeset landed | 6 Sep 2026 |
| [reown-com/appkit](https://github.com/reown-com/appkit) | [#5763](https://github.com/reown-com/appkit/pull/5763) | Accessible names on the modal card (`wui-card`) and header icon buttons via optional `label` on `wui-icon-button`. +114/-5, 6 files. | Open | 4 Sep 2026 |
| [reown-com/appkit](https://github.com/reown-com/appkit) | [#5766](https://github.com/reown-com/appkit/pull/5766) | Meld on-ramp URL gets `countryCode` (plus source currency/amount when known) so the widget does not land on Binance Connect with a fabricated receive amount (fixes #5752). Patch changeset for `@reown/appkit-controllers` added. Vercel preview needs team authorize. | Open; changeset landed | 6 Sep 2026 |
| [rainbow-me/rainbowkit](https://github.com/rainbow-me/rainbowkit) | [#2701](https://github.com/rainbow-me/rainbowkit/pull/2701) | Account modal accessible name: pass `titleId` into `ProfileDetails` so `aria-labelledby` resolves (fixes #2700). +8/-2, 3 files. | Open | 3 Sep 2026 |
| [rainbow-me/rainbowkit](https://github.com/rainbow-me/rainbowkit) | [#2703](https://github.com/rainbow-me/rainbowkit/pull/2703) | Mobile connecting screen shows GET / store link when the wallet app may be missing (fixes #2574). Patch changeset for `@rainbow-me/rainbowkit` added. Vercel preview needs team authorize. | Open; changeset landed | 6 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1715](https://github.com/stellar/js-stellar-sdk/pull/1715) | Coerce RPC timestamps to `number`; `coerceUnixTimestamp` rejects NaN/null/blank; mocks use `hash` (fixes #1644). | Open; Copilot follow-ups pushed | 6 Sep 2026 |
| [ethers-io/ethers.js](https://github.com/ethers-io/ethers.js) | [#5186](https://github.com/ethers-io/ethers.js/pull/5186) | Expose `Signature._yParity` for non-canonical Authorization List values; serialize with raw yParity (fixes #5091). +33/-17, 2 files. | Open | 6 Sep 2026 |

## Closed (not merged)

| Repo | PR | What | Status | Closed |
| --- | --- | --- | --- | --- |
| [wevm/viem](https://github.com/wevm/viem) | [#5065](https://github.com/wevm/viem/pull/5065) | `TestClient.revert` threw `SnapshotRevertError` when `evm_revert` returned `false` (invalid / already-consumed snapshot). Schema, tests, docs, changeset. +57/-5, 8 files. | Closed by author, not merged | 4 Sep 2026 |
| [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3882](https://github.com/solana-foundation/solana-web3.js/pull/3882) | ALT Freeze/Deactivate decoders check instruction discriminators via `decodeData` (fixes #3853). Base was `maintenance/v1.x`. | Closed by maintainer (`amilz`): not accepting PRs in v1.x (maintenance only) | 6 Sep 2026 |

## Issue claims (no PR until assigned)

Claimed on [drips-network/app](https://github.com/drips-network/app). Waiting for a maintainer to say the issue is still open for an external contribution. **No maintainer replies yet** (as of 7 Sep 2026).

| Issue | Claim | What | Status | Claimed |
| --- | --- | --- | --- | --- |
| [#1845](https://github.com/drips-network/app/issues/1845) | [comment](https://github.com/drips-network/app/issues/1845#issuecomment-5529629078) | Create-stream UI: Drip List URL is replaced with an internal account ID, then fails `validatedValue`. | Open, unassigned | 3 Sep 2026 |
| [#1509](https://github.com/drips-network/app/issues/1509) | [comment](https://github.com/drips-network/app/issues/1509#issuecomment-5531962994) | Transaction timeline titles stay imperative; should follow status (Approve → Approving → Approved). | Open, unassigned | 3 Sep 2026 |
| [#1576](https://github.com/drips-network/app/issues/1576) | [comment](https://github.com/drips-network/app/issues/1576#issuecomment-5531986355) | Hide the step index when a flow has only one transaction. | Open, unassigned | 3 Sep 2026 |
| [#1500](https://github.com/drips-network/app/issues/1500) | [comment](https://github.com/drips-network/app/issues/1500#issuecomment-5532011398) | Drip List chips don't pile: `DripListBadge` still mounts the `.name` row when name/owner are hidden. | Open, unassigned | 3 Sep 2026 |

## Pipeline / not opened yet

| Repo | Target | Why waiting |
| --- | --- | --- |
| [ponder-sh/ponder](https://github.com/ponder-sh/ponder) | [#2363](https://github.com/ponder-sh/ponder/issues/2363) (also #2286 / #2264) | Backfill crash needs a confident repro against current `main` before a PR. Still in queue. |
| [wevm/wagmi](https://github.com/wevm/wagmi) | [#4396](https://github.com/wevm/wagmi/issues/4396) | Crowded (multiple open PRs). Shipped #5233 instead as #5240. |
| [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3853](https://github.com/solana-foundation/solana-web3.js/issues/3853) | v1.x PR #3882 closed (maintenance only). Only reopen on a non-v1.x / kit path if maintainers want it. |
| [wevm/viem](https://github.com/wevm/viem) | [#5064](https://github.com/wevm/viem/issues/5064) | Related to closed #5065. Do not reopen without a new angle / maintainer signal. |
| [starknet-io/starknet.js](https://github.com/starknet-io/starknet.js) | [#1341](https://github.com/starknet-io/starknet.js/issues/1341) | Empty-enum extra `0` still on `develop`, but collaborator draft [#1413](https://github.com/starknet-io/starknet.js/pull/1413) already owns the SNIP-12 aggregate. Skip. |

## Merged (upstream)

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| [anza-xyz/kit](https://github.com/anza-xyz/kit) | [#2032](https://github.com/anza-xyz/kit/pull/2032) | Docs: `getPatternMatchCodec` example predicates use `number` again after #1809 (fixes #1810). Docs-only; no changeset on purpose. | 9 Sep 2026 by [`lorisleiva`](https://github.com/lorisleiva) |
| [thirdweb-dev/js](https://github.com/thirdweb-dev/js) | [#8938](https://github.com/thirdweb-dev/js/pull/8938) | `useTokenQuery` `.catch` returns `undefined` only for genuine "not supported" errors and rethrows 401/429/timeout so CheckoutWidget can show ErrorBanner instead of Token Not Supported (fixes #8937). Tests + patch changeset. | 7 Sep 2026 by [`0xFirekeeper`](https://github.com/0xFirekeeper) |

This section is for merges into **other people's** repos only (not `devtechedge/*`).

---

## How to read this

| Column | Meaning |
| --- | --- |
| Open | Waiting on a maintainer review or CI |
| Merged | Landed on the upstream default branch |
| Closed (not merged) | Closed by the author or a maintainer; not landed |
| Claim | Comment on the issue; no PR until assigned |
| Pipeline | Known target, not opened (crowded, skip, or needs repro) |

---

## Stack

| Layer | What |
| --- | --- |
| Surface | This GitHub README |
| Scope | TypeScript / Web3 library bugs, adapters, wallet SDKs |
| Process | Claim first, then fork + PR when the issue is free |

---

## License

MIT. See [LICENSE](LICENSE).

---

Last updated: 9 Sep 2026

``n
---

## 2. non-web3-oss-contributions
- **URL:** https://github.com/devtechedge/non-web3-oss-contributions
- **Language:** Not specified
- **Topics:** better-auth, biome, contributions, drizzle, javascript, langgraph, opensource, oss, pull-requests, rust, tanstack, tanstack-router, tanstack-start, typescript, vite, vitest
- **Description:** Public ledger of upstream non-Web3 PRs by @devtechedge. Own-repo work excluded. Open, closed-not-merged, pipeline/skip, and merges on other people's repos (Biome, Better Auth, LangGraph.js, Drizzle, TanStack). README is the product. Sibling of web3-oss-contributions. Snapshot 9 Sep 2026: 3 open / 2 merged / 1 closed / 9 pipeline.


### README.md

`markdown
# Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-3-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-2-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/non-web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/non-web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Non-Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**15 external items** as of 9 Sep 2026: **3 open PRs**, **1 closed**, **2 merged**, **9 pipeline / skip**.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API.

better-auth#11208 moved Open → Merged. Snapshot now **3 open / 2 merged / 1 closed / 9 pipeline**.

- First merge: [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667), [@dyc3](https://github.com/dyc3), 8 Sep 2026
- Latest: [better-auth/better-auth#11208](https://github.com/better-auth/better-auth/pull/11208), [@bytaesu](https://github.com/bytaesu), 9 Sep 2026

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
| [langchain-ai/langgraphjs](https://github.com/langchain-ai/langgraphjs) | [#2803](https://github.com/langchain-ai/langgraphjs/pull/2803) | JS port of CVE-2026-71433. `search(["tenant","acme"])` no longer leaks sibling `acme-corp`. Exact-or-descendant match; empty prefix still returns everything on InMemoryStore; `:` rejected in labels. Postgres `= path OR LIKE path:%` plus segment-aware `listNamespaces`. Closes #2721. +337/−62, 8 files. Patch changeset for checkpoint + checkpoint-postgres. | Open; PR title lint + Socket Security green; CI lint/format/build in progress; changeset-bot will bump 10 packages | 8 Sep 2026 |
| [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | [#6258](https://github.com/drizzle-team/drizzle-orm/pull/6258) | `drizzle-kit pull` no longer treats two-FK domain tables as M2M junctions. Junction only if every column is an FK column (pure join table still `through`). SQLite/Cockroach now pass `columns` into `SchemaForPull`. Closes #6253. +212/−6, 7 files. Targets `rc5`. Changelog line in `1.0.0-rc.5.md`. | Open; no labels; no CI checks yet; issue #6253 still open | 8 Sep 2026 |
| [TanStack/router](https://github.com/TanStack/router) | [#8285](https://github.com/TanStack/router/pull/8285) | `handleServerAction` returns **400** for malformed JSON on GET `?payload=` and JSON POST bodies (`SyntaxError`), instead of an unhandled 500. Action is not invoked. Patch changeset for `@tanstack/start-server-core`. Unit tests for both shapes. +114/−4, 3 files. Covers Shape 2 of #8237 (Shape 1 is already in #8220). | Open; CodeRabbit clean; first-time-contributor CI waiting on maintainer | 7 Sep 2026 |

Files for #2803: `libs/checkpoint/src/store/base.ts`, `libs/checkpoint/src/store/memory.ts`, `libs/checkpoint/src/tests/namespace.test.ts`, `libs/checkpoint-postgres/src/store/index.ts`, `libs/checkpoint-postgres/src/store/modules/search-operations.ts`, `libs/checkpoint-postgres/src/store/modules/utils.ts`, `libs/checkpoint-postgres/src/store/modules/utils.test.ts`, `.changeset/namespace-segment-boundary.md`.

Files for #6258: `drizzle-kit/src/cli/commands/pull-common.ts`, `drizzle-kit/src/dialects/sqlite/ddl.ts`, `drizzle-kit/src/dialects/cockroach/ddl.ts`, `drizzle-kit/tests/other/relations-to-typescript.test.ts`, `drizzle-kit/tests/postgres/pull.test.ts`, `drizzle-kit/tests/postgres/mocks.ts`, `changelogs/drizzle-kit/1.0.0-rc.5.md`.

Files for #8285: `packages/start-server-core/src/server-functions-handler.ts`, `packages/start-server-core/tests/server-functions-handler-invalid-json.test.ts`, `.changeset/clear-json-payload-400.md`.

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
| Scope | TypeScript / Rust library bugs outside Web3 (TanStack Start, Router, Query, Form, Virtual, Vitest, Vite, Zod, better-auth, drizzle-kit, langgraphjs, Biome) |
| Process | Search open PRs first. Skip if claimed. Fork + PR when the issue is free. |
| Sibling | [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions) |

---

## License

MIT. See [LICENSE](LICENSE).

---

Last updated: 9 Sep 2026

``n
---

## 3. ai-news-agent
- **URL:** https://github.com/devtechedge/ai-news-agent
- **Language:** Python
- **Topics:** ai-agent, cron, feedparser, gemini, github-actions, google-gemini, llm, news-aggregator, python, rss, serverless, telegram-bot
- **Description:** Serverless daily AI news agent. GitHub Actions at 19:30 UTC fetches HN, arXiv cs.AI, Reddit r/MachineLearning, Google AI Blog, OpenAI News, and Hugging Face RSS, dedupes in-repo memory, summarizes with Gemini, and sends one Telegram executive brief. Python 3.11. No public web UI. Fork, add three Actions secrets, and the next run is yours.


### README.md

`markdown
# <img src="docs/favicon.svg" width="36" height="36" alt="" /> AI News Agent

Serverless daily AI digest — GitHub Actions pulls public RSS, Gemini writes the brief, Telegram delivers it.

[![Live run](https://img.shields.io/badge/Live%20run-GitHub%20Actions-black?logo=githubactions&logoColor=white)](https://github.com/devtechedge/ai-news-agent/actions/workflows/daily_news.yml)
[![Daily agent](https://github.com/devtechedge/ai-news-agent/actions/workflows/daily_news.yml/badge.svg)](https://github.com/devtechedge/ai-news-agent/actions/workflows/daily_news.yml)
[![CI](https://github.com/devtechedge/ai-news-agent/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/ai-news-agent/actions/workflows/ci.yml)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Live Demo

**[Daily workflow on GitHub Actions](https://github.com/devtechedge/ai-news-agent/actions/workflows/daily_news.yml)** — scheduled 19:30 UTC, plus manual `workflow_dispatch`.

> **Status:** This is a real scheduled backend, not a client-side mock. There is **no public web UI**. Gemini reads public RSS and writes one short daily brief of the important developments, sent to a **private Telegram chat**. Fork the repo, add three Actions secrets, and the next run is yours. `memory.json` in this public copy stores article hashes only.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.jpg" alt="AI News Agent" width="800">
</p>

| Pipeline | Telegram brief (sample layout) |
|----------|--------------------------------|
| ![Pipeline](docs/screenshots/01-pipeline.png) | ![Telegram brief](docs/screenshots/02-telegram-brief.png) |

| Schedule + memory |
|-------------------|
| ![Schedule](docs/screenshots/03-schedule-memory.png) |

---

## Features

- **Zero laptop, zero bill** — GitHub Actions + Gemini free tier + Telegram Bot API
- **Six public feeds** — HN (AI query), arXiv cs.AI, Reddit r/MachineLearning, Google AI Blog, OpenAI News, Hugging Face Blog
- **In-repo memory** — MD5 of `title|link|source` in `memory.json` so reruns skip duplicates
- **Important-only brief** — Gemini keeps models, launches, landmark research, policy, and big deals; skips recaps and noise
- **One Telegram message** — hard-capped under the Bot API length limit, never split into a thread
- **Rate-limit safe** — one Gemini call per run, 10 RPM cap, exponential backoff on 429, 50-article candidate ceiling
- **Fail-closed** — a Gemini or Telegram miss does **not** commit empty memory and does **not** report success

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Python 3.11 on GitHub Actions |
| Feeds | `feedparser` + `requests` |
| Summarizer | `google-genai` · `gemini-3.6-flash` · thinking level `high` |
| Delivery | Telegram Bot API (plain text) |
| Memory | `memory.json` committed back to `main` |
| CI | GitHub Actions (`compileall` + pytest) |
| License | MIT |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/ai-news-agent.git
cd ai-news-agent
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
python -m pytest
```

### Run locally (optional)

```bash
export GEMINI_API_KEY=...
export TELEGRAM_BOT_TOKEN=...
export TELEGRAM_CHAT_ID=...
python agent.py
# Telegram-only smoke:
TEST_TELEGRAM_ONLY=true python agent.py
```

### Wire the daily job

1. Create a Telegram bot via [@BotFather](https://t.me/BotFather) and note the token + chat id.
2. Create a Gemini key in [Google AI Studio](https://aistudio.google.com/app/apikey).
3. Repo **Settings → Secrets and variables → Actions** — add `GEMINI_API_KEY`, `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.
4. **Actions → Daily AI News Agent → Run workflow**. Cron is `30 19 * * *` (19:30 UTC).

Schedule, feeds, and RPM caps live in `.github/workflows/daily_news.yml` and `agent.py`.

---

## How it works

```
RSS feeds ──► filter / dedupe ──► Gemini (one brief) ──► one Telegram message
                    │                                        │
                    └──────── memory.json ◄──── commit ──────┘
```

Memory is written only after a non-empty summary **and** a successful Telegram send. CI never calls Gemini.

Threat model: [`SECURITY.md`](SECURITY.md).

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 4. job-board
- **URL:** https://github.com/devtechedge/job-board
- **Language:** TypeScript
- **Topics:** ashby, ats, greenhouse, job-board, job-search, lever, postgres, public-api, react, tanstack, typescript, vercel
- **Description:** Jobrow indexes still-open US tech roles from public Greenhouse, Ashby, and Lever board APIs. 50 companies, 5,000+ open roles. Table-first search, same-day close when a board drops a posting. TanStack Start, TypeScript, Neon Postgres. Independent index — not an employer or agency.


### README.md

`markdown
# Jobrow

Public register of **still-open US tech roles**, read from employer ATS JSON — not from another job site.

Tagline: **Still open.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://jobrow.vercel.app)
[![Boards](https://img.shields.io/badge/Boards-50-1F6B4A)](https://jobrow.vercel.app/companies)
[![TanStack Start](https://img.shields.io/badge/TanStack%20Start-black)](https://tanstack.com/start)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live demo

**https://jobrow.vercel.app**

Production is **Neon Postgres** on Vercel Hobby. The board currently holds **5,000+ open US tech roles across 50 companies**. Apply always leaves Jobrow for the employer ATS. Public listings — not an employer, recruiter, or agency.

`GET /api/health` reports `{ db, openJobs, pendingBoards, staleBoards, lastOkAt }`.

### Public JSON API

Unauthenticated read API for the same US-tech slice Jobs shows (`status=open`, `us_eligible`, `tech_eligible`). Native apps and other clients can call these without going through server functions:

- `GET /api/jobs` — `JobQuery` as querystring (`q`, `fn`, `seniority`, `workplace`, `location`, `salaryMin`, `posted`, `ats`, `company`, `sort`, `page`). Page size 40.
- `GET /api/jobs/:id` — one role, with sanitized `description_html` plus `description_text`
- `GET /api/companies` — boards
- `GET /api/companies/:slug` — board plus open roles
- `GET /api/home` — register KPIs (open count, boards, first-seen 24h, last crawl, functions, boards) plus a latest page
- `GET /api/closed` — roles closed after a successful crawl

`/api/health`, `/api/desk`, cron, and admin are unchanged. Product auth stays off. Apply URLs are employer ATS https links. Discovery helpers: [`/sitemap.xml`](https://jobrow.vercel.app/sitemap.xml), [`/llms.txt`](https://jobrow.vercel.app/llms.txt).

### Native app

An Expo (Android + iOS) client lives in [`mobile/`](mobile/). It is a separate package so the Vercel web build does not compile it. See [mobile/README.md](mobile/README.md) to run it in the iOS simulator or Android emulator.

---

## Sister product

**[Lattice](https://lattice-devtechedge1.vercel.app)** — free board for **blockchain, crypto, and Web3 jobs** from live employer ATS boards (Coinbase, Binance, Ripple, and more). Jobrow stays US tech; Lattice covers Web3 careers. Source: [devtechedge/lattice](https://github.com/devtechedge/lattice).

---

## Screenshots

| Jobs | Search |
|----------|--------|
| ![Jobs](docs/screenshots/01-register.png) | ![Search](docs/screenshots/05-index.png) |

| Role | Companies |
|------|-----------|
| ![Job detail](docs/screenshots/03-job-detail.png) | ![Companies](docs/screenshots/04-companies.png) |

| About | Pricing |
|-------|--------|
| ![About](docs/screenshots/02-about.png) | ![Pricing](docs/screenshots/06-rates.png) |

Share card: [docs/screenshots/social-preview.png](docs/screenshots/social-preview.png)

---

## What you can do

- **Jobs** (`/`) — Latest (8 roles, one company per row), filters, KPIs, Companies strip (8)
- **Closed** (`/closed`) — roles removed after a successful crawl (filled or pulled)
- Company marks next to every listing (site icon, initials if the icon fails)
- **Search** (`/jobs`) — full paginated table of the US tech slice
- **Companies** (`/companies`) — 50 boards, US-tech count vs listed count, last successful fetch
- **Saved** — browser watchlist count in the header (nav: Jobs · Search · Companies · About · Saved · Closed)
- **Role** (`/jobs/:id`) — summary, pay, workplace, posting HTML, Apply (leaves the site)
- **Contact** (`/contact`) — corrections and legal notes (not applications)
- **Add a board** (`/employers`) — public Greenhouse / Ashby / Lever / Workable token
- **Pricing** (`/pricing`) — Bound pass waitlist (`$11` / 28 days). No live checkout
- **Promote** (`/placements`) — Ruled pin `$120` / masthead line `$55`. Waitlist only
- **Watchlist** — local to the browser (`localStorage` key `jobrow:watchlist`, max 200). No account. No resume upload
- **JSON API** (`/api/jobs`, `/api/companies`, `/api/home`) — public register contract for native apps
- **iOS / Android** — Expo app in `mobile/`. Apply opens the employer ATS. Saved jobs use local AsyncStorage.
- **Admin** (`/admin`) — password-gated crawl and board edits

A role **drops when a successful crawl no longer sees it**. A failed fetch does not close that board.

---

## Registry (50)

Seeded from [data/companies.csv](data/companies.csv) and [src/lib/seed-companies.ts](src/lib/seed-companies.ts). Tokens were confirmed against live public board JSON.

| ATS | Companies |
|-----|-----------|
| Greenhouse (36) | Stripe, Anthropic, Airbnb, Coinbase, Discord, Figma, Cloudflare, Databricks, Vercel, Dropbox, Robinhood, Block, Lyft, Pinterest, Reddit, Twilio, Datadog, MongoDB, Instacart, Roblox, GitLab, Grafana Labs, Asana, Okta, Alpaca, Affirm, Brex, Scale AI, Anduril, HubSpot, DoorDash, Elastic, Glean, Chime, Flexport, Samsara |
| Ashby (11) | OpenAI, Ramp, Linear, Notion, Cursor, Perplexity, Supabase, Plaid, Snowflake, Confluent, Sentry |
| Lever (3) | Palantir, Wealthfront, Spotify |

US-eligible **tech** titles stay on Jobs. Sales, finance, and non-US postings on the same board are ignored. The companies table shows both **US tech** and **listed** (raw JSON rows on the last good fetch).

### Add another company

1. Confirm the public board JSON exists:
   - Greenhouse: `https://boards-api.greenhouse.io/v1/boards/{token}/jobs`
   - Ashby: `https://api.ashbyhq.com/posting-api/job-board/{token}?includeCompensation=true`
   - Lever: `https://api.lever.co/v0/postings/{token}?mode=json`
2. `/admin` → unlock with `ADMIN_PASSWORD` → name / slug / ATS / board token / careers URL → crawl that row.
3. Or append a line to `data/companies.csv` and a matching object in `SEED_COMPANIES`.

Do not scrape career marketing HTML when the board JSON exists. Do not scrape other job aggregators.

---

## Stack

| Layer | Technology |
|-------|------------|
| App | TanStack Start, React 19, TypeScript, Tailwind v4 |
| Data | Neon Postgres in production; embedded PGLite when `DATABASE_URL` is omitted (local) |
| Sources | Greenhouse, Ashby, Lever public JSON (Workable adapter ready) |
| Host | Vercel Hobby |
| Crawl | GitHub Action, 4× daily (8 shards, retry on a flaky board), `POST /api/cron/crawl` with `Authorization: Bearer` |
| Security | CSP and related headers in [vercel.json](vercel.json); see [SECURITY.md](SECURITY.md) |

---

## Quick start

```bash
npm install
npm run dev
```

Without `DATABASE_URL` the app uses embedded PGLite and seeds the 50 boards on first load.

```bash
npm test
npm run typecheck
```

Env template: [.env.example](.env.example). Never commit secrets.

| Variable | Where | Purpose |
|----------|--------|---------|
| `DATABASE_URL` | Vercel | Neon pooled URI (`sslmode=require`) |
| `ADMIN_PASSWORD` | Vercel | `/admin` |
| `CRON_SECRET` | Vercel + GitHub Actions | Cron bearer token |
| `APP_URL` | GitHub Actions | Origin the Action calls |
| `VITE_SITE_URL` | Vercel | Sitemap / JSON-LD origin |

Production already has Neon attached. Local demos can omit `DATABASE_URL`.

---

## Security

See [SECURITY.md](SECURITY.md). Report vulnerabilities with GitHub private advisory, not a public issue.

Hardening in this tree: parameterized SQL, escaped job HTML, script-safe JSON-LD, fail-closed admin/cron secrets in production, IP-limited admin unlock, public API rate limits, ATS host allowlist, no `?secret=` on cron, desk size cap, HTTPS-only Apply links, HSTS + CSP headers. Details: [SECURITY.md](SECURITY.md).

---

## Discovery (SEO)

| Item | Status |
|------|--------|
| Crawlable pages + `robots.txt` + sitemap (`lastmod`) | Live |
| `/llms.txt`, OG/canonical, long-tail titles | Live |
| Google Search Console + Bing Webmaster | Verified / imported |
| Crawl freshness | GitHub Action **4× daily**, 8 shards; retry + warn on one flaky board |
| Earn links (X / Indie Hackers / Discord) | Operator posts; HN gated for new accounts |
| Patience | New hosts often need weeks–months for competitive queries |

## Remaining

| Item | Status |
|------|--------|
| Custom domain / final brand | Working name is Jobrow. Buy later. |
| Neon | Live. |
| GitHub Action `APP_URL` + `CRON_SECRET` | Set on the repo. |
| Counsel | Terms / privacy / sourcing are drafts. |
| Bound pass / ruled pins | Rate card exists. Checkout is not live. |
| Private GitHub repo | Optional. Does not replace Vercel secrets — see [SECURITY.md](SECURITY.md). |

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 5. vitest
- **URL:** https://github.com/devtechedge/vitest
- **Language:** Not specified
- **Topics:** None
- **Description:** Next generation testing framework powered by Vite.


### README.md

`markdown
<p align="center">
  <br>
  <br>
  <a href="https://vitest.dev" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://vitest.dev/vitest-light.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://vitest.dev/vitest-dark.svg">
      <img alt="Vitest logo" src="https://vitest.dev/vitest-dark.svg" height="60">
    </picture>
  </a>
  <br>
  <br>
  <br>
</p>

<h1 align="center">
Vitest
</h1>
<p align="center">
Next generation testing framework powered by Vite.
<p>
<p align="center">
  <a href="https://npmx.dev/package/vitest"><img src="https://img.shields.io/npm/v/vitest?color=729B1B&label=" alt="current vitest version badge"></a>
<p>

<p align="center">
<a href="https://chat.vitest.dev"><b>Get involved!</b></a>
</p>
<p align="center">
 <a href="https://vitest.dev">Documentation</a> | <a href="https://vitest.dev/guide/">Getting Started</a> | <a href="https://vitest.dev/guide/#examples">Examples</a> | <a href="https://vitest.dev/guide/why">Why Vitest?</a>
</p>
<p align="center">
<a href="https://cn.vitest.dev">中文文档</a>
</p>

<h4 align="center">

</h4>
<br>
<br>

## Features

- [Vite](https://vitejs.dev/)'s config, transformers, resolvers, and plugins. Use the same setup from your app!
- [Jest Snapshot](https://jestjs.io/docs/snapshot-testing)
- [Chai](https://www.chaijs.com/) built-in for assertions, with [Jest expect](https://jestjs.io/docs/expect) compatible APIs
- [Smart & instant watch mode](https://vitest.dev/guide/features.html#watch-mode), like HMR for tests!
- [Native code coverage](https://vitest.dev/guide/features.html#coverage) via [`v8`](https://v8.dev/blog/javascript-code-coverage) or [`istanbul`](https://istanbul.js.org/).
- Jest-compatible mocking, stubbing, and spies.
- [JSDOM](https://github.com/jsdom/jsdom) and [happy-dom](https://github.com/capricorn86/happy-dom) for DOM and browser API mocking
- [Browser Mode](https://vitest.dev/guide/browser/) for running component tests in the browser
- Components testing ([Vue](https://github.com/vitest-tests/browser-examples/tree/main/examples/vue), [React](https://github.com/vitest-tests/browser-examples/tree/main/examples/react), [Svelte](https://github.com/vitest-tests/browser-examples/tree/main/examples/svelte), [Lit](./examples/lit), [Marko](https://github.com/marko-js/examples/tree/master/examples/library-ts))
- Benchmarking support with [Tinybench](https://github.com/tinylibs/tinybench)
- [Projects](https://vitest.dev/guide/projects) support
- [expect-type](https://github.com/mmkal/expect-type) for type-level testing
- ESM first, top level await
- Out-of-box TypeScript / JSX support
- Filtering, timeouts, concurrent for suite and tests
- Sharding support
- Reporting Uncaught Errors
- Run your tests in the browser natively

> Vitest requires Vite >=v6.4.0 and Node >=v22.12.0

```ts
import { assert, describe, expect, it } from 'vitest'

describe('suite name', () => {
  it('foo', () => {
    expect(1 + 1).toEqual(2)
    expect(true).to.be.true
  })

  it('bar', () => {
    assert.equal(Math.sqrt(4), 2)
  })

  it('snapshot', () => {
    expect({ foo: 'bar' }).toMatchSnapshot()
  })
})
```

```bash
$ npx vitest
```

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/sheremet-va/static/vitest/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/sheremet-va/static/vitest/sponsors.svg' alt="vitest's sponsors"/>
  </a>
</p>

## Credits

Thanks to:

- [The Jest team and community](https://jestjs.io/) for creating a delightful testing API
- [@lukeed](https://github.com/lukeed) for the work on [uvu](https://github.com/lukeed/uvu) where we are inspired a lot from.
- [@pi0](https://github.com/pi0) for the idea and implementation of using Vite to transform and bundle the server code.
- [The Vite team](https://github.com/vitejs/vite) for brainstorming the initial idea.
- [@patak-dev](https://github.com/patak-dev) for the awesome package name!

## Contribution

See [Contributing Guide](https://github.com/vitest-dev/vitest/blob/main/CONTRIBUTING.md).

## License

[MIT](./LICENSE) License © 2021-Present VoidZero Inc. and Vitest contributors

``n
---

## 6. biome
- **URL:** https://github.com/devtechedge/biome
- **Language:** Not specified
- **Topics:** None
- **Description:** A toolchain for web projects, aimed to provide functionalities to maintain them. Biome offers formatter and linter, usable via CLI and LSP.


### README.md

`markdown
./packages/@biomejs/biome/README.md
``n
---

## 7. langgraphjs
- **URL:** https://github.com/devtechedge/langgraphjs
- **Language:** Not specified
- **Topics:** None
- **Description:** Framework to build resilient language agents as graphs.


### README.md

`markdown
libs/langgraph-core/README.md
``n
---

## 8. drizzle-orm
- **URL:** https://github.com/devtechedge/drizzle-orm
- **Language:** Not specified
- **Topics:** None
- **Description:** ORM


### README.md

`markdown
<div align="center">
  <img src="./misc/readme/logo-github-sq-dark.svg#gh-dark-mode-only" />
  <img src="./misc/readme/logo-github-sq-light.svg#gh-light-mode-only" />
</div>

<br/>
<div align="center">
  <h3>Headless ORM for NodeJS, TypeScript and JavaScript 🚀</h3>
  <a href="https://orm.drizzle.team">Website</a> •
  <a href="https://orm.drizzle.team/docs/overview">Documentation</a> •
  <a href="https://x.com/drizzleorm">Twitter</a> •
  <a href="https://driz.link/discord">Discord</a>
</div>

<br/>
<br/>

### What's Drizzle?
Drizzle is a modern TypeScript ORM developers [wanna use in their next project](https://stateofdb.com/tools/drizzle). 
It is [lightweight](https://bundlephobia.com/package/drizzle-orm) at only ~7.4kb minified+gzipped, and it's tree shakeable with exactly 0 dependencies. 

**Drizzle supports every PostgreSQL, MySQL and SQLite database**, including serverless ones like [Turso](https://orm.drizzle.team/docs/get-started-sqlite#turso), [Neon](https://orm.drizzle.team/docs/get-started-postgresql#neon), [Xata](https://orm.drizzle.team/docs/connect-xata), [PlanetScale](https://orm.drizzle.team/docs/get-started-mysql#planetscale), [Cloudflare D1](https://orm.drizzle.team/docs/get-started-sqlite#cloudflare-d1), [FlyIO LiteFS](https://fly.io/docs/litefs/), [Vercel Postgres](https://orm.drizzle.team/docs/get-started-postgresql#vercel-postgres), [Supabase](https://orm.drizzle.team/docs/get-started-postgresql#supabase) and [AWS Data API](https://orm.drizzle.team/docs/get-started-postgresql#aws-data-api). No bells and whistles, no Rust binaries, no serverless adapters, everything just works out of the box.

**Drizzle is serverless-ready by design**. It works in every major JavaScript runtime like NodeJS, Bun, Deno, Cloudflare Workers, Supabase functions, any Edge runtime, and even in browsers.  
With Drizzle you can be [**fast out of the box**](https://orm.drizzle.team/benchmarks) and save time and costs while never introducing any data proxies into your infrastructure. 

While you can use Drizzle as a JavaScript library, it shines with TypeScript. It lets you [**declare SQL schemas**](https://orm.drizzle.team/docs/sql-schema-declaration) and build both [**relational**](https://orm.drizzle.team/docs/rqb) and [**SQL-like queries**](https://orm.drizzle.team/docs/select), while keeping the balance between type-safety and extensibility for toolmakers to build on top.  

### Ecosystem
While Drizzle ORM remains a thin typed layer on top of SQL, we made a set of tools for people to have best possible developer experience.  
  
Drizzle comes with a powerful [**Drizzle Kit**](https://orm.drizzle.team/kit-docs/overview) CLI companion for you to have hassle-free migrations. It can generate SQL migration files for you or apply schema changes directly to the database.  
  
We also have [**Drizzle Studio**](https://orm.drizzle.team/drizzle-studio/overview) for you to effortlessly browse and manipulate data in your database of choice.

### Documentation
Check out the full documentation on [the website](https://orm.drizzle.team/docs/overview).

### Our sponsors ❤️
<p align="center">
<a href="https://drizzle.team" target="_blank">
<img src='https://api.drizzle.team/v2/sponsors/svg'/>
</a>
</p>

``n
---

## 9. better-auth
- **URL:** https://github.com/devtechedge/better-auth
- **Language:** Not specified
- **Topics:** None
- **Description:** The most comprehensive authentication framework


### README.md

`markdown
<div align="center">
  <picture>
    <source srcset="./banner-dark.png" media="(prefers-color-scheme: dark)"/>
    <source srcset="./banner-light.png" media="(prefers-color-scheme: light)"/>
    <img src="./banner-light.png" alt="Better Auth Logo"/>
  </picture>

  [![npm](https://img.shields.io/npm/dm/better-auth?style=flat&colorA=000000&colorB=000000)](https://npm.chart.dev/better-auth?primary=neutral&gray=neutral&theme=dark)
  [![npm version](https://img.shields.io/npm/v/better-auth.svg?style=flat&colorA=000000&colorB=000000)](https://www.npmjs.com/package/better-auth)
  [![GitHub stars](https://img.shields.io/github/stars/better-auth/better-auth?style=flat&colorA=000000&colorB=000000)](https://github.com/better-auth/better-auth/stargazers)

  <p>
    <a href="https://discord.gg/better-auth">Discord</a>
    ·
    <a href="https://better-auth.com">Website</a>
    ·
    <a href="https://github.com/better-auth/better-auth/issues">Issues</a>
  </p>
</div>

## Better Auth

Better Auth is a framework-agnostic authentication (and authorization) framework for TypeScript. It provides a comprehensive set of features out of the box and includes a plugin ecosystem that simplifies adding advanced functionalities with minimal code in a short amount of time. Whether you need 2FA, multi-tenant support, or other complex features, it lets you focus on building your actual application instead of reinventing the wheel.

### Why Better Auth

Authentication in the TypeScript ecosystem is a half-solved problem. Other open-source libraries often require a lot of additional code for anything beyond basic authentication. Rather than just pushing third-party services as the solution, I believe we can do better as a community—hence, Better Auth.

## Contribution

Better Auth is a free and open source project licensed under the [MIT License](./LICENSE.md). You are free to do whatever you want with it.

You could help continuing its development by:

- [Contribute to the source code](./CONTRIBUTING.md)
- [Suggest new features and report issues](https://github.com/better-auth/better-auth/issues)

## Security
If you discover a security vulnerability within Better Auth, please report it via [GitHub Security Advisories](https://github.com/better-auth/better-auth/security/advisories/new).

All reports will be promptly addressed, and you'll be credited accordingly.

``n
---

## 10. safe-core-sdk
- **URL:** https://github.com/devtechedge/safe-core-sdk
- **Language:** Not specified
- **Topics:** None
- **Description:** The Safe{Core} SDK allows builders to add account abstraction functionality into their apps.


### README.md

`markdown
![license](https://img.shields.io/github/license/safe-global/safe-core-sdk) [![Coverage Status](https://coveralls.io/repos/github/safe-global/safe-core-sdk/badge.svg?branch=main)](https://coveralls.io/github/safe-global/safe-core-sdk?branch=main)

![Safe_Logos_Core_SDK_Black](https://github.com/safe-global/safe-core-sdk/assets/6764315/7202a24a-2981-4b31-9cf5-ace1c3b2c4fa)

## Table of contents

- [About](#about)
- [Documentation](#documentation)
- [Packages](#packages)
- [Guides](#guides)
- [Need Help or Have Questions?](#need-help-or-have-questions)
- [Contributing](#contributing)
- [Playground](#playground)
- [License](#license)

## About

This is a mono-repository containing Javascript/Typescript software developer tools that facilitate the interaction with [Safe Smart Accounts](https://github.com/safe-global/safe-smart-account), [Safe Transaction Service API](https://github.com/safe-global/safe-transaction-service), and enabling uses like ERC-4337 compatibility.

## Documentation

If you want to develop using Safe Smart Accounts in a Javascript/Typescript app, we recommend that you visit [our documentation site](https://docs.safe.global/sdk/overview).

## Packages

| Package | Release | Description |
| ------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [protocol-kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/protocol-kit)                 | [![npm Version](https://badge.fury.io/js/%40safe-global%2Fprotocol-kit.svg)](https://badge.fury.io/js/%40safe-global%2Fprotocol-kit)       | TypeScript library that facilitates the interaction with [Safe Smart Accounts](https://github.com/safe-global/safe-smart-account). Can be used to create new Safe accounts, update the configuration of existing Safes, create and execute transactions, among other features.                                              |
| [api-kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/api-kit)                           | [![npm Version](https://badge.fury.io/js/%40safe-global%2Fapi-kit.svg)](https://badge.fury.io/js/%40safe-global%2Fapi-kit)                 | [Safe Transaction Service API](https://github.com/safe-global/safe-transaction-service) typescript library. Allows to propose and share transactions with the other signers of a Safe, sending the signatures to the service to collect them, and getting information about a Safe, among other features.                                                                       |
| [relay-kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/relay-kit)                       | ​​​[​![npm Version](https://badge.fury.io/js/%40safe-global%2Frelay-kit.svg)​](https://badge.fury.io/js/%40safe-global%2Frelay-kit)​             | Typescript library that enables ERC-4337 with Safe and allows users to pay for the transaction fees from their Safe account balance using the blockchain native token or ERC-20 tokens, or to get their transactions sponsored.                                                                            |
| [types-kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/types-kit)   | [![npm Version](https://badge.fury.io/js/%40safe-global%2Ftypes-kit.svg)](https://badge.fury.io/js/%40safe-global%2Ftypes-kit)  | Common types used in the [Safe Core SDK](https://github.com/safe-global/safe-core-sdk/tree/main/packages) packages.                                                  |

## Guides

| Title | Description |
| ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Integrating the Safe{Core} SDK](https://github.com/safe-global/safe-core-sdk/blob/main/guides/integrating-the-safe-core-sdk.md) | This guide shows how to use the [Protocol Kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/protocol-kit) and [API Kit](https://github.com/safe-global/safe-core-sdk/tree/main/packages/api-kit). |

## Need Help or Have Questions?

If you have any doubts, questions, or need assistance, feel free to reach out! [Here you will find how to get support.](https://github.com/safe-global/safe-core-sdk/tree/main/SUPPORT.md)

## Contributing

If you are interested in contributing, please read the [Contributing Guidelines](https://github.com/safe-global/safe-core-sdk/tree/main/CONTRIBUTING.md) **before opening an issue or submitting a pull request**.

## Playground

This project includes a [playground](https://github.com/safe-global/safe-core-sdk/tree/main/playground/README.md) with a few scripts that can be used as a starting point to use the Safe{Core} SDK. These scripts contain valuable snippets that demonstrate various Safe features. They serve as a useful learning tool or starting point for implementing these features in your application.

## License

This library is released under [MIT](https://github.com/safe-global/safe-core-sdk/tree/main/LICENSE.md).

``n
---

## 11. router
- **URL:** https://github.com/devtechedge/router
- **Language:** Not specified
- **Topics:** None
- **Description:** 🤖 A client-first, server-capable, fully type-safe router and full-stack framework for the web (React and more).


### README.md

`markdown
<img src="https://static.scarf.sh/a.png?x-pxid=d988eb79-b0fc-4a2b-8514-6a1ab932d188" />

<table>
<tr>
<td>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://tanstack.com/api/readme/router.png?theme=dark"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://tanstack.com/api/readme/router.png"
  />
  <img
    src="https://tanstack.com/api/readme/router.png"
    alt="TanStack Router"
  />
</picture>

## TanStack Router

A modern router designed for type safety, data‑driven navigation, and seamless developer experience.

- End‑to-end type safety (routes, params, loaders)
- Schema‑driven search params with validation
- Built‑in caching, prefetching & invalidation
- Nested layouts, transitions & error boundaries

### [Read the Router Docs →](https://tanstack.com/router)

</td>
<td>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://tanstack.com/api/readme/start.png?theme=dark"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://tanstack.com/api/readme/start.png"
  />
  <img
    src="https://tanstack.com/api/readme/start.png"
    alt="TanStack Start"
  />
</picture>

## TanStack Start

A full‑stack framework built on Router, designed for server rendering, streaming, and production‑ready deployments.

- Full‑document SSR & streaming
- Server functions & end‑to‑end type safety
- Deployment‑ready bundling & builds
- All the power of TanStack Router, plus full‑stack features

### [Read the Start Docs →](https://tanstack.com/start)

</td>
</tr>
</table>

<br />

<p align="center">
  <a href="https://npmjs.com/package/@tanstack/react-router"><img src="https://img.shields.io/npm/dm/@tanstack/react-router.svg" alt="npm downloads" /></a> <a href="https://github.com/tanstack/router"><img src="https://img.shields.io/github/stars/tanstack/router.svg?style=social&label=Star" alt="GitHub stars" /></a> <a href="https://bundlephobia.com/result?p=@tanstack/react-router"><img src="https://badgen.net/bundlephobia/minzip/@tanstack/react-router" alt="Bundle size" /></a>
</p>
<p align="center">
  <a href="#badge"><img alt="semantic-release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg"></a> <a href="https://bestofjs.org/projects/tanstack-router"><img alt="Best of JS" src="https://img.shields.io/endpoint?url=https://bestofjs-serverless.now.sh/api/project-badge?fullName=TanStack%2Frouter%26since=daily" /></a> <a href="https://twitter.com/tan_stack"><img src="https://img.shields.io/twitter/follow/tan_stack.svg?style=social" alt="Follow @TanStack"/></a>
</p>

<div align="center">

### [Become a Sponsor!](https://github.com/sponsors/tannerlinsley/)

</div>

## Get Involved

- We welcome issues and pull requests!
- Participate in [GitHub discussions](https://github.com/TanStack/router/discussions)
- Chat with the community on [Discord](https://discord.com/invite/WrRKjPJ)
- See [CONTRIBUTING.md](./CONTRIBUTING.md) for setup instructions

## Partners

<table align="center">
  <tr>
        <td>
      <a href="https://www.coderabbit.ai/?via=tanstack&dub_id=aCcEEdAOqqutX6OS" >
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://tanstack.com/assets/coderabbit-dark-D643Zkrv.svg" />
          <source media="(prefers-color-scheme: light)" srcset="https://tanstack.com/assets/coderabbit-light-CIzGLYU_.svg" />
          <img src="https://tanstack.com/assets/coderabbit-light-CIzGLYU_.svg" height="40" alt="CodeRabbit" />
        </picture>
      </a>
    </td>
    <td>
      <a href="https://www.cloudflare.com?utm_source=tanstack">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://tanstack.com/assets/cloudflare-white-Co-Tyjbl.svg" />
          <source media="(prefers-color-scheme: light)" srcset="https://tanstack.com/assets/cloudflare-black-6Ojsn8yh.svg" />
          <img src="https://tanstack.com/assets/cloudflare-white-Co-Tyjbl.svg" height="60" alt="Cloudflare" />
        </picture>
      </a>
    </td>
    <td>
      <a href="https://netlify.com?utm_source=tanstack">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tanstack/tanstack.com/main/src/images/netlify-dark.svg" height="70"/>
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/netlify.svg" height="70"/>
        <img src="https://raw.githubusercontent.com/tanstack/tanstack.com/main/src/images/netlify-dark.svg" height="70" alt="Netlify" />
      </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://neon.tech?utm_source=tanstack">
		  <picture>
	        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tanstack/tanstack.com/main/src/images/neon-dark.svg" height="50"/>
	        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/neon.svg" height="50"/>
	        <img src="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/neon.svg" height="50" alt="Neon" />
		  </picture>
	  </a>
    </td>
    <td>
      <a href="https://go.clerk.com/wOwHtuJ">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://tanstack.com/assets/clerk-logo-dark-CRE22T_2.svg" height="40"/>
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/clerk.svg" height="40"/>
          <img src="https://tanstack.com/assets/clerk-logo-dark-CRE22T_2.svg" height="40" alt="Clerk" />
        </picture>
      </a>
    </td>
    <td>
      <a href="https://convex.dev?utm_source=tanstack">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tanstack/tanstack.com/main/src/images/convex-white.svg" height="30"/>
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/convex.svg" height="30"/>
          <img src="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/convex.svg" height="30" alt="Convex" />
        </picture>
      </a>
    </td>
  </tr>
    <tr>
    <td>
      <a href="https://sentry.io?utm_source=tanstack">
        <picture>
           <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tanstack/tanstack.com/main/src/images/sentry-wordmark-light.svg" height="50"/>
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/sentry.svg" height="50"/>
          <img src="https://raw.githubusercontent.com/tannerlinsley/files/master/partners/sentry.svg" height="50" alt="Sentry" />
        </picture>
      </a>
    </td>
    <td>
      <a href="https://www.prisma.io?utm_source=tanstack&via=tanstack">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://tanstack.com/assets/prisma-dark-DwgDxLwn.svg" height="50"/>
          <source media="(prefers-color-scheme: light)" srcset="https://tanstack.com/assets/prisma-light-Cloa3Onm.svg" height="50"/>
          <img src="https://tanstack.com/assets/prisma-dark-DwgDxLwn.svg" height="50" alt="Prisma" />
        </picture>
      </a>
    </td>
    <td>
      <a href="https://strapi.link/tanstack-start">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://tanstack.com/assets/strapi-dark-CQ84tQTk.svg" height="40"/>
          <source media="(prefers-color-scheme: light)" srcset="https://tanstack.com/assets/strapi-light-6x7linao.svg" height="40"/>
          <img src="https://tanstack.com/assets/strapi-dark-CQ84tQTk.svg" height="40" alt="Strapi" />
        </picture>
      </a>
    </td>
  </tr>
</table>

<div align="center">
<img src="./media/partner_logo.svg" alt="Router & you?" height="65">
<p>
We're looking for TanStack Router & Start Partners to join our mission! Partner with us to push the boundaries of TanStack Router & Start and build amazing things together.
</p>
<a href="mailto:partners@tanstack.com?subject=TanStack Router & Start Partnership"><b>LET'S CHAT</b></a>
</div>

## Explore the TanStack Ecosystem

- <a href="https://github.com/tanstack/config"><b>TanStack Config</b></a> – Tooling for JS/TS packages
- <a href="https://github.com/tanstack/db"><b>TanStack DB</b></a> – Reactive sync client store
- <a href="https://github.com/tanstack/devtools"><b>TanStack DevTools</b></a> – Unified devtools panel
- <a href="https://github.com/tanstack/form"><b>TanStack Form</b></a> – Type‑safe form state
- <a href="https://github.com/tanstack/pacer"><b>TanStack Pacer</b></a> – Debouncing, throttling, batching <br/>
- <a href="https://github.com/tanstack/query"><b>TanStack Query</b></a> – Async state & caching
- <a href="https://github.com/tanstack/ranger"><b>TanStack Ranger</b></a> – Range & slider primitives
- <a href="https://github.com/tanstack/store"><b>TanStack Store</b></a> – Reactive data store
- <a href="https://github.com/tanstack/table"><b>TanStack Table</b></a> – Headless datagrids
- <a href="https://github.com/tanstack/virtual"><b>TanStack Virtual</b></a> – Virtualized rendering

… and more at <a href="https://tanstack.com"><b>TanStack.com »</b></a>

<!-- Use the force, Luke!!! -->

``n
---

## 12. js
- **URL:** https://github.com/devtechedge/js
- **Language:** Not specified
- **Topics:** None
- **Description:** Best in class web3 SDKs for Browser, Node and Mobile apps


### README.md

`markdown
<p align="center">
    <br />
    <a href="https://thirdweb.com">
        <img src="https://thirdweb.com/brand/thirdweb-icon.svg" width="200" alt=""/></a>
    <br />
</p>

<h1 align="center"><a href='https://thirdweb.com/'>thirdweb</a> TypeScript SDK</h1>

<p align="center">
    <a href="https://github.com/thirdweb-dev/js/actions/workflows/CI.yml">
        <img alt="Build Status" src="https://github.com/thirdweb-dev/js/actions/workflows/CI.yml/badge.svg"/>
    </a>
</p>

<p align="center"><strong>All-in-one web3 SDK for Browser, Node and Mobile apps</strong></p>

## Core Package

#### [`thirdweb`](./packages/thirdweb/README.md)

The main SDK package providing all-in-one web3 functionality for Browser, Node, and Mobile applications.

```bash
npm install thirdweb
```

**Features:**

- Type-safe contract and transaction APIs
- In-app wallets with social/email login
- Account abstraction (ERC4337/EIP7702) support
- 500+ external wallets supported
- Built in infra (RPC, bundler, paymaster, indexer)
- React hooks and UI components
- Automatic ABI resolution
- IPFS upload/download
- Cross-platform support (Web, React Native)

### Documentation

Visit the [developer portal](https://portal.thirdweb.com) for full documentation.

### 🚀 Quick Start

#### For React Applications

```bash
npm install thirdweb
```

```typescript
import { createThirdwebClient } from "thirdweb";
import { ConnectButton, useActiveAccount } from "thirdweb/react";

const client = createThirdwebClient({
  clientId: "YOUR_CLIENT_ID",
});

function App() {
  const account = useActiveAccount();
  console.log("Connected as", account?.address);

  return <ConnectButton client={client} />;
}
```

For React Native Applications, you'll also need to install the `@thirdweb-dev/react-native-adapter` package and import it at app startup for polyfills.

#### For Backend Applications

```bash
npm install thirdweb
```

```typescript
import { createThirdwebClient, Engine } from "thirdweb";

const client = createThirdwebClient({
  secretKey: "YOUR_SECRET_KEY",
});

const wallet = Engine.serverWallet({
  client,
  address: "0x...",
});

const transaction = transfer({
  contract: getContract({
    client,
    address: "0x...", // token contract
    chain: defineChain(1),
  }),
  to: "0x...", // recipient
  amount: "0.01", // amount in tokens
});

await wallet.enqueueTransaction({
  transaction,
});
```

## Adapters

#### [`@thirdweb-dev/react-native-adapter`](./packages/react-native-adapter/README.md)

Required polyfills and configuration for running the thirdweb SDK in React Native applications.

```bash
npm install @thirdweb-dev/react-native-adapter
```

#### [`@thirdweb-dev/wagmi-adapter`](./packages/wagmi-adapter/README.md)

Integration layer for using thirdweb's in-app wallets with wagmi.

```bash
npm install @thirdweb-dev/wagmi-adapter
```

## Type safe API wrappers

#### [`@thirdweb-dev/api`](./packages/api/README.md)

TypeScript SDK for thirdweb's API, combining all of thirdweb products.

```bash
npm install @thirdweb-dev/api
```

#### [`@thirdweb-dev/engine`](./packages/engine/README.md)

TypeScript SDK for Engine, thirdweb's backend onchain executor service.

```bash
npm install @thirdweb-dev/engine
```

#### [`@thirdweb-dev/insight`](./packages/insight/README.md)

TypeScript SDK for Insight, thirdweb's multichain indexer service.

```bash
npm install @thirdweb-dev/insight
```

#### [`@thirdweb-dev/vault-sdk`](./packages/vault-sdk/README.md)

SDK for interacting with Vault, thirdweb's secure key management service.

```bash
npm install @thirdweb-dev/vault-sdk
```

#### [`@thirdweb-dev/nebula`](./packages/nebula/README.md)

TypeScript SDK for Nebula, thirdweb's AI agent service.

```bash
npm install @thirdweb-dev/nebula
```

## Contributing

We welcome contributions from all developers regardless of experience level. If you are interested in contributing, please read our [Contributing Guide](.github/contributing.md) to learn how the repo works, how to test your changes, and how to submit a pull request.

See our [open source page](https://thirdweb.com/open-source) for more information on our open-source bounties and program.

## Additional Resources

- [Dashboard](https://thirdweb.com/login)
- [Documentation](https://portal.thirdweb.com/)
- [Templates](https://thirdweb.com/templates)
- [YouTube](https://www.youtube.com/c/thirdweb)
- [X/Twitter](https://x.com/thirdweb)
- [Telegram](https://t.me/officialthirdweb)

## Support

For help or feedback, please [visit our support site](https://thirdweb.com/support)

## Security

If you believe you have found a security vulnerability in any of our packages, we kindly ask you not to open a public issue; and to disclose this to us by emailing `security@thirdweb.com`.

``n
---

## 13. extension
- **URL:** https://github.com/devtechedge/extension
- **Language:** Not specified
- **Topics:** None
- **Description:** Your Web3 Wallet that just works. EIP-7702 ready.


### README.md

*No standard README.md found.*

---

## 14. ethers.js
- **URL:** https://github.com/devtechedge/ethers.js
- **Language:** Not specified
- **Topics:** None
- **Description:** Complete Ethereum library and wallet implementation in JavaScript.


### README.md

`markdown
The Ethers Project
==================

[![npm (tag)](https://img.shields.io/npm/v/ethers)](https://www.npmjs.com/package/ethers)
[![CI Tests](https://github.com/ethers-io/ethers.js/actions/workflows/test-ci.yml/badge.svg?branch=main)](https://github.com/ethers-io/ethers.js/actions/workflows/test-ci.yml)
![npm bundle size (version)](https://img.shields.io/bundlephobia/minzip/ethers)
![npm (downloads)](https://img.shields.io/npm/dm/ethers)
[![GitPOAP Badge](https://public-api.gitpoap.io/v1/repo/ethers-io/ethers.js/badge)](https://www.gitpoap.io/gh/ethers-io/ethers.js)
[![Twitter Follow](https://img.shields.io/twitter/follow/ricmoo?style=social)](https://twitter.com/ricmoo)

-----

A complete, compact and simple library for Ethereum and ilk, written
in [TypeScript](https://www.typescriptlang.org).

**Features**

- Keep your private keys in your client, **safe** and sound
- Import and export **JSON wallets** (Geth, Parity and crowdsale)
- Import and export BIP 39 **mnemonic phrases** (12 word backup phrases) and **HD Wallets** (English as well as Czech, French, Italian, Japanese, Korean, Simplified Chinese, Spanish, Traditional Chinese)
- Meta-classes create JavaScript objects from any contract ABI, including **ABIv2** and **Human-Readable ABI**
- Connect to Ethereum nodes over [JSON-RPC](https://ethereum.org/en/developers/docs/apis/json-rpc/), [INFURA](https://infura.io), [Etherscan](https://etherscan.io), [Alchemy](https://alchemyapi.io), [Ankr](https://ankr.com) or [MetaMask](https://metamask.io)
- **ENS names** are first-class citizens; they can be used anywhere an Ethereum addresses can be used
- **Small** (~144kb compressed; 460kb uncompressed)
- **Tree-shaking** focused; include only what you need during bundling
- **Complete** functionality for all your Ethereum desires
- Extensive [documentation](https://docs.ethers.org/v6/)
- Large collection of **test cases** which are maintained and added to
- Fully written in **TypeScript**, with strict types for security and safety
- **MIT License** (including ALL dependencies); completely open source to do with as you please


Keep Updated
------------

For advisories and important notices, follow [@ethersproject](https://twitter.com/ethersproject)
on Twitter (low-traffic, non-marketing, important information only) as well as watch this GitHub project.

For more general news, discussions, and feedback, follow or DM me,
[@ricmoo](https://twitter.com/ricmoo) on Twitter or on the
[Ethers Discord](https://discord.gg/qYtSscGYYc).


For the latest changes, see the
[CHANGELOG](https://github.com/ethers-io/ethers.js/blob/main/CHANGELOG.md).


**Summaries**

- [August 2023](https://blog.ricmoo.com/highlights-ethers-js-august-2023-fb68354c576c)
- [September 2022](https://blog.ricmoo.com/highlights-ethers-js-september-2022-d7bda0fc37ed)
- [June 2022](https://blog.ricmoo.com/highlights-ethers-js-june-2022-f5328932e35d)
- [March 2022](https://blog.ricmoo.com/highlights-ethers-js-march-2022-f511fe1e88a1)
- [December 2021](https://blog.ricmoo.com/highlights-ethers-js-december-2021-dc1adb779d1a)
- [September 2021](https://blog.ricmoo.com/highlights-ethers-js-september-2021-1bf7cb47d348)
- [May 2021](https://blog.ricmoo.com/highlights-ethers-js-may-2021-2826e858277d)
- [March 2021](https://blog.ricmoo.com/highlights-ethers-js-march-2021-173d3a545b8d)
- [December 2020](https://blog.ricmoo.com/highlights-ethers-js-december-2020-2e2db8bc800a)



Installing
----------

**NodeJS**

```
/home/ricmoo/some_project> npm install ethers
```

**Browser (ESM)**

The bundled library is available in the `./dist/` folder in this repo.

```
<script type="module">
    import { ethers } from "./dist/ethers.min.js";
</script>
```


Documentation
-------------

Browse the [documentation](https://docs.ethers.org) online:

- [Getting Started](https://docs.ethers.org/v6/getting-started/)
- [Full API Documentation](https://docs.ethers.org/v6/api/)
- [Various Ethereum Articles](https://blog.ricmoo.com/)



Providers
---------

Ethers works closely with an ever-growing list of third-party providers
to ensure getting started is quick and easy, by providing default keys
to each service.

These built-in keys mean you can use `ethers.getDefaultProvider()` and
start developing right away.

However, the API keys provided to ethers are also shared and are
intentionally throttled to encourage developers to eventually get
their own keys, which unlock many other features, such as faster
responses, more capacity, analytics and other features like archival
data.

When you are ready to sign up and start using for your own keys, please
check out the [Provider API Keys](https://docs.ethers.org/v5/api-keys/) in
the documentation.

A special thanks to these services for providing community resources:

- [Ankr](https://www.ankr.com/)
- [QuickNode](https://www.quicknode.com/)
- [Etherscan](https://etherscan.io/)
- [INFURA](https://infura.io/)
- [Alchemy](https://dashboard.alchemyapi.io/signup?referral=55a35117-028e-4b7c-9e47-e275ad0acc6d)


Extension Packages
------------------

The `ethers` package only includes the most common and most core
functionality to interact with Ethereum. There are many other
packages designed to further enhance the functionality and experience.

- [MulticallProvider](https://github.com/ethers-io/ext-provider-multicall) - A Provider which bundles multiple call requests into a single `call` to reduce latency and backend request capacity
- [MulticoinPlugin](https://github.com/ethers-io/ext-provider-plugin-multicoin) - A Provider plugin to expand the support of ENS coin types
- [GanaceProvider](https://github.com/ethers-io/ext-provider-ganache) - A Provider for in-memory node instances, for fast debugging, testing and simulating blockchain operations
- [Optimism Utilities](https://github.com/ethers-io/ext-utils-optimism) - A collection of Optimism utilities
- [LedgerSigner](https://github.com/ethers-io/ext-signer-ledger) - A Signer to interact directly with Ledger Hardware Wallets


License
-------

MIT License (including **all** dependencies).


``n
---

## 15. js-stellar-sdk
- **URL:** https://github.com/devtechedge/js-stellar-sdk
- **Language:** Not specified
- **Topics:** None
- **Description:** Main Stellar client library for the JavaScript language.


### README.md

`markdown
# Stellar JS SDK (js-stellar-sdk)

<p class="badges">
  <a href="https://badge.fury.io/js/@stellar%2Fstellar-sdk"><img src="https://badge.fury.io/js/@stellar%2Fstellar-sdk.svg" alt="npm version" height="18"></a>
  <a href="https://www.npmjs.com/package/@stellar/stellar-sdk"><img alt="Weekly Downloads" src="https://img.shields.io/npm/dw/@stellar/stellar-sdk" /></a>
  <a href="https://github.com/stellar/js-stellar-sdk/actions/workflows/tests.yml"><img alt="Test Status" src="https://github.com/stellar/js-stellar-sdk/actions/workflows/tests.yml/badge.svg" /></a>
  <a href="https://deepwiki.com/stellar/js-stellar-sdk"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki" /></a>
</p>

`js-stellar-sdk` is a JavaScript library for communicating with a
[Stellar Horizon server](https://developers.stellar.org/docs/data/apis/horizon)
and [Stellar RPC](https://developers.stellar.org/docs/data/apis/rpc). While
primarily intended for applications built on Node.js or in the browser, it can
be adapted for use in other environments with some tinkering.

The library provides:

- a networking layer API for Horizon endpoints (REST-based),
- a networking layer for Soroban RPC (JSONRPC-based).
- facilities for building and signing transactions, for communicating with a
  Stellar Horizon instance, and for submitting transactions or querying network
  history.

**Jump to:**

- [Installation](#installation): details on hitting the ground running
- [Usage](#usage): links to documentation and a variety of workarounds for
  non-traditional JavaScript environments
  - [...with React Native](#usage-with-react-native)
  - [...with Expo](#usage-with-expo-managed-workflows)
  - [...with CloudFlare Workers](#usage-with-cloudflare-workers)
  - [...with Deno](#usage-with-deno)
- [CLI](#cli): generate TypeScript bindings for Stellar smart contracts
- [Migrating](#migrating): migration guides for breaking changes
- [Developing](#developing): contribute to the project!
- [License](#license)

## Installation

Using npm, pnpm, or yarn to include `stellar-sdk` in your own project:

```shell
npm install --save @stellar/stellar-sdk
# or
pnpm add @stellar/stellar-sdk
# or
yarn add @stellar/stellar-sdk
# or
deno add npm:@stellar/stellar-sdk
```

Then, require or import it in your JavaScript code:

```js
var StellarSdk = require("@stellar/stellar-sdk");
// or
import * as StellarSdk from "@stellar/stellar-sdk";
```

(Preferably, you would only import the pieces you need to enable tree-shaking
and lower your final bundle sizes.)

### Browsers

You can use a CDN:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/stellar-sdk/{version}/stellar-sdk.js"></script>
```

> **Note:** Always make sure that you are using the latest version number. They can be found on the [releases page](https://github.com/stellar/js-stellar-sdk/releases) in GitHub.

### Custom Installation

The default bundle uses a native-fetch HTTP client with no axios dependency. If
you need the axios transport (for example, to match the behavior of older SDK
versions), set the `USE_AXIOS` environment variable to `true` when building.

#### Build with Axios

```
pnpm run build:lib:axios
```

This will create `stellar-sdk-axios.js` in `dist/`. Consumers can also import
the axios-backed entry from Node via `@stellar/stellar-sdk/axios`.

### Migrating from @stellar/stellar-base

`@stellar/stellar-base` is now folded into `@stellar/stellar-sdk`. Its classes
and functions are bundled in and re-exported from the top level, so the SDK is
the only package you need.

This only matters if you import `@stellar/stellar-base` directly. If you depend
on `@stellar/stellar-sdk` and never installed the base package separately, skip
this section. The fold-in landed in `@stellar/stellar-sdk` v16.0.0; on earlier
versions the SDK still depends on the separate base package, so don't remove it
there.

To migrate:

1. Install `@stellar/stellar-sdk` if you don't already (see
   [Installation](#installation)).

2. Update your imports. The symbols you import keep their names, so a
   project-wide find and replace of `"@stellar/stellar-base"` with
   `"@stellar/stellar-sdk"` usually does it:

   ```js
   // before
   import { Keypair, TransactionBuilder, Asset } from "@stellar/stellar-base";

   // after
   import { Keypair, TransactionBuilder, Asset } from "@stellar/stellar-sdk";
   ```

3. Uninstall the base package:

   ```shell
   npm uninstall @stellar/stellar-base
   ```

Don't keep both packages installed. Two copies of the base library cause
confusing runtime errors, such as `instanceof` checks failing on values that
look correct.

If you only use the offline primitives (`StrKey`, `Keypair`,
`TransactionBuilder`, `xdr`, and friends), you can import them from the `/base`
subpath instead of the package root:

```js
import { StrKey, Keypair } from "@stellar/stellar-sdk/base";
```

This loads only the former stellar-base modules, skipping Horizon, RPC, and the
SEP helpers (federation, web auth, stellar.toml) and their networking
dependencies. In CommonJS environments — where `require()` can't tree-shake the
root barrel — this is noticeably leaner and avoids pulling in dependencies like
`axios`, `eventsource`, and `smol-toml`.

## Versioning and compatibility

Always use the latest `@stellar/stellar-sdk`. The Stellar network upgrades its
protocol periodically, and an older SDK may fail to decode newer data (for
example, newer XDR). You can check the protocol a network currently runs in the
`current_protocol_version` field of its Horizon root (for example
[horizon.stellar.org](https://horizon.stellar.org/) for Mainnet; Testnet and
Futurenet expose their own).

These docs and the API reference cover the latest version only. To read docs for
an older version, find its Git tag on the
[releases page](https://github.com/stellar/js-stellar-sdk/releases) and browse
the `docs/` directory at that ref on GitHub. The release notes there mark the
breaking changes in each version.

## Usage

The usage documentation for this library lives in a handful of places:

- across the [Stellar Developer Docs](https://developers.stellar.org), which
  includes tutorials and examples, and
- on the generated [API doc site](https://stellar.github.io/js-stellar-sdk/) —
  which also publishes
  [agent-friendly bundles, raw markdown siblings, and a crawler policy](https://stellar.github.io/js-stellar-sdk/agents/)
  for AI tools. The site's URL, base path, and AI policy values live in
  [`config/site.ts`](https://github.com/stellar/js-stellar-sdk/blob/main/config/site.ts).

### AI agent documentation

Agents can use the documentation bundles published on the website:

- [`llms.txt`](https://stellar.github.io/js-stellar-sdk/llms.txt) — an index of
  the guides, reference pages, and other agent-facing docs.
- [`llms-full.txt`](https://stellar.github.io/js-stellar-sdk/llms-full.txt) —
  the full documentation corpus plus the changelog in one text file.

These generated bundles are not committed to the repo. To inspect bundles for a
local branch, run `pnpm docs:llms`; the generated files are written under
`public/` for the website build.

You can also refer to:

- the [documentation](https://developers.stellar.org/docs/data/horizon) for the
  Horizon REST API (if using the `Horizon` module) and
- the [documentation](https://developers.stellar.org/docs/data/rpc) for Soroban
  RPC's API (if using the `rpc` module)

### Usage with Jest

Some of the SDK's dependencies (`@noble/hashes`, `@noble/ed25519`,
`uint8array-extras`, `@exodus/bytes`) ship only ES modules. Node itself handles
this (`require(esm)` is unflagged from Node 22.12.0, the minimum this SDK
supports), but Jest's default transform pipeline does not: tests that load the
SDK fail with
`SyntaxError: Cannot use import statement outside a module` coming from inside
`node_modules`.

Tell Jest to transform those packages instead of skipping them:

```js
// jest.config.js
module.exports = {
  transformIgnorePatterns: [
    "node_modules/(?!(\\.pnpm|@noble|@exodus|uint8array-extras)/)",
  ],
};
```

`.pnpm` belongs in that list even though it is not a package. Under pnpm the
real path is `node_modules/.pnpm/<pkg>@<version>/node_modules/<pkg>/…`, so
without it the pattern matches at the first `node_modules/` segment and the
package is skipped before the name is ever compared.

If you compile tests with ts-jest or Babel, also make sure the compilation
target is `es2020` or later — the SDK and its crypto dependencies use native
`BigInt`, and downleveling below `es2020` breaks it at runtime (for example
`TypeError: Cannot convert a BigInt value to a number`).

### Usage with React Native

The SDK works in React Native, and as of v17 it no longer needs a `Buffer`
polyfill. The one thing you still need to provide in your app's entry file:

- **A Web Crypto random source.** `Keypair.random()` and SEP-10 challenge
  generation call `crypto.getRandomValues()`, which React Native doesn't
  provide out of the box. Add a polyfill that registers it on the global scope,
  imported once before any SDK code runs.

Modern React Native uses Metro with autolinking, so beyond adding the polyfill
above, no manual native linking or custom resolver config is required.

If you use Horizon streaming (`server.…().stream()`), be aware it depends on an
`EventSource`, which is now an included dependency and will work in any runtimes
that support [fetch](https://developer.mozilla.org/en-US/docs/Web/API/fetch),
[ReadableStream](https://developer.mozilla.org/en-US/docs/Web/API/ReadableStream),
[TextDecoder](https://developer.mozilla.org/en-US/docs/Web/API/TextDecoder),
[URL](https://developer.mozilla.org/en-US/docs/Web/API/URL),
[Event](https://developer.mozilla.org/en-US/docs/Web/API/Event),
[MessageEvent](https://developer.mozilla.org/en-US/docs/Web/API/MessageEvent),
[EventTarget](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget).

React Native apps using the Hermes engine may need to polyfill broken typed
array methods such as `subarray`, since this compatibility is no longer
provided by `@stellar/js-xdr`. If you run into issues, consider a polyfill such
as `@exodus/patch-broken-hermes-typed-arrays`.

#### Usage with Expo managed workflows

Expo has the same requirement as React Native above — a
`crypto.getRandomValues()` source. Install a polyfill for it (use
`npx expo install` so versions are matched to your Expo SDK) and import it at
the top of your entry point (by default `App.js`) before any SDK code.

Once `crypto.getRandomValues()` is available, `Keypair.random()` works normally
— the manual `expo-random` workaround from older Expo SDKs is no longer needed.

#### Usage with CloudFlare Workers

The SDK defaults to a native-`fetch` HTTP client, so Horizon and RPC requests
work in the Workers runtime without an HTTP adapter. As of v17 the SDK no
longer uses `Buffer`, so the
[`nodejs_compat`](https://developers.cloudflare.com/workers/runtime-apis/nodejs/)
flag is no longer required for it. The one thing to watch for:

- **Streaming.** Horizon's `.stream()` depends on `EventSource`; long-lived
  streaming connections don't fit the Workers request model well, so prefer
  polling (`.call()` / `.cursor()`) for Horizon data in a Worker.

### Usage with Deno

Deno pulls the SDK in through its npm compatibility layer. Add it to your
`deno.json` (see [Installation](#installation)) and import the bare specifier,
or skip that step and import the `npm:` specifier directly:

```js
import * as StellarSdk from "@stellar/stellar-sdk";
// or, without adding it to deno.json
import * as StellarSdk from "npm:@stellar/stellar-sdk";
```

Two Deno-specific things to keep in mind:

- **Permissions.** Horizon and RPC calls need network access, so run with
  `--allow-net` (or scope it, e.g.
  `--allow-net=horizon-testnet.stellar.org,soroban-testnet.stellar.org`).
- **The CLI.** Run it without installing anything:
  `deno run -A npm:@stellar/stellar-sdk` (see [CLI](#cli)).

## CLI

The SDK includes a command-line tool for generating TypeScript bindings from
Stellar smart contracts. These bindings provide fully-typed client code with IDE
autocompletion and compile-time type checking.

### Running the CLI

```shell
# Using npx (no installation required)
npx @stellar/stellar-sdk generate [options]

# Or if installed globally
stellar-js generate [options]
```

### Generating Bindings

You can generate bindings from three different sources:

#### From a local WASM file

```shell
npx @stellar/stellar-sdk generate \
  --wasm ./path/to/wasm_file/my_contract.wasm \
  --output-dir ./my-contract-client \
  --contract-name my-contract
```

#### From a WASM hash on the network

```shell
# testnet, futurenet, and localnet have default RPC URLs
npx @stellar/stellar-sdk generate \
  --wasm-hash <hex-encoded-hash> \
  --network testnet \
  --output-dir ./my-contract-client \
  --contract-name my-contract
```

#### From a deployed contract ID

```shell
npx @stellar/stellar-sdk generate \
  --contract-id CABC...XYZ \
  --network testnet \
  --output-dir ./my-contract-client
```

#### With custom RPC server options

For mainnet or when connecting to RPC servers that require authentication:

```shell
# Mainnet requires --rpc-url (no default)
npx @stellar/stellar-sdk generate \
  --contract-id CABC...XYZ \
  --rpc-url https://my-rpc-provider.com \
  --network mainnet \
  --output-dir ./my-contract-client

# With custom timeout and headers for authenticated RPC servers
npx @stellar/stellar-sdk generate \
  --contract-id CABC...XYZ \
  --rpc-url https://my-rpc-server.com \
  --network mainnet \
  --output-dir ./my-contract-client \
  --timeout 30000 \
  --headers '{"Authorization": "Bearer my-token"}'

# localnet with default RPC URL auto-enables --allow-http
npx @stellar/stellar-sdk generate \
  --contract-id CABC...XYZ \
  --network localnet \
  --output-dir ./my-contract-client

# When overriding the default URL, you must specify --allow-http if using HTTP
npx @stellar/stellar-sdk generate \
  --contract-id CABC...XYZ \
  --rpc-url http://my-local-server:8000/rpc \
  --network localnet \
  --output-dir ./my-contract-client \
  --allow-http
```

### CLI Options

| Option                   | Description                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------- |
| `--wasm <path>`          | Path to a local WASM file                                                                       |
| `--wasm-hash <hash>`     | Hex-encoded hash of WASM blob on the network                                                    |
| `--contract-id <id>`     | Contract ID of a deployed contract                                                              |
| `--rpc-url <url>`        | Stellar RPC server URL (has defaults for testnet/futurenet/localnet, required for mainnet)      |
| `--network <network>`    | Network to use: `testnet`, `mainnet`, `futurenet`, or `localnet` (required for network sources) |
| `--output-dir <dir>`     | Output directory for generated bindings (required)                                              |
| `--contract-name <name>` | Name for the generated package (derived from filename if not provided)                          |
| `--overwrite`            | Overwrite existing files in the output directory                                                |
| `--allow-http`           | Allow insecure HTTP connections to RPC server (default: false)                                  |
| `--timeout <ms>`         | RPC request timeout in milliseconds                                                             |
| `--headers <json>`       | Custom headers as JSON object (e.g., `'{"Authorization": "Bearer token"}'`)                     |

#### Default RPC URLs

When using `--network`, the CLI provides default RPC URLs for most networks:

| Network     | Default RPC URL                                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------ |
| `testnet`   | `https://soroban-testnet.stellar.org`                                                                              |
| `futurenet` | `https://rpc-futurenet.stellar.org`                                                                                |
| `localnet`  | `http://localhost:8000/rpc` (auto-enables `--allow-http` only when using default URL)                              |
| `mainnet`   | None - you must provide `--rpc-url` ([find providers](https://developers.stellar.org/docs/data/rpc/rpc-providers)) |

### Generated Output

The CLI generates a complete npm package structure:

```
my-contract-client/
├── src/
│   ├── index.ts      # Barrel exports
│   ├── client.ts     # Typed Client class with contract methods
│   └── types.ts      # TypeScript interfaces for contract types
├── package.json
├── tsconfig.json
├── README.md
└── .gitignore
```

### Using Generated Bindings

After generating, you can use the bindings in your project:

```typescript
import { Client } from "./my-contract-client";

const client = new Client({
  contractId: "CABC...XYZ",
  networkPassphrase: Networks.TESTNET,
  rpcUrl: "https://soroban-testnet.stellar.org",
  publicKey: keypair.publicKey(),
  ...basicNodeSigner(keypair, Networks.TESTNET),
});

// Fully typed method calls with IDE autocompletion
const result = await client.transfer({
  from: "GABC...",
  to: "GDEF...",
  amount: 1000n,
});
```

## Migrating

Upgrading from an earlier version? The
[Migration Guide](https://stellar.github.io/js-stellar-sdk/guides/00-migration/)
lists every breaking change by SDK version, newest first, and links to the
deep-dive guides for the largest ones.

## Developing

So you want to contribute to the library: welcome! Whether you're working on a
fork or want to make an upstream request, the dev-test loop is pretty
straightforward.

1. Clone the repo:

```shell
git clone https://github.com/stellar/js-stellar-sdk.git
```

2. Install Node

Because we support the oldest maintenance version of Node, please install and
develop on the version pinned in
[`.nvmrc`](https://github.com/stellar/js-stellar-sdk/blob/main/.nvmrc)
(currently Node 22; the minimum supported is 22.12.0) so you don't get
surprised when your code works locally but breaks in CI.

Here's how to install `nvm` if you haven't: https://github.com/creationix/nvm

```shell
nvm install
```

If you work on several projects that use different Node versions, you might it
helpful to install this automatic version manager:
https://github.com/wbyoung/avn

3. Enable Corepack

```shell
corepack enable
```

4. Install dependencies inside js-stellar-sdk folder:

```shell
cd js-stellar-sdk
pnpm install
```

5. Observe the project's code style

While you're making changes, make sure to run the linter to catch any linting
errors (in addition to making sure your text editor supports ESLint) and conform
to the project's code style.

```shell
pnpm run fmt
```

### Building

You can build the developer version (unoptimized, commented, with source maps,
etc.) or the production bundles:

```shell
pnpm run build
# or
pnpm run build:prod
```

### Testing

To run all tests:

```shell
pnpm run test
```

To run a specific set of tests:

```shell
pnpm run test:node
pnpm run test:browser
pnpm run test:integration
```

To generate and check the documentation site:

```shell
# generate the docs site (reference pages, llms bundles, and the Astro site under dist/site)
pnpm run docs

# preview the built site in a browser
pnpm docs:preview

# the preview server prints the local URL (default http://localhost:4321)

# for a live-reloading dev server instead, use:
pnpm docs:dev
```

### Publishing

For information on how to contribute or publish new versions of this software to
`npm`, please refer to our
[contribution guide](https://github.com/stellar/js-stellar-sdk/blob/main/CONTRIBUTING.md).

## Miscellaneous

### License

js-stellar-sdk is licensed under an Apache-2.0 license. See the
[LICENSE](https://github.com/stellar/js-stellar-sdk/blob/main/LICENSE) file
for details.

``n
---

## 16. kit
- **URL:** https://github.com/devtechedge/kit
- **Language:** Not specified
- **Topics:** None
- **Description:** Solana JavaScript SDK


### README.md

`markdown
[![npm][npm-image]][npm-url]
[![npm-downloads][npm-downloads-image]][npm-url]
<br />
[![code-style-prettier][code-style-prettier-image]][code-style-prettier-url]

[code-style-prettier-image]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
[code-style-prettier-url]: https://github.com/prettier/prettier
[npm-downloads-image]: https://img.shields.io/npm/dm/@solana/kit?style=flat
[npm-image]: https://img.shields.io/npm/v/@solana/kit?style=flat
[npm-url]: https://www.npmjs.com/package/@solana/kit

# Kit

This is the JavaScript SDK for building Solana apps for Node, web, and React Native.

> [!NOTE]
> Did you expect to find `@solana/web3.js` here? You're in the right place! We have renamed the 2.x line of `@solana/web3.js` to `@solana/kit`.
>
> The code for the 1.x line of `@solana/web3.js` can be found [here](https://github.com/solana-labs/solana-web3.js/tree/maintenance/v1.x) and the documentation [here](https://solana-foundation.github.io/solana-web3.js/).

# Installation

For use in a Node.js or web application:

```shell
npm install --save @solana/kit
```

For use in a browser, without a build system:

```html
<!-- Development (debug mode, unminified) -->
<script src="https://unpkg.com/@solana/kit/dist/index.development.js"></script>

<!-- Production (minified) -->
<script src="https://unpkg.com/@solana/kit/dist/index.production.min.js"></script>
```

# Quick Start

To get a feel for the API, run and modify the live examples in the `examples/` directory. There, you will find a series of single-purpose Node scripts that demonstrate a specific feature or use case. You will also find a React application that you can run in a browser, that demonstrates being able to create, sign, and send transactions using browser wallets.

For a fully baked intro, see: [Getting started with Solana kit](https://www.solanakit.com/docs/getting-started)

# What's New in Kit

Kit is a response to many of the pain points you have communicated to us when developing Solana applications with web3.js.

## Tree-Shakability

The object-oriented design of the web3.js (1.x) API prevents optimizing compilers from being able to ‘tree-shake’ unused code from your production builds. No matter how much of the web3.js API you use in your application, you have until now been forced to package all of it.

Read more about tree-shaking here:

- [Mozilla Developer Docs: Tree Shaking](https://developer.mozilla.org/en-US/docs/Glossary/Tree_shaking)
- [WebPack Docs: Tree Shaking](https://webpack.js.org/guides/tree-shaking/)
- [Web.Dev Blog Article: Reduce JavaScript Payloads with Tree Shaking](https://web.dev/articles/reduce-javascript-payloads-with-tree-shaking)

One example of an API that can’t be tree-shaken is the `Connection` class. It has dozens of methods, but because it’s a _class_ you have no choice but to include every method in your application’s final bundle, no matter how many you _actually_ use.

Needlessly large JavaScript bundles can cause issues with deployments to cloud compute providers like Cloudflare or AWS Lambda. They also impact webapp startup performance because of longer download and JavaScript parse times.

Kit is fully tree-shakable and will remain so, enforced by build-time checks. Optimizing compilers can now eliminate those parts of the library that your application does not use.

Kit is comprised of several smaller, modular packages under the `@solana` organization, including:

- `@solana/accounts`: For fetching and decoding accounts
- `@solana/codecs`: For composing data (de)serializers from a set of primitives or building custom ones
- `@solana/errors`: For identifying and refining coded errors thrown in the `@solana` namespace
- `@solana/rpc`: For sending RPC requests
- `@solana/rpc-subscriptions`: For subscribing to RPC notifications
- `@solana/signers`: For building message and/or transaction signer objects
- `@solana/sysvars`: For fetching and decoding sysvar accounts
- `@solana/transaction-messages`: For building and transforming Solana transaction message objects
- `@solana/transactions`: For compiling and signing transactions for submission to the network
- And many more!

Some of these packages are themselves composed of smaller packages. For instance, `@solana/rpc` is composed of `@solana/rpc-spec` (for core JSON RPC specification types), `@solana/rpc-api` (for the Solana-specific RPC methods), `@solana/rpc-transport-http` (for the default HTTP transport) and so on.

Developers can use the default configurations within the main library (`@solana/kit`) or import any of its subpackages where customization-through-composition is desired.

## Composable Internals

Depending on your use case and your tolerance for certain application behaviours, you may wish to configure your application to make a different set of tradeoffs than another developer. The web3.js (1.x) API imposed a rigid set of common-case defaults on _all_ developers, some of which were impossible to change.

The inability to customize web3.js up until now has been a source of frustration:

- The Mango team wanted to customize the transaction confirmation strategy, but all of that functionality is hidden away behind `confirmTransaction` – a static method of `Connection`. [Here’s the code for `confirmTransaction` on GitHub](https://github.com/solana-labs/solana-web3.js/blob/69a8ad25ef09f9e6d5bff1ffa8428d9be0bd32ac/packages/library-legacy/src/connection.ts#L3734).
- Solana developer ‘mPaella’ [wanted us to add a feature in the RPC](https://github.com/solana-labs/solana-web3.js/issues/1143#issuecomment-1435927152) that would failover to a set of backup URLs in case the primary one failed.
- Solana developer ‘epicfaace’ wanted first-class support for automatic time-windowed batching in the RPC transport. [Here’s their pull request](https://github.com/solana-labs/solana/pull/23628).
- Multiple folks have expressed the need for custom retry logic for failed requests or transactions. [Here’s a pull request from ‘dafyddd’](https://github.com/solana-labs/solana/pull/11811) and [another from ‘abrkn’](https://github.com/solana-labs/solana-web3.js/issues/1041) attempting to modify retry logic to suit their individual use cases.

Kit exposes far more of its internals, particularly where communication with an RPC is concerned, and allows willing developers the ability to compose new implementations from the default ones that manifest a nearly limitless array of customizations.

The individual modules that make up Kit are assembled in a **default** configuration reminiscent of the legacy library as part of the npm package `@solana/kit`, but those who wish to assemble them in different configurations may do so.

Generic types are offered in numerous places, allowing you to specify new functionality, to make extensions to each API via composition and supertypes, and to encourage you to create higher-level opinionated abstractions of your own.

In fact, we expect you to do so, and to open source some of those for use by others with similar needs.

## Modern JavaScript; Zero-Dependency

The advance of modern JavaScript features presents an opportunity to developers of crypto applications, such as the ability to use native Ed25519 keys and to express large values as native `bigint`.

The Web Incubator Community Group has advocated for the addition of Ed25519 support to the [Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API), and support has already landed in _most_ modern JavaScript runtimes.

Engine support for `bigint` values has also become commonplace. The older `number` primitive in JavaScript has a maximum value of 2^53 - 1, whereas Rust’s `u64` can represent values up to 2^64.

Kit eliminates userspace implementations of Ed25519 cryptography, large number polyfills, and more, in favour of custom implementations or the use of native JavaScript features, reducing the size of the library. It has no third-party dependencies.

## Functional Architecture

The object oriented, class-based architecture of web3.js (1.x) causes unnecessary bundle bloat. Your application has no choice but to bundle _all_ of the functionality and dependencies of a class no matter how many methods you actually use at runtime.

Class-based architecture also presents unique risks to developers who trigger the dual-package hazard. This describes a situation you can find yourself in if you build for both CommonJS and ES modules. It arises when two copies of the same class are present in the dependency tree, causing checks like `instanceof` to fail. This introduces aggravating and difficult to debug problems.

Read more about dual-package hazard:

- [NodeJS: Dual Package Hazard](https://nodejs.org/api/packages.html#dual-package-hazard)

Kit implements no classes (with the notable exception of the `SolanaError` class) and implements the thinnest possible interfaces at function boundaries.

## Statistics

Consider these statistical comparisons between Kit and the legacy web3.js 1.x.

|                                                                                                        | 1.x (Legacy) | Kit        | +/- % |
| ------------------------------------------------------------------------------------------------------ | ------------ | ---------- | ----- |
| Total minified size of library                                                                         | 81 KB        | 57.5 KB    | -29%  |
| Total minified size of library (when runtime supports Ed25519)                                         | 81 KB        | 53 KB      | -33%  |
| Bundled size of a web application that executes a transfer of lamports                                 | 111 KB       | 23.9 KB    | -78%  |
| Bundled size of a web application that executes a transfer of lamports (when runtime supports Ed25519) | 111 KB       | 18.2 KB    | -83%  |
| Performance of key generation, signing, and verifying signatures (Brave with Experimental API flag)    | 700 ops/s    | 7000 ops/s | +900% |
| First-load size for Solana Explorer                                                                    | 311 KB       | 228 KB     | -26%  |

The re-engineered library achieves these speedups and reductions in bundle size in large part through use of modern JavaScript APIs.

To validate our work, we replaced the legacy 1.x library with Kit on the homepage of the Solana Explorer. Total first-load bundle size dropped by 26% without removing a single feature. [Here’s an X thread](https://twitter.com/callum_codes/status/1679124485218226176) by Callum McIntyre if you would like to dig deeper.

# A Tour of the Kit API

Here’s an overview of how to use the new library to interact with the RPC, configure network transports, work with Ed25519 keys, and to serialize data.

## RPC

Kit ships with an implementation of the [JSON RPC specification](https://www.jsonrpc.org/specification) and a type spec for the [Solana JSON RPC](https://solana.com/docs/rpc).

The main package responsible for managing communication with an RPC is `@solana/rpc`. However, this package makes use of more granular packages to break down the RPC logic into smaller pieces. Namely, these packages are:

- `@solana/rpc`: Contains all logic related to sending Solana RPC calls.
- `@solana/rpc-api`: Describes all Solana RPC methods using types.
- `@solana/rpc-transport-http`: Provides a concrete implementation of an RPC transport using HTTP requests.
- `@solana/rpc-spec`: Defines the JSON RPC spec for sending RPC requests.
- `@solana/rpc-spec-types`: Shared JSON RPC specifications types and helpers that are used by both `@solana/rpc` and `@solana/rpc-subscriptions` (described in the next section).
- `@solana/rpc-types`: Shared Solana RPC types and helpers that are used by both `@solana/rpc` and `@solana/rpc-subscriptions`.

The main `@solana/kit` package re-exports the `@solana/rpc` package so, going forward, we will import RPC types and functions from the library directly.

### RPC Calls

You can use the `createSolanaRpc` function by providing the URL of a Solana JSON RPC server. This will create a default client for interacting with the Solana JSON RPC API.

```ts
import { createSolanaRpc } from '@solana/kit';

// Create an RPC client.
const rpc = createSolanaRpc('http://127.0.0.1:8899');
//    ^? Rpc<SolanaRpcApi>

// Send a request.
const slot = await rpc.getSlot().send();
```

### Custom RPC Transports

The `createSolanaRpc` function communicates with the RPC server using a default HTTP transport that should satisfy most use cases. You can provide your own transport or wrap an existing one to communicate with RPC servers in any way you see fit. In the example below, we explicitly create a transport and use it to create a new RPC client via the `createSolanaRpcFromTransport` function.

```ts
import { createSolanaRpcFromTransport, createDefaultRpcTransport } from '@solana/kit';

// Create an HTTP transport or any custom transport of your choice.
const transport = createDefaultRpcTransport({ url: 'https://api.devnet.solana.com' });

// Create an RPC client using that transport.
const rpc = createSolanaRpcFromTransport(transport);
//    ^? Rpc<SolanaRpcApi>

// Send a request.
const slot = await rpc.getSlot().send();
```

A custom transport can implement specialized functionality such as coordinating multiple transports, implementing retries, and more. Let's take a look at some concrete examples.

#### Round Robin

A ‘round robin’ transport is one that distributes requests to a list of endpoints in sequence.

```ts
import { createDefaultRpcTransport, createSolanaRpcFromTransport, type RpcTransport } from '@solana/kit';

// Create an HTTP transport for each RPC server.
const transports = [
    createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-1.com' }),
    createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-2.com' }),
    createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-3.com' }),
];

// Set up the round-robin transport.
let nextTransport = 0;
async function roundRobinTransport<TResponse>(...args: Parameters<RpcTransport>): Promise<TResponse> {
    const transport = transports[nextTransport];
    nextTransport = (nextTransport + 1) % transports.length;
    return await transport(...args);
}

// Create an RPC client using the round-robin transport.
const rpc = createSolanaRpcFromTransport(roundRobinTransport);
```

#### Sharding

A sharding transport is a kind of distributing transport that sends requests to a particular server based on something about the request itself. Here’s an example that sends requests to different servers depending on the name of the method:

```ts
import { createDefaultRpcTransport, createSolanaRpcFromTransport, type RpcTransport } from '@solana/kit';

// Create multiple transports.
const transportA = createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-1.com' });
const transportB = createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-2.com' });
const transportC = createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-3.com' });
const transportD = createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-4.com' });

// Function to determine which shard to use based on the request method.
function selectShard(method: string): RpcTransport {
    switch (method) {
        case 'getAccountInfo':
        case 'getBalance':
            return transportA;
        case 'getLatestBlockhash':
        case 'getTransaction':
            return transportB;
        case 'sendTransaction':
            return transportC;
        default:
            return transportD;
    }
}

// Create a transport that selects the correct transport given the request method name.
async function shardingTransport<TResponse>(...args: Parameters<RpcTransport>): Promise<TResponse> {
    const payload = args[0].payload as { method: string };
    const selectedTransport = selectShard(payload.method);
    return (await selectedTransport(...args)) as TResponse;
}

// Create an RPC client using the sharding transport.
const rpc = createSolanaRpcFromTransport(shardingTransport);
```

#### Retry

A custom transport is a good place to implement global retry logic for every request:

```ts
import { createDefaultRpcTransport, createSolanaRpcFromTransport, type RpcTransport } from '@solana/kit';

// Set the maximum number of attempts to retry a request.
const MAX_ATTEMPTS = 4;

// Create the default transport.
const defaultTransport = createDefaultRpcTransport({ url: 'https://mainnet-beta.my-server-1.com' });

// Sleep function to wait for a given number of milliseconds.
function sleep(ms: number): Promise<void> {
    return new Promise(resolve => setTimeout(resolve, ms));
}

// Calculate the delay for a given attempt.
function calculateRetryDelay(attempt: number): number {
    // Exponential backoff with a maximum of 1.5 seconds.
    return Math.min(100 * Math.pow(2, attempt), 1500);
}

// A retrying transport that will retry up to MAX_ATTEMPTS times before failing.
async function retryingTransport<TResponse>(...args: Parameters<RpcTransport>): Promise<TResponse> {
    let requestError;
    for (let attempts = 0; attempts < MAX_ATTEMPTS; attempts++) {
        try {
            return await defaultTransport(...args);
        } catch (err) {
            requestError = err;
            // Only sleep if we have more attempts remaining.
            if (attempts < MAX_ATTEMPTS - 1) {
                const retryDelay = calculateRetryDelay(attempts);
                await sleep(retryDelay);
            }
        }
    }
    throw requestError;
}

// Create the RPC client using the retrying transport.
const rpc = createSolanaRpcFromTransport(retryingTransport);
```

#### Failover

Support for handling network failures can be implemented in the transport itself. Here’s an example of some failover logic integrated into a transport:

```ts
import { createDefaultRpcTransport, createSolanaRpcFromTransport, type RpcTransport } from '@solana/kit';

// List of RPC endpoints for failover.
const rpcEndpoints = [
    'https://mainnet-beta.my-server-1.com',
    'https://mainnet-beta.my-server-2.com',
    'https://mainnet-beta.my-server-3.com',
    'https://mainnet-beta.my-server-3.com',
];

// Create an array of transports from the endpoints.
const transports = rpcEndpoints.map(url => createDefaultRpcTransport({ url }));

// A failover transport that switches to the next transport on failure.
async function failoverTransport<TResponse>(...args: Parameters<RpcTransport>): Promise<TResponse> {
    let lastError;
    for (const transport of transports) {
        try {
            return await transport(...args);
        } catch (err) {
            lastError = err;
            console.warn(`Transport failed: ${err}. Trying next transport...`);
        }
    }
    // If all transports fail, throw the last error.
    throw lastError;
}

// Create the RPC client using the failover transport.
const rpc = createSolanaRpcFromTransport(failoverTransport);
```

### Augmenting/Constraining the RPC API

Using the `createSolanaRpc` or `createSolanaRpcFromTransport` methods, we always get the same API that includes the Solana RPC API methods. Since the RPC API is described using types only, it is possible to augment those types to add your own methods.

When constraining the API scope, keep in mind that types don’t affect bundle size. You may still like to constrain the type-spec for a variety of reasons, including reducing TypeScript noise.

#### Constraining by Cluster

If you're using a specific cluster, you may wrap your RPC URL inside a helper function like `mainnet` or `devnet` to inject that information into the RPC type system.

```ts
import { createSolanaRpc, mainnet, devnet } from '@solana/kit';

const mainnetRpc = createSolanaRpc(mainnet('https://api.mainnet-beta.solana.com'));
//    ^? RpcMainnet<SolanaRpcApiMainnet>

const devnetRpc = createSolanaRpc(devnet('https://api.devnet.solana.com'));
//    ^? RpcDevnet<SolanaRpcApiDevnet>
```

In the example above, `devnetRpc.requestAirdrop(..)` will work, but `mainnetRpc.requestAirdrop(..)` will raise a TypeScript error since `requestAirdrop` is not a valid method of the mainnet cluster.

#### Cherry-Picking API Methods

You can constrain the API’s type-spec even further so you are left only with the methods you need. The simplest way to do this is to cast the created RPC client to a type that only includes the required methods.

```ts
import { createSolanaRpc, type Rpc, type GetAccountInfoApi, type GetMultipleAccountsApi } from '@solana/kit';

const rpc = createSolanaRpc('http://127.0.0.1:8899') as Rpc<GetAccountInfoApi & GetMultipleAccountsApi>;
```

Alternatively, you can explicitly create the RPC API using the `createSolanaRpcApi` function. You will need to create your own transport and bind the two together using the `createRpc` function.

```ts
import {
    createDefaultRpcTransport,
    createRpc,
    createSolanaRpcApi,
    DEFAULT_RPC_CONFIG,
    type GetAccountInfoApi,
    type GetMultipleAccountsApi,
} from '@solana/kit';

const api = createSolanaRpcApi<GetAccountInfoApi & GetMultipleAccountsApi>(DEFAULT_RPC_CONFIG);
const transport = createDefaultRpcTransport({ url: 'http://127.0.0.1:8899' });

const rpc = createRpc({ api, transport });
```

Note that the `createSolanaRpcApi` function is a wrapper on top of the `createJsonRpcApi` function which adds some Solana-specific transformers such as setting a default commitment on all methods or throwing an error when an integer overflow is detected.

#### Creating Your Own API Methods

The new library’s RPC specification supports an _infinite_ number of JSON-RPC methods with **zero increase** in bundle size.

This means the library can support future additions to the official [Solana JSON RPC](https://docs.solana.com/api), or [custom RPC methods](https://docs.helius.dev/compression-and-das-api/digital-asset-standard-das-api/get-asset) defined by some RPC provider.

Here’s an example of how a developer at might build a custom RPC type-spec for an RPC provider's implementation of the Metaplex Digital Asset Standard's `getAsset` method:

```ts
// Define the method's response payload.
type GetAssetApiResponse = Readonly<{
    interface: DasApiAssetInterface;
    id: Address;
    content: Readonly<{
        files?: readonly {
            mime?: string;
            uri?: string;
            [key: string]: unknown;
        }[];
        json_uri: string;
        links?: readonly {
            [key: string]: unknown;
        }[];
        metadata: DasApiMetadata;
    }>;
    /* ...etc... */
}>;

// Set up a type spec for the request method.
type GetAssetApi = {
    // Define the method's name, parameters and response type
    getAsset(args: { id: Address }): GetAssetApiResponse;
};

// Export the type spec for downstream users.
export type MetaplexDASApi = GetAssetApi;
```

Here’s how a developer might use it:

```ts
import { createDefaultRpcTransport, createRpc, createJsonRpcApi } from '@solana/kit';

// Create the custom API.
const api = createJsonRpcApi<MetaplexDASApi>();

// Set up an HTTP transport to a server that supports the custom API.
const transport = createDefaultRpcTransport({
    url: 'https://mainnet.helius-rpc.com/?api-key=<api_key>',
});

// Create the RPC client.
const metaplexDASRpc = createRpc({ api, transport });
//    ^? Rpc<MetaplexDASApi>
```

As long as a particular JSON RPC method adheres to the [official JSON RPC specification](https://www.jsonrpc.org/specification), it will be supported by Kit.

### Aborting RPC Requests

RPC requests are now abortable with modern `AbortControllers`. When calling an RPC method such as `getSlot`, it will return a `PendingRpcRequest` proxy object that contains a `send` method to send the request to the server.

```ts
const pendingRequest: PendingRpcRequest<Slot> = rpc.getSlot();

const slot: Slot = await pendingRequest.send();
```

The arguments of the `getSlot` method are reserved for the request payload, but the `send` method is where additional arguments such as an `AbortSignal` can be accepted in the context of the request.

Aborting RPC requests can be useful for a variety of things such as setting a timeout on a request or cancelling a request when a user navigates away from a page.

```ts
import { createSolanaRpc } from '@solana/kit';

const rpc = createSolanaRpc('http://127.0.0.1:8900');

// Create a new AbortController.
const abortController = new AbortController();

// Abort the request when the user navigates away from the current page.
function onUserNavigateAway() {
    abortController.abort();
}

// The request will be aborted if and only if the user navigates away from the page.
const slot = await rpc.getSlot().send({ abortSignal: abortController.signal });
```

Read more about `AbortController` here:

- [Mozilla Developer Docs: `AbortController`](https://developer.mozilla.org/en-US/docs/Web/API/AbortController)
- [Mozilla Developer Docs: `AbortSignal`](https://developer.mozilla.org/en-US/docs/Web/API/AbortSignal)
- [JavaScript.info: Fetch: Abort](https://javascript.info/fetch-abort)

## RPC Subscriptions

Subscriptions in the legacy library do not allow custom retry logic and do not allow you to recover from potentially missed messages. The new version does away with silent retries, surfaces transport errors to your application, and gives you the opportunity to recover from gap events.

The main package responsible for managing communication with RPC subscriptions is `@solana/rpc-subscriptions`. However, similarly to `@solana/rpc`, this package also makes use of more granular packages. These packages are:

- `@solana/rpc-subscriptions`: Contains all logic related to subscribing to Solana RPC notifications.
- `@solana/rpc-subscriptions-api`: Describes all Solana RPC subscriptions using types.
- `@solana/rpc-subscriptions-channel-websocket`: Provides a concrete implementation of an RPC Subscriptions channel using WebSockets.
- `@solana/rpc-subscriptions-spec`: Defines the JSON RPC spec for subscribing to RPC notifications.
- `@solana/rpc-spec-types`: Shared JSON RPC specifications types and helpers that are used by both `@solana/rpc` and `@solana/rpc-subscriptions`.
- `@solana/rpc-types`: Shared Solana RPC types and helpers that are used by both `@solana/rpc` and `@solana/rpc-subscriptions`.

Since the main `@solana/kit` library also re-exports the `@solana/rpc-subscriptions` package we will import RPC Subscriptions types and functions directly from the main library going forward.

### Getting Started with RPC Subscriptions

To get started with RPC Subscriptions, you may use the `createSolanaRpcSubscriptions` function by providing the WebSocket URL of a Solana JSON RPC server. This will create a default client for interacting with Solana RPC Subscriptions.

```ts
import { createSolanaRpcSubscriptions } from '@solana/kit';

// Create an RPC Subscriptions client.
const rpcSubscriptions = createSolanaRpcSubscriptions('ws://127.0.0.1:8900');
//    ^? RpcSubscriptions<SolanaRpcSubscriptionsApi>
```

### Subscriptions as `AsyncIterators`

The new subscriptions API vends subscription notifications as an `AsyncIterator`. The `AsyncIterator` conforms to the [async iterator protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_async_iterator_and_async_iterable_protocols), which allows developers to consume messages using a `for await...of` loop.

Here’s an example of working with a subscription in the new library:

```ts
import { address, createSolanaRpcSubscriptions, createDefaultRpcSubscriptionsTransport } from '@solana/kit';

// Create the RPC Subscriptions client.
const rpcSubscriptions = createSolanaRpcSubscriptions('ws://127.0.0.1:8900');

// Set up an abort controller.
const abortController = new AbortController();

// Subscribe to account notifications.
const accountNotifications = await rpcSubscriptions
    .accountNotifications(address('AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3'), { commitment: 'confirmed' })
    .subscribe({ abortSignal: abortController.signal });

try {
    // Consume messages.
    for await (const notification of accountNotifications) {
        console.log('New balance', notification.value.lamports);
    }
} catch (e) {
    // The subscription went down.
    // Retry it and then recover from potentially having missed
    // a balance update, here (eg. by making a `getBalance()` call).
}
```

You can read more about `AsyncIterator` at the following links:

- [Mozilla Developer Docs: `AsyncIterator`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/AsyncIterator)
- [Luciano Mammino (Blog): JavaScript Async Iterators](https://www.nodejsdesignpatterns.com/blog/javascript-async-iterators/)

### Aborting RPC Subscriptions

Similarly to RPC calls, applications can terminate active subscriptions using an `AbortController` attribute on the `subscribe` method. In fact, this parameter is _required_ for subscriptions to encourage you to clean up subscriptions that your application no longer needs.

Let's take a look at some concrete examples that demonstrate how to abort subscriptions.

#### Subscription Timeout

Here's an example of an `AbortController` used to abort a subscription after a 5-second timeout:

```ts
import { createSolanaRpcSubscriptions } from '@solana/kit';

const rpcSubscriptions = createSolanaRpcSubscriptions('ws://127.0.0.1:8900');

// Subscribe for slot notifications using an AbortSignal that times out after 5 seconds.
const slotNotifications = await rpcSubscriptions
    .slotNotifications()
    .subscribe({ abortSignal: AbortSignal.timeout(5000) });

// Log slot notifications.
for await (const notification of slotNotifications) {
    console.log('Slot notification', notification);
}

console.log('Done.');
```

Read more about `AbortController` at the following links:

- [Mozilla Developer Docs: `AbortController`](https://developer.mozilla.org/en-US/docs/Web/API/AbortController)
- [Mozilla Developer Docs: `AbortSignal`](https://developer.mozilla.org/en-US/docs/Web/API/AbortSignal)
- [JavaScript.info: Fetch: Abort](https://javascript.info/fetch-abort)

#### Cancelling Subscriptions

It is also possible to abort a subscription inside the `for await...of` loop. This enables us to cancel a subscription based on some condition, such as a change in the state of an account. For instance, the following example cancels a subscription when the owner of an account changes:

```ts
// Subscribe to account notifications.
const accountNotifications = await rpc
    .accountNotifications(address('AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3'), { commitment: 'confirmed' })
    .subscribe({ abortSignal });

// Consume messages.
let previousOwner = null;
for await (const notification of accountNotifications) {
    const {
        value: { owner },
    } = notification;
    // Check the owner to see if it has changed
    if (previousOwner && owner !== previousOwner) {
        // If so, abort the subscription
        abortController.abort();
    } else {
        console.log(notification);
    }
    previousOwner = owner;
}
```

### Failed vs. Aborted Subscriptions

It is important to note that a subscription failure behaves differently from a subscription abort. A subscription failure occurs when the subscription goes down and will throw an error that can be intercepted in a `try/catch`. However, an aborted subscription will not throw an error, but will instead exit the `for await...of` loop.

```ts
try {
    for await (const notification of notifications) {
        // Consume messages.
    }
    // [ABORTED] Reaching this line means the subscription was aborted — i.e. unsubscribed.
} catch (e) {
    // [FAILED] Reaching this line means the subscription went down.
    // Retry it, then recover from potential missed messages.
} finally {
    // [ABORTED or FAILED] Whether the subscription failed or was aborted, you can run cleanup code here.
}
```

### Message Gap Recovery

One of the most crucial aspects of any subscription API is managing potential missed messages. Missing messages, such as account state updates, could be catastrophic for an application. That’s why the new library provides native support for recovering missed messages using the `AsyncIterator`.

When a connection fails unexpectedly, any messages you miss while disconnected can result in your UI falling behind or becoming corrupt. Because subscription failure is now made explicit in the new API, you can implement ‘catch-up’ logic after re-establishing the subscription.

Here’s an example of such logic:

```ts
try {
    for await (const notif of accountNotifications) {
        updateAccountBalance(notif.lamports);
    }
} catch (e) {
    // The subscription failed.
    // First, re-establish the subscription.
    await setupAccountBalanceSubscription(address);
    // Then make a one-shot request to 'catch up' on any missed balance changes.
    const { value: lamports } = await rpc.getBalance(address).send();
    updateAccountBalance(lamports);
}
```

### Using Custom RPC Subscriptions Transports

The `createSolanaRpcSubscriptions` function communicates with the RPC server using a default `WebSocket` channel that should satisfy most use cases. However, you may here as well provide your own channel creator or decorate existing ones to communicate with RPC servers in any way you see fit. In the example below, we supply a custom `WebSocket` channel creator and use it to create a new RPC Subscriptions client via the `createSolanaRpcSubscriptionsFromTransport` function.

```ts
import { createDefaultRpcSubscriptionsTransport, createSolanaRpcSubscriptionsFromTransport } from '@solana/kit';

// Create a transport with a custom channel creator of your choice.
const transport = createDefaultRpcSubscriptionsTransport({
    createChannel({ abortSignal }) {
        return createWebSocketChannel({
            maxSubscriptionsPerChannel: 100,
            minChannels: 25,
            sendBufferHighWatermark: 32_768,
            signal: abortSignal,
            url: 'ws://127.0.0.1:8900',
        });
    },
});

// Create an RPC client using that transport.
const rpcSubscriptions = createSolanaRpcSubscriptionsFromTransport(transport);
//    ^? RpcSubscriptions<SolanaRpcSubscriptionsApi>
```

### Augmenting/Constraining the RPC Subscriptions API

Using the `createSolanaRpcSubscriptions` or `createSolanaRpcSubscriptionsFromTransport` functions, we always get the same RPC Subscriptions API, including all Solana RPC stable subscriptions. However, since the RPC Subscriptions API is described using types only, it is possible to constrain the API to a specific set of subscriptions or even add your own custom subscriptions.

#### Constraining by Cluster

If you're using a specific cluster, you may wrap your RPC URL inside a helper function like `mainnet` or `devnet` to inject that information into the RPC type system.

```ts
import { createSolanaRpcSubscriptions, mainnet, devnet } from '@solana/kit';

const mainnetRpc = createSolanaRpcSubscriptions(mainnet('https://api.mainnet-beta.solana.com'));
//    ^? RpcSubscriptionsMainnet<SolanaRpcSubscriptionsApi>

const devnetRpc = createSolanaRpcSubscriptions(devnet('https://api.devnet.solana.com'));
//    ^? RpcSubscriptionsDevnet<SolanaRpcSubscriptionsApi>
```

#### Including Unstable Subscriptions

If your app needs access to [unstable RPC Subscriptions](https://solana.com/docs/rpc/websocket/blocksubscribe) — e.g. `BlockNotificationsApi` or `SlotsUpdatesNotificationsApi` — and your RPC server supports them, you may use the `createSolanaRpcSubscriptions_UNSTABLE` and `createSolanaRpcSubscriptionsFromTransport_UNSTABLE` functions to create an RPC Subscriptions client that includes those subscriptions.

```ts
import {
    createDefaultSolanaRpcSubscriptionsChannelCreator,
    createDefaultRpcSubscriptionsTransport,
    createSolanaRpcSubscriptions_UNSTABLE,
    createSolanaRpcSubscriptionsFromTransport_UNSTABLE,
} from '@solana/kit';

// Using the default WebSocket channel.
const rpcSubscriptions = createSolanaRpcSubscriptions_UNSTABLE('ws://127.0.0.1:8900');
//    ^? RpcSubscriptions<SolanaRpcSubscriptionsApi & SolanaRpcSubscriptionsApiUnstable>

// Using a custom transport.
const transport = createDefaultRpcSubscriptionsTransport({
    createChannel: createDefaultSolanaRpcSubscriptionsChannelCreator({
        url: 'ws://127.0.0.1:8900',
    }),
});
const rpcSubscriptions = createSolanaRpcSubscriptionsFromTransport_UNSTABLE(transport);
//    ^? RpcSubscriptions<SolanaRpcSubscriptionsApi & SolanaRpcSubscriptionsApiUnstable>
```

#### Cherry-Picking API Methods

You may constrain the scope of the Subscription API even further so you are left only with the subscriptions you need. The simplest way to do this is to cast the created RPC client to a type that only includes the methods you need.

```ts
import {
    createSolanaRpcSubscriptions,
    type RpcSubscriptions,
    type AccountNotificationsApi,
    type SlotNotificationsApi,
} from '@solana/kit';

const rpc = createSolanaRpcSubscriptions('ws://127.0.0.1:8900') as RpcSubscriptions<
    AccountNotificationsApi & SlotNotificationsApi
>;
```

Alternatively, you may explicitly create the RPC Subscriptions API using the `createSolanaRpcSubscriptionsApi` function. You will then need to create your own transport explicitly and bind the two together using the `createSubscriptionRpc` function.

```ts
import {
    createDefaultSolanaRpcSubscriptionsChannelCreator,
    createDefaultRpcSubscriptionsTransport,
    createSubscriptionRpc,
    createSolanaRpcSubscriptionsApi,
    DEFAULT_RPC_CONFIG,
    type AccountNotificationsApi,
    type SlotNotificationsApi,
} from '@solana/kit';

const api = createSolanaRpcSubscriptionsApi<AccountNotificationsApi & SlotNotificationsApi>(DEFAULT_RPC_CONFIG);
const transport = createDefaultRpcSubscriptionsTransport({
    createChannel: createDefaultSolanaRpcSubscriptionsChannelCreator({
        url: 'ws://127.0.0.1:8900',
    }),
});
const rpcSubscriptions = createSubscriptionRpc({ api, transport });
```

Note that the `createSolanaRpcSubscriptionsApi` function is a wrapper on top of the `createRpcSubscriptionsApi` function which adds some Solana-specific transformers such as setting a default commitment on all methods or throwing an error when an integer overflow is detected.

## Keys

The new library takes a brand-new approach to Solana key pairs and addresses, which will feel quite different from the classes `PublicKey` and `Keypair` from version 1.x.

### Web Crypto API

All key operations now use the native Ed25519 implementation in JavaScript’s Web Crypto API.

The API itself is designed to be a more reliably secure way to manage highly sensitive secret key information, but **developers should still use extreme caution when dealing with secret key bytes in their applications**.

One thing to note is that many operations from Web Crypto – such as importing, generating, signing, and verifying are now **asynchronous**.

Here’s an example of generating a `CryptoKeyPair` using the Web Crypto API and signing a message:

```ts
import { generateKeyPair, signBytes, verifySignature } from '@solana/kit';

const keyPair: CryptoKeyPair = await generateKeyPair();

const message = new Uint8Array(8).fill(0);

const signedMessage = await signBytes(keyPair.privateKey, message);
//    ^? Signature

const verified = await verifySignature(keyPair.publicKey, signedMessage, message);
```

### Web Crypto Polyfill

Wherever Ed25519 is not supported, we offer a polyfill for Web Crypto’s Ed25519 API.

This polyfill can be found at `@solana/webcrypto-ed25519-polyfill` and mimics the functionality of the Web Crypto API for Ed25519 key pairs using the same userspace implementation we used in web3.js 1.x. It does not polyfill other algorithms.

Determine if your target runtime supports Ed25519, and install the polyfill if it does not:

```ts
import { install } from '@solana/webcrypto-ed25519-polyfill';
import { generateKeyPair, signBytes, verifySignature } from '@solana/kit';

install();
const keyPair: CryptoKeyPair = await generateKeyPair();

/* Remaining logic */
```

You can see where Ed25519 is currently supported in [this GitHub issue](https://github.com/WICG/webcrypto-secure-curves/issues/20) on the Web Crypto repository. Consider sniffing the user-agent when deciding whether or not to deliver the polyfill to browsers.

Operations on `CryptoKey` objects using the Web Crypto API _or_ the polyfill are mostly handled by the `@solana/keys` package.

### String Addresses

All addresses are now JavaScript strings. They are represented by the opaque type `Address`, which describes exactly what a Solana address actually is.

Consequently, that means no more `PublicKey`.

Here’s what they look like in development:

```ts
import { Address, address, getAddressFromPublicKey, generateKeyPair } from '@solana/kit';

// Coerce a string to an `Address`
const myOtherAddress = address('AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3');

// Typecast it instead
const myAddress =
    'AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3' as Address<'AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3'>;

// From CryptoKey
const keyPair = await generateKeyPair();
const myPublicKeyAsAddress = await getAddressFromPublicKey(keyPair.publicKey);
```

Some tooling for working with base58-encoded addresses can be found in the `@solana/addresses` package.

## Transactions

### Creating Transaction Messages

Like many other familiar aspects of the 1.0 library, transactions have received a makeover.

For starters, all transaction messages are now version-aware, so there’s no longer a need to juggle two different types (eg. `Transaction` vs. `VersionedTransaction`).

Address lookups are now completely described inside transaction message instructions, so you don’t have to materialize `addressTableLookups` anymore.

Here’s a simple example of creating a transaction message &ndash; notice how its type is refined at each step of the process:

```ts
import {
    address,
    createTransactionMessage,
    setTransactionMessageFeePayer,
    setTransactionMessageLifetimeUsingBlockhash,
    Blockhash,
} from '@solana/kit';

const recentBlockhash = {
    blockhash: '4uhcVJyU9pJkvQyS88uRDiswHXSCkY3zQawwpjk2NsNY' as Blockhash,
    lastValidBlockHeight: 196055492n,
};
const feePayer = address('AxZfZWeqztBCL37Mkjkd4b8Hf6J13WCcfozrBY6vZzv3');

// Create a new transaction message
const transactionMessage = createTransactionMessage({ version: 0 });
//    ^? V0TransactionMessage

// Set the fee payer
const transactionMessageWithFeePayer = setTransactionMessageFeePayer(feePayer, transactionMessage);
//    ^? V0TransactionMessage & TransactionMessageWithFeePayer

const transactionMessageWithFeePayerAndLifetime = setTransactionMessageLifetimeUsingBlockhash(
    // ^? V0TransactionMessage & TransactionMessageWithFeePayer & TransactionMessageWithBlockhashLifetime
    recentBlockhash,
    transactionMessageWithFeePayer,
);
```

As you can see, each time a transaction message is modified, the type reflects its new shape. If you add a fee payer, you’ll get a type representing a transaction message with a fee payer, and so on.

Transaction message objects are also **frozen by these functions** to prevent them from being mutated in place.

### Signing Transaction Messages

The `signTransaction(..)` function will raise a type error if your transaction message is not already equipped with a fee payer and a lifetime. This helps you catch errors at author-time instead of runtime.

```ts
const feePayer = await generateKeyPair();
const feePayerAddress = await getAddressFromPublicKey(feePayer.publicKey);

const transactionMessage = createTransactionMessage({ version: 'legacy' });
const transactionMessageWithFeePayer = setTransactionMessageFeePayer(feePayerAddress, transactionMessage);

// Attempting to sign the transaction message without a lifetime will throw a type error
const signedTransaction = await signTransaction([signer], transactionMessageWithFeePayer);
// => "Property 'lifetimeConstraint' is missing in type"
```

### Calibrating a Transaction Message's Compute Unit Budget

Correctly budgeting a compute unit limit for your transaction message can increase the probability that your transaction will be accepted for processing. If you don't declare a compute unit limit on your transaction, validators will assume an upper limit of 200K compute units (CU) per instruction.

Since validators have an incentive to pack as many transactions into each block as possible, they may choose to include transactions that they know will fit into the remaining compute budget for the current block over transactions that might not. For this reason, you should set a compute unit limit on each of your transaction messages, whenever possible.

Use these utilities to estimate the actual compute unit cost of a given transaction message and set it on the message.

```ts
import { createSolanaRpc, estimateComputeUnitLimitFactory, setTransactionMessageComputeUnitLimit } from '@solana/kit';

// Create an estimator function.
const rpc = createSolanaRpc('http://127.0.0.1:8899');
const estimateComputeUnitLimit = estimateComputeUnitLimitFactory({ rpc });

// Create your transaction message.
const transactionMessage = pipe(
    createTransactionMessage({ version: 'legacy' }),
    /* ... */
);

// Request an estimate of the actual compute units this message will consume.
const computeUnitsEstimate = await estimateComputeUnitLimit(transactionMessage);

// Set the transaction message's compute unit budget.
const transactionMessageWithComputeUnitLimit = setTransactionMessageComputeUnitLimit(
    computeUnitsEstimate,
    transactionMessage,
);
```

> [!NOTE]
> For legacy and v0 transactions, if the transaction message does not already have a `SetComputeUnitLimit` instruction, the estimator will add one before simulation. This ensures that the compute unit consumption of the instruction itself is included in the estimate.

Alternatively, use `estimateAndSetComputeUnitLimitFactory` to estimate and set the compute unit limit in a single step. Pair it with `fillTransactionMessageProvisoryComputeUnitLimit` during transaction construction to reserve space for the limit that will later be estimated.

```ts
import {
    estimateAndSetComputeUnitLimitFactory,
    estimateComputeUnitLimitFactory,
    fillTransactionMessageProvisoryComputeUnitLimit,
} from '@solana/kit';

// During construction, reserve space for the compute unit limit.
const messageWithProvisoryLimit = fillTransactionMessageProvisoryComputeUnitLimit(transactionMessage);

// Later, estimate and replace the provisory limit.
const estimator = estimateComputeUnitLimitFactory({ rpc });
const estimateAndSet = estimateAndSetComputeUnitLimitFactory(estimator);
const updatedMessage = await estimateAndSet(messageWithProvisoryLimit);
```

> [!WARNING]
> The compute unit estimate is just that &ndash; an estimate. The compute unit consumption of the actual transaction might be higher or lower than what was observed in simulation. Unless you are confident that your particular transaction message will consume the same or fewer compute units as was estimated, you might like to augment the estimate by either a fixed number of CUs or a multiplier.

> [!NOTE]
> If you are preparing an _unsigned_ transaction, destined to be signed and submitted to the network by a wallet, you might like to leave it up to the wallet to determine the compute unit limit. Consider that the wallet might have a more global view of how many compute units certain types of transactions consume, and might be able to make better estimates of an appropriate compute unit budget.

### Helpers For Building Transaction Messages

Building transaction messages in this manner might feel different from what you’re used to. Also, we certainly wouldn’t want you to have to bind transformed transaction messages to a new variable at each step, so we have released a functional programming library dubbed `@solana/functional` that lets you build transaction messages in **pipelines**. Here’s how it can be used:

```ts
import { pipe } from '@solana/functional';
import {
    address,
    createTransactionMessage,
    setTransactionMessageFeePayer,
    setTransactionMessageLifetimeUsingBlockhash,
    Blockhash,
} from '@solana/kit';

// Use `pipe(..)` to create a pipeline of transaction message transformation operations
const transactionMessage = pipe(
    createTransactionMessage({ version: 0 }),
    tx => setTransactionMessageFeePayer(feePayer, tx),
    tx => setTransactionMessageLifetimeUsingBlockhash(recentBlockhash, tx),
);
```

Note that `pipe(..)` is general-purpose, so it can be used to pipeline any functional transforms.

## Codecs

We have taken steps to make it easier to write data (de)serializers, especially as they pertain to Rust datatypes and byte buffers.

Solana’s codecs libraries are broken up into modular components so you only need to import the ones you need. They are:

- `@solana/codecs-core`: The core codecs library for working with codecs serializers and creating custom ones
- `@solana/codecs-numbers`: Used for serialization of numbers (little-endian and big-endian bytes, etc.)
- `@solana/codecs-strings`: Used for serialization of strings
- `@solana/codecs-data-structures`: Codecs and serializers for structs
- `@solana/options`: Designed to build codecs and serializers for types that mimic Rust’s enums, which can include embedded data within their variants such as values, tuples, and structs

These packages are included in the main `@solana/kit` library but you may also import them from `@solana/codecs` if you only need the codecs.

Here’s an example of encoding and decoding a custom struct with some strings and numbers:

```ts
import { addCodecSizePrefix } from '@solana/codecs-core';
import { getStructCodec } from '@solana/codecs-data-structures';
import { getU32Codec, getU64Codec, getU8Codec } from '@solana/codecs-numbers';
import { getUtf8Codec } from '@solana/codecs-strings';

// Equivalent in Rust:
// struct {
//     amount: u64,
//     decimals: u8,
//     name: String,
// }
const structCodec = getStructCodec([
    ['amount', getU64Codec()],
    ['decimals', getU8Codec()],
    ['name', addCodecSizePrefix(getUtf8Codec(), getU32Codec())],
]);

const myToken = {
    amount: 1000000000000000n, // `bigint` or `number` is supported
    decimals: 2,
    name: 'My Token',
};

const myEncodedToken: Uint8Array = structCodec.encode(myToken);
const myDecodedToken = structCodec.decode(myEncodedToken);

myDecodedToken satisfies {
    amount: bigint;
    decimals: number;
    name: string;
};
```

You may only need to encode or decode data, but not both. Importing one or the other allows your optimizing compiler to tree-shake the other implementation away:

```ts
import { Codec, combineCodec, Decoder, Encoder, addDecoderSizePrefix, addEncoderSizePrefix } from '@solana/codecs-core';
import { getStructDecoder, getStructEncoder } from '@solana/codecs-data-structures';
import {
    getU8Decoder,
    getU8Encoder,
    getU32Decoder,
    getU32Encoder,
    getU64Decoder,
    getU64Encoder,
} from '@solana/codecs-numbers';
import { getUtf8Decoder, getUtf8Encoder } from '@solana/codecs-strings';

export type MyToken = {
    amount: bigint;
    decimals: number;
    name: string;
};

export type MyTokenArgs = {
    amount: number | bigint;
    decimals: number;
    name: string;
};

export const getMyTokenEncoder = (): Encoder<MyTokenArgs> =>
    getStructEncoder([
        ['amount', getU64Encoder()],
        ['decimals', getU8Encoder()],
        ['name', addEncoderSizePrefix(getUtf8Encoder(), getU32Encoder())],
    ]);

export const getMyTokenDecoder = (): Decoder<MyToken> =>
    getStructDecoder([
        ['amount', getU64Decoder()],
        ['decimals', getU8Decoder()],
        ['name', addDecoderSizePrefix(getUtf8Decoder(), getU32Decoder())],
    ]);

export const getMyTokenCodec = (): Codec<MyTokenArgs, MyToken> =>
    combineCodec(getMyTokenEncoder(), getMyTokenDecoder());
```

You can read more about codecs in [the official Codec documentation](https://github.com/anza-xyz/kit/blob/main/packages/codecs/README.md).

## Type-Safety

The new library makes use of some advanced TypeScript features, including generic types, conditional types, `Parameters<..>`, `ReturnType<..>` and more.

We’ve described the RPC API in detail so that TypeScript can determine the _exact_ type of the result you will receive from the server given a particular input. Change the type of the input, and you will see the return type reflect that change.

### RPC Types

The RPC methods – both HTTP and subscriptions – are built with multiple overloads and conditional types. The expected HTTP response payload or subscription message format will be reflected in the return type of the function you’re working with when you provide the inputs in your code.

Here’s an example of this in action:

```ts
// Provide one set of parameters, get a certain type
// These parameters resolve to return type:
// {
//     blockhash: Blockhash;
//     blockHeight: bigint;
//     blockTime: UnixTimestamp;
//     parentSlot: bigint;
//     previousBlockhash: Blockhash;
// }
const blockResponse = await rpc
    .getBlock(0n, {
        rewards: false,
        transactionDetails: 'none',
    })
    .send();

// Switch `rewards` to `true`, get `rewards` in the return type
// {
//     /* ... Previous response */
//     rewards: Reward[];
// }
const blockWithRewardsResponse = await rpc
    .getBlock(0n, {
        rewards: true,
        transactionDetails: 'none',
    })
    .send();

// Switch `transactionDetails` to `full`, get `transactions` in the return type
// {
//     /* ... Previous response */
//     transactions: TransactionResponse[];
// }
const blockWithRewardsAndTransactionsResponse = await rpc
    .getBlock(0n, {
        rewards: true,
        transactionDetails: 'full',
    })
    .send();
```

### Catching Compile-Time Bugs with TypeScript

As previously mentioned, the type coverage in Kit allows developers to catch common bugs at compile time, rather than runtime.

In the example below, a transaction message is created and then attempted to be signed without setting the fee payer. This would result in a runtime error from the RPC, but instead you will see a type error from TypeScript as you type:

```ts
const transactionMessage = pipe(createTransactionMessage({ version: 0 }), tx =>
    setTransactionMessageLifetimeUsingBlockhash(recentBlockhash, tx),
);
const signedTransaction = await signTransaction([keyPair], transactionMessage); // ERROR: Property 'feePayer' is missing in type
```

Consider another example where a developer is attempting to send a transaction that has not been fully signed. Again, the TypeScript compiler will throw a type error:

```ts
const transactionMessage = pipe(
    createTransactionMessage({ version: 0 }),
    tx => setTransactionMessageFeePayer(feePayerAddress, tx),
    tx => setTransactionMessageLifetimeUsingBlockhash(recentBlockhash, tx),
);

const signedTransaction = await signTransaction([], transactionMessage);

// Asserts the transaction is a `FullySignedTransaction`
// Throws an error if any signatures are missing!
assertIsFullySignedTransaction(signedTransaction);

await sendAndConfirmTransaction(signedTransaction);
```

Are you building a nonce transaction and forgot to make `AdvanceNonce` the first instruction? That’s a type error:

```ts
const feePayer = await generateKeyPair();
const feePayerAddress = await getAddressFromPublicKey(feePayer.publicKey);

const notNonceTransactionMessage = pipe(createTransactionMessage({ version: 0 }), tx =>
    setTransactionMessageFeePayer(feePayerAddress, tx),
);

notNonceTransactionMessage satisfies TransactionMessageWithDurableNonceLifetime;
// => Property 'lifetimeConstraint' is missing in type

const nonceConfig = {
    nonce: 'nonce' as Nonce,
    nonceAccountAddress: address('5tLU66bxQ35so2bReGcyf3GfMMAAauZdNA1N4uRnKQu4'),
    nonceAuthorityAddress: address('GDhj8paPg8woUzp9n8fj7eAMocN5P7Ej3A7T9F5gotTX'),
};

const stillNotNonceTransactionMessage = {
    lifetimeConstraint: nonceConfig,
    ...notNonceTransactionMessage,
};

stillNotNonceTransactionMessage satisfies TransactionMessageWithDurableNonceLifetime;
// => 'readonly Instruction<string>[]' is not assignable to type 'readonly [AdvanceNonceAccountInstruction<string, string>, ...Instruction<string>[]]'

const validNonceTransactionMessage = pipe(
    createTransactionMessage({ version: 0 }),
    tx => setTransactionMessageFeePayer(feePayerAddress, tx),
    tx => setTransactionMessageLifetimeUsingDurableNonce(nonceConfig, tx), // Adds the instruction!
);

validNonceTransactionMessage satisfies TransactionMessageWithDurableNonceLifetime; // OK
```

The library’s type-checking can even catch you using lamports instead of SOL for a value:

```ts
const airdropAmount = 1n; // SOL
const signature = rpc.requestAirdrop(myAddress, airdropAmount).send();
```

It will force you to cast the numerical value for your airdrop (or transfer, etc.) amount using `lamports()`, which should be a good reminder!

```ts
const airdropAmount = lamports(1000000000n);
const signature = rpc.requestAirdrop(myAddress, airdropAmount).send();
```

## Compatibility Layer

You will have noticed by now that Kit is a complete and total breaking change from the web3.js 1.x line. We want to provide you with a strategy for interacting with web3.js 1.x APIs while building your application using Kit. You need a tool for converting between web3.js 1.x and Kit data types.

The `@solana/compat` library allows for interoperability between functions and class objects from the legacy library - such as `VersionedTransaction`, `PublicKey`, and `Keypair` - and functions and types of the new library - such as `Address`, `Transaction`, and `CryptoKeyPair`.

Here’s how you can use `@solana/compat` to convert from a legacy `PublicKey` to an `Address`:

```ts
import { fromLegacyPublicKey } from '@solana/compat';

const publicKey = new PublicKey('B3piXWBQLLRuk56XG5VihxR4oe2PSsDM8nTF6s1DeVF5');
const address: Address = fromLegacyPublicKey(publicKey);
```

Here’s how to convert from a legacy `Keypair` to a `CryptoKeyPair`:

```ts
import { fromLegacyKeypair } from '@solana/compat';

const keypairLegacy = Keypair.generate();
const cryptoKeyPair: CryptoKeyPair = fromLegacyKeypair(keypair);
```

Here’s how to convert legacy transaction objects to the new library’s transaction types:

```ts
// Note that you can only convert `VersionedTransaction` objects
const modernTransaction = fromVersionedTransaction(classicTransaction);
```

To see more conversions supported by `@solana/compat`, you can check out the package’s [README on GitHub](https://github.com/anza-xyz/kit/blob/main/packages/compat/README.md).

## Program Clients

Writing JavaScript clients for on-chain programs has been done manually up until now. Without an IDL for some of the native programs, this process has been necessarily manual and has resulted in clients that lag behind the actual capabilities of the programs themselves.

We think that program clients should be _generated_ rather than written. Developers should be able to write Rust programs, compile the program code, and generate all of the JavaScript client-side code to interact with the program.

We use [Codama](https://github.com/codama-idl/codama) to represent Solana programs and generate clients for them. This includes a JavaScript client compatible with this library. For instance, here is how you’d construct a transaction message composed of instructions from three different core programs.

```ts
import { appendTransactionMessageInstructions, createTransactionMessage, pipe } from '@solana/kit';
import { getAddMemoInstruction } from '@solana-program/memo';
import { getSetComputeUnitLimitInstruction } from '@solana-program/compute-budget';
import { getTransferSolInstruction } from '@solana-program/system';

const instructions = [
    getSetComputeUnitLimitInstruction({ units: 600_000 }),
    getTransferSolInstruction({ source, destination, amount: 1_000_000_000 }),
    getAddMemoInstruction({ memo: "I'm transferring some SOL!" }),
];

// Creates a V0 transaction message with 3 instructions inside.
const transactionMessage = pipe(createTransactionMessage({ version: 0 }), tx =>
    appendTransactionMessageInstructions(instructions, tx),
);
```

As you can see, each program now generates its own library allowing you to cherry-pick your dependencies.

Note that asynchronous versions may be available for some instructions which allows them to resolve more inputs on your behalf — such as PDA derivation. For instance, the `CreateLookupTable` instruction offers an asynchronous builder that derives the `address` account and the `bump` argument for us.

```ts
const rpc = createSolanaRpc('http://127.0.0.1:8899');
const [authority, recentSlot] = await Promise.all([
    generateKeyPairSigner(),
    rpc.getSlot({ commitment: 'finalized' }).send(),
]);

const instruction = await getCreateLookupTableInstructionAsync({
    authority,
    recentSlot,
});
```

Alternatively, you may use the synchronous builder if you already have all the required inputs at hand.

```ts
const [address, bump] = await findAddressLookupTablePda({
    authority: authority.address,
    recentSlot,
});

const instruction = getCreateLookupTableInstruction({
    address,
    authority,
    bump,
    recentSlot,
});
```

On top of instruction builders, these clients offer a variety of utilities such as:

- Instruction codecs — e.g. `getTransferSolInstructionDataCodec`.
- Account types — e.g. `AddressLookupTable`.
- Account codecs — e.g. `getAddressLookupTableAccountDataCodec`.
- Account helpers — e.g. `fetchAddressLookupTable`.
- PDA helpers — e.g. `findAddressLookupTablePda`, `fetchAddressLookupTableFromSeeds`.
- Defined types and their codecs — e.g. `NonceState`, `getNonceStateCodec`.
- Program helpers — e.g. `SYSTEM_PROGRAM_ADDRESS`, `SystemAccount` enum, `identifySystemInstruction`.
- And much more!

Here’s another example that fetches an `AddressLookupTable` PDA from its seeds.

```ts
const account = await fetchAddressLookupTableFromSeeds(rpc, {
    authority: authority.address,
    recentSlot,
});

account.address; // Address
account.lamports; // Lamports
account.data.addresses; // Address[]
account.data.authority; // Some<Address>
account.data.deactivationSlot; // Slot
account.data.lastExtendedSlot; // Slot
account.data.lastExtendedSlotStartIndex; // number
```

### How Does This Work?

All of this code is 100% auto-generated by Codama from a tree of standardized nodes that represent our programs. It contains obvious nodes such as `AccountNode` but also more specified nodes such as `ConditionalValueNode` that allows us to resolve account or argument default values conditionally.

Codama allows us to hydrate our tree of nodes from IDLs which are typically generated by program frameworks such as [Anchor](https://github.com/coral-xyz/anchor) or [Shank](https://github.com/metaplex-foundation/shank). Additionally, visitors can be used on our nodes to expand the knowledge of our programs since the IDL itself doesn’t yet contain that level of information. Finally, special visitors called ‘renderers’ visit our tree to generate clients such as this JavaScript client.

Currently, there is one other renderer that generates Rust clients but this is only the beginning. In the future, you can expect renderers for auto-generated Python clients, documentation, CLIs, etc.

## Create Solana Program

We believe the whole ecosystem could benefit from generated program clients. That’s why we introduced a new NPM binary that allows you to create your Solana program — and generate clients for it — in no time. Simply run the following and follow the prompts to get started.

```sh
pnpm create solana-program
```

This [`create-solana-program`](https://github.com/solana-program/create-solana-program) installer will create a new repository including:

- An example program using the framework of your choice (Anchor coming soon).
- Generated clients for any of the selected clients.
- A set of scripts that allows you to:
    - Start a local validator including all programs and accounts you depend on.
    - Build, lint and test your programs.
    - Generate IDLs from your programs.
    - Generate clients from the generated IDLs.
    - Build and test each of your clients.
- GitHub Actions pipelines to test your program, test your clients, and even manually publish new packages or crates for your clients. (Coming soon).

When selecting the JavaScript client, you will get a fully generated library compatible with Kit much like the `@solana-program` packages showcased above.

## GraphQL

Though not directly related to web3.js, we wanted to hijack your attention to show you something else that we’re working on, of particular interest to frontend developers. It’s a new API for interacting with the RPC: a GraphQL API.

The `@solana/rpc-graphql` package can be used to make GraphQL queries to Solana RPC endpoints, using the same transports described above (including any customizations).

Here’s an example of retrieving account data with GraphQL:

```ts
const source = `
    query myQuery($address: String!) {
        account(address: $address) {
            dataBase58: data(encoding: BASE_58)
            dataBase64: data(encoding: BASE_64)
            lamports
        }
    }
`;

const variableValues = {
    address: 'AyGCwnwxQMCqaU4ixReHt8h5W4dwmxU7eM3BEQBdWVca',
};

const result = await rpcGraphQL.query(source, variableValues);

expect(result).toMatchObject({
    data: {
        account: {
            dataBase58: '2Uw1bpnsXxu3e',
            dataBase64: 'dGVzdCBkYXRh',
            lamports: 10290815n,
        },
    },
});
```

Using GraphQL allows developers to only specify which fields they _actually_ need, and do away with the rest of the response.

However, GraphQL is also extremely powerful for **nesting queries**, which can be particularly useful if you want to, say, get the **sum** of every lamports balance of every **owner of the owner** of each token account, while discarding any mint accounts.

```ts
const source = `
    query getLamportsOfOwnersOfOwnersOfTokenAccounts {
        programAccounts(programAddress: "TokenkegQfeZyiNwAJbNbGKPFXCWuBvf9Ss623VQ5DA") {
            ... on TokenAccount {
                owner {
                    ownerProgram {
                        lamports
                    }
                }
            }
        }
    }
`;

const result = await rpcGraphQL.query(source);

const sumOfAllLamportsOfOwnersOfOwnersOfTokenAccounts = result
    .map(o => o.account.owner.ownerProgram.lamports)
    .reduce((acc, lamports) => acc + lamports, 0);
```

The new GraphQL package supports this same style of nested querying on transactions and blocks.

```ts
const source = `
    query myQuery($signature: String!, $commitment: Commitment) {
        transaction(signature: $signature, commitment: $commitment) {
            message {
                instructions {
                    ... on CreateAccountInstruction {
                        lamports
                        programId
                        space
                    }
                }
            }
        }
    }
`;

const variableValues = {
    signature: '63zkpxATgAwXRGFQZPDESTw2m4uZQ99sX338ibgKtTcgG6v34E3MSS3zckCwJHrimS71cvei6h1Bn1K1De53BNWC',
    commitment: 'confirmed',
};

const result = await rpcGraphQL.query(source, variableValues);

expect(result).toMatchObject({
    data: {
        transaction: {
            message: {
                instructions: expect.arrayContaining([
                    {
                        lamports: expect.any(BigInt),
                        programId: '11111111111111111111111111111111',
                        space: expect.any(BigInt),
                    },
                ]),
            },
        },
    },
});
```

See more in the package’s [README on GitHub](https://github.com/anza-xyz/kit/tree/main/packages/rpc-graphql).

## Development

You can see all development of this library and associated GraphQL tooling in the Kit repository on GitHub.

- https://github.com/anza-xyz/kit

You can follow along with program client generator development in the `@solana-program` org and the `@codama-idl/codama` repository.

- https://github.com/solana-program/
- https://github.com/codama-idl/codama

Solana Labs develops these tools in public, as open source. We encourage any and all developers who would like to work on these tools to contribute to the codebase.

## Thank you

We’re grateful that you have read this far. If you are interested in migrating an existing application to Kit to take advantage of some of the benefits we’ve demonstrated, we want to give you some direct support. Reach out to [@steveluscher](https://t.me/steveluscher/) on Telegram to start a conversation.

``n
---

## 17. solana-web3.js
- **URL:** https://github.com/devtechedge/solana-web3.js
- **Language:** Not specified
- **Topics:** None
- **Description:** Solana JavaScript SDK


### README.md

`markdown
[![npm][npm-image]][npm-url]
[![npm-downloads][npm-downloads-image]][npm-url]
[![semantic-release][semantic-release-image]][semantic-release-url]
<br />
[![code-style-prettier][code-style-prettier-image]][code-style-prettier-url]

[code-style-prettier-image]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
[code-style-prettier-url]: https://github.com/prettier/prettier
[npm-downloads-image]: https://img.shields.io/npm/dm/@solana/web3.js.svg?style=flat
[npm-image]: https://img.shields.io/npm/v/@solana/web3.js.svg?style=flat
[npm-url]: https://www.npmjs.com/package/@solana/web3.js
[semantic-release-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]: https://github.com/semantic-release/semantic-release

> [!NOTE]
> This is the maintenance branch for the 1.x line of `@solana/web3.js`. You can find the successor to this library here: [`@solana/kit`](https://l.anza.xyz/s/js-sdk-repo).

# Solana JavaScript SDK (v1.x)

Use this to interact with accounts and programs on the Solana network through the Solana [JSON RPC API](https://solana.com/docs/rpc).

## Installation

### For use in Node.js or a web application

```
$ npm install --save @solana/web3.js
```

### For use in a browser, without a build system

```html
<!-- Development (un-minified) -->
<script src="https://unpkg.com/@solana/web3.js@latest/lib/index.iife.js"></script>

<!-- Production (minified) -->
<script src="https://unpkg.com/@solana/web3.js@latest/lib/index.iife.min.js"></script>
```

## Documentation and examples

- [The Solana Cookbook](https://solanacookbook.com/) has extensive task-based documentation using this library.
- For more detail on individual functions, see the [latest API Documentation](https://solana-foundation.github.io/solana-web3.js)

## Getting help

Have a question or a problem? Check the [Solana Stack Exchange](https://solana.stackexchange.com) to see if anyone else is having the same one. If not, [post a new question](https://solana.stackexchange.com/questions/ask).

Include:

- A detailed description of what you're trying to achieve
- Source code, if possible
- The text of any errors you encountered, with stacktraces if available

## Compatibility

This library requires a JavaScript runtime that supports [`BigInt`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt) and the [exponentiation operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation). Both are supported in the following runtimes:

- Browsers, by [release date](https://caniuse.com/bigint):
  - Chrome: May 2018
  - Firefox: July 2019
  - Safari: September 2020
  - Mobile Safari: September 2020
  - Edge: January 2020
  - Opera: June 2018
  - Samsung Internet: April 2019
- Runtimes, [by version](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt):
  - Deno: >=1.0
  - Node: >=10.4.0
- React Native:
  - \>=0.7.0 using the [Hermes](https://reactnative.dev/blog/2022/07/08/hermes-as-the-default) engine ([integration guide](https://solanacookbook.com/integrations/react-native.html#how-to-use-solana-web3-js-in-a-react-native-app)):

## Development environment setup

### Testing

#### Unit tests

To run the full suite of unit tests, execute the following in the root:

```shell
$ npm test
```

#### Integration tests

Integration tests require a validator client running on your machine.

To install a test validator:

```shell
$ npm run test:live-with-test-validator:setup
```

To start the test validator and run all of the integration tests in live mode:

```shell
$ cd packages/library-legacy
$ npm run test:live-with-test-validator
```

## Contributing

If you found a bug or would like to request a feature, please [file an issue](https://github.com/solana-foundation/solana-web3.js/issues/new). If, based on the discussion on an issue you would like to offer a code change, please make a [pull request](https://github.com/solana-foundation/solana-web3.js/compare). If neither of these describes what you would like to contribute, read the [getting help](#getting-help) section above.

## Disclaimer

All claims, content, designs, algorithms, estimates, roadmaps,
specifications, and performance measurements described in this project
are done with the Solana Foundation's ("SF") best efforts. It is up to
the reader to check and validate their accuracy and truthfulness.
Furthermore nothing in this project constitutes a solicitation for
investment.

Any content produced by SF or developer resources that SF provides, are
for educational and inspiration purposes only. SF does not encourage,
induce or sanction the deployment, integration or use of any such
applications (including the code comprising the Solana blockchain
protocol) in violation of applicable laws or regulations and hereby
prohibits any such deployment, integration or use. This includes use of
any such applications by the reader (a) in violation of export control
or sanctions laws of the United States or any other applicable
jurisdiction, (b) if the reader is located in or ordinarily resident in
a country or territory subject to comprehensive sanctions administered
by the U.S. Office of Foreign Assets Control (OFAC), or (c) if the
reader is or is working on behalf of a Specially Designated National
(SDN) or a person subject to similar blocking or denied party
prohibitions.

The reader should be aware that U.S. export control and sanctions laws
prohibit U.S. persons (and other persons that are subject to such laws)
from transacting with persons in certain countries and territories or
that are on the SDN list. As a project based primarily on open-source
software, it is possible that such sanctioned persons may nevertheless
bypass prohibitions, obtain the code comprising the Solana blockchain
protocol (or other project code or applications) and deploy, integrate,
or otherwise use it. Accordingly, there is a risk to individuals that
other persons using the Solana blockchain protocol may be sanctioned
persons and that transactions with such persons would be a violation of
U.S. export controls and sanctions law. This risk applies to
individuals, organizations, and other ecosystem participants that
deploy, integrate, or use the Solana blockchain protocol code directly
(e.g., as a node operator), and individuals that transact on the Solana
blockchain through light clients, third party interfaces, and/or wallet
software.

``n
---

## 18. wagmi
- **URL:** https://github.com/devtechedge/wagmi
- **Language:** Not specified
- **Topics:** None
- **Description:** Reactive primitives for Ethereum apps


### README.md

*No standard README.md found.*

---

## 19. regulatory_compliance
- **URL:** https://github.com/devtechedge/regulatory_compliance
- **Language:** Python
- **Topics:** compliance, docker, fastapi, hitl, mica, nextjs, postgresql, rag, typescript, vara, vasp, web3
- **Description:** HITL Web3 compliance copilot for VASP licensing reviewers. Maps project packs onto MiCA and VARA with retrieval-bounded findings, article citations, hallucination flags, split-screen accept/edit/reject, and markdown gap exports. Next.js, FastAPI, Postgres. Live Vercel demo-mode (seeded Aurum Custody, no API key). Compose is the full backend.


### README.md

`markdown
﻿# RegTrace-AI

HITL Web3 compliance copilot for VASP licensing: source-traced MiCA / VARA mapping, hallucination flags, and a human review dashboard.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://regtrace-ai.vercel.app)
[![CI](https://github.com/devtechedge/regulatory_compliance/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/regulatory_compliance/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.111-teal?logo=fastapi)](https://fastapi.tiangolo.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

[https://regtrace-ai.vercel.app](https://regtrace-ai.vercel.app)

> **Status:** Vercel demo-mode (Next.js API routes, seeded Aurum Custody, HITL reviews in-memory / reset on cold start). Local Compose remains the full FastAPI + Postgres path. Deterministic retrieval-bounded generator; no API key. Findings are not legal advice. CI on `main` is green (pytest, typecheck, Playwright).
>
> **Demo password (HITL / eval mutations):** `Demo123!` — sent as `x-demo-token` (see [SECURITY.md](SECURITY.md)). Public GET of the seeded pack stays open.

Vercel project Root Directory is `frontend` (Next.js App Router demo API; FastAPI is not part of the Vercel build).

### Demo auth (mutations)

| Item | Value |
|------|--------|
| Header | `x-demo-token` |
| Default password | `Demo123!` |
| Env override | `DEMO_TOKEN` (server), `NEXT_PUBLIC_DEMO_TOKEN` or `localStorage.regtrace_demo_token` (client) |
| Gated routes | `POST /api/projects/{id}/evaluate`, `POST /api/findings/{id}/review` |

Threat model: [SECURITY.md](SECURITY.md).

```bash
cp .env.example .env
docker compose up --build
```

Then http://localhost:3000 (web) and http://localhost:8000/docs (API).

---

## Screenshots

| Overview | HITL workspace |
|----------|----------------|
| ![Dashboard](docs/screenshots/01-overview.png) | ![Split-screen review](docs/screenshots/02-hitl-workspace.png) |

| Gap analysis |
|--------|
| ![Licensing readiness](docs/screenshots/03-gap-analysis.png) |

---

## Features

- HITL accept/edit/reject with logged eval cases
- Source-traced MiCA article and VARA rule citations
- Hallucination flags via citation validator
- 12 MiCA + 12 VARA VASP licensing modules
- Markdown gap export for the licence file

This is compliance engineering, not a smart-contract auditor.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js App Router, TypeScript, Tailwind |
| API | FastAPI, SQLAlchemy 2, pydantic v2 (Compose / local); Next.js App Router demo routes on Vercel |
| Retrieval | BM25 + TF-IDF (no embedding API) |
| Data | Postgres in Compose; SQLite locally; seeded demo JSON on Vercel |
| Generator | Deterministic writer; optional OpenAI |
| Hosting | Vercel demo-mode (same-origin `/api`); Docker Compose for FastAPI + Postgres |

---

## Quick Start

### Vercel demo-mode (same-origin `/api`)

Leave `NEXT_PUBLIC_API_URL` empty. The Next.js app serves seeded Aurum Custody, framework JSON, and a snapshot evaluation from `frontend/app/api/*`. HITL reviews are in-memory and reset on cold start.

### Docker Compose (full FastAPI + Postgres)

Copy `.env.example` to `.env`, set `NEXT_PUBLIC_API_URL=http://localhost:8000`, then start postgres, api, and web with compose.

- API: http://localhost:8000/docs and GET /api/health
- Web: http://localhost:3000
- Postgres: localhost:5432 (user/password/db: regtrace)

No OpenAI key required.

### Local (no Docker)

Postgres is optional. The API defaults to SQLite if DATABASE_URL is unset.

From `backend/`, create a virtualenv, install the Python requirements file, export `DATA_DIR=../frontend/data` and a sqlite `DATABASE_URL`, then start uvicorn on `app.main:app` port 8000.

From `frontend/`, install Node dependencies. Leave `NEXT_PUBLIC_API_URL` empty to use the Next demo API, or export `NEXT_PUBLIC_API_URL=http://localhost:8000` to use FastAPI, then start the Next.js dev server.

Seed runs on API startup. To re-seed after wiping the DB, from backend/: `python -m app.seed`.

### Smoke

```
GET  /api/health
GET  /api/frameworks
POST /api/projects/aurum-custody/evaluate   {"frameworks":["MiCA","VARA"]}
```

## Tests

pytest backend/tests; frontend typecheck; Playwright from frontend/.

## License

MIT. See [LICENSE](LICENSE).


``n
---

## 20. veritas-engine
- **URL:** https://github.com/devtechedge/veritas-engine
- **Language:** TypeScript
- **Topics:** ai-research-agent, gemini-api, langchain, langgraph-js, multi-agent-systems, nextjs, portfolio, serverless-agent, sse, tavily-api, typescript, vercel
- **Description:** Self-correcting multi-agent research engine for technical briefs. Planner drafts queries, Tavily retrieves in parallel, a critic grades 1-10 and loops until >=8 or max depth, then a synthesizer writes Markdown. Next.js 14, LangGraph.js, Gemini 2.5 Flash, SSE. Public Vercel is Demo mode (simulated). Live needs GEMINI_API_KEY and TAVILY_API_KEY. MIT.


### README.md

`markdown
# Veritas Engine

Self-correcting multi-agent research console. Plan queries, retrieve in parallel, grade the evidence, loop until the critic passes, then synthesize a Markdown brief.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://veritas-engine-woad.vercel.app/)
[![CI](https://github.com/devtechedge/veritas-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/veritas-engine/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![LangGraph](https://img.shields.io/badge/LangGraph.js-1-1C3C3C)](https://js.langchain.com/docs/langgraph)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://veritas-engine-woad.vercel.app/**

> **Status:** The public site defaults to **Demo** mode (simulated). Keys alone do not enable spend — set `LIVE_MODE=true` (optional `PUBLIC_RUN_TOKEN` / `x-run-token`). There is no login.

This is the **only** public repo for the project.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="Veritas Engine" width="800">
</p>

| Console | Cycle |
|---------|-------|
| ![Dark orchestration panel and graph](docs/screenshots/01-overview.png) | ![Live logstream and graph during a demo run](docs/screenshots/02-cycle-running.png) |

| Brief | Quality audit |
|-------|----------------|
| ![Synthesized Markdown brief](docs/screenshots/03-synthesized-brief.png) | ![Critic score ring and auditor notes](docs/screenshots/04-quality-audit.png) |

---

## Features

- LangGraph.js cycle: **Planner → Retrieval → Critic → (loop or) Synthesizer**
- Critic scores 1–10 and reroutes below 8 until max iteration depth
- Parallel Tavily searches on Live; mock hits on Demo
- SSE stream of node updates into the logstream and graph visualizer
- Custom zero-dependency Markdown renderer (headings, tables, lists, code)
- Copy brief or export `.md`
- Dark / light console; Demo / Live toggle

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 14 App Router, React 18, TypeScript, Tailwind 3 |
| Agents | LangGraph.js + LangChain.js (`Annotation.Root`) |
| LLM (Live) | Gemini 2.5 Flash via `@langchain/google-genai` |
| Search (Live) | Tavily Search API |
| Streaming | Server-Sent Events from `POST /api/research` |
| Data on Vercel | Demo repository (simulated retrieval + canned brief) |
| Auth | None |
| Hosting | Vercel |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Architecture

```
Start → Planner → Retrieval (parallel) → Critic
                      ↑                    │
                      └── score < 8 ───────┤
                                           ▼
                                    Synthesizer → Markdown UI
```

---

## Quick Start

```bash
git clone https://github.com/devtechedge/veritas-engine.git
cd veritas-engine
npm install
cp .env.example .env.local
npm run dev
```

Open **http://localhost:3000**. Demo mode runs without keys.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: **no login**. Demo is forced unless `LIVE_MODE=true` (and optional run token). Headers, origin checks, rate limits: see SECURITY.md. Live keys stay on the server.

Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 21. luxe-tracker
- **URL:** https://github.com/devtechedge/luxe-tracker
- **Language:** TypeScript
- **Topics:** arbitrage, client-side, dashboard, editorial-ui, fashion-tech, luxury-retail, nextjs, portfolio, price-disparity, recharts, tailwindcss, typescript
- **Description:** Luxe Tracker is a high-fashion global launch and price-disparity dashboard for Prada, Gucci, Balenciaga, Louis Vuitton, and Versace. 17 intelligence panels, 5 maisons, 5 regions, 11k+ price rows: arbitrage, FX hedge, landed-cost optimizer, brand pulse. Next.js 15, Tailwind 4, Recharts. Pure client-side deterministic snapshot—no env vars, no backend


### README.md

`markdown
# Luxe Tracker

High-fashion global launch & price disparity tracker for Prada, Gucci, Balenciaga, Louis Vuitton and Versace. 17 intelligence panels across 5 regions with arbitrage detection, FX hedge calculator, landed-cost optimizer and brand pulse.

![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-06b6d4?logo=tailwindcss)
![Recharts](https://img.shields.io/badge/Recharts-2-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Live Demo

**https://luxe-disparity-tracker.vercel.app/**

Pure client-side deterministic snapshot (seeded PRNG). Zero environment variables, always green. Data shape matches a full Prisma + Supabase backend but runs entirely in the browser.

## Screenshots

### Overview — Live Telemetry
![Overview](docs/screenshots/01-overview.png)

### Price Disparity Matrix
![Price Matrix](docs/screenshots/02-price-matrix.png)

### Arbitrage Opportunity Finder
![Arbitrage](docs/screenshots/03-arbitrage.png)

### Competitive Brand Comparison
![Competitive Matrix](docs/screenshots/04-competitive-matrix.png)

### Sustainability Scores
![Sustainability](docs/screenshots/05-sustainability.png)

## Features

- **Live Telemetry Overview** — editorial hero number, 8-column KPI strip, FX rates, region & brand markup charts
- **Price Disparity Matrix** — sortable 5-region matrix with EUR baseline, duties, taxes and landed cost
- **Launch Calendar** — 90-day rolling grid of regional drops with status badges
- **Arbitrage Opportunity Detector** — net profit after duties, taxes and shipping per region pair
- **Landed-Cost Optimizer** — cheapest buying region recommendation per SKU
- **Price History & Anomaly Flags** — 90-day time series with >3 % daily move detection
- **FX Volatility Hedge Calculator** — 90-day FX history + what-if revaluation
- **Brand Pulse Radar** — 5-dimensional prestige / hype / scarcity / FX risk / resale score
- **Stock-Out Risk Index** — sell-out probability from inventory × hype × days-to-launch
- **Competitive Matrix, Runway Tracker, VIP Tier Simulator, Sustainability, Trend Forecast, Drop Queue, Watchlist & Alerts**

## Tech Stack

| Layer | Choice |
|-------|--------|
| Framework | Next.js 15 (App Router) |
| Language | TypeScript 5 |
| Styling | Tailwind CSS 4 (CSS-first `@theme`) |
| Charts | Recharts 2 |
| Icons | Lucide React |
| Theme | Custom dark / light with zero-FOUC bootstrap |
| Data | Deterministic in-browser snapshot (mulberry32 PRNG) |

## Quick Start

```bash
git clone https://github.com/devtechedge/luxe-tracker.git
cd luxe-tracker
bun install          # or: npm install
bun run dev          # → http://localhost:3000
```

No environment variables required.

## Tests & CI

```bash
bun test              # unit: snapshot counts, telemetry, price-history key split, VIP, validation
bun run typecheck
bun run test:e2e      # Playwright Chromium — overview, Price Matrix nav, theme toggle
```

GitHub Actions runs unit + typecheck + e2e on every push to `main`. Dependabot opens weekly PRs for patch/minor npm and Actions updates (majors ignored).

## Security

See [SECURITY.md](./SECURITY.md). Public demo has no backend, no env vars, and no auth boundary. Watchlist / alerts / spend in `localStorage` are allow-listed on read.

## Architecture

Single Vercel deployment. All analytics are pure functions over a seeded in-memory snapshot (`src/lib/data-snapshot.ts` + `src/lib/analytics.ts`). Watchlist and alerts persist in `localStorage`. Dark/light theme is controlled by a no-flash inline script + CSS variables.

The same data shape was previously backed by Prisma + Supabase; the client-side version keeps the full panel surface while guaranteeing a permanent green live demo.

## License

MIT License. See [LICENSE](./LICENSE) for details.

---

Brand names and prices are synthetic and used for demonstration only. Trademarks belong to their respective owners.

``n
---

## 22. aarop
- **URL:** https://github.com/devtechedge/aarop
- **Language:** TypeScript
- **Topics:** agentic-ai, agentic-loop, ai-agents, llm, machine-learning, multi-agent-systems, nextjs, observability, orchestration, python, state-machine, typescript, vercel
- **Description:** AAROP is a multi-agent system on an explicit Perceive→Plan→Act→Observe→Reflect→Adapt loop: orchestration, self-verification, resilient recovery, bounded autonomy, replayable traces. Python core with 24 tests and 99% coverage plus a live Next.js demo. Public Vercel is a client-side TypeScript port with a deterministic mock provider—no API keys. MIT.


### README.md

`markdown
# 🧠 AAROP — Autonomous Agentic Reasoning & Orchestration Platform

> A reference implementation of a **multi-agent AI system built on agentic-loop engineering principles**: `Perceive → Plan → Act → Observe → Reflect → Adapt`. The loop is an **explicit, inspectable state machine** — not a hidden prompt chain — with bounded autonomy, self-verification, durable checkpointing, and full trace replay.

<p align="left">
  <a href="https://aarop.vercel.app/"><img alt="live demo" src="https://img.shields.io/badge/live%20demo-online-brightgreen"></a>
  <a href="https://github.com/devtechedge/aarop/actions"><img alt="ci" src="https://github.com/devtechedge/aarop/actions/workflows/ci.yml/badge.svg"></a>
  <img alt="python" src="https://img.shields.io/badge/python-3.10%2B-blue">
  <img alt="next" src="https://img.shields.io/badge/Next.js-14-black">
  <img alt="tests" src="https://img.shields.io/badge/tests-24%20passing-brightgreen">
  <img alt="coverage" src="https://img.shields.io/badge/coverage-99%25-brightgreen">
  <a href="LICENSE"><img alt="license" src="https://img.shields.io/badge/license-MIT-black"></a>
</p>

### 🌐 [**▶ Try the Live Demo →**](https://aarop.vercel.app/)
Watch an objective flow through the full agentic loop in real time — no install, no API keys, no sign-up.

> **Live demo status:** 100% client-side TypeScript port with a deterministic mock provider — always online on Vercel. The Python `core/` engine runs offline with the same loop semantics (24 tests, 99% coverage).

**Built by [Devayan Mandal](https://github.com/devtechedge)** — AI / ML Engineer.

---

## Screenshots

| Live agentic loop | Multi-agent orchestration |
|-------------------|---------------------------|
| ![Agentic loop](docs/screenshots/01-agentic-loop.png) | ![Multi-agent](docs/screenshots/02-multi-agent.png) |

| System architecture + engineering rigor |
|-----------------------------------------|
| ![Architecture](docs/screenshots/03-architecture.png) |

---

## What's in this repository

| Path | What it is |
|---|---|
| **[`core/`](core/)** | The Python reference engine — the agentic loop, agents, tool registry, memory, model router, observability. **24 tests, 99% coverage. Runs offline, no API keys.** |
| **[`web-demo/`](web-demo/)** | A **Next.js live demo** ([aarop.vercel.app](https://aarop.vercel.app/)) that animates the full agentic loop in the browser. |
| **[`docs/AAROP_Case_Study.pdf`](docs/AAROP_Case_Study.pdf)** | A polished 4-page case study (problem → architecture → results → ADRs). |
| **[`core/docs/ARCHITECTURE.md`](core/docs/ARCHITECTURE.md)** | C4 diagrams, production reference stack, and 5 ADRs. |
| **[`core/docs/PROJECT_SPEC.md`](core/docs/PROJECT_SPEC.md)** | The full chief-architect-level system specification. |

## The Agentic Loop

```
PERCEIVE → PLAN → ACT → OBSERVE → REFLECT ──accept──► DONE
   ▲                                  │
   └──────────── ADAPT ◄──────reject──┘   (budget exhausted → ESCALATE)
```

| Phase | Responsibility |
|---|---|
| **Perceive** | Normalize input + retrieve relevant context / memory (RAG) |
| **Plan** | Build a cost-aware hierarchical task graph |
| **Act** | Invoke schema-validated, sandboxed tools / sub-agents |
| **Observe** | Capture structured results + detect anomalies |
| **Reflect** | Critic verifies output against acceptance criteria |
| **Adapt** | Replan / retry with backoff / escalate to a human |

Every phase transition emits a structured trace event, so any run is fully reconstructable and replayable. Every run respects step / cost / time budgets and escalates instead of looping forever.

## Repository layout

```
aarop/
├── core/                       # Python reference engine (runs offline, 99% tested)
│   ├── src/aarop/
│   │   ├── core/loop.py        # agentic loop state machine + Budget guardrails
│   │   ├── agents/agents.py    # Planner · Actor · Verifier (critic)
│   │   ├── tools/registry.py   # schema-validated tools, scopes, circuit breaker
│   │   ├── memory/store.py     # working / episodic / semantic memory + RAG
│   │   ├── routing/            # cost-aware model router
│   │   └── observability/      # structured tracing + replay
│   ├── examples/run_demo.py
│   ├── tests/test_loop.py
│   └── docs/                   # ARCHITECTURE.md, PROJECT_SPEC.md
├── web-demo/                   # Next.js 14 live demo (Vercel)
│   ├── app/
│   ├── lib/aarop.ts            # TS port + node:test helpers
│   ├── e2e/                    # Playwright Chromium smokes
│   └── public/favicon.svg
├── docs/
│   ├── AAROP_Case_Study.pdf
│   └── screenshots/
├── SECURITY.md
├── LICENSE
└── README.md
```

## Quickstart

**Core engine (Python):**
```bash
cd core
pip install -e ".[dev]"
python examples/run_demo.py --objective "calculate 21*2 + 8" --verbose
pytest --cov=aarop          # 24 passed · 99% coverage
```

**Live demo (Next.js):**
```bash
cd web-demo
npm ci
npm test                    # node:test helpers (calculator, planner, loop)
npm run typecheck
npm run dev                 # http://localhost:3000
```

## Architecture & engineering rigor

- **Explicit loop state machine** — observable, replayable, crash-recoverable
- **Bounded autonomy** — step / cost / time budgets with human escalation
- **Self-verification** — a critic agent gates every result before commit
- **Resilient tooling** — schema-validated, permission-scoped, retries + circuit breaker + audit log
- **Cost-aware model routing** — cloud + self-hosted, pluggable
- **Observability** — structured trace per run (OpenTelemetry-shaped)
- **99% test coverage** on core orchestration; CI across Python 3.10–3.12, plus web unit tests, `tsc --noEmit`, and Playwright smokes

See **[`core/docs/ARCHITECTURE.md`](core/docs/ARCHITECTURE.md)** for C4 diagrams, the production reference stack (Temporal, FastAPI, pgvector, vLLM, Kubernetes, OpenTelemetry), and **5 Architecture Decision Records**.

## Live demo

The [`web-demo/`](web-demo/) ports the exact loop logic to TypeScript and runs **100% client-side** with a deterministic mock provider — instant, free, and always online. Deployed on Vercel: **[aarop.vercel.app](https://aarop.vercel.app/)**. See [`web-demo/README.md`](web-demo/README.md) for deploy steps.

Threat model for both surfaces: **[`SECURITY.md`](SECURITY.md)**.

## Roadmap

- [ ] Pluggable real LLM provider (OpenAI / Anthropic / self-hosted vLLM)
- [ ] Persistent memory backend (pgvector / Qdrant) + cross-encoder reranker
- [ ] Durable workflow execution via Temporal
- [ ] OpenTelemetry exporter + Grafana dashboards
- [ ] "Bring your own API key" toggle in the live demo

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Issues and PRs welcome.

## License

MIT © 2026 Devayan Mandal — see [`LICENSE`](LICENSE).

``n
---

## 23. notion-clone
- **URL:** https://github.com/devtechedge/notion-clone
- **Language:** HTML
- **Topics:** animation, app-router, component-architecture, css, frontend-architecture, frontend-engineering, frontend-testing, github-actions, html, lighthouse, nextjs, pixel-perfect, playwright, react, rendering, responsive-design, typescript, ui-engineering, visual-regression, web-performance
- **Description:** Pixel-perfect Next.js App Router recreation of the Notion marketing homepage. Source-backed DOM, CSS, fonts, and inline artwork from the original capture, not a restyle. Playwright visual QA and pixel-diff overlays. TypeScript, React 18, Lighthouse. Live on Vercel as a visual engineering exercise; no Notion auth, no database, no editor backend. MIT


### README.md

`markdown
# Notion Homepage Clone

<p align="center">
  <strong>A source-backed, pixel-focused recreation of the Notion homepage.</strong>
</p>

<p align="center">
  <a href="https://notion-clone-devtechedge1.vercel.app/">Live demo →</a>
</p>

<p align="center">
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-14.2.30-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js 14.2.30"></a>
  <a href="https://notion-clone-devtechedge1.vercel.app/"><img src="https://img.shields.io/badge/Vercel-production-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel production deployment"></a>
  <a href="https://github.com/devtechedge/notion-clone/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/devtechedge/notion-clone/ci.yml?style=flat-square&label=build" alt="Build status"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-2ea44f?style=flat-square" alt="MIT license"></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-20%2B-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js 20 or newer"></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-18.3.1-149eca?style=flat-square&logo=react&logoColor=white" alt="React 18.3.1"></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5.5.4-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript 5.5.4"></a>
  <a href="https://github.com/devtechedge/notion-clone/stargazers"><img src="https://img.shields.io/github/stars/devtechedge/notion-clone?style=flat-square" alt="GitHub stars"></a>
  <a href="https://github.com/devtechedge/notion-clone/network/members"><img src="https://img.shields.io/github/forks/devtechedge/notion-clone?style=flat-square" alt="GitHub forks"></a>
  <a href="https://github.com/devtechedge/notion-clone/commits/main"><img src="https://img.shields.io/github/last-commit/devtechedge/notion-clone?style=flat-square" alt="Last commit"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/devtechedge/notion-clone?style=flat-square" alt="MIT license"></a>
  <img src="https://img.shields.io/github/repo-size/devtechedge/notion-clone?style=flat-square" alt="Repository size">
</p>

<p align="center">
  <img src="./docs/screenshots/desktop-reference.png" alt="Notion homepage reference preview" width="920">
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#getting-started">Getting started</a> ·
  <a href="#visual-qa">Visual QA</a> ·
  <a href="#roadmap">Roadmap</a>
</p>

## Overview

This repository is a high-fidelity recreation of the supplied Notion homepage
reference. It exists as a visual engineering exercise: the goal is to preserve
the original page’s coordinates, typography, artwork, spacing, and responsive
behavior rather than reinterpret the design.

The supplied `reference.html` is treated as the visual source of truth. Its
captured DOM, CSS, inline artwork, SVGs, fonts, and design tokens are retained
so the result stays source-backed and reproducible.

## Key Features

| Area | What is included |
| --- | --- |
| Hero | Headline, Build pill, avatar rail, artwork, floating illustrations, and CTAs |
| Navigation | Desktop navigation, product links, login, and primary action |
| Logo wall | Trusted-by statement and company logo arrangement |
| Bento cards | Source artwork for meetings, dashboards, agents, and quick links |
| Testimonials | Gradient quote cards, attribution, and statistics strip |
| CTA | Get-started section with matching actions and spacing |
| Footer | Brand block, language selector, resource columns, and legal details |
| Responsive layout | Reference-driven behavior across viewport sizes |
| Source-backed rendering | Supplied DOM and inline assets preserved instead of redrawn |
| Deterministic image loading | Native eager loading and synchronous decoding for Bento artwork |
| Pixel verification | Full-page captures, overlays, and difference images |
| Visual QA | Chromium checks at a controlled desktop viewport |

## Technology Stack

| Layer | Choice |
| --- | --- |
| Framework | Next.js 14 App Router |
| UI runtime | React 18 |
| Language | TypeScript |
| Styling | Captured reference CSS with CSS variables and design tokens |
| Tooling | npm, TypeScript compiler, Next.js build pipeline |
| Rendering | Static App Router shell redirecting to the reference document |
| Assets | Supplied inline WebP, SVG, font, and HTML assets |
| Verification | Chromium screenshots and source-level image inspection |

See [the architecture notes](./docs/architecture.md) for the rendering
pipeline and image lifecycle decisions.

## Repository Structure

```text
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── workflows/ci.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── app/
│   ├── layout.tsx       # App Router metadata and document shell
│   └── page.tsx         # Root redirect to the source-backed homepage
├── docs/
│   ├── screenshots/     # Committed reference and visual QA captures
│   └── visual-qa.md     # Rendering and parity notes
├── public/
│   ├── favicon.ico
│   └── reference.html   # Supplied single-file homepage capture
├── .editorconfig
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── SECURITY.md
├── next-env.d.ts
├── package-lock.json
├── package.json
└── tsconfig.json
```

The reference page is intentionally kept as a single source-backed document.
The thin Next.js shell provides a conventional project entrypoint without
rebuilding the captured page into visually divergent components.

## Getting Started

### Prerequisites

- Node.js 18.17 or newer
- npm 9 or newer
- Chromium for visual QA

### Installation

```bash
git clone https://github.com/devtechedge/notion-clone.git
cd notion-clone
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

### Build

```bash
npm run build
```

### Production

```bash
npm run build
npm run start
```

## Visual QA

Visual parity is evaluated against the supplied reference screenshot and saved
HTML. The workflow uses:

1. A controlled Chromium viewport.
2. Full-page screenshots of the reference and localhost pages.
3. A blended overlay to reveal alignment drift.
4. A pixel-difference image to locate high-contrast mismatches.
5. Browser inspection of image source, dimensions, visibility, and paint state.

| Artifact | Purpose |
| --- | --- |
| [Reference](./docs/screenshots/desktop-reference.png) | Supplied visual baseline |
| [Local desktop](./docs/screenshots/desktop-local.png) | Current localhost render |
| [Overlay](./docs/screenshots/visual-qa-overlay.png) | Blended alignment comparison |
| [Pixel difference](./docs/screenshots/pixel-difference.png) | Amplified visual delta |

## Rendering Decisions

### Why the supplied HTML is used

The reference document contains the exact DOM hierarchy, CSS, font declarations,
inline assets, and design-token values needed for fidelity. Recreating those
details manually would introduce unnecessary visual drift.

### Image lifecycle handling

The saved document uses lazy and asynchronous image behavior. That lifecycle
can leave below-the-fold Bento artwork unpainted during an immediate full-page
capture even though the data URI and natural dimensions are valid.

The eight Bento images therefore use native eager loading and synchronous
decoding. This is a browser rendering decision, not a screenshot-time script:
there is no artificial scrolling, timeout-based painting, or placeholder art.

### Artwork preservation

Existing WebP, SVG, canvas-like compositions, logos, and font assets remain
source-backed. Artwork is preserved rather than redrawn so the implementation
can be audited against the supplied reference.

## Project Goals

- High visual fidelity to the supplied reference.
- Pixel-accurate coordinates, typography, spacing, and composition.
- Deterministic rendering in Chromium.
- No placeholder or generically recreated artwork.
- A maintainable project shell around the source-backed page.

## Challenges Solved

<details>
<summary>Lazy loading</summary>

Below-the-fold images can remain unloaded during automated full-page capture.
The Bento assets are promoted to native eager loading while preserving their
original source data.
</details>

<details>
<summary>Image decoding</summary>

Asynchronous decoding can complete after layout and capture have already begun.
Synchronous decoding makes the critical Bento artwork available for the first
stable render.
</details>

<details>
<summary>Render lifecycle and viewport activation</summary>

The page must render correctly without synthetic scroll events or delayed
capture logic. The final approach moves the fix into standard image loading
semantics rather than manipulating viewport state.
</details>

<details>
<summary>Full-page capture</summary>

Reference and localhost captures are normalized to the same dimensions before
overlay and difference generation, making section-level drift easier to find.
</details>

## Performance

- Next.js provides a small App Router shell and production build pipeline.
- Inline source assets avoid network dependency for the captured page.
- Bento images use deterministic native loading instead of runtime polling.
- `npm run build` performs compilation, type checking, and static generation.
- Visual fidelity is prioritized before secondary Lighthouse tuning.

## FAQ

### Why is the homepage served from `reference.html`?

The supplied saved DOM is the parity contract. Serving it directly preserves
the original structure, inline artwork, and browser behavior under review.

### Can the artwork be replaced with new components?

No. Existing source-backed artwork is intentionally preserved; changes should
be validated against the committed reference evidence first.

## Known limitations

- Lighthouse JSON generation on the current Windows environment is blocked by
  Chrome Launcher temporary-profile cleanup (`EPERM`); the reproducible command
  is documented under `docs/lighthouse/`.
- The visual baseline is intentionally desktop-first, with responsive smoke
  coverage in Playwright.

## Roadmap

- [x] Preserve the supplied HTML and inline artwork.
- [x] Add native deterministic Bento image loading.
- [x] Add Chromium visual QA captures and comparison artifacts.
- [x] Add repository documentation and contribution policy.
- [x] Add GitHub Actions build validation.
- [x] Add Playwright-based screenshot regression automation.
- [x] Run visual regression checks on every pull request.
- [ ] Add Lighthouse reporting to CI.
- [ ] Add a responsive viewport comparison matrix.

## Repository Statistics

| Property | Value |
| --- | --- |
| Languages | TypeScript, CSS, HTML, inline SVG/WebP |
| Framework | Next.js App Router |
| Architecture | Static source-backed reference document with a Next.js shell |
| Project type | Frontend visual recreation / portfolio case study |
| License | MIT |

## Screenshots

### Desktop

![Desktop local render](./docs/screenshots/desktop-local.png)

### Reference

![Supplied desktop reference](./docs/screenshots/desktop-reference.png)

### Visual QA Overlay

![Visual QA overlay](./docs/screenshots/visual-qa-overlay.png)

### Pixel Difference

![Pixel difference](./docs/screenshots/pixel-difference.png)

The gallery intentionally keeps the reference, local render, overlay, and
difference captures together so visual review can be repeated from a clean
clone.

## Acknowledgements

Thanks to the supplied visual reference, saved HTML capture, design tokens, and
network asset archive that make source-backed parity work possible.

## License

Distributed under the MIT License. See [LICENSE](./LICENSE).

## Author

Built by [Devtechedge](https://github.com/devtechedge).

Repository: [github.com/devtechedge/notion-clone](https://github.com/devtechedge/notion-clone)

``n
---

## 24. polygot
- **URL:** https://github.com/devtechedge/polygot
- **Language:** TypeScript
- **Topics:** ai, gemini, language-learning, nextjs, portfolio, pronunciation, react, roleplay, spanish, speech-recognition, typescript, vercel
- **Description:** PolyGlot Live is a Spanish speaking lab for learners who want live roleplay, not flashcards. Pick a Madrid tapas bar, a Barcelona bike rental, or a Tokyo tech interview. Talk via mic or type, then get IPA, grammar toasts, vocab chips, and a fluency scorecard. Next.js 15, React 19, Gemini with canned demo fallback. Browser speech; no accounts. MIT.


### README.md

`markdown
# PolyGlot Live

Spanish speaking lab for learners who want live roleplay, not flashcards. Order tapas in Madrid, rent a bike in Barcelona, or sit a tech interview — then get IPA, grammar toasts, and a fluency scorecard.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://polygot-snowy.vercel.app)
[![CI](https://github.com/devtechedge/polygot/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/polygot/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Gemini](https://img.shields.io/badge/Gemini-optional-4285F4?logo=google)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://polygot-snowy.vercel.app**

> **Status:** Portfolio demo. Scenario copy, hosts, and vocab ship in `lib/scenarios.ts`. `POST /api/chat` uses canned host replies unless `GEMINI_API_KEY` is set on the server. Speech uses the browser Web Speech API (Chrome / Edge). Type mode is the fallback. No accounts.

This is the **only** public repo for the project.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="PolyGlot Live" width="800">
</p>

| Passport hub | Briefing |
|--------------|----------|
| ![Mobile passport hub with three Spanish scenarios](docs/screenshots/01-passport-hub.png) | ![Tapas briefing with objectives and vocab](docs/screenshots/02-scenario-briefing.png) |

| Live HUD | Desktop studio |
|----------|----------------|
| ![In-call HUD with host avatar and transcript](docs/screenshots/03-live-hud.png) | ![Desktop marketing landing and studio CTA](docs/screenshots/04-desktop-landing.png) |

---

## Features

- Three Spanish roleplays: El Sol tapas (beginner), Barcelona bike rental (intermediate), Tokyo tech interview (advanced)
- Live HUD with host avatar, transcript, IPA line, and English gloss
- Grammar toasts on gender / conjugation slips (`un copa` → `una copa` in demo mode)
- Vocab chips, hint sheet, flashcards, and a post-call fluency scorecard
- Madrid vs Latin American dialect + 0.8× / 1.0× / 1.2× speech rate
- Mic or type. Public demo does not require a Gemini key

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 15 (App Router), React 19, TypeScript, Tailwind 4, Motion |
| Speech | Web Speech API (`SpeechRecognition` + `speechSynthesis`) |
| AI | Optional `@google/genai` (`gemini-2.5-flash`). Canned fallback in `lib/demo-chat.ts` |
| Data | Static scenario catalog — not Prisma, not a database |
| Auth | None |
| Hosting | Vercel |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/polygot.git
cd polygot
npm install
cp .env.example .env.local
npm run dev
```

Open **http://localhost:3000**. Gemini is optional.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: unauthenticated chat route, canned replies without a key, browser speech. Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 25. calendar-math
- **URL:** https://github.com/devtechedge/calendar-math
- **Language:** Python
- **Topics:** calendar, evaluation, llm-evaluation, prime-intellect, python, reinforcement-learning, rl, rlvr, verifiers
- **Description:** Single-turn calendar arithmetic RL environment for Prime Intellect: datetime gold solver, exact+format+partial grader, vf-eval ready.


### README.md

`markdown
# calendar-math

Single-turn **calendar arithmetic** for RLVR / evals on the [Prime Intellect Environments Hub](https://app.primeintellect.ai/dashboard/environments).

Hub: [devtechedge/calendar-math](https://app.primeintellect.ai/dashboard/environments/devtechedge/calendar-math) · Source: [github.com/devtechedge/calendar-math](https://github.com/devtechedge/calendar-math)

The model is given one of three question types, reasons, and puts a final answer in `<answer>` tags. The grader is pure `datetime` — no LLM-as-judge, no fuzzy string matching on the main reward.

| Task | Example prompt | Gold answer |
| --- | --- | --- |
| `add_days` | What date is 1 day after 2024-02-28? | `2024-02-29` |
| `days_between` | How many days after 2024-02-28 is 2024-03-01? | `2` |
| `weekday` | What day of the week is 2024-02-29? | `Thursday` |

This is intentionally **not** reverse-text or word-count. Calendar reasoning is a documented LLM failure mode (leap years, century years, month lengths, weekday). The environment turns that into a dense, automatically-graded RL signal.

## Why this design

- **Verifiable.** Gold answers are produced by Python `datetime.date`. The same functions are the reference solver.
- **Hard where it matters.** Eval always includes curated edge cases: 1900-02-28 (century, not leap), 2000-02-28 (century, leap), 2024-02-29, year boundaries.
- **Not gameable by format alone.** Format is a 0.2 bonus. Exact match is the 1.0 term.
- **Shaping, not noise.** Off-by-one dates / day-counts score 0.5 partial credit — models routinely confuse inclusive vs exclusive counting. Adjacent weekdays score 0.3.
- **Configurable.** `num_train_examples`, `num_eval_examples`, `seed`, and an optional `task` pin.

## Reward

```
reward = 1.0 * exact_match + 0.2 * format + 0.2 * partial_credit
```

| Term | 1.0 when | Notes |
| --- | --- | --- |
| `exact_match` | parsed `<answer>` equals gold | dates ISO, weekdays canonical English, counts decimal integers |
| `format` | `<answer>...</answer>` present | extra prose outside the tags is ignored |
| `partial_credit` | near-miss as above | 0 when exact match already fired, so a perfect answer is **1.2** not 1.4 |

## Eval

`vf-eval` on the 15 curated edge cases (`num_eval_examples=15`, 1 rollout):

| Policy | avg reward | exact | format | partial |
| --- | --- | --- | --- | --- |
| Gold datetime solver (ceiling) | **1.200** | 1.000 | 1.000 | 0.000 |
| Naive calendar (year%4 leaps, inclusive counts) | **0.768** | 0.533 | 1.000 | 0.173 |

The gold policy is a harness check: install, `load_environment`, rollouts, and the rubric all fire. The naive policy is a discrimination check: century non-leaps and inclusive day-counts do not rubber-stamp 1.2.

Against an API model (needs `OPENAI_API_KEY` or `--provider prime`):

```bash
uv run vf-eval calendar-math -n 20 -r 1 -m gpt-4.1-mini
```

## Installation

```bash
uv pip install -e .
python -m pytest tests/test_calendar_math.py -q
```

From the Hub:

```bash
prime env install devtechedge/calendar-math
```

```python
import verifiers as vf

env = vf.load_environment("calendar-math")
```

## `load_environment` arguments

| Arg | Default | Meaning |
| --- | --- | --- |
| `num_train_examples` | `500` | train split size |
| `num_eval_examples` | `100` | eval split size (edge cases prepended) |
| `seed` | `42` | train RNG; eval uses `seed + 1` |
| `task` | `None` | `"add_days"` \| `"days_between"` \| `"weekday"` \| mixed |

```bash
uv run vf-eval calendar-math -n 20
uv run vf-eval calendar-math -a '{"task": "weekday", "num_eval_examples": 40}'
```

Requires `verifiers>=0.1.14`. Dataset rows use `task_type` (not `task`): current verifiers treat `info["task"]` as a nested rollout payload.

## Gold solution

Dataset construction **is** the gold solver. For a row `info`:

```python
from datetime import date, timedelta

WEEKDAYS = ["Monday", "Tuesday", "Wednesday", "Thursday",
            "Friday", "Saturday", "Sunday"]

def gold(info):
    if info["task_type"] == "add_days":
        return (date.fromisoformat(info["start"]) + timedelta(days=info["n"])).isoformat()
    if info["task_type"] == "days_between":
        a = date.fromisoformat(info["start"])
        b = date.fromisoformat(info["end"])
        return str((b - a).days)          # midnights that pass; same day = 0
    return WEEKDAYS[date.fromisoformat(info["start"]).weekday()]
```

`tests/test_calendar_math.py` asserts the solver against a hand-checked fixture list (leap years, century years, negative offsets, same-day diffs).

## Files

```
calendar_math.py              # generator, gold, grader, load_environment
pyproject.toml
README.md
LICENSE
tests/test_calendar_math.py
```

## What this is not

- Not a wrap of GSM8K or any public dataset.
- Not LLM-judged.
- Not multi-turn / tool-using. Those are the right shape for a **second** environment (meeting-conflict scheduler, timezone conversion with a tz database, etc.).

## License

MIT

``n
---

## 26. meeting-slot
- **URL:** https://github.com/devtechedge/meeting-slot
- **Language:** Python
- **Topics:** calendar, evaluation, llm-evaluation, prime-intellect, python, reinforcement-learning, rl, rlvr, scheduling, timezone, tool-use, verifiers
- **Description:** Multi-turn tool-using meeting scheduler RL environment for Prime Intellect: hidden calendars, timezone gold solver, exact+format+partial grader.


### README.md

`markdown
# meeting-slot

Multi-turn **tool-using meeting scheduler** for RLVR / evals on the [Prime Intellect Environments Hub](https://app.primeintellect.ai/dashboard/environments).

Hub: [devtechedge/meeting-slot](https://app.primeintellect.ai/dashboard/environments/devtechedge/meeting-slot) · Source: [github.com/devtechedge/meeting-slot](https://github.com/devtechedge/meeting-slot)

A sequel to [calendar-math](https://github.com/devtechedge/calendar-math): same calendar domain, but the model has to **query tools** instead of reading the calendar out of the prompt.

The task is to find the **earliest valid UTC start** that works for every attendee. Busy intervals, working hours, and timezones are hidden. The final answer goes in `<answer>` tags as a UTC ISO-8601 timestamp, e.g. `2024-03-11T15:00:00Z`. If no slot exists, `NONE`.

The grader is a UTC sweep-line over `zoneinfo` — no LLM-as-judge, no fuzzy string match on the main reward.

| Tool | Returns |
| --- | --- |
| `list_attendees()` | JSON names |
| `get_timezone(name)` | IANA timezone |
| `get_working_hours(name)` | local `HH:MM` hours + weekdays (`0=Monday`) |
| `get_busy(name, date)` | local half-open busy intervals for that **local** date |

## Why this design

- **Verifiable.** Gold answers are produced by interval intersection in UTC. The same functions are the reference solver.
- **Tool use is load-bearing.** The world is not in the prompt. A model that does not call tools cannot solve the task.
- **Hard where it matters.** Eval always includes curated edge cases: US/EU DST, NY↔Kolkata no-overlap, Friday 16:30 vs Monday 09:00, 30 vs 60 minute gaps, four-person summer overlap, inclusive-busy traps.
- **Not gameable by format alone.** Format is a 0.2 bonus. Exact match is the 1.0 term.
- **Shaping, not noise.** A conflict-free in-hours start that is not the earliest scores 0.5 partial credit. Invalid overlap / wrong duration / outside hours score 0 on the main terms.
- **Configurable.** `num_train_examples`, `num_eval_examples`, `seed`, `max_turns`, optional `difficulty` pin.

## Reward

```
reward = 1.0 * exact_match + 0.2 * format + 0.2 * partial_credit
```

| Term | 1.0 when | Notes |
| --- | --- | --- |
| `exact_match` | parsed `<answer>` equals gold | UTC ISO with `Z`, or `NONE` |
| `format` | `<answer>...</answer>` present | extra prose outside the tags is ignored |
| `partial_credit` | valid-but-not-earliest | 0.5; 0 when exact match already fired, so a perfect answer is **1.2** not 1.4 |

Intervals are half-open `[start, end)`. A busy block ending at 11:00 means 11:00 is free.

## Eval

15 curated edge cases (`num_eval_examples=15`, 1 rollout each).

| Policy | avg reward | exact | format | partial |
| --- | --- | --- | --- | --- |
| Gold sweep-line via tools (ceiling) | **1.200** | 1.000 | 1.000 | 0.000 |
| Naive (ignore TZ; busy end inclusive) | **0.293** | 0.067 | 1.000 | 0.133 |
| `minimax/minimax-m2.7` (OpenRouter, T=0, 2048 tok) | **0.993** | 0.800 | 0.933 | 0.033 |

The gold policy is a harness check: tools leak enough to rebuild the world, and the rubric fires 1.2. The naive policy is a discrimination check: DST offsets, NY/Kolkata non-overlap, and inclusive busy do not rubber-stamp 1.2. Naive is exact on only the fully-booked `NONE` row.

MiniMax is exact on **12/15**. The three misses are the ones the env is supposed to catch:

- `sydney_ny_none` — format only (0.2). Claimed a 13:00Z overlap between Sydney and New York that does not exist.
- `dst_eu_monday` — valid-not-earliest (0.3). Answered 10:00Z after the EU spring-forward; gold is 08:00Z.
- `no_slot_fully_booked` — 0.0. Truncated before `</answer>` at 2048 tokens.

```bash
uv run vf-eval meeting-slot -n 15 -r 1 -p openrouter \
  -m minimax/minimax-m2.7 --max-tokens 2048 \
  --temperature 0 --max-concurrent 1 --disable-tui --disable-env-server
```

`--max-concurrent 1` keeps OpenRouter in-flight budget from aborting mid-rollout. Budget ≥2048 max tokens. Reasoning models spend the window on tool calls before `</answer>`; truncation looks like a grader bug.

## Installation

```bash
uv pip install -e .
python -m pytest tests/test_meeting_slot.py -q
```

From the Hub:

```bash
prime env install devtechedge/meeting-slot
```

```python
import verifiers as vf

env = vf.load_environment("meeting-slot")
```

Requires `verifiers>=0.1.14,<0.2`.

## `load_environment` arguments

| Arg | Default | Meaning |
| --- | --- | --- |
| `num_train_examples` | `500` | train split size |
| `num_eval_examples` | `100` | eval split size (edge cases prepended) |
| `seed` | `42` | train RNG; eval uses `seed + 1` |
| `max_turns` | `40` | tool-call turns before stop |
| `difficulty` | `None` | `"easy"` \| `"medium"` \| `"hard"` \| mixed |

```bash
uv run vf-eval meeting-slot -n 20
uv run vf-eval meeting-slot -a '{"difficulty": "hard", "num_eval_examples": 40}'
```

Dataset rows never use a column named `task`. Verifiers ≥0.1 treats `info["task"]` as a nested rollout payload.

## Gold solution

Dataset construction **is** the gold solver. For each attendee, working hours minus busy are converted to UTC with `zoneinfo` (both DST folds, skipping spring-forward gaps). The UTC free intervals are intersected; the earliest start `s` with `s + duration` inside the intersection and inside the search window is gold.

```python
from meeting_slot import gold_earliest, solve_from_tools

gold_earliest(world, duration_minutes, window_start, window_days)
# identical, but only using the four public tools:
solve_from_tools(world, duration_minutes, window_start, window_days)
```

`tests/test_meeting_slot.py` asserts the solver against a hand-checked fixture list (US/EU DST, 30 vs 60 minute gaps, NY–Kolkata NONE, inclusive busy).

## Files

```
meeting_slot.py                 # generator, gold, tools, grader, load_environment
pyproject.toml
README.md
LICENSE
tests/test_meeting_slot.py
```

## What this is not

- Not a wrap of a public calendar dataset.
- Not LLM-judged.
- Not single-turn. The calendars are behind tools on purpose.
- Not a dump of the whole calendar into the prompt.

## License

MIT

``n
---

## 27. pulsar
- **URL:** https://github.com/devtechedge/pulsar
- **Language:** TypeScript
- **Topics:** base-chain, decentralized-ai, erc20, foundry, framer-motion, nextjs, rainbowkit, recharts, solidity, staking, typescript, web3
- **Description:** Decentralized AI compute marketplace on Base. Pay $PULSAR for inference; earn by supplying GPU. Next.js site with a 3D neutron-star hero, staking UI, tokenomics, RainbowKit wallet connect, plus Foundry ERC-20 and staking contracts. GitHub Pages uses mock data—contracts are audit-ready but not deployed to Base (pre-TGE). TypeScript, Framer Motion.


### README.md

`markdown
<div align="center">

# <img src="public/pulsar.svg" width="48" height="48" alt="Pulsar logo" /> PULSAR

**The signal layer for decentralized AI compute**

Pay `$PULSAR` to run AI inference. Earn by supplying GPU power. Deflationary by design.

[![CI](https://github.com/devtechedge/pulsar/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/pulsar/actions/workflows/ci.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-black?logo=github)](https://devtechedge.github.io/pulsar/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.24-363636?logo=solidity)](https://soliditylang.org/)
[![Base](https://img.shields.io/badge/Base-8453-0052FF?logo=coinbase)](https://base.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](./LICENSE)

</div>

## Live Demo

**https://devtechedge.github.io/pulsar/**

> **Status:** Frontend + client-side Web3 is live. Smart contracts are audit-ready but not yet deployed to Base (pre-TGE). The UI uses realistic mock data and wallet-connect flows so the product experience is fully reviewable today.

## Screenshots

| Hero + 3D neutron star | How it works |
|:---:|:---:|
| ![Hero](docs/screenshots/Screenshot%202026-07-27%20042906.png) | ![How it works](docs/screenshots/Screenshot%202026-07-27%20042925.png) |

| Tokenomics | Live network pulse |
|:---:|:---:|
| ![Tokenomics](docs/screenshots/Screenshot%202026-07-27%20042931.png) | ![Network](docs/screenshots/Screenshot%202026-07-27%20042955.png) |

## Features

- **3D hero** — React Three Fiber neutron star with polar jets, accretion disk, and animated pulse rings
- **Wallet connect** — wagmi v3 + RainbowKit on Base (mainnet + Sepolia fallback)
- **Staking dashboard** — full approve → stake → unstake → claim flow with live APY reads
- **Tokenomics visuals** — Recharts allocation donut, vesting bars, animated burned-supply counter
- **Live network pulse** — simulated job feed, supplier map, latency & volume KPIs
- **Trust primitives** — Basescan verification hooks, UNCX lock proof, Gnosis Safe, KYC badge
- **Smart contracts** — `Pulsar.sol` (fixed 1B supply, tax + burn) + `PulsarStaking.sol` (Foundry + 14 tests)

## Tech Stack

| Layer | Tech |
|-------|------|
| Framework | Next.js 16 (App Router) + TypeScript |
| Styling | Tailwind CSS 4 + shadcn/ui |
| 3D / Motion | three.js + @react-three/fiber + Framer Motion |
| Charts | Recharts |
| Web3 | wagmi v3 + viem + RainbowKit |
| Contracts | Solidity 0.8.24 + OpenZeppelin + Foundry |
| Chain | Base (8453) |

## Quick Start

```bash
bun install
bun run dev          # → http://localhost:3000

# Optional — contracts
cd contracts
forge install OpenZeppelin/openzeppelin-contracts --no-commit
forge build && forge test -vv
```

Copy `.env.example` → `.env.local` and fill the four public vars when you are ready to point the UI at a live contract address.

```bash
bun run test          # unit tests (format, mock data, address guards)
bun run typecheck
bun run test:e2e      # Playwright Chromium smokes
```

See [`SECURITY.md`](./SECURITY.md) for the threat model.

## Smart Contracts

See [`contracts/`](./contracts) for the full Foundry project, ABIs, deployment scripts, and audit notes. Deployment guide: [`DEPLOY.md`](./DEPLOY.md).

## License

MIT — see [LICENSE](./LICENSE).

``n
---

## 28. obsidian
- **URL:** https://github.com/devtechedge/obsidian
- **Language:** HTML
- **Topics:** creative-coding, frontend, generative-art, github-pages, lenis, no-build, portfolio, react, single-file, tailwindcss, threejs, web-audio
- **Description:** The Obsidian Archive is a single-file immersive portfolio for a fictional generative sculpture studio. Twenty frontend features: Three.js crystal, Web Audio drone, command palette, pinned horizontal gallery. React 18 UMD, Tailwind Play CDN, Lenis, Three.js—zero build, GitHub Pages, SRI-pinned CDNs. Open index.html anywhere. Client-side only. MIT.


### README.md

`markdown
# The Obsidian Archive

Single-file immersive portfolio for a fictional generative digital sculpture studio. Twenty complex frontend features, Three.js crystal, Web Audio drone, command palette, and pinned horizontal gallery — all with zero build step.

[![CI](https://github.com/devtechedge/obsidian/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/obsidian/actions/workflows/ci.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-black?logo=github)](https://devtechedge.github.io/obsidian/)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![Three.js](https://img.shields.io/badge/Three.js-0.160-black?logo=threedotjs)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-Play%20CDN-06b6d4?logo=tailwindcss)
![Lenis](https://img.shields.io/badge/Lenis-Smooth%20Scroll-black)
![License](https://img.shields.io/badge/License-MIT-green)

## Live Demo

**https://devtechedge.github.io/obsidian/**

> **Status:** Client-side only on GitHub Pages. Zero backend. Open `index.html` anywhere. CDNs (React / Three / Lenis) are version-pinned with SRI. Tailwind Play CDN remains a runtime compiler by design.

Client-side only · zero build · fully self-contained (React UMD + Tailwind Play CDN + Three.js + Lenis + Web Audio).

## Screenshots

![Hero with 3D crystal](docs/screenshots/01-hero.jpg)

*Hero — Three.js crystal + particle field*

![Archive grid](docs/screenshots/02-archive.jpg)

*Archive — generative sculpture grid*

![Philosophy section](docs/screenshots/03-philosophy.jpg)

*Philosophy — live-drawing mandala + stats*

![Dark contact](docs/screenshots/04-contact-dark.jpg)

*Contact — dark theme*

## Features

- **One file, zero build** — entire experience ships as a single `index.html` (~140 KB)
- **Three.js hero crystal** with custom GLSL shader + mouse-drag rotation
- **Six generative SVG sculptures** (Vortex, Grid, Waves, Facets, Rings, Hex)
- **Pinned horizontal-scroll gallery** driven by vertical scroll
- **Web Audio ambient drone** (opt-in, four-oscillator with LFO filter)
- **⌘K command palette** with fuzzy search across sections, actions, and sculptures
- **Editorial light + gallery dark themes** with localStorage persistence and no FOUC
- **Accessible lightbox**, magnetic buttons, particle bursts, cursor trail, scroll progress, Konami easter egg, and more

## Tech Stack

| Layer | Choice |
|-------|--------|
| UI | React 18 (UMD) |
| Styling | Tailwind CSS (Play CDN) |
| 3D | Three.js 0.160 |
| Scroll | Lenis |
| Audio | Web Audio API |
| Fonts | Inter (variable) |
| Hosting | GitHub Pages |

No bundler. No package manager. The file is the project.

## Quick Start

```bash
# Clone and open locally
git clone https://github.com/devtechedge/obsidian.git
cd obsidian
# Just open index.html in a browser — there is no build step

# Optional: CI tooling only
npm ci
npm test
npx playwright install --with-deps chromium
npm run test:e2e
```

## Security

Threat model, CDN pinning, CSP, and XSS notes: [SECURITY.md](SECURITY.md).

## License

MIT License. See [LICENSE](LICENSE) for details.

``n
---

## 29. blockchain_expert
- **URL:** https://github.com/devtechedge/blockchain_expert
- **Language:** TypeScript
- **Topics:** agents, hitl, llm, mcp, nextjs, security, smart-contracts, solidity, static-analysis, swc, typescript, web3
- **Description:** Argus is an agentic smart-contract security copilot for auditors. Deterministic static analysis, SWC-mapped retrieval, false-positive filtering, remediation diffs, and human-in-the-loop triage. TypeScript engine, Next.js workbench, MCP tool host. Educational samples only; never connects to a chain. Vercel is demo-mode (no API key required).


### README.md

`markdown
# ARGUS

Agentic smart-contract security copilot: deterministic static analysis, SWC-mapped retrieval, and a human-in-the-loop triage board.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://argus-copilot.vercel.app)
[![CI](https://github.com/devtechedge/blockchain_expert/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/blockchain_expert/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://argus-copilot.vercel.app**

> **Status:** Vercel demo-mode. The analyzer, SWC retrieval, MCP tool host, and HITL board run in the browser. No API key. No chain RPC. Educational fixtures only — do not deploy the samples.

---

## Screenshots

| Workbench | HITL triage |
|-----------|-------------|
| ![Overview](docs/screenshots/01-overview.png) | ![Triage](docs/screenshots/02-triage.png) |

| Agent protocol |
|----------------|
| ![Protocol](docs/screenshots/03-protocol.png) |

---

## Features

- Deterministic Solidity static analysis (CEI / reentrancy, `tx.origin`, delegatecall, unchecked calls, unprotected withdraw, SELFDESTRUCT, weak seeds, floating pragma)
- SWC registry mapping with offline TF-IDF retrieval
- Heuristic false-positive filter (guards demote CEI smells)
- Remediation diff drafts
- Human-in-the-loop accept / dismiss / mark patched
- Markdown audit memo export
- MCP-shaped local tool host (`tools/list`, `tools/call`)
- CLI: `npm run scan -- path.sol`

This is a defensive review aid, not a professional audit and not a chain client.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Workbench | Next.js 15 App Router, TypeScript, React 19 |
| Engine | Local TypeScript parser + detectors + TF-IDF SWC corpus |
| Agent | Explicit nine-phase state machine with trace events |
| Tools | JSON-RPC 2.0 subset (MCP-shaped, read-only) |
| Data | Educational Solidity fixtures in-repo |
| Hosting | Vercel demo-mode (client-side analyzer) |
| CI | GitHub Actions — `npm ci`, unit tests, typecheck. No RPC. |

---

## Quick Start

```bash
npm install
npm test
npm run scan -- benchmarks/educational_samples/reentrancy_vault.sol
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). Pick a fixture, run **Static scan**, then Accept / Dismiss on the board.

Optional local LLM review uses `XAI_API_KEY` from `.env.example`. The public demo does not.

---

## Agent protocol

```
INGEST → PARSE → STATIC_SCAN → RAG_ENRICH → FP_FILTER
       → SEVERITY_RANK → PATCH_DRAFT → HITL_GATE → REPORT
```

See [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md). Educational samples live in `benchmarks/educational_samples/` and are labeled do-not-deploy.

---

## License

MIT. See [LICENSE](LICENSE).

## Security

Threat model, residual risk, and operator secrets: see [SECURITY.md](SECURITY.md).
This public deploy is a portfolio / demo surface; the GitHub repo may go private
after review without changing the live site’s required env hygiene.

``n
---

## 30. synthesis
- **URL:** https://github.com/devtechedge/synthesis
- **Language:** TypeScript
- **Topics:** agentic, drizzle, hitl, langgraph, multi-agent, nextjs, observability, postgres, rag, react, sse, typescript
- **Description:** Autonomous multi-agent research: plan → research → synthesize → critique → finalize. Live agent graph, HITL approval, RAG, Reflexion, streaming SSE, eval gate. Next.js 16, Drizzle, Postgres. Groq llama-3.3-70b + Tavily when keys are set; otherwise a deterministic grounded simulator with the same UI. Free-tier Vercel demo. OpenAI-compatible keys.


### README.md

`markdown
# Synthesis — Autonomous Multi-Agent Research Platform

[![Live Demo](https://img.shields.io/badge/Live%20Demo-synthesis--gold.vercel.app-black?style=for-the-badge&logo=vercel)](https://synthesis-gold.vercel.app/)
[![CI](https://github.com/devtechedge/synthesis/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/synthesis/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=nextdotjs)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![LangGraph](https://img.shields.io/badge/LangGraph.js-agent%20graph-1C3C3C?style=flat-square)](https://langchain-ai.github.io/langgraphjs/)
[![Drizzle](https://img.shields.io/badge/Drizzle-Postgres-C5F74F?style=flat-square&logo=drizzle)](https://orm.drizzle.team/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](./LICENSE)

> Plan → research → synthesize → critique → finalize. A free-tier Vercel demo of senior agentic-loop engineering: live agent graph, HITL approval, RAG, Reflexion, streaming SSE, and an eval gate.

---

## Live Demo

**https://synthesis-gold.vercel.app/**

- **Real LLM path is live** — Groq (`llama-3.3-70b-versatile`) + Tavily web search. Full multi-agent runs with cited reports, Reflexion, and telemetry.
- **Demo / simulated mode is the default** — works with or without keys. Real LLM/search only when LIVE_MODE=true and keys are set (optional PUBLIC_RUN_TOKEN).
- Any OpenAI-compatible provider works via `OPENAI_API_KEY` + `OPENAI_BASE_URL` + `OPENAI_MODEL`.

---

## Screenshots

| Plan approval (HITL) | Run complete |
|---|---|
| ![Plan approval](docs/screenshots/plan-approval.png) | ![Complete](docs/screenshots/run-complete.png) |

| Cited report | Evidence (11 sources) |
|---|---|
| ![Report](docs/screenshots/report-view.png) | ![Evidence](docs/screenshots/evidence-gathered.png) |

---

## What it does

1. **Brief** — enter a complex research question.
2. **Planner** — decomposes into research vectors; run **pauses for human-in-the-loop approval**.
3. **Research crew (parallel fan-out)** — tools (`web_search`, `read_url`), typed evidence, RAG ingest.
4. **Synthesizer** — cited Markdown report, streamed.
5. **Critic (Reflexion)** — faithfulness score; bounded revision loop if below threshold.
6. **Fact-checker** — source credibility audit.
7. **Finalizer** — confidence + cost/latency dashboard.

Every event is persisted — any past run is replayable.

---

## Agentic-loop principles (enforced)

| Principle | Implementation |
|---|---|
| **Loop is a graph, not a `while`** | `StateGraph` executor — nodes, conditional edges, explicit `END`. |
| **Plan → Act → Observe → Reflect** | ReAct tools + Reflexion critic with bounded revisions. |
| **Bounded autonomy + budget** | Max steps / tokens / cost / wall-clock → graceful finalize. |
| **Human-in-the-loop** | Planner checkpoint → `awaiting_approval` → resume on approve. |
| **Resumable state** | Full checkpoint to Postgres after every node. |
| **Structured I/O** | Zod-validated agent protocol; LLMs forced to JSON. |
| **Streaming-first** | SSE token + state events drive live graph & timeline. |
| **Observe before optimize** | Traced spans (latency / tokens / cost). |
| **Eval-driven** | `/api/eval` golden set + CI gate. |
| **Fail safe, fail cheap** | Retry/backoff, tool isolation, simulated fallback, partial results. |

---

## Architecture

```
Browser ──SSE──▶ Next.js (App Router) ──▶ Orchestration (StateGraph)
                                              │
        ┌──────────────┬──────────────────────┼───────────────────────┐
        ▼              ▼                      ▼                       ▼
   Agent crew      Tools / MCP bus        RAG / Memory           Observability
   planner         web_search, read_url,  JSONB embeddings,      event store +
   researcher      compute, query_memory  cosine retrieval,      cost/token/lat
   synthesizer                            long-term memory        spans
   critic
   fact_checker
   finalizer
        │
        ▼
   Postgres: runs · checkpoints · events · documents · evidence · memories · eval_runs
```

**Portability:** embeddings as JSONB float arrays (no pgvector required) — runs on any Neon / Vercel Postgres free DB.

---

## Key source

```
src/
├─ db/schema.ts                 # Drizzle schema
├─ lib/agent/
│  ├─ schemas.ts                # Zod state + AgentEvent protocol
│  ├─ llm.ts                    # OpenAI-compatible client + simulated mode
│  ├─ tools.ts                  # web_search / read_url / compute
│  ├─ rag.ts                    # embeddings, ingest, cosine retrieve
│  ├─ graph.ts                  # StateGraph executor
│  ├─ agents.ts                 # planner → finalizer crew
│  ├─ engine.ts                 # planResearch (HITL) + runResearch (stream)
│  └─ tracer.ts                 # SSE + durable events + cost spans
├─ app/api/run/...              # create, approve (SSE), detail, eval
└─ components/synthesis/        # App, AgentGraph, Timeline, ReportView
```

---

## Local dev

```bash
npm install
cp .env.example .env          # DATABASE_URL required; LLM/search keys optional
npx drizzle-kit push
npm run dev
```

Open http://localhost:3000.

### Demo mode (no keys)
Deterministic grounded engine — full graph, HITL, telemetry, eval. **Deployed demo always works.**

### Real mode
```
OPENAI_API_KEY=gsk_...                    # Groq (or any OpenAI-compatible key)
OPENAI_BASE_URL=https://api.groq.com/openai/v1
OPENAI_MODEL=llama-3.3-70b-versatile
TAVILY_API_KEY=...                        # live web search
```

---

## Evaluation & CI

[![CI](https://github.com/devtechedge/synthesis/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/synthesis/actions/workflows/ci.yml)

- **Unit tests** — Zod schemas, token/cost math, cosine, tool allow-lists, StateGraph termination, Reflexion routing (`npm test`)
- **Typecheck** — `tsc --noEmit`
- **Playwright** — Chromium smokes for idle chrome + HITL plan pause (`npm run test:e2e`)
- **Eval gate** — `GET /api/eval?limit=2` golden set (simulated engine, Postgres service)

```bash
npm ci
npm test
npm run typecheck
npm run test:e2e    # needs DATABASE_URL for the HITL path; UI smokes skip it
```

Threat model: [SECURITY.md](./SECURITY.md).

---

## Deploy (Vercel free tier)

1. Import the GitHub repo on Vercel.
2. Add Neon Postgres (Storage → Create Database → Neon) — `DATABASE_URL` is injected automatically.
3. Optional: Groq + Tavily env vars. Real spend also needs LIVE_MODE=true (keep false on public demos).
4. Optional: PUBLIC_RUN_TOKEN — live calls must send matching x-run-token.
5. Redeploy and open the live URL.

---

## Environment

See [`.env.example`](./.env.example). Only `DATABASE_URL` is required. Provider keys alone do not enable live spend — set LIVE_MODE=true (and optionally PUBLIC_RUN_TOKEN). Details: [SECURITY.md](./SECURITY.md).

---

## Roadmap

- CrewAI / AutoGen reference engines behind the same contract
- pgvector + ANN for larger corpora
- MCP tool-server exposure
- Langfuse-hosted tracing

---

## License

MIT — see [LICENSE](./LICENSE).

See also [SECURITY.md](./SECURITY.md).

Built as a senior-portfolio demonstration of agentic-loop engineering.

``n
---

## 31. lattice
- **URL:** https://github.com/devtechedge/lattice
- **Language:** TypeScript
- **Topics:** blockchain, crypto, freelance, job-board, react, salaries, tailwindcss, talent, tanstack, typescript, vercel, web3
- **Description:** Web3 career lattice: live roles from twenty crypto teams’ public Greenhouse, Lever, and Ashby boards, plus gigs, talent, and a salary observatory. Apply on the employer’s site. Pay only when the board publishes it. Public listings. Not an employer.


### README.md

`markdown
# Lattice

**Web3 jobs, crypto careers, blockchain roles** — live from employer ATS boards. Roles, gigs, talent, salaries, and companies — without five tabs and a paywall.

<p align="left">
  <img src="public/favicon.svg" width="48" height="48" alt="Lattice mark" />
</p>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://lattice-devtechedge1.vercel.app)
[![CI](https://github.com/devtechedge/lattice/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/lattice/actions/workflows/ci.yml)
[![TanStack Start](https://img.shields.io/badge/TanStack%20Start-black)](https://tanstack.com/start)
[![React](https://img.shields.io/badge/React-19-0052CC?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://lattice-devtechedge1.vercel.app**

> **Status:** Production is a **live job board**. Roles come from twenty crypto teams’ public Greenhouse, Lever, and Ashby boards (Coinbase, Binance, OKX, Bybit, Ripple, Kraken, Fireblocks, Crypto.com, Chainalysis, Blockchain.com, BitGo, Gemini, Alchemy, Phantom, Circle, Uniswap Labs, Ledger, Consensys, Ethereum Foundation, Solana Labs). Apply on the employer’s site. **Pay is only shown when the board publishes it** (posted metadata or inferred from the posting, marked `~`). Lattice does not invent a band. Talent, gigs, and learn remain a small editorial catalog. Posted listings, applications, bookmarks, and salary submissions persist in Postgres when `DATABASE_URL` is set. Without it the app uses embedded PGLite and reseeds on cold start. Sign-in is optional (bookmarks, applications, and talent profiles). Public listings. Not an employer. Not an offering. No wallet connect.

This is the **only** public repo for the product.

### Sister product

**[Jobrow](https://jobrow.vercel.app)** indexes still-open **US tech** roles from public ATS boards. Lattice stays on **blockchain / crypto / Web3**. Source: [devtechedge/job-board](https://github.com/devtechedge/job-board).

### Fresh openings

**[Companies hiring this week](https://lattice-devtechedge1.vercel.app/hiring)** — live roundup of crypto/Web3 employers that posted in the last seven days. Also: [job hubs](https://lattice-devtechedge1.vercel.app/jobs) (Solidity, DeFi, Ethereum, remote) and the [salary observatory](https://lattice-devtechedge1.vercel.app/salaries).

---

## Screenshots

| Home | Roles |
|------|-------|
| ![Editorial homepage](docs/screenshots/01-home.png) | ![Roles index with filters](docs/screenshots/02-roles.png) |

| Role | Salaries |
|------|----------|
| ![Role detail](docs/screenshots/03-role-detail.png) | ![Salary observatory](docs/screenshots/04-salaries.png) |

| Talent |
|--------|
| ![Talent directory](docs/screenshots/05-talent.png) |

Share card: [docs/screenshots/social-preview.png](docs/screenshots/social-preview.png)

---

## Features

- Editorial homepage: latest live role, twenty-team strip, new-this-week, companies hiring, manifesto
- [Companies hiring this week](https://lattice-devtechedge1.vercel.app/hiring) — shareable 7-day roundup from live ATS crawls
- Roles index with table and card views, persisted locally
- Live openings from twenty first-party ATS boards (Greenhouse, Lever, Ashby). Apply on the employer’s site; pay is posted or inferred (`~`), never invented
- Filters for chain, scene, department, seniority, remote region, benefits, pay-in-crypto
- Compensation as cash + token + equity, with vesting and cliff on the card
- Gigs marketplace and simulated digital contracts
- Public talent directory plus a privacy-flagged talent collective
- Salary observatory (mean / min / max, seniority, region, language sparkline)
- Anonymous salary submit, alerts / RSS view, market pulse, learn hub
- Free employer post (Markdown, preview, no account required)
- Apply flow with screening questions; studio desk for inbound applications
- Light / dark theme (persisted), command palette, hover-reveal scrollbars

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| App | TanStack Start, React 19, TypeScript, Tailwind v4 |
| Data | Live ATS fetch in `src/lib/server/live.ts`. Talent / gigs / learn in `src/lib/catalog`. Postgres when `DATABASE_URL` is set; embedded PGLite otherwise |
| Auth | Optional Better Auth session for bookmarks, applications, and profiles |
| Hosting | Vercel |
| License | MIT |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/lattice.git
cd lattice
npm install
npm run dev
```

Without `DATABASE_URL` the app uses embedded PGLite and seeds the catalog on first load.

```bash
npm run typecheck
npm test
npm run test:e2e
npm run build
```

Env template: [.env.example](.env.example). Never commit secrets.

| Variable | Where | Purpose |
|----------|--------|---------|
| `DATABASE_URL` | Vercel | Neon pooled URI (`sslmode=require`). Omit locally. |

See [SECURITY.md](SECURITY.md) for the threat model, reporting, and residual risk (guest posting, anonymous salary submit).

---

## Security

Lattice is hardened for a public Vercel deploy (parameterized SQL, same-site auth guards, CSP/HSTS headers, Markdown URL allow-lists, guest-post rate limits). **No public site is unhackable** — see [SECURITY.md](SECURITY.md) for the threat model, residual risk, and how to make this GitHub repo private later. SEO checklist: [docs/SEO.md](docs/SEO.md).

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 32. zenith-canvas
- **URL:** https://github.com/devtechedge/zenith-canvas
- **Language:** TypeScript
- **Topics:** canvas, interactive, localstorage, neo-brutalist, nextjs, playwright, portfolio, productivity, react, tailwindcss, typescript, web-audio-api
- **Description:** Zenith Canvas is a neo-brutalist family workspace: drag-and-drop bento cards, checklists, sketches, guest passes, Web Audio chimes, and a 4-digit PIN vault. Next.js 14, React, TypeScript, Tailwind. Everything lives in localStorage - no backend, no accounts, no database. Fresh Start reset and architecture-blueprint modal.


### README.md

`markdown
# Zenith Canvas

Neo-brutalist family canvas workspace — drag-and-drop bento cards, client-side persistence, Web Audio chimes, and a 4-digit PIN vault.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://zenith-workspace-ten.vercel.app)
[![CI](https://github.com/devtechedge/zenith-canvas/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/zenith-canvas/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-06b6d4?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://zenith-workspace-ten.vercel.app**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://zenith-workspace-ten.vercel.app)

Do **not** use https://zenith-canvas.vercel.app or https://zenith-workspace.vercel.app — those hostnames are not this project.

> **Status:** Client-side only. Canvases, checklists, sketches, guest passes and the vault PIN live in `localStorage`. There is no account system, no database, and no production backend. Do not store secrets on the board.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="Zenith Canvas" width="800">
</p>

| Workspace | Control Deck |
|-----------|----------------|
| ![Workspace](docs/screenshots/01-workspace.png) | ![Control Deck](docs/screenshots/02-control-deck.png) |

---

## Features

- Absolute-positioned family canvas with drag, resize, and multi-canvas switching
- Checklist, note, sketch, countdown, and ambient-sound cards
- Direct-DOM drag/resize so pointer moves do not re-render the React tree
- Web Audio chimes and a client-side 4-digit PIN vault (Control Deck)
- CSV / text drop import with formula-injection sanitization (`= + - @` → quoted)
- Demo “Fresh Start” reset in Control Deck → Automations

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 14 (App Router), React 18, TypeScript, Tailwind CSS 3, Lucide |
| Data | Browser `localStorage` (no database) |
| Auth | None. Demo PIN is a client-side UX gate — see [SECURITY.md](SECURITY.md) |
| Audio | Native Web Audio API |
| Hosting | Vercel (import this repo; do not use `output: "standalone"`) |
| CI | GitHub Actions (unit + typecheck + Playwright) |

---

## Quick Start

```bash
npm install
npm run dev
```

Open http://localhost:3000

```bash
npm test            # unit (CSV sanitizer, PIN, stars, guest passes)
npm run typecheck
npm run test:e2e    # Playwright Chromium smokes (shell, Control Deck, check-off, Fresh Start)
```

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 33. pulse-work
- **URL:** https://github.com/devtechedge/pulse-work
- **Language:** TypeScript
- **Topics:** block-editor, dark-mode, focus-timer, kanban, nextjs, notion-clone, portfolio, productivity, react, tailwindcss, typescript, workspace
- **Description:** Pulse Workspace is a block-based notes and collections OS for students and makers: slash-command editor, Kanban/table/calendar/Gantt views, ⌘K spotlight, flashcards, habits, and a 25-minute timer with procedural ambient noise. Next.js 15, React 19, Tailwind 4, Fira Code. Client-side demo — in-memory state, no auth; billing screens simulated. MIT.


### README.md

`markdown
# Pulse Workspace

Block-based workspace for notes, collections, and deep work. A slash-command editor, Kanban / table / calendar / Gantt views, ⌘K spotlight, flashcards, habits, and a focus timer with procedural ambient noise.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://pulse-work-indol.vercel.app)
[![CI](https://github.com/devtechedge/pulse-work/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/pulse-work/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://pulse-work-indol.vercel.app**

> **Status:** Portfolio demo. Notebooks, collections, habits, and the timer live in **React client memory** and reset on refresh. There is no auth backend. Billing screens are simulated (`alert()`). No Gemini key is required.

This is the **only** public repo for Pulse Workspace.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="Pulse Workspace" width="800">
</p>

| Launchpad | Editor |
|-----------|--------|
| ![Dark launchpad with pinned pages](docs/screenshots/01-launchpad.png) | ![Slash-command notebook editor](docs/screenshots/02-editor.png) |

| Collections | Focus timer |
|-------------|-------------|
| ![Kanban board of deliverables](docs/screenshots/03-kanban.png) | ![Pomodoro timer with ambient noise](docs/screenshots/04-focus.png) |

---

## Features

- Launchpad with pinned pages, deliverables, and habit chips
- Block editor with slash commands, covers, and version-history chrome
- Collections that share one dataset across Kanban, table, calendar, Gantt, and gallery
- ⌘K spotlight search over notebook titles
- Focus timer (25 / 5 / 15) with Web Audio white / pink / brown noise
- Flashcards, habit week grid, mind map, templates, trash
- Light / dark Fira Code shell

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| App | Next.js 15 (App Router), React 19, TypeScript |
| UI | Tailwind 4, Lucide, Fira Code |
| Data | In-memory React context (`context/WorkspaceContext.tsx`) |
| Audio | Web Audio API (procedural noise, no samples) |
| Hosting | Vercel |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/pulse-work.git
cd pulse-work
npm install
npm run dev
```

Open **http://localhost:3000**. No environment variables required.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: no auth, in-memory client store, simulated billing. Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 34. aether-flow
- **URL:** https://github.com/devtechedge/aether-flow
- **Language:** TypeScript
- **Topics:** canvas, flowchart, gemini, local-first, portfolio, react, state-machine, tailwindcss, typescript, visual-programming, vite, workflow
- **Description:** AetherFlow is a local-first visual flowchart IDE. Drag nodes on a pan/zoom canvas, compile the graph, and run a sandboxed step simulator with time-travel snapshots. Optional Gemini plus mock Gmail/Drive/Docs nodes. Public Vercel stores graphs in localStorage and uses mock Workspace payloads. React, Vite, TypeScript, Tailwind. No accounts. MIT. OSS.


### README.md

`markdown
# AetherFlow

Local-first visual flowchart IDE. Drag nodes onto a custom pan/zoom canvas, compile the graph, and run a step simulator with time-travel snapshots.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://aetherflow-ide.vercel.app)
[![CI](https://github.com/devtechedge/aether-flow/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/aether-flow/actions/workflows/ci.yml)
[![React](https://img.shields.io/badge/React-19-0052CC?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://aetherflow-ide.vercel.app**

Do **not** use https://aether-flow.vercel.app — that hostname is paused and is not this project.

> **Status:** The live site is a **client-side demo**. Graphs persist in `localStorage`. Gmail / Drive / Docs nodes use mock payloads unless you sign in locally with Firebase env vars. Gemini calls hit `/api/gemini/generate` and fall back to a canned reply when `GEMINI_API_KEY` is unset.

This is the **only** public repo for the project.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="AetherFlow" width="800">
</p>

| Canvas | Run |
|--------|-----|
| ![Default pipeline on the canvas](docs/screenshots/01-canvas-overview.png) | ![Compile & run with live console](docs/screenshots/02-pipeline-run.png) |

| Inspector | Version control |
|-----------|-----------------|
| ![Node inspector](docs/screenshots/03-inspector.png) | ![Local git ledger](docs/screenshots/04-version-control.png) |

---

## Features

- Custom SVG canvas (no React Flow / GoJS) with pan, wheel-zoom, 8px snap, and cubic-bezier links
- Quadtree viewport culling so off-screen cards skip DOM work
- Node palette: Start, End, Delay, Logic, Gmail, Drive, Docs, Gemini
- Graph compiler: start/end checks, dangling edges, self-loop reject
- Step simulator with VCR controls and snapshot scrubber
- Local branch / commit ledger on `localStorage` plus a visual added / modified / ghost-deleted overlay
- Optional Gemini proxy and Google Workspace nodes; public demo stays mock

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 19, Vite 6, TypeScript, Tailwind 4 |
| Canvas | SVG + DOM cards, quadtree cull |
| Persistence | `localStorage` (not IndexedDB) |
| Auth | Optional Firebase Google popup — mock mode by default |
| AI | Optional `POST /api/gemini/generate` (Gemini 2.5). Mock fallback on Vercel |
| Local server | Express + Vite middleware (`tsx server.ts`) |
| Hosting | Vercel (static Vite + serverless `/api`) |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/aether-flow.git
cd aether-flow
npm install
cp .env.example .env
npm run dev
```

Open **http://localhost:3000**. Gemini and Google sign-in are optional — the default pipeline runs on mock data.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: **no login** on the public site. Logic nodes evaluate short expressions with `Function` in the visitor's own browser. The Gemini key, when present, stays on the server.

Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 35. chaos-simulator
- **URL:** https://github.com/devtechedge/chaos-simulator
- **Language:** TypeScript
- **Topics:** bun, chaos-engineering, dashboard, framer-motion, full-stack, microservices, nextjs, observability, realtime, recharts, self-healing, socket-io, typescript
- **Description:** Chaos Simulator is a real-time chaos-engineering dashboard: self-healing microservices, animated SVG topology, particle effects, scenario builder, and live telemetry charts. Next.js 16, Bun, TypeScript, Framer Motion, Recharts. Public Vercel is client-side simulation—no backend. Chaos injection, healing, latency, and event stream run in-browser.


### README.md

`markdown
# 🔥 Chaos Simulator

Real-time chaos engineering dashboard with self-healing microservices, animated SVG topology, particle effects, scenario builder, and live telemetry.

[![CI](https://github.com/devtechedge/chaos-simulator/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/chaos-simulator/actions/workflows/ci.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://chaos-simulation.vercel.app)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Bun](https://img.shields.io/badge/Bun-1.x-fbf0df?logo=bun)](https://bun.sh/)
[![Socket.io](https://img.shields.io/badge/Socket.io-4.8-black?logo=socket.io)](https://socket.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-06b6d4?logo=tailwindcss)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer%20Motion-12-black)](https://www.framer.com/motion/)
[![Recharts](https://img.shields.io/badge/Recharts-2-orange)](https://recharts.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://chaos-simulation.vercel.app**

> **Status:** The live site is a full **client-side simulation** (no backend, no paid host). Chaos injection, self-healing, scenarios, latency charts, and the event stream all run in the browser. A Bun + Socket.io engine lives in this repo for **local** use only — it is not exposed on Vercel.

This is the **only** public repo for the project.

---

## Screenshots

### Dashboard Overview
![Dashboard with live topology, latency chart and toast notifications](docs/screenshots/01-dashboard-overview.png)

### Chaos Scenario Builder
![Multi-step Scenario Builder with presets](docs/screenshots/02-scenario-builder.png)

### Live Controls & Event Stream
![Disaster controls, targeted injection and live event stream](docs/screenshots/03-controls-and-stream.png)

### Anomaly Timeline
![Filterable anomaly history with recovery times](docs/screenshots/04-anomaly-timeline.png)

---

## Features

- **3 mock microservices** (Auth, Payment, Inventory) with live health, latency, and request volume
- **Automated chaos injector** — 500 errors, latency spikes, and service crashes every 30 s
- **Self-healing recovery** — services restore themselves within 8–15 seconds
- **Animated SVG topology** with particle data flow and health-based pulse rings
- **Canvas particle bursts + synthesized sound** on every critical event
- **Multi-step Scenario Builder** with presets (Black Friday, Cascading Failure, etc.)
- **Real-time latency chart** (60 s window) and filterable anomaly timeline
- **Manual injection controls** and a network-partition button

---

## Tech Stack

| Layer        | Technology |
|--------------|------------|
| Frontend     | Next.js 16, React 19, TypeScript, Tailwind 4, shadcn/ui |
| Animation    | Framer Motion 12, Canvas particles |
| Charts       | Recharts |
| Demo mode    | Client-side simulation on Vercel |
| Local engine | Bun + Socket.io (not public) |
| CI           | GitHub Actions — unit, `tsc`, Playwright |
| Package mgr  | Bun |

---

## Architecture

**Public demo (Vercel)** uses `useChaosEngine` in the browser. No paid backend.


```
Vercel / Demo                         Local only
┌─────────────────────────┐         ┌──────────────────────────┐
│ Next.js dashboard       │         │ Chaos Engine (Bun :3030) │
│ + useChaosEngine        │         │ + 3 mock services        │
│ (client simulation)     │         └──────────────────────────┘
└─────────────────────────┘
```

---

## Quality

| Check | How |
|-------|-----|
| Unit tests | Validation, simulation transitions, Scenario Builder presets |
| Types | `ignoreBuildErrors` is **off** — `bun run typecheck` |
| E2E | Playwright: dashboard, Scenario Builder, 500 inject, partition |
| CI | [GitHub Actions](https://github.com/devtechedge/chaos-simulator/actions) on every push to `main` |
| Supply chain | Unused template packages removed; Dependabot weekly (**patch/minor only** — do not merge majors blindly) |

```bash
bun install
bun run test
bun run typecheck
bunx playwright install chromium
bun run test:e2e
```

---

## Security

Portfolio demo: **no user login** on the public site. The browser simulation cannot reach other users.

The local Bun engine allow-lists service names and anomaly types, caps scenario payloads, and reads `CORS_ORIGIN` from the environment. **Do not bind port 3030 to the internet** without auth and a locked origin.

Details: **[SECURITY.md](SECURITY.md)**.

---

## Quick Start (demo — same as Vercel)

```bash
bun install
bun run dev
```

Open **http://localhost:3000**.

---


## License

MIT License. See [LICENSE](LICENSE).

``n
---

## 36. collabspace-express
- **URL:** https://github.com/devtechedge/collabspace-express
- **Language:** TypeScript
- **Topics:** canvas, collaborative-whiteboard, express, multiplayer, prisma, react, realtime, socketio, typescript, vercel, vite, websocket
- **Description:** CollabSpace Express is a real-time multiplayer whiteboard: infinite canvas, live cursors, rooms, and Prisma persistence. React 19, Vite, Express, Socket.io, TypeScript. Vercel hosts the client only; the Node/Socket server is local, and the public URL falls back to a solo canvas if the API is down. Anonymous localStorage name. No accounts, MIT. OSS.


### README.md

`markdown
# CollabSpace Express

Real-time multiplayer whiteboard — infinite canvas, live cursors, and Prisma-backed rooms.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://collabspace-express.vercel.app)
[![CI](https://github.com/devtechedge/collabspace-express/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/collabspace-express/actions/workflows/ci.yml)
[![React](https://img.shields.io/badge/React-19-61dafb?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646cff?logo=vite)](https://vite.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Express](https://img.shields.io/badge/Express-4-black?logo=express)](https://expressjs.com/)
[![Socket.io](https://img.shields.io/badge/Socket.io-4-black?logo=socket.io)](https://socket.io/)
[![Prisma](https://img.shields.io/badge/Prisma-5-2D3748?logo=prisma)](https://www.prisma.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://collabspace-express.vercel.app**

> **Status:** Vercel hosts the **Vite client**. There is no public Express/Socket.io process on that URL. When the API is unreachable the client falls back to **localStorage boards** so the live demo is still drawable. Clone and `npm run dev` for real multiplayer (two browser windows on the same room ID).
>
> This is not a production auth or payment product. Identity is an anonymous display name in `localStorage`.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.jpg" alt="CollabSpace" width="800">
</p>

### Dark canvas
![Dark-mode whiteboard with drawings, sidebar and tool rail](docs/screenshots/01-dark-canvas.png)

### Light canvas
![Light-mode whiteboard with rooms and collaborators](docs/screenshots/02-light-canvas.png)

### Empty board
![Dark UI after load — sidebar, infinite canvas, start-drawing hint](docs/screenshots/03-toolbar.png)

---

## Features

- **11 drawing tools** — pencil, highlighter, line, rectangle, circle, text, sticky note, eraser, select, image, laser pointer
- **Live collaboration** — Socket.io rooms, color-coded cursors, laser trails, presence list
- **Infinite canvas** — scroll zoom, Shift-drag / middle-click pan, grid overlay
- **Undo / redo** — local history, broadcast to peers
- **Shareable rooms** — UUID in the URL (`?room=`), join-by-ID in the sidebar
- **Persistence** — boards and elements in SQLite via Prisma (local backend)
- **PNG export**, dark / light theme, keyboard shortcuts (`V` `P` `E` `L` `R` `O` `T`)

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 19, Vite 8, TypeScript, HTML5 Canvas, Lucide |
| Realtime | Socket.io 4 |
| API | Express 4 |
| Data | Prisma 5 + SQLite (swap the provider for Postgres locally) |
| Hosting | Vercel (client). Express is **local** |
| CI | GitHub Actions |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/collabspace-express.git
cd collabspace-express
npm install

cp client/.env.example client/.env
cp server/.env.example server/.env

cd server && npx prisma migrate dev && npx prisma generate && cd ..

npm run dev
```

| Service | URL |
|---------|-----|
| Client | http://localhost:5173 |
| API + WebSocket | http://localhost:5000 |

Open two windows, create a board, paste the room ID in the second — strokes sync live.

---

## Project shape

```
client/                 Vite + React UI (Vercel)
  public/favicon.svg
  src/components/       DrawingBoard, Toolbar, Sidebar
server/                 Express + Socket.io + Prisma
  prisma/schema.prisma
  src/index.ts
```

Prisma is the local production path, not leftover template. The public Vercel alias does not run this server.

---

## Quality

| Check | How |
|-------|-----|
| Unit | Allow-lists, payload sanitizer, board-name rules, element upsert (`npm test`) |
| Types | `npm run typecheck` — server `tsc --noEmit`, client `tsc -b` |
| E2E | Playwright Chromium: shell, create board, pencil tool, theme toggle |
| CI | GitHub Actions — install → Prisma generate → unit → typecheck → e2e |
| Supply chain | Unused Testing Library removed; Dependabot weekly (patch/minor only — do not merge majors blindly) |

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: **no login**. Vercel cannot reach other users' boards.

The local Express engine allow-lists element types, clamps strokes, caps payload size, and reads `CORS_ORIGIN`. **Do not bind port 5000 to the internet** without auth and a locked origin.

Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 37. aegis_vercel
- **URL:** https://github.com/devtechedge/aegis_vercel
- **Language:** Python
- **Topics:** ai-agents, autonomous-agents, fastapi, hitl, human-in-the-loop, langchain, langgraph, langserve, langsmith, mermaid, multi-agent, pgvector, python, rag, serverless, sre, sse, streaming, vercel
- **Description:** AEGIS is a multi-agent operations cortex with a live dashboard. Supervisor plus specialist agents (SRE, knowledge, coder, evaluator, communicator), Hybrid RAG, HITL gates, streaming SSE, and a real-time Mermaid LangGraph. FastAPI, LangChain, LangGraph, LangSmith. Open /ui, toggle Demo vs Live. Demo is instant simulation; Live needs API keys. MIT.


### README.md

`markdown
# AEGIS — Autonomous Enterprise Graph Intelligence System

**A self-hosted, auditable alternative to Glean + Devin + PagerDuty Autopilot, built 100% on LangChain.**

> **Try it live:** [aegis-agent-api.vercel.app/ui](https://aegis-agent-api.vercel.app/ui) — toggle between Demo and Live inference, watch the LangGraph supervisor route specialists in real time, and approve/reject HITL gates.

AEGIS takes a natural language operational request — _"Why is checkout latency spiking in us-east?"_ — and autonomously plans, delegates to specialist sub-agents, retrieves from hybrid knowledge bases, executes tools, hits human-in-the-loop gates, and posts a fully traced, evaluated, and auditable result.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://aegis-agent-api.vercel.app/ui)
[![CI](https://img.shields.io/github/actions/workflow/status/devtechedge/aegis_vercel/ci.yml?branch=main)](https://github.com/devtechedge/aegis_vercel/actions)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()
[![LangChain](https://img.shields.io/badge/LangChain-0.3-orange)]()
[![Security](https://img.shields.io/badge/Security-threat%20model-informational)](SECURITY.md)

---

## Live Demo

Open [aegis-agent-api.vercel.app/ui](https://aegis-agent-api.vercel.app/ui) and click **Run AEGIS**.

**What you'll see:**

- **Real-time Mermaid graph** animating the execution path: Supervisor → SRE Analyst → Knowledge → Coder → [HITL] → Evaluator → Communicator
- **Streaming agent output** — each specialist's findings appear as they execute, with confidence scores and artifact counts
- **Human-in-the-Loop gate** — the Coder produces a patch, pauses for your approval, then the Evaluator and Communicator complete the flow
- **Demo / Live toggle** — Demo mode runs an instant simulation; Live mode connects to the real LangGraph with your API keys
- **Live info panel** — step count, confidence %, artifact count, and elapsed time update in real time
- **LangSmith traces** — one-click link to the full trace for every run

### Screenshots

![Live run with specialist streaming](docs/screenshots/01-live-run-streaming.png)

![Demo mode HITL approval gate](docs/screenshots/02-demo-hitl-gate.png)

![Demo completed with confidence chips](docs/screenshots/03-demo-completed.png)

Public demo threat model: [SECURITY.md](SECURITY.md). Demo/sim is public by default; live LLM path requires `LIVE_MODE` (optional `PUBLIC_RUN_TOKEN`). Rate-limited. Not bank-grade.

---

## Architecture

```
[Next.js UI / LangGraph Studio] <-SSE-> [LangServe FastAPI /api]
                                        |
                              [LangGraph Supervisor]
                   /     |      |       |       |      \
            Researcher Coder  SRE   Knowledge Comm  Evaluator
               |         |     |        |
         Tavily/Arxiv  E2B  Prometheus  PGVector Hybrid RAG
                                        |
                                [Postgres + PGVector + Redis]
                                        |
                              [LangSmith Traces / Evals / Prompt Hub]
```

## Feature Matrix — Full LangChain Ecosystem

| Product | Used For |
|---|---|
| **langchain-core** | LCEL everywhere, structured output Pydantic v2, fallback LLM router |
| **langgraph** | Supervisor + 6 subgraphs, PostgresSaver, `interrupt()` HITL, `astream_events` |
| **langsmith** | Tracing, Prompt Hub (`aegis/supervisor_router`), Evals, Feedback API |
| **langserve** | FastAPI `/invoke`, `/stream`, `/threads/{id}/resume`, OpenAPI playground |
| **RAG** | MultiQuery → Cohere Rerank → LLM Grader → HyDE, PGVector + BM25 hybrid |
| **Tools (14)** | Tavily, Code Executor, Postgres, GitHub, Slack, Browser, Prometheus, Runbook, Arxiv, Wikipedia, Email, Calendar, FS, Memory |

## 7 Agentic Loops — All Implemented

1. Perception-Plan-Act-Reflect
2. Supervisor-Worker Hierarchical
3. RAG Self-Correction
4. Tool-Use ReAct + Self-Heal
5. Human-in-the-Loop Interrupt
6. Evaluation-Driven Self-Improvement
7. Memory Consolidation

All visible in LangSmith with custom metadata.

---

## Quickstart

### Vercel (recommended — zero config)

1. Fork this repo
2. Import into [Vercel](https://vercel.com)
3. Set root directory to `apps/api`
4. Add `GOOGLE_API_KEY` (or `OPENAI_API_KEY`) as an environment variable
5. Deploy — visit `/ui` for the live dashboard, `/docs` for the API playground

Without API keys the UI gracefully falls back to **Demo mode** (instant simulation).

### Docker (local / self-hosted)

```bash
cp .env.example .env
docker-compose -f infra/docker-compose.yml up --build
```

- Dashboard: http://localhost:8000/ui
- API playground: http://localhost:8000/docs
- LangGraph Studio: `langgraph dev`

### API Endpoints

| Endpoint | Method | Purpose |
|---|---|---|
| `/ui` | GET | Live dashboard (SSE, Mermaid, HITL) |
| `/stream` | POST | Streaming inference (SSE) |
| `/invoke` | POST | Single-shot inference (JSON) |
| `/threads/{id}/resume` | POST | Resume after HITL (JSON) |
| `/threads/{id}/resume/stream` | POST | Resume after HITL (SSE) |
| `/health` | GET | Graph status, key availability |
| `/docs` | GET | OpenAPI / Swagger playground |

---

## Why This Proves Senior+ AI Engineering

- **Agentic Loops**: 7 explicit loops, not chains
- **LangGraph HITL**: `interrupt()` / `Command(resume=...)`, PostgresSaver
- **LangSmith Evals/Prompt Hub**: 3 datasets, LLM-as-judge, CI gating faithfulness > 0.82
- **Hybrid RAG**: MultiQuery + Compression + Grader + HyDE
- **Multi-agent Supervisor**: 6 specialists, tool-use ReAct
- **Production Observability**: OpenTelemetry → LangSmith, run metadata
- **Vercel Serverless**: graceful degradation, SSE streaming, version-agnostic chunk handling

## Repo Structure

```
aegis/
├── apps/api/              # LangServe FastAPI + live UI
├── packages/aegis_graph/  # Supervisor + 6 subgraphs
├── packages/tools/        # 14 production tools
├── packages/rag/          # Ingestion / retriever / vectorstore
├── packages/memory/
├── packages/evals/
├── infra/docker-compose.yml
├── tests/
└── scripts/run_evals.py
```

## Evals

```bash
python scripts/run_evals.py
```

Writes `evals/reports/latest.md`. Public CI has no `LANGCHAIN_API_KEY`, so that job writes a **mock** report and exits 0 — it does not measure live LangSmith faithfulness. With the key set, datasets `aegis_rag_qa`, `aegis_tool_use`, and `aegis_incident_triage` run against project `aegis-production`; the intended production threshold is faithfulness ≥ 0.82.

CI itself fails on ruff (real errors), mypy on tools/evals/tests, and pytest (graph compile, RAG loop, tool guards, `/health` `/ui` `/stream` smokes). `pip-audit` is informational and does not fail the job on LangChain majors.

## Environment Variables

| Var | Purpose |
|---|---|
| `GOOGLE_API_KEY` | Gemini LLM (primary) |
| `OPENAI_API_KEY` | OpenAI fallback |
| `ANTHROPIC_API_KEY` | Coding fallback |
| `LANGCHAIN_API_KEY` | LangSmith tracing |
| `LANGCHAIN_TRACING_V2=true` | Enable tracing |
| `DATABASE_URL` | Postgres + PGVector |
| `REDIS_URL` | Short-term memory |
| `TAVILY_API_KEY` | Web search |

All optional — fake models/fallbacks keep Vercel deploy green even without keys.

---

MIT License — Built with LangChain, LangGraph, LangSmith

``n
---

## 38. collabspace
- **URL:** https://github.com/devtechedge/collabspace
- **Language:** TypeScript
- **Topics:** collaborative-whiteboard, framer-motion, infinite-canvas, multiplayer, presence, react, realtime, supabase, typescript, vercel, vite, websocket-alternative
- **Description:** CollabSpace is a real-time multiplayer whiteboard: infinite canvas, presence, chat, reactions, and a laser pointer. React 18, Vite, TypeScript, Framer Motion, Supabase Realtime. Dark/light, responsive. Public Vercel currently shows a Supabase-not-configured shell; full multiplayer needs a Supabase project. Local path is Docker + npx supabase start.


### README.md

`markdown
# CollabSpace

Real-time multiplayer collaborative whiteboard with infinite canvas, presence, chat, reactions, and a laser pointer.

![CI](https://github.com/devtechedge/collabspace/actions/workflows/ci.yml/badge.svg)
![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)
![React](https://img.shields.io/badge/React-18-61dafb?logo=react)
![Vite](https://img.shields.io/badge/Vite-5-646cff?logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![Supabase](https://img.shields.io/badge/Supabase-Realtime-3ecf8e?logo=supabase)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-11-black)
![License](https://img.shields.io/badge/License-MIT-green)

## Live Demo

**https://collabspace-mauve.vercel.app**

> **Status:** The production deploy currently shows a clean “Supabase not configured” shell. Full multiplayer collaboration requires a Supabase project; the free tier is limited to 2 active projects and those slots are already used by other portfolio apps.  
> Locally the project runs fully: Docker + local Supabase (`npx supabase start`) + `npm run dev`. Schema is idempotent — paste `supabase/migrations/0001_init.sql` into any free Supabase project (or use the local stack) for a working realtime demo.

## Screenshots

### Dark mode — Rooms
![Dark mode Rooms view](docs/screenshots/Screenshot%202026-07-27%20082946.png)

### Light mode — Chat
![Light mode Chat view](docs/screenshots/Screenshot%202026-07-27%20082952.png)

### Dark mode — Users
![Dark mode Users view](docs/screenshots/Screenshot%202026-07-27%20082958.png)

## Features

- **Infinite canvas** — pan (Shift-drag / middle-click), zoom (scroll), minimap
- **Drawing tools** — Pencil, Line, Rectangle, Circle, Text, Sticky note, Eraser, Select, Laser pointer
- **Real-time multiplayer** — live cursors with name labels via Supabase Presence
- **Persistent elements & chat** — Postgres Changes fan-out (no custom Socket server)
- **Ephemeral signals** — floating emoji reactions + laser pointer via Realtime Broadcast
- **Undo / Redo** with full history stack (`⌘Z` / `⌘⇧Z`)
- **Dark / light theme** with system preference + anti-flash
- **Responsive** — 5 breakpoints, mobile bottom-drawer sidebar, 44 px touch targets
- **Accessible** — focus-visible rings, ARIA tablist, prefers-reduced-motion, prefers-contrast
- **Anonymous identity** — random user stored in `localStorage` (auth-ready later)

## Related

Sibling demo: [collabspace-express](https://github.com/devtechedge/collabspace-express) — Express + Vite whiteboard without the Supabase realtime stack.

## Tech Stack

| Layer        | Tech                                              |
|--------------|---------------------------------------------------|
| Frontend     | React 18 · Vite 5 · TypeScript · Framer Motion   |
| Backend      | Supabase (Postgres + Realtime Presence / Broadcast / Postgres Changes) |
| Deploy       | Vercel (SPA rewrite via `vercel.json`)            |
| Identity     | Client-side random (localStorage)                 |

## Quick Start

```bash
# 1. Install
npm install

# 2. Env
cp client/.env.example client/.env
# Add VITE_SUPABASE_URL and VITE_SUPABASE_ANON_KEY

# 3. Schema (paste supabase/migrations/0001_init.sql into Supabase SQL Editor)
# Idempotent — safe to re-run

# 4. Dev server
npm run dev
# → http://localhost:5173
```

## Architecture (v1 → v2)

Original v1 used Express + Socket.io + Prisma + SQLite.  
v2 is fully client-side against Supabase — no custom backend process.

| Concern              | v2 implementation                          |
|----------------------|--------------------------------------------|
| Boards / elements    | `boardSync.ts` / `canvasSync.ts` → Supabase REST + Postgres Changes |
| Chat                 | `chatSync.ts` → Supabase insert + Postgres Changes |
| Cursors / presence   | Supabase Realtime Presence                 |
| Reactions / laser    | Realtime Broadcast (ephemeral)             |
| Identity             | `identity.ts` → localStorage               |

See `client/src/lib/realtime.ts` for the single `joinBoard()` session that wires all four channels.


## Engineering

Phase B hardening: [`SECURITY.md`](SECURITY.md) (open RLS, no auth, payload allow-lists), `npm test` (node:test), `npm run typecheck`, Playwright smokes of the unconfigured Vercel shell, GitHub Actions CI, Dependabot (patch/minor only).

## License

MIT License. See [LICENSE](LICENSE) for details.

``n
---

## 39. healthcare-deep-memory-agents
- **URL:** https://github.com/devtechedge/healthcare-deep-memory-agents
- **Language:** Python
- **Topics:** ai-agents, clinical-memory, consent, deep-memory, groq, healthcare, ollama, patient-journey, python, sentence-transformers, sqlite, vertical-agents
- **Description:** Cadence is a pure-Python deep-memory healthcare agent lab: multi-layer patient memory, journey stages, and consent-scoped clinician briefs. No LangChain. Local path is Ollama + SQLite + sentence-transformers. Public Vercel UI is a companion + share-code brief with Groq llama-3.3-70b (demo fallback without a key). Educational prototype, not real PHI


### README.md

`markdown
# <img src="web/favicon.svg" width="40" height="40" alt="" /> Cadence

**Deep-memory vertical agents for healthcare** — pure Python, fully local, zero agentic frameworks.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://cadence-healthcare.vercel.app/)
[![CI](https://github.com/devtechedge/healthcare-deep-memory-agents/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/healthcare-deep-memory-agents/actions/workflows/ci.yml)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Release](https://img.shields.io/badge/release-v0.2.0-brightgreen.svg)](https://github.com/devtechedge/healthcare-deep-memory-agents/releases/tag/v0.2.0)

> **Disclaimer**: Educational / research prototype only. Never use for real medical decisions. Always consult qualified clinicians.

## Live Demo

https://cadence-healthcare.vercel.app/

> **Status:** Public UI is a client-side companion + share-code clinician brief. Live chat uses Groq `llama-3.3-70b-versatile` (env `OPENAI_API_KEY` on Vercel). If the key is missing or Groq errors, the badge switches to **demo fallback**. Full multi-layer memory + consent grants run locally (`python run_patient.py` / `python run_clinician.py` + Ollama). Do not enter real PHI.

## Screenshots

<p align="center">
  <img src="docs/social-preview.jpg" alt="Cadence Healthcare" width="800">
</p>

| Overview | Companion |
| --- | --- |
| ![Overview](docs/screenshots/01-overview.png) | ![Companion](docs/screenshots/02-companion-timeline.png) |

| Share code | Clinician brief |
| --- | --- |
| ![Share](docs/screenshots/03-share-code.png) | ![Brief](docs/screenshots/04-clinician-brief.png) |

---

## What it is

Vertical AI agents that remember — symptoms, history, preferences — across sessions.

- Multi-layer deep memory (session · episodic · semantic · knowledge · insights)
- Pure Python only (no LangChain, CrewAI, AutoGen, Mem0…)
- Fully local & free (Ollama + SQLite + sentence-transformers)
- Consent-scoped clinician brief / note draft
- **Patient journey first**: Baseline → Triage → Visit Prep → Care → Pattern → Recovery

---

## Tech stack

| Layer | Choice |
|-------|--------|
| Agents | Pure Python (no LangChain / CrewAI / Mem0) |
| Local LLM | Ollama (`llama3.1`) |
| Live UI chat | Groq `llama-3.3-70b-versatile` via Vercel `/api/chat` |
| Memory | SQLite + sentence-transformers (injectable embedder) |
| Consent | Scope-gated grants + audit table |
| UI | Static HTML / Tailwind CDN on Vercel |

---

## Quick Start

```bash
# 1. Ollama
ollama pull llama3.1

# 2. Python
python -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3a. Patient journey (recommended)
python run_patient.py

# 3b. Single triage agent
python run_agent.py

# 3c. Clinician grant / brief / note
python run_clinician.py grant --patient demo --clinician dr_lee --hours 48
```

Force a stage:

```bash
python run_patient.py --stage VISIT_PREP
```

In-session: type `/stage CARE` to switch.

Memory lives in `data/` and survives restarts (gitignored).

### Tests

```bash
pip install -r requirements-dev.txt
python -m pytest -q
npm ci && npx playwright install chromium && npm run test:e2e
```

---

## Patient journey stages

| Stage | Agent | Role |
|-------|-------|------|
| BASELINE | Baseline | Profile, allergies, meds, goals |
| TRIAGE | Triage | Symptom structure + cautious red flags |
| VISIT_PREP | VisitPrep | Questions + brief for the clinician visit |
| CARE | CareCompanion | Adherence, side effects, care-plan tasks |
| PATTERN | Pattern | Hypothesis correlations from memory |
| RECOVERY | Recovery | Milestones and “what better looks like” |

Spec: [`docs/PATIENT_JOURNEY.md`](docs/PATIENT_JOURNEY.md)

---

## Architecture

### Memory Layers
1. **Session / Working** – recent turns  
2. **Episodic** – timestamped events, symptoms, visits  
3. **Semantic** – vector long-term facts  
4. **Knowledge** – local RAG over guidelines  
5. **Insights** – synthesized patterns (human-verified)

---

## Project Structure

```
healthcare-deep-memory-agents/
├── docs/screenshots/        ← product screenshots
├── run_patient.py           ← patient journey CLI
├── run_clinician.py         ← grant / brief / note CLI
├── src/memory/              ← DeepMemory + ConsentStore
├── src/agents/
├── web/                     ← Cadence UI (Vercel)
├── tests/                   ← pytest (no torch / Ollama)
├── e2e/                     ← Playwright smokes
└── data/                    ← local DB (gitignored)
```

---

## Security

See [`SECURITY.md`](SECURITY.md). Educational prototype. Public chat messages go to Groq when live mode is on.

---

## License

MIT (code). Any medical content you add keeps its original license.

``n
---

## 40. nexus-bazaar
- **URL:** https://github.com/devtechedge/nexus-bazaar
- **Language:** TypeScript
- **Topics:** b2b, checkout, ecommerce, local-first, marketplace, multi-role, portfolio, react, spa, tailwindcss, typescript, vite
- **Description:** NexusBazaar is a client-side multi-role marketplace for buyers, sellers, and admins. Browse a seeded catalog, run cart and promo checkout, switch into seller or admin hubs, and walk B2B RFQ plus Net-30 credit. React 19, Vite, TypeScript, Tailwind. Data lives in localStorage — no production payments, JWT, or backend. Optional Gemini concierge. MIT.


### README.md

`markdown
# NexusBazaar

Client-side multi-role marketplace for buyers, sellers, and admins — storefront, promo checkout, B2B RFQ, and localStorage persistence.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://nexusbazaar-market.vercel.app)
[![CI](https://github.com/devtechedge/nexus-bazaar/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/nexus-bazaar/actions/workflows/ci.yml)
[![React](https://img.shields.io/badge/React-19-0052CC?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://nexusbazaar-market.vercel.app**

> **Status:** Public deploy is a **client-side demo**. Catalog, cart, orders, loyalty, and B2B ledgers persist in `localStorage`. There is no production payment backend, JWT, or NextAuth. Switch Buyer / Seller / Admin from the header avatar. `NEXUS10` is a public promo; `ELITEPRO` needs Elite (crown toggle). NexusBot falls back to a mock reply unless `GEMINI_API_KEY` is set locally.

Do **not** use [nexus-bazaar.vercel.app](https://nexus-bazaar.vercel.app) — that hostname is a different lifestyle-blog project.

This is the **only** public repo for the marketplace.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.jpg" alt="NexusBazaar" width="800">
</p>

| Storefront | Cart |
|------------|------|
| ![Storefront](docs/screenshots/01-storefront.png) | ![Cart](docs/screenshots/02-cart.png) |

| Seller hub | B2B wholesale |
|------------|---------------|
| ![Seller hub](docs/screenshots/03-seller-hub.png) | ![B2B wholesale](docs/screenshots/04-b2b.png) |

---

## Features

- Buyer storefront with search, product details, wishlist, live-auction tiles, and promo checkout (`NEXUS10`, `ELITEPRO`, `BIGSAVER`)
- Header identity switcher for Buyer, Seller, and Admin — seller/admin chrome is role-gated
- Seller hub: listings, inventory, vouchers, broadcast tiles
- Admin workspace: user flags, promo ledger, marketplace metrics
- B2B desk: RFQ, Net-30 credit, team budget, pallet calculator
- Loyalty, guilds, curations, security-vault UI — all `localStorage`
- Optional Gemini concierge at `POST /api/gemini/chat` (mock without a key)

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 19, Vite 8, TypeScript, Tailwind 4 |
| Data | Seeded in-memory catalog + `localStorage` (not a SQL backend) |
| Auth | Demo role switcher — not JWT, not NextAuth |
| Payments | Simulated checkout only |
| AI | Optional `POST /api/gemini/chat` — mock fallback on Vercel |
| Hosting | Vercel (static Vite + `/api` function) |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/nexus-bazaar.git
cd nexus-bazaar
npm install
npm run dev
```

Open **http://localhost:3000**. Gemini is optional.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Demo notes

| Identity | How |
|----------|-----|
| Eager Buyer | Default. Cart, wishlist, orders, loyalty. |
| Elite Tech Seller | Header avatar → Seller Hub |
| Platform Admin | Header avatar → Admin Panel |

Promo codes: `NEXUS10` (10%), `ELITEPRO` (20%, Elite only), `BIGSAVER` (15% over $200).

---

## License

MIT. See [LICENSE](LICENSE).

## Security

Threat model, residual risk, and operator secrets: see [SECURITY.md](SECURITY.md).
This public deploy is a portfolio / demo surface; the GitHub repo may go private
after review without changing the live site’s required env hygiene.

``n
---

## 41. holdslot
- **URL:** https://github.com/devtechedge/holdslot
- **Language:** JavaScript
- **Topics:** hackathon, openai, webmcp
- **Description:** HoldSlot — agent can search and hold a slot; only the human can confirm. OpenAI WebMCP Challenge 2026.


### README.md

`markdown
# HoldSlot

OpenAI [WebMCP Challenge](https://webmcp.devpost.com/) 2026.

A booking desk where an **in-browser agent can search and hold a slot**, and **only the human can confirm**. The hold is visible on the same page. Confirm is a button, not a WebMCP tool.

Live: https://holdslot-cyan.vercel.app

## Why WebMCP

Agents are bad at calendars. They click the wrong cell, double-book, or submit while the person looks away. HoldSlot exposes **page-owned tools** so the agent does real work on the live board, then stops at the commitment.

## Tools (`document.modelContext.registerTool`)

| Tool | Who | What |
| --- | --- | --- |
| `search_slots` | Agent | Open slots by day and duration |
| `hold_slot` | Agent | Hold an open slot (expires in 3 minutes) |
| `list_holds` | Agent | Current holds and remaining time |
| `release_hold` | Agent | Drop a hold |
| `get_board` | Agent | Full board snapshot |
| `request_confirm` | Agent | Ask the human to confirm. **Does not confirm.** |

**Not a tool:** `Confirm booking`. Only the person on the page can press it.

## Test (judges)

1. Open the live URL in **ChatGPT’s in-app browser**, or Chrome with `chrome://flags/#enable-webmcp-testing` enabled.
2. Ask: *Search next available 30-minute slots, hold one, then stop. Do not confirm.*
3. You should see a **hold** with a timer. Confirm stays a human button.
4. If WebMCP is missing, the banner on the page says so.

No login. Simulated clinic / interview slots only. No real payments.

## Run locally

Serve the folder over HTTP (WebMCP needs a page context; file:// is unreliable):

```bash
npx serve .
```

Open the URL, enable the Chrome WebMCP flag, reload.

## Stack

Static HTML / CSS / JS. No backend. State is in the page so the human and the agent share one board.

## License

MIT. See [LICENSE](LICENSE).

## Security

Threat model, residual risk, and operator secrets: see [SECURITY.md](SECURITY.md).
This public deploy is a portfolio / demo surface; the GitHub repo may go private
after review without changing the live site’s required env hygiene.

``n
---

## 42. wanderlodge
- **URL:** https://github.com/devtechedge/wanderlodge
- **Language:** TypeScript
- **Topics:** airbnb-clone, dark-mode, gemini, lodging, marketplace, nextjs, peer-to-peer, portfolio, react, tailwindcss, travel, typescript
- **Description:** Peer-to-peer lodge marketplace for subalpine cabins. Search sensory-scored stays, book as a traveler or host as a provider, then run a trip workspace with group expenses, cabin controls, and a wilderness log. Next.js 15, React, TypeScript. Vercel uses an in-memory JSON store (writes reset). Gemini optional. Demo marcus@wanderlodge.com / password123


### README.md

`markdown
# WanderLodge

Peer-to-peer marketplace for subalpine cabins and lodges. Search sensory-scored stays, book as a traveler or host as a provider, then run a trip workspace with group expenses, in-stay cabin controls, and a wilderness log.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://wanderlodge-taupe.vercel.app)
[![CI](https://github.com/devtechedge/wanderlodge/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/wanderlodge/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://wanderlodge-taupe.vercel.app**

> **Status:** Portfolio demo. Listings and bookings live in an in-memory JSON store (`/tmp` on Vercel, so writes reset). Gemini herb/Q&A/adventure calls fall back to canned payloads when `GEMINI_API_KEY` is unset. Auth is an unsigned demo cookie, not JWT or NextAuth. Payments are simulated.

Demo accounts (password `password123`):

| Role | Email |
|------|-------|
| Traveler | `marcus@wanderlodge.com` |
| Provider | `evelyn@wanderlodge.com` |

This is the **only** public repo for the project.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="WanderLodge" width="800">
</p>

| Explore | Property |
|---------|----------|
| ![Lodge grid on the explore home](docs/screenshots/01-explore-lodges.png) | ![Property detail and booking card](docs/screenshots/02-property-detail.png) |

| Search | Trip workspace |
|--------|----------------|
| ![Search results with map](docs/screenshots/03-search-map.png) | ![Group coordination hub](docs/screenshots/04-trip-workspace.png) |

---

## Features

- Curated lodge grid with category chips, eco-score, and EV badges
- Search + map with amenity, price, guest, and sensory filters (decibel, astrophotography, solitude, fragrance-free)
- Traveler / provider demo auth with a one-click role switch
- Booking card: nights, 50% day-retreat, pantry upgrades, 30/70 deposit split
- Trip workspace: host chat, co-traveler expense split, in-stay cabin controls, wilderness log
- Optional Gemini botanist / concierge — mocked on the public demo

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 15 (App Router), React 19, TypeScript, Tailwind 4 |
| Motion | Motion (`motion/react`) |
| Data | JSON file store in `lib/db.ts` (not Prisma, not Mongo) |
| Auth | HttpOnly user-id cookie (`lib/session.ts`) — demo only |
| AI | Optional `@google/genai` with canned fallback |
| Hosting | Vercel |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/wanderlodge.git
cd wanderlodge
npm install
cp .env.example .env
npm run dev
```

Open **http://localhost:3000**. Gemini is optional.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: public passwords, unsigned session cookie, ephemeral JSON on Vercel. Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 43. vivid-pulse
- **URL:** https://github.com/devtechedge/vivid-pulse
- **Language:** TypeScript
- **Topics:** app-router, dark-theme, instagram-clone, nextjs, playwright, portfolio, react, social-network, tailwindcss, typescript, vercel, vitest
- **Description:** Neo-noir visual social network for digital creators. Photo feed with carousels, likes, bookmarks and threaded comments; 24-hour stories; discover search; DMs; and a cozy neighbors board. Next.js 15 App Router, TypeScript, Tailwind. In-memory Vercel demo (resets on cold start)—not JWT or NextAuth. Demo login alex_vivid / password123. MIT licensed.


### README.md

`markdown
# VividPulse

Neo-noir visual social network. A seeded photo feed, 24-hour stories, DMs, and a cozy neighbors board — built with Next.js 15.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://vividpulse-social.vercel.app)
[![CI](https://github.com/devtechedge/vivid-pulse/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/vivid-pulse/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Live Demo

**https://vividpulse-social.vercel.app**

Do **not** use https://vividpulse.vercel.app — that hostname is a different AI-automation product.

> **Status:** The public site is a **demo**. Auth is a signed `vp_session` cookie (not JWT / NextAuth). Posts, stories, and DMs live in **process memory** and reset on cold start. Seeded login: `alex_vivid` / `password123` (or the one-click ports on the login screen).

This is the **only** public repo for the project.

---

## Screenshots

<p align="center">
  <img src="docs/social-preview.png" alt="Vivid Pulse" width="800">
</p>

| Login | Feed |
|-------|------|
| ![Sign in with seeded demo ports](docs/screenshots/01-login.png) | ![Stories tray and photo feed](docs/screenshots/02-feed.png) |

| Neighbors | Discover |
|-----------|----------|
| ![Cozy neighbors hub](docs/screenshots/03-neighbors.png) | ![Discover grid](docs/screenshots/04-discover.jpg) |

![Private chats](docs/screenshots/05-messages.png)

---

## Features

- Seeded creator network with one-click demo login
- Photo feed with carousels, likes, bookmarks, and threaded comments
- 24-hour stories tray and viewer
- Discover search over captions and locations
- Direct messages with polling
- Cozy Neighbors hub — vibes, bulletin notes, strolls, treats
- Session cookie is httpOnly + `SameSite=lax` (`secure` in production)

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| App | Next.js 15 (App Router), React 19, TypeScript |
| UI | Tailwind 4, Lucide, Motion |
| Data | In-memory store (`lib/db.ts`). SQL shape in `docs/schema.sql` |
| Auth | SHA-256 password hash + signed session cookie |
| Media | Mock `/api/upload` (data URLs). Feed images from picsum.photos |
| Hosting | Vercel |
| CI | GitHub Actions — Vitest, `tsc`, Playwright |

---

## Quick Start

```bash
git clone https://github.com/devtechedge/vivid-pulse.git
cd vivid-pulse
npm install
npm run dev
```

Open **http://localhost:3000** and sign in as `alex_vivid` / `password123`. No environment variables required.

```bash
npm test
npm run typecheck
npx playwright install chromium
npm run test:e2e
```

---

## Security

Portfolio demo: public password, committed fallback session secret, in-memory store. Details: **[SECURITY.md](SECURITY.md)**.

---

## License

MIT. See [LICENSE](LICENSE).

``n
---

## 44. smart-waitlist
- **URL:** https://github.com/devtechedge/smart-waitlist
- **Language:** TypeScript
- **Topics:** drizzle-orm, full-stack, nextjs, referral-system, saas, server-actions, shadcn-ui, stripe, supabase, tailwindcss, typescript, waitlist
- **Description:** Smart Waitlist is a SaaS waitlist and referral engine: viral growth loops, live queue position, admin analytics, Stripe tiers, and Postgres RLS. Next.js 16, Supabase Auth + Postgres, Drizzle, shadcn/ui, Tailwind. Public Vercel is full-stack live—sign up, grab a referral link, climb the queue, open the admin dashboard. TypeScript. Not a toy form.


### README.md

`markdown
# Smart Waitlist & Referral Engine

Production-ready SaaS waitlist with viral referral loops, live position tracking, admin analytics, Stripe tiers, and full RLS. Built with Next.js 16, Supabase, Drizzle ORM, and shadcn/ui.

[![CI](https://github.com/devtechedge/smart-waitlist/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/smart-waitlist/actions/workflows/ci.yml)
![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)
![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![Supabase](https://img.shields.io/badge/Supabase-Postgres-3ecf8e?logo=supabase)
![Drizzle](https://img.shields.io/badge/Drizzle-ORM-c5f74f)
![Stripe](https://img.shields.io/badge/Stripe-Payments-635bff?logo=stripe)
![License](https://img.shields.io/badge/License-MIT-green)

## Live Demo

**https://smart-waitlist-engine.vercel.app/**

> Full-stack live. Supabase (Auth + Postgres + RLS) is healthy. Sign up, get a referral link, climb the queue, and explore the admin dashboard.

## Screenshots

| Landing / Hero | How it works |
|---------------|--------------|
| ![Landing](docs/screenshots/Screenshot%202026-07-27%20051317.png) | ![How it works](docs/screenshots/work.png) |

| Dashboard | Admin / Analytics |
|-----------|-------------------|
| ![Dashboard](docs/screenshots/Screenshot%202026-07-27%20053200.png) | ![Admin](docs/screenshots/Screenshot%202026-07-27%20053209.png) |

## Features

- **Viral referral engine** — unique referral codes, position leapfrogging, live leaderboard
- **Real-time position tracking** — dashboard shows rank, referrals, and shareable link
- **Admin analytics** — waitlist table, conversion funnel, geo heatmap, CSV export
- **Stripe tiers** — paid upgrades and promo codes
- **Secure by default** — Supabase RLS, Zod validation, admin allow-list, webhook signatures. See [SECURITY.md](SECURITY.md).
- **Modern stack** — Next.js 16 App Router + Server Actions, Drizzle ORM, Tailwind v4 + shadcn/ui, strict TypeScript

## Tech Stack

| Layer | Choice |
|-------|--------|
| Framework | Next.js 16 (App Router, RSC, Server Actions) |
| Language | TypeScript (strict) |
| Styling | Tailwind CSS v4 + shadcn/ui |
| Database | Supabase Postgres + RLS |
| Auth | Supabase Auth + `@supabase/ssr` |
| ORM | Drizzle ORM |
| Payments | Stripe |
| Validation | Zod |
| Deploy | Vercel + Supabase Cloud |

## Quick Start

```bash
git clone https://github.com/devtechedge/smart-waitlist.git
cd smart-waitlist
npm install
cp .env.example .env.local   # fill Supabase + Stripe keys
npm run db:push              # or apply supabase/migrations
npm run dev
```

Open http://localhost:3000.

See `.env.example` for the full list of required variables.

## Tests

```bash
npm test            # unit (pure helpers: ranking, auth, fraud email, CSV, redirects)
npm run typecheck
npm run test:e2e    # Playwright Chromium smokes (landing, sign-in, auth gate, 404)
```

CI runs all three on every push to `main`. Dependabot opens weekly patch/minor PRs only (majors ignored).

## License

MIT. See [LICENSE](LICENSE) for details.

``n
---

## 45. unit-fix
- **URL:** https://github.com/devtechedge/unit-fix
- **Language:** Python
- **Topics:** None
- **Description:** Single-turn Python repair RL environment: patch a small function so hidden unit tests pass. Sandboxed exec grader for Prime Intellect Environments Hub.


### README.md

`markdown
# unit-fix

Single-turn **Python repair** for RLVR / evals on the [Prime Intellect Environments Hub](https://app.primeintellect.ai/dashboard/environments).

Hub: [devtechedge/unit-fix](https://app.primeintellect.ai/dashboard/environments/devtechedge/unit-fix) · Source: [github.com/devtechedge/unit-fix](https://github.com/devtechedge/unit-fix)

A third environment next to [calendar-math](https://github.com/devtechedge/calendar-math) (datetime gold) and [meeting-slot](https://github.com/devtechedge/meeting-slot) (multi-turn tools). This one is **code**: a small broken function plus a failing unit test. The model puts a patched function in `<answer>` tags. The grader execs the tests in a stdlib sandbox — no LLM-as-judge, no source-string match on the main reward.

| Family | Bug the eval edge exists to catch |
| --- | --- |
| `nth_item` | 1-based indexing, uses `items[n]` |
| `sum_through` | `range` exclusive of `hi` |
| `mean_or_none` | empty list divides by zero |
| `codepoint_count` | UTF-8 bytes, not code points |
| `with_item` | mutates the input list |
| `closed_slice` | Python slice drops the end index |
| `rotate_left` | `n % len([])` crashes |
| `safe_ratio` | no zero-denominator guard |
| `window_count` | fencepost: `n-k` instead of `n-k+1` |
| `same_letters` | `str.lower` misses `ß → ss` |
| `field_count` | `split(" ")` misses NBSP / unicode whitespace |
| `unique_keep_order` | `sorted(set)` loses first-seen order |
| `clamp` | closed interval treated as `hi-1` |
| `chunks` | drops the remainder chunk |
| `first_index` | returns last match, not first |

## Why this design

- **Verifiable.** Gold answers are in-repo repairs. Dataset construction **executes** gold (must pass) and the original function (must fail).
- **Behavioral exact, not AST match.** Any repair that passes the hidden tests scores 1.0 on the main term. Hardcoding the visible example does not.
- **Hard where it matters.** Eval is 15 curated edges: off-by-one, empty list, unicode, mutation vs copy, inclusive/exclusive slice.
- **Not gameable by format alone.** Format is a 0.2 bonus. Exact match is the 1.0 term (all tests pass).
- **Shaping, not noise.** Visible tests pass but a hidden test still fails → 0.5 partial credit. Naive echo of the original function never gets there.
- **Sandbox.** AST gate (no imports, no dunders, no I/O), capped `range`/`sum`, `sys.settrace` step + wall-clock limit. No subprocess, so Hub CI does not fork.
- **Configurable.** `num_train_examples`, `num_eval_examples`, `seed`, optional `family` / `difficulty` pin.

## Reward

```
reward = 1.0 * exact_match + 0.2 * format + 0.2 * partial_credit
```

| Term | 1.0 when | Notes |
| --- | --- | --- |
| `exact_match` | every test (visible + hidden) passes | behavioral; source need not match gold |
| `format` | `<answer>...</answer>` present with a body | extra prose outside the tags is ignored; markdown fences inside are stripped |
| `partial_credit` | every **visible** test passes, a hidden test fails | 0.5; 0 when exact already fired, so a perfect answer is **1.2** not 1.4 |

## Eval

15 curated edge cases (`num_eval_examples=15`, 1 rollout each).

| Policy | avg reward | exact | format | partial |
| --- | --- | --- | --- | --- |
| Gold repair (ceiling) | **1.200** | 1.000 | 1.000 | 0.000 |
| Naive (echo original function) | **0.200** | 0.000 | 1.000 | 0.000 |

The gold policy is a harness check: install, `load_environment`, the sandbox, and the rubric all fire 1.2. The naive policy is a discrimination check: returning the prompt's broken function does not rubber-stamp 1.2 — it fails a visible test on every eval edge, so it never collects partial credit either.

Model row pending a fresh OpenRouter key (`minimax/minimax-m2.7`, T=0, 2048 tok, `--max-concurrent 1`).

```bash
uv run vf-eval unit-fix -n 15 -r 1 -p openrouter \
  -m minimax/minimax-m2.7 --max-tokens 2048 \
  --temperature 0 --max-concurrent 1 --disable-tui --disable-env-server
```

## Installation

```bash
uv pip install -e .
python -m pytest tests/test_unit_fix.py -q
```

From the Hub:

```bash
prime env install devtechedge/unit-fix
```

```python
import verifiers as vf

env = vf.load_environment("unit-fix")
```

Requires `verifiers>=0.1.14,<0.2`.

## `load_environment` arguments

| Arg | Default | Meaning |
| --- | --- | --- |
| `num_train_examples` | `500` | train split size |
| `num_eval_examples` | `100` | eval split size (15 edges prepended) |
| `seed` | `42` | train RNG; eval uses `seed + 1` |
| `family` | `None` | pin to one bug family, or mixed |
| `difficulty` | `None` | `"easy"` \| `"medium"` \| `"hard"` \| mixed |

```bash
uv run vf-eval unit-fix -n 20
uv run vf-eval unit-fix -a '{"family": "with_item", "num_eval_examples": 40}'
```

Dataset rows never use a column named `task`. Verifiers ≥0.1 treats `info["task"]` as a nested rollout payload. Nested tests are JSON-stringified before `Dataset.from_list`.

## Gold solution

Dataset construction **is** the gold solver. Each family has a buggy body and a repair in `FAMILY_IMPL`. `example_from_spec` runs both through the sandbox: gold must pass every test; the original must fail a visible test (so naive cannot farm partial).

```python
from unit_fix import run_tests, gold_completion, naive_completion, grade

run_tests(info["gold_code"], info["func_name"], info["tests"]).all_passed  # True
run_tests(info["buggy_code"], info["func_name"], info["tests"]).all_passed  # False

grade(gold_completion(info["gold_code"]), info["gold_code"], info)["reward"]  # 1.2
grade(naive_completion(info), info["gold_code"], info)["reward"]              # 0.2
```

`tests/test_unit_fix.py` asserts the 15 edges, the sandbox rejects `import os` / dunder escapes / `while True`, and a function that hardcodes the visible expected value scores 0.3 not 1.2.

## Files

```
unit_fix.py                 # generator, sandbox, grader, load_environment
pyproject.toml
README.md
LICENSE
tests/test_unit_fix.py
```

## What this is not

- Not a wrap of HumanEval, MBPP, or any public coding dataset.
- Not LLM-judged.
- Not multi-turn / tool-using (that's meeting-slot).
- Not calendar arithmetic (that's calendar-math).
- Not source-diff matching. Hidden tests are the spec.

## License

MIT

``n
---

## 46. astra-marketplace
- **URL:** https://github.com/devtechedge/astra-marketplace
- **Language:** TypeScript
- **Topics:** admin-dashboard, ecommerce, full-stack, marketplace, nextjs, portfolio, postgresql, prisma, react, seller-portal, tailwindcss, typescript
- **Description:** AstraMart: paper-and-copper marketplace demo. 18-SKU catalog, HMAC demo sessions, seller and admin portals. Next.js 14. Live Vercel is seeded demo data with mock payments. customer@demo.com / Demo123!


### README.md

`markdown
# AstraMart

Independent paper-and-copper marketplace demo with a customer storefront, seller portal, admin back-office, HMAC demo sessions, cart/checkout, returns, recommendations, and a Prisma schema for local production mode. Built as a portfolio demo.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://astra-marketplace.vercel.app/)
[![CI](https://github.com/devtechedge/astra-marketplace/actions/workflows/ci.yml/badge.svg)](https://github.com/devtechedge/astra-marketplace/actions/workflows/ci.yml)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-5-2D3748?logo=prisma)](https://www.prisma.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-06b6d4?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Live Demo

**https://astra-marketplace.vercel.app/**

> **Demo-mode status:** The live Vercel site uses seeded in-memory demo data and mock payments — not Prisma. Catalog browse, search, product photos, health, and coupon GET are public. **Checkout, account, orders, seller, and admin require sign-in.** Full Prisma/PostgreSQL schema + Docker Compose remain the local production foundation. No real payment capture, carrier labels, or object storage.

### Demo credentials

| Role     | Email              | Password  |
|----------|--------------------|-----------|
| Customer | `customer@demo.com` | `Demo123!` |
| Seller   | `seller@demo.com`   | `Demo123!` |
| Admin    | `admin@demo.com`    | `Demo123!` |

Shown on `/login` and this README on purpose for portfolio DX. Passwords are bcrypt-hashed in a server-only module (`src/lib/server/demoUsers.ts`) and are never shipped in the client bundle.

## Screenshots

| Storefront | Account |
|------------|---------|
| ![Storefront](docs/screenshots/01-storefront.png) | ![Account](docs/screenshots/02-account.png) |

| Orders | Seller dashboard |
|--------|------------------|
| ![Orders](docs/screenshots/03-orders.png) | ![Seller](docs/screenshots/04-seller-dashboard.png) |

| Admin operations |
|------------------|
| ![Admin](docs/screenshots/05-admin-ops.png) |

## Features

- **Design system** — paper `#F4EFE6` / surface `#FFFCF7` / ink `#1A1612` / copper `#C45C26` tokens; Fraunces (display) + IBM Plex Sans via `next/font`; Fraunces wordmark with a 4-point copper star; Account menu holds Seller/Admin; overlay scrollbars hidden until overflow + hover/focus
- **Customer storefront** — merchandising hero (not a GMV/SLA pitch), search, deals, product detail, cart, 6-step checkout (login required), orders, tracking, returns, wishlist, gift-card SKUs, AstraPlus membership
- **18-SKU catalog** — real JPEGs in `public/products` (not SVG placeholders) across Electronics, Home & Kitchen, Fashion, Books, Beauty, Sports, Toys, Grocery, Automotive, Pet Supplies, and Gift cards. Header lists Gift cards once via `/gift-cards`
- **Seller portal** — KPI dashboard, listings/inventory, product listing wizard, promotions, payouts, ads, support (signed session)
- **Admin command center** — GMV/orders/refund/SLA metrics, seller & product moderation, support tickets, audit, CMS, feature flags, analytics, search merchandising (signed session)
- **Commerce core** — coupons, tax/shipping calculation, mock payment intents, RMA-style returns, recommendation rows (buy again / trending / recently viewed)
- **Platform services** — HMAC session middleware, API RBAC, origin checks, auth rate limits, webhook secret, CSP without `unsafe-eval`, health API, notifications, review/Q&A endpoints
- **Production foundation** — Prisma schema, Docker Compose, GitHub Actions (unit + typecheck + Playwright), Dependabot, [SECURITY.md](SECURITY.md)

Playwright testids kept: `site-header`, `home-hero`, `add-to-cart`, `shopping-cart`, `login-page`, `seller-dashboard`, `admin-command-center`.

## Tech Stack

| Layer        | Technology |
|--------------|------------|
| Frontend     | Next.js 14 (App Router), TypeScript, Tailwind CSS, Fraunces + IBM Plex Sans via next/font, Lucide |
| Backend      | Next.js API routes, Zod validation |
| Data         | Prisma 5 + PostgreSQL schema (local foundation); seeded demo repository on Vercel |
| Auth         | HMAC cookie sessions + bcrypt demo users (server-only) |
| Tooling      | Vitest, Playwright, ESLint, GitHub Actions |
| Deploy       | Vercel — https://astra-marketplace.vercel.app/ |


## Quick Start

```bash
npm install
npm run dev
```

Open http://localhost:3000

```bash
npm test            # unit — 26 passed (commerce, rbac, validation, session, origin)
npm run typecheck
npm run test:e2e    # Playwright Chromium smokes (signed session cookies)
```

Optional local database (not used by the Vercel demo):

```bash
cp .env.example .env
docker compose up -d
npm run db:generate && npm run db:push && npm run db:seed
```

Set `APP_SECRET` before treating sessions as real. The code has a demo HMAC fallback if it is unset.

## Architecture notes

- Service/repository split for auth, catalog, cart, checkout, fulfillment, returns, seller and admin
- HMAC-SHA256 `astra-session` cookie (httpOnly, SameSite=lax, Secure on Vercel/production, 8h). Missing/invalid session is **GUEST**, never CUSTOMER. `astra-role` is ignored and cleared.
- API RBAC via `requireSession` in `src/lib/security/api.ts`; origin check on mutating `/api` except the payment webhook; auth rate limit 10/10min/IP in memory
- Middleware gates `/admin*`, `/seller*`, `/checkout*`, `/account*`, `/orders*`
- Demo repository powers the live Vercel deploy; swap to Prisma client for real persistence. **Prisma is not live on Vercel.**
- Threat model: [SECURITY.md](SECURITY.md). Deeper docs under `docs/` (ARCHITECTURE, API_SPEC, DEPLOYMENT)

## License

MIT License. See [LICENSE](LICENSE) for details.

``n
---

## 47. devtechedge
- **URL:** https://github.com/devtechedge/devtechedge
- **Language:** Not specified
- **Topics:** None
- **Description:** GitHub profile landing for Devayan Mandal (DevTechEdge): AI/ML and full-stack work across agentic systems, marketplaces, and polished Next.js demos. Index of public repos with live Vercel and GitHub Pages links. Python, TypeScript, React, Next.js, LangGraph, Postgres, Supabase. Portfolio README only—no app, no API keys, no backend. Account home. v1


### README.md

`markdown
# Hi, I'm Dev 👋

### Full Stack & Forward Deployed AI Engineer
⚡ *Architecting autonomous multi-agent systems, Hybrid RAG, HITL workflows, and real-time observability — end to end in Python and Next.js.*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)](https://chatgpt.com)
[![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.ai)

---

## 🚀 Flagship Architectures & Projects

- 🔬 **[Synthesis](https://synthesis-gold.vercel.app/)** – Autonomous multi-agent research: plan → research → synthesize → critique → finalize, with HITL gates, RAG, Reflexion, and live SSE agent graphs ([repo](https://github.com/devtechedge/synthesis)).
- 🛡️ **[AEGIS](https://aegis-agent-api.vercel.app/ui)** – Multi-agent operations cortex: LangGraph supervisor + specialist agents, Hybrid RAG, HITL, streaming SSE, FastAPI ([repo](https://github.com/devtechedge/aegis_vercel)).
- 🧠 **[AAROP](https://aarop.vercel.app)** – Explicit Perceive → Plan → Act → Observe → Reflect → Adapt loop with self-verification, bounded autonomy, and replayable traces ([repo](https://github.com/devtechedge/aarop)).
- ⚖️ **[RegTrace](https://regtrace-ai.vercel.app)** – HITL Web3 compliance copilot mapping packs onto MiCA/VARA with retrieval-bounded findings and article citations ([repo](https://github.com/devtechedge/regulatory_compliance)).
- 🏥 **[Cadence](https://cadence-healthcare.vercel.app/)** – Deep-memory healthcare agent lab: multi-layer patient memory, journey stages, consent-scoped clinician briefs ([repo](https://github.com/devtechedge/healthcare-deep-memory-agents)).
- 🔎 **[Veritas](https://veritas-engine-woad.vercel.app/)** – LangGraph research agent with SSE streaming, Gemini + Tavily when keyed, grounded demo mode otherwise ([repo](https://github.com/devtechedge/veritas-engine)).

---

## 🛠️ Tech Stack

| Category | Tooling, Frameworks & Architecture |
| :--- | :--- |
| **AI Systems & Agents** | Python, LangGraph, LangChain, FastAPI, multi-agent supervisors, explicit state machines, Hybrid RAG / pgvector, HITL gates, SSE telemetry, eval & critique loops, Ollama / local LLMs |
| **Full-stack product surface** | TypeScript, Next.js, React, Tailwind, Drizzle / Prisma, Postgres, Supabase, Docker, Vercel |
| **Backend & observability** | SSE streaming, WebSockets, REST, replayable traces, schema validation, demo/live provider toggles |
| **Also in the toolbox** | Node.js, Bun, Stripe, Solidity / Foundry (Base) when the product needs Web3 |

---

## 🎯 Engineering Philosophy

| Principle | Core Architecture & Realization |
| :--- | :--- |
| **Bounded autonomy** | Explicit state graphs over fragile prompt chaining; schema validation, cost-aware routing, and HITL on irreversible actions. |
| **Retrieval-bounded truth** | Hybrid RAG with citations and hallucination flags — agents argue from sources, not vibes. |
| **Observability first** | Live agent graphs, SSE/WebSocket telemetry, and replayable traces so every decision is inspectable. |
| **Ship the full stack** | Same systems run as FastAPI/Next demos and as durable Python cores with tests — portfolio that behaves like product. |

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dev-ma/)
[![X / Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DevTechEdge)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devtechedge)

``n
---

## 48. viem
- **URL:** https://github.com/devtechedge/viem
- **Language:** Not specified
- **Topics:** None
- **Description:** TypeScript Interface for Ethereum


### README.md

`markdown
src/README.md
``n
---

## 49. appkit
- **URL:** https://github.com/devtechedge/appkit
- **Language:** Not specified
- **Topics:** None
- **Description:** The full stack toolkit to build onchain app UX


### README.md

`markdown
# AppKit

The full stack toolkit to build onchain app UX.

Onboard millions of users to your app in minutes with social & email embedded wallets, web3 wallet login, crypto swaps, on-ramp and more.

🛝 [Demo](https://demo.reown.com) ・🧪 [Laboratory](https://appkit-lab.reown.com) ・📚 [Documentation](https://docs.reown.com/appkit/overview) ・💻 [AppKit Web Examples](https://github.com/reown-com/appkit-web-examples) ・🔗 [Website](https://reown.com/appkit) ・🛟 [Contact us on Discord](https://discord.gg/reown)

<p align="center">
  <img src="https://github.com/reown-com/appkit/blob/HEAD/.github/assets/header.png" alt="" border="0">
</p>

## Features

Refer to the "Features" section of the [AppKit docs](https://docs.reown.com/appkit/features).

- Swaps
- On-Ramp
- Multi Chain
- Multi Wallets
- Smart Accounts
- Telegram Mini Apps
- Sponsored Transactions
- Networks: EVM Chains, Solana, Bitcoin
- AppKit Core: Chain Agnostic
- Authentication: Email & Social Login, One-Click Auth & Sign with X (SIWX)

## AppKit Available SDKs

- [React](https://docs.reown.com/appkit/react/core/installation)
- [Next](https://docs.reown.com/appkit/next/core/installation)
- [Vue](https://docs.reown.com/appkit/vue/core/installation)
- [Nuxt](https://docs.reown.com/appkit/nuxt/core/installation)
- [Svelte](https://docs.reown.com/appkit/svelte/core/installation)
- [Javascript](https://docs.reown.com/appkit/javascript/core/installation)
- [React Native](https://docs.reown.com/appkit/react-native/core/installation)
- [Flutter](https://docs.reown.com/appkit/flutter/core/installation)
- [Android](https://docs.reown.com/appkit/android/core/installation)
- [iOS](https://docs.reown.com/appkit/ios/core/installation)
- [Unity](https://docs.reown.com/appkit/unity/core/installation)

> [!NOTE]
> If you are using Web3Modal v1–v5, please use our [migration guides](https://docs.reown.com/appkit/upgrade/to-reown-appkit-web#migrate-from-web3modal-v5-to-reown-appkit).

## License and Use

This SDK is provided under the **[Reown AppKit] Community License** (“Community License”), that governs, among other things:

- Permitted non-commercial use
- RPC and MAU thresholds for commercial licensing
- Required connection to Reown's proprietary infrastructure
- Redistribution and attribution obligations
- Ownership of modifications
- Mandatory binding arbitration for disputes

**Downloading, installation, integration and use of this SDK constitutes acceptance of the [Reown AppKit Community License](./LICENSE.md).**

``n
---

## 50. rainbowkit
- **URL:** https://github.com/devtechedge/rainbowkit
- **Language:** Not specified
- **Topics:** None
- **Description:** The best way to connect a wallet 🌈 🧰


### README.md

`markdown
<a href="https://rainbowkit.com">
  <img alt="rainbowkit" src="https://user-images.githubusercontent.com/372831/168174718-685980e0-391e-4621-94a1-29bf83979fa5.png" />
</a>

# RainbowKit &nbsp; [![Version](https://img.shields.io/npm/v/@rainbow-me/rainbowkit?colorA=1f2937&colorB=3b82f6&labelColor=1f2937)](https://www.npmjs.com/package/@rainbow-me/rainbowkit) [![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/rainbow-me/rainbowkit)

**The best way to connect a wallet 🌈**

RainbowKit is a [React](https://reactjs.org/) library that makes it easy to add wallet connection to your dapp.

- 🔥 Out-of-the-box wallet management
- ✅ Easily customizable
- 🦄 Built on top of [wagmi](https://wagmi.sh) and [viem](https://viem.sh)

## Quick start

You can scaffold a new RainbowKit + [wagmi](https://wagmi.sh) + [Next.js](https://nextjs.org) app with one of the following commands, using your package manager of choice:

```bash
npm init @rainbow-me/rainbowkit@latest
# or
pnpm create @rainbow-me/rainbowkit@latest
# or
yarn create @rainbow-me/rainbowkit
```

## Documentation

For full documentation, visit [rainbowkit.com](https://rainbowkit.com).

### Try it out

You can use the CodeSandbox links below to try out RainbowKit:

- with [Create React App](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-create-react-app)
- with [Next.js](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-next)
- with [Next.js App Router](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-next-app)
- with [Remix](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-remix)
- with [Vite](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-vite)
- with [React Router](https://codesandbox.io/p/sandbox/github/rainbow-me/rainbowkit/tree/main/examples/with-react-router)

## Examples

The following examples are provided in the [examples](./examples/) folder of this repo.

- `with-create-react-app`
- `with-next`
- `with-next-app`
- `with-next-custom-button`
- `with-next-mint-nft`
- `with-next-siwe-next-auth`
- `with-next-siwe-iron-session`
- `with-remix`
- `with-vite`
- `with-react-router`

### Running examples

To run an example locally, install dependencies.

```bash
pnpm install
```

Then go into an example directory, eg: `with-next`.

```bash
cd examples/with-next
```

Then run the dev script.

```bash
pnpm run dev
```

## Contributing

Please follow our [contributing guidelines](/.github/CONTRIBUTING.md).

## License

Licensed under the MIT License, Copyright © 2022-present [Rainbow](https://rainbow.me).

See [LICENSE](/LICENSE) for more information.

``n
---

