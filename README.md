<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-hero-light.svg">
  <img alt="Anirudh Tumuluru: founder, engineer, open-source builder" src="assets/profile-hero-light.svg" width="100%">
</picture>

**Founder & engineer.** Building autonomous systems, blockchain infrastructure, and products that solve real-world
problems. Hyderabad, India.

**About me.** Professional footballer: I played in the I-League with NEROCA FC in 2023–24, after district, state
and national levels in India. Fitness freak. Now I build: blockchain tools that show their work, and OnlyKrida, so the
next player gets seen.

[Where's My Swap](https://wheres-my-swap.station-wheres-my-swap.workers.dev) ·
[Zcash Refund Helper](https://cryppit.github.io/zec-refund-helper/) ·
[Safe to Send](https://cryppit.github.io/safe-to-send/) ·
[OnlyKrida](https://onlykrida.com) ·
[LinkedIn](https://www.linkedin.com/in/anirudh-tumuluru-315a7b23b/)

## What I'm building

<p>
<a href="https://github.com/cryppit"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/card-cryppit-dark.svg">
  <img alt="Cryppit: autonomous agents and blockchain infrastructure" src="assets/card-cryppit-light.svg" width="410">
</picture></a>
<a href="https://wheres-my-swap.station-wheres-my-swap.workers.dev"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/card-wheres-my-swap-dark.svg">
  <img alt="Where's My Swap: cross-chain swap tracing and diagnostics" src="assets/card-wheres-my-swap-light.svg" width="410">
</picture></a>
<a href="https://onlykrida.com"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/card-onlykrida-dark.svg">
  <img alt="OnlyKrida: athlete discovery and sports technology" src="assets/card-onlykrida-light.svg" width="410">
</picture></a>
<a href="https://github.com/Anirudh-712/SUPERCORTEX-"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/card-supercortex-dark.svg">
  <img alt="Supercortex: quantitative research and autonomous systems" src="assets/card-supercortex-light.svg" width="410">
</picture></a>
</p>

| | What it is | Status | Look at |
|---|---|---|---|
| **Cryppit** | My company: keyless, read-only tools for cross-chain money, and research into autonomous agents. | Active | [github.com/cryppit](https://github.com/cryppit) |
| **Where's My Swap** | Paste a NEAR Intents order and see every hop to its payout, where the money is now and who can move it. Checks payouts on 33 chains and flags order accounts locked by NEAR Intents' operators. Its address check says, before you send, whether your wallet can pay an address on all 21 chains NEAR Intents pays out to. Free, no keys, no sign-in. | Live | [the checker](https://wheres-my-swap.station-wheres-my-swap.workers.dev) · [address check](https://wheres-my-swap.station-wheres-my-swap.workers.dev/address) · [ZEC route](https://wheres-my-swap.station-wheres-my-swap.workers.dev/zec) |
| **Where's My Withdrawal** | Paste a rollup withdrawal and see which step is missing and who can finish it, across 13 chains: the OP Stack chains, Blast, Arbitrum One, Robinhood Chain, Linea and ZKsync Era. It prints the exact call, and anyone may send it. Read-only, no keys. | Live | [repo](https://github.com/cryppit/wheres-my-withdrawal) · [page](https://cryppit.github.io/wheres-my-withdrawal/) |
| **Safe to Send** | Paste an address and the chain you are sending on: see whether funds sent there can be reached, before you send. Reads 20 chains and catches smart wallets that only exist on one chain, with an archive of all 4.25M Abstract wallets that keeps working after Abstract shuts down on 15 Dec 2026. Read-only, no keys. | Live (26 Oct 2026) | [page](https://cryppit.github.io/safe-to-send/) · [repo](https://github.com/cryppit/safe-to-send) |
| **NU7 Readiness** | Which Zcash wallets, libraries, bridges and swaps are ready for NU7, from public evidence (GitHub issues, PRs, releases, source). Read-only, re-checked hourly. | Live | [board](https://cryppit.github.io/nu7-readiness/) · [repo](https://github.com/cryppit/nu7-readiness) |
| **Zcash Refund Helper** | Finds a ZEC or BTC deposit stuck in the NEAR Omni bridge and prints the bridge's own refund steps. Read-only: it never holds keys or signs. 213 tests, MIT, ZECATHON 2026 entry. Used on mainnet on 15 Oct 2026 to return a stuck deposit to its owner's address. | Released v0.1.0 | [repo](https://github.com/cryppit/zec-refund-helper) · [page](https://cryppit.github.io/zec-refund-helper/) |
| **OnlyKrida** | Athlete discovery for India: tested, coach-verified results and opportunities for players the scouting pipeline doesn't reach. | Waitlist | [onlykrida.com](https://onlykrida.com) |
| **Supercortex** | A local-first quant research desk that counts every backtest so the Deflated Sharpe Ratio stays honest, with an Indian crypto-tax cost model and a falsification engine whose job is to kill ideas. Backtests only. | Research prototype | [repo](https://github.com/Anirudh-712/SUPERCORTEX-) |

## Open-source work

Fixes, documentation and bug reports I contributed upstream while building these tools. States are verified from GitHub
as of 31 Oct 2026.

| Project | Contribution | State |
|---|---|---|
| [ZcashFoundation/zebra](https://github.com/ZcashFoundation/zebra/pull/12150) | PR #12150: a custom Testnet or Regtest that gives an activation height to an upgrade with no consensus branch ID now fails at config load with an error naming the upgrade, instead of panicking at that block (fixes #11482) | Open (31 Oct 2026) |
| [Kenbak/zecblock](https://github.com/Kenbak/zecblock/pull/137) | PR #137: look up ZIP 320 TEX addresses by the P2PKH address they encode, instead of reporting them as invalid (issue [#136](https://github.com/Kenbak/zecblock/issues/136)) | Open |
| [near/docs](https://github.com/near/docs/pull/3133) | PR #3133: fixed the stale Chain Signatures `sign` link; the maintainer kept the link fix and left out the note on signing domains | **Merged** (26 Oct 2026) |
| [wevm/viem](https://github.com/wevm/viem/pull/5302) | PR [#5296](https://github.com/wevm/viem/pull/5296): use the withdrawal's L2 timestamp to find super-root dispute games in the OP Stack withdrawal actions; merged through the maintainer's [#5302](https://github.com/wevm/viem/pull/5302) with the commit kept as-is | **Merged** (26 Oct 2026) |
| [wevm/viem](https://github.com/wevm/viem/pull/5298) | PR [#5295](https://github.com/wevm/viem/pull/5295): `getTimeToFinalize` waits for the dispute game to resolve, so an OP Stack withdrawal is no longer shown finalizable days early; merged through the maintainer's [#5298](https://github.com/wevm/viem/pull/5298) with the commit kept as-is | **Merged** (26 Oct 2026) |
| [zingolabs/zingo-mobile](https://github.com/zingolabs/zingo-mobile/pull/1754) | PR #1754: in Insight privacy mode, an unnamed row's address shows its mask, matching the hidden amounts and the donut caption (closes #1542) | **Merged** (26 Oct 2026) |
| [Near-One/omni-bridge](https://github.com/Near-One/omni-bridge/issues/251) | Issue #251 (large native NEAR withdrawals stuck): showed it was already fixed by #259 in the deployed omni.bridge.near 0.4.17; closed as completed | Closed (25 Oct 2026) |
| [defuse-protocol/nearintents-mpp-sdk](https://github.com/defuse-protocol/nearintents-mpp-sdk/pull/36) | PR #36: implemented draft-nearintents-charge-01 refund and settlement recovery, including payer-controlled refunds, chain-canonical transaction hashes and replay protection | **Merged** (22 Oct 2026) |
| [ZecHub/zechub](https://github.com/ZecHub/zechub/pull/2444) | PR #2444: corrected the Ironwood and turnstile documentation to explain that transfers between shielded pools reveal their amount | **Merged** (21 Oct 2026) |
| [near/docs](https://github.com/near/docs/pull/3121) | PR #3121: made Chain Signatures documentation point to the live MPC network instead of a fixed node count | **Merged** (20 Oct 2026) |
| [zingolabs/zingo-mobile](https://github.com/zingolabs/zingo-mobile/pull/1663) | PR #1663: accept every valid NEAR account ID in the swap address check without allowing other chains' addresses through | **Merged** (19 Oct 2026) |
| [zingolabs/zingo-mobile](https://github.com/zingolabs/zingo-mobile/pull/1665) | PR #1665: store uppercase Bech32 and CashAddr addresses in their canonical lowercase form | **Merged** (19 Oct 2026) |
| [blockscout/blockscout](https://github.com/blockscout/blockscout/issues/14974) | Issue #14974: an OP Mainnet withdrawal is shown "Ready for relay" from a pre-fault-proofs proof, before it can finalize | Open |
| [base/withdrawer](https://github.com/base/withdrawer/issues/99) | Issue #99: the `--fault-proofs` withdrawal flow is broken on OP Mainnet since Upgrade 20 (super-root games), with a patch | Open |
| [shapeshift/web](https://github.com/shapeshift/web/issues/12794) | Issue #12794: Zcash sends will fail at NU7 because the consensus branch ID is pinned to NU6.3 | Open |
| [ZcashFoundation/zebra](https://github.com/ZcashFoundation/zebra/pull/11880) | PR #11880: display ZIP 320 TEX addresses as Bech32m on Mainnet, Testnet and Regtest, with parsing round-trip tests for every network | **Merged** (23 Oct 2026) |
| [defuse-protocol/sdk-monorepo](https://github.com/defuse-protocol/sdk-monorepo) | PRs [#497](https://github.com/defuse-protocol/sdk-monorepo/pull/497), [#498](https://github.com/defuse-protocol/sdk-monorepo/pull/498) and [#499](https://github.com/defuse-protocol/sdk-monorepo/pull/499): validate PoA destination memos, Dogecoin and Stellar checksums, and zero-amount withdrawals | Open |
| [near/docs](https://github.com/near/docs) | PRs [#3120](https://github.com/near/docs/pull/3120) and [#3123](https://github.com/near/docs/pull/3123): document Omni Bridge relayers and add the currently supported chains | **Merged** (22 Oct 2026) |
| [XRPLF/xrpl.js](https://github.com/XRPLF/xrpl.js/pull/3546) | PR #3546: reject negative, fractional and NaN destination tags in `encodeXAddress` | Open |
| [defuse-protocol/defuse-frontend](https://github.com/defuse-protocol/defuse-frontend/pull/999) | PR #999: validate Zcash unified addresses according to ZIP 316, including Bech32m, F4Jumble and receiver typecodes | Open |
| [Near-One/bridge-sdk-rs](https://github.com/Near-One/bridge-sdk-rs/pull/324) | PR #324: correct the BTC refund example's required deposit and unsafe timelock | Open |
| [horizontalsystems/unstoppable-wallet-ios](https://github.com/horizontalsystems/unstoppable-wallet-ios/issues/7295) | Issue #7295 and PR #7299: diagnosed and fixed the Send memo field appearing for TEX addresses | Fixed by the maintainers in [#7300](https://github.com/horizontalsystems/unstoppable-wallet-ios/pull/7300), merged |
| [KeystoneHQ/keystone3-firmware](https://github.com/KeystoneHQ/keystone3-firmware/issues/2313) | Issue #2313: TEX addresses fail the transparent-output check | Open, planned for a feature release |
| [ZcashFoundation/zebra](https://github.com/ZcashFoundation/zebra/issues/11803) | Issue #11803: `z_validateaddress` rejects unified addresses carrying an unknown item that ZIP 316 requires implementations to tolerate | Open |
| [zcash/zcash-test-vectors](https://github.com/zcash/zcash-test-vectors/issues/135) | Issue #135: unified-address negative test vectors are missing | Open |

## Engineering

- **Chain forensics from public data.** Tracing an order across NEAR, Bitcoin, Zcash, Solana, TON, EVM chains and
  others, labelling each hop by how it is known, and reading the bridge contract when an indexer lags.
- **Protocol details that lose people money.** ZIP 316 unified addresses, ZIP 320 TEX, consensus branch IDs, memo and
  destination-tag rules, refund timelocks.
- **Serverless products.** Cloudflare Workers and D1, scheduled checks, webhooks, nothing custodial.
- **Range.** [famtv](https://github.com/Anirudh-712/famtv): an ad-free Android TV home screen with an offline Telugu
  panchangam, built without Gradle.

**Stack:** TypeScript · Node · Cloudflare Workers / D1 · Python · Rust · Java (Android) · React / React Native ·
Supabase / PostgreSQL · SQL
