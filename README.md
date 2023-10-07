# Awesome Rust [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [Applications](#applications) — 应用
  * [Audio and Music](#audio-and-music) — 音频和音乐
  * [Cryptocurrencies](#cryptocurrencies) — 加密货币
  * [Database](#database) — 数据库
  * [Emulators](#emulators) — 仿真器
  * [Games](#games) — 游戏
  * [Graphics](#graphics) — 图形
  * [Image processing](#image-processing) — 图像处理
  * [Industrial automation](#industrial-automation) — 工业自动化
  * [Observability](#observability) — 可观察性
  * [Operating systems](#operating-systems) — 操作系统
  * [Payments](#payments) — 付款
  * [Productivity](#productivity) — 生产力
  * [Routing protocols](#routing-protocols) — 路由协议
  * [Security tools](#security-tools) — 安全工具
  * [Simulation](#simulation) — 仿真
  * [Social networks](#social-networks) — 社交网络
  * [System tools](#system-tools) — 系统工具
  * [Task scheduling](#task-scheduling) — 任务调度
  * [Text editors](#text-editors) — 文本编辑器
  * [Text processing](#text-processing) — 文本处理
  * [Utilities](#utilities) — 公用事业
  * [Video](#video) — 视频
  * [Virtualization](#virtualization) — 虚拟化
  * [Web](#web) — Web
  * [Web Servers](#web-servers) — 网络服务器
- [Development tools](#development-tools) — 开发工具
  * [Build system](#build-system) — 构建系统
  * [Debugging](#debugging) — 调试
  * [Deployment](#deployment) — 部署
  * [Embedded](#embedded) — 嵌入式
  * [FFI](#ffi) — FFI
  * [Formatters](#formatters) — 格式化器
  * [IDEs](#ides) — IDEs
  * [Profiling](#profiling) — 剖析
  * [Services](#services) — 服务
  * [Static analysis](#static-analysis) — 静态分析
  * [Testing](#testing) — 测试
  * [Transpiling](#transpiling) — 换位
- [Libraries](#libraries) — 图书馆
  * [Artificial Intelligence](#artificial-intelligence) — 人工智能
    + [Genetic algorithms](#genetic-algorithms)
    + [Machine learning](#machine-learning)
    + [OpenAI](#openai)
  * [Astronomy](#astronomy) — 天文学
  * [Asynchronous](#asynchronous) — 异步
  * [Audio and Music](#audio-and-music-1) — 音频和音乐
  * [Authentication](#authentication) — 身份验证
  * [Automotive](#automotive) — 汽车
  * [Bioinformatics](#bioinformatics) — 生物信息学
  * [Caching](#caching) — 缓存
  * [Cloud](#cloud) — 云
  * [Command-line](#command-line) — 命令行
  * [Compression](#compression) — 压缩
  * [Computation](#computation) — 计算
  * [Concurrency](#concurrency) — 并发
  * [Configuration](#configuration) — 配置
  * [Cryptography](#cryptography) — 密码学
  * [Data processing](#data-processing) — 数据处理
  * [Data streaming](#data-streaming) — 数据流
  * [Data structures](#data-structures) — 数据结构
  * [Data visualization](#data-visualization) — 数据可视化
  * [Database](#database-1) — 数据库
  * [Date and time](#date-and-time) — 日期和时间
  * [Distributed systems](#distributed-systems) — 分布式系统
  * [Domain driven design](#domain-driven-design) — 域驱动设计
  * [eBPF](#ebpf) — eBPF
  * [Email](#email) — 电子邮件
  * [Encoding](#encoding) — 编码
  * [Filesystem](#filesystem) — 文件系统
  * [Finance](#finance) — 金融
  * [Functional Programming](#functional-programming) — 函数式编程
  * [Game development](#game-development) — 游戏开发
  * [Geospatial](#geospatial) — 地理空间
  * [Graph algorithms](#graph-algorithms) — 图算法
  * [Graphics](#graphics-1) — 图形
  * [GUI](#gui) — 图形用户界面
  * [Image processing](#image-processing-1) — 图像处理
  * [Language specification](#language-specification) — 语言规范
  * [Logging](#logging) — 日志记录
  * [Macro](#macro) — 宏
  * [Markup language](#markup-language) — 标记语言
  * [Mobile](#mobile) — 移动
  * [Network programming](#network-programming) — 网络编程
  * [Parsing](#parsing) — 解析
  * [Peripherals](#peripherals) — 外围设备
  * [Platform specific](#platform-specific) — 特定平台
  * [Scripting](#scripting) — 脚本
  * [Simulation](#simulation-1) — 仿真
  * [System](#system) — 系统
  * [Task scheduling](#task-scheduling-1) — 任务调度
  * [Template engine](#template-engine) — 模板引擎
  * [Text processing](#text-processing-1) — 文本处理
  * [Text search](#text-search) — 文本搜索
  * [Unsafe](#unsafe) — 不安全
  * [Video](#video-1) — 视频
  * [Virtualization](#virtualization-1) — 虚拟化
  * [Web programming](#web-programming) — 网络编程
- [Registries](#registries) — 登记处
- [Resources](#resources) — 资源
- [License](#license) — 许可证

<!-- tocstop -->

## Applications

See also [Rust — Production](https://www.rust-lang.org/production) organizations running Rust in production.

* [alacritty](https://github.com/alacritty/alacritty)  — 一种跨平台的GPU增强型终端仿真器 
* [Arti](https://gitlab.torproject.org/tpo/core/arti)  — Tor的一种实现，在Rust中。(到目前为止，它不是一个非常完整的客户端。但是请注意这个空间!) [![Crates.io](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust)  — 用rust编写的交互式装配外壳 
* [broot](https://github.com/Canop/broot)  — 查看和导航目录树的新方法 (获取目录的概述，甚至是大目录; 找到一个目录，然后将其 “cd” 到目录; 搜索时永远不会丢失文件层次结构; 操作文件，...)，进一步阅读 [dystroy.org/broot](https://dystroy.org/broot/) [![Latest Version](https://img.shields.io/crates/v/broot.svg)](https://crates.io/crates/broot)
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun)  — 一种用户空间WireGuard VPN实现 [![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
* [datafusion](https://github.com/apache/arrow-datafusion)  — 阿帕奇箭头数据融合和弩炮查询引擎 
* [denoland/deno](https://github.com/denoland/deno)  — 用V8、Rust和Tokio构建的安全JavaScript/打字稿运行时 [![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
* [doprz/dipc](https://github.com/doprz/dipc)  — 用你最喜欢的调色板/主题转换你最喜欢的图像和壁纸 [![crates.io](https://img.shields.io/crates/v/dipc)](https://crates.io/crates/dipc)
* [Factotum](https://github.com/snowplow/factotum)  — [一个以编程方式运行数据管道的系统](https://snowplow.io/blog/introduct防-factotum-data-pipeline-runner/) 
* [fcsonline/drill](https://github.com/fcsonline/drill)  — 受Ansible语法启发的HTTP负载测试应用程序 
* [fend](https://github.com/printfn/fend)  — 任意精度单位感知计算器 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
* [Fractalide](https://github.com/fractalide/fractalide)  — 简单锈微服务 
* [habitat](https://github.com/habitat-sh/habitat)  — 由Chef创建的用于构建，部署和管理应用程序的工具。 
* [Herd](https://github.com/imjacobclark/Herd)  — 一个实验性的HTTP负载测试应用程序 
* [innernet](https://github.com/tonarino/innernet)  — 在引擎盖下使用Wireguard的覆盖或专用网状网络 
* [jedisct1/flowgger](https://github.com/awslabs/flowgger)  — 快速、简单、轻便的数据收集器 
* [kalker](https://github.com/PaddiM8/kalker)  — 一种科学的计算器，支持类似数学的语法，具有用户定义的变量，函数，推导，积分和复数。跨平台WASM支持 [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kytan](https://github.com/changlan/kytan)  — 高性能对等VPN 
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy)  — Kubernetes的超轻服务网格。 
* [MaidSafe](https://github.com/maidsafe)  — 一个分散的平台。 
* [mdBook](https://github.com/rust-lang/mdBook)  — 从markdown文件创建书籍的命令行实用程序 [![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon)  — 适用于linux和macosx的steam和无drm游戏注册表和启动器 
* [notty](https://github.com/withoutboats/notty)  — 一种新型终端 
* [Pijul](https://pijul.org)  — 一种基于补丁的分布式版本控制系统 
* [Rio](https://github.com/raphamorim/rio)  — 由WebGPU提供支持的硬件加速GPU终端仿真器，专注于在台式机和浏览器中运行。 
* [rx](https://github.com/cloudhead/rx)  — Vi启发现代像素艺术编辑器 
* [Servo](https://github.com/servo/servo)  — 一个原型网络浏览器引擎 
* [shoes](https://github.com/cfal/shoes)  — 一种多协议代理服务器 
* [shuttle](https://github.com/shuttle-hq/shuttle)  — 为生锈而建造的无服务器平台 
* [Sniffnet](https://github.com/GyulyVGC/sniffnet)  — 跨平台应用程序可轻松监控您的网络流量 [![build badge](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)
* [SWC](https://github.com/swc-project/swc)  — 超快打字稿/JavaScript编译器 
* [tiny](https://github.com/osa1/tiny)  — 终端IRC客户端 
* [trust-dns](https://crates.io/crates/trust-dns)  — 域名系统服务器 [![Build Status](https://github.com/bluejekyll/trust-dns/workflows/test/badge.svg?branch=main)](https://github.com/bluejekyll/trust-dns/actions?query=workflow%3Atest)
* [wasmer](https://github.com/wasmerio/wasmer)  — 支持WASI和Emscripten的安全快速WebAssembly运行时 [![Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld)  — 全假REST API生成器 
* [wezterm](https://github.com/wez/wezterm)  — 一种GPU加速跨平台终端仿真器和多路复用器 
* [zellij](https://github.com/zellij-org/zellij)  — 包括电池的终端多路复用器 (工作区) 
### Audio and Music

* [enginesound](https://github.com/DasEtwas/enginesound)  — GUI和命令行应用程序，用于程序生成半逼真的引擎声音。具有深入的配置，可变的采样率和频率分析窗口。 
* [figsoda/mmtc](https://github.com/figsoda/mmtc) [[mmtc](https://crates.io/crates/mmtc)]  — 旨在简单但高度可配置的最小mpd终端客户端 [![build-badge](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)
* [Glicol](https://github.com/chaosprint/glicol)  — 用Rust编写的面向图形的实时编码语言，用于在浏览器中进行协作音乐。 
* [ncspot](https://github.com/hrkfdn/ncspot)  — 跨平台ncurses Spotify客户端，灵感来自ncmpc等。 [![build badge](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* [Polaris](https://github.com/agersant/polaris)  — 音乐流应用程序。 
* [Spotify TUI](https://github.com/Rigellute/spotify-tui)  — 用Rust写的终端的Spotify客户端。! [Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd)  — 作为UNIX守护程序运行的开源Spotify客户端。! [Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)
* [WhatBPM](https://github.com/sergree/whatbpm)  — 电子舞曲制作人每日静态生成的信息资源。使用Beatport和Spotify等公开可用的数据，对每种EDM类型的最常用值提供每日分析: 节奏，键，根注释等。! [Continuous Integration](https://github.com/sergree/whatbpm/actions/workflows/website_build_deploy.yml/badge.svg?branch=main)

### Cryptocurrencies

* [artemis](https://github.com/paradigmxyz/artemis)  — 一个简单、模块化、快速的框架，用于在Rust中编写MEV机器人。 
* [beerus](https://github.com/keep-starknet-strange/beerus)  — Beerus是一个不信任的StarkNet轻客户，⚡炽热的速度⚡由铁锈驱动 [![GitHub Workflow Status](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml)
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)]  — 用于处理比特币SV的Rust库 
* [cairo](https://github.com/starkware-libs/cairo)  — Cairo是第一个创建通用计算可证明程序的图灵完备语言。这也是 [StarkNet](https://www.starknet.io/en), a ZK-Rollup using STARK proofs ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)
* [cairo-vm](https://github.com/lambdaclass/cairo-vm)  — 开罗虚拟机的Rust实现 [![rust](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml)
* [ChainX](https://github.com/chainx-org/ChainX)  — Polkadot上完全分散的链间加密资产管理。 
* [CITA](https://github.com/citahub/cita)  — 面向企业用户的高性能区块链内核 
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs)  — Rust中的Coinbase pro客户端，支持同步/异步/websocket 
* [Diem](https://github.com/diem/diem)  — Diem的使命是建立一个简单的全球货币和金融基础设施，赋予数十亿人权力。 
* [electrumrs](https://github.com/romanz/electrs)  — 在Rust中高效地重新实现Electrum服务器。 
* [ethabi](https://github.com/rust-ethereum/ethabi)  — 对智能合约调用进行编码和解码。 
* [ethaddrgen](https://github.com/Limeth/ethaddrgen)  — 自定义以太坊虚荣地址生成器铁锈制造 
* [ethers-rs](https://github.com/gakonst/ethers-rs)  — 在Rust中完成Ethereum & Celo库和钱包实现。! [Build Status](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
* [etk](https://github.com/quilt/etk)  — etk是用于编写，读取和分析EVM字节码的工具的集合。 
* [Forest](https://github.com/ChainSafe/forest)  — Rust Filecoin实现 [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* [Foundry](https://github.com/foundry-rs/foundry)  — Foundry是用Rust编写的用于以太坊应用程序开发的快速，便携式和模块化工具包。! [Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
* [Grin](https://github.com/mimblewimble/grin/)  — MimbleWimble协议的演变 
* [hdwallet](https://github.com/jjyr/hdwallet) [[hdwallet](https://crates.io/crates/hdwallet)]  — BIP-32高清钱包相关密钥派生实用程序。 
* [Holochain](https://github.com/holochain/holochain)  — 适用于您一直想要构建的所有分布式应用程序的可扩展P2P替代区块链。 [![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
* [ibc-rs](https://github.com/informalsystems/hermes)  — [区块链间通信](https://ibc.cosmos.net工作/) 协议的Rust实现 
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) [[bip39](https://crates.io/crates/bip39)]  — Bip39的Rust实现。 
* [interBTC](https://github.com/interlay/interbtc)  — 无信任和完全去中心化的比特币桥到波尔卡多特和草间。 
* [Joystream](https://github.com/Joystream/joystream)  — 用户管理的视频平台 
* [Lighthouse](https://github.com/sigp/lighthouse)  — Rust以太坊共识层 (CL) 客户端 [![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
* [madara](https://github.com/keep-starknet-strange/madara)  — Kaioshin是一个⚡炽热的速度⚡Starknet音序器，基于基底，用铁锈书写。 [![GitHub Workflow Status](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml)
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs)  — 生锈的Ethereum MEV检查员 
* [near/nearcore](https://github.com/near/nearcore)  — 面向低端移动设备的分散式智能合约平台。 
* [Nervos CKB](https://github.com/nervosnetwork/ckb)  — Nervos CKB是一个公共无权限区块链，是Nervos网络的常识层。 
* [Nimiq](https://github.com/nimiq/core-rs)  — Nimiq节点的Rust实现 
* [opensea-rs](https://github.com/gakonst/opensea-rs)  — Rust绑定和CLI到Opensea API和合同。 
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin)  — 平价比特币客户端 
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain)  — 基于英特尔SGX和基板的机密智能合约区块链 
* [Polkadot](https://github.com/paritytech/polkadot)  — 具有池化安全性的异构多链技术 
* [revm](https://github.com/bluealloy/revm)  — 革命机器 (Revolutionary Machine，revm) 是用rust编写的快速以太坊虚拟机。 
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)  — 库支持去/序列化，解析和执行与比特币相关的数据结构和网络消息。 
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning)  — [![板条箱](https:// img.shields.io/crates/v/lightning.svg？logo = rust)](https:// crates.io/crates/lightning) -用Rust编写的比特币闪电库主板条箱 “闪电” 不处理网络、持久性或任何其他I/O。因此，它是与运行时无关的，但是用户必须在链接板条箱上实现基本的网络逻辑，链交互和磁盘存储.po。 
* [sigma-rust](https://github.com/ergoplatform/sigma-rust)  — ErgoTree解释器和钱包相关功能的Rust实现 
* [Solana](https://github.com/solana-labs/solana)  — 使用历史证明的令人难以置信的快速、高度可扩展的区块链。 
* [Substrate](https://github.com/paritytech/substrate)  — 用Rust编写的通用模块化区块链模板 
* [svm-rs](https://github.com/alloy-rs/svm-rs)  — Solidity-编译器版本管理器 
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs)  — Tendermint区块链数据结构和客户端的Rust实现 
* [wagyu](https://github.com/howardwu/wagyu) [[wagyu](https://crates.io/crates/wagyu)]  — 用于生成加密货币钱包的Rust库 
* [zcash](https://github.com/zcash/zcash)  — Zcash是 “Zerocash” 协议的实现。 
### Database

* [Atomic-Server](https://github.com/atomicdata-dev/atomic-server/) [[atomic-server](https://crates.io/crates/atomic_server)]  — 具有实时更新、动态索引和易于使用的图形用户界面的NoSQL图形数据库，用于CMS目的。 [![Release](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml/badge.svg)](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml)
* [CozoDB](https://github.com/cozodb/cozo)  — 一个使用Datalog的事务性关系数据库，专注于图形数据和算法。时间旅行能力强，速度快! [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
* [Databend](https://github.com/datafuselabs/databend)  — 具有云原生架构的现代实时数据处理和分析DBMS [![Release](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* [DB3 Network](https://github.com/dbpunk-labs/db3)  — DB3是一个社区驱动的区块链层2去中心化数据库网络! [GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/dbpunk-labs/db3/ci.yml?branch=main&style=flat-square)
* [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/)  — 支持PromQL/SQL/Python的开源、云原生、分布式时序数据库。 [![CI](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)
* [indradb](https://crates.io/crates/indradb)  — 基于Rust的图数据库 
* [Lucid](https://github.com/lucid-kv/lucid)  — 高性能和分布式KV存储可通过HTTP API访问。 [![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [Materialize](https://github.com/MaterializeInc/materialize)  — 由及时数据流提供支持的流sql数据库: heavy_dollar_sign: [![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
* [Neon](https://github.com/neondatabase/neon)  — 无服务器Postgres。我们将存储和计算分开，以提供自动缩放，分支和无底存储。 
* [noria](https://github.com/mit-pdos/noria) [[noria](https://crates.io/crates/noria)]  — 为web应用程序后端动态更改部分状态的数据流 
* [ParityDB](https://github.com/paritytech/parity-db)  — 快速可靠的数据库，针对读取操作进行了优化 
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB)  — 事件源数据库引擎 
* [Qdrant](https://github.com/qdrant/qdrant)  — 具有扩展过滤支持的开源向量相似性搜索引擎 [![Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave)  — 云中的下一代流媒体数据库 [![CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis)  — Rust中的Redis重新实现 
* [Skytable](https://github.com/skytable/skytable)  — 一个多模型的NoSQL数据库! [GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* [sled](https://crates.io/crates/sled)  — A (beta) 现代嵌入式数据库 [![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SurrealDB](https://github.com/surrealdb/surrealdb)  — 可扩展的分布式文档图数据库 [![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store)  — 开源图形数据库和文档存储 [![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv)  — Rust中的分布式KV数据库 [![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx-sys](https://crates.io/crates/mdbx-sys)]  — 用于MDBX的Rust绑定，这是一个 “快速，紧凑，功能强大，嵌入式，具有许可许可证的事务性键值数据库”。这是mozilla/lmdb-rs的一个分支，带有补丁，使其与libmdbx一起工作。 
* [WooriDB](https://github.com/naomijub/wooridb)  — 受Crux和Datomic启发的通用时间序列数据库。 
### Emulators

See also [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

* CHIP-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8)  — 用铁锈编写的WebAssembly CHIP-8仿真器 
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust)  — 另一个rust chip8仿真器 
* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64)  — * 闪存播放器 
  * [Ruffle](https://github.com/ruffle-rs/ruffle)  — Ruffle是用Rust编程语言编写的Adobe Flash Player模拟器。皱褶使用WebAssembly同时针对桌面和网络。 [![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb)  — * [joamag/boytacean](https://github.com/joamag/boytacean) -使用WebAssembly在网络上运行的Rust编写的GameBoy颜色模拟器。 
  * [mohanson/gameboy](https://github.com/mohanson/gameboy)  — 全功能跨平台GameBoy模拟器。永远的男孩!。 
  * [mvdnes/rboy](https://github.com/mvdnes/rboy)  — * 游戏男孩前进 
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng)  — RustboyAdvance-ng是一款具有桌面、安卓和 [WebAssembly](https://michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* GameMaker
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK)  — OpenGMK是专有的GameMaker Classic引擎的现代重写，提供了完整的runner源端口，反编译器，tassing框架以及用于自己使用gamedata的库。 
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080)  — 英特尔8080 cpu仿真器by Rust 
* iOS
  * [touchHLE](https://github.com/hikari-no-yume/touchHLE)  — 适用于iPhone OS应用程序的高级模拟器 
* iPod
  * [clicky](https://github.com/daniel5151/clicky)  — 一个点击轮iPod模拟器 (WIP) 
* NES
  * [koute/pinky](https://github.com/koute/pinky)  — * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
* Nintendo DS
  * [dust](https://github.com/kelpsyberry/dust)  — 用Rust编写的任天堂DS模拟器 
* PlayStation 4
  * [Obliteration](https://github.com/obhq/obliteration)  — 用Rust编写的实验PS4仿真器，用于Windows、macOS和Linux [![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx)  — [! [RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### Games

See also [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [citybound](https://github.com/citybound/citybound)  — 你应得的城市模拟 
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom)  — Doom的渲染器可能会发展成为可玩游戏 
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs)  — 洞穴故事引擎的Rust重新实现，并进行了一些增强。 
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins)  — 具有像素艺术的可扩展开放世界流氓游戏 
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium)  — Ferium是一个快速和功能丰富的CLI程序，用于从Modrinth、CurseForge和GitHub版本下载和更新Minecraft mods，以及从Modrinth和CurseForge下载和更新modpacks! [ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust)  — 支持BMS格式的简约音乐视频游戏 
* [maras-archive/rsnake](https://github.com/maras-archive/rsnake)  — 铁锈写的蛇。 
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi)  — 电脑游戏保存的备份工具 [![build badge](https://img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?logo=github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![crate](https://img.shields.io/crates/v/ludusavi?logo=rust)](https://crates.io/crates/ludusavi)
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth)  — 一个小型的2D回位六边形策略游戏 
* [rhex](https://github.com/dpc/rhex)  — 六角ascii roguelike 
* [rsaarelm/magog](https://github.com/rsaarelm/magog)  — Rust中的roguelike游戏 
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48)  — Mk48.io是一款在线多人海军战斗游戏 
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs)  — 一个索科班的实现 
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy)  — 一款致力于成为新游戏开发者做出第一贡献的切入点的太空射击游戏。! [build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake)  — 铁锈中的地震地图渲染器 
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer)  — 为终端编写的单人打字测试游戏 
* [Veloren](https://gitlab.com/veloren/veloren)  — 一款开放世界、开源的多人体素RPG游戏目前正在阿尔法开发中 [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [Zone of Control](https://github.com/ozkriff/zoc)  — 基于回合的六边形策略游戏 
### Graphics

* [ivanceras/svgbob](https://github.com/ivanceras/svgbob)  — 将ASCII图转换为SVG图形 
* [Limeth/euclider](https://github.com/Limeth/euclider)  — 一种实时4D中央处理器射线跟踪器 
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg)  — 一个SVG渲染库。 
* [rustq/vue-skia](https://github.com/rustq/vue-skia)  — 基于Skia的2d图形vue渲染库。它基于Rust来实现软件光栅化来执行渲染。 
* [turnage/valora](https://crates.io/crates/valora)  — 生成美术图书馆! [Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust)  — 射线示踪剂 
### Image processing

* [Imager](https://github.com/imager-io/imager)  — 自动图像优化。 
* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) [[oxipng](https://crates.io/crates/oxipng)]  — 用Rust编写的多线程PNG优化器。 [![Build Status](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Industrial automation

* [locka99/opcua](https://github.com/locka99/opcua)  — 纯锈 [OPC UA](https://opcfoundation.org/about/opc-技术/opc-ua/) 库。 
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus)  — 基于 [tokio](https:// tokio.rs) 的 [modbus](https://modbus.org) 库。 
### Observability

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino)  — 高性能可扩展StatsD兼容服务器 
* [OpenTelemetry](https://crates.io/crates/opentelemetry)  — Opentelemetrie提供了一组api、库、代理和收集器服务，用于从应用程序中捕获分布式跟踪和度量。您可以使用Prometheus，Jaeger和其他可观察性工具对其进行分析。 [![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit)  — 云原生且高成本效益的日志管理搜索引擎。 [![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* [Scaphandre](https://github.com/hubblo-org/scaphandre)  — 功耗监控代理，用于跟踪主机和每个服务的功耗，并能够设计系统和应用程序以实现更大的可持续性。设计适合任何监控工具链 (已经支持普罗米修斯，warp10，黎曼...)。 
* [vectordotdev/vector](https://github.com/vectordotdev/vector)  — 高性能、日志、度量和事件路由器。 
### Operating systems

See also [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison).
* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)  — -用于armv8-a架构的操作系统。 
* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero)  — 遵循单片内核设计的现代类unix操作系统。 
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox)  — * [Powersgang/rust_os](https://github.com/thepowersgang/rust_os)- 
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus)  — 一种安全语言、单一地址空间和单一特权级别的操作系统，从头开始用纯铁锈编写- [![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock)  — 用于基于Cortex-M的微控制器的安全嵌入式操作系统 
### Payments

* [hyperswitch](https://github.com/juspay/hyperswitch)  — 一个开源支付协调器，可让您与多个支付处理器连接，并毫不费力地路由支付流量，所有这些都需要一个API集成! [GitHub last commit](https://img.shields.io/github/last-commit/juspay/hyperswitch?style=flat-square)

### Productivity

* [Bartib](https://github.com/nikolassv/bartib) [[Bartib](https://crates.io/crates/bartib)]  — 命令行的简单时间跟踪器 [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [espanso](https://github.com/espanso/espanso)  — 用Rust编写的跨平台文本扩展器 [![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka)  — 一个CLI工具，可以在不离开终端的情况下输入和存储您的想法 
* [Furtherance](https://github.com/lakoliu/Furtherance)  — 使用Rust和GTK4构建的时间跟踪应用程序 
* [illacloud/illa](https://github.com/illacloud/illa) [[ILLA Cloud](https://www.illacloud.com/)]  — 用Rust编写的低代码内部工具生成器 
* [LLDAP](https://github.com/lldap/lldap)  — 用于身份验证的简化LDAP接口。 
* [pier-cli/pier](https://github.com/pier-cli/pier)  — 用于管理 (添加，搜索元数据等) 所有单线，脚本，工具和cl的中央存储库 
### Routing protocols

* [Holo](https://github.com/rwestphal/holo)  — Holo是一套路由协议，旨在支持大规模和自动化驱动的网络 
* [RustyBGP](https://github.com/osrg/rustybgp)  — 用Rust编程语言实现的BGP 
### Security tools

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL)  — 高级模糊库-将你的模糊器放在铁锈中!跨核心和机器扩展。适用于Windows、Android、MacOS、Linux、no_std等。 [![build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [cargo-audit](https://crates.io/crates/cargo-audit)  — 审计货物。锁定有安全漏洞的板条箱 
* [cargo-auditable](https://crates.io/crates/cargo-auditable)  — 使生产锈二进制文件可审计 
* [cargo-crev](https://crates.io/crates/cargo-crev)  — 货物 (Rust) 包裹管理器的密码可验证代码审查系统 
* [cargo-deny](https://crates.io/crates/cargo-deny)  — 帮助您管理大型依赖关系图的货物插件 
* [Cherrybomb](https://github.com/blst-security/cherrybomb)  — 使用CLI工具停止半途而废的API规范，该工具可通过验证API规范来帮助您避免未定义的用户行为。 
* [cotp](https://github.com/replydev/cotp)  — 具有导入功能的可信、加密、命令行TOTP/HOTP身份验证器应用程序。 
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster)  — 用Rust编写的一种简单、快速、递归的内容发现工具 ( 
* [Inspektor](https://github.com/inspektor-dev/inspektor)  — 用于实施访问策略的数据库协议感知代理 
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope)  — 一种脚本网络认证破解器 
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack)  — 一个TCP连接劫机者，shijack的rust rewrite 
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int)  — 一个半自动OSINT框架和包管理器 
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue)  — 一种安全的多线程数据包嗅探器 
* [ObserverWard](https://github.com/0x727/ObserverWard)  — 基于社区的网络技术分析工具。 
* [ripasso](https://github.com/cortex/ripasso/)  — 一个密码管理器，与pass兼容的文件系统 
* [rustscan/rustscan](https://github.com/RustScan/RustScan)  — 使用此端口扫描工具使Nmap更快 [![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)

### Simulation

* [hEngine](https://github.com/hashintel/hash/tree/main/apps/engine)  — Rust实现的计算仿真引擎，支持基于大规模代理的建模，仿真逻辑用JavaScript和Python编写。 
### Social networks

* Mastodon
  * [Rustodon](https://github.com/rustodon/rustodon)  — Rust中与乳齿象兼容的ActivityPub-讲服务器 
### System tools

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/)  — 学习您的习惯的 “cd” 的快速替代品 [![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [Alonely0/Voila](https://github.com/Alonely0/Voila)  — Voila是一种通过CLI工具启动的特定于域的语言，用于以快速可靠的方式大量操作文件和目录。 [![Linux build](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml) [![Windows build](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
* [atuin](https://github.com/atuinsh/atuin) [[atuin](https://crates.io/crates/atuin)]  — Atuin用SQLite数据库替换您现有的shell历史记录，并为您的命令记录其他上下文。此外，它还通过Atuin服务器提供了计算机之间历史记录的可选和完全加密的同步。 
* [bandwhich](https://github.com/imsnif/bandwhich)  — 终端带宽利用工具 
* [bottom](https://github.com/ClementTsang/bottom)  — 另一个跨平台的图形过程/系统监视器。 [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* [brocode/fblog](https://github.com/brocode/fblog)  — 小型命令行JSON日志查看器 
* [bustd](https://github.com/vrmiguel/bustd)  — 轻量级进程杀手守护程序，用于处理Linux上的内存不足场景。 [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* [buster/rrun](https://github.com/buster/rrun)  — Linux的命令启动器，类似于gmrun 
* [cantino/mcfly](https://github.com/cantino/mcfly)  — 翻阅你的贝壳历史。伟大的斯科特! 
* [crabz](https://github.com/sstadick/crabz)  — 多线程压缩和解压CLI工具 [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy)  — 受以下启发的可配置文件系统观察者 [entr](http://eradman.com/entrproject/)
* [dalance/procs](https://github.com/dalance/procs)  — Rust撰写的 “p” 的现代替代品 [![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* [ddh](https://github.com/darakian/ddh)  — 快速重复文件查找器 
* [diskonaut](https://github.com/imsnif/diskonaut)  — 终端可视磁盘空间导航器 
* [dust](https://github.com/bootandy/dust)  — 更直观的du版本 
* [eza-community/eza](https://github.com/eza-community/eza)  — “Ls” 的替代品 
* [fselect](https://crates.io/crates/fselect)  — 使用类似SQL的查询查找文件 
* [gitui](https://github.com/extrawurst/gitui)  — 用铁锈写的git的快速终端客户端。 [![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
* [GQL](https://github.com/amrdeveloper/gql)  — 要运行的类似SQL的查询语言。git文件。 
* [j0ru/kickoff](https://github.com/j0ru/kickoff)  — 快速活泼的wayland程序启动器 [![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
* [Kondo](https://github.com/tbillington/kondo)  — 用于删除软件项目工件和回收磁盘空间的CLI & GUI工具 
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)]  — 支持模式匹配的xargs awk 
* [lotabout/skim](https://github.com/lotabout/skim)  — 纯锈中的模糊查找器 
* [lsd](https://github.com/lsd-rs/lsd)  — 一个有很多漂亮颜色和令人敬畏的图标的ls [![build](https://github.com/lsd-rs/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/lsd-rs/lsd/actions)
* [Luminarys/synapse](https://github.com/Luminarys/synapse)  — 灵活快速的BitTorrent守护程序。 
* [m4b/bingrep](https://github.com/m4b/bingrep)  — Greps通过来自各种OSs和体系结构的二进制文件，并为它们着色。 
* [mitnk/cicada](https://github.com/mitnk/cicada)  — 类似bash的Unix外壳 
* [mmstick/concurr](https://github.com/mmstick/concurr)  — 替代GNU并行w/ a客户端-服务器体系结构 
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder)  — GTK3预览和安装谷歌字体的应用程序 
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer)  — 带有可选GTK3前端的电视系列重命名应用程序。 
* [mxseev/logram](https://github.com/mxseev/logram)  — 将日志文件的更新推送到Telegram 
* [nickgerace/gfold](https://github.com/nickgerace/gfold) [[gfold](https://crates.io/crates/gfold)]  — 帮助跟踪多个Git存储库的CLI工具 [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
* [nivekuil/rip](https://github.com/nivekuil/rip)  — 安全且符合人体工程学的 “rm” 替代品 
* [nushell/nushell](https://github.com/nushell/nushell)  — 一种新型外壳 
* [orhun/kmon](https://github.com/orhun/kmon)  — Linux内核管理器和活动监视器! [https://github.com/orhun/kmon/actions](https://img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml?branch=master&label=build)
* [orhun/systeroid](https://github.com/orhun/systeroid)  — 具有终端用户界面的更强大的sysctl(8) 替代品! [https://github.com/orhun/systeroid/actions](https://img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml?branch=main&label=build)
* [ouch](https://github.com/ouch-org/ouch)  — 命令行无痛压缩和减压 [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* [pop-os/popsicle](https://github.com/pop-os/popsicle)  — GTK3和CLI实用程序，用于并行闪烁多个USB设备 
* [pop-os/system76-power](https://github.com/pop-os/system76-power/)  — 使用CLI工具的Linux电源管理守护程序 (DBus接口)。 
* [pueue](https://github.com/nukesor/pueue)  — 管理您长时间运行的shell命令。 [![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
* [qarmin/cakawka](https://github.com/qarmin/czkawka)  — 多功能应用程序，查找重复，空文件夹，类似的图像等。 [![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
* [redox-os/ion](https://github.com/redox-os/ion)  — 下一代系统外壳 
* [sharkdp/bat](https://github.com/sharkdp/bat)  — 有翅膀的猫 (1) 克隆。 [![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd)  — 一个简单、快速和用户友好的替代方法。 [![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex)  — 彩色hexdump终端实用程序。 
* [supercilex/fuc](https://github.com/supercilex/fuc)  — 快速的 'cp' 和 'rm' 命令 
* [trippy](https://github.com/fujiapple852/trippy)  — 一种网络诊断工具 [![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* [uutils/coreutils](https://github.com/uutils/coreutils)  — GNU coreutils的跨平台Rust重写 [[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [watchexec](https://github.com/watchexec/watchexec)  — 响应文件修改执行命令 
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei)  — 计算代码行 
### Task scheduling

* [delicate](https://github.com/BinChengZhao/delicate)  — 用rust编写的轻量级分布式任务调度平台 [![Build Status](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### Text editors

* [amp](https://amp.rs)  — 灵感来自Vi/Vim。 
* [emacs-ng](https://github.com/emacs-ng/emacs-ng)  — 用rust代码补充C代码库，引入新功能。 
* [gchp/iota](https://github.com/gchp/iota)  — 一个简单的文本编辑器 
* [helix](https://github.com/helix-editor/helix)  — 受Neovim/Kakoune启发的后现代模态文本编辑器。 [![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi)  — 一个很小的 (≤ 1024 LOC) 文本编辑器，具有语法高亮显示、增量搜索等功能。 [![build badge](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* [Lapce](https://github.com/lapce/lapce)  — 用铁锈写的后端的现代编辑器。从已停产的 [xi-editor](https://github.com/xi-editor) 中汲取灵感。 
* [mathall/rim](https://github.com/mathall/rim)  — 用Rust编写的类似Vim的文本编辑器 
* [ox](https://github.com/curlpipe/ox)  — 在您的终端中运行的独立的Rust文本编辑器! 
* [vamolessa/pepper](https://github.com/vamolessa/pepper) [[pepper](https://crates.io/crates/pepper)]  — 自以为是的模态编辑器，可简化终端的代码编辑 [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)

### Text processing

* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) [[cfonts](https://crates.io/crates/cfonts)]  — 控制台的性感ANSI字体! [build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [grex](https://github.com/pemistahl/grex)  — 用于从用户提供的测试用例生成正则表达式的命令行工具和库 
* [jqnatividad/qsv](https://github.com/jqnatividad/qsv) [[qsv](https://crates.io/crates/qsv)]  — 高性能CSV数据-争吵工具包从xsv分叉，有34个附加命令 & 更多。 [![Linux build status](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml) [![Windows build status](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml) [![macOS build status](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search)  — 一种简单快速的人类字符串搜索工具 
* [Melody](https://github.com/yoav-lavi/melody)  — 一种编译为正则表达式的语言，旨在更容易阅读和维护 [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all)  — ripgrep，但也可以搜索pdf，电子书，办公文档，zip，tar.gz等。 
* [replicadse/complate](https://github.com/replicadse/complate)  — 一种用于标准化消息 (如GIT提交) 的终端文本模板工具。 [![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* [ripgrep](https://crates.io/crates/ripgrep)  — 将银搜索器的可用性与grep的原始速度相结合 
* [ruplacer](https://github.com/your-tools/ruplacer)  — 查找并替换源文件中的文本 [![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [sd](https://crates.io/crates/sd)  — 直观的查找和替换CLI 
* [sstadick/hck](https://github.com/sstadick/hck)  — 替换 “切割” 的速度更快，功能更丰富 [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff)  — 按名称查找文件 (ff)! 
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[bytelines](https://crates.io/crates/bytelines)]  — 将输入线读取为字节切片，以提高效率。 
* [whitfin/runiq](https://github.com/whitfin/runiq)  — 一种从未排序的输入中过滤重复行的有效方法。 
* [xsv](https://crates.io/crates/xsv)  — 一个快速的CSV命令行工具 (切片、索引、选择、搜索、采样等) 
### Utilities

* [1History](https://github.com/1History/1History)  — 将Firefox/Chrome/Safari历史备份到一个SQLite文件的命令行界面 [![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* [brycx/checkpwn](https://github.com/brycx/checkpwn)  — 我已经被修改了 (HIBP) 命令行实用工具，可让您轻松检查受损的帐户和密码。 
* [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager)  — 一个非官方客户端，用于安装虚幻引擎，从Epic games Store下载和管理购买的资产，项目，插件和游戏。 
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak)  — 命令行OTP (一次性密码) 身份验证器应用程序。 
![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs)  — 闪电般的快速版本的tmux-用铁锈书写的手指，像vimum/vimperator一样复制/粘贴tmux。 
* [guoxbin/dtool](https://github.com/guoxbin/dtool)  — 一个有用的命令行工具集合，可帮助开发，包括转换，编解码器，哈希，加密等。 
* [mprocs](https://github.com/pvolok/mprocs)  — 用于运行多个进程的TUI 
* [mrjackwills/oxker](https://github.com/mrjackwills/oxker) [[oxker](https://crates.io/crates/oxker)]  — 一个简单的tui来查看和控制docker容器。 
* [nix-community/nix-init](https://github.com/nix-community/nix-init)  — 从具有哈希预取、依赖推断、许可证检测等功能的url生成Nix包 [![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
* [nix-community/nix-melt](https://github.com/nix-community/nix-melt)  — 像护林员一样的薄片。锁定查看器 [![build-badge](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)
* [nix-community/nurl](https://github.com/nix-community/nurl) [[nurl](https://crates.io/crates/nurl)]  — 从存储库url生成Nix fetcher调用 [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
* [nomino](https://github.com/yaa110/nomino)  — 面向开发人员的批量重命名实用程序 
* [raftario/licensor](https://github.com/raftario/licensor)  — 向stdoout写入许可证 [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [rust-parallel](https://github.com/aaronriekenberg/rust-parallel)  — 使用Tokio并行执行命令的快速命令行应用程序。与GNU Parallel或xargs类似的接口。 [![Crate](https://img.shields.io/crates/v/rust-parallel.svg?logo=rust)](https://crates.io/crates/rust-parallel) [![Build Status](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml/badge.svg)](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk)  — 远程桌面软件，是TeamViewer和AnyDesk的绝佳替代品。 
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) [[rustic-rs](https://crates.io/crates/rustic-rs)]  — 由Rust提供支持的快速、加密、重复数据删除备份。 [![Version](https://img.shields.io/crates/v/rustic-rs.svg)](https://crates.io/crates/rustic-rs)
* [suckit](https://github.com/Skallwar/suckit)  — 递归访问并将网站的内容下载到您的磁盘上。 [![Crate](https://img.shields.io/crates/v/suckit.svg?logo=rust)](https://crates.io/crates/suckit) [![Build Status](https://github.com/Skallwar/suckit/workflows/Build%20and%20test/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)
* [tversteeg/emplace](https://github.com/tversteeg/emplace)  — 同步多台机器上已安装的软件包 
* [vamolessa/verco](https://github.com/vamolessa/verco) [[verco](https://crates.io/crates/verco)]  — 专注于键盘快捷键的简单Git/Hg tui客户端 
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme)  — [![构建](https://github.com/dani-garcia/vaultwarden/操作/工作流/构建.yml/徽章.svg)](https://github.com/dani-garcia/vaultwarden/操作/工作流/构建.yml) -用Rust编写的Bitwarden服务器API的替代实现 
* [warpdotdev/Warp](https://github.com/warpdotdev/Warp)  — : heavy_dollar_sign:-Warp是一种基于Rust的快速现代GPU加速终端，旨在使您和您的团队提高工作效率。 
* [yaa110/cb](https://github.com/yaa110/cb)  — 用于管理剪贴板的命令行界面 
### Video

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[yaydl](https://crates.io/crates/yaydl)]  — 一个简单的视频下载器 
* [harlanc/xiu](https://github.com/harlanc/xiu)  — 由纯rust (rtmp/httpflv/hls/relay) 提供的功能强大且安全的实时服务器。 [![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* [vidmerger](https://github.com/TGotwig/vidmerger)  — 通过CLI合并视频和音频文件 
* [xiph/rav1e](https://github.com/xiph/rav1e)  — 最快和最安全的AV1编码器。 
### Virtualization

* [containers/youki](https://github.com/containers/youki)  — Rust中的容器运行时间 [![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker)  — 用于容器工作负载的轻量级虚拟机 [Firecracker Microvm](https://firecracker-microvm.github.io/)
* [tailhook/vagga](https://github.com/tailhook/vagga)  — 没有守护程序的容器化工具 
### Web

* [cfal/tobaru](https://github.com/cfal/tobaru)  — 具有allowlists、IP和TLS SNI/ALPN基于规则的路由、iptables支持、循环转发 (负载平衡) 和热重载的端口转发器。 
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy)  — fediverse的链接聚合器/reddit克隆 [![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* [libreddit](https://github.com/libreddit/libreddit)  — Reddit的替代私有前端 
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node)  — MASQ节点软件为全球用户提供了一个分散的网状节点网络，以访问正常的internet内容-技术的下一个发展超越Tor和VPN [![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume)  — ActivityPub联合博客应用程序 
* [Revolt/backend](https://github.com/revoltchat/backend)  — 用现代网络技术构建的用户优先聊天平台。 
### Web Servers

* [emanuele-em/man-in-the-middle-proxy](https://github.com/emanuele-em/man-in-the-middle-proxy)  — MITM代理!具有SSL/TLS功能的HTTP/1、HTTP/2和WebSockets工具包 [![Rust](https://github.com/emanuele-em/man-in-the-middle-proxy/actions/workflows/rust.yml/badge.svg)](https://github.com/emanuele-em/man-in-the-middle-proxy/actions/workflows/rust.yml)
* [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder)  — 漂亮的HTTP/Bittorrent服务器没有麻烦。安全图形用户界面非常快 
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve)  — 具有路由，模板化和安全性的出色快速静态web服务器，您可以使用零代码进行设置 [![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste)  — 最小文件上传/粘贴服务! [https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml?branch=master&label=build)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura)  — 演示如何将Rust GraphQL服务器用作远程架构 [Hasura](https://hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* [static-web-server](https://github.com/static-web-server/static-web-server)  — 用于静态文件服务的快速异步web服务器。⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve)  — 一个小型的，独立的跨平台CLI工具，可让您仅获取二进制文件并通过HTTP提供一些文件 [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http)  — 请托管这些东西-一个基本的http服务器，用于快速简单地托管文件夹 
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server)  — 简单静态http服务器 
* [wyhaya/see](https://github.com/wyhaya/see)  — 静态HTTP文件服务器 
## Development tools

* [bacon](https://github.com/Canop/bacon)  — 背景铁锈代码检查器，类似于货物手表 
* [clippy](https://crates.io/crates/clippy)  — 锈色棉绒 
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli)  — 从git元数据生成变更日志 ( [conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))
* [comtrya](https://github.com/comtrya/comtrya)  — 用于本地主机/dotfiles的配置管理工具 [![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* [create-rust-app](https://github.com/Wulf/create-rust-app)  — 通过运行一个命令设置一个现代rust react web应用程序。 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags)  — 为货运项目及其所有依赖项创建ctags/etags 
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer)  — 具有灵活规则的强大数据库匿名器 [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* [delta](https://crates.io/crates/git-delta)  — git和diff输出的语法荧光笔 [![build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter)  — '.Env' 文件的棉绒 [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* [frolic](https://github.com/FrolicOrg/Frolic)  — -一个API层，以10倍的速度构建面向客户的仪表板 
* [fw](https://github.com/brocode/fw)  — 工作空间生产力提升 [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [geiger](https://github.com/rust-secure-code/cargo-geiger)  — 列出与防锈箱中不安全的Rust代码的使用及其所有依赖项相关的统计信息的程序 [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-cliff](https://github.com/orhun/git-cliff)  — 遵循常规提交规范的高度可定制的变更日志生成器! [https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml?branch=main&label=build)
* [git-journal](https://github.com/saschagrunert/git-journal/)  — Git Commit消息和Changelog生成框架 
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs)  — 热重装锈代码 [![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [intelli-shell](https://github.com/lasantosr/intelli-shell)  — 随时使用占位符和搜索或自动完成的书签命令 [![crate](https://img.shields.io/crates/v/intelli-shell.svg)](https://crates.io/crates/intelli-shell) [![build badge](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml)
* [just](https://github.com/casey/just)  — 用于特定项目任务的便捷命令运行器 
* [mask](https://github.com/jacobdeichert/mask)  — 由简单markdown文件定义的CLI任务运行器 [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* [Module Linker](https://github.com/fiatjaf/module-linker)  — 扩展名为GitHub上的 “模式” 、 “使用” 和 “外部crate” 语句中的引用添加了 “<a>” 链接。 
* [ptags](https://github.com/dalance/ptags)  — git存储库的并行通用ctags包装器 
* [Racer](https://github.com/racer-rust/racer)  — 生锈的代码完成 
* [Rust Search Extension](https://github.com/huhu/rust-search-extension)  — 一个方便的浏览器扩展，用于在地址栏 (omnibox) 中搜索板条箱和文档。 [![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  — -自动应用rustc提出的建议 
* [Rustup](https://github.com/rust-lang/rustup)  — 铁锈工具链安装程序 [![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto)  — 一种与语言无关的 “shebang解释器”，使您可以用编译语言编写一个文件脚本。 [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### Build system

* [Cargo](https://crates.io/)  — 防锈包装管理器 
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features)  — 可配置的子命令，可简化测试，构建以及所有功能组合的更多内容 [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp)  — 比较Rust微基准的实用程序 
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake)  — 可以使用meta-rust的类生成BitBake食谱的货物扩展 
  * [cargo-cache](https://crates.io/crates/cargo-cache)  — 检查/管理/清理您的货物缓存 ('~/.cargo/' ${CARGO_HOME}')，打印尺寸等 [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check)  — 围绕 “cargo rustc -- -Zno-trans' 的包装器，如果您只需要正确性检查，它可以帮助运行更快的编译 
  * [cargo-commander](https://crates.io/crates/cargo-commander)  — 用于 “cargo” 运行CLI命令的子命令，类似于 “package.Json” 中的脚本部分的工作方式 [![Build and test](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml)
  * [cargo-count](https://crates.io/crates/cargo-count)  — 列出了有关货运项目的源代码计数和详细信息，包括不安全的统计数据 
  * [cargo-deb](https://crates.io/crates/cargo-deb)  — 生成二进制Debian包 
  * [cargo-deps](https://crates.io/crates/cargo-deps)  — 构建Rust项目的依赖关系图 
  * [cargo-do](https://crates.io/crates/cargo-do)  — 连续运行多个货物命令 
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild)  — 可以使用树内eclasses生成ebuild的货物扩展 
  * [cargo-edit](https://crates.io/crates/cargo-edit)  — 允许您通过从命令行读取/写入Cargo.toml文件来添加和列出依赖项 
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate)  — 利用预先存在的git存储库作为模板的rust项目的生成器。 
  * [cargo-graph](https://crates.io/crates/cargo-graph)  — 更新了带有附加功能的 “货物点” 叉。未维护，请参阅 “货物-设备” 
  * [cargo-info](https://crates.io/crates/cargo-info)  — 从命令行查询板条箱的详细信息 
  * [cargo-license](https://crates.io/crates/cargo-license)  — 一个货运子命令，用于快速查看所有依赖项的许可证。 
  * [cargo-limit](https://crates.io/crates/cargo-limit)  — 噪音较小的货物: 警告被跳过，直到错误被修复，Neovim集成等。 [![build badge](https://github.com/alopatindev/cargo-limit/actions/workflows/rust.yml/badge.svg)](https://github.com/alopatindev/cargo-limit/actions)
  * [cargo-make](https://crates.io/crates/cargo-make)  — 生锈任务运行器和构建工具。 [![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules)  — 一个货物插件，用于显示板条箱模块的树状概述。 
  * [cargo-multi](https://crates.io/crates/cargo-multi)  — 在多个板条箱上运行指定的货物命令 
  * [cargo-outdated](https://crates.io/crates/cargo-outdated)  — 显示较新版本的Rust依赖项何时可用或过期 
  * [cargo-rdme](https://github.com/orium/cargo-rdme) [[cargo-rdme](https://crates.io/crates/cargo-rdme)]  — 货运子命令从板条箱的文档中创建自述文件。 [![build badge](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)
  * [cargo-release](https://crates.io/crates/cargo-release)  — 用于发布git管理的货物项目、构建、标记、发布、文档和推送的工具 [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script)  — 让人们快速轻松地运行Rust “脚本”，该脚本可以利用货物的包裹生态系统 
  * [cargo-udeps](https://github.com/est31/cargo-udeps) [[cargo-udeps](https://crates.io/crates/cargo-udeps)]  — 查找未使用的依赖项 
  * [cargo-update](https://crates.io/crates/cargo-update)  — 用于检查并将更新应用于已安装的可执行文件的cargo子命令 
  * [cargo-watch](https://crates.io/crates/cargo-watch)  — 货源更改时，货物用于编译项目的实用程序 
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand)  — 在源代码中扩展宏 
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust)  — 对于将Rust库集成到c制造项目中很有用 
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake)  — 一个示例项目，显示了带有Rust的c制造的使用情况 
* [Fleet](https://github.com/dimensionhq/fleet) [[fleet-rs](https://crates.io/crates/fleet-rs)]  — 炽热的快速生锈工具。 
* Github actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action)  — 生锈github操作 
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook)  — 适用于mdBook的GitHub操作 
* [Nix](https://nixos.org/)
  * [nix-community/fenix](https://github.com/nix-community/fenix)  — nix每晚防锈工具链和防锈分析仪 [![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)

### Debugging

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui)  — 基于浏览器的前端，用于gdb调试C、Rust和go。 
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)  — [Visual Studio代码](https://code.visualstudio.com/) 的LLDB扩展。 
### Deployment

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder)  — 使用musl-libc和musl-gcc编译静态Rust二进制文件的Docker图像，具有有用的C库的静态版本 
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust)  — 非常小的rust docker图像的示例项目 
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup)  — 多版本 (带有musl工具) Rust Docker图像 
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef)  — 用于缓存编译Docker构建之间的远程依赖关系的工具和预构建的映像。 
  * [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross)  — 使用musl-cross编译静态锈二进制文件的Docker图像 [![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust)  — 官方Rust Docker图像 
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust)  — Heroku上防锈应用的构建包 
* [MarcoIeni/release-plz](https://github.com/MarcoIeni/release-plz) [[release-plz](https://crates.io/crates/release-plz)]  — 从CI释放防锈板条箱，使用变更日志生成和semver检查。 [![build badge](https://github.com/MarcoIeni/release-plz/workflows/CI/badge.svg)](https://github.com/MarcoIeni/release-plz/actions)

### Embedded

[Rust Embedded](https://rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino)  — Arduino Uno的可重用组件。 
* Cross compiling
  * [japaric/rust-cross](https://github.com/japaric/rust-cross)  — 关于交叉编译Rust程序，你需要知道的一切 
  * [japaric/xargo](https://github.com/japaric/xargo)  — 毫不费力地交叉编译Rust程序，以自定义裸金属目标，如ARM Cortex-M 
* Espressif
  * [esp-rs](https://github.com/esp-rs)  — 许多社区项目的所在地，可以在Espressif Systems生产的各种soc和模块上使用Rust编程语言。 
* Firmware
  * [oreboot/oreboot](https://github.com/oreboot/oreboot)  — oreboot是coreboot的一个叉，去掉了C，用铁锈写 
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal)  — nRF设备系列的Rust HAL 
### FFI

See also [Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html), [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples).

* C
  * [mozilla/cbindgen](https://github.com/mozilla/cbindgen)  — 从Rust源文件生成C头文件。用于WebRender的壁虎 
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar)  — 从Rust源文件生成C头文件 
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx)  — 铁锈和C之间的安全交互 [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp)  — 直接在Rust中嵌入C代码。 [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen)  — 铁锈绑定发生器 
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler)  — 用于创建Erlang NIF功能的安全锈桥 
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni)  — 使用Rust中的Java 
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example)  — 使用Java中的Rust 
  * [j4rs](https://crates.io/crates/j4rs)  — 使用Rust中的Java 
  * [jni](https://crates.io/crates/jni)  — 使用Java中的Rust 
  * [jni-sys](https://crates.io/crates/jni-sys)  — 对应于jni.h的Rust定义 
  * [rucaja](https://crates.io/crates/rucaja)  — 使用Rust中的Java 
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53)  — Lua 5.3绑定防锈 
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua)  — Lua 5.1的安全锈绑定 
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rlua](https://crates.io/crates/td_rlua)]  — 零成本高级lua铁锈5.3包装 
  * [tomaka/hlua](https://github.com/tomaka/hlua)  — Rust库与Lua接口 
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty)  — mruby防锈安全绑定 
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen)  — 使用Rust生成nodejs模块的简单方法 
  * [neon-bindings/neon](https://github.com/neon-bindings/neon)  — 用于编写安全快速的本机Node.js模块的Rust绑定 
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc)  — Objective-C运行时绑定和Rust包装 
* PHP
  * [phper-framework/phper](https://github.com/phper-framework/phper)  — 允许我们尽可能使用纯净和安全的Rust编写PHP扩展的框架 
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython)  — Python绑定 
  * [getsentry/milksnake](https://github.com/getsentry/milksnake)  — python setuptools的扩展，允许您以可想象的最可移植的方式在Python wheels中分发动态链接库。 
  * [PyO3/PyO3](https://github.com/PyO3/PyO3)  — Python解释器的Rust绑定 
  * [RustPython](https://github.com/RustPython/RustPython)  — 用Rust编写的Python解释器 [![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
* Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru)  — 用Rust编写的本地Ruby扩展 
  * [danielpclark/rutie](https://github.com/danielpclark/rutie)  — 用Rust编写的本地Ruby扩展，反之亦然 
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain)  — wain: wbassembly解释器在零依赖的安全锈中从头开始 [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen)  — 一个促进wasm模块和JS之间高层交互的项目。 
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack)  — : package: :sparkles: 打包wasm并将其发布到npm! 
### Formatters

* [dprint](https://github.com/dprint/dprint)  — 可插拔和可配置的代码格式化平台 [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust)  — 自以为是的Rust代码格式化程序，可自动修复不良语法 ( [Prettier](https://prettier.io/) community plugin)
* [rustfmt](https://github.com/rust-lang/rustfmt)  — 由Rust团队维护并包含在货物中的Rust代码格式化程序 
### IDEs

See also [Are we (I)DE yet?](https://areweideyet.com/) and [Rust Tools](https://www.rust-lang.org/tools).

  * [Atom](https://github.blog/2022-06-08-sunsetting-atom/)
    * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust)  — Rust IDE支持Atom，由Rust语言服务器 (RLS) 提供支持 
  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer)  — 自动完成 (另见 [company](https://company-mode.github.io) and [auto-complete](https://github.com/auto-complete/auto-complete))
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust)  — 防锈支架 [Flycheck](https://github.com/flycheck/flycheck)
    * [rust-mode](https://github.com/rust-lang/rust-mode)  — 生锈主要模式 
    * [rustic](https://github.com/brotzeit/rustic)  — Emacs的Rust开发环境 [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * [gitpod.io](https://gitpod.io)  — 基于Rust语言服务器的具有完全Rust支持的在线IDE 
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder)  — 自3.22.2版以来对铁锈和货物的本机支持 
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust)  — * [Kakoune](http://kakoune.org/)
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/)  — [LSP](https:// microsoft.github.io/language-server-protocol/) 客户端。在Rust中实现，并支持开箱即用的rls。 
  * [lapce](https://github.com/lapce/lapce)  — 闪电-用Rust编写的快速和强大的代码编辑器。 [![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
  * [Ride](https://github.com/madeso/ride)  — * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced)  — 官方防锈包装 
  * [Vim](https://vim.sourceforge.io/)  — 无处不在的文本编辑器 
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim)  — [LSP](https:// microsoft.github.io/language-server-protocol/) 客户端。在Rust中实现，并支持开箱即用的rls。 
    * [crates.nvim](https://github.com/Saecki/crates.nvim)  — 有助于管理板条箱的插件。io依赖关系。 
    * [rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim)  — 使用neovim内置lsp更好地开发铁锈的工具 
    * [rust.vim](https://github.com/rust-lang/rust.vim)  — 提供文件检测、语法突出显示、格式化、语法集成等。 
    * [vim-racer](https://github.com/racer-rust/vim-racer)  — 允许vim使用 [Racer](https://github.com/racer-rust/racer) 进行Rust代码完成和导航。 
  * Visual Studio
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017)  — Rust支持Visual Studio 2017预览 [![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust)  — Rust的Visual Studio扩展 [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)  — vscode中的TOML支持 
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)  — 一个LLDB扩展 
    * [crates](https://github.com/serayuzgur/crates)  — 板条箱是板条箱的扩展。io依赖关系。 [![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates)
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust)  — 自以为是的Rust代码格式化程序，自动修复不良语法 ( [Prettier](https://prettier.io/) community plugin)
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)  — RLS的替代rust语言服务器 
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust)  — Rust支持Visual Studio代码 (同时支持RLS和rust-analyzer) 
### Profiling

* [Bencher](https://github.com/bencherdev/bencher)  — 一套连续的基准测试工具，旨在捕捉CI中的性能回归 
* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs)  — 统计驱动的Rust基准库 
* [Bytehound](https://github.com/koute/bytehound)  — 一种适用于Linux的内存分析器 
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch)  — 秒表库 
* FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame)  — * [mrhooray/torch](https://github.com/mrhooray/torch) -基于矮人调试信息生成火焰图 
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine)  — 命令行基准测试工具 
### Services

* [deps.rs](https://github.com/deps-rs/deps.rs)  — 检测过时或不安全的依赖关系 
* [docs.rs](https://docs.rs)  — 板条箱的自动文档生成 
### Static analysis

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai)  — 在Rust的中级表示 (MIR) 上运行的抽象解释器 [![Continuous Integration](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml)
* [static_assertions](https://crates.io/crates/static_assertions)  — 编译时断言，以确保满足不变量 
### Testing

[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]

* Code Coverage
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin)  — 为Rust设计的代码覆盖工具 
* Continuous Integration
  * [trust](https://github.com/japaric/trust)  — Travis CI和AppVeyor模板，用于在5种体系结构上测试您的Rust板条箱，并为Linux，macOS和Windows发布其二进制版本 
* Frameworks and Runners
  * [AlKass/polish](https://github.com/AlKass/polish)  — 迷你测试/测试驱动框架 [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/)  — 一种货物扩展，可简化智能手机和其他小型处理器设备上的程序库测试和工作台。 
  * [cucumber](https://crates.io/crates/cucumber)  — [! [Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — An implementation of the Cucumber testing framework for Rust. Fully native, no external test runners or dependencies. [![Build Status](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
  * [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log) [[test-log](https://crates.io/crates/test-log)]  — 替换 '# [test]` attribute that initializes logging and/or tracing infrastructure before running tests. [![GitHub Workflow Status](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml)
  * [demonstrate](https://crates.io/crates/demonstrate)  — 声明性测试框架 [![Build Status](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
  * [rstest](https://crates.io/crates/rstest)  — 基于夹具的铁锈测试框架 [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate)  — RSpec启发的生锈最小测试框架 
* Mocking and Test Data
  * [asomers/mockall](https://github.com/asomers/mockall) [[mockall](https://crates.io/crates/mockall)]  — 用于Rust的强大的模拟对象库。 [![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  * [fake-rs](https://github.com/cksac/fake-rs)  — 生成假数据的库 
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[goldenfile](https://crates.io/crates/goldenfile)]  — 为goldenfile测试提供简单API的库。 
  * [httpmock](https://github.com/alexliesenfeld/httpmock)  — HTTP嘲笑 [![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
  * [mockiato](https://crates.io/crates/mockiato)  — 一个严格但友好的鲁斯特2018嘲笑库 
  * [mockito](https://crates.io/crates/mockito)  — HTTP嘲笑 
  * [nrxus/faux](https://github.com/nrxus/faux/)  — [! [Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — A library to create mocks out of structs. ![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
  * [synth](https://github.com/shuttle-hq/synth/)  — 以声明方式生成数据库数据。 [![build](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)
* Mutation Testing
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) [[cargo-mutants](https://crates.io/crates/cargo-mutants)]  — 通过注入突变找到测试不充分的代码，不需要源更改。 [![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * [mutagen](https://github.com/llogiq/mutagen) [[mutagen](https://crates.io/crates/mutagen)]  — 源级突变测试框架 (仅限每晚) 
* Property Testing and Fuzzing
  * [proptest](https://crates.io/crates/proptest)  — 受 [假设](https://hypothesis.works/) Python框架启发的属性测试框架 
  * [quickcheck](https://crates.io/crates/quickcheck)  — 生锈的实现 [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1)
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs)  — 锈模糊器，使用 [AFL](https://lcamtuf.coredump.cx/afl/)

### Transpiling

* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen)  — 一个CLI工具，用于将经过训练的经典机器学习模型转换为具有零依赖关系的本机Rust代码。 [![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
* [immunant/c2rust](https://github.com/immunant/c2rust)  — C到锈转换器和交叉检查器建立在Clang/LLVM之上。 
* [jameysharp/corrode](https://github.com/jameysharp/corrode)  — 用Haskell编写的C到Rust翻译器。 
## Libraries

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs)  — 一个工具包，旨在成为应用程序监视其性能的基础。 [![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)

### Artificial Intelligence

#### Genetic algorithms

* [innoave/genevo](https://github.com/innoave/genevo)  — 以可定制和可扩展的方式执行遗传算法 (GA) 仿真。 
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic)  — Rust中的遗传算法库处于维护模式。 
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen)  — 快速、并行、可扩展和适应性强的遗传算法库使用此库的示例仅在几秒钟内解决了N = 255的N Queens问题，并且使用的RAM少于1 MB。 
* [pkalivas/radiate](https://github.com/pkalivas/radiate)  — 可定制的并行遗传编程引擎，能够针对有监督，无监督和强化学习问题不断发展解决方案。附带整洁和Evtree的完整和可定制的实现。! [Crates.io](https://img.shields.io/crates/v/radiate)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs)  — 带有锈蚀的进化算法 
#### Machine learning

See [[Machine learning](https://crates.io/keywords/machine-learning)]

See also [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and [Are we learning yet?](https://www.arewelearningyet.com).

* [autumnai/leaf](https://github.com/autumnai/leaf)  — 开放机器智能框架 ..放弃的项目。最新的叉子是 [spearow/juice]( https://github.com/spearow/juice)。 
* [coreylowman/dfdx](https://github.com/coreylowman/dfdx)  — CUDA加速了机器学习框架，它利用了Rust的许多独特功能。! [Crates.io](https://img.shields.io/crates/v/dfdx)
* [huggingface/candle](https://github.com/huggingface/candle)  — [ [candle-core](https://crates.io/crates/candle-core)]- a minimalist ML framework with a focus on easiness of use and on performance (including GPU support)
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers)  — 用Rust (原始实现) 编写的带有Python绑定的现代NLP管道的拥抱Face的标记器。 [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs)  — PyTorch的Rust语言绑定。 
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn)  — 机器学习铁锈板条箱。 [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [rust-ml/linfa](https://github.com/rust-ml/linfa)  — 机器学习框架。 
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore)  — Rust中的机器学习库 [![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
* [tensorflow/rust](https://github.com/tensorflow/rust)  — TensorFlow的Rust语言绑定 
#### OpenAI

* [64bit/async-openai](https://github.com/64bit/async-openai) [[async-openai](https://crates.io/crates/async-openai)]  — 基于OpenAPI规范的OpenAI API的人体工程学防锈绑定。 
* [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) [[tiktoken-rs](https://crates.io/crates/tiktoken-rs)]  — 使用tiktoken将文本与OpenAI模型进行标记的Rust库。 [![CI](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml)

### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite)  — 用于可视化不同投影中的空间和行星图像调查的Web应用程序 
* [fitsio](https://crates.io/crates/fitsio)  — 适合接口库包装cfitsio 
* [flosse/rust-sun](https://github.com/flosse/rust-sun) [[sun](https://crates.io/crates/sun)]  — JS库suncalc的一个锈端口 
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust)  — 铁锈天文学 
### Asynchronous

* [async-std](https://async.rs/) [[async-std](https://crates.io/crates/async-std)]  — Async版本的Rust标准库 [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [dpc/mioco](https://github.com/dpc/mioco)  — 可扩展的、基于协程序的异步IO处理库 
* [mio](https://github.com/tokio-rs/mio)  — MIO是用于Rust的轻量级IO库，其重点是在OS抽象上增加尽可能少的开销 
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs)  — Rust中的零成本期货 
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust)  — Monad/MonadIO，处理程序，协程/doNotation，Rust的函数式编程特性 
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may)  — 铁锈堆叠协程序库 
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs)  — 具有工作窃取调度程序的协程I/O库 
### Audio and Music

[[audio](https://crates.io/keywords/audio)]

* [hound](https://crates.io/crates/hound)  — 一个WAV编码和解码库 
* [insomnimus/nodi](https://github.com/insomnimus/nodi) [[nodi](https://crates.io/crates/nodi)]  — 用于播放和抽象MIDI文件的库。 [![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears)  — 一个简单的库来播放声音和音乐，在OpenAL和libsndfile之上 
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs)  — [·波特米迪](https://portmedia.sourceforge.net/portmidi/) 绑定 
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory)  — Rust音乐理论库 
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia)  — 支持AAC，FLAC，MP3，MP4，OGG，Vorbis和WAV的纯Rust音频解码和媒体解码库。 
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal)  — 纯锈中的低级跨平台音频I/O库。 [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio)  — Rust音频播放库 
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio)  — PortAudio绑定 
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) [[lofty](https://crates.io/crates/lofty)]  — 用于读取和编辑各种音频格式的元数据的库 [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) [[totp-rs](https://crates.io/crates/totp-rs)]  — 2fa库，生成并验证基于TOTP的令牌! [Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken)  — [JSON Web令牌](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust 
* [oauth2](https://github.com/ramosbugs/oauth2-rs)  — 可扩展的强类型Rust OAuth2客户端库 
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth)  — OAuth2服务器库，可与actix或其他前端结合使用，具有一组可配置和可插拔的后端 [![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault)  — 异步库管理和编排JWT工作流 
* [yup-oauth2](https://github.com/dermesser/yup-oauth2)  — 提供设备、安装和服务帐户流的oauth2客户端实现 
### Automotive

* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)]  — DBC格式的解析器 
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)]  — Linux SocketCAN BCM对tokio的支持 
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)]  — Linux SocketCAN库 
* [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [[tokio-socketcan](https://crates.io/crates/tokio-socketcan)]  — 基于SocketCAN板条箱的Linux socketcan支持tokio 
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)]  — LIN总线驾驶员特征及协议实现 [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio)  — Rust中的生物信息学库。 
### Caching

* [06chaynes/http-cache](https://github.com/06chaynes/http-cache) [[http-cache](https://crates.io/crates/http-cache)]  — 遵循HTTP缓存规则的缓存中间件 [![build badge](https://github.com/06chaynes/http-cache/workflows/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/actions/workflows/http-cache.yml)
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache)  — Memcached客户端库 
* [al8n/stretto](https://github.com/al8n/stretto)  — 一种高性能的线程安全内存绑定Rust缓存 [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [jaemk/cached](https://github.com/jaemk/cached)  — 简单函数缓存/记忆 
* [moka-rs/moka](https://github.com/moka-rs/moka)  — 受Java咖啡因库启发的Rust高性能并发缓存库 [![build badge](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)
* [mozilla/sccache](https://github.com/mozilla/sccache/)  — 共享编译缓存，非常适合Rust编译 
* [zkat/cacache-rs](https://github.com/zkat/cacache-rs)  — 高性能，并发，可寻址内容的磁盘缓存，针对异步api进行了优化 [![build badge](https://github.com/zkat/cacache-rs/workflows/CI/badge.svg)](https://github.com/zkat/cacache-rs/actions/workflows/ci.yml)

### Cloud

* AWS [[aws](https://crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) [[lambda_runtime](https://crates.io/crates/lambda_runtime)]  — AWS Lambda的Rust运行时 [![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust)  — 新的AWS Rust SDK 
  * [rusoto/rusoto](https://github.com/rusoto/rusoto)  — * 负载均衡器 
  * [Convey](https://github.com/bparli/convey)  — 具有动态配置加载的第4层负载平衡器 
* Multi Cloud
  * [Qovery/engine](https://github.com/Qovery/engine)  — 抽象层库，只需几分钟就可以在云提供商上轻松部署应用程序 
### Command-line

* Argument parsing
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)]  — 一个简单易用的全功能命令行参数解析器 
  * [cliparser](https://crates.io/crates/cliparser)  — 简单的命令行解析器。 [![build badge](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [[docopt](https://crates.io/crates/docopt)]  — 生锈的实现 [DocOpt](http://docopt.org)
  * [google/argh](https://github.com/google/argh) [[argh](https://crates.io/crates/argh)]  — 优化代码大小的基于派生的自以为是参数解析器 [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)]  — 在Rust中快速构建酷的CLI应用 
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[seahorse](https://crates.io/crates/seahorse)]  — 用Rust编写的最小CLI框架 [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)]  — 通过定义一个结构来解析命令行参数 
* Data visualization
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[comfy-table](https://crates.io/crates/comfy-table)]  — 漂亮的动态表为您的cli工具。 [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) [[tabled](https://crates.io/crates/tabled)]  — 一个易于使用的库，用于漂亮的Rust structts和枚举打印表。 [![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* Human-centered design
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)]  — 给人类的恐慌信息 
* Line editor
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)]  — Rust中的readline实现 
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)]  — 提供类似readline功能的库 
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)]  — 可配置、可扩展、交互式线路阅读器 
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)]  — pure-Rust命令行编辑库 
* Other
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) [[update-informer](https://crates.io/crates/update-informer)]  — 更新CLI应用程序的informer。它在Crates.io和GitHub上检查新版本 [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* Pipeline
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)]  — 与外部管道交互的设施 
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)]  — 通过外部寻呼机引导您的输出 
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)]  — 子进程管道和IO重定向的构建器 
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) [[rexpect](https://crates.io/crates/rexpect)]  — 自动化交互式应用程序，如ssh、ftp、passwd等 [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) [[expectrl](https://crates.io/crates/expectrl)]  — 用于控制伪终端中的交互式程序的库 [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* Progress
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)]  — 控制台防锈进度条 
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[indicatif](https://crates.io/crates/indicatif)]  — 向用户指示进度 
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) [[spinach](https://crates.io/crates/spinach)]  — 实用的防锈旋转器。 [![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)]  — 60个优雅的终端旋转器 
* Prompt
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)]  — -构建交互式命令提示符 
  * [mikaelmello/inquire](https://github.com/mikaelmello/inquire) [[inquire](https://crates.io/crates/inquire)]  — 用于在终端上构建交互式提示的库。 [![Build status](https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mikaelmello/inquire/actions)
  * [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)]  — -任何外壳的最小、快速和极其可定制的提示 [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) [[promkit](https://crates.io/crates/promkit)]  — -用于构建交互式命令行工具的工具包 [![Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
* Style
  * [colored](https://github.com/colored-rs/colored) [[colored](https://crates.io/crates/colored)]  — 着色终端这么简单，你已经知道怎么做了! 
  * [console-rs/dialoguer](https://github.com/console-rs/dialoguer) [[dialoguer](https://crates.io/crates/dialoguer)]  — 用于命令行提示和类似事物的rust库。 
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) [[bunt](https://crates.io/crates/bunt)]  — 跨平台终端颜色和带宏的造型 [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)]  — 跨平台风格的终端输出 
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)]  — 控制ANSI终端上的颜色和格式 
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)]  — 一个死的简单ANSI终端彩色画库 
* TUI
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)]  — [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) 绑定 
  * [fdehau/tui-rs](https://github.com/fdehau/tui-rs) [[tui](https://crates.io/crates/tui)]  — 受启发的TUI图书馆 [blessed-contrib](https://github.com/yaronn/blessed-contrib) and [termui](https://github.com/gizak/termui)
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)]  — 构建丰富的TUI应用 
  * [ivanceras/titik](https://github.com/ivanceras/titik)  — 一个跨平台的TUI小部件库，目标是提供交互式小部件 
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)]  — curses库，支持linux和windows 
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)]  — [ncurses](https://www.gnu.org/software/ncurses/) 绑定 
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)]  — 用于将东西放在网格中的Rust库 
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)]  — 用于控制终端/TTY的无bindless库 
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) [[rustbox](https://crates.io/crates/rustbox)]  — 绑定到 [Termbox](https://github.com/nsf/termbox)
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)]  — 跨平台终端库 
### Compression

* [7z](https://7-zip.org/7z.html)
  * [dyz1990/sevenz-rust](https://github.com/dyz1990/sevenz-rust) [[sevenz-rust](https://crates.io/crates/sevenz-rust)]  — 用纯铁锈编写的7z解压缩器/压缩器。 [![Rust](https://github.com/dyz1990/sevenz-rust/workflows/Rust/badge.svg?branch=main)](https://github.com/dyz1990/sevenz-rust/actions)
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli)  — 铁锈中的Brotli解压缩器，可选地避免stdlib 
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs)  — Brotli压缩的实现 
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs)  — [libbz2](https://www.sourceware.org/bzip2/) 绑定 
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)]  — 实现Zopfli压缩算法以实现更高质量的deflate或zlib压缩 
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/)  — deflate格式和snappy的多线程编码和解码 
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs)  — [miniz](https://code.google.com/archive/p/miniz) 绑定 [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy)  — [·斯纳皮](https://github.com/google/snappy) 绑定 
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs)  — 铁锈中的tar档案阅读/写作 
* zip
  * [zip-rs/zip](https://github.com/zip-rs/zip)  — 读写ZIP档案 
### Computation

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)]  — 一个纯锈优化库 
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
 — * [mikkyang/rust-bas](https://github.com/mikkyang/rust-bas)-bas绑定 
* [calebwin/emu](https://github.com/calebwin/emu)  — 一种从Rust宏中进行GPGPU数值计算的语言 
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra)  — 低维线性代数库 
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL)  — GSL绑定 
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack)  — LAPACK绑定 
* Parallel
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust)  — [Arrayfire](https://github.com/arrayfire) 绑定 
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma)  — 一个可扩展的，可插拔的，与后端无关的框架，用于在CUDA，OpenCL和通用主机CPU上进行并行，高性能的计算。 
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl)  — [OpenCL](https://www.khronos.org/opencl/) 绑定 
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust)  — Rust中的科学计算库 
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs)  — 鲁斯特中的鲁棒统计计算库 
### Concurrency

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam)  — -在Rust中支持并行性和低级并发 
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)]  — 库从 'Rc'/'Arc' 指针类型进行抽象。 [![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
* [Rayon](https://github.com/rayon-rs/rayon)  — -用于Rust的数据并行性库 
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs)  — -铁锈中的协图库 
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs)  — -用于生锈的协程序I/O 
### Configuration

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) [[uclicious](https://crates.io/crates/uclicious)]  — 基于 [libUCL](https://github.com/vstakhov/libucl) 的功能丰富配置库。 [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)]  — 易于处理应用程序配置的库 
* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)]  — 用于Rust应用的分层配置系统 (对12因素应用的强大支持)。 
* [softprops/envy](https://github.com/softprops/envy)  — 将env vars反序列化为类型安全结构 [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat)  — Arkworks绑定到Circom的R1CS，用于在Rust中生成Groth16证明和见证。 
* [briansmith/ring](https://github.com/briansmith/ring)  — 使用Rust和BoringSSL的密码学原语安全、快速、小加密。 
* [briansmith/webpki](https://github.com/briansmith/webpki)  — Rust中的Web PKI TLS X.509证书验证 
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)]  — 在终端中使用的简单密码管理器 
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)]  — 用于解决典型数据安全任务的高级密码库，最适合多平台应用程序。 [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto)  — Rust中的密码算法 
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek)  — 纯锈实现Curve25519操作 
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek)  — Ed25519数字签名的纯锈实现 
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek)  — X25519密钥交换的纯锈实现 
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak)  — Keccak家族 (SHA3) 的纯锈实施 
* [exonum/exonum](https://github.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)]  — 区块链项目的可扩展框架 
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke)  — 最近的纯锈实施 [OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* [klutzy/suruga](https://github.com/klutzy/suruga)  — 生锈的实现 [TLS 1.2](https://datatracker.ietf.org/doc/html/rfc5246)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework)  — 安全框架的绑定 (OSX原生) 
* [libOctavo/octavo](https://github.com/libOctavo/octavo)  — 鲁斯特中的模块化哈希和加密库 
* [orion-rs/orion](https://github.com/orion-rs/orion)  — 该库旨在提供简单可用的加密。“可用” 表示公开易于使用且难以滥用的高级API。 [![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)]  — Django项目中使用的密码原语的Rust端口。它不需要Django，只需要根据其样式进行哈希和验证密码。 
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes)  — 用纯Rust编写的加密哈希函数的集合 
* [rustls/rustls](https://github.com/rustls/rustls)  — TLS的Rust实现 
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls)  — 本机TLS库的绑定 
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl)  — [OpenSSL](https://www.openssl.org/) 绑定 
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) [[scryptenc](https://crates.io/crates/scryptenc)]  — scrypt加密数据格式的一种实现 [![CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)
* [vityafx/randomorg](https://github.com/vityafx/randomorg)  — A random.org客户端库。 [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel)  — Schnorr vrf和ristretta组上的签名 
### Data processing

* [amv-dev/yata](https://github.com/amv-dev/yata)  — 高性能技术分析库 [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray)  — 具有数组视图、多维切片和高效操作的n维数组 
* [kernelmachine/utah](https://github.com/kernelmachine/utah)  — 铁锈中的数据帧结构和操作 
* [pola-rs/polars](https://github.com/pola-rs/polars)  — 快速功能完成DataFrame库! [Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
* [weld-project/weld](https://github.com/weld-project/weld)  — 数据分析应用程序的高性能运行时 
### Data streaming

* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo)  — Rust和SQL中的高性能实时分析 [![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* [infinyon/fluvio](https://github.com/infinyon/fluvio)  — 可编程数据流平台 [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### Data structures

* [becheran/grid](https://github.com/becheran/grid) [[grid](https://crates.io/crates/grid)]  — 为rust提供易于使用且快速的二维数据结构。 [![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)]  — 三元搜索树集合 
* [contain-rs](https://github.com/contain-rs)  — Rust的std::collections的扩展 
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool)  — 防锈阵列助手。一些最常见的方法，你会使用在数组上提供矢量。用于处理大多数用例的多态实现。 
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array)  — -允许按类型大小排列的数组的黑客 
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] — A priority queue that implements priority changes.
* [greyblake/nutype](https://github.com/greyblake/nutype) [[nutype](https://crates.io/crates/nutype)]  — 定义具有验证约束的新类型结构。 [![build status](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs)  — Rust中的K维树，用于快速地理空间索引和最近邻查找 
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)]  — Rust中的持久数据结构。 [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs)  — -Rust中的咆哮位图 
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools)  — * [tnballo/scapegoat](https://github.com/tnballo/scapegoat) [[scapegoat](https://crates.io/crates/scapegoat)] — Safe, fallible, stack-only alternative to `BTreeSet` and `BTreeMap`. [![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* [xfix/enum-map](https://github.com/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)]  — 使用数组存储值的枚举的优化映射实现。 
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) [[hypergraph](https://crates.io/crates/hypergraph)]  — 超图是生成有向超图的数据结构库。 [![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs)  — [ [egui_graphs](https://crates.io/crates/egui_graphs)] - Interactive graph visualization widget for rust powered by egui and petgraph. [![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)
* [djduque/pgfplots](https://github.com/djduque/pgfplots) [[pgfplots](https://crates.io/crates/pgfplots)]  — 生成出版物质量数字的Rust库。 [![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly)  — 为生锈而努力。 
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) [[colorgrad](https://crates.io/crates/colorgrad)]  — 用于数据可视化，图表，游戏，地图，生成艺术等的Rust彩色标度库。 
* [milliams/plotlib](https://github.com/milliams/plotlib)  — * [plotters](https://github.com/plotters-rs/plotters) — [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* [rerun](https://github.com/rerun-io/rerun)  — [[重新运行](https:// crates.io/crates/rerun)] -一个用于记录计算机视觉和机器人数据 (张量、点云等) 的SDK，与一个可视化器配对，用于随着时间的推移探索这些数据。 
* [saresend/gust](https://github.com/saresend/Gust)  — ### 数据库 
[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://www.arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)]  — 轻量级ArangoDB对象文档、关系图映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)]  — 用于Rust的ArangoDB驱动程序 
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
 — * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] -用Rust编写的本机客户端 
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio)  — [! [build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol)] - Cassandra protocol implementation in Rust
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - production-ready async Apache Cassandra driver written in pure Rust
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs)  — 绑定到DataStax C/C客户端 
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)]  — CouchDB REST API的Rust客户端 
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
 — * [softprops/dynomite](https://github.com/softprops/dynomite) - A library for strongly-typed and convenient interaction with `rusoto_dynamodb` [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)]  — [弹性](https://www.elastic.co/) REST API的Rust客户端 
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) [[elastic](https://crates.io/crates/elastic)]  — elastic是一种高效的模块化API客户端，用于用Rust编写的Elasticsearch [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)]  — CoreOS的etcd的客户端库 
    * [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs)  — 用于rust的异步etcd客户端 [![CI](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood)  — [ForestDB](https://github.com/couchbase/forestdb) 绑定 
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs)  — 同步接口 
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb)  — [LevelDB](https://github.com/google/leveldb) 绑定 
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)]  — [LMDB](https://www.symas.com/symas-嵌入式-数据库-lmdb) 绑定 
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)]  — [MongoDB](https://www.mongodb.com/) 绑定 
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs)  — 一个轻量级和简单的键值存储，在很大程度上受到Python的PickleDB的启发。 
  * [PoloDB](https://www.polodb.org/)
    * [PoloDB](https://github.com/PoloDB/PoloDB)  — 基于JSON的嵌入式数据库具有类似于MongoDB的API。! [GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
  * [Redb](https://www.redb.org/)
    * [Redb](https://github.com/cberner/redb)  — 用纯Rust编写的嵌入式键值数据库它提供了与其他嵌入式键值存储 (如rocksdb和lmdb) 类似的接口。! [GitHub Workflow Status](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[fred](https://crates.io/crates/fred)]  — 高级异步 [Redis](https://redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs)  — Rust中的 [Redis](https://redis.io/) 库 [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb)  — RocksDB绑定 [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb)  — 超现实数据库嵌入式文档-图形数据库 
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs)  — UnQLite绑定 
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)]  — Apache ZooKeeper的客户端库 
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[zookeeper-async](https://crates.io/crates/zookeeper-async)]  — Async Zookeeper客户端在Rust中编写的100%，基于tokio。! [build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)]  — 轻量级ArangoDB对象文档、关系图映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust)  — 自动生成的查询生成器，可使用Prisma生态系统提供简单且完全类型安全的数据库访问。 [![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel)  — Rust的ORM和查询生成器 
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm)  — 生锈的ORM 
  * [rbatis/rbatis](https://github.com/rbatis/rbatis)  — Rust ORM框架高性能 (基于JSON) 
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm)  — 铁锈的异步和动态ORM [![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * [SeaQL/seaography](https://github.com/SeaQL/seaography)  — SeaORM的GraphQL框架 [![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
* [sfackler/r2d2](https://github.com/sfackler/r2d2)  — 通用连接池 
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx)  — 异步PostgreSQL/MySQL/SQLite连接池，支持强大的打字功能 [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query)  — 适用于MySQL、Postgres和SQLite的动态SQL查询构建器 [![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema)  — SQL模式定义和发现 [![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius)  — [! [Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs)  — MySQL代理 [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)]  — 基于Tokio的异步Rust Mysql驱动程序。 [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)]  — 原生MySql客户端 
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) [[oracle](https://crates.io/crates/oracle)]  — Oracle Rust驱动程序 [![build badge](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)]  — 本地 [PostgreSQL](https://www.postgresql.org/) 客户端 
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite)  — [Sqlite3](https://www.sqlite.org/index.html) 绑定 
### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://github.com/chronotope/chrono)  — * [Mnwa/ms](https://github.com/Mnwa/ms) [[ms-converter](https://crates.io/crates/ms-converter)] — it's a library for converting human-like times to milliseconds [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) [[nt-time](https://crates.io/crates/nt-time)]  — 一个Windows文件时间库。 [![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)
* [time-rs/time](https://github.com/time-rs/time)  — [! [build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)]  — 流处理/分布式计算平台 
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)]  — [librdkafka](https://github.com/confluentinc/librdkafka) 绑定 
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)]  — 与 [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust)  — * 豆豆 
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd)  — [Beanstalkd](https://github.com/beanstalkd/beanstalkd) 绑定 
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) [[hdfs](https://crates.io/crates/hdfs)]  — libhdfs绑定 
* Other
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)]  — 面向分布式应用的端到端加密、相互认证和ABAC [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)

### Domain driven design

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [[cqrs-es](https://crates.io/crates/cqrs-es)]  — CQRS和事件采购的框架 [user guide](https://doc.rust-cqrs.org/)

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya)  — Rust编程语言的Rust库，以开发人员经验和可操作性为重点。 
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs)  — Rust生态系统的最小且自以为是的eBPF工具。 
### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) [[imap-codec](https://crates.io/crates/imap-codec)]  — 用于IMAP的坚如磐石和完整的编解码器 [![Build & Test](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs)  — SendGrid API的非官方Rust库 
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte)  — 使用 [MRML](https://github.com/jdrouet/mrml) 模板发送电子邮件的微服务。 
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail)  — 用于构建 [MRML](https://github.com/jdrouet/mrml) 模板的web应用程序。 
* [jdrouet/mrml](https://github.com/jdrouet/mrml)  — 一个库，用于生成在任何邮件客户端上工作的漂亮电子邮件模板。 
* [lettre/lettre](https://github.com/lettre/lettre)  — 用于生锈的SMTP库 [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan)  — 用于测试和开发环境的SMTP服务器。 
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)]  — 解析真实世界电子邮件文件的库 
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) [[mail-auth](https://crates.io/crates/mail-auth)]  — DKIM、ARC、SPF和DMARC消息认证库 [![build badge](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[mail-parser](https://crates.io/crates/mail-parser)]  — 具有完全MIME支持的快速强大的电子邮件解析库 [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[mail-send](https://crates.io/crates/mail-send)]  — 支持DKIM的电子邮件生成器和SMTP客户端库 [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab)  — 用于开发的电子邮件测试服务器。 
### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1)  — Rust ASN.1 (DER) 序列化器 
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode)  — Rust中的二进制编码器/解码器 [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) [[postcard](https://crates.io/crates/postcard)]  — 明信片是 #![no_std] Serde的聚焦序列化器和反序列化器。 
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)]  — 跨平台、零副本和字节序感知的二进制解析 
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust)  — Rust中BSON的编码和解码支持 
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder)  — 支持大端序、小端序和原生字节顺序 
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust)  — * CBOR 
  * [serde_cbor](https://crates.io/crates/serde_cbor)  — CBOR对serde的支持 
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)]  — Rust中面向壁虎的编码标准的实现 
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding)  — * 儿童权利委员会 
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs)  — * CSV 
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv)  — 快速灵活的CSV阅读器和编写器，支持Serde 
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)]  — 板条箱将EDN格式解析并发射成Rust类型。 
* [FlatBuffers](https://flatbuffers.dev/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust)  — 货物构建脚本的FlatBuffers编译器 (flatc) 集成 
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) [[har](https://crates.io/crates/har)]  — 一个HTTP归档格式 (HAR) 序列化 & 反序列化库 
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever)  — 高性能浏览器级HTML5解析器 
* JSON
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson](https://crates.io/crates/ajson)]  — 快速获取JSON值 
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)]  — Rust中的JSON实现 
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[pikkr](https://crates.io/crates/pikkr)]  — JSON解析器，它直接获取值，而无需在Rust中执行标记化 
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)]  — JSON支持 [Serde](https://github.com/serde-rs/serde) 框架 
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)]  — 基于simdjson端口的高性能JSON解析器 
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust)  — 纯Rust低/高级MessagePack实现 
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) [[netcdf](https://crates.io/crates/netcdf)]  — 用于Rust的中级netCDF绑定，可轻松读取和写入类似数组的结构到文件。 
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)]  — 一种基于Rust的PEM编码数据解析和编码方法 
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf)  — * [tokio-rs/prost](https://github.com/tokio-rs/prost) — [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) [[rkyv](https://crates.io/crates/rkyv)]  — rkyv (archive) 是Rust的零副本反序列化框架 
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron)  — * 塞德 
  * [vityafx/serde-aux](https://github.com/vityafx/serde-aux/)  — 用于与serde库一起使用的其他工具。 [![CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) [[taplo](https://crates.io/crates/taplo)]  — 用Rust编写的TOML工具包 [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
  * [toml-rs/toml](https://github.com/toml-rs/toml)  — [! [CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML)  — 用Rust编写的XML解析器 
  * [media-io/yaserde](https://github.com/media-io/yaserde)  — 又一个专门用于XML的序列化器/反序列化器 
  * [netvl/xml-rs](https://github.com/netvl/xml-rs)  — 流式XML库 
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document)  — Rust中的XML库 
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath)  — Rust中的XPath库 
  * [tafia/quick-xml](https://github.com/tafia/quick-xml)  — 高性能XML拉式读取器/写入器 
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust)  — 缺少的YAML 1.2 Rust的实现。 
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)]  — YAML支持 [Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)]  — UTF-8中的Sorta文本格式 
### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [Camino](https://github.com/camino-rs/camino) [[camino](https://crates.io/crates/camino)]  — 像Rust的std::path::Path，但UTF-8。 
  * [ParthJadhav/Rust_Search](https://github.com/ParthJadhav/Rust_Search) [[rust_search](https://crates.io/crates/rust_search)]  — Rust内置的快速文件搜索库。 
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) [[dbus-udisks2](https://crates.io/crates/dbus-udisks2)]  — UDisks2 DBus应用编程接口 
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)]  — “Mount”/“umount2” 系统调用的高级抽象。 
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) [[path_abs](https://crates.io/crates/path_abs)]  — 绝对可序列化路径类型和关联方法 
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra)  — 扩大机会标准图书馆标准::fs和标准::io 
* Temporary Files
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile)  — 临时文件库 
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)]  — 列出和操作unix扩展文件属性 
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)]  — 零细节、注重隐私的可嵌入文件系统。 
### Finance

* [avhz/RustQuant](https://github.com/avhz/RustQuant) [[RustQuant](https://crates.io/crates/RustQuant)]  — 一个量化金融库。! [GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) [[apca](https://crates.io/crates/apca)]  — 自以为是的全面绑定到 [Alpaca API](https://alpaca.markets/) for stock trading and more. ![GitHub Workflow Status](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)

### Functional Programming

[[functional programming](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs)  — Rust中的函数式编程库 
  * [myrrlyn/tap](https://github.com/myrrlyn/tap)  — 后缀-位置管道行为 
### Game development

See also [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro)  — [快板5](https://liballeg.org/) 绑定 
* [Awesome Quads](https://github.com/ozkriff/awesome-quads)  — 到miniquad/macroquad相关代码和资源的链接的精选列表 
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu)  — wgpu代码和资源的精选列表 
* bracket-lib (previously RLTK)
  * [bracket-lib](https://github.com/amethyst/bracket-lib) [[bracket-lib](https://crates.io/crates/bracket-lib)]  — 为Rust实现的Roguelike工具包 (RLTK)。 [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) [[challonge](https://crates.io/crates/challonge)]  — Challonge REST API的客户端库有助于组织锦标赛。 [![CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs)  — [·科兰格](https://github.com/orangeduck/Corange) 绑定 
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs)  — 规格并行ECS 
  * [legion](https://github.com/amethyst/legion)  — 功能丰富的高性能ECS库，具有最少的样板 [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  * [Bevy](https://github.com/bevyengine/bevy)  — 是Rust中内置的令人耳目一新的简单数据驱动游戏引擎。- [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [Fyrox](https://fyrox.rs/)  — 生锈游戏引擎3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez)  — 一个轻量级的游戏框架，用于制作摩擦最小的2D游戏- [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org)  — 一个保持简单，用铁锈编写的愚蠢的3d图形引擎 [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator)  — 用Rust和WebGPU编写的实时战略游戏/引擎 
  * [Piston](https://www.piston.rs/)  — [! [Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * [Unrust](https://github.com/unrust/unrust)  — unrust-基于纯锈 (webgl 2.0/原生) 游戏引擎 
* [Godot](https://godotengine.org/)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) [[gdnative](https://crates.io/crates/gdnative)]  — Godot游戏引擎的Rust绑定 [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)]  — raylib的防锈绑定 
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
 — * [brson/rust-sdl](https://github.com/brson/rust-sdl)-SDL1绑定 
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2)  — SDL2绑定 
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml)  — [SFML](sfml-dev.org/) 绑定 
* Skillratings
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) [[skillratings](https://crates.io/crates/skillratings)]  — Elo，Glicko-2，TrueSkill等多人游戏的技能评级算法集合。 [![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs)  — 用于Rust的Libtcod绑定。 
  * Warning: Not maintained anymore
* Toornament-rs
  * [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs)  — 为Rust Toornament.com API绑定。 [![CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)]  — 简单的UDP游戏服务器和UDP客户端框架，用于创建简单的2D和3D在线游戏原型 
### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) [[coord_transforms](https://crates.io/crates/coord_transforms)]  — 坐标变换 (二维、三维和地理空间) 
* [Georust](https://github.com/georust)  — 用Rust编写的地理空间工具和库 
* [MapLibre/Martin](https://github.com/maplibre/martin)  — 地图瓦片服务器，支持PostGIS、MBTiles、PMTiles和sprites。 [![CI build](https://github.com/maplibre/martin/workflows/CI/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io version](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![Book](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo)  — Rust中的快速离线反向地理编码器，灵感来自 [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)]  — UTM、LatLon和MGRS坐标之间的转换 
### Graph algorithms

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph)  — 高性能图算法库 [![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* [petgraph/petgraph](https://github.com/petgraph/petgraph)  — 用于Rust的图数据结构库 [![graph CI status](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz)  — 生锈的增量harfbuzz端口 
  * [redox-os/rusttype](https://github.com/redox-os/rusttype)  — FreeType等库的纯Rust替代品 
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx)  — 用于Rust的高性能，无二进制图形API。 
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu)  — 基于gfx-hal的原生WebGPU实现 [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs)  — * [glium/glium](https://github.com/glium/glium) -Rust语言的安全OpenGL包装器。 
  * [glutin](https://crates.io/crates/glutin)  — 铁锈替代品 [GLFW](https://www.glfw.org/)
  * [Kiss3d](http://kiss3d.org)  — 画简单的几何图形，用单线玩弄 
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs)  — * PDF 
  * [fschutt/printpdf](https://github.com/fschutt/printpdf)  — PDF写作库 
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf)  — PDF文档操作 
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf)  — * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) – Generates PDF files with JavaScript and WASM (WebAssembly)
* [Vulkan](https://www.vulkan.org/) [[vulkan](https://crates.io/keywords/vulkan)]
 — * [erupt](https://gitlab.com/Friz64/erupt) [[erupt](https://crates.io/crates/erupt)] — [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)]  — # 图形用户界面 
[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs)  — 一个简单的跨平台的Rust GUI自动化库 
* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs)  — * [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [emilk/egui](https://github.com/emilk/egui)  — 用于Rust. egui的简单，快速和高度可移植的即时模式GUI库在网络上本地运行，并在您最喜欢的游戏引擎中运行。 [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb)  — minifb是具有可选位图渲染的跨平台窗口设置。它还带有简单的鼠标和键盘输入。主要为原型设计 
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs)  — FLTK铁锈绑定 [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs)  — 在dart & rust中构建flutter桌面应用程序。 
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge)  — Flutter/Dart <-> Rust的高级内存安全绑定生成器 
* [fschutt/azul](https://github.com/fschutt/azul)  — 一个免费的、功能的、面向IMGUI的GUI框架，用于快速开发用Rust编写的桌面应用程序，由Mozilla WebRender渲染引擎支持。 
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
 — * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) - GTK4 binding for rust ![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm)  — 异步，基于GTK的，GUI库，灵感来自Elm 
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)]  — 用于Rust的跨平台GUI库专注于简单性和类型安全性。受到榆树的启发。 
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs)  — ImGui的防锈绑定 [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui)  — 基于IUP构建的简单UI框架 
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native)  — 一个真正的原生和跨平台的GUI库。一个统一的代码可以作为本机GUI，Html Web和TUI运行。 
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs)  — libui绑定。 
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust)  — Nuklear的防锈绑定 
* [OrbTk](https://github.com/redox-os/orbtk)  — 轨道小部件工具包是一个使用SDL2的多平台 (G)UI工具包 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/)  — 完全用Rust编写的易于使用的即时模式2D GUI库 
* [Qt](https://doc.qt.io)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs)  — QtQuick绑定 
  * [rust-qt](https://github.com/rust-qt)
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs)  — 通过在编译时构建QMetaObject来集成Qml和Rust。 
* [rise-ui](https://github.com/rise-ui/rise)  — 简单的基于组件的跨平台GUI工具包，用于开发美观且用户友好的界面。 
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs)  — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 绑定 
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter)  — Sciter绑定 [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint)  — [·斯林特](https://crates.io/crates/slint)- [Slint](https://slint.dev/) is a toolkit to efficiently develop fluid graphical user interfaces for embedded devices and desktop applications. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri)  — 使用web前端构建更小、更快、更安全的桌面应用程序，由 [WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/wry](https://github.com/tauri-apps/wry)  — Webview渲染库。 
* [xilem](https://github.com/linebender/xilem)  — 数据第一锈原生ui设计工具包的继任者 [德鲁伊](https://github.com/linebender/druid)。 
### Image processing

* [abonander/img_hash](https://github.com/abonander/img_hash)  — 感知图像散列和比较的平等和相似。 
* [image-rs/image](https://github.com/image-rs/image)  — 用于转换和转换图像格式的基本成像处理功能和方法 
* [image-rs/imageproc](https://github.com/image-rs/imageproc)  — 一种基于 '图像' 库的图像处理库 
* [marekm4/dominant_color](https://github.com/marekm4/dominant_color) [[dominant_color](https://crates.io/crates/dominant_color)]  — 显性颜色提取器! [build badge](https://github.com/marekm4/dominant_color/actions/workflows/rust.yml/badge.svg?branch=master)
* [rust-cv/cv](https://github.com/rust-cv/cv)  — Rust CV是一个在Rust中实现计算机视觉算法，抽象和系统的项目。# [no_std] is supported where possible. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)]  — 一个简单的隐写术库 
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust)  — OpenCV的防锈绑定 
### Language specification

* [shnewto/bnf](https://github.com/shnewto/bnf)  — 用于解析Backus-Naur形式上下文无关语法的库。 
### Logging

[[log](https://crates.io/keywords/log)]

* [estk/log4rs](https://github.com/estk/log4rs)  — 基于Java的Logback和log4j库建模的高度可配置日志记录框架 [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [jesusprubio/leg](https://github.com/jesusprubio/leg)  — 懒惰开发人员的优雅印花。用最少的努力让你的克莱尔变得更好。 [![Build Status](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
* [rbatis/fast_log](https://github.com/rbatis/fast_log)  — Rust异步日志高性能异步日志 
* [rust-lang/log](https://github.com/rust-lang/log)  — Rust的日志记录实现 
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger)  — 一种漂亮、易于使用的生锈记录器。 
* [slog-rs/slog](https://github.com/slog-rs/slog)  — 结构化、可组合的生锈日志记录 
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing)  — 用于异步感知结构化日志记录、错误处理、度量等的应用程序级别跟踪框架 [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute)  — Rust中Python风格列表理解的宏。 
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust)  — C #-LINQ-like表达式的宏及方法 [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark)  — [CommonMark](https://commonmark.org/) Rust中的解析器 
### Mobile

* Android / iOS
  * [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios)  — 分别使用Rust-swig和cbindgen为Android和iOS使用共享rust lib的示例。 
* Generic
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo)  — 一个货物lipo子命令，它会自动创建一个通用库，供您的iOS应用程序使用。 
### Network programming

* Bluetooth
  * [bluez/bluer](https://github.com/bluez/bluer) [[bluer](https://crates.io/crates/bluer)]  — 铁锈的官方BlueZ绑定。 [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs)  — 用于Rust的 [约束应用协议 (CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) 库。 
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard)  — Rust中的Docker守护进程API 
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp)  — 用于Rust的 [FTP](https://en.wikipedia.org/wiki/文件_传输_协议) 客户端 
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic)  — 具有异步/等待支持的本地gRPC客户端和服务器实现 [![Crates.io](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs)  — 基于C核心库和期货的gRPC Rust库 
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl)  — 使用纯文本和libcurl运行和测试HTTP请求 [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork)  — 在纯铁锈中使用ip网络的库 
  * [candrew/netsim](https://github.com/canndrew/netsim)  — 用于网络仿真和测试的Rust库 
  * [jesusprubio/online](https://github.com/jesusprubio/online)  — 图书馆检查您的互联网连接 [![CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
* Low level
  * [actix/actix](https://github.com/actix/actix)  — 演员库防锈 
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol)  — 自定义TCP/UDP协议定义 
  * [libpnet/libpnet](https://github.com/libpnet/libpnet)  — 跨平台、低级网络 
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp)  — 一个独立的、事件驱动的TCP/IP堆栈，专为裸机实时系统设计 
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio)  — 一种网络应用框架，用于客户端和服务器的快速开发和高度可扩展的生产部署。 
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io)  — 事件驱动的消息库，轻松快速地构建网络应用程序。支持TCP、UDP和WebSockets。 [![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt)  — 供开发人员构建与 [MQTT protocol](https://mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs)  — [nanomsg](https://nanomsg.org/) 绑定 
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs)  — 云原生消息系统NATS的Rust客户端。 [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)]  — [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) 绑定 [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) [[nntp](https://crates.io/crates/nntp)]  — 用于Rust的 [NNTP](https://en.wikipedia.org/wiki/网络_新闻_传输_协议) 客户端 
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p)  — libp2p网络栈的Rust实现 [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) [[pop3](https://crates.io/crates/pop3)]  — 用于Rust的 [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 客户端 
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic)  — IETF QUIC协议的实现! [ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)
  * [cloudflare/quiche](https://github.com/cloudflare/quiche)  — QUIC传输协议和HTTP/3的cloudflare实现! [build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)
  * [mozilla/neqo](https://github.com/mozilla/neqo)  — 用Rust编写的QUIC的实现 
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn)  — 基于期货的QUIC在Rust中的实施 [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet)  — Rust的RakNet协议实现 [![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) [[remoc](https://crates.io/crates/remoc)]  — Remoc提供类似于Tokio的频道 (广播，mpsc，oneshot，watch) 和通过任何远程传输的特征呼叫。 [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs)  — 用于Rust的RPC库，用于以简单明了的方式开发微服务。 
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[rust_socketio](https://crates.io/crates/rust_socketio)]  — 一种实现 [socket.io](https://socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs)  — [libssh2](https:// libssh2.org/) 绑定 
  * [Thrussh](https://pijul.org/thrussh) [[thrussh](https://crates.io/crates/thrussh)]  — 用Rust从头开始编写的SSH库，由 [libsodium](https://doc.libsodium.org/)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs)  — Rust中的 [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) 客户端实现 
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq)  — [ZeroMQ](https://zeromq.org/) 绑定 
### Parsing

  * [comex/rust-shlex](https://github.com/comex/rust-shlex) [[shlex](https://crates.io/crates/shlex)]  — 将字符串拆分为shell单词，例如Python的shlex。 [![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt)  — Google的robots.txt解析器和匹配器C库的本机Rust端口 
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath)  — [JsonPath](https://goessner.net/articles/JsonPath/) 用铁锈写的引擎。Webassembly和Javascript也支持 
  * [hmeyer/stl_io](https://crates.io/crates/stl_io)  — STL (立体平版) 文件的解析器 
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg)  — 解析表达式语法 (PEG) 解析器生成器 
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop)  — LR(1) 锈蚀解析器生成器 
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp)  — -快速单子风格的解析器组合器 
  * [Marwes/combine](https://github.com/Marwes/combine)  — 解析器组合器库 
  * [nrc/zero](https://github.com/nrc/zero) [[zero](https://crates.io/crates/zero/)]  — 二进制数据的零分配解析 
  * [pest-parser/pest](https://github.com/pest-parser/pest)  — 优雅的解析器 
  * [ptal/oak](https://github.com/ptal/oak)  — 一个类型化的PEG解析器生成器 (编译器插件) 
  * [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs)  — 波前OBJ格式的解析器。 [![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
  * [rust-bakery/nom](https://github.com/rust-bakery/nom)  — 解析器组合器库 
  * [s-panferov/queryst](https://github.com/s-panferov/queryst)  — 启发了Rust的查询字符串解析库 [gs](https://github.com/ljharb/qs#readme)
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/)  — 具有更好的纠错功能的LR解析器 
### Peripherals

* Serial Port
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) [[serialport](https://crates.io/crates/serialport)]  — 提供对串行端口的访问的跨平台库 
### Platform specific

* Cross-platform
  * [svartalf/rust-battery](https://crates.io/crates/battery)  — 关于笔记本电池的跨平台信息 
  * [vityafx/thread-priority](https://github.com/vityafx/thread-priority/)  — 简单，跨平台线程优先级管理。 [![CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)]  — FreeBSD监狱图书馆的Rust实现 
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs)  — [inotify](https://en.wikipedia.org/wiki/Inotify) 绑定 [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/)  — Linux发行版安装程序 
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) [[iptables](https://crates.io/crates/iptables)]  — [iptables](https://www.netfilter.org/projects/iptables/index.html) 绑定 
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix)  — 类Unix API绑定 [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix)  — POSIX/Unix/Linux/Winsock2系统的安全锈绑定 [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs)  — [保险丝](https://github.com/libfuse/libfuse) 绑定 
* Windows
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs)  — 窗户生锈 [![Actions Status](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs)  — Windows API绑定 [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Scripting

[[scripting](https://crates.io/keywords/scripting)]

* [duckscript](https://crates.io/crates/duckscript)  — [简单、可扩展和可嵌入的脚本语言。](https://github.com/sagiegurari/duckscript) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp)  — 用于Rust游戏开发的类似Lisp的脚本语言 
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon)  — 一种小型的静态类型的函数式编程语言 
* [kcl](https://github.com/kcl-lang/kcl)  — 一种基于约束的记录和功能语言，主要用于配置和策略场景。 
* [metacall/core](https://github.com/metacall/core) [[metacall](https://crates.io/crates/metacall)]  — 支持NodeJS，JavaScript，TypeScript，Python，Ruby，C #，Wasm，Java，Cobol等的跨平台Polyglot运行时。 [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun)  — 一种具有一流热重载支持的编译静态脚本语言 
* [murarth/ketos](https://github.com/murarth/ketos)  — Lisp方言功能编程语言，用作rust的脚本和扩展语言 
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon)  — 一种生锈的动态类型化脚本语言 
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai)  — 一种微小而快速的嵌入式脚本语言，类似于JavaScript和Rust的组合 [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune)  — 用于Rust的可嵌入动态编程语言 
### Simulation

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space)  — 高保真、快速、可靠和经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定 [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### System

* [ardaku/whoami](https://github.com/ardaku/whoami) [[whoami](https://crates.io/crates/whoami)]  — 锈板条箱以获取当前用户和环境。 [![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) [[sysinfo](https://crates.io/crates/sysinfo)]  — 跨平台库获取系统信息 [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[nixinfo](https://crates.io/crates/nixinfo)]  — 用于收集系统信息的lib箱，例如cpu，发行版，环境，内核等。 
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) [[sysexits](https://crates.io/crates/sysexits)]  — 定义的系统退出代码 [`<sysexits.h>`](https://man.openbsd.org/sysexits). [![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)

### Task scheduling

* [delay-timer](https://github.com/BinChengZhao/delay-timer)  — 延迟任务的时间经理。像crontab，但异步任务是可能的。 
[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)](
https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

* Handlebars
  * [botika/yarte](https://github.com/botika/yarte)  — Yarte代表 ** Y ** et ** A ** nother ** R ** ust ** T ** emplate ** E ** ngine，是最快的模板引擎。 
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust)  — 带继承的车把模板引擎，自定义助手支持。 
* HTML
  * [djc/askama](https://github.com/djc/askama)  — 基于Jinja的模板渲染引擎 
  * [kaj/ructe](https://github.com/kaj/ructe)  — 生锈的HTML模板系统 
  * [Keats/tera](https://github.com/Keats/tera)  — 基于Jinja2和Django模板语言的模板引擎。 [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud)  — 编译时HTML模板 
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs)  — 编译时HTML模板 
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache)  — ### 文本处理 
* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[wildmatch](https://crates.io/crates/wildmatch)]  — 使用questionmark和star-wildcard运算符的简单字符串匹配 [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix)  — 线性时间后缀数组构造 (支持Unicode) 
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter)  — 弹性选项卡停止 (即文本列对齐) 
* [cpc](https://github.com/probablykasper/cpc)  — 解析并计算数学字符串，支持单位和单位转换，从 “1 2” 到 “1% 的回合 (1光年/14!s到km/h)”。 
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) [[triple_accel](https://crates.io/crates/triple_accel)]  — Rust编辑使用SIMD加速的距离例程; 支持快速汉明、Levenshtein、受限Damerau-Levenshtein等距离计算和字符串搜索 [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[fancy-regex](https://crates.io/crates/fancy-regex)]  — 正则表达式实现旨在支持相对丰富的功能集，例如环顾和回溯。 [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs)  — 基于三格拉姆语的自然语言检测库 
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)]  — -通用字符串可迭代连接 
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)]  — 自动换行文字 (支持连字) 
* [null8626/decancer](https://github.com/null8626/decancer) [[decancer](https://crates.io/crates/decancer)]  — 一个微小的包，从字符串中删除常见的unicode混淆/同位词。 [![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader)  — 允许在不消耗迭代器的情况下通过巨大文件行进行向前，向后和随机导航的阅读器 
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) [[ngrams](https://crates.io/crates/ngrams)]  — 从任意迭代器构造 [n-gram](https://en.wikipedia.org/wiki/N-gram) 
* [rust-lang/regex](https://github.com/rust-lang/regex)  — 正则表达式 (RE2样式) 
* [strsim-rs](https://crates.io/crates/strsim)  — 字符串相似性度量 
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)]  — Rust的RAKE算法的多语言实现 
### Text search

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)]  — 一个简单而轻量级的模糊搜索引擎，在内存中工作，搜索相似的字符串 
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)]  — * [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) [[perlin](https://crates.io/crates/perlin)] 
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch)  — 超相关、即时和容忍错字的全文搜索API。 [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [tantivy](https://github.com/quickwit-oss/tantivy) [[tantivy](https://crates.io/crates/tantivy)]  — 用Rust编写的马速全文搜索引擎库。 [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy)  — 用于安全地将任意字节序列重新解释为本机Rust类型的实用程序 
### Video

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar)  — 在直观的迭代器界面中包装一个独立的FFmpeg二进制文件。 [![Build Status](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml)

### Virtualization

* [beneills/quantum](https://github.com/beneills/quantum)  — 先进的铁锈量子计算机模拟器 
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime)  — WebAssembly的独立运行时 [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/)  — Crossvm-使Chrome操作系统能够在快速、安全的虚拟化环境中运行Linux应用 
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis)  — 用于illumos bhyve内核模块的基于Rust的用户空间程序 
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs)  — OS X上的硬件加速虚拟化 
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs)  — 独角兽CPU仿真器的Rust绑定 
### Web programming

See also [Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web)  — 客户端Web的货物子命令 
  * [leptos](https://github.com/leptos-rs/leptos)  — Leptos是一个全栈，同构的Rust web框架，利用细粒度的反应性来构建声明性用户界面。 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)
  * [sauron](https://github.com/ivanceras/sauron)  — 密切遵守Elm体系结构的客户端web框架。 
  * [seed](https://seed-rs.org/)  — 用于创建web应用程序的Rust框架 
  * [stdweb](https://crates.io/crates/stdweb)  — 客户端Web的标准库 
  * [yew](https://crates.io/crates/yew)  — 用于制作客户端web应用程序的Rust框架 
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust)  — [·libcurl](https:// curl.se/libcurl/) 绑定 
  * [async-graphql](https://github.com/async-graphql/async-graphql)  — 在Rust中实现的GraphQL服务器库 [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[yukikaze](https://crates.io/crates/yukikaze)]  — 美丽优雅的Yukikaze是基于hyper的小HTTP客户端库。 [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh)  — 用于发送HTTP请求的友好快速工具 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![Github actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)
  * [graphql-client](https://github.com/graphql-rust/graphql-client)  — 在Rust中键入，正确的GraphQL请求和响应。 [![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper)  — 一个HTTP实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest)  — 用于Rust的符合人体工程学的HTTP客户端。 
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web)  — 具有websocket支持的用于Rust的轻量级异步web框架 
  * [Anansi](https://github.com/saru-tora/anansi)  — 用于Rust的简单全栈web框架 
  * [branca](https://crates.io/crates/branca)  — 用于经过身份验证和加密的API令牌的Branca的纯Rust实现。 
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)]  — 一个快速、无样板的铁锈网络框架 
  * [danclive/sincere](https://github.com/danclive/sincere)  — 基于超多线程的Rust (稳定) 微web框架 
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt)  — Rust中的JSON Web令牌实现 
  * [Gotham](https://github.com/gotham-rs/gotham)  — 灵活的web框架，不会牺牲安全性，安全性或速度。 
  * [Graphul](https://github.com/graphul-rs/graphul)  — 用Rust编写的Express启发的web框架。 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust)  — 一个Iron web框架中间件 
  * [hyperium/hyper](https://github.com/hyperium/hyper)  — 一个HTTP实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Iron](https://github.com/iron/iron)  — 一种基于中间件的服务器框架 
  * [Juniper](https://github.com/graphql-rust/juniper)  — GraphQL Rust服务器库 
  * [miketang84/sapper](https://github.com/miketang84/sapper)  — 基于async hyper构建的轻量级web框架，以Rust语言实现。 
  * [Nickel](https://github.com/nickel-org/nickel.rs/)  — 灵感来自 [Express](http://expressjs.com/)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful)  — 用于Rust的RESTful web框架 
  * [poem-web/poem](https://github.com/poem-web/poem)  — 具有Rust编程语言的功能齐全且易于使用的web框架。 [![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rocket](https://github.com/SergioBenitez/Rocket)  — 火箭是铁锈的网络框架 (每晚)，重点是易用性、可表达性和速度 
  * [Rustless](https://github.com/rustless/rustless)  — 一个类似REST的API微框架，灵感来自 [Grape](https://github.com/ruby-grape/grape) and [Hyper](https://github.com/hyperium/hyper)
  * [Salvo](https://github.com/salvo-rs/salvo)  — 基于hyper和tokio的易于使用的webframework。 [![build build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir)  — 具有低级控制功能的渐进式web框架，没有痛苦。 
  * [seanmonstar/warp](https://github.com/seanmonstar/warp)  — 超简单，可组合的web服务器框架，可提高warp速度。 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http)  — 低级HTTP服务器库 
  * [tokio/axum](https://github.com/tokio-rs/axum)  — 使用Tokio、Tower和Hyper构建的人体工程学和模块化网络框架 [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille)  — Rust中的Web框架 
* Miscellaneous
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts)  — 旨在构建可维护的，精心设计的web应用程序的web框架。 
  * [causal-agent/scraper](https://github.com/causal-agent/scraper) [[scraper](https://crates.io/crates/scraper)]  — 使用CSS选择器的HTML解析和查询 [![Build Status](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
  * [hominee/dyer](https://github.com/hominee/dyer) [[dyer](https://crates.io/crates/dyer)]  — dyer专为可靠，灵活和快速的基于请求响应的服务而设计，包括数据处理，web爬网等，可提供一些友好，灵活，全面的功能，而不会影响速度。 
  * [juhaku/utoipa](https://github.com/juhaku/utoipa)  — 简单、快速、代码优先和编译时间生成的Rust的OpenAPI文档 [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)]  — 嵌入在应用程序中的授权策略引擎。 [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)]  — 类似于Python的BeautifulSoup的库，旨在实现快速简便的操作和查询HTML文档。 [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed)  — 将静态资产嵌入rust二进制的宏 
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)]  — Discord API的Rust库 
  * [softprops/openapi](https://github.com/softprops/openapi)  — 用于处理openapi规范文件的库 
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks)  — [[svix](https://crates.io/crates/svix)]-用于发送webhooks和验证签名的库。 
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[tbot](https://crates.io/crates/tbot)]  — 容易使酷炫的电报机器人生锈 [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/)  — 优雅的Rust电报机器人框架 [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)]  — 从HTML文档中提取有用数据的库，适用于网页抓取。 
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)]  — 一个HTTP反向代理。 [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs)  — 用铁锈书写的静态现场发生器 [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)]  — 来自markdown文件的静态站点生成器。 
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)]  — 内置所有内容的自以为是的静态站点生成器。 [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) [[blades](https://getblades.org/)]  — 炽热的快速死亡简单静态站点发生器。 
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)]  — 一个简单的、并行化的博客生成器。 
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs)  — 轻量级、事件驱动的防锈网络套接字 
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket)  — 用于处理WebSocket连接 (客户端和服务器) 的框架 
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs)  — 针对Rust的轻量级基于流的WebSocket实现 
  * [vi/websocat](https://github.com/vi/websocat)  — 用于与WebSockets交互的CLI，具有Netcat、Curl和Socat的功能。 
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs)  — 一个非常简单的用于Rust的urlshortener库。 [![CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry)  — 完全托管的软件包管理SaaS，对公共和私人货物/防锈注册中心 (以及许多其他注册中心) 具有一流的支持。有一个慷慨的免费层，也是完全免费的开源。 
* [Crates](https://crates.io)  — 铁锈/货物的官方公共登记处。 
* [w4/chartered](https://github.com/w4/chartered)  — 私人、经认证、许可的货物登记处 [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

* Benchmarks
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs)  — Rust实现 [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/)
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust)  — 由 [·朱莉娅·埃文斯提交 (https://twitter.com/@ b0rk) @ Rustconf 2016。 
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI)  — 由 [·尼古拉斯·马塔基斯 (https://github.com/nikomatsakis) @ C呈现现在2018 
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA)  — 由 [·迈克尔·加托齐 (https://github.com/mgattozzi) @ RustConf 2017呈现 
* [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust)  — 关于kandi的Rust库、作者、工具包、教程和学习资源的精选列表 
* Learning
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope)  — 编译时和运行时Rust的交互式可视化 
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming)  — 社区策划的关于铁锈的直播列表。 
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/)  — 愿意招募学员并教育他们有关生锈和编程的有用的Rust导师列表。 
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust)  — 在Rust中构建自己的Redis、Git、Docker或SQLite 
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/)  — 关于Rust基础知识的3天课程以及关于Android，裸金属Rust和并发的1天课程。提供英文、 [巴西葡萄牙文](https://google.github.io/compreley-rust/pt-BR/) 、 [韩文](https://google.github.io/compley-rust/ko/)。 
  * [Easy Rust](https://github.com/Dhghomon/easy_rust)  — 用简单的英语学习铁锈。 
  * [exercism.org](https://exercism.org/tracks/rust)  — 帮助您学习Rust新概念的编程练习。 
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/)  — 通过制作游戏来学习铁锈的实践指南 [Herbert Wolverson](https://github.com/thebracket/) (paid)
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust)  — 经过同行评审的文章/演讲/回购集，教授惯用的锈。 
  * [Learn Rust by 500 lines code](https://github.com/cuppar/rtd)  — 通过500行代码来学习Rust，从头开始构建Todo Cli应用程序。 
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)  — 通过实现几种不同类型的列表结构，深入探索Rust的内存管理规则。 
  * [Little Book of Rust Books](https://lborb.github.io/book/)  — 精心策划的铁锈书籍和操作方法清单。 
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust)  — 编程社区投票的推荐资源列表。 
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust)  — 一本介绍Rust语言的书。 
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)  — 一系列简单的示例，这些示例展示了使用Rust生态系统的板条箱完成常见编程任务的良好实践。 
  * [Rust for professionals](https://overexact.com/rust-for-professionals/)  — 为经验丰富的软件开发人员快速介绍Rust。 
  * [Rust Gym](https://github.com/warycat/rustgym)  — Rust中解决的大量编码面试问题。 
  * [Rust in Action](https://www.manning.com/books/rust-in-action)  — 使用Rust进行系统编程的动手指南 [Tim McNamara](https://github.com/timClicks) (paid)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e)  — 由 [Carol Nichols](https://github.com/carols10cents) and [Jake Goulding](https://github.com/shepmaster) (paid)
  * [Rust Language Cheat Sheet](https://cheats.rs/)
  * [Rust Online Courses at Classpert](https://classpert.com/search/rust)  — 来自Classpert在线课程搜索的Rust在线课程 (付费) 列表 
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/)  — 用越南语学习铁锈。 
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start)  — 专门用于回答以下问题的回购: “那么，Rust。我如何_start_？”。初学者只手工挑选资源和学习轨迹。 
  * [rust-learning](https://github.com/ctjhoa/rust-learning)  — 学习铁锈的有用资源集合 
  * [Rustlings](https://github.com/rust-lang/rustlings)  — 让你习惯阅读和编写Rust代码的小练习 
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS)  — 计算机科学课程，可帮助实践在Rust中获得的学术知识 
  * [stdx](https://github.com/brson/stdx)  — 首先学习这些板条箱作为std的扩展 
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/)  — 为在Rust中构建快速有效的程序奠定知识基础。 
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
* Podcasts
  * [New Rustacean](https://newrustacean.com)  — 关于学习生锈的播客 
  * [Rustacean Station](https://rustacean-station.org/)  — 为Rust创建播客内容的社区项目 
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps)  — 在Rust中构建后端服务器，服务和前端，以获取快速，可靠和可维护的应用程序。 
* [Rust Subreddit](https://www.reddit.com/r/rust/)  — 发布和讨论rust相关问题、文章和资源的subreddit (论坛) 
* [RustBooks](https://github.com/sger/RustBooks)  — 生锈的清单 
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* [RustViz](https://github.com/rustviz/rustviz)  — 从简单的Rust程序生成可视化效果，以帮助用户更好地理解Rust寿命和借用机制。 
## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
