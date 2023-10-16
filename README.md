# 真棒铁锈 [![build badge](https://github.com/rust-非官方/awesome-rust/actions/workflows/rust.yml/badge.svg？branch = main)](https://github.com/rust-非官方/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-非官方/awesome-rust/)
Rust代码和资源的精选列表。
如果您想贡献，请阅读 [此] (contribute.md)。

# # 目录
<!-- toc -->

- [Applications](#applications) 应用
  * [Audio and Music](#audio-and-music) 音频和音乐
  * [Cryptocurrencies](#cryptocurrencies) 加密货币
  * [Database](#database) 数据库
  * [Emulators](#emulators) 仿真器
  * [Games](#games) 游戏
  * [Graphics](#graphics) 图形
  * [Image processing](#image-processing) 图像处理
  * [Industrial automation](#industrial-automation) 工业自动化
  * [Observability](#observability) 可观察性
  * [Operating systems](#operating-systems) 操作系统
  * [Payments](#payments) 付款
  * [Productivity](#productivity) 生产力
  * [Routing protocols](#routing-protocols) 路由协议
  * [Security tools](#security-tools) 安全工具
  * [Simulation](#simulation) 仿真
  * [Social networks](#social-networks) 社交网络
  * [System tools](#system-tools) 系统工具
  * [Task scheduling](#task-scheduling) 任务调度
  * [Text editors](#text-editors) 文本编辑器
  * [Text processing](#text-processing) 文本处理
  * [Utilities](#utilities) 公用事业
  * [Video](#video) 视频
  * [Virtualization](#virtualization) 虚拟化
  * [Web](#web) Web
  * [Web Servers](#web-servers) 网络服务器
- [Development tools](#development-tools) 开发工具
  * [Build system](#build-system) 构建系统
  * [Debugging](#debugging) 调试
  * [Deployment](#deployment) 部署
  * [Embedded](#embedded) 嵌入式
  * [FFI](#ffi) FFI
  * [Formatters](#formatters) 格式化器
  * [IDEs](#ides) IDEs
  * [Profiling](#profiling) 剖析
  * [Services](#services) 服务
  * [Static analysis](#static-analysis) 静态分析
  * [Testing](#testing) 测试
  * [Transpiling](#transpiling) 换位
- [Libraries](#libraries) 图书馆
  * [Artificial Intelligence](#artificial-intelligence) 人工智能     [遗传算法](# 遗传算法) [机器学习](# 机器学习) [OpenAI](# openai)
  * [Astronomy](#astronomy) 天文学
  * [Asynchronous](#asynchronous) 异步
  * [Audio and Music](#audio-and-music-1) 音频和音乐
  * [Authentication](#authentication) 身份验证
  * [Automotive](#automotive) 汽车
  * [Bioinformatics](#bioinformatics) 生物信息学
  * [Caching](#caching) 缓存
  * [Cloud](#cloud) 云
  * [Command-line](#command-line) 命令行
  * [Compression](#compression) 压缩
  * [Computation](#computation) 计算
  * [Concurrency](#concurrency) 并发
  * [Configuration](#configuration) 配置
  * [Cryptography](#cryptography) 密码学
  * [Data processing](#data-processing) 数据处理
  * [Data streaming](#data-streaming) 数据流
  * [Data structures](#data-structures) 数据结构
  * [Data visualization](#data-visualization) 数据可视化
  * [Database](#database-1) 数据库
  * [Date and time](#date-and-time) 日期和时间
  * [Distributed systems](#distributed-systems) 分布式系统
  * [Domain driven design](#domain-driven-design) 域驱动设计
  * [eBPF](#ebpf) eBPF
  * [Email](#email) 电子邮件
  * [Encoding](#encoding) 编码
  * [Filesystem](#filesystem) 文件系统
  * [Finance](#finance) 金融
  * [Functional Programming](#functional-programming) 函数式编程
  * [Game development](#game-development) 游戏开发
  * [Geospatial](#geospatial) 地理空间
  * [Graph algorithms](#graph-algorithms) 图算法
  * [Graphics](#graphics-1) 图形
  * [GUI](#gui) 图形用户界面
  * [Image processing](#image-processing-1) 图像处理
  * [Language specification](#language-specification) 语言规范
  * [Logging](#logging) 日志记录
  * [Macro](#macro) 宏
  * [Markup language](#markup-language) 标记语言
  * [Mobile](#mobile) 移动
  * [Network programming](#network-programming) 网络编程
  * [Parsing](#parsing) 解析
  * [Peripherals](#peripherals) 外围设备
  * [Platform specific](#platform-specific) 特定平台
  * [Scripting](#scripting) 脚本
  * [Simulation](#simulation-1) 仿真
  * [System](#system) 系统
  * [Task scheduling](#task-scheduling-1) 任务调度
  * [Template engine](#template-engine) 模板引擎
  * [Text processing](#text-processing-1) 文本处理
  * [Text search](#text-search) 文本搜索
  * [Unsafe](#unsafe) 不安全
  * [Video](#video-1) 视频
  * [Virtualization](#virtualization-1) 虚拟化
  * [Web programming](#web-programming) 网络编程
- [Registries](#registries) 登记处
- [Resources](#resources) 资源
- [License](#license) 许可证
<!-- tocstop -->

# # 应用程序
另请参见 [Rust - Production](https:// rust-lang.org/production) 在生产中运行Rust的组织。

* [alacritty](https://github.com/alacritty/alacritty) 敏捷 — 一种跨平台的GPU增强型终端仿真器
* [Arti](https://gitlab.torproject.org/tpo/core/arti) Arti — 在Rust中实现Tor。(到目前为止，它不是一个非常完整的客户端，但请注意这个空间!)[![Crates.io](https:// img.shields.io/crates/v/arti.svg)](https:// crates.io/crates/arti)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) asm-cli-rust — 用rust编写的交互式装配外壳
* [broot](https://github.com/Canop/broot) 布鲁特 一种查看和导航目录树的新方法 (获取目录的概述，甚至是一个大目录; 找到一个目录，然后对其进行 “cd”; 在搜索时永远不会丢失文件层次结构的轨道; 操作您的文件，...)，进一步阅读 [dystroy.org/broot](https://dystroy.org/broot/) [![最新版本](https:// img.shields.io/crates/v/broot.svg)](https:// crates.io/crates/broot)
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) cloudflare/boringtun — 用户空间WireGuard VPN实现 [![构建徽章](https:// img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https:// crates.io/crates/boringtun)
* [datafusion](https://github.com/apache/arrow-datafusion) 数据融合 — 阿帕奇箭头数据融合和弩炮查询引擎
* [denoland/deno](https://github.com/denoland/deno) denoland/deno — 使用V8，Rust和Tokio构建的安全JavaScript/TypeScript运行时 [![构建状态] (https://github.com/denoland/deno/workflows/ci/badge.svg？branch=master&event=push)](https://github.com/denoland/deno/actions)
* [doprz/dipc](https://github.com/doprz/dipc) doprz/dipc — 使用您喜欢的调色板/主题转换您喜欢的图像和壁纸 [![crates.io](https:// img.shields.io/crates/v/dipc)](https:// crates.io/crates/dipc)
* [Factotum](https://github.com/snowplow/factotum) Factotum — [一个以编程方式运行数据管道的系统](https://snowplow.io/blog/introduct防-factotum-data-pipeline-runner/)
* [fcsonline/drill](https://github.com/fcsonline/drill) fcsonline/drill — 受Ansible语法启发的HTTP负载测试应用程序
* [fend](https://github.com/printfn/fend) 挡风板 - 任意精度单位感知计算器 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
* [Fractalide](https://github.com/fractalide/fractalide) Fractalide — 简单锈微服务
* [habitat](https://github.com/habitat-sh/habitat) 生境 — 由Chef创建的用于构建，部署和管理应用程序的工具。
* [Herd](https://github.com/imjacobclark/Herd) 牛群 — 一个实验性的HTTP负载测试应用程序
* [hickory-dns](https://crates.io/crates/trust-dns) 山核桃-dns — DNS服务器 [![构建状态](https://github.com/hickory-dns/workflows/test/badge.svg？branch = main)](https://github.com/hickory-dns/actions？查询 = 工作流: 测试)
* [innernet](https://github.com/tonarino/innernet) 内网 - 在引擎盖下使用Wireguard的覆盖或专用网状网络
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) jedisct1/flowgger — 快速、简单、轻便的数据收集器
* [kalker](https://github.com/PaddiM8/kalker) kalker - 一种科学计算器，支持类似数学的语法，包含用户定义的变量、函数、推导、积分和复数。跨平台WASM支持 [![构建状态](https://github.com/PaddiM8/kalker/工作流/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kytan](https://github.com/changlan/kytan) kytan — 高性能对等VPN
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) linkerd/linkerd2-proxy — Kubernetes的超轻服务网格。
* [MaidSafe](https://github.com/maidsafe) MaidSafe — 一个分散的平台。
* [mdBook](https://github.com/rust-lang/mdBook) mdBook — 用于从markdown文件创建图书的命令行实用程序 [![构建状态](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg？branch = master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) 尼科曼/eidolon — 适用于linux和macosx的steam和无drm游戏注册表和启动器
* [notty](https://github.com/withoutboats/notty) notty — 一种新型终端
* [Pijul](https://pijul.org) 皮朱尔 — 一种基于补丁的分布式版本控制系统
* [Rio](https://github.com/raphamorim/rio) 里约 - 由WebGPU提供支持的硬件加速GPU终端仿真器，专注于在台式机和浏览器中运行。
* [rx](https://github.com/cloudhead/rx) rx — Vi启发现代像素艺术编辑器
* [Servo](https://github.com/servo/servo) 伺服 — 一个原型网络浏览器引擎
* [shoes](https://github.com/cfal/shoes) 鞋子 - 一种多协议代理服务器
* [shuttle](https://github.com/shuttle-hq/shuttle) 穿梭机 — 为生锈而建造的无服务器平台
* [Sniffnet](https://github.com/GyulyVGC/sniffnet) 嗅探网 — 跨平台应用程序轻松监控您的网络流量 [![build badge](https:// img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?徽标 = github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https:// img.shields.io/crates/v/sniffnet?logo = rust)](https:// crates.io/crates/sniffnet)
* [SWC](https://github.com/swc-project/swc) SWC — 超快打字稿/JavaScript编译器
* [tiny](https://github.com/osa1/tiny) 微小的 — 终端IRC客户端
* [wasmer](https://github.com/wasmerio/wasmer) wasmer — 支持WASI和Emscripten的安全快速的WebAssembly运行时 [![构建状态] (https://github.com/wasmerio/wasmer/workflows/build/badge.svg？style= 平面)](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld) 焊缝 — 全假REST API生成器
* [wezterm](https://github.com/wez/wezterm) Wez术语 — 一种GPU加速跨平台终端仿真器和多路复用器
* [zellij](https://github.com/zellij-org/zellij) zellij — 包括电池的终端多路复用器 (工作区)

### 音频和音乐

* [enginesound](https://github.com/DasEtwas/enginesound) enginesound — GUI和命令行应用程序，用于程序生成半逼真的引擎声音。具有深入的配置，可变的采样率和频率分析窗口。
* [figsoda/mmtc](https://github.com/figsoda/mmtc) 无花果/mmtc [[mmtc](https:// crates.io/crates/mmtc)] -最小mpd终端客户端，旨在简单但高度可配置 [![build-badge](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)
* [Glicol](https://github.com/chaosprint/glicol) Glicol — 用Rust编写的面向图形的实时编码语言，用于在浏览器中进行协作音乐。
* [ncspot](https://github.com/hrkfdn/ncspot) ncspot - 跨平台ncurses Spotify客户端，灵感来自ncmpc等。[![构建徽章](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions？query=workflow: 构建)
* [Polaris](https://github.com/agersant/polaris) 北极星 — 音乐流应用程序。
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) Spotify TUI — 用Rust写的终端的Spotify客户端。![持续集成](https://github.com/Rigellute/spotify-tui/工作流/持续集成/徽章.svg？branch = master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd) Spotifyd — 作为UNIX守护进程运行的开源Spotify客户端。![持续集成](https://github.com/Spotifyd/spotifyd/workflows/Continuous集成/badge.svg？branch = master)
* [WhatBPM](https://github.com/sergree/whatbpm) WhatBPM — 电子舞曲制作人每天静态生成的信息资源。使用Beatport和Spotify等公开数据，为每种EDM类型提供最常用值的每日分析: 节奏，键，根音符等。![持续集成](https://github.com/sergree/whatbpm/actions/workflows/website_build_deploy.yml/badge.svg？branch = main)

### 加密货币

* [artemis](https://github.com/paradigmxyz/artemis) 阿耳特弥斯 - 一个简单、模块化、快速的框架，用于在Rust中编写MEV机器人。
* [beerus](https://github.com/keep-starknet-strange/beerus) 比勒斯 - Beerus是一个不信任的StarkNet轻客户，⚡超快⚡由铁锈提供动力[![GitHub工作流状态](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml)
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) 比特币Satoshi的愿景 [[sv](https://crates.io/crates/sv)] -用于处理比特币SV的Rust库。
* [cairo](https://github.com/starkware-libs/cairo) 开罗 - Cairo是第一个用于创建通用计算的可证明程序的图灵完备语言。这也是 [StarkNet](https:// www.starknet.io/en) 的母语，使用STARK证明的zk-rollup![GitHub工作流状态](https:// img.shields.io/github/Workflow/Status/starkware-libs/cairo/CI？style = flat-square & logo = github)
* [cairo-vm](https://github.com/lambdaclass/cairo-vm) 开罗-vm — 开罗虚拟机的Rust实现 [![rust](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml)
* [ChainX](https://github.com/chainx-org/ChainX) 链子 — Polkadot上完全分散的链间加密资产管理。
* [CITA](https://github.com/citahub/cita) CITA — 面向企业用户的高性能区块链内核
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) coinbase-pro-rs — Rust中的Coinbase pro客户端，支持同步/异步/websocket
* [Diem](https://github.com/diem/diem) Diem — Diem的使命是建立一个简单的全球货币和金融基础设施，赋予数十亿人权力。
* [electrumrs](https://github.com/romanz/electrs) 电子 — 在Rust中高效地重新实现Electrum服务器。
* [ethabi](https://github.com/rust-ethereum/ethabi) ethabi - 对智能合约调用进行编码和解码。
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) ethaddrgen — 自定义以太坊虚荣地址生成器铁锈制造
* [ethers-rs](https://github.com/gakonst/ethers-rs) 醚-rs - 在Rust中完成以太坊和Celo库和钱包实现。![构建状态](https://github.com/gakonst/醚-rs/工作流/测试/badge.svg)
* [etk](https://github.com/quilt/etk) etk - etk是用于编写，读取和分析EVM字节码的工具的集合。
* [Forest](https://github.com/ChainSafe/forest) 森林 - Rust Filecoin实现 [![构建状态](https:// img.shields.io/circlecl/Build/gh/ChainSafe/forest/main？branch = master)](https://app.circleci.com/pipelines/github/ChainSafe/forest？branch=main)
* [Foundry](https://github.com/foundry-rs/foundry) 铸造厂 - Foundry是一个用Rust编写的快速，可移植和模块化的以太坊应用程序开发工具包。[构建状态](https:// img.shields.io/github/workflow/Status/foundry-rs/foundry/test？style = flat-square)
* [Grin](https://github.com/mimblewimble/grin/) 咧嘴笑 — MimbleWimble协议的演变
* [hdwallet](https://github.com/jjyr/hdwallet) hdwallet [[hdwallet](https://crates.io/crates/hdwallet)]-BIP-32高清钱包相关密钥派生实用程序。
* [Holochain](https://github.com/holochain/holochain) 全息链 — 可扩展的P2P替代区块链，适用于您一直想要构建的所有分布式应用程序。[![检测关键检查失败](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
* [ibc-rs](https://github.com/informalsystems/hermes) ibc-rs - [区块链间通信](https://ibc.cosmos.net工作/) 协议的Rust实现
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) infincia/bip39-rs [[bip39](https://crates.io/crates/bip39)] -bip39的Rust实现
* [interBTC](https://github.com/interlay/interbtc) interBTC — 无信任和完全去中心化的比特币桥到波尔卡多特和草间。
* [Joystream](https://github.com/Joystream/joystream) Joystream — 用户管理的视频平台
* [Lighthouse](https://github.com/sigp/lighthouse) 灯塔 — Rust以太坊共识层 (CL) 客户端 [![构建状态](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg？branch = master)](https://github.com/sigp/lighthouse/actions)
* [madara](https://github.com/keep-starknet-strange/madara) madara - Kaioshin是一个⚡超快⚡Starknet测序仪，基于底物并用Rust编写.[![GitHub工作流状态](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml)
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) mev-检查-rs - 生锈的Ethereum MEV检查员
* [near/nearcore](https://github.com/near/nearcore) 近/近核心 — 面向低端移动设备的分散式智能合约平台。
* [Nervos CKB](https://github.com/nervosnetwork/ckb) Nervos CKB — Nervos CKB是一个公共无权限区块链，是Nervos网络的常识层。
* [Nimiq](https://github.com/nimiq/core-rs) Nimiq — Nimiq节点的Rust实现
* [opensea-rs](https://github.com/gakonst/opensea-rs) opensea-rs - Rust绑定和CLI到Opensea API和合同。
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) 奇偶校验-比特币 — 平价比特币客户端
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) Phala-网络/phala-区块链 — 基于英特尔SGX和基板的机密智能合约区块链
* [Polkadot](https://github.com/paritytech/polkadot) 波尔卡多 — 具有池化安全性的异构多链技术
* [revm](https://github.com/bluealloy/revm) revm - 革命机器 (Revolutionary Machine，revm) 是用rust编写的快速以太坊虚拟机。
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) rust-比特币 — 库支持去/序列化，解析和执行与比特币相关的数据结构和网络消息。
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) 铁锈-闪电 [![板条箱](https:// img.shields.io/crates/v/lightning.svg？logo = rust)](https:// crates.io/crates/lightning) -用Rust编写的比特币闪电库主板条箱 “闪电” 不处理网络、持久性或任何其他I/O。因此，它是与运行时无关的，但是用户必须在链接板条箱上实现基本的网络逻辑，链交互和磁盘存储.po。
* [sigma-rust](https://github.com/ergoplatform/sigma-rust) 西格玛-铁锈 — ErgoTree解释器和钱包相关功能的Rust实现
* [Solana](https://github.com/solana-labs/solana) 索拉纳 — 使用历史证明的令人难以置信的快速、高度可扩展的区块链。
* [Substrate](https://github.com/paritytech/substrate) 基材 — 用Rust编写的通用模块化区块链模板
* [Sui](https://github.com/MystenLabs/sui) Sui — 具有高吞吐量、低延迟的下一代智能合约平台，以及由Move编程语言提供支持的面向资产的编程模型。
* [svm-rs](https://github.com/alloy-rs/svm-rs) svm-rs - Solidity-编译器版本管理器
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) tendermint-rs - Tendermint区块链数据结构和客户端的Rust实现
* [wagyu](https://github.com/howardwu/wagyu) wagyu [[wagyu](https://crates.io/crates/wagyu)] -用于生成加密货币钱包的Rust库
* [zcash](https://github.com/zcash/zcash) zcash — Zcash是 “Zerocash” 协议的实现。

### 数据库

* [Atomic-Server](https://github.com/atomicdata-dev/atomic-server/) 原子服务器 [[atomic-server](https:// crates.io/crates/atomic_server)] -具有实时更新、动态索引和易于使用的用于CMS目的的GUI的NoSQL图形数据库。[![发布](https://github.com/atomicdata_dev/atomic-server/actions/workflows/docker.yml/badge.svg)](https://github.com/atomicdata_dev/atomic-server/actions/workflows/docker.yml)
* [CozoDB](https://github.com/cozodb/cozo) 科佐布 - 使用Datalog并专注于图形数据和算法的事务性关系数据库。时间旅行能力，而且快![![GitHub工作流状态](https:// img.shields.io/github/actions/Workflow/Status/cozodb/cozo/build.yml？分支 = main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
* [Databend](https://github.com/datafuselabs/databend) Databend - 具有云原生架构的现代实时数据处理和分析DBMS [![发布](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* [DB3 Network](https://github.com/dbpunk-labs/db3) DB3网络 — DB3是一个社区驱动的区块链layer2分散数据库网络![GitHub工作流状态 (带事件)](https:// img.shields.io/github/actions/Workflow/Status/dbpunk-labs/db3/ci.yml？branch = main & style = flat-square)
* [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb) erikgrinaker/toydb — Rust中的分布式sql数据库，作为学习项目编写。
* [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/) GreptimeDB - 支持PromQL/SQL/Python的开源云原生分布式时序数据库。[![CI](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)
* [indradb](https://crates.io/crates/indradb) indradb — 基于Rust的图数据库
* [Lucid](https://github.com/lucid-kv/lucid) 清醒 — 高性能和分布式KV存储可通过HTTP API访问。[![构建状态](https://github.com/清醒-kv/清醒/工作流/清醒/徽章.svg？分支 = 主)](https://github.com/清醒-kv/清醒/行动？工作流 = 清醒)
* [Materialize](https://github.com/MaterializeInc/materialize) 物化 - 由及时数据流提供支持的流式SQL数据库: heavy_dollar_sign: [![构建状态](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg？branch = main)](https://buildkite.com/materialize/tests)
* [Neon](https://github.com/neondatabase/neon) 霓虹灯 无服务器Postgres。我们将存储和计算分开，以提供自动缩放，分支和无底存储。
* [noria](https://github.com/mit-pdos/noria) noria [[noria](https://crates.io/crates/noria)] -用于web应用程序后端的动态更改部分状态的数据流
* [ParityDB](https://github.com/paritytech/parity-db) ParityDB — 快速可靠的数据库，针对读取操作进行了优化
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) PumpkinDB — 事件源数据库引擎
* [Qdrant](https://github.com/qdrant/qdrant) Qdrant - 具有扩展过滤支持的开源矢量相似性搜索引擎 [![测试](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) RisingWaveLabs/RisingWave - 云中的下一代流式数据库 [![CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg？branch=main)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) seppo0010/rsedis — Rust中的Redis重新实现
* [Skytable](https://github.com/skytable/skytable) Skytable — 多模型NoSQL数据库![GitHub工作流状态](https:// img.shields.io/github/Workflow/Status/skytable/Tests？style = flat-square)
* [sled](https://crates.io/crates/sled) 雪橇 — A (测试版) 现代嵌入式数据库 [![构建状态] (https://github.com/spacejam/sled/workflows/Rust/badge.svg？branch=master)](https://github.com/spacejam/sled/actions？workflow=Rust)
* [SurrealDB](https://github.com/surrealdb/surrealdb) SurrealDB — 可扩展的分布式文档图形数据库 [![构建状态](https:// img.shields.io/github/workflow/Status/surrealdb/持续集成/main)](https://github.com/surrealdb/surrealdb/actions)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) 终端db - 开源图形数据库和文档存储 [![构建状态](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg？branch = master)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv) tikv — Rust [![构建状态](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/) 中的分布式KV数据库
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) vorot93/libmdbx-rs [[Mdbx-sys](https://crates.io/crates/mdbx-sys)] -用于mdbx的Rust绑定，一个 “快速、紧凑、强大、嵌入式、事务性键值数据库，具有许可许可证”。这是mozilla/lmdb-rs的一个分支，带有补丁，使其与libmdbx一起工作。
* [WooriDB](https://github.com/naomijub/wooridb) WooriDB - 受Crux和Datomic启发的通用时间序列数据库。

### 仿真器
另请参阅 [crates匹配关键字 'emulator'](https:// crates.io/keywords/emulator)。

* 芯片-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) 科林伯哈特/wasm-rust-chip8 — 用铁锈编写的WebAssembly CHIP-8仿真器
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) starrhorne/chip8-rust — 另一个rust chip8仿真器
* 准将64
  * [kondrak/rust64](https://github.com/kondrak/rust64) kondrak/rust64 —
* Flash Player
  * [Ruffle](https://github.com/ruffle-rs/ruffle) 荷叶边 — Ruffle是一个用Rust编程语言编写的Adobe Flash Player模拟器。Ruffle使用WebAssembly同时面向桌面和web。[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) Gekkio/月眼-gb —
  * [joamag/boytacean](https://github.com/joamag/boytacean) joamag/boytacean — 使用WebAssembly在网络上运行的Rust编写的GameBoy颜色模拟器。
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) mohanson/gameboy — 全功能跨平台GameBoy模拟器。永远的男孩!。
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) mvdnes/rboy —
* Gameboy前进
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) michelhe/rustboyadvance-ng - RustboyAdvance-ng是具有桌面，android和 [WebAssembly](https:// michelhe.github.io/rustboyadvance-ng/) 支持的Gameboy高级模拟器。[![生成徽章](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg？branch = master)](https://github.com/michelhe/rustboyadvance-ng/actions？query = workflow:Deploy)
* 游戏制造者
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) OpenGMK — OpenGMK是专有的GameMaker Classic引擎的现代重写，提供了完整的runner源端口，反编译器，tassing框架以及用于自己使用gamedata的库。
* 英特尔8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) mohanson/i8080 — 英特尔8080 cpu仿真器by Rust
* iOS
  * [touchHLE](https://github.com/hikari-no-yume/touchHLE) touchHLE — 适用于iPhone OS应用程序的高级模拟器
* iPod
  * [clicky](https://github.com/daniel5151/clicky) clicky — 一个点击轮iPod模拟器 (WIP)
* NES
  * [koute/pinky](https://github.com/koute/pinky) koute/pinky —
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes) pcwalton/链轮
* 任天堂DS
  * [dust](https://github.com/kelpsyberry/dust) 粉尘 — 用Rust编写的任天堂DS模拟器
* PlayStation 4
  * [Obliteration](https://github.com/obhq/obliteration) 湮灭 — 用Rust编写的实验性PS4模拟器，适用于Windows，macOS和Linux [![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
* ZX光谱
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) rustzx/rustzx — [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### 游戏
另请参阅 [用活塞制作的游戏](https://github.com/PistonDevelopers/piston/wiki/用活塞制作的游戏)。

* [citybound](https://github.com/citybound/citybound) 城市 — 你应得的城市模拟
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) cristicbz/rust-doom — Doom的渲染器可能会发展成为可玩游戏
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) doukutsu-rs — 洞穴故事引擎的Rust重新实现，并进行了一些增强。
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) garkimasera/生锈-废墟 — 具有像素艺术的可扩展开放世界流氓游戏
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) 大猩猩-devs/ferium — Ferium是一个快速且功能丰富的CLI程序，用于从Modrinth，CurseForge和GitHub版本以及modpacks和CurseForge下载和更新Minecraft mods![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg？branch = main)
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) lifthrasiir/angolmois-rust — 支持BMS格式的简约音乐视频游戏
* [maras-archive/rsnake](https://github.com/maras-archive/rsnake) maras-存档/rsnake — 铁锈写的蛇。
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi) mtkennerly/ludusavi — Pc游戏的备份工具保存 [![build badge](https:// img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?徽标 = github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![crate](https:// img.shields.io/crates/v/ludusavi?徽标 = 铁锈)](https:// crates.io/crates/ludusavi)
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) ozkriff/zemeroth — 一个小型的2D回位六边形策略游戏
* [rhex](https://github.com/dpc/rhex) rhex — 六角ascii roguelike
* [rsaarelm/magog](https://github.com/rsaarelm/magog) rsaarelm/magog — Rust中的roguelike游戏
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) SoftbearStudios/mk48 — Mk48.io是一款在线多人海军战斗游戏
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) swatteau/sokoban-rs — 一个索科班的实现
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) thetawavegame/thetawave-legacy - 一款太空射击游戏，致力于成为新游戏开发人员做出首次贡献的切入点。![构建徽章](https://github.com/thetawavegame/thotavewa-legacy/actions/workflows/ci.yml/badge.svg？branch = master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) Thinkofname/rust-quake — 铁锈中的地震地图渲染器
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) ttyperacer/终端-typeracer - 为终端编写的单人打字测试游戏
* [Veloren](https://gitlab.com/veloren/veloren) Veloren — 一个开放的世界，开源多人体素RPG游戏目前在alpha开发中 [![构建徽章](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [Zone of Control](https://github.com/ozkriff/zoc) 控制区 — 基于回合的六边形策略游戏

### 图形

* [dps/rust-raytracer](https://github.com/dps/rust-raytracer) dps/rust-raytracer - 一个非常简单的raytracer的实现，基于一个周末的光线跟踪，由Peter Shirley在Rust。
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) ivanceras/svgbob — 将ASCII图转换为SVG图形
* [KaminariOS/rustracer](https://github.com/KaminariOS/rustracer) KaminariOS/rustracer — 一种基于Vulkan光线跟踪的PBR glTF 2.0渲染器，用Rust编写。
* [Limeth/euclider](https://github.com/Limeth/euclider) Limeth/euclider — 一种实时4D中央处理器射线跟踪器
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) RazrFalcon/resvg — 一个SVG渲染库。
* [rodrigorc/papercraft](https://github.com/rodrigorc/papercraft) rodrigorc/papercraft - 一个工具来解开3D模型，并用剪刀和胶水在纸上创建它们。
* [rustq/vue-skia](https://github.com/rustq/vue-skia) rustq/vue-skia — 基于Skia的2d图形vue渲染库。它基于Rust来实现软件光栅化来执行渲染。
* [turnage/valora](https://crates.io/crates/valora) 周转/valora — 一个生成美术的图书馆![铁锈] (https://github.com/turnage/valora/workflows/Rust/badge.svg？branch=master)
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) Twinklebear/tray_rust — 射线示踪剂

### 图像处理

* [Imager](https://github.com/imager-io/imager) 成像仪 — 自动图像优化。
* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) shssoichiro/oxipng [[oxipng](https:// crates.io/crates/oxipng)] -用Rust编写的多线程PNG优化器。[![构建状态](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions？query=branch: master) [![版本](https:// img.shields.io/crates/v/oxipng.svg)](https:// crates.io/crates/oxipng)

### 工业自动化

* [locka99/opcua](https://github.com/locka99/opcua) locka99/opcua — 纯锈 [OPC UA](https://opcfoundation.org/about/opc-技术/opc-ua/) 库。
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) slowtec/tokio-modbus — 基于 [tokio](https:// tokio.rs) 的 [modbus](https://modbus.org) 库。

### 可观察性

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino) avito-tech/bioyino — 高性能可扩展StatsD兼容服务器
* [OpenTelemetry](https://crates.io/crates/opentelemetry) 开放遥测术 — OpenTelemetry提供一组api、库、代理和收集器服务，用于从应用程序捕获分布式跟踪和指标。您可以使用Prometheus、Jaeger和其他可观察性工具来分析它们。[![GitHub操作CI](https://github.com/开放遥测-铁锈/工作流/CI/badge.svg？分支 = 主)](https://github.com/开放遥测-铁锈/操作？查询 = 工作流: CI分支: 主)
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) Quickwit-oss/quickwit - 云原生和高成本效益的日志管理搜索引擎。[![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg？branch = main)](https://github.com/quickwit-oss/quickwit/actions？query = workflow:CI)
* [Scaphandre](https://github.com/hubblo-org/scaphandre) Scaphandre - 功耗监控代理，用于跟踪主机和每个服务的功耗，并能够设计系统和应用程序以实现更大的可持续性。设计适合任何监控工具链 (已经支持普罗米修斯，warp10，黎曼...)。
* [vectordotdev/vector](https://github.com/vectordotdev/vector) 向量/向量 — 高性能、日志、度量和事件路由器。

### 操作系统
另请参见 [用Rust编写的操作系统的比较](https://github.com/flosse/rust-os-比较)。
* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS) 0x59616e/SteinsOS  — 用于armv8-a架构的操作系统。
* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero) 安迪-Python-程序员/aero — 遵循单片内核设计的现代类unix操作系统。
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) 氧化还原-os/氧化还原 —
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) thepowersgang/rust_os —
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) 忒修斯-os/忒修斯 — 在纯Rust中从头开始编写的安全语言，单地址空间和单特权级别操作系统- [![build badge](https:// img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label = docs build)](https:// theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock) tock/tock — 用于基于Cortex-M的微控制器的安全嵌入式操作系统

### 付款

* [hyperswitch](https://github.com/juspay/hyperswitch) 超级开关 — 一个开源支付协调器，让您与多个支付处理器连接和路由支付流量毫不费力，所有与一个单一的API集成![GitHub last commit](https:// img.shields.io/github/last-commit/juspay/hyperswitch?style = flat-square)

### 生产力

* [Bartib](https://github.com/nikolassv/bartib) 巴提布 [[Bartib](https://crates.io/crates/bartib)] -命令行的简单时间跟踪器 [![测试] (https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg？branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [espanso](https://github.com/espanso/espanso) espanso — 用Rust[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg？branch=dev&event=push)] 编写的跨平台文本扩展器 (https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka) 尤里卡 — 一个CLI工具，可以在不离开终端的情况下输入和存储您的想法
* [Furtherance](https://github.com/lakoliu/Furtherance) Furtherance - 使用Rust和GTK4构建的时间跟踪应用程序
* [illacloud/illa](https://github.com/illacloud/illa) illacloud/illa [[ILLA云](https://www.illacloud.com/)] -用铁锈编写的低代码内部工具生成器。
* [LLDAP](https://github.com/lldap/lldap) LLDAP - 用于身份验证的简化LDAP接口。
* [pier-cli/pier](https://github.com/pier-cli/pier) 码头-cli/码头 — 用于管理 (添加，搜索元数据等) 所有单线，脚本，工具和cl的中央存储库

### 路由协议

* [Holo](https://github.com/rwestphal/holo) 全息图像 - Holo是一套路由协议，旨在支持大规模和自动化驱动的网络
* [RustyBGP](https://github.com/osrg/rustybgp) RustyBGP - 用Rust编程语言实现的BGP

### 安全工具

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) AFLplusplus/LibAFL - 先进的模糊库-插槽你的Fuzzer一起生锈!跨内核和机器扩展。适用于Windows、Android、MacOS、Linux、no_std等。[![构建和测试](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [cargo-audit](https://crates.io/crates/cargo-audit) 货物-审计 - 审计货物。锁定有安全漏洞的板条箱
* [cargo-auditable](https://crates.io/crates/cargo-auditable) cargo-可审计 - 使生产锈二进制文件可审计
* [cargo-crev](https://crates.io/crates/cargo-crev) 货舱-crev - 货物 (Rust) 包裹管理器的密码可验证代码审查系统
* [cargo-deny](https://crates.io/crates/cargo-deny) 货舱-拒绝 - 帮助您管理大型依赖关系图的货物插件
* [Cherrybomb](https://github.com/blst-security/cherrybomb) 樱桃炸弹 - 使用CLI工具停止半途而废的API规范，该工具可通过验证API规范来帮助您避免未定义的用户行为。
* [cotp](https://github.com/replydev/cotp) cotp - 具有导入功能的可信、加密、命令行TOTP/HOTP身份验证器应用程序。
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) epi052/feroxbuster - 用Rust编写的一种简单、快速、递归的内容发现工具 (
* [Inspektor](https://github.com/inspektor-dev/inspektor) Inspektor - 用于实施访问策略的数据库协议感知代理
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) kpcyrd/authoscope — 一种脚本网络认证破解器
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) kpcyrd/rshijack — 一个TCP连接劫机者，shijack的rust rewrite
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) kpcyrd/sn0int — 一个半自动OSINT框架和包管理器
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) kpcyrd/sniffglue — 一种安全的多线程数据包嗅探器
* [ObserverWard](https://github.com/0x727/ObserverWard) 观察员 — 基于社区的网络技术分析工具。
* [ripasso](https://github.com/cortex/ripasso/) 里帕索 — 一个密码管理器，与pass兼容的文件系统
* [rustscan/rustscan](https://github.com/RustScan/RustScan) rustscan/rustscan — 使用此端口扫描工具使Nmap更快 [![构建徽章](https://github.com/RustScan/RustScan/workflows/Continuous集成/badge.svg？branch = master)](https://github.com/RustScan/RustScan/actions？query=workflow: “持续集成”)

### 模拟

* [hEngine](https://github.com/hashintel/hash/tree/main/apps/engine) hEngine - Rust实现的计算仿真引擎，支持基于大规模代理的建模，仿真逻辑用JavaScript和Python编写。

### 社交网络

* 乳齿象
  * [Rustodon](https://github.com/rustodon/rustodon) Rustodon - Rust中与乳齿象兼容的ActivityPub-讲服务器

### 系统工具

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) ajeetdsouza/zoxide — 学习您的习惯的 “cd” 的快速替代品 [![发布](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [Alonely0/Voila](https://github.com/Alonely0/Voila) Alonely0/Voila — Voila是通过CLI工具启动的特定于域的语言，用于以快速可靠的方式大量操作文件和目录。[![Linux构建](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/瞧/动作/工作流/mac-ci.yml/badge.svg)](https://github.com/Alonely0/瞧/动作/工作流/mac-ci.yml) [![Windows build](https://github.com/Alonely0/瞧/操作/工作流/windows-ci.yml/badge.svg)](https://github.com/Alonely0/瞧/操作/工作流/windows-ci.yml)
* [atuin](https://github.com/atuinsh/atuin) atuin [[atuin](https://crates.io/crates/atuin)]-Atuin用SQLite数据库替换您现有的shell历史记录，并为您的命令记录其他上下文。此外，它还通过Atuin服务器提供了计算机之间历史记录的可选和完全加密的同步。
* [bandwhich](https://github.com/imsnif/bandwhich) Band其中 — 终端带宽利用工具
* [bottom](https://github.com/ClementTsang/bottom) 底部 - 另一个跨平台的图形流程/系统监视器。[![GitHub工作流状态 (分支)](https:// img.shields.io/github/Workflow/Status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions？query=branch: master)
* [brocode/fblog](https://github.com/brocode/fblog) brocode/fblog — 小型命令行JSON日志查看器
* [bustd](https://github.com/vrmiguel/bustd) bustd - 轻量级进程杀手守护程序，用于处理Linux上的内存不足情况。[![GitHub工作流状态 (分支)](https:// img.shields.io/github/Workflow/Status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions？query=branch: master)
* [buster/rrun](https://github.com/buster/rrun) 巴斯特/运行 — Linux的命令启动器，类似于gmrun
* [cantino/mcfly](https://github.com/cantino/mcfly) cantino/mcfly - 翻阅你的贝壳历史。伟大的斯科特!
* [crabz](https://github.com/sstadick/crabz) 克拉布 - 多线程压缩和解压缩CLI工具 [![构建状态](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions？query=workflow: 检查)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) cristianoliveira/funzzy — 受 [entr](http://eradman.com/entrproject/) 启发的可配置文件系统观察器
* [dalance/procs](https://github.com/dalance/procs) 达兰斯/procs — Rust [![回归](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml) 编写的 'ps' 的现代替代品
* [ddh](https://github.com/darakian/ddh) ddh — 快速重复文件查找器
* [diskonaut](https://github.com/imsnif/diskonaut) diskonaut — 终端可视磁盘空间导航器
* [dust](https://github.com/bootandy/dust) 粉尘 — 更直观的du版本
* [eza-community/eza](https://github.com/eza-community/eza) eza-社区/eza — “Ls” 的替代品
* [fselect](https://crates.io/crates/fselect) fselect — 使用类似SQL的查询查找文件
* [gitui](https://github.com/extrawurst/gitui) 吉图 - 用Rust编写的git的快速终端客户端。[![建造] (https://github.com/extrawurst/gitui/workflows/CI/badge.svg？branch=master)](https://github.com/extrawurst/gitui/actions)
* [GQL](https://github.com/amrdeveloper/gql) GQL — 要运行的类似SQL的查询语言。git文件。
* [j0ru/kickoff](https://github.com/j0ru/kickoff) j0ru/启动 - 快速快速的wayland程序启动器 [![构建](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
* [Kondo](https://github.com/tbillington/kondo) 近藤 - 用于删除软件项目工件和回收磁盘空间的CLI & GUI工具
* [lotabout/rargs](https://github.com/lotabout/rargs) 关于/rargs [[rargs](https:// crates.io/crates/rargs)] -带有模式匹配支持的xargs awk
* [lotabout/skim](https://github.com/lotabout/skim) 关于/略过 — 纯锈中的模糊查找器
* [lsd](https://github.com/lsd-rs/lsd) lsd — 一个ls，有很多漂亮的颜色和很棒的图标 [![构建](https://github.com/lsd-rs/lsd/工作流/CICD/badge.svg？branch = master)](https://github.com/lsd-rs/lsd/actions)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) Luminarys/突触 — 灵活快速的BitTorrent守护程序。
* [m4b/bingrep](https://github.com/m4b/bingrep) m4b/bingrep — Greps通过来自各种OSs和体系结构的二进制文件，并为它们着色。
* [mdgaziur/findex](https://github.com/mdgaziur/findex) mdgaziur/findex - Findex是用Rust编写的高度可定制的应用程序查找器，使用GTK3
* [mitnk/cicada](https://github.com/mitnk/cicada) mitnk/蝉 — 类似bash的Unix外壳
* [mmstick/concurr](https://github.com/mmstick/concurr) mmstick/concurr — 替代GNU并行w/ a客户端-服务器体系结构
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) mmstick/fontfinder — GTK3预览和安装谷歌字体的应用程序
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) mmstick/tv-renamer — 带有可选GTK3前端的电视系列重命名应用程序。
* [mxseev/logram](https://github.com/mxseev/logram) mxseev/logram — 将日志文件的更新推送到Telegram
* [nickgerace/gfold](https://github.com/nickgerace/gfold) 尼克格拉斯/gfold [[gfold](https:// crates.io/crates/gfold)]-CLI工具，可帮助跟踪多个Git存储库 [![build](https:// img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions？query=workflow: 合并分支: main)
* [nivekuil/rip](https://github.com/nivekuil/rip) nivekuil/rip - 安全且符合人体工程学的 “rm” 替代品
* [nushell/nushell](https://github.com/nushell/nushell) nushell/nushell - 一种新型外壳
* [orhun/kmon](https://github.com/orhun/kmon) orhun/kmon — Linux内核管理器和活动监视器![https://github.com/orhun/kmon/actions](https:// img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml？branch = master & label = build)
* [orhun/systeroid](https://github.com/orhun/systeroid) orhun/systeroid — 一个更强大的替代sysctl(8) 与终端用户界面![https://github.com/orhun/systeroid/actions](https:// img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml？branch = main & label = build)
* [ouch](https://github.com/ouch-org/ouch) 哎哟 - 命令行上的无痛压缩和解压缩 [![GitHub工作流状态 (分支)](https:// img.shields.io/github/Workflow/Status/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions？query = branch:master)
* [pkolaczk/fclones](https://github.com/pkolaczk/fclones) pkolaczk/fclones — 高效的重复文件查找器和卸妆器
* [pop-os/popsicle](https://github.com/pop-os/popsicle) pop-os/冰棒 — GTK3和CLI实用程序，用于并行闪烁多个USB设备
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) pop-os/system76-power — 使用CLI工具的Linux电源管理守护程序 (DBus接口)。
* [pueue](https://github.com/nukesor/pueue) 普尤 — 管理长时间运行的shell命令。[![GitHub操作工作流](https://github.com/nukesor/pueue/workflows/Test build/badge.svg？分支 = master)](https://github.com/nukesor/pueue/actions)
* [qarmin/cakawka](https://github.com/qarmin/czkawka) qarmin/cakawka - 多功能应用程序查找重复，空文件夹，类似的图像等。[![GitHub Actions工作流](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg？branch = master)](https://github.com/qarmin/czkawka/actions)
* [redox-os/ion](https://github.com/redox-os/ion) 氧化还原-os/离子 — 下一代系统外壳
* [sharkdp/bat](https://github.com/sharkdp/bat) sharkdp/bat — 有翅膀的猫 (1) 克隆。[![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg？branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd) sharkdp/fd — 一个简单，快速和用户友好的替代发现。[![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex) sitkevij/hex — 彩色hexdump终端实用程序。
* [supercilex/fuc](https://github.com/supercilex/fuc) supercilex/fuc - 快速的 'cp' 和 'rm' 命令
* [trippy](https://github.com/fujiapple852/trippy) trippy - 网络诊断工具 [![构建徽章](https://github.com/fujiapple852/trippy/工作流/CI/badge.svg)](https://github.com/fujiapple852/trippy/操作/工作流/ci.yml)
* [uutils/coreutils](https://github.com/uutils/coreutils) uutils/coreutils — GNU coreutils的跨平台Rust重写 [[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [watchexec](https://github.com/watchexec/watchexec) watchexec — 响应文件修改执行命令
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) XAMPPRocky/tokei — 计算代码行

### 任务调度

* [delicate](https://github.com/BinChengZhao/delicate) 精致 — 用rust编写的轻量级分布式任务调度平台。[![构建状态](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### 文本编辑器

* [amp](https://amp.rs) 放大器 — 灵感来自Vi/Vim。
* [emacs-ng](https://github.com/emacs-ng/emacs-ng) emacs-ng — 用rust代码补充C代码库，引入新功能。
* [gchp/iota](https://github.com/gchp/iota) gchp/iota — 一个简单的文本编辑器
* [helix](https://github.com/helix-editor/helix) 螺旋线 — 受Neovim/Kakoune启发的后现代模态文本编辑器。[![构建徽章](https://github.com/螺旋编辑器/螺旋/动作/工作流/构建.yml/徽章.svg)](https://github.com/螺旋编辑器/螺旋/动作)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) ilai-deutel/kibi — 一个微型 (≤ 1024 LOC) 文本编辑器，具有语法突出显示，增量搜索等功能。[![构建徽章](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg？branch = master)](https://github.com/ilai-deutel/kibi/actions？query = branch:master)
* [Lapce](https://github.com/lapce/lapce) Lapce — 用铁锈写的后端的现代编辑器。从已停产的 [xi-editor](https://github.com/xi-editor) 中汲取灵感。
* [mathall/rim](https://github.com/mathall/rim) mathall/rim — 用Rust编写的类似Vim的文本编辑器
* [ox](https://github.com/curlpipe/ox) 公牛 — 在您的终端中运行的独立的Rust文本编辑器!
* [vamolessa/pepper](https://github.com/vamolessa/pepper) vamolessa/胡椒 [[pepper](https:// crates.io/crates/pepper)] -一个自以为是的模式编辑器，用于简化从终端进行的代码编辑 [![构建徽章] (https://github.com/vamolessa/pepper/workflows/rust/badge.svg？branch=master)](https://github.com/vamolessa/pepper)

### 文本处理

* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) dominikwilkowski/cfonts [[cfonts](https:// crates.io/crates/cfonts)] -控制台的性感ANSI字体![建立徽章](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [grex](https://github.com/pemistahl/grex) 格雷克斯 — 用于从用户提供的测试用例生成正则表达式的命令行工具和库
* [jqnatividad/qsv](https://github.com/jqnatividad/qsv) jqnatividad/qsv [[qsv](https:// crates.io/crates/qsv)] -高性能CSV数据整理工具包。从xsv分叉，有34个额外的命令和更多。[![Linux内部版本状态](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml) [![Windows内部版本状态](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml) [![macOS内部版本状态](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) Lisprez/so_stupid_search — 一种简单快速的人类字符串搜索工具
* [Melody](https://github.com/yoav-lavi/melody) 旋律 - 一种编译为正则表达式的语言，旨在更易于阅读和维护 [![构建徽章](https://github.com/yoav-lavi/melody/动作/工作流/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/动作/工作流/rust.yml) [![crates.io](https:// img.shields.io/crates/v/melody_compiler?label = compiler)](https:// crates.io/crates/melody_compiler)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) phiresky/ripgrep-全部 — ripgrep，但也可以搜索pdf，电子书，办公文档，zip，tar.gz等。
* [replicadse/complate](https://github.com/replicadse/complate) 复制/complate — 一个终端内文本模板工具，用于标准化消息 (如GIT提交)。[![crates.io](https:// img.shields.io/crates/v/complate.svg)](https:// crates.io/crates/complate) [![crates.io](https:// img.shields.io/crates/d/complate?label = crates.io下载)](https:// crates.io/crates/complate) [![建立徽章] (https://github.com/replicadse/complate/workflows/pipeline/badge.svg？branch=master)](https://github.com/replicadse/complate/actions)
* [ripgrep](https://crates.io/crates/ripgrep) 催熟 — 将银搜索器的可用性与grep的原始速度相结合
* [ruplacer](https://github.com/your-tools/ruplacer) 红宝石 — 查找和替换源文件中的文本 [![运行测试](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg？branch = master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [sd](https://crates.io/crates/sd) sd — 直观的查找和替换CLI
* [sstadick/hck](https://github.com/sstadick/hck) sstadick/hck - 更快，更有特色的下降，以代替 “切割” [![构建徽章] (https://github.com/sstadick/hck/workflows/Check/badge.svg？branch=master)](https://github.com/sstadick/hck)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) vishaltelangre/ff — 按名称查找文件 (ff)!
* [whitfin/bytelines](https://github.com/whitfin/bytelines) 惠特芬/拜特利尼 [[bytelines](https://crates.io/crates/bytelines)] -将输入线读取为字节切片，以提高效率。
* [whitfin/runiq](https://github.com/whitfin/runiq) 惠特芬/runiq — 一种从未排序的输入中过滤重复行的有效方法。
* [xsv](https://crates.io/crates/xsv) xsv — 一个快速的CSV命令行工具 (切片、索引、选择、搜索、采样等)

### 实用程序

* [1History](https://github.com/1History/1History) 1历史 — 命令行界面将Firefox/Chrome/Safari历史记录备份到一个SQLite文件 [![构建状态](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* [brycx/checkpwn](https://github.com/brycx/checkpwn) brycx/checkpwn — 我已经被修改了 (HIBP) 命令行实用工具，可让您轻松检查受损的帐户和密码。
* [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager) 史诗资产经理 — 一个非官方客户端，用于安装虚幻引擎，从Epic games Store下载和管理购买的资产，项目，插件和游戏。
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) evansmurithi/斗篷 — 一个命令行OTP (一次性密码) 验证器应用程序。![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![生成徽章](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master？svg = true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) fcsonline/tmux-拇指 — 闪电般的快速版本的tmux-用铁锈书写的手指，像vimum/vimperator一样复制/粘贴tmux。
* [guoxbin/dtool](https://github.com/guoxbin/dtool) 国宾/dtool — 一个有用的命令行工具集合，可帮助开发，包括转换，编解码器，哈希，加密等。
* [mprocs](https://github.com/pvolok/mprocs) mprocs — 用于运行多个进程的TUI
* [mrjackwills/oxker](https://github.com/mrjackwills/oxker) mrjackwills/oxker [[oxker](https://crates.io/crates/oxker)] -一个简单的tui来查看和控制docker容器。
* [nix-community/nix-init](https://github.com/nix-community/nix-init) nix-community/nix-init — 使用哈希预取，依赖性推断，许可证检测等从url生成Nix包 [![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
* [nix-community/nix-melt](https://github.com/nix-community/nix-melt) nix-社区/nix-melt — 类似ranger的flake.lock查看器 [![build-badge](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)
* [nix-community/nurl](https://github.com/nix-community/nurl) nix-社区/nurl [[nurl](https:// crates.io/crates/nurl)] -从存储库url生成Nix fetcher调用 [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
* [nomino](https://github.com/yaa110/nomino) 诺米诺 — 面向开发人员的批量重命名实用程序
* [raftario/licensor](https://github.com/raftario/licensor) raftario/许可方 — 将许可证写入stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg？branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) 铁锈-平行 - 使用Tokio并行执行命令的快速命令行应用程序。与GNU Parallel或xargs类似的接口。[![板条箱](https:// img.shields.io/板条箱/v/rust-parallel.svg？logo = rust)](https:// crates.io/crates/rust-parallel) [![构建状态](https://github.com/aaronriekenberg/rust并行/操作/工作流/CI.yml/徽章.svg)](https://github.com/aaronriekenberg/rust并行/操作/工作流/CI.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) rustdesk/rustdesk — 远程桌面软件，是TeamViewer和AnyDesk的绝佳替代品。
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) 乡村风格-rs/乡村风格 [[rustic-rs](https:// crates.io/crates/rustic-rs)] -由Rust提供支持的快速、加密、重复数据删除备份。[![版本](https:// img.shields.io/crates/v/rustic-rs.svg)](https:// crates.io/crates/rustic-rs)
* [suckit](https://github.com/Skallwar/suckit) 吸盘 - 递归访问网站内容并将其下载到您的磁盘。[![Crate](https:// img.shields.io/crates/v/suckit.svg?logo = 铁锈)](https:// crates.io/crates/suckit) [![构建状态](https://github.com/Skallwar/suckit/workflows/Build和测试/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)
* [tversteeg/emplace](https://github.com/tversteeg/emplace) tversteeg/emplace — 同步多台机器上已安装的软件包
* [vamolessa/verco](https://github.com/vamolessa/verco) vamolessa/verco [[verco](https://crates.io/crates/verco)] -专注于键盘快捷键的简单Git/Hg tui客户端
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) vaultwarden [![构建](https://github.com/dani-garcia/vaultwarden/操作/工作流/构建.yml/徽章.svg)](https://github.com/dani-garcia/vaultwarden/操作/工作流/构建.yml) -用Rust编写的Bitwarden服务器API的替代实现
* [warpdotdev/Warp](https://github.com/warpdotdev/Warp) warpdotdev/Warp : heavy_dollar_sign:-Warp是一种基于Rust的快速现代GPU加速终端，旨在使您和您的团队提高工作效率。
* [yaa110/cb](https://github.com/yaa110/cb) yaa110/cb — 用于管理剪贴板的命令行界面

### 视频

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) dertuxmalwieder/yaydl [[yaydl](https://crates.io/crates/yaydl)] -一个简单的视频下载器
* [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow) 回旋流/回旋流 - 使用陀螺仪数据的视频稳定应用
* [harlanc/xiu](https://github.com/harlanc/xiu) 哈兰克/修 — 由纯rust (rtmp/httpflv/hls/relay) 提供的功能强大且安全的实时服务器。[![crates.io](https:// img.shields.io/crates/v/xiu.svg)](https:// crates.io/crates/xiu)
* [vidmerger](https://github.com/TGotwig/vidmerger) vidmerger — 通过CLI合并视频和音频文件
* [xiph/rav1e](https://github.com/xiph/rav1e) xiph/rav1e — 最快和最安全的AV1编码器。

### 虚拟化

* [containers/youki](https://github.com/containers/youki) 容器/youki — Rust中的容器运行时 [![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg？branch=main)](https://github.com/containers/youki/actions)
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) 鞭炮-微vm/鞭炮 — 面向容器工作负载的轻量级虚拟机 [frecracker Microvm](https:// firecracker-microvm.github.io/)
* [tailhook/vagga](https://github.com/tailhook/vagga) 尾钩/vagga — 没有守护程序的容器化工具

### Web

* [cfal/tobaru](https://github.com/cfal/tobaru) cfal/托巴鲁 - 具有allowlists、IP和TLS SNI/ALPN基于规则的路由、iptables支持、循环转发 (负载平衡) 和热重载的端口转发器。
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) LemmyNet/lemmy — 用于fediverse [![构建状态](https:// cloud.drone.io/api/badges/LemmyNet/lemmy/Status.svg)](https:// cloud.drone.io/LemmyNet/lemmy) 的链接聚合器/reddit克隆
* [libreddit](https://github.com/libreddit/libreddit) libreddit - Reddit的替代私有前端
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) MASQ-项目/节点 — MASQ节点软件为全球用户提供了一个分散的节点网状网络，以访问正常的internet内容-Tor和VPN [![构建徽章](https://github.com/masq-project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/masq-project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume) 羽流-组织/羽流 — ActivityPub联合博客应用程序
* [Revolt/backend](https://github.com/revoltchat/backend) 反叛/后端 - 用现代网络技术构建的用户优先聊天平台。

### Web服务器

* [emanuele-em/man-in-the-middle-proxy](https://github.com/emanuele-em/man-in-the-middle-proxy) Emanuele-em/中间人代理 — MITM代理!具有SSL/TLS功能的HTTP/1、HTTP/2和WebSockets工具包 [![Rust](https://github.com/emanuele-em/中间人代理/操作/工作流/rust.yml/badge.svg)](https://github.com/emanuele-em/中间人代理/操作/工作流/rust.yml)
* [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder) mu-arch/skyfolder - 漂亮的HTTP/Bittorrent服务器没有麻烦。安全图形用户界面非常快
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) mufeedvh/binserve — 一个快速的静态web服务器，在一个二进制文件中具有路由，模板和安全性，您可以使用零代码 [![构建徽章] (https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg？branch=master)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste) orhun/rustypaste — 一个最小的文件上传/pastebin服务![https://github.com/orhun/rustypaste/actions](https:// img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml？branch = master & label = build)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) ronanyeah/铁锈-hasura — 演示如何将Rust GraphQL服务器用作 [Hasura](https:// hasura.io/) 的远程模式![Rust](https://github.com/ronanyeah/rust-hasura/工作流/rust/badge.svg？branch = master)
* [static-web-server](https://github.com/static-web-server/static-web-server) 静态web服务器 — 用于静态文件服务的超快且异步的web服务器。⚡[![CI](https://github.com/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/actions/workflows/devel.yml？query = branch:master)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) svenstaro/迷你服务器 — 一个小的，自包含的跨平台CLI工具，允许您抓取二进制文件并通过HTTP提供一些文件 [![构建徽章] (https://github.com/svenstaro/miniserve/workflows/CI/badge.svg？branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) thecoshman/http — 请托管这些东西-一个基本的http服务器，用于快速简单地托管文件夹
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) Wawar/simple-http-服务器 — 简单静态http服务器
* [wyhaya/see](https://github.com/wyhaya/see) wyhaya/见 — 静态HTTP文件服务器

# # 开发工具

* [bacon](https://github.com/Canop/bacon) 培根 — 背景铁锈代码检查器，类似于货物手表
* [clippy](https://crates.io/crates/clippy) clippy — 锈色棉绒
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) 堵塞-工具/堵塞-cli — 从git元数据生成changelog ([常规changelog](https:// blog.thoughtram.io/公告/工具/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))
* [comtrya](https://github.com/comtrya/comtrya) comtrya — localhost/dotfiles的配置管理工具 [![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* [create-rust-app](https://github.com/Wulf/create-rust-app) create-rust-app — 通过运行一个命令来设置现代rust react web应用程序。[![crate](https:// img.shields.io/crates/v/create-rust-app.svg)](https:// crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) Dan-t/生锈-标签 — 为货运项目及其所有依赖项创建ctags/etags
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) datanymizer/datanymizer - 具有灵活规则的强大数据库匿名器 [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg？branch=main)](https://github.com/datanymizer/datanymizer/actions？query=workflow: CI分支: main)
* [delta](https://crates.io/crates/git-delta) 三角洲 — 用于git和diff输出的语法荧光笔 [![构建徽章](https://github.com/dandavison/delta/workflows/Continuous集成/badge.svg)](https://github.com/dandavison/delta // 操作)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) dotenv-短绒 — “.Env” 文件的Linter [![生成徽章](https://github.com/dotenv-linter/workflows/CI/badge.svg？branch = master)](https://github.com/dotenv-linter/actions？查询 = 工作流: CI分支: master)
* [frolic](https://github.com/FrolicOrg/Frolic) 嬉戏  — 一个API层，以10倍的速度构建面向客户的仪表板
* [fw](https://github.com/brocode/fw) 前 — 工作空间生产力助推器 [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [geiger](https://github.com/rust-secure-code/cargo-geiger) 盖革 — 一个程序，列出与Rust crate中不安全Rust代码的使用情况相关的统计信息及其所有依赖项 [![构建状态](https://dev.azure.com/cargo-geiger/_api/Build/Status/rust-secure-code.cargo-geiger？branchName = master)](https://dev.azure.com/货物-盖革/_build/最新？definitionId = 1 & branchName = master)
* [git-cliff](https://github.com/orhun/git-cliff) git-cliff — 遵循常规提交规范的高度可定制的变更日志生成器![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml？branch = main & label = build)
* [git-journal](https://github.com/saschagrunert/git-journal/) git-期刊 — Git Commit消息和Changelog生成框架
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) hot-lib-reloader — 热重载Rust代码 [![构建徽章](https://github.com/rksm/Hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [intelli-shell](https://github.com/lasantosr/intelli-shell) intelli-shell - 书签命令与占位符和搜索或自动完成在任何时间 [![crate](https:// img.shields.io/crates/v/intelli-shell.svg)](https:// crates.io/crates/intelli-shell) [![生成徽章](https://github.com/lasantosr/intelli-shell/操作/工作流/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/操作/工作流/release.yml)
* [just](https://github.com/casey/just) 只是 — 用于特定项目任务的便捷命令运行器
* [mask](https://github.com/jacobdeichert/mask) 面具 — 由简单markdown文件 [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg？branch=master)] 定义的CLI任务运行程序 (https://github.com/jacobdeichert/mask/actions？query=workflow: CI)
* [Module Linker](https://github.com/fiatjaf/module-linker) 模块链接器 — 扩展名为GitHub上的 “模式” 、 “使用” 和 “外部crate” 语句中的引用添加了 “<a>” 链接。
* [ptags](https://github.com/dalance/ptags) ptags — git存储库的并行通用ctags包装器
* [Racer](https://github.com/racer-rust/racer) 赛车手 — 生锈的代码完成
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) Rust搜索扩展 — 一个方便的浏览器扩展，用于在地址栏 (omnibox) 中搜索板条箱和文档。[![构建状态](https://github.com/huhu/rust-search-extension/workflows/Build/badge.svg？branch = master)](https://github.com/huhu/rust-search-extension/actions)
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix) rust-lang/rustfix  — 自动应用rustc提出的建议
* [Rustup](https://github.com/rust-lang/rustup) Rustup — Rust工具链安装程序 [![构建徽章](https://github.com/rust-lang/rustup/工作流/Linux (master)/badge.svg？branch = master)](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto) scriptisto 与语言无关的 “shebang解释器”，使您能够用编译语言编写一个文件脚本。[![构建状态](https:// cloud.drone.io/api/badges/igor-petruk/scriptisto/Status.svg)](https:// cloud.drone.io/igor-petruk/scriptisto)

### 构建系统

* [Cargo](https://crates.io/) 货物 — 防锈包装管理器
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) 货物-所有功能 - 一个可配置的子命令，用于简化所有功能组合的测试，构建和更多功能 [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) 货物-benchcmp — 比较Rust微基准的实用程序
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) 货物-bitbake — 可以使用meta-rust的类生成BitBake食谱的货物扩展
  * [cargo-cache](https://crates.io/crates/cargo-cache) 货物缓存 — 检查/管理/清理您的货物缓存 ('~/.cargo/' $ {cargo _ home} ') 、打印尺寸等 [![构建状态](https://github.com/matthiaskrgr/货物缓存/工作流/ci/徽章.svg？branch = master)](https://github.com/matthiaskrgr/货物缓存/操作)
  * [cargo-check](https://crates.io/crates/cargo-check) 货舱检查 — 围绕 “cargo rustc -- -Zno-trans' 的包装器，如果您只需要正确性检查，它可以帮助运行更快的编译
  * [cargo-commander](https://crates.io/crates/cargo-commander) 货舱-指挥官 — “Cargo” 的子命令，用于运行CLI命令，类似于 “package.Json” 中的脚本部分的工作方式 [![构建和测试](https://github.com/simonhyll/cargo-commander/操作/工作流/Build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/操作/工作流/build.yml)
  * [cargo-count](https://crates.io/crates/cargo-count) 货物-计数 — 列出了有关货运项目的源代码计数和详细信息，包括不安全的统计数据
  * [cargo-deb](https://crates.io/crates/cargo-deb) 货物-deb — 生成二进制Debian包
  * [cargo-deps](https://crates.io/crates/cargo-deps) 货物-deps — 构建Rust项目的依赖关系图
  * [cargo-do](https://crates.io/crates/cargo-do) 货舱-do — 连续运行多个货物命令
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) 货物-ebuild — 可以使用树内eclasses生成ebuild的货物扩展
  * [cargo-edit](https://crates.io/crates/cargo-edit) 货舱-编辑 — 允许您通过从命令行读取/写入Cargo.toml文件来添加和列出依赖项
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) 货物-生成 利用预先存在的git存储库作为模板的rust项目的生成器。
  * [cargo-graph](https://crates.io/crates/cargo-graph) 货物-图表 — 更新了带有附加功能的 “货物点” 叉。未维护，请参阅 “货物-设备”
  * [cargo-info](https://crates.io/crates/cargo-info) 货物-信息 — 从命令行查询板条箱的详细信息
  * [cargo-license](https://crates.io/crates/cargo-license) 货物-许可证 — 一个货运子命令，用于快速查看所有依赖项的许可证。
  * [cargo-limit](https://crates.io/crates/cargo-limit) 货物-限制 — 噪音较小的货物: 跳过警告，直到错误被修复，Neovim集成等。[![构建徽章](https://github.com/alopatindev/货物限制/操作/工作流/rust.yml/badge.svg)](https://github.com/alopatindev/货物限制/操作)
  * [cargo-make](https://crates.io/crates/cargo-make) 货舱-制造 — Rust任务运行器和构建工具。[![构建徽章](https://github.com/sagiegurari/货物-制造/工作流/CI/badge.svg？分支 = 主)](https://github.com/sagiegurari/货物-制造/操作)
  * [cargo-modules](https://crates.io/crates/cargo-modules) 货舱-模块 — 一个货物插件，用于显示板条箱模块的树状概述。
  * [cargo-multi](https://crates.io/crates/cargo-multi) 货物-多 — 在多个板条箱上运行指定的货物命令
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) 货物-过时 — 显示较新版本的Rust依赖项何时可用或过期
  * [cargo-rdme](https://github.com/orium/cargo-rdme) 货物-rdme [[cargo-rdme](https:// crates.io/crates/cargo-rdme)]-Cargo子命令，用于从crate的文档中创建自述文件。[![生成徽章](https://github.com/orium/货物-rdme/工作流/CI/badge.svg)](https://github.com/orium/货物-rdme/操作？查询 = 工作流: CI)
  * [cargo-release](https://crates.io/crates/cargo-release) 货物-放行 — 发布git管理的cargo项目的工具，build，tag，publish，doc，push [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) 货物-脚本 — 让人们快速轻松地运行Rust “脚本”，该脚本可以利用货物的包裹生态系统
  * [cargo-udeps](https://github.com/est31/cargo-udeps) 货物-udeps [[cargo-udeps](https://crates.io/crates/cargo-udeps)] -查找未使用的依赖项
  * [cargo-update](https://crates.io/crates/cargo-update) 货舱-更新 — 用于检查并将更新应用于已安装的可执行文件的cargo子命令
  * [cargo-watch](https://crates.io/crates/cargo-watch) 货物-手表 — 货源更改时，货物用于编译项目的实用程序
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) dtolnay/cargo-expand — 在源代码中扩展宏
* C制造
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) 发展/CMakeRust — 对于将Rust库集成到c制造项目中很有用
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) SiegeLord/RustCMake — 一个示例项目，显示了带有Rust的c制造的使用情况
* [Fleet](https://github.com/dimensionhq/fleet) 舰队 [[fleet-rs](https://crates.io/crates/fleet-rs)] -铁锈的快速构建工具。
* Github操作
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) icepuma/rust-动作 — 生锈github操作
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) 和平行动-mdbook — 适用于mdBook的GitHub操作
* [Nix](https://nixos.org/) 尼克斯
  * [nix-community/fenix](https://github.com/nix-community/fenix) nix-社区/fenix — 适用于nix的Rust工具链和rust分析器 [![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)

### 调试

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) gdbgui — 基于浏览器的前端，用于gdb调试C、Rust和go。
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) CodeLLDB — [Visual Studio代码](https://code.visualstudio.com/) 的LLDB扩展。

### 部署

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) emk/rust-musl-builder — 使用musl-libc和musl-gcc编译静态Rust二进制文件的Docker图像，具有有用的C库的静态版本
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) kpcyrd/mini-docker-rust — 非常小的rust docker图像的示例项目
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) 刘冲/docker-rustup — 多版本 (带有musl工具) Rust Docker图像
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) LukeMathWalker/货物-厨师 - 用于缓存编译Docker构建之间的远程依赖关系的工具和预构建的映像。
  * [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross) rust-cross/rust-musl-cross — 使用musl-cross [编译静态Rust二进制文件的Docker图像![构建](https://github.com/rust-cross/rust-musl-cross/工作流/构建/徽章.svg)](https://github.com/rust-cross/rust-musl-cross/actions？查询 = 工作流: 构建)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) rust-lang-nursery/docker-rust — 官方Rust Docker图像
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) emk/heroku-buildpack-rust — Heroku上防锈应用的构建包
* [MarcoIeni/release-plz](https://github.com/MarcoIeni/release-plz) MarcoIeni/发布-plz [[release-plz](https:// crates.io/crates/release-plz)] -从CI释放Rust crates，带有changelog生成和semver检查。[![构建徽章](https://github.com/MarcoIeni/发布-plz/工作流/CI/badge.svg)](https://github.com/MarcoIeni/发布-plz/操作)

### 嵌入式

[Rust Embedded](https://rust-embedded.org/) 铁锈嵌入 专注于改善在资源受限的环境和非传统平台中使用Rust的端到端体验。请参阅 [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust)，了解嵌入式Rust资源的精选和更多扩展列表。

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) avr-rust/ruduino Arduino Uno的可重用组件。
* 交叉编译
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) japaric/rust-cross — 关于交叉编译Rust程序，你需要知道的一切
  * [japaric/xargo](https://github.com/japaric/xargo) 日本/xargo — 毫不费力地交叉编译Rust程序，以自定义裸金属目标，如ARM Cortex-M
* Espressif
  * [esp-rs](https://github.com/esp-rs) esp-rs 许多社区项目的所在地，可以在Espressif Systems生产的各种soc和模块上使用Rust编程语言。
* 固件
  * [oreboot/oreboot](https://github.com/oreboot/oreboot) oreboot/oreboot — oreboot是coreboot的一个叉，去掉了C，用铁锈写
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) nrf-rs/nrf-hal — nRF设备系列的Rust HAL

### FFI
另见 [外函数接口](https:// doc.rust-lang.org/book/first-edition/ffi.html)，[Rust FFI综合](http://jakegoulding.com/rust-ffi-omnibus/) (使用其他语言用Rust编写的代码的示例的集合) 和 [用Rust编写的ffi示例](https://github.com/alexcrichton/rust-ffi-examples)。

* 
  * [mozilla/cbindgen](https://github.com/mozilla/cbindgen) mozilla/cbindgen — 从Rust源文件生成C头文件。用于WebRender的壁虎
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) Sean1708/生锈-切达干酪 — 从Rust源文件生成C头文件
* C
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) 德托内/cxx — Rust和C [![build badge] 之间的安全互操作 (https:// img.shields.io/badge/github-dtolnay/cxx-8da0cb？style = for-the-badge & labelColor = 555555 & logo = github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) 铁锈-cpp - 直接在Rust中嵌入C代码。[![构建状态](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master？svg = true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) rust-lang/rust-bindgen — 铁锈绑定发生器
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) rusterlium/rustler — 用于创建Erlang NIF功能的安全锈桥
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) bennettanderson/rjni — 使用Rust中的Java
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) drrb/java-rust-示例 — 使用Java中的Rust
  * [j4rs](https://crates.io/crates/j4rs) j4rs — 使用Rust中的Java
  * [jni](https://crates.io/crates/jni) jni — 使用Java中的Rust
  * [jni-sys](https://crates.io/crates/jni-sys) jni-sys — 对应于jni.h的Rust定义
  * [rucaja](https://crates.io/crates/rucaja) rucaja — 使用Rust中的Java
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) jcmoyer/rust-lua53 — Lua 5.3绑定防锈
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) 百合球/铁锈-lua — Lua 5.1的安全锈绑定
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) tickbh/td_rlua [[td_rlua](https://crates.io/crates/td_rlua)] -用于生锈的零成本高级lua 5.3包装器
  * [tomaka/hlua](https://github.com/tomaka/hlua) tomaka/hlua — Rust库与Lua接口
* 红宝石
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) anima-引擎/mrusty — mruby防锈安全绑定
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) infinyon/node-bindgen - 使用Rust生成nodejs模块的简单方法
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) 霓虹灯绑定/霓虹灯 — 用于编写安全快速的本机Node.js模块的Rust绑定
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) SSheldon/rust-objc — Objective-C运行时绑定和Rust包装
* PHP
  * [phper-framework/phper](https://github.com/phper-framework/phper) phper-框架/phper — 允许我们尽可能使用纯净和安全的Rust编写PHP扩展的框架
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) dgrunwald/rust-cpython — Python绑定
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) getsentry/milksnake — python setuptools的扩展，允许您以可想象的最可移植的方式在Python wheels中分发动态链接库。
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) PyO3/PyO3 — Python解释器的Rust绑定
  * [RustPython](https://github.com/RustPython/RustPython) RustPython — 用Rust [![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)] 编写的Python解释器 (https://github.com/RustPython/RustPython/actions？query=workflow: CI)
* 红宝石
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) d-不可诱惑/ruru — 用Rust编写的本地Ruby扩展
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) danielpclark/rutie — 用Rust编写的本地Ruby扩展，反之亦然
* 腹板组件
  * [rhysd/wain](https://github.com/rhysd/wain) rhysd/wain - wain: 零依赖的安全Rust中从头开始的WebAssembly解释器 [![构建徽章] (https://github.com/rhysd/wain/workflows/CI/badge.svg？branch=master&event=push)](https://github.com/rhysd/wain/actions？query=workflow: CI分支: 主事件: 推送)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) rustwasm/wasm-bindgen — 一个促进wasm模块和JS之间高层交互的项目。
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) rustwasm/wasm-pack — : package: :sparkles: 打包wasm并将其发布到npm!

### 格式化程序

* [dprint](https://github.com/dprint/dprint) dprint — 可插入和可配置的代码格式化平台 [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions？query=workflow: CI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust) 更漂亮的铁锈 — 一个固执己见的Rust代码格式化程序，可以自动修复错误的语法 ([Prettier](https:// prettier.io/) 社区插件)
* [rustfmt](https://github.com/rust-lang/rustfmt) rustfmt — 由Rust团队维护并包含在货物中的Rust代码格式化程序

### IDEs
另请参见 [我们 (I)DE yet？](https://areweideyet.com/) 和 [Rust工具](https:// www.rust-lang.org/工具)。

  * [Atom](https://github.blog/2022-06-08-sunsetting-atom/) 原子
    * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) rust-lang/atom-ide-rust — Rust IDE支持Atom，由Rust语言服务器 (RLS) 提供支持
  * [Eclipse](https://www.eclipse.org/) 日蚀
    * [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion) 日蚀腐蚀
  * [Emacs](https://www.gnu.org/software/emacs/) Emacs
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) emacs-racer — 自动完成 (另请参见 [公司](https:// company-mode.github.io) 和 [自动完成](https://github.com/自动完成))
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) flycheck-铁锈 — Rust支持 [Flycheck](https://github.com/flycheck/flycheck)
    * [rust-mode](https://github.com/rust-lang/rust-mode) rust-模式 — 生锈主要模式
    * [rustic](https://github.com/brotzeit/rustic) 质朴 - Rust Emacs开发环境 [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions？query=workflow: CI)
  * [gitpod.io](https://gitpod.io) gitpod.io — 基于Rust语言服务器的具有完全Rust支持的在线IDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) gnome-builder 自3.22.2版以来对铁锈和货物的本机支持
  * [IntelliJ](https://www.jetbrains.com/idea/) IntelliJ
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) intellij-rust/intellij-rust —
  * [Kakoune](http://kakoune.org/) Kakoune
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) kak-lsp/kak-lsp — [LSP](https:// microsoft.github.io/language-server-protocol/) 客户端。在Rust中实现，并支持开箱即用的rls。
  * [lapce](https://github.com/lapce/lapce) lapce — 用Rust编写的闪电般快速且功能强大的代码编辑器。[![建造徽章](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
  * [Ride](https://github.com/madeso/ride) 乘坐 —
  * [Sublime Text](https://www.sublimetext.com/) 崇高的文本
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) rust-lang/rust-增强 — 官方防锈包装
  * [Vim](https://vim.sourceforge.io/) Vim — 无处不在的文本编辑器
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) autozimu/LanguageClient-neovim — [LSP](https:// microsoft.github.io/language-server-protocol/) 客户端。在Rust中实现，并支持开箱即用的rls。
    * [crates.nvim](https://github.com/Saecki/crates.nvim) 板条箱.nvim - 有助于管理板条箱的插件。io依赖关系。
    * [rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) rust-tools.nvim - 使用neovim内置lsp更好地开发铁锈的工具
    * [rust.vim](https://github.com/rust-lang/rust.vim) rust.vim — 提供文件检测、语法突出显示、格式化、语法集成等。
    * [vim-racer](https://github.com/racer-rust/vim-racer) vim-赛车 — 允许vim使用 [Racer](https://github.com/racer-rust/racer) 进行Rust代码完成和导航。
  * Visual Studio
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) dgriffen/rls-vs2017 — Rust支持Visual Studio 2017预览版 [![生成徽章](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng？svg = true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) 活塞开发者/VisualRust — Rust的Visual Studio扩展 [![生成状态](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f？svg = true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/) Visual Studio代码
    * [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) 更好的TOML - vscode中的TOML支持
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) CodeLLDB — 一个LLDB扩展
    * [crates](https://github.com/serayuzgur/crates) 板条箱 — crates是crates.io依赖项的扩展。[![构建徽章](https:// img.shields.io/vscode-市场/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates)
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) 更漂亮的代码格式化程序 (Rust) — 固执己见的Rust代码格式化程序，自动修复错误的语法 ([Prettier](https:// prettier.io/) 社区插件)
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) 锈蚀分析仪 — RLS的替代rust语言服务器
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) rust-lang/rls-vscode — Rust支持Visual Studio代码 (同时支持RLS和rust-analyzer)

### 分析

* [Bencher](https://github.com/bencherdev/bencher) 板凳 - 一套连续的基准测试工具，旨在捕捉CI中的性能回归
* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) bheisler/criterion.rs — 统计驱动的Rust基准库
* [Bytehound](https://github.com/koute/bytehound) Bytehound — 一种适用于Linux的内存分析器
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) ellisonch/rust-秒表 — 秒表库
* 火焰图
  * [llogiq/flame](https://github.com/llogiq/flame) llogiq/火焰 —
  * [mrhooray/torch](https://github.com/mrhooray/torch) mrhooray/火炬 — 基于矮人调试信息生成火焰图
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) sharkdp/超精细 — 命令行基准测试工具

### 服务

* [deps.rs](https://github.com/deps-rs/deps.rs) deps.rs — 检测过时或不安全的依赖关系
* [docs.rs](https://docs.rs) 文档rs — 板条箱的自动文档生成

### 静态分析

[[assert](https://crates.io/keywords/assert) [断言,[静态](https:// crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) Facebook实验/MIRAI — 在Rust的中级中间表示 (MIR) 上操作的抽象解释器 [![持续集成](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml)
* [static_assertions](https://crates.io/crates/static_assertions) static_assertions — 编译时断言，以确保满足不变量

### 测试

[[test](https://crates.io/keywords/test) [试验,[测试](https:// crates.io/关键字/测试)]

* 代码覆盖率
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) 防水油布 — 为Rust设计的代码覆盖工具
* 持续集成
  * [trust](https://github.com/japaric/trust) 信任 — Travis CI和AppVeyor模板，用于在5种体系结构上测试您的Rust板条箱，并为Linux，macOS和Windows发布其二进制版本
* 框架和Runners
  * [AlKass/polish](https://github.com/AlKass/polish) AlKass/波兰语 — 迷你测试/测试驱动的框架 [![Crates包状态](https:// img.shields.io/crates/v/polish.svg)](https:// crates.io/crates/polish)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) 货物-小艇 - 一种货物扩展，可简化智能手机和其他小型处理器设备上的程序库测试和工作台。
  * [cucumber](https://crates.io/crates/cucumber) 黄瓜 [![最新版本](https:// img.shields.io/crates/v/cucumber.svg)](https:// crates.io/crates/cucumber) -用于Rust的Cucumber测试框架的实现。完全原生，没有外部测试运行器或依赖项。[![构建状态](https://github.com/黄瓜-rs/黄瓜/工作流/CI/badge.svg？branch = master)](https://github.com/黄瓜-rs/黄瓜)
  * [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log) d-e-s-o/test-log [[test-log](https:// crates.io/crates/test-log)] -替换 “#[test]” 属性，用于在运行测试之前初始化日志记录和/或跟踪基础结构。[![GitHub工作流状态](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg？branch = main)](https://github.com/d-e-s-o/test-log/操作/工作流/test.yml)
  * [demonstrate](https://crates.io/crates/demonstrate) 演示 — 声明性测试框架 [![构建状态](https://github.com/aubaugh/demonstrate/workflows/Continuous集成/badge.svg？分支 = 主)](https://github.com/aubaugh/demonstrate)
  * [rstest](https://crates.io/crates/rstest) rstest — Rust [![构建状态](https://github.com/la10736/rstest/工作流/测试/badge.svg？branch = master)](https://github.com/la10736/rstest/actions) 的基于夹具的测试框架
  * [speculate](https://crates.io/crates/speculate) 推测 — RSpec启发的生锈最小测试框架
* 模拟和测试数据
  * [asomers/mockall](https://github.com/asomers/mockall) asomers/mockall [[mockall](https:// crates.io/crates/mockall)] -一个强大的Rust模拟对象库。[![Cirrus构建状态](https:// api.cirrus-ci.com/github/asomers/mockall.svg)](https:// cirrus-ci.com/github/asomers/mockall)
  * [fake-rs](https://github.com/cksac/fake-rs) 假-rs —  生成假数据的库
  * [goldenfile](https://github.com/calder/rust-goldenfile) goldenfile [[goldenfile](https://crates.io/crates/goldenfile)] -一个为goldenfile测试提供简单API的库。
  * [httpmock](https://github.com/alexliesenfeld/httpmock) httpmock — HTTP mocking [![构建徽章] (https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock？branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest？definitionId=2&branchName=master)
  * [mockiato](https://crates.io/crates/mockiato) 莫奇亚托 — 一个严格但友好的鲁斯特2018嘲笑库
  * [mockito](https://crates.io/crates/mockito) mockito — HTTP嘲笑
  * [nrxus/faux](https://github.com/nrxus/faux/) nrxus/人造 [![最新版本](https:// img.shields.io/crates/v/faux.svg)](https:// crates.io/crates/faux) -用于从结构中创建模拟的库。![构建] (https://github.com/nrxus/faux/workflows/test/badge.svg？branch=master)
  * [synth](https://github.com/shuttle-hq/synth/) 合成器 — 以声明方式生成数据库数据。[![构建](https://github.com/穿梭-hq/合成器/操作/工作流/synth-test.yml/badge.svg)](https://github.com/穿梭-hq/合成器)
* 突变检测
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) 货物-变种人 [[cargo-mutants](https:// crates.io/crates/cargo-mutants)] -通过注入突变来查找未充分测试的代码，无需更改源。[![构建徽章](https://github.com/sourcefrog/货物-突变体/操作/工作流/tests.yml/badge.svg？分支 = 主事件 = 推送)](https://github.com/sourcefrog/货物-突变体/操作/工作流/tests.yml？查询 = 分支: 主)
  * [mutagen](https://github.com/llogiq/mutagen) 诱变剂 [[诱变剂](https:// crates.io/crates/诱变剂)] -源级突变测试框架 (仅每晚)
* 性能测试和模糊测试
  * [proptest](https://crates.io/crates/proptest) proptest — 受 [假设](https://hypothesis.works/) Python框架启发的属性测试框架
  * [quickcheck](https://crates.io/crates/quickcheck) 快速检查 — [QuickCheck] 的Rust实现 (https://wiki.haskell.org/Introduction_to_QuickCheck1)
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) rust-fuzz/afl.rs — Rust fuzzer，使用 [AFL](https:// lcamtuf.coredump.cx/afl/)

### 转载

* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) 贝叶斯目击者/m2cgen — 一个CLI工具，用于将经过训练的经典机器学习模型转换为具有零依赖关系的本机Rust代码。[![GitHub Actions状态](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub Actions/badge.svg？branch = master)](https://github.com/BayesWitnesses/m2cgen/actions)
* [immunant/c2rust](https://github.com/immunant/c2rust) 免疫剂/c2rust — C到锈转换器和交叉检查器建立在Clang/LLVM之上。
* [jameysharp/corrode](https://github.com/jameysharp/corrode) jameysharp/腐蚀 — 用Haskell编写的C到Rust翻译器。

# # 库

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) 性能-监视器-rs — 旨在作为应用程序监视其性能的基础的工具包。[![crates.io](https:// img.shields.io/crates/v/perf_monitor.svg)](https:// crates.io/crates/perf_monitor)

### 人工智能

#### 遗传算法

* [innoave/genevo](https://github.com/innoave/genevo) innoave/日内瓦 — 以可定制和可扩展的方式执行遗传算法 (GA) 仿真。
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) m-decoster/RsGenetic — Rust中的遗传算法库处于维护模式。
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) Martin1887/oxigen — 快速、并行、可扩展和适应性强的遗传算法库使用此库的示例仅在几秒钟内解决了N = 255的N Queens问题，并且使用的RAM少于1 MB。
* [pkalivas/radiate](https://github.com/pkalivas/radiate) pkalivas/辐射 — 可定制的并行遗传编程引擎，能够针对有监督，无监督和强化学习问题不断发展解决方案。附带整洁和Evtree的完整和可定制的实现。![板条箱.io](https://img.shields.io/板条箱/v/辐射)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) 威利-卡普勒/达尔文-rs — 带有锈蚀的进化算法

#### 机器学习
参见 [[机器学习](https:// crates.io/keywords/Machine-learning)]
另请参阅 [关于Rust的机器学习社区](https://medium.com/@ autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790 #.hvkp56j3f) 和 [我们正在学习吗？](https://www.arewelearningyet.com)。

* [autumnai/leaf](https://github.com/autumnai/leaf) 秋天/叶子 — 开放机器智能框架 ..放弃的项目。最新的叉子是 [spearow/juice]( https://github.com/spearow/juice)。
* [burn-rs/burn](https://github.com/burn-rs/burn) 烧伤-rs/烧伤 - Rust中灵活而全面的深度学习框架。
* [coreylowman/dfdx](https://github.com/coreylowman/dfdx) coreylowman/dfdx — CUDA采用了机器学习框架，该框架利用了Rust的许多独特功能。![Crates.io](https:// img.shields.io/crates/v/dfdx)
* [huggingface/candle](https://github.com/huggingface/candle) 拥抱脸/蜡烛 [[candle-core](https:// crates.io/crates/candle-core)]-一个极简ML框架，专注于易用性和性能 (包括GPU支持)
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) huggingface/tokenizers - 用Rust (原始实现) 编写的带有Python绑定的现代NLP管道的Face标记器。[![构建状态] (https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg？branch=master)](https://github.com/huggingface/tokenizers/actions)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) LaurentMazare/tch-rs — PyTorch的Rust语言绑定。
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) maciejkula/rustlearn — 机器学习板条箱生锈。[![圈CI](https://circleci.com/gh/maciejkula/rustlearn.svg？style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [rust-ml/linfa](https://github.com/rust-ml/linfa) 铁锈-ml/linfa — 机器学习框架。
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) smartcorelib/smartcore — Rust中的机器学习库 [![构建状态](https:// img.shields.io/circleci/Build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
* [tensorflow/rust](https://github.com/tensorflow/rust) tensorflow/rust — TensorFlow的Rust语言绑定

#### OpenAI

* [64bit/async-openai](https://github.com/64bit/async-openai) 64位/异步-openai [[async-openai](https://crates.io/crates/async-openai)] -基于OpenAPI规范的OpenAI API的人体工学铁锈绑定。
* [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) zurawiki/tiktoken-rs [[tiktoken-rs](https:// crates.io/crates/tiktoken-rs)]-Rust库，用于使用tiktoken在OpenAI模型中标记文本。[![CI](https://github.com/zurawiki/tiktoken-rs/操作/工作流/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/操作/工作流/ci.yml)

### 天文学

[[astronomy](https://crates.io/keywords/astronomy) [天文学

* [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite) cds-astro/aladin-lite - 用于可视化不同投影中的空间和行星图像调查的Web应用程序
* [fitsio](https://crates.io/crates/fitsio) fitsio — 适合接口库包装cfitsio
* [flosse/rust-sun](https://github.com/flosse/rust-sun) 牙线/铁锈-阳光 [[sun](https://crates.io/crates/sun)] -JS库suncalc的一个锈端口
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) saurvs/天文铁锈 — 铁锈天文学

### 异步

* [async-std](https://async.rs/) async-std [[async-std](https://crates.io/crates/async-std)]-Async版本的Rust标准库 [![CI](https://github.com/异步rs/异步std/操作/工作流/ci.yml/徽章.svg？branch = master)](https://github.com/异步-rs/异步-std/操作/工作流/ci.yml)
* [dpc/mioco](https://github.com/dpc/mioco) dpc/mioco — 可扩展的、基于协程序的异步IO处理库
* [mio](https://github.com/tokio-rs/mio) mio — MIO是用于Rust的轻量级IO库，其重点是在OS抽象上增加尽可能少的开销
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) rust-lang/期货-rs — Rust中的零成本期货
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) TeaEntityLab/fpRust — Monad/MonadIO，处理程序，协程/doNotation，Rust的函数式编程特性
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) 徐东-黄/五月 — 铁锈堆叠协程序库
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) zonyitoo/coio-rs — 具有工作窃取调度程序的协程I/O库

### 音频和音乐

[[audio](https://crates.io/keywords/audio) [音频

* [hound](https://crates.io/crates/hound) 猎犬 — 一个WAV编码和解码库
* [insomnimus/nodi](https://github.com/insomnimus/nodi) 失眠症/诺迪 [[nodi](https:// crates.io/crates/nodi)] -用于播放和提取MIDI文件的库。[![建造徽章] (https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg？branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears) jhasse/耳朵 — 一个简单的库来播放声音和音乐，在OpenAL和libsndfile之上
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) musitdev/portmidi-rs — [·波特米迪](https://portmedia.sourceforge.net/portmidi/) 绑定
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) ozankasikci/rust-音乐-理论 — Rust音乐理论库
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) pdeljanov/Symphonia — 支持AAC，FLAC，MP3，MP4，OGG，Vorbis和WAV的纯Rust音频解码和媒体解码库。
* [RustAudio](https://github.com/RustAudio) RustAudio
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) RustAudio/cpal - pure Rust中的低级跨平台音频I/O库。[![操作状态] (https://github.com/RustAudio/cpal/workflows/cpal/badge.svg？branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) RustAudio/rodio — Rust音频播放库
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) RustAudio/rust-portaudio — PortAudio绑定
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) 串行-ATA/lofty-rs [[lofty](https:// crates.io/crates/lofty)] -用于读取和编辑各种音频格式的元数据的库 [![构建徽章](https://github.com/串行-ATA/lofty-rs/操作/工作流/ci.yml/badge.svg？分支 = 主)](https://github.com/串行-ATA/lofty-rs/行动)

### 身份验证

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) constantoine/totp-rs [[Totp-rs](https:// crates.io/crates/totp-rs)]-2fa库，用于生成和验证基于totp的令牌![构建状态](https://github.com/constantoine/totp-rs/工作流/Rust/badge.svg)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) 济慈/jsonwebtoken — [JSON Web令牌](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust
* [oauth2](https://github.com/ramosbugs/oauth2-rs) oauth2 — 可扩展的强类型Rust OAuth2客户端库
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) 氧化物-auth — 一个OAuth2服务器库，用于与actix或其他前端结合使用，具有一组可配置和可插入的后端 [![构建状态](https:// api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg？branch = master)](https:// cirrus-ci.com/github/HeroicKatora/oxe-auth)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) sgrust01/jwtvault — 异步库管理和编排JWT工作流
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) yup-oauth2 — 提供设备、安装和服务帐户流的oauth2客户端实现

### 汽车

* [idletea/tokio-socketcan](https://github.com/idletea/tokio-socketcan) idletea/tokio-socketcan [[tokio-socketcan](https://crates.io/crates/tokio-socketcan)] -基于SocketCAN板条箱的Linux socketcan对tokio的支持
* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) marcelbuesing/can-dbc [[can-dbc](https://crates.io/crates/can-dbc)] -DBC格式的解析器
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) marcelbuesing/tokio-socketcan-bcm [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] - Linux SocketCAN BCM对tokio的支持
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) mbr/socketcan [[socketcan](https://crates.io/crates/socketcan)] - Linux SocketCAN库
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) Sensirion/lin-总线 [[lin总线](https:// crates.io/crates/lin总线)]-LIN总线驱动程序特性和协议实现 [![构建徽章](https://circleci.com/gh/Sensirion/lin-bus-rs.svg？样式 = svg)](https://app.circleci.com/pipelines/github/Sensirion/lin总线rs)

### 生物信息学

* [Rust-Bio](https://github.com/rust-bio) 铁锈-生物 — Rust中的生物信息学库。

### 缓存

* [06chaynes/http-cache](https://github.com/06chaynes/http-cache) 06chaynes/http缓存 [[http缓存](https:// crates.io/crates/http缓存)] -遵循HTTP缓存规则的缓存中间件 [![构建徽章](https://github.com/06chaynes/http-cache/工作流/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/操作/工作流/http-cache.yml)
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) aisk/rust-memcache — Memcached客户端库
* [al8n/stretto](https://github.com/al8n/stretto) al8n/stretto - 高性能线程安全内存绑定Rust缓存 [![构建徽章](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [jaemk/cached](https://github.com/jaemk/cached) jaemk/缓存 — 简单函数缓存/记忆
* [moka-rs/moka](https://github.com/moka-rs/moka) moka-rs/moka - Rust的高性能并发缓存库，灵感来自Java的咖啡因库 [![构建徽章](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)
* [mozilla/sccache](https://github.com/mozilla/sccache/) mozilla/sccache - 共享编译缓存，非常适合Rust编译
* [zkat/cacache-rs](https://github.com/zkat/cacache-rs) zkat/cacache-rs - 高性能、并发、内容可寻址的磁盘缓存，针对异步api进行了优化 [![生成徽章](https://github.com/zkat/cacache-rs/工作流/CI/badge.svg)](https://github.com/zkat/cacache-rs/操作/工作流/ci.yml)

### 云

* AWS [[aws](https:// crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) awslabs/aws-lambda-rust-runtime [[lambda_runtime](https:// crates.io/crates/lambda_runtime)] -AWS Lambda的Rust运行时 [![构建徽章](https://github.com/awslabs/aws-lambda-rust-runtime/工作流/rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/操作)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) awslabs/aws-sdk-rust - 新的AWS Rust SDK
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) rusoto/rusoto —
* 负载均衡器
  * [Convey](https://github.com/bparli/convey) 传达 - 具有动态配置加载的第4层负载平衡器
* 多云
  * [Qovery/engine](https://github.com/Qovery/engine) 恢复/引擎 - 抽象层库，只需几分钟就可以在云提供商上轻松部署应用程序

### 命令行

* 参数解析
  * [clap-rs](https://github.com/clap-rs/clap) clap-rs [[clap](https://crates.io/crates/clap)] -一个简单易用的全功能命令行参数解析器
  * [cliparser](https://crates.io/crates/cliparser) cliparser — 简单的命令行解析器。[![建造徽章] (https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg？branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) docopt/docopt.rs [[docopt](https:// crates.io/crates/docopt)] -[DocOpt] 的Rust实现 (http://docopt.org)
  * [google/argh](https://github.com/google/argh) google/argh [[argh](https:// crates.io/crates/argh)] -一个自以为是的基于派生的参数解析器，针对代码大小进行了优化 [![构建徽章] (https://github.com/google/argh/workflows/Argh/badge.svg？branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) killercup/quicli [[quicli](https://crates.io/crates/quicli)] -在Rust中快速构建酷炫的CLI应用
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) ksk001100/海马 [[seahorse](https:// crates.io/crates/seahorse)] -用Rust编写的最小CLI框架 [![构建状态](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg？branch = master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) TeXitoi/结构 [[structopt](https://crates.io/crates/structopt)] -通过定义一个结构来解析命令行参数
* 数据可视化
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) nukesor/comfy-table [[comfy-table](https:// crates.io/crates/comfy-table)] -用于cli工具的漂亮动态表。[![构建状态](https://github.com/Nukesor/舒适表/工作流/测试/badge.svg？分支 = 主)](https://github.com/nukesor/舒适表/操作)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) zhiburt/tabled [[tabled](https:// crates.io/crates/tabled)] -一个易于使用的库，用于Rust结构和枚举的漂亮打印表。[![构建状态](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* 以人为本的设计
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) rust-cli/human-panic [[人类恐慌](https://crates.io/crates/人类恐慌)] -人类恐慌消息
* 线条编辑器
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) kkawakam/rustyline [[rustyline](https://crates.io/crates/rustyline)] -Rust中的readline实现
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) 移动托马/衬垫 [[liner](https://crates.io/crates/liner)] -提供类似readline功能的库
  * [murarth/linefeed](https://github.com/murarth/linefeed) murarth/换行 [[linefeed](https://crates.io/crates/linefeed)] -可配置、可扩展、交互式线路阅读器
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) srijs/rust-copperline [[copperline](https://crates.io/crates/copperline)]-pure-Rust命令行编辑库
* 其他
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) mgrachev/更新-线人 [[Update-informer](https:// crates.io/crates/update-informer)] -更新CLI应用程序的informer。它检查Crates.io和GitHub上的新版本 [![构建徽章](https://github.com/mgrachev/更新-通知器/工作流/CI/badge.svg)](https://github.com/mgrachev/更新-通知器/操作)
* 管道
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) hniksic/rust-子流程 [[子流程](https://crates.io/crates/子流程)] -与外部管道交互的设施
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) 小号/寻呼机-rs [[寻呼机](https://crates.io/crates/寻呼机)] -通过外部寻呼机引导输出
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) 奥康纳663/导管.rs [[管道](https://crates.io/crates/duct)] -子进程管道和IO重定向的构建器
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) rust-cli/rexpect [[rexpect](https:// crates.io/crates/rexpect)] -自动化交互式应用程序，如ssh，ftp，passwd等 [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) zhiburt/expectrl [[expectrl](https:// crates.io/crates/expectrl)] -用于控制伪终端中的交互式程序的库 [![构建徽章](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* 进度
  * [a8m/pb](https://github.com/a8m/pb) a8m/pb [[pbr](https://crates.io/crates/pbr)] -用于生锈的控制台进度条
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) 控制台-rs/指标 [[indicatif](https://crates.io/crates/indicatif)] -向用户指示进度
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) 艾蒂安-拿破仑/菠菜 [[菠菜](https:// crates.io/crates/菠菜)] -生锈的实用微调器。[![CI](https://github.com/艾蒂安-拿破仑/菠菜/动作/工作流/ci.yml/badge.svg)](https://github.com/艾蒂安-拿破仑/菠菜/动作/工作流/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) FGRibreau/微调器 [[旋转器](https://crates.io/crates/spinners)]-60个优雅的终端旋转器
* 提示
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) 哈希不匹配/terminal_cli.rs [[terminal_cli](https://crates.io/crates/terminal_cli)] -构建交互式命令提示符
  * [mikaelmello/inquire](https://github.com/mikaelmello/inquire) mikaelmello/查询 [[inquire](https:// crates.io/crates/inquire)] -用于在终端上构建交互式提示的库。[![构建状态] (https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg？branch=main)](https://github.com/mikaelmello/inquire/actions)
  * [starship/starship](https://starship.rs/) 星舰/星舰 [[starship](https:// crates.io/crates/starship)] -对于任何shell [![构建状态](https://github.com/starship/starship/workflows/Main工作流/badge.svg？branch = master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) ynqa/promkit [[promkit](https:// crates.io/crates/promkit)] -用于构建交互式命令行工具的工具包 [![构建状态] (https://github.com/ynqa/promkit/workflows/promkit/badge.svg？branch=master)](https://github.com/ynqa/promkit/actions)
* 风格
  * [colored](https://github.com/colored-rs/colored) 彩色 [[colored](https://crates.io/crates/colored)] -着色终端如此简单，您已经知道该怎么做!
  * [console-rs/dialoguer](https://github.com/console-rs/dialoguer) 控制台-rs/dialoguer [[dialoguer](https://crates.io/crates/dialoguer)] -用于命令行提示和类似事物的rust库。
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) LukasKalbertodt/bunt [[bunt](https:// crates.io/crates/bunt)] -跨平台终端颜色和带有宏的样式 [![构建状态](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions？query=workflow: CI分支: 主)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) LukasKalbertodt/术语画家 [[term-painter](https://crates.io/crates/term-painter)] -跨平台风格的终端输出
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) ogham/rust-ansi-术语 [[ansi_term](https://crates.io/crates/ansi_term)] -控制ANSI终端上的颜色和格式
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) 塞尔吉奥贝尼特斯/yansi [[yansi](https://crates.io/crates/yansi)] -一个死了的简单ANSI终端彩色画库
* TUI
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) cfyzium/bearlibterminal [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] - [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) 绑定
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) gyscos/草书 [[草书](https://crates.io/crates/cursive)] -构建丰富的TUI应用程序
  * [ivanceras/titik](https://github.com/ivanceras/titik) ivanceras/titik - 一个跨平台的TUI小部件库，目标是提供交互式小部件
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) ihalila/pancurses [[pancurses](https://crates.io/crates/pancurses)]-curses库，支持linux和windows
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) jeaye/ncurses-rs [[ncurses](https://crates.io/crates/ncurses)] - [ncurses](https://www.gnu.org/software/ncurses/) 绑定
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) ogham/rust-术语-网格 [[term_grid](https://crates.io/crates/term_grid)] -用于将东西放入网格中的Rust库
  * [ratatui-org/ratatui](https://github.com/ratatui-org/ratatui) ratatui-组织/ratatui [[ratatui](https:// crates.io/crates/ratatui)] -一个Rust库，它完全是关于烹饪终端用户界面 (TUIs)
  * [redox-os/termion](https://github.com/redox-os/termion) 氧化还原-os/termion [[termion](https://crates.io/crates/termion)] -用于控制终端/TTY的无bindless库
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) gchp/rustbox [[rustbox](https:// crates.io/crates/rustbox)] -绑定到 [Termbox](https://github.com/nsf/termbox)
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) TimonPost/crossterm [[Crosserm](https://crates.io/crates/crosserm)]-crossplatform终端库

### 压缩

* [7z](https://7-zip.org/7z.html) 7z
  * [dyz1990/sevenz-rust](https://github.com/dyz1990/sevenz-rust) dyz1990/sevenz-rust [[sevenz-rust](https:// crates.io/crates/sevenz-rust)] -用纯rust编写的7z解压缩器/压缩器。[![Rust](https://github.com/dyz1990/sevenz-rust/工作流/Rust/badge.svg？branch = main)](https://github.com/dyz1990/sevenz-rust/actions)
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html) Brotli
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) dropbox/rust-brotli — 铁锈中的Brotli解压缩器，可选地避免stdlib
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) ende76/布罗特利-rs — Brotli压缩的实现
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) alexcrichton/bzip2-rs — [libbz2](https://www.sourceware.org/bzip2/) 绑定
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) zopfli [[zopfli](https://crates.io/crates/zopfli)] -实现更高质量的deflate或zlib压缩的Zopfli压缩算法
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/) sstadick/gzp - deflate格式和snappy的多线程编码和解码
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) 铁锈-郎/flate2-rs — [miniz](https://code.google.com/archive/p/miniz) 绑定 [![构建徽章](https://github.com/rust-lang/flate2-rs/工作流/CI/badge.svg？branch = master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) JeffBelgum/rust-snappy — [·斯纳皮](https://github.com/google/snappy) 绑定
* 焦油
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) alexcrichton/tar-rs — 铁锈中的tar档案阅读/写作
* 邮编
  * [zip-rs/zip](https://github.com/zip-rs/zip) zip-rs/zip — 读写ZIP档案

### 计算

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) argmin-rs/argmin [[argmin](https://crates.io/crates/argmin)] -一个纯锈优化库
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) BLAS [[blas](https:// crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) mikkyang/rust-blas — 布拉斯绑定
* [calebwin/emu](https://github.com/calebwin/emu) calebwin/emu — 一种从Rust宏中进行GPGPU数值计算的语言
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) dimforge/nalgebra — 低维线性代数库
* [GSL](http://www.gnu.org/software/gsl/) GSL
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) GuillaumeGomez/rust-GSL — GSL绑定
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK) LAPACK
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) 不锈钢/lapack — LAPACK绑定
* 平行
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) arrayfire/arrayfire-rust — [Arrayfire](https://github.com/arrayfire) 绑定
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) 秋水/厚角组织 — 一个可扩展的，可插拔的，与后端无关的框架，用于在CUDA，OpenCL和通用主机CPU上进行并行，高性能的计算。
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) luqmana/rust-opencl — [OpenCL](https://www.khronos.org/opencl/) 绑定
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) 数字/scirust — Rust中的科学计算库
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) statrs-dev/statrs — 鲁斯特中的鲁棒统计计算库

### 并发

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) 横梁-rs/横梁 -在Rust中支持并行性和低级并发
* [orium/archery](https://github.com/orium/archery) 拱门/射箭 [[archery](https:// crates.io/crates/archery)] -从 'Rc'/'Arc' 指针类型中抽象出来的库。[![构建徽章](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions？query=workflow: CI)
* [Rayon](https://github.com/rayon-rs/rayon) 人造丝 -用于Rust的数据并行性库
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) rustcc/coroutine-rs -铁锈中的协图库
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) zonyitoo/coio-rs -用于生锈的协程序I/O

### 配置

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) andoriyu/uclicious [[uclicious](https:// crates.io/crates/uclicious)] - [libUCL](https://github.com/vstakhov/libucl) 基于功能丰富的配置库。[![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg？style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) Kixunil/configure_me [[configure_me](https:// crates.io/crates/configure_me)] -用于轻松处理应用程序配置的库
* [mehcode/config-rs](https://github.com/mehcode/config-rs) mehcode/config-rs [[config](https:// crates.io/crates/config)] -用于Rust应用程序的分层配置系统 (具有对12因素应用程序的强大支持)。
* [softprops/envy](https://github.com/softprops/envy) 软道具/羡慕 - 将env vars反序列化为类型安全结构 [![主要](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### 密码学

[[crypto](https://crates.io/keywords/crypto) [密码,[密码学](https://crates.io/keywords/密码学)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat) arkworks-rs/circom-compat - Arkworks绑定到Circom的R1CS，用于在Rust中生成Groth16证明和见证。
* [briansmith/ring](https://github.com/briansmith/ring) briansmith/戒指 — 使用Rust和BoringSSL的密码学原语安全、快速、小加密。
* [briansmith/webpki](https://github.com/briansmith/webpki) briansmith/webpki — Rust中的Web PKI TLS X.509证书验证
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) conradkleinespel/公鸡 [[rooster](https://crates.io/crates/rooster)] -在您的终端中使用的简单密码管理器
* [cossacklabs/themis](https://github.com/cossacklabs/themis) cossacklabs/themis [[themis](https:// crates.io/crates/themis)] -用于解决典型数据安全任务的高级加密库，最适合多平台应用程序。[![建造徽章] (https://circleci.com/gh/cossacklabs/themis/tree/master.svg？style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) DaGenix/rust-加密 — Rust中的密码算法
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) dalek-密码学/curve25519-dalek — 纯锈实现Curve25519操作
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) dalek-密码学/ed25519-dalek — Ed25519数字签名的纯锈实现
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) dalek-密码学/x25519-dalek — X25519密钥交换的纯锈实现
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) 碎片/tiny-keccak — Keccak家族 (SHA3) 的纯锈实施
* [exonum/exonum](https://github.com/exonum/exonum) exonum/exonum [[exonum](https://crates.io/crates/exonum)] -区块链项目的可扩展框架
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) facebook/不透明-ke — Pure Rust实现了最近的 [OPAQUE](https://datatracker.ietf.org/doc/draf-krawczyk-cfrg-opaque/) 密码认证密钥交换。[![构建徽章](https://github.com/facebook/不透明-ke/工作流/Rust CI/badge.svg？分支 = 主)](https://github.com/facebook/不透明-ke)
* [klutzy/suruga](https://github.com/klutzy/suruga) klutzy/suruga — [TLS 1.2] 的Rust实现 (https://datatracker.ietf.org/doc/html/rfc5246)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) kornelski/rust-安全-框架 — 安全框架的绑定 (OSX原生)
* [libOctavo/octavo](https://github.com/libOctavo/octavo) libOctavo/octavo — 鲁斯特中的模块化哈希和加密库
* [orion-rs/orion](https://github.com/orion-rs/orion) 猎户座-rs/猎户座 — 这个库旨在提供简单和可用的加密。“Usable” 意味着暴露易于使用且难以滥用的高级API。[![测试](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg？branch = master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) racum/rust-djangohashers [[djangohashers](https://crates.io/crates/djangohashers)] -Django项目中使用的密码原语的Rust端口。它不需要Django，只需要根据其样式进行哈希和验证密码。
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) RustCrypto/哈希 — 用纯Rust编写的加密哈希函数的集合
* [rustls/rustls](https://github.com/rustls/rustls) rustls/rustls — TLS的Rust实现
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) sfackler/rust-native-tls — 本机TLS库的绑定
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) sfackler/rust-openssl — [OpenSSL](https://www.openssl.org/) 绑定
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) sorairolake/scryptenc-rs [[scryptenc](https:// crates.io/crates/scryptenc)] -scrypt加密数据格式的实现。[![CI](https://github.com/sorairolake/scryptenc-rs/工作流/CI/badge.svg？branch = 开发)](https://github.com/sorairolake/scryptenc-rs/actions？查询 = 工作流: CI)
* [vityafx/randomorg](https://github.com/vityafx/randomorg) vityafx/randomorg - A random.org客户端库。[![Crates badge](https:// img.shields.io/crates/v/randomorg.svg)](https:// crates.io/crates/randomorg)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) w3f/schnorrkel - Schnorr vrf和ristretta组上的签名

### 数据处理

* [amv-dev/yata](https://github.com/amv-dev/yata) amv-开发/yata — 高性能技术分析库 [![构建状态](https:// img.shields.io/github/workflow/Status/amv-dev/yata/Rust？branch = master)](https://github.com/amv-dev/yata/actions？query = workflow:Rust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) bluss/ndarray — 具有数组视图、多维切片和高效操作的n维数组
* [kernelmachine/utah](https://github.com/kernelmachine/utah) kernelmachine/犹他州 — 铁锈中的数据帧结构和操作
* [pola-rs/polars](https://github.com/pola-rs/polars) pola-rs/polars - 快速功能完整的DataFrame库![构建和测试](https://github.com/pola-rs/polars/工作流/构建和测试/badge.svg？branch = master)
* [weld-project/weld](https://github.com/weld-project/weld) 焊接-项目/焊接 — 数据分析应用程序的高性能运行时

### 数据流

* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) 阿罗约系统/阿罗约 - Rust和SQL中的高性能实时分析 [![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg？branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* [infinyon/fluvio](https://github.com/infinyon/fluvio) infinyon/fluvio - 可编程数据流平台 [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg？branch=stable)](https://github.com/infinyon/fluvio/actions)

### 数据结构

* [becheran/grid](https://github.com/becheran/grid) 贝赫兰/网格 [[grid](https:// crates.io/crates/grid)] -为rust提供易于使用且快速的二维数据结构。[![构建状态](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) billyevans/tst [[tst](https://crates.io/crates/tst)] -三元搜索树集合
* [contain-rs](https://github.com/contain-rs) 包含-rs — Rust的std::collections的扩展
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) danielpclark/array_tool — 防锈阵列助手。一些最常见的方法，你会使用在数组上提供矢量。用于处理大多数用例的多态实现。
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) fizyk20/通用阵列 -允许按类型大小排列的数组的黑客
* [garro95/priority-queue](https://github.com/garro95/priority-queue) garro95/优先级队列[[优先级队列](https:// crates.io/crates/priority-queue)] -实现优先级更改的优先级队列。
* [greyblake/nutype](https://github.com/greyblake/nutype) greyblake/nutype [[nutype](https:// crates.io/crates/nutype)] -定义具有验证约束的newtype结构。[![构建状态](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) mrhooray/kdtree-rs — Rust中的K维树，用于快速地理空间索引和最近邻查找
* [orium/rpds](https://github.com/orium/rpds) orium/rpds [[rpds](https:// crates.io/crates/rpds)] -Rust中的持久性数据结构。[![构建徽章](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions？query=workflow: CI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) 咆哮位图/咆哮-rs -Rust中的咆哮位图
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) rust-itertools/itertools —
* [tnballo/scapegoat](https://github.com/tnballo/scapegoat) tnballo/替罪羊 [[替罪羊](https:// crates.io/crates/替罪羊)] -安全，易出错，仅堆栈替代 “btreeset” 和 “btreemap”。[![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg？branch=master)](https://github.com/tnballo/scapegoat/actions)
* [xfix/enum-map](https://github.com/xfix/enum-map) xfix/枚举映射 [[enum-map](https://crates.io/crates/enum-map)] -使用数组存储值的enum的优化map实现。
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) yamafaktory/超图 [[hypergraph](https:// crates.io/crates/hypergraph)]-Hypergraph是一个数据结构库，用于生成有向超图。[![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg？branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### 数据可视化

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs) blitzarx1/egui_graphs - [[egui_graphs](https:// crates.io/crates/egui_graphs)] -由egui和petgraph提供支持的rust交互式图形可视化小部件。[![Crates.io](https:// img.shields.io/crates/v/egui_graphs)](https:// crates.io/crates/egui_graphs) [![docs.rs](https:// img.shields.io/docsrs/egui_graphs)](https:// docs.rs/egui_graphs)
* [djduque/pgfplots](https://github.com/djduque/pgfplots) djduque/pgfplots [[pgfplots](https:// crates.io/crates/pgfplots)] -生成出版质量数字的Rust库。[![建造](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) igiagkiozis/plotly — 为生锈而努力。
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) mazznoer/colorgrad-rs [[colorgrad](https://crates.io/crates/colorgrad)] -用于数据可视化，图表，游戏，地图，生成艺术等的Rust颜色标度库。
* [milliams/plotlib](https://github.com/milliams/plotlib) 毫安/plotlib —
* [plotters](https://github.com/plotters-rs/plotters) 绘图仪 — [![构建徽章](https://github.com/绘图仪-rs/绘图仪/工作流/CI/badge.svg)](https://github.com/绘图仪-rs/绘图仪/动作)
* [rerun](https://github.com/rerun-io/rerun) 重新运行 — [[重新运行](https:// crates.io/crates/rerun)] -一个用于记录计算机视觉和机器人数据 (张量、点云等) 的SDK，与一个可视化器配对，用于随着时间的推移探索这些数据。
* [saresend/gust](https://github.com/saresend/Gust) 沙地/阵风 —

### 数据库

[[database](https://crates.io/keywords/database) [数据库

* NoSQL [[nosql](https:// crates.io/keywords/nosql)]

  * [ArangoDB](https://arangodb.com) ArangoDB
    * [Aragog](https://gitlab.com/qonfucius/aragog) 阿拉戈格 [[aragog](https:// crates.io/crates/aragog)] -一个轻量级的ArangoDB对象文档，关系和图形映射器 [![管道状态](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) 阿兰戈人 [[arangors](https://crates.io/crates/arangors)] -用于Rust的ArangoDB驱动程序
  * [Cassandra](https://cassandra.apache.org/_/index.html) 卡桑德拉 [[cassandra](https:// crates.io/keywords/cassandra), [cql](https:// crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) AlexPikalov/cdrs [[cdrs](https://crates.io/crates/cdrs)] -用Rust编写的本地客户端
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) krojew/cdrs-tokio [![构建徽章](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol) [卡桑德拉-协议]-Rust中的Cassandra协议实现
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio) [cdrs-东京]-用纯Rust编写的生产就绪异步Apache Cassandra驱动程序
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) Metaswitch/cassandra-rs —  绑定到DataStax C/C客户端
  * CouchDB [[couchdb](https:// crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) 寒意-rs/寒意 [[couchdb](https://crates.io/crates/chill)] -CouchDB REST API的Rust客户端
  * [DynamoDB](https://aws.amazon.com/dynamodb/) DynamoDB [[dynamodb](https:// crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) 软道具/dynomite - 用于与 “rusoto_dynamodb” [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg？branch=master)](https://github.com/softprops/dynomite/actions) 进行强类型且方便的交互的库
  * Elasticsearch [[elasticsearch](https:// crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) 贝纳什福德/rs-es [[rs-es](https://crates.io/crates/rs-es)] -[Elastic](https://www.elastic.co/) REST API的Rust客户端
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) 弹性-rs/弹性 [[elastic](https:// crates.io/crates/elastic)]-elastic是用Rust编写的Elasticsearch的高效模块化API客户端 [![构建徽章](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2？svg = true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) jimmycuadra/rust-etcd [[etcd](https://crates.io/crates/etcd)] -用于CoreOS的etcd的客户端库。
    * [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs) lodrem/etcd-rs — rust [![CI] 的异步etcd客户端 (https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) vhbit/sherwood — [ForestDB](https://github.com/couchbase/forestdb) 绑定
  * [InfluxDB](https://www.influxdata.com/) InfluxDB
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) driftluo/InfluxDBClient-rs — 同步接口
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) skade/leveldb — [LevelDB](https://github.com/google/leveldb) 绑定
  * LMDB [[lmdb](https:// crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) vhbit/lmdb-rs [[lmdb-rs](https://crates.io/crates/lmdb-rs)] - [LMDB](https://www.symas.com/symas-embedded-database-lmdb) 绑定
  * MongoDB [[mongodb](https:// crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) mongodb/mongo-rust-驱动程序 [[mongodb](https://crates.io/crates/mongodb)] - [MongoDB](https://www.mongodb.com/) 绑定
  * [PickleDB](https://pythonhosted.org/pickleDB/) PickleDB
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) seladb/pickledb-rs — 一个轻量级和简单的键值存储，在很大程度上受到Python的PickleDB的启发。
  * [PoloDB](https://www.polodb.org/) PoloDB
    * [PoloDB](https://github.com/PoloDB/PoloDB) PoloDB - 基于JSON的嵌入式数据库具有类似于MongoDB的API。![GitHub工作流状态](https:// img.shields.io/github/actions/Workflow/Status/PoloDB/rust.yml)
  * [Redb](https://www.redb.org/) Redb
    * [Redb](https://github.com/cberner/redb) Redb - 用纯Rust编写的嵌入式键值数据库。它提供了与其他嵌入式键值存储 (如rocksdb和lmdb) 类似的接口。[GitHub工作流状态](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis [[redis](https:// crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) aembke/弗雷德 [[fred](https:// crates.io/crates/fred)] -带有Tokio的Rust的高级异步 [Redis](https:// redis.io/) 客户端。[![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg？style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs？branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) redis-rs — Rust中的 [Redis](https:// redis.io/) 库 [![Rust](https://github.com/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/) RocksDB
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) rust-rocksdb/rust-rocksdb — RocksDB绑定 [![RocksDB CI](https://github.com/rust-rocksdb/actions/workflows/rust.yml/badge.svg？branch = master)](https://github.com/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/) SurrealDB
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) surrealdb/surrealdb — 超现实数据库嵌入式文档-图形数据库
  * [UnQLite](https://unqlite.org/) UnQLite
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) zitsen/unqlite.rs — UnQLite绑定
  * [ZooKeeper](https://zookeeper.apache.org/) ZooKeeper
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) bonifaido/rust-zookeeper [[zookeeper](https://crates.io/crates/zookeeper)] -Apache ZooKeeper的客户端库。
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) krojew/rust-zookeeper [[zookeeper-async](https:// crates.io/crates/zookeeper-async)] - Async Zookeeper客户端在Rust中100% 编写，基于tokio. ![构建状态](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https:// crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) 阿拉戈格 [[aragog](https:// crates.io/crates/aragog)] -一个轻量级的ArangoDB对象文档，关系和图形映射器 [![管道状态](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https:// crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) Brendonovich/prisma-client-rust — 一个自动生成的查询生成器，使用Prisma生态系统提供简单且完全类型安全的数据库访问。[![测试状态](https:// img.shields.io/github/workflow/Status/Brendonovich/prisma-client-rust/CI？label = tests & style = flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) 柴油-rs/柴油 — Rust的ORM和查询生成器
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) 伊万卡拉斯/鲁斯托姆 — 生锈的ORM
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) rbatis/rbatis — Rust ORM框架高性能 (基于JSON)
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) SeaQL/sea-orm — Rust的异步和动态ORM [![crate](https:// img.shields.io/crates/v/sea-orm.svg)](https:// crates.io/crates/sea-orm) [![docs](https:// img.shields.io/docsrs/sea-orm/latest)](https:// docs.rs/sea-orm) [![构建状态](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * [SeaQL/seaography](https://github.com/SeaQL/seaography) SeaQL/seaography — 用于SeaORM的GraphQL框架 [![crate](https:// img.shields.io/crates/v/seaography.svg)](https:// crates.io/crates/seaography) [![docs](https:// img.shields.io/docsrs/seaography/latest)](https:// docs.rs/seaography) [![构建状态](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
* [sfackler/r2d2](https://github.com/sfackler/r2d2) sfackler/r2d2 — 通用连接池
* SQL [[sql](https:// crates.io/keywords/sql)]
  * 通用
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) launchbadge/sqlx - 具有强类型支持的async PostgreSQL/MySQL/SQLite连接池 [![构建徽章](https:// img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master？style = flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) SeaQL/sea-查询 - 用于MySQL，Postgres和SQLite的动态SQL查询构建器 [![crate](https:// img.shields.io/crates/v/sea-query.svg)](https:// crates.io/crates/sea-query) [![docs](https:// img.shields.io/docsrs/sea-query/latest)](https:// docs.rs/sea-query) [![构建状态](https://github.com/SeaQL/sea-查询/操作/工作流/rust.yml/badge.svg)](https://github.com/SeaQL/sea-查询/操作/工作流/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) SeaQL/sea-schema - SQL架构定义和发现 [![crate](https:// img.shields.io/crates/v/sea-schema.svg)](https:// crates.io/crates/sea-schema) [![docs](https:// img.shields.io/docsrs/sea-schema/latest)](https:// docs.rs/sea-schema) [![构建状态](https://github.com/SeaQL/sea模式/操作/工作流/rust.yml/badge.svg)](https://github.com/SeaQL/sea模式/操作/工作流/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) prisma/提比略 — [![货物测试] (https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg？branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql [[mysql](https:// crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) AgilData/mysql-proxy-rs — MySQL代理 [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg？style = svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs？branch = master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) blackbeam/mysql_async [[mysql_async](https:// crates.io/crates/mysql_async)] -基于Tokio的异步Rust Mysql驱动程序。[![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg？style = shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async？branch = master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) blackbeam/rust-mysql-简单 [[mysql](https://crates.io/crates/mysql)] -原生MySql客户端
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) 久保/铁锈-甲骨文 [[oracle](https:// crates.io/crates/oracle)] -用于Rust的Oracle驱动程序 [![构建徽章](https://github.com/kubo/rust-oracle/操作/工作流/run-tests.yml/badge.svg？branch = master)](https://github.com/kubo/rust-oracle/操作/工作流/run-tests.yml)
  * PostgreSql [[postgres](https:// crates.io/keywords/postgres), [postgresql](https:// crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) 斯法克勒/铁锈-postgres [[postgres](https://crates.io/crates/postgres)] -本地 [PostgreSQL](https://www.postgresql.org/) 客户端
  * Sqlite [[sqlite](https:// crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) rusqlite — [Sqlite3](https://www.sqlite.org/index.html) 绑定

### 日期和时间

[[date](https://crates.io/keywords/date) [日期,[时间](https:// crates.io/关键字/时间)]

* [chronotope/chrono](https://github.com/chronotope/chrono) 计时/计时 —
* [Mnwa/ms](https://github.com/Mnwa/ms) Mnwa/ms [[Ms-converter](https:// crates.io/crates/ms-converter)] -这是一个用于将类人时间转换为毫秒的库 [![构建徽章] (https://github.com/Mnwa/ms/workflows/build/badge.svg？branch=master)](https://github.com/Mnwa/ms/actions？query=workflow: 构建)
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) sorairolake/nt-time [[Nt-time](https:// crates.io/crates/nt-time)] -Windows文件时间库。[![CI](https://github.com/sorairolake/nt-time/工作流/CI/badge.svg？分支 = 开发)](https://github.com/sorairolake/nt-time/操作？查询 = 工作流: CI)
* [time-rs/time](https://github.com/time-rs/time) 时间-rs/时间 — [![构建徽章](https://github.com/时间-rs/时间/工作流/构建/badge.svg)](https://github.com/时间-rs/时间/操作)

### 分布式系统

* 锑
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) 锑项目/锑 [[锑](https://crates.io/crates/锑)] -流处理/分布式计算平台
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) fede1024/rust-rdkafka [·卡夫卡](https://github.com/confluentinc/librdkafka) 绑定
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) gklijs/schema_registry_converter [[schema_registry_converter](https:// crates.io/crates/schema_registry_converter)] -与 [confluent schema registry] 集成 (https:// www.confluent.io/product/confluent-platform/data-compatibility/)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) 卡夫卡-锈/卡夫卡-锈 —
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) 刺痛/铁锈-豆豆 — [Beanstalkd](https://github.com/beanstalkd/beanstalkd) 绑定
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) hyunsik/hdfs-rs [[hdfs](https://crates.io/crates/hdfs)]-libhdfs绑定
* 其他
  * [build-trust/ockam](https://github.com/build-trust/ockam) 建立信任/ockam [[ockam](https:// crates.io/crates/ockam)] -分布式应用程序的端到端加密、相互身份验证和ABAC [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)

### 领域驱动设计

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) 服务器技术/cqrs [[Cqrs-es](https:// crates.io/crates/cqrs-es)] -使用 [用户指南](https:// doc.rust-cqrs.org/)

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya) aya/aya-rs — Rust编程语言的Rust库，以开发人员经验和可操作性为重点。
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs) libbpf/libbpf-rs — Rust生态系统的最小且自以为是的eBPF工具。

### 电子邮件

[[email](https://crates.io/keywords/email) [电子邮件,[imap](https:// crates.io/keywords/imap), [smtp](https:// crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) duesee/imap编解码器 [[imap编解码器](https:// crates.io/crates/imap编解码器)] -用于IMAP [![构建和测试](https://github.com/duesee/imap-codec/操作/工作流/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/操作/工作流/build_and_test.yml)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) gsquire/sendgrid-rs — SendGrid API的非官方Rust库
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) jdrouet/catapulte - 使用 [MRML](https://github.com/jdrouet/mrml) 模板发送电子邮件的微服务。
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) jdrouet/jolimail - 用于构建 [MRML](https://github.com/jdrouet/mrml) 模板的web应用程序。
* [jdrouet/mrml](https://github.com/jdrouet/mrml) jdrouet/mrml - 一个库，用于生成在任何邮件客户端上工作的漂亮电子邮件模板。
* [lettre/lettre](https://github.com/lettre/lettre) lettre/lettre — Rust的SMTP库 [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg？branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan) mailtutan/mailtutan 用于测试和开发环境的SMTP服务器。
* [staktrace/mailparse](https://github.com/staktrace/mailparse) staktrace/mailparse [[mailparse](https://crates.io/crates/mailparse)] -用于解析真实电子邮件文件的库
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) stalwartlabs/mail-auth [[Mail-auth](https:// crates.io/crates/mail-auth)]-DKIM、ARC、SPF和DMARC消息身份验证库 [![构建徽章](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) stalwartlabs/邮件解析器 [[mail-parser](https:// crates.io/crates/mail-parser)] -具有完整MIME支持的快速而强大的电子邮件解析库 [![构建徽章](https://github.com/stalwartlabs/邮件解析器/操作/工作流/rust.yml/badge.svg)](https://github.com/stalwartlabs/邮件解析器/操作/工作流/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) stalwartlabs/mail-send [[mail-send](https:// crates.io/crates/mail-send)] -支持DKIM的电子邮件生成器和SMTP客户端库 [![构建徽章](https://github.com/stalwartlabs/邮件发送/操作/工作流/rust.yml/badge.svg)](https://github.com/stalwartlabs/邮件发送/操作/工作流/rust.yml)
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab) tweedegolf/mailcrab — 用于开发的电子邮件测试服务器。

### 编码

[[encoding](https://crates.io/keywords/encoding) [编码

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) 亚历克斯/rust-asn1 — Rust ASN.1 (DER) 序列化器
* 二进制
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) bincode-组织/bincode — Rust [![CI] 中的二进制编码器/解码器 (https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg？branch = trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) jamesmunns/明信片 [[明信片](https://crates.io/crates/明信片)] -明信片是 #![no_std] 针对Serde的聚焦序列化器和反序列化器。
  * [m4b/goblin](https://github.com/m4b/goblin) m4b/哥布林 [[地精](https://crates.io/crates/goblin)] -跨平台，零副本和字节序感知二进制解析
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) mongodb/bson-rust — Rust中BSON的编码和解码支持
* 字节交换
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) BurntSushi/byteorder — 支持大端序、小端序和原生字节顺序
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) capnproto/capnproto-rust —
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) serde_cbor — CBOR对serde的支持
* 字符编码
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) hsivonen/encoding_rs [[encoding_rs](https://crates.io/crates/encoding_rs)] -Rust中面向壁虎的编码标准实现
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) lifthrasiir/rust-编码 —
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) mrhooray/crc-rs —
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) BurntSushi/rust-csv — 快速灵活的CSV阅读器和编写器，支持Serde
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) naomijub/edn-rs [[edn-rs](https://crates.io/crates/edn-rs)]-crate将EDN格式解析并发出为Rust类型。
* [FlatBuffers](https://flatbuffers.dev/) FlatBuffers
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) frol/flatc-生锈 — 货物构建脚本的FlatBuffers编译器 (flatc) 集成
* 哈尔
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) mandrean/har-rs [[har](https://crates.io/crates/har)] -一个HTTP存档格式 (HAR) 序列化和反序列化库
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) 伺服/html5ever — 高性能浏览器级HTML5解析器
* JSON
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) importcjj/rust-ajson [[ajson](https://crates.io/crates/ajson)] -快速获取JSON值
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) maciejhirsz/json-rust [[json](https://crates.io/crates/json)] -Rust中的JSON实现
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) pikkr/pikkr [[pikkr](https://crates.io/crates/pikkr)]-JSON解析器，它直接获取值，而无需在Rust中执行标记化
  * [serde-rs/json](https://github.com/serde-rs/json) serde-rs/json [[serde \_json](https://crates.io/crates/serde_json)]-JSON支持 [Serde](https://github.com/serde-rs/serde) 框架
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) simd-lite/simd-json [[Simd-json](https://crates.io/crates/simd-json)] -基于simdjson端口的高性能json解析器
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) 3Hren/msgpack-铁锈 — 纯Rust低/高级MessagePack实现
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) georust/netcdf [[netcdf](https://crates.io/crates/netcdf)] -用于Rust的中级netCDF绑定，允许轻松读取和写入类似数组的结构到文件。
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) jcreekmore/pem-rs [[pem](https://crates.io/crates/pem)] -一种基于Rust的解析和编码PEM编码数据的方法
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) stepancheg/rust-protobuf —
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) tokio-rs/prost — [![持续集成](https://github.com/tokio-rs/prost/工作流/持续集成/badge.svg？branch = master)](https://github.com/tokio-rs/prost/actions)
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) rkyv/rkyv [[rkyv](https://crates.io/crates/rkyv)] - rkyv (存档) 是Rust的零副本反序列化框架
* RON (生锈的对象符号)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) https://github.com/ron-rs/ron —
* Serde
  * [vityafx/serde-aux](https://github.com/vityafx/serde-aux/) vityafx/serde-aux - 与serde库一起使用的其他工具。[![CI](https://github.com/vityafx/serde-aux/操作/工作流/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/操作/工作流/ci.yml) [![Crates徽章](https:// img.shields.io/crates/v/serde-aux.svg)](https:// crates.io/crates/serde-aux)
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) 塔马斯菲/塔普洛 [[taplo](https:// crates.io/crates/taplo)] -用Rust [![CI](https://github.com/tamasfe/taplo/workflows/Continuous集成/badge.svg)] 编写的TOML工具包 (https://github.com/tamasfe/taplo/actions？query=workflow: “持续集成”)
  * [toml-rs/toml](https://github.com/toml-rs/toml) toml-rs/toml — [![CI](https://github.com/toml-rs/toml/操作/工作流/ci.yml/badge.svg)](https://github.com/toml-rs/toml/操作/工作流/ci.yml)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) Florob/RustyXML — 用Rust编写的XML解析器
  * [media-io/yaserde](https://github.com/media-io/yaserde) 媒体-io/yaserde — 又一个专门用于XML的序列化器/反序列化器
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) netvl/xml-rs — 流式XML库
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) shepmaster/sxd-文档 — Rust中的XML库
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) shepmaster/sxd-xpath — Rust中的XPath库
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) tafia/quick-xml — 高性能XML拉式读取器/写入器
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) chyh1990/yaml-铁锈 — 缺少的YAML 1.2 Rust的实现。
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) dtolnay/serde-yaml [[serde \ _yaml](https:// crates.io/crates/serde_yaml)] -yaml支持 [Serde](https://github.com/serde-rs/serde) 框架 [![build](https:// img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions？query = branch:master)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) vitiral/stfu8 [[stfu8](https://crates.io/crates/stfu8)] -UTF-8中的排序文本格式

### 文件系统

[[filesystem](https://crates.io/keywords/filesystem) [文件系统
* 运营
  * [Camino](https://github.com/camino-rs/camino) 卡米诺 [[camino](https://crates.io/crates/camino)] -像Rust的std::path::Path，但UTF-8。
  * [ParthJadhav/Rust_Search](https://github.com/ParthJadhav/Rust_Search) ParthJadhav/Rust_Search [[rust_search](https://crates.io/crates/rust_search)] -Rust内置的快速文件搜索库。
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) pop-os/dbus-udisks2 [[dbus-udisks2](https://crates.io/crates/dbus-udisks2)] - UDisks2 DBus应用编程接口
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) pop-os/sys-mount [[sys-mount](https://crates.io/crates/sys-mount)] -“mount”/“umount2” 系统调用的高级抽象。
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) vitiral/path_abs [[path_abs](https://crates.io/crates/path_abs)] -绝对可序列化路径类型和关联方法。
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) webdesus/fs_extra — 扩大机会标准图书馆标准::fs和标准::io
* 临时文件
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) Stebalien/tempfile — 临时文件库
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) Stebalien/xattr [[xattr](https://crates.io/crates/xattr)] -列出和操作unix扩展文件属性
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) zboxfs/zbox [[zbox](https://crates.io/crates/zbox)] -零细节，注重隐私的可嵌入文件系统。

### 财务

* [avhz/RustQuant](https://github.com/avhz/RustQuant) avhz/RustQuant [[RustQuant](https:// crates.io/crates/RustQuant)] -一个定量金融库。![GitHub工作流状态 (带事件)](https:// img.shields.io/github/actions/Workflow/Status/avhz/RustQuant/build.yml)
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) d-e-s-o/apca [[apca](https:// crates.io/crates/apca)] -对 [Alpaca API](https:// alpaca.markets/) 的自以为是的全面绑定，用于股票交易等。![GitHub工作流状态](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg？分支 = main)

### 函数式编程

[[functional programming](https://crates.io/keywords/fp) [函数式编程
* 前奏
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) JasonShin/fp-core.rs — Rust中的函数式编程库
  * [myrrlyn/tap](https://github.com/myrrlyn/tap) myrrlyn/tap - 后缀-位置管道行为

### 游戏开发
另见 [我们还在玩游戏吗？](https:// arewegameyet.rs)
* 快板
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) SiegeLord/RustAllegro — [Allegro 5](https:// liballeg.github.io/) 绑定
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) 真棒四边形 — 到miniquad/macroquad相关代码和资源的链接的精选列表
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) 真棒wgpu — wgpu代码和资源的精选列表
* 支架-lib (以前为RLTK)
  * [bracket-lib](https://github.com/amethyst/bracket-lib) 支架-lib [[bracket-lib](https:// crates.io/crates/bracket-lib)] -为Rust实现的Roguelike工具包 (RLTK)。[![Rust](https://github.com/amethyst/支架-lib/操作/工作流/rust.yml/badge.svg)](https://github.com/amethyst/支架-lib/操作/工作流/rust.yml)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) 维塔夫克斯/挑战-rs [[challonge](https:// crates.io/crates/challonge)] -Challonge REST API的客户端库。帮助组织比赛。[![CI](https://github.com/vityafx/challonge-rs/操作/工作流/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/操作/工作流/ci.yml)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) lucidscape/corange-rs — [·科兰格](https://github.com/orangeduck/Corange) 绑定
* 实体组件系统 (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) 紫水晶/规格 — 规格并行ECS
  * [legion](https://github.com/amethyst/legion) 军团 — 功能丰富的高性能ECS库，带有最少的样板 [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg？branch=master)](https://github.com/amethyst/legion/actions)
* 游戏引擎
  * [Bevy](https://github.com/bevyengine/bevy) 贝维 是一个构建在Rust中的令人耳目一新的简单数据驱动游戏引擎。- [![Crates.io](https:// img.shields.io/crates/v/bevy.svg)](https:// crates.io/crates/bevy)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg) ![板条箱.io](https:// crates.io/crates/bevy)
  * [Fyrox](https://fyrox.rs/) Fyrox — Rust游戏引擎3D [![Crates.io](https:// img.shields.io/crates/v/fyrox.svg)](https:// crates.io/crates/fyrox) [![license](https:// img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https:// img.shields.io/crates/d/fyrox.svg)](https:// crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez) ggez — 一个轻量级的游戏框架，用于以最小的摩擦制作2D游戏- [![Crates.io](https:// img.shields.io/crates/v/ggez.svg)](https:// crates.io/crates/ggez) [![license](https:// img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https:// img.shields.io/crates/d/ggez.svg)](https:// crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org) Kiss3d — 一个用Rust编写的简单，愚蠢的3d图形引擎 [![Crates.io](https:// img.shields.io/crates/d/kiss3d.svg)](https:// crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator) 氧化器 — 用Rust和WebGPU编写的实时战略游戏/引擎
  * [Piston](https://www.piston.rs/) 活塞 — [![板条箱.io](https://img.shields.io/板条箱/v/活塞.svg？style = flat-square)](https://crates.io/crates/活塞) [![板条箱](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![板条箱.io](https://img.shields.io/板条箱/d/活塞.svg)](https://crates.io/板条箱/活塞)
  * [Unrust](https://github.com/unrust/unrust) 不生锈 — unrust-基于纯锈 (webgl 2.0/原生) 游戏引擎
* [Godot](https://godotengine.org/) 戈多
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) godot-rust/gdnative [[gdnative](https:// crates.io/crates/gdnative)]-Rust绑定到Godot游戏引擎 [![CI](https://github.com/godot-rust/gdnative/操作/工作流/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/操作/工作流/full-ci.yml)
* [Raylib](https://www.raylib.com/) Raylib
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) deltaphc/raylib-rs [[raylib](https://crates.io/crates/raylib)] -raylib的Rust绑定
* [SDL](http://www.libsdl.org/) SDL [[sdl](https:// crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) brson/rust-sdl — SDL1绑定
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) Rust-SDL2/rust-sdl2 — SDL2绑定
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) jeremyletang/rust-sfml — [SFML](sfml-dev.org/) 绑定
* 技能评级
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) Atomfllder/技能等级 [[技能评级](https:// crates.io/crates/skillratings)] -Elo，Glicko-2，TrueSkill等多人游戏的技能评级算法集合。[![crates.io徽章](https:// img.shields.io/crates/v/技能评级)](https:// crates.io/crates/技能评级) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) tomassedovic/tcod-rs — 用于Rust的Libtcod绑定。
  * 警告: 不再维护
* 装饰-rs
  * [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs) vityafx/toornament-rs - Toornament.com Rust的API绑定。[![CI](https://github.com/vityafx/toinjoving-rs/操作/工作流/ci.yml/badge.svg)](https://github.com/vityafx/toinjoving-rs/操作/工作流/ci.yml) [![Crates badge](https:// img.shields.io/crates/v/toornament.svg)](https:// crates.io/crates/toornament)
* 维克托雷姆
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) VictoremWinbringer/Victorem [[Victorem](https://crates.io/crates/Victorem)] -简单的UDP游戏服务器和UDP客户端框架，用于创建简单的2D和3D在线游戏原型

### 地理空间

[[geo](https://crates.io/keywords/geo) [geo,[gis](https:// crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) DaveKram/coord_transforms [[coord_transforms](https:// crates.io/crates/coord_transforms)] -坐标转换 (二维、三维和地理空间)
* [Georust](https://github.com/georust) 乔治 — 用Rust编写的地理空间工具和库
* [MapLibre/Martin](https://github.com/maplibre/martin) 马普利布/马丁 — 支持PostGIS、MBTiles、PMTiles和sprites的地图瓦片服务器。[![CI构建](https://github.com/maplibre/martin/workflows/CI/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io版本](https:// img.shields.io/crates/v/martin.svg)](https:// crates.io/crates/martin)[![Book](https:// img.shields.io/badge/docs-book-informationional)](https://maplibre.org/martin/)
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) rust-reverse-geocoder — Rust中的快速离线反向地理编码器，灵感来自 [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) vlopes11/geomorph [[Geomoph](https://crates.io/crates/geomoph)] -UTM，LatLon和MGRS坐标之间的转换

### 图算法

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph) neo4j-labs/图形 - 高性能图形算法的库 [![图形CI状态](https:// img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main？label = CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* [petgraph/petgraph](https://github.com/petgraph/petgraph) petgraph/petgraph - Rust的图形数据结构库。[![图形CI状态](https://github.com/petgraph/petgraph/workflows/Continuous集成/badge.svg？分支 = 主)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### 图形

[[graphics](https://crates.io/keywords/graphics) [图形

* 字体
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) RazrFalcon/rustybuzz - 生锈的增量harfbuzz端口
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) 氧化还原-os/rusttype — FreeType等库的纯Rust替代品
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) gfx-rs/gfx — 用于Rust的高性能，无二进制图形API。
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) gfx-rs/wgpu - 基于gfx-hal的原生WebGPU实现.[![生成徽章](https://github.com/gfx-rs/wgpu/工作流/CI/badge.svg？分支 = 主)](https://github.com/gfx-rs/wgpu/动作)
* OpenGL [[opengl](https:// crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) brendanzab/gl-rs —
  * [glium/glium](https://github.com/glium/glium) 胶质/胶质 — Rust语言的安全OpenGL包装器
  * [glutin](https://crates.io/crates/glutin) 谷蛋白 — Rust替代 [GLFW](https://www.glfw.org/)
  * [Kiss3d](http://kiss3d.org) Kiss3d — 画简单的几何图形，用单线玩弄
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) PistonDevelopers/glfw-rs —
* PDF
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) fschutt/printpdf — PDF写作库
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) J-F-Liu/lopdf — PDF文档操作
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) kaj/rust-pdf —
  * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) 瓦姆-PDF -使用JavaScript和WASM (WebAssembly) 生成pdf文件
* [Vulkan](https://www.vulkan.org/) Vulkan [[vulkan](https://crates.io/关键字/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) 喷发 [[爆发](https:// crates.io/crates/爆发)]-[![构建徽章](https://gitlab.com/Friz64/爆发/徽章/主要/管道.svg)](https://gitlab.com/Friz64/爆发/-/管道)
  * [vulkano](https://github.com/vulkano-rs/vulkano) vulkano [[vulkano](https:// crates.io/crates/vulkano)]-

# 图形用户界面

[[gui](https://crates.io/keywords/gui) [gui

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) 自动驾驶仪-rs/自动驾驶仪-rs — 一个简单的跨平台的Rust GUI自动化库
* 可可
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) 伺服/核心-基础-rs —
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) DioxusLabs/dioxus - 一个可移植的、高性能的、符合人体工程学的框架，用于在Rust中构建跨平台的用户界面。![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [emilk/egui](https://github.com/emilk/egui) emilk/egui - 用于Rust. egui的简单，快速且高度可移植的即时模式GUI库在web上本地运行，并在您最喜欢的游戏引擎中运行。[![构建状态](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions？workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) emoon/rust_minifb — minifb是具有可选位图渲染的跨平台窗口设置。它还带有简单的鼠标和键盘输入。主要为原型设计
* [FLTK](https://www.fltk.org/) FLTK
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) fltk-rs — FLTK Rust绑定 [![Build](https://github.com/fltk-rs/workflows/Build/badge.svg？branch = master)](https://github.com/fltk-rs/actions)
* [Flutter](https://flutter.dev/) 颤振
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) 颤振-rs — 在dart & rust中构建flutter桌面应用程序。
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) fzyzcjy/flutter_rust_bridge — Flutter/Dart <-> Rust的高级内存安全绑定生成器
* [fschutt/azul](https://github.com/fschutt/azul) fschutt/azul — 一个免费的、功能的、面向IMGUI的GUI框架，用于快速开发用Rust编写的桌面应用程序，由Mozilla WebRender渲染引擎支持。
* [GTK+](https://www.gtk.org/) GTK [[gtk](https:// crates.io/keywords/gtk)]
  * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) gtk-rs/gtk4-rs - rust的GTK4绑定![CI](https://github.com/gtk-rs/gtk4-rs/工作流/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) relm — 异步，基于GTK的，GUI库，灵感来自Elm
* [iced-rs/iced](https://github.com/iced-rs/iced) 冰-rs/冰 [[iced](https://crates.io/crates/iced)] -一个专注于简单性和类型安全的用于Rust的跨平台GUI库。受到榆树的启发。
* [ImGui](https://github.com/ocornut/imgui) ImGui
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) imgui-rs — 用于ImGui的Rust绑定 [![构建状态](https://github.com/imgui-rs/工作流/ci/badge.svg？branch = master)](https://github.com/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) IUP
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) 接吻-ui — 基于IUP构建的简单UI框架
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) ivanceras/索龙-原生 - 一个真正的原生和跨平台的GUI库。一个统一的代码可以作为本机GUI，Html Web和TUI运行。
* [libui](https://github.com/andlabs/libui) libui
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) rust-native-ui/libui-rs — libui绑定。
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) 努克利尔
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) nuklear-铁锈 — Nuklear的防锈绑定
* [OrbTk](https://github.com/redox-os/orbtk) OrbTk — 轨道小部件工具包是一个多平台 (G)UI工具包，使用SDL2 [![构建和测试](https://github.com/氧化还原os/orbtk/工作流/构建/badge.svg？分支 = 开发)](https://github.com/氧化还原os/orbtk/操作)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) PistonDevelopers/conrod — 完全用Rust编写的易于使用的即时模式2D GUI库
* [Qt](https://doc.qt.io) Qt
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) cyndis/qmlrs — QtQuick绑定
  * [rust-qt](https://github.com/rust-qt) 铁锈-qt
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) woboq/qmetaobject-rs — 通过在编译时构建QMetaObject来集成Qml和Rust。
* [rise-ui](https://github.com/rise-ui/rise) rise-ui — 简单的基于组件的跨平台GUI工具包，用于开发美观且用户友好的界面。
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) 索尔维/nfd-rs — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 绑定
* [Sciter](https://sciter.com/) Sciter
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) sciter-sdk/rust-sciter — Sciter绑定 [![构建徽章](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter？svg = true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint) slint-ui/slint [slint](https:// crates.io/crates/slint) - [Slint](https:// slint.Dev/) 是一个工具包，用于高效地为嵌入式设备和桌面应用程序开发流畅的图形用户界面。[![构建状态](https://github.com/slint-ui/slint/workflows/CI/badge.svg？分支 = 主)](https://github.com/slint-ui/slint/actions？查询 = workflow:CI)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) tauri-应用程序/tauri — 使用由 [WRY](https://github.com/tauri-apps/wry) 提供支持的web前端构建更小，更快，更安全的桌面应用程序。[![测试库](https:// img.shields.io/github/workflow/status/tauri-apps/tauri/test library？标签 = 测试库)](https://github.com/tauri-apps/tauri/actions？query = workflow:"测试库")
* [tauri-apps/wry](https://github.com/tauri-apps/wry) tauri-应用程序/wry - Webview渲染库。
* [xilem](https://github.com/linebender/xilem) xilem — 数据第一锈原生ui设计工具包的继任者 [德鲁伊](https://github.com/linebender/druid)。

### 图像处理

* [abonander/img_hash](https://github.com/abonander/img_hash) abonander/img_hash — 感知图像散列和比较的平等和相似。
* [image-rs/image](https://github.com/image-rs/image) 图像-rs/图像 — 用于转换和转换图像格式的基本成像处理功能和方法
* [image-rs/imageproc](https://github.com/image-rs/imageproc) 图片-rs/imageproc — 一种基于 '图像' 库的图像处理库
* [marekm4/dominant_color](https://github.com/marekm4/dominant_color) marekm4/dominant_color [[dominant_color](https:// crates.io/crates/dominant_color)] -主色提取器![构建徽章](https://github.com/malekm4/dominant_color/actions/workflows/rust.yml/badge.svg？branch = master)
* [rust-cv/cv](https://github.com/rust-cv/cv) 铁锈-cv/cv — Rust CV是一个在Rust中实现计算机视觉算法，抽象和系统的项目。#[no_std] 在可能的情况下得到支持。![建筑徽章](https://github.com/铁锈-简历/工作流/测试/徽章.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) teovoinea/隐写术 [[隐写术](https://crates.io/crates/隐写术)] -一个简单的隐写术库
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) twistedfall/opencv-rust — OpenCV的防锈绑定

### 语言规范

* [shnewto/bnf](https://github.com/shnewto/bnf) shnewto/bnf — 用于解析Backus-Naur形式上下文无关语法的库。

### 日志记录

[[log](https://crates.io/keywords/log) [日志

* [estk/log4rs](https://github.com/estk/log4rs) estk/log4rs — 根据Java的Logback和log4j库 [![CircleCI](https://circleci.com/gh/estk/log4rs.svg？style = shield)](https://app.circleci.com/pipelines/github/estk/log4rs) 建模的高度可配置的日志框架
* [jesusprubio/leg](https://github.com/jesusprubio/leg) jesusprubio/腿 — 懒惰开发者的优雅印花。用最小的努力让你的克莱斯更好。[![构建状态](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
* [rbatis/fast_log](https://github.com/rbatis/fast_log) rbatis/fast_log — Rust异步日志高性能异步日志
* [rust-lang/log](https://github.com/rust-lang/log) rust-lang/log — Rust的日志记录实现
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) seanmonstar/漂亮的环境记录器 — 一种漂亮、易于使用的生锈记录器。
* [slog-rs/slog](https://github.com/slog-rs/slog) slog-rs/slog — 结构化、可组合的生锈日志记录
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) tokio-rs/tracing — 一个应用程序级跟踪框架，用于异步感知的结构化日志记录，错误处理，指标等 [![构建状态](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg？branch = master)](https://github.com/tokio-rs/tracing/actions？query = 工作流: CI)

### 宏

* 可爱
  * [mattgathu/cute](https://github.com/mattgathu/cute) mattgathu/可爱 — Rust中Python风格列表理解的宏。
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) Linq-in-Rust - C # 类LINQ表达式的宏和方法。[![CI](https://github.com/StardustDL/linq-in-Rust/工作流/CI/badge.svg？branch = master)](https://github.com/StardustDL/linq-in-Rust/操作？查询 = 工作流: CI)

### 标记语言

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) 拉普林纳斯/下拉-cmark — [CommonMark](https://commonmark.org/) Rust中的解析器

### 手机

* Android / iOS
  * [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios) ivanschuetz/rust_android_ios — 分别使用Rust-swig和cbindgen为Android和iOS使用共享rust lib的示例。
* 通用
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile) Geal/rust_on_mobile
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) TimNN/货物-lipo — 一个货物lipo子命令，它会自动创建一个通用库，供您的iOS应用程序使用。

### 网络编程

* 蓝牙
  * [bluez/bluer](https://github.com/bluez/bluer) 蓝色/蓝色 [[bluer](https:// crates.io/crates/bluer)] -Rust的官方BlueZ绑定。[![建造徽章] (https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg？branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) 隐蔽性/coap-rs — 用于Rust的 [约束应用协议 (CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) 库。
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) fussybeaver/护柱 — Rust中的Docker守护进程API
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) mattnenterprise/rust-ftp — 用于Rust的 [FTP](https://en.wikipedia.org/wiki/文件_传输_协议) 客户端
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic) 药膜/补品 — 支持async/await的本机gRPC客户端和服务器实现 [![Crates.io](https:// img.shields.io/crates/v/tonic)](https:// crates.io/crates/tonic)
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) tikv/grpc-rs — 基于C核心库和期货的gRPC Rust库
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) 投掷 — 使用纯文本和libcurl [![CI](https://github.com/Orange-开源/hurl/工作流/CI/badge.svg)](https://github.com/Orange-开源/hurl/actions) 运行和测试HTTP请求
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) achanda/ipnetwork — 在纯铁锈中使用ip网络的库
  * [candrew/netsim](https://github.com/canndrew/netsim) candrew/netsim — 用于网络仿真和测试的Rust库
  * [jesusprubio/online](https://github.com/jesusprubio/online) jesusprubio/在线 — 用于检查Internet连接的库 [![CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
* 低电平
  * [actix/actix](https://github.com/actix/actix) actix/actix — 演员库防锈
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) dylanmckay/协议 — 自定义TCP/UDP协议定义
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) libpnet/libpnet — 跨平台、低级网络
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) smoltcp-rs/smoltcp — 一个独立的、事件驱动的TCP/IP堆栈，专为裸机实时系统设计
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) tokio-rs/tokio — 一种网络应用框架，用于客户端和服务器的快速开发和高度可扩展的生产部署。
* 消息-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) lemunozm/message-io — 事件驱动消息库构建网络应用程序简单快捷。支持TCP，UDP和WebSockets。[![构建徽章](https:// img.shields.io/github/workflow/status/lemunozm/message-io ci)](https://github.com/lemunozm/message-io/actions？查询 = workflow:"message-io ci")
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) bytebeamio/rumqtt - 一个库，供开发人员构建通过TCP和WebSockets与 [MQTT协议](https://mqtt.org) 通信的应用程序，使用或不使用TLS。[![构建和测试](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* 纳米sg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) 液压脉冲/纳米sg.rs — [nanomsg](https://nanomsg.org/) 绑定
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) nats-io/nats.rs — NATS的Rust客户端，云原生消息传递系统。[![构建状态](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg？branch = master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) neachdainn/nng-rs [[Nng](https:// crates.io/crates/nng)] - [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) 绑定 [![构建徽章](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) mattnenterprise/rust-nntp [·nntp](https://板条箱.io/板条箱/nntp)] -一个 [·NNTP](https://en.wikipedia.org/wiki/网络_新闻_传输_协议) 客户端
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) libp2p/rust-libp2p — libp2p网络堆栈的Rust实现。[![圈CI](https://circleci.com/gh/libp2p/rust-libp2p.svg？样式 = svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) 企业/rust-pop3 [[pop3](https://crates.io/crates/pop3)] -一个 [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 客户端
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic) aws/s2n-quic - IETF QUIC协议的实现![ci](https:// img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml？branch = main)
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) cloudflare/quiche — QUIC传输协议和HTTP/3的cloudflare实现![构建](https:// img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml？branch = master)
  * [mozilla/neqo](https://github.com/mozilla/neqo) mozilla/neqo — 用Rust编写的QUIC的实现
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) 奎因-rs/奎因 — Rust中基于期货的QUIC实现 [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn？branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet) b23r0/rust-raknet — Rust的RakNet协议实现 [![构建状态](https:// img.shields.io/github/workflow/Status/b23r0/rust-raknet/rust)](https://github.com/b23r0/rust-raknet/actions/workflows/Rust.yml)
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) ENQT-GmbH/remoc [[remoc](https:// crates.io/crates/remoc)]-Remoc提供类似于Tokio的频道 (广播，mpsc，oneshot，watch) 和通过任何远程传输调用的特征。[![构建徽章](https://github.com/enqt-gmbh/remoc/actions/workflows/rust.yml/badge.svg？branch = master)](https://github.com/enqt-gmbh/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) 小窝/rpcx-rs — 用于Rust的RPC库，用于以简单明了的方式开发微服务。
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) 1c3t3a/rust-socketio [[rust_socketio](https:// crates.io/crates/rust_socketio)] -用Rust编写的 [socket.io](https:// socket.io) 客户端的实现。[![构建徽章](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) alexcrichton/ssh2-rs — [libssh2](https:// libssh2.org/) 绑定
  * [Thrussh](https://pijul.org/thrussh) Thrussh [[thrussh](https:// crates.io/crates/thrussh)] -在Rust中从头开始编写的SSH库，由 [libsodium](https://doc.libsodium.org/) 支持
* 踩踏
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) zslayton/stomp-rs — Rust中的 [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) 客户端实现
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) erickt/rust-zmq — [ZeroMQ](https://zeromq.org/) 绑定

### 解析

  * [comex/rust-shlex](https://github.com/comex/rust-shlex) comex/rust-shlex [[shlex](https:// crates.io/crates/shlex)] -将字符串拆分为shell单词，如Python的shlex。[![构建徽章](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg？branch = master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt) Folyd/robotstxt - Google的robots.txt解析器和匹配器C库的本机Rust端口
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath) freestrings/jsonpath — [JsonPath](https://goessner.net/articles/JsonPath/) 用铁锈写的引擎。Webassembly和Javascript也支持
  * [hmeyer/stl_io](https://crates.io/crates/stl_io) hmeyer/stl_io - STL (立体平版) 文件的解析器
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) kevinmehall/rust-peg — 解析表达式语法 (PEG) 解析器生成器
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) lalrpop/lalrpop — LR(1) 锈蚀解析器生成器
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) m4rw3r/chomp -快速单子风格的解析器组合器
  * [Marwes/combine](https://github.com/Marwes/combine) 马维斯/联合收割机 — 解析器组合器库
  * [nrc/zero](https://github.com/nrc/zero) nrc/零 [[零](https://crates.io/crates/zero/)] -二进制数据的零分配解析
  * [pest-parser/pest](https://github.com/pest-parser/pest) 害虫解析器/害虫 — 优雅的解析器
  * [ptal/oak](https://github.com/ptal/oak) ptal/橡木 — 一个类型化的PEG解析器生成器 (编译器插件)
  * [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) 复制/wavefront_rs — 波前OBJ格式的解析器。[![crates.io](https:// img.shields.io/crates/v/wavefront_rs.svg)](https:// crates.io/crates/wavefront_rs) [![crates.io](https:// img.shields.io/crates/d/wavefront_rs?label = crates.io下载)](https:// crates.io/crates/wavefront_rs) [![构建徽章](https://github.com/replicadse/wavefront_rs/工作流/管道/badge.svg？branch = master)](https://github.com/replicadse/wavefront_rs/操作)
  * [rust-bakery/nom](https://github.com/rust-bakery/nom) rust-面包店/nom — 解析器组合器库
  * [s-panferov/queryst](https://github.com/s-panferov/queryst) s-panferov/queryst — 受 [gs] 启发的Rust查询字符串解析库 (https://github.com/ljharb/qs#readme)
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) softdevteam/grmtools - 具有更好的纠错功能的LR解析器

### 外围设备

* 串行端口
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) 串行端口/串行端口-rs [[serialport](https://crates.io/crates/serialport)] -提供对串行端口的访问的跨平台库

### 平台特定

* 跨平台
  * [svartalf/rust-battery](https://crates.io/crates/battery) svartalf/rust-电池 — 关于笔记本电池的跨平台信息
  * [vityafx/thread-priority](https://github.com/vityafx/thread-priority/) vityafx/线程优先级 - 简单的跨平台线程优先级管理。[![CI](https://github.com/vityafx/线程优先级/操作/工作流/ci.yml/badge.svg)](https://github.com/vityafx/线程优先级/操作/工作流/ci.yml) [![Crates徽章](https:// img.shields.io/crates/v/thread-priority.svg)](https:// crates.io/crates/线程优先级)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) fubarnetes/libjail-rs [[监狱](https://crates.io/crates/监狱)] -FreeBSD监狱库的Rust实现
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) hannobraun/inotify-rs — [inotify](https://en.wikipedia.org/wiki/Inotify) 绑定 [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/) pop-os/distinst — Linux发行版安装程序
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) yaa110/rust-iptables [[iptables](https://crates.io/crates/iptables)] - [iptables](https://www.netfilter.org/projects/iptables/index.html) 绑定
* 类Unix
  * [nix-rust/nix](https://github.com/nix-rust/nix) nix-生锈/nix — 类Unix API绑定 [![Cirrus构建状态](https:// api.cirrus-ci.com/github/nix-rust/nix.svg)](https:// cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix) rustix — 安全锈绑定到POSIX/Unix/Linux/Winsock2系统系统 [![动作状态](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions？query=workflow: CI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) zargony/保险丝-rs — [保险丝](https://github.com/libfuse/libfuse) 绑定
* 窗户
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs) microsoft/windows-rs — Rust for Windows [![操作状态](https://github.com/microsoft/windows-rs/工作流/CI/badge.svg)](https://github.com/microsoft/windows-rs/操作)
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) retep998/winapi-rs — Windows API绑定 [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg？branch = dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### 脚本

[[scripting](https://crates.io/keywords/scripting) [脚本编写

* [duckscript](https://crates.io/crates/duckscript) 鸭子脚本 — [简单，可扩展和可嵌入的脚本语言。](https://github.com/sagiegurari/duckscript) [![构建徽章] (https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg？branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) fleabitdev/gamelisp — 用于Rust游戏开发的类似Lisp的脚本语言
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) 胶子-lang/胶子 —  一种小型的静态类型的函数式编程语言
* [kcl](https://github.com/kcl-lang/kcl) 氯化钾 - 一种基于约束的记录和功能语言，主要用于配置和策略场景。
* [metacall/core](https://github.com/metacall/core) metacall/核心 [[metacall](https:// crates.io/crates/metacall)] -跨平台多语言运行时，支持NodeJS、JavaScript、TypeScript、Python、Ruby、C # 、Wasm、Java、Cobol等。[![建造徽章](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) mun — 一种具有一流热重载支持的编译静态脚本语言
* [murarth/ketos](https://github.com/murarth/ketos) murarth/ketos — Lisp方言功能编程语言，用作rust的脚本和扩展语言
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) PistonDevelopers/dyon — 一种生锈的动态类型化脚本语言
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) rhaiscript/rhai — 一种小巧而快速的嵌入式脚本语言，类似于JavaScript和Rust的组合 [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) 符文-rs/符文 — 用于Rust的可嵌入动态编程语言

### 模拟

[[simulation](https://crates.io/keywords/simulation) [模拟

* [nyx-space](https://crates.io/crates/nyx-space) nyx-空间 - 高保真，快速，可靠且经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定 [![构建状态](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### 系统

* [ardaku/whoami](https://github.com/ardaku/whoami) ardaku/whoami [[whoami](https:// crates.io/crates/whoami)] - Rust crate获取当前用户和环境。[![建造徽章] (https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg？branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) 吉洛梅戈麦斯/系统信息 [[sysinfo](https:// crates.io/crates/sysinfo)] -用于获取系统信息的跨平台库 [![构建徽章] (https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg？branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) Phate6660/nixinfo [[nixinfo](https://crates.io/crates/nixinfo)] -用于收集系统信息 (例如cpu，发行版，环境，内核等) 的lib板条箱。
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) sorairolake/sysexits-rs [[sysexits](https:// crates.io/crates/sysexits)] -由 ['<sysexits.h>'] 定义的系统退出代码 (https://man.openbsd.org/sysexits)。[![CI](https://github.com/sorairolake/sysexits-rs/工作流/CI/badge.svg？分支 = 开发)](https://github.com/sorairolake/sysexits-rs/操作？查询 = 工作流: CI)

### 任务调度

* [delay-timer](https://github.com/BinChengZhao/delay-timer) 延迟定时器 — 延迟任务的时间经理。像crontab，但异步任务是可能的。
[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg) ![构建]( https://github.com/BinChengZhao/延迟-计时器/操作)

### 模板引擎

* 车把
  * [botika/yarte](https://github.com/botika/yarte) botika/yarte — Yarte代表**Y**et**A**nother**右**ust**T**emplate**E**ngine是最快的模板引擎。
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) sunng87/车把-生锈 — 带继承的车把模板引擎，自定义助手支持。
* HTML
  * [djc/askama](https://github.com/djc/askama) djc/askama — 基于Jinja的模板渲染引擎
  * [kaj/ructe](https://github.com/kaj/ructe) kaj/ructe — 生锈的HTML模板系统
  * [Keats/tera](https://github.com/Keats/tera) 济慈/tera — 基于Jinja2和Django模板语言的模板引擎。[![操作状态] (https://github.com/Keats/tera/workflows/ci/badge.svg？branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) 拉姆达-仙女/莫德 — 编译时HTML模板
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) Stepalien/恐怖表演-rs — 编译时HTML模板
* 小胡子
  * [rustache/rustache](https://github.com/rustache/rustache) rustache/rustache —

### 文本处理

* [becheran/wildmatch](https://github.com/becheran/wildmatch) becheran/wildmatch [[wildmatch](https:// crates.io/crates/wildmatch)] -与questionmark和star通配符运算符匹配的简单字符串 [![操作状态] (https://github.com/becheran/wildmatch/workflows/Build/badge.svg？branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) BurntSushi/后缀 — 线性时间后缀数组构造 (支持Unicode)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) BurntSushi/tabwriter — 弹性选项卡停止 (即文本列对齐)
* [cpc](https://github.com/probablykasper/cpc) cpc - 解析并计算数学字符串，支持单位和单位转换，从 “1 2” 到 “1% 的回合 (1光年/14!s到km/h)”。
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) Daniel-Liu-c0deb0t/triple_accel [[triple_accel](https:// crates.io/crates/triple_accel)] -使用SIMD加速的Rust编辑距离例程; 支持快速汉明、Levenshtein、受限damerau-levenshtein等距离计算和字符串搜索 [![构建徽章](https://github.com/Daniel-Liu-c0deb0t/triple_accel/工作流/测试/badge.svg？branch = master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/操作)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) fancy-regex/fancy-regex [[fancy-regex](https:// crates.io/crates/fancy-regex)] -正则表达式实现，旨在支持相对丰富的功能集，例如环视和回溯。[![板条箱](https://img.shields.io/板条箱/v/fancy-regex.svg)](https:// 板条箱.io/板条箱/花式正则表达式) [![构建徽章](https://github.com/花式正则表达式/工作流/ci/徽章.svg)](https://github.com/花式正则表达式/动作/工作流/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) greyblake/whatlang-rs — 基于三格拉姆语的自然语言检测库
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) Lucretiel/细木工 [[细木工](https://crates.io/crates/细木工)] -通用字符串可迭代连接
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) mgeisler/textwrap [[textwrap](https:// crates.io/crates/textwrap)] -自动换行 (支持断字)
* [null8626/decancer](https://github.com/null8626/decancer) null8626/decancer [[decancer](https:// crates.io/crates/decancer)] -一个微小的包，从字符串中删除常见的unicode混淆/同形文字。[![crates](https:// img.shields.io/crates/v/decancer.svg)](https:// crates.io/crates/decancer) [![生成徽章](https://github.com/null8626/decancer/工作流/CI/badge.svg)](https://github.com/null8626/decancer/操作/工作流/CI.yml)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) ps1dr3x/easy_reader — 允许在不消耗迭代器的情况下通过巨大文件行进行向前，向后和随机导航的阅读器
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) pwoolcoc/n克 [[Ngram](https://crates.io/crates/ngram)] -从任意迭代器构造 [n-gram](https://en.wikipedia.org/wiki/N-gram)
* [rust-lang/regex](https://github.com/rust-lang/regex) rust-lang/regex — 正则表达式 (RE2样式)
* [strsim-rs](https://crates.io/crates/strsim) strsim-rs — 字符串相似性度量
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) yaa110/rake-rs [[rake](https://crates.io/crates/rake)] -RAKE算法的多语言实现

### 文本搜索

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) andylokandy/simsearch-rs [[simsearch](https://crates.io/crates/simsearch)] -一种简单轻巧的模糊搜索引擎，可在内存中工作，搜索相似的字符串
* [BurntSushi/fst](https://github.com/BurntSushi/fst) BurntSushi/fst [[fst](https:// crates.io/crates/fst)]-
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) CurrySoftware/perlin [[perlin](https:// crates.io/crates/perlin)]
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) meilisearch/MeiliSearch — 超相关，即时和错字容错全文搜索API。[![构建状态](https://github.com/meilisearch/MeiliSearch/workflows/Cargo测试/badge.svg？分支 = 主)](https://github.com/meilisearch/MeiliSearch/actions)
* [tantivy](https://github.com/quickwit-oss/tantivy) 坦蒂维 [[tantivy](https:// crates.io/crates/tantivy)] -用Rust编写的马速全文搜索引擎库。[![构建状态](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### 不安全

* [zerocopy](https://crates.io/crates/zerocopy) zerocopy — 用于安全地将任意字节序列重新解释为本机Rust类型的实用程序

### 视频

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar) ffmpeg-sidecar — 在直观的迭代器界面中包装独立的FFmpeg二进制文件。[![构建状态](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml)

### 虚拟化

* [beneills/quantum](https://github.com/beneills/quantum) 贝尼尔斯/量子 — 先进的铁锈量子计算机模拟器
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) 字节联盟/wasmtime — WebAssembly [![生成状态](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)] 的独立运行时 (https://github.com/bytecodealliance/wasmtime/actions？query=workflow: CI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) 铬/平台/crosvm Crossvm-使Chrome操作系统能够在快速、安全的虚拟化环境中运行Linux应用
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) 氧化计算机/蜂胶 - 用于illumos bhyve内核模块的基于Rust的用户空间程序
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) saurvs/hypervisor-rs — OS X上的硬件加速虚拟化
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) 独角兽-rs/独角兽-rs — 独角兽CPU仿真器的Rust绑定

### Web编程
另请参阅 [we web？](https://www.arewewebyet.org) 和 [Rust web framework比较](https://github.com/flosse/rust-web-framework-比较)。

* 客户端/WASM
  * [cargo-web](https://crates.io/crates/cargo-web) 货舱-web — 客户端Web的货物子命令
  * [leptos](https://github.com/leptos-rs/leptos) leptos — Leptos是一个全栈、同构的Rust web框架，利用细粒度的反应性来构建声明式用户界面。[![crate](https:// img.shields.io/crates/v/create-rust-app.svg)](https:// crates.io/crates/leptos)
  * [sauron](https://github.com/ivanceras/sauron) 索罗 - 密切遵守Elm体系结构的客户端web框架。
  * [seed](https://seed-rs.org/) 种子 — 用于创建web应用程序的Rust框架
  * [stdweb](https://crates.io/crates/stdweb) stdweb — 客户端Web的标准库
  * [yew](https://crates.io/crates/yew) 紫杉 — 用于制作客户端web应用程序的Rust框架
* HTTP客户端
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) alexcrichton/curl-rust — [·libcurl](https:// curl.se/libcurl/) 绑定
  * [async-graphql](https://github.com/async-graphql/async-graphql) async-graphql - 在Rust [![构建状态] 中实现的GraphQL服务器库 (https://dev.azure.com/graphql-rust/graphql rust/_api/Build/Status/graphql-rust.juniper)](https://dev.azure.com/GraphQL-Rust/graphql rust/_build/latest？definitionId = 1)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) 杜马纳什/yukikaze [[yukikaze](https:// crates.io/crates/yukikaze)] -美丽优雅的Yukikaze是基于hyper的小HTTP客户端库。[![建造徽章](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh) 杜卡莱/xh - 用于发送HTTP请求的友好且快速的工具 [![crate](https:// img.shields.io/crates/v/create-rust-app.svg)](https:// crates.io/crates/xh) [![Github actions状态] (https://github.com/ducaale/xh/workflows/CI/badge.svg？branch=master)](https://github.com/ducaale/xh/actions)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) graphql-客户端 — 在Rust中输入正确的GraphQL请求和响应。[![Github操作状态](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg？branch = master)](https://github.com/graphql-rust/graphql-client/操作)
  * [hyperium/hyper](https://github.com/hyperium/hyper) hyperium/hyper — HTTP实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg？branch=master)](https://github.com/hyperium/hyper/actions？query=workflow: CI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) seanmonstar/reqwest — 用于Rust的符合人体工程学的HTTP客户端。
* HTTP服务器
  * [actix/actix-web](https://github.com/actix/actix-web) actix/actix-web — 具有websocket支持的用于Rust的轻量级异步web框架
  * [Anansi](https://github.com/saru-tora/anansi) Anansi — 用于Rust的简单全栈web框架
  * [branca](https://crates.io/crates/branca) 布兰卡 — 用于经过身份验证和加密的API令牌的Branca的纯Rust实现。
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) carllerche/tower-web [[tower-web](https://crates.io/crates/tower-web)] -快速，无样板，防锈的web框架
  * [danclive/sincere](https://github.com/danclive/sincere) danclive/真诚 — 基于超多线程的Rust (稳定) 微web框架
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) GildedHonour/frank_jwt — Rust中的JSON Web令牌实现
  * [Gotham](https://github.com/gotham-rs/gotham) 哥谭 — 灵活的web框架，不会牺牲安全性，安全性或速度。
  * [Graphul](https://github.com/graphul-rs/graphul) Graphul — 一个用Rust编写的Express风格的web框架。[![crate](https:// img.shields.io/crates/v/create-rust-app.svg)](https:// crates.io/crates/graphul)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) 车把-生锈 — 一个Iron web框架中间件
  * [hyperium/hyper](https://github.com/hyperium/hyper) hyperium/hyper — HTTP实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg？branch=master)](https://github.com/hyperium/hyper/actions？query=workflow: CI)
  * [Iron](https://github.com/iron/iron) 铁 — 一种基于中间件的服务器框架
  * [Juniper](https://github.com/graphql-rust/juniper) 杜松 — GraphQL Rust服务器库
  * [miketang84/sapper](https://github.com/miketang84/sapper) miketang84/工兵 — 基于async hyper构建的轻量级web框架，以Rust语言实现。
  * [Nickel](https://github.com/nickel-org/nickel.rs/) 镍 — 灵感来自 [Express](http://expressjs.com/)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) Ogeon/rustful — 用于Rust的RESTful web框架
  * [poem-web/poem](https://github.com/poem-web/poem) 诗歌-web/诗歌 - 一个功能齐全，易于使用的web框架与Rust编程语言。[![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rocket](https://github.com/SergioBenitez/Rocket) 火箭 — 火箭是铁锈的网络框架 (每晚)，重点是易用性、可表达性和速度
  * [Rustless](https://github.com/rustless/rustless) 无锈 — 受 [Grape](https://github.com/ruby-葡萄/葡萄) 和 [Hyper](https://github.com/hyperium/hyper) 启发的类似REST的API微框架
  * [Salvo](https://github.com/salvo-rs/salvo) 齐射 — 一个易于使用的基于hyper和tokio的web框架。[![构建构建](https://github.com/salvo-rs/salvo/workflows/CI (Linux)/badge.svg？branch = master & event = push)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) Saphir — 具有低级控制功能的渐进式web框架，没有痛苦。
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) seanmonstar/warp — 一个超级简单，可组合的web服务器框架，用于warp速度。[![crate](https:// img.shields.io/crates/v/create-rust-app.svg)](https:// crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http) tiny-http — 低级HTTP服务器库
  * [tokio/axum](https://github.com/tokio-rs/axum) tokio/axum - 符合人体工程学和模块化的web框架与Tokio，Tower和Hyper [![构建徽章](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg？branch = main)](https://github.com/tokio-rs/axum/操作/工作流/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille) tomaka/rouille — Rust中的Web框架
* 杂项
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) 货运人员 — 旨在构建可维护的，精心设计的web应用程序的web框架。
  * [causal-agent/scraper](https://github.com/causal-agent/scraper) 因果代理/刮刀 [[scraper](https:// crates.io/crates/scraper)] -使用CSS选择器进行HTML解析和查询。[![构建状态](https://github.com/因果代理/抓取器/操作/工作流/test.yml/badge.svg？分支 = 主)](https://github.com/因果代理/抓取器/操作)
  * [hominee/dyer](https://github.com/hominee/dyer) hominee/dyer [[dyer](https://crates.io/crates/dyer)]-dyer专为可靠，灵活和快速的基于请求响应的服务而设计，包括数据处理，web爬网等，提供一些友好，灵活，全面的功能，而不会影响速度。
  * [juhaku/utoipa](https://github.com/juhaku/utoipa) juhaku/utoipa - 简单，快速，代码优先，编译时生成的OpenAPI文档Rust [![crates.io](https:// img.shields.io/crates/v/utoipa.svg?label = crates.io & color = orange & logo = rust)](https:// crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [osohq/oso](https://github.com/osohq/oso) osohq/oso [[oso](https:// crates.io/crates/oso)] -嵌入在应用程序中的授权策略引擎。[![构建状态] (https://github.com/osohq/oso/workflows/Development/badge.svg？branch=main)](https://github.com/osohq/oso/actions？query=branch: 主要工作流程: 开发)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) pwoolcoc/汤 [[soup](https:// crates.io/crates/soup)] -一个类似于Python的BeautifulSoup的库，旨在实现对HTML文档的快速简便的操作和查询。[![构建状态](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) pyrossh/rust-嵌入 — 将静态资产嵌入rust二进制的宏
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) 宁静-rs/宁静 [[serenity](https://crates.io/crates/serenity)] -Discord API的Rust库
  * [softprops/openapi](https://github.com/softprops/openapi) softprops/openapi — 用于处理openapi规范文件的库
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) svix/svix-webhooks [[svix](https://crates.io/crates/svix)]-用于发送webhooks和验证签名的库。
  * [tbot](https://gitlab.com/SnejUgal/tbot) tbot [[tbot](https:// crates.io/crates/tbot)] -用Rust轻松制作很酷的电报机器人 [![管道状态](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) teloxide/teloxide - 一个优雅的电报机器人框架Rust [![构建状态](https://github.com/teloxide/teloxide/workflows/Continuous集成/badge.svg？branch = master)](https://github.com/teloxide/teloxide/actions)
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) utkarshkukreti/select.rs [[select](https://crates.io/crates/select)] -从HTML文档中提取有用数据的库，适合网页抓取。
* 反向代理
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) sozu-代理/sozu [[sozu](https:// crates.io/crates/sozu)] -HTTP反向代理。[![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg？branch = main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* 静态站点生成器
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) 钴-org/cobalt.rs — 用Rust [![构建状态](https://dev.azure.com/cobalt-org/_api/Build/Status/cobalt.rs？branchName = master)](https://dev.azure.com/cobalt-org/_build？definitionId = 2) 编写的静态站点生成器
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) 富刚强/mdblog.rs [[mdblog](https://crates.io/crates/mdblog)] -来自markdown文件的静态站点生成器。
  * [getzola/zola](https://github.com/getzola/zola) getzola/zola [[zola](https://www.getzola.org/)] -一个固执己见的静态站点生成器，内置所有内容。[![构建状态] (https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola？branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) grego/刀片式服务器 [[刀片](https://getblades.org/)] -快速死的简单静态站点发生器。
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) leven-the-blog/leven [[leven](https://crates.io/crates/leven)] -一个简单的并行化博客生成器。
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/) WebSocket
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) housleyjk/ws-rs — 轻量级、事件驱动的防锈网络套接字
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) rust-websocket — 用于处理WebSocket连接 (客户端和服务器) 的框架
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) snapview/钨矿-rs — 针对Rust的轻量级基于流的WebSocket实现
  * [vi/websocat](https://github.com/vi/websocat) vi/websocat — 用于与WebSockets交互的CLI，具有Netcat、Curl和Socat的功能。
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) vityafx/urlshortener-rs — 一个非常简单的Rust的urlshortener库。[![CI](https://github.com/vityafx/urlshortener-rs/操作/工作流/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/操作/工作流/ci.yml) [![Crates徽章](https:// img.shields.io/crates/v/urlshortener.svg)](https:// crates.io/crates/urlshortener)

# # 注册表
注册表允许您将Rust库发布为crate包，以公开和私下与其他人共享。

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry) Cloudsmith :heavy_dollar_sign: — 完全托管的软件包管理SaaS，对公共和私人货物/防锈注册中心 (以及许多其他注册中心) 具有一流的支持。有一个慷慨的免费层，也是完全免费的开源。
* [Crates](https://crates.io) 板条箱 — 铁锈/货物的官方公共登记处。
* [w4/chartered](https://github.com/w4/chartered) w4/特许 - 私有的，经过身份验证的，许可的货物注册表 [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

# # 资源

* 基准
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) TeXitoi/基准测试游戏-rs — [计算机语言基准测试游戏] 的Rust实现 (https:// benchmarksgame-team.pages.debian.net/benchmarksgame/)
* 甲板和演示文稿
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) 用Rust学习系统编程 — 由 [·朱莉娅·埃文斯提交 (https://twitter.com/@ b0rk) @ Rustconf 2016。
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) Rust: 无所畏惧! — 由 [·尼古拉斯·马塔基斯 (https://github.com/nikomatsakis) @ C呈现现在2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) 装运固体铁锈板条箱 — 由 [·迈克尔·加托齐 (https://github.com/mgattozzi) @ RustConf 2017呈现
* [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust) 发现Rust库和代码段 - 关于kandi的Rust库、作者、工具包、教程和学习资源的精选列表
* 学习
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope) Aquascope - 编译时和运行时Rust的交互式可视化
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) 真棒铁锈流 - 社区策划的关于铁锈的直播列表。
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) 真棒-铁锈-导师 — 愿意招募学员并教育他们有关生锈和编程的有用的Rust导师列表。
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/) 构建语言VM
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) CodeCrafters.io — 在Rust中构建自己的Redis、Git、Docker或SQLite
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/) 综合锈蚀 — 关于Rust基础知识的3天课程以及关于Android，裸金属Rust和并发的1天课程。提供英文、 [巴西葡萄牙文](https://google.github.io/compreley-rust/pt-BR/) 、 [韩文](https://google.github.io/compley-rust/ko/)。
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) 易生锈 - 用简单的英语学习铁锈。
  * [exercism.org](https://exercism.org/tracks/rust) exercism.org — 帮助您学习Rust新概念的编程练习。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) 动手生锈 - 通过制作游戏学习Rust的动手指南-作者 [Herbert Wolverson](https://github.com/thebracket/) (付费)
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) 惯用铁锈 —  经过同行评审的文章/演讲/回购集，教授惯用的锈。
  * [Learn Rust by 500 lines code](https://github.com/cuppar/rtd) 通过500行代码学习Rust — 通过500行代码来学习Rust，从头开始构建Todo Cli应用程序。
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) 用太多的链表学习Rust — 通过实现几种不同类型的列表结构，深入探索Rust的内存管理规则。
  * [Little Book of Rust Books](https://lborb.github.io/book/) 生锈的小书 - 精心策划的铁锈书籍和操作方法清单。
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) 编程社区精选的学习Rust资源 — 编程社区投票的推荐资源列表。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) 重构为Rust - 一本介绍Rust语言的书。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/) 生锈的例子
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) 铁锈食谱 — 一系列简单的示例，这些示例展示了使用Rust生态系统的板条箱完成常见编程任务的良好实践。
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) 专业人士的Rust — 为经验丰富的软件开发人员快速介绍Rust。
  * [Rust Gym](https://github.com/warycat/rustgym) 铁锈健身房 - Rust中解决的大量编码面试问题。
  * [Rust in Action](https://www.manning.com/books/rust-in-action) 生锈在行动 — 使用Rust进行系统编程的实践指南 [Tim McNamara](https://github.com/timClicks) (付费)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) 运动中的生锈 — [Carol Nichols](https://github.com/carols10美分) 和 [Jake Goulding](https://github.com/shepmaster) (付费) 的视频系列
  * [Rust Language Cheat Sheet](https://cheats.rs/) Rust语言作弊表
  * [Rust Online Courses at Classpert](https://classpert.com/search/rust) Rust在线课程在Classpert — 来自Classpert在线课程搜索的Rust在线课程 (付费) 列表
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) 铁锈ti ế ng vi ệ t - 用越南语学习铁锈。
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) rust-how-do-i-start - 专门用于回答以下问题的回购: “那么，Rust。我如何_start_？”。初学者只手工挑选资源和学习轨迹。
  * [rust-learning](https://github.com/ctjhoa/rust-learning) rust-学习 — 学习铁锈的有用资源集合
  * [Rustlings](https://github.com/rust-lang/rustlings) 沙沙声 — 让你习惯阅读和编写Rust代码的小练习
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) 生锈的CS - 计算机科学课程，可帮助实践在Rust中获得的学术知识
  * [stdx](https://github.com/brson/stdx) stdx — 首先学习这些板条箱作为std的扩展
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) 与Rust一起迈出第一步 - 为在Rust中构建快速有效的程序奠定知识基础。
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/) 宾夕法尼亚大学的Comp Sci Rust编程课程
* 播客
  * [New Rustacean](https://newrustacean.com) 新Rustacean — 关于学习生锈的播客
  * [Rustacean Station](https://rustacean-station.org/) Rustacean站 — 为Rust创建播客内容的社区项目
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns) Rust设计模式
* [Rust Guidelines](http://aturon.github.io/) Rust指南
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) Rust服务器、服务和应用程序-MEAP - 在Rust中构建后端服务器，服务和前端，以获取快速，可靠和可维护的应用程序。
* [Rust Subreddit](https://www.reddit.com/r/rust/) Rust Subreddit — 发布和讨论rust相关问题、文章和资源的subreddit (论坛)
* [RustBooks](https://github.com/sger/RustBooks) RustBooks — 生锈的清单
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t) RustCamp 2015会谈
* [RustViz](https://github.com/rustviz/rustviz) RustViz — 从简单的Rust程序生成可视化效果，以帮助用户更好地理解Rust寿命和借用机制。

# # 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png) ![CC0](https://creativecommons.org/publicdomain/zero/1.0/)
