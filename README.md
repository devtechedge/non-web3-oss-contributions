# ⚙️ OSS contributions

Public ledger of **upstream open-source contributions** by [@devtechedge](https://github.com/devtechedge).

This repository is now the **single unified contribution ledger** for all upstream OSS work. It records substantive contributions to established projects across TypeScript, JavaScript, Rust, Python, developer tooling, frameworks, infrastructure, testing, concurrency, portability, security, accessibility, wallets, SDKs, blockchain infrastructure, and reliability.

![Upstream PRs](https://img.shields.io/badge/upstream%20PRs-70-black?logo=git&logoColor=white) ![Open PRs](https://img.shields.io/badge/open%20PRs-56-blue?logo=github&logoColor=white) ![Merged](https://img.shields.io/badge/merged-9-brightgreen?logo=git&logoColor=white) ![Closed not merged](https://img.shields.io/badge/closed%20not%20merged-5-red?logo=github&logoColor=white)

## 📊 Current snapshot

**Latest update:** 13 Sep 2026

The former separate Web3 and non-Web3 ledgers are now consolidated here. Future scans, issue claims, PRs, reviews, merges, closures, and no-go decisions use this repository as the single operational record.

## ✅ Merged pull requests

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| <img src="https://github.com/brianc.png?size=40" width="18" /> [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer permanently sets `_ending`, so later `ECONNRESET` / `EPIPE` errors are not swallowed. Regression and integration coverage protects the behavior. | 11 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | `lockfile: false` is respected with `devEngines.packageManager.onFail: download`; package-manager download/switch still works without project lockfile synchronization. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` preserves existing `^` / `~` range operators and supported `npm:` / `jsr:` prefixes. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer terminates sibling scripts after the first failure. | 10 Sep 2026 |
| <img src="https://github.com/SQLMesh.png?size=40" width="18" /> [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | `ModelTest.create_test()` runs on the calling thread, eliminating a race around shared `execution_time` / `time_machine` state. | 10 Sep 2026 |
| <img src="https://github.com/better-auth.png?size=40" width="18" /> [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | Regression coverage locks the `/phone-number/verify` OpenAPI `requestBody` contract after a Zod intersection issue. | 9 Sep 2026 |
| <img src="https://github.com/biomejs.png?size=40" width="18" /> [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Added the `useBetterDomTraversing` nursery lint rule, ported from `eslint-plugin-unicorn`, with fixtures and release integration. | 8 Sep 2026 |
| <img src="https://github.com/anza-xyz.png?size=40" width="18" /> [anza-xyz/kit](https://github.com/anza-xyz/kit) | [#2032](https://github.com/anza-xyz/kit/pull/2032) | Restored `number` predicates in the `getPatternMatchCodec` documentation examples so they match the actual codec typing. | 9 Sep 2026 |
| <img src="https://github.com/thirdweb-dev.png?size=40" width="18" /> [thirdweb-dev/js](https://github.com/thirdweb-dev/js) | [#8938](https://github.com/thirdweb-dev/js/pull/8938) | Genuine `useTokenQuery` request failures are rethrown instead of being converted into `Token Not Supported`; added regression tests and changeset. | 7 Sep 2026 |

## 🔀 Open pull requests

The repository currently tracks active upstream contributions across application libraries, infrastructure, frameworks, developer tooling, testing, security, accessibility, wallets, SDKs, and blockchain-related software. These contributions are maintained directly in their respective upstream repositories, and this ledger records the substantive work and its current state.

## 🧭 Engineering focus

TypeScript · JavaScript · Python · Rust · frameworks · developer tooling · infrastructure · concurrency · portability · security · accessibility · testing · wallets · SDKs · blockchain infrastructure

## 📚 Unified workflow

There is now one queue, one canonical triage record, and one contribution ledger for all OSS targets. Selection is based on upstream quality, contribution eligibility, fit, bounded scope, reproducibility, maintainer posture, and merge potential.

## 🗄️ History

The former separate Web3 and non-Web3 ledgers were consolidated into this repository in September 2026. Historical archive commits from the retired Web3 repository, preserved here as provenance:

- `6cd492a568d75d724013003ff9b714a9296a3482` - docs: archive Web3 ledger into unified OSS ledger
- `8eee58c1305949362c7cf7529e5b5ee873fe3b53` - docs: archive Web3 triage into unified ledger

## 📄 License

MIT
