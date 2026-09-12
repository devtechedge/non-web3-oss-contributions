# ⚙️ Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 open-source contributions.

This repository records substantive contributions to established open-source projects across TypeScript, JavaScript, Python, Rust, developer tooling, frameworks, infrastructure, testing, concurrency, portability, security, and reliability.

![Merged](https://img.shields.io/badge/merged-7-brightgreen?logo=git&logoColor=white)

## 📊 Current snapshot

**Latest update:** 13 Sep 2026

## ✅ Merged pull requests

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| <img src="https://github.com/brianc.png?size=40" width="18" /> [brianc/node-postgres](https://github.com/brianc/node-postgres) | [#3772](https://github.com/brianc/node-postgres/pull/3772) | `Connection.sync()` no longer permanently sets `_ending`, so later `ECONNRESET` / `EPIPE` errors are not swallowed.<br><br>The fix restores correct connection-lifetime error propagation.<br><br>Regression and integration coverage protects the behavior. | 11 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14753](https://github.com/pnpm/pnpm/pull/14753) | `lockfile: false` is now respected with `devEngines.packageManager.onFail: download`.<br><br>pnpm skips environment-lockfile synchronization while still downloading and switching to the requested package-manager version.<br><br>Includes Rust and TypeScript changes, tests, and a changeset. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14756](https://github.com/pnpm/pnpm/pull/14756) | `pnpm update pkg@x.y.z` now preserves an existing `^` / `~` manifest operator.<br><br>Supported `npm:` / `jsr:` prefixes are preserved as well.<br><br>This prevents updates from silently changing dependency range or protocol intent. | 10 Sep 2026 |
| <img src="https://github.com/pnpm.png?size=40" width="18" /> [pnpm/pnpm](https://github.com/pnpm/pnpm) | [#14754](https://github.com/pnpm/pnpm/pull/14754) | Non-recursive `pnpm run "/pattern/" --no-bail` no longer terminates sibling scripts after the first failure.<br><br>Pattern-selected scripts can continue as intended under `--no-bail`. | 10 Sep 2026 |
| <img src="https://github.com/SQLMesh.png?size=40" width="18" /> [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | [#6040](https://github.com/SQLMesh/sqlmesh/pull/6040) | `ModelTest.create_test()` now runs on the calling thread.<br><br>This eliminates a race around shared `execution_time` / `time_machine` state when model tests are created across worker threads.<br><br>Test setup is now deterministic and thread-safe. | 10 Sep 2026 |
| <img src="https://github.com/better-auth.png?size=40" width="18" /> [better-auth/better-auth](https://github.com/better-auth/better-auth) | [#11208](https://github.com/better-auth/better-auth/pull/11208) | Added a regression test for the `/phone-number/verify` OpenAPI contract.<br><br>The test locks the expected `requestBody` schema after a Zod `.and(z.record())` intersection.<br><br>This prevents the generated API description from regressing. | 9 Sep 2026 |
| <img src="https://github.com/biomejs.png?size=40" width="18" /> [biomejs/biome](https://github.com/biomejs/biome) | [#11667](https://github.com/biomejs/biome/pull/11667) | Ported `useBetterDomTraversing` from `eslint-plugin-unicorn` into Biome's Rust-based nursery linter.<br><br>The contribution adds the rule implementation and fixtures and integrates it into Biome's analyzer.<br><br>The associated release changeset ships the new rule. | 8 Sep 2026 |

## 🔀 Open pull requests

The repository currently has a number of active upstream contributions across developer tooling, frameworks, infrastructure, testing, concurrency, portability, security, and reliability. These contributions are maintained directly in their respective upstream repositories, and this ledger highlights the substantive work.

## 🧭 Engineering focus

TypeScript · JavaScript · Python · Rust · developer tooling · frameworks · concurrency · portability · security · testing

## 📄 License

MIT
