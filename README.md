# Awesome Rust [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)
 A curated list of Rust code and resources.
如果你想贡献，请阅读[this](CONTRIBUTING.md)

## Table of contents
 <!-- toc -->

- [Applications](#applications)
  * [Audio and Music](#audio-and-music)
  * [Cryptocurrencies](#cryptocurrencies)
  * [Database](#database)
  * [Emulators](#emulators)
  * [Games](#games)
  * [Graphics](#graphics)
  * [Image processing](#image-processing)
  * [Industrial automation](#industrial-automation)
  * [Observability](#observability)
  * [Operating systems](#operating-systems)
  * [Payments](#payments)
  * [Productivity](#productivity)
  * [Routing protocols](#routing-protocols)
  * [Security tools](#security-tools)
  * [Simulation](#simulation)
  * [Social networks](#social-networks)
  * [System tools](#system-tools)
  * [Task scheduling](#task-scheduling)
  * [Text editors](#text-editors)
  * [Text processing](#text-processing)
  * [Utilities](#utilities)
  * [Video](#video)
  * [Virtualization](#virtualization)
  * [Web](#web)
  * [Web Servers](#web-servers)
- [Development tools](#development-tools)
  * [Build system](#build-system)
  * [Debugging](#debugging)
  * [Deployment](#deployment)
  * [Embedded](#embedded)
  * [FFI](#ffi)
  * [Formatters](#formatters)
  * [IDEs](#ides)
  * [Profiling](#profiling)
  * [Services](#services)
  * [Static analysis](#static-analysis)
  * [Testing](#testing)
  * [Transpiling](#transpiling)
- [Libraries](#libraries)
  * [Artificial Intelligence](#artificial-intelligence) 人工智能       [Genetic algorithms](#genetic-algorithms)     + [Machine learning](#machine-learning)     + [OpenAI](#openai)
  * [Astronomy](#astronomy)
  * [Asynchronous](#asynchronous)
  * [Audio and Music](#audio-and-music-1)
  * [Authentication](#authentication)
  * [Automotive](#automotive)
  * [Bioinformatics](#bioinformatics)
  * [Caching](#caching)
  * [Cloud](#cloud)
  * [Command-line](#command-line)
  * [Compression](#compression)
  * [Computation](#computation)
  * [Concurrency](#concurrency)
  * [Configuration](#configuration)
  * [Cryptography](#cryptography)
  * [Data processing](#data-processing)
  * [Data streaming](#data-streaming)
  * [Data structures](#data-structures)
  * [Data visualization](#data-visualization)
  * [Database](#database-1)
  * [Date and time](#date-and-time)
  * [Distributed systems](#distributed-systems)
  * [Domain driven design](#domain-driven-design)
  * [eBPF](#ebpf)
  * [Email](#email)
  * [Encoding](#encoding)
  * [Filesystem](#filesystem)
  * [Finance](#finance)
  * [Functional Programming](#functional-programming)
  * [Game development](#game-development)
  * [Geospatial](#geospatial)
  * [Graph algorithms](#graph-algorithms)
  * [Graphics](#graphics-1)
  * [GUI](#gui)
  * [Image processing](#image-processing-1)
  * [Language specification](#language-specification)
  * [Logging](#logging)
  * [Macro](#macro)
  * [Markup language](#markup-language)
  * [Mobile](#mobile)
  * [Network programming](#network-programming)
  * [Parsing](#parsing)
  * [Peripherals](#peripherals)
  * [Platform specific](#platform-specific)
  * [Scripting](#scripting)
  * [Simulation](#simulation-1)
  * [System](#system)
  * [Task scheduling](#task-scheduling-1)
  * [Template engine](#template-engine)
  * [Text processing](#text-processing-1)
  * [Text search](#text-search)
  * [Unsafe](#unsafe)
  * [Video](#video-1)
  * [Virtualization](#virtualization-1)
  * [Web programming](#web-programming)
- [Registries](#registries)
- [Resources](#resources)
- [License](#license)
 <!-- tocstop -->

## Applications
 See also [Rust — Production](https://www.rust-lang.org/production) organizations running Rust in production.

* [alacritty](https://github.com/alacritty/alacritty) — A cross-platform, GPU enhanced terminal emulator
* [Arti](https://gitlab.torproject.org/tpo/core/arti) Arti — 在Rust中实现Tor。(到目前为止，它不是一个非常完整的客户端，但请注意这个空间!)[![Crates.io](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) — An interactive assembly shell written in rust.
* [broot](https://github.com/Canop/broot) 布鲁特 一种查看和导航目录树的新方法 (获取目录的概述，甚至是一个大目录; 找到一个目录，然后对其进行 “cd”; 在搜索时永远不会丢失文件层次结构的轨道; 操作您的文件，...)，进一步阅读[dystroy.org/broot](https://dystroy.org/broot/) [![Latest Version](https://img.shields.io/crates/v/broot.svg)](https://crates.io/crates/broot)
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) cloudflare/boringtun — 一个用户空间WireGuard VPN实现[![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
* [datafusion](https://github.com/apache/arrow-datafusion) — Apache Arrow DataFusion and Ballista query engines
* [denoland/deno](https://github.com/denoland/deno) denoland/deno — 使用V8、Rust和Tokio构建的安全JavaScript/TypeScript运行时[![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
* [doprz/dipc](https://github.com/doprz/dipc) doprz/dipc — 用你最喜欢的调色板/主题转换你最喜欢的图像和壁纸[![crates.io](https://img.shields.io/crates/v/dipc)](https://crates.io/crates/dipc)
* [Factotum](https://github.com/snowplow/factotum) Factotum — [A system to programmatically run data pipelines](https://snowplow.io/blog/introducing-factotum-data-pipeline-runner/)
* [fcsonline/drill](https://github.com/fcsonline/drill) — A HTTP load testing application inspired by Ansible syntax
* [fend](https://github.com/printfn/fend) 挡风板 - 任意精度单位感知计算器[![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
* [Fractalide](https://github.com/fractalide/fractalide) — Simple Rust Microservices
* [habitat](https://github.com/habitat-sh/habitat) — A tool created by Chef to build, deploy, and manage applications.
* [Herd](https://github.com/imjacobclark/Herd) — an experimental HTTP load testing application
* [hickory-dns](https://crates.io/crates/trust-dns) 山核桃-dns — DNS服务器[![Build Status](https://github.com/hickory-dns/hickory-dns/workflows/test/badge.svg?branch=main)](https://github.com/hickory-dns/hickory-dns/actions?query=workflow%3Atest)
* [innernet](https://github.com/tonarino/innernet) - An overlay or private mesh network that uses Wireguard under the hood
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) — A fast, simple and lightweight data collector
* [kalker](https://github.com/PaddiM8/kalker) kalker - 一种科学计算器，支持类似数学的语法，包含用户定义的变量、函数、推导、积分和复数。跨平台WASM支持[![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kytan](https://github.com/changlan/kytan) — High Performance Peer-to-Peer VPN
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) — Ultralight service mesh for Kubernetes.
* [MaidSafe](https://github.com/maidsafe) — A decentralized platform.
* [mdBook](https://github.com/rust-lang/mdBook) mdBook — 从markdown文件创建书籍的命令行实用程序[![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) — A steam and drm-free game registry and launcher for linux and macosx
* [notty](https://github.com/withoutboats/notty) — A new kind of terminal
* [Pijul](https://pijul.org) — A patch-based distributed version control system
* [Rio](https://github.com/raphamorim/rio) - A hardware-accelerated GPU terminal emulator powered by WebGPU, focusing to run in desktops and browsers.
* [rx](https://github.com/cloudhead/rx) — Vi inspired Modern Pixel Art Editor
* [Servo](https://github.com/servo/servo) — A prototype web browser engine
* [shoes](https://github.com/cfal/shoes) - A multi-protocol proxy server
* [shuttle](https://github.com/shuttle-hq/shuttle) — A serverless platform built for Rust
* [Sniffnet](https://github.com/GyulyVGC/sniffnet) 嗅探网 — 跨平台应用程序，轻松监控您的网络流量[![build badge](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)
* [SWC](https://github.com/swc-project/swc) — super-fast TypeScript / JavaScript compiler
* [tiny](https://github.com/osa1/tiny) — A terminal IRC client
* [wasmer](https://github.com/wasmerio/wasmer) wasmer — 支持WASI和Emscripten的安全快速的WebAssembly运行时[![Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld) — Full fake REST API generator
* [wezterm](https://github.com/wez/wezterm) — A GPU-accelerated cross-platform terminal emulator and multiplexer
* [zellij](https://github.com/zellij-org/zellij) — A terminal multiplexer (workspace) with batteries included

### Audio and Music

* [enginesound](https://github.com/DasEtwas/enginesound) — A GUI and command line application used to procedurally generate semi-realistic engine sounds. Featuring in-depth configuration, variable sample rate and a frequency analysis window.
* [figsoda/mmtc](https://github.com/figsoda/mmtc) 无花果/mmtc [[mmtc](https://crates.io/crates/mmtc)] — Minimal mpd terminal client that aims to be simple yet highly configurable [![build-badge](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)
* [Glicol](https://github.com/chaosprint/glicol) — Graph-oriented live coding language written in Rust for collaborative musicking in browsers.
* [ncspot](https://github.com/hrkfdn/ncspot) ncspot - 跨平台ncurses Spotify客户端，灵感来自ncmpc等。[![build badge](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* [Polaris](https://github.com/agersant/polaris) — A music streaming application.
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) Spotify TUI — 用Rust写的终端的Spotify客户端。![Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd) Spotifyd — 作为UNIX守护程序运行的开源Spotify客户端。![Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)
* [WhatBPM](https://github.com/sergree/whatbpm) WhatBPM — 电子舞曲制作人每日静态生成的信息资源。使用Beatport和Spotify等公开可用的数据，对每种EDM类型的最常用值提供每日分析: 节奏，键，根注释等。![Continuous Integration](https://github.com/sergree/whatbpm/actions/workflows/website_build_deploy.yml/badge.svg?branch=main)

### Cryptocurrencies

* [artemis](https://github.com/paradigmxyz/artemis) - A simple, modular, and fast framework for writing MEV bots in Rust.
* [beerus](https://github.com/keep-starknet-strange/beerus) 比勒斯 - Beerus是一个不信任的StarkNet轻客户，⚡炽热的速度⚡由铁锈驱动🦀[![GitHub Workflow Status](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml)
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)] — A Rust library for working with Bitcoin SV .
* [cairo](https://github.com/starkware-libs/cairo) 开罗 - Cairo是第一个用于创建通用计算的可证明程序的图灵完备语言。这也是的母语[StarkNet](https://www.starknet.io/en), a ZK-Rollup using STARK proofs ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)
* [cairo-vm](https://github.com/lambdaclass/cairo-vm) 开罗-vm — Cairo VM的Rust实现[![rust](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml)
* [ChainX](https://github.com/chainx-org/ChainX) — Fully Decentralized Interchain Crypto Asset Management on Polkadot.
* [CITA](https://github.com/citahub/cita) — A high performance blockchain kernel for enterprise users.
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) — Coinbase pro client in Rust, supports sync/async/websocket
* [Diem](https://github.com/diem/diem) — Diem’s mission is to enable a simple global currency and financial infrastructure that empowers billions of people.
* [electrumrs](https://github.com/romanz/electrs) — An efficient re-implementation of Electrum Server in Rust.
* [ethabi](https://github.com/rust-ethereum/ethabi) - Encode and decode smart contract invocations.
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) — Custom Ethereum vanity address generator made in Rust
* [ethers-rs](https://github.com/gakonst/ethers-rs) 醚-rs - 在Rust中完成Ethereum & Celo库和钱包实现。![Build Status](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
* [etk](https://github.com/quilt/etk) - etk is a collection of tools for writing, reading, and analyzing EVM bytecode.
* [Forest](https://github.com/ChainSafe/forest) 森林 - Rust Filecoin实现[![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* [Foundry](https://github.com/foundry-rs/foundry) 铸造厂 - Foundry是用Rust编写的用于以太坊应用程序开发的快速，便携式和模块化工具包。![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
* [Grin](https://github.com/mimblewimble/grin/) — Evolution of the MimbleWimble protocol
* [hdwallet](https://github.com/jjyr/hdwallet) [[hdwallet](https://crates.io/crates/hdwallet)] — BIP-32 HD wallet related key derivation utilities.
* [Holochain](https://github.com/holochain/holochain) 全息链 — 适用于您一直想要构建的所有分布式应用程序的可扩展P2P替代区块链。[![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
* [ibc-rs](https://github.com/informalsystems/hermes) - Rust implementation of the [Interblockchain Communication](https://ibc.cosmos.network/) protocol
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) [[bip39](https://crates.io/crates/bip39)] — Rust implementation of BIP39.
* [interBTC](https://github.com/interlay/interbtc) — Trustless and fully decentralized Bitcoin bridge to Polkadot and Kusama.
* [Joystream](https://github.com/Joystream/joystream) — A user governed video platform
* [Lighthouse](https://github.com/sigp/lighthouse) 灯塔 — Rust以太坊共识层 (CL) 客户端[![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
* [madara](https://github.com/keep-starknet-strange/madara) madara - Kaioshin是一个⚡超快⚡Starknet测序仪，基于底物并用Rust编写。[![GitHub Workflow Status](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml)
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) - Ethereum MEV Inspector in Rust
* [near/nearcore](https://github.com/near/nearcore) — decentralized smart-contract platform for low-end mobile devices.
* [Nervos CKB](https://github.com/nervosnetwork/ckb) — Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network.
* [Nimiq](https://github.com/nimiq/core-rs) — Rust implementation of Nimiq node
* [opensea-rs](https://github.com/gakonst/opensea-rs) - Rust bindings & CLI to the Opensea API and Contracts.
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) — The Parity Bitcoin client
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) — Confidential smart contract blockchain based on Intel SGX and Substrate
* [Polkadot](https://github.com/paritytech/polkadot) — Heterogeneous multi‑chain technology with pooled security
* [revm](https://github.com/bluealloy/revm) - Revolutionary Machine (revm) is a fast Ethereum virtual machine written in rust.
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) — Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) — Bitcoin Lightning library written in Rust. The main crate,`lightning`, does not handle networking, persistence, or any other I/O. Thus,it is runtime-agnostic, but users must implement basic networking logic, chain interactions, and disk storage.po on linking crate.
* [sigma-rust](https://github.com/ergoplatform/sigma-rust) — Rust implementation of ErgoTree interpreter and wallet-related features.
* [Solana](https://github.com/solana-labs/solana) — Incredibly fast, highly scalable blockchain using Proof-of-History.
* [Substrate](https://github.com/paritytech/substrate) — Generic modular blockchain template written in Rust
* [Sui](https://github.com/MystenLabs/sui) — A next-generation smart contract platform with high throughput, low latency, and an asset-oriented programming model powered by the Move programming language.
* [svm-rs](https://github.com/alloy-rs/svm-rs) - Solidity-Compiler Version Manager.
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Rust implementation of Tendermint blockchain data structures and clients
* [wagyu](https://github.com/howardwu/wagyu) [[wagyu](https://crates.io/crates/wagyu)] — Rust library for generating cryptocurrency wallets
* [zcash](https://github.com/zcash/zcash) — Zcash is an implementation of the "Zerocash" protocol.

### Database

* [Atomic-Server](https://github.com/atomicdata-dev/atomic-server/) 原子服务器 [[atomic-server](https://crates.io/crates/atomic_server)] - NoSQL graph database with realtime updates, dynamic indexing and easy-to-use GUI for CMS purposes. [![Release](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml/badge.svg)](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml)
* [CozoDB](https://github.com/cozodb/cozo) 科佐布 - 使用Datalog并专注于图形数据和算法的事务性关系数据库。时间旅行能力，而且快![![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
* [Databend](https://github.com/datafuselabs/databend) Databend - 具有云原生架构的现代实时数据处理和分析DBMS[![Release](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* [DB3 Network](https://github.com/dbpunk-labs/db3) DB3网络 — DB3是一个社区驱动的区块链层2去中心化数据库网络![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/dbpunk-labs/db3/ci.yml?branch=main&style=flat-square)
* [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb) — Distributed SQL database in Rust, written as a learning project.
* [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/) GreptimeDB - 支持PromQL/SQL/Python的开源、云原生、分布式时序数据库。[![CI](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)
* [indradb](https://crates.io/crates/indradb) — Rust based graph database
* [Lucid](https://github.com/lucid-kv/lucid) 清醒 — 高性能和分布式KV存储可通过HTTP API访问。[![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [Materialize](https://github.com/MaterializeInc/materialize) 物化 - 由及时数据流提供支持的流式SQL数据库: heavy_dollar_sign:[![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
* [Neon](https://github.com/neondatabase/neon) Serverless Postgres. We separated storage and compute to offer autoscaling, branching, and bottomless storage.
* [noria](https://github.com/mit-pdos/noria) [[noria](https://crates.io/crates/noria)] — Dynamically changing, partially-stateful data-flow for web application backends
* [ParityDB](https://github.com/paritytech/parity-db) — Fast and reliable database, optimised for read operation
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) — an event sourcing database engine
* [Qdrant](https://github.com/qdrant/qdrant) Qdrant - 具有扩展过滤支持的开源矢量相似性搜索引擎[![Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) RisingWaveLabs/RisingWave - 云中的下一代流式数据库[![CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — A Redis reimplementation in Rust
* [Skytable](https://github.com/skytable/skytable) Skytable — 一个多模型的NoSQL数据库![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* [sled](https://crates.io/crates/sled) 雪橇 — A (beta) 现代嵌入式数据库[![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SurrealDB](https://github.com/surrealdb/surrealdb) SurrealDB — 可扩展的分布式文档图数据库[![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) 终端db - 开源图形数据库和文档存储[![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv) tikv — Rust中的分布式KV数据库[![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx-sys](https://crates.io/crates/mdbx-sys)] — Rust bindings for MDBX, a "fast, compact, powerful, embedded, transactional key-value database, with permissive license". This is a fork of mozilla/lmdb-rs with patches to make it work with libmdbx.
* [WooriDB](https://github.com/naomijub/wooridb) - General purpose time serial database inspired by Crux and Datomic.

### Emulators
另请参见[crates matching keyword 'emulator'](https://crates.io/keywords/emulator)

* CHIP-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) — A WebAssembly CHIP-8 emulator written with Rust
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) — Yet another rust chip8 emulator
* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64) —
* Flash Player
  * [Ruffle](https://github.com/ruffle-rs/ruffle) 荷叶边 — Ruffle是一个用Rust编程语言编写的Adobe Flash Player模拟器。Ruffle使用WebAssembly同时面向桌面和web。[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) —
  * [joamag/boytacean](https://github.com/joamag/boytacean) — GameBoy Color emulator written in Rust that runs on the Web using WebAssembly.
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) — Full featured Cross-platform GameBoy emulator. Forever boys!.
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) —
* Gameboy Advance
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) michelhe/rustboyadvance-ng - RustboyAdvance-ng是一个Gameboy高级模拟器与桌面，android和[WebAssembly](https://michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* GameMaker
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) — OpenGMK is a modern rewrite of the proprietary GameMaker Classic engines, providing a full sourceport of the runner, a decompiler, a TASing framework, and libraries for working with gamedata yourself.
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) — Intel 8080 cpu emulator by Rust
* iOS
  * [touchHLE](https://github.com/hikari-no-yume/touchHLE) — High-level emulator for iPhone OS apps
* iPod
  * [clicky](https://github.com/daniel5151/clicky) — A clickwheel iPod emulator (WIP)
* NES
  * [koute/pinky](https://github.com/koute/pinky) —
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
* Nintendo DS
  * [dust](https://github.com/kelpsyberry/dust) — A Nintendo DS emulator written in Rust
* PlayStation 4
  * [Obliteration](https://github.com/obhq/obliteration) 湮灭 — 用Rust编写的实验性PS4模拟器，适用于Windows，macOS和Linux[![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) rustzx/rustzx — [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### Games
另请参见[Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston)

* [citybound](https://github.com/citybound/citybound) — The city sim you deserve
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) — A renderer for Doom, may progress to being a playable game
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) — A Rust reimplementation of Cave Story engine with some enhancements.
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) — Extensible open world rogue like game with pixel art
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) 大猩猩-devs/ferium — Ferium是一个快速和功能丰富的CLI程序，用于从Modrinth、CurseForge和GitHub版本下载和更新Minecraft mods，以及从Modrinth和CurseForge下载和更新modpacks![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — A minimalistic music video game which supports the BMS format
* [maras-archive/rsnake](https://github.com/maras-archive/rsnake) — Snake written in Rust.
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi) mtkennerly/ludusavi — 用于pc游戏保存的备份工具[![build badge](https://img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?logo=github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![crate](https://img.shields.io/crates/v/ludusavi?logo=rust)](https://crates.io/crates/ludusavi)
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) — A small 2D turn-based hexagonal strategy game
* [rhex](https://github.com/dpc/rhex) — hexagonal ascii roguelike
* [rsaarelm/magog](https://github.com/rsaarelm/magog) — A roguelike game in Rust
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) — Mk48.io is an online multiplayer naval combat game
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — A Sokoban implementation
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) thetawavegame/thetawave-legacy - 一款致力于成为新游戏开发者做出第一贡献的切入点的太空射击游戏。![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) — Quake map renderer in Rust
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - Single player typing test game written for the terminal
* [Veloren](https://gitlab.com/veloren/veloren) Veloren — 一个开放的世界，开源多人体素RPG游戏目前在alpha开发中[![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [Zone of Control](https://github.com/ozkriff/zoc) — A turn-based hexagonal strategy game

### Graphics

* [dps/rust-raytracer](https://github.com/dps/rust-raytracer) - An implementation of a very simple raytracer based on Ray Tracing in One Weekend by Peter Shirley in Rust.
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) — converts ASCII diagrams into SVG graphics
* [KaminariOS/rustracer](https://github.com/KaminariOS/rustracer) — A PBR glTF 2.0 renderer based on Vulkan ray-tracing, written in Rust.
* [Limeth/euclider](https://github.com/Limeth/euclider) — A real-time 4D CPU ray tracer
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) — An SVG rendering library.
* [rodrigorc/papercraft](https://github.com/rodrigorc/papercraft) - A tool to unwrap 3D models and create them in paper with scissors and glue.
* [rustq/vue-skia](https://github.com/rustq/vue-skia) — Skia based 2d graphics vue rendering library. It is based on Rust to implement software rasterization to perform rendering.
* [turnage/valora](https://crates.io/crates/valora) 周转/valora — 生成美术图书馆![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) — A ray tracer

### Image processing

* [Imager](https://github.com/imager-io/imager) — Automated image optimization.
* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) shssoichiro/oxipng [[oxipng](https://crates.io/crates/oxipng)] — Multithreaded PNG optimizer written in Rust. [![Build Status](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Industrial automation

* [locka99/opcua](https://github.com/locka99/opcua) — A pure rust [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) library.
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) — A [tokio](https://tokio.rs)-based [modbus](https://modbus.org) library.

### Observability

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino) — A high-performance scalable StatsD compatible server.
* [OpenTelemetry](https://crates.io/crates/opentelemetry) 开放遥测术 — OpenTelemetry提供一组api、库、代理和收集器服务，用于从应用程序捕获分布式跟踪和指标。您可以使用Prometheus、Jaeger和其他可观察性工具来分析它们。[![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) Quickwit-oss/quickwit - 云原生和高成本效益的日志管理搜索引擎。[![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - A power consumption monitoring agent, to track host and each service power consumption and enable designing systems and applications for more sustainability. Designed to fit any monitoring toolchain (already supports prometheus, warp10, riemann...)
* [vectordotdev/vector](https://github.com/vectordotdev/vector) — A High-Performance, Logs, Metrics, & Events Router.

### Operating systems
另请参见[A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison)
* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)  — An OS for armv8-a architecture.
* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero) — A modern, unix-like operating system following the monolithic kernel design.
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) —
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) —
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) 忒修斯-os/忒修斯 — 在纯Rust中从头开始编写的安全语言，单地址空间和单特权级别操作系统-[![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock) — A secure embedded operating system for Cortex-M based microcontrollers

### Payments

* [hyperswitch](https://github.com/juspay/hyperswitch) 超级开关 — 一个开源支付协调器，可让您与多个支付处理器连接，并毫不费力地路由支付流量，所有这些都需要一个API集成![GitHub last commit](https://img.shields.io/github/last-commit/juspay/hyperswitch?style=flat-square)

### Productivity

* [Bartib](https://github.com/nikolassv/bartib) 巴提布 [[Bartib](https://crates.io/crates/bartib)] - A simple timetracker for the command line [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [espanso](https://github.com/espanso/espanso) espanso — 用Rust编写的跨平台文本扩展器[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka) — A CLI tool to input and store your ideas without leaving the terminal
* [Furtherance](https://github.com/lakoliu/Furtherance) - Time tracking app built with Rust and GTK4
* [illacloud/illa](https://github.com/illacloud/illa) [[ILLA Cloud](https://www.illacloud.com/)] - Low-code internal tool builder written with Rust.
* [LLDAP](https://github.com/lldap/lldap) - Simplified LDAP interface for authentication.
* [pier-cli/pier](https://github.com/pier-cli/pier) — A central repository to manage (add, search metadata, etc.) all your one-liners, scripts, tools, and CLIs

### Routing protocols

* [Holo](https://github.com/rwestphal/holo) - Holo is a suite of routing protocols designed to support high-scale and automation-driven networks
* [RustyBGP](https://github.com/osrg/rustybgp) - BGP implemented in the Rust Programming Language

### Security tools

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) AFLplusplus/LibAFL - 高级模糊库-将你的模糊器放在铁锈中!跨核心和机器扩展。适用于Windows、Android、MacOS、Linux、no_std等。[![build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [cargo-audit](https://crates.io/crates/cargo-audit) - Audit Cargo.lock for crates with security vulnerabilities
* [cargo-auditable](https://crates.io/crates/cargo-auditable) - Make production Rust binaries auditable
* [cargo-crev](https://crates.io/crates/cargo-crev) - A cryptographically verifiable code review system for the cargo (Rust) package manager.
* [cargo-deny](https://crates.io/crates/cargo-deny) - Cargo plugin to help you manage large dependency graphs
* [Cherrybomb](https://github.com/blst-security/cherrybomb) - Stop half-done API specifications with a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.
* [cotp](https://github.com/replydev/cotp) - Trustworthy, encrypted, command-line TOTP/HOTP authenticator app with import functionality.
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - A simple, fast, recursive content discovery tool written in Rust (
* [Inspektor](https://github.com/inspektor-dev/inspektor) - A database protocol-aware proxy that is used to enforce access policies 👮
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) — A scriptable network authentication cracker
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) — A TCP connection hijacker, rust rewrite of shijack
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) — A semi-automatic OSINT framework and package manager
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) — A secure multithreaded packet sniffer
* [ObserverWard](https://github.com/0x727/ObserverWard) — Community based web technologies analysis tool.
* [ripasso](https://github.com/cortex/ripasso/) — A password manager, filesystem compatible with pass
* [rustscan/rustscan](https://github.com/RustScan/RustScan) rustscan/rustscan — 使用此端口扫描工具使Nmap更快[![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)

### Simulation

* [hEngine](https://github.com/hashintel/hash/tree/main/apps/engine) - A Rust-implemented computational simulation engine, supporting large-scale agent-based modelling, with simulation logic written in JavaScript and Python.

### Social networks

* Mastodon
  * [Rustodon](https://github.com/rustodon/rustodon) - A Mastodon-compatible, ActivityPub-speaking server in Rust

### System tools

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) ajeetdsouza/zoxide — 学习您的习惯的 “cd” 的快速替代方案[![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [Alonely0/Voila](https://github.com/Alonely0/Voila) Alonely0/Voila — Voila是通过CLI工具启动的特定于域的语言，用于以快速可靠的方式大量操作文件和目录。[![Linux build](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml) [![Windows build](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
* [atuin](https://github.com/atuinsh/atuin) [[atuin](https://crates.io/crates/atuin)] — Atuin replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [bandwhich](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool
* [bottom](https://github.com/ClementTsang/bottom) 底部 - 另一个跨平台的图形流程/系统监视器。[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* [brocode/fblog](https://github.com/brocode/fblog) — Small command-line JSON Log viewer
* [bustd](https://github.com/vrmiguel/bustd) bustd - 轻量级进程杀手守护程序，用于处理Linux上的内存不足情况。[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* [buster/rrun](https://github.com/buster/rrun) — A command launcher for Linux, similar to gmrun
* [cantino/mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scott!
* [crabz](https://github.com/sstadick/crabz) 克拉布 - 多线程压缩和解压缩CLI工具[![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) cristianoliveira/funzzy — 一个可配置的文件系统观察者的启发[entr](http://eradman.com/entrproject/)
* [dalance/procs](https://github.com/dalance/procs) 达兰斯/procs — Rust编写的 “p” 的现代替代品[![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* [ddh](https://github.com/darakian/ddh) — Fast duplicate file finder
* [diskonaut](https://github.com/imsnif/diskonaut) — Terminal visual disk space navigator
* [dust](https://github.com/bootandy/dust) — A more intuitive version of du
* [eza-community/eza](https://github.com/eza-community/eza) — A replacement for 'ls'
* [fselect](https://crates.io/crates/fselect) — Find files with SQL-like queries
* [gitui](https://github.com/extrawurst/gitui) 吉图 - 用Rust编写的git的快速终端客户端。[![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
* [GQL](https://github.com/amrdeveloper/gql) — A SQL like query language to run on .git files.
* [j0ru/kickoff](https://github.com/j0ru/kickoff) j0ru/启动 - 快速和活泼的wayland程序启动器[![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
* [Kondo](https://github.com/tbillington/kondo) - CLI & GUI tool for deleting software project artifacts and reclaiming disk space
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)] — xargs + awk with pattern matching support
* [lotabout/skim](https://github.com/lotabout/skim) — A fuzzy finder in pure rust
* [lsd](https://github.com/lsd-rs/lsd) lsd — 一个有很多漂亮颜色和令人敬畏的图标的ls[![build](https://github.com/lsd-rs/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/lsd-rs/lsd/actions)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) — Flexible and fast BitTorrent daemon.
* [m4b/bingrep](https://github.com/m4b/bingrep) — Greps through binaries from various OSs and architectures, and colors them.
* [mdgaziur/findex](https://github.com/mdgaziur/findex) - Findex is a highly customizable application finder written in Rust and uses GTK3
* [mitnk/cicada](https://github.com/mitnk/cicada) — A bash-like Unix shell
* [mmstick/concurr](https://github.com/mmstick/concurr) — Alternative to GNU Parallel w/ a client-server architecture
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) — GTK3 application for previewing and installing Google's fonts
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) — A tv series renaming application with an optional GTK3 frontend.
* [mxseev/logram](https://github.com/mxseev/logram) — Push log files' updates to Telegram
* [nickgerace/gfold](https://github.com/nickgerace/gfold) 尼克格拉斯/gfold [[gfold](https://crates.io/crates/gfold)] - CLI tool to help keep track of multiple Git repositories [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
* [nivekuil/rip](https://github.com/nivekuil/rip) - A safe and ergonomic alternative to `rm`
* [nushell/nushell](https://github.com/nushell/nushell) - A new type of shell
* [orhun/kmon](https://github.com/orhun/kmon) orhun/kmon — Linux内核管理器和活动监视器![https://github.com/orhun/kmon/actions](https://img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml?branch=master&label=build)
* [orhun/systeroid](https://github.com/orhun/systeroid) orhun/systeroid — 具有终端用户界面的更强大的sysctl(8) 替代品![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml?branch=main&label=build)
* [ouch](https://github.com/ouch-org/ouch) 哎哟 - 命令行上的无痛压缩和解压缩[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* [pkolaczk/fclones](https://github.com/pkolaczk/fclones) — Efficient duplicate file finder and remover
* [pop-os/popsicle](https://github.com/pop-os/popsicle) — GTK3 & CLI utility for flashing multiple USB devices in parallel
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) — Linux power management daemon (DBus-interface) with CLI tool.
* [pueue](https://github.com/nukesor/pueue) 普尤 — 管理长时间运行的shell命令。[![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
* [qarmin/cakawka](https://github.com/qarmin/czkawka) qarmin/cakawka - 多功能应用程序查找重复，空文件夹，类似的图像等。[![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
* [redox-os/ion](https://github.com/redox-os/ion) — Next-generation system shell
* [sharkdp/bat](https://github.com/sharkdp/bat) sharkdp/bat — 有翅膀的猫 (1) 克隆。[![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd) sharkdp/fd — 一个简单，快速和用户友好的替代发现。[![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex) — A colorized hexdump terminal utility.
* [supercilex/fuc](https://github.com/supercilex/fuc) - Fast `cp` and `rm` commands
* [trippy](https://github.com/fujiapple852/trippy) trippy - 网络诊断工具[![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* [uutils/coreutils](https://github.com/uutils/coreutils) uutils/coreutils — GNU cortils的跨平台Rust重写[[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [watchexec](https://github.com/watchexec/watchexec) — Executes commands in response to file modifications
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) — counts the lines of code

### Task scheduling

* [delicate](https://github.com/BinChengZhao/delicate) 精致 — 用rust编写的轻量级分布式任务调度平台。[![Build Status](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### Text editors

* [amp](https://amp.rs) — Inspired by Vi/Vim.
* [emacs-ng](https://github.com/emacs-ng/emacs-ng) — Complementing the C codebase with rust code to introduce new features.
* [gchp/iota](https://github.com/gchp/iota) — A simple text editor
* [helix](https://github.com/helix-editor/helix) 螺旋线 — 受Neovim/Kakoune启发的后现代模态文本编辑器。[![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) ilai-deutel/kibi — 一个微型 (≤ 1024 LOC) 文本编辑器，具有语法突出显示，增量搜索等功能。[![build badge](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* [Lapce](https://github.com/lapce/lapce) Lapce — 一个用Rust编写的后端的现代编辑器。从停产中获取灵感[xi-editor](https://github.com/xi-editor/xi-editor)
* [mathall/rim](https://github.com/mathall/rim) — Vim-like text editor written in Rust
* [ox](https://github.com/curlpipe/ox) — An independent Rust text editor that runs in your terminal!
* [vamolessa/pepper](https://github.com/vamolessa/pepper) vamolessa/胡椒 [[pepper](https://crates.io/crates/pepper)] — An opinionated modal editor to simplify code editing from the terminal [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)

### Text processing

* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) dominikwilkowski/cfonts [[cfonts](https://crates.io/crates/cfonts)] — Sexy ANSI fonts for the console ![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [grex](https://github.com/pemistahl/grex) — A command-line tool and library for generating regular expressions from user-provided test cases
* [jqnatividad/qsv](https://github.com/jqnatividad/qsv) jqnatividad/qsv [[qsv](https://crates.io/crates/qsv)] — A high performance CSV data-wrangling toolkit. Forked from xsv, with 34+ additional commands & more. [![Linux build status](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml) [![Windows build status](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml) [![macOS build status](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) — A simple and fast string search tool for human beings
* [Melody](https://github.com/yoav-lavi/melody) 旋律 - 一种编译为正则表达式的语言，旨在更容易阅读和维护[![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) — ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc.
* [replicadse/complate](https://github.com/replicadse/complate) 复制/complate — 一个终端内文本模板工具，用于标准化消息 (如GIT提交)。[![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* [ripgrep](https://crates.io/crates/ripgrep) — combines the usability of The Silver Searcher with the raw speed of grep
* [ruplacer](https://github.com/your-tools/ruplacer) 红宝石 — 查找和替换源文件中的文本[![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [sd](https://crates.io/crates/sd) — Intuitive find & replace CLI
* [sstadick/hck](https://github.com/sstadick/hck) sstadick/hck - 更快，更有特色的下降，以取代 “削减”[![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) — Find files (ff) by name!
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[bytelines](https://crates.io/crates/bytelines)] — Read input lines as byte slices for high efficiency.
* [whitfin/runiq](https://github.com/whitfin/runiq) — an efficient way to filter duplicate lines from unsorted input.
* [xsv](https://crates.io/crates/xsv) — A fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.)

### Utilities

* [1History](https://github.com/1History/1History) 1历史 — 命令行界面将Firefox/Chrome/Safari历史记录备份到一个SQLite文件[![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* [brycx/checkpwn](https://github.com/brycx/checkpwn) — A Have I Been Pwned (HIBP) command-line utility tool that lets you easily check for compromised accounts and passwords.
* [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager) — An unofficial client to install Unreal Engine, download and manage purchased assets, projects, plugins and games from the Epic Games Store.
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) evansmurithi/斗篷 — 一个命令行OTP (一次性密码) 验证器应用程序。![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) — A lightning fast version of tmux-fingers written in Rust, copy/pasting tmux like vimium/vimperator.
* [guoxbin/dtool](https://github.com/guoxbin/dtool) — A useful command-line tool collection to assist development including conversion, codec, hashing, encryption, etc.
* [mprocs](https://github.com/pvolok/mprocs) — TUI for running multiple processes
* [mrjackwills/oxker](https://github.com/mrjackwills/oxker) [[oxker](https://crates.io/crates/oxker)] - A simple tui to view & control docker containers.
* [nix-community/nix-init](https://github.com/nix-community/nix-init) nix-community/nix-init — 使用哈希预取，依赖性推断，许可证检测等从url生成Nix包[![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
* [nix-community/nix-melt](https://github.com/nix-community/nix-melt) nix-社区/nix-melt — 护林员般的片状。锁定查看器[![build-badge](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)
* [nix-community/nurl](https://github.com/nix-community/nurl) nix-社区/nurl [[nurl](https://crates.io/crates/nurl)] — Generate Nix fetcher calls from repository URLs [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
* [nomino](https://github.com/yaa110/nomino) — Batch rename utility for developers
* [raftario/licensor](https://github.com/raftario/licensor) raftario/许可方 — 将许可证写入stdout[![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) 铁锈-平行 - 使用Tokio并行执行命令的快速命令行应用程序。与GNU Parallel或xargs类似的接口。[![Crate](https://img.shields.io/crates/v/rust-parallel.svg?logo=rust)](https://crates.io/crates/rust-parallel) [![Build Status](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml/badge.svg)](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) — A remote desktop software, great alternative to TeamViewer and AnyDesk.
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) 乡村风格-rs/乡村风格 [[rustic-rs](https://crates.io/crates/rustic-rs)] — Fast, encrypted, deduplicated backups powered by Rust. [![Version](https://img.shields.io/crates/v/rustic-rs.svg)](https://crates.io/crates/rustic-rs)
* [suckit](https://github.com/Skallwar/suckit) 吸盘 - 递归访问网站内容并将其下载到您的磁盘。[![Crate](https://img.shields.io/crates/v/suckit.svg?logo=rust)](https://crates.io/crates/suckit) [![Build Status](https://github.com/Skallwar/suckit/workflows/Build%20and%20test/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)
* [tversteeg/emplace](https://github.com/tversteeg/emplace) — Synchronize installed packages on multiple machines
* [vamolessa/verco](https://github.com/vamolessa/verco) [[verco](https://crates.io/crates/verco)] — A simple Git/Hg tui client focused on keyboard shortcuts
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) — Alternative implementation of the Bitwarden server API written in Rust
* [warpdotdev/Warp](https://github.com/warpdotdev/Warp) :heavy_dollar_sign: — Warp is a blazingly-fast modern Rust based GPU-accelerated terminal built to make you and your team more productive.
* [wrestic](https://github.com/alvaro17f/wrestic) —  👽 A wrapper around restic built in rust
* [yaa110/cb](https://github.com/yaa110/cb) — Command line interface to manage clipboard

### Video

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[yaydl](https://crates.io/crates/yaydl)] - A simple video downloader
* [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow) - Video stabilization application using gyroscope data
* [harlanc/xiu](https://github.com/harlanc/xiu) 哈兰克/修 — 由纯rust (rtmp/httpflv/hls/relay) 提供的功能强大且安全的实时服务器。[![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* [vidmerger](https://github.com/TGotwig/vidmerger) — 📼 Merge video & audio files via CLI
* [xiph/rav1e](https://github.com/xiph/rav1e) — The fastest and safest AV1 encoder.

### Virtualization

* [containers/youki](https://github.com/containers/youki) 容器/youki — Rust中的容器运行时[![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) 鞭炮-微vm/鞭炮 — 用于容器工作负载的轻量级虚拟机[Firecracker Microvm](https://firecracker-microvm.github.io/)
* [tailhook/vagga](https://github.com/tailhook/vagga) — A containerization tool without daemons

### Web

* [cfal/tobaru](https://github.com/cfal/tobaru) - Port forwarder with allowlists, IP and TLS SNI/ALPN rule-based routing, iptables support, round-robin forwarding (load balancing), and hot reloading.
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) LemmyNet/lemmy — 用于fediverse的链接聚合器/reddit克隆[![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* [libreddit](https://github.com/libreddit/libreddit) - An alternative private front-end to Reddit
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) MASQ-项目/节点 — MASQ节点软件为全球用户提供了一个分散的节点网状网络，以访问正常的互联网内容-Tor和VPN之外的技术的下一个发展[![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume) — ActivityPub federating blogging application
* [Revolt/backend](https://github.com/revoltchat/backend) - User-first chat platform built with modern web technologies.

### Web Servers

* [emanuele-em/man-in-the-middle-proxy](https://github.com/emanuele-em/man-in-the-middle-proxy) Emanuele-em/中间人代理 — MITM代理!具有SSL/TLS功能的HTTP/1、HTTP/2和WebSockets工具包[![Rust](https://github.com/emanuele-em/man-in-the-middle-proxy/actions/workflows/rust.yml/badge.svg)](https://github.com/emanuele-em/man-in-the-middle-proxy/actions/workflows/rust.yml)
* [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder) - 🪂 Beautiful HTTP/Bittorrent server without the hassle. Secure - GUI - Pretty - Fast
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) mufeedvh/binserve — 一个快速的静态web服务器，在一个二进制文件中具有路由，模板和安全性，您可以使用零代码进行设置[![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste) orhun/rustypaste — 最小文件上传/粘贴服务![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml?branch=master&label=build)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) ronanyeah/铁锈-hasura — 演示如何将Rust GraphQL服务器用作远程模式[Hasura](https://hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* [static-web-server](https://github.com/static-web-server/static-web-server) 静态web服务器 — 用于静态文件服务的超快且异步的web服务器。⚡[![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) svenstaro/迷你服务器 — 一个小的，自包含的跨平台CLI工具，允许您只抓取二进制文件并通过HTTP提供一些文件[![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) — Host These Things Please — A basic http server for hosting a folder fast and simply
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) — simple static http server
* [wyhaya/see](https://github.com/wyhaya/see) — Static HTTP file server

## Development tools

* [bacon](https://github.com/Canop/bacon) — background rust code checker, similar to cargo-watch
* [clippy](https://crates.io/crates/clippy) — Rust lints
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) 堵塞-工具/堵塞-cli — 从git元数据生成变更日志 ([conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))
* [comtrya](https://github.com/comtrya/comtrya) comtrya — localhost/dotfiles的配置管理工具[![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* [create-rust-app](https://github.com/Wulf/create-rust-app) create-rust-app — 通过运行一个命令来设置现代rust react web应用程序。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — create ctags/etags for a cargo project and all of its dependencies
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) datanymizer/datanymizer - 具有灵活规则的强大数据库匿名器[![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* [delta](https://crates.io/crates/git-delta) 三角洲 — git和diff输出的语法荧光笔[![build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) dotenv-短绒 — Linter for '.env' 文件[![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* [frolic](https://github.com/FrolicOrg/Frolic)  — An API layer to build customer facing dashboards 10x faster
* [fw](https://github.com/brocode/fw) 前 — 工作空间生产力助推器[![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [geiger](https://github.com/rust-secure-code/cargo-geiger) 盖革 — 列出与Rust crate中不安全Rust代码的使用及其所有依赖项相关的统计信息的程序[![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-cliff](https://github.com/orhun/git-cliff) git-cliff — 遵循常规提交规范的高度可定制的变更日志生成器![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml?branch=main&label=build)
* [git-journal](https://github.com/saschagrunert/git-journal/) — The Git Commit Message and Changelog Generation Framework
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) hot-lib-reloader — 热重载Rust代码[![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [intelli-shell](https://github.com/lasantosr/intelli-shell) intelli-shell - 书签命令与占位符和搜索或自动完成在任何时间[![crate](https://img.shields.io/crates/v/intelli-shell.svg)](https://crates.io/crates/intelli-shell) [![build badge](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml)
* [just](https://github.com/casey/just) — A handy command runner for project-specific tasks
* [mask](https://github.com/jacobdeichert/mask) 面具 — 由简单markdown文件定义的CLI任务运行程序[![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* [Module Linker](https://github.com/fiatjaf/module-linker) — Extension that adds `<a>` links to references in `mod`, `use` and `extern crate` statements at GitHub.
* [ptags](https://github.com/dalance/ptags) — A parallel universal-ctags wrapper for git repository
* [Racer](https://github.com/racer-rust/racer) — code completion for Rust
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) Rust搜索扩展 — 一个方便的浏览器扩展，用于在地址栏 (omnibox) 中搜索板条箱和文档。[![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  — automatically applies the suggestions made by rustc
* [Rustup](https://github.com/rust-lang/rustup) Rustup — Rust工具链安装程序[![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto) scriptisto 与语言无关的 “shebang解释器”，使您能够用编译语言编写一个文件脚本。[![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### Build system

* [Cargo](https://crates.io/) — the Rust package manager
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) 货物-所有功能 - 一个可配置的子命令，以简化测试，构建和更多的功能的所有组合[![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) — A utility to compare Rust micro-benchmarks
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) — A cargo extension that can generate BitBake recipes utilizing the classes from meta-rust
  * [cargo-cache](https://crates.io/crates/cargo-cache) 货物缓存 — 检查/管理/清理您的货物缓存 ('~/.cargo/' ${CARGO_HOME}'), 打印尺寸等[![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) — A wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks
  * [cargo-commander](https://crates.io/crates/cargo-commander) 货舱-指挥官 — “Cargo” 的子命令，用于运行CLI命令，类似于 “package.Json” 中的脚本部分的工作方式[![Build and test](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml)
  * [cargo-count](https://crates.io/crates/cargo-count) — lists source code counts and details about cargo projects, including unsafe statistics
  * [cargo-deb](https://crates.io/crates/cargo-deb) — Generates binary Debian packages
  * [cargo-deps](https://crates.io/crates/cargo-deps) — build dependency graphs of Rust projects
  * [cargo-do](https://crates.io/crates/cargo-do) — run multiple cargo commands in a row
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) — cargo extension that can generate ebuilds using the in-tree eclasses
  * [cargo-edit](https://crates.io/crates/cargo-edit) — allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) A generator of a rust project by leveraging a pre-existing git repository as a template.
  * [cargo-graph](https://crates.io/crates/cargo-graph) — updated fork of `cargo-dot` with additional features. Unmaintained, see `cargo-deps`
  * [cargo-info](https://crates.io/crates/cargo-info) — queries crates.io for crates details from command line
  * [cargo-license](https://crates.io/crates/cargo-license) — A cargo subcommand to quickly view the licenses of all dependencies.
  * [cargo-limit](https://crates.io/crates/cargo-limit) 货物-限制 — 噪音较小的货物: 跳过警告，直到错误被修复，Neovim集成等。[![build badge](https://github.com/alopatindev/cargo-limit/actions/workflows/rust.yml/badge.svg)](https://github.com/alopatindev/cargo-limit/actions)
  * [cargo-make](https://crates.io/crates/cargo-make) 货舱-制造 — Rust任务运行器和构建工具。[![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules) — A cargo plugin for showing a tree-like overview of a crate's modules.
  * [cargo-multi](https://crates.io/crates/cargo-multi) — runs specified cargo command on multiple crates
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) — displays when newer versions of Rust dependencies are available, or out of date
  * [cargo-rdme](https://github.com/orium/cargo-rdme) 货物-rdme [[cargo-rdme](https://crates.io/crates/cargo-rdme)] — Cargo subcommand to create your README from your crate’s documentation. [![build badge](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)
  * [cargo-release](https://crates.io/crates/cargo-release) 货物-放行 — 发布git管理的货物项目，构建，标记，发布，doc和推送的工具[![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) — lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem
  * [cargo-udeps](https://github.com/est31/cargo-udeps) [[cargo-udeps](https://crates.io/crates/cargo-udeps)] — find unused dependencies
  * [cargo-update](https://crates.io/crates/cargo-update) — cargo subcommand for checking and applying updates to installed executables
  * [cargo-watch](https://crates.io/crates/cargo-watch) — utility for cargo to compile projects when sources change
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) — Expand macros in your source code
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) — useful for integrating a Rust library into a CMake project
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — an example project showing usage of CMake with Rust
* [Fleet](https://github.com/dimensionhq/fleet) [[fleet-rs](https://crates.io/crates/fleet-rs)] - The blazing fast build tool for Rust.
* Github actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) — rust github action
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) — GitHub Actions for mdBook
* [Nix](https://nixos.org/)
  * [nix-community/fenix](https://github.com/nix-community/fenix) nix-社区/fenix — nix的Rust工具链和rust分析器[![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)

### Debugging

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) — Browser based frontend for gdb to debug C, C++, Rust, and go.
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) CodeLLDB — 的LLDB扩展[Visual Studio Code](https://code.visualstudio.com/)

### Deployment

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) — Docker images for compiling static Rust binaries using musl-libc and musl-gcc, with static versions of useful C libraries
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) — An example project for very small rust docker images
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) — A multiple version (with musl tools) Rust Docker image
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - A tool and pre-built images for caching compiling remote dependencies between Docker builds.
  * [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross) rust-cross/rust-musl-cross — 使用musl-cross编译静态Rust二进制文件的Docker映像[![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) — the official Rust Docker image
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) — A buildpack for Rust applications on Heroku
* [MarcoIeni/release-plz](https://github.com/MarcoIeni/release-plz) MarcoIeni/发布-plz [[release-plz](https://crates.io/crates/release-plz)] — Release Rust crates from CI, with changelog generation and semver check. [![build badge](https://github.com/MarcoIeni/release-plz/workflows/CI/badge.svg)](https://github.com/MarcoIeni/release-plz/actions)

### Embedded

[Rust Embedded](https://rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) Reusable components for the Arduino Uno.
* Cross compiling
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) — everything you need to know about cross compiling Rust programs
  * [japaric/xargo](https://github.com/japaric/xargo) — effortless cross compilation of Rust programs to custom bare-metal targets like ARM Cortex-M
* Espressif
  * [esp-rs](https://github.com/esp-rs) home to a number of community projects enabling the use of the Rust programming language on various SoCs and modules produced by Espressif Systems.
* Firmware
  * [oreboot/oreboot](https://github.com/oreboot/oreboot) — oreboot is a fork of coreboot, with C removed, written in Rust
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) — A Rust HAL for the nRF family of devices

### FFI
另请参见[Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html), [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples)

* C
  * [mozilla/cbindgen](https://github.com/mozilla/cbindgen) — generates C header files from Rust source files. Used in Gecko for WebRender
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) 德托内/cxx — Rust和C之间的安全互操作[![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) 铁锈-cpp - 直接在Rust中嵌入C代码。[![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — A Rust bindings generator
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) — safe Rust bridge for creating Erlang NIF functions
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) — use Java from Rust
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — use Rust from Java
  * [j4rs](https://crates.io/crates/j4rs) — use Java from Rust
  * [jni](https://crates.io/crates/jni) — use Rust from Java
  * [jni-sys](https://crates.io/crates/jni-sys) — Rust definitions corresponding to jni.h
  * [rucaja](https://crates.io/crates/rucaja) — use Java from Rust
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Lua 5.3 bindings for Rust
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) — Safe Rust bindings to Lua 5.1
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rlua](https://crates.io/crates/td_rlua)] — Zero-cost high-level lua 5.3 wrapper for Rust
  * [tomaka/hlua](https://github.com/tomaka/hlua) — Rust library to interface with Lua
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — mruby safe bindings for Rust
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - Easy way to generate nodejs module using Rust
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) — Rust bindings for writing safe and fast native Node.js modules
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust
* PHP
  * [phper-framework/phper](https://github.com/phper-framework/phper) — The framework that allows us to write PHP extensions using pure and safe Rust whenever possible
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python bindings
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) — extension for python setuptools that allows you to distribute dynamic linked libraries in Python wheels in the most portable way imaginable.
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) — Rust bindings for the Python interpreter
  * [RustPython](https://github.com/RustPython/RustPython) RustPython — 用Rust编写的Python解释器[![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
* Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — native Ruby extensions written in Rust
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) — native Ruby extensions written in Rust and vice versa
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain) rhysd/wain - wain: 零依赖的安全Rust中从头开始的WebAssembly解释器[![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — A project for facilitating high-level interactions between wasm modules and JS.
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — :package: :sparkles: pack up the wasm and publish it to npm!

### Formatters

* [dprint](https://github.com/dprint/dprint) dprint — 可插入和可配置的代码格式化平台[![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust) 更漂亮的铁锈 — 自以为是的Rust代码格式化程序，可自动修复不良语法 ([Prettier](https://prettier.io/) community plugin)
* [rustfmt](https://github.com/rust-lang/rustfmt) — Rust code formatter maintained by the Rust team and included in cargo

### IDEs
另请参见[Are we (I)DE yet?](https://areweideyet.com/) and [Rust Tools](https://www.rust-lang.org/tools)

  * [Atom](https://github.blog/2022-06-08-sunsetting-atom/)
    * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) — Rust IDE support for Atom, powered by the Rust Language Server (RLS)
  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) emacs-racer — 自动完成 (另请参见[company](https://company-mode.github.io) and [auto-complete](https://github.com/auto-complete/auto-complete))
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) flycheck-铁锈 — Rust支持[Flycheck](https://github.com/flycheck/flycheck)
    * [rust-mode](https://github.com/rust-lang/rust-mode) — Rust Major Mode
    * [rustic](https://github.com/brotzeit/rustic) 质朴 - Emacs的Rust开发环境[![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * [gitpod.io](https://gitpod.io) — Online IDE with full Rust support based on Rust Language Server
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) native support for rust and cargo since Version 3.22.2
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) —
  * [Kakoune](http://kakoune.org/)
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
  * [lapce](https://github.com/lapce/lapce) lapce — 用Rust编写的闪电般快速且功能强大的代码编辑器。[![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
  * [Ride](https://github.com/madeso/ride) —
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) — official Rust package
  * [Vim](https://vim.sourceforge.io/) — the ubiquitous text editor
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
    * [crates.nvim](https://github.com/Saecki/crates.nvim) - plugin that helps to managing crates.io dependencies.
    * [rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - Tools for better development in rust using neovim's builtin lsp
    * [rust.vim](https://github.com/rust-lang/rust.vim) — provides file detection, syntax highlighting, formatting, Syntastic integration, and more.
    * [vim-racer](https://github.com/racer-rust/vim-racer) — allows vim to use [Racer](https://github.com/racer-rust/racer) for Rust code completion and navigation.
  * Visual Studio
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) dgriffen/rls-vs2017 — Visual Studio 2017预览版的Rust支持[![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) 活塞开发者/VisualRust — Rust的Visual Studio扩展[![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) - TOML support in vscode
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — A LLDB extension
    * [crates](https://github.com/serayuzgur/crates) 板条箱 — crates是crates.io依赖项的扩展。[![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates)
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) 更漂亮的代码格式化程序 (Rust) — 自以为是的Rust代码格式化程序，自动修复不良语法 ([Prettier](https://prettier.io/) community plugin)
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) — An alternative rust language server to the RLS
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) — Rust support for Visual Studio Code (supports both RLS and rust-analyzer)

### Profiling

* [Bencher](https://github.com/bencherdev/bencher) - A suite of continuous benchmarking tools designed to catch performance regressions in CI
* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) — Statistics-driven benchmarking library for Rust
* [Bytehound](https://github.com/koute/bytehound) — A memory profiler for Linux
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — A stopwatch library
* FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame) —
  * [mrhooray/torch](https://github.com/mrhooray/torch) — generates FlameGraphs based on DWARF Debug Info
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) — A command-line benchmarking tool

### Services

* [deps.rs](https://github.com/deps-rs/deps.rs) — Detect outdated or insecure dependencies
* [docs.rs](https://docs.rs) — Automatic documentation generation of crates

### Static analysis

[[assert](https://crates.io/keywords/assert) [断言,[static](https://crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) Facebook实验/MIRAI — 在Rust的中级中间表示 (MIR) 上操作的抽象解释器[![Continuous Integration](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml)
* [static_assertions](https://crates.io/crates/static_assertions) — Compile-time assertions to ensure that invariants are met

### Testing

[[test](https://crates.io/keywords/test) [试验,[testing](https://crates.io/keywords/testing)]

* Code Coverage
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) — A code coverage tool designed for Rust
* Continuous Integration
  * [trust](https://github.com/japaric/trust) — A Travis CI and AppVeyor template to test your Rust crate on 5 architectures and publish binary releases of it for Linux, macOS and Windows
* Frameworks and Runners
  * [AlKass/polish](https://github.com/AlKass/polish) AlKass/波兰语 — 迷你测试/测试驱动框架[![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - A cargo extension to simplify running library tests and benches on smartphones and other small processor devices.
  * [cucumber](https://crates.io/crates/cucumber) 黄瓜 [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — An implementation of the Cucumber testing framework for Rust. Fully native, no external test runners or dependencies. [![Build Status](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
  * [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log) d-e-s-o/test-log [[test-log](https://crates.io/crates/test-log)] — A replacement of the `#[test]` attribute that initializes logging and/or tracing infrastructure before running tests. [![GitHub Workflow Status](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml)
  * [demonstrate](https://crates.io/crates/demonstrate) 演示 — 声明式测试框架[![Build Status](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
  * [rstest](https://crates.io/crates/rstest) rstest — 基于夹具的Rust测试框架[![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate) — An RSpec inspired minimal testing framework for Rust
* Mocking and Test Data
  * [asomers/mockall](https://github.com/asomers/mockall) asomers/mockall [[mockall](https://crates.io/crates/mockall)] — A powerful mock object library for Rust. [![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  * [fake-rs](https://github.com/cksac/fake-rs) —  A library for generating fake data
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[goldenfile](https://crates.io/crates/goldenfile)] - A library providing a simple API for goldenfile testing.
  * [httpmock](https://github.com/alexliesenfeld/httpmock) httpmock — HTTP模拟[![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
  * [mockiato](https://crates.io/crates/mockiato) — A strict, yet friendly mocking library for Rust 2018
  * [mockito](https://crates.io/crates/mockito) — HTTP mocking
  * [nrxus/faux](https://github.com/nrxus/faux/) nrxus/人造 [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — A library to create mocks out of structs. ![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
  * [synth](https://github.com/shuttle-hq/synth/) 合成器 — 以声明方式生成数据库数据。[![build](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)
* Mutation Testing
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) 货物-变种人 [[cargo-mutants](https://crates.io/crates/cargo-mutants)] - Finds inadequately tested code by injecting mutations, no source changes required. [![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * [mutagen](https://github.com/llogiq/mutagen) 诱变剂 [[mutagen](https://crates.io/crates/mutagen)] — A source-level mutation testing framework (nightly only)
* Property Testing and Fuzzing
  * [proptest](https://crates.io/crates/proptest) — property testing framework inspired by the [Hypothesis](https://hypothesis.works/) framework for Python
  * [quickcheck](https://crates.io/crates/quickcheck) 快速检查 — 的Rust实现[QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1)
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) rust-fuzz/afl.rs — 生锈模糊器，使用[AFL](https://lcamtuf.coredump.cx/afl/)

### Transpiling

* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) 贝叶斯目击者/m2cgen — 一个CLI工具，用于将经过训练的经典机器学习模型转换为具有零依赖关系的本机Rust代码。[![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
* [immunant/c2rust](https://github.com/immunant/c2rust) — C to Rust translator and cross checker built atop Clang/LLVM.
* [jameysharp/corrode](https://github.com/jameysharp/corrode) — A C to Rust translator written in Haskell.

## Libraries

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) 性能-监视器-rs — 旨在作为应用程序监视其性能的基础的工具包。[![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)

### Artificial Intelligence

#### Genetic algorithms

* [innoave/genevo](https://github.com/innoave/genevo) — Execute genetic algorithm (GA) simulations in a customizable and extensible way.
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — Genetic Algorithm library in Rust. In maintenance mode.
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — Fast, parallel, extensible and adaptable genetic algorithm library. A example using this library solves the N Queens problem for N = 255 in only few seconds and using less than 1 MB of RAM.
* [pkalivas/radiate](https://github.com/pkalivas/radiate) pkalivas/辐射 — 可定制的并行遗传编程引擎，能够针对有监督，无监督和强化学习问题不断发展解决方案。附带整洁和Evtree的完整和可定制的实现。![Crates.io](https://img.shields.io/crates/v/radiate)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — Evolutionary algorithms with Rust

#### Machine learning
请参见[[Machine learning](https://crates.io/keywords/machine-learning)]
另请参见[About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and [Are we learning yet?](https://www.arewelearningyet.com)

* [autumnai/leaf](https://github.com/autumnai/leaf) 秋天/叶子 — 开放的机器智能框架。被遗弃的项目。最新的fork是[spearow/juice]( https://github.com/spearow/juice)
* [burn-rs/burn](https://github.com/burn-rs/burn) - A Flexible and Comprehensive Deep Learning Framework in Rust.
* [coreylowman/dfdx](https://github.com/coreylowman/dfdx) coreylowman/dfdx — CUDA加速了机器学习框架，它利用了Rust的许多独特功能。![Crates.io](https://img.shields.io/crates/v/dfdx)
* [huggingface/candle](https://github.com/huggingface/candle) 拥抱脸/蜡烛 [[candle-core](https://crates.io/crates/candle-core)]- a minimalist ML framework with a focus on easiness of use and on performance (including GPU support)
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) huggingface/tokenizers - 用Rust (原始实现) 编写的带有Python绑定的现代NLP管道的Face标记器。[![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — Rust language bindings for PyTorch.
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) maciejkula/rustlearn — 机器学习板条箱生锈。[![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [rust-ml/linfa](https://github.com/rust-ml/linfa) — Machine learning framework.
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) smartcorelib/smartcore — Rust中的机器学习库[![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
* [tensorflow/rust](https://github.com/tensorflow/rust) — Rust language bindings for TensorFlow.

#### OpenAI

* [64bit/async-openai](https://github.com/64bit/async-openai) [[async-openai](https://crates.io/crates/async-openai)] — Ergonomic Rust bindings for OpenAI API based on OpenAPI spec.
* [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) zurawiki/tiktoken-rs [[tiktoken-rs](https://crates.io/crates/tiktoken-rs)] — Rust library for tokenizing text with OpenAI models using tiktoken. [![CI](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml)

### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite) - Web application for visualizing spatial and planetary image surveys in different projections
* [fitsio](https://crates.io/crates/fitsio) — fits interface library wrapping cfitsio
* [flosse/rust-sun](https://github.com/flosse/rust-sun) [[sun](https://crates.io/crates/sun)] — A rust port of the JS library suncalc
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — astronomy for Rust

### Asynchronous

* [async-std](https://async.rs/) async-std [[async-std](https://crates.io/crates/async-std)] - Async version of the Rust standard library [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [dpc/mioco](https://github.com/dpc/mioco) — Scalable, coroutine-based, asynchronous IO handling library
* [mio](https://github.com/tokio-rs/mio) — MIO is a lightweight IO library for Rust with a focus on adding as little overhead as possible over the OS abstractions
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) — Zero-cost futures in Rust
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — Monad/MonadIO, Handler, Coroutine/doNotation, Functional Programming features for Rust
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — rust stackful coroutine library
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — A coroutine I/O library with a working-stealing scheduler

### Audio and Music

[[audio](https://crates.io/keywords/audio)]

* [hound](https://crates.io/crates/hound) — A WAV encoding and decoding library
* [insomnimus/nodi](https://github.com/insomnimus/nodi) 失眠症/诺迪 [[nodi](https://crates.io/crates/nodi)] — A library for playback and abstraction of MIDI files. [![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears) — A simple library to play Sounds and Musics, on top of OpenAL and libsndfile
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](https://portmedia.sourceforge.net/portmidi/) bindings
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) — A Rust music theory library
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) — A pure Rust audio decoding and media demuxing library supporting AAC, FLAC, MP3, MP4, OGG, Vorbis, and WAV.
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) RustAudio/cpal - pure Rust中的低级跨平台音频I/O库。[![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) — A Rust audio playback library
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — PortAudio bindings
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) 串行-ATA/lofty-rs [[lofty](https://crates.io/crates/lofty)] — A library for reading and editing the metadata of various audio formats [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) constantoine/totp-rs [[totp-rs](https://crates.io/crates/totp-rs)] — 2fa library to generate and verify TOTP-based tokens ![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust
* [oauth2](https://github.com/ramosbugs/oauth2-rs) — Extensible, strongly-typed Rust OAuth2 client library
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) 氧化物-auth — 一个OAuth2服务器库，与actix或其他前端结合使用，具有一组可配置和可插入的后端[![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) — Async library to manage and orchestrate JWT workflow
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) — An oauth2 client implementation providing the Device, Installed and Service Account flows

### Automotive

* [idletea/tokio-socketcan](https://github.com/idletea/tokio-socketcan) [[tokio-socketcan](https://crates.io/crates/tokio-socketcan)] — Linux SocketCAN support for tokio based on the socketcan crate
* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)] — A parser for the DBC format
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] — Linux SocketCAN BCM support for tokio
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)] — Linux SocketCAN library
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) Sensirion/lin-总线 [[lin-bus](https://crates.io/crates/lin-bus)] — LIN bus driver traits and protocol implementation [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) — bioinformatics libraries in Rust.

### Caching

* [06chaynes/http-cache](https://github.com/06chaynes/http-cache) 06chaynes/http缓存 [[http-cache](https://crates.io/crates/http-cache)] - A caching middleware that follows HTTP caching rules [![build badge](https://github.com/06chaynes/http-cache/workflows/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/actions/workflows/http-cache.yml)
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) — Memcached client library
* [al8n/stretto](https://github.com/al8n/stretto) al8n/stretto - 一种高性能线程安全的内存绑定Rust cache[![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [jaemk/cached](https://github.com/jaemk/cached) — Simple function caching/memoization
* [moka-rs/moka](https://github.com/moka-rs/moka) moka-rs/moka - 受适用于Java的咖啡因库启发，用于Rust的高性能并发缓存库[![build badge](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)
* [mozilla/sccache](https://github.com/mozilla/sccache/) - Shared Compilation Cache, great for Rust compilation
* [zkat/cacache-rs](https://github.com/zkat/cacache-rs) zkat/cacache-rs - 高性能、并发、内容可寻址的磁盘缓存，针对异步api进行了优化[![build badge](https://github.com/zkat/cacache-rs/workflows/CI/badge.svg)](https://github.com/zkat/cacache-rs/actions/workflows/ci.yml)

### Cloud

* AWS[[aws](https://crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) awslabs/aws-lambda-rust-runtime [[lambda_runtime](https://crates.io/crates/lambda_runtime)] — A Rust runtime for AWS Lambda [![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - The new AWS SDK for Rust
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) —
* Load Balancer
  * [Convey](https://github.com/bparli/convey) - Layer 4 Load Balancer with dynamic configuration loading.
* Multi Cloud
  * [Qovery/engine](https://github.com/Qovery/engine) - Abstraction layer library that turns easy application deployment on Cloud providers in just a few minutes

### Command-line

* Argument parsing
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)] — A simple to use, full featured command-line argument parser
  * [cliparser](https://crates.io/crates/cliparser) cliparser — 简单的命令行解析器。[![build badge](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) docopt/docopt.rs [[docopt](https://crates.io/crates/docopt)] — A Rust implementation of [DocOpt](http://docopt.org)
  * [google/argh](https://github.com/google/argh) google/argh [[argh](https://crates.io/crates/argh)] — An opinionated Derive-based argument parser optimized for code size [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)] — quickly build cool CLI apps in Rust
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) ksk001100/海马 [[seahorse](https://crates.io/crates/seahorse)] — A minimal CLI framework written in Rust [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)] — parse command line argument by defining a struct
* Data visualization
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) nukesor/comfy-table [[comfy-table](https://crates.io/crates/comfy-table)] — Beautiful dynamic tables for your cli tools. [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) zhiburt/tabled [[tabled](https://crates.io/crates/tabled)] — An easy to use library for pretty print tables of Rust structs and enums. [![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* Human-centered design
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)] — panic messages for humans
* Line editor
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)] — readline implementation in Rust
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)] — A library offering readline-like functionality
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)] — Configurable, extensible, interactive line reader
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)] — pure-Rust command line editing library
* Other
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) mgrachev/更新-线人 [[update-informer](https://crates.io/crates/update-informer)] — Update informer for CLI applications. It checks for a new version on Crates.io and GitHub [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* Pipeline
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)] — facilities for interaction with external pipelines
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)] — pipe your output through an external pager
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)] — A builder for subprocess pipelines and IO redirection
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) rust-cli/rexpect [[rexpect](https://crates.io/crates/rexpect)] — automate interactive applications such as ssh, ftp, passwd, etc [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) zhiburt/expectrl [[expectrl](https://crates.io/crates/expectrl)] — A library for controlling interactive programs in a pseudo-terminal [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* Progress
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)] — console progress bar for Rust
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[indicatif](https://crates.io/crates/indicatif)] — indicate progress to users
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) 艾蒂安-拿破仑/菠菜 [[spinach](https://crates.io/crates/spinach)] — Practical spinner for Rust. [![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)] — 60+ elegant terminal spinners
* Prompt
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)]  — build an interactive command prompt
  * [mikaelmello/inquire](https://github.com/mikaelmello/inquire) mikaelmello/查询 [[inquire](https://crates.io/crates/inquire)] — A library for building interactive prompts on terminals. [![Build status](https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mikaelmello/inquire/actions)
  * [starship/starship](https://starship.rs/) 星舰/星舰 [[starship](https://crates.io/crates/starship)]  — A minimal, blazing fast, and extremely customizable prompt for any shell [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) ynqa/promkit [[promkit](https://crates.io/crates/promkit)]  — A toolkit for building interactive command-line tools [![Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
* Style
  * [colored](https://github.com/colored-rs/colored) [[colored](https://crates.io/crates/colored)] — Coloring terminal so simple, you already know how to do it!
  * [console-rs/dialoguer](https://github.com/console-rs/dialoguer) [[dialoguer](https://crates.io/crates/dialoguer)] — A rust library for command line prompts and similar things.
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) LukasKalbertodt/bunt [[bunt](https://crates.io/crates/bunt)] — cross-platform terminal colors and styling with macros [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)] — cross-platform styled terminal output
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)] — control colours and formatting on ANSI terminals
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)] — A dead simple ANSI terminal color painting library
* TUI
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] — [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) bindings
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] — build rich TUI applications
  * [ivanceras/titik](https://github.com/ivanceras/titik) - a crossplatform TUI widget library with the goal of providing interactive widgets
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)] — curses library, supports linux and windows
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] — [ncurses](https://www.gnu.org/software/ncurses/) bindings
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)] — Rust library for putting things in a grid
  * [ratatui-org/ratatui](https://github.com/ratatui-org/ratatui) ratatui-组织/ratatui [[ratatui](https://crates.io/crates/ratatui)] — A Rust library that's all about cooking up terminal user interfaces (TUIs)
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] — bindless library for controlling terminals/TTY
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) gchp/rustbox [[rustbox](https://crates.io/crates/rustbox)] — bindings to [Termbox](https://github.com/nsf/termbox)
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] — crossplatform terminal library

### Compression

* [7z](https://7-zip.org/7z.html)
  * [dyz1990/sevenz-rust](https://github.com/dyz1990/sevenz-rust) dyz1990/sevenz-rust [[sevenz-rust](https://crates.io/crates/sevenz-rust)] — A 7z decompressor/compressor written in pure rust. [![Rust](https://github.com/dyz1990/sevenz-rust/workflows/Rust/badge.svg?branch=main)](https://github.com/dyz1990/sevenz-rust/actions)
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) — Brotli decompressor in Rust that optionally avoids the stdlib
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — implementation of Brotli compression
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](https://www.sourceware.org/bzip2/) bindings
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)] — implementation of the Zopfli compression algorithm for higher quality deflate or zlib compression
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/) - multi-threaded encoding and decoding of deflate formats and snappy
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) 铁锈-郎/flate2-rs — [miniz](https://code.google.com/archive/p/miniz) bindings [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [snappy](https://github.com/google/snappy) bindings
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — tar archive reading/writing in Rust
* zip
  * [zip-rs/zip](https://github.com/zip-rs/zip) — read and write ZIP archives

### Computation

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] — A pure Rust optimization library
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) BLAS [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — BLAS bindings
* [calebwin/emu](https://github.com/calebwin/emu) — A language for GPGPU numerical computing from a Rust macro
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) — low-dimensional linear algebra library
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) — GSL bindings
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) — LAPACK bindings
* Parallel
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://github.com/arrayfire) bindings
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) — An extensible, pluggable, backend-agnostic framework for parallel, high-performance computations on CUDA, OpenCL and common host CPU.
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) bindings
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) — scientific computing library in Rust
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) — Robust statistical computation library in Rust

### Concurrency

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) – Support for parallelism and low-level concurrency in Rust
* [orium/archery](https://github.com/orium/archery) 拱门/射箭 [[archery](https://crates.io/crates/archery)] — Library to abstract from `Rc`/`Arc` pointer types. [![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
* [Rayon](https://github.com/rayon-rs/rayon) – A data parallelism library for Rust
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) – Coroutine Library in Rust
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) – Coroutine I/O for Rust

### Configuration

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) andoriyu/uclicious [[uclicious](https://crates.io/crates/uclicious)] — [libUCL](https://github.com/vstakhov/libucl) based feature-rich configuration library. [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] — library for processing application configuration easily
* [mehcode/config-rs](https://github.com/mehcode/config-rs) mehcode/config-rs [[config](https://crates.io/crates/config)] — Layered configuration system for Rust applications (with strong support for 12-factor applications)
* [softprops/envy](https://github.com/softprops/envy) 软道具/羡慕 - 将env var反序列化为类型安全结构[![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### Cryptography

[[crypto](https://crates.io/keywords/crypto) [密码,[cryptography](https://crates.io/keywords/cryptography)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation in Rust.
* [briansmith/ring](https://github.com/briansmith/ring) — Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives.
* [briansmith/webpki](https://github.com/briansmith/webpki) — Web PKI TLS X.509 certificate validation in Rust.
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] — Simple password manager to use in your terminal
* [cossacklabs/themis](https://github.com/cossacklabs/themis) cossacklabs/themis [[themis](https://crates.io/crates/themis)] — a high-level cryptographic library for solving typical data security tasks, best fit for multi-platform apps. [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — cryptographic algorithms in Rust
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — Pure Rust implementation of Curve25519 operations
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) — Pure Rust implementation of Ed25519 digital signatures
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) — Pure Rust implementation of X25519 key exchange
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) — Pure Rust implementation of the Keccak family (SHA3)
* [exonum/exonum](https://github.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)] — extensible framework for blockchain projects
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) facebook/不透明-ke — 最近的纯Rust实现[OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* [klutzy/suruga](https://github.com/klutzy/suruga) klutzy/suruga — 的Rust实现[TLS 1.2](https://datatracker.ietf.org/doc/html/rfc5246)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) — Bindings for Security Framework (OSX native)
* [libOctavo/octavo](https://github.com/libOctavo/octavo) — Modular hash and crypto library in Rust
* [orion-rs/orion](https://github.com/orion-rs/orion) 猎户座-rs/猎户座 — 这个库旨在提供简单和可用的加密。“Usable” 意味着暴露易于使用且难以滥用的高级API。[![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)] — A Rust port of the password primitives used in the Django Project. It doesn't require Django, only hashes and validates passwords according to its style.
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) — Collection of cryptographic hash functions written in pure Rust
* [rustls/rustls](https://github.com/rustls/rustls) — A Rust implementation of TLS
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) — Bindings for native TLS libraries
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) bindings
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) sorairolake/scryptenc-rs [[scryptenc](https://crates.io/crates/scryptenc)] — An implementation of the scrypt encrypted data format. [![CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)
* [vityafx/randomorg](https://github.com/vityafx/randomorg) vityafx/randomorg - A random.org客户端库。[![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - Schnorr VRFs and signatures on the Ristretto group

### Data processing

* [amv-dev/yata](https://github.com/amv-dev/yata) amv-开发/yata — 高性能技术分析库[![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) — N-dimensional array with array views, multidimensional slicing, and efficient operations
* [kernelmachine/utah](https://github.com/kernelmachine/utah) — Dataframe structure and operations in Rust
* [pola-rs/polars](https://github.com/pola-rs/polars) pola-rs/polars - 快速功能完成DataFrame库![Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
* [weld-project/weld](https://github.com/weld-project/weld) — High-performance runtime for data analytics applications

### Data streaming

* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) 阿罗约系统/阿罗约 - Rust和SQL中的高性能实时分析[![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* [infinyon/fluvio](https://github.com/infinyon/fluvio) infinyon/fluvio - 可编程数据流平台[![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### Data structures

* [becheran/grid](https://github.com/becheran/grid) 贝赫兰/网格 [[grid](https://crates.io/crates/grid)] —  Provide a two dimensional data structure for rust that is easy to use and fast. [![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)] — Ternary search tree collection
* [contain-rs](https://github.com/contain-rs) — Extension of Rust's std::collections
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) — Array helpers for Rust. Some of the most common methods you would use on Arrays made available on Vectors. Polymorphic implementations for handling most of your use cases.
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) – a hack to allow for arrays sized by typenums
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] — A priority queue that implements priority changes.
* [greyblake/nutype](https://github.com/greyblake/nutype) greyblake/nutype [[nutype](https://crates.io/crates/nutype)] — define newtype structures with validation constraints. [![build status](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) — K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup
* [orium/rpds](https://github.com/orium/rpds) orium/rpds [[rpds](https://crates.io/crates/rpds)] — Persistent data structures in Rust. [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) – Roaring Bitmaps in Rust
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) —
* [tnballo/scapegoat](https://github.com/tnballo/scapegoat) tnballo/替罪羊 [[scapegoat](https://crates.io/crates/scapegoat)] — Safe, fallible, stack-only alternative to `BTreeSet` and `BTreeMap`. [![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* [xfix/enum-map](https://github.com/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)] — An optimized map implementation for enums using an array to store values.
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) yamafaktory/超图 [[hypergraph](https://crates.io/crates/hypergraph)] — Hypergraph is a data structure library to generate directed hypergraphs. [![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs) blitzarx1/egui_graphs - [[egui_graphs](https://crates.io/crates/egui_graphs)] - Interactive graph visualization widget for rust powered by egui and petgraph. [![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)
* [djduque/pgfplots](https://github.com/djduque/pgfplots) djduque/pgfplots [[pgfplots](https://crates.io/crates/pgfplots)] — A Rust library to generate publication-quality figures. [![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) — Plotly for Rust.
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) [[colorgrad](https://crates.io/crates/colorgrad)] — Rust color scales library for data visualization, charts, games, maps, generative art and others.
* [milliams/plotlib](https://github.com/milliams/plotlib) —
* [plotters](https://github.com/plotters-rs/plotters) 绘图仪 — [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* [rerun](https://github.com/rerun-io/rerun) — [[rerun](https://crates.io/crates/rerun)] — An SDK for logging computer vision and robotics data (tensors, point clouds, etc) paired with a visualizer for exploring that data over time.
* [saresend/gust](https://github.com/saresend/Gust) —

### Database

[[database](https://crates.io/keywords/database)]

* NoSQL[[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) 阿拉戈格 [[aragog](https://crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)] - An ArangoDB driver for Rust
  * [Cassandra](https://cassandra.apache.org/_/index.html) 卡桑德拉 [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] — native client written in Rust
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) krojew/cdrs-tokio [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol)] - Cassandra protocol implementation in Rust
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - production-ready async Apache Cassandra driver written in pure Rust
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) —  bindings to the DataStax C/C++ client
  * CouchDB[[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)] — A Rust client for the CouchDB REST API
  * [DynamoDB](https://aws.amazon.com/dynamodb/) DynamoDB [[dynamodb](https://crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) 软道具/dynomite - 与 “rusoto_dynamodb” 进行强类型和方便交互的库[![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch[[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)] — A Rust client for the [Elastic](https://www.elastic.co/) REST API
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) 弹性-rs/弹性 [[elastic](https://crates.io/crates/elastic)] — elastic is an efficient, modular API client for Elasticsearch written in Rust [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)] — A client library for CoreOS's etcd.
    * [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs) lodrem/etcd-rs — rust的异步etcd客户端[![CI](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [ForestDB](https://github.com/couchbase/forestdb) bindings
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) — Synchronization interface
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) — [LevelDB](https://github.com/google/leveldb) bindings
  * LMDB[[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](https://www.symas.com/symas-embedded-database-lmdb) bindings
  * MongoDB[[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.com/) bindings
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) — a lightweight and simple key-value store, heavily inspired by Python's PickleDB.
  * [PoloDB](https://www.polodb.org/)
    * [PoloDB](https://github.com/PoloDB/PoloDB) PoloDB - 基于JSON的嵌入式数据库具有类似于MongoDB的API。![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
  * [Redb](https://www.redb.org/)
    * [Redb](https://github.com/cberner/redb) Redb - 用纯Rust编写的嵌入式键值数据库它提供了与其他嵌入式键值存储 (如rocksdb和lmdb) 类似的接口。![GitHub Workflow Status](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis[[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) aembke/弗雷德 [[fred](https://crates.io/crates/fred)] - A high level async [Redis](https://redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) redis-rs — [Redis](https://redis.io/) library in Rust [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) rust-rocksdb/rust-rocksdb — RocksDB绑定[![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) — SurrealDB embedded document-graph database
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) — UnQLite bindings
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)] — A client library for Apache ZooKeeper.
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) krojew/rust-zookeeper [[zookeeper-async](https://crates.io/crates/zookeeper-async)] - Async Zookeeper client written 100% in Rust, based on tokio.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM[[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) 阿拉戈格 [[aragog](https://crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM[[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) Brendonovich/prisma-client-rust — 自动生成的查询生成器，可使用Prisma生态系统提供简单且完全类型安全的数据库访问。[![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) — an ORM and Query builder for Rust
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — an ORM for Rust
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) — Rust ORM Framework High Performance(JSON based)
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) SeaQL/sea-orm — Rust的异步和动态ORM[![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * [SeaQL/seaography](https://github.com/SeaQL/seaography) SeaQL/seaography — 适用于SeaORM的GraphQL框架[![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
* [sfackler/r2d2](https://github.com/sfackler/r2d2) — generic connection pool
* SQL[[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) launchbadge/sqlx - 具有强类型支持的异步PostgreSQL/MySQL/SQLite连接池[![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) SeaQL/sea-查询 - 用于MySQL、Postgres和SQLite的动态SQL查询生成器[![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) SeaQL/sea-schema - SQL架构定义和发现[![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) prisma/提比略 — [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql[[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) AgilData/mysql-proxy-rs — MySQL代理[![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) blackbeam/mysql_async [[mysql_async](https://crates.io/crates/mysql_async)] — asyncronous Rust Mysql driver based on Tokio. [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] — A native MySql client
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) 久保/铁锈-甲骨文 [[oracle](https://crates.io/crates/oracle)] — Oracle driver for Rust [![build badge](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)
  * PostgreSql[[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] — A native [PostgreSQL](https://www.postgresql.org/) client
  * Sqlite[[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) — [Sqlite3](https://www.sqlite.org/index.html) bindings

### Date and time

[[date](https://crates.io/keywords/date) [日期,[time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://github.com/chronotope/chrono) —
* [Mnwa/ms](https://github.com/Mnwa/ms) Mnwa/ms [[ms-converter](https://crates.io/crates/ms-converter)] — it's a library for converting human-like times to milliseconds [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) sorairolake/nt-time [[nt-time](https://crates.io/crates/nt-time)] — A Windows file time library. [![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)
* [time-rs/time](https://github.com/time-rs/time) 时间-rs/时间 — [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)] — stream processing / distributed computation platform
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka](https://github.com/confluentinc/librdkafka) bindings
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) gklijs/schema_registry_converter [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)] — to integrate with [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) —
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd](https://github.com/beanstalkd/beanstalkd) bindings
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) [[hdfs](https://crates.io/crates/hdfs)] — libhdfs bindings
* Other
  * [build-trust/ockam](https://github.com/build-trust/ockam) 建立信任/ockam [[ockam](https://crates.io/crates/ockam)] - End-to-End Encryption, Mutual Authentication, and ABAC for distributed applications [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)

### Domain driven design

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) 服务器技术/cqrs [[cqrs-es](https://crates.io/crates/cqrs-es)] — A framework for CQRS and event sourcing with [user guide](https://doc.rust-cqrs.org/)

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya) — A Rust library for the Rust programming language, built with a focus on developer experience and operability.
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs) — A minimal and opinionated eBPF tooling for the Rust ecosystem.

### Email

[[email](https://crates.io/keywords/email) [电子邮件,[imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) duesee/imap编解码器 [[imap-codec](https://crates.io/crates/imap-codec)] — Rock-solid and complete codec for IMAP [![Build & Test](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) — unofficial Rust library for SendGrid API
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - A microservice to send emails using [MRML](https://github.com/jdrouet/mrml) templates.
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) - A web application to build [MRML](https://github.com/jdrouet/mrml) templates.
* [jdrouet/mrml](https://github.com/jdrouet/mrml) - A library to generate nice email templates working on any mail client.
* [lettre/lettre](https://github.com/lettre/lettre) lettre/lettre — 用于Rust的SMTP库[![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan) An SMTP server for test and development environment.
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] — A library for parsing real-world email files
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) stalwartlabs/mail-auth [[mail-auth](https://crates.io/crates/mail-auth)] - DKIM, ARC, SPF and DMARC message authentication library [![build badge](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) stalwartlabs/邮件解析器 [[mail-parser](https://crates.io/crates/mail-parser)] - A fast and robust e-mail parsing library with full MIME support [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) stalwartlabs/mail-send [[mail-send](https://crates.io/crates/mail-send)] - E-mail builder and SMTP client library with DKIM support [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab) — Email test server for development.

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — A Rust ASN.1 (DER) serializer
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) bincode-组织/bincode — Rust中的二进制编码器/解码器[![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) [[postcard](https://crates.io/crates/postcard)] — Postcard is a #![no_std] focused serializer and deserializer for Serde.
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] —  cross-platform, zero-copy, and endian-aware binary parsing
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) — Encoding and decoding support for BSON in Rust
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — Supports big-endian, little-endian and native byte orders
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) —
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) — CBOR support for serde
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] — A Gecko-oriented implementation of the Encoding Standard in Rust
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) —
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) —
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — A fast and flexible CSV reader and writer, with support for Serde
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)] — crate to parse and emit EDN format into Rust types.
* [FlatBuffers](https://flatbuffers.dev/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) — FlatBuffers compiler (flatc) integration for Cargo build scripts
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) [[har](https://crates.io/crates/har)] — A HTTP Archive Format (HAR) serialization & deserialization library
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — High-performance browser-grade HTML5 parser
* JSON
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson](https://crates.io/crates/ajson)] —  Get JSON values quickly
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)] — JSON implementation in Rust
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[pikkr](https://crates.io/crates/pikkr)] — JSON parser which picks up values directly without performing tokenization in Rust
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] — JSON support for [Serde](https://github.com/serde-rs/serde) framework
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] — High performance JSON parser based on a port of simdjson
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — A pure Rust low/high level MessagePack implementation
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) [[netcdf](https://crates.io/crates/netcdf)] — Medium-level netCDF bindings for Rust, allowing easy reading and writing of array-like structures to a file.
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] — A Rust based way to parse and encode PEM-encoded data
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) —
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) tokio-rs/prost — [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) [[rkyv](https://crates.io/crates/rkyv)] — rkyv (archive) is a zero-copy deserialization framework for Rust
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) —
* Serde
  * [vityafx/serde-aux](https://github.com/vityafx/serde-aux/) vityafx/serde-aux - 与serde库一起使用的其他工具。[![CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) 塔马斯菲/塔普洛 [[taplo](https://crates.io/crates/taplo)] — A TOML toolkit written in Rust [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
  * [toml-rs/toml](https://github.com/toml-rs/toml) toml-rs/toml — [![CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — an XML parser written in Rust
  * [media-io/yaserde](https://github.com/media-io/yaserde) — Yet Another Serializer/Deserializer specialized for XML
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) — A streaming XML library
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — An XML library in Rust
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — An XPath library in Rust
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) — High performance XML pull reader/writer
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — The missing YAML 1.2 implementation for Rust.
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) dtolnay/serde-yaml [[serde\_yaml](https://crates.io/crates/serde_yaml)] — YAML support for [Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)] — Sorta Text Format in UTF-8

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [Camino](https://github.com/camino-rs/camino) [[camino](https://crates.io/crates/camino)] - Like Rust's std::path::Path, but UTF-8.
  * [ParthJadhav/Rust_Search](https://github.com/ParthJadhav/Rust_Search) [[rust_search](https://crates.io/crates/rust_search)] - Blazingly fast file search library built in Rust.
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) [[dbus-udisks2](https://crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)] — High level abstraction for the `mount` / `umount2` system calls.
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) [[path_abs](https://crates.io/crates/path_abs)] — Absolute serializable path types and associated methods.
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) — expanding opportunities standard library std::fs and std::io
* Temporary Files
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) — temporary file library
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] — list and manipulate unix extended file attributes
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)] — Zero-details, privacy-focused embeddable file system.

### Finance

* [avhz/RustQuant](https://github.com/avhz/RustQuant) avhz/RustQuant [[RustQuant](https://crates.io/crates/RustQuant)] — A quantitative finance library. ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) d-e-s-o/apca [[apca](https://crates.io/crates/apca)] — Opinionated and comprehensive bindings to the [Alpaca API](https://alpaca.markets/) for stock trading and more. ![GitHub Workflow Status](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)

### Functional Programming

[[functional programming](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) — A library for functional programming in Rust
  * [myrrlyn/tap](https://github.com/myrrlyn/tap) - Suffix-Position Pipeline Behavior

### Game development
另请参见[Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](https://liballeg.github.io/) bindings
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) — A curated list of links to miniquad/macroquad-related code & resources
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) — A curated list of wgpu code and resources
* bracket-lib (previously RLTK)
  * [bracket-lib](https://github.com/amethyst/bracket-lib) 支架-lib [[bracket-lib](https://crates.io/crates/bracket-lib)] - The Roguelike Toolkit (RLTK), implemented for Rust. [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) 维塔夫克斯/挑战-rs [[challonge](https://crates.io/crates/challonge)] — Client library for the Challonge REST API. Helps to organize tournaments. [![CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange) bindings
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) — Specs Parallel ECS
  * [legion](https://github.com/amethyst/legion) 军团 — 功能丰富的高性能ECS库，具有最少的样板[![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  * [Bevy](https://github.com/bevyengine/bevy) 贝维 是一个构建在Rust中的令人耳目一新的简单数据驱动游戏引擎。-[![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [Fyrox](https://fyrox.rs/) Fyrox — Rust游戏引擎3D[![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez) ggez — 一个轻量级的游戏框架，用于制作具有最小摩擦的2D游戏-[![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org) Kiss3d — 一个保持简单，用Rust编写的愚蠢的3d图形引擎[![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator) — A real time strategy game/engine written with Rust and WebGPU
  * [Piston](https://www.piston.rs/) 活塞 — [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * [Unrust](https://github.com/unrust/unrust) — unrust — A pure rust based (webgl 2.0 / native) game engine
* [Godot](https://godotengine.org/)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) godot-rust/gdnative [[gdnative](https://crates.io/crates/gdnative)] - Rust bindings to the Godot game engine [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)] — Rust bindings for raylib
* [SDL](http://www.libsdl.org/) SDL [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — SDL1 bindings
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) — SDL2 bindings
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/) bindings
* Skillratings
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) Atomfllder/技能等级 [[skillratings](https://crates.io/crates/skillratings)] - Collection of skill rating algorithms for multiplayer games like Elo, Glicko-2, TrueSkill etc. [![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) — Libtcod bindings for Rust.
  * Warning: Not maintained anymore
* Toornament-rs
  * [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs) vityafx/toornament-rs - Toornament.com Rust的API绑定。[![CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)] — Easy UDP Game Server and UDP Client framework for creating simple 2D and 3D online game prototype

### Geospatial

[[geo](https://crates.io/keywords/geo) [geo,[gis](https://crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) DaveKram/coord_transforms [[coord_transforms](https://crates.io/crates/coord_transforms)] — coordinate transformations (2-d, 3-d, and geospatial)
* [Georust](https://github.com/georust) — geospatial tools and libraries written in Rust
* [MapLibre/Martin](https://github.com/maplibre/martin) 马普利布/马丁 — 支持PostGIS、MBTiles、PMTiles和sprites的地图瓦片服务器。[![CI build](https://github.com/maplibre/martin/workflows/CI/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io version](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![Book](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) rust-reverse-geocoder — Rust中的快速，离线反向地理编码器，灵感来自[thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] — conversion between UTM, LatLon and MGRS coordinates

### Graph algorithms

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph) neo4j-labs/图形 - 高性能图算法库[![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* [petgraph/petgraph](https://github.com/petgraph/petgraph) petgraph/petgraph - Rust的图形数据结构库。[![graph CI status](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - An incremental harfbuzz port to Rust
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) — A pure Rust alternative to libraries like FreeType
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) — A high-performance, bindless graphics API for Rust.
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) gfx-rs/wgpu - 基于gfx-hal的原生WebGPU实现.[![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL[[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) —
  * [glium/glium](https://github.com/glium/glium) — safe OpenGL wrapper for the Rust language.
  * [glutin](https://crates.io/crates/glutin) 谷蛋白 — Rust替代[GLFW](https://www.glfw.org/)
  * [Kiss3d](http://kiss3d.org) — draw simple geometric figures and play with them with one-liners
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) —
* PDF
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) — PDF writing library
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) — PDF document manipulation
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) —
  * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) – Generates PDF files with JavaScript and WASM (WebAssembly)
* [Vulkan](https://www.vulkan.org/) Vulkan [[vulkan](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) 喷发 [[erupt](https://crates.io/crates/erupt)] — [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] —

### GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) — A simple, cross-platform GUI automation library for Rust.
* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) —
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) DioxusLabs/dioxus - 一种便携式、高性能和符合人体工程学的框架，用于在Rust中构建跨平台用户界面。![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [emilk/egui](https://github.com/emilk/egui) emilk/egui - 用于Rust. egui的简单，快速且高度可移植的即时模式GUI库在web上本地运行，并在您最喜欢的游戏引擎中运行。[![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) — minifb is a cross-platform window setup with optional bitmap rendering. It also comes with easy mouse and keyboard input. Primarily designed for prototyping
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) fltk-rs — FLTK Rust绑定[![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) — Build flutter desktop app in dart & rust.
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) — High-level memory-safe binding generator for Flutter/Dart <-> Rust
* [fschutt/azul](https://github.com/fschutt/azul) — A free, functional, IMGUI-oriented GUI framework for rapid development of desktop applications written in Rust, supported by the Mozilla WebRender rendering engine.
* [GTK+](https://www.gtk.org/) GTK [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) gtk-rs/gtk4-rs - GTK4铁锈装订![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) — Asynchronous, GTK+-based, GUI library, inspired by Elm
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)] — A cross-platform GUI library for Rust focused on simplicity and type-safety. Inspired by Elm.
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) imgui-rs — ImGui的Rust绑定[![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — A simple UI framework built on IUP
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - A truly native and cross platform GUI library. One unified code can be run as native GUI, Html Web and TUI.
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) — libui bindings.
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) — Rust bindings for Nuklear
* [OrbTk](https://github.com/redox-os/orbtk) OrbTk — 轨道小部件工具包是一个使用SDL2的多平台 (G)UI工具包[![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — An easy-to-use, immediate-mode, 2D GUI library written entirely in Rust
* [Qt](https://doc.qt.io)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — QtQuick bindings
  * [rust-qt](https://github.com/rust-qt)
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) — Integrate Qml and Rust by building the QMetaObject at compile time.
* [rise-ui](https://github.com/rise-ui/rise) — Simple component-based cross-Platform GUI Toolkit for developing beautiful and user-friendly interfaces.
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) bindings
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) sciter-sdk/rust-sciter — Sciter绑定[![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint) slint-ui/slint [slint](https://crates.io/crates/slint) — [Slint](https://slint.dev/) is a toolkit to efficiently develop fluid graphical user interfaces for embedded devices and desktop applications. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) tauri-应用程序/tauri — 通过web前端构建更小、更快、更安全的桌面应用程序[WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview Rendering librarY.
* [xilem](https://github.com/linebender/xilem) xilem — 数据优先的Rust原生ui设计工具包的继任者[druid](https://github.com/linebender/druid)

### Image processing

* [abonander/img_hash](https://github.com/abonander/img_hash) — Perceptual image hashing and comparison for equality and similarity.
* [image-rs/image](https://github.com/image-rs/image) — Basic imaging processing functions and methods for converting to and from image formats
* [image-rs/imageproc](https://github.com/image-rs/imageproc) — An image processing library, based on the `image` library.
* [marekm4/dominant_color](https://github.com/marekm4/dominant_color) marekm4/dominant_color [[dominant_color](https://crates.io/crates/dominant_color)] — Dominant color extractor ![build badge](https://github.com/marekm4/dominant_color/actions/workflows/rust.yml/badge.svg?branch=master)
* [rust-cv/cv](https://github.com/rust-cv/cv) 铁锈-cv/cv — Rust CV是一个在Rust中实现计算机视觉算法，抽象和系统的项目。#[no_std] is supported where possible. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)] — A simple steganography library
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) — Rust bindings for OpenCV

### Language specification

* [shnewto/bnf](https://github.com/shnewto/bnf) — A library for parsing Backus–Naur form context-free grammars.

### Logging

[[log](https://crates.io/keywords/log)]

* [estk/log4rs](https://github.com/estk/log4rs) estk/log4rs — 以Java的Logback和log4j库为模型的高度可配置的日志记录框架[![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [jesusprubio/leg](https://github.com/jesusprubio/leg) jesusprubio/腿 — 懒惰开发者的优雅印花。用最小的努力让你的克莱斯更好。[![Build Status](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
* [rbatis/fast_log](https://github.com/rbatis/fast_log) — Rust async log High-performance asynchronous logging
* [rust-lang/log](https://github.com/rust-lang/log) — Logging implementation for Rust
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) — A pretty, easy-to-use logger for Rust.
* [slog-rs/slog](https://github.com/slog-rs/slog) — Structured, composable logging for Rust
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) tokio-rs/tracing — 用于异步感知结构化日志记录、错误处理、指标等的应用程序级跟踪框架[![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute) — Macro for Python-esque list comprehensions in Rust.
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) Linq-in-Rust - C # 类LINQ表达式的宏和方法。[![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — [CommonMark](https://commonmark.org/) parser in Rust

### Mobile

* Android / iOS
  * [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios) — An example of using a shared Rust lib for Android and iOS using rust-swig and cbindgen respectively.
* Generic
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — A cargo lipo subcommand which automatically creates a universal library for use with your iOS application.

### Network programming

* Bluetooth
  * [bluez/bluer](https://github.com/bluez/bluer) 蓝色/蓝色 [[bluer](https://crates.io/crates/bluer)] — Official BlueZ bindings for Rust. [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) — A [Constrained Application Protocol(CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) library for Rust.
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) — Docker daemon API in Rust
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — an [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) client for Rust
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic) 药膜/补品 — 具有async/await支持的本机gRPC客户端和服务器实现[![Crates.io](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) — The gRPC library for Rust built on C Core library and futures
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) 投掷 — 使用纯文本和libcurl运行和测试HTTP请求[![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) — A library to work with IP networks in pure Rust
  * [candrew/netsim](https://github.com/canndrew/netsim) — A Rust library for network simulation and testing
  * [jesusprubio/online](https://github.com/jesusprubio/online) jesusprubio/在线 — 用于检查Internet连接的库[![CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
* Low level
  * [actix/actix](https://github.com/actix/actix) — Actor library for Rust
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — Custom TCP/UDP protocol definitions
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — A cross-platform, low level networking
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — A network application framework for rapid development and highly scalable production deployments of clients and servers.
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) lemunozm/message-io — 事件驱动消息库构建网络应用程序简单快捷。支持TCP，UDP和WebSockets。[![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) bytebeamio/rumqtt - 一个库，供开发人员构建与[MQTT protocol](https://mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](https://nanomsg.org/) bindings
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) nats-io/nats.rs — NATS的Rust客户端，云原生消息传递系统。[![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) neachdainn/nng-rs [[Nng](https://crates.io/crates/nng)] — [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) bindings [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) [[nntp](https://crates.io/crates/nntp)] — an [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client for Rust
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) libp2p/rust-libp2p — libp2p网络堆栈的Rust实现。[![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) [[pop3](https://crates.io/crates/pop3)] — A [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) client for Rust
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic) aws/s2n-quic - IETF QUIC协议的实现![ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) cloudflare/quiche — QUIC传输协议和HTTP/3的cloudflare实现![build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)
  * [mozilla/neqo](https://github.com/mozilla/neqo) — an Implementation of QUIC written in Rust
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) 奎因-rs/奎因 — 基于期货的QUIC在Rust中的实现[![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet) b23r0/rust-raknet — Rust实现的RakNet协议[![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) ENQT-GmbH/remoc [[remoc](https://crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) — A RPC library for Rust for developing microservices in easy and simple way.
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) 1c3t3a/rust-socketio [[rust_socketio](https://crates.io/crates/rust_socketio)] — an implementation of a [socket.io](https://socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [libssh2](https://libssh2.org/) bindings
  * [Thrussh](https://pijul.org/thrussh) Thrussh [[thrussh](https://crates.io/crates/thrussh)] — an SSH library written from scratch in Rust, backed by [libsodium](https://doc.libsodium.org/)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — A [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation in Rust
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — [ZeroMQ](https://zeromq.org/) bindings

### Parsing

  * [comex/rust-shlex](https://github.com/comex/rust-shlex) comex/rust-shlex [[shlex](https://crates.io/crates/shlex)] — Split a string into shell words, like Python's shlex. [![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - A native Rust port of Google's robots.txt parser and matcher C++ library
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath) — [JsonPath](https://goessner.net/articles/JsonPath/) engine written in Rust. Webassembly and Javascript support too
  * [hmeyer/stl_io](https://crates.io/crates/stl_io) - A parser for STL (STereoLithography) files
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — Parsing Expression Grammar (PEG) parser generator
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — LR(1) parser generator for Rust
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) – A fast monadic-style parser combinator
  * [Marwes/combine](https://github.com/Marwes/combine) — parser combinator library
  * [nrc/zero](https://github.com/nrc/zero) [[zero](https://crates.io/crates/zero/)] — zero-allocation parsing of binary data
  * [pest-parser/pest](https://github.com/pest-parser/pest) — The Elegant Parser
  * [ptal/oak](https://github.com/ptal/oak) — A typed PEG parser generator (compiler plugin)
  * [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) 复制/wavefront_rs — 波前OBJ格式的解析器。[![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
  * [rust-bakery/nom](https://github.com/rust-bakery/nom) — parser combinator library
  * [s-panferov/queryst](https://github.com/s-panferov/queryst) s-panferov/queryst — Rust的查询字符串解析库的灵感来自[gs](https://github.com/ljharb/qs#readme)
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - A LR parser with better error correction

### Peripherals

* Serial Port
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) [[serialport](https://crates.io/crates/serialport)] — A cross-platform library that provides access to a serial port

### Platform specific

* Cross-platform
  * [svartalf/rust-battery](https://crates.io/crates/battery) — Cross-platform information about the notebook batteries
  * [vityafx/thread-priority](https://github.com/vityafx/thread-priority/) vityafx/线程优先级 - 简单的跨平台线程优先级管理。[![CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)] — Rust implementation of a FreeBSD jail library
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) hannobraun/inotify-rs — [inotify](https://en.wikipedia.org/wiki/Inotify) bindings [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/) — Linux distribution installer
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) [[iptables](https://crates.io/crates/iptables)] — [iptables](https://www.netfilter.org/projects/iptables/index.html) bindings
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) nix-生锈/nix — 类Unix API绑定[![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix) rustix — 安全Rust绑定到POSIX/Unix/Linux/Winsock2系统调用[![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) — [FUSE](https://github.com/libfuse/libfuse) bindings
* Windows
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs) microsoft/windows-rs — Rust for Windows[![Actions Status](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) retep998/winapi-rs — Windows API绑定[![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Scripting

[[scripting](https://crates.io/keywords/scripting)]

* [duckscript](https://crates.io/crates/duckscript) 鸭子脚本 — [Simple, extendable and embeddable scripting language.](https://github.com/sagiegurari/duckscript) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) — A Lisp-like scripting language for Rust game development
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) —  A small, statically-typed, functional programming language
* [kcl](https://github.com/kcl-lang/kcl) - A constraint-based record & functional language mainly used in configuration and policy scenarios.
* [metacall/core](https://github.com/metacall/core) metacall/核心 [[metacall](https://crates.io/crates/metacall)] — Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) — A compiled, statically-typed scripting language with first class hot reloading support
* [murarth/ketos](https://github.com/murarth/ketos) — A Lisp dialect functional programming language serving as a scripting and extension language for rust
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) — A rusty dynamically typed scripting language
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) rhaiscript/rhai — 一种小型快速的嵌入式脚本语言，类似于JavaScript和Rust的组合[![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) — An embeddable dynamic programming language for Rust

### Simulation

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) nyx-空间 - 高保真、快速、可靠和经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定[![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### System

* [ardaku/whoami](https://github.com/ardaku/whoami) ardaku/whoami [[whoami](https://crates.io/crates/whoami)] — Rust crate to get the current user and environment. [![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) 吉洛梅戈麦斯/系统信息 [[sysinfo](https://crates.io/crates/sysinfo)] — Cross-platform library to fetch system information [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[nixinfo](https://crates.io/crates/nixinfo)] — A lib crate for gathering system info such as cpu, distro, environment, kernel, etc.
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) sorairolake/sysexits-rs [[sysexits](https://crates.io/crates/sysexits)] — The system exit codes as defined by [`<sysexits.h>`](https://man.openbsd.org/sysexits). [![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)

### Task scheduling

* [delay-timer](https://github.com/BinChengZhao/delay-timer) — Time-manager of delayed tasks. Like crontab, but asynchronous tasks are possible.
[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)]( https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

* Handlebars
  * [botika/yarte](https://github.com/botika/yarte) — Yarte stands for **Y**et **A**nother **R**ust **T**emplate **E**ngine, is the fastest template engine.
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — Handlebars template engine with inheritance, custom helper support.
* HTML
  * [djc/askama](https://github.com/djc/askama) — template rendering engine based on Jinja
  * [kaj/ructe](https://github.com/kaj/ructe) — HTML template system for Rust
  * [Keats/tera](https://github.com/Keats/tera) 济慈/tera — 基于Jinja2和Django模板语言的模板引擎。[![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) — compile-time HTML templates
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — compile-time HTML templates
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) —

### Text processing

* [becheran/wildmatch](https://github.com/becheran/wildmatch) becheran/wildmatch [[wildmatch](https://crates.io/crates/wildmatch)] — Simple string matching with questionmark- and star-wildcard operator [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — Linear time suffix array construction (with Unicode support)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — Elastic tab stops (i.e., text column alignment)
* [cpc](https://github.com/probablykasper/cpc) - Parses and calculates strings of math with support for units and unit conversion, from `1+2` to `1% of round(1 lightyear / 14!s to km/h)`.
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) Daniel-Liu-c0deb0t/triple_accel [[triple_accel](https://crates.io/crates/triple_accel)] - Rust edit distance routines accelerated using SIMD; supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) fancy-regex/fancy-regex [[fancy-regex](https://crates.io/crates/fancy-regex)] - Regular expressions implementation designed to support a relatively rich set of features such as look-around and backtracking. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) — Natural language detection library based on trigrams
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)] – Generic string + iterable joining
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) mgeisler/textwrap [[textwrap](https://crates.io/crates/textwrap)] — Word wrap text (with support for hyphenation)
* [null8626/decancer](https://github.com/null8626/decancer) null8626/decancer [[decancer](https://crates.io/crates/decancer)] — A tiny package that removes common unicode confusables/homoglyphs from strings. [![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) — A reader that allows forwards, backwards and random navigations through the lines of huge files without consuming iterators
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) [[ngrams](https://crates.io/crates/ngrams)] — Construct [n-grams](https://en.wikipedia.org/wiki/N-gram) from arbitrary iterators
* [rust-lang/regex](https://github.com/rust-lang/regex) — Regular expressions (RE2 style)
* [strsim-rs](https://crates.io/crates/strsim) — String similarity metrics
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)] — Multilingual implementation of RAKE algorithm for Rust

### Text search

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] — A simple and lightweight fuzzy search engine that works in memory, searching for similar strings
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] —
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) CurrySoftware/perlin [[perlin](https://crates.io/crates/perlin)]
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) meilisearch/MeiliSearch — 超相关，即时和错字容错全文搜索API。[![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [tantivy](https://github.com/quickwit-oss/tantivy) 坦蒂维 [[tantivy](https://crates.io/crates/tantivy)] — A horse-speed full-text search engine library written in Rust. [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy) — Utilities for safely reinterpreting arbitrary byte sequences as native Rust types

### Video

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar) ffmpeg-sidecar — 在直观的迭代器界面中包装独立的FFmpeg二进制文件。[![Build Status](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml)

### Virtualization

* [beneills/quantum](https://github.com/beneills/quantum) — Advanced Rust quantum computer simulator
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) 字节联盟/wasmtime — WebAssembly的独立运行时[![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM — Enables Chrome OS to run Linux apps inside a fast, secure virtualized environment
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - Rust-based userspace program for illumos bhyve kernel modules
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — Hardware-accelerated virtualization on OS X
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) — Rust bindings for the unicorn CPU emulator

### Web programming
另请参见[Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison)

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) — A Cargo subcommand for the client-side Web
  * [leptos](https://github.com/leptos-rs/leptos) leptos — Leptos是一个全栈，同构的Rust web框架，利用细粒度的反应性来构建声明性用户界面。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)
  * [sauron](https://github.com/ivanceras/sauron) - Client side web framework which closely adheres to The Elm Architecture.
  * [seed](https://seed-rs.org/) — A Rust framework for creating web apps
  * [stdweb](https://crates.io/crates/stdweb) — A standard library for the client-side Web
  * [yew](https://crates.io/crates/yew) — Rust framework for making client web apps
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) — [libcurl](https://curl.se/libcurl/) bindings
  * [async-graphql](https://github.com/async-graphql/async-graphql) async-graphql - 在Rust中实现的GraphQL服务器库[![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) 杜马纳什/yukikaze [[yukikaze](https://crates.io/crates/yukikaze)] — Beautiful and elegant Yukikaze is little HTTP client library based on hyper. [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh) 杜卡莱/xh - 用于发送HTTP请求的友好且快速的工具[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![Github actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) graphql-客户端 — 在Rust中输入正确的GraphQL请求和响应。[![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) hyperium/hyper — 一个HTTP实现[![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) — an ergonomic HTTP Client for Rust.
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web) — A lightweight async web framework for Rust with websocket support
  * [Anansi](https://github.com/saru-tora/anansi) — A simple full-stack web framework for Rust.
  * [branca](https://crates.io/crates/branca) — A Pure Rust implementation of Branca for Authenticated and Encrypted API tokens.
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)] — A fast, boilerplate free, web framework for Rust
  * [danclive/sincere](https://github.com/danclive/sincere) — A micro web framework for Rust(stable) based on hyper and multithreading.
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) — JSON Web Token implementation in Rust.
  * [Gotham](https://github.com/gotham-rs/gotham) — A flexible web framework that does not sacrifice safety, security or speed.
  * [Graphul](https://github.com/graphul-rs/graphul) Graphul — 一个用Rust编写的Express风格的web框架。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) — an Iron web framework middleware.
  * [hyperium/hyper](https://github.com/hyperium/hyper) hyperium/hyper — 一个HTTP实现[![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Iron](https://github.com/iron/iron) — A middleware-based server framework
  * [Juniper](https://github.com/graphql-rust/juniper) — GraphQL server library for Rust
  * [miketang84/sapper](https://github.com/miketang84/sapper) — A lightweight web framework built on async hyper, implemented in Rust language.
  * [Nickel](https://github.com/nickel-org/nickel.rs/) 镍 — 灵感来自[Express](http://expressjs.com/)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) — A RESTful web framework for Rust
  * [poem-web/poem](https://github.com/poem-web/poem) 诗歌-web/诗歌 - 一个功能齐全，易于使用的web框架与Rust编程语言。[![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rocket](https://github.com/SergioBenitez/Rocket) — Rocket is web framework for Rust (nightly) with a focus on ease-of-use, expressability, and speed
  * [Rustless](https://github.com/rustless/rustless) 无锈 — 一个类似REST的API微框架的灵感来自[Grape](https://github.com/ruby-grape/grape) and [Hyper](https://github.com/hyperium/hyper)
  * [Salvo](https://github.com/salvo-rs/salvo) 齐射 — 一个易于使用的基于hyper和tokio的web框架。[![build build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) — A progressive web framework with low-level control, without the pain.
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) seanmonstar/warp — 一个超级简单，可组合的web服务器框架，用于warp速度。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http) — Low level HTTP server library
  * [tokio/axum](https://github.com/tokio-rs/axum) tokio/axum - 采用Tokio、Tower和Hyper构建的人体工程学和模块化web框架[![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille) — Web framework in Rust
* Miscellaneous
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) — A web framework intended for building maintainable, well-factored web apps.
  * [causal-agent/scraper](https://github.com/causal-agent/scraper) 因果代理/刮刀 [[scraper](https://crates.io/crates/scraper)] - HTML parsing and querying with CSS selectors. [![Build Status](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
  * [hominee/dyer](https://github.com/hominee/dyer) [[dyer](https://crates.io/crates/dyer)] - dyer is designed for reliable, flexible and fast Request-Response based service, including data processing, web-crawling and so on, providing some friendly, flexible, comprehensive features without compromising speed.
  * [juhaku/utoipa](https://github.com/juhaku/utoipa) juhaku/utoipa - 简单，快速，代码优先和编译时生成的Rust OpenAPI文档[![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [osohq/oso](https://github.com/osohq/oso) osohq/oso [[oso](https://crates.io/crates/oso)] - A policy engine for authorization that's embedded in your application. [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) pwoolcoc/汤 [[soup](https://crates.io/crates/soup)] — A library similar to Python's BeautifulSoup, designed to enable quick and easy manipulation and querying of HTML documents. [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) — A macro to embed static assets into the rust binary
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)] - A Rust library for the Discord API
  * [softprops/openapi](https://github.com/softprops/openapi) — A library for processing openapi spec files
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) [[svix](https://crates.io/crates/svix)]- A library for sending webhooks and verifying signatures.
  * [tbot](https://gitlab.com/SnejUgal/tbot) tbot [[tbot](https://crates.io/crates/tbot)] - Make cool Telegram bots with Rust easily [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) teloxide/teloxide - 一个优雅的电报机器人Rust框架[![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] — A library to extract useful data from HTML documents, suitable for web scraping.
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) sozu-代理/sozu [[sozu](https://crates.io/crates/sozu)] — A HTTP reverse proxy. [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) 钴-org/cobalt.rs — 用Rust编写的静态站点生成器[![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)] — Static site generator from markdown files.
  * [getzola/zola](https://github.com/getzola/zola) getzola/zola [[zola](https://www.getzola.org/)] — An opinionated static site generator with everything built-in. [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) [[blades](https://getblades.org/)] — Blazing fast dead simple static site generator.
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)] — A simple, parallelized blog generator.
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — lightweight, event-driven WebSockets for Rust
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) — A framework for dealing with WebSocket connections (both clients and servers)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) — Lightweight stream-based WebSocket implementation for Rust.
  * [vi/websocat](https://github.com/vi/websocat) — CLI for interacting with WebSockets, with functionality of Netcat, Curl and Socat.
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) vityafx/urlshortener-rs — 一个非常简单的用于Rust的urlshortener库。[![CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## Registries
 A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry) — A fully managed package management SaaS, with first-class support for public and private Cargo/Rust registries (plus many others). Has a generous free-tier and is also completely free for open-source.
* [Crates](https://crates.io) — The official public registry for Rust/Cargo.
* [w4/chartered](https://github.com/w4/chartered) w4/特许 - 一个私人的、经过认证的、许可的货物登记处[![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

* Benchmarks
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) TeXitoi/基准测试游戏-rs — 的Rust实现[The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/)
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — Presented by [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) — Presented by [Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) — Presented by [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
* [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust) - A curated list of Rust libraries, authors, kits, tutorials & learning resources on kandi
* Learning
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope) - Interactive visualizations of Rust at compile-time and run-time
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - A community curated list of livestreams about Rust.
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) — A list of helpful Rust mentors willing to take mentees and educate them about Rust and programming.
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) — Build your own Redis, Git, Docker, or SQLite in Rust
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/) 综合锈蚀 — 为期3天的Rust基础课程，以及为期1天的Android，裸机Rust和并发课程。提供英文，[Brazilian Portuguese](https://google.github.io/comprehensive-rust/pt-BR/), and [Korean](https://google.github.io/comprehensive-rust/ko/)
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) - Learn Rust in easy English.
  * [exercism.org](https://exercism.org/tracks/rust) — programming exercises that help you learn new concepts in Rust.
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) 动手生锈 - 通过制作游戏来学习Rust的动手指南-by[Herbert Wolverson](https://github.com/thebracket/) (paid)
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) —  A peer-reviewed collection of articles/talks/repos which teach idiomatic Rust.
  * [Learn Rust by 500 lines code](https://github.com/cuppar/rtd) — Learn Rust by 500 lines code, build a Todo Cli Application from scratch.
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) — in-depth exploration of Rust's memory management rules, through implementing a few different types of list structures.
  * [Little Book of Rust Books](https://lborb.github.io/book/) - Curated list of rust books and how-tos.
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) — A list of recommended resources voted by the programming community.
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - A book that introduces to Rust language.
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — A collection of simple examples that demonstrate good practices to accomplish common programming tasks, using the crates of the Rust ecosystem.
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) — A quick introduction to Rust for experienced software developers.
  * [Rust Gym](https://github.com/warycat/rustgym) - A big collection of coding interview problems solved in Rust.
  * [Rust in Action](https://www.manning.com/books/rust-in-action) 生锈在行动 — 使用Rust进行系统编程的动手指南[Tim McNamara](https://github.com/timClicks) (paid)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) 运动中的生锈 — 视频系列由[Carol Nichols](https://github.com/carols10cents) and [Jake Goulding](https://github.com/shepmaster) (paid)
  * [Rust Language Cheat Sheet](https://cheats.rs/)
  * [Rust Online Courses at Classpert](https://classpert.com/search/rust) — A list of Rust online courses (paid) from Classpert Online Course Search
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - Learn Rust in Vietnamese.
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) - A repo dedicated to answering the question: "So, Rust. How do I _start_?". A beginner only hand-picked resources and learning track.
  * [rust-learning](https://github.com/ctjhoa/rust-learning) — A collection of useful resources to learn Rust
  * [Rustlings](https://github.com/rust-lang/rustlings) — small exercises to get you used to reading and writing Rust code
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - A Computer Science Curriculum that helps practice the acquired academic knowledge in Rust
  * [stdx](https://github.com/brson/stdx) — Learn these crates first as an extension to std
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - Lay the foundation of knowledge you need to build fast and effective programs in Rust.
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
* Podcasts
  * [New Rustacean](https://newrustacean.com) — A podcast about learning Rust
  * [Rustacean Station](https://rustacean-station.org/) — A community project for creating podcast content for Rust
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) - Build backend servers, services, and front-ends in Rust to get fast, reliable, and maintainable applications.
* [Rust Subreddit](https://www.reddit.com/r/rust/) — A subreddit(forum) where rust related questions, articles and resources are posted and discussed
* [RustBooks](https://github.com/sger/RustBooks) — list of RustBooks
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* [RustViz](https://github.com/rustviz/rustviz) — generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 
