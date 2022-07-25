<div align="center">
  <h1 align="center">Awesome Interoperability</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/gakonst/awesome-starknet/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/nomad-xyz/awesome-interoperability/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/nomad-xyz/awesome-interoperability">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">A curated list of awesome interoperability resources, libraries, tools and more.</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

</div>

# Resources

## Projects

### Light Clients - SPV

- [Cross-Consensus Message Format (XCM)](https://wiki.polkadot.network/docs/learn-crosschain) - The XCM specification used in Polkadot's cross-chain communication protocol
- [Inter-Blockchain Communication Protocol](https://tutorials.cosmos.network/academy/4-ibc/what-is-ibc.html) - The IBC specification used in Cosmos' cross-chain communication protocol
- [Ethereum BTC Relay](https://github.com/ethereum/btcrelay) - A BTC relay on Ethereum
- [Stateless BTC Relay](https://github.com/summa-tx/relays) - An improved stateless BTC relay on Ethereum

### PoA Validator set

- [Chainswap](https://docs.chainswap.com/) - Swaps
- [LayerZero](https://layerzero.gitbook.io/docs/) - Generalised cross-chain message passing
- [Multichain](https://docs.multichain.org/getting-started/introduction) - Generalised cross-chain message passing
- [Synapse](https://docs.synapseprotocol.com/) - Swaps
- [Wormhole](https://book.wormholenetwork.com/) - Generalised cross-chain message passing

### PoS Validator Set

- [Abacus](https://docs.useabacus.network/abacus-docs/introduction/what-is-abacus) - Generalised cross-chain message passing
- [Axelar](https://docs.axelar.dev/) - Generalised cross-chain message passing
- [ThorChain](https://thorchain.org/document-library) - Swaps

### Optimistic

- [Nomad.xyz](https://docs.nomad.xyz/) - Generalised cross-chain message passing

### Hashed Timelock Contract (HTLC)

### Liquidity Networks

- [Connext](https://docs.connext.network/) - Liquidity Network on top of Nomad

## General Interoperability

## Articles, Papers

- [Blockchain Bridges: Building Networks of Cryptonetworks](https://medium.com/1kxnetwork/blockchain-bridges-5db6afac44f8) by Dmitriy Berenzon
- [Clusters: how trusted & trust-minimized bridges shape the multi-chain landscape](https://blog.celestia.org/clusters/) by Mustafa Al-Bassam
- [Ethereum Bridges Documentation](https://ethereum.org/en/developers/docs/bridges/) - The ethereum bridges
- [Optimistic Bridges: A New Paradigm for Crosschain Communication](https://blog.connext.network/optimistic-bridges-fb800dc7b0e0) - An overview of the optimistic design for cross-chain communication
- [SoK: Communication Across Distributed Ledgers](https://eprint.iacr.org/2019/1128) - Systemization of Knowledge for the cross-chain domain
- [The Interoperability Trilemma](https://blog.connext.network/the-interoperability-trilemma-657c2cf69f17) - The trillema of interoperability
- [With Bridges, Trust is a Spectrum](https://blog.li.fi/li-fi-with-bridges-trust-is-a-spectrum-354cd5a1a6d8) - The different trust assumptions that exist in cross-chain protocols

## Podcasts, Videos

- [Axelar: Solving Interoperability across Blockchains](https://www.youtube.com/watch?v=m2RF_yWE6xo) - An overview of Axelar
- [Burning Bridges: The Pitfalls of Multisig Bridges](https://www.youtube.com/watch?v=0L9G1zKjpqA) - What are the common pitfalls of Multisig Bridges
- [CSCON[0] Breaking Down Bridges](https://www.youtube.com/watch?v=b0mC-ZqN8Oo) -
- [Cross-app Communication Panel](https://youtube.com/watch?v=EYzYAokCVgM) - The state of cross-chain communication and it's challenges
- [HTLCs Considered Harmful - SBC '19](https://www.youtube.com/watch?v=qUAyW4pdooA&t=1244s) - The design drawbacks of HTLCs
- [MIT Bitcoin Expo 2019 - Non-Atomic Swaps](https://www.youtube.com/watch?v=njGSFAOz7F8) - Use a Bitcoin SPV on Ethereum for non-atomic swaps between ETH and BTC
- [The Zero Knowledge Podcast: Designing Optimistic Interoperability with Nomad](https://www.youtube.com/watch?v=jBGVy2uVy2U) - An overview of Nomad and it's optimistic design
- [The Zero Knowledge Podcast: Through the Wormhole with Jump Crypto](https://www.youtube.com/watch?v=N-gayIFspno) - An overview of LayerZero and the tradeoffs of Validator Bridges
- [The problem with cross-chain Governance](https://www.youtube.com/watch?v=MmMpB6PxXrs&t) - An overview of cross-chain Governance and Nomad's solution

## Discussions

- [Bridge Risk Framework](https://gov.l2beat.com/t/l2bridge-risk-framework/31) - Discussion on L2Beat on creating a Risk Framework for Bridges

## Tutorials

- [Cross-chain testing with Foundry](https://twitter.com/hexonaut/status/1545845549328465932) - Example on cross-chain testing with Foundry

## Zero Knowledge Interoperability

- [Geometry presents: Slush, a proposal for Fractal scaling](https://hackmd.io/@kalmanlajko/rkgg9GLG5) - A fractal design of cross-domain bridges between rollups
- [Zero-Knowledge Proofs in Cross-Chain Communication](https://www.youtube.com/watch?v=6HftDh9mk-8) - A sketch on using Zero-Knowledge proofs for cross-chain communication

## Cross-Domain MEV

- [Overcommitted: MEV in Message Passing](https://www.youtube.com/watch?v=jCKumKWtYVQ) - Where MEV exists in cross-chain communication
- [MEV at the liquidity layer of bridges](https://www.youtube.com/watch?v=F_zi9oToHtU) - Where MEV exists in cross-chain liquidity networks
- [The multichain world is centralized 🙁 - studying cross-domain MEV](https://www.youtube.com/watch?v=dv5-Lzntv5M) - What is cross-chain MEV?
- [Unity is Strength: A Formalization of Cross-Domain Maximal Extractable Value](https://arxiv.org/abs/2112.01472)- First approach in formalizing cross-domain MEV

# Job Board

- [Abacus](https://jobs.lever.co/Abacus/)
- [Axelar](https://axelar.network/careers)
- [Connext](https://jobs.connext.network/Connext-Job-Board-d89dc91421794b47ab4a2356495a2a9c)
- [LayerZero](https://boards.greenhouse.io/layerzerolabs)
- [Multichain](https://docs.multichain.org/getting-started/careers)
- [Nomad.xyz](https://boards.greenhouse.io/nomad)
- [Wormhole](https://boards.greenhouse.io/wormhole)

# Tools

- [Dora](https://www.ondora.xyz/) - Cross-chain focused block explorer
- [Foundry](https://getfoundry.sh) - Testing framework that supports cross-chain

# License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,[Nomad.xyz](https://github.com/nomad-xyz) has waived all copyright and related or neighboring rights to this work.
