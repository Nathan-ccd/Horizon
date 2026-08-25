---
layout: default
title: "Horizon Summary: 2026-08-25 (ZH)"
date: 2026-08-25
lang: zh
---

> 从 20 条内容中筛选出 15 条重要资讯。

---

1. [小米 XRing O3 处理器单核追平苹果，多核超越](#item-1) ⭐️ 8.0/10
2. [MS Paint 和照片应用在 AI 图像中嵌入隐形 GUID 水印](#item-2) ⭐️ 8.0/10
3. [海洋温度创历史新高，预示气候危机加速](#item-3) ⭐️ 8.0/10
4. [IPFS 维护团队在 Shipyard 逐步收尾，项目继续](#item-4) ⭐️ 8.0/10
5. [seL4 安全证明在 AArch64 上完成](#item-5) ⭐️ 8.0/10
6. [你的可执行文件是一个 SQLite 数据库](#item-6) ⭐️ 8.0/10
7. [AI 作为空间软件生成器，创造可编程 3D 对象](#item-7) ⭐️ 8.0/10
8. [旧金山被重现为交互式 3D 网页游戏](#item-8) ⭐️ 7.0/10
9. [欧盟包装法规威胁微型企业家](#item-9) ⭐️ 7.0/10
10. [XMPP 25 周年：回顾数字独立之路](#item-10) ⭐️ 7.0/10
11. [Unbounded Labs 推出 Bart，一个基于 1931 年前英语训练的复古 LLM](#item-11) ⭐️ 7.0/10
12. [延迟校正的 Bellman 算子与因果归因用于约束强化学习](#item-12) ⭐️ 7.0/10
13. [美国公共厕所的减少](#item-13) ⭐️ 6.0/10
14. [多智能体强化学习公平比较中的超参数统一问题探讨](#item-14) ⭐️ 6.0/10
15. [AAAI 2027 承认审稿人勾结，引发地域集中担忧](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [小米 XRing O3 处理器单核追平苹果，多核超越](https://twitter.com/lemire/status/2091894299289874926) ⭐️ 8.0/10

据 Daniel Lemire 的推文，小米新款 XRing O3 芯片在单核性能上追平苹果，并在多核基准测试中超越。该芯片采用台积电 3nm 工艺，配备 10 核 CPU。 这对移动芯片行业意义重大，表明小米现在能够生产具有竞争力的高端芯片，可能对高通和联发科构成挑战。这也凸显了中国芯片制造商在全球市场的快速进步。 XRing O3 采用台积电 3nm 工艺，拥有 240 亿晶体管、16 核 GPU、LPDDR6 内存和 200 TOPS NPU。据称在 Geekbench 6.5 中，单核得分 3945，多核 15221，而苹果 M5 iPad 分别为 3556 和 15285。

hackernews · tosh · 8月24日 15:08 · [社区讨论](https://news.ycombinator.com/item?id=49420873)

**背景**: XRing O3 是小米的第二代 SoC，继 XRing O1 之后推出。它基于 ARM 架构，与联发科天玑 9500 使用的芯片类似。该芯片的性能声明基于开发板测量，实际手机性能可能因散热和功耗限制而有所不同。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nokiapoweruser.com/xiaomi-xring-o3-chip-specs-benchmarks/">Xiaomi XRING O 3 Specs & Benchmarks : 3nm TSMC, 10-Core CPU...</a></li>
<li><a href="https://www.huaweicentral.com/xiaomi-xring-o3-chip/">Xiaomi XRING O3 debuts – world’s first 3nm chip with LPDDR6 ...</a></li>
<li><a href="https://xenospectrum.com/en/xiaomi-xring-o3-lpddr6-performance/">Xiaomi's XRING O3 Keeps 3nm Process, Adds 10 CPU Cores and ...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，多核优势部分源于 10 核对比苹果的 6 核，而每瓦性能这一关键指标缺失。一些人认为这对高通和联发科构成威胁，另一些人则警告实际性能可能不及实验室结果。

**标签**: `#Xiaomi`, `#CPU`, `#Apple`, `#ARM`, `#mobile chips`

---

<a id="item-2"></a>
## [MS Paint 和照片应用在 AI 图像中嵌入隐形 GUID 水印](https://xusheng.dev/posts/reversing/mspaint_invisible_watermark/main/) ⭐️ 8.0/10

微软的画图（Paint）和照片（Photos）应用现在会在经过 AI 处理的图像中静默嵌入一个不可见的 GUID 水印，即使处理是在本地完成的。这一发现是通过逆向工程得出的，并在最近的一篇博客文章中进行了报道。 这引发了严重的隐私担忧，因为水印可用于将图像追溯到用户的微软账户，可能将匿名内容与个人身份关联起来。这也凸显了 AI 生成内容被隐形标记的更广泛趋势，这可能影响用户匿名性和数据追踪。 水印通过名为 ApplyWatermark 的函数嵌入，使用 GUID 作为水印载荷。在画图应用中，水印失败会导致图像不被返回，而在照片应用中，它会记录错误但仍返回图像。即使使用本地 AI 模型，水印也会被应用，且用户无法禁用。

hackernews · ComputerGuru · 8月24日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=49421158)

**背景**: 数字水印是一种将隐藏信息嵌入媒体以识别所有权或来源的技术。隐形水印旨在对人类不可见，但可被自动化系统检测到。微软的实现似乎是标记 AI 生成内容更广泛努力的一部分，类似于谷歌的 SynthID 和 OpenAI 的 C2PA 元数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://xusheng.dev/posts/reversing/mspaint_invisible_watermark/main/">Microsoft Paint and Photos Embed Server-Issued GUIDs as Invisible Watermarks in Locally-Generated Images :: Xusheng Li</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_watermarking">Digital watermarking - Wikipedia</a></li>
<li><a href="https://www.brookings.edu/articles/detecting-ai-fingerprints-a-guide-to-watermarking-and-beyond/">Detecting AI fingerprints: A guide to watermarking and beyond | Brookings</a></li>

</ul>
</details>

**社区讨论**: 社区评论对隐藏水印表示震惊和担忧，有人指出它可能通过向微软提出法律请求来去匿名化用户。其他人指出微软有实施不严谨的历史，例如错误地给 Azure DevOps 提交加水印，并建议在使用此类应用时保持谨慎。一些用户还报告了误报情况，即水印被错误触发。

**标签**: `#privacy`, `#watermarking`, `#Microsoft`, `#AI`, `#security`

---

<a id="item-3"></a>
## [海洋温度创历史新高，预示气候危机加速](https://www.bbc.com/news/articles/c62m4gpnp78o) ⭐️ 8.0/10

根据最近的一份报告，海洋温度已达到有记录以来的最高水平，标志着加速的气候危机又一个新的里程碑。这一纪录凸显了全球海洋变暖的速度之快。 这一纪录意义重大，因为海洋变暖会导致海平面上升、风暴加剧并破坏海洋生态系统，影响全球数十亿人。它凸显了采取气候行动和适应策略的紧迫性。 这一纪录是在 2025 年初创下的，平均海面温度超过了此前的高点。科学家将其归因于温室气体排放和正在发展的厄尔尼诺事件的共同作用，后者可能进一步加剧变暖。

hackernews · tcp_handshaker · 8月24日 19:19 · [社区讨论](https://news.ycombinator.com/item?id=49424606)

**背景**: 海洋吸收了温室气体排放产生的约 90%的多余热量，因此海洋温度是气候变化的关键指标。厄尔尼诺是一种自然气候模式，会使太平洋变暖并影响全球天气。这一纪录凸显了海洋变暖的长期趋势，而这一趋势在近几十年来一直在加速。

**社区讨论**: 评论者对政府的不作为以及问题恶化表示担忧，尤其是在美国。一些人分享了教育资源并讨论了冰融化的物理原理，而另一些人则指出厄尔尼诺可能对天气不可预测性产生影响。

**标签**: `#climate change`, `#ocean temperature`, `#environment`, `#science`, `#policy`

---

<a id="item-4"></a>
## [IPFS 维护团队在 Shipyard 逐步收尾，项目继续](https://ipshipyard.com/blog/2026-the-end-of-ipfs-at-shipyard/) ⭐️ 8.0/10

IPFS 和 libp2p 的核心维护团队 Interplanetary Shipyard 宣布，将逐步结束对 IPFS 项目的集中维护，涉及 Kubo、Helia 和 IPFS Desktop 等项目。这一转变将转向个人维护者资助，而非 Shipyard 的专门支持，但 IPFS 项目本身并未关闭。 这一变化对去中心化网络社区意义重大，标志着像 IPFS 这样的基础开源项目的维持方式发生转变，可能影响开发速度和社区信任。它也凸显了去中心化基础设施在资金和维护方面的更广泛挑战。 受影响的项目包括 Kubo、Helia、Boxo、Rainbow、IPFS Desktop、IPFS Companion、Someguy、Service Worker Gateway 和 IPFS Check，这些项目将不再有专门的维护者负责新功能或错误修复。公告澄清这不是 IPFS 的终结，而是向个人资助的过渡。

hackernews · iand · 8月24日 15:48 · [社区讨论](https://news.ycombinator.com/item?id=49421489)

**背景**: IPFS（星际文件系统）是一个用于存储和访问文件、网站、应用程序和数据的分布式系统，通过内容寻址将内容与对等节点链接。Interplanetary Shipyard 一直是 IPFS 和 libp2p 的核心维护者，但现在正在逐步结束其集中支持，转向个人资助。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ipshipyard.com/blog/2026-the-end-of-ipfs-at-shipyard/">The end of IPFS at Shipyard</a></li>
<li><a href="https://ipshipyard.com/blog/2025-shipyard-ipfs-year-in-review/">Shipyard 2025: Bringing IPFS Home</a></li>
<li><a href="https://docs.ipfs.eth.link/concepts/what-is-ipfs/">What is IPFS ? | IPFS Docs</a></li>

</ul>
</details>

**社区讨论**: 社区评论对公告的措辞表示困惑，一些人最初以为 IPFS 本身正在关闭。一位前维护者建议使用 Iroh 等替代方案，而其他人则批评对 IPNS 的专注以及使用 Google 表单收集反馈，反映出复杂情绪和对项目未来的担忧。

**标签**: `#IPFS`, `#decentralized web`, `#open source`, `#maintenance`, `#p2p`

---

<a id="item-5"></a>
## [seL4 安全证明在 AArch64 上完成](https://proofcraft.systems/news-2026/#2026-08-21) ⭐️ 8.0/10

seL4 微内核的安全证明已在 AArch64 架构上完成，标志着正式验证系统软件的一个重要里程碑。这一成就将 seL4 的验证状态扩展到了广泛使用的 64 位 ARM 平台。 这很重要，因为 AArch64 是移动、嵌入式和服务器环境中的主导架构，在其上拥有正式验证的微内核可增强关键系统的安全性保证。它可能影响汽车和国防等安全关键型行业对 seL4 的采用。 这些证明仅限于单核（unicore）配置，并且不涵盖 MCS（混合关键性系统）变体。与这类工作的标准做法一致，验证假设编译器、汇编代码和硬件是正确的。

hackernews · snvzz · 8月24日 11:32 · [社区讨论](https://news.ycombinator.com/item?id=49418255)

**背景**: seL4 是一个以正式验证著称的微内核，这意味着其实现已被数学证明与其规范一致。操作系统内核的正式验证是一个严格的过程，可确保不存在某些类别的错误，为安全关键型应用提供高保证。AArch64 是 ARM 架构的 64 位执行状态，广泛用于现代设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dl.acm.org/doi/10.1145/1629575.1629596">seL4 | Proceedings of the ACM SIGOPS 22nd symposium on Operating systems principles</a></li>
<li><a href="https://sel4.systems/Research/pdfs/comprehensive-formal-verification-os-microkernel.pdf">Comprehensive Formal Verification of an OS Microkernel</a></li>

</ul>
</details>

**社区讨论**: 社区评论既突出了这一成就，也指出了其局限性。一些用户指出，这些证明仅限于单核和非 MCS 配置，而另一些用户则注意到潜在的侧信道时序攻击可能使安全保证失效。还有关于 seL4 实际采用的讨论，提到了 GenodeOS、LionsOS 和汽车用例。

**标签**: `#seL4`, `#formal verification`, `#AArch64`, `#microkernel`, `#security`

---

<a id="item-6"></a>
## [你的可执行文件是一个 SQLite 数据库](https://simonwillison.net/2026/Aug/24/your-executable-is-a-sqlite-database/) ⭐️ 8.0/10

Farid Zakaria 提出了一种 Linux 模式，通过将 SQLite 应用 ID 设置为“SELF”并将 ELF 组件组织到 SQLite 表中，将 ELF 可执行文件嵌入 SQLite 数据库文件。自定义解释器 self-exec 提取并运行可执行文件，同时可使用 binfmt_misc 让内核直接识别此类文件。 这一技巧展示了数据库与可执行文件格式的创造性融合，可能为软件打包和分发提供新方式，使数据和代码共存于单个文件中。它可能激发可执行格式和数据嵌入领域的进一步创新，并已在系统和数据库社区引发讨论。 SQLite 应用 ID 是文件头偏移 68 字节处的 4 字节字段，此处设置为“SELF”以标记文件为结构化可执行与链接格式。ELF 组件通过特定 schema 分布在多个 SQLite 表中，self-exec 解释器（用 C 编写）提取并执行必要部分。可通过类似“printf ... > /proc/sys/fs/binfmt_misc/register”的命令注册到 binfmt_misc。

rss · Simon Willison · 8月24日 11:38

**背景**: SQLite 是一种广泛使用的嵌入式数据库，将数据存储在单个文件中，其文件头包含用于文件类型识别的应用 ID 字段。ELF 是 Linux 上的标准可执行文件格式，包含定义程序加载和运行方式的头、节和段。binfmt_misc 是 Linux 内核的一项功能，允许通过将自定义二进制格式与用户空间解释器关联来执行它们。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://fzakaria.com/2026/08/23/your-executable-is-a-sqlite-database">Your executable is a SQLite database | Farid Zakaria’s Blog</a></li>
<li><a href="https://en.wikipedia.org/wiki/Executable_and_Linkable_Format">Executable and Linkable Format - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Binfmt_misc">binfmt _ misc - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论可能称赞了这一技巧的创造性和技术深度，一些用户讨论了其对可执行格式的影响和潜在用例。其他人可能对安全性或实用性提出担忧，但总体情绪似乎是积极和好奇的。

**标签**: `#SQLite`, `#ELF`, `#Linux`, `#executable`, `#systems programming`

---

<a id="item-7"></a>
## [AI 作为空间软件生成器，创造可编程 3D 对象](https://www.reddit.com/r/MachineLearning/comments/1vxcc1h/r_using_ai_as_a_spatial_software_generator_to/) ⭐️ 8.0/10

一篇新论文提出了一种方法，利用大型语言模型（LLM）将 3D 对象生成为空间软件，使其从诞生起就具有可编程性、层级结构和动画就绪特性。作者在 nova3d.xyz 和 GitHub 仓库中提供了可视化演示和代码。 这种方法可能颠覆工业设计、游戏开发、模拟以及 AR/VR/XR 等行业，提供比传统单体网格模型更有用的 3D 对象。它预示着基于代码的 3D 生成将成为常态，利用 LLM 不断提升的空间编码能力。 生成的 3D 对象可以根据计算环境（如移动设备与强大的游戏引擎）调整外观，并在创作时包含铰链/插座关节。然而，该方法目前在创建复杂有机形状方面落后于传统 AI 3D 生成器。

reddit · r/MachineLearning · /u/mhb_11 · 8月24日 19:10

**背景**: 传统的 AI 3D 生成器通常输出难以编辑或动画化的单体网格模型。空间编程涉及将 3D 对象表示为代码，从而允许逻辑部件、层级结构和可编程性。本文探索使用 LLM 进行空间编程，以生成具有这些优势的 3D 对象。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.esri.com/en-us/capabilities/3d-gis/overview">3D GIS | 3D Mapping Software - ArcGIS - Esri</a></li>
<li><a href="https://github.com/ActiveVisionLab/Awesome-LLM-3D">Awesome-LLM-3D - GitHub</a></li>
<li><a href="https://arxiv.org/abs/2507.16524">[2507.16524] Spatial 3D-LLM: Exploring Spatial Awareness in ... SpatialLLM: A Compound 3D-Informed Design towards Spatially ... GitHub - LaVi-Lab/VG-LLM: The code for paper 'Learning from ... SpatialLM - manycore-research.github.io Spatial 3D-LLM : Exploring Spatial Awareness in 3D Vision ...</a></li>

</ul>
</details>

**社区讨论**: 鉴于技术深度和新颖性，社区讨论可能会很实质，作者积极参与。由于未提供评论，无法总结具体观点。

**标签**: `#AI`, `#3D generation`, `#spatial programming`, `#LLM`, `#computer graphics`

---

<a id="item-8"></a>
## [旧金山被重现为交互式 3D 网页游戏](https://sf.thijs.gg/) ⭐️ 7.0/10

一个基于网页的交互式 3D 旧金山重现项目已在 sf.thijs.gg 发布，利用公共数据构建，让用户可以在类似视频游戏的环境中探索城市。该项目在 Hacker News 上获得了广泛关注，获得了 309 分和 109 条评论。 该项目展示了将公共地理空间数据与现代网络技术相结合，创造沉浸式交互城市体验的潜力。它可能激发城市规划、游戏和虚拟旅游领域的进一步发展，展示了一种面向广泛受众的 3D 城市渲染新方法。 该重现包括驾驶机制和可收集的硬币，但缺乏完整的游戏叙事。用户建议了可能的增强功能，如街道名称、地标和基于地址的传送，表明该项目是一个概念验证，而非完整游戏。

hackernews · centrosphere · 8月24日 17:05 · [社区讨论](https://news.ycombinator.com/item?id=49422784)

**背景**: 3D 城市模型通常由建筑足迹、高程模型和航空影像等地理空间数据源创建。基于 Web 的查看器如 Cesium 和 3DCityDB 允许在浏览器中交互式探索这些模型。该项目利用类似数据创造了类似游戏的体验，突显了 GIS 与游戏开发的融合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/3dcitydb/3dcitydb-web-map">GitHub - 3dcitydb/3dcitydb-web-map: Cesium-based 3D viewer and JavaScript API for the 3D City Database · GitHub</a></li>
<li><a href="https://www.cybercity3d.com/">CyberCity 3D</a></li>
<li><a href="https://www.linkedin.com/posts/milos-popovic-phd-89778117_python-can-now-render-an-entire-city-in-high-quality-activity-7487208970764365824-y7Bp">Python can now render an entire city in high-quality 3 D directly from...</a></li>

</ul>
</details>

**社区讨论**: 社区反应极为积极，用户表达了对重现的情感联系，并建议改进如街道名称和 MMO 功能。一些用户报告了技术问题，如 Safari 冻结，其他人则讨论了利用该流程为 GTA 等游戏引擎创建地图的潜力。

**标签**: `#3D rendering`, `#web technology`, `#geospatial data`, `#interactive maps`, `#San Francisco`

---

<a id="item-9"></a>
## [欧盟包装法规威胁微型企业家](https://lectronz.com/u/lectronz/articles/how-europe-is-killing-makers-and-micro-entrepreneurs) ⭐️ 7.0/10

一篇文章指出，新的欧盟包装法规正在损害创客和微型企业家，在 Hacker News 上引发了超过 1000 分和 600 条评论的大讨论。讨论中强调了关于监管负担和执行不一致的担忧。 这一点很重要，因为欧盟法规可能对小企业和个人创客产生不成比例的影响，可能扼杀创新和创业精神。这场辩论也反映了欧盟统一规则与国家实施之间的更广泛紧张关系，这可能影响单一市场的有效性。 评论者指出，欧盟规则可能不适用于微型企业或通用包装，文章可能歪曲了法规。还有人指出，欧盟委员会曾希望建立中央登记处，但成员国阻止了，导致执行不一致。

hackernews · l-one-lone · 8月24日 13:05 · [社区讨论](https://news.ycombinator.com/item?id=49419237)

**背景**: 欧盟一直在更新包装和包装废弃物法规，以减少对环境的影响。这些规则通常要求生产者注册、报告并支付包装费用，这对小企业来说可能是一个负担。这场辩论凸显了在环境目标与微型企业家需求之间取得平衡的挑战。

**社区讨论**: 社区意见分歧：一些人认为文章夸大了影响，引用了欧盟 FAQ 中对微型企业的豁免，而另一些人则分享了国家实施不一致的经历。一位评论者比较了中国的做法，中国侧重于平台和物流等关键节点，并指出欧盟缺乏分阶段实施。

**标签**: `#EU regulation`, `#small business`, `#makers`, `#e-commerce`, `#policy`

---

<a id="item-10"></a>
## [XMPP 25 周年：回顾数字独立之路](https://gultsch.de/posts/25-years-of-digital-independence/) ⭐️ 7.0/10

这篇文章庆祝 XMPP（Jabber）诞生 25 周年，回顾了它在数字独立中的作用以及社区为保持其相关性所做的持续努力。文章强调了该协议的持久遗产以及 Movim 和 Fluux 等项目的工作。 这一里程碑凸显了 XMPP 在围墙花园式消息平台时代中的持续相关性，提供了一种去中心化的替代方案。对于重视开放协议、隐私和互操作性的用户和开发者来说，这很重要，并引发了关于联邦通信未来的讨论。 文章提到了 Movim 和 Fluux 等项目，它们正在积极开发 XMPP 客户端，并提到了使用 XMPP 进行代理通信和通过 jmp.chat 进行电话桥接。文章还将 XMPP 与 Matrix 进行了对比，指出 Matrix“重新发明了轮子”，可能导致供应商锁定。

hackernews · inputmice · 8月24日 15:51 · [社区讨论](https://news.ycombinator.com/item?id=49421536)

**背景**: XMPP（可扩展消息与存在协议），最初名为 Jabber，是一种开放通信协议，专为即时消息、存在信息和联系人列表维护而设计。它基于 XML，支持近实时的结构化数据交换。XMPP 在 2000 年代初由 IETF 正式标准化，曾被 Facebook 和 Google 等大公司使用，但后来被专有平台所取代。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/XMPP">XMPP - Wikipedia</a></li>
<li><a href="https://xmpp.org/about/technology-overview/">An Overview of XMPP | XMPP - The universal messaging standard</a></li>
<li><a href="https://meetfranz.com/blog/how-messaging-went-from-open-protocols-to-walled-gardens">How Messaging Went From Open Protocols to Walled Gardens · Franz</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 XMPP 的未来表示乐观，提到了 Movim 和 Fluux 等活跃项目，以及代理通信和电话桥接等实际用例。一些人感叹 Matrix 的分道扬镳，并想知道如果 Matrix 的资金投入 XMPP 会怎样。其他人则注意到近年来 XMPP 的可见度下降，并质疑其当前的采用情况。

**标签**: `#XMPP`, `#open protocols`, `#decentralization`, `#messaging`, `#history`

---

<a id="item-11"></a>
## [Unbounded Labs 推出 Bart，一个基于 1931 年前英语训练的复古 LLM](https://www.reddit.com/r/MachineLearning/comments/1vx94er/bart_a_vintage_llm_r/) ⭐️ 7.0/10

Unbounded Labs 发布了 Bart，这是一个从头训练的 2.82B 参数 LLM，基于 20.1B 个 1931 年前的英语 token，并提供了演示、文章以及开源的数据集和代码。该项目旨在测试 LLM 是否能重新发现历史上的科学见解，正如 Demis Hassabis 所提议的那样。 该项目直接回应了 AI 研究中的一个基本问题：LLM 是否能产生原创想法，还是仅仅预测下一个 token。通过基于历史文本训练，它为评估推理和创造力提供了一个独特的基准，可能影响未来 AI 驱动的科学发现方法。 Bart 在新创建的 Vintage CORE 基准套件上，在其规模下取得了最佳性能，以更小的 token 预算超越了 GPT-1900。团队还清理了哈佛大学机构图书数据集（从 242B 到 23B token），创建了 20 个复古专用基准，并发布了 416k 对 SFT 数据集，全部开源。

reddit · r/MachineLearning · /u/soggydoggy8 · 8月24日 17:20

**背景**: Google DeepMind 首席执行官 Demis Hassabis 提出，一个基于 1911 年前数据训练的 LLM 可以独立发现相对论，作为 AGI 的测试。该项目是构建仅基于 1931 年前英语文本训练的“复古”LLM 的几次尝试之一，这与现代基于互联网的语料库形成对比。目标是看看这样的模型能否推理并产生与历史科学家相当的见解，挑战 LLM 仅仅是“随机鹦鹉”的观点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://officechai.com/ai/someone-built-an-llm-to-test-out-demis-hassabis-agi-definition-of-pre-1900-science-discovering-relativity/">Someone Built An LLM To Test Out Demis Hassabis' AGI ...</a></li>
<li><a href="https://didof.dev/blog/talkie-1930-llm-reasoning/">Talkie-1930: An LLM That Has Never Heard of Computers Just...</a></li>
<li><a href="https://www.marktechpost.com/2026/04/27/meet-talkie-1930-a-13b-open-weight-llm-trained-on-pre-1931-english-text-for-historical-reasoning-and-generalization-research/">Meet Talkie-1930: A 13B Open-Weight LLM Trained on Pre - 1931 ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论可能包括对开源和严谨方法的赞扬，以及对重新发现科学见解的可行性和记忆化可能性的怀疑。一些人可能质疑基准的重要性或方法的泛化能力。

**标签**: `#LLM`, `#AI research`, `#historical text`, `#training from scratch`, `#benchmarking`

---

<a id="item-12"></a>
## [延迟校正的 Bellman 算子与因果归因用于约束强化学习](https://www.reddit.com/r/MachineLearning/comments/1vx11hz/delaycorrected_bellman_operator_causal/) ⭐️ 7.0/10

该帖子介绍了 CCPL（因果后果惩罚学习），其中包括一个延迟校正的 Bellman 算子，该算子根据后果延迟分布自适应有效折扣，并在未知随机延迟下保持收缩性证明。它还提出了一种干预后果网络（ICN），该网络基于结构因果模型标签进行预训练，估计每个动作的因果贡献以进行归因。 这项工作解决了约束强化学习中的一个关键限制：延迟和随机的后果常常被错误地归因于时间上先行的动作，导致错误的惩罚。通过提供收缩性证明和因果归因方法，它可能提高约束强化学习在反馈延迟的现实安全关键系统中的适用性。 ICN 目前需要访问环境的结构因果模型（SCM）来生成预训练标签，这限制了其在已知或可指定 SCM 的基准设置之外的适用性。该方法欢迎贡献和合作者，特别是在约束/安全强化学习和因果推断领域。

reddit · r/MachineLearning · /u/No_Cauliflower7923 · 8月24日 12:11

**背景**: 在约束强化学习中，智能体必须在最大化奖励的同时满足安全约束。标准方法假设后果是即时的且可归因于当前动作，但在许多现实场景中，违规是延迟且随机的，这使得难以正确惩罚负责的动作。Bellman 算子是强化学习中的基本工具，用于迭代更新价值函数，证明收缩性确保收敛到唯一不动点。因果推断方法，如结构因果模型，有助于将结果归因于特定动作，这在延迟设置中对于正确的信用分配至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pypi.org/project/ccpl-rl/">Causal Consequence-Penalized Learning for delayed constrained...</a></li>
<li><a href="https://web.stanford.edu/class/cme241/lecture_slides/BellmanOperators.pdf">Understanding (Exact) Dynamic Programming through Bellman ...</a></li>
<li><a href="https://ai.stackexchange.com/questions/11057/what-is-the-bellman-operator-in-reinforcement-learning">terminology - What is the Bellman operator in reinforcement learning?</a></li>

</ul>
</details>

**标签**: `#reinforcement learning`, `#constrained RL`, `#causal inference`, `#delayed feedback`, `#Bellman operator`

---

<a id="item-13"></a>
## [美国公共厕所的减少](https://daily.jstor.org/where-did-all-the-public-bathrooms-go/) ⭐️ 6.0/10

这篇文章讨论了美国公共厕所持续减少的现象，探讨了其原因和社会影响。文章强调了这一趋势如何影响日常生活和公共卫生。 公共厕所的减少是一个重要的公共政策和城市规划问题，影响每个人，尤其是弱势群体。它反映了公共空间管理和不平等方面的更广泛社会挑战。 这篇文章可能涵盖历史背景，如公共厕所的兴衰，并讨论资金削减、维护成本和社会污名等因素。它可能还会提到其他国家在公共厕所提供方面做得更好的例子。

hackernews · herbertl · 8月24日 17:07 · [社区讨论](https://news.ycombinator.com/item?id=49422800)

**背景**: 公共厕所是重要的城市基础设施，但由于预算限制和滥用问题，在许多城市逐渐减少。这个问题常被描述为“公地悲剧”，即少数人破坏了设施，影响了所有人。这导致许多人无法使用公共厕所，尤其影响无家可归者、老年人和有医疗需求的人。

**社区讨论**: HN 评论表达了沮丧和个人经历。一些用户分享了公共厕所设施更好的国家的轶事，而另一些人则批评缺乏政治意愿来资助维护。关于问题究竟是“公地悲剧”还是执法和社会责任缺失，存在争论。

**标签**: `#urban planning`, `#public policy`, `#society`, `#infrastructure`

---

<a id="item-14"></a>
## [多智能体强化学习公平比较中的超参数统一问题探讨](https://www.reddit.com/r/MachineLearning/comments/1vxfmms/hyperparameters_fine_tuning_for_marl_comparative/) ⭐️ 6.0/10

一位研究人员在 VMAS 任务上训练 PPO 变体，询问是否必须统一各模型的超参数以实现公平的架构比较，并指出统一有时会导致模型不收敛。 这一问题凸显了 MARL 研究中常见的方法论挑战：在公平比较与最优性能之间取得平衡。答案可能影响未来比较研究的设计，尤其是在对抗攻击下的鲁棒性测试方面。 研究人员提到了学习率、熵系数、KL 系数和 SGD 批大小等具体超参数。他们使用 HetGPPO 和其他 PPO 变体在 VMAS 上训练，目标是测试冻结模型在测试时对抗攻击下的鲁棒性。

reddit · r/MachineLearning · /u/ham_bam0 · 8月24日 21:10

**背景**: 在多智能体强化学习（MARL）中，公平比较不同算法通常需要严格控制超参数。然而，不同架构可能有不同的最优超参数，使得统一变得困难。VMAS 是多智能体任务的基准测试，HetGPPO 是一种基于 GNN 的异构 PPO 变体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/proroklab/HetGPPO">GitHub - proroklab/HetGPPO: Heterogeneous Multi-Robot Reinforcement Learning</a></li>
<li><a href="https://arxiv.org/html/2408.06503v2">Enhancing Heterogeneous Multi-Agent Cooperation in Decentralized MARL via GNN-driven Intrinsic Rewards</a></li>
<li><a href="https://arxiv.org/html/2412.07165v1">A Method for Evaluating Hyperparameter Sensitivity in ...</a></li>

</ul>
</details>

**标签**: `#multi-agent reinforcement learning`, `#hyperparameter tuning`, `#PPO`, `#VMAS`, `#research methodology`

---

<a id="item-15"></a>
## [AAAI 2027 承认审稿人勾结，引发地域集中担忧](https://www.reddit.com/r/MachineLearning/comments/1vwujcy/aaai_2027_reviewer_bidding_and_assignment/) ⭐️ 6.0/10

AAAI 2027 组织者发送邮件承认审稿过程中存在勾结行为，特别指出作者互相审稿的 2-cycles 现象。帖子还质疑 AAAI 是否会像以前一样发布投稿统计数据。 这一来自顶级 AI 会议的承认凸显了同行评审中的系统性诚信问题，可能影响对已发表研究的信任。同时，它也引发了对勾结行为地域集中的担忧，这可能影响全球研究人员的评审公平性。 帖子特别提到 2-cycles 现象，即论文 A 的作者审阅论文 B，而论文 B 的作者审阅论文 A。作者指出，大多数投稿来自单一国家，这增加了该国作者之间自然形成 2-cycles 的可能性，但为避免被贴上种族主义标签，未点名该国。

reddit · r/MachineLearning · /u/Fragrant_Fan_6751 · 8月24日 06:11

**背景**: 同行评审是学术出版的基石，由专家评估投稿的质量和有效性。同行评审中的勾结行为指作者协调操纵评审过程，例如互相竞标论文或形成评审圈。AAAI 是顶级 AI 会议，其对勾结行为的承认对研究界意义重大。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aaai.org/conference/aaai/aaai-27/">AAAI -27 - AAAI</a></li>
<li><a href="https://arxiv.org/html/2608.08486">Detecting Collusion in Peer Review : Drawing Inspiration from VCG...</a></li>
<li><a href="https://csconfstats.xoveexu.com/conferences/aaai/">AAAI Acceptance Rate and Submission Statistics | CS Conf Stats</a></li>

</ul>
</details>

**社区讨论**: 该帖子引发了讨论，一些评论者表达了对缺乏统计数据和潜在地域偏见的担忧。其他人指出，勾结行为多年来一直是已知问题，并对 AAAI 的承认表示赞赏，同时一些人质疑当前检测方法的有效性。

**标签**: `#AAAI`, `#peer review`, `#collusion`, `#academic integrity`, `#conference`

---