# ⚙️ Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 open-source contributions.

This repository records substantive contributions to established open-source projects across TypeScript, JavaScript, Python, Rust, developer tooling, frameworks, infrastructure, testing, concurrency, portability, security, and reliability.

![Merged](https://img.shields.io/badge/merged-7-brightgreen?logo=git&logoColor=white)

## 📊 Current snapshot

**Latest update:** 13 Sep 2026

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

The repository currently has a number of active upstream contributions across developer tooling, frameworks, infrastructure, testing, concurrency, portability, security, and reliability. These contributions are maintained directly in their respective upstream repositories, and this ledger highlights the substantive work.

## 🧭 Engineering focus

TypeScript · JavaScript · Python · Rust · developer tooling · frameworks · concurrency · portability · security · testing

## 📄 License

MIT
