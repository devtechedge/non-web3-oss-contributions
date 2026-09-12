# Complete Repository Portfolio for @devtechedge

Total Repositories: 87

---

## 1. web3-oss-contributions
- **URL:** https://github.com/devtechedge/web3-oss-contributions
- **Language:** Not specified
- **Topics:** blockchain, ethereum, ethers, rainbowkit, safe, stellar, typescript, wagmi, walletconnect, web3, solana, thirdweb
- **Description:** Public ledger of upstream Web3 pull requests and issue claims. Own-repo work is excluded. Merged: anza-xyz/kit #2032 (getPatternMatchCodec docs) and thirdweb-dev/js #8938 (useTokenQuery). Snapshot 12 Sep 2026: 38 open PRs, 2 merged, 11 closed, 6 issue claims. TypeScript library bugs, adapters, wallet SDKs. Claim first, then fork + PR.

### README.md

# ⛓️ Web3 OSS contributions

Public ledger of **upstream** Web3 pull requests and issue claims by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed; non-Web3 work lives in [non-web3-oss-contributions](https://github.com/devtechedge/non-web3-oss-contributions).

![Total](https://img.shields.io/badge/upstream%20items-60-black?logo=git&logoColor=white) ![Open PRs](https://img.shields.io/badge/open%20PRs-38-blue?logo=github&logoColor=white) ![Merged](https://img.shields.io/badge/merged-2-brightgreen?logo=git&logoColor=white) ![Closed](https://img.shields.io/badge/closed%20not%20merged-11-red?logo=git&logoColor=white) ![Issue claims](https://img.shields.io/badge/issue%20claims-6-blueviolet?logo=git&logoColor=white)

## 📊 Snapshot (12 Sep 2026)

**60 upstream items: 38 open PRs, 2 merged, 11 closed (not merged), 6 issue claims, 3 no-go skips** - across:

<img src="https://github.com/safe-global.png?size=40" width="16"> Safe · <img src="https://github.com/MetaMask.png?size=40" width="16"> MetaMask · <img src="https://github.com/coinbase.png?size=40" width="16"> Coinbase · <img src="https://github.com/rainbow-me.png?size=40" width="16"> RainbowKit · <img src="https://github.com/reown-com.png?size=40" width="16"> Reown AppKit · <img src="https://github.com/across-protocol.png?size=40" width="16"> Across · <img src="https://github.com/stellar.png?size=40" width="16"> Stellar · <img src="https://github.com/wevm.png?size=40" width="16"> viem / wagmi · <img src="https://github.com/ethers-io.png?size=40" width="16"> ethers.js · <img src="https://github.com/tkhq.png?size=40" width="16"> Turnkey · <img src="https://github.com/thirdweb-dev.png?size=40" width="16"> thirdweb · <img src="https://github.com/anza-xyz.png?size=40" width="16"> anza-xyz · <img src="https://github.com/solana-foundation.png?size=40" width="16"> Solana · <img src="https://github.com/wormhole-foundation.png?size=40" width="16"> Wormhole · <img src="https://github.com/farcasterxyz.png?size=40" width="16"> Farcaster · <img src="https://github.com/AmbireTech.png?size=40" width="16"> Ambire

## ✅ Merged

| Repo | PR | What | Merged |
| --- | --- | --- | --- |
| <img src="https://github.com/anza-xyz.png?size=40" width="18" /> [anza-xyz/kit](https://github.com/anza-xyz/kit) | [#2032](https://github.com/anza-xyz/kit/pull/2032) | Docs: `getPatternMatchCodec` example predicates use `number` again (fixes #1810). | 9 Sep 2026 by [`lorisleiva`](https://github.com/lorisleiva) |
| <img src="https://github.com/thirdweb-dev.png?size=40" width="18" /> [thirdweb-dev/js](https://github.com/thirdweb-dev/js) | [#8938](https://github.com/thirdweb-dev/js/pull/8938) | `useTokenQuery` rethrows real errors so CheckoutWidget shows ErrorBanner instead of "Token Not Supported" (fixes #8937). Tests + changeset. | 7 Sep 2026 by [`0xFirekeeper`](https://github.com/0xFirekeeper) |

## 🔀 Open pull requests

| Repo | PR | What | Opened |
| --- | --- | --- | --- |
| <img src="https://github.com/wevm.png?size=40" width="18" /> [wevm/viem](https://github.com/wevm/viem) | [#5084](https://github.com/wevm/viem/pull/5084) | `shouldRetry` handles QuickNode's `-32007` rate-limit code (HTTP 200 + JSON-RPC body), so `retryCount` on `http()` is honored for QuickNode limits (fixes #5082). Unit + end-to-end regressions. Changeset. Note: competing PR [#5083](https://github.com/wevm/viem/pull/5083) targets the same fix. | 12 Sep 2026 |
| <img src="https://github.com/wormhole-foundation.png?size=40" width="18" /> [wormhole-foundation/wormhole-connect](https://github.com/wormhole-foundation/wormhole-connect) | [#4042](https://github.com/wormhole-foundation/wormhole-connect/pull/4042) | Per-token balance-fetch failures after RPC fallback log a clarified "balance unavailable (not confirmed insufficient)" message with structured network/chain/token context; new `normalizeBalanceFetchError` helper redacts RPC URLs, wallet addresses, and credentials (fixes #4040). First-time-contributor workflow approval pending; Socket checks green. | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/stellar-docs](https://github.com/stellar/stellar-docs) | [#2853](https://github.com/stellar/stellar-docs/pull/2853) | Pooled-accounts guide no longer frames memos as a thing of the past in the intro while later sections say to keep supporting them: memos framed as the legacy mechanism still in use, muxed accounts preferred long term, guide covers both (fixes #2769). Checks green. | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/stellar-docs](https://github.com/stellar/stellar-docs) | [#2851](https://github.com/stellar/stellar-docs/pull/2851) | Frontend guide qualifies the Freighter HTTPS requirement: loopback origins are secure contexts per the W3C spec, so plain HTTP works on localhost; HTTPS steps kept as optional (fixes #2773). | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/freighter](https://github.com/stellar/freighter) | [#3009](https://github.com/stellar/freighter/pull/3009) | `makeDisplayableBalances` skips the Blockaid `scan-asset-bulk` call when no scannable assets exist - the empty token list errored and wasted rate limit (fixes #2905). | 12 Sep 2026 |
| <img src="https://github.com/trustwallet.png?size=40" width="18" /> [trustwallet/wallet-core](https://github.com/trustwallet/wallet-core) | [#4868](https://github.com/trustwallet/wallet-core/pull/4868) | Cardano compile: `buildTx` failures return a `SigningOutput` with the error code instead of throwing a protobuf enum past the `std::exception` catch boundary (fixes #4795). | 12 Sep 2026 |
| <img src="https://github.com/trustwallet.png?size=40" width="18" /> [trustwallet/wallet-core](https://github.com/trustwallet/wallet-core) | [#4867](https://github.com/trustwallet/wallet-core/pull/4867) | Rust `TWData` zeroizes its buffer on drop; `into_vec` hands the buffer over via `mem::take` so conversion stays allocation-free (fixes #4841). | 12 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-docs](https://github.com/safe-global/safe-docs) | [#905](https://github.com/safe-global/safe-docs/pull/905) | Protocol Kit signatures guide: prose said `safe1_1` where the code builds `SAFE_2_3_ADDRESS` (fixes #825). | 12 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-docs](https://github.com/safe-global/safe-docs) | [#904](https://github.com/safe-global/safe-docs/pull/904) | Multi-chain deployment: dropped ZKSyncEra from the non-EVM exception since zkSync is EVM compatible (fixes #828). | 12 Sep 2026 |
| <img src="https://github.com/solana-foundation.png?size=40" width="18" /> [solana-foundation/program-examples](https://github.com/solana-foundation/program-examples) | [#732](https://github.com/solana-foundation/program-examples/pull/732) | `pda-rent-payer`: caution note above `create_new_account` in anchor / native / pinocchio flavors on the unrestricted caller and the authority checks a real rent vault needs (fixes #671). AI disclosure per repo CI policy. | 12 Sep 2026 |
| <img src="https://github.com/solana-foundation.png?size=40" width="18" /> [solana-foundation/program-examples](https://github.com/solana-foundation/program-examples) | [#731](https://github.com/solana-foundation/program-examples/pull/731) | `token-fundraiser`: maker-callable `teardown` for failed campaigns - duration elapsed, all contributions refunded, then strays swept to maker and vault + fundraiser closed. Anchor only (pinocchio port #708 closed unmerged). 2 LiteSVM regressions. AI disclosure per repo CI policy; anchor build waits on first-time-contributor workflow approval (fixes #725). | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/stellar-docs](https://github.com/stellar/stellar-docs) | [#2850](https://github.com/stellar/stellar-docs/pull/2850) | Document the shipped `--enable-core-manual-close` quickstart flag (fixes #2772). Checks green. | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/stellar-docs](https://github.com/stellar/stellar-docs) | [#2849](https://github.com/stellar/stellar-docs/pull/2849) | Error handling instead of `unwrap()` on untrusted XDR in the address-conversion example (fixes #2768). Checks green. | 11 Sep 2026 |
| <img src="https://github.com/tkhq.png?size=40" width="18" /> [tkhq/sdk](https://github.com/tkhq/sdk) | [#1519](https://github.com/tkhq/sdk/pull/1519) | Docs: TypeScript samples match current exports and pass strict-mode checks (fixes #1501). | 11 Sep 2026 |
| <img src="https://github.com/across-protocol.png?size=40" width="18" /> [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#275](https://github.com/across-protocol/toolkit/pull/275) | `percentageString` rejects decimal-point strings; guarded BigInt pct parsing (fixes #266). | 11 Sep 2026 |
| <img src="https://github.com/across-protocol.png?size=40" width="18" /> [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#274](https://github.com/across-protocol/toolkit/pull/274) | Docs: correct `executeSwapQuote` step and route example (fixes #267). | 9 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1725](https://github.com/stellar/js-stellar-sdk/pull/1725) | Wire `docs/migration/` into the Starlight sidebar so migration pages are reachable (fixes #1674). | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1432](https://github.com/safe-global/safe-core-sdk/pull/1432) | 4337 tests use disposable private keys instead of a shared hardcoded key (fixes #938). | 9 Sep 2026 |
| <img src="https://github.com/farcasterxyz.png?size=40" width="18" /> [farcasterxyz/miniapps](https://github.com/farcasterxyz/miniapps) | [#626](https://github.com/farcasterxyz/miniapps/pull/626) | `openUrl` validates HTTPS scheme before dispatch (fixes #590). | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-wallet-monorepo](https://github.com/safe-global/safe-wallet-monorepo) | [#8687](https://github.com/safe-global/safe-wallet-monorepo/pull/8687) | Sending to a Safe owner shows "co-signer address" instead of "unknown address" (fixes #8672). | 9 Sep 2026 |
| <img src="https://github.com/coinbase.png?size=40" width="18" /> [coinbase/coinbase-wallet-sdk](https://github.com/coinbase/coinbase-wallet-sdk) | [#1910](https://github.com/coinbase/coinbase-wallet-sdk/pull/1910) | WalletLink snackbar / redirect dialog keyboard and screen-reader a11y (fixes #1909). | 9 Sep 2026 |
| <img src="https://github.com/across-protocol.png?size=40" width="18" /> [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#273](https://github.com/across-protocol/toolkit/pull/273) | `waitForFillByDepositTx` timeout and reject path so polling cannot run forever (fixes #271). | 9 Sep 2026 |
| <img src="https://github.com/across-protocol.png?size=40" width="18" /> [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#272](https://github.com/across-protocol/toolkit/pull/272) | `parseFillLogs` returns `undefined` on empty logs instead of throwing (fixes #268). | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-docs](https://github.com/safe-global/safe-docs) | [#902](https://github.com/safe-global/safe-docs/pull/902) | Fix incorrect contract filename in fallback handler tutorial (fixes #826). Approved by collaborator; commits signed. | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1431](https://github.com/safe-global/safe-core-sdk/pull/1431) | `generateHash` truncates by bytes, not chars; identifier version `00` → `01` (fixes #1424). | 9 Sep 2026 |
| <img src="https://github.com/MetaMask.png?size=40" width="18" /> [MetaMask/metamask-sdk](https://github.com/MetaMask/metamask-sdk) | [#1401](https://github.com/MetaMask/metamask-sdk/pull/1401) | Gate RN async-storage require so web bundles stop warning (fixes #1376). | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1430](https://github.com/safe-global/safe-core-sdk/pull/1430) | Document MultiSend batching for protocol-kit (fixes #1182). | 9 Sep 2026 |
| <img src="https://github.com/across-protocol.png?size=40" width="18" /> [across-protocol/sdk](https://github.com/across-protocol/sdk) | [#1533](https://github.com/across-protocol/sdk/pull/1533) | Apply configured gas/capital discount percents in `relayerFeeDetails` (fixes #1449). | 9 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1723](https://github.com/stellar/js-stellar-sdk/pull/1723) | Docs: optional-null rewrite guidance + Jest CJS note (fixes #1685 / #1686). | 9 Sep 2026 |
| <img src="https://github.com/AmbireTech.png?size=40" width="18" /> [AmbireTech/extension](https://github.com/AmbireTech/extension) | [#29](https://github.com/AmbireTech/extension/pull/29) | Surface RPC forwarding errors via `console.debug` in prod inpage (fixes #23). | 9 Sep 2026 |
| <img src="https://github.com/safe-global.png?size=40" width="18" /> [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1426](https://github.com/safe-global/safe-core-sdk/pull/1426) | Keep `TransactionOptions.nonce = 0` instead of truthiness-dropping it. Tests + changeset. CLA signed. (fixes #1425) | 7 Sep 2026 |
| <img src="https://github.com/reown-com.png?size=40" width="18" /> [reown-com/appkit](https://github.com/reown-com/appkit) | [#5767](https://github.com/reown-com/appkit/pull/5767) | `createNamespaces` uses `caipNetworkId` so non-EVM aliases are not advertised as WC chain ids (fixes #5552). | 7 Sep 2026 |
| <img src="https://github.com/wevm.png?size=40" width="18" /> [wevm/wagmi](https://github.com/wevm/wagmi) | [#5240](https://github.com/wevm/wagmi/pull/5240) | `reconnect()` no longer strands on `reconnecting` when `isAuthorized()` rejects (fixes #5233). Changeset. | 6 Sep 2026 |
| <img src="https://github.com/reown-com.png?size=40" width="18" /> [reown-com/appkit](https://github.com/reown-com/appkit) | [#5766](https://github.com/reown-com/appkit/pull/5766) | Meld on-ramp URL gets `countryCode` so the widget does not fabricate a receive amount (fixes #5752). Changeset. | 6 Sep 2026 |
| <img src="https://github.com/rainbow-me.png?size=40" width="18" /> [rainbow-me/rainbowkit](https://github.com/rainbow-me/rainbowkit) | [#2703](https://github.com/rainbow-me/rainbowkit/pull/2703) | Mobile connecting screen shows GET / store link when the wallet app may be missing (fixes #2574). Changeset. | 6 Sep 2026 |
| <img src="https://github.com/ethers-io.png?size=40" width="18" /> [ethers-io/ethers.js](https://github.com/ethers-io/ethers.js) | [#5186](https://github.com/ethers-io/ethers.js/pull/5186) | Expose `Signature._yParity` and serialize raw yParity for non-canonical authorization values (fixes #5091). | 6 Sep 2026 |
| <img src="https://github.com/reown-com.png?size=40" width="18" /> [reown-com/appkit](https://github.com/reown-com/appkit) | [#5763](https://github.com/reown-com/appkit/pull/5763) | Accessible names on the modal card and header icon buttons. | 4 Sep 2026 |
| <img src="https://github.com/rainbow-me.png?size=40" width="18" /> [rainbow-me/rainbowkit](https://github.com/rainbow-me/rainbowkit) | [#2701](https://github.com/rainbow-me/rainbowkit/pull/2701) | Account modal accessible name: pass `titleId` into `ProfileDetails` (fixes #2700). | 3 Sep 2026 |

## 🚫 Closed (not merged)

| Repo | PR | Why closed | Closed |
| --- | --- | --- | --- |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1715](https://github.com/stellar/js-stellar-sdk/pull/1715), [#1721](https://github.com/stellar/js-stellar-sdk/pull/1721), [#1722](https://github.com/stellar/js-stellar-sdk/pull/1722), [#1724](https://github.com/stellar/js-stellar-sdk/pull/1724) | Maintainer close: repo accepts PRs only when invited on `help wanted` issues. | 11 Sep 2026 |
| <img src="https://github.com/wevm.png?size=40" width="18" /> [wevm/viem](https://github.com/wevm/viem) | [#5070](https://github.com/wevm/viem/pull/5070), [#5071](https://github.com/wevm/viem/pull/5071) | Closed by maintainer, not merged. | 9 Sep 2026 |
| <img src="https://github.com/wevm.png?size=40" width="18" /> [wevm/viem](https://github.com/wevm/viem) | [#5065](https://github.com/wevm/viem/pull/5065) | Closed by author, not merged. | 4 Sep 2026 |
| <img src="https://github.com/solana-foundation.png?size=40" width="18" /> [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3882](https://github.com/solana-foundation/solana-web3.js/pull/3882) | v1.x is maintenance-only; not accepting PRs. | 6 Sep 2026 |
| <img src="https://github.com/anza-xyz.png?size=40" width="18" /> [anza-xyz/kit](https://github.com/anza-xyz/kit) | [#2033](https://github.com/anza-xyz/kit/pull/2033) | Superseded by merged [#2032](https://github.com/anza-xyz/kit/pull/2032). | 6 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1714](https://github.com/stellar/js-stellar-sdk/pull/1714) | Closed in favor of [#1715](https://github.com/stellar/js-stellar-sdk/pull/1715). | 6 Sep 2026 |
| <img src="https://github.com/solana-foundation.png?size=40" width="18" /> [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3881](https://github.com/solana-foundation/solana-web3.js/pull/3881) | Duplicate of [#3882](https://github.com/solana-foundation/solana-web3.js/pull/3882). | 6 Sep 2026 |

## 🎯 Issue claims

Issues claimed on [drips-network/app](https://github.com/drips-network/app) on 3 Sep 2026 (all open and unassigned, re-checked 11 Sep 2026), on [wormhole-foundation/wormhole-connect](https://github.com/wormhole-foundation/wormhole-connect) on 12 Sep 2026 (PR [#4042](https://github.com/wormhole-foundation/wormhole-connect/pull/4042) opened), and on [stellar/stellar-docs](https://github.com/stellar/stellar-docs) on 12 Sep 2026 (PR [#2853](https://github.com/stellar/stellar-docs/pull/2853) opened).

| Issue | What |
| --- | --- |
| <img src="https://github.com/wormhole-foundation.png?size=40" width="18" /> [#4040](https://github.com/wormhole-foundation/wormhole-connect/issues/4040) | Per-token balance-fetch errors after RPC fallback read as insufficient balance; clarify wording, add structured context and safe error normalization. |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [#2769](https://github.com/stellar/stellar-docs/issues/2769) | Pooled-accounts guide opens by framing memos as a thing of the past, then instructs readers to keep supporting them; rework the intro so the framing is consistent. |
| <img src="https://github.com/drips-network.png?size=40" width="18" /> [#1845](https://github.com/drips-network/app/issues/1845) | Create-stream UI: Drip List URL replaced with internal account ID, then fails `validatedValue`. |
| <img src="https://github.com/drips-network.png?size=40" width="18" /> [#1509](https://github.com/drips-network/app/issues/1509) | Transaction timeline titles should follow status (Approve → Approving → Approved). |
| <img src="https://github.com/drips-network.png?size=40" width="18" /> [#1576](https://github.com/drips-network/app/issues/1576) | Hide the step index when a flow has only one transaction. |
| <img src="https://github.com/drips-network.png?size=40" width="18" /> [#1500](https://github.com/drips-network/app/issues/1500) | Drip List chips still mount the `.name` row when name/owner are hidden. |

## ⛔ Already tried, no-go

Verified and deliberately skipped - recorded here so scan agents do not spend time re-checking these targets.

| Repo | Issue | Why no-go | Checked |
| --- | --- | --- | --- |
| <img src="https://github.com/AmbireTech.png?size=40" width="18" /> [AmbireTech/extension](https://github.com/AmbireTech/extension) | [#28](https://github.com/AmbireTech/extension/issues/28) | Bug confirmed on main, but maintainers took ownership on 2 Sep 2026 and are designing the `portfolio-additional` endpoint split - do not revisit until they follow up. | 12 Sep 2026 |
| <img src="https://github.com/stellar.png?size=40" width="18" /> [stellar/freighter](https://github.com/stellar/freighter) | [#2926](https://github.com/stellar/freighter/issues/2926) | signMessage confirmation view missing its header, overlaid text illegible. Clean on paper (open, unassigned, no competing PR), but stellar/* repos are no-go without an explicit maintainer invite on the specific issue (directive 12 Sep 2026) and none exists here; also borderline stale, filed 31 Jul 2026. | 12 Sep 2026 |
| <img src="https://github.com/trustwallet.png?size=40" width="18" /> [trustwallet/wallet-core](https://github.com/trustwallet/wallet-core) | [#4860](https://github.com/trustwallet/wallet-core/issues/4860) | Solana SPL amount 1000x bug is app-layer, not in the library: wallet-core has no Solana Pay URI parsing and the signing proto takes a raw amount plus explicit decimals from the caller. A library-side fix would be a new URI-parsing feature needing maintainer buy-in first. | 12 Sep 2026 |

## 📄 License

MIT. See [LICENSE](LICENSE).


---

## 2. stellar-docs
- **URL:** https://github.com/devtechedge/stellar-docs
- **Language:** MDX
- **Topics:** None
- **Description:** Documentation for Stellar

### README.md

# Stellar Documentation and API Reference 🌌 <!-- omit in toc -->

[![Apache 2.0 licensed](https://img.shields.io/badge/license-apache%202.0-blue.svg)](LICENSE)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/stellar/stellar-docs)

Welcome to the official home repository for [Documentation][docs] for the [Stellar network][stellar].

## Table of Contents <!-- omit in toc -->

- [Contributing](#contributing)
- [Quick Start](#quick-start)
  - [Prerequisites](#prerequisites)
  - [Development](#development)
- [Repository Structure](#repository-structure)
- [Using Markdown](#using-markdown)
  - [Markdown Basics](#markdown-basics)
  - [Custom Markdown](#custom-markdown)

## Contributing

Contributions are more than welcome! Thank you! 🎉

Before diving in, please read our [Stellar Contribution Guide][contrib] for
details on contributing to Stellar's various repositories. Please take special
note of the [code of conduct][coc].

Our documentation site is built using [Docusaurus][docusaurus]. The content is
written in [MDX][mdx], which adds a lot of cool possibilities. Even if you're
unfamiliar with plain markdown, do not fear! You can still contribute in a
helpful and meaningful way. Markdown is super easy to learn, and will come quite
naturally after only a bit of practice. You can always help fix typos, spelling,
and broken links, too.

You can contribute to the docs in several ways:

- See something that needs to be fixed in the docs, like an error in the code or a typo? File a [pull request (PR)](https://github.com/stellar/stellar-docs/pulls) proposing to correct the error;
- Think there is helpful content missing from the docs, like a specific how-to guide or piece of explanatory content? File an [issue](https://github.com/stellar/stellar-docs/issues) explaining what you’d like to see (be sure to search existing issues to avoid duplication);
- Have an idea that could make the docs better, like a structural change or a new section idea? File an [issue](https://github.com/stellar/stellar-docs/issues) explaining what you’d like to see (these will be added to the Ideas section on the [Dev Docs board](https://github.com/orgs/stellar/projects/56/views/1) for discussion);
- Want to complete an existing issue? Search through the issues to find something to work on! Issues without an assignee and labeled as a “Good First Issue” or with “Help Wanted” are great places to start! Once you’ve selected an issue to work on, file a PR with your proposed fix.

No matter what you contribute, whether a PR or an issue, you can expect to receive a response from docs maintainers within one week.

- PRs need to be reviewed and approved before merging. Look for either an approval or a follow-up question.
- Issues will be prioritized, labeled, and assigned (if possible). You can check the status of your issue on the Dev Docs board. The status of issues according to the column is:
  - Ideas: these issues are being actively discussed. Ideas will either be discarded or repurposed into an actionable issue and added to the queue within three weeks.
  - Backlog: these issues are not prioritized or actively being worked on.
  - To Do: these issues are prioritized and will be worked on soon.
  - In Progress: these issues are currently being worked on.
  - Blocked: these issues are being worked on but are blocked for some reason and need attention.
  - Done: these issues have been completed and can be closed.

If you have questions, feel free to ask in the [Stellar Developer Discord](https://discord.gg/stellardev).

## Quick Start

[![Open in Codespaces](https://github.com/codespaces/badge.svg)][open-in-github-codespaces]

[![Open in Codeanywhere](https://codeanywhere.com/img/open-in-codeanywhere-btn.svg)][open-in-code-anywhere]

### Prerequisites

To begin development on the documentation, you will first need to install the following:

- Node.js (v24, or higher): see https://nodejs.org/en/download/package-manager for details for your system
- pnpm: e.g., `corepack enable pnpm`

### Development

Once all the prerequisites have been installed, you can run the following commands:

```bash
git clone https://github.com/stellar/stellar-docs
cd stellar-docs
pnpm install
pnpm start
```

This will begin the development server, and open a browser window/tab pointing
to `http://localhost:3000/docs/`. This development server will auto-reload when
it detects changes to the repository.

> **Already cloned this repo before we moved to pnpm?** Delete the old
> `node_modules` directory before running `pnpm install` — pnpm uses a different
> `node_modules` layout than Yarn, so installing on top of an existing one can
> fail.

After you've made your changes, use the following commands to ensure the consistent
MDX file formatting and style across the repository:

```bash
pnpm check:mdx # this will search for problems in the MDX files
pnpm format:mdx # this will fix any problems that were found
```

After that you need to build the `routes.txt` file, to do that run the next command

```bash
pnpm build
```

## Repository Structure

- `/docs/` Contains all the documentation content. If you're contributing to the
  actual documentation, rather than site functionality, this is likely where you
  will want to be.
  - `/docs/<subdirectory>/` Each subdirectory inside the `docs` directory
    contains content documents relating to a common idea (asset issuance, or
    running a validator node, for example). There can also be subdirectories
    nested even further, which will follow the same rules. The location of a
    document within this directory structure will have a direct impact on the
    URL given to the document on the site (unless there is metadata or front
    matter that overrides these defaults.)
  - `/docs/<subdirectory>/_category_.json` This file contains information that
    determines the directory's location and position within the site's sidebar.
  - `/docs/<subdirectory>/<filename>.mdx` The actual documents live in these
    files (written in Markdown), and also contains "front matter" which can
    specify configuration parameter for the document's display, URL, etc. **All
    filenames must use dashes for spaces instead of spaces or underscores**
- `/src/` Contains non-documentation files like custom React components and
  styling.
- `/static/` Contains static assets. Anything in this directory will be copied
  to the root of the final `build` directory.
- `/nginx/` Contains configuration used to deploy and host the docs site. Unless
  you're part of Stellar's IT Ops team, you probably don't need to do anything
  with this. *Exception*:
  - `/nginx/includes/redirects.conf` Contains redirect rules to avoid broken
    links. If you find a broken link somewhere out in the wilds of the internet,
    and there's no way for it to be changed, a redirect could be a useful tool.
    (Note our aim isn't to *completely* avoid 404 pages for a user. That would
    be impossible and impractical. These redirects are evaluated on a
    case-by-case basis, and it may be determined that a redirect isn't the right
    approach in some instances.)

## Using Markdown

### Markdown Basics

If you're unfamiliar with Markdown, there are **loads** of good tutorials and
cheat sheets out there. Check out some of these resources to get a handle on the
basics:

- [CommonMark cheat sheet and tutorial][commonmark]
- [Interactive markdown tutorial][tutorial]
- [The markdown guide][guide]

### Custom Markdown

Our repository uses some custom React components that can be used inside the
`MDX` documents. Use them as follows:

**Make sure that there is an empty line within the wrapper.** For example,

````markdown
<CodeExample>
<!-- EMPTY LINE AFTER THE COMPONENT'S OPENING TAG IS REQUIRED -->

```javascript
console.log("hello world");
```

```python
print("hello world")
```

<!-- EMPTY LINE BEFORE THE COMPONENT'S CLOSING TAG IS REQUIRED -->
</CodeExample>
````

#### Code Example

![Create account code example](./static/img/github/code-example.png)

`<CodeExample />` is a code snippet component. You can use this component when
you want to include snippets for more than one language. See an example
including a snippet for `JavaScript` and `Python` below. It is using [Prism
React Renderer][prism] for syntax highlighting. If you're only making a code
snippet for a _single programming language_, you should just stick with a
"normal" markdown code fence using backticks.

> [!NOTE]
> The `CodeExample` component has been added to the list of globally available
> components, in `/src/theme/MDXComponents.ts`. This means it's not required to
> `import { CodeExample } ...` in a page if you're planning to use it. It's just
> always available in MDX file.

````markdown
<CodeExample>

```js
// create a completely new and unique pair of keys
// see more about KeyPair objects: https://stellar.github.io/js-stellar-sdk/Keypair.html
const pair = StellarSdk.Keypair.random();

pair.secret();
// SAV76USXIJOBMEQXPANUOQM6F5LIOTLPDIDVRJBFFE2MDJXG24TAPUU7
pair.publicKey();
// GCFXHS4GXL6BVUCXBWXGTITROWLVYXQKQLF4YH5O5JT3YZXCYPAFBJZB
```

```python
# stellar-sdk >= 2.0.0 required
# create a completely new and unique pair of keys
# see more about KeyPair objects: https://stellar-sdk.readthedocs.io/en/latest/api.html#keypair
from stellar_sdk import Keypair

pair = Keypair.random()
print(f"Secret: {pair.secret}")
# Secret: SCMDRX7A7OVRPAGXLUVRNIYTWBLCS54OV7UH2TF5URSG4B4JQMUADCYU
print(f"Public Key: {pair.public_key}")
# Public Key: GAG7SXULMNWCW6LX42JKZOZRA2JJXQT23LYY32OXA6XECUQG7RZTQJHO
```

</CodeExample>
````

Languages that are currently being used in Documentation and API Reference are
below. This snippet is copied from `config/constants.ts` and is **only the
subset of languages used as `CodeExample` tab labels**, not every language
Prism can highlight. If you add a fenced language in docs, add the same key
here *and* in `config/constants.ts` so the tab does not fall back to
“Example”.

```js
// https://github.com/stellar/stellar-docs/blob/main/config/constants.ts

export const CODE_LANGS = {
  bash: 'bash',
  cpp: 'C++',
  css: 'CSS',
  curl: 'cURL',
  dart: 'Flutter',
  flutter: 'Flutter',
  swift: 'Swift',
  docker: 'Dockerfile',
  go: 'Go',
  html: 'HTML',
  kotlin: 'Kotlin',
  kt: 'Kotlin',
  java: 'Java',
  javascript: 'JavaScript',
  js: 'JavaScript',
  jsx: 'JSX',
  json: 'JSON',
  json5: 'JSON5',
  python: 'Python',
  scss: 'SCSS',
  sql: 'SQL',
  rust: 'Rust',
  php: 'PHP',
  toml: 'TOML',
  ts: 'TypeScript',
  tsx: 'TSX',
  typescript: 'TypeScript',
  yaml: 'YAML',
};
```

**Remember that this is a community; we build together! 🫱🏻‍🫲🏽 Our code of conduct is [here](https://stellar.org/community/code-of-conduct) and our Privacy Policy is [here](https://stellar.org/privacy-policy).**

[docs]: https://developers.stellar.org/docs
[stellar]: https://stellar.org
[contrib]: https://github.com/stellar/.github/blob/master/CONTRIBUTING.md
[coc]: https://github.com/stellar/.github/blob/master/CODE_OF_CONDUCT.md
[docusaurus]: https://docusaurus.io
[mdx]: https://mdxjs.com
[commonmark]: https://commonmark.org/help/
[tutorial]: https://www.markdowntutorial.com/
[guide]: https://www.markdownguide.org/
[prism]: https://github.com/FormidableLabs/prism-react-renderer
[open-in-github-codespaces]: https://github.com/codespaces/new?repo=stellar/stellar-docs&editor=web
[open-in-code-anywhere]: https://app.codeanywhere.com/#https://github.com/stellar/stellar-docs


---

## 3. non-web3-oss-contributions
- **URL:** https://github.com/devtechedge/non-web3-oss-contributions
- **Language:** Not specified
- **Topics:** opensource, pull-requests, tanstack, tanstack-router, tanstack-start, typescript, contributions, javascript, oss, vite, vitest, better-auth, biome, drizzle, langgraph, rust
- **Description:** Public ledger of upstream non-Web3 pull requests. Own-repo work excluded. Merged: biomejs/biome #11667 (useBetterDomTraversing rule) and brianc/node-postgres #3772 (Connection.sync fix). Snapshot 12 Sep 2026: 11 open PRs, 7 merged, 5 closed. TypeScript and Python library fixes. Claim first, then fork + PR.

### README.md

# ⚙️ Non-Web3 OSS contributions

Public ledger of **upstream** non-Web3 pull requests by [@devtechedge](https://github.com/devtechedge). Web3 work lives in [web3-oss-contributions](https://github.com/devtechedge/web3-oss-contributions).

![Total](https://img.shields.io/badge/upstream%20items-23-black?logo=git&logoColor=white) ![Open PRs](https://img.shields.io/badge/open%20PRs-11-blue?logo=github&logoColor=white) ![Merged](https://img.shields.io/badge/merged-7-brightgreen?logo=git&logoColor=white) ![Closed](https://img.shields.io/badge/closed%20not%20merged-5-red?logo=git&logoColor=white)

## 📊 Status

**23 external upstream PRs** as of 12 Sep 2026, 5 closed without merge. First merge [biomejs/biome#11667](https://github.com/biomejs/biome/pull/11667) on 8 Sep; latest merge [brianc/node-postgres#3772](https://github.com/brianc/node-postgres/pull/3772) on 11 Sep.

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

- Opened 12 Sep with an explicit override of the design gate: [vercel/next.js#98593](https://github.com/vercel/next.js/pull/98593) for [#98417](https://github.com/vercel/next.js/issues/98417) after the approach comment went unanswered; competing PR [#98556](https://github.com/vercel/next.js/pull/98556) implements the same semantics. Queue resumes at [mswjs/msw#2401](https://github.com/mswjs/msw/issues/2401).

## 📄 License

MIT


---

## 4. viem
- **URL:** https://github.com/devtechedge/viem
- **Language:** TypeScript
- **Topics:** None
- **Description:** TypeScript Interface for Ethereum

### README.md

<!-- > [!IMPORTANT] -->
<!-- > Viem is participating in Gitcoin Grants round 21. Consider <a href="https://explorer.gitcoin.co/#/round/42161/389/73">supporting the project</a>. Thank you. 🙏 -->

<br/>

<p align="center">
  <a href="https://viem.sh">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/viem/main/.github/gh-logo-dark.svg">
        <img alt="viem logo" src="https://raw.githubusercontent.com/wevm/viem/main/.github/gh-logo-light.svg" width="auto" height="60">
      </picture>
</a>
</p>

<p align="center">
  TypeScript Interface for Ethereum
<p>

<p align="center">
  <a href="https://www.npmjs.com/package/viem">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/v/viem?colorA=21262d&colorB=21262d&style=flat">
      <img src="https://img.shields.io/npm/v/viem?colorA=f6f8fa&colorB=f6f8fa&style=flat" alt="Version">
    </picture>
  </a>
  <a href="https://app.codecov.io/gh/wevm/viem">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/codecov/c/github/wevm/viem?colorA=21262d&colorB=21262d&style=flat">
      <img src="https://img.shields.io/codecov/c/github/wevm/viem?colorA=f6f8fa&colorB=f6f8fa&style=flat" alt="Code coverage">
    </picture>
  </a>
  <a href="https://github.com/wevm/viem/blob/main/LICENSE">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/l/viem?colorA=21262d&colorB=21262d&style=flat">
      <img src="https://img.shields.io/npm/l/viem?colorA=f6f8fa&colorB=f6f8fa&style=flat" alt="MIT License">
    </picture>
  </a>
  <a href="https://www.npmjs.com/package/viem">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/dm/viem?colorA=21262d&colorB=21262d&style=flat">
      <img src="https://img.shields.io/npm/dm/viem?colorA=f6f8fa&colorB=f6f8fa&style=flat" alt="Downloads per month">
    </picture>
  </a>
  <a href="https://bestofjs.org/projects/viem">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/endpoint?colorA=21262d&colorB=21262d&style=flat&url=https://bestofjs-serverless.now.sh/api/project-badge?fullName=wevm%2Fviem%26since=daily">
      <img src="https://img.shields.io/endpoint?colorA=f6f8fa&colorB=f6f8fa&style=flat&url=https://bestofjs-serverless.now.sh/api/project-badge?fullName=wevm%2Fviem%26since=daily" alt="Best of JS">
    </picture>
  </a>
</p>

<br>

## Features

- Abstractions over the [JSON-RPC API](https://ethereum.org/en/developers/docs/apis/json-rpc/) to make your life easier
- First-class APIs for interacting with [Smart Contracts](https://ethereum.org/en/glossary/#smart-contract)
- Language closely aligned to official [Ethereum terminology](https://ethereum.org/en/glossary/)
- Import your Browser Extension, WalletConnect or Private Key Wallet
- Browser native [BigInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt), instead of large BigNumber libraries
- Utilities for working with [ABIs](https://ethereum.org/en/glossary/#abi) (encoding/decoding/inspection)
- TypeScript ready ([infer types](https://viem.sh/docs/typescript) from ABIs and EIP-712 Typed Data)
- First-class support for [Anvil](https://book.getfoundry.sh/), [Hardhat](https://hardhat.org/) & [Ganache](https://trufflesuite.com/ganache/)
- Test suite running against [forked](https://ethereum.org/en/glossary/#fork) Ethereum network

... and a lot more.

## Overview

```ts
// 1. Import modules.
import { createPublicClient, http } from 'viem';
import { mainnet } from 'viem/chains';

// 2. Set up your client with desired chain & transport.
const client = createPublicClient({
  chain: mainnet,
  transport: http(),
});

// 3. Consume an action!
const blockNumber = await client.getBlockNumber();
```

## Documentation

[Head to the documentation](https://viem.sh/docs/getting-started) to read and learn more about viem.

## Community

Check out the following places for more viem-related content:

- Follow [@wevm_dev](https://twitter.com/wevm_dev), [@_jxom](https://twitter.com/_jxom), and [@awkweb](https://twitter.com/awkweb) on Twitter for project updates
- Join the [discussions on GitHub](https://github.com/wevm/viem/discussions)
- [Share your project/organization](https://github.com/wevm/viem/discussions/104) that uses viem

## Support

- [GitHub Sponsors](https://github.com/sponsors/wevm?metadata_campaign=docs_support)
- [Gitcoin Grant](https://wagmi.sh/gitcoin)
- [wevm.eth](https://etherscan.io/name-lookup-search?id=wevm.eth)

## Sponsors

<a href="https://paradigm.xyz">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/paradigm-dark.svg">
    <img alt="paradigm logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/paradigm-light.svg" width="auto" height="70">
  </picture>
</a>
<a href="https://tempo.xyz">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/tempo-dark.svg">
    <img alt="tempo logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/tempo-light.svg" width="auto" height="70">
  </picture>
</a>

<br>

<a href="https://twitter.com/family">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/family-dark.svg">
    <img alt="family logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/family-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://twitter.com/context">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/context-dark.svg">
    <img alt="context logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/context-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://twitter.com/prtyDAO">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/partydao-dark.svg">
    <img alt="PartyDAO logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/partydao-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://dynamic.xyz">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/dynamic-dark.svg">
    <img alt="Dynamic logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/dynamic-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://sushi.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sushi-dark.svg">
    <img alt="Sushi logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sushi-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://stripe.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/stripe-dark.svg">
    <img alt="Stripe logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/stripe-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://privy.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/privy-dark.svg">
    <img alt="Privy logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/privy-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://pancakeswap.finance">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pancake-dark.svg">
    <img alt="pancake logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pancake-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://pimlico.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pimlico-dark.svg">
    <img alt="pimlico logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pimlico-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://zora.co">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/zora-dark.svg">
    <img alt="zora logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/zora-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://syndicate.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/syndicate-dark.svg">
    <img alt="syndicate logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/syndicate-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://relay.link">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/relay-dark.svg">
    <img alt="relay logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/relay-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://polymarket.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/polymarket-dark.svg">
    <img alt="polymarket logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/polymarket-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://sequence.xyz">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sequence-dark.svg">
    <img alt="sequence logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sequence-light.svg" width="auto" height="50">
  </picture>
</a>
<a href="https://web3auth.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/web3auth-dark.svg">
    <img alt="web3auth logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/web3auth-light.svg" width="auto" height="50">
  </picture>
</a>

## Contributing

If you're interested in contributing, please read the [contributing docs](/.github/CONTRIBUTING.md) **before submitting a pull request**.

## Authors

- [@jxom](https://github.com/jxom) (jxom.eth, [Twitter](https://twitter.com/_jxom))
- [@tmm](https://github.com/tmm) (awkweb.eth, [Twitter](https://twitter.com/awkweb))

## License

[MIT](/LICENSE) License


<br />
<br />

<a href="https://vercel.com/?utm_source=wevm&utm_campaign=oss">
  <img src="https://www.datocms-assets.com/31049/1618983297-powered-by-vercel.svg" alt="Powered by Vercel" height="35">
</a>


---

## 5. wormhole-connect
- **URL:** https://github.com/devtechedge/wormhole-connect
- **Language:** TypeScript
- **Topics:** None
- **Description:** Wormhole Connect brings all the functionality and utility of Wormhole right into your application and removes all of the complexity.

### README.md

# Wormhole Connect [![Documentation](https://img.shields.io/badge/Documentation-2a67c9)](https://docs.wormhole.com/wormhole/wormhole-connect/overview) [![npm version](https://img.shields.io/npm/v/@wormhole-foundation/wormhole-connect.svg)](https://www.npmjs.com/package/@wormhole-foundation/wormhole-connect) ![CI build](https://github.com/wormhole-foundation/wormhole-connect/actions/workflows/build.yml/badge.svg)

Wormhole Connect is a customizable React widget for cross-chain asset transfers powered by Wormhole.

[![Wormhole Connect running on Portal Bridge](https://i.imgur.com/U7ZB8y5.png)](https://portalbridge.com/)

Connect is powered by the [Wormhole TypeScript SDK](https://github.com/wormhole-foundation/wormhole-sdk-ts). Developers interested in building their
own interface for Wormhole bridging functionality are encouraged to explore the SDK!

## Demo

Wormhole Connect is deployed live in several production apps. Here are a few:

- [Portal Bridge](https://portalbridge.com/)
- [Jupiter](https://jup.ag/onboard/cctp)
- [PancakeSwap](https://bridge.pancakeswap.finance/wormhole)


## Getting Started

### Via package manager for React apps (Recommended)

If you're using React, you can import the `<WormholeConnect />` component directly into your JSX:

#### Installation

```bash
# Using bun (recommended)
bun add @wormhole-foundation/wormhole-connect

# Using npm
npm i @wormhole-foundation/wormhole-connect
```

#### Using the component

```javascript
import WormholeConnect from '@wormhole-foundation/wormhole-connect';

function App() {
  return (
    <WormholeConnect />
  );
}
```

### Alternative: hosted version via CDN (for any website)

If you're not using React, you can still embed Connect on your website by using the hosted version:

```ts
import {
  wormholeConnectHosted,
} from '@wormhole-foundation/wormhole-connect';

const container = document.getElementById('connect')!;

wormholeConnectHosted(container);
```


You can provide `config` and `theme` parameters in a second function argument:

```ts
import {
  wormholeConnectHosted,
} from '@wormhole-foundation/wormhole-connect';

const container = document.getElementById('connect')!;

wormholeConnectHosted(container, {
  config: {
    rpcs: {
      ...
    }
  },
  theme: {
    background: {
      default: '#004547',
    }
  }
});
```

## Configuration

Wormhole Connect is highly customizable via two props: `config` and `theme`. Here is an example which
limits it to two chains and customizes the background color:

```tsx
import WormholeConnect, {
  WormholeConnectConfig, WormholeConnectPartialTheme
} from '@wormhole-foundation/wormhole-connect';

const config: WormholeConnectConfig = {
  chains: ['Ethereum', 'Solana']
};

const theme: WormholeConnectPartialTheme = {
  background: {
    default: '#212b4a'
  }
};

function App() {
  return (
    <WormholeConnect config={config} theme={theme} />
  )
}
```

If using the hosted version, provide `config` and `theme` as JSON-serialized strings on the mount point:

```html
<div id="wormhole-connect" data-config="{...}" data-theme="{...}"></div>
```

Below are some of the more commonly used config options. See
[the full Connect docs](https://docs.wormhole.com/wormhole/wormhole-connect/overview) for more complete
documentation and examples of the different config options.

### Network (`network`):

Values: `Mainnet` | `Testnet` | `Devnet`

Connect renders in Mainnet mode by default, but you can switch it to testnet by setting `network` to `Testnet`:

```ts
const config: WormholeConnectConfig = {
  network: 'Testnet'
}
```

### Choosing Chains (`chains`):

You can provide a whitelist of chains to limit which ones Connect offers.

```ts
const config: WormholeConnectConfig = {
  chains: ['Ethereum', 'Solana']
}
```

See [`chains.ts`](https://github.com/wormhole-foundation/wormhole-sdk-ts/blob/main/core/base/src/constants/chains.ts) in the SDK. By default, Connect offers a subset of chains for both `mainnet` and `testnet`:

| `mainnet` | `testnet` |
| ---------- | ------------- |
| Ethereum | Sepolia |
| Polygon | |
| Bsc | Bsc |
| Avalanche | Avalanche |
| Fantom | Fantom |
| Celo | Celo |
| Moonbeam | Moonbeam |
| Solana | Solana |
| Sui | Sui |
| Aptos | Aptos |
| Base | BaseSepolia |
| Arbitrum | ArbitrumSepolia |
| Optimism | OptimismSepolia |
| Klaytn | Klaytn |
| Scroll | Scroll |
| Xlayer | Xlayer |
| Mantle | Mantle |
| Worldchain | Worldchain |
| Unichain | Unichain |
| Berachain | |
| Ink | |
| Linea | Linea |
| Sonic | Sonic |
| Mezo | Mezo |
| Seievm | Seievm |
| Plume | Plume |
| HyperEVM | |
| HyperCore | |
| XRPLEVM | XRPLEVM |
| Creditcoin | |
| Fogo | Fogo |
| | Monad |
| | Moca |

### RPC Endpoints (`rpcs`):

We strongly recommend that you configure your own custom RPC endpoints for each network your application needs. The default public RPCs may be throttled or rate limited.

```ts
const config: WormholeConnectConfig = {
  rpcs: {
    Solana: 'https://mainnet.helius-rpc.com/?api-key=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx',
    Ethereum: 'https://rpc.ankr.com/eth/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
  }
}
```

### Custom Tokens (`tokensConfig`)

You can add arbitrary tokens to the Connect tokens menu by providing a `tokensConfig` key.

```ts
const config: WormholeConnectConfig = {
  tokensConfig: {
    ...
  }
}
```

See the "Arbitrary Token" example in [the config docs](https://docs.wormhole.com/wormhole/wormhole-connect/configuration#arbitrary-token).

Please note you have to [register a token](https://portalbridge.com/advanced-tools/#/register) with the token bridge before you can use it in Connect.

### Configuring Custom NTT (Native Token Transfer) Tokens

To configure a custom NTT token, pass your NTT config to the `nttRoutes` helper function, which will add the NTT routes to the `routes` array. You can find the definition for the NTT config [here](https://github.com/wormhole-foundation/example-native-token-transfers/blob/6a1a3d9e6d1a2045fb1688c2b53c9ac145cb40bc/sdk/route/src/types.ts#L34).

```ts
const config: WormholeConnectConfig = {
  routes: [
    ...nttRoutes({
      tokens: {
        // Your custom NTT configs go here
        // See: https://github.com/wormhole-foundation/wormhole-connect/blob/9548507ca68dfd249bf84057889dc61553b17b5f/wormhole-connect/src/components/DemoApp/consts.ts#L3 for an example NTT config
      }
    })
    // other routes
  ]
}
```

Each `token` address specified in the NTT config must have a corresponding entry in `tokensConfig`, whether it is a built-in or custom token.

### Custom Theme

You can also customize Connect's color scheme by providing a `WormholeConnectTheme` as the `theme` prop.
By default, Connect renders using the `dark` theme.

```jsx
import WormholeConnect, {
  dark,
  WormholeConnectTheme,
} from "@wormhole-foundation/wormhole-connect";

// alters the `dark` theme
const customized: WormholeConnectTheme = dark;
customized.success = '#212b4a';
customized.background.default = "navy";
customized.button.action = "#81c784";
customized.button.actionText = "#000000";

export default function App() {
  return <WormholeConnect theme={customized} />;
}
```

You can change the `theme` prop to dynamically change Connect's colors, for example when your application
switches from light to dark mode.

See the definitions of `WormholeConnectTheme` and `dark` in [theme.ts](https://github.com/wormhole-foundation/wormhole-connect/blob/development/wormhole-connect/src/theme.ts) for type definitions.

### Learn More

Please read [the full Connect documentation](https://docs.wormhole.com/wormhole/wormhole-connect/overview) to see what else is possible!

## Contributing

We welcome contributions and bug fixes. Please see [CONTRIBUTING.md](https://github.com/wormhole-foundation/wormhole-connect/blob/development/CONTRIBUTING.md)


## Disclaimer

This SDK is an open source software SDK that leverages the Wormhole protocol, a cross chain messaging protocol. The SDK does not process payments. THIS SDK AND THE WORMHOLE PROTOCOL ARE PROVIDED "AS IS", AT YOUR OWN RISK, AND WITHOUT WARRANTIES OF ANY KIND. By using or accessing this SDK or Wormhole, you agree that no developer or entity involved in creating, deploying, maintaining, operating this SDK or Wormhole, or causing or supporting any of the foregoing, will be liable in any manner for any claims or damages whatsoever associated with your use, inability to use, or your interaction with other users of, this SDK or Wormhole, or this SDK or Wormhole themselves, including any direct, indirect, incidental, special, exemplary, punitive or consequential damages, or loss of profits, cryptocurrencies, tokens, or anything else of value. By using or accessing this SDK, you represent that you are not subject to sanctions or otherwise designated on any list of prohibited or restricted parties or excluded or denied persons, including but not limited to the lists maintained by the United States' Department of Treasury's Office of Foreign Assets Control, the United Nations Security Council, the European Union or its Member States, or any other government authority.

Wormhole Connect is an NPM package that interacts with the Wormhole protocol. You assume all risks associated with using the SDK, the Wormhole Connect NPM package, the Wormhole protocol, and digital assets and decentralized systems generally, including but not limited to, that: (a) digital assets are highly volatile; (b) using digital assets is inherently risky due to both features of such assets and the potential unauthorized acts of third parties; (c) you may not have ready access to assets; and (d) you may lose some or all of your tokens or other assets. You agree that you will have no recourse against anyone else for any losses due to the use of the SDK or Wormhole. For example, these losses may arise from or relate to: (i) incorrect information; (ii) software or network failures; (iii) corrupted cryptocurrency wallet files; (iv) unauthorized access; (v) errors, mistakes, or inaccuracies; or (vi) third-party activities.



---

## 6. next.js
- **URL:** https://github.com/devtechedge/next.js
- **Language:** JavaScript
- **Topics:** None
- **Description:** The React Framework

### README.md

<div align="center">
  <a href="https://nextjs.org">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://assets.vercel.com/image/upload/v1662130559/nextjs/Icon_dark_background.png">
      <img alt="Next.js logo" src="https://assets.vercel.com/image/upload/v1662130559/nextjs/Icon_light_background.png" height="128">
    </picture>
  </a>
  <h1>Next.js</h1>

<a href="https://vercel.com"><img alt="Vercel logo" src="https://img.shields.io/badge/MADE%20BY%20Vercel-000000.svg?style=for-the-badge&logo=Vercel&labelColor=000"></a>
<a href="https://www.npmjs.com/package/next"><img alt="NPM version" src="https://img.shields.io/npm/v/next.svg?style=for-the-badge&labelColor=000000"></a>
<a href="https://github.com/vercel/next.js/blob/canary/license.md"><img alt="License" src="https://img.shields.io/npm/l/next.svg?style=for-the-badge&labelColor=000000"></a>
<a href="https://github.com/vercel/next.js/discussions"><img alt="Join the community on GitHub" src="https://img.shields.io/badge/Join%20the%20community-blueviolet.svg?style=for-the-badge&logo=Next.js&labelColor=000000&logoWidth=20"></a>

</div>

## Getting Started

Used by some of the world's largest companies, Next.js enables you to create full-stack web applications by extending the latest React features, and integrating powerful Rust-based JavaScript tooling for the fastest builds.

- Visit our [Learn Next.js](https://nextjs.org/learn) course to get started with Next.js.
- Visit the [Next.js Showcase](https://nextjs.org/showcase) to see more sites built with Next.js.

## Documentation

Visit [https://nextjs.org/docs](https://nextjs.org/docs) to view the full documentation.

## Community

The Next.js community can be found on [GitHub Discussions](https://github.com/vercel/next.js/discussions) where you can ask questions, voice ideas, and share your projects with other people.

To chat with other community members, you can join the Next.js [Discord](https://nextjs.org/discord) server.

Do note that our [Code of Conduct](https://github.com/vercel/next.js/blob/canary/CODE_OF_CONDUCT.md) applies to all Next.js community channels. Users are **highly encouraged** to read and adhere to it to avoid repercussions.

## Contributing

Contributions to Next.js are welcome and highly appreciated. However, before you jump right into it, we would like you to review our [Contribution Guidelines](/contributing.md) to make sure you have a smooth experience contributing to Next.js.

### Good First Issues:

We have a list of **[good first issues](https://github.com/vercel/next.js/labels/good%20first%20issue)** that contain bugs that have a relatively limited scope. This is a great place for newcomers and beginners alike to get started, gain experience, and get familiar with our contribution process.

---
## Security

If you believe you have found a security vulnerability in Next.js, we encourage you to **_responsibly disclose this and NOT open a public issue_**.

To participate in our Open Source Software Bug Bounty program, please email [responsible.disclosure@vercel.com](mailto:responsible.disclosure@vercel.com). We will add you to the program and provide further instructions for submitting your report.


---

## 7. freighter
- **URL:** https://github.com/devtechedge/freighter
- **Language:** TypeScript
- **Topics:** None
- **Description:** Stellar browser extension

### README.md

# Freighter

Freighter is a non-custodial wallet extension that enables you to sign Stellar
transactions via your browser. Learn more at
[freighter.app](https://www.freighter.app/).

## Yarn Workspaces

This repo is constructed using yarn workspaces and consists of the 4 sections:

- the browser extension (`/extension`)
- the client-facing SDK (`/@stellar/freighter-api`)
- the docs (`/docs`)
- some shared files that the above use (`/@shared/*`)

## Prerequisites

- Node (>= 22): https://nodejs.org/en/download/ (use `nvm use` — the repo has
  `.nvmrc`)
- Yarn 4.10.0: `corepack enable && corepack prepare yarn@4.10.0 --activate`

For a complete setup guide including LLM-assisted quick setup, see
[CONTRIBUTING.MD](CONTRIBUTING.MD).

## Build the extension

To simply build a production version of the extension, install the prerequisites
then navigate to this root folder (`/freighter`) in your command line and run
these 2 steps:

```
yarn install
yarn setup
```

followed by

```
yarn build:extension:production
```

This will generate the files that make up the extension in `extension/build`

## Configure environment variables

Before starting the dev server, you need to configure the backend URLs. Create a
file `extension/.env` with the following variables:

```
INDEXER_URL=your_backend_v1_prod_url_here
INDEXER_V2_URL=your_backend_v2_prod_url_here

```

These URLs should point to your deployment of Freighter backend. For more
details on backend configuration, see
[extension/README.md](extension/README.md#configure-the-backend).

If you're running the backends locally, follow the setup instructions in
[stellar/freighter-backend](https://github.com/stellar/freighter-backend) (V1)
and
[stellar/freighter-backend-v2](https://github.com/stellar/freighter-backend-v2)
(V2).

## Starting a dev environment

```
yarn setup
yarn start
```

This will start up multiple watching builds in parallel:

- The `@stellar/freighter-api` npm module
- The docs, serving on `localhost:3000`
- A dev server with the webapp running in the extension, serving on
  `localhost:9000`
- The actual built extension, able to be installed in Chrome or Firefox, in
  `build/`

Each of these will build in response to editing their source.

These can be started individually with `yarn start:\<workspace name\>` where
`\<workspace name\>` is one of:

- `freighter-api`
- `docs`
- `extension`

```
yarn build
```

This will produce final output for the docs, the `@stellar/freighter` npm
module, and the extension.

`yarn build:\<workspace name\>`, like the equivalent start commands, will build
an individual workspace.

### Testing for Safari

First you should allow unsigned extension in your safari session. This resets
every time Safari shuts down.
https://developer.apple.com/documentation/safariservices/safari_web_extensions/running_your_safari_web_extension#3744467

Next, run the Safari Extension Converter locally to convert Freighter to an
xcode project. Example from the project root -
`xcrun safari-web-extension-converter freighter/extension/build --project-location freighter-safari`

That should launch your project in xcode. You should run the project, with a
target of macos. If you have not allowed unsigned extensions, you will see a
related warning but otherwise you should see Freighter launched on your Safari
instance.

### Useful URLs:

[Configure the backend](https://github.com/stellar/freighter/blob/master/extension/README.md#configure-the-backend)

[Build the extension and install it on your machine](https://github.com/stellar/freighter/blob/master/extension/README.md#build-the-extension-and-install-it-on-your-machine)

[The popup webapp](http://localhost:9000/#/)

[The `setAllowed` playground](http://localhost:3000/docs/playground/setAllowed)

[The `requestAccess` playground](http://localhost:3000/docs/playground/requestAccess)

[The `getAddress` playground](http://localhost:3000/docs/playground/getAddress)

[The `signTransaction` playground](http://localhost:3000/docs/playground/signTransaction)

[The `addToken` playground](http://localhost:3000/docs/playground/addToken)

It's important to note that these last functions won't interact with the _dev
server_ popup UI on `localhost:9000` — you'll need to re-install the unpacked
extension each time you make a change.

### Importing a workspace

In some cases, you will want to import a workspace into another. For example, in
`extension` we need to import `@shared/constants`. To do this, simply add
`@shared/constants` to the dependencies list in package.json in `extension`.
Yarn symlinks all the workspaces, so doing so will allow you to import files
from the `@shared/constants` workspace as if it were a published npm package.

### Dependencies

Many dev dependencies (such as Typescript, linters, Webpack, etc.) have been
moved to the root `package.json` to allow devs to upgrade these libraries all in
one place.

### Pushing to repo

This repo will run a pre-push hook before pushing. This hook will run the cmd
`yarn build:extension:translations` to check if any strings in the extension
need to be added to the translations JSON. If there is no need to update the
translations JSON, the push will go through. If there is a need to update, the
changes will be automatically committed to your branch and the push will be
aborted. You will need to run `git push` again.

NOTE: If you're using nvm and run into an error where the git hook is using an
incompatible version of node, create a file `~/.huskryc` on your system and
added the following:

```
# This loads nvm.sh, sets the correct PATH before running hook, and ensures the project version of Node
export NVM_DIR="$HOME/.nvm"

[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

# If you have an .nvmrc file, we use the relevant node version
if [[ -f ".nvmrc" ]]; then
  nvm use
fi
```

This will instruct the git hook to use the .nvmrc found in this repo.


---

## 8. wallet-core
- **URL:** https://github.com/devtechedge/wallet-core
- **Language:** C++
- **Topics:** None
- **Description:** Cross-platform, cross-blockchain wallet library.

### README.md

<img src="docs/banner.png" align="center" title="Trust logo">

Trust Wallet Core is an open-source, cross-platform, mobile-focused library
implementing low-level cryptographic wallet functionality for a high number of blockchains.
It is a core part of the popular [Trust Wallet](https://trustwallet.com), and some other projects.
Most of the code is C++ with a set of strict C interfaces, and idiomatic interfaces for supported languages:
Swift for iOS and Java (Kotlin) for Android.

[![iOS CI](https://github.com/trustwallet/wallet-core/actions/workflows/ios-ci.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/ios-ci.yml)
[![Android CI](https://github.com/trustwallet/wallet-core/actions/workflows/android-ci.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/android-ci.yml)
[![Linux CI](https://github.com/trustwallet/wallet-core/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/linux-ci.yml)
[![Rust CI](https://github.com/trustwallet/wallet-core/actions/workflows/linux-ci-rust.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/linux-ci-rust.yml)
[![Wasm CI](https://github.com/trustwallet/wallet-core/actions/workflows/wasm-ci.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/wasm-ci.yml)
[![Kotlin CI](https://github.com/trustwallet/wallet-core/actions/workflows/kotlin-ci.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/kotlin-ci.yml)
[![Docker CI](https://github.com/trustwallet/wallet-core/actions/workflows/docker.yml/badge.svg)](https://github.com/trustwallet/wallet-core/actions/workflows/docker.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=TrustWallet_wallet-core&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=TrustWallet_wallet-core)

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/trustwallet/wallet-core)
![GitHub](https://img.shields.io/github/license/TrustWallet/wallet-core.svg)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/trustwallet/wallet-core)
![SPM](https://img.shields.io/badge/SPM-ready-blue)
![Cocoapods](https://img.shields.io/cocoapods/v/TrustWalletCore.svg)

# Documentation

For comprehensive documentation, see [developer.trustwallet.com](https://developer.trustwallet.com/wallet-core).

# Audit Reports

Security Audit reports can be found in the [audit](audit) directory.

# Supported Blockchains

Wallet Core supports more than **130** blockchains: Bitcoin, Ethereum, BNB, Cosmos, Solana, and most major blockchain platforms.
The full list is [here](docs/registry.md).

# Building

For build instructions, see [developer.trustwallet.com/wallet-core/building](https://developer.trustwallet.com/wallet-core/building).


# Using from your project

If you want to use wallet core in your project follow these instructions.

## Android

Android releases are hosted on [GitHub packages](https://github.com/trustwallet/wallet-core/packages/700258), you need to add GitHub access token to install it. Please check out [this installation guide](https://developer.trustwallet.com/wallet-core/integration-guide/android-guide#adding-library-dependency) or `build.gradle` from our [android sample](https://github.com/trustwallet/wallet-core/blob/master/samples/android/build.gradle)

Don't forget replacing the version in the code with latest: ![GitHub release (latest by date)](https://img.shields.io/github/v/release/trustwallet/wallet-core)

## iOS

We currently support Swift Package Manager and CocoaPods (will discontinue in the future).

### SPM

Download latest `Package.swift` from [GitHub Releases](https://github.com/trustwallet/wallet-core/releases) and put it in a local `WalletCore` folder.

Add this line to the `dependencies` parameter in your `Package.swift`:

```swift
.package(name: "WalletCore", path: "../WalletCore"),
```

Or add remote url + `master` branch, it points to recent (not always latest) binary release.

```swift
.package(name: "WalletCore", url: "https://github.com/trustwallet/wallet-core", .branchItem("master")),
```

Then add libraries to target's `dependencies`:

```swift
.product(name: "WalletCore", package: "WalletCore"),
.product(name: "WalletCoreSwiftProtobuf", package: "WalletCore"),
```

### CocoaPods

Add this line to your Podfile and run `pod install`:

```ruby
pod 'TrustWalletCore'
```

## NPM (beta)

```js
npm install @trustwallet/wallet-core
```

## Go (beta)

Please check out the [Go integration sample](https://github.com/trustwallet/wallet-core/tree/master/samples/go).

## Kotlin Multipleplatform (beta)

Please check out the [Kotlin Multiplatform sample](https://github.com/trustwallet/wallet-core/tree/master/samples/kmp)

# Projects

Projects using Trust Wallet Core. Add yours too!

[<img src="https://trustwallet.com/icon.svg" alt="Trust Wallet"/>](https://trustwallet.com)

[Coinpaprika](https://coinpaprika.com/)
| [crypto.com](https://crypto.com)
| [Frontier](https://frontier.xyz/)
| [Tokenary](https://tokenary.io/)
| [MemesWallet](https://planetmemes.com/)
| [xPortal](https://xportal.com/)
| [Slingshot](https://slingshot.finance/)
| [ECOIN Wallet](https://play.google.com/store/apps/details?id=org.ecoinwallet&pcampaignid=web_share)

# Community

There are a few community-maintained projects that extend Wallet Core to some additional platforms and languages. Note this is not an endorsement, please do your own research before using them:

- Flutter binding https://github.com/weishirongzhen/flutter_trust_wallet_core
- Python binding https://github.com/phuang/wallet-core-python
- Wallet Core on Windows https://github.com/kaetemi/wallet-core-windows

# Contributing

The best way to submit feedback and report bugs related to WalletCore is to [open a GitHub issue](https://github.com/trustwallet/wallet-core/issues/new).
If the bug is not related to WalletCore but to the TrustWallet app, please [create a Customer Support ticket](https://support.trustwallet.com/en/support/tickets/new).
If you want to contribute code please see [Contributing](https://developer.trustwallet.com/wallet-core/contributing).
If you want to add support for a new blockchain also see [Adding Support for a New Blockchain](https://developer.trustwallet.com/wallet-core/newblockchain), make sure you have read the [requirements](https://developer.trustwallet.com/wallet-core/newblockchain#requirements) section.

Thanks to all the people who contribute.
<a href="https://github.com/trustwallet/wallet-core/graphs/contributors"><img src="https://opencollective.com/wallet-core/contributors.svg?width=890&button=false" /></a>

# Disclaimer

The Wallet Core project is led and managed by Trust Wallet with a large contributor community and actively used in several projects.  Our goal at Wallet Core is to give other wallets an easy way to add chain support.

Trust Wallet products leverage wallet core, however, they may or may not leverage all the capabilities, features, and assets available in wallet core due to their own product requirements.

# License

Trust Wallet Core is available under the Apache 2.0 license. See the [LICENSE](LICENSE) file for more info.


---

## 9. program-examples
- **URL:** https://github.com/devtechedge/program-examples
- **Language:** TypeScript
- **Topics:** None
- **Description:** A repository of Solana program examples

### README.md

# Program Examples

## Onchain program examples for ⚓ Anchor, 🤥 Pinocchio, and 🦀 Native Rust.

[![Anchor](https://github.com/solana-developers/program-examples/actions/workflows/anchor.yml/badge.svg?event=schedule)](https://github.com/solana-developers/program-examples/actions/workflows/anchor.yml) [![Pinocchio](https://github.com/solana-developers/program-examples/actions/workflows/solana-pinocchio.yml/badge.svg?event=schedule)](https://github.com/solana-developers/program-examples/actions/workflows/solana-pinocchio.yml) [![Native](https://github.com/solana-developers/program-examples/actions/workflows/solana-native.yml/badge.svg?event=schedule)](https://github.com/solana-developers/program-examples/actions/workflows/solana-native.yml)

This repo contains Solana onchain programs (referred to as 'Smart Contracts' in other blockchains).

> [!NOTE]
> If you're new to Solana, you don't need to create your own programs to perform basic things like making accounts, creating tokens, sending tokens, or minting NFTs. These common tasks are handled with existing programs, for example the System Program (for making account or transferring SOL) or the token program (for creating tokens and NFTs). See the [Solana Developer site](https://solana.com/developers) to learn more.

> ⚠️ This repository uses **pnpm** as the default package manager.  
> Ensure pnpm is installed before running any examples.

Each folder includes examples for one or more of the following:

- `anchor` - Written using [Anchor](https://www.anchor-lang.com/), the most popular framework for Solana development, which uses Rust.
  Use `anchor build` and `anchor deploy` to build and deploy the program.
  Tests should be executed using `pnpm test` as defined in the `Anchor.toml` scripts section.

- `pinocchio` - Written using [Pinocchio](https://github.com/febo/pinocchio), a zero-copy, zero-allocation library for Solana programs.
  Build and test commands are the same as native examples.
  Run `pnpm test` to execute tests.

- `native` - Written using Solana's native Rust crates and vanilla Rust.
  Build and test commands are defined via pnpm scripts and use `litesvm` for testing.
  Run `pnpm test` to execute tests.

**If a given example is missing, please send us a PR to add it!** Our aim is to have every example available in every option. We'd also love to see more programs involving staking, wrapped tokens, oracles, compression and VRF. Follow the [contributing guidelines](./CONTRIBUTING.md) to keep things consistent.

## The example programs

## Basics

### Hello world

[Hello World on Solana! A minimal program that logs a greeting.](./basics/hello-solana/README.md)

[anchor](./basics/hello-solana/anchor) [pinocchio](./basics/hello-solana/pinocchio) [native](./basics/hello-solana/native)

### Account-data

Store and retrieve data using Solana accounts.

[anchor](./basics/account-data/anchor) [pinocchio](./basics/account-data/pinocchio) [native](./basics/account-data/native)

### Storing global state - Counter

[Store global state in an account, making a counter that increments when called.](./basics/counter/README.md)

[anchor](./basics/counter/anchor) [pinocchio](./basics/counter/pinocchio) [native](./basics/counter/native)

### Saving per-user state - Favorites

Save and update per-user state on the blockchain, ensuring users can only update their own information.

[anchor](./basics/favorites/anchor) [pinocchio](./basics/favorites/pinocchio) [native](./basics/favorites/native)

### Checking Instruction Accounts

[Check that the accounts provided in incoming instructions meet particular criteria.](./basics/checking-accounts/README.md)

[anchor](./basics/checking-accounts/anchor) [pinocchio](./basics/checking-accounts/pinocchio) [native](./basics/checking-accounts/native)

### Closing Accounts

Close an account and get the Lamports back.

[anchor](./basics/close-account/anchor) [pinocchio](./basics/close-account/pinocchio) [native](./basics/close-account/native)

### Creating Accounts

[Make new accounts on the blockchain, calculating the necessary minimum rent from the account's size.](./basics/create-account/README.md)

[anchor](./basics/create-account/anchor) [pinocchio](./basics/create-account/pinocchio) [native](./basics/create-account/native)

### Cross program invocations

[Invoke an instruction handler from one onchain program in another onchain program.](./basics/cross-program-invocation/README.md)

[anchor](./basics/cross-program-invocation/anchor) [native](./basics/cross-program-invocation/native)

### PDA rent-payer

[Use a PDA to pay the rent for the creation of a new account.](./basics/pda-rent-payer/README.md)

[anchor](./basics/pda-rent-payer/anchor) [pinocchio](./basics/pda-rent-payer/pinocchio) [native](./basics/pda-rent-payer/native)

### Processing instructions

[Add parameters to an instruction handler and use them.](./basics/processing-instructions/README.md)

[anchor](./basics/processing-instructions/anchor) [pinocchio](./basics/processing-instructions/pinocchio) [native](./basics/processing-instructions/native)

### Storing date in program derived addresses

Store and retrieve state in Solana.

[anchor](./basics/program-derived-addresses/anchor) [pinocchio](./basics/program-derived-addresses/pinocchio) [native](./basics/program-derived-addresses/native)

### Handling accounts that expand in size

How to store state that changes size in Solana.

[anchor](./basics/realloc/anchor) [pinocchio](./basics/realloc/pinocchio) [native](./basics/realloc/native)

### Laying out larger programs

[Layout larger Solana onchain programs.](./basics/repository-layout/README.md)

[anchor](./basics/repository-layout/anchor) [native](./basics/repository-layout/native)

### Transferring SOL

[Send SOL between two accounts.](./basics/transfer-sol/README.md)

[anchor](./basics/transfer-sol/anchor) [pinocchio](./basics/transfer-sol/pinocchio) [native](./basics/transfer-sol/native)

## Tokens

### Creating tokens

[Create a token on Solana with a token symbol and icon.](./tokens/create-token/README.md)

[anchor](./tokens/create-token/anchor) [pinocchio](./tokens/create-token/pinocchio) [native](./tokens/create-token/native)

### NFT operations

Create an NFT collection, mint NFTs, and verify NFTs as part of a collection using Metaplex Token Metadata. Reminder: you don't need your own program just to mint an NFT, see the note at the top of this README.

[anchor](./tokens/nft-operations/anchor) [pinocchio](./tokens/nft-operations/pinocchio)

### Transferring Tokens

[Create a token mint, mint tokens, and transfer tokens between accounts.](./tokens/transfer-tokens/README.md)

[anchor](./tokens/transfer-tokens/anchor) [pinocchio](./tokens/transfer-tokens/pinocchio) [native](./tokens/transfer-tokens/native)

### Allowing users to swap digital assets - Escrow

Allow two users to swap digital assets with each other, each getting 100% of what the other has offered due to the power of decentralization!

[anchor](./tokens/escrow/anchor) [pinocchio](./tokens/escrow/pinocchio) [native](./tokens/escrow/native)

### Fundraising with SPL Tokens

Create a fundraiser account specifying a target mint and amount, allowing contributors to deposit tokens until the goal is reached.

[anchor](./tokens/token-fundraiser/anchor)

### Distributing tokens with Merkle-proof claims

[Fund a vault once, publish a Merkle root of a balance snapshot, and let each holder claim their allocation with a proof](./tokens/merkle-tree-token-claimer/README.md) — the claim pattern behind large airdrops and chain migrations.

[anchor](./tokens/merkle-tree-token-claimer/anchor)

### Minting a token from inside a program with a PDA as the mint authority

[Mint a Token from inside your own onchain program using the Token program.](./tokens/pda-mint-authority/README.md) Reminder: you don't need your own program just to mint an NFT, see the note at the top of this README.

[anchor](./tokens/pda-mint-authority/anchor) [native](./tokens/pda-mint-authority/native) [pinocchio](./tokens/pda-mint-authority/pinocchio)

### Creating an Automated Market Maker

[Create liquidity pools to allow trading of new digital assets and allows users that provide liquidity to be rewarded by creating an Automated Market Maker.](./tokens/token-swap/README.md)

[anchor](./tokens/token-swap/anchor)

### External delegate token master

Control token transfers using an external secp256k1 delegate signature.

[anchor](./tokens/external-delegate-token-master/anchor)

## Token Extensions

### Basics - create token mints, mint tokens, and transfer tokens with Token Extensions

Create token mints, mint tokens, and transfer tokens using Token Extensions.

[anchor](./tokens/token-2022/basics/anchor)

### Preventing CPIs with CPI guard

Enable CPI guard to prevents certain token action from occurring within CPI (Cross-Program Invocation).

[anchor](./tokens/token-2022/cpi-guard/anchor)

### Using default account state

Create new token accounts that are frozen by default.

[anchor](./tokens/token-2022/default-account-state/anchor) [native](./tokens/token-2022/default-account-state/native)

### Grouping tokens

Create tokens that belong to larger groups of tokens using the Group Pointer extension.

[anchor](./tokens/token-2022/group/anchor)

### Creating token accounts whose owner cannot be changed

Create tokens whose owning program cannot be changed.

[anchor](./tokens/token-2022/immutable-owner/anchor)

### Interest bearing tokens

Create tokens that show an 'interest' calculation.

[anchor](./tokens/token-2022/interest-bearing/anchor)

### Requiring transactions to include descriptive memos

Create tokens where transfers must have a memo describing the transaction attached.

[anchor](./tokens/token-2022/memo-transfer/anchor)

### Adding on-chain metadata to the token mint

Create tokens that store their onchain metadata inside the token mint, without needing to use or pay for additional programs.

[anchor](./tokens/token-2022/metadata/anchor)

### Storing NFT metadata using the metadata pointer extension

Create an NFT using the Token Extensions metadata pointer, storing onchain metadata (including custom fields) inside the mint account itself.

[anchor](./tokens/token-2022/nft-meta-data-pointer/anchor)

### Allow a designated account to close a mint

Allow a designated account to close a Mint.

[anchor](./tokens/token-2022/mint-close-authority/anchor) [native](./tokens/token-2022/mint-close-authority/native) [pinocchio](./tokens/token-2022/mint-close-authority/pinocchio)

### Using multiple token extensions

Use multiple Token Extensions at once.

[native](./tokens/token-2022/multiple-extensions/native)

### Non-transferrable - create tokens that can't be transferred.

Create tokens that cannot be transferred.

[anchor](./tokens/token-2022/non-transferable/anchor) [native](./tokens/token-2022/non-transferable/native) [pinocchio](./tokens/token-2022/non-transferable/pinocchio)

### Permanent Delegate - Create tokens permanently under the control of a particular account

Create tokens that remain under the control of an account, even when transferred elsewhere.

[anchor](./tokens/token-2022/permanent-delegate/anchor)

### Create tokens with a transfer-fee.

Create tokens with an inbuilt transfer fee.

[anchor](./tokens/token-2022/transfer-fee/anchor) [native](./tokens/token-2022/transfer-fee/native)

### Transfer hook - hello world

A minimal transfer hook program that executes custom logic on every token transfer.

[anchor](./tokens/token-2022/transfer-hook/hello-world/anchor)

### Transfer hook - counter

Count how many times tokens have been transferred using a transfer hook.

[anchor](./tokens/token-2022/transfer-hook/counter/anchor)

### Transfer hook - using account data as seed

Use token account owner data as seeds to derive extra accounts in a transfer hook.

[anchor](./tokens/token-2022/transfer-hook/account-data-as-seed/anchor)

### Transfer hook - allow/block list

Restrict or allow token transfers using an on-chain allow/block list managed by a list authority.

[anchor](./tokens/token-2022/transfer-hook/allow-block-list-token/anchor)

### Transfer hook - block list with Codama clients

A block-list transfer hook as a full project: Pinocchio program, Codama-generated Rust and TypeScript clients, and a CLI.

[pinocchio](./tokens/token-2022/transfer-hook/block-list/pinocchio)

### Transfer hook - transfer cost

Charge an additional cost or fee on every token transfer using a transfer hook.

[anchor](./tokens/token-2022/transfer-hook/transfer-cost/anchor)

### Transfer hook - transfer switch

Enable or disable token transfers with an on-chain switch using a transfer hook.

[anchor](./tokens/token-2022/transfer-hook/transfer-switch/anchor)

## Compression

### Cnft-burn

Burn compressed NFTs.

[anchor](./compression/cnft-burn/anchor)

### Cnft-vault

Store Metaplex compressed NFTs inside a PDA.

[anchor](./compression/cnft-vault/anchor)

### Cutils

Work with Metaplex compressed NFTs.

[anchor](./compression/cutils/anchor)

## Cryptography

One stateless program per curve, wrapping the raw cryptographic syscalls. These run in LiteSVM today but only work on public clusters once their feature gates activate. Applied examples (multisig, key registry, encrypted ballot) live in the [crypto-primitives-examples](https://github.com/solana-foundation/crypto-primitives-examples) reference repo.

### BN254 (alt_bn128) operations

Add and scalar-multiply G2 points (SIMD-0302) and verify aggregate BLS signatures with a single pairing check, via the `sol_alt_bn128_group_op` syscall.

[pinocchio](./cryptography/bn254/pinocchio)

### BLS12-381 curve operations

Add, subtract, and scalar-multiply BLS12-381 G1 and G2 points with the `sol_curve_group_op` syscall.

[pinocchio](./cryptography/bls12-381/pinocchio)

## Oracles

### pyth

Use a data source for offchain data (called an Oracle) to perform activities onchain.

[anchor](./oracles/pyth/anchor)

## Games

### World Cup bracket prediction

A bracket-prediction game: entrants pay a fee to submit a 32-game bracket, an oracle posts results, scores are tallied on-chain, and the unique winner sweeps the pot. A full Pinocchio + Codama project with a TypeScript client and a webapp.

[pinocchio](./games/world-cup/pinocchio)

### Gacha (provably-fair pack pulls)

A provably-fair gacha / loot-box game — the on-chain mechanic behind RWA pack platforms like Collector Crypt and Phygitals. Buyers open pulls revealed with an RFC 9381 ECVRF anchored in the deployed [`cc-vrf`](https://vrf.collectorcrypt.com) registry by CPI; the VRF input binds buyer entropy, reveals are publicly verifiable off-chain, unsettled pulls are refundable, and prizes are minted as Token-2022 NFTs carrying a `rarity` metadata field. A full Pinocchio + Codama project with TypeScript + Rust clients.

[pinocchio](./games/gacha/pinocchio)

---


---

## 10. safe-docs
- **URL:** https://github.com/devtechedge/safe-docs
- **Language:** MDX
- **Topics:** None
- **Description:** Developer Docs for building on Safe.

### README.md

# Safe Documentation

[![License](https://img.shields.io/github/license/safe-global/safe-docs)](https://github.com/safe-global/safe-docs/blob/main/LICENSE.md)
![GitHub package.json version (branch)](https://img.shields.io/github/package-json/v/safe-global/safe-docs)

This repository hosts [Safe](https://safe.global) documentation.

The documentation is built with [Nextra](https://nextra.site) and is live at [docs.safe.global](https://docs.safe.global).

## Installation

Install the dependencies using [pnpm](https://pnpm.io):

```
pnpm install
```

## Development

Git hooks are set up to run tests and linting checks before every `git push`. These hooks can be executed locally by running the following command:

```
pnpm prepush
```

All links in the documentation are checked for validity on every pull request. These checks can be executed locally by running the following command:

```
pnpm linkcheck
```

## Execution

The project can be run with a server that's executed in development and production mode.

### Development mode

Run the server in development mode using the following command:

```
pnpm dev
```

### Production mode

Build the project:

```
pnpm build
```

Run the server in production mode using the following command:

```
pnpm start
```

## Testing

Create an environment file in the root of the project and copy the content from the `.env.example` file using the following command:

```
cp .env.example .env
```

Remember to update the environment variables once the `.env` file is created.

Run the tests using the following command:

```
pnpm test
```

## License

This project is licensed under the [MIT License](./LICENSE.md).

## Contributing

Contributions are more than welcome! Please open an issue or create a pull request by following our [contributions guidelines](./CONTRIBUTING.md).


---

## 11. ruff
- **URL:** https://github.com/devtechedge/ruff
- **Language:** Rust
- **Topics:** None
- **Description:** An extremely fast Python linter and code formatter, written in Rust.

### README.md

<!-- Begin section: Overview -->

# Ruff

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![image](https://img.shields.io/pypi/v/ruff.svg)](https://pypi.python.org/pypi/ruff)
[![image](https://img.shields.io/pypi/l/ruff.svg)](https://github.com/astral-sh/ruff/blob/main/LICENSE)
[![image](https://img.shields.io/pypi/pyversions/ruff.svg)](https://pypi.python.org/pypi/ruff)
[![Actions status](https://github.com/astral-sh/ruff/workflows/CI/badge.svg)](https://github.com/astral-sh/ruff/actions)
[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?logo=discord&logoColor=white)](https://discord.com/invite/astral-sh)

[**Docs**](https://docs.astral.sh/ruff/) | [**Playground**](https://play.ruff.rs/)

An extremely fast Python linter and code formatter, written in Rust.

<p align="center">
  <picture align="center">
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/1309177/232603514-c95e9b0f-6b31-43de-9a80-9e844173fd6a.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/1309177/232603516-4fb4892d-585c-4b20-b810-3db9161831e4.svg">
    <img alt="Shows a bar chart with benchmark results." src="https://user-images.githubusercontent.com/1309177/232603516-4fb4892d-585c-4b20-b810-3db9161831e4.svg">
  </picture>
</p>

<p align="center">
  <i>Linting the CPython codebase from scratch.</i>
</p>

- ⚡️ 10-100x faster than existing linters (like Flake8) and formatters (like Black)
- 🐍 Installable via `pip`
- 🛠️ `pyproject.toml` support
- 🤝 Python 3.14 compatibility
- ⚖️ Drop-in parity with [Flake8](https://docs.astral.sh/ruff/faq/#how-does-ruffs-linter-compare-to-flake8), [isort](https://docs.astral.sh/ruff/faq/#how-does-ruffs-import-sorting-compare-to-isort), and [Black](https://docs.astral.sh/ruff/faq/#how-does-ruffs-formatter-compare-to-black)
- 📦 Built-in caching, to avoid re-analyzing unchanged files
- 🔧 Fix support, for automatic error correction (e.g., automatically remove unused imports)
- 📏 Over [900 built-in rules](https://docs.astral.sh/ruff/rules/), with native re-implementations
    of popular Flake8 plugins, like flake8-bugbear
- ⌨️ First-party [editor integrations](https://docs.astral.sh/ruff/editors) for [VS Code](https://github.com/astral-sh/ruff-vscode) and [more](https://docs.astral.sh/ruff/editors/setup)
- 🌎 Monorepo-friendly, with [hierarchical and cascading configuration](https://docs.astral.sh/ruff/configuration/#config-file-discovery)

Ruff aims to be orders of magnitude faster than alternative tools while integrating more
functionality behind a single, common interface.

Ruff can be used to replace [Flake8](https://pypi.org/project/flake8/) (plus dozens of plugins),
[Black](https://github.com/psf/black), [isort](https://pypi.org/project/isort/),
[pydocstyle](https://pypi.org/project/pydocstyle/), [pyupgrade](https://pypi.org/project/pyupgrade/),
[autoflake](https://pypi.org/project/autoflake/), and more, all while executing tens or hundreds of
times faster than any individual tool.

Ruff is extremely actively developed and used in major open-source projects like:

- [Apache Airflow](https://github.com/apache/airflow)
- [Apache Superset](https://github.com/apache/superset)
- [FastAPI](https://github.com/tiangolo/fastapi)
- [Hugging Face](https://github.com/huggingface/transformers)
- [Pandas](https://github.com/pandas-dev/pandas)
- [SciPy](https://github.com/scipy/scipy)

Ruff is backed by [Astral](https://astral.sh), the creators of
[uv](https://github.com/astral-sh/uv) and [ty](https://github.com/astral-sh/ty).

Read the [launch
post](https://astral.sh/blog/announcing-astral-the-company-behind-ruff), or the
original [project
announcement](https://notes.crmarsh.com/python-tooling-could-be-much-much-faster).

## Testimonials

[**Sebastián Ramírez**](https://twitter.com/tiangolo/status/1591912354882764802), creator
of [FastAPI](https://github.com/tiangolo/fastapi):

> Ruff is so fast that sometimes I add an intentional bug in the code just to confirm it's actually
> running and checking the code.

[**Nick Schrock**](https://twitter.com/schrockn/status/1612615862904827904), founder of [Elementl](https://www.elementl.com/),
co-creator of [GraphQL](https://graphql.org/):

> Why is Ruff a gamechanger? Primarily because it is nearly 1000x faster. Literally. Not a typo. On
> our largest module (dagster itself, 250k LOC) pylint takes about 2.5 minutes, parallelized across 4
> cores on my M1. Running ruff against our _entire_ codebase takes .4 seconds.

[**Bryan Van de Ven**](https://github.com/bokeh/bokeh/pull/12605), co-creator
of [Bokeh](https://github.com/bokeh/bokeh/), original author
of [Conda](https://docs.conda.io/en/latest/):

> Ruff is ~150-200x faster than flake8 on my machine, scanning the whole repo takes ~0.2s instead of
> ~20s. This is an enormous quality of life improvement for local dev. It's fast enough that I added
> it as an actual commit hook, which is terrific.

[**Timothy Crosley**](https://twitter.com/timothycrosley/status/1606420868514877440),
creator of [isort](https://github.com/PyCQA/isort):

> Just switched my first project to Ruff. Only one downside so far: it's so fast I couldn't believe
> it was working till I intentionally introduced some errors.

[**Tim Abbott**](https://github.com/zulip/zulip/pull/23431#issuecomment-1302557034), lead developer of [Zulip](https://github.com/zulip/zulip) (also [here](https://github.com/astral-sh/ruff/issues/465#issuecomment-1317400028)):

> This is just ridiculously fast... `ruff` is amazing.

<!-- End section: Overview -->

## Table of Contents

For more, see the [documentation](https://docs.astral.sh/ruff/).

1. [Getting Started](#getting-started)
1. [Configuration](#configuration)
1. [Rules](#rules)
1. [Contributing](#contributing)
1. [Support](#support)
1. [Acknowledgements](#acknowledgements)
1. [Show Your Support](#show-your-support)
1. [License](#license)

## Getting Started<a id="getting-started"></a>

For more, see the [documentation](https://docs.astral.sh/ruff/).

### Installation

Ruff is available as [`ruff`](https://pypi.org/project/ruff/) on PyPI.

Invoke Ruff directly with [`uvx`](https://docs.astral.sh/uv/):

```shell
uvx ruff@0.16.7 check   # Lint all files in the current directory.
uvx ruff@0.16.7 format  # Format all files in the current directory.
```

Or install Ruff with `uv` (recommended), `pip`, or `pipx`:

```shell
# With uv.
uv tool install ruff@latest  # Install Ruff globally.
uv add --dev ruff            # Or add Ruff to your project.

# With pip.
pip install ruff

# With pipx.
pipx install ruff
```

Starting with version `0.5.0`, Ruff can be installed with our standalone installers:

```shell
# On macOS and Linux.
curl -LsSf https://astral.sh/ruff/install.sh | sh

# On Windows.
powershell -c "irm https://astral.sh/ruff/install.ps1 | iex"

# For a specific version.
curl -LsSf https://astral.sh/ruff/0.16.7/install.sh | sh
powershell -c "irm https://astral.sh/ruff/0.16.7/install.ps1 | iex"
```

You can also install Ruff via [Homebrew](https://formulae.brew.sh/formula/ruff), [Conda](https://anaconda.org/conda-forge/ruff),
and with [a variety of other package managers](https://docs.astral.sh/ruff/installation/).

### Usage

To run Ruff as a linter, try any of the following:

```shell
ruff check                          # Lint all files in the current directory (and any subdirectories).
ruff check path/to/code/            # Lint all files in `/path/to/code` (and any subdirectories).
ruff check path/to/code/*.py        # Lint all `.py` files in `/path/to/code`.
ruff check path/to/code/to/file.py  # Lint `file.py`.
ruff check @arguments.txt           # Lint using an input file, treating its contents as newline-delimited command-line arguments.
```

Or, to run Ruff as a formatter:

```shell
ruff format                          # Format all files in the current directory (and any subdirectories).
ruff format path/to/code/            # Format all files in `/path/to/code` (and any subdirectories).
ruff format path/to/code/*.py        # Format all `.py` files in `/path/to/code`.
ruff format path/to/code/to/file.py  # Format `file.py`.
ruff format @arguments.txt           # Format using an input file, treating its contents as newline-delimited command-line arguments.
```

Ruff can also be used as a [pre-commit](https://pre-commit.com/) hook via [`ruff-pre-commit`](https://github.com/astral-sh/ruff-pre-commit):

```yaml
- repo: https://github.com/astral-sh/ruff-pre-commit
  # Ruff version.
  rev: v0.16.7
  hooks:
    # Run the linter.
    - id: ruff-check
      args: [ --fix ]
    # Run the formatter.
    - id: ruff-format
```

Ruff can also be used as a [VS Code extension](https://github.com/astral-sh/ruff-vscode) or with [various other editors](https://docs.astral.sh/ruff/editors/setup).

Ruff can also be used as a [GitHub Action](https://github.com/features/actions) via
[`ruff-action`](https://github.com/astral-sh/ruff-action):

```yaml
name: Ruff
on: [ push, pull_request ]
jobs:
  ruff:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: astral-sh/ruff-action@v3
```

### Configuration<a id="configuration"></a>

Ruff can be configured through a `pyproject.toml`, `ruff.toml`, or `.ruff.toml` file (see:
[_Configuration_](https://docs.astral.sh/ruff/configuration/), or [_Settings_](https://docs.astral.sh/ruff/settings/)
for a complete list of all configuration options).

For the complete list of enabled rules, see [_Default Rules_](https://docs.astral.sh/ruff/default-rules/).

If left unspecified, Ruff's default configuration is equivalent to the following `ruff.toml` file:

```toml
# Exclude a variety of commonly ignored directories.
exclude = [
    ".bzr",
    ".direnv",
    ".eggs",
    ".git",
    ".git-rewrite",
    ".hg",
    ".ipynb_checkpoints",
    ".mypy_cache",
    ".nox",
    ".pants.d",
    ".pyenv",
    ".pytest_cache",
    ".pytype",
    ".ruff_cache",
    ".svn",
    ".tox",
    ".venv",
    ".vscode",
    "__pypackages__",
    "_build",
    "buck-out",
    "build",
    "dist",
    "node_modules",
    "site-packages",
    "venv",
]

# Same as Black.
line-length = 88
indent-width = 4

# Assume Python 3.10
target-version = "py310"

[lint]
# select = [...]  # See the Default Rules page for the full listing.
ignore = []

# Allow fix for all enabled rules (when `--fix`) is provided.
fixable = ["ALL"]
unfixable = []

# Allow unused variables when underscore-prefixed.
dummy-variable-rgx = "^(_+|(_+[a-zA-Z0-9_]*[a-zA-Z0-9]+?))$"

[format]
# Like Black, use double quotes for strings.
quote-style = "double"

# Like Black, indent with spaces, rather than tabs.
indent-style = "space"

# Like Black, respect magic trailing commas.
skip-magic-trailing-comma = false

# Like Black, automatically detect the appropriate line ending.
line-ending = "auto"
```

Note that, in a `pyproject.toml`, each section header should be prefixed with `tool.ruff`. For
example, `[lint]` should be replaced with `[tool.ruff.lint]`.

Some configuration options can be provided via dedicated command-line arguments, such as those
related to rule enablement and disablement, file discovery, and logging level:

```shell
ruff check --select F401 --select F403 --quiet
```

The remaining configuration options can be provided through a catch-all `--config` argument:

```shell
ruff check --config "lint.per-file-ignores = {'some_file.py' = ['F841']}"
```

To opt in to the latest lint rules, formatter style changes, interface updates, and more, enable
[preview mode](https://docs.astral.sh/ruff/preview/) by setting `preview = true` in your configuration
file or passing `--preview` on the command line. Preview mode enables a collection of unstable
features that may change prior to stabilization.

See `ruff help` for more on Ruff's top-level commands, or `ruff help check` and `ruff help format`
for more on the linting and formatting commands, respectively.

## Rules<a id="rules"></a>

<!-- Begin section: Rules -->

**Ruff supports over 900 lint rules**, many of which are inspired by popular tools like Flake8,
isort, pyupgrade, and others. Regardless of the rule's origin, Ruff re-implements every rule in
Rust as a first-party feature.

By default, Ruff enables rules from the `F`, `E`, `B`, `UP`, and `RUF` categories,
as well as many more, omitting any stylistic rules that overlap with the use of a formatter, like
`ruff format` or [Black](https://github.com/psf/black).

If you're just getting started with Ruff, **the default rule set is a great place to start**: it
catches a wide variety of common errors (like unused imports) with zero configuration. See
[_Default Rules_](https://docs.astral.sh/ruff/default-rules/) for the complete list.

<!-- End section: Rules -->

Beyond the defaults, Ruff re-implements some of the most popular Flake8 plugins and related code
quality tools, including:

- [autoflake](https://pypi.org/project/autoflake/)
- [eradicate](https://pypi.org/project/eradicate/)
- [flake8-2020](https://pypi.org/project/flake8-2020/)
- [flake8-annotations](https://pypi.org/project/flake8-annotations/)
- [flake8-async](https://pypi.org/project/flake8-async)
- [flake8-bandit](https://pypi.org/project/flake8-bandit/) ([#1646](https://github.com/astral-sh/ruff/issues/1646))
- [flake8-blind-except](https://pypi.org/project/flake8-blind-except/)
- [flake8-boolean-trap](https://pypi.org/project/flake8-boolean-trap/)
- [flake8-bugbear](https://pypi.org/project/flake8-bugbear/)
- [flake8-builtins](https://pypi.org/project/flake8-builtins/)
- [flake8-commas](https://pypi.org/project/flake8-commas/)
- [flake8-comprehensions](https://pypi.org/project/flake8-comprehensions/)
- [flake8-copyright](https://pypi.org/project/flake8-copyright/)
- [flake8-datetimez](https://pypi.org/project/flake8-datetimez/)
- [flake8-debugger](https://pypi.org/project/flake8-debugger/)
- [flake8-django](https://pypi.org/project/flake8-django/)
- [flake8-docstrings](https://pypi.org/project/flake8-docstrings/)
- [flake8-eradicate](https://pypi.org/project/flake8-eradicate/)
- [flake8-errmsg](https://pypi.org/project/flake8-errmsg/)
- [flake8-executable](https://pypi.org/project/flake8-executable/)
- [flake8-future-annotations](https://pypi.org/project/flake8-future-annotations/)
- [flake8-gettext](https://pypi.org/project/flake8-gettext/)
- [flake8-implicit-str-concat](https://pypi.org/project/flake8-implicit-str-concat/)
- [flake8-import-conventions](https://github.com/joaopalmeiro/flake8-import-conventions)
- [flake8-logging](https://pypi.org/project/flake8-logging/)
- [flake8-logging-format](https://pypi.org/project/flake8-logging-format/)
- [flake8-no-pep420](https://pypi.org/project/flake8-no-pep420)
- [flake8-pie](https://pypi.org/project/flake8-pie/)
- [flake8-print](https://pypi.org/project/flake8-print/)
- [flake8-pyi](https://pypi.org/project/flake8-pyi/)
- [flake8-pytest-style](https://pypi.org/project/flake8-pytest-style/)
- [flake8-quotes](https://pypi.org/project/flake8-quotes/)
- [flake8-raise](https://pypi.org/project/flake8-raise/)
- [flake8-return](https://pypi.org/project/flake8-return/)
- [flake8-self](https://pypi.org/project/flake8-self/)
- [flake8-simplify](https://pypi.org/project/flake8-simplify/)
- [flake8-slots](https://pypi.org/project/flake8-slots/)
- [flake8-super](https://pypi.org/project/flake8-super/)
- [flake8-tidy-imports](https://pypi.org/project/flake8-tidy-imports/)
- [flake8-todos](https://pypi.org/project/flake8-todos/)
- [flake8-type-checking](https://pypi.org/project/flake8-type-checking/)
- [flake8-use-pathlib](https://pypi.org/project/flake8-use-pathlib/)
- [flynt](https://pypi.org/project/flynt/) ([#2102](https://github.com/astral-sh/ruff/issues/2102))
- [isort](https://pypi.org/project/isort/)
- [mccabe](https://pypi.org/project/mccabe/)
- [pandas-vet](https://pypi.org/project/pandas-vet/)
- [pep8-naming](https://pypi.org/project/pep8-naming/)
- [pydocstyle](https://pypi.org/project/pydocstyle/)
- [pygrep-hooks](https://github.com/pre-commit/pygrep-hooks)
- [pylint-airflow](https://pypi.org/project/pylint-airflow/)
- [pyupgrade](https://pypi.org/project/pyupgrade/)
- [tryceratops](https://pypi.org/project/tryceratops/)
- [yesqa](https://pypi.org/project/yesqa/)

For a complete enumeration of the supported rules, see [_Rules_](https://docs.astral.sh/ruff/rules/).

## Contributing<a id="contributing"></a>

Contributions are welcome and highly appreciated. To get started, check out the
[**contributing guidelines**](https://docs.astral.sh/ruff/contributing/).

You can also join us on [**Discord**](https://discord.com/invite/astral-sh).

## Support<a id="support"></a>

Having trouble? Check out the existing issues on [**GitHub**](https://github.com/astral-sh/ruff/issues),
or feel free to [**open a new one**](https://github.com/astral-sh/ruff/issues/new).

You can also ask for help on [**Discord**](https://discord.com/invite/astral-sh).

## Acknowledgements<a id="acknowledgements"></a>

Ruff's linter draws on both the APIs and implementation details of many other
tools in the Python ecosystem, especially [Flake8](https://github.com/PyCQA/flake8), [Pyflakes](https://github.com/PyCQA/pyflakes),
[pycodestyle](https://github.com/PyCQA/pycodestyle), [pydocstyle](https://github.com/PyCQA/pydocstyle),
[pyupgrade](https://github.com/asottile/pyupgrade), and [isort](https://github.com/PyCQA/isort).

In some cases, Ruff includes a "direct" Rust port of the corresponding tool.
We're grateful to the maintainers of these tools for their work, and for all
the value they've provided to the Python community.

Ruff's formatter is built on a fork of Rome's [`rome_formatter`](https://github.com/rome/tools/tree/main/crates/rome_formatter),
and again draws on both API and implementation details from [Rome](https://github.com/rome/tools),
[Prettier](https://github.com/prettier/prettier), and [Black](https://github.com/psf/black).

Ruff's import resolver is based on the import resolution algorithm from [Pyright](https://github.com/microsoft/pyright).

Ruff is also influenced by a number of tools outside the Python ecosystem, like
[Clippy](https://github.com/rust-lang/rust-clippy) and [ESLint](https://github.com/eslint/eslint).

Ruff is the beneficiary of a large number of [contributors](https://github.com/astral-sh/ruff/graphs/contributors).

Ruff is released under the MIT license.

## Show Your Support

If you're using Ruff, consider adding the Ruff badge to your project's `README.md`:

```md
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
```

...or `README.rst`:

```rst
.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
    :target: https://github.com/astral-sh/ruff
    :alt: Ruff
```

...or, as HTML:

```html
<a href="https://github.com/astral-sh/ruff"><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json" alt="Ruff" style="max-width:100%;"></a>
```

## License<a id="license"></a>

This repository is licensed under the [MIT License](https://github.com/astral-sh/ruff/blob/main/LICENSE)

<div align="center">
  <a target="_blank" href="https://astral.sh" style="background:none">
    <img src="https://raw.githubusercontent.com/astral-sh/ruff/main/assets/svg/Astral.svg" alt="Made by Astral">
  </a>
</div>


---

## 12. ai-news-agent
- **URL:** https://github.com/devtechedge/ai-news-agent
- **Language:** Python
- **Topics:** ai-agent, cron, feedparser, gemini, github-actions, google-gemini, llm, news-aggregator, python, rss, serverless, telegram-bot
- **Description:** Serverless daily AI news agent. GitHub Actions at 19:30 UTC fetches HN, arXiv cs.AI, Reddit r/MachineLearning, Google AI Blog, OpenAI News, and Hugging Face RSS, dedupes in-repo memory, summarizes with Gemini, and sends one Telegram executive brief. Python 3.11. No public web UI. Fork, add three Actions secrets, and the next run is yours.

### README.md

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


---

## 13. crawlee
- **URL:** https://github.com/devtechedge/crawlee
- **Language:** TypeScript
- **Topics:** None
- **Description:** CrawleeΓÇöA web scraping and browser automation library for Node.js to build reliable crawlers. In JavaScript and TypeScript. Extract data for AI, LLMs, RAG, or GPTs. Download HTML, PDF, JPG, PNG, and other files from websites. Works with Puppeteer, Playwright, Cheerio, JSDOM, and raw HTTP. Both headful and headless mode. With proxy rotation.

### README.md

<h1 align="center">
    <a href="https://crawlee.dev">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/apify/crawlee/master/website/static/img/crawlee-dark.svg?sanitize=true" />
          <img alt="Crawlee" src="https://raw.githubusercontent.com/apify/crawlee/master/website/static/img/crawlee-light.svg?sanitize=true" width="500" />
        </picture>
    </a>
    <br />
    <small>A web scraping and browser automation library</small>
</h1>

<p align="center">
    <a href="https://trendshift.io/repositories/5179" target="_blank"><img src="https://trendshift.io/api/badge/repositories/5179" alt="apify%2Fcrawlee | Trendshift" width="250" height="55"/></a>
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/@crawlee/core" rel="nofollow"><img src="https://img.shields.io/npm/v/@crawlee/core.svg" alt="NPM latest version" data-canonical-src="https://img.shields.io/npm/v/@crawlee/core/next.svg" /></a>
    <a href="https://www.npmjs.com/package/@crawlee/core" rel="nofollow"><img src="https://img.shields.io/npm/dm/@crawlee/core.svg" alt="Downloads" data-canonical-src="https://img.shields.io/npm/dm/@crawlee/core.svg" /></a>
    <a href="https://discord.gg/jyEM2PRvMU" rel="nofollow"><img src="https://img.shields.io/discord/801163717915574323?label=discord" alt="Chat on discord" data-canonical-src="https://img.shields.io/discord/801163717915574323?label=discord" /></a>
    <a href="https://github.com/apify/crawlee/actions/workflows/test-ci.yml"><img src="https://github.com/apify/crawlee/actions/workflows/test-ci.yml/badge.svg?branch=master" alt="Build Status" /></a>
</p>

Crawlee covers your crawling and scraping end-to-end and **helps you build reliable scrapers. Fast.**

Your crawlers will appear human-like and fly under the radar of modern bot protections even with the default configuration. Crawlee gives you the tools to crawl the web for links, scrape data, and store it to disk or cloud while staying configurable to suit your project's needs.

Crawlee is available as the [`crawlee`](https://www.npmjs.com/package/crawlee) NPM package.

> 👉 **View full documentation, guides and examples on the [Crawlee project website](https://crawlee.dev)** 👈

> Do you prefer 🐍 Python instead of JavaScript? [👉 Checkout Crawlee for Python 👈](https://github.com/apify/crawlee-python).

## Installation

We recommend visiting the [Introduction tutorial](https://crawlee.dev/js/docs/introduction) in Crawlee documentation for more information.

> Crawlee requires **Node.js 16 or higher**.

### With Crawlee CLI

The fastest way to try Crawlee out is to use the **Crawlee CLI** and choose the **Getting started example**. The CLI will install all the necessary dependencies and add boilerplate code for you to play with.

```bash
npx crawlee create my-crawler
```

```bash
cd my-crawler
npm start
```

### Manual installation
If you prefer adding Crawlee **into your own project**, try the example below. Because it uses `PlaywrightCrawler` we also need to install [Playwright](https://playwright.dev). It's not bundled with Crawlee to reduce install size.

```bash
npm install crawlee playwright
```

```js
import { PlaywrightCrawler, Dataset } from 'crawlee';

// PlaywrightCrawler crawls the web using a headless
// browser controlled by the Playwright library.
const crawler = new PlaywrightCrawler({
    // Use the requestHandler to process each of the crawled pages.
    async requestHandler({ request, page, enqueueLinks, log }) {
        const title = await page.title();
        log.info(`Title of ${request.loadedUrl} is '${title}'`);

        // Save results as JSON to ./storage/datasets/default
        await Dataset.pushData({ title, url: request.loadedUrl });

        // Extract links from the current page
        // and add them to the crawling queue.
        await enqueueLinks();
    },
    // Uncomment this option to see the browser window.
    // headless: false,
});

// Add first URL to the queue and start the crawl.
await crawler.run(['https://crawlee.dev']);
```

By default, Crawlee stores data to `./storage` in the current working directory. You can override this directory via Crawlee configuration. For details, see [Configuration guide](https://crawlee.dev/js/docs/guides/configuration), [Request storage](https://crawlee.dev/js/docs/guides/request-storage) and [Result storage](https://crawlee.dev/js/docs/guides/result-storage).

### Installing pre-release versions

We provide automated beta builds for every merged code change in Crawlee. You can find them in the npm [list of releases](https://www.npmjs.com/package/crawlee?activeTab=versions). If you want to test new features or bug fixes before we release them, feel free to install a beta build like this:

```bash
npm install crawlee@next
```

If you also use the [Apify SDK](https://github.com/apify/apify-sdk-js), you need to specify dependency overrides in your `package.json` file so that you don't end up with multiple versions of Crawlee installed:

```json
{
    "overrides": {
       "apify": {
           "@crawlee/core": "$crawlee",
           "@crawlee/types": "$crawlee",
           "@crawlee/utils": "$crawlee"
       }
    }
}
```

## 🛠 Features

- Single interface for **HTTP and headless browser** crawling
- Persistent **queue** for URLs to crawl (breadth & depth first)
- Pluggable **storage** of both tabular data and files
- Automatic **scaling** with available system resources
- Integrated **proxy rotation** and session management
- Lifecycles customizable with **hooks**
- **CLI** to bootstrap your projects
- Configurable **routing**, **error handling** and **retries**
- **Dockerfiles** ready to deploy
- Written in **TypeScript** with generics

### 👾 HTTP crawling

- Zero config **HTTP2 support**, even for proxies
- Automatic generation of **browser-like headers**
- Replication of browser **TLS fingerprints**
- Integrated fast **HTML parsers**. Cheerio and JSDOM
- Yes, you can scrape **JSON APIs** as well

### 💻 Real browser crawling

- JavaScript **rendering** and **screenshots**
- **Headless** and **headful** support
- Zero-config generation of **human-like fingerprints**
- Automatic **browser management**
- Use **Playwright** and **Puppeteer** with the same interface
- **Chrome**, **Firefox**, **Webkit** and many others

## Usage on the Apify platform

Crawlee is open-source and runs anywhere, but since it's developed by [Apify](https://apify.com), it's easy to set up on the Apify platform and run in the cloud. Visit the [Apify SDK website](https://sdk.apify.com) to learn more about deploying Crawlee to the Apify platform.

## Support

If you find any bug or issue with Crawlee, please [submit an issue on GitHub](https://github.com/apify/crawlee/issues). For questions, you can ask on [Stack Overflow](https://stackoverflow.com/questions/tagged/apify), in GitHub Discussions or you can join our [Discord server](https://discord.com/invite/jyEM2PRvMU).

## Contributing

Your code contributions are welcome, and you'll be praised to eternity! If you have any ideas for improvements, either submit an issue or create a pull request. For contribution guidelines and the code of conduct, see [CONTRIBUTING.md](https://github.com/apify/crawlee/blob/master/CONTRIBUTING.md).

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](https://github.com/apify/crawlee/blob/master/LICENSE.md) file for details.


---

## 14. better-auth
- **URL:** https://github.com/devtechedge/better-auth
- **Language:** TypeScript
- **Topics:** None
- **Description:** The most comprehensive authentication framework

### README.md

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


---

## 15. bdk
- **URL:** https://github.com/devtechedge/bdk
- **Language:** Rust
- **Topics:** None
- **Description:** A modern, lightweight, descriptor-based wallet library written in Rust!

### README.md

# The Bitcoin Dev Kit

<div align="center">

  <img src="./static/bdk.png" width="220" />

  <p>
    <strong>A suite of libraries for building modern, lightweight, descriptor-based wallets written in Rust!</strong>
  </p>

  <p>
    <a href="https://github.com/bitcoindevkit/bdk/blob/master/LICENSE"><img alt="MIT or Apache-2.0 Licensed" src="https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg"/></a>
    <a href="https://github.com/bitcoindevkit/bdk/actions?query=workflow%3ACI"><img alt="CI Status" src="https://github.com/bitcoindevkit/bdk/workflows/CI/badge.svg"></a>
    <a href="https://coveralls.io/github/bitcoindevkit/bdk?branch=master"><img src="https://coveralls.io/repos/github/bitcoindevkit/bdk/badge.svg?branch=master"/></a>
    <a href="https://blog.rust-lang.org/2025/02/20/Rust-1.85.0/"><img alt="Rustc Version 1.85.0+" src="https://img.shields.io/badge/rustc-1.85.0%2B-lightgrey.svg"/></a>
    <a href="https://discord.gg/d7NkDKm"><img alt="Chat on Discord" src="https://img.shields.io/discord/753336465005608961?logo=discord"></a>
  </p>

  <h4>
    <a href="https://bitcoindevkit.org">Project Homepage</a>
  </h4>
</div>

## About

The `bdk` libraries aim to provide well engineered and reviewed components for Bitcoin wallets and other applications.
They are built upon the excellent [`rust-bitcoin`] and [`rust-miniscript`] crates.

## Architecture

The workspace in this repository contains several crates in the `/crates` directory:

| Sub-Directory | Description | Badges |
|---------------|-------------|--------|
| [`chain`](./crates/chain) | Tools for storing and indexing chain data. | ![Chain Crate Info](https://img.shields.io/crates/v/bdk_chain.svg) ![Chain API Docs](https://img.shields.io/badge/docs.rs-bdk_chain-green) |
| [`core`](./crates/core) | A collection of core structures used by the [`bdk_chain`], [`bdk_wallet`], and BDK's chain data source crates. | ![Core Crate Info](https://img.shields.io/crates/v/bdk_core.svg) ![Core API Docs](https://img.shields.io/badge/docs.rs-bdk_core-green) |
| [`esplora`](./crates/esplora) | Extends the [`esplora-client`] crate with methods to fetch chain data from an esplora HTTP server in the form that [`bdk_chain`] and `Wallet` can consume. | ![Esplora Crate Info](https://img.shields.io/crates/v/bdk_esplora.svg) ![Esplora API Docs](https://img.shields.io/badge/docs.rs-bdk_esplora-green) |
| [`electrum`](./crates/electrum) | Extends the [`electrum-client`] crate with methods to fetch chain data from an electrum server in the form that [`bdk_chain`] and `Wallet` can consume. | ![Electrum Crate Info](https://img.shields.io/crates/v/bdk_electrum.svg) ![Electrum API Docs](https://img.shields.io/badge/docs.rs-bdk_electrum-green) |
| [`bitcoind_rpc`](./crates/bitcoind_rpc) | Extends [`bitcoincore-rpc`] for emitting blockchain data from the `bitcoind` RPC interface in the form that [`bdk_chain`] and `Wallet` can consume. | ![BitcoinD RPC Crate Info](https://img.shields.io/crates/v/bdk_bitcoind_rpc.svg) ![BitcoinD RPC API Docs](https://img.shields.io/badge/docs.rs-bdk_bitcoind_rpc-green) |
| [`file_store`](./crates/file_store) | Persistence backend for storing chain data in a single file. Intended for testing and development purposes, not for production. | ![File Store Crate Info](https://img.shields.io/crates/v/bdk_file_store.svg) ![File Store API Docs](https://img.shields.io/badge/docs.rs-bdk_file_store-green) |

The [`bdk_wallet`] repository and crate contains a higher level `Wallet` type that depends on the above lower-level mechanism crates.

[`rust-miniscript`]: https://github.com/rust-bitcoin/rust-miniscript
[`rust-bitcoin`]: https://github.com/rust-bitcoin/rust-bitcoin
[`esplora-client`]: https://docs.rs/esplora-client/
[`electrum-client`]: https://docs.rs/electrum-client/
[`bitcoincore-rpc`]: https://docs.rs/bitcoincore-rpc/
[`bdk_chain`]: https://docs.rs/bdk-chain/
[`bdk_wallet`]: https://github.com/bitcoindevkit/bdk_wallet

## Security Policy

To report a security issue, please refer to the [security policy](SECURITY.md).

## Minimum Supported Rust Version (MSRV)

The following BDK crates maintains a MSRV of 1.85.0. To build these crates with the MSRV of 1.85.0 you will need to pin dependencies by running the [`pin-msrv.sh`](./ci/pin-msrv.sh) script.

- `bdk_core`
- `bdk_chain`
- `bdk_bitcoind_rpc`
- `bdk_esplora`
- `bdk_file_store`
- `bdk_electrum`

## Just

This project has a [`justfile`](/justfile) for easy command running. You must have [`just`](https://github.com/casey/just) installed.

To see a list of available recipes: `just`

## License

Licensed under either of

* Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or <https://www.apache.org/licenses/LICENSE-2.0>)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or <https://opensource.org/licenses/MIT>)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.


---

## 16. safe-wallet-monorepo
- **URL:** https://github.com/devtechedge/safe-wallet-monorepo
- **Language:** TypeScript
- **Topics:** None
- **Description:** Safe{Wallet} ΓÇô smart account wallet

### README.md

# <img src="https://github.com/user-attachments/assets/b8249113-d515-4c91-a12a-f134813614e8" height="60" valign="middle" alt="Safe{Wallet}" style="background: #fff; padding: 20px; margin: 0 -20px" />

# Safe{Wallet} monorepo

🌐 [Safe{Wallet} web app](/apps/web/README.md) ・ 📱 [Safe{Wallet} mobile app](/apps/mobile/README.md)

## Overview

Welcome to the Safe{Wallet} monorepo! Safe (formerly Gnosis Safe) is a multi-signature smart contract wallet for Ethereum and other EVM chains, requiring multiple signatures to execute transactions.

This repository houses both web and mobile applications along with shared packages, managed under a unified structure using Yarn Workspaces. The monorepo setup simplifies dependency management and ensures consistent development practices across projects.

### Key components

- **apps/web** - Next.js web application ([detailed documentation](/apps/web/README.md))
- **apps/mobile** - Expo/React Native mobile application ([detailed documentation](/apps/mobile/README.md))
- **packages/store** - Shared Redux store used by both platforms
- **packages/utils** - Shared utilities and TypeScript types
- **config/** - Shared configuration files

> [!IMPORTANT]
>
> For detailed setup instructions and platform-specific development guides, please refer to the dedicated README files:
>
> - **[Web App Documentation](/apps/web/README.md)** - Complete guide for the Next.js web application
> - **[Mobile App Documentation](/apps/mobile/README.md)** - Complete guide for the mobile application, including iOS/Android setup

## Getting started

To get started, ensure you have the required tools installed and follow these steps:

### Prerequisites

- **Node.js**: Install the latest stable version from [Node.js](https://nodejs.org/).
- **Yarn**: Use Yarn version 4.5.3 or later

to install it with the latest node version you can simply do

```bash
corepack enable
```

and then just run

```bash
yarn
```

This will install the required version of yarn and resolve all dependencies.

> [!NOTE]
>
> Corepack is a tool to help with managing versions of your package managers. It exposes binary proxies for each supported package manager that, when called, will identify whatever package manager is
> configured for the current project, download it if needed, and finally run it.

### Initial setup

1. Clone the repository:

```bash
git clone <repo-url>
cd monorepo
```

2. Install dependencies:

```bash
yarn install
```

### Quick start commands

```bash
# Run web app in development mode
yarn workspace @safe-global/web dev

# Run mobile app in development mode
yarn workspace @safe-global/mobile start

# Run tests for web
yarn workspace @safe-global/web test

# Run Storybook for web
yarn workspace @safe-global/web storybook
```

> [!TIP]
>
> For comprehensive setup instructions, environment variables, testing, and platform-specific workflows, see:
>
> - **[Web App README](/apps/web/README.md)** - Environment setup, Cypress E2E tests, Storybook, and more
> - **[Mobile App README](/apps/mobile/README.md)** - iOS/Android setup, Maestro E2E tests, Expo configuration, and more

## Monorepo commands

Here are some essential commands to help you navigate the monorepo:

### Workspace management

- **Run a script in a specific workspace:**

```bash
yarn workspace <workspace-name> <script>
```

Example:

```bash
yarn workspace @safe-global/web dev
```

- **Add a dependency to a specific workspace:**

```bash
yarn workspace <workspace-name> add <package-name>
```

- **Remove a dependency from a specific workspace:**

```bash
yarn workspace <workspace-name> remove <package-name>
```

> [!Note]
>
> Yarn treats commands that contain a colon as global commands. For example if you have a
> command in a workspace that has a colon and there isn't another workspace that has the same command,
> you can run the command without specifying the workspace name. For example:
>
> ```bash
> yarn cypress:open
> ```
>
> is equivalent to:
>
> ```bash
> yarn workspace @safe-global/web cypress:open
> ```

### Linting, formatting, and type-checking

- **Run ESLint across all workspaces:**

```bash
yarn lint
```

- **Run Prettier to check formatting:**

```bash
yarn prettier
```

- **Run type-check for a workspace:**

```bash
yarn workspace @safe-global/web type-check
yarn workspace @safe-global/mobile type-check
```

### Testing

- **Run unit tests across all workspaces:**

```bash
yarn test
```

- **Run E2E tests (web only):**

```bash
yarn workspace @safe-global/web cypress:open  # Interactive mode
yarn workspace @safe-global/web cypress:run   # Headless mode
```

## Contributing

### Adding a new workspace

1. Create a new directory under `apps/` or `packages/`.
2. Add a `package.json` file with the appropriate configuration.
3. Run:

```bash
yarn install
```

### Best practices

- Use Yarn Workspaces commands for managing dependencies.
- Ensure type-check, lint, prettier, and tests pass before pushing changes.
- Follow the [semantic commit message guidelines](https://www.conventionalcommits.org/).
- For AI contributors, see [AGENTS.md](AGENTS.md) for detailed guidelines.

### Tools & configurations

- **Husky**: Pre-commit hooks for linting, formatting, and type-checking.
- **ESLint & Prettier**: Enforce coding standards and formatting.
- **Jest**: Unit testing framework.
- **Cypress**: E2E testing for the web app.
- **Storybook**: Component documentation and development for the web app.
- **Expo**: Mobile app framework for the `mobile` workspace.
- **Next.js**: React framework for the `web` workspace.
- **Tamagui**: UI component library for the mobile app.

## Release process

For information on releasing the web app, see the [Automated Release Procedure](apps/web/docs/release-procedure-automated.md).

## Useful links

- [Yarn Workspaces Documentation](https://yarnpkg.com/features/workspaces)
- [Expo Documentation](https://docs.expo.dev/)
- [Next.js Documentation](https://nextjs.org/docs)
- [Storybook Documentation](https://storybook.js.org/docs)
- [Jest Documentation](https://jestjs.io/)
- [ESLint Documentation](https://eslint.org/)
- [Prettier Documentation](https://prettier.io/)
- [Safe Developer Docs](https://docs.safe.global/)

## Ode to the repo

```
In ages past when Gnosis laid the founding stone,
A vault was wrought that no single key could own.
Where signatures must gather ere the gate will yield,
M-of-N doth guard the treasure, sworn and sealed.

Now Yarn doth wind its threads through hall and bower,
Binding web and mobile in a single tower.
Redux keeps the ledger, RTK Query rides afar,
Returning with the fetched gold beneath the evening star.

Chain by chain the watchers set their vigil wide,
Across th' EVM kingdoms, ever at the Safe's own side.
Storybook doth chronicle each component's tale,
And Cypress walks the paths where lesser tests would fail.

No `any` types shall darken these well-guarded lands —
That ancient law doth hold by Prettier's own hands.
Feature flags like waypoints mark what lies ahead,
And lazy loads awaken only where the road doth tread.

Long the name hath wandered — Gnosis once, now Safe it stands,
Yet still the vow endureth, written into typed commands:
That what you hold stays guarded, deep beyond all theft or flame,
For this the codebase liveth — and security its name.
```

---

If you have any questions or run into issues, feel free to open a discussion or contact the maintainers. Happy coding!
🚀


---

## 17. devtechedge
- **URL:** https://github.com/devtechedge/devtechedge
- **Language:** Not specified
- **Topics:** None
- **Description:** GitHub profile landing for Devayan Mandal (DevTechEdge): AI/ML and full-stack work across agentic systems, marketplaces, and polished Next.js demos. Index of public repos with live Vercel and GitHub Pages links. Python, TypeScript, React, Next.js, LangGraph, Postgres, Supabase. Portfolio README onlyΓÇöno app, no API keys, no backend. Account home. v1

### README.md

# Hi, I'm Dev 👋

### Full Stack AI Native Engineer · Open Source Contributor

I build production-grade AI and full-stack systems, while contributing fixes upstream to the infrastructure I build on.

My work spans multi-agent systems, RAG, HITL workflows, observability, developer tooling, distributed systems, and Web3 infrastructure.

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF66?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)](https://chatgpt.com)
[![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.ai)

---

## 🌍 Open Source Engineering

### Contribution ledgers

- 🧩 **[Non-Web3 OSS Contributions](https://github.com/devtechedge/non-web3-oss-contributions)** - upstream fixes across AI, developer tooling, databases, runtimes, and JS/Python infrastructure.
- ⛓️ **[Web3 OSS Contributions](https://github.com/devtechedge/web3-oss-contributions)** - upstream fixes across wallets, SDKs, blockchain tooling, and Web3 infrastructure.

### Merged upstream contributions

#### Non-Web3

- ✅ **[node-postgres #3772](https://github.com/brianc/node-postgres/pull/3772)** - stopped `Connection.sync()` from setting the internal `_ending` flag, since the extended-query Sync message is a protocol barrier rather than a disconnect. The flag had silenced genuine `ECONNRESET` / `EPIPE` socket errors for the rest of the connection lifetime after the first parameterized query, with recovery depending only on the async close path under `pipeline: true`.
- ✅ **[pnpm #14754](https://github.com/pnpm/pnpm/pull/14754)** - fixed `pnpm run "/pattern/" --no-bail` so one failing matched script no longer cancels its siblings. Non-recursive pattern runs now continue all selected scripts and report the aggregate failure correctly.
- ✅ **[pnpm #14756](https://github.com/pnpm/pnpm/pull/14756)** - fixed `pnpm update <name>@<version>` dropping the dependency's existing `^` or `~` range operator. Updates now preserve the manifest's range style and correctly retain `npm:` / `jsr:` prefixes, including prerelease ranges.
- ✅ **[pnpm #14753](https://github.com/pnpm/pnpm/pull/14753)** - fixed `lockfile: false` being ignored when `devEngines.packageManager.onFail` was `download`. Automatic package-manager switching now works without creating or updating a project `pnpm-lock.yaml`, with persistence moved to the global environment when appropriate.
- ✅ **[Better Auth #11208](https://github.com/better-auth/better-auth/pull/11208)** - added regression coverage for `/phone-number/verify` OpenAPI `requestBody` generation after a Zod intersection had caused the request body to disappear from generated specs. The runtime was unaffected; the fix locks in the expected generated contract.
- ✅ **[SQLMesh #6040](https://github.com/SQLMesh/sqlmesh/pull/6040)** - fixed a concurrency race in `sqlmesh test` where `ModelTest.create_test()` ran on worker threads while `time_machine` was being started or stopped, causing intermittent `IndexError` failures. Test creation now happens before work is submitted to the pool.
- ✅ **[Biome #11667](https://github.com/biomejs/biome/pull/11667)** - added the `useBetterDomTraversing` nursery lint rule, ported from ESLint Unicorn, to flag unnecessary DOM traversal patterns and provide safe transformations where semantics permit.

#### Web3

- ✅ **[thirdweb JS #8938](https://github.com/thirdweb-dev/js/pull/8938)** - fixed `useTokenQuery` swallowing real token lookup failures and incorrectly turning 401, 429, timeout, and other unexpected errors into `unsupported_token`. Genuine failures now reach the existing error and retry path.
- ✅ **[Anza Kit #2032](https://github.com/anza-xyz/kit/pull/2032)** - corrected the `getPatternMatchCodec` advanced guide to use `number` predicates, matching the current codec typing after the related narrowing fix landed.

### Selected upstream ecosystems

**Non-Web3:** pnpm · Biome · SQLMesh · LangGraph.js · Drizzle ORM · CrewAI · node-postgres · TanStack Router · Better Auth · LiveKit Agents · Jinja · Undici · TypeScript-ESLint · Vitest

**Web3:** Safe · Stellar · Wagmi · RainbowKit · ethers.js · Coinbase Wallet SDK · MetaMask SDK · Reown AppKit · Across Protocol · viem · Solana Web3.js · Ambire

---

## 🚀 Flagship Architectures & Projects

- 🔬 **[Synthesis](https://synthesis-gold.vercel.app/)** - Autonomous multi-agent research: plan → research → synthesize → critique → finalize, with HITL gates, RAG, Reflexion, and live SSE agent graphs ([repo](https://github.com/devtechedge/synthesis)).
- 💼 **[Jobrow](https://jobrow.vercel.app)** - Live register of still-open US tech roles sourced directly from employer ATS boards, with search, filters, company boards, closed-role tracking, and a public JSON API ([repo](https://github.com/devtechedge/job-board)).
- ⛓️ **[Lattice](https://lattice-devtechedge1.vercel.app)** - Live Web3 jobs platform aggregating blockchain and crypto roles from employer ATS boards, with salary observatory, talent directory, gigs, and hiring intelligence ([repo](https://github.com/devtechedge/lattice)).
- 🪐 **[Pulsar](https://devtechedge.github.io/pulsar/)** - Decentralized AI compute protocol interface with Base smart contracts, staking flows, wallet connectivity, 3D visualization, tokenomics, and Foundry-tested contracts ([repo](https://github.com/devtechedge/pulsar)).
- 🧠 **[AAROP](https://aarop.vercel.app)** - Explicit Perceive → Plan → Act → Observe → Reflect → Adapt loop with self-verification, bounded autonomy, and replayable traces ([repo](https://github.com/devtechedge/aarop)).
- ⚖️ **[RegTrace](https://regtrace-ai.vercel.app)** - HITL Web3 compliance copilot mapping packs onto MiCA/VARA with retrieval-bounded findings and article citations ([repo](https://github.com/devtechedge/regulatory_compliance)).
- 🏥 **[Cadence](https://cadence-healthcare.vercel.app/)** - Deep-memory healthcare agent lab: multi-layer patient memory, journey stages, consent-scoped clinician briefs ([repo](https://github.com/devtechedge/healthcare-deep-memory-agents)).
- 🔎 **[Veritas](https://veritas-engine-woad.vercel.app)** - LangGraph research agent with SSE streaming, Gemini + Tavily when keyed, grounded demo mode otherwise ([repo](https://github.com/devtechedge/veritas-engine)).
- 🔥 **[Chaos Simulator](https://chaos-simulation.vercel.app)** - Real-time chaos engineering dashboard with fault injection, self-healing services, animated service topology, scenario orchestration, live telemetry, and recovery analysis ([repo](https://github.com/devtechedge/chaos-simulator)).

---

## 🛠️ Tech Stack

| Category | Tooling, Frameworks & Architecture |
| :--- | :--- |
| **AI systems & agents** | Python, LangGraph, LangChain, LangServe, FastAPI, explicit agentic state machines, multi-agent supervisors, HITL interrupts, bounded autonomy, Reflexion / critique loops, tool-use / ReAct, durable checkpoints |
| **RAG, memory & evaluation** | Hybrid RAG, pgvector, BM25, TF-IDF, JSONB embeddings, cosine retrieval, sentence-transformers, long-term memory, retrieval-bounded generation, eval gates, LLM-as-judge, LangSmith |
| **LLMs, tools & integrations** | Gemini, OpenAI-compatible providers, Groq, Ollama / local LLMs, Tavily, Telegram Bot API, MCP-oriented tool buses, Google Workspace integrations |
| **Frontend & product** | TypeScript, React, Next.js, TanStack Start, Vite, Tailwind CSS, shadcn/ui, Lucide, Motion / Framer Motion, Recharts, Three.js, React Three Fiber, HTML5 Canvas, SVG |
| **Data, auth & backend** | PostgreSQL, Supabase, Neon, PGLite, SQLite, Prisma, Drizzle ORM, SQLAlchemy, Pydantic, Zod, Better Auth, REST, Server Actions, API routes |
| **Realtime, streaming & observability** | SSE, WebSockets, Socket.io, replayable traces, structured telemetry, OpenTelemetry-shaped tracing, live/demo provider switching |
| **Web3 & smart contracts** | Solidity, OpenZeppelin, Foundry, Base, viem, wagmi, RainbowKit, ethers.js, wallet SDKs, blockchain / wallet infrastructure |
| **Mobile, runtime & infrastructure** | Expo / React Native, Node.js, Bun, Express, Docker, Vercel, GitHub Actions, GitHub-hosted automation |
| **Testing & developer tooling** | Vitest, pytest, Playwright, TypeScript compiler, ESLint / Biome, CI test gates, visual regression, security hardening and threat-model documentation |

---

## 🎯 Engineering Philosophy

- **Bounded autonomy:** explicit state, validation, cost-aware routing, and HITL for irreversible actions.
- **Retrieval-bounded truth:** citation-backed RAG with hallucination checks.
- **Observable, upstream, production-ready:** inspectable traces, upstream fixes, and tested full-stack systems.
- **Ship the full stack:** production-style TypeScript/React surfaces with Python/FastAPI where it fits.

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dev-ma/)
[![X / Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DevTechEdge)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devtechedge)

---


---

## 18. web3-oss-gemini
- **URL:** https://github.com/devtechedge/web3-oss-gemini
- **Language:** TypeScript
- **Topics:** None
- **Description:** web3-oss-gemini

### README.md

# Web3 OSS contributions

Public ledger of **upstream** Web3 pull requests and issue claims by [@devtechedge](https://github.com/devtechedge). Own-repo work is not listed. Non-Web3 work lives in [non-web3-oss-contributions](https://github.com/devtechedge/non-web3-oss-contributions).

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-library%20fixes-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Open PRs](https://img.shields.io/badge/open%20PRs-27-black)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Aopen)
[![Merged](https://img.shields.io/badge/merged-2-brightgreen)](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge+is%3Amerged+-user%3Adevtechedge)
[![PRs](https://img.shields.io/github/issues-pr/devtechedge/web3-oss-contributions?label=tracker%20PRs)](https://github.com/devtechedge/web3-oss-contributions)

Live GitHub search: [PRs authored by @devtechedge](https://github.com/pulls?q=is%3Apr+author%3Adevtechedge)

![Web3 OSS contributions](docs/screenshots/social-preview.png)

---

## Status

**40 external items** as of 11 Sep 2026: **27 open PRs**, **2 merged**, **7 closed (not merged)**, **4 issue claims** waiting on maintainer assignment.

> **This README is the product.** There is no separate app or Vercel alias. Counts are a snapshot, not a live API. First upstream merge: [thirdweb-dev/js#8938](https://github.com/thirdweb-dev/js/pull/8938). Latest merge: [anza-xyz/kit#2032](https://github.com/anza-xyz/kit/pull/2032). Latest opens: 10 Sep 2026 batch (Across toolkit, Safe, Stellar, viem, Coinbase, Farcaster, Ambire, MetaMask). Latest closures: [wevm/viem#5070](https://github.com/wevm/viem/pull/5070) and [wevm/viem#5071](https://github.com/wevm/viem/pull/5071), both closed by maintainer `jxom` on 9 Sep 2026 without a submitted formal review.

The 10 Sep 2026 deep-scan replaced stale Wave 1 candidates before any upstream claim was made: EthereumJS #4313 is already fixed by merged #4349; Token-2022 #1325 is closed as completed; Token-2022 #1448 was taken by PR #1451. No new upstream claims were posted because the connected GitHub integration could not write to the upstream issue threads.

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
| [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#274](https://github.com/across-protocol/toolkit/pull/274) | Docs: `executeSwapQuote` README step `"deposit"` → `"swap"`; `getSwapQuote` example includes route object (fixes #267). | Open | 9 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1725](https://github.com/stellar/js-stellar-sdk/pull/1725) | Wire `docs/migration/` into Starlight sidebar / llms bundles so migration pages are not invisible (fixes #1674). | Open | 9 Sep 2026 |
| [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1432](https://github.com/safe-global/safe-core-sdk/pull/1432) | 4337 tests use disposable private keys instead of a shared hardcoded key (fixes #938). | Open | 9 Sep 2026 |
| [farcasterxyz/miniapps](https://github.com/farcasterxyz/miniapps) | [#626](https://github.com/farcasterxyz/miniapps/pull/626) | `openUrl` validates HTTPS scheme before dispatch (fixes #590). | Open | 9 Sep 2026 |
| [safe-global/safe-wallet-monorepo](https://github.com/safe-global/safe-wallet-monorepo) | [#8687](https://github.com/safe-global/safe-wallet-monorepo/pull/8687) | Sending to a Safe owner shows "co-signer address" instead of "unknown address" (fixes #8672). | Open | 9 Sep 2026 |
| [coinbase/coinbase-wallet-sdk](https://github.com/coinbase/coinbase-wallet-sdk) | [#1910](https://github.com/coinbase/coinbase-wallet-sdk/pull/1910) | WalletLink snackbar / redirect dialog keyboard and screen-reader a11y (fixes #1909). | Open | 9 Sep 2026 |
| [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#273](https://github.com/across-protocol/toolkit/pull/273) | `waitForFillByDepositTx` timeout + reject path so polling cannot run forever (fixes #271). | Open | 9 Sep 2026 |
| [across-protocol/toolkit](https://github.com/across-protocol/toolkit) | [#272](https://github.com/across-protocol/toolkit/pull/272) | `parseFillLogs` returns `undefined` on empty logs instead of throwing (fixes #268). | Open | 9 Sep 2026 |
| [safe-global/safe-docs](https://github.com/safe-global/safe-docs) | [#902](https://github.com/safe-global/safe-docs/pull/902) | Fix incorrect contract filename in fallback handler tutorial (fixes #826). | Open | 9 Sep 2026 |
| [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1431](https://github.com/safe-global/safe-core-sdk/pull/1431) | `generateHash` truncates by bytes (`size * 2` hex chars); bump identifier version `00` → `01` (fixes #1424). | Open | 9 Sep 2026 |
| [MetaMask/metamask-sdk](https://github.com/MetaMask/metamask-sdk) | [#1401](https://github.com/MetaMask/metamask-sdk/pull/1401) | Gate RN async-storage require so web bundles stop warning about a missing dependency (fixes #1376). | Open | 9 Sep 2026 |
| [safe-global/safe-core-sdk](https://github.com/safe-global/safe-core-sdk) | [#1430](https://github.com/safe-global/safe-core-sdk/pull/1430) | Document MultiSend batching for protocol-kit and sdk-starter-kit (fixes #1182). | Open | 9 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1724](https://github.com/stellar/js-stellar-sdk/pull/1724) | Declare optional `transaction_attr` and correct `join()` JSDoc (fixes #1646). | Open | 9 Sep 2026 |
| [across-protocol/sdk](https://github.com/across-protocol/sdk) | [#1533](https://github.com/across-protocol/sdk/pull/1533) | Apply configured gas/capital discount percents in `relayerFeeDetails` (fixes #1449). | Open | 9 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1723](https://github.com/stellar/js-stellar-sdk/pull/1723) | Docs: optional-null rewrite guidance scoped correctly + Jest CJS note (fixes #1685 / #1686). | Open | 9 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1722](https://github.com/stellar/js-stellar-sdk/pull/1722) | Run `call_builders` in the browser Vitest suite; drop obsolete exclude (fixes #1708). | Open | 9 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1721](https://github.com/stellar/js-stellar-sdk/pull/1721) | Pass CallBuilder base URL into `expandUriTemplate` for relative templated `_links` (fixes #1717). | Open | 9 Sep 2026 |
| [AmbireTech/extension](https://github.com/AmbireTech/extension) | [#29](https://github.com/AmbireTech/extension/pull/29) | Surface RPC forwarding errors via `console.debug` in prod inpage (fixes #23). | Open | 9 Sep 2026 |
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
| [wevm/viem](https://github.com/wevm/viem) | [#5071](https://github.com/wevm/viem/pull/5071) | `TestClient.revert` surfaces errors for invalid / missing snapshot IDs instead of failing silently (fixes #5064). | Closed by maintainer (`jxom`), not merged | 9 Sep 2026 |
| [wevm/viem](https://github.com/wevm/viem) | [#5070](https://github.com/wevm/viem/pull/5070) | Strict `isHex` rejects odd-length hex nibbles; non-strict unchanged (fixes #5048). | Closed by maintainer (`jxom`), not merged | 9 Sep 2026 |
| [wevm/viem](https://github.com/wevm/viem) | [#5065](https://github.com/wevm/viem/pull/5065) | `TestClient.revert` threw `SnapshotRevertError` when `evm_revert` returned `false` (invalid / already-consumed snapshot). Schema, tests, docs, changeset. +57/-5, 8 files. | Closed by author, not merged | 4 Sep 2026 |
| [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3882](https://github.com/solana-foundation/solana-web3.js/pull/3882) | ALT Freeze/Deactivate decoders check instruction discriminators via `decodeData` (fixes #3853). Base was `maintenance/v1.x`. | Closed by maintainer (`amilz`): not accepting PRs in v1.x (maintenance only) | 6 Sep 2026 |
| [anza-xyz/kit](https://github.com/anza-xyz/kit) | [#2033](https://github.com/anza-xyz/kit/pull/2033) | Docs: restore `number` predicates in the `getPatternMatchCodec` example. | Superseded: the same fix landed as [#2032](https://github.com/anza-xyz/kit/pull/2032); closed by author, not merged | 6 Sep 2026 |
| [stellar/js-stellar-sdk](https://github.com/stellar/js-stellar-sdk) | [#1714](https://github.com/stellar/js-stellar-sdk/pull/1714) | Coerce `getTransaction`/`sendTransaction` close times to `number`. | Closed by author in favor of [#1715](https://github.com/stellar/js-stellar-sdk/pull/1715) (same fix plus unit tests), not merged | 6 Sep 2026 |
| [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3881](https://github.com/solana-foundation/solana-web3.js/pull/3881) | ALT Freeze/Deactivate decoders validate instruction discriminators. | Closed by author: duplicate of [#3882](https://github.com/solana-foundation/solana-web3.js/pull/3882), not merged | 6 Sep 2026 |

## Issue claims (no PR until assigned)

Claimed on [drips-network/app](https://github.com/drips-network/app). Waiting for a maintainer to say the issue is still open for an external contribution. **No maintainer replies yet** (as of 10 Sep 2026).

| Issue | Claim | What | Status | Claimed |
| --- | --- | --- | --- | --- |
| [#1845](https://github.com/drips-network/app/issues/1845) | [comment](https://github.com/drips-network/app/issues/1845#issuecomment-5529629078) | Create-stream UI: Drip List URL is replaced with an internal account ID, then fails `validatedValue`. | Open, unassigned | 3 Sep 2026 |
| [#1509](https://github.com/drips-network/app/issues/1509) | [comment](https://github.com/drips-network/app/issues/1509#issuecomment-5531962994) | Transaction timeline titles stay imperative; should follow status (Approve → Approving → Approved). | Open, unassigned | 3 Sep 2026 |
| [#1576](https://github.com/drips-network/app/issues/1576) | [comment](https://github.com/drips-network/app/issues/1576#issuecomment-5531986355) | Hide the step index when a flow has only one transaction. | Open, unassigned | 3 Sep 2026 |
| [#1500](https://github.com/drips-network/app/issues/1500) | [comment](https://github.com/drips-network/app/issues/1500#issuecomment-5532011398) | Drip List chips don't pile: `DripListBadge` still mounts the `.name` row when name/owner are hidden. | Open, unassigned | 3 Sep 2026 |

## Wave 1 candidate queue

These are **candidate issues only**. No upstream claim has been posted yet, so they do not increase the external-item count.

| Priority | Repo | Issue | Why it is in Wave 1 | State |
| --- | --- | --- | --- | --- |
| 1 | [anza-xyz/sbpf](https://github.com/anza-xyz/sbpf) | [#204](https://github.com/anza-xyz/sbpf/issues/204) | `load_with_strict_parser` currently collapses many header validation failures into `InvalidFileHeader`; maintainers prefer a static diagnostic enum over runtime formatting. | Open; unassigned; 3 comments |
| 2 | [solana-program/create-solana-program](https://github.com/solana-program/create-solana-program) | [#127](https://github.com/solana-program/create-solana-program/issues/127) | CLI prints `RangeError: Incorrect locale information provided` immediately after the banner before prompting for input. | Open; unassigned; 0 comments |
| 3 | [solana-foundation/program-examples](https://github.com/solana-foundation/program-examples) | [#725](https://github.com/solana-foundation/program-examples/issues/725) | Failed token-fundraiser campaigns lack a teardown path, leaving fundraiser/vault rent stranded and direct vault transfers locked; fix should cover Anchor and Pinocchio. | Open; unassigned; 0 comments |
| 4 | [anza-xyz/sbpf](https://github.com/anza-xyz/sbpf) | [#202](https://github.com/anza-xyz/sbpf/issues/202) | `jit: validate_instruction_count` can simplify x86_64 code generation now that `pc` is `u32`; no issue comments were present during the scan. | Open; no comments |

### Stale candidates removed during the scan

| Candidate | Reason removed |
| --- | --- |
| [ethereumjs/ethereumjs-monorepo#4313](https://github.com/ethereumjs/ethereumjs-monorepo/issues/4313) | Fixed by merged [#4349](https://github.com/ethereumjs/ethereumjs-monorepo/pull/4349) on 21 Jul 2026. |
| [solana-program/token-2022#1325](https://github.com/solana-program/token-2022/issues/1325) | Closed as completed on 12 Aug 2026. |
| [solana-program/token-2022#1448](https://github.com/solana-program/token-2022/issues/1448) | Taken by [#1451](https://github.com/solana-program/token-2022/pull/1451). |

## Pipeline / not opened yet

| Repo | Target | Why waiting |
| --- | --- | --- |
| [ponder-sh/ponder](https://github.com/ponder-sh/ponder) | [#2363](https://github.com/ponder-sh/ponder/issues/2363) (also #2286 / #2264) | Backfill crash needs a confident repro against current `main` before a PR. Still in queue. |
| [wevm/wagmi](https://github.com/wevm/wagmi) | [#4396](https://github.com/wevm/wagmi/issues/4396) | Crowded (multiple open PRs). Shipped #5233 instead as #5240. |
| [solana-foundation/solana-web3.js](https://github.com/solana-foundation/solana-web3.js) | [#3853](https://github.com/solana-foundation/solana-web3.js/issues/3853) | v1.x PR #3882 closed (maintenance only). Only reopen on a non-v1.x / kit path if maintainers want it. |
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

Last updated: 11 Sep 2026 (IST: PR states re-reconciled directly against live GitHub; three closed-not-merged PRs previously missing from the Closed table (kit #2033, stellar #1714, solana-web3.js #3881) added; external-item total corrected 37 -> 40).


---

## 19. sdk-1
- **URL:** https://github.com/devtechedge/sdk-1
- **Language:** TypeScript
- **Topics:** None
- **Description:** Turnkey TypeScript SDK

### README.md

---
title: "Turnkey SDK"
---

# Turnkey SDK

[![js-build](https://github.com/tkhq/sdk/actions/workflows/js-build.yml/badge.svg)](https://github.com/tkhq/sdk/actions/workflows/js-build.yml)

## Overview

The Turnkey SDK includes functionality to interact with Turnkey in various contexts and ecosystems. It consists of three main NPM package groups.

- the [Primary Turnkey SDK Packages](#primary-turnkey-sdk-packages) which expose the main functionality required to build Turnkey-powered applications in different web and mobile environments
- the [Chain/Ecosystem-Specific Signing Packages](#chainecosystem-specific-signing-sdk-packages) which expose signers with support for specific ecosystems, built on top of our SDK packages
- the [Advanced Functionality SDK Packages](#advanced-functionality-sdk-packages) which exposes lower level functionality that is leveraged by our Primary SDK Packages for those with highly-specific implementations looking to use them.

The diagram below helps visualize the packages in our SDK organized by the functionality they expose.

<img src="./img/sdk-map.png" alt="homepage screenshot" width="1000px" />

## Primary Turnkey SDK Packages

The following packages expose the main functionality required to build Turnkey-powered applications. Each package exposes functions, and/or client classes with methods that manage the process of authenticating requests to the Turnkey API in the contexts of a generic browser environment or react client environment, or a server environment.

While these higher level packages are the main points of reference to be used while designing and building Turnkey applications, they wrap other packages with lower level functionality which we also expose separately for those who would like to explore them for more specialized use cases. These packages are listed and described below in the [Advanced Functionality SDK Packages](#advanced-functionality-sdk-packages) section.

Our main web SDK packages are as follows:

| Package                                                                                                    | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | NPM                                                                                                                                                     | Changelog                                                   | Docs                                                        |
| ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- |
| [@turnkey/react-wallet-kit](https://github.com/tkhq/sdk/tree/main/packages/react-wallet-kit)               | `@turnkey/react-wallet-kit` is the easiest way to integrate Turnkey’s Embedded Wallets into React applications. It works without requiring you to run your own backend, using Turnkey’s managed Auth Proxy, while still supporting backend-based architectures if needed. Built on @turnkey/core, it provides UI components and ergonomic hooks for quickly building secure embedded wallet experiences. This package supersedes `@turnkey/sdk-react`.                                                                                                                                                                                                                                                                                                                                 | [![npm](https://img.shields.io/npm/v/@turnkey/react-wallet-kit?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/react-wallet-kit)               | [CHANGELOG](/packages/react-wallet-kit/CHANGELOG.md)        | [Docs](https://docs.turnkey.com/sdks/react)                 |
| [@turnkey/react-native-wallet-kit](https://github.com/tkhq/sdk/tree/main/packages/react-native-wallet-kit) | `@turnkey/react-native-wallet-kit` is the easiest way to integrate Turnkey’s Embedded Wallets into React Native applications. It works without requiring you to run your own backend, using Turnkey’s managed Auth Proxy, while still supporting backend-based architectures if needed. Built on @turnkey/core, it provides ergonomic hooks and utilities for quickly building secure embedded wallet experiences. This package supersedes `@turnkey/sdk-react-native`.                                                                                                                                                                                                                                                                                                                | [![npm](https://img.shields.io/npm/v/@turnkey/react-native-wallet-kit?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/react-native-wallet-kit) | [CHANGELOG](/packages/react-native-wallet-kit/CHANGELOG.md) | [Docs](https://docs.turnkey.com/sdks/react-native/overview) |
| [@turnkey/core](/packages/core)                                                                            | `@turnkey/core` is a low-level TypeScript client SDK that provides the foundational building blocks used by Turnkey’s higher-level wallet kits. It includes primitives for interacting with Turnkey’s APIs, session management, stampers, and a raw HTTP client for advanced or custom integrations. This package is primarily intended for framework environments that do not yet have an official Turnkey wallet kit, such as Angular, Vue, or Svelte, or for advanced use cases that require direct access to Turnkey’s lower-level APIs. In most cases you shouldn’t use @turnkey/core directly, React and React Native apps should use the dedicated wallet kits instead. This package supersedes `@turnkey/sdk-browser`.                                                         | [![npm](https://img.shields.io/npm/v/@turnkey/http?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/core)                                       | [CHANGELOG](/packages/core/CHANGELOG.md)                    | [Docs](https://docs.turnkey.com/sdks/typescript-frontend)   |
| [@turnkey/sdk-server](https://github.com/tkhq/sdk/tree/main/packages/sdk-server)                           | The `@turnkey/sdk-server` package exposes functionality that lets developers build server-side functionality for applications that interact with the Turnkey API with different types of authentication – allowing applications to authenticate users, manage sessions, and perform organizational operations securely and efficiently. It consists of an API Client and API Proxies that enable requests to the Turnkey API to be authenticated with the appropriate credentials. Specifically, the API Client manages requests signed by the user's authentication details, and the API proxies handle requests signed by the parent organization's authentication details. Use this package to handle server-side interactions for applications that interact with the Turnkey API. | [![npm](https://img.shields.io/npm/v/@turnkey/sdk-server?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/sdk-server)                           | [CHANGELOG](/packages/sdk-server/CHANGELOG.md)              | [Docs](https://docs.turnkey.com/sdks/javascript-server)     |

The diagram below helps visualize how each package can be used to devlop the appropriate service in your Turnkey Powered Application, and how Turnkey requests would flow between those services.

<img src="./img/sdk-diagram.png" alt="homepage screenshot" width="1000px" />

## Chain/Ecosystem-Specific Signing SDK Packages

The following packages contain chain or ecosystem specific signers that take some of our [Primary Turnkey SDK Packages](#primary-turnkey-sdk-packages) and add additional support based on the signing process or transaction structure relevant to that specific chain or ecosystem.

| Package                                                     | NPM                                                                                                                                         | Description                                                                                       | Changelog                                             |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| [`@turnkey/ethers`](/packages/ethers)                       | [![npm](https://img.shields.io/npm/v/@turnkey/ethers?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/ethers)                       | Turnkey Signer for Ethers                                                                         | [CHANGELOG](/packages/ethers/CHANGELOG.md)            |
| [`@turnkey/viem`](/packages/viem)                           | [![npm](https://img.shields.io/npm/v/@turnkey/viem?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/viem)                           | Turnkey Signer for Viem                                                                           | [CHANGELOG](/packages/viem/CHANGELOG.md)              |
| [`@turnkey/cosmjs`](/packages/cosmjs)                       | [![npm](https://img.shields.io/npm/v/@turnkey/cosmjs?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/cosmjs)                       | Turnkey Signer for CosmJS                                                                         | [CHANGELOG](/packages/cosmjs/CHANGELOG.md)            |
| [`@turnkey/solana`](/packages/solana)                       | [![npm](https://img.shields.io/npm/v/@turnkey/solana?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/solana)                       | Turnkey Signer for Solana                                                                         | [CHANGELOG](/packages/solana/CHANGELOG.md)            |
| [`@turnkey/eip-1193-provider`](/packages/eip-1193-provider) | [![npm](https://img.shields.io/npm/v/@turnkey/eip-1193-provider?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/eip-1193-provider) | Turnkey-compatible EIP-1193 Provider                                                              | [CHANGELOG](/packages/eip-1193-provider/CHANGELOG.md) |
| [`@turnkey/gas-station`](/packages/gas-station)             | [![npm](https://img.shields.io/npm/v/@turnkey/gas-station?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/gas-station)             | Implement gasless transactions using EIP-7702, Turnkey wallet management, and your own paymaster. | [CHANGELOG](/packages/gas-station/CHANGELOG.md)       |

## Advanced Functionality SDK Packages

For those with more specialized use cases, Turnkey exposes it's lower level-libraries stamping and encryption libraries to be used directly. Note: for most use-cases, these libraries are not meant to be used directly and we encourage working on designing your application mainly using our [Primary Turnkey SDK Packages](#primary-turnkey-sdk-packages) along with our [Chain and Ecosystem Specific SDK Packages](#chainecosystem-specific-signing-sdk-packages) as per your use case!

### Request Stamping

| Package                                                                                 | NPM                                                                                                                                                                   | Description                                                                                             | Changelog                                                          | Docs                                                                                  |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------- |
| [`@turnkey/http`](/packages/http)                                                       | [![npm](https://img.shields.io/npm/v/@turnkey/http?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/http)                                                     | Lower-level, fully typed HTTP client for interacting with Turnkey API                                   | [CHANGELOG](/packages/http/CHANGELOG.md)                           | [Docs](https://docs.turnkey.com/sdks/advanced/turnkey-client)                         |
| [`@turnkey/api-key-stamper`](/packages/api-key-stamper)                                 | [![npm](https://img.shields.io/npm/v/@turnkey/api-key-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/api-key-stamper)                               | Provide API key signatures over Turnkey requests                                                        | [CHANGELOG](/packages/api-key-stamper/CHANGELOG.md)                | [Docs](https://docs.turnkey.com/sdks/advanced/api-key-stamper)                        |
| [`@turnkey/iframe-stamper`](/packages/iframe-stamper)                                   | [![npm](https://img.shields.io/npm/v/@turnkey/iframe-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/iframe-stamper)                                 | Provide API key signatures over Turnkey requests within iframe contexts                                 | [CHANGELOG](/packages/iframe-stamper/CHANGELOG.md)                 | [Docs](https://docs.turnkey.com/sdks/advanced/iframe-stamper)                         |
| [`@turnkey/webauthn-stamper`](/packages/webauthn-stamper)                               | [![npm](https://img.shields.io/npm/v/@turnkey/webauthn-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/webauthn-stamper)                             | Provide Webauthn signatures over Turnkey requests                                                       | [CHANGELOG](/packages/webauthn-stamper/CHANGELOG.md)               | [Docs](https://docs.turnkey.com/sdks/advanced/webauthn-stamper)                       |
| [`@turnkey/wallet-stamper`](/packages/wallet-stamper)                                   | [![npm](https://img.shields.io/npm/v/@turnkey/wallet-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/wallet-stamper)                                 | Provide wallet signatures over Turnkey requests                                                         | [CHANGELOG](/packages/wallet-stamper/CHANGELOG.md)                 | [Docs](https://docs.turnkey.com/sdks/advanced/wallet-stamper)                         |
| [`@turnkey/sdk-react-native-passkey-stamper`](/packages/react-native-passkey-stamper/)  | [![npm](https://img.shields.io/npm/v/@turnkey/react-native-passkey-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/react-native-passkey-stamper)     | Provide Passkey signatures over Turnkey requests in a React Native context                              | [CHANGELOG](/packages/react-native-passkey-stamper/CHANGELOG.md)   | [Docs](https://docs.turnkey.com/sdks/react-native)                                    |
| [`@turnkey/indexed-db-stamper/`](/packages/indexed-db-stamper/)                         | [![npm](https://img.shields.io/npm/v/@turnkey/indexed-db-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/indexed-db-stamper)                         | Enables secure request stamping using an unextractable P-256 keypair stored in the browser’s IndexedDB. | [CHANGELOG](/packages/indexed-db-stamper/CHANGELOG.md)             | [Docs](https://docs.turnkey.com/authentication/sessions#indexeddb-web-only-:)         |
| [`@turnkey/telegram-cloud-storage-stamper/`](/packages/telegram-cloud-storage-stamper/) | [![npm](https://img.shields.io/npm/v/@turnkey/telegram-cloud-storage-stamper?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/telegram-cloud-storage-stamper) | Handles stamping a Turnkey request with an API key stored within Telegram Cloud Storage.                | [CHANGELOG](/packages/telegram-cloud-storage-stamper/CHANGELOG.md) | [Docs](https://github.com/tkhq/sdk/tree/main/packages/telegram-cloud-storage-stamper) |

### Utilities

| Package                                   | NPM                                                                                                                       | Description                                                       | Changelog                                    |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------- |
| [`@turnkey/encoding`](/packages/encoding) | [![npm](https://img.shields.io/npm/v/@turnkey/encoding?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/encoding) | Encoding and decoding utilities, primarily for internal usage     | [CHANGELOG](/packages/encoding/CHANGELOG.md) |
| [`@turnkey/crypto`](/packages/crypto)     | [![npm](https://img.shields.io/npm/v/@turnkey/crypto?color=%234C48FF)](https://www.npmjs.com/package/@turnkey/crypto)     | Cryptographic utilities for P256 keys, encryption, and decryption | [CHANGELOG](/packages/crypto/CHANGELOG.md)   |

## Code Examples

### Instant examples (powered by Stackblitz)

The following code examples have been loaded into Stackblitz web environments so you can test them out immediately

| Example                                                                          | Description                                                                                                                             | Stackblitz Link                                                                      |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [`email-auth-local-storage`](/examples/authentication/email-auth-local-storage/) | A NextJS app demonstrating a complete email auth flow using a locally stored target embedded key                                        | [Test it out on Stackblitz!](https://stackblitz.com/edit/stackblitz-starters-pyyw59) |
| [`with-eth-passkeys-galore`](/examples/demos/with-eth-passkeys-galore/)          | A NextJS app powering users to create suborgs and sign messages via Viem or Ethers                                                      | [Test it out on Stackblitz!](https://stackblitz.com/edit/stackblitz-starters-2psu3g) |
| [`with-solana`](/examples/chain-integrations/with-solana/)                       | Create a new Solana address, then sign and broadcast a transaction on Solana's devnet                                                   | [Test it out on Stackblitz!](https://stackblitz.com/edit/stackblitz-starters-xeb93i) |
| [`with-solana-passkeys`](/examples/authentication/with-solana-passkeys/)         | A NextJS app powering users to create suborgs, sign messages, and create transactions sponsored by the parent org using @turnkey/solana | [Test it out on Stackblitz!](https://stackblitz.com/edit/stackblitz-starters-h5pmnu) |

### Other Code Examples

The below examples will require a local installation of `node.js`. Follow the specific instructions in the respective README's of each examples to run them!

| Example                                                                                            | Description                                                                                                                                                                              |
| -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`demo-consumer-wallet`](https://github.com/tkhq/demo-consumer-wallet)                             | A minimal consumer wallet app powered by Turnkey and WalletConnect                                                                                                                       |
| [`demo-passkey-wallet`](https://github.com/tkhq/demo-passkey-wallet)                               | A minimal consumer wallet app powered by Turnkey and passkeys                                                                                                                            |
| [`demo-ethers-passkeys`](https://github.com/tkhq/demo-ethers-passkeys)                             | A NextJS app that demonstrates how to use `@turnkey/ethers` to build a passkey-powered application                                                                                       |
| [`demo-viem-passkeys`](https://github.com/tkhq/demo-viem-passkeys)                                 | A NextJS app that demonstrates how to use `@turnkey/viem` to build a passkey-powered application                                                                                         |
| [`react-native-demo-wallet`](https://github.com/tkhq/react-native-demo-wallet)                     | A React Native app that demonstrates how to use the Turnkey's JavaScript packages in a mobile environment to authenticate users, create wallets, export wallets, sign messages, and more |
| [`flutter-demo-app`](https://github.com/tkhq/dart-sdk/tree/main/examples/flutter-demo-app)         | A Flutter app that demonstrates how to use the Turnkey's Flutter packages to authenticate users, create wallets, export wallets, sign messages, and more                                 |
| [`deployer`](/examples/advanced/deployer/)                                                         | Compile and deploy a smart contract                                                                                                                                                      |
| [`email-auth`](/examples/authentication/email-auth/)                                               | A NextJS app demonstrating a complete email auth flow using Turnkey iframes                                                                                                              |
| [`import-export-with-iframe-stamper`](/examples/key-management/import-export-with-iframe-stamper/) | A NextJS app demonstrating wallet import, export, and retrieval using iframes                                                                                                            |
| [`import-export-with-rwk`](/examples/key-management/import-export-with-rwk/)                       | A NextJS app demonstrating wallet and private key import and export using React Wallet Kit                                                                                               |
| [`wallet-export-sign`](/examples/key-management/wallet-export-sign/)                               | A NextJS app demonstrating wallet and wallet account export, and signing with the exported key                                                                                           |
| [`rebalancer`](/examples/transaction-management/rebalancer/)                                       | A demo application which showcases an example of how to use Turnkey for managing multiple types of keys & users                                                                          |
| [`solana-cctp-bridge`](/examples/transaction-management/solana-cctp-bridge/)                       | Bridge USDC from Solana to Base through Circle CCTP using three Turnkey-managed Solana signers (owner, MessageSent event account, rent payer)                                            |
| [`sweeper`](/examples/transaction-management/sweeper/)                                             | Sweep funds from one address to a different address                                                                                                                                      |
| [`trading-runner`](/examples/defi/trading-runner/)                                                 | A sample application demonstrating a trading operation, using various private keys, users, and policies, powered by Uniswap                                                              |
| [`with-ethers`](/examples/chain-integrations/with-ethers/)                                         | Create a new Ethereum address, then sign and broadcast a transaction using the Ethers signer with Infura                                                                                 |
| [`with-viem`](/examples/chain-integrations/with-viem/)                                             | Sign and broadcast a transaction using the Turnkey Custom Account and Infura                                                                                                             |
| [`with-cosmjs`](/examples/chain-integrations/with-cosmjs/)                                         | Create a new Cosmos address, then sign and broadcast a transaction on Celestia testnet using the CosmJS signer                                                                           |
| [`with-bitcoin`](/examples/chain-integrations/with-bitcoin/)                                       | Create a new wallet, derive a BTC address, create, sign, and broadcast a transaction using BitcoinJS and other external APIs                                                             |
| [`with-biconomy-aa`](/examples/account-abstraction/with-biconomy-aa/)                              | Create a new wallet, connect a Turnkey wallet client to Biconomy Nexus, and create, sign, and broadcast an EIP-1559 transaction                                                          |
| [`with-zerodev-aa`](/examples/account-abstraction/with-zerodev-aa/)                                | Create a new wallet, instantiate a Turnkey signer, create a ZeroDev kernel account and client, and broadcast a UserOp                                                                    |
| [`with-gnosis`](/examples/account-abstraction/with-gnosis/)                                        | Create new Ethereum addresses, configure a 3/3 Gnosis safe, and create + execute a transaction from it                                                                                   |
| [`with-uniswap`](/examples/defi/with-uniswap/)                                                     | Sign and broadcast a Uniswap v3 trade using the Ethers signer with Infura                                                                                                                |
| [`solana-usdc-swap`](/examples/defi/solana-usdc-swap/)                                             | Swap SOL to USDC through Jupiter using Turnkey Solana sponsorship with rent-safe token account handling                                                                                  |
| [`with-nonce-manager`](/examples/transaction-management/with-nonce-manager/)                       | Create a new Ethereum address, then sign and broadcast multiple transactions in a sequential or optimistic manner                                                                        |
| [`with-offline`](/examples/advanced/with-offline/)                                                 | Sign a Turnkey request in offline context                                                                                                                                                |
| [`with-federated-passkeys`](/examples/authentication/with-federated-passkeys/)                     | A NextJS app that demonstrates how to use Turnkey to build a federated, webauthn powered authentication flow                                                                             |
| [`with-eip-1193-provider`](/examples/chain-integrations/with-eip-1193-provider/)                   | A NextJS app that demonstrates how to use Turnkey the `@turnkey/eip-1193-provider` in your app                                                                                           |
| [`with-wallet-stamper`](/examples/authentication/with-wallet-stamper/)                             | A NextJS app that demonstrates how to use Turnkey the `@turnkey/wallet-stamper` in your app                                                                                              |

## Demos built with Turnkey

### Demo Consumer Wallet ([code](https://github.com/tkhq/demo-consumer-wallet))

A minimal consumer wallet app powered by Turnkey. Behind the scenes, it uses [`@turnkey/ethers`](https://www.npmjs.com/package/@turnkey/ethers) for signing and WalletConnect (v1) for accessing dapps.

https://github.com/tkhq/demo-consumer-wallet/assets/127255904/2c3409df-2d7c-4ec3-9aa8-e2944a0b0e0a

See https://github.com/tkhq/demo-consumer-wallet for the code.

### Demo Passkey Wallet ([code](https://github.com/tkhq/demo-passkey-wallet), [live link](https://wallet.tx.xyz))

A wallet application showing how users can register and authenticate using passkeys.
This demo uses the Turnkey API to create a new [Turnkey Sub-Organization](https://docs.turnkey.com/concepts/sub-organizations) for each user, create a testnet Ethereum address and send a transaction on Sepolia (ETH testnet).

<img src="./img/demo-passkey-wallet.png" alt="homepage screenshot" width="800px" />

See https://wallet.tx.xyz (and https://github.com/tkhq/demo-passkey-wallet for the code).

### Demo Ethers Passkeys ([code](https://github.com/tkhq/demo-ethers-passkeys))

A simple application demonstrating how to create sub-organizations, create private keys, and sign with the [`@turnkey/ethers`](https://github.com/tkhq/sdk/tree/main/packages/ethers) signer, using passkeys.

<img src="./img/ethers-ui-screenshot.png" alt="homepage screenshot" width="800px" />

See https://github.com/tkhq/demo-ethers-passkeys for the code.

### Demo Viem Passkeys ([code](https://github.com/tkhq/demo-viem-passkeys))

A similar, simple application demonstrating how to create sub-organizations, create private keys, and sign with the [`@turnkey/viem`](https://github.com/tkhq/sdk/tree/main/packages/viem) signer, using passkeys.

<img src="./img/viem-ui-screenshot.png" alt="homepage screenshot" width="800px" />

See https://github.com/tkhq/demo-viem-passkeys for the code.

### React Native Demo App ([code](https://github.com/tkhq/react-native-demo-wallet))

A React Native app that demonstrates how to use the Turnkey's JavaScript packages in a mobile environment to authenticate users, create wallets, export wallets, sign messages, and more

https://github.com/user-attachments/assets/e4cff012-11e9-4636-b67a-5dbf75355832

See https://github.com/tkhq/react-native-demo-wallet for the code.

### Flutter Demo App ([code](https://github.com/tkhq/dart-sdk/tree/main/examples/flutter-demo-app))

A Flutter app that demonstrates how to use the Turnkey's Flutter packages to authenticate users, create wallets, export wallets, sign messages, and more

https://github.com/user-attachments/assets/3d583ed8-1eff-4101-ae43-3c76c655e635

See https://github.com/tkhq/dart-sdk/tree/main/examples/flutter-demo-app for the code


---

## 20. toolkit
- **URL:** https://github.com/devtechedge/toolkit
- **Language:** TypeScript
- **Topics:** None
- **Description:** No description

### README.md

<br/>

<p align="center">
  <a href="https://across.to">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/across-protocol/toolkit/refs/heads/master/.github/across-logo-dark.png">
        <img alt="across logo" src="https://raw.githubusercontent.com/across-protocol/toolkit/refs/heads/master/.github/across-logo-light.png" width="auto" height="60">
      </picture>
</a>
</p>

<p align="center">
  Toolkit  🛠️ for building on top of the <a href="https://across.to">Across Protocol</a> 
<p>
<p align="center">
  Fastest and lowest-cost bridging for end-users. Streamlined interoperability for developers.
</p>

<p align="center">
  <a href="https://discord.across.to" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Chat%20on-Discord-%235766f2" />
  </a>
  <a href="https://github.com/across-protocol/toolkit/blob/master/LICENSE">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/license-AGPL-21262d?style=flat">
      <img src="https://img.shields.io/badge/license-AGPL-f6f8fa?style=flat" alt="MIT License">
    </picture>
  </a>
  <a href="https://twitter.com/AcrossProtocol/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/twitter/follow/AcrossProtocol?style=social"/>
  </a>
</p>

<br>

## Overview

Quickly integrate with a few lines of code. See [here](./packages/sdk/README.md) for more details.

```ts
import { createAcrossClient } from "@across-protocol/app-sdk";
import { mainnet, optimism, arbitrum } from "viem/chains";
import { useWalletClient } from "wagmi";

const wallet = useWalletClient();

// 1. Create client
const client = createAcrossClient({
  integratorId: "0xdead", // 2-byte hex string
  chains: [mainnet, optimism, arbitrum],
});

// 2. Retrieve quote for USDC from Arbitrum -> ETH on Optimism
const route = {
  originChainId: arbitrum.id,
  destinationChainId: optimism.id,
  inputToken: "0xaf88d065e77c8cC2239327C5EDb3A432268e5831", // USDC
  outputToken: "0x0000000000000000000000000000000000000000", // Native ETH
};
const swapQuote = await client.getSwapQuote({
  route,
  amount: parseUnit("10", 6), // USDC decimals
});

// 3. Execute quote
await client.executeSwapQuote({
  walletClient: wallet,
  swapQuote,
  onProgress: (progress) => {
    // handle progress
  },
});
```

## Tools

| Package                                                | Description                                                                                |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| [`@across-protocol/app-sdk`](./packages/sdk/README.md) | TypeScript package for building on top of Across Protocol's Smart Contracts and Quotes API |

## Examples

| App                                | Description                          |
| ---------------------------------- | ------------------------------------ |
| [using viem](./apps/example/app)   | Example Next.js app using [viem]()   |
| [using ethers](./apps/example/app) | Example Next.js app using [ethers]() |

## Links

- Website: <https://across.to>
- App: <https://app.across.to>
- Docs: <https://docs.across.to>
- X/Twitter: <https://x.com/AcrossProtocol>
- Medium: <https://medium.com/across-protocol>


---

## 21. node-postgres
- **URL:** https://github.com/devtechedge/node-postgres
- **Language:** JavaScript
- **Topics:** None
- **Description:** PostgreSQL client for node.js.

### README.md

# node-postgres

![Build Status](https://github.com/brianc/node-postgres/actions/workflows/ci.yml/badge.svg)
<span class="badge-npmversion"><a href="https://npmjs.org/package/pg" title="View this project on NPM"><img src="https://img.shields.io/npm/v/pg.svg" alt="NPM version" /></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/pg" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/pg.svg" alt="NPM downloads" /></a></span>

Non-blocking PostgreSQL client for Node.js (and bun, deno, cloudflare, etc...). Pure JavaScript and optional native libpq bindings.

## Monorepo

This repo is a monorepo which contains the core [pg](https://github.com/brianc/node-postgres/tree/master/packages/pg) module as well as a handful of related modules.

- [pg](https://github.com/brianc/node-postgres/tree/master/packages/pg)
- [pg-pool](https://github.com/brianc/node-postgres/tree/master/packages/pg-pool)
- [pg-native](https://github.com/brianc/node-postgres/tree/master/packages/pg-native)
- [pg-cursor](https://github.com/brianc/node-postgres/tree/master/packages/pg-cursor)
- [pg-query-stream](https://github.com/brianc/node-postgres/tree/master/packages/pg-query-stream)
- [pg-connection-string](https://github.com/brianc/node-postgres/tree/master/packages/pg-connection-string)
- [pg-protocol](https://github.com/brianc/node-postgres/tree/master/packages/pg-protocol)

## Install

```
npm install pg
```

## Documentation

Each package in this repo should have its own readme more focused on how to develop/contribute. For overall documentation on the project and the related modules managed by this repo please see:

### :star: [Documentation](https://node-postgres.com) :star:

The source repo for the documentation is available for contribution [here](https://github.com/brianc/node-postgres/tree/master/docs).

### Features

- [Fastest PostgreSQL client for Node.js](https://github.com/nigrosimone/postgres-benchmarks)
- Pure JavaScript client and native libpq bindings share _the same API_
- Connection pooling
- Extensible JS ↔ PostgreSQL data-type coercion
- Supported PostgreSQL features
  - Parameterized queries
  - Named statements with query plan caching
  - Async notifications with `LISTEN/NOTIFY`
  - Bulk import & export with `COPY TO/COPY FROM`

### Extras

node-postgres is by design pretty light on abstractions. These are some handy modules we've been using over the years to complete the picture.
The entire list can be found on our [wiki](https://github.com/brianc/node-postgres/wiki/Extras).

## Support

node-postgres is free software. If you encounter a bug with the library please open an issue on the [GitHub repo](https://github.com/brianc/node-postgres). If you have questions unanswered by the documentation please open an issue pointing out how the documentation was unclear & I will do my best to make it better!

When you open an issue please provide:

- version of Node
- version of Postgres
- smallest possible snippet of code to reproduce the problem

You can also follow me [@brianc](https://bsky.app/profile/brianc.bsky.social) on bluesky if that's your thing for updates on node-postgres with nearly zero non node-postgres content. My old twitter/x account is no longer used.

## Sponsorship :two_hearts:

node-postgres's continued development has been made possible in part by generous financial support from [the community](https://github.com/brianc/node-postgres/blob/master/SPONSORS.md).

If you or your company are benefiting from node-postgres and would like to help keep the project financially sustainable [please consider supporting](https://github.com/sponsors/brianc) its development.

### Featured sponsor

Special thanks to [medplum](https://medplum.com) for their generous and thoughtful support of node-postgres!

<img src="https://github.com/medplum/medplum-logo/blob/main/v3/medplum-logo-grape8.svg" alt="Medplum logo" width="20%" />

## Contributing

**:heart: contributions!**

I will **happily** accept your pull request if it:

- **has tests**
- looks reasonable
- does not break backwards compatibility

If your change involves breaking backwards compatibility please please point that out in the pull request & we can discuss & plan when and how to release it and what type of documentation or communication it will require.

### Setting up for local development

1. Clone the repo
2. Ensure you have installed libpq-dev in your system (the native bindings are built in the test process)
3. From your workspace root run `yarn` and then `yarn lerna bootstrap`
4. Ensure you have a PostgreSQL instance running with SSL enabled and an empty database for tests. _note: you can skip the tests requring SSL by setting the environment variable `PGTESTNOSSL=1` if you're not changing any SSL related code_.
5. Ensure you have the proper environment variables configured for connecting to your postgres instance. Using the standard `PG*` environment variables like `PGUSER` and `PGPASSWORD` etc...
6. Run `yarn test` to run all the tests.

## Troubleshooting and FAQ

The causes and solutions to common errors can be found among the [Frequently Asked Questions (FAQ)](https://github.com/brianc/node-postgres/wiki/FAQ)

## License

Copyright (c) 2010-2020 Brian Carlson (brian.m.carlson@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


---

## 22. interceptors
- **URL:** https://github.com/devtechedge/interceptors
- **Language:** TypeScript
- **Topics:** None
- **Description:** Low-level network interception library for Node.js.

### README.md

# `@mswjs/interceptors`

Low-level network interception library for Node.js.

Use this library if you wish to intercept any of the below:

- Raw TCP and TLS socket connections (`net.connect()`, `tls.connect()`);
- HTTP requests regardless of the request client (e.g. `http.request()`, `axios()`, etc);
- Fetch requests (both global `fetch()` and custom fetch implementations like `undici()`);
- WebSocket connections (global `WebSocket` constructor).

## Motivation

There has been a few attempts at the network interception in Node.js throughout its existence. Around 2018, those efforts have settled on patching `http.request()` and `http.ClientRequest`, if not resorting to far worse practices like patching request clients directly. These algorithms turned network requests into black boxes that, effectively, short-circuited the network code at the interception point.

Consider how Node.js orchestrates an average HTTP request:

```
1. Third-party request client (axios/got/etc);
---- node:http / node:https ----
2. http.request() (node:http/node:https);
3. new http.ClientRequest();
---- node:net / node:tls ----
4. net.connect() / tls.connect();
5. new net.Socket();
6. socket.connect();
---- native bindings ----
7. TCPWrap / TLSWrap;
---- C++ network code ---
8. [TOO_COMPLEX_TO_FATHOM];
```

You can see how intercepting requests at the `http.request()` level (2) is rather limiting as, typically, nothing executes past the interception point. As a result, whenever such interception is introduced, it significantly deviates your system from how it normally behaves otherwise.

So I decided to build a network interception algorithm that would have no such limitations, would execute as much of the Node.js network code as possible, and actually establish network connections (yes, even when mocking requests to non-existing hosts). On top of that, I want that algorithm to be fully available for anybody who wishes to build their own API mocking library.

### What makes Interceptors different?

Interceptors (the library you're reading about) implements the network interception on the TCP/TLS handle level (point 7 on the graph above). In the simplest of terms, it's the lowest possible level to spy on outgoing traffic without having to recompile Node.js on your machine.

In more technical terms, the algorithm combines multiple entry points along the network graph, each playing its role in the interception:

- Spies on the network on the socket level by intercepting `Socket.prototype.connect`, `net.connect()`, and `tls.connect()`;
- Stubs `TCPWrap`/`TLSWrap` until the connection is either claimed or passed through;
- Wraps socket-level interception in higher-level interceptors, like `HttpRequestInterceptor`, which pipe outgoing and incoming socket packets through respective parsers;
- Wraps higher-level interceptors in request client interceptors that leverage `AsyncLocalStorage` to annotate request initiators without intercepting any traffic themselves (a socket connection are unaware of any protocols, let alone request clients that triggered the connection);

Intercepting the network this low on the network graph means executing as much of Node.js network code as physically possible even when mocking requests. This minimizes the deviations introduced by the said interception and yields a more compliant mocking experience.

## When to use Interceptors?

Interceptors is **not** an API mocking library. It's a low-level network interception library. Mocking the network is just a subset of what you can do with it.

As a rule of thumb, if you're uncertain whether you need Interceptors, you likely don't. Interceptors exist primarily to help other developers implement their own higher-level API mocking libraries, like [Nock](https://github.com/nock/nock) or [Mock Service Worker](https://mswjs.io), with the goal of unifying the network interception algorithm for richer features and better runtime compliance.

## Getting started

```bash
npm i @mswjs/interceptors
```

### Debugging

Enable default interceptor logs with `debug` namespaces:

```bash
DEBUG='interceptors:*' node app.js
```

Default logs cover interceptor lifecycle, requests, and request
resolution. Add verbose logs for socket packets, event forwarding, and other
internals:

```bash
DEBUG='interceptors:*' DEBUG_LEVEL=verbose node app.js
```

Scope either level to an interceptor using its lowercase kebab-case name, such
as `interceptors:fetch`, `interceptors:xhr`, `interceptors:client-request`, or
`interceptors:websocket`. In browsers, assign the same value to
`localStorage.debug` and set `localStorage.debugLevel` to `verbose` for verbose
logs. Each namespace has a stable color.

## Interceptors

To use this library you need to choose one or multiple interceptors to apply. There are different interceptors exported by this library to spy on respective request-issuing modules:

- [`SocketInterceptor`](#socketinterceptor) to spy on any socket connections in Node.js;
- [`HttpRequestInterceptor`](#httprequestinterceptor) to spy on any HTTP requests in Node.js;
- [`ClientRequestInterceptor`](#clientrequestinterceptor) to spy on `http.ClientRequest` (`http.get`/`http.request`);
- [`XMLHttpRequestInterceptor`](#xmlhttprequestinterceptor) to spy on `XMLHttpRequest`;
- [`FetchInterceptor`](#fetchinterceptor) to spy on the global `fetch`;
- [`WebSocketInterceptor`](#websocketinterceptor) to spy on WebSocket connections.

You can combine multiple interceptors using [`BatchInterceptor`](#batchinterceptor).

### `SocketInterceptor`

The lowest-level interceptor in this library. It intercepts _every outgoing TCP and TLS connection_ in Node.js at the `net.Socket` level, no matter which module or third-party package creates it. It is the foundation the HTTP interceptors below are built upon.

```js
import { SocketInterceptor } from '@mswjs/interceptors/net'

const interceptor = new SocketInterceptor()

interceptor.on('connection', ({ socket, connectionOptions, controller }) => {
  if (connectionOptions.host === 'example.com') {
    controller.claim()

    socket.on('data', (chunk) => {
      socket.write(anotherChunk)
    })
  }
})

interceptor.apply()
```

> The exposed `socket` instance is _mirrored_ so you can think of the connection listener as a server-side handler. It emits `data` when the client _writes_ to it and writing to it will emit `data` events on the intercepted socket.

The `connection` event is emitted whenever a socket connection is open in this process. Use its listener to inspect and it decide whether you want to claim it for manual management (`controller.claim()`) or let it pass through (`controller.passthrough()`). Until you decide either, the connection will remain in the pending state.

### `HttpRequestInterceptor`

Intercepts **all HTTP requests in Node.js, regardless of the client** that issued them. Because the interception happens at the socket level, this includes `http`/`https` modules, the global `fetch`, direct Undici usage (`fetch`, `request`, pools, agents), and any third-party HTTP client built on top of them (Axios, Got, node-fetch, superagent, etc).

```js
import { HttpRequestInterceptor } from '@mswjs/interceptors/http'

const interceptor = new HttpRequestInterceptor()
interceptor.apply()
```

#### Observing requests

Add a listener to the `request` event to observe outgoing HTTP requests. The listener exposes the intercepted request as a [Fetch API `Request`](https://developer.mozilla.org/en-US/docs/Web/API/Request) instance.

> There are many ways to describe a request in Node.js but this library coerces different request definitions to a single specification-compliant `Request` instance to make the handling consistent.

```js
interceptor.on('request', ({ request, requestId }) => {
  console.log(request.method, request.url)
})
```

Since the exposed `request` instance implements the Fetch API specification, you can operate with it just as you do with the regular browser request. For example, this is how you would read the request body as JSON:

```js
interceptor.on('request', async ({ request, requestId }) => {
  const json = await request.clone().json()
})
```

> Make sure to clone the request before reading its body.

##### Request initiator

The `request` event exposes an `initiator` property that references the object that issued the intercepted request:

- an `http.ClientRequest` instance for requests made via the `http`/`https` modules;
- a Fetch API `Request` instance for requests made via the global `fetch`;
- an `XMLHttpRequest` instance for requests made via `XMLHttpRequest`;
- a `net.Socket` instance for requests that cannot be attributed to a known client (e.g. raw socket connections or direct Undici usage).

> Attributing a request to its client requires the corresponding client-level interceptor ([`ClientRequestInterceptor`](#clientrequestinterceptor), [`FetchInterceptor`](#fetchinterceptor), or [`XMLHttpRequestInterceptor`](#xmlhttprequestinterceptor)) to be applied alongside `HttpRequestInterceptor`. With `HttpRequestInterceptor` alone, the initiator is the underlying `net.Socket`.

The initiator is typed as `unknown`. Narrow it down with `instanceof` to access the client-specific state, e.g. to tell the requests from different clients apart:

```js
import http from 'node:http'

interceptor.on('request', ({ request, initiator }) => {
  if (initiator instanceof http.ClientRequest) {
    // This request was made via "http.request()"/"http.get()".
    console.log(initiator.getHeaders())
  }

  if (initiator instanceof Request) {
    // This request was made via the global "fetch".
  }
})
```

#### Modifying outgoing requests

Request representations are readonly. You can, however, mutate the intercepted request's headers in the `request` listener. The modified headers are sent to the actual server if the request is performed as-is:

```js
interceptor.on('request', ({ request }) => {
  request.headers.set('x-my-header', 'true')
})
```

> This restriction is done so that the library wouldn't have to unnecessarily synchronize the actual request instance and its Fetch API request representation. As of now, this library is not meant to be used as a full-scale proxy.

#### Mocking responses

Although this library can be used purely for observing the network, you can also affect request resolution by responding to any intercepted request within the `request` event.

Access the `controller` object from the request event listener arguments and call its `controller.respondWith()` method, providing it with a mocked `Response` instance:

```js
interceptor.on('request', ({ request, controller }) => {
  controller.respondWith(
    new Response(
      JSON.stringify({
        firstName: 'John',
        lastName: 'Maverick',
      }),
      {
        status: 201,
        statusText: 'Created',
        headers: {
          'Content-Type': 'application/json',
        },
      }
    )
  )
})
```

> We use Fetch API `Response` class as the middle-ground for mocked response definition. This library then coerces the response instance to the appropriate response format (e.g. to `http.OutgoingMessage` in the case of `http.ClientRequest`).

Note that a single request _can only be handled once_. You may want to introduce conditional logic, like routing, in your request listener but it's generally advised to use a higher-level library like [Mock Service Worker](https://github.com/mswjs/msw) that does request matching for you.

Requests must be responded to within the same tick as the request listener. This means you cannot respond to a request using `setTimeout`, as this will delegate the callback to the next tick. If you wish to introduce asynchronous side-effects in the listener, consider making it an `async` function, awaiting any side-effects you need.

```js
import { setTimeout } from 'node:timers/promises'

// Respond to all requests with a 500 response
// delayed by 500ms.
interceptor.on('request', async ({ controller }) => {
  await setTimeout(500)
  controller.respondWith(new Response(null, { status: 500 }))
})
```

##### Mocking response errors

You can provide an instance of `Response.error()` to error the pending request.

```js
interceptor.on('request', ({ request, controller }) => {
  controller.respondWith(Response.error())
})
```

This will automatically translate to the appropriate request error based on the request client that issued the request. **Use this method to produce a generic network error**.

> Note that the standard `Response.error()` API does not accept an error message.

##### Mocking errors

Use the `controller.errorWith()` method to error the request.

```js
interceptor.on('request', ({ request, controller }) => {
  controller.errorWith(new Error('reason'))
})
```

Unlike responding with `Response.error()`, you can provide an exact error reason to use to `.errorWith()`. **Use this method to error the request**.

> Note that it is up to the request client to respect your custom error. Some clients, like `ClientRequest` will use the provided error message, while others, like `fetch`, will produce a generic `TypeError: failed to fetch` responses. Interceptors will try to preserve the original error in the `cause` property of such generic errors.

##### Handling exceptions

By default, all unhandled exceptions thrown within the `request` listener are coerced to 500 error responses, emulating those exceptions occurring on the actual server. You can listen to the exceptions by adding the `unhandledException` listener to the interceptor:

```js
interceptor.on(
  'unhandledException',
  ({ error, request, requestId, controller }) => {
    console.log(error)
  }
)
```

To opt out from the default coercion of unhandled exceptions to server responses, you need to either:

1. Respond to the request with [a mocked response](#mocking-responses) (including error responses);
1. Propagate the error up by throwing it explicitly in the `unhandledException` listener.

Here's an example of propagating the unhandled exception up:

```js
interceptor.on('unhandledException', ({ error }) => {
  // Now, any unhandled exception will NOT be coerced to a 500 error response,
  // and instead will be thrown during the process execution as-is.
  throw error
})
```

#### Observing responses

You can use the `response` event to transparently observe any incoming responses in your Node.js process.

```js
interceptor.on(
  'response',
  ({ response, responseType, request, requestId }) => {
    // react to the incoming response...
  }
)
```

> Note that the `responseType` property equals `"mock"` if you resolved this request in the `request` event listener using the `controller.respondWith()` method, and `"original"` for the responses received from the actual server.

### `ClientRequestInterceptor`

Intercepts HTTP requests made via `http.ClientRequest`—that is, `http.get()`/`http.request()` and their `https` counterparts (this also covers third-party clients built on top of them, like Axios or Got).

```js
import { ClientRequestInterceptor } from '@mswjs/interceptors/ClientRequest'

const interceptor = new ClientRequestInterceptor()
interceptor.apply()

interceptor.on('request', ({ request, controller }) => {
  console.log(request.method, request.url)
  controller.respondWith(new Response('Hello world'))
})
```

This interceptor implements the same events as [`HttpRequestInterceptor`](#httprequestinterceptor)—`request`, `response`, and `unhandledException`—and you subscribe to them in the same way. See the sections above for observing, modifying, and mocking requests.

### `XMLHttpRequestInterceptor`

Intercepts HTTP requests made via `XMLHttpRequest`, both in the browser and in Node.js (e.g. in test environments polyfilling `XMLHttpRequest`, like JSDOM).

```js
import { XMLHttpRequestInterceptor } from '@mswjs/interceptors/XMLHttpRequest'

const interceptor = new XMLHttpRequestInterceptor()
interceptor.apply()

interceptor.on('request', ({ request, controller }) => {
  console.log(request.method, request.url)
  controller.respondWith(new Response('Hello world'))
})
```

This interceptor implements the same events as [`HttpRequestInterceptor`](#httprequestinterceptor)—`request`, `response`, and `unhandledException`—and you subscribe to them in the same way.

This interceptor has two versions: `/node` and `/web`. The `@mswjs/interceptors/XMLHttpRequest` import automatically loads the correct one based on your environment. If you wish, you can import the exact version manually:

```js
import { XMLHttpRequestInterceptor } from '@mswjs/interceptors/XMLHttpRequest/node'
import { XMLHttpRequestInterceptor } from '@mswjs/interceptors/XMLHttpRequest/web'
```

### `FetchInterceptor`

Intercepts HTTP requests made via the global `fetch` function. In Node.js, the global `fetch` is powered by Undici; in the browser, it is the native `window.fetch`.

> To intercept the requests made via _direct_ Undici imports (e.g. `fetch` or `request` from the `undici` package), use the [`HttpRequestInterceptor`](#httprequestinterceptor) instead—those requests do not go through the global `fetch` but are still intercepted at the socket level.

```js
import { FetchInterceptor } from '@mswjs/interceptors/fetch'

const interceptor = new FetchInterceptor()
interceptor.apply()

interceptor.on('request', ({ request, controller }) => {
  console.log(request.method, request.url)
  controller.respondWith(new Response('Hello world'))
})
```

This interceptor implements the same events as [`HttpRequestInterceptor`](#httprequestinterceptor)—`request`, `response`, and `unhandledException`—and you subscribe to them in the same way.

This interceptor has two versions: `/node` and `/web`. The `@mswjs/interceptors/fetch` import automatically loads the correct one based on your environment. If you wish, you can import the exact version manually:

```js
import { FetchInterceptor } from '@mswjs/interceptors/fetch/node'
import { FetchInterceptor } from '@mswjs/interceptors/fetch/web'
```

### `WebSocketInterceptor`

Intercepts WebSocket connections created using the global WHATWG `WebSocket` class.

> [!IMPORTANT]
> The `WebSocketInterceptor` provides its connection-level API only for the global WHATWG `WebSocket` class. In Node.js, WebSocket handshakes issued by other clients (e.g. the `ws` package or direct Undici usage) are additionally interceptable at the HTTP layer as `Upgrade` requests via the [`HttpRequestInterceptor`](#httprequestinterceptor). Polling transports (HTTP/XHR long-polling) surface as regular HTTP requests, not as WebSocket connections.

```js
import { WebSocketInterceptor } from '@mswjs/interceptors/WebSocket'

const interceptor = new WebSocketInterceptor()
interceptor.apply()
```

Unlike the HTTP-based interceptors that share the same `request`/`response` events, the WebSocket interceptor only emits the `connection` event and lets you handle the incoming/outgoing events in its listener.

#### Important defaults

1. Intercepted WebSocket connections are _not opened_. To open the actual WebSocket connection, call [`server.connect()`](#connect) in the interceptor.
1. Once connected to the actual server, the outgoing client events are _forwarded to that server by default_. If you wish to prevent a client message from reaching the server, call `event.preventDefault()` for that client message event.
1. Once connected to the actual server, the incoming server events are _forwarded to the client by default_. If you wish to prevent a server message from reaching the client, call `event.preventDefault()` for the server message event.
1. Once connected to the actual server, the `close` event received from that server is _forwarded to the client by default_. If you wish to prevent that, call `event.preventDefault()` for that close event of the server.

#### Observing connections

Whenever a WebSocket instance is constructed, the `connection` event is emitted on the WebSocket interceptor.

```js
interceptor.on('connection', ({ client }) => {
  console.log(client.url)
})
```

The `connection` event exposes the following arguments:

| Name     | Type                                                      | Description                                                                         |
| -------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| `client` | [`WebSocketClientConnection`](#websocketclientconnection) | An object representing a connected WebSocket client instance.                       |
| `server` | [`WebSocketServerConnection`](#websocketserverconnection) | An object representing the original WebSocket server connection.                    |
| `info`   | `object`                                                  | Additional WebSocket connection information (like the original client `protocols`). |

#### `WebSocketClientConnection`

##### `.addEventListener(type, listener)`

- `type`, `string`
- `listener`, `EventListener`

Adds an event listener to the given event type of the WebSocket client.

```ts
interface WebSocketServerConnectionEventMap {
  // Dispatched when the WebSocket client sends data.
  message: (this: WebSocket, event: MessageEvent<WebSocketData>) => void

  // Dispatched when the WebSocket client is closed.
  close: (this: WebSocket, event: CloseEvent) => void
}
```

```js
client.addEventListener('message', (event) => {
  console.log('outgoing:', event.data)
})
```

##### `.removeEventListener(type, listener)`

- `type`, `string`
- `listener`, `EventListener`

Removes the listener for the given event type.

##### `.send(data)`

- `data`, `string | Blob | ArrayBuffer`

Sends the data to the intercepted WebSocket client.

```js
client.send('text')
client.send(new Blob(['blob']))
client.send(new TextEncoder().encode('array buffer'))
```

##### `.close(code, reason)`

- `code`, close [status code](https://www.rfc-editor.org/rfc/rfc6455#section-7.4.1).
- `reason`, [close reason](https://www.rfc-editor.org/rfc/rfc6455#section-7.1.6).

Closes the client connection. Unlike the regular `WebSocket.prototype.close()`, the `client.close()` method can accept a non-configurable status codes, such as 1001, 1003, etc.

```js
// Gracefully close the connection with the
// intercepted WebSocket client.
client.close()
```

```js
// Terminate the connection by emulating
// the server unable to process the received data.
client.close(1003)
```

#### `WebSocketServerConnection`

##### `.connect()`

Establishes the connection to the original WebSocket server. Connection cannot be awaited. Any data sent via `server.send()` while connecting is buffered and flushed once the connection is open.

##### `.addEventListener(type, listener)`

- `type`, `string`
- `listener`, `EventListener`

Adds an event listener to the given event type of the WebSocket server.

```ts
interface WebSocketServerConnectionEventMap {
  // Dispatched when the server connection is open.
  open: (this: WebSocket, event: Event) => void

  // Dispatched when the server sends data to the client.
  message: (this: WebSocket, event: MessageEvent<WebSocketData>) => void

  // Dispatched when the server connection closes.
  close: (this: WebSocket, event: CloseEvent) => void
}
```

```js
server.addEventListener('message', (event) => {
  console.log('incoming:', event.data)
})
```

##### `.removeEventListener(type, listener)`

- `type`, `string`
- `listener`, `EventListener`

Removes the listener for the given event type.

##### `.send(data)`

- `data`, `string | Blob | ArrayBuffer`

Sends the data to the original WebSocket server. Useful in a combination with the client-sent events forwarding:

```js
client.addEventListener('message', (event) => {
  server.send(event.data)
})
```

##### `.close()`

Closes the connection with the original WebSocket server. Unlike `client.close()`, closing the server connection does not accept any arguments and always assumes a graceful closure. Sending data via `server.send()` after the connection has been closed will have no effect.

## API

### `Interceptor`

A generic class implemented by all interceptors. You do not interact with this class directly.

```ts
class Interceptor {
  // Applies the interceptor, enabling the interception of requests
  // in the current process.
  apply(): void

  // Listens to the public interceptor events.
  // For HTTP requests, these are "request' and "response" events.
  on(event, listener): void

  // Cleans up any side-effects introduced by the interceptor
  // and disables the interception of requests.
  dispose(): void
}
```

**For public consumption, use [interceptors](#interceptors) instead**.

### `BatchInterceptor`

Applies multiple request interceptors at the same time. Use it to combine interceptors to capture requests from different request-issuing modules at once.

```js
import { BatchInterceptor } from '@mswjs/interceptors'
import { XMLHttpRequestInterceptor } from '@mswjs/interceptors/XMLHttpRequest'
import { FetchInterceptor } from '@mswjs/interceptors/fetch'

const interceptor = new BatchInterceptor({
  name: 'my-interceptor',
  interceptors: [
    new XMLHttpRequestInterceptor(),
    new FetchInterceptor(),
  ],
})

interceptor.apply()

// Spy on both XMLHttpRequest and fetch requests in this process.
interceptor.on('request', listener)
```

Instead of listing the interceptors manually, you can provide one of the pre-defined presets to the `interceptors` option to capture all requests for that environment:

#### Node.js preset

This preset combines the following interceptors:

- `ClientRequestInterceptor`
- `XMLHttpRequestInterceptor`
- `FetchInterceptor`

```js
import { BatchInterceptor } from '@mswjs/interceptors'
import nodeInterceptors from '@mswjs/interceptors/presets/node'

const interceptor = new BatchInterceptor({
  name: 'my-interceptor',
  interceptors: nodeInterceptors,
})

interceptor.on('request', listener)

interceptor.apply()
```

#### Browser preset

This preset combines the following interceptors:

- `XMLHttpRequestInterceptor`
- `FetchInterceptor`

```js
import { BatchInterceptor } from '@mswjs/interceptors'
import browserInterceptors from '@mswjs/interceptors/presets/browser'

const interceptor = new BatchInterceptor({
  name: 'my-interceptor',
  interceptors: browserInterceptors,
})

interceptor.on('request', listener)

interceptor.apply()
```

### `RemoteHttpInterceptor`

Enables request interception in the current process while delegating the response resolution logic to the _parent process_. **Requires the current process to be a child process**. Requires the parent process to establish a resolver by calling the `createRemoteResolver` function.

```js
// child.js
import { RemoteHttpInterceptor } from '@mswjs/interceptors/RemoteHttpInterceptor'
import { ClientRequestInterceptor } from '@mswjs/interceptors/ClientRequest'

const interceptor = new RemoteHttpInterceptor({
  interceptors: [new ClientRequestInterceptor()],
})

interceptor.apply()

process.on('disconnect', () => {
  interceptor.dispose()
})
```

You can still listen to and handle any requests in the child process via the `request` event listener. Keep in mind that a single request can only be responded to once.

### `RemoteHttpResolver`

Resolves an intercepted request in the given child `process`. Requires for that child process to enable request interception by calling the `createRemoteInterceptor` function.

```js
// parent.js
import { spawn } from 'child_process'
import { RemoteHttpResolver } from '@mswjs/interceptors/RemoteHttpInterceptor'

const appProcess = spawn('node', ['app.js'], {
  stdio: ['inherit', 'inherit', 'inherit', 'ipc'],
})

const resolver = new RemoteHttpResolver({
  process: appProcess,
})

resolver.on('request', ({ request, requestId }) => {
  // Optionally, return a mocked response
  // for a request that occurred in the "appProcess".
})

resolver.apply()
```

## Special mention

The following libraries were used as an inspiration to write this low-level API:

- [`node`](https://github.com/nodejs/node)
- [`nock`](https://github.com/nock/nock)
- [`mock-xmlhttprequest`](https://github.com/berniegp/mock-xmlhttprequest)


---

## 23. pnpm
- **URL:** https://github.com/devtechedge/pnpm
- **Language:** Rust
- **Topics:** None
- **Description:** Fast, disk space efficient package manager

### README.md

[简体中文](https://pnpm.io/zh/) |
[日本語](https://pnpm.io/ja/) |
[한국어](https://pnpm.io/ko/) |
[Italiano](https://pnpm.io/it/) |
[Português Brasileiro](https://pnpm.io/pt/)

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://i.imgur.com/qlW1eEG.png">
  <source media="(prefers-color-scheme: dark)"  srcset="https://i.imgur.com/qlW1eEG.png">
  <img src="https://i.imgur.com/qlW1eEG.png" alt="pnpm">
</picture>

Fast, disk space efficient package manager:

* **Fast.** Up to 2x faster than the alternatives (see [benchmark](#benchmark)).
* **Efficient.** Files inside `node_modules` are linked from a single content-addressable storage.
* **[Great for monorepos](https://pnpm.io/workspaces).**
* **Strict.** A package can access only dependencies that are specified in its `package.json`.
* **Deterministic.** Has a lockfile called `pnpm-lock.yaml`.
* **Works as a Node.js version manager.** See [pnpm runtime](https://pnpm.io/11.x/cli/runtime).
* **Works everywhere.** Supports Windows, Linux, and macOS.
* **Battle-tested.** Used in production by teams of [all sizes](https://pnpm.io/workspaces#usage-examples) since 2016.
* **Experimental Rust port.** Includes [pacquet](./pnpm), an experimental port of the CLI written in Rust.
* [See the full feature comparison with npm and Yarn](https://pnpm.io/feature-comparison).

To quote the [Rush](https://rushjs.io/) team:

> Microsoft uses pnpm in Rush repos with hundreds of projects and hundreds of PRs per day, and we’ve found it to be very fast and reliable.

[![npm version](https://img.shields.io/npm/v/pnpm.svg?label=latest)](https://github.com/pnpm/pnpm/releases/latest)
[![Ecosystem E2E](https://github.com/pnpm/pnpm/actions/workflows/ecosystem-e2e.yml/badge.svg?branch=main)](https://github.com/pnpm/pnpm/actions/workflows/ecosystem-e2e.yml)
[![OpenCollective](https://opencollective.com/pnpm/backers/badge.svg)](https://opencollective.com/pnpm)
[![OpenCollective](https://opencollective.com/pnpm/sponsors/badge.svg)](https://opencollective.com/pnpm)
[![X Follow](https://img.shields.io/twitter/follow/pnpmjs.svg?style=social&label=Follow)](https://x.com/intent/follow?screen_name=pnpmjs&region=follow_link)
[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://stand-with-ukraine.pp.ua)

<!-- sponsors -->

## Platinum Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://bit.cloud/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/bit.svg" width="80" alt="Bit"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://openai.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/openai_dark.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/openai_light.svg" />
            <img src="https://pnpm.io/img/users/openai_dark.svg" width="160" alt="OpenAI" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://notion.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/notion.svg" width="80" alt="Notion"></a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://coderabbit.ai/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/coderabbit.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/coderabbit_light.svg" />
            <img src="https://pnpm.io/img/users/coderabbit.svg" width="220" alt="CodeRabbit" />
          </picture>
        </a>
      </td>
    </tr>
  </tbody>
</table>

## Gold Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://sanity.io/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/sanity.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/sanity_light.svg" />
            <img src="https://pnpm.io/img/users/sanity.svg" width="120" alt="Sanity" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://discord.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/discord.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/discord_light.svg" />
            <img src="https://pnpm.io/img/users/discord.svg" width="220" alt="Discord" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://vite.dev/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/vitejs.svg" width="42" alt="Vite"></a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://serpapi.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/serpapi_dark.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/serpapi_light.svg" />
            <img src="https://pnpm.io/img/users/serpapi_dark.svg" width="160" alt="SerpApi" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://stackblitz.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/stackblitz.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/stackblitz_light.svg" />
            <img src="https://pnpm.io/img/users/stackblitz.svg" width="190" alt="Stackblitz" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://workleap.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/workleap.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/workleap_light.svg" />
            <img src="https://pnpm.io/img/users/workleap.svg" width="190" alt="Workleap" />
          </picture>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://nx.dev/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/nx.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/nx_light.svg" />
            <img src="https://pnpm.io/img/users/nx.svg" width="50" alt="Nx" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://latitude.so/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/latitude.svg" width="160" alt="Latitude"></a>
      </td>
    </tr>
  </tbody>
</table>

## Silver Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://replit.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/replit.png" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/replit_light.png" />
            <img src="https://pnpm.io/img/users/replit.png" width="140" alt="Replit" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://cybozu.co.jp/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/cybozu.svg" width="70" alt="Cybozu"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.bairesdev.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/bairesdev.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/bairesdev_light.svg" />
            <img src="https://pnpm.io/img/users/bairesdev.svg" width="160" alt="BairesDev" />
          </picture>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://www.thesys.dev/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/thesys.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/thesys_light.svg" />
            <img src="https://pnpm.io/img/users/thesys.svg" width="120" alt="Thesys" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://devowl.io/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/devowlio.svg" width="100" alt="devowl.io"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://uscreen.de/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/uscreen.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/uscreen_light.svg" />
            <img src="https://pnpm.io/img/users/uscreen.svg" width="180" alt="u|screen" />
          </picture>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://www.leniolabs.com/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer"><img src="https://pnpm.io/img/users/leniolabs.jpg" width="40" alt="Leniolabs_"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://depot.dev/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/depot.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/depot_light.svg" />
            <img src="https://pnpm.io/img/users/depot.svg" width="100" alt="Depot" />
          </picture>
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://cerbos.dev/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://pnpm.io/img/users/cerbos.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://pnpm.io/img/users/cerbos_light.svg" />
            <img src="https://pnpm.io/img/users/cerbos.svg" width="90" alt="Cerbos" />
          </picture>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://time.now/?utm_source=pnpm&utm_medium=readme" target="_blank" rel="noopener noreferrer">⏱️ Time.now</a>
      </td>
    </tr>
  </tbody>
</table>

<!-- sponsors end -->

Support this project by [becoming a sponsor](https://opencollective.com/pnpm#sponsor).

## Background

pnpm uses a content-addressable filesystem to store all files from all module directories on a disk.
When using npm, if you have 100 projects using lodash, you will have 100 copies of lodash on disk.
With pnpm, lodash will be stored in a content-addressable storage, so:

1. If you depend on different versions of lodash, only the files that differ are added to the store.
  If lodash has 100 files, and a new version has a change only in one of those files,
  `pnpm update` will only add 1 new file to the storage.
1. All the files are saved in a single place on the disk. When packages are installed, their files are linked
  from that single place consuming no additional disk space. Linking is performed using either hard-links or reflinks (copy-on-write).

As a result, you save gigabytes of space on your disk and you have a lot faster installations!
If you'd like more details about the unique `node_modules` structure that pnpm creates and
why it works fine with the Node.js ecosystem, read this small article: [Flat node_modules is not the only way](https://pnpm.io/blog/2020/05/27/flat-node-modules-is-not-the-only-way).

💖 Like this project? Let people know with a [tweet](https://r.pnpm.io/tweet)

## Getting Started

- [Installation](https://pnpm.io/installation)
- [Usage](https://pnpm.io/pnpm-cli)
- [Frequently Asked Questions](https://pnpm.io/faq)
- [X](https://x.com/pnpmjs)
- [Bluesky](https://bsky.app/profile/pnpm.io)
- [Discord](https://r.pnpm.io/chat)

## Benchmark

pnpm is up to 2x faster than npm and Yarn classic. See all benchmarks [here](https://r.pnpm.io/benchmarks).

Benchmarks on an app with lots of dependencies:

![](https://pnpm.io/img/benchmarks/alotta-files.svg)

## License

[MIT](https://github.com/pnpm/pnpm/blob/main/LICENSE), except the [`pnpr/`](https://github.com/pnpm/pnpm/tree/main/pnpr) directory, which is source-available under the [PolyForm Shield License 1.0.0](https://github.com/pnpm/pnpm/blob/main/pnpr/LICENSE.md).



---

## 24. krusty-kms
- **URL:** https://github.com/devtechedge/krusty-kms
- **Language:** Rust
- **Topics:** None
- **Description:** No description

### README.md

<p align="center">
  <img src="assets/krusty-crab.png" width="400" alt="Krusty" />
</p>

<h1 align="center">Krusty</h1>

<p align="center">
  Deterministic key management, Starknet account tooling, and protocol cryptography in Rust.
</p>

> **Disclaimer**: This repository is experimental and is provided strictly for testing and experimentation purposes. It should not be used in production environments or relied upon for any security-critical application. There are no guarantees of stability, correctness, or continued maintenance. Use at your own risk.

Krusty provides BIP-39/44 key derivation for Starknet and Nostr domains, deterministic Stark and Nostr signing, OpenZeppelin account descriptor/address calculation, Tongo confidential proof generation, and a focused Starknet client/gateway surface.

## Published Crates

Maintainers should follow the [crates.io release playbook](docs/crates-release.md).

```
krusty-kms-common     Shared value types, errors, and exact serialization helpers
krusty-kms-wallet-api Shared wallet execution contract: transaction tracking, wait options,
                      and the minimal WalletExecutor boundary shared by wallet crates
krusty-kms-domain     Pure typed integration contracts for gateway/client orchestration
krusty-kms-gateway    Long-lived runtime for derive/check/deploy/sign/query flows with
                      explicit secret, cache, and RPC boundaries
krusty-kms-crypto     Cryptographic primitives and zero-knowledge proofs
krusty-kms            Deterministic derivation, account descriptors, and Stark/Nostr signing
krusty-kms-sdk        Tongo protocol operations: fund, transfer, withdraw, rollover,
                      ragequit for confidential balances
krusty-kms-client     Focused Starknet wallet, deployment, Tongo account, and call-builder client
```

## Internal Crates

These remain in the repository for internal, experimental, or integration-specific use:

```
krusty-kms-oracle     Versioned stdio transport on top of the gateway
krusty-kms-wasm       WebAssembly bindings for browser environments
krusty-kms-controller Cartridge Controller integration
krusty-kms-cabi       C ABI shared library (libkms)
mental-poker*         Experimental gaming protocol crates
qb-game               Experimental game crate
```

## Language Bindings

| Package | Language | Method |
|---------|----------|--------|
| `packages/kms-swift` | Swift | SwiftPM via C FFI |
| `packages/kms-jvm` | Java/Kotlin | JNI |
| `packages/kms-dart` | Dart | dart:ffi |
| `packages/kms-c` | C | Header distribution |
| `@starknetfoundation/krusty-kms-wasm` | JavaScript/TypeScript | npm / wasm-pack |

## Quick Start

```bash
bash tools/check.sh quick  # Formatting and fast maintainability checks
bash tools/check.sh rust   # CI-equivalent native Rust lint/examples/tests
bash tools/check.sh wasm   # JS/WASM boundary tests under Node
bash tools/check.sh all    # Standard pre-handoff check
```

Use `bash tools/check.sh help` for granular modes. Native workspace tests exclude
`krusty-kms-wasm`; its boundary is exercised separately through `wasm-pack`.

## Examples

Examples live in:

```text
crates/kms/examples/key_derivation.rs
crates/kms/examples/stark_sign.rs
crates/kms/examples/nostr_sign.rs
crates/kms/examples/oz_address.rs
crates/kms/examples/oz_multisig_address.rs
crates/client/examples/oz_multisig_coordination.rs
crates/sdk/examples/tongo_proof_generation.rs
```

OpenZeppelin multisig wallet integration, devnet tests, and the CLI-style
transaction lifecycle are documented in
[`docs/oz-multisig-wallet-guide.md`](docs/oz-multisig-wallet-guide.md).
Architecture, trust boundaries, upgrade assumptions, and transaction-ordering
limits are documented in
[`docs/architecture-and-trust-boundaries.md`](docs/architecture-and-trust-boundaries.md).

### WASM

```bash
cd crates/wasm && wasm-pack build --target web
```

### JavaScript / TypeScript

Install the published browser-oriented ESM package:

```bash
npm install @starknetfoundation/krusty-kms-wasm
```

Initialize it before calling its exports:

```ts
import init, {
  getVersion,
  poseidonHash,
} from "@starknetfoundation/krusty-kms-wasm";

await init();

console.log(getVersion());
console.log(poseidonHash("0x1", "0x2"));
```

See the [npm package](https://www.npmjs.com/package/@starknetfoundation/krusty-kms-wasm)
for the generated API documentation.

`computeInvokeTransactionHashV3` accepts an optional final `proofFacts`
argument for proof-carrying invoke-v3 transactions:

```ts
const txHash = computeInvokeTransactionHashV3(
  senderAddress,
  compiledCalldata,
  chainId,
  nonce,
  tip,
  resourceBounds,
  paymasterData,
  nonceDataAvailabilityMode,
  feeDataAvailabilityMode,
  accountDeploymentData,
  proofFacts
);
```

Omit `proofFacts` or pass `[]` for the standard invoke-v3 hash.

## License

MIT OR Apache-2.0


---

## 25. sqlmesh
- **URL:** https://github.com/devtechedge/sqlmesh
- **Language:** Python
- **Topics:** None
- **Description:** Scalable and efficient data transformation framework - backwards compatible with dbt.

### README.md

<p align="center">
  <img src="docs/readme/sqlmesh.png" alt="SQLMesh logo" width="50%" height="50%">
</p>
<p align="center">SQLMesh is a project of the <a href="https://www.linuxfoundation.org/">Linux Foundation</a>.</p>

SQLMesh is a next-generation data transformation framework designed to ship data quickly, efficiently, and without error. Data teams can run and deploy data transformations written in SQL or Python with visibility and control at any size.

It is more than just a [dbt alternative](https://tobikodata.com/reduce_costs_with_cron_and_partitions.html).

<p align="center">
  <img src="docs/readme/architecture_diagram.png" alt="Architecture Diagram" width="100%" height="100%">
</p>

## Core Features

<img src="https://github.com/SQLMesh/sqlmesh-public-assets/blob/main/vscode.gif?raw=true" alt="SQLMesh Plan Mode">

> Get instant SQL impact and context of your changes, both in the CLI and in the [SQLMesh VSCode Extension](https://sqlmesh.readthedocs.io/en/latest/guides/vscode/?h=vs+cod)

  <details>
  <summary><b>Virtual Data Environments</b></summary>

  * See a full diagram of how [Virtual Data Environments](https://whimsical.com/virtual-data-environments-MCT8ngSxFHict4wiL48ymz) work
  * [Watch this video to learn more](https://www.youtube.com/watch?v=weJH3eM0rzc)

  </details>

  * Create isolated development environments without data warehouse costs
  * Plan / Apply workflow like [Terraform](https://www.terraform.io/) to understand potential impact of changes
  * Easy to use [CI/CD bot](https://sqlmesh.readthedocs.io/en/stable/integrations/github/) for true blue-green deployments

<details>
<summary><b>Efficiency and Testing</b></summary>

Running this command will generate a unit test file in the `tests/` folder: `test_stg_payments.yaml`

Runs a live query to generate the expected output of the model

```bash
sqlmesh create_test tcloud_demo.stg_payments --query tcloud_demo.seed_raw_payments "select * from tcloud_demo.seed_raw_payments limit 5"

# run the unit test
sqlmesh test
```

```sql
MODEL (
  name tcloud_demo.stg_payments,
  cron '@daily',
  grain payment_id,
  audits (UNIQUE_VALUES(columns = (
      payment_id
  )), NOT_NULL(columns = (
      payment_id
  )))
);

SELECT
    id AS payment_id,
    order_id,
    payment_method,
    amount / 100 AS amount, /* `amount` is currently stored in cents, so we convert it to dollars */
    'new_column' AS new_column, /* non-breaking change example  */
FROM tcloud_demo.seed_raw_payments
```

```yaml
test_stg_payments:
model: tcloud_demo.stg_payments
inputs:
    tcloud_demo.seed_raw_payments:
      - id: 66
        order_id: 58
        payment_method: coupon
        amount: 1800
      - id: 27
        order_id: 24
        payment_method: coupon
        amount: 2600
      - id: 30
        order_id: 25
        payment_method: coupon
        amount: 1600
      - id: 109
        order_id: 95
        payment_method: coupon
        amount: 2400
      - id: 3
        order_id: 3
        payment_method: coupon
        amount: 100
outputs:
    query:
      - payment_id: 66
        order_id: 58
        payment_method: coupon
        amount: 18.0
        new_column: new_column
      - payment_id: 27
        order_id: 24
        payment_method: coupon
        amount: 26.0
        new_column: new_column
      - payment_id: 30
        order_id: 25
        payment_method: coupon
        amount: 16.0
        new_column: new_column
      - payment_id: 109
        order_id: 95
        payment_method: coupon
        amount: 24.0
        new_column: new_column
      - payment_id: 3
        order_id: 3
        payment_method: coupon
        amount: 1.0
        new_column: new_column
```
</details>

* Never build a table [more than once](https://tobikodata.com/simplicity-or-efficiency-how-dbt-makes-you-choose.html)
* Track what data’s been modified and run only the necessary transformations for [incremental models](https://tobikodata.com/correctly-loading-incremental-data-at-scale.html)
* Run [unit tests](https://tobikodata.com/we-need-even-greater-expectations.html) for free and configure automated audits
* Run [table diffs](https://sqlmesh.readthedocs.io/en/stable/examples/sqlmesh_cli_crash_course/?h=crash#run-data-diff-against-prod) between prod and dev based on tables/views impacted by a change

<details>
<summary><b>Level Up Your SQL</b></summary>
Write SQL in any dialect and SQLMesh will transpile it to your target SQL dialect on the fly before sending it to the warehouse.
<img src="https://github.com/SQLMesh/sqlmesh/blob/main/docs/readme/transpile_example.png?raw=true" alt="Transpile Example">
</details>

* Debug transformation errors *before* you run them in your warehouse in [10+ different SQL dialects](https://sqlmesh.readthedocs.io/en/stable/integrations/overview/#execution-engines)
* Definitions using [simply SQL](https://sqlmesh.readthedocs.io/en/stable/concepts/models/sql_models/#sql-based-definition) (no need for redundant and confusing `Jinja` + `YAML`)
* See impact of changes before you run them in your warehouse with column-level lineage

For more information, check out the [documentation](https://sqlmesh.readthedocs.io/en/stable/).

## Getting Started
Install SQLMesh through [pypi](https://pypi.org/project/sqlmesh/) by running:

```bash
mkdir sqlmesh-example
cd sqlmesh-example
python -m venv .venv
source .venv/bin/activate
pip install 'sqlmesh[lsp]' # install the sqlmesh package with extensions to work with VSCode
source .venv/bin/activate # reactivate the venv to ensure you're using the right installation
sqlmesh init # follow the prompts to get started (choose DuckDB)
```

</details>

> Note: You may need to run `python3` or `pip3` instead of `python` or `pip`, depending on your python installation.

<details>
<summary><b>Windows Installation</b></summary>

```bash
mkdir sqlmesh-example
cd sqlmesh-example
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install 'sqlmesh[lsp]' # install the sqlmesh package with extensions to work with VSCode
.\.venv\Scripts\Activate.ps1 # reactivate the venv to ensure you're using the right installation
sqlmesh init # follow the prompts to get started (choose DuckDB)
```
</details>


Follow the [quickstart guide](https://sqlmesh.readthedocs.io/en/stable/quickstart/cli/) to learn how to use SQLMesh. You already have a head start!

Follow the [crash course](https://sqlmesh.readthedocs.io/en/stable/examples/sqlmesh_cli_crash_course/) to learn the core movesets and use the easy to reference cheat sheet.

Follow this [example](https://sqlmesh.readthedocs.io/en/stable/examples/incremental_time_full_walkthrough/) to learn how to use SQLMesh in a full walkthrough.

## Join Our Community
Connect with us in the following ways:

* Join the [Tobiko Slack Community](https://tobikodata.com/slack) to ask questions, or just to say hi!
* File an issue on our [GitHub](https://github.com/SQLMesh/sqlmesh/issues/new)
* Send us an email at [hello@tobikodata.com](mailto:hello@tobikodata.com) with your questions or feedback
* Read our [blog](https://tobikodata.com/blog)

## Contributing
We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute, including our DCO sign-off requirement.

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) and [Governance](GOVERNANCE.md) documents.

[Read more](https://sqlmesh.readthedocs.io/en/stable/development/) on how to set up your development environment.

## License
This project is licensed under the [Apache License 2.0](LICENSE). Documentation is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).


---

## 26. agents
- **URL:** https://github.com/devtechedge/agents
- **Language:** Python
- **Topics:** None
- **Description:** A framework for building realtime voice AI agents ≡ƒñû≡ƒÄÖ∩╕Å≡ƒô╣ 

### README.md

<!--BEGIN_BANNER_IMAGE-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/.github/banner_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="/.github/banner_light.png">
  <img style="width:100%;" alt="The LiveKit icon, the name of the repository and some sample code in the background." src="https://raw.githubusercontent.com/livekit/agents/main/.github/banner_light.png">
</picture>

<!--END_BANNER_IMAGE-->
<br />

![PyPI - Version](https://img.shields.io/pypi/v/livekit-agents)
[![PyPI Downloads](https://static.pepy.tech/badge/livekit-agents/month)](https://pepy.tech/projects/livekit-agents)
[![Slack community](https://img.shields.io/endpoint?url=https%3A%2F%2Flivekit.io%2Fbadges%2Fslack)](https://livekit.io/join-slack)
[![Twitter Follow](https://img.shields.io/twitter/follow/livekit)](https://twitter.com/livekit)
[![Ask DeepWiki for understanding the codebase](https://deepwiki.com/badge.svg)](https://deepwiki.com/livekit/agents)
[![License](https://img.shields.io/github/license/livekit/livekit)](https://github.com/livekit/livekit/blob/master/LICENSE)

<br />

Looking for the JS/TS library? Check out [AgentsJS](https://github.com/livekit/agents-js)

## What is Agents?

<!--BEGIN_DESCRIPTION-->

The Agent Framework is designed for building realtime, programmable participants
that run on servers. Use it to create conversational, multi-modal voice
agents that can see, hear, and understand.

<!--END_DESCRIPTION-->

## Features

- **Flexible integrations**: A comprehensive ecosystem to mix and match the right STT, LLM, TTS, and Realtime API to suit your use case.
- **Integrated job scheduling**: Built-in task scheduling and distribution with [dispatch APIs](https://docs.livekit.io/agents/build/dispatch/) to connect end users to agents.
- **Extensive WebRTC clients**: Build client applications using LiveKit's open-source SDK ecosystem, supporting all major platforms.
- **Telephony integration**: Works seamlessly with LiveKit's [telephony stack](https://docs.livekit.io/sip/), allowing your agent to make calls to or receive calls from phones.
- **Exchange data with clients**: Use [RPCs](https://docs.livekit.io/home/client/data/rpc/) and other [Data APIs](https://docs.livekit.io/home/client/data/) to seamlessly exchange data with clients.
- **Semantic turn detection**: Uses a transformer model to detect when a user is done with their turn, helps to reduce interruptions.
- **MCP support**: Native support for MCP. Integrate tools provided by MCP servers with one line of code.
- **Builtin test framework**: Write tests and use judges to ensure your agent is performing as expected.
- **Open-source**: Fully open-source, allowing you to run the entire stack on your own servers, including [LiveKit server](https://github.com/livekit/livekit), one of the most widely used WebRTC media servers.

## Installation

To install the core Agents library, along with plugins for popular model providers:

```bash
pip install "livekit-agents[openai,deepgram,cartesia]"
```

## Docs and guides

Documentation on the framework and how to use it can be found [here](https://docs.livekit.io/agents/)

### Building with AI coding agents

If you're using an AI coding assistant to build with LiveKit Agents, we recommend the following setup for the best results:

1. **Install the [LiveKit Docs MCP server](https://docs.livekit.io/mcp)** — Gives your coding agent access to up-to-date LiveKit documentation, code search across LiveKit repositories, and working examples.

2. **Install the [LiveKit Agent Skill](https://github.com/livekit/agent-skills)** — Provides your coding agent with architectural guidance and best practices for building voice AI applications, including workflow design, handoffs, tasks, and testing patterns.

   ```shell
   npx skills add livekit/agent-skills --skill livekit-agents
   ```

The Agent Skill works best alongside the MCP server: the skill teaches your agent *how to approach* building with LiveKit, while the MCP server provides the *current API details* to implement it correctly.

## Core concepts

- Agent: An LLM-based application with defined instructions.
- AgentSession: A container for agents that manages interactions with end users.
- entrypoint: The starting point for an interactive session, similar to a request handler in a web server.
- AgentServer: The main process that coordinates job scheduling and launches agents for user sessions.

## Usage

### Simple voice agent

---

```python
from livekit.agents import (
    Agent,
    AgentServer,
    AgentSession,
    JobContext,
    RunContext,
    cli,
    function_tool,
    inference,
)


@function_tool
async def lookup_weather(
    context: RunContext,
    location: str,
):
    """Used to look up weather information."""

    return {"weather": "sunny", "temperature": 70}


server = AgentServer()


@server.rtc_session()
async def entrypoint(ctx: JobContext):
    session = AgentSession(
        vad=inference.VAD(),
        # any combination of STT, LLM, TTS, or realtime API can be used
        # this example shows LiveKit Inference, a unified API to access different models via LiveKit Cloud
        # to use model provider keys directly, replace with the following:
        # from livekit.plugins import deepgram, openai, cartesia
        # stt=deepgram.STT(model="nova-3"),
        # llm=openai.LLM(model="gpt-4.1-mini"),
        # tts=cartesia.TTS(model="sonic-3", voice="9626c31c-bec5-4cca-baa8-f8ba9e84c8bc"),
        stt=inference.STT("deepgram/nova-3", language="multi"),
        llm=inference.LLM("google/gemma-4-31b-it"),  # low-latency gemma, hosted on LiveKit
        tts=inference.TTS("cartesia/sonic-3", voice="9626c31c-bec5-4cca-baa8-f8ba9e84c8bc"),
    )

    agent = Agent(
        instructions="You are a friendly voice assistant built by LiveKit.",
        tools=[lookup_weather],
    )

    await session.start(agent=agent, room=ctx.room)
    await session.generate_reply(instructions="greet the user and ask about their day")


if __name__ == "__main__":
    cli.run_app(server)
```

You'll need the following environment variables for this example:

- LIVEKIT_URL
- LIVEKIT_API_KEY
- LIVEKIT_API_SECRET

### Multi-agent handoff

---

This code snippet is abbreviated. For the full example, see the [LiveKit docs](https://docs.livekit.io/agents/handoffs/)

```python
...
class IntroAgent(Agent):
    def __init__(self) -> None:
        super().__init__(
            instructions=f"You are a story teller. Your goal is to gather a few pieces of information from the user to make the story personalized and engaging."
            "Ask the user for their name and where they are from"
        )

    async def on_enter(self):
        self.session.generate_reply(instructions="greet the user and gather information")

    @function_tool
    async def information_gathered(
        self,
        context: RunContext,
        name: str,
        location: str,
    ):
        """Called when the user has provided the information needed to make the story personalized and engaging.

        Args:
            name: The name of the user
            location: The location of the user
        """

        context.userdata.name = name
        context.userdata.location = location

        story_agent = StoryAgent(name, location)
        return story_agent, "Let's start the story!"


class StoryAgent(Agent):
    def __init__(self, name: str, location: str) -> None:
        super().__init__(
            instructions=f"You are a storyteller. Use the user's information in order to make the story personalized."
            f"The user's name is {name}, from {location}",
            # override the default model, switching to Realtime API from standard LLMs
            llm=openai.realtime.RealtimeModel(voice="echo"),
            chat_ctx=chat_ctx,
        )

    async def on_enter(self):
        self.session.generate_reply()


@server.rtc_session()
async def entrypoint(ctx: JobContext):
    userdata = StoryData()
    session = AgentSession[StoryData](
        vad=inference.VAD(),
        stt="deepgram/nova-3",
        llm="google/gemma-4-31b-it",  # low-latency gemma, hosted on LiveKit
        tts="cartesia/sonic-3:9626c31c-bec5-4cca-baa8-f8ba9e84c8bc",
        userdata=userdata,
    )

    await session.start(
        agent=IntroAgent(),
        room=ctx.room,
    )
...
```

### Testing

Automated tests are essential for building reliable agents, especially with the non-deterministic behavior of LLMs. LiveKit Agents include native test integration to help you create dependable agents.

```python
@pytest.mark.asyncio
async def test_no_availability() -> None:
    llm = google.LLM()
    async with AgentSession(llm=llm) as sess:
        await sess.start(MyAgent())
        result = await sess.run(
            user_input="Hello, I need to place an order."
        )
        result.expect.skip_next_event_if(type="message", role="assistant")
        result.expect.next_event().is_function_call(name="start_order")
        result.expect.next_event().is_function_call_output()
        await (
            result.expect.next_event()
            .is_message(role="assistant")
            .judge(llm, intent="assistant should be asking the user what they would like")
        )

```

## Examples

For more examples and detailed setup instructions, see the [examples directory](examples/). For even more examples, see the [python-agents-examples](https://github.com/livekit-examples/python-agents-examples) repository.

<table>
<tr>
<td width="50%">
<h3>🎙️ Starter Agent</h3>
<p>A starter agent optimized for voice conversations.</p>
<p>
<a href="examples/voice_agents/basic_agent.py">Code</a>
</p>
</td>
<td width="50%">
<h3>☎️ Outbound caller</h3>
<p>Agent that makes outbound phone calls</p>
<p>
<a href="https://github.com/livekit-examples/outbound-caller-python">Code</a>
</p>
</td>
</tr>

<tr>
<td width="50%">
<h3>🔌 MCP support</h3>
<p>Use tools from MCP servers</p>
<p>
<a href="examples/voice_agents/mcp">Code</a>
</p>
</td>
<td width="50%">
<h3>📝 Multi-user transcriber</h3>
<p>Produce transcriptions from all users in the room</p>
<p>
<a href="examples/other/transcription/multi-user-transcriber.py">Code</a>
</p>
</td>
</tr>

<tr>
<td width="50%">
<h3>🎥 Video avatars</h3>
<p>Add an AI avatar with Tavus, Bithuman, LemonSlice, and more</p>
<p>
<a href="examples/avatar/">Code</a>
</p>
</td>
<td width="50%">
<h3>👁️ Gemini Live vision</h3>
<p>Full example (including iOS app) of Gemini Live agent that can see.</p>
<p>
<a href="https://github.com/livekit-examples/vision-demo">Code</a>
</p>
</td>
</tr>

</table>

## Running your agent

### Testing in terminal

```shell
python myagent.py console
```

Runs your agent in terminal mode, enabling local audio input and output for testing.
This mode doesn't require external servers or dependencies and is useful for quickly validating behavior.

### Developing with LiveKit clients

```shell
python myagent.py dev
```

Starts the agent server and enables hot reloading when files change. This mode allows each process to host multiple concurrent agents efficiently.

The agent connects to LiveKit Cloud or your self-hosted server. Set the following environment variables:
- LIVEKIT_URL
- LIVEKIT_API_KEY
- LIVEKIT_API_SECRET

You can connect using any LiveKit client SDK or telephony integration.
To get started quickly, try the [Agents Playground](https://agents-playground.livekit.io/).

### Running for production

```shell
python myagent.py start
```

Runs the agent with production-ready optimizations.

## License

The Agents framework is licensed under [Apache-2.0](LICENSE). The LiveKit turn detection models are licensed under the [LiveKit Model License](MODEL_LICENSE).

## Contributing

The Agents framework is under active development in a rapidly evolving field. We welcome and appreciate contributions of any kind, be it feedback, bugfixes, features, new plugins and tools, or better documentation. You can file issues under this repo, open a PR, or chat with us in the [LiveKit community](https://docs.livekit.io/intro/community/).

### Development setup

This project uses [uv](https://docs.astral.sh/uv/) for package management. To install dependencies for development:

```shell
uv sync --all-extras --dev
```

### Examples

This project includes many examples in the [`examples`](examples/) directory. To run them, create the file `examples/.env` with credentials for LiveKit Server and any necessary model providers (see `examples/.env.example`), then run:

```shell
uv run examples/voice_agents/basic_agent.py dev
```

For more information, see the [examples README](examples/README.md).

### Tests

Unit tests are in the `tests` directory and can be run with:

```shell
uv run pytest --unit
```

Integration tests for each plugin require various API credentials and run automatically in GitHub CI for PRs submitted by project maintainers. See the [tests workflow](.github/workflows/tests.yml) for details.

### Formatting

This project uses [ruff](https://github.com/astral-sh/ruff) for formatting and linting:

```shell
uv run ruff format
uv run ruff check --fix
```

### Documentation

To generate docs locally with [pdoc](https://github.com/pdoc3/pdoc):

```shell
uv sync --all-extras --group docs
uv run --active pdoc --skip-errors --html --output-dir=docs livekit
```

<!--BEGIN_REPO_NAV-->
<br/><table>
<thead><tr><th colspan="2">LiveKit Ecosystem</th></tr></thead>
<tbody>
<tr><td>Agents SDKs</td><td><b>Python</b> · <a href="https://github.com/livekit/agents-js">Node.js</a></td></tr><tr></tr>
<tr><td>LiveKit SDKs</td><td><a href="https://github.com/livekit/client-sdk-js">Browser</a> · <a href="https://github.com/livekit/client-sdk-swift">Swift</a> · <a href="https://github.com/livekit/client-sdk-android">Android</a> · <a href="https://github.com/livekit/client-sdk-flutter">Flutter</a> · <a href="https://github.com/livekit/client-sdk-react-native">React Native</a> · <a href="https://github.com/livekit/rust-sdks">Rust</a> · <a href="https://github.com/livekit/node-sdks">Node.js</a> · <a href="https://github.com/livekit/python-sdks">Python</a> · <a href="https://github.com/livekit/client-sdk-unity">Unity</a> · <a href="https://github.com/livekit/client-sdk-unity-web">Unity (WebGL)</a> · <a href="https://github.com/livekit/client-sdk-esp32">ESP32</a> · <a href="https://github.com/livekit/client-sdk-cpp">C++</a></td></tr><tr></tr>
<tr><td>Starter Apps</td><td><a href="https://github.com/livekit-examples/agent-starter-python">Python Agent</a> · <a href="https://github.com/livekit-examples/agent-starter-node">TypeScript Agent</a> · <a href="https://github.com/livekit-examples/agent-starter-react">React App</a> · <a href="https://github.com/livekit-examples/agent-starter-swift">SwiftUI App</a> · <a href="https://github.com/livekit-examples/agent-starter-android">Android App</a> · <a href="https://github.com/livekit-examples/agent-starter-flutter">Flutter App</a> · <a href="https://github.com/livekit-examples/agent-starter-react-native">React Native App</a> · <a href="https://github.com/livekit-examples/agent-starter-embed">Web Embed</a></td></tr><tr></tr>
<tr><td>UI Components</td><td><a href="https://github.com/livekit/components-js">React</a> · <a href="https://github.com/livekit/components-android">Android Compose</a> · <a href="https://github.com/livekit/components-swift">SwiftUI</a> · <a href="https://github.com/livekit/components-flutter">Flutter</a></td></tr><tr></tr>
<tr><td>Server APIs</td><td><a href="https://github.com/livekit/node-sdks">Node.js</a> · <a href="https://github.com/livekit/server-sdk-go">Golang</a> · <a href="https://github.com/livekit/server-sdk-ruby">Ruby</a> · <a href="https://github.com/livekit/server-sdk-kotlin">Java/Kotlin</a> · <a href="https://github.com/livekit/python-sdks">Python</a> · <a href="https://github.com/livekit/rust-sdks">Rust</a> · <a href="https://github.com/agence104/livekit-server-sdk-php">PHP (community)</a> · <a href="https://github.com/pabloFuente/livekit-server-sdk-dotnet">.NET (community)</a></td></tr><tr></tr>
<tr><td>Resources</td><td><a href="https://docs.livekit.io">Docs</a> · <a href="https://docs.livekit.io/mcp">Docs MCP Server</a> · <a href="https://github.com/livekit/livekit-cli">CLI</a> · <a href="https://cloud.livekit.io">LiveKit Cloud</a></td></tr><tr></tr>
<tr><td>LiveKit Server OSS</td><td><a href="https://github.com/livekit/livekit">LiveKit server</a> · <a href="https://github.com/livekit/egress">Egress</a> · <a href="https://github.com/livekit/ingress">Ingress</a> · <a href="https://github.com/livekit/sip">SIP</a></td></tr><tr></tr>
<tr><td>Community</td><td><a href="https://community.livekit.io">Developer Community</a> · <a href="https://livekit.io/join-slack">Slack</a> · <a href="https://x.com/livekit">X</a> · <a href="https://www.youtube.com/@livekit_io">YouTube</a></td></tr>
</tbody>
</table>
<!--END_REPO_NAV-->


---

## 27. jinja
- **URL:** https://github.com/devtechedge/jinja
- **Language:** Python
- **Topics:** None
- **Description:** A very fast and expressive template engine.

### README.md

<div align="center"><img src="https://raw.githubusercontent.com/pallets/jinja/refs/heads/stable/docs/_static/jinja-name.svg" alt="" height="150"></div>

# Jinja

Jinja is a fast, expressive, extensible templating engine. Special
placeholders in the template allow writing code similar to Python
syntax. Then the template is passed data to render the final document.

It includes:

-   Template inheritance and inclusion.
-   Define and import macros within templates.
-   HTML templates can use autoescaping to prevent XSS from untrusted
    user input.
-   A sandboxed environment can safely render untrusted templates.
-   AsyncIO support for generating templates and calling async
    functions.
-   I18N support with Babel.
-   Templates are compiled to optimized Python code just-in-time and
    cached, or can be compiled ahead-of-time.
-   Exceptions point to the correct line in templates to make debugging
    easier.
-   Extensible filters, tests, functions, and even syntax.

Jinja's philosophy is that while application logic belongs in Python if
possible, it shouldn't make the template designer's job difficult by
restricting functionality too much.


## In A Nutshell

```jinja
{% extends "base.html" %}
{% block title %}Members{% endblock %}
{% block content %}
  <ul>
  {% for user in users %}
    <li><a href="{{ user.url }}">{{ user.username }}</a></li>
  {% endfor %}
  </ul>
{% endblock %}
```

## Donate

The Pallets organization develops and supports Jinja and other popular
packages. In order to grow the community of contributors and users, and
allow the maintainers to devote more time to the projects, [please
donate today][].

[please donate today]: https://palletsprojects.com/donate

## Contributing

See our [detailed contributing documentation][contrib] for many ways to
contribute, including reporting issues, requesting features, asking or answering
questions, and making PRs.

[contrib]: https://palletsprojects.com/contributing/


---

## 28. undici
- **URL:** https://github.com/devtechedge/undici
- **Language:** JavaScript
- **Topics:** None
- **Description:** An HTTP/1.1 client, written from scratch for Node.js

### README.md

# undici

[![Node CI](https://github.com/nodejs/undici/actions/workflows/ci.yml/badge.svg)](https://github.com/nodejs/undici/actions/workflows/nodejs.yml) [![neostandard javascript style](https://img.shields.io/badge/neo-standard-7fffff?style=flat\&labelColor=ff80ff)](https://github.com/neostandard/neostandard) [![npm version](https://badge.fury.io/js/undici.svg)](https://badge.fury.io/js/undici) [![codecov](https://codecov.io/gh/nodejs/undici/branch/main/graph/badge.svg?token=yZL6LtXkOA)](https://codecov.io/gh/nodejs/undici)

An HTTP/1.1 client, written from scratch for Node.js.

> Undici means eleven in Italian. 1.1 -> 11 -> Eleven -> Undici.
It is also a Stranger Things reference.

## How to get involved

Have a question about using Undici? Open a [Q&A Discussion](https://github.com/nodejs/undici/discussions/new) or join our official OpenJS [Slack](https://openjs-foundation.slack.com/archives/C01QF9Q31QD) channel.

Looking to contribute? Start by reading the [contributing guide](./CONTRIBUTING.md)

## Install

```
npm i undici
```

## Benchmarks

The benchmark is a simple getting data [example](https://github.com/nodejs/undici/blob/main/benchmarks/benchmark.js) using
50 TCP connections with a pipelining depth of 10 running on Node 24.14.1.

### HTTP/1.1

```
┌────────────────────────┬─────────┬────────────────────┬────────────┬─────────────────────────┐
│  Tests                 │ Samples │ Result             │ Tolerance  │ Difference with slowest │
├────────────────────────┼─────────┼────────────────────┼────────────┼─────────────────────────┤
│  'node-fetch'          │ 50      │ '4711.86 req/sec'  │ '± 2.92 %' │ '-'                     │
│  'undici - fetch'      │ 75      │ '5438.50 req/sec'  │ '± 2.97 %' │ '+ 15.42 %'             │
│  'axios'               │ 45      │ '5448.08 req/sec'  │ '± 2.98 %' │ '+ 15.62 %'             │
│  'request'             │ 65      │ '5809.63 req/sec'  │ '± 2.90 %' │ '+ 23.30 %'             │
│  'http - no keepalive' │ 35      │ '5910.77 req/sec'  │ '± 2.87 %' │ '+ 25.44 %'             │
│  'got'                 │ 50      │ '6047.80 req/sec'  │ '± 2.91 %' │ '+ 28.35 %'             │
│  'superagent'          │ 60      │ '7534.53 req/sec'  │ '± 2.97 %' │ '+ 59.91 %'             │
│  'http - keepalive'    │ 75      │ '9343.41 req/sec'  │ '± 2.90 %' │ '+ 98.30 %'             │
│  'undici - pipeline'   │ 65      │ '13470.70 req/sec' │ '± 2.93 %' │ '+ 185.89 %'            │
│  'undici - request'    │ 80      │ '16850.87 req/sec' │ '± 2.93 %' │ '+ 257.63 %'            │
│  'undici - stream'     │ 101     │ '18488.56 req/sec' │ '± 3.81 %' │ '+ 292.38 %'            │
│  'undici - dispatch'   │ 101     │ '20786.44 req/sec' │ '± 3.08 %' │ '+ 341.15 %'            │
└────────────────────────┴─────────┴────────────────────┴────────────┴─────────────────────────┘
```

### HTTP/1.1 over HTTPS

Using [benchmark-https.js](https://github.com/nodejs/undici/blob/main/benchmarks/benchmark-https.js) against an h1-over-TLS server (50 connections, pipelining depth 10, Node 24.14.1).

```
┌────────────────────────┬─────────┬───────────────────┬────────────┬─────────────────────────┐
│  Tests                 │ Samples │ Result            │ Tolerance  │ Difference with slowest │
├────────────────────────┼─────────┼───────────────────┼────────────┼─────────────────────────┤
│  'https - no keepalive'│ 10      │ '1358.40 req/sec' │ '± 1.99 %' │ '-'                     │
│  'undici - fetch'      │ 30      │ '3721.76 req/sec' │ '± 2.97 %' │ '+ 173.98 %'            │
│  'https - keepalive'   │ 35      │ '5633.91 req/sec' │ '± 2.84 %' │ '+ 314.75 %'            │
│  'undici - pipeline'   │ 15      │ '6254.05 req/sec' │ '± 2.80 %' │ '+ 360.40 %'            │
│  'undici - request'    │ 25      │ '6669.80 req/sec' │ '± 2.73 %' │ '+ 391.01 %'            │
│  'undici - stream'     │ 25      │ '7019.04 req/sec' │ '± 2.77 %' │ '+ 416.71 %'            │
│  'undici - dispatch'   │ 20      │ '7361.85 req/sec' │ '± 2.90 %' │ '+ 441.95 %'            │
└────────────────────────┴─────────┴───────────────────┴────────────┴─────────────────────────┘
```

### HTTP/2

Using [benchmark-http2.js](https://github.com/nodejs/undici/blob/main/benchmarks/benchmark-http2.js) against an h2 server (50 connections, pipelining depth 10, Node 24.14.1).

```
┌────────────────────────┬─────────┬───────────────────┬────────────┬─────────────────────────┐
│  Tests                 │ Samples │ Result            │ Tolerance  │ Difference with slowest │
├────────────────────────┼─────────┼───────────────────┼────────────┼─────────────────────────┤
│  'undici - fetch'      │ 45      │ '3499.03 req/sec' │ '± 2.93 %' │ '-'                     │
│  'native - http2'      │ 25      │ '4904.58 req/sec' │ '± 2.81 %' │ '+ 40.17 %'             │
│  'undici - pipeline'   │ 60      │ '5836.82 req/sec' │ '± 2.99 %' │ '+ 66.81 %'             │
│  'undici - request'    │ 65      │ '6831.25 req/sec' │ '± 2.83 %' │ '+ 95.23 %'             │
│  'undici - stream'     │ 55      │ '6874.30 req/sec' │ '± 2.91 %' │ '+ 96.46 %'             │
│  'undici - dispatch'   │ 55      │ '7791.23 req/sec' │ '± 2.96 %' │ '+ 122.67 %'            │
└────────────────────────┴─────────┴───────────────────┴────────────┴─────────────────────────┘
```

## Undici vs. Fetch

### Overview

Node.js includes a built-in `fetch()` implementation powered by undici starting from Node.js v18. However, there are important differences between using the built-in fetch and installing undici as a separate module.

### Built-in Fetch (Node.js v18+)

Node.js's built-in fetch is powered by a bundled version of undici:

```js
// Available globally in Node.js v18+
const response = await fetch('https://api.example.com/data');
const data = await response.json();

// Check the bundled undici version
console.log(process.versions.undici); // e.g., "5.28.4"
```

**Pros:**
- No additional dependencies required
- Works across different JavaScript runtimes
- Automatic compression handling (gzip, deflate, br)
- Built-in caching support (in development)

**Cons:**
- Limited to the undici version bundled with your Node.js version
- Less control over connection pooling and advanced features
- Error handling follows Web API standards (errors wrapped in `TypeError`)
- Performance overhead due to Web Streams implementation

### Undici Module

Installing undici as a separate module gives you access to the latest features and APIs:

```bash
npm install undici
```

```js
import { request, fetch, Agent, setGlobalDispatcher } from 'undici';

// Use undici.request for maximum performance
const { statusCode, headers, body } = await request('https://api.example.com/data');
const data = await body.json();

// Or use undici.fetch with custom configuration
const agent = new Agent({ keepAliveTimeout: 10000 });
setGlobalDispatcher(agent);
const response = await fetch('https://api.example.com/data');
```

**Pros:**
- Latest undici features and bug fixes
- Access to advanced APIs (`request`, `stream`, `pipeline`)
- Fine-grained control over connection pooling
- Better error handling with clearer error messages
- Superior performance, especially with `undici.request`
- HTTP/1.1 pipelining support
- Custom interceptors and middleware
- Advanced features like `ProxyAgent`, `Socks5Agent`, `MockAgent`

**Cons:**
- Additional dependency to manage
- Larger bundle size

### When to Use Each

#### Use Built-in Fetch When:
- You want zero dependencies
- Building isomorphic code that runs in browsers and Node.js
- Publishing to npm and want to maximize compatibility with JS runtimes
- Simple HTTP requests without advanced configuration
- You're publishing to npm and you want to maximize compatiblity
- You don't depend on features from a specific version of undici

#### Use Undici Module When:
- You need the latest undici features and performance improvements
- You require advanced connection pooling configuration
- You need APIs not available in the built-in fetch (`ProxyAgent`, `Socks5Agent`, `MockAgent`, etc.)
- Performance is critical (use `undici.request` for maximum speed)
- You want better error handling and debugging capabilities
- You need HTTP/1.1 pipelining or advanced interceptors
- You prefer decoupled protocol and API interfaces

### Performance Comparison

Based on benchmarks, here's the typical performance hierarchy:

1. **`undici.request()`** - Fastest, most efficient
2. **`undici.fetch()`** - Good performance, standard compliance
3. **Node.js `http`/`https`** - Baseline performance

### Migration Guide

If you're currently using built-in fetch and want to migrate to undici:

```js
// Before: Built-in fetch
const response = await fetch('https://api.example.com/data');

// After: Undici fetch (drop-in replacement)
import { fetch } from 'undici';
const response = await fetch('https://api.example.com/data');

// Or: Undici request (better performance)
import { request } from 'undici';
const { statusCode, body } = await request('https://api.example.com/data');
const data = await body.json();
```

### Keep `fetch` and `FormData` together

When you send a `FormData` body, keep `fetch` and `FormData` from the same
implementation.

Use one of these patterns:

```js
// Built-in globals
const body = new FormData()
body.set('name', 'some')
await fetch('https://example.com', {
  method: 'POST',
  body
})
```

```js
// undici module imports
import { fetch, FormData } from 'undici'

const body = new FormData()
body.set('name', 'some')
await fetch('https://example.com', {
  method: 'POST',
  body
})
```

If you want the installed `undici` package to provide the globals, call
`install()` first:

```js
import { install } from 'undici'

install()

const body = new FormData()
body.set('name', 'some')
await fetch('https://example.com', {
  method: 'POST',
  body
})
```

`install()` replaces the global `fetch`, `Headers`, `Response`, `Request`, and
`FormData` implementations with undici's versions, so they all match. It also
installs undici's `WebSocket`, `CloseEvent`, `ErrorEvent`, `MessageEvent`, and
`EventSource` globals.

Avoid mixing a global `FormData` with `undici.fetch()`, or `undici.FormData`
with the built-in global `fetch()`.

### Version Compatibility

You can check which version of undici is bundled with your Node.js version:

```js
console.log(process.versions.undici);
```

Installing undici as a module allows you to use a newer version than what's bundled with Node.js, giving you access to the latest features and performance improvements.

## Quick Start

### Basic Request

```js
import { request } from 'undici'

const {
  statusCode,
  headers,
  trailers,
  body
} = await request('http://localhost:3000/foo')

console.log('response received', statusCode)
console.log('headers', headers)

for await (const data of body) { console.log('data', data) }

console.log('trailers', trailers)
```

### Using Cache Interceptor

Undici provides a powerful HTTP caching interceptor that follows HTTP caching best practices. Here's how to use it:

```js
import { fetch, Agent, interceptors, cacheStores } from 'undici';

// Create a client with cache interceptor
const client = new Agent().compose(interceptors.cache({
  // Optional: Configure cache store (defaults to MemoryCacheStore)
  store: new cacheStores.MemoryCacheStore({
    maxSize: 100 * 1024 * 1024, // 100MB
    maxCount: 1000,
    maxEntrySize: 5 * 1024 * 1024 // 5MB
  }),
  
  // Optional: Specify which HTTP methods to cache (default: ['GET', 'HEAD'])
  methods: ['GET', 'HEAD']
}));

// Set the global dispatcher to use our caching client
setGlobalDispatcher(client);

// Now all fetch requests will use the cache
async function getData() {
  const response = await fetch('https://api.example.com/data');
  // The server should set appropriate Cache-Control headers in the response
  // which the cache will respect based on the cache policy
  return response.json();
}

// First request - fetches from origin
const data1 = await getData();

// Second request - served from cache if within max-age
const data2 = await getData();
```

#### Key Features:
- **Automatic Caching**: Respects `Cache-Control` and `Expires` headers
- **Validation**: Supports `ETag` and `Last-Modified` validation
- **Storage Options**: In-memory or persistent SQLite storage
- **Flexible**: Configure cache size, TTL, and more

## Global Installation

Undici provides an `install()` function to add fetch-related and other web API classes to `globalThis`, making them available globally:

```js
import { install } from 'undici'

// Install undici's global web APIs
install()

// Now you can use fetch classes globally without importing
const response = await fetch('https://api.example.com/data')
const data = await response.json()

// All classes are available globally:
const headers = new Headers([['content-type', 'application/json']])
const request = new Request('https://example.com')
const formData = new FormData()
const ws = new WebSocket('wss://example.com')
const eventSource = new EventSource('https://example.com/events')
```

The `install()` function adds the following classes to `globalThis`:

- `fetch` - The fetch function
- `Headers` - HTTP headers management
- `Response` - HTTP response representation
- `Request` - HTTP request representation
- `FormData` - Form data handling
- `WebSocket` - WebSocket client
- `CloseEvent`, `ErrorEvent`, `MessageEvent` - WebSocket events
- `EventSource` - Server-sent events client

When you call `install()`, these globals come from the same undici
implementation. For example, global `fetch` and global `FormData` will both be
undici's versions, and `WebSocket` and `EventSource` will also come from
undici, which is the recommended setup if you want to use undici through
globals.

This is useful for:
- Polyfilling environments that don't have fetch
- Ensuring consistent fetch behavior across different Node.js versions
- Making undici's implementations available globally for libraries that expect them

## Body Mixins

The `body` mixins are the most common way to format the request/response body. Mixins include:

- [`.arrayBuffer()`](https://fetch.spec.whatwg.org/#dom-body-arraybuffer)
- [`.blob()`](https://fetch.spec.whatwg.org/#dom-body-blob)
- [`.bytes()`](https://fetch.spec.whatwg.org/#dom-body-bytes)
- [`.json()`](https://fetch.spec.whatwg.org/#dom-body-json)
- [`.text()`](https://fetch.spec.whatwg.org/#dom-body-text)

> [!NOTE]
> The body returned from `undici.request` does not implement `.formData()`.

> [!WARNING]
> Calling `body.formData()` on a fetch response causes undici to buffer and parse the entire body. Since this is dictated by the spec, `body.formData()` must only be called on responses from trusted servers.

Example usage:

```js
import { request } from 'undici'

const {
  statusCode,
  headers,
  trailers,
  body
} = await request('http://localhost:3000/foo')

console.log('response received', statusCode)
console.log('headers', headers)
console.log('data', await body.json())
console.log('trailers', trailers)
```

_Note: Once a mixin has been called then the body cannot be reused, thus calling additional mixins on `.body`, e.g. `.body.json(); .body.text()` will result in an error `TypeError: unusable` being thrown and returned through the `Promise` rejection._

Should you need to access the `body` in plain-text after using a mixin, the best practice is to use the `.text()` mixin first and then manually parse the text to the desired format.

For more information about their behavior, please reference the body mixin from the [Fetch Standard](https://fetch.spec.whatwg.org/#body-mixin).

## Common API Methods

This section documents our most commonly used API methods. Additional APIs are documented in their own files within the [docs](./docs/) folder and are accessible via the navigation list on the left side of the docs site.

For the top-level APIs below, the `url` argument supplies the request origin and
path. Do not pass `origin` or `path` in the second `options` argument. The linked
`Dispatcher` option types include those fields because dispatcher methods are
lower-level APIs that do not receive a separate `url` argument.

### `undici.request([url, options]): Promise`

Arguments:

* **url** `string | URL | UrlObject`
* **options** [`RequestOptions`](./docs/docs/api/Dispatcher.md#parameter-requestoptions)
  * **dispatcher** `Dispatcher` - Default: [getGlobalDispatcher](#undicigetglobaldispatcher)
  * **method** `String` - Default: `PUT` if `options.body`, otherwise `GET`

Returns a promise with the result of the `Dispatcher.request` method.

Calls `options.dispatcher.request(options)`.

See [Dispatcher.request](./docs/docs/api/Dispatcher.md#dispatcherrequestoptions-callback) for more details, and [request examples](./docs/examples/README.md) for examples.

### `undici.stream([url, options, ]factory): Promise`

Arguments:

* **url** `string | URL | UrlObject`
* **options** [`StreamOptions`](./docs/docs/api/Dispatcher.md#parameter-streamoptions)
  * **dispatcher** `Dispatcher` - Default: [getGlobalDispatcher](#undicigetglobaldispatcher)
  * **method** `String` - Default: `PUT` if `options.body`, otherwise `GET`
* **factory** `Dispatcher.stream.factory`

Returns a promise with the result of the `Dispatcher.stream` method.

Calls `options.dispatcher.stream(options, factory)`.

See [Dispatcher.stream](./docs/docs/api/Dispatcher.md#dispatcherstreamoptions-factory-callback) for more details.

### `undici.pipeline([url, options, ]handler): Duplex`

Arguments:

* **url** `string | URL | UrlObject`
* **options** [`PipelineOptions`](./docs/docs/api/Dispatcher.md#parameter-pipelineoptions)
  * **dispatcher** `Dispatcher` - Default: [getGlobalDispatcher](#undicigetglobaldispatcher)
  * **method** `String` - Default: `PUT` if `options.body`, otherwise `GET`
* **handler** `Dispatcher.pipeline.handler`

Returns: `stream.Duplex`

Calls `options.dispatch.pipeline(options, handler)`.

See [Dispatcher.pipeline](./docs/docs/api/Dispatcher.md#dispatcherpipelineoptions-handler) for more details.

### `undici.connect([url, options]): Promise`

Starts two-way communications with the requested resource using [HTTP CONNECT](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/CONNECT).

Arguments:

* **url** `string | URL | UrlObject`
* **options** [`ConnectOptions`](./docs/docs/api/Dispatcher.md#parameter-connectoptions)
  * **dispatcher** `Dispatcher` - Default: [getGlobalDispatcher](#undicigetglobaldispatcher)
* **callback** `(err: Error | null, data: ConnectData | null) => void` (optional)

Returns a promise with the result of the `Dispatcher.connect` method.

Calls `options.dispatch.connect(options)`.

See [Dispatcher.connect](./docs/docs/api/Dispatcher.md#dispatcherconnectoptions-callback) for more details.

### `undici.fetch(input[, init]): Promise`

Implements [fetch](https://fetch.spec.whatwg.org/#fetch-method).

* https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch
* https://fetch.spec.whatwg.org/#fetch-method

Basic usage example:

```js
import { fetch } from 'undici'


const res = await fetch('https://example.com')
const json = await res.json()
console.log(json)
```

You can pass an optional dispatcher to `fetch` as:

```js
import { fetch, Agent } from 'undici'

const res = await fetch('https://example.com', {
  // Mocks are also supported
  dispatcher: new Agent({
    keepAliveTimeout: 10,
    keepAliveMaxTimeout: 10
  })
})
const json = await res.json()
console.log(json)
```

#### `request.body`

A body can be of the following types:

- ArrayBuffer
- ArrayBufferView
- AsyncIterables
- Blob
- Iterables
- String
- URLSearchParams
- FormData

In this implementation of fetch, ```request.body``` now accepts ```Async Iterables```. It is not present in the [Fetch Standard](https://fetch.spec.whatwg.org).

```js
import { fetch } from 'undici'

const data = {
  async *[Symbol.asyncIterator]() {
    yield 'hello'
    yield 'world'
  },
}

await fetch('https://example.com', { body: data, method: 'POST', duplex: 'half' })
```

[FormData](https://developer.mozilla.org/en-US/docs/Web/API/FormData) besides text data and buffers can also utilize streams via [Blob](https://developer.mozilla.org/en-US/docs/Web/API/Blob) objects:

```js
import { openAsBlob } from 'node:fs'

const file = await openAsBlob('./big.csv')
const body = new FormData()
body.set('file', file, 'big.csv')

await fetch('http://example.com', { method: 'POST', body })
```

#### `request.duplex`

- `'half'`

In this implementation of fetch, `request.duplex` must be set if `request.body` is `ReadableStream` or `Async Iterables`, however, even though the value must be set to `'half'`, it is actually a _full_ duplex. For more detail refer to the [Fetch Standard](https://fetch.spec.whatwg.org/#dom-requestinit-duplex).

#### `response.body`

Nodejs has two kinds of streams: [web streams](https://nodejs.org/api/webstreams.html), which follow the API of the WHATWG web standard found in browsers, and an older Node-specific [streams API](https://nodejs.org/api/stream.html). `response.body` returns a readable web stream. If you would prefer to work with a Node stream you can convert a web stream using `.fromWeb()`.

```js
import { fetch } from 'undici'
import { Readable } from 'node:stream'

const response = await fetch('https://example.com')
const readableWebStream = response.body
const readableNodeStream = Readable.fromWeb(readableWebStream)
```

## Specification Compliance

This section documents parts of the [HTTP/1.1](https://www.rfc-editor.org/rfc/rfc9110.html) and [Fetch Standard](https://fetch.spec.whatwg.org) that Undici does
not support or does not fully implement.

#### CORS

Unlike browsers, Undici does not implement CORS (Cross-Origin Resource Sharing) checks by default. This means:

- No preflight requests are automatically sent for cross-origin requests
- No validation of `Access-Control-Allow-Origin` headers is performed
- Requests to any origin are allowed regardless of the source

This behavior is intentional for server-side environments where CORS restrictions are typically unnecessary. If your application requires CORS-like protections, you will need to implement these checks manually.

#### Garbage Collection

* https://fetch.spec.whatwg.org/#garbage-collection

The [Fetch Standard](https://fetch.spec.whatwg.org) allows users to skip consuming the response body by relying on
[garbage collection](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management#garbage_collection) to release connection resources.

Garbage collection in Node is less aggressive and deterministic
(due to the lack of clear idle periods that browsers have through the rendering refresh rate)
which means that leaving the release of connection resources to the garbage collector can lead
to excessive connection usage, reduced performance (due to less connection re-use), and even
stalls or deadlocks when running out of connections.
Therefore, __it is important to always either consume or cancel the response body anyway__.

```js
// Do
const { body, headers } = await fetch(url);
for await (const chunk of body) {
  // force consumption of body
}

// Do not
const { headers } = await fetch(url);
```

However, if you want to get only headers, it might be better to use `HEAD` request method. Usage of this method will obviate the need for consumption or cancelling of the response body. See [MDN - HTTP - HTTP request methods - HEAD](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/HEAD) for more details.

```js
const headers = await fetch(url, { method: 'HEAD' })
  .then(res => res.headers)
```

Note that consuming the response body is _mandatory_ for `request`:

```js
// Do
const { body, headers } = await request(url);
await body.dump(); // force consumption of body

// Do not
const { headers } = await request(url);
```

#### Forbidden and Safelisted Header Names

* https://fetch.spec.whatwg.org/#cors-safelisted-response-header-name
* https://fetch.spec.whatwg.org/#forbidden-header-name
* https://fetch.spec.whatwg.org/#forbidden-response-header-name
* https://github.com/wintercg/fetch/issues/6

The [Fetch Standard](https://fetch.spec.whatwg.org) requires implementations to exclude certain headers from requests and responses. In browser environments, some headers are forbidden so the user agent remains in full control over them. In Undici, these constraints are removed to give more control to the user.

#### Content-Encoding

* https://www.rfc-editor.org/rfc/rfc9110#field.content-encoding

Undici limits the number of `Content-Encoding` layers in a response to **5** to prevent resource exhaustion attacks. If a server responds with more than 5 content-encodings (e.g., `Content-Encoding: gzip, gzip, gzip, gzip, gzip, gzip`), the fetch will be rejected with an error. This limit matches the approach taken by [curl](https://curl.se/docs/CVE-2022-32206.html) and [urllib3](https://github.com/advisories/GHSA-gm62-xv2j-4rw9).

#### `undici.upgrade([url, options]): Promise`

Upgrade to a different protocol. See [MDN - HTTP - Protocol upgrade mechanism](https://developer.mozilla.org/en-US/docs/Web/HTTP/Protocol_upgrade_mechanism) for more details.

Arguments:

* **url** `string | URL | UrlObject`
* **options** [`UpgradeOptions`](./docs/docs/api/Dispatcher.md#parameter-upgradeoptions)
  * **dispatcher** `Dispatcher` - Default: [getGlobalDispatcher](#undicigetglobaldispatcher)
* **callback** `(error: Error | null, data: UpgradeData) => void` (optional)

Returns a promise with the result of the `Dispatcher.upgrade` method.

Calls `options.dispatcher.upgrade(options)`.

See [Dispatcher.upgrade](./docs/docs/api/Dispatcher.md#dispatcherupgradeoptions-callback) for more details.

### `undici.setGlobalDispatcher(dispatcher)`

* dispatcher `Dispatcher`

Sets the global dispatcher used by Common API Methods. Global dispatcher is shared among compatible undici modules,
including undici that is bundled internally with node.js.

Undici stores this dispatcher under `Symbol.for('undici.globalDispatcher.2')`.

`setGlobalDispatcher()` also mirrors the configured dispatcher to
`Symbol.for('undici.globalDispatcher.1')` using `Dispatcher1Wrapper`, so Node.js built-in `fetch`
can keep using the legacy handler contract while Undici uses the new handler API.

### `undici.getGlobalDispatcher()`

Gets the global dispatcher used by Common API Methods.

Returns: `Dispatcher`

### `undici.setGlobalOrigin(origin)`

* origin `string | URL | undefined`

Sets the global origin used in `fetch`.

If `undefined` is passed, the global origin will be reset. This will cause `Response.redirect`, `new Request()`, and `fetch` to throw an error when a relative path is passed.

```js
setGlobalOrigin('http://localhost:3000')

const response = await fetch('/api/ping')

console.log(response.url) // http://localhost:3000/api/ping
```

### `undici.getGlobalOrigin()`

Gets the global origin used in `fetch`.

Returns: `URL`

### `UrlObject`

* **port** `string | number` (optional)
* **path** `string` (optional)
* **pathname** `string` (optional)
* **hostname** `string` (optional)
* **origin** `string` (optional)
* **protocol** `string` (optional)
* **search** `string` (optional)

#### Expect

Undici does not support the `Expect` request header field. The request
body is  always immediately sent and the `100 Continue` response will be
ignored.

Refs: https://tools.ietf.org/html/rfc7231#section-5.1.1

#### Pipelining

Undici will only use pipelining if configured with a `pipelining` factor
greater than `1`. Only enable pipelining when the remote server is trusted.
Also it is important to pass `blocking: false` to the request options to
properly pipeline requests.

Undici always assumes that connections are persistent and will immediately
pipeline requests, without checking whether the connection is persistent.
Hence, automatic fallback to HTTP/1.0 or HTTP/1.1 without pipelining is
not supported.

Undici will immediately pipeline when retrying requests after a failed
connection. However, Undici will not retry the first remaining requests in
the prior pipeline and instead error the corresponding callback/promise/stream.

Undici will abort all running requests in the pipeline when any of them are
aborted.

* Refs: https://tools.ietf.org/html/rfc2616#section-8.1.2.2
* Refs: https://tools.ietf.org/html/rfc7230#section-6.3.2

#### Manual Redirect

Since it is not possible to manually follow an HTTP redirect on the server-side,
Undici returns the actual response instead of an `opaqueredirect` filtered one
when invoked with a `manual` redirect. This aligns `fetch()` with the other
implementations in Deno and Cloudflare Workers.

Refs: https://fetch.spec.whatwg.org/#atomic-http-redirect-handling

### Workarounds

#### Network address family autoselection.

If you experience problem when connecting to a remote server that is resolved by your DNS servers to a IPv6 (AAAA record)
first, there are chances that your local router or ISP might have problem connecting to IPv6 networks. In that case
undici will throw an error with code `UND_ERR_CONNECT_TIMEOUT`.

If the target server resolves to both a IPv6 and IPv4 (A records) address and you are using a compatible Node version
(18.3.0 and above), you can fix the problem by providing the `autoSelectFamily` option (support by both `undici.request`
and `undici.Agent`) which will enable the family autoselection algorithm when establishing the connection.

## Collaborators

* [__Daniele Belardi__](https://github.com/dnlup), <https://www.npmjs.com/~dnlup>
* [__Ethan Arrowood__](https://github.com/ethan-arrowood), <https://www.npmjs.com/~ethan_arrowood>
* [__Matteo Collina__](https://github.com/mcollina), <https://www.npmjs.com/~matteo.collina>
* [__Matthew Aitken__](https://github.com/KhafraDev), <https://www.npmjs.com/~khaf>
* [__Robert Nagy__](https://github.com/ronag), <https://www.npmjs.com/~ronag>
* [__Szymon Marczak__](https://github.com/szmarczak), <https://www.npmjs.com/~szmarczak>

## Past Collaborators
* [__Tomas Della Vedova__](https://github.com/delvedor), <https://www.npmjs.com/~delvedor>

### Releasers

* [__Ethan Arrowood__](https://github.com/ethan-arrowood), <https://www.npmjs.com/~ethan_arrowood>
* [__Matteo Collina__](https://github.com/mcollina), <https://www.npmjs.com/~matteo.collina>
* [__Robert Nagy__](https://github.com/ronag), <https://www.npmjs.com/~ronag>
* [__Matthew Aitken__](https://github.com/KhafraDev), <https://www.npmjs.com/~khaf>

## Long Term Support

Undici aligns with the Node.js LTS schedule. The following table shows the supported versions:

| Undici Version | Bundled in Node.js | Node.js Versions Supported | End of Life |
|----------------|--------------------|----------------------------|-------------|
| 5.x            | 18.x               | ≥14.0 (tested: 14, 16, 18) | 2024-04-30  |
| 6.x            | 20.x, 22.x         | ≥18.17 (tested: 18, 20, 21, 22) | 2027-04-30  |
| 7.x            | 24.x               | ≥20.18.1 (tested: 20, 22, 24) | 2028-04-30  |
| 8.x            | 26.x               | ≥22.19.0 (tested: 22, 24, 26) | 2029-04-30  |

## License

MIT


---

## 29. typescript-eslint
- **URL:** https://github.com/devtechedge/typescript-eslint
- **Language:** TypeScript
- **Topics:** None
- **Description:** :sparkles: Monorepo for all the tooling which enables ESLint to support TypeScript

### README.md

<h1 align="center">typescript-eslint</h1>

<p align="center">Monorepo for typescript-eslint: powerful static analysis for JavaScript and TypeScript</p>

<p align="center">
    <img src="https://github.com/typescript-eslint/typescript-eslint/workflows/CI/badge.svg" alt="CI" />
    <a href="https://opencollective.com/typescript-eslint"><img src="https://opencollective.com/typescript-eslint/all/badge.svg?label=financial+contributors&style=flat-square" alt="Financial Contributors on Open Collective" /></a>
    <a href="https://www.npmjs.com/package/@typescript-eslint/typescript-estree"><img src="https://img.shields.io/npm/dm/@typescript-eslint/typescript-estree.svg?style=flat-square" alt="NPM Downloads" /></a>
    <a href="https://codecov.io/gh/typescript-eslint/typescript-eslint"><img alt="Codecov" src="https://img.shields.io/codecov/c/github/typescript-eslint/typescript-eslint.svg?style=flat-square"></a>
</p>

<!-- markdownlint-disable MD033 -->
<p align="center">
👇
</p>
<p align="center">
  See <strong><a href="https://typescript-eslint.io">typescript-eslint.io</a></strong> for documentation on the latest released version.
</p>
<p align="center">
<small>
  See <strong><a href="https://main--typescript-eslint.netlify.app">main--typescript-eslint.netlify.app</a></strong> for documentation on the latest <a href="https://main--typescript-eslint.netlify.app/users/versioning">canary release</a>.
</small>
</p>
<p align="center">
👆
</p>
<!-- markdownlint-enable MD033 -->

## Code Contributors

This project exists thanks to the awesome people who contribute code and documentation:

<a href="https://github.com/typescript-eslint/typescript-eslint/graphs/contributors"><img alt="Gallery of all contributors' profile photos" src="https://opencollective.com/typescript-eslint/contributors.svg?width=890&button=false" /></a>

🙏 An extra special thanks goes out to the wonderful people listed in <https://github.com/typescript-eslint/typescript-eslint/graphs/contributors>.

## Financial Contributors

In addition to submitting code and documentation updates, you can help us sustain our community by becoming a financial contributor [[Click here to contribute - every little bit helps!](https://opencollective.com/typescript-eslint/contribute)]

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-light.svg" alt="Deploys by Netlify" />
</a>

## License

typescript-eslint inherits is licensed under a permissive MIT license.


---

## 30. starlette
- **URL:** https://github.com/devtechedge/starlette
- **Language:** Python
- **Topics:** None
- **Description:** The little ASGI framework that shines. ≡ƒîƒ

### README.md

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kludex/starlette/main/docs/img/starlette_dark.svg" width="420px">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kludex/starlette/main/docs/img/starlette.svg" width="420px">
    <img alt="starlette-logo" src="https://raw.githubusercontent.com/Kludex/starlette/main/docs/img/starlette.svg">
  </picture>
</p>

<p align="center">
    <em>✨ The little ASGI framework that shines. ✨</em>
</p>

---

[![Build Status](https://github.com/Kludex/starlette/workflows/Test%20Suite/badge.svg)](https://github.com/Kludex/starlette/actions)
[![Package version](https://badge.fury.io/py/starlette.svg)](https://pypi.python.org/pypi/starlette)
[![Supported Python Version](https://img.shields.io/pypi/pyversions/starlette.svg?color=%2334D058)](https://pypi.org/project/starlette)
[![Discord](https://img.shields.io/discord/1051468649518616576?logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/RxKUF5JuHs)

---

**Documentation**: <a href="https://starlette.dev/" target="_blank">https://starlette.dev</a>

**Source Code**: <a href="https://github.com/Kludex/starlette" target="_blank">https://github.com/Kludex/starlette</a>

---

# Starlette

Starlette is a lightweight [ASGI][asgi] framework/toolkit,
which is ideal for building async web services in Python.

It is production-ready, and gives you the following:

* A lightweight, low-complexity HTTP web framework.
* WebSocket support.
* In-process background tasks.
* Startup and shutdown events.
* Test client built on `httpx2`.
* CORS, GZip, Static Files, Streaming responses.
* Session and Cookie support.
* 100% test coverage.
* 100% type annotated codebase.
* Few hard dependencies.
* Compatible with `asyncio` and `trio` backends.
* Great overall performance [against independent benchmarks][techempower].

## Installation

```shell
$ pip install starlette
```

You'll also want to install an ASGI server, such as [uvicorn](https://uvicorn.dev) or any of the [other ASGI server implementations](https://asgi.readthedocs.io/en/latest/implementations.html#servers).

```shell
$ pip install uvicorn
```

## Example

```python title="main.py"
from starlette.applications import Starlette
from starlette.responses import JSONResponse
from starlette.routing import Route


async def homepage(request):
    return JSONResponse({'hello': 'world'})

routes = [
    Route("/", endpoint=homepage)
]

app = Starlette(debug=True, routes=routes)
```

Then run the application using Uvicorn:

```shell
$ uvicorn main:app
```

## Dependencies

Starlette only requires `anyio`, and the following are optional:

* [`httpx2`][httpx2] - Required if you want to use the `TestClient`.
* [`jinja2`][jinja2] - Required if you want to use `Jinja2Templates`.
* [`opentelemetry-api`][opentelemetry-api] - Required for `OpenTelemetryMiddleware`.
* [`python-multipart`][python-multipart] - Required if you want to support form parsing, with `request.form()`.
* [`itsdangerous`][itsdangerous] - Required for `SessionMiddleware` support.
* [`pyyaml`][pyyaml] - Required for `SchemaGenerator` support.

You can install all of these with `pip install starlette[full]`.

## Framework or Toolkit

Starlette is designed to be used either as a complete framework, or as
an ASGI toolkit. You can use any of its components independently.

```python
from starlette.responses import PlainTextResponse


async def app(scope, receive, send):
    assert scope['type'] == 'http'
    response = PlainTextResponse('Hello, world!')
    await response(scope, receive, send)
```

Run the `app` application in `example.py`:

```shell
$ uvicorn example:app
INFO: Started server process [11509]
INFO: Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
```

Run uvicorn with `--reload` to enable auto-reloading on code changes.

## Modularity

The modularity that Starlette is designed on promotes building reusable
components that can be shared between any ASGI framework. This should enable
an ecosystem of shared middleware and mountable applications.

The clean API separation also means it's easier to understand each component
in isolation.

---

<p align="center"><i>Starlette is <a href="https://github.com/Kludex/starlette/blob/main/LICENSE.md">BSD licensed</a> code.<br/>Designed & crafted with care.</i></br>&mdash; ⭐️ &mdash;</p>

[asgi]: https://asgi.readthedocs.io/en/latest/
[httpx2]: https://pypi.org/project/httpx2/
[jinja2]: https://jinja.palletsprojects.com/
[opentelemetry-api]: https://opentelemetry.io/docs/languages/python/api/
[python-multipart]: https://multipart.fastapiexpert.com/
[itsdangerous]: https://itsdangerous.palletsprojects.com/
[sqlalchemy]: https://www.sqlalchemy.org
[pyyaml]: https://pyyaml.org/wiki/PyYAMLDocumentation
[techempower]: https://github.com/TechEmpower/FrameworkBenchmarks


---

## 31. js-stellar-sdk
- **URL:** https://github.com/devtechedge/js-stellar-sdk
- **Language:** TypeScript
- **Topics:** None
- **Description:** Main Stellar client library for the JavaScript language.

### README.md

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


---

## 32. safe-core-sdk
- **URL:** https://github.com/devtechedge/safe-core-sdk
- **Language:** TypeScript
- **Topics:** None
- **Description:** The Safe{Core} SDK allows builders to add account abstraction functionality into their apps.

### README.md

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


---

## 33. coinbase-wallet-sdk
- **URL:** https://github.com/devtechedge/coinbase-wallet-sdk
- **Language:** TypeScript
- **Topics:** None
- **Description:** An open protocol that lets users connect their mobile wallets to your DApp

### README.md

# Coinbase Wallet SDK

[![npm](https://img.shields.io/npm/v/@coinbase/wallet-sdk.svg)](https://www.npmjs.com/package/@coinbase/wallet-sdk)

## Coinbase Wallet SDK allows dapps to connect to Coinbase Wallet

1. [Coinbase Smart Wallet](https://keys.coinbase.com/onboarding)
   - [Docs](https://www.smartwallet.dev/)
1. Coinbase Wallet mobile for [Android](https://play.google.com/store/apps/details?id=org.toshi&referrer=utm_source%3DWallet_LP) and [iOS](https://apps.apple.com/app/apple-store/id1278383455?pt=118788940&ct=Wallet_LP&mt=8)
   - Desktop: Users can connect to your dapp by scanning a QR code
   - Mobile: Users can connect to your mobile dapp through a deeplink to the dapp browser
1. Coinbase Wallet extension for [Chrome](https://chrome.google.com/webstore/detail/coinbase-wallet-extension/hnfanknocfeofbddgcijnmhnfnkdnaad?hl=en) and [Brave](https://chromewebstore.google.com/detail/coinbase-wallet-extension/hnfanknocfeofbddgcijnmhnfnkdnaad?hl=en)
   - Desktop: Users can connect by clicking the connect with an extension option.

### Installing Wallet SDK

1. Check available versions:

   ```shell
     # yarn
     yarn info @coinbase/wallet-sdk versions

     # npm
     npm view @coinbase/wallet-sdk versions
   ```

2. Install latest version:

   ```shell
   # yarn
   yarn add @coinbase/wallet-sdk

   # npm
   npm install @coinbase/wallet-sdk
   ```

3. Check installed version:

   ```shell
   # yarn
   yarn list @coinbase/wallet-sdk

   # npm
   npm list @coinbase/wallet-sdk
   ```

### Upgrading Wallet SDK

> Migrating from v3 to v4? Please see our [v4 migration guide](https://www.smartwallet.dev/sdk/v3-to-v4-changes) for a full list of breaking changes.

1. Compare the installed version with the latest:

   ```shell
   # yarn
   yarn outdated @coinbase/wallet-sdk

   # npm
   npm outdated @coinbase/wallet-sdk
   ```

2. Update to latest:

   ```shell
   # yarn
   yarn upgrade @coinbase/wallet-sdk --latest

   # npm
   npm update @coinbase/wallet-sdk
   ```

### Basic Usage

1. Initialize SDK

   ```js
   const sdk = new CoinbaseWalletSDK({
     appName: 'SDK Playground',
   });
   ```

2. Make web3 Provider

   ```js
   const provider = sdk.makeWeb3Provider();
   ```

3. Request accounts to initialize a connection to wallet

   ```js
   const addresses = provider.request({
     method: 'eth_requestAccounts',
   });
   ```

4. Make more requests

   ```js
   provider.request('personal_sign', [
     `0x${Buffer.from('test message', 'utf8').toString('hex')}`,
     addresses[0],
   ]);
   ```

5. Handle provider events

   ```js
   provider.on('connect', (info) => {
     setConnect(info);
   });

   provider.on('disconnect', (error) => {
     setDisconnect({ code: error.code, message: error.message });
   });

   provider.on('accountsChanged', (accounts) => {
     setAccountsChanged(accounts);
   });

   provider.on('chainChanged', (chainId) => {
     setChainChanged(chainId);
   });

   provider.on('message', (message) => {
     setMessage(message);
   });
   ```

### Developing locally and running the test dapp

- The Coinbase Wallet SDK test dapp can be viewed here https://coinbase.github.io/coinbase-wallet-sdk/.
- To run it locally follow these steps:

  1. Fork this repo and clone it
  1. From the root dir run `yarn install`
  1. From the root dir run `yarn dev`


---

## 34. router
- **URL:** https://github.com/devtechedge/router
- **Language:** TypeScript
- **Topics:** None
- **Description:** ≡ƒñû A client-first, server-capable, fully type-safe router and full-stack framework for the web (React and more).

### README.md

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


---

## 35. miniapps
- **URL:** https://github.com/devtechedge/miniapps
- **Language:** TypeScript
- **Topics:** None
- **Description:** No description

### README.md

<br />

<p align="center">
  <a href="https://miniapps.farcaster.xyz">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/farcasterxyz/miniapps/main/.github/gh-logo-dark.svg">
        <img alt="farcaster mini apps logo" src="https://raw.githubusercontent.com/farcasterxyz/miniapps/main/.github/gh-logo-light.svg" width="auto" height="30">
      </picture>
  </a>
</p>

<p align="center">
  Build onchain social apps
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@farcaster/frame-sdk">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/v/@farcaster/frame-sdk?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/v/@farcaster/frame-sdk?colorA=f6f8fa&colorB=f6f8fa" alt="Version">
    </picture>
  </a>
  <a href="https://github.com/farcasterxyz/miniapps/blob/main/LICENSE">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/l/@farcaster/frame-sdk?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/l/@farcaster/frame-sdk?colorA=f6f8fa&colorB=f6f8fa" alt="MIT License">
    </picture>
  </a>
  <a href="https://www.npmjs.com/package/@farcaster/frame-sdk">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/dm/@farcaster/frame-sdk?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/dm/@farcaster/frame-sdk?colorA=f6f8fa&colorB=f6f8fa" alt="Downloads per month">
    </picture>
  </a>
</p>

---

## Documentation

For documentation and guides, visit [miniapps.farcaster.xyz](https://miniapps.farcaster.xyz).

## Community

For fast, casual conversations:

[Join the Mini Apps Developer Chat on Warpcast](https://farcaster.xyz/~/group/X2P7HNc4PHTriCssYHNcmQ)

For slow, formal conversations that would benefit from being searchable:

[Discuss Mini Apps on GitHub](https://github.com/farcasterxyz/miniapps/discussions)

## Contributing

Contributions are greatly appreciated! If you're interested in contributing to the Mini Apps monorepo, please read the [Contributing Guide](https://github.com/farcasterxyz/miniapps/blob/main/.github/CONTRIBUTING.md) **before submitting a pull request**.



---

## 36. alchemy-sdk-js
- **URL:** https://github.com/devtechedge/alchemy-sdk-js
- **Language:** TypeScript
- **Topics:** None
- **Description:** The easiest way to connect your dApp to the blockchain.

### README.md

> [!WARNING]
> The Alchemy SDK JS has been deprecated and will be archived **January 2026**. The software will only receive minimal support until then. New and existing users are encourage to use the following tools instead:
> - [Alchemy Smart Wallets SDK](https://github.com/alchemyplatform/aa-sdk) for transacting applications (includes support for the [Portfolio Data APIs](https://www.alchemy.com/docs/reference/portfolio-apis)).
> - [Viem](https://github.com/wevm/viem/) for JS based Ethereum development.
> - [Solana Web3JS](https://www.npmjs.com/package/@solana/web3.js) for JS based Solana development.

# Alchemy SDK for Javascript

The Alchemy SDK is the most comprehensive, stable, and powerful Javascript SDK available today to interact with the blockchain.

It supports the exact same syntax and functionality of the Ethers.js `AlchemyProvider` and `WebSocketProvider`, making it a 1:1 mapping for anyone using the Ethers.js `Provider`. However, it adds a significant amount of improved functionality on top of Ethers, such as easy access to Alchemy’s Enhanced and NFT APIs, robust WebSockets, and quality-of-life improvements such as automated retries.

The SDK currently supports the following chains (chains with '(d)' after are deprecated):

- **Ethereum**: Mainnet, Goerli (d), Sepolia, Holesky, Hoodi
- **Polygon**: Mainnet, Mumbai (d), Amoy
- **Optimism**: Mainnet, Goerli (d), Sepolia
- **Arbitrum**: Mainnet, Goerli (d), Sepolia
- **Astar**: Mainnet
- **PolygonZKEVM**: Mainnet, Testnet(d), Cardona
- **Base**: Mainnet, Goerli (d), Sepolia
- **Zksync**: Mainnet, Sepolia
- **Shape**: Mainnet, Sepolia
- **Linea**: Mainnet, Sepolia
- **Fantom**: Mainnet, Testnet
- **Zetachain**: Mainnet, Testnet
- **Arbnova**: Mainnet
- **Blast**: Mainnet, Sepolia
- **Mantle**: Mainnet, Sepolia
- **Scroll**: Mainnet, Sepolia
- **Gnosis**: Mainnet, Chiado
- **BNB**: Mainnet, Testnet
- **Avalanche**: Mainnet, Fuji
- **Celo**: Mainnet, Alfajores, Baklava
- **Metis**: Mainnet
- **OpBNB**: Mainnet, Testnet
- **Berachain**: Mainnet, Bartio, Bepolia
- **Soneium**: Mainnet, Minato
- **Worldchain**: Mainnet, Sepolia
- **Rootstock**: Mainnet, Testnet
- **Flow**: Mainnet, Testnet
- **Zora**: Mainnet, Sepolia
- **Frax**: Mainnet, Sepolia
- **Polynomial**: Mainnet, Sepolia
- **Crossfi**: Mainnet, Testnet
- **Apechain**: Mainnet, Curtis
- **Lens**: Mainnet, Sepolia
- **Geist**: Mainnet, Polter
- **Lumia**: Prism, Testnet
- **Unichain**: Mainnet, Sepolia
- **Sonic**: Mainnet, Blaze
- **XMTP**: Testnet
- **Abstract**: Mainnet, Testnet
- **Degen**: Mainnet
- **Ink**: Mainnet, Sepolia
- **Sei**: Mainnet, Testnet
- **Ronin**: Mainnet, Saigon
- **Monad**: Testnet
- **Settlus**: Mainnet, Testnet (Sepolia)
- **Gensyn**: Testnet
- **Superseed**: Mainnet, Sepolia
- **Tea**: Sepolia
- **Anime**: Mainnet, Sepolia
- **Story**: Mainnet, Aeneid
- **Megaeth**: Testnet
- **Botanix**: Mainnet, Testnet
- **Humanity**: Mainnet
- **Rise**: Testnet
- **Hyperliquid**: Mainnet, Testnet
- **Plasma**: Mainnet, Testnet

You can find per-method documentation of the Alchemy SDK endpoints at the [Alchemy Docs linked in the sidebar](https://docs.alchemy.com/reference/alchemy-sdk-quickstart).

## Getting started

```
npm install alchemy-sdk
```

After installing the app, you can then import and use the SDK:

```ts
import { Alchemy, Network } from 'alchemy-sdk';

// Optional config object, but defaults to the API key 'demo' and Network 'eth-mainnet'.
const settings = {
  apiKey: 'demo', // Replace with your Alchemy API key.
  network: Network.ETH_MAINNET // Replace with your network.
};

const alchemy = new Alchemy(settings);
```

> **ℹ️ Creating a unique Alchemy API Key**
>
> The public "demo" API key may be rate limited based on traffic. To create your own API key, **[sign up for an Alchemy account here](https://alchemy.com/?a=SDKquickstart)** and use the key created on your dashboard for the first app.

The `Alchemy` object returned by `new Alchemy()` provides access to the Alchemy API. An optional config object can be passed in when initializing to set your API key, change the network, or specify the max number of retries.

## Using the Alchemy SDK

The Alchemy SDK currently supports the following namespaces:

- `core`: All commonly-used Ethers.js Provider methods and Alchemy Enhanced API methods
- `nft`: All Alchemy NFT API methods
- `ws`: All WebSockets methods
- `transact`: All Alchemy Transaction API methods
- `notify`: CRUD endpoints for modifying Alchemy Notify Webhooks
- `debug`: Methods to inspect and replay transactions and blocks

If you are already using Ethers.js, you should be simply able to replace the Ethers.js Provider object with `alchemy.core` and it should work properly.

> **ℹ️ ENS Name Resolution**
>
> The Alchemy SDK now supports ENS names (e.g. `vitalik.eth`) for every parameter where you can pass in a Externally Owned Address, or user address (e.g. `0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045`).

```ts
import { Alchemy, AlchemySubscription } from 'alchemy-sdk';

// Using default settings - pass in a settings object to specify your API key and network
const alchemy = new Alchemy();

// Access standard Ethers.js JSON-RPC node request
alchemy.core.getBlockNumber().then(console.log);

// Access Alchemy Enhanced API requests
alchemy.core
  .getTokenBalances('0x3f5CE5FBFe3E9af3971dD833D26bA9b5C936f0bE')
  .then(console.log);

// Access the Alchemy NFT API
alchemy.nft.getNftsForOwner('vitalik.eth').then(console.log);

// Access WebSockets and Alchemy-specific WS methods
alchemy.ws.on(
  {
    method: AlchemySubscription.PENDING_TRANSACTIONS
  },
  res => console.log(res)
);
```

The Alchemy SDK also supports a number of Ethers.js objects that streamline the development process:

- [`Utils`](https://docs.ethers.io/v5/api/utils/): Equivalent to `ethers.utils`, this provides a number of common Ethers.js utility methods for developers.
  - [`Interface`](https://docs.ethers.io/v5/api/utils/abi/interface/): Found in `Utils.Interface`, this class abstracts the encoding and decoding required to interact with contracts on the Ethereum network.
- [`Contract`](https://docs.ethers.io/v5/api/contract/contract/): An abstraction for smart contract code deployed to the blockchain.
- [`ContractFactory`](https://docs.ethers.io/v5/api/contract/contract-factory/): Allows developers to build a `Contract` object.
- [`Wallet`](https://docs.ethers.io/v5/api/signer/#Wallet): An implementation of `Signer` that can sign transactions and messages using a private key as a standard Externally Owned Account.

## Alchemy Settings

An `AlchemySettings` object can be passed on instantiation to the Alchemy object, with the following optional parameters:

- `apiKey`: API key that can be found in the Alchemy dashboard. Defaults to `demo`: a rate-limited public key.
- `network`: Name of the network. Defaults to `Network.ETH_MAINNET`
- `maxRetries`: The maximum number of retries to attempt if a request fails. Defaults to 5.
- `url`: Optional URL endpoint to use for all requests. Setting this field will override the URL generated by the `network` and`apiKey` fields.
- `authToken`: Alchemy auth token required to use the Notify API. This token can be found in the Alchemy Dashboard on the Notify tab.
- `batchRequests`: Optional setting that automatically batches and sends json-rpc requests for higher throughput and reduced network IO. Defaults to false.
- `requestTimeout`: Optional setting that sets the timeout for requests in milliseconds for the NFT and Notify namespaces. Defaults to no timeout.

## Alchemy Core

The core namespace contains all commonly-used [Ethers.js Provider](https://docs.ethers.io/v5/api/providers/api-providers/#AlchemyProvider) methods. If you are already using Ethers.js, you should be simply able to replace the Ethers.js Provider object with `alchemy.core` when accessing provider methods and it should just work.

It also includes the majority of Alchemy Enhanced APIs, including:

- `getTokenMetadata()`: Get the metadata for a token contract address.
- `getTokenBalances()`: Gets the token balances for an owner given a list of contracts.
- `getAssetTransfers()`: Get transactions for specific addresses.
- `getTransactionReceipts()`: Gets all transaction receipts for a given block.

You will also find the following utility methods:

- `findContractDeployer()`: Find the contract deployer and block number for a given contract address.
- `getTokensForOwner()`: Get all token balances and metadata for a given owner address

### Accessing the full Ethers.js Provider

To keep the package clean, we don't support certain uncommonly-used Ethers.js Provider methods as top-level methods in the Alchemy `core` namespace - for example, `provider.formatter`. If you'd like to access these methods, simply use the `alchemy.config.getProvider()` function to configure the
Ethers.js Provider [AlchemyProvider](https://docs.ethers.io/v5/api/providers/api-providers/#AlchemyProvider) and return it.

```ts
import { Alchemy } from 'alchemy-sdk';

const alchemy = new Alchemy();

async function runAlchemy() {
  const ethersProvider = await alchemy.config.getProvider();
  console.log(ethersProvider.formatter);
}
runAlchemy();
```

## Alchemy WebSockets

In addition to the built-in Ethers.js listeners, the Alchemy SDK includes support for [Alchemy's Subscription API](https://docs.alchemy.com/alchemy/enhanced-apis/subscription-api-websockets). This allows you to subscribe to events and receive updates as they occur.

The `alchemy.ws` instance can be used like the standard Ethers.js [WebSocketProvider](https://docs.ethers.io/v5/api/providers/other/#WebSocketProvider) to add listeners for Alchemy events:

```ts
import { Alchemy, AlchemySubscription } from 'alchemy-sdk';

const alchemy = new Alchemy();

// Listen to all new pending transactions.
alchemy.ws.on('block', res => console.log(res));

// Listen to only the next transaction on the USDC contract.
alchemy.ws.once(
  {
    method: AlchemySubscription.PENDING_TRANSACTIONS,
    toAddress: 'vitalik.eth'
  },
  res => console.log(res)
);

// Remove all listeners.
alchemy.ws.removeAllListeners();
```

The SDK brings multiple improvements to ensure correct WebSocket behavior in cases of temporary network failure or
dropped connections. As with any network connection, you should not assume that a WebSocket will remain open forever
without interruption, but correctly handling dropped connections and reconnection by hand can be challenging to get
right. The Alchemy SDK automatically handles these failures with no configuration necessary. The main benefits are:

- Resilient event delivery: Unlike standard Web3.js or Ethers.js, you will not permanently miss events which arrive
  while the backing WebSocket is temporarily down. Instead, you will receive these events as soon as the connection
  is reopened. Note that if the connection is down for more than 120 blocks (approximately 20 minutes), you may
  still miss some events that were not part of the most recent 120 blocks.
- Lowered rate of failure: Compared to standard Web3.js or Ethers.js, there are fewer failures when sending requests
  over the WebSocket while the connection is down. The Alchemy SDK will attempt to send the requests once the connection
  is reopened. Note that it is still possible, with a lower likelihood, for outgoing requests to be lost,
  so you should still have error handling as with any network request.

## Alchemy Transact

The `transact` namespace contains methods used for simulating and sending transactions. The unique methods to the `transact` namespace are:

- `sendPrivateTransaction()`: Send a private transaction through Flashbots.
- `cancelPrivateTransaction()`: Cancel a private transaction sent with Flashbots.
- `simulateAssetChanges()`: Simulate a transaction and get a list of asset changes.
- `simulateExecution()`: Simulate a transaction and get a full list of internal transactions, logs, ABI decoded results and more.
- `simulateAssetChangesBundle()`: Simulate a list of transactions in sequence and get a list of asset changes.
- `simulateExecutionBundle()`: Simulate a list of transactions in sequence and get a full list of internal transactions, logs, ABI decoded results and more.

The `transact` namespace also aliases over several commonly used methods from the `core` namespace for convenience:

- `getTransaction()`: Returns the transaction for the given transaction hash.
- `sendTransaction()`: Sends a standard transaction to the network to be mined.
- `waitForTransaction()`: Waits for a transaction to be mined and returns the transaction receipt.

## Alchemy NFT API

The SDK currently supports the following [NFT API](https://docs.alchemy.com/alchemy/enhanced-apis/nft-api) endpoints
under the `alchemy.nft` namespace:

- `getNftMetadata()`: Get the NFT metadata for an NFT contract address and tokenId.
- `getNftMetadataBatch()`: Get the NFT metadata for multiple NFT contract addresses/token id pairs.
- `getContractMetadata()`: Get the metadata associated with an NFT contract
- `getContractMetadataBatch()`: Get the metadata associated with multiple NFT contracts in a single request.
- `getContractsForOwner()`: Get all NFT contracts that the provided owner address owns.
- `getNftsForOwner()`: Get NFTs for an owner address.
- `getNftsForOwnerIterator()`: Get NFTs for an owner address as an async iterator (handles paging automatically).
- `getNftsForContract()`: Get all NFTs for a contract address.
- `getNftsForContractIterator()`: Get all NFTs for a contract address as an async iterator (handles paging
  automatically).
- `getOwnersForNft()`: Get all the owners for a given NFT contract address and a particular token ID.
- `getOwnersForContract()`: Get all the owners for a given NFT contract address.
- `getMintedNfts()`: Get all the NFTs minted by the owner address.
- `getTransfersForOwner()`: Get all the NFT transfers for a given owner address.
- `getTransfersForContract()`: Get all the NFT transfers for a given NFT contract address.
- `verifyNftOwnership()`: Check whether the provided owner address owns the provided NFT contract addresses.
- `isSpamContract()`: Check whether the given NFT contract address is a spam contract as defined by Alchemy (see the [NFT API FAQ](https://docs.alchemy.com/alchemy/enhanced-apis/nft-api/nft-api-faq#nft-spam-classification))
- `getSpamContracts()`: Returns a list of all spam contracts marked by Alchemy.
- `reportSpam()`: Report feedback that a given NFT contract address is a spam contract as defined by Alchemy.
- `isAirdropNft()`: Check whether the given NFT token is marked as an airdrop or not. Airdrops are defined as NFTs that were minted to a user address in a transaction sent by a different address.
- `refreshNftMetadata()`: Refresh the cached NFT metadata for a contract address and a single tokenId.
- `refreshContract()`: Enqueues the specified contract address to have all token ids' metadata refreshed.
- `getFloorPrice()`: Return the floor prices of a NFT contract by marketplace.
- `computeRarity()`: Get the rarity of each attribute of an NFT.
- `getNftSales()`: Returns NFT sales that have happened through on-chain marketplaces.
- `summarizeNftAttributes()`: Get the summary of attribute prevalence for all NFTs in a contract.
- `searchContractMetadata()`: Search for a keyword across metadata of all ERC-721 and ERC-1155 smart contracts.

### Pagination

The Alchemy NFT endpoints return 100 results per page. To get the next page, you can pass in the `pageKey` returned by
the
previous call. To simplify paginating through all results, the SDK provides the `getNftsIterator()`
and `getNftsForContractIterator()` functions that automatically paginate through all NFTs and yields them via
an `AsyncIterable`.

Here's an example of how to paginate through all the NFTs in Vitalik's ENS address:

```ts
import { Alchemy } from 'alchemy-sdk';

const alchemy = new Alchemy();

async function main() {
  const ownerAddress = 'vitalik.eth';
  for await (const nft of alchemy.nft.getNftsForOwnerIterator(ownerAddress)) {
    console.log('ownedNft:', nft);
  }
}

main();
```

### SDK vs API Differences

The NFT API in the SDK standardizes response types to reduce developer friction, but note this results in some
differences compared to the Alchemy REST endpoints:

- Methods referencing `Collection` have been renamed to use the name `Contract` for greater accuracy: e.g. `getNftsForContract`.
- Some methods have different naming that the REST API counterparts in order to provide a consistent API interface (
  e.g. `getNftsForOwner()` is `alchemy_getNfts`, `getOwnersForNft()` is `alchemy_getOwnersForToken`).
- SDK standardizes to `omitMetadata` parameter (vs. `withMetadata`).
- Standardization to `pageKey` parameter for pagination (vs. `nextToken`/`startToken`)
- Empty `TokenUri` fields are omitted.
- Token ID is always normalized to an integer string on `BaseNft` and `Nft`.
- Some fields omitted in the REST response are included in the SDK response in order to return an `Nft` object.
- Some fields in the SDK's `Nft` object are named differently than the REST response.

## Alchemy Portfolio API

The [Alchemy Portfolio APIs](https://www.alchemy.com/docs/reference/portfolio-apis) include everything you need to build a view of a user’s assets: fungibles, NFTs, and their transactions.

Methods on the `PortfolioNamespace` can be accessed via `alchemy.portfolio`. To use the methods, you must include your team's auth token in the `authToken` field of `AlchemySettings` when instantiating the SDK. The auth token can be found on the Alchemy Dashboard.

Methods include:

- `getTokensByWallet()`: Fetches fungible tokens (native and ERC-20) for multiple wallet addresses and networks.
- `getTokenBalancesByWallet()`: Fetches fungible tokens (native and ERC-20) for multiple wallet addresses and networks.
- `getNftsByWallet()`: Fetches NFTs for multiple wallet addresses and networks.
- `getNftCollectionsByWallet()`: Fetches NFT collections (contracts) for multiple wallet addresses and networks.
- `getTransactionsByWallet()`: Fetches all historical transactions (internal & external) for multiple wallet addresses and networks.

## Alchemy Notify

The [Alchemy Notify API](https://docs.alchemy.com/reference/notify-api-quickstart) helps developers set up webhooks in their apps. The namespace provides methods to programmatically create, read, update, and delete your webhooks along with typings for the different webhooks. To learn more about Webhooks, please refer to the [Alchemy documentation](https://docs.alchemy.com/reference/notify-api-quickstart#what-are-webhooks).

Methods on the `NotifyNamespace` can be accessed via `alchemy.notify`. To use the methods, you must include your team's auth token in the `authToken` field of `AlchemySettings` when instantiating the SDK. The auth token can be found on the Alchemy Dashboard in the Notify Tab.

Methods include:

- `getAllWebhooks()`: Get all webhooks on your team.
- `getAddresses()`: Get all addresses tracked for the provided Address Activity Webhook.
- `getNftFilters()`: Get all NFT filters tracked for the provided NFT Activity Webhook.
- `createWebhook()`: Create a new webhook.
- `updateWebhook()`: Update an existing webhook's active status or tracked addresses and NFT filters.
- `deleteWebhook()`: Delete the provided webhook.

## Alchemy Debug

Methods on the `DebugNamespace` can be accessed via `alchemy.debug`. These methods are used for inspecting and debugging transactions.

Methods include:

- `traceCall()`: Run an `eth_call` with the context of the provided block execution using the final state of the parent block as the base.
- `traceTransaction()`: Run the transaction in the exact same manner as it was executed on the network. It will replay any transaction that may have been executed prior to this one before it and will then attempt to execute the transaction that corresponds to the given hash.
- `traceBlock()`: Replay a block that has already been mined.

## Documentation

The SDK is documented via `tsdoc` comments in the source code. The generated types and documentation are included when
using an IDE. To browse the documentation separately, you can view the generated API interfaces
in `etc/alchemy-sdk.api.md`. You can view generated Markdown files for each endpoint in the `docs-md` directory,
or as a webpage by opening `docs/index.html` in your browser.

## Usage Examples

Below are a few usage examples.

> **ℹ️ More Examples **
>
> You can also go here: [Examples Using the Alchemy SDK](https://docs.alchemy.com/reference/using-the-alchemy-sdk).

### Getting the NFTs owned by an address

```ts
import { Alchemy, NftExcludeFilters } from 'alchemy-sdk';

const alchemy = new Alchemy();

// Get how many NFTs an address owns.
alchemy.nft.getNftsForOwner('vitalik.eth').then(nfts => {
  console.log(nfts.totalCount);
});

// Get all the image urls for all the NFTs an address owns.
async function main() {
  for await (const nft of alchemy.nft.getNftsForOwnerIterator('vitalik.eth')) {
    console.log(nft.media);
  }
}

main();

// Filter out spam NFTs.
alchemy.nft
  .getNftsForOwner('vitalik.eth', {
    excludeFilters: [NftExcludeFilters.SPAM]
  })
  .then(console.log);
```

### Getting all the owners of the BAYC NFT

```ts
import { Alchemy } from 'alchemy-sdk';

const alchemy = new Alchemy();

// Bored Ape Yacht Club contract address.
const baycAddress = '0xBC4CA0EdA7647A8aB7C2061c2E118A18a936f13D';

async function main() {
  for await (const nft of alchemy.nft.getNftsForContractIterator(baycAddress, {
    // Omit the NFT metadata for smaller payloads.
    omitMetadata: true
  })) {
    await alchemy.nft
      .getOwnersForNft(nft.contract.address, nft.tokenId)
      .then(response =>
        console.log('owners:', response.owners, 'tokenId:', nft.tokenId)
      );
  }
}

main();
```

### Get all outbound transfers for a provided address

```ts
import { Alchemy } from 'alchemy-sdk';

const alchemy = new Alchemy();

alchemy.core.getTokenBalances('vitalik.eth').then(console.log);
```

## Questions and Feedback

If you have any questions, issues, or feedback, please file an issue
on [GitHub](https://github.com/alchemyplatform/alchemy-sdk-js/issues), or drop us a message on
our [Discord](https://discord.com/invite/alchemyplatform) channel for the SDK.


---

## 37. metamask-sdk-1
- **URL:** https://github.com/devtechedge/metamask-sdk-1
- **Language:** TypeScript
- **Topics:** None
- **Description:** The simplest yet most secure way to connect your blockchain-based applications to millions of MetaMask Wallet users.

### README.md

# MetaMask SDK (Deprecated)

> **⚠️ DEPRECATED**
>
> This repository is deprecated and no longer actively maintained. MetaMask SDK has been superseded by **MetaMask Connect**, a ground-up rewrite with a streamlined API, direct wallet communication (no relay server), and multichain support out of the box.
>
> **Migrate to:**
>
> - [`@metamask/connect-evm`](https://www.npmjs.com/package/@metamask/connect-evm) — drop-in EVM dapp integration (browser, Node.js, React Native)
> - [`@metamask/connect-multichain`](https://www.npmjs.com/package/@metamask/connect-multichain) — multichain dapp integration (EVM + non-EVM)
>
> **Migration guide & docs:** <https://docs.metamask.io/metamask-connect>
>
> **New repo:** <https://github.com/MetaMask/connect-monorepo>

---

[![codecov](https://codecov.io/gh/MetaMask/metamask-sdk/graph/badge.svg?token=6B3Z3724OO)](https://codecov.io/gh/MetaMask/metamask-sdk)

MetaMask SDK enables developers to seamlessly connect their dapps to the MetaMask extension and mobile app.

You can use the SDK via the following platforms and libraries:

- [Wagmi](https://docs.metamask.io/sdk/connect/javascript-wagmi/) (recommended)
- [JavaScript](https://docs.metamask.io/sdk/connect/javascript/)
- [Dynamic SDK](https://docs.metamask.io/sdk/connect/javascript-dynamic/)
- [Web3Auth SDK](https://docs.metamask.io/sdk/connect/javascript-web3auth/)
- [React Native](https://docs.metamask.io/sdk/connect/react-native/)
- [Web3-Onboard](https://onboard.blocknative.com/)

See the [MetaMask SDK documentation](https://docs.metamask.io/sdk/) for more information.

## Features

- Session persistence
- Multi MetaMask provider (let user choose between browser extension and mobile wallet)
- Batch RPC calls (send multiple requests to your wallet at once)
- Read-only RPC calls and Infura integration
- Wagmi hook integration (alpha)
- i18n
- Full modal UI customization
- Smart contract library (coming soon)

## Get started

Install the SDK:

```bash
yarn add @metamask/sdk
```

or

```bash
npm i @metamask/sdk
```

## SDK options

See the full list of [JavaScript SDK options](https://docs.metamask.io/sdk/reference/sdk-options/).

## Contributing

To contribute to MetaMask SDK, see the [contribution guidelines](./docs/contributing.md).

## Contacts

Fill out [this form](https://fq1an8d8ib2.typeform.com/to/sC7eK5F1) for a complimentary design
optimization workshop.


---

## 38. sdk
- **URL:** https://github.com/devtechedge/sdk
- **Language:** TypeScript
- **Topics:** None
- **Description:** Repository for shared logic and useful utilities

### README.md

# Across SDK

Across is a system that quickly moves tokens across chains. This repository contains shareable code and libraries for Across.

## Modules
| Name | Description | README | Source Code |
|---|---|---|---|
| **LP Fee Calculator** | Calculate LP fee for transfers | [README](./src/lpFeeCalculator/README.md) | [Source Code](./src/lpFeeCalculator/) |
| **Merkle Distributor** | ACX token distribution | [README](./src/merkleDistributor/README.md) | [Source Code](./src/merkleDistributor/) |

## TSDX User Guide

**This project was bootstrapped with [tsdx](https://github.com/jaredpalmer/tsdx). Read below for more instructions or check out the [repository](https://github.com/jaredpalmer/tsdx)**

Congrats! You just saved yourself hours of work by bootstrapping this project with TSDX. Let’s get you oriented with what’s here and how to use it.

> This TSDX setup is meant for developing libraries (not apps!) that can be published to NPM. If you’re looking to build a Node app, you could use `ts-node-dev`, plain `ts-node`, or simple `tsc`.

> If you’re new to TypeScript, checkout [this handy cheatsheet](https://devhints.io/typescript)

## Commands

TSDX scaffolds your new library inside `/src`.

To run TSDX, use:

```bash
npm start # or yarn start
```

This builds to `/dist` and runs the project in watch mode so any edits you save inside `src` causes a rebuild to `/dist`.

To do a one-off build, use `npm run build` or `yarn build`.

To run tests, use `npm test` or `yarn test`.

## Configuration

Code quality is set up for you with `prettier`, `husky`, and `lint-staged`. Adjust the respective fields in `package.json` accordingly.

### Jest

Jest tests are set up to run with `npm test` or `yarn test`.

### Bundle Analysis

[`size-limit`](https://github.com/ai/size-limit) is set up to calculate the real cost of your library with `npm run size` and visualize the bundle with `npm run analyze`.

#### Setup Files

This is the folder structure we set up for you:

```txt
/src
  index.tsx       # EDIT THIS
/test
  blah.test.tsx   # EDIT THIS
.gitignore
package.json
README.md         # EDIT THIS
tsconfig.json
```

### Rollup

TSDX uses [Rollup](https://rollupjs.org) as a bundler and generates multiple rollup configs for various module formats and build settings. See [Optimizations](#optimizations) for details.

### TypeScript

`tsconfig.json` is set up to interpret `dom` and `esnext` types, as well as `react` for `jsx`. Adjust according to your needs.

## Continuous Integration

### GitHub Actions

Two actions are added by default:

- `main` which installs deps w/ cache, lints, tests, and builds on all pushes against a Node and OS matrix
- `size` which comments cost comparison of your library on every pull request using [`size-limit`](https://github.com/ai/size-limit)

## Optimizations

Please see the main `tsdx` [optimizations docs](https://github.com/palmerhq/tsdx#optimizations). In particular, know that you can take advantage of development-only optimizations:

```js
// ./types/index.d.ts
declare var __DEV__: boolean;

// inside your code...
if (__DEV__) {
  console.log('foo');
}
```

You can also choose to install and use [invariant](https://github.com/palmerhq/tsdx#invariant) and [warning](https://github.com/palmerhq/tsdx#warning) functions.

## Module Formats

CJS, ESModules, and UMD module formats are supported.

The appropriate paths are configured in `package.json` and `dist/index.js` accordingly. Please report if any issues are found.

## Named Exports

Per Palmer Group guidelines, [always use named exports.](https://github.com/palmerhq/typescript#exports) Code split inside your React app instead of your React library.

## Including Styles

There are many ways to ship styles, including with CSS-in-JS. TSDX has no opinion on this, configure how you like.

For vanilla CSS, you can include it at the root directory and add it to the `files` section in your `package.json`, so that it can be imported separately by your users and run through their bundler's loader.

## Publishing a new version
1. Bump version in package.json and merge to master. Example: https://github.com/across-protocol/sdk/pull/67
2. Create a new release with a new tag (version number should be incremented): https://github.com/across-protocol/sdk/releases
3. Update any upstream repos/binaries that depend on the sdk such as https://github.com/across-protocol/frontend. Example: https://github.com/across-protocol/frontend/pull/202


---

## 39. metamask-sdk-empty-placeholder
- **URL:** https://github.com/devtechedge/metamask-sdk-empty-placeholder
- **Language:** Not specified
- **Topics:** None
- **Description:** No description

### README.md

*No standard README.md found.*

---

## 40. crewAI
- **URL:** https://github.com/devtechedge/crewAI
- **Language:** Python
- **Topics:** None
- **Description:** Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks.

### README.md

<p align="center">
  <a href="https://github.com/crewAIInc/crewAI">
    <img src="docs/images/crewai_logo.png" width="600px" alt="Open source Multi-AI Agent orchestration framework">
  </a>
</p>
<p align="center" style="display: flex; justify-content: center; gap: 20px; align-items: center;">
  <a href="https://trendshift.io/repositories/11239" target="_blank">
    <img src="https://trendshift.io/api/badge/repositories/11239" alt="crewAIInc%2FcrewAI | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/>
  </a>
</p>

<p align="center">
  <a href="https://crewai.com">Homepage</a>
  ·
  <a href="https://crewai.com/open-source">Open Source</a>
  ·
  <a href="https://docs.crewai.com">Docs</a>
  ·
  <a href="https://app.crewai.com">Start Cloud Trial</a>
  ·
  <a href="https://blog.crewai.com">Blog</a>
  ·
  <a href="https://community.crewai.com">Forum</a>
</p>

<p align="center">
  <a href="https://github.com/crewAIInc/crewAI">
    <img src="https://img.shields.io/github/stars/crewAIInc/crewAI" alt="GitHub Repo stars">
  </a>
  <a href="https://github.com/crewAIInc/crewAI/network/members">
    <img src="https://img.shields.io/github/forks/crewAIInc/crewAI" alt="GitHub forks">
  </a>
  <a href="https://github.com/crewAIInc/crewAI/issues">
    <img src="https://img.shields.io/github/issues/crewAIInc/crewAI" alt="GitHub issues">
  </a>
  <a href="https://github.com/crewAIInc/crewAI/pulls">
    <img src="https://img.shields.io/github/issues-pr/crewAIInc/crewAI" alt="GitHub pull requests">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT">
  </a>
</p>

<p align="center">
  <a href="https://pypi.org/project/crewai/">
    <img src="https://img.shields.io/pypi/v/crewai" alt="PyPI version">
  </a>
  <a href="https://pypi.org/project/crewai/">
    <img src="https://img.shields.io/pypi/dm/crewai" alt="PyPI downloads">
  </a>
  <a href="https://twitter.com/crewAIInc">
    <img src="https://img.shields.io/twitter/follow/crewAIInc?style=social" alt="Twitter Follow">
  </a>
</p>

### Fast and Flexible Multi-Agent Automation Framework

> CrewAI is an open-source Python framework with high-level abstractions and low-level APIs for building production-ready multi-agent workflows.
> It gives developers autonomous agent collaboration through Crews and precise, event-driven control through Flows.

- **CrewAI Crews**: Optimize for autonomy and collaborative intelligence with role-based AI agents.
- **CrewAI Flows**: Build event-driven automations that combine precise workflow control, single LLM calls, and native support for Crews.

With over 100,000 developers certified through our community courses at [learn.crewai.com](https://learn.crewai.com), CrewAI is rapidly becoming the
standard for production-ready agentic automation.

# CrewAI AMP Suite

For organizations that need a commercial control plane around CrewAI, [CrewAI AMP Suite](https://crewai.com/amp) adds managed deployment, observability, governance, security, and enterprise support.

You can try one part of the suite, the [Crew Control Plane, for free](https://app.crewai.com).

## Crew Control Plane Key Features:

- **Tracing & Observability**: Monitor and track your AI agents and workflows in real-time, including metrics, logs, and traces.
- **Unified Control Plane**: A centralized platform for managing, monitoring, and scaling your AI agents and workflows.
- **Seamless Integrations**: Easily connect with existing enterprise systems, data sources, and cloud infrastructure.
- **Advanced Security**: Built-in robust security and compliance measures ensuring safe deployment and management.
- **Actionable Insights**: Real-time analytics and reporting to optimize performance and decision-making.
- **24/7 Support**: Dedicated enterprise support to ensure uninterrupted operation and quick resolution of issues.
- **On-premise and Cloud Deployment Options**: Deploy CrewAI AMP on-premise or in the cloud, depending on your security and compliance requirements.

CrewAI AMP is designed for enterprises seeking a powerful, reliable solution to transform complex business processes into efficient,
intelligent automations.

## Table of contents

- [Build with AI](#build-with-ai)
- [Why CrewAI?](#why-crewai)
- [Getting Started](#getting-started)
  - [Learning Resources](#learning-resources)
  - [Understanding Flows and Crews](#understanding-flows-and-crews)
  - [Installation](#1-installation)
  - [Setting Up Your Crew](#2-setting-up-your-crew)
  - [Running Your Crew](#3-running-your-crew)
- [Key Features](#key-features)
- [Examples](#examples)
  - [Quick Tutorial](#quick-tutorial)
  - [Write Job Descriptions](#write-job-descriptions)
  - [Trip Planner](#trip-planner)
  - [Stock Analysis](#stock-analysis)
  - [Using Crews and Flows Together](#using-crews-and-flows-together)
- [Connecting Your Crew to a Model](#connecting-your-crew-to-a-model)
- [When to Use CrewAI](#when-to-use-crewai)
- [Contribution](#contribution)
- [Telemetry](#telemetry)
- [License](#license)
- [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)

## Build with AI

Using an AI coding agent? Teach it CrewAI best practices in one command:

**Claude Code:**
```shell
/plugin marketplace add crewAIInc/skills
/plugin install crewai-skills@crewai-plugins
/reload-plugins
```
Four skills that activate automatically when you ask relevant CrewAI questions:

| Skill | When it runs |
|-------|--------------|
| `getting-started` | Scaffolding new projects, choosing between `LLM.call()` / `Agent` / `Crew` / `Flow`, wiring `crew.jsonc` / `main.py` |
| `design-agent` | Configuring agents — role, goal, backstory, tools, LLMs, memory, guardrails |
| `design-task` | Writing task descriptions, dependencies, structured output (`output_pydantic`, `output_json`), human review |
| `ask-docs` | Querying the live [CrewAI docs MCP server](https://docs.crewai.com/mcp) for up-to-date API details |

**Cursor, Codex, Windsurf, and others ([skills.sh](https://skills.sh/crewaiinc/skills)):**
```shell
npx skills add crewaiinc/skills
```

This installs the official [CrewAI Skills](https://github.com/crewAIInc/skills) — structured instructions that teach coding agents how to scaffold Flows, configure Crews, design agents and tasks, and follow CrewAI patterns.

## Why CrewAI?

<div align="center" style="margin-bottom: 30px;">
  <img src="docs/images/asset.png" alt="CrewAI Logo" width="100%">
</div>

CrewAI unlocks the true potential of multi-agent automation, delivering speed, flexibility, and control through Crews of AI agents and event-driven Flows:

- **Purpose-built architecture**: Designed specifically for agent orchestration, with a lightweight Python core and clean primitives for real-world automation.
- **High Performance**: Optimized for speed and minimal resource usage, enabling faster execution.
- **Flexible Low-Level Customization**: Complete freedom to customize everything from workflows and system architecture to agent behaviors, internal prompts, and execution logic.
- **Ideal for Every Use Case**: Proven effective for simple tasks, complex workflows, and production-grade automation.
- **Robust Community**: Backed by a rapidly growing community of over **100,000 certified** developers offering comprehensive support and resources.

CrewAI empowers developers and teams to build intelligent automations that balance simplicity, flexibility, and production-grade control.

## Getting Started

Setup and run your first CrewAI agents by following this tutorial.

[![CrewAI Getting Started Tutorial](https://img.youtube.com/vi/-kSOTtYzgEw/hqdefault.jpg)](https://www.youtube.com/watch?v=-kSOTtYzgEw "CrewAI Getting Started Tutorial")

### Learning Resources

Learn CrewAI through our comprehensive courses:

- [Multi AI Agent Systems with CrewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) - Master the fundamentals of multi-agent systems
- [Practical Multi AI Agents and Advanced Use Cases](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/) - Deep dive into advanced implementations

### Understanding Flows and Crews

CrewAI offers two powerful, complementary approaches that work seamlessly together to build sophisticated AI applications:

1. **Crews**: Teams of AI agents with true autonomy and agency, working together to accomplish complex tasks through role-based collaboration. Crews enable:

   - Natural, autonomous decision-making between agents
   - Dynamic task delegation and collaboration
   - Specialized roles with defined goals and expertise
   - Flexible problem-solving approaches

2. **Flows**: Production-ready, event-driven workflows that deliver precise control over complex automations. Flows provide:

   - Fine-grained control over execution paths for real-world scenarios
   - Secure, consistent state management between tasks
   - Clean integration of AI agents with production Python code
   - Conditional branching for complex business logic

The true power of CrewAI emerges when combining Crews and Flows. This synergy allows you to:

- Build complex, production-grade applications
- Balance autonomy with precise control
- Handle sophisticated real-world scenarios
- Maintain clean, maintainable code structure

### Getting Started with Installation

To get started with CrewAI, follow these simple steps. The full walkthrough lives in the [installation guide](https://docs.crewai.com/en/installation).

### 1. Installation

CrewAI requires `Python >=3.10 and <3.14`. Check your version with:

```bash
python3 --version
```

CrewAI uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling. If you haven't installed `uv` yet, install it first.

**macOS/Linux:**

```shell
curl -LsSf https://astral.sh/uv/install.sh | sh
```

If your system doesn't have `curl`, you can use `wget`:

```shell
wget -qO- https://astral.sh/uv/install.sh | sh
```

**Windows:**

```shell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

If you run into any issues, refer to [UV's installation guide](https://docs.astral.sh/uv/getting-started/installation/).

Then install the CrewAI CLI:

```shell
uv tool install crewai
```

If you encounter a `PATH` warning, run:

```shell
uv tool update-shell
```

If you encounter the `chroma-hnswlib==0.7.6` build error (`fatal error C1083: Cannot open include file: 'float.h'`) on Windows, install [Visual Studio Build Tools](https://visualstudio.microsoft.com/downloads/) with *Desktop development with C++*.

Verify the install:

```shell
uv tool list
```

You should see something like:

```shell
crewai v0.102.0
- crewai
```

To upgrade the global CLI later:

```shell
uv tool install crewai --upgrade
```

This upgrades the **global `crewai` CLI tool** only. To upgrade the `crewai` version inside a project's virtual environment, see [Upgrading CrewAI in a project](https://docs.crewai.com/en/guides/migration/upgrading-crewai).

### 2. Setting Up Your Crew

`crewai create crew` creates a JSON-first crew project. Agents live in `agents/*.jsonc`, tasks and crew-level settings live in `crew.jsonc`, and `crewai run` loads that JSON definition directly.

```shell
crewai create crew <project_name>
```

This command creates a new project folder with the following structure:

```
my_project/
├── .gitignore
├── .env
├── agents/
│   └── researcher.jsonc
├── crew.jsonc
├── knowledge/
├── pyproject.toml
├── README.md
├── skills/
└── tools/
```

If you need the older Python/YAML scaffold with `crew.py`, `config/agents.yaml`, and `config/tasks.yaml`, run:

```shell
crewai create crew <project_name> --classic
```

See [Using Annotations](https://docs.crewai.com/en/learn/using-annotations) for the classic pattern.

#### To customize your project, you can:

- Modify `agents/*.jsonc` to define each agent's role, goal, backstory, LLM, tools, and behavior.
- Modify `crew.jsonc` to define tasks, process, and input defaults.
- Add custom tools in `tools/` and reference them as `"custom:<name>"`.
- Add optional knowledge files in `knowledge/` and skill files in `skills/`.
- Add your environment variables into the `.env` file.

Use `{placeholder}` values in agent and task text, then set defaults in `crew.jsonc` under `inputs`. When you run `crewai run`, the CLI prompts for any missing values.

#### Example of a simple crew with a sequential process:

```shell
crewai create crew latest-ai-development
cd latest_ai_development
```

Then edit the generated files:

**agents/researcher.jsonc**

```jsonc
{
  "role": "{topic} Senior Data Researcher",
  "goal": "Uncover cutting-edge developments in {topic}",
  "backstory": "You're a seasoned researcher who finds relevant information and presents it clearly.",
  "llm": "openai/gpt-4o",
  "tools": ["SerperDevTool"],
  "settings": {
    "verbose": true
  }
}
```

**agents/reporting_analyst.jsonc**

```jsonc
{
  "role": "{topic} Reporting Analyst",
  "goal": "Create detailed reports based on {topic} data analysis and research findings",
  "backstory": "You're a meticulous analyst who turns complex data into clear, concise reports.",
  "llm": "openai/gpt-4o",
  "settings": {
    "verbose": true
  }
}
```

**crew.jsonc**

```jsonc
{
  "name": "Latest AI Development",
  "agents": ["researcher", "reporting_analyst"],
  "tasks": [
    {
      "name": "research_task",
      "description": "Conduct thorough research about {topic}. Find recent, relevant information.",
      "expected_output": "A list with 10 bullet points of the most relevant information about {topic}.",
      "agent": "researcher"
    },
    {
      "name": "reporting_task",
      "description": "Review the research and expand each topic into a full section for a report.",
      "expected_output": "A markdown report with the main topics, each with a full section of information. No fenced code blocks around the whole document.",
      "agent": "reporting_analyst",
      "context": ["research_task"],
      "output_file": "output/report.md",
      "markdown": true
    }
  ],
  "process": "sequential",
  "verbose": true,
  "inputs": {
    "topic": "AI Agents"
  }
}
```

### 3. Running Your Crew

Before running your crew, set the required keys in your `.env` file:

- Your model provider API key — see [LLM setup](https://docs.crewai.com/en/concepts/llms#setting-up-your-llm)
- A [Serper.dev](https://serper.dev/) API key if you use web search: `SERPER_API_KEY=YOUR_KEY_HERE`

Then install dependencies and run from the project directory:

```shell
crewai install
crewai run
```

If you need additional packages, use `uv add <package-name>`.

You should see the output in the console, and `output/report.md` should be created in the project root.

In addition to the sequential process, you can use the hierarchical process, which automatically assigns a manager to the defined crew to properly coordinate the planning and execution of tasks through delegation and validation of results. [See more about the processes here](https://docs.crewai.com/en/concepts/processes).

For a Flow-first walkthrough, see the [Quickstart](https://docs.crewai.com/en/quickstart).

## Key Features

CrewAI gives developers a practical foundation for building agentic systems that move from prototype to production: autonomous collaboration where it helps, explicit workflow control where it matters, and Python-native customization throughout.

- **Crews for autonomy**: Model teams of specialized AI agents with roles, goals, tools, and tasks.
- **Flows for control**: Build event-driven workflows with state, branching, routing, and production logic.
- **Seamless integration**: Combine Crews and Flows to create complex, real-world automations.
- **Python-native customization**: Customize prompts, tools, execution paths, state, and integrations without fighting the framework.
- **Agent-ready capabilities**: Use tools, memory, knowledge, checkpointing, async execution, and MCP/A2A support for more capable production agents.
- **Production-ready patterns**: Add deterministic steps, human input, structured outputs, and checkpointing as your system grows.
- **Thriving community**: Backed by robust documentation and over 100,000 certified developers, providing exceptional support and guidance.

Choose CrewAI to build powerful, adaptable, and production-ready AI automations.

## Examples

You can test different real life examples of AI crews in the [CrewAI-examples repo](https://github.com/crewAIInc/crewAI-examples?tab=readme-ov-file):

- [Landing Page Generator](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/landing_page_generator)
- [Having Human input on the execution](https://docs.crewai.com/en/learn/human-input-on-execution)
- [Trip Planner](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/trip_planner)
- [Stock Analysis](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis)

### Quick Tutorial

[![CrewAI Tutorial](https://img.youtube.com/vi/tnejrr-0a94/maxresdefault.jpg)](https://www.youtube.com/watch?v=tnejrr-0a94 "CrewAI Tutorial")

### Write Job Descriptions

[Check out code for this example](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/job-posting) or watch a video below:

[![Jobs postings](https://img.youtube.com/vi/u98wEMz-9to/maxresdefault.jpg)](https://www.youtube.com/watch?v=u98wEMz-9to "Jobs postings")

### Trip Planner

[Check out code for this example](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/trip_planner) or watch a video below:

[![Trip Planner](https://img.youtube.com/vi/xis7rWp-hjs/maxresdefault.jpg)](https://www.youtube.com/watch?v=xis7rWp-hjs "Trip Planner")

### Stock Analysis

[Check out code for this example](https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis) or watch a video below:

[![Stock Analysis](https://img.youtube.com/vi/e0Uj4yWdaAg/maxresdefault.jpg)](https://www.youtube.com/watch?v=e0Uj4yWdaAg "Stock Analysis")

### Using Crews and Flows Together

CrewAI's power truly shines when combining Crews with Flows to create sophisticated automation pipelines.
CrewAI flows support logical operators like `or_` and `and_` to combine multiple conditions. This can be used with `@start`, `@listen`, or `@router` decorators to create complex triggering conditions.

- `or_`: Triggers when any of the specified conditions are met.
- `and_`: Triggers when all of the specified conditions are met.

Here's how you can orchestrate multiple Crews within a Flow:

```python
from crewai.flow.flow import Flow, listen, start, router, or_
from crewai import Crew, Agent, Task, Process
from pydantic import BaseModel

# Define structured state for precise control
class MarketState(BaseModel):
    sentiment: str = "neutral"
    confidence: float = 0.0
    recommendations: list = []

class AdvancedAnalysisFlow(Flow[MarketState]):
    @start()
    def fetch_market_data(self):
        # Demonstrate low-level control with structured state
        self.state.sentiment = "analyzing"
        return {"sector": "tech", "timeframe": "1W"}  # These parameters match the task description template

    @listen(fetch_market_data)
    def analyze_with_crew(self, market_data):
        # Show crew agency through specialized roles
        analyst = Agent(
            role="Senior Market Analyst",
            goal="Conduct deep market analysis with expert insight",
            backstory="You're a veteran analyst known for identifying subtle market patterns"
        )
        researcher = Agent(
            role="Data Researcher",
            goal="Gather and validate supporting market data",
            backstory="You excel at finding and correlating multiple data sources"
        )

        analysis_task = Task(
            description="Analyze {sector} sector data for the past {timeframe}",
            expected_output="Detailed market analysis with confidence score",
            agent=analyst
        )
        research_task = Task(
            description="Find supporting data to validate the analysis",
            expected_output="Corroborating evidence and potential contradictions",
            agent=researcher
        )

        # Demonstrate crew autonomy
        analysis_crew = Crew(
            agents=[analyst, researcher],
            tasks=[analysis_task, research_task],
            process=Process.sequential,
            verbose=True
        )
        return analysis_crew.kickoff(inputs=market_data)  # Pass market_data as named inputs

    @router(analyze_with_crew)
    def determine_next_steps(self):
        # Show flow control with conditional routing
        if self.state.confidence > 0.8:
            return "high_confidence"
        elif self.state.confidence > 0.5:
            return "medium_confidence"
        return "low_confidence"

    @listen("high_confidence")
    def execute_strategy(self):
        # Demonstrate complex decision making
        strategy_crew = Crew(
            agents=[
                Agent(role="Strategy Expert",
                      goal="Develop optimal market strategy")
            ],
            tasks=[
                Task(description="Create detailed strategy based on analysis",
                     expected_output="Step-by-step action plan")
            ]
        )
        return strategy_crew.kickoff()

    @listen(or_("medium_confidence", "low_confidence"))
    def request_additional_analysis(self):
        self.state.recommendations.append("Gather more data")
        return "Additional analysis required"
```

This example demonstrates how to:

1. Use Python code for basic data operations
2. Create and execute Crews as steps in your workflow
3. Use Flow decorators to manage the sequence of operations
4. Implement conditional branching based on Crew results

## Connecting Your Crew to a Model

CrewAI supports using various LLMs through a variety of connection options. By default your agents will use the OpenAI API when querying the model. However, there are several other ways to allow your agents to connect to models. For example, you can configure your agents to use a local model via the Ollama tool.

Please refer to the [Connect CrewAI to LLMs](https://docs.crewai.com/en/learn/llm-connections) page for details on configuring your agents' connections to models.

## When to Use CrewAI

Use CrewAI when you need more than a single prompt or chatbot: multi-step work, specialized agents, tool use, structured outputs, human review, or workflows that combine autonomous reasoning with explicit business logic.

CrewAI is especially useful when you want to:

- Coordinate multiple agents with clear roles and tasks.
- Wrap agent work in deterministic, event-driven workflows.
- Keep application logic in regular Python.
- Move from experiment to production without changing frameworks.
- Add tools, memory, checkpointing, and async execution as your system grows.

## Contribution

CrewAI is open-source and we welcome contributions. See
[`.github/CONTRIBUTING.md`](.github/CONTRIBUTING.md) for the full setup guide,
branching conventions, and PR checklist.

Quick start:

```bash
git clone https://github.com/crewAIInc/crewAI.git
cd crewAI
uv sync --all-groups --all-extras
uv run pre-commit install
```

```bash
# Tests
uv run pytest lib/crewai/tests/ -x -q

# Type checks
uv run mypy lib/
```

### Contributing to the docs

The site at [docs.crewai.com](https://docs.crewai.com) is published from
`docs/` by [Mintlify](https://www.mintlify.com/). The docs use directory-based
versioning: edits to `docs/edge/<lang>/...` (e.g.
`docs/edge/en/concepts/agents.mdx`) land under the **Edge** version selector
immediately and are frozen into a new versioned snapshot under
`docs/v<X.Y.Z>/` at the next release cut. Frozen snapshots are immutable — CI
rejects PRs that modify them without a `[docs-freeze]` title prefix. The
release CLI (`devtools release`) handles the freeze automatically; see
[`.github/CONTRIBUTING.md`](.github/CONTRIBUTING.md) for contributor guidance and
[`lib/devtools/README.md`](lib/devtools/README.md) for release tooling.

## Telemetry

CrewAI uses anonymous telemetry to collect usage data with the main purpose of helping us improve the library by focusing our efforts on the most used features, integrations and tools.

It's pivotal to understand that **NO data is collected** concerning prompts, task descriptions, agents' backstories or goals, usage of tools, API calls, responses, any data processed by the agents, or secrets and environment variables, with the exception of the conditions mentioned. When the `share_crew` feature is enabled, detailed data including task descriptions, agents' backstories or goals, and other specific attributes are collected to provide deeper insights while respecting user privacy. Users can disable telemetry by setting the environment variable OTEL_SDK_DISABLED to true.

Data collected includes:

- Version of CrewAI
  - So we can understand how many users are using the latest version
- Version of Python
  - So we can decide on what versions to better support
- General OS (e.g. number of CPUs, macOS/Windows/Linux)
  - So we know what OS we should focus on and if we could build specific OS related features
- Number of agents and tasks in a crew
  - So we make sure we are testing internally with similar use cases and educate people on the best practices
- Crew Process being used
  - Understand where we should focus our efforts
- If Agents are using memory or allowing delegation
  - Understand if we improved the features or maybe even drop them
- If Tasks are being executed in parallel or sequentially
  - Understand if we should focus more on parallel execution
- Language model being used
  - Improved support on most used languages
- Roles of agents in a crew
  - Understand high level use cases so we can build better tools, integrations and examples about it
- Tools names available
  - Understand out of the publicly available tools, which ones are being used the most so we can improve them

Users can opt-in to Further Telemetry, sharing the complete telemetry data by setting the `share_crew` attribute to `True` on their Crews. Enabling `share_crew` results in the collection of detailed crew and task execution data, including `goal`, `backstory`, `context`, and `output` of tasks. This enables a deeper insight into usage patterns while respecting the user's choice to share.

## License

CrewAI is released under the [MIT License](https://github.com/crewAIInc/crewAI/blob/main/LICENSE).

## Frequently Asked Questions (FAQ)

### General

- [What exactly is CrewAI?](#q-what-exactly-is-crewai)
- [How do I install CrewAI?](#q-how-do-i-install-crewai)
- [Is CrewAI a standalone framework?](#q-is-crewai-a-standalone-framework)
- [Is CrewAI open-source?](#q-is-crewai-open-source)
- [Does CrewAI collect data from users?](#q-does-crewai-collect-data-from-users)

### Features and Capabilities

- [Can CrewAI handle complex use cases?](#q-can-crewai-handle-complex-use-cases)
- [Can I use CrewAI with local AI models?](#q-can-i-use-crewai-with-local-ai-models)
- [What makes Crews different from Flows?](#q-what-makes-crews-different-from-flows)
- [Does CrewAI support fine-tuning or training custom models?](#q-does-crewai-support-fine-tuning-or-training-custom-models)

### Resources and Community

- [Where can I find real-world CrewAI examples?](#q-where-can-i-find-real-world-crewai-examples)
- [How can I contribute to CrewAI?](#q-how-can-i-contribute-to-crewai)

### Enterprise Features

- [What additional features does CrewAI AMP offer?](#q-what-additional-features-does-crewai-amp-offer)
- [Is CrewAI AMP available for cloud and on-premise deployments?](#q-is-crewai-amp-available-for-cloud-and-on-premise-deployments)
- [Can I try CrewAI AMP for free?](#q-can-i-try-crewai-amp-for-free)

### Q: What exactly is CrewAI?

A: CrewAI is a lean, fast Python framework built specifically for orchestrating autonomous AI agents and production-ready agentic workflows.

### Q: How do I install CrewAI?

A: Install the CrewAI CLI with [UV](https://docs.astral.sh/uv/):

```shell
uv tool install crewai
```

Then create a project with `crewai create crew <project_name>`, run `crewai install`, and start it with `crewai run`. See the [installation guide](https://docs.crewai.com/en/installation) for details.

### Q: Is CrewAI a standalone framework?

A: Yes. CrewAI is a standalone Python framework with its own primitives for agents, tasks, crews, flows, tools, and orchestration.

### Q: Can CrewAI handle complex use cases?

A: Yes. CrewAI excels at both simple and highly complex real-world scenarios, offering deep customization options at both high and low levels, from internal prompts to sophisticated workflow orchestration.

### Q: Can I use CrewAI with local AI models?

A: Absolutely! CrewAI supports various language models, including local ones. Tools like Ollama and LM Studio allow seamless integration. Check the [LLM Connections documentation](https://docs.crewai.com/en/learn/llm-connections) for more details.

### Q: What makes Crews different from Flows?

A: Crews provide autonomous agent collaboration, ideal for tasks requiring flexible decision-making and dynamic interaction. Flows offer precise, event-driven control, ideal for managing detailed execution paths and secure state management. You can seamlessly combine both for maximum effectiveness.

### Q: Is CrewAI open-source?

A: Yes, CrewAI is open-source and actively encourages community contributions and collaboration.

### Q: Does CrewAI collect data from users?

A: CrewAI collects anonymous telemetry data strictly for improvement purposes. Sensitive data such as prompts, tasks, or API responses are never collected unless explicitly enabled by the user.

### Q: Where can I find real-world CrewAI examples?

A: Check out practical examples in the [CrewAI-examples repository](https://github.com/crewAIInc/crewAI-examples), covering use cases like trip planners, stock analysis, and job postings.

### Q: How can I contribute to CrewAI?

A: Contributions are warmly welcomed! Fork the repository, create your branch, implement your changes, and submit a pull request. See [`.github/CONTRIBUTING.md`](.github/CONTRIBUTING.md) for detailed guidelines.

### Q: What additional features does CrewAI AMP offer?

A: CrewAI AMP provides advanced features such as a unified control plane, real-time observability, secure integrations, advanced security, actionable insights, and dedicated 24/7 enterprise support.

### Q: Is CrewAI AMP available for cloud and on-premise deployments?

A: Yes, CrewAI AMP supports both cloud-based and on-premise deployment options, allowing enterprises to meet their specific security and compliance requirements.

### Q: Can I try CrewAI AMP for free?

A: Yes, you can explore part of the CrewAI AMP Suite by accessing the [Crew Control Plane](https://app.crewai.com) for free.

### Q: Does CrewAI support fine-tuning or training custom models?

A: Yes, CrewAI can integrate with custom-trained or fine-tuned models, allowing you to enhance your agents with domain-specific knowledge and accuracy.

### Q: Can CrewAI agents interact with external tools and APIs?

A: Absolutely! CrewAI agents can easily integrate with external tools, APIs, and databases, empowering them to leverage real-world data and resources.

### Q: Is CrewAI suitable for production environments?

A: Yes, CrewAI is designed with production-grade patterns that support reliable, stable, and scalable agentic workflows.

### Q: How scalable is CrewAI?

A: CrewAI is highly scalable, supporting simple automations and large-scale workflows involving numerous agents and complex tasks simultaneously.

### Q: Does CrewAI offer debugging and monitoring tools?

A: Yes, CrewAI AMP includes advanced debugging, tracing, and real-time observability features, simplifying the management and troubleshooting of your automations.

### Q: What programming languages does CrewAI support?

A: CrewAI is primarily Python-based but easily integrates with services and APIs written in any programming language through its flexible API integration capabilities.

### Q: Does CrewAI offer educational resources for beginners?

A: Yes, CrewAI provides extensive beginner-friendly tutorials, courses, and documentation through learn.crewai.com, supporting developers at all skill levels.

### Q: Can CrewAI automate human-in-the-loop workflows?

A: Yes, CrewAI fully supports human-in-the-loop workflows, allowing seamless collaboration between human experts and AI agents for enhanced decision-making.


---

## 41. extension
- **URL:** https://github.com/devtechedge/extension
- **Language:** TypeScript
- **Topics:** None
- **Description:** Your Web3 Wallet that just works. EIP-7702 ready.

### README.md

# Ambire Wallet

<div align="center">
  <a href="https://chromewebstore.google.com/detail/ambire-wallet/ehgjhhccekdedpbkifaojjaefeohnoea" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./mockups/mockup-dashboard-dark-v6.png">
      <source media="(prefers-color-scheme: light)" srcset="./mockups/mockup-dashboard-light-v6.png">
      <img src="./mockups/mockup-dashboard-light-v6.png" alt="Ambire Wallet Dashboard" width="528" height="648" />
    </picture>
  </a>

  <p>
    Your Web3 wallet that just works. EIP-7702 ready.<br>
    <em>A self-custodial browser wallet extension built for Ethereum and EVM networks.</em><br />
    <a href="https://www.ambire.com/get-extension" target="_blank">
      <strong>Download Ambire extension 🔥</strong>
    </a>
    <br />
    <em>(Chrome, Firefox, Brave, Opera, Edge, Arc)</em>
    <br /><br />
    👥 Join the community:
    <a href="https://discord.com/invite/Ambire" target="_blank">Discord</a> |
    <a href="https://t.me/AmbireOfficial" target="_blank">Telegram</a>
    <br />
    🐞
    <a href="https://github.com/AmbireTech/extension/issues">Report a Bug</a> ·
    <a href="https://help.ambire.com/en" target="_blank">Get help</a>
  </p>
</div>

## Environment Setup

Built in a hybrid approach (with React Native and React Native Web) so that in a single codebase we can support building cross-browser extensions, mobile apps and web apps.

This project is built with Expo's bare workflow, allowing us to extend the default Vanilla React Native with additional expo modules in the form of installable expo libraries.

More about the environment setup and prerequisites [here](https://reactnative.dev/docs/environment-setup).

Toolchain versions are pinned in the repo, so use a version manager that reads them (nvm, rbenv, jenv, etc.)

| Tool      | File             | Target   |
| --------- | ---------------- | -------- |
| Node      | `.nvmrc`         | All apps |
| Yarn      | `package.json`   | All apps |
| Ruby      | `.ruby-version`  | iOS      |
| Xcode     | `.xcode-version` | iOS      |
| CocoaPods | `Gemfile`        | iOS      |
| JDK       | `.java-version`  | Android  |

Yarn and CocoaPods are not picked up by a version manager: Yarn is pinned via `packageManager`/`engines` in `package.json`, CocoaPods via the `Gemfile` (run it through `bundle exec`, see "Mobile Apps").

## Install

Install all dependencies:

```bash
yarn setup
```

Install the [ambire-common](https://github.com/AmbireTech/ambire-common) submodule, a common ground for the Ambire apps, run:

```bash
git submodule init
git submodule update
```

## Environment Variables

Create ".env" file in the root directory and fill in all variables, see ".env-sample" for a reference.

## Editor Config

Make sure your code editor has plugins that support the following configuration files: `.editorconfig`, `.prettierrc`, `tsconfig.json`, `eslintrc.js`, [`import-sorter.json`](https://github.com/SoominHan/import-sorter).

## Browser Extensions

### Development-optimized Builds

- Start the browser extension for webkit browsers (tested mostly on Chrome and Brave):

  ```bash
  yarn web:webkit
  ```

  Then follow the instructions to load an unpacked extension [here](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked).

- Start the browser extension for gecko browsers (tested mostly on Firefox):

  ```bash
  yarn web:gecko
  ```

  Then follow the instructions to temporarily install an extension in Firefox [here](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/).

- Start the browser extension for the Safari browser:

  ```bash
  yarn web:safari
  ```

  Two new folders will be created:

  - build/safari-dev (dev build folder)
  - safari-extension/wallet-dev (Xcode project)

  then in the Safari browser:

  - Developer -> Developer settings...
  - Check the “Allow unsigned extensions” option. (Note: This setting may not persist after Safari is restarted.)​
  - Then the extension should be automatically added and pinned in the browser.

  NOTE: You can manage the available extensions from: Safari -> Settings... -> Extensions

  NOTE: The development script for Safari relies on the fswatch tool to automatically reload the Safari build when the development server is reloaded. If fswatch is not already installed on your system, you can install it using Homebrew with the following command:

  ```bash
  brew install fswatch
  ```

### Production-optimized Builds

- For webkit browsers:

  ```bash
  yarn build:web:webkit
  ```

  And find the resulting build in the "build/webkit-prod" folder.

- For gecko browsers:

  ```bash
  yarn build:web:gecko
  ```

  And find the resulting build in the "build/gecko-prod" folder.

- For the Safari browser:

  ```bash
  yarn build:web:safari
  ```

  Two new folders will be created:

  - "build/safari-prod" (production build folder)
  - "safari-extension/wallet" (the Xcode project)

  Then, in xCode manually do (TODO: automate these steps, it turned out to be a huge challenge):

  - Delete "walletTests" and "walletUITests" targets.
  - For both targets (macOS and extension): Signing & Capabilities: Team: "Ambire Tech Ltd", Signing Certificate: Development
  - For both targets (macOS and extension): General - Identity - Version: X.X (should match the version in the app.json file, example: `4.36`) and Build: X (integer, bump up on every next build submitted to the App Store Connect, example: `3`)
  - For the macOS target: General - App Category: "Utilities"
  - For the extension target: General - Identity - Bundle Identifier: `com.ambire.app.wallet.extension`

### LavaMoat Policy Generation

The extension uses [LavaMoat](https://github.com/LavaMoat/LavaMoat) with SES (Secure EcmaScript) to harden the background service worker. LavaMoat uses a policy file (`lavamoat/webpack/policy.json`) to control which packages can import what and access which globals.

#### When to Regenerate Policy

Regenerate the policy when:

- Adding/removing dependencies
- Updating dependencies that change their import patterns
- Runtime errors: "Policy does not allow importing X from Y"
- Runtime errors: "Policy does not allow accessing global X"

Do NOT regenerate for:

- Every build (policy is stable and should be version-controlled)
- Code changes that don't affect dependencies
- UI changes (UI chunks are unlocked and don't use policy)

#### Policy Generation Workflow

1. **Generate policy:**

   ```bash
   yarn build:extensions:generate-policy
   ```

2. **Review generated policy:**

   - Check `lavamoat/webpack/policy.json` for any unexpected entries
   - Review package dependencies and global access patterns

3. **Update policy overrides:**

   - Manually edit `lavamoat/webpack/policy-override.json` for custom overrides
   - Common overrides: primordial mutations, font packages, reflect-metadata globals

4. **Commit policy files:**

   - Both `policy.json` and `policy-override.json` should be version-controlled
   - This ensures consistent builds across environments

**Note:** The same policy works for both gecko and webkit builds since they share the same dependencies and only differ in entry points (which are mostly unlocked).

### Extract Source Maps

The production-optimized builds come with source maps files included. When preparing a production build for a browser store release, run the following commands to extract the source maps in separate directories:

- For the webkit build:

  ```bash
  yarn export:web:webkit:sourcemaps
  ```

  As a result, build/webkit-prod will no longer include the source map files (as before). Instead, a new folder, build/webkit-prod-source-maps, will be created to hold only the source maps. This folder should also be included in the GitHub release tag we create.

- For the gecko build:

  ```bash
  yarn export:web:gecko:sourcemaps
  ```

  Same as for the webkit build, but for the gecko build.

- For the Safari build: not implemented yet.

For more details, including how to trace /deminify a production reported error, see [#3191](https://github.com/AmbireTech/ambire-app/pull/3191).

### Store-prepared Builds

Automates the steps before every extension extension store release that could be otherwise done manually:

- Makes webkit and gecko extension production builds
- Exports source maps to "clean" the builds (and to prepare for upload those source maps in the GitHub release)
- Zips the "clean" builds (stores accept zips only) and the source maps

```bash
yarn build:extensions
```

And find the resulting zips in the "build" folder as `ambire-extension-<VERSION>-<TYPE>.zip`

### Verifying a Downloaded Release

Releases live at [AmbireTech/extension/releases](https://github.com/AmbireTech/extension/releases). Installing from the [official download page](https://www.ambire.com/get-extension) is the recommended way, because the stores handle signing and updates for you. If you install a `.zip` by hand instead, verify it first.

Applies to **v6.19.2 and later**.

#### Check the signature (recommended)

GitHub signs every release and everything attached to it, so this proves the file is exactly what we published and that nobody changed it afterwards. Needs [GitHub CLI](https://cli.github.com/) 2.81 or newer:

```bash
gh release verify-asset v6.19.2 ./ambire-extension-v6.19.2-webkit.zip -R AmbireTech/extension
```

Success looks like `✓ Verification succeeded!`. Anything else means the file does not match the release - do not install it.

#### Or check the hash

If you would rather not install anything, download the `SHA256SUMS` file from the same release, put it next to the `.zip` files, and run:

```bash
sha256sum -c SHA256SUMS --ignore-missing   # macOS: shasum -a 256 -c SHA256SUMS --ignore-missing
```

Every file must print `OK`. This catches a corrupted or swapped download, but only the signature check above proves the file came from us.

Releases before v6.19.2 have neither a signature nor a `SHA256SUMS` file.

## Mobile Apps

The mobile apps share the same codebase, but the business logic (the `background`) runs inside a WebView worker (`src/mobile/modules/webview/services/`) instead of a service worker. That's why every mobile build needs the webview bundle built (or the webview dev server running).

### Install

- For iOS: Make sure you have Xcode + CocoaPods via bundler (see the "Environment Setup" section), then install the pods:

  ```bash
  cd ios && bundle install && bundle exec pod install
  ```

- For Android: Make sure you have Android Studio with the Android SDK and the NDK required by React Native (see "Environment Setup" section).

### Development-optimized Builds

Run the webview dev server in one terminal (the app shows an explicit error screen if it isn't running):

```bash
yarn dev:webview
```

Then, in another terminal, compile a new native build and run it on a simulator/emulator or a connected device:

```bash
yarn ios
# or
yarn android
```

These recompile the native app every time, which is slow. If the app is already installed, only the Metro bundler is needed - start it with a cleared cache and launch the app from the device:

```bash
yarn start:clean
```

A new native build is only needed after changing native code or native dependencies.

#### Webview dev server

It listens on port `8182` and is separate from the Metro bundler (port `8081`), which `yarn ios`/`yarn android` start on their own. The app resolves its host automatically:

| Target           | Host                           |
| ---------------- | ------------------------------ |
| iOS simulator    | `localhost`                    |
| Android emulator | `10.0.2.2`                     |
| Physical device  | `WEBVIEW_DEV_HOST` from `.env` |

On a physical device, set `WEBVIEW_DEV_HOST` to the LAN IP of the machine running the dev server and keep both on the same network.

The error screen prints the exact URL the app expects. The app also keeps re-probing the server and remounts the webview by itself once it is back up, so starting the dev server late doesn't require restarting the app.

### Production-optimized Builds

Both platforms run `yarn build:inject:mobile-ota-config` (seeds the Stallion OTA config into `Info.plist`/`strings.xml`) and `yarn build:webview` before the native build, so no manual prep is needed.

Local production builds are normally **not** OTA-capable: without the `STALLION_*` variables in ".env" the injection is skipped, the committed placeholders stay, and the app never pulls an OTA update. That is fine for testing. Fill them in (see "Over-the-Air (OTA) Updates") only if you specifically need to test the OTA flow locally. In CI they are mandatory - a missing one fails the build instead of shipping an app that silently cannot update.

- iOS, for a simulator (unsigned `.app`, useful for sharing test builds):

  ```bash
  yarn build:ios:simulator
  ```

  Find the result in "ios/build/Build/Products/Release-iphonesimulator/Ambire.app", and install it on the booted simulator with:

  ```bash
  yarn build:ios:simulator:install
  ```

- iOS, for the App Store (signed `.ipa`):

  ```bash
  yarn build:ios:production
  ```

  This archives the app and exports it with "ios/ExportOptions.plist". Find the result in the "ios/build/ipa" folder.

  Requires the Ambire distribution certificate in your keychain and the matching provisioning profile installed.

  For an ad-hoc/development `.ipa` (installable on registered test devices) use `yarn build:ios:production-for-testing`, which exports with "ios/ExportOptions-Development.plist" into "ios/build/ipa-for-testing".

- Android, APK (for testing, easiest to install directly on a device):

  ```bash
  yarn build:android:production:apk
  ```

  Find the result in the "android/app/build/outputs/apk/release" folder. To build, reinstall and restart on a connected device in one go:

  ```bash
  yarn build:android:production:apk:install
  ```

- Android, AAB (for the Play Store):

  ```bash
  yarn build:android:production:aab
  ```

  Find the result in the "android/app/build/outputs/bundle/release" folder.

  NOTE: Locally, release builds are signed with the debug keystore unless a "credentials.json" file with the release keystore details exists in the root directory. That's fine for testing, but a Play Store upload requires the real upload keystore, so use the CI build for store releases.

### CI Builds (GitHub Actions)

Store-ready artifacts are built in CI, so nobody has to keep signing material locally. All four are manually triggered (`workflow_dispatch`) and upload a zipped artifact named `ambire-<platform>-v<VERSION>-<TYPE>`, where the version is read from "app.json":

| Workflow                      | Yarn command                        | Artifact                     | Signed |
| ----------------------------- | ----------------------------------- | ---------------------------- | ------ |
| 🍎 Build · iOS Simulator      | `yarn build:ios:simulator`          | `Ambire.app`                 | No     |
| 🍎 Build · iOS App Store      | `yarn build:ios:production`         | `Ambire.ipa`                 | Yes    |
| 🤖 Build · Android APK        | `yarn build:android:production:apk` | `Ambire.apk` (arm64-v8a)     | No     |
| 🤖 Build · Android Play Store | `yarn build:android:production:aab` | `Ambire.aab` (+ armeabi-v7a) | Yes    |

The shared steps live in `.github/workflows/_build-ios.yml` and `.github/workflows/_build-android.yml`. The signing material (Apple certificate and provisioning profile, Android upload keystore), the Stallion OTA credentials and all API keys come from the GitHub environment.

### Over-the-Air (OTA) Updates

JS-only changes can be shipped to already installed apps without a store release, via [Stallion](https://stalliontech.io/). Both the React Native bundle and the webview worker bundle (the `background`) ride the OTA, so the core business logic can be updated too.

A build can only receive OTA updates if it was made with the Stallion credentials in place: `yarn build:inject:mobile-ota-config` swaps the placeholders in "Info.plist"/"strings.xml" for `STALLION_PROJECT_ID`, `STALLION_APP_TOKEN` and `STALLION_PUBLIC_SIGNING_KEY`. CI always has them, a local ".env" usually doesn't.

NOTE: that injection rewrites the committed "Info.plist" and "strings.xml" in place. Never commit the result - restore them with `git checkout` first.

OTA bundles are signed (RS256), so a tampered bundle cannot reach a device: the app verifies every incoming bundle against the `STALLION_PUBLIC_SIGNING_KEY` embedded into it at build time.

Once an OTA is downloaded, the app shows an "Update Available" banner. The active OTA version and build are listed in Settings - About.

#### Two copies of the webview worker bundle

Every build has the webview worker bundle (the `background`) baked into the app binary. An OTA can only replace JS, never a file inside the binary, so that copy on its own would keep the wallet's core logic frozen at whatever the store build shipped.

That is why the same bundle now travels inside the OTA JS bundle as well. On the first launch after an install or an update, the app writes it out into its own private folder and the WebView loads it from there via `file://`; later launches reuse what is already on disk. If that write ever fails, the app falls back to the copy baked into the binary, so it always has a working bundle to boot from.

Loading from disk keeps the protections the baked-in copy had: the page may only run scripts from `file://` (CSP), and its HTML carries a SHA-384 hash (SRI) pinning the exact JS file it loads, so the two can never drift apart. That hash only proves the HTML and the JS belong together, though - what makes OTA'd code trustworthy in the first place is the signature check above.

## Explorer (Old name: Benzin)

Ambire's transaction explorer, that makes human readable ERC-4337 transactions and contract interactions.

Comes not only as integrated module in the Ambire extension(s), but as a standalone web app also.

### Development-optimized Build

```bash
yarn web:benzin
```

And find the resulting build in the "build/benzin-dev" folder.

### Production-optimized Build

```bash
yarn build:web:benzin
```

And find the resulting build in the "build/benzin-prod" folder.

## Ambire Rewards

Ambire Rewards is a gamified testing web3 app for the Ambire browser extensions. It is designed to users you discover the power of Smart Accounts via an epic onchain adventure. [Read more](https://rewards.ambire.com/).

### Development-optimized Build

```bash
yarn web:legends
```

And find the resulting build in the "build/legends-dev" folder.

```bash
yarn build:web:legends
```

And find the resulting build in the "build/legends-prod" folder.

## Others

### Starting the Ledger Emulator Locally

You can run the Ledger emulator locally for testing purposes. Make sure **Docker** is installed on your machine before proceeding.

#### Steps

1. **Navigate to the emulator folder**:

```bash
cd e2e-playwright-tests/ledger-emulator
```

2. **Start the emulator**:

```bash
$LEDGER_EMULATOR_SEED='<LEDGER-SEED-PHRASE>' ./start-emulator.sh
```

**Note:** Make sure port `5000` is available before starting the emulator.

1. **Check if port 5000 is in use:**

```bash
lsof -i :5000
```

If nothing is returned, the port is free.
If you see a process listed, the port is occupied.

2. **macOS specific context**

On macOS, port 5000 is commonly taken by AirPlay Receiver (enabled by default on newer macOS versions).
To check:

System Settings → General → AirDrop & Handoff → AirPlay Receiver

If enabled, it may bind to port 5000.

You can either:

- Disable AirPlay Receiver, or
- Kill the process manually:

```bash
kill -9 $(lsof -t -i :5000)
```

### Browser Extensions E2E Tests

#### Configuration

We've migrated from Puppeteer to Playwright (./e2e-playwright-tests/). Documentation will follow soon.


---

## 42. remix
- **URL:** https://github.com/devtechedge/remix
- **Language:** TypeScript
- **Topics:** None
- **Description:** The fully-stacked web framework

### README.md

<br />
<br />

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/remix-wordmark-racing-darkmode.svg">
    <img alt="Remix" src=".github/assets/remix-wordmark-racing-lightmode.svg" width="400">
  </picture>
</p>

<br />
<br />

# Welcome to Remix 3!

This is the source repository for Remix 3. It is under active development.

We published [a blog post](https://remix.run/blog/wake-up-remix) earlier this year with some of our thoughts around Remix 3. It explains our philosophy for web development and why we think the time is right for something new. When working on Remix 3, we follow these principles:

1. **Model-First Development**. AI fundamentally shifts the human-computer interaction model for both user experience and developer workflows. Optimize the source code, documentation, tooling, and abstractions for LLMs. Additionally, develop abstractions for applications to use models in the product itself, not just as a tool to develop it.
2. **Build on Web APIs**. Sharing abstractions across the stack greatly reduces the amount of context switching, both for humans and machines. Build on the foundation of Web APIs and JavaScript because it is the only full stack ecosystem.
3. **Religiously Runtime**. Designing for bundlers/compilers/typegen (and any pre-runtime static analysis) leads to poor API design that eventually pollutes the entire system. All packages must be designed with no expectation of static analysis and all tests must run without bundling. Because browsers are involved, `--import` loaders for simple transformations like TypeScript and JSX are permissible.
4. **Avoid Dependencies**. Dependencies lock you into somebody else's roadmap. Choose them wisely, wrap them completely, and expect to replace most of them with our own package eventually. The goal is zero.
5. **Demand Composition**. Abstractions should be single-purpose and replaceable. A composable abstraction is easy to add and remove from an existing program. Every package must be useful and documented independent of any other context. New features should first be attempted as a new package. If impossible, attempt to break up the existing package to make it more composable. However, tightly coupled modules that almost always change together in both directions should be moved to the same package.
6. **Distribute Cohesively**. Extremely composable ecosystems are difficult to learn and use. Remix will be distributed as a single `remix` package for both distribution and documentation.

## Goals

Although we recommend the `remix` package for ease of use, all packages that make up Remix should be usable standalone as well. This forces us to consider package boundaries and helps us define public interfaces that are portable and interoperable.

Each package in Remix:

- Has a [single responsibility](https://en.wikipedia.org/wiki/Single-responsibility_principle)
- Prioritizes web standards to ensure maximum interoperability and portability across JavaScript runtimes
- Augments standards unobtrusively where they are missing or incomplete, minimizing incompatibility risks

This means Remix code is **portable by default**. Remix packages work seamlessly across [Node.js](https://nodejs.org/), [Bun](https://bun.sh/), [Deno](https://deno.com/), [Cloudflare Workers](https://workers.cloudflare.com/), and other environments.

We leverage server-side web APIs when they are available:

- [The Web Streams API](https://developer.mozilla.org/en-US/docs/Web/API/Streams_API) instead of `node:stream`
- [`Uint8Array`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array) instead of Node.js `Buffer`s
- [The Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API) instead of `node:crypto`
- [`Blob`](https://developer.mozilla.org/en-US/docs/Web/API/Blob) and [`File`](https://developer.mozilla.org/en-US/docs/Web/API/File) instead of some bespoke runtime-specific API

The benefit is code that's not just reusable, but **future-proof**.

## Packages

Most packages in this repository are standalone JavaScript/TypeScript tools. The `remix` package composes them under one umbrella for distribution and documentation.

- [assert](packages/assert): Node assert-compatible utilities for any JavaScript environment
- [assets](packages/assets): Fetch-based server for compiling browser JS/TS and CSS assets on demand
- [async-context-middleware](packages/async-context-middleware): Middleware for storing request context in AsyncLocalStorage
- [auth](packages/auth): Browser login, OAuth, and OIDC helpers for Remix
- [auth-middleware](packages/auth-middleware): Pluggable authentication middleware for Remix
- [cli](packages/cli): Command-line interface for Remix
- [compression-middleware](packages/compression-middleware): Middleware for compressing HTTP responses
- [cookie](packages/cookie): A toolkit for working with cookies in JavaScript
- [cop-middleware](packages/cop-middleware): Middleware for tokenless cross-origin protection in Fetch API servers
- [cors-middleware](packages/cors-middleware): Middleware for handling CORS in Fetch API servers
- [csrf-middleware](packages/csrf-middleware): Middleware for CSRF protection in Fetch API servers
- [data-schema](packages/data-schema): Tiny, standards-aligned schema validation
- [data-table](packages/data-table): A typed, relational query toolkit for JavaScript
- [data-table-mysql](packages/data-table-mysql): MySQL database implementation for remix/data-table
- [data-table-postgres](packages/data-table-postgres): PostgreSQL database implementation for remix/data-table
- [data-table-sqlite](packages/data-table-sqlite): SQLite database implementation for remix/data-table
- [fetch-proxy](packages/fetch-proxy): An HTTP proxy for the web Fetch API
- [fetch-router](packages/fetch-router): A minimal, composable router for the web Fetch API
- [file-storage](packages/file-storage): Key/value storage for JavaScript File objects
- [file-storage-s3](packages/file-storage-s3): S3 backend for remix/file-storage
- [form-data-middleware](packages/form-data-middleware): Middleware for parsing FormData from request bodies
- [form-data-parser](packages/form-data-parser): A request.formData() wrapper with streaming file upload handling
- [fs](packages/fs): Filesystem utilities using the Web File API
- [headers](packages/headers): A toolkit for working with HTTP headers in JavaScript
- [html-template](packages/html-template): HTML template tag with auto-escaping for JavaScript
- [lazy-file](packages/lazy-file): Lazy, streaming files for JavaScript
- [logger-middleware](packages/logger-middleware): Middleware for logging HTTP requests and responses
- [method-override-middleware](packages/method-override-middleware): Middleware for overriding HTTP request methods from form data
- [mime](packages/mime): Utilities for working with MIME types
- [multipart-parser](packages/multipart-parser): A fast, efficient parser for multipart streams in any JavaScript environment
- [node-fetch-server](packages/node-fetch-server): Build servers for Node.js using the web fetch API
- [node-hmr](packages/node-hmr): Run Node.js applications with hot module reloading
- [node-tsx](packages/node-tsx): Run Node.js with TypeScript and JSX syntax support
- [remix](packages/remix): The Remix web framework
- [response](packages/response): Response helpers for the web Fetch API
- [route-pattern](packages/route-pattern): Match and generate URLs with strong typing
- [session](packages/session): Session management for JavaScript
- [session-middleware](packages/session-middleware): Middleware for managing sessions with cookie-based storage
- [session-storage-memcache](packages/session-storage-memcache): Memcache session storage for remix/session
- [session-storage-redis](packages/session-storage-redis): Redis session storage for remix/session
- [static-middleware](packages/static-middleware): Middleware for serving static files from the filesystem
- [tar-parser](packages/tar-parser): A fast, efficient parser for tar streams in any JavaScript environment
- [terminal](packages/terminal): Terminal output utilities for JavaScript libraries and CLIs
- [test](packages/test): A test framework for JavaScript and TypeScript projects
- [ui](packages/ui): View layer with reconciler, component model, and first-party UI components
- [ui-hmr](packages/ui-hmr): Hot module replacement runtime and transforms for Remix UI components

## Installation

To try the current Remix beta, install the `next` dist-tag:

```sh
npm install remix@next
```

To create a new Remix app with the CLI, use `npx remix@next new`:

```sh
npx remix@next new my-remix-app
```

If you want to play around with the bleeding edge, we also build the latest `main` branch into a `preview/main` branch which can be [installed directly](https://pnpm.io/package-sources#install-from-a-git-repository-combining-different-parameters) with `pnpm` (version 9+):

```sh
pnpm install "remix-run/remix#preview/main&path:packages/remix"
```

Or, just install a single package:

```
pnpm install "remix-run/remix#preview/main&path:packages/fetch-router"
```

## Agent Skills For Building Apps

Agents that are starting a Remix 3 app from this repository should use the [`remix` app skill](./.agents/skills/remix/SKILL.md). The CLI prepack step copies this skill into the app template so generated apps can use the same guidance.

## Contributing

We welcome contributions! If you'd like to contribute, please feel free to open an issue or submit a pull request. See [CONTRIBUTING](https://github.com/remix-run/remix/blob/main/CONTRIBUTING.md) for more information.

## License

See [LICENSE](https://github.com/remix-run/remix/blob/main/LICENSE)


---

## 43. nest
- **URL:** https://github.com/devtechedge/nest
- **Language:** TypeScript
- **Topics:** None
- **Description:** A progressive Node.js framework for building efficient, scalable, and enterprise-grade server-side applications with TypeScript/JavaScript ≡ƒÜÇ

### README.md

<p align="center">
  <a href="https://nestjs.com/" target="_blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="https://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://github.com/nestjs/nest/blob/master/LICENSE" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

Nest is a framework for building efficient, scalable <a href="https://nodejs.org" target="_blank">Node.js</a> server-side applications. It uses modern JavaScript, is built with <a href="https://www.typescriptlang.org" target="_blank">TypeScript</a> (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

<p>Under the hood, Nest makes use of <a href="https://expressjs.com/" target="_blank">Express</a>, but also provides compatibility with a wide range of other libraries, like <a href="https://github.com/fastify/fastify" target="_blank">Fastify</a>, allowing for easy use of the myriad of third-party plugins which are available.</p>

## Philosophy

<p>In recent years, thanks to Node.js, JavaScript has become the “lingua franca” of the web for both front-end and back-end applications, giving rise to awesome projects like <a href="https://angular.dev/" target="_blank">Angular</a>, <a href="https://react.dev/" target="_blank">React</a>, and <a href="https://vuejs.org/" target="_blank">Vue</a>, which improve developer productivity and enable the construction of fast, testable, and extensible frontend applications. However, on the server-side, while there are a lot of superb libraries, helpers, and tools for Node, none of them effectively solve the main problem - the architecture.</p>
<p>Nest aims to provide an application architecture out of the box which allows for effortless creation of highly testable, scalable, and loosely coupled and easily maintainable applications. The architecture is heavily inspired by Angular.</p>

## Getting started

- To check out the [guide](https://docs.nestjs.com), visit [docs.nestjs.com](https://docs.nestjs.com). :books:
- 要查看中文 [指南](readme_zh.md), 请访问 [docs.nestjs.cn](https://docs.nestjs.cn). :books:
- [가이드](readme_kr.md) 문서는 [docs.nestjs.com](https://docs.nestjs.com)에서 확인하실 수 있습니다. :books:
- [ガイド](readme_jp.md)は [docs.nestjs.com](https://docs.nestjs.com)でご確認ください。 :books:

## Questions

For questions and support please use the official [Discord channel](https://discord.gg/G7Qnnhy). The issue list of this repo is **exclusively** for bug reports and feature requests.

## Issues

Please make sure to read the [Issue Reporting Checklist](https://github.com/nestjs/nest/blob/master/CONTRIBUTING.md#-submitting-an-issue) before opening an issue. Issues not conforming to the guidelines may be closed immediately.

## Consulting

With official support, you can get expert help straight from the Nest core team. We provide dedicated technical support, migration strategies, advice on best practices (and design decisions), PR reviews, and team augmentation. Read more about [support here](https://enterprise.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support from the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

#### Principal Sponsors

<table style="text-align:center;">
<tr>
<td><a href="https://trilon.io" target="_blank"><img src="https://nestjs.com/img/github/trilon-logo.svg" width="200" valign="middle" /></a></td>
<td><a href="https://microsoft.com/" target="_blank"><img src="https://nestjs.com/img/github/microsoft-logo.png" width="180" valign="middle" /></a></td>
<td><a href="https://mojam.co" target="_blank"><img src="https://images.opencollective.com/mojamco/981e9de/logo/256.png?height=256" width="80" valign="middle" /></a></td>
<td><a href="https://valor-software.com/" target="_blank"><img src="https://docs.nestjs.com/assets/sponsors/valor-software.png" width="170" valign="middle" /></a></td>
<td><a href="https://serpapi.com/" target="_blank"><img src="https://nestjs.com/img/github/serpapi-logo.png" width="150" valign="middle" /></a></td>
</tr>
</table>

#### Gold Sponsors

<table style="text-align:center;">
<tr>
<td><a href="https://www.redhat.com" target="_blank"><img src="https://nestjs.com/img/github/red-hat-logo.svg" width="150" valign="middle" /></a></td>
<td><a href="https://github.com/Sanofi-IADC" target="_blank"><img src="https://docs.nestjs.com/assets/sponsors/sanofi.png" width="120" valign="middle" /></a></td>
<td><a href="https://nx.dev" target="_blank"><img src="https://nestjs.com/img/github/nx-logo.png" height="45" valign="middle" /></a></td>
<td><a href="https://intrinsic.ventures/" target="_blank"><img src="https://nestjs.com/img/github/intrinisic-logo.png" width="150" valign="middle" /></a></td>
<td><a href="https://jetbrains.com/" target="_blank"><img src="https://nestjs.com/img/github/jetbrains-logo.svg" width="70" valign="middle" /></a></td>
</tr>
<tr>
<td><a href="https://snyk.co/nestjs" target="_blank"><img src="https://nestjs.com/img/github/snyk-logo-black.png" width="125" valign="middle" /></a></td>
<td align="center"><a href="https://www.movavi.com/imovie-for-windows.html" target="_blank"><img src="https://images.opencollective.com/movavi/1fb15e5/avatar/256.png?height=256" width="60" valign="middle" /></a></td>
</tr>
</table>

#### Silver Sponsors

<table style="text-align:center;">
<tr>
<td><a href="https://www.mercedes-benz.com/" target="_blank"><img src="https://nestjs.com/img/github/mercedes-logo.png" width="100" valign="middle" /></a></td>
<td><a href="https://handsontable.com/docs/react-data-grid/?utm_source=NestJS_GH&utm_medium=sponsorship&utm_campaign=library_sponsorship_2024" target="_blank"><img src="https://nestjs.com/img/github/handsontable-dark-logo.svg#2" width="150" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://www.itflashcards.com/" target="_blank"><img src="https://nestjs.com/img/github/it_flashcards-logo.png" width="170" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://arcjet.com/?ref=nestjs" target="_blank"><img src="https://nestjs.com/img/github/arcjet-logo.svg" width="170" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://pandektes.com" target="_blank"><img src="https://nestjs.com/img/github/pandektes-logo.png" width="65" valign="middle" /></a></td>
</tr><tr>
<td align="center" valign="middle"><a href="https://www.fintechcrafts.com/" target="_blank"><img src="https://opencollective-production.s3.us-west-1.amazonaws.com/account-avatar/935813df-48a9-4b41-b923-7d70b5621c6b/2026-05-06%2010%2021%2033.png" width="65" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://talordata.com/?campaignid=Ya5Xpw2gmhyee6Tg&utm_source=nestjs&utm_term=nestjs" target="_blank"><img src="https://images.opencollective.com/elowen/9ccac7f/avatar/512.png" width="65" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://memory2.co/" target="_blank"><img src="https://images.opencollective.com/memory-squared/bbe37f5/avatar/256.png?height=50" width="65" valign="middle" /></a></td>
</tr>
</table>

#### Sponsors

<table>
<tr>
<td align="center" valign="middle"><a href="https://mantro.net/" target="_blank"><img src="https://nestjs.com/img/github/mantro-logo.svg" width="95" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://triplebyte.com/" target="_blank"><img src="https://nestjs.com/img/github/triplebyte-logo.png" width="107" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://nearpod.com/" target="_blank"><img src="https://nestjs.com/img/github/nearpod-logo.svg" width="100" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://www.naologic.com/" target="_blank"><img src="https://nestjs.com/img/github/naologic-logo.svg" width="125" valign="middle" /></a></td>
<td align="center" valign="middle"><a href="https://triplecore.io" target="_blank"><img src="https://nestjs.com/img/github/triplecore-logo.svg" width="50" valign="middle" /></a>
<td align="center" valign="middle"><a href="https://www.hingehealth.com/" target="_blank"><img src="https://nestjs.com/img/github/hinge-health-logo.svg" width="100" valign="middle" /></a></td>
</tr>
</table>

## Backers

<a href="https://opencollective.com/nest" target="_blank"><img src="https://opencollective.com/nest/backers.svg?width=1000"></a>

## Stay in touch

- Author - [Kamil Myśliwiec](https://x.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- X - [@nestframework](https://x.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).


---

## 44. dotnet-stellar-sdk
- **URL:** https://github.com/devtechedge/dotnet-stellar-sdk
- **Language:** C#
- **Topics:** None
- **Description:** Stellar API SDK for .NET 8

### README.md

<p align="center">
    <img height="200" src="https://raw.githubusercontent.com/Beans-BV/dotnet-stellar-sdk/main/docfx/images/logo.svg">
    <h3 align="center">dotnet-stellar-sdk</h3>
    <p align="center">
        Stellar API SDK for .NET
        <br /> 
        <a href="https://github.com/Beans-BV/dotnet-stellar-sdk/actions/workflows/pack_and_test.yml">
            <img src="https://github.com/Beans-BV/dotnet-stellar-sdk/actions/workflows/pack_and_test.yml/badge.svg?branch=main">
        </a>
        <a href="https://www.nuget.org/packages/stellar-dotnet-sdk">
            <img src="https://img.shields.io/nuget/v/stellar-dotnet-sdk.svg" />
        </a>
        <a href="https://www.nuget.org/packages/stellar-dotnet-sdk">
            <img src="https://img.shields.io/nuget/dt/stellar-dotnet-sdk.svg" />
        </a>
        <br />
        <a href="https://github.com/Beans-BV/dotnet-stellar-sdk/issues/new?template=Bug_report.md">Report Bug</a> · 
        <a href="https://github.com/Beans-BV/dotnet-stellar-sdk/issues/new?template=Feature_request.md">Request Feature</a> · 
        <a href="https://github.com/Beans-BV/dotnet-stellar-sdk/security/policy">Report Security Vulnerability</a> 
    </p>
</p>

## About The Project

`dotnet-stellar-sdk` is a .NET library for communicating with
a [Stellar Horizon server](https://github.com/stellar/go/tree/master/services/horizon)
or [Stellar RPC server](https://developers.stellar.org/docs/data/apis/rpc).

It is used for building Stellar apps.

_This project originated as a full port of the
official [Java SDK API](https://github.com/lightsail-network/java-stellar-sdk)._

_The SEP (Stellar Ecosystem Proposal) protocol implementations were ported from the
[Flutter SDK](https://github.com/Soneso/stellar_flutter_sdk)._

## Features

- **Built-in HTTP resilience for Stellar** - Opt-in retries for 408/429/5xx tuned for Horizon (`ForHorizon()`) and Stellar RPC / Soroban (`ForSoroban()`), with `Retry-After` honored (capped by `MaxRetryAfterDelay`, default 1 minute)
- **Configurable** - Customize retry count, delays, jitter, status codes, and method filter
- **Full Stellar Support** - Works with both Horizon API and Stellar RPC servers

## Installation

The `stellar-dotnet-sdk` library is bundled in a NuGet package.

- [NuGet Package](https://www.nuget.org/packages/stellar-dotnet-sdk)

### Visual Studio

- Using the [console](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-powershell)
    - Run `Install-Package stellar-dotnet-sdk` in the console.
- Using
  the [NuGet Package Manager](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-visual-studio)
    - Search this package [NuGet Package](https://www.nuget.org/packages/stellar-dotnet-sdk) and install it.

### JetBrains Rider

- [Using NuGet in Rider](https://www.jetbrains.com/help/rider/Using_NuGet.html)

### Other

- [Ways to install a NuGet package](https://docs.microsoft.com/en-us/nuget/consume-packages/overview-and-workflow#ways-to-install-a-nuget-package)

## Platform support

The `stellar-dotnet-sdk` and `stellar-dotnet-sdk-xdr` packages multi-target the following frameworks:

| Target framework | Typical platforms | Crypto backend |
|------------------|-------------------|----------------|
| `net10.0` | .NET 10 apps | NSec |
| `net8.0` | .NET 8 apps | NSec |
| `netstandard2.1` | Unity 6, Unity 2022.3 (see compiler note below), Tizen 5.5+, portable libraries | Sodium.Core |

NuGet resolves the best matching assembly for your project automatically.

### TFM-specific API notes

- **SEP-0009 date fields** (`BirthDate`, `IdIssueDate`, `IdExpirationDate`, `RegistrationDate`): `DateOnly?` on `net8.0` / `net10.0`; `string?` (ISO `yyyy-MM-dd`) on `netstandard2.1`. JSON wire format is identical across TFMs.
- **Synchronous `HttpClient.Send` resilience**: on `net8.0` / `net10.0`, `RetryingHttpMessageHandler` overrides sync `Send` with the full retry pipeline. On the `netstandard2.1` assembly (also what `net5`–`net7` apps resolve), sync `Send` throws `NotSupportedException` instead of silently bypassing retries — use `SendAsync`.
- **Unity compiler note (`required` members)**: many SDK request/response models declare C# `required` members. Constructing them from *your* code needs a compiler that understands `required`: Unity 6 qualifies; Unity 2022.3's bundled compiler (Roslyn 4.1) does not — member initialization of those types fails to compile there unless you upgrade the compiler (e.g. [UnityRoslynUpdater](https://github.com/DaZombieKiller/UnityRoslynUpdater)). Deserialization and APIs without `required` members are unaffected.

### Examples

The SDK includes numerous example applications showcasing its features. Explore these standalone projects:

- [Horizon Examples](https://github.com/Beans-BV/dotnet-stellar-sdk/tree/master/Examples/Horizon/HorizonExamples.cs)
- [Soroban Examples](https://github.com/Beans-BV/dotnet-stellar-sdk/tree/master/Examples/Soroban/SorobanExamples.cs)

### HTTP retry & resilience

The SDK ships with opt-in retry support tuned for Stellar's HTTP surfaces (Horizon and Stellar RPC).
Pick the preset that matches the server you're calling:

```csharp
// For Horizon — GET queries and SubmitTransaction()
var resilience = HttpResilienceOptionsPresets.ForHorizon();
var server = new Server("https://horizon-testnet.stellar.org", resilience, bearerToken: null);

// For Stellar RPC (Soroban)
var rpcResilience = HttpResilienceOptionsPresets.ForSoroban();
var rpcClient = new DefaultStellarSdkHttpClient(resilienceOptions: rpcResilience);
var rpcServer = new StellarRpcServer("https://soroban-testnet.stellar.org", rpcClient);
```

Both retry HTTP 408, 429, 500, 502, 503, 504 on the Stellar requests they're scoped to (see the
matrix below) with exponential backoff, jitter, and `Retry-After` honored (capped by
`MaxRetryAfterDelay`, default 1 minute). They differ in retry budget and delay range.

#### Which Stellar operations are retried?

`HttpResilienceOptions.RetryHttpMethods` is an explicit whitelist. By default it contains only the
RFC-safe methods (`GET`, `HEAD`, `OPTIONS`). Each preset opts in to the additional methods it needs.

| Stellar operation | HTTP method | Retried by `ForHorizon()` | Retried by `ForSoroban()` |
|---|---|---|---|
| Horizon queries (`Server.Accounts`, `Ledgers`, `Operations`, `Effects`, `Root`, …) | GET | ✅ | ✅ |
| `Server.SubmitTransaction()` / `SubmitTransactionAsync()` | POST | ✅ | n/a |
| Every `StellarRpcServer` method — read (`getLatestLedger`, `simulateTransaction`, `getEvents`, …) or write (`sendTransaction`) | POST | n/a | ✅ |
| SEP-6 `PATCH /transactions/{id}` | PATCH | ❌ | ❌ |

Retrying `SubmitTransaction()` is safe on Stellar even though it is HTTP POST: every envelope is
uniquely keyed by transaction hash plus the source account's sequence number, so a resubmit either
returns the cached server result or fails with `tx_bad_seq` — there is no double-spend window. If
the original submission had already committed when the transient failure occurred, the retry
surfaces `tx_bad_seq` and your code should look up the transaction by its hash to recover the
original result.

> **⚠️ Do not wire `ForHorizon()` or `ForSoroban()` into SEP service clients**
> (`ClientWebAuth`, `InteractiveService`, `TransferServerService`, `StellarToml` with a custom
> `HttpClient`). Specific SEP POST endpoints are **non-idempotent by spec** and silently retrying
> them creates real problems:
>
> - **SEP-10 `POST /auth`** — the spec says: *"The Server should not provide more than one JWT for
>   a specific challenge transaction."* The challenge is one-shot. On transient failure, request a
>   **fresh** challenge — don't resubmit the same body.
> - **SEP-24 `POST /transactions/{deposit,withdraw}/interactive`** — each call mints a fresh
>   `transaction_id`. Retrying creates a duplicate transaction record and an orphaned interactive
>   URL. The spec defines no idempotency-key mechanism.
> - **SEP-6 `PATCH /transactions/{id}`** — not in the SEP-6 master spec; anchor-vendor extension
>   that mutates KYC state. Treat as non-idempotent.
>
> For SEP HttpClients, use `WithConnectionRetries()` (transport retries only) or build a custom
> `HttpResilienceOptions` whose `RetryHttpMethods` contains only `GET`/`HEAD`/`OPTIONS`. Note that
> transport (connection-failure) retries apply to **all** HTTP methods: a POST whose response was
> lost may already have been processed server-side, so even `WithConnectionRetries()` carries a
> small replay window. If that window is unacceptable, use `NoRetry()` and recover at the
> application level (e.g. request a fresh SEP-10 challenge).

#### Presets

- `ForHorizon()` — for the Stellar Horizon API. Retries the transient HTTP status codes on
  Horizon's GET queries and `SubmitTransaction()` POST. 3 retries, 200ms–5s exponential backoff
  with jitter, honors `Retry-After`. PATCH/PUT/DELETE are not retried.
- `ForSoroban()` — for Stellar RPC (Soroban). Same status-code set as `ForHorizon()`; adds POST
  to the retry-method whitelist (every JSON-RPC call is POST). Higher retry budget (5) and longer
  delays (up to 15s) — tuned for long-running polling workflows like `getTransaction(hash)`. For
  latency-sensitive one-off calls (e.g. `simulateTransaction`), override `MaxRetryCount`/`MaxDelay`.
- `WithConnectionRetries()` — transport-level retries only (`HttpRequestException` and timeouts
  thrown inside the handler chain; an `HttpClient.Timeout` cancellation is never retried). No
  status-code retries, but transport retries apply to **all** HTTP methods — see the SEP warning
  above for the replay window this implies on one-shot endpoints.
- `LowLatency()` — minimal retries and short delays (trading bots, latency-sensitive workloads).
- `NoRetry()` — no retries at all.

The retry pipeline observes responses inside the HTTP handler chain, so it triggers
*before* status codes are translated into typed exceptions like `TooManyRequestsException`
and `ServiceUnavailableException`. Those exceptions also expose a
`RetryAfterDelay` (`TimeSpan?`) accessor for direct inspection when needed.

**A note on `Retry-After` for Stellar services.** Horizon sends `Retry-After` only on
HTTP 429 (always as an integer number of seconds); on HTTP 503 it relies on the client's
configured backoff. Stellar RPC (Soroban) does not send `Retry-After` at all, so when it
reports overload as HTTP 503/504 the retry pipeline falls back to exponential backoff. The
parser still accepts the RFC 7231 HTTP-date form because upstream proxies and CDNs
(Cloudflare, nginx, API gateways) may rewrite the header.

**JSON-RPC errors are not retried.** Stellar RPC reports request-scoped failures — an
out-of-range `startLedger`, malformed parameters, a TTL ledger key queried directly — as a
JSON-RPC error body delivered with HTTP status 200. The retry pipeline keys on the status
code, and 200 is not a failure, so these never enter it: neither `RetryHttpStatusCodes` nor
`AdditionalRetriableExceptionTypes` can reach them and no backoff applies. They surface as
`SorobanRpcException`, carrying the server's own error code and message, and are meant to be
handled at the call site.

## Documentation

Documentation is available [here](https://beans-bv.github.io/dotnet-stellar-sdk/).

## Community & Support

- [Stellar Stack Exchange](https://stellar.stackexchange.com/)
- [Keybase Team](https://keybase.io/team/stellar_dotnet)
- [Stellar Developers on Discord](https://discord.com/invite/stellardev)

## Contributing

For information on how to contribute, please refer to
our [contribution guide](https://github.com/Beans-BV/dotnet-stellar-sdk/blob/master/CONTRIBUTING.md).

## License

`dotnet-stellar-sdk` is licensed under an Apache-2.0 license. See
the [LICENSE](https://github.com/Beans-BV/dotnet-stellar-sdk/blob/master/LICENSE.txt) file for details.


---

## 45. biome
- **URL:** https://github.com/devtechedge/biome
- **Language:** Rust
- **Topics:** None
- **Description:** A toolchain for web projects, aimed to provide functionalities to maintain them. Biome offers formatter and linter, usable via CLI and LSP.

### README.md

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/biomejs/resources/main/svg/slogan-dark-transparent.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/biomejs/resources/main/svg/slogan-light-transparent.svg">
    <img alt="Shows the banner of Biome, with its logo and the phrase 'Biome - Toolchain of the web'." src="https://raw.githubusercontent.com/biomejs/resources/main/svg/slogan-light-transparent.svg" width="700">
  </picture>

  <br>
  <br>

  [![CI on main][ci-badge]][ci-url]
  [![Discord chat][discord-badge]][discord-url]
  [![npm version][npm-badge]][npm-url]
  [![VSCode version][vscode-badge]][vscode-url]
  [![Open VSX version][open-vsx-badge]][open-vsx-url]

  [ci-badge]: https://github.com/biomejs/biome/actions/workflows/main.yml/badge.svg
  [ci-url]: https://github.com/biomejs/biome/actions/workflows/main.yml
  [discord-badge]: https://badgen.net/discord/online-members/BypW39g6Yc?icon=discord&label=discord&color=60a5fa
  [discord-url]: https://biomejs.dev/chat
  [npm-badge]: https://npmx.dev/api/registry/badge/version/@biomejs/biome?color=60a5fa&style=shieldsio&label=%40biomejs%2Fbiome
  [npm-url]: https://npmx.dev/package/@biomejs/biome
  [vscode-badge]: https://img.shields.io/visual-studio-marketplace/v/biomejs.biome?label=Visual%20Studio%20Marketplace&labelColor=374151&color=60a5fa
  [vscode-url]: https://marketplace.visualstudio.com/items?itemName=biomejs.biome
  [open-vsx-badge]: https://img.shields.io/visual-studio-marketplace/v/biomejs.biome?label=Open%20VSX%20Registry&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPHN2ZyB2aWV3Qm94PSI0LjYgNSA5Ni4yIDEyMi43IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogIDxwYXRoIGQ9Ik0zMCA0NC4yTDUyLjYgNUg3LjN6TTQuNiA4OC41aDQ1LjNMMjcuMiA0OS40em01MSAwbDIyLjYgMzkuMiAyMi42LTM5LjJ6IiBmaWxsPSIjYzE2MGVmIi8+CiAgPHBhdGggZD0iTTUyLjYgNUwzMCA0NC4yaDQ1LjJ6TTI3LjIgNDkuNGwyMi43IDM5LjEgMjIuNi0zOS4xem01MSAwTDU1LjYgODguNWg0NS4yeiIgZmlsbD0iI2E2MGVlNSIvPgo8L3N2Zz4=&labelColor=374151&color=60a5fa
  [open-vsx-url]: https://open-vsx.org/extension/biomejs/biome

<!-- Insert new entries lexicographically by language code.
     For example given below is the same order as these files appear on page:
     https://github.com/biomejs/biome/tree/main/packages/@biomejs/biome -->

  [हिन्दी](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.hi.md) | English | [Español](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.es.md) | [Français](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.fr.md) | [繁體中文](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.zh-TW.md) | [简体中文](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.zh-CN.md) | [日本語](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.ja.md) | [Polski](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.pl.md) | [Português do Brasil](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.pt-BR.md) | [한국어](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.kr.md) | [Русский](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.ru.md) | [Українська](https://github.com/biomejs/biome/blob/main/packages/%40biomejs/biome/README.uk.md)
</div>

<br>

**Biome** is a performant toolchain for web projects, it aims to provide developer tools to maintain the health of said projects.

**Biome is a [fast formatter](https://github.com/biomejs/benchmark#formatting)** for _JavaScript_, _TypeScript_, _JSX_, _JSON_, _CSS_ and _GraphQL_ that scores **[97% compatibility with _Prettier_](https://algora.io/challenges/prettier)**.

**Biome is a [performant linter](https://github.com/biomejs/benchmark#linting)** for _JavaScript_, _TypeScript_, _JSX_, _JSON_, _CSS_, and _GraphQL_ that features **[more than 500 rules](https://biomejs.dev/linter/javascript/rules/)** from ESLint, typescript-eslint, and [other sources](https://github.com/biomejs/biome/discussions/3).
It **outputs detailed and contextualized diagnostics** that help you to improve your code and become a better programmer!

**Biome** is designed from the start to be used [interactively within an editor](https://biomejs.dev/editors/first-party-extensions/).
It can format and lint malformed code as you are writing it.

### Installation

```shell
npm install --save-dev --save-exact @biomejs/biome
```

### Usage

```shell
# format files
npx @biomejs/biome format --write

# lint files and apply the safe fixes
npx @biomejs/biome lint --write

# run format, lint, etc. and apply the safe fixes
npx @biomejs/biome check --write

# check all files against format, lint, etc. in CI environments
npx @biomejs/biome ci
```

If you want to give Biome a run without installing it, use the [online playground](https://biomejs.dev/playground/), compiled to WebAssembly.

## Documentation

Check out our [homepage][biomejs] to learn more about Biome,
or directly head to the [Getting Started guide][getting-started] to start using Biome.

## More about Biome

**Biome** has sane defaults and it doesn't require configuration.

**Biome** aims to support [all main languages][language-support] of modern web development.

**Biome** [doesn't require Node.js](https://biomejs.dev/guides/manual-installation/) to function.

**Biome** has first-class LSP support, with a sophisticated parser that represents the source text in full fidelity and top-notch error recovery.

**Biome** wants to offer a high-quality *Developer Experience*, with descriptive diagnostics and great performance.

**Biome** unifies functionalities that have previously been separate tools. Building upon a shared base allows us to provide a cohesive experience for processing code, displaying errors, parallelize work, caching, and configuration.

Read more about our [project philosophy][biome-philosophy].

**Biome** is [MIT licensed](https://github.com/biomejs/biome/tree/main/LICENSE-MIT) or [Apache 2.0 licensed](https://github.com/biomejs/biome/tree/main/LICENSE-APACHE) and moderated under the [Contributor Covenant Code of Conduct](https://github.com/biomejs/biome/tree/main/CODE_OF_CONDUCT.md).

## Funding

You can fund the project in different ways

### Project sponsorship and funding

You can sponsor or fund the project via [Open collective](https://opencollective.com/biome) or [GitHub sponsors](https://github.com/sponsors/biomejs)

Biome offers a simple sponsorship program that allows companies to get visibility and recognition among various developers.

Biome offers [enterprise support](https://biomejs.dev/enterprise), where Core Contributors can be employed to work on company-focused projects.

## Sponsors

### Platinum Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://depot.dev/?utm_source=biome&utm_medium=readme" target="_blank">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://depot.dev/assets/brand/horizontal/depot-logo-horizontal-on-light-x3.png" />
            <source media="(prefers-color-scheme: dark)" srcset="https://depot.dev/assets/brand/horizontal/depot-logo-horizontal-on-dark-x3.png" />
            <img src="https://depot.dev/assets/brand/horizontal/depot-logo-horizontal-on-light-x3.png" width="600" alt="Depot logo" />
          </picture>
        </a>
      </td>
    </tr>
  </tbody>
</table>

### Gold Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://codspeed.io/?utm_source=biome&utm_medium=readme" target="_blank">
          <picture>
            <source media="(prefers-color-scheme: light)" srcset="https://biomejs.dev/_astro/codspeed-logo-light.NPF02X9E.svg" />
            <source media="(prefers-color-scheme: dark)" srcset="https://biomejs.dev/_astro/codspeed-logo-dark.DqfyMRf2.svg" />
            <img src="https://biomejs.dev/_astro/codspeed-logo-light.NPF02X9E.svg" width="300" alt="CodSpeed logo" />
          </picture>
        </a>
      </td>
    </tr>
  </tbody>
</table>

### Silver Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://lokalise.com/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/14294501?s=200&v=4" height="100" alt="Lokalise logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://latitude.so/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/98949449?s=200&v=4" height="100" alt="Latitude logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.cloudflare.com/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/314135?s=200&v=4" height="100" alt="Cloudflare logo"></a>
      </td>
    </tr>
  </tbody>
</table>

### Bronze Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://vital.io/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/25357309?s=200" width="80" alt="Vital logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://coderabbit.ai/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/132028505?s=200&v=4" width="80" alt="CodeRabbit logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://forge42.dev/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/161314831?s=200&v=4" width="80" alt="Forge42 logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="http://rstudio.org/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/513560?s=200&v=4" width="80" alt="RStudio logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://pennylane.com/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/57875210?s=200&v=4" width="80" alt="Pennylane logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://jetbrains.com/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://resources.jetbrains.com/storage/products/company/brand/logos/jetbrains.png" width="100" alt="JetBrains logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.egstock.co.jp/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://images.opencollective.com/egstock/b18c836/logo/256.png?height=256" width="80" alt="EGSTOCK, Inc. logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.convex.dev/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/81530787?s=200&v=4" width="80" alt="Convex logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://graphite.dev/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/61942612?s=200&v=4" width="80" alt="Graphite logo"></a>
      </td>
      <td align="center" valign="middle">
        <a href="https://kraken.tech/?utm_source=biome&utm_medium=readme" target="_blank"><img src="https://avatars.githubusercontent.com/u/105941848?s=200&v=4" width="80" alt="Kraken Tech logo"></a>
      </td>
    </tr>
  </tbody>
</table>

[biomejs]: https://biomejs.dev/
[biome-philosophy]: https://biomejs.dev/internals/philosophy/
[language-support]: https://biomejs.dev/internals/language-support/
[getting-started]: https://biomejs.dev/guides/getting-started/


---

## 46. job-board
- **URL:** https://github.com/devtechedge/job-board
- **Language:** TypeScript
- **Topics:** ats, greenhouse, job-board, postgres, tanstack, typescript, vercel, ashby, job-search, lever, public-api, react
- **Description:** Jobrow indexes still-open US tech roles from public Greenhouse, Ashby, and Lever board APIs. 50 companies, 5,000+ open roles. Table-first search, same-day close when a board drops a posting. TanStack Start, TypeScript, Neon Postgres. Independent index ΓÇö not an employer or agency.

### README.md

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


---

## 47. vitest
- **URL:** https://github.com/devtechedge/vitest
- **Language:** TypeScript
- **Topics:** None
- **Description:** Next generation testing framework powered by Vite.

### README.md

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


---

## 48. langgraphjs
- **URL:** https://github.com/devtechedge/langgraphjs
- **Language:** TypeScript
- **Topics:** None
- **Description:** Framework to build resilient language agents as graphs.

### README.md

<div align="center">
  <a href="https://www.langchain.com/langgraph">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/langchain-ai/langgraphjs/HEAD/.github/images/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/langchain-ai/langgraphjs/HEAD/.github/images/logo-light.svg">
      <img alt="LangGraph Logo" src="https://raw.githubusercontent.com/langchain-ai/langgraphjs/HEAD/.github/images/logo-dark.svg" width="50%">
    </picture>
  </a>
</div>

<div align="center">
  <h3>Low-level orchestration framework for building stateful agents.</h3>
</div>

<div align="center">
  <a href="https://docs.langchain.com/oss/javascript/langgraph/overview" target="_blank"><img src="https://img.shields.io/badge/docs-latest-blue" alt="Docs"></a>
  <a href="https://www.npmjs.com/package/@langchain/langgraph" target="_blank"><img src="https://img.shields.io/npm/v/@langchain/langgraph?logo=npm" alt="Version"></a>
  <a href="https://www.npmjs.com/package/@langchain/langgraph" target="_blank"><img src="https://img.shields.io/npm/dm/@langchain/langgraph" alt="npm - Downloads"></a>
  <a href="https://github.com/langchain-ai/langgraphjs/issues" target="_blank"><img src="https://img.shields.io/github/issues-raw/langchain-ai/langgraphjs" alt="Open Issues"></a>
</div>

LangGraph — used by Replit, Uber, LinkedIn, GitLab and more — is a low-level orchestration framework for building controllable agents. While langchain provides integrations and composable components to streamline LLM application development, the LangGraph library enables agent orchestration — offering customizable architectures, long-term memory, and human-in-the-loop to reliably handle complex tasks.

```bash
npm install @langchain/langgraph @langchain/core
```

> [!TIP]
> If you're looking to quickly build agents, check out **[Deep Agents](https://docs.langchain.com/oss/javascript/deepagents/overview)** — a higher-level package built on LangGraph for agents that can plan, use subagents, and leverage file systems for complex tasks.

For an equivalent Python library, check out [LangGraph](https://github.com/langchain-ai/langgraph) and the [Python docs](https://docs.langchain.com/oss/python/langgraph/overview).

## Why use LangGraph?

LangGraph provides low-level supporting infrastructure for *any* long-running, stateful workflow or agent:

- **[Durable execution](https://docs.langchain.com/oss/javascript/langgraph/durable-execution)** — Build agents that persist through failures and can run for extended periods, automatically resuming from exactly where they left off.
- **[Human-in-the-loop](https://docs.langchain.com/oss/javascript/langgraph/interrupts)** — Seamlessly incorporate human oversight by inspecting and modifying agent state at any point during execution.
- **[Comprehensive memory](https://docs.langchain.com/oss/javascript/langgraph/memory)** — Create truly stateful agents with both short-term working memory for ongoing reasoning and long-term persistent memory across sessions.
- **[Debugging with LangSmith](https://www.langchain.com/langsmith)** — Gain deep visibility into complex agent behavior with visualization tools that trace execution paths, capture state transitions, and provide detailed runtime metrics.
- **[Production-ready deployment](https://docs.langchain.com/langsmith/deployments)** — Deploy sophisticated agent systems confidently with scalable infrastructure designed to handle the unique challenges of stateful, long-running workflows.

> [!TIP]
> For developing, debugging, and deploying AI agents and LLM applications, see [LangSmith](https://docs.langchain.com/langsmith/home).

## LangGraph’s ecosystem

While LangGraph can be used standalone, it also integrates seamlessly with any LangChain product, giving developers a full suite of tools for building agents. To improve your LLM application development, pair LangGraph with:

- [Deep Agents (JS)](https://docs.langchain.com/oss/javascript/deepagents/overview) — Build agents that can plan, use subagents, and leverage file systems for complex tasks. A higher-level package built on top of LangGraph.
- [LangChain](https://docs.langchain.com/oss/javascript/langchain/overview) – Provides integrations and composable components to streamline LLM application development.
- [LangSmith](http://www.langchain.com/langsmith) — Helpful for agent evals and observability. Debug poor-performing LLM app runs, evaluate agent trajectories, gain visibility in production, and improve performance over time.

## Additional resources

- [LangChain Forum](https://forum.langchain.com/): Connect with the community and share all of your technical questions, ideas, and feedback.
- [LangChain Academy](https://academy.langchain.com/courses/intro-to-langgraph): Learn the basics of LangGraph in our free, structured course.
- [Streaming Cookbook](https://github.com/langchain-ai/streaming-cookbook): Documentation and examples around LangGraphs's streaming capabilities.
- [API Reference](https://reference.langchain.com/javascript/langchain-langgraph): Detailed reference on core classes, methods, how to use the graph and checkpointing APIs, and higher-level prebuilt components.
- [Built with LangGraph](https://www.langchain.com/built-with-langgraph): Hear how industry leaders use LangGraph to ship powerful, production-ready AI applications.

## Acknowledgements

LangGraph is inspired by [Pregel](https://research.google/pubs/pub37252/) and [Apache Beam](https://beam.apache.org/). The public interface draws inspiration from [NetworkX](https://networkx.org/documentation/latest/). LangGraph is built by LangChain Inc, the creators of LangChain, but can be used without LangChain.


---

## 49. drizzle-orm
- **URL:** https://github.com/devtechedge/drizzle-orm
- **Language:** TypeScript
- **Topics:** None
- **Description:** ORM

### README.md

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


---

## 50. appkit
- **URL:** https://github.com/devtechedge/appkit
- **Language:** TypeScript
- **Topics:** None
- **Description:** The full stack toolkit to build onchain app UX

### README.md

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


---

## 51. js
- **URL:** https://github.com/devtechedge/js
- **Language:** TypeScript
- **Topics:** None
- **Description:** Best in class web3 SDKs for Browser, Node and Mobile apps

### README.md

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


---

## 52. rainbowkit
- **URL:** https://github.com/devtechedge/rainbowkit
- **Language:** MDX
- **Topics:** None
- **Description:** The best way to connect a wallet ≡ƒîê ≡ƒº░

### README.md

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


---

## 53. wagmi
- **URL:** https://github.com/devtechedge/wagmi
- **Language:** TypeScript
- **Topics:** None
- **Description:** Reactive primitives for Ethereum apps

### README.md

<!-- > [!IMPORTANT] -->
<!-- > Wagmi is participating in Gitcoin Grants round 21. Consider <a href="https://explorer.gitcoin.co/#/round/42161/389/74">supporting the project</a>. Thank you. 🙏 -->

<br>

<p align="center">
  <a href="https://wagmi.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/wagmi/main/.github/logo-dark.svg">
      <img alt="wagmi logo" src="https://raw.githubusercontent.com/wevm/wagmi/main/.github/logo-light.svg" width="auto" height="60">
    </picture>
  </a>
</p>

<p align="center">
  Reactive primitives for Ethereum apps
<p>

<p align="center">
  <a href="https://www.npmjs.com/package/wagmi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/v/wagmi?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/v/wagmi?colorA=f6f8fa&colorB=f6f8fa" alt="Version">
    </picture>
  </a>
  <a href="https://scorecard.dev/viewer/?uri=github.com/ossf/scorecard">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/ossf-scorecard/github.com/wevm/wagmi?label=openssf+scorecard&style=flat&color=21262d&labelColor=21262d">
      <img src="https://img.shields.io/ossf-scorecard/github.com/wevm/wagmi?label=openssf+scorecard&style=flat&color=f6f8fa&labelColor=f6f8fa" alt="OpenSSF Best Practices">
    </picture>
  </a>
  <a href="https://www.bestpractices.dev/en/projects/11233">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/openssf_best_practices-passing-21262d?labelColor=21262d">
      <img src="https://img.shields.io/badge/openssf_best_practices-passing-f6f8fa?labelColor=f6f8fa" alt="OpenSSF Best Practices">
    </picture>
  </a>
  <br />
  <a href="https://github.com/wevm/wagmi/blob/main/LICENSE">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/l/wagmi?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/l/wagmi?colorA=f6f8fa&colorB=f6f8fa" alt="MIT License">
    </picture>
  </a>
  <a href="https://www.npmjs.com/package/wagmi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/npm/dm/@wagmi/core?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/npm/dm/@wagmi/core?colorA=f6f8fa&colorB=f6f8fa" alt="Downloads per month">
    </picture>
  </a>
  <a href="https://bestofjs.org/projects/wagmi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/endpoint?colorA=21262d&colorB=21262d&url=https://bestofjs-serverless.now.sh/api/project-badge?fullName=wevm%2Fviem%26since=daily">
      <img src="https://img.shields.io/endpoint?colorA=f6f8fa&colorB=f6f8fa&url=https://bestofjs-serverless.now.sh/api/project-badge?fullName=wevm%2Fviem%26since=daily" alt="Best of JS">
    </picture>
  </a>
  <a href="https://app.codecov.io/gh/wevm/wagmi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/codecov/c/github/wevm/wagmi?colorA=21262d&colorB=21262d">
      <img src="https://img.shields.io/codecov/c/github/wevm/wagmi?colorA=f6f8fa&colorB=f6f8fa" alt="Code coverage">
    </picture>
  </a>
</p>

---

## Documentation

For documentation and guides, visit [wagmi.sh](https://wagmi.sh).

## Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[Discuss Wagmi on GitHub](https://github.com/wevm/wagmi/discussions)

For casual chit-chat with others using the framework:

[Join the Wagmi Discord](https://discord.gg/SghfWBKexF)

## Contributing

Contributions to Wagmi are greatly appreciated! If you're interested in contributing to Wagmi, please read the [Contributing Guide](https://wagmi.sh/dev/contributing) **before submitting a pull request**.

## Sponsors

If you find Wagmi useful or use it for work, please consider [sponsoring Wagmi](https://github.com/sponsors/wevm?metadata_campaign=gh_readme_support). Thank you 🙏

<p>
  <a href="https://paradigm.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/paradigm-dark.svg">
      <img alt="paradigm logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/paradigm-light.svg" width="auto" height="70">
    </picture>
  </a>
  <a href="https://tempo.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/tempo-dark.svg">
      <img alt="tempo logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/tempo-light.svg" width="auto" height="70">
    </picture>
  </a>
</p>

<p>
  <a href="https://twitter.com/family">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/family-dark.svg">
      <img alt="family logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/family-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://twitter.com/context">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/context-dark.svg">
      <img alt="context logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/context-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://dynamic.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/dynamic-dark.svg">
      <img alt="Dynamic logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/dynamic-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://sushi.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sushi-dark.svg">
      <img alt="Sushi logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sushi-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://stripe.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/stripe-dark.svg">
      <img alt="Stripe logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/stripe-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://www.privy.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/privy-dark.svg">
      <img alt="Privy logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/privy-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://pancakeswap.finance">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pancake-dark.svg">
      <img alt="pancake logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pancake-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://pimlico.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pimlico-dark.svg">
      <img alt="pimlico logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/pimlico-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://zora.co">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/zora-dark.svg">
      <img alt="zora logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/zora-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://syndicate.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/syndicate-dark.svg">
      <img alt="syndicate logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/syndicate-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://relay.link">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/relay-dark.svg">
      <img alt="relay logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/relay-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://polymarket.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/polymarket-dark.svg">
      <img alt="polymarket logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/polymarket-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://sequence.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sequence-dark.svg">
      <img alt="sequence logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/sequence-light.svg" width="auto" height="50">
    </picture>
  </a>
  <a href="https://web3auth.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/web3auth-dark.svg">
      <img alt="web3auth logo" src="https://raw.githubusercontent.com/wevm/.github/main/content/sponsors/web3auth-light.svg" width="auto" height="50">
    </picture>
  </a>
</p>

[Sponsor Wagmi](https://github.com/sponsors/wevm?metadata_campaign=gh_readme_support_bottom)

<br />
<br />

<a href="https://vercel.com/?utm_source=wevm&utm_campaign=oss">
  <img src="https://www.datocms-assets.com/31049/1618983297-powered-by-vercel.svg" alt="Powered by Vercel" height="35">
</a>




---

## 54. ethers.js
- **URL:** https://github.com/devtechedge/ethers.js
- **Language:** TypeScript
- **Topics:** None
- **Description:** Complete Ethereum library and wallet implementation in JavaScript.

### README.md

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



---

## 55. kit
- **URL:** https://github.com/devtechedge/kit
- **Language:** TypeScript
- **Topics:** None
- **Description:** Solana JavaScript SDK

### README.md

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


---

## 56. solana-web3.js
- **URL:** https://github.com/devtechedge/solana-web3.js
- **Language:** TypeScript
- **Topics:** None
- **Description:** Solana JavaScript SDK

### README.md

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


---

## 57. regulatory_compliance
- **URL:** https://github.com/devtechedge/regulatory_compliance
- **Language:** Python
- **Topics:** compliance, fastapi, hitl, mica, nextjs, rag, vara, web3, docker, postgresql, typescript, vasp
- **Description:** HITL Web3 compliance copilot for VASP licensing reviewers. Maps project packs onto MiCA and VARA with retrieval-bounded findings, article citations, hallucination flags, split-screen accept/edit/reject, and markdown gap exports. Next.js, FastAPI, Postgres. Live Vercel demo-mode (seeded Aurum Custody, no API key). Compose is the full backend.

### README.md

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



---

## 58. veritas-engine
- **URL:** https://github.com/devtechedge/veritas-engine
- **Language:** TypeScript
- **Topics:** ai-research-agent, gemini-api, langchain, langgraph-js, multi-agent-systems, nextjs, tavily-api, typescript, serverless-agent, portfolio, sse, vercel
- **Description:** Self-correcting multi-agent research engine for technical briefs. Planner drafts queries, Tavily retrieves in parallel, a critic grades 1-10 and loops until >=8 or max depth, then a synthesizer writes Markdown. Next.js 14, LangGraph.js, Gemini 2.5 Flash, SSE. Public Vercel is Demo mode (simulated). Live needs GEMINI_API_KEY and TAVILY_API_KEY. MIT.

### README.md

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


---

## 59. luxe-tracker
- **URL:** https://github.com/devtechedge/luxe-tracker
- **Language:** TypeScript
- **Topics:** arbitrage, client-side, dashboard, editorial-ui, fashion-tech, luxury-retail, nextjs, portfolio, recharts, tailwindcss, typescript, price-disparity
- **Description:** Luxe Tracker is a high-fashion global launch and price-disparity dashboard for Prada, Gucci, Balenciaga, Louis Vuitton, and Versace. 17 intelligence panels, 5 maisons, 5 regions, 11k+ price rows: arbitrage, FX hedge, landed-cost optimizer, brand pulse. Next.js 15, Tailwind 4, Recharts. Pure client-side deterministic snapshotΓÇöno env vars, no backend

### README.md

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


---

## 60. aarop
- **URL:** https://github.com/devtechedge/aarop
- **Language:** TypeScript
- **Topics:** agentic-ai, ai-agents, llm, machine-learning, multi-agent-systems, nextjs, orchestration, python, agentic-loop, observability, state-machine, typescript, vercel
- **Description:** AAROP is a multi-agent system on an explicit PerceiveΓåÆPlanΓåÆActΓåÆObserveΓåÆReflectΓåÆAdapt loop: orchestration, self-verification, resilient recovery, bounded autonomy, replayable traces. Python core with 24 tests and 99% coverage plus a live Next.js demo. Public Vercel is a client-side TypeScript port with a deterministic mock providerΓÇöno API keys. MIT.

### README.md

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


---

## 61. notion-clone
- **URL:** https://github.com/devtechedge/notion-clone
- **Language:** HTML
- **Topics:** nextjs, pixel-perfect, react, typescript, visual-regression, animation, app-router, component-architecture, css, frontend-architecture, frontend-engineering, frontend-testing, github-actions, html, lighthouse, playwright, rendering, responsive-design, ui-engineering, web-performance
- **Description:** Pixel-perfect Next.js App Router recreation of the Notion marketing homepage. Source-backed DOM, CSS, fonts, and inline artwork from the original capture, not a restyle. Playwright visual QA and pixel-diff overlays. TypeScript, React 18, Lighthouse. Live on Vercel as a visual engineering exercise; no Notion auth, no database, no editor backend. MIT

### README.md

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


---

## 62. polygot
- **URL:** https://github.com/devtechedge/polygot
- **Language:** TypeScript
- **Topics:** ai, gemini, language-learning, nextjs, portfolio, pronunciation, react, roleplay, spanish, speech-recognition, typescript, vercel
- **Description:** PolyGlot Live is a Spanish speaking lab for learners who want live roleplay, not flashcards. Pick a Madrid tapas bar, a Barcelona bike rental, or a Tokyo tech interview. Talk via mic or type, then get IPA, grammar toasts, vocab chips, and a fluency scorecard. Next.js 15, React 19, Gemini with canned demo fallback. Browser speech; no accounts. MIT.

### README.md

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


---

## 63. calendar-math
- **URL:** https://github.com/devtechedge/calendar-math
- **Language:** Python
- **Topics:** calendar, evaluation, python, reinforcement-learning, rl, rlvr, verifiers, llm-evaluation, prime-intellect
- **Description:** Single-turn calendar arithmetic RL environment for Prime Intellect: datetime gold solver, exact+format+partial grader, vf-eval ready.

### README.md

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


---

## 64. meeting-slot
- **URL:** https://github.com/devtechedge/meeting-slot
- **Language:** Python
- **Topics:** calendar, evaluation, llm-evaluation, prime-intellect, python, reinforcement-learning, rl, rlvr, scheduling, timezone, tool-use, verifiers
- **Description:** Multi-turn tool-using meeting scheduler RL environment for Prime Intellect: hidden calendars, timezone gold solver, exact+format+partial grader.

### README.md

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


---

## 65. pulsar
- **URL:** https://github.com/devtechedge/pulsar
- **Language:** TypeScript
- **Topics:** base-chain, decentralized-ai, erc20, foundry, framer-motion, nextjs, rainbowkit, recharts, solidity, staking, typescript, web3
- **Description:** Decentralized AI compute marketplace on Base. Pay $PULSAR for inference; earn by supplying GPU. Next.js site with a 3D neutron-star hero, staking UI, tokenomics, RainbowKit wallet connect, plus Foundry ERC-20 and staking contracts. GitHub Pages uses mock dataΓÇöcontracts are audit-ready but not deployed to Base (pre-TGE). TypeScript, Framer Motion.

### README.md

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


---

## 66. obsidian
- **URL:** https://github.com/devtechedge/obsidian
- **Language:** HTML
- **Topics:** creative-coding, frontend, generative-art, github-pages, lenis, no-build, portfolio, react, single-file, tailwindcss, threejs, web-audio
- **Description:** The Obsidian Archive is a single-file immersive portfolio for a fictional generative sculpture studio. Twenty frontend features: Three.js crystal, Web Audio drone, command palette, pinned horizontal gallery. React 18 UMD, Tailwind Play CDN, Lenis, Three.jsΓÇözero build, GitHub Pages, SRI-pinned CDNs. Open index.html anywhere. Client-side only. MIT.

### README.md

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


---

## 67. blockchain_expert
- **URL:** https://github.com/devtechedge/blockchain_expert
- **Language:** TypeScript
- **Topics:** agents, hitl, llm, mcp, nextjs, security, smart-contracts, solidity, static-analysis, swc, typescript, web3
- **Description:** Argus is an agentic smart-contract security copilot for auditors. Deterministic static analysis, SWC-mapped retrieval, false-positive filtering, remediation diffs, and human-in-the-loop triage. TypeScript engine, Next.js workbench, MCP tool host. Educational samples only; never connects to a chain. Vercel is demo-mode (no API key required).

### README.md

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


---

## 68. synthesis
- **URL:** https://github.com/devtechedge/synthesis
- **Language:** TypeScript
- **Topics:** agentic, drizzle, hitl, langgraph, multi-agent, nextjs, observability, postgres, rag, react, sse, typescript
- **Description:** Autonomous multi-agent research: plan ΓåÆ research ΓåÆ synthesize ΓåÆ critique ΓåÆ finalize. Live agent graph, HITL approval, RAG, Reflexion, streaming SSE, eval gate. Next.js 16, Drizzle, Postgres. Groq llama-3.3-70b + Tavily when keys are set; otherwise a deterministic grounded simulator with the same UI. Free-tier Vercel demo. OpenAI-compatible keys.

### README.md

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


---

## 69. lattice
- **URL:** https://github.com/devtechedge/lattice
- **Language:** TypeScript
- **Topics:** blockchain, crypto, freelance, job-board, react, salaries, tailwindcss, talent, tanstack, typescript, vercel, web3
- **Description:** Web3 career lattice: live roles from twenty crypto teamsΓÇÖ public Greenhouse, Lever, and Ashby boards, plus gigs, talent, and a salary observatory. Apply on the employerΓÇÖs site. Pay only when the board publishes it. Public listings. Not an employer.

### README.md

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


---

## 70. zenith-canvas
- **URL:** https://github.com/devtechedge/zenith-canvas
- **Language:** TypeScript
- **Topics:** canvas, interactive, neo-brutalist, nextjs, productivity, react, tailwindcss, web-audio-api, localstorage, playwright, portfolio, typescript
- **Description:** Zenith Canvas is a neo-brutalist family workspace: drag-and-drop bento cards, checklists, sketches, guest passes, Web Audio chimes, and a 4-digit PIN vault. Next.js 14, React, TypeScript, Tailwind. Everything lives in localStorage - no backend, no accounts, no database. Fresh Start reset and architecture-blueprint modal.

### README.md

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


---

## 71. pulse-work
- **URL:** https://github.com/devtechedge/pulse-work
- **Language:** TypeScript
- **Topics:** block-editor, dark-mode, focus-timer, kanban, nextjs, notion-clone, portfolio, productivity, react, tailwindcss, typescript, workspace
- **Description:** Pulse Workspace is a block-based notes and collections OS for students and makers: slash-command editor, Kanban/table/calendar/Gantt views, ΓîÿK spotlight, flashcards, habits, and a 25-minute timer with procedural ambient noise. Next.js 15, React 19, Tailwind 4, Fira Code. Client-side demo ΓÇö in-memory state, no auth; billing screens simulated. MIT.

### README.md

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


---

## 72. aether-flow
- **URL:** https://github.com/devtechedge/aether-flow
- **Language:** TypeScript
- **Topics:** canvas, flowchart, gemini, local-first, portfolio, react, state-machine, tailwindcss, typescript, visual-programming, vite, workflow
- **Description:** AetherFlow is a local-first visual flowchart IDE. Drag nodes on a pan/zoom canvas, compile the graph, and run a sandboxed step simulator with time-travel snapshots. Optional Gemini plus mock Gmail/Drive/Docs nodes. Public Vercel stores graphs in localStorage and uses mock Workspace payloads. React, Vite, TypeScript, Tailwind. No accounts. MIT. OSS.

### README.md

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


---

## 73. chaos-simulator
- **URL:** https://github.com/devtechedge/chaos-simulator
- **Language:** TypeScript
- **Topics:** bun, chaos-engineering, dashboard, framer-motion, full-stack, microservices, nextjs, observability, realtime, recharts, self-healing, socket-io, typescript
- **Description:** Chaos Simulator is a real-time chaos-engineering dashboard: self-healing microservices, animated SVG topology, particle effects, scenario builder, and live telemetry charts. Next.js 16, Bun, TypeScript, Framer Motion, Recharts. Public Vercel is client-side simulationΓÇöno backend. Chaos injection, healing, latency, and event stream run in-browser.

### README.md

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


---

## 74. collabspace-express
- **URL:** https://github.com/devtechedge/collabspace-express
- **Language:** TypeScript
- **Topics:** canvas, collaborative-whiteboard, express, prisma, react, socketio, typescript, vite, websocket, multiplayer, realtime, vercel
- **Description:** CollabSpace Express is a real-time multiplayer whiteboard: infinite canvas, live cursors, rooms, and Prisma persistence. React 19, Vite, Express, Socket.io, TypeScript. Vercel hosts the client only; the Node/Socket server is local, and the public URL falls back to a solo canvas if the API is down. Anonymous localStorage name. No accounts, MIT. OSS.

### README.md

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


---

## 75. collabspace
- **URL:** https://github.com/devtechedge/collabspace
- **Language:** TypeScript
- **Topics:** collaborative-whiteboard, framer-motion, infinite-canvas, multiplayer, presence, react, realtime, supabase, typescript, vercel, vite, websocket-alternative
- **Description:** CollabSpace is a real-time multiplayer whiteboard: infinite canvas, presence, chat, reactions, and a laser pointer. React 18, Vite, TypeScript, Framer Motion, Supabase Realtime. Dark/light, responsive. Public Vercel currently shows a Supabase-not-configured shell; full multiplayer needs a Supabase project. Local path is Docker + npx supabase start.

### README.md

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


---

## 76. aegis_vercel
- **URL:** https://github.com/devtechedge/aegis_vercel
- **Language:** Python
- **Topics:** fastapi, langchain, langgraph, python, serverless, vercel, ai-agents, langserve, langsmith, multi-agent, pgvector, rag, autonomous-agents, hitl, human-in-the-loop, mermaid, sre, sse, streaming
- **Description:** AEGIS is a multi-agent operations cortex with a live dashboard. Supervisor plus specialist agents (SRE, knowledge, coder, evaluator, communicator), Hybrid RAG, HITL gates, streaming SSE, and a real-time Mermaid LangGraph. FastAPI, LangChain, LangGraph, LangSmith. Open /ui, toggle Demo vs Live. Demo is instant simulation; Live needs API keys. MIT.

### README.md

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


---

## 77. healthcare-deep-memory-agents
- **URL:** https://github.com/devtechedge/healthcare-deep-memory-agents
- **Language:** Python
- **Topics:** ai-agents, clinical-memory, consent, deep-memory, groq, healthcare, ollama, patient-journey, python, sentence-transformers, sqlite, vertical-agents
- **Description:** Cadence is a pure-Python deep-memory healthcare agent lab: multi-layer patient memory, journey stages, and consent-scoped clinician briefs. No LangChain. Local path is Ollama + SQLite + sentence-transformers. Public Vercel UI is a companion + share-code brief with Groq llama-3.3-70b (demo fallback without a key). Educational prototype, not real PHI

### README.md

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


---

## 78. nexus-bazaar
- **URL:** https://github.com/devtechedge/nexus-bazaar
- **Language:** TypeScript
- **Topics:** b2b, checkout, ecommerce, local-first, marketplace, multi-role, portfolio, react, spa, tailwindcss, typescript, vite
- **Description:** NexusBazaar is a client-side multi-role marketplace for buyers, sellers, and admins. Browse a seeded catalog, run cart and promo checkout, switch into seller or admin hubs, and walk B2B RFQ plus Net-30 credit. React 19, Vite, TypeScript, Tailwind. Data lives in localStorage ΓÇö no production payments, JWT, or backend. Optional Gemini concierge. MIT.

### README.md

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


---

## 79. holdslot
- **URL:** https://github.com/devtechedge/holdslot
- **Language:** JavaScript
- **Topics:** hackathon, openai, webmcp
- **Description:** HoldSlot ΓÇö agent can search and hold a slot; only the human can confirm. OpenAI WebMCP Challenge 2026.

### README.md

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


---

## 80. wanderlodge
- **URL:** https://github.com/devtechedge/wanderlodge
- **Language:** TypeScript
- **Topics:** airbnb-clone, dark-mode, gemini, lodging, marketplace, nextjs, peer-to-peer, portfolio, react, tailwindcss, travel, typescript
- **Description:** Peer-to-peer lodge marketplace for subalpine cabins. Search sensory-scored stays, book as a traveler or host as a provider, then run a trip workspace with group expenses, cabin controls, and a wilderness log. Next.js 15, React, TypeScript. Vercel uses an in-memory JSON store (writes reset). Gemini optional. Demo marcus@wanderlodge.com / password123

### README.md

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


---

## 81. vivid-pulse
- **URL:** https://github.com/devtechedge/vivid-pulse
- **Language:** TypeScript
- **Topics:** app-router, dark-theme, instagram-clone, nextjs, playwright, portfolio, react, social-network, tailwindcss, typescript, vercel, vitest
- **Description:** Neo-noir visual social network for digital creators. Photo feed with carousels, likes, bookmarks and threaded comments; 24-hour stories; discover search; DMs; and a cozy neighbors board. Next.js 15 App Router, TypeScript, Tailwind. In-memory Vercel demo (resets on cold start)ΓÇönot JWT or NextAuth. Demo login alex_vivid / password123. MIT licensed.

### README.md

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


---

## 82. smart-waitlist
- **URL:** https://github.com/devtechedge/smart-waitlist
- **Language:** TypeScript
- **Topics:** drizzle-orm, full-stack, nextjs, referral-system, saas, server-actions, shadcn-ui, stripe, supabase, tailwindcss, typescript, waitlist
- **Description:** Smart Waitlist is a SaaS waitlist and referral engine: viral growth loops, live queue position, admin analytics, Stripe tiers, and Postgres RLS. Next.js 16, Supabase Auth + Postgres, Drizzle, shadcn/ui, Tailwind. Public Vercel is full-stack liveΓÇösign up, grab a referral link, climb the queue, open the admin dashboard. TypeScript. Not a toy form.

### README.md

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


---

## 83. unit-fix
- **URL:** https://github.com/devtechedge/unit-fix
- **Language:** Python
- **Topics:** None
- **Description:** Single-turn Python repair RL environment: patch a small function so hidden unit tests pass. Sandboxed exec grader for Prime Intellect Environments Hub.

### README.md

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


---

## 84. astra-marketplace
- **URL:** https://github.com/devtechedge/astra-marketplace
- **Language:** TypeScript
- **Topics:** ecommerce, marketplace, nextjs, postgresql, prisma, react, tailwindcss, typescript, admin-dashboard, full-stack, portfolio, seller-portal
- **Description:** AstraMart: paper-and-copper marketplace demo. 18-SKU catalog, HMAC demo sessions, seller and admin portals. Next.js 14. Live Vercel is seeded demo data with mock payments. customer@demo.com / Demo123!

### README.md

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


---

## 85. github-repo-presentation
- **URL:** https://github.com/devtechedge/github-repo-presentation
- **Language:** Not specified
- **Topics:** None
- **Description:** Private skill archive. Not a product repo.

### README.md

# github-repo-presentation

Private skill archive. **Revision 11 — 2026-09-01.** Not a product repo.

## Download

**[github-repo-presentation-revision-11.zip](https://github.com/devtechedge/github-repo-presentation/raw/main/github-repo-presentation-revision-11.zip)** — click to download.

Or clone with GitHub Desktop into `Documents\GitHub\github-repo-presentation`.

## Layout

```
github-repo-presentation-revision-11.zip
github-repo-presentation/
  SKILL.md
  HANDOFF.md
  readme-skeleton.md
  mit-license.txt
  references/mit-license.txt
  references/chrome-and-data.md
```

Revision 11 adds general chrome and data-path traps that apply to **every** public repo (cool silver light, native `<select>` vs leftover CSS transform, WASM copy on serverless, `DATABASE_URL` vs vendor `STORAGE_URL`, README matching the live store, CSP for remote images, cron Bearer on host and Actions). Re-upload the zip at grok.com/skills-and-connectors.

Keep this repository private. Do not copy the zip into public product repos.


---

## 86. alephium-web3
- **URL:** https://github.com/devtechedge/alephium-web3
- **Language:** TypeScript
- **Topics:** None
- **Description:** The Typescript SDK for building dapps on Alephium

### README.md

# Alephium Web3

[![Github CI][test-badge]][test-link]
[![NPM][npm-badge]][npm-link]
[![code style: prettier][prettier-badge]][prettier-link]

A Typescript library for building decentralized applications on Alephium.

## Getting started

You could run the following command to scaffold a skeleton project for smart contract development:

```
npx @alephium/cli init <project-dir> [-t (base | react | nextjs)]
```

Please read the [documentation](https://docs.alephium.org/sdk/getting-started/) for more.

## Packages

There are a few packages in this repository:

1. `@alephium/cli` is the CLI tool for dApp development.
2. `@alephium/web3` is the core and base package for all dApp development.
3. `@alephium/web3-wallet` contains wallet related functions.
4. `@alephium/web3-test` contains test related functions.
5. `@alephium/web3-react` contains react components to help authenticate and interact with the Alephium blockchain
6. `@alephium/get-extension-wallet` contains functions to get the extension wallet object
6. `@alephium/walletconnect` contains Alephium's WalletConnect implementation

## Development

### Build System

The modernized packages (`@alephium/web3`, `@alephium/web3-wallet`, `@alephium/walletconnect-provider`) use a **tsc dual-build** approach (same pattern as [viem](https://github.com/wevm/viem)):

```
pnpm build
```

Each package runs two `tsc` passes that output to separate directories:

| Output | Directory | Description |
|---|---|---|
| CJS + types | `dist/_cjs/` | CommonJS for Node.js `require()` consumers |
| ESM + types | `dist/_esm/` | ES Modules for bundlers and modern Node.js `import` consumers |

Each output directory contains a nested `package.json` that tells Node.js how to interpret the `.js` files:
- `dist/_cjs/package.json` → `{"type": "commonjs"}`
- `dist/_esm/package.json` → `{"type": "module", "sideEffects": false}`

This approach avoids the need for `.cjs`/`.mjs` extensions while keeping CJS and ESM unambiguous.

#### Build flags explained

**`build:cjs`**: `tsc --module commonjs --moduleResolution node --declaration --verbatimModuleSyntax false`
- `--module commonjs` — overrides the root tsconfig's `es2020` to emit `require()`/`module.exports`. The `"type": "commonjs"` in the root `package.json` only affects Node.js runtime, not tsc.
- `--moduleResolution node` — overrides the root's `bundler` to use Node's CJS resolution algorithm.
- `--declaration` — emits `.d.ts` type declarations alongside `.js` files, so CJS consumers get CJS-flavored types.
- `--verbatimModuleSyntax false` — allows tsc to transform `import`/`export` to `require()`/`module.exports`.

**`build:esm`**: `tsc --declaration && tsc-alias --resolve-full-paths`
- Inherits `--module es2020` and `--moduleResolution bundler` from root tsconfig.
- `--declaration` — emits `.d.ts` type declarations alongside `.js` files, so ESM consumers get ESM-flavored types.
- The `"sideEffects": false` in the nested `package.json` enables tree-shaking for bundlers that check the nearest `package.json` to the resolved file.
- **`tsc-alias --resolve-full-paths`** — post-processes the ESM output to add `.js` extensions to all relative import paths (e.g., `from './api'` becomes `from './api/index.js'`). This is necessary because strict ESM resolvers (Node.js with `"type": "module"`, Vitest) require explicit file extensions — bare directory imports like `'./api'` don't resolve in ESM. TypeScript deliberately does not rewrite import specifiers during compilation ([by design](https://github.com/microsoft/TypeScript/issues/16577)), so a post-processing step is needed. The CJS output does not need this because Node's `require()` handles directory resolution natively.

#### Package fields

```json
{
  "type": "commonjs",
  "sideEffects": false,
  "main": "dist/_cjs/index.js",
  "module": "dist/_esm/index.js",
  "types": "dist/_cjs/index.d.ts",
  "exports": {
    ".": {
      "import": {
        "types": "./dist/_esm/index.d.ts",
        "default": "./dist/_esm/index.js"
      },
      "require": {
        "types": "./dist/_cjs/index.d.ts",
        "default": "./dist/_cjs/index.js"
      }
    },
    "./api/explorer": { ... },
    "./api/node": { ... }
  }
}
```

**`"type": "commonjs"`** — declares the package's default module type. Without this, Node.js auto-detects the type on each file access, causing a small performance hit ([publint suggestion](https://publint.dev/)). We use `"commonjs"` (not `"module"`) because:
- The package root contains source files, config files, and scripts that are CJS
- The `dist/_esm/` directory overrides this with its own `{"type": "module"}` nested `package.json`
- Vitest runs tests relative to the package root

**`"sideEffects": false`** — tells bundlers (webpack, Vite, Rollup) that all modules in this package are pure — importing a module without using its exports has no observable effect. This enables aggressive tree-shaking: if a consumer imports only `isValidAddress`, the bundler can safely drop all other modules.

**`"main"`** — entry point for Node.js `require('@alephium/web3')` and legacy bundlers that don't understand `exports`. Points to the CJS output.

**`"module"`** — entry point for legacy bundlers (webpack 4, older Rollup) that look for ESM via this non-standard field. Modern bundlers use `exports` instead, but `module` provides a fallback.

**`"types"`** — entry point for TypeScript when `moduleResolution` is `"node"` (node10). Points to the CJS type declarations since `"type": "commonjs"` packages default to CJS resolution.

**`"exports"`** — the modern entry point map. Runtimes and bundlers that support it use `exports` over `main`/`module`/`types`. Each condition (`import`/`require`) has its own `types` entry pointing to the type declarations in the corresponding output directory. This ensures CJS consumers get CJS-flavored type declarations and ESM consumers get ESM-flavored type declarations, avoiding [FalseCJS](https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/FalseCJS.md) and [FalseESM](https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/FalseESM.md) type issues.

#### Sub-path exports

`@alephium/web3` exposes the generated API types via sub-path exports:

```ts
// Node API types (generated from the Alephium full node OpenAPI spec)
import { Balance, Transaction } from '@alephium/web3/api/node'

// Explorer API types (generated from the explorer backend OpenAPI spec)
import { FungibleTokenMetadata, MempoolTransaction } from '@alephium/web3/api/explorer'
```

These replace the old deep imports into the package's internal directory structure:

```ts
// ❌ Old (v2) — reaches into internal dist structure
import { FungibleTokenMetadata } from '@alephium/web3/dist/src/api/api-explorer'

// ✅ New (v3) — stable public sub-path
import { FungibleTokenMetadata } from '@alephium/web3/api/explorer'
```

The `typesVersions` field provides fallback resolution for TypeScript consumers using `moduleResolution: "node"` (which doesn't support `exports`).

### Package Quality Checks

```
pnpm check
```

Runs [publint](https://publint.dev/) and [@arethetypeswrong/cli](https://arethetypeswrong.github.io/) on the modernized packages.

- **publint** validates that `package.json` fields, `exports`, and file references are correct.
- **attw** checks that TypeScript types resolve correctly for consumers using different module resolution strategies (`node10`, `node16`, `bundler`).

The `internal-resolution-error` rule is ignored in attw because the `node16 (from ESM)` resolution mode requires `.js` extensions in all import paths within type declaration files. Since tsc does not rewrite import paths in emitted `.d.ts` files, bare specifiers like `'./api'` fail strict ESM resolution. This is a [known limitation](https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/InternalResolutionError.md) affecting most dual CJS/ESM packages, including viem. The `node10`, `node16 (from CJS)`, and `bundler` resolution modes all resolve correctly.

### React Native / Expo

When using `@alephium/web3` in a React Native environment (Expo or bare), one workaround is needed:

**`react-native-get-random-values`** — `@noble/secp256k1` requires `crypto.getRandomValues`, which is not available in React Native by default. Install the package and load it before any `@alephium/web3` import:

```ts
// index.ts (entry point)
require('react-native-get-random-values')
// ... then load your app
```

> **Note:** If using pnpm, add `node-linker=hoisted` to `.npmrc` — Metro is incompatible with pnpm's strict symlink layout.

Create `shims/fs.js`:
```js
module.exports = {}
```

Add it to your `metro.config.js`:
```js
config.resolver.extraNodeModules = {
  ...config.resolver.extraNodeModules,
  fs: path.resolve(__dirname, 'shims/fs.js')
}
```

> **Note:** If using pnpm, add `node-linker=hoisted` to `.npmrc` — Metro is incompatible with pnpm's strict symlink layout.

### Testing

```
pnpm test
```

Runs Vitest across all packages. The root `vitest.config.ts` configures test discovery, globals, and coverage. Vitest handles ESM natively, so no special transforms or ignore patterns are needed for `@noble` and `@scure` packages.


[test-badge]: https://github.com/alephium/alephium-web3/actions/workflows/test.yml/badge.svg
[test-link]: https://github.com/alephium/alephium-web3/actions/workflows/test.yml
[npm-badge]: https://img.shields.io/npm/v/@alephium/web3.svg
[npm-link]: https://www.npmjs.org/package/@alephium/web3
[prettier-badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg
[prettier-link]: https://github.com/prettier/prettier
[release-notes]: https://github.com/alephium/alephium-web3/releases


---

## 87. cuer
- **URL:** https://github.com/devtechedge/cuer
- **Language:** TypeScript
- **Topics:** None
- **Description:** QR Code for React

### README.md

# cuer

Opinionated QR Code component for React, powered by [`qr`](https://github.com/paulmillr/qr)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wevm/cuer/refs/heads/main/.github/qr-dark.svg">
  <img alt="cuer logo" src="https://raw.githubusercontent.com/wevm/cuer/refs/heads/main/.github/qr-light.svg" width="auto" height="150px">
</picture>

## Install

```sh
npm i cuer
```

## Usage

### Basic

Use the `Cuer` component to render a QR code (with an optional `arena`).

```tsx
import { Cuer } from 'cuer'

export function App() {
  return <Cuer arena="https://example.com/logo.png" value="https://wevm.dev" />
}
```

### Advanced

Further customization is possible by composition components (ie. `Cuer.Root`, `Cuer.Cells`, etc).

```tsx
import { Cuer } from 'cuer'

export function App() {
  return (
    <Cuer.Root value="https://wevm.dev">
      <Cuer.Finder fill="red" radius={0} />
      <Cuer.Cells fill="blue" radius={0} />
      <Cuer.Arena>
        <img
          src="https://example.com/logo.png"
          style={{ width: '100%', height: '100%', objectFit: 'cover' }}
        />
      </Cuer.Arena>
    </Cuer.Root>
  )
}
```

## License

[MIT](/LICENSE) License


---


