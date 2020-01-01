# Rust in Blockchain #7 - Dec 2019

**#7 - Dec 2019**

Welcome to the #7 edition of Rust in Blockchain, the hypest newsletter about the hypest tech. <!--[Previous: #6](https://rustinblockchain.org/2019/11/07/rust-in-blockchain-5-october-2019/). -->



&nbsp;


## Project spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Zebra](https://github.com/ZcashFoundation/zebra).

Zebra is an implementation of Zcash in Rust. It also appears to be the future of Zcash.

Originally developed by Parity, based off [their bitcoin client][pbt], for the Zcash Foundation, [Zebra was announced][zan] in July 2019. In late August development was started over from scratch, to take advantage of modern Rust idioms, to divorce the design from that of bitcoin, and to use a different license. The current version of Zebra is developed by long-time Rust cryptographer [Henry de Valence], co-author of a number of high-profile Rust cryptography libraries, and expert in zero-knowledge proofs.

So now there are _two_ Rust implementations of Zcash, including [parity-zcash] (which presumably inherits the original Zebra codebase).

According to the [Zcash Foundation roadmap][zcr], in the future Zebra will be "the bedrock of our engineering output". So it seems like Zcash is all-in on Rust!

Rust is awesome for blockchain, y'all.

[pbt]: https://github.com/paritytech/parity-bitcoin
[zan]: https://www.prnewswire.com/news-releases/parity-releases-zebra-the-first-alternative-zcash-client-to-the-zcash-foundation-300869620.html
[Henry de Valence]: https://github.com/hdevalence
[parity-zcash]: https://github.com/paritytech/parity-zcash
[zcr]: https://www.zfnd.org/blog/eng-roadmap-2020/

&nbsp;


## Most Active in December

[COMIT][comit]: 113 ([1][comit-mergedpr1], [2][comit-mergedpr2]) merged PRs, 40 ([1][comit-issue1], [2][comit-issue2]) closed issues.

