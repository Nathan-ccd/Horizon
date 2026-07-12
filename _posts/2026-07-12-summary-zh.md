---
layout: default
title: "Horizon Summary: 2026-07-12 (ZH)"
date: 2026-07-12
lang: zh
---

> 从 11 条内容中筛选出 6 条重要资讯。

---

1. [ClickHouse 通过 Peering 机制将 PgBouncer 吞吐量提升 4 倍](#item-1) ⭐️ 8.0/10
2. [VultronRetriever 模型登顶 MTEB 排行榜](#item-2) ⭐️ 8.0/10
3. [英伟达、CoreWeave 与 Nebius：GPU 热潮中的循环融资](#item-3) ⭐️ 7.0/10
4. [SQLite 中应优先使用严格表](#item-4) ⭐️ 7.0/10
5. [Ant：一个新的 JavaScript 运行时与生态系统](#item-5) ⭐️ 6.0/10
6. [通过从零重建 Redis、Git 和数据库来学习](#item-6) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ClickHouse 通过 Peering 机制将 PgBouncer 吞吐量提升 4 倍](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 8.0/10

ClickHouse 详细介绍了他们如何通过实现一种 peering 机制，将查询取消请求转发到正确的进程，从而解决多进程环境下的取消路由问题，将 PgBouncer 的吞吐量提升了 4 倍。 这一改进使 PostgreSQL 连接池能够更高效地处理更高负载，对大规模数据库部署至关重要。Peering 方法为多进程 PgBouncer 环境中长期存在的查询取消问题提供了一种新颖的解决方案。 Peering 机制需要在所有 PgBouncer 进程中配置 peer_id 和 [peers] 部分，使它们能够将取消请求转发到原始进程。此更改在 v1.21.0 版本前后不兼容。

hackernews · saisrirampur · 7月11日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是 PostgreSQL 的轻量级连接池。在多进程或多实例部署中，查询取消请求可能落在不拥有该会话的进程上，导致取消被忽略。Peering 机制通过让进程相互感知并正确转发取消请求来解决此问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pgbouncer.org/config.html">PgBouncer config</a></li>
<li><a href="https://www.pgbouncer.org/changelog.html">PgBouncer changelog</a></li>
<li><a href="https://boosterkrd.github.io/2024/08/20/Handling-Cancellation-Request.html">Handling Cancellation Request | Booster's Blog</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 Odyssey 和 pgdog 等替代方案，并提出了关于 Kubernetes 兼容性的问题。一些用户指出，在 Kubernetes 上运行多个 PgBouncer 进程很简单，但如果独立的 pod 各自独立运行，则可能不需要 peering。

**标签**: `#PostgreSQL`, `#PgBouncer`, `#database scaling`, `#connection pooling`, `#ClickHouse`

---

<a id="item-2"></a>
## [VultronRetriever 模型登顶 MTEB 排行榜](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

VultronRetriever 系列检索模型已在 HuggingFace 上发布，在 MTEB 排行榜上多个尺寸类别中均获得第一名，其中 8B 模型成为全球第一。 与之前的领先模型相比，这些模型索引存储最多缩小 16 倍，吞吐量提高 12 倍，支持在 iPhone 等边缘设备上离线进行问答和嵌入，这可能使高质量检索在移动和资源受限环境中普及。 该系列包括三个模型：VultronRetrieverPrime-8B（全球第一）、VultronRetrieverCore-4.5B（仅次于 Prime）和 VultronRetrieverFlash-0.8B（性能超越其 5 倍大小的模型）。它们采用 Hydra 架构实现后期交互检索，并在 0% 跨数据集重复和 0% 评估污染的数据集上训练。

reddit · r/MachineLearning · /u/madkimchi · 7月11日 15:22

**背景**: MTEB（大规模文本嵌入基准）是评估嵌入模型在检索、分类和聚类等任务上性能的标准公开排行榜。Hydra 架构采用的后期交互检索将查询和文档分开处理，直到最终匹配阶段，从而实现高效精确的检索。边缘 AI 是指在智能手机等设备上本地运行 AI 模型，可降低延迟并提升隐私性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/spaces/mteb/leaderboard">MTEB Leaderboard - a Hugging Face Space by mteb</a></li>
<li><a href="https://www.codesota.com/benchmarks/mteb">MTEB Leaderboard 2026: Best Embedding Models for... | CodeSOTA</a></li>
<li><a href="https://weaviate.io/blog/late-interaction-overview">An Overview of Late Interaction Retrieval Models... | Weaviate</a></li>

</ul>
</details>

**标签**: `#retrieval`, `#MTEB`, `#edge AI`, `#embedding`, `#NLP`

---

<a id="item-3"></a>
## [英伟达、CoreWeave 与 Nebius：GPU 热潮中的循环融资](https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom) ⭐️ 7.0/10

一项分析揭示了英伟达、CoreWeave 和 Nebius 之间的循环融资关系：英伟达投资 GPU 云提供商，后者再用资金购买英伟达硬件，引发可持续性担忧。 这种模式可能推高 AI 基础设施估值，若需求未能实现则产生系统性风险，影响投资者、云提供商及整个 AI 生态系统。 英伟达投资 20 亿美元获得 CoreWeave 9%股权，而 CoreWeave 计划 2026 年资本支出 350 亿美元；英伟达持股仅覆盖该支出的 5.7%，表明循环程度有限。Nebius（前 Yandex 分拆公司）同样接受英伟达投资并购买其 GPU。

hackernews · adletbalzhanov · 7月11日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=48873836)

**背景**: 循环融资指一家公司投资于客户，客户再用资金购买投资方的产品，形成自我强化的循环。在 AI 领域，英伟达在 GPU 市场的主导地位使其投资于 CoreWeave 和 Nebius 等云初创公司，这些公司随后购买英伟达硬件，可能扭曲需求信号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://computestacker.com/providers/coreweave/">CoreWeave GPU Cloud – Pricing, Specs... | ComputeStacker</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nebius_Group">Nebius Group - Wikipedia</a></li>
<li><a href="https://www.buildthisnow.com/blog/guide/mechanics/is-ai-a-bubble">Is AI a Bubble? ' Circular Financing ' in Plain English | Build This Now</a></li>

</ul>
</details>

**社区讨论**: 评论者就循环融资的重要性展开辩论：有人认为英伟达的投资仅占 CoreWeave 总资本支出的一小部分，而另一些人则警告这可能是纸牌屋。此外还讨论了每 token ROI 和企业 token 预算等盈利指标。

**标签**: `#GPU`, `#financing`, `#Nvidia`, `#cloud computing`, `#AI infrastructure`

---

<a id="item-4"></a>
## [SQLite 中应优先使用严格表](https://evanhahn.com/prefer-strict-tables-in-sqlite/) ⭐️ 7.0/10

Evan Hahn 的一篇博客文章提倡使用 SQLite 的 STRICT 表（自 3.37.0 版本引入）来强制类型安全，而不是依赖默认的灵活类型系统。 这很重要，因为严格表可以防止意外的数据类型不匹配，提高数据完整性，使 SQLite 更适合多应用或生产环境。 STRICT 表会拒绝违反列类型声明的插入或更新，但不支持所有 SQL 数据类型（如 DATE）。可以使用 ANY 类型在严格表中允许任意类型。

hackernews · ingve · 7月11日 17:33 · [社区讨论](https://news.ycombinator.com/item?id=48873940)

**背景**: SQLite 传统上使用动态类型，列类型只是建议（亲和性）而非严格约束。这种灵活性可能导致应用程序无意中存储错误类型，从而造成数据损坏。STRICT 表在 SQLite 3.37.0 中引入，对每列强制执行精确的类型规则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sqlite.org/stricttables.html">STRICT Tables</a></li>
<li><a href="https://antonz.org/sqlite-strict-tables/">STRICT tables in SQLite</a></li>
<li><a href="https://www.sqlitetutorial.net/sqlite-strict-tables/">SQLite Strict Tables</a></li>

</ul>
</details>

**社区讨论**: 评论者如 simonw 创建了工具（sqlite-utils）将非严格表转换为严格表。其他人则争论是否应将 STRICT 设为默认值，并引用了 SQLite 官方关于保留灵活类型的理由。一些用户指出缺少 DATE 等数据类型是一个限制。

**标签**: `#SQLite`, `#database`, `#type safety`, `#software engineering`

---

<a id="item-5"></a>
## [Ant：一个新的 JavaScript 运行时与生态系统](https://antjs.org/) ⭐️ 6.0/10

Ant 是一个新的 JavaScript 生态系统，包含一个拥有自有引擎的运行时、一个包管理器、一个包注册中心（ants.land）、一个部署平台以及一个桌面应用构建器（Ant Desktop）。 Ant 旨在为现有的 JavaScript 技术栈（如 Node.js 和 Electron）提供一个连贯的端到端替代方案，可能简化 JavaScript 开发者的开发和部署流程。 该运行时基于自有引擎从头构建，支持 npm 包和 TypeScript，并以单个 9 MB 二进制文件形式提供，包含 Node 兼容 API、VM 隔离沙箱和 Wasm 支持。

hackernews · theMackabu · 7月11日 20:07 · [社区讨论](https://news.ycombinator.com/item?id=48875377)

**背景**: 像 Node.js 和 Deno 这样的 JavaScript 运行时可以在浏览器之外执行 JavaScript。Ant 引入了自己的引擎和一个完整的生态系统，包括包管理器和注册中心，旨在实现连贯性并与现有工具兼容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://antjs.org/">Ant, a lightweight JavaScript runtime</a></li>
<li><a href="https://news.ycombinator.com/item?id=48875377">Show HN: Ant – A JavaScript runtime and ecosystem | Hacker News</a></li>
<li><a href="https://github.com/themackabu/ant/">GitHub - theMackabu/ant: javascript for 🐜's, a tiny runtime with big ambitions</a></li>

</ul>
</details>

**社区讨论**: 社区评论对该项目的原创性提出质疑，指出初始版本依赖于现有的 AGPL 代码库（Elk）。此外，名称与 Apache Ant 冲突也受到批评，部分人对该项目的严肃性表示怀疑。

**标签**: `#JavaScript`, `#runtime`, `#ecosystem`, `#package manager`, `#desktop`

---

<a id="item-6"></a>
## [通过从零重建 Redis、Git 和数据库来学习](https://shipthatcode.com/) ⭐️ 6.0/10

一个新的免费平台 ShipThatCode 提供基于项目的学习，用户可以从零开始重建 Redis、Git 和数据库等核心系统。 这种方法帮助开发者深入理解系统内部原理，对系统编程教育和实践技能培养很有价值。 该平台免费，不同于 CodeCrafters 等类似服务，但社区评论质疑其原创性以及内容是否由 AI 生成。

hackernews · acley · 7月11日 13:40 · [社区讨论](https://news.ycombinator.com/item?id=48871973)

**背景**: 从零重建系统是一种理解内部原理的知名学习技巧。已有如《从零构建数据库》和 James Coglan 的《构建 Git》等资源，但 ShipThatCode 将多个项目整合到一个免费平台中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://build-your-own.org/database/">Build Your Own Database From Scratch in Go | Build Your Own...</a></li>

</ul>
</details>

**社区讨论**: 评论对原创性表示怀疑，指出与 CodeCrafters 相似，并可能使用 LLM 从现有书籍中抄袭。一些用户报告注册问题，并请求支持 Zig 语言。

**标签**: `#education`, `#systems programming`, `#open source`, `#learning`

---