[COMIT]: https://comit.network/
[comit-mergedpr1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-mergedpr2]: https://github.com/comit-network/create-comit-app/pulls?q=is%3Apr+is%3Aclosed+merged%3A2019-12-01..2019-12-31
[comit-issue1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31
[comit-issue2]: https://github.com/comit-network/create-comit-app/issues?q=is%3Aissue+is%3Aclosed+closed%3A2019-12-01..2019-12-31

&nbsp;



## Project updates

#### [**COMIT**](https://comit.network/)

- [Blog: Vision and Mission + 2020 goals](https://blog.coblox.tech/2019/12/05/2020-COMIT-goals.html)
- [PR: Make more use of async/await](https://github.com/comit-network/create-comit-app/pull/305)
- [PR: Refactor toward more idiomatic async code](https://github.com/comit-network/create-comit-app/pull/253)
- [PR: Use clarity instead of emerald-rs](https://github.com/comit-network/create-comit-app/pull/286)


#### [**Enigma**](https://enigma.co/)


#### [**Grin**](https://github.com/mimblewimble/grin)


#### [**Interledger**](https://interledger.org/)


#### [**Near**](https://github.com/nearprotocol/nearcore)


#### [**Nervos CKB**](https://github.com/nervosnetwork/ckb)


#### [**Oasis**](https://github.com/oasislabs)


#### [**Parity** ](https://github.com/paritytech)
- [News: Polymesh — Flexibility through Smart Extensions](https://blog.polymath.network/polymesh-flexibility-through-smart-extensions-c461f1504ce9). Polymath and Parity collaborate on extending Substrate to provide rich interoperability between base layer runtime modules, and dynamically deployed smart contracts.
- [News: The Foundation of a New Internet](https://medium.com/cornellblockchain/the-foundation-of-a-new-internet-86d72d3074eb). A look at Web 3.0 with Polkadot — Cornell Blockchain.
- [News: Kusama Upgrade Bulletin](https://polkadot.network/kusama-upgrade-bulletin-2/). Kusama is about to get a new logic core. Runtime version: 1031; Supported natively by Polkadot v0.7.10.
- [News: We are planning to move Parity Ethereum to a DAO ownership & maintainer model](https://twitter.com/ParityTech/status/1206657981288456193). OpenEthereum will provide the basis for cross-org collaboration to ensure the codebase gets the attention it needs to realize its full potential.
- [News: PolkaWorld Interview House to feature guest speakers and A look at Web 3.0 with Polkadot](https://medium.com/paradigm-fund/polkadot-polkaworld-interview-house-to-feature-guest-speakers-and-a-look-at-web-3-0-with-polkadot-5971256018bb)
- [News: The Inspiration Behind Web3 Grant Winner Attic Lab's Substrate Plugin](https://commonwealth.im/edgeware/proposal/discussion/168-the-inspiration-behind-web3-grant-winner-attic-labs-substrate-plugin)
- [Blog: Have a TEE with Polkadot](https://polkadot.network/have-a-tee-with-polkadot)
- [Blog: Polkadot 2019](https://polkadot.network/polkadot-2019-year-in-review/)
- [Blog: Secure and Decentralized Polkadot Domain Name System](https://medium.com/@chainx_org/secure-and-decentralized-polkadot-domain-name-system-e06c35c2a48d)
- Blog: Polkadot Consensus [Part 1: Introduction](https://polkadot.network/polkadot-consensus-part-1-introduction), [Part 2: GRANDPA](https://polkadot.network/polkadot-consensus-part-2-grandpa/), [Part 3: BABE](https://polkadot.network/polkadot-consensus-part-3-babe/), [Part 4: Security](https://polkadot.network/polkadot-consensus-part-4-security/).
- [Video: Sub0.1: Substrate Ecosystem Overview - Fredrik Harryson](https://www.youtube.com/watch?v=dg50O_wurME)
- [Video: Participating in Kusama with Logan Saether](https://www.youtube.com/watch?v=EqRM11XU9mA&feature=youtu.be)
- [Podcast: How can non money tokens accrue value in crypto](https://podcasts.apple.com/us/podcast/how-can-non-money-tokens-accrue-value-in-crypto-jack/id1350649166) | Jack Platt, Polkadot.
- [Repo: substrate-client-cli](https://github.com/docknetwork/substrate-client-cli). Example command line utility for querying latest state from a substrate based chain.
- [Slides: Plasm Network at Sub0.1](https://speakerdeck.com/sotawatanabe/plasm-network-at-sub0-dot-1-summit). Plasm Network slide deck at Sub0.1. The Plasm team describes what they are working on and what they will implement on Plasm Network.

#### [**Solana**](https://github.com/solana-labs/solana)

- [Blog: Solana in 2019: Growth, Development, and the Road to Mainnet](https://medium.com/solana-labs/solana-in-2019-growth-development-and-the-road-to-mainnet-16b642fd7fb1)
- [Podcast: How Solana Works with Anatoly Yakovenko Ep #2](https://podcasts.apple.com/us/podcast/how-solana-works-with-anatoly-yakovenko-ep-2/id1476353378?i=1000446769632)
- [Video: Solana & SKALE live podcast recording - Jack O'Holleran & Anatoly Yakovenko](https://www.youtube.com/watch?v=fmVuXfwG6eY&feature=youtu.be)
- [Video: Layer 1 Event ft. Solana, NEAR, Harmony, CODA, Nervos](https://www.youtube.com/watch?v=LEKcBeDcEAY)
- [PR: Stabilize fn coverage by creating a clean room](https://github.com/solana-labs/solana/pull/7576) by [@ryoqun](https://github.com/ryoqun)
- [PR: Check for incorrect hash value on snapshot ingest](https://github.com/solana-labs/solana/pull/7559) by [@ryoqun](https://github.com/ryoqun)
- [PR: Improve bench-tps stability](https://github.com/solana-labs/solana/pull/7537) by [@jstarry](https://github.com/jstarry)
- [PR: Update "limit-ledger-size" to use DeleteRange for much faster deletes](https://github.com/solana-labs/solana/pull/7515) by [@sagar-solana](https://github.com/sagar-solana)
- [PR: Strictly sanitize mmapped AppendVec file contents](https://github.com/solana-labs/solana/pull/7464) by [@ryoqun](https://github.com/ryoqun)
- [PR: Add SystemInstruction::CreateAccountWithSeed](https://github.com/solana-labs/solana/pull/7390) by [@rob-solana](https://github.com/rob-solana)

&nbsp;

## Challenges


&nbsp;

## Learning


&nbsp;

## Interesting Things

[Mark Zuckerberg has a big Libra problem](https://www.wired.co.uk/article/libra-ethereum-web-3) by Gavin Wood. Libra is too closely tied to megacorporations to succeed. Platforms built to be open and free will outperform Libra.

[Hold Tight, Here Come the Blockchain Wars](https://www.coindesk.com/hold-tight-here-come-the-blockchain-wars) by Gavin Wood.

&nbsp;

## Events


&nbsp;

## Careers


&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the [#7 draft](), or Tweet [@rust_blockchain](https://twitter.com/rust_blockchain).

**Join the discussion on** [**RiB telegram group**](https://t.me/rustinblockchain) **❤️**