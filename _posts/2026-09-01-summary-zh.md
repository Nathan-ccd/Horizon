---
layout: default
title: "Horizon Summary: 2026-09-01 (ZH)"
date: 2026-09-01
lang: zh
---

> 从 16 条内容中筛选出 12 条重要资讯。

---

1. [谷歌从 Chrome 网上应用店移除 MV2 扩展，包括 uBlock Origin](#item-1) ⭐️ 8.0/10
2. [滑动窗口注意力在长上下文推理上优于线性注意力](#item-2) ⭐️ 8.0/10
3. [动态图上的 GNN 存在时间泄漏；SynthFin-AML 强制因果边界](#item-3) ⭐️ 8.0/10
4. [Darling：在 Linux 上运行 macOS 应用](#item-4) ⭐️ 7.0/10
5. [将安防摄像头改造成自动鸟类识别系统](#item-5) ⭐️ 7.0/10
6. [Wrapture：通过猴子补丁实现追踪与测试的新 Python 库](#item-6) ⭐️ 7.0/10
7. [Entropic Scree：用于脏高维数据的新诊断工具](#item-7) ⭐️ 7.0/10
8. [Playa Phone：火人节上的功能性公用电话艺术项目](#item-8) ⭐️ 6.0/10
9. [单个 HTML 文件中的可步行 ASCII 赛博朋克城市](#item-9) ⭐️ 6.0/10
10. [苹果因 Mac Mini 和 Mac Studio 的 AI 需求措手不及](#item-10) ⭐️ 6.0/10
11. [RavynOS：融合 macOS 与 FreeBSD 的预 alpha 开源操作系统](#item-11) ⭐️ 6.0/10
12. [教授关于博士申请冷邮件的建议](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [谷歌从 Chrome 网上应用店移除 MV2 扩展，包括 uBlock Origin](https://webiterate.dev/google-removed-extensions-ublock-origin-108/) ⭐️ 8.0/10

谷歌已从 Chrome 网上应用店移除所有 Manifest V2（MV2）扩展，包括流行的广告拦截器 uBlock Origin。此次移除是向 Manifest V3 过渡的一部分，Chrome 150 计划于 6 月 30 日禁用所有剩余的 MV2 扩展。 这影响了数百万依赖 uBlock Origin 进行广告拦截和安全的用户，因为 MV3 限制了广告拦截器的功能。这引发了对企业控制网络的担忧，并促使用户考虑 Firefox 等仍支持 MV2 的替代浏览器。 uBlock Origin 被移除并非因为恶意，而是因为它与 MV3 的新安全性和性能框架不兼容。用户可以改用 uBlock Origin Lite 或其他兼容 MV3 的拦截器，但这些拦截器的过滤能力有所减弱。一旦 Chrome 150 禁用最后一个覆盖标志，此次移除将使 4000 万用户没有变通办法。

hackernews · twapi · 8月31日 21:10 · [社区讨论](https://news.ycombinator.com/item?id=49514878)

**背景**: Manifest V3 是 Chrome 新的扩展框架，旨在提高安全性、性能和隐私。它取代了旧的 Manifest V2，后者允许 uBlock Origin 等扩展使用强大的网络请求 API 来拦截广告。这一过渡一直存在争议，因为 MV3 限制了这些功能，使广告拦截器难以有效运作。谷歌自 2023 年以来一直在逐步淘汰 MV2，现在正在进行最终移除。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.chrome.com/docs/extensions/develop/migrate/checklist">Manifest V 3 migration checklist | Chrome for Developers</a></li>
<li><a href="https://www.devdigest.org/articles/chrome-150-kills-ublock-origin-manifest-v2-extensions-die-june-30">Chrome 150 Kills uBlock Origin : Manifest V 2 Extensions... | Devdigest</a></li>
<li><a href="https://www.ghostery.com/blog/ublock-origin-not-supported-chrome">uBlock Origin No Longer Supported On Chrome: Best Fixes | Ghostery</a></li>

</ul>
</details>

**社区讨论**: 社区对谷歌的决定普遍持批评态度，许多用户表示不信任并计划转向 Firefox。一些人强调广告拦截现在是一个安全问题，因为恶意广告可能欺骗不太懂技术的用户。其他人指出 Firefox 已经改进，并推荐它作为可行的替代方案，uBlock Origin 在那里效果更好。

**标签**: `#Chrome`, `#Manifest V2`, `#ad blocking`, `#uBlock Origin`, `#Firefox`

---

<a id="item-2"></a>
## [滑动窗口注意力在长上下文推理上优于线性注意力](https://www.reddit.com/r/MachineLearning/comments/1w3j1vw/slidingwindow_attention_beats_linear_on/) ⭐️ 8.0/10

一篇新的 arXiv 预印本（2608.28444）声称，带 sinks 的滑动窗口注意力（SWA）在长上下文推理基准上的表现不逊于甚至优于经过后训练的线性注意力模型。作者报告称，在 Needle-in-a-Haystack 和 BABILong 任务上，SWA 的性能高出 2 到 10 倍。 这挑战了当前为线性注意力投入复杂后训练流程的主流趋势，表明更简单的基线可能在长上下文推理上更有效。这可能会重新引导研究方向，并为 LLM 社区节省大量计算资源。 论文特别指出 Needle-in-a-Haystack 和 BABILong 基准上 SWA 表现出巨大的性能差距。作者建议改用 SWA 而不是后训练线性模型，并指出线性注意力可能需要从头训练或大量后训练才能达到 SWA 的水平。

reddit · r/MachineLearning · /u/Justgototheeffinmoon · 8月31日 16:35

**背景**: Transformer 中的标准注意力机制随序列长度呈二次方扩展，使得长上下文处理成本高昂。线性注意力变体旨在将其降低到线性扩展，但通常需要后训练来保持性能。滑动窗口注意力限制每个 token 只关注局部窗口，降低了复杂度同时保持了效率，已在 Mistral 等模型中使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2608.28444">[2608.28444] Sliding-window beats linear attention</a></li>
<li><a href="https://arxiv.org/abs/2406.10149">[2406.10149] BABILong : Testing the Limits of LLMs with Long ...</a></li>
<li><a href="https://www.digitalocean.com/community/tutorials/sliding-window-attention-efficient-long-context-models">Sliding Window Attention: Efficient Long-Context Modeling | DigitalOcean</a></li>

</ul>
</details>

**标签**: `#attention mechanisms`, `#long-context reasoning`, `#LLM efficiency`, `#arXiv preprint`, `#benchmarking`

---

<a id="item-3"></a>
## [动态图上的 GNN 存在时间泄漏；SynthFin-AML 强制因果边界](https://www.reddit.com/r/MachineLearning/comments/1w3imxy/your_gnn_is_probably_just_an_overcomplicated_mlp/) ⭐️ 8.0/10

作者发布了 SynthFin-AML v10.0，这是一个包含 10 万个节点和 120 万条边的合成反洗钱数据集，通过 3 快照时间分割来强制严格的因果边界。他们将 LightGBM 与 GraphSAGE 进行基准测试，结果显示在严格时间分割下，GraphSAGE 的 PR-AUC 为 0.881，而 LightGBM 为 0.848。 这解决了动态图 GNN 研究中一个关键的评估缺陷，即标准随机分割导致时间泄漏和性能虚高。通过提供具有严格因果边界的基准，它为时间场景下的 GNN 评估设定了更高标准，这对欺诈检测和金融交易网络等领域至关重要。 该数据集确保欺诈和零售交易金额共享相同的对数正态分布（μ=8.517，σ=0.8），以防止表格泄漏。3 快照分割使用截至第 7 天的训练边、截至第 8 天的验证边和截至第 10 天的测试边，物理上分离时间窗口以限制 GNN 的感受野。该基准已作为 PR #10774 提交给 PyTorch Geometric。

reddit · r/MachineLearning · /u/Glabmayt2075 · 8月31日 16:21

**背景**: 图神经网络（GNN）广泛用于图上的节点分类，但在动态图上，标准训练分割可能无意中包含未来边，导致时间泄漏。这使模型能够通过使用未来信息来“作弊”，导致性能被高估。SynthFin-AML 数据集旨在为反洗钱（AML）检测提供一个现实的基准，其中时间正确性至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kumo.ai/pyg/production/temporal-graphs/">Handling Time in Graph Neural Networks | PyG Guide | Kumo.ai</a></li>
<li><a href="https://profitlyai.com/no-peeking-ahead-time-aware-graph-fraud-detection/">No Peeking Ahead: Time-Aware Graph Fraud Detection - ProfitlyAI</a></li>
<li><a href="https://github.com/valiyevoktay-cmd/synthfin-aml-">GitHub - valiyevoktay-cmd/ synthfin - aml -: A graph-native Anti-Money...</a></li>

</ul>
</details>

**标签**: `#GNN`, `#temporal leakage`, `#dynamic graphs`, `#anti-money laundering`, `#dataset`

---

<a id="item-4"></a>
## [Darling：在 Linux 上运行 macOS 应用](https://www.darlinghq.org/) ⭐️ 7.0/10

Darling，一个开源兼容层，使得在 Linux 上运行 macOS 应用程序成为可能，目前针对 x86_64 架构，性能和功能完整性有限。 该项目为 Linux 用户提供了访问 macOS 专属软件的潜在途径，促进了跨平台互操作性。它可能减少对专有硬件或双启动设置的依赖，尽管目前的限制限制了其实际应用。 Darling 必须在 64 位 x86 Linux 发行版上从源代码构建，需要 Clang 11 或更高版本。它基于苹果的开源 Darwin 代码，并使用 The Cocotron 实现 Cocoa，但更新不频繁。

hackernews · Bluestein · 8月31日 22:53 · [社区讨论](https://news.ycombinator.com/item?id=49515830)

**背景**: Darling 类似于 Wine，后者在 Linux 上运行 Windows 应用程序，但 Darling 针对的是 macOS 软件。它将 macOS 系统调用和框架转换为 Linux 等效项，无需完全模拟即可原生执行。该项目仍处于早期阶段，应用兼容性和性能有限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/CynicalWilson/macOS_emu">GitHub - CynicalWilson/ macOS _emu: Darling - macOS translation...</a></li>
<li><a href="https://docs.darlinghq.org/build-instructions.html">Build instructions - Darling Docs</a></li>
<li><a href="https://emulation.gametechwiki.com/index.php/Darling">Darling - Emulation General Wiki</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了复杂的情绪：有人感叹缺乏 macOS 美感，也有人指出技术挑战和开发缓慢。一位用户提到在 ARM64 Linux 上运行 Apple Silicon 应用的潜力，但承认还很遥远。另一位指出 Darling 使用了 Apportable 等旧项目的组件，凸显了其渐进式方法。

**标签**: `#compatibility layer`, `#macOS`, `#Linux`, `#open source`, `#emulation`

---

<a id="item-5"></a>
## [将安防摄像头改造成自动鸟类识别系统](https://jasontucker.blog/how-i-turned-my-security-cameras-into-an-automatic-bird-identification-system-with-birdnet-go/) ⭐️ 7.0/10

一位开发者详细介绍了他们如何利用 BirdNET-Go 将安防摄像头改造成自动识别鸟类的系统，并提供了教程，引发了社区讨论。 该项目展示了现有技术的创造性实际应用，使鸟类识别对爱好者变得触手可及，并鼓励了创客社区的 DIY 创新。 该系统使用 BirdNET-Go（一个自托管的 AI 声景分析器）通过 RTSP 流监听安防摄像头的音频。挑战包括麦克风质量和采样率要求（BirdNET 需要 48kHz 音频）。

hackernews · speckx · 8月31日 16:47 · [社区讨论](https://news.ycombinator.com/item?id=49511856)

**背景**: BirdNET 是康奈尔大学开发的基于 AI 的声音识别工具，可以从音频录音中识别鸟类物种。BirdNET-Go 是自托管版本，可在本地运行，实现对音频流的连续实时分析。安防摄像头通常内置麦克风并提供 RTSP 流，使其成为音频采集的便捷来源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tphakala/birdnet-go/wiki/">Home · tphakala/ birdnet - go Wiki · GitHub</a></li>
<li><a href="https://birdnet.cornell.edu/">BirdNET – AI-Powered Sound ID</a></li>
<li><a href="https://selfhost.directory/project/birdnet-go">birdnet - go — self-hosted BirdNET (SaaS) alternative · selfhost.directory</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了他们的经验，例如使用支持 RTSP 流的 Unifi 门铃摄像头并添加电子墨水显示屏。一些人提到麦克风质量和采样率问题，导致硬件改造。还有人称赞 Merlin Bird ID 应用作为替代方案，一位用户提供了关于 markdown 卡片中 ASCII 块字符的技术提示。

**标签**: `#BirdNET`, `#bird identification`, `#security cameras`, `#DIY`, `#machine learning`

---

<a id="item-6"></a>
## [Wrapture：通过猴子补丁实现追踪与测试的新 Python 库](https://simonwillison.net/2026/Aug/31/introducing-wrapture/) ⭐️ 7.0/10

Graham Dumpleton（wrapt 和 mod_wsgi 的创建者）推出了 Wrapture，这是一个 Python 库，扩展了 wrapt 的猴子补丁功能，以实现对函数的追踪和覆盖，用于测试和观察。该项目仅有几周历史，包含 OpenTelemetry 支持，并提供基于配置的机制来为现有项目添加追踪。 Wrapture 为测试提供了 unittest.mock 的潜在替代方案，并为无法控制的代码添加追踪提供了途径，这对调试和可观测性很有价值。它可能成为 Python 开发者的有用工具，尤其是那些处理遗留代码或第三方代码的开发者。 Wrapture 允许包装任何函数或方法，以追踪所有访问或覆盖返回值。它包含基于 TOML 的配置化追踪机制，并支持 OpenTelemetry 导出。该项目非常年轻，所有代码和文档均由 AI 助手在 Graham 的指导下编写，他强调这不是“vibe coding”，而是经过精心设计的工程。

rss · Simon Willison · 8月31日 23:59

**背景**: 猴子补丁是 Python 中的一种技术，允许在运行时修改函数或方法的行为。wrapt 是一个流行的库，用于实现装饰器和透明对象代理的猴子补丁。追踪涉及记录程序的执行流程，通常用于调试或性能分析。Wrapture 结合了这些概念，为测试和观察提供了统一的工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Aug/31/introducing-wrapture/">Introducing wrapture | Simon Willison’s Weblog</a></li>
<li><a href="https://stackoverflow.com/questions/tagged/monkeypatching?tab=Unanswered">Unanswered ' monkeypatching ' Questions - Stack Overflow</a></li>
<li><a href="https://pymotw.com/2/sys/tracing.html">Tracing a Program As It Runs - Python Module of the Week</a></li>

</ul>
</details>

**社区讨论**: 此新闻条目未提供社区评论。

**标签**: `#Python`, `#Testing`, `#Tracing`, `#Monkeypatching`, `#Developer Tools`

---

<a id="item-7"></a>
## [Entropic Scree：用于脏高维数据的新诊断工具](https://www.reddit.com/r/MachineLearning/comments/1w3br9c/how_to_assess_if_there_is_a_strong_signal_in_your/) ⭐️ 7.0/10

一款名为 Entropic Scree 的新诊断工具已发布，它使用转换后的互信息度量来估计高维真实世界数据集中的信号强度、信噪比（SNR）、内在秩和线性充分性。该工具目前以 R 函数形式提供，Python 和 R 包即将发布。 该工具解决了应用机器学习中的一个常见痛点：评估脏的高维数据是否包含足够强的信号以用于建模。通过提供一种非参数、无分布假设的替代传统 PCA 方法，它可以帮助从业者更明智地判断数据的可用性和模型选择。 Entropic Scree 评估的是转换后的互信息度量，而不是线性方差、秩次或欧氏距离，因此对强参数或距离假设的依赖较少。它还提供探索性图谱以识别解耦的变量子网络，并作为“从垃圾到黄金”框架的实用诊断工具。

reddit · r/MachineLearning · /u/Chocolate_Milk_Son · 8月31日 12:02

**背景**: 传统的降维技术如 PCA 依赖于线性方差和欧氏距离，这对于高维、噪声或非线性数据可能产生误导。内在秩指数据的真实潜在维度，而线性充分性表示数据是否符合线性假设。该工具旨在通过使用信息论度量来克服这些限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tjleestjohn/Entropic-Scree">GitHub - tjleestjohn/ Entropic - Scree : Overcome the limits of standard...</a></li>
<li><a href="https://trendshift.io/repositories/198927">tjleestjohn/ Entropic - Scree — GitHub trending stats... | Trendshift</a></li>

</ul>
</details>

**标签**: `#data quality`, `#dimensionality reduction`, `#mutual information`, `#tabular data`, `#diagnostics`

---

<a id="item-8"></a>
## [Playa Phone：火人节上的功能性公用电话艺术项目](https://playaphone.com/) ⭐️ 6.0/10

一个名为 Playa Phone 的功能性公用电话艺术项目在火人节上设立，允许参与者从沙漠中拨打真实电话。该项目引发了社区故事和轻微的好奇心，创作者表示愿意回答问题。 该项目突显了艺术、技术与人类联系在独特节日环境中的交汇点。它展示了即使没有先进技术，简单的互动装置也能促进有意义的社会互动和社区参与。 该电话是一个功能性的公用电话，社区评论包括用户拨打真实电话并在附近经历自发事件的个人轶事。创作者 aaron42net 在评论中活跃，愿意回答有关该项目的问题。

hackernews · cutoff · 8月31日 14:52 · [社区讨论](https://news.ycombinator.com/item?id=49510514)

**背景**: 火人节是内华达沙漠一年一度的活动，以其大型艺术装置和社区驱动的精神而闻名。像 Playa Phone 这样的互动艺术项目是其中的常见元素，鼓励参与者之间的参与和社交互动。

**社区讨论**: 社区评论总体积极，用户分享使用电话的个人故事以及遇到的意外事件。一位用户对火人节的人群构成表示好奇，另一位则推广了相关应用，显示出怀旧与创业精神的混合。

**标签**: `#Burning Man`, `#art project`, `#interactive`, `#community`, `#phone`

---

<a id="item-9"></a>
## [单个 HTML 文件中的可步行 ASCII 赛博朋克城市](https://www.youtube.com/watch?v=3YtygAx_C6A) ⭐️ 6.0/10

一位开发者展示了一个完全在单个 HTML 文件中渲染的可步行 ASCII 赛博朋克城市，更新中增加了交通、室内、海拔和摩天大楼。该项目展示了基于浏览器的固定宽度字符艺术和程序生成技术。 该项目突显了基于浏览器的 ASCII 艺术的创意潜力，为复古美学提供了现代诠释。它可能激励其他开发者探索在 Web 环境中进行基于字符的渲染和程序生成，推动用简单文本字符所能实现的边界。 该城市使用浏览器中的固定宽度字符渲染，允许精确控制字体和比例。视频提到了交通、室内和摩天大楼的更新，但 GitHub 仓库与视频的关系尚不明确，一些用户报告在本地运行时渲染效果不同。

hackernews · keithcarolus · 8月31日 18:21 · [社区讨论](https://news.ycombinator.com/item?id=49512975)

**背景**: ASCII 艺术是一种使用 ASCII 标准中的可打印字符来创建图像的图形设计技术。在计算中，程序生成是一种通过算法而非手动创建数据的方法，常用于游戏和模拟。在浏览器中渲染 ASCII 艺术相比基于终端的方法具有优势，例如更好地控制字体、比例和鼠标输入。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ASCII_art">ASCII art - Wikipedia</a></li>
<li><a href="https://www.wikiwand.com/en/Procedural_generation">Procedural generation - Wikiwand</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了基于浏览器的 ASCII 艺术方法，指出与终端相比，在渲染和输入方面有更好的控制。然而，一些用户在自行运行项目时遇到了视觉差异，并对 GitHub 仓库与视频的一致性提出疑问。一位评论者建议使用块字符和抖动来改善视觉效果。

**标签**: `#ASCII art`, `#creative coding`, `#browser graphics`, `#procedural generation`, `#demo`

---

<a id="item-10"></a>
## [苹果因 Mac Mini 和 Mac Studio 的 AI 需求措手不及](https://www.macrumors.com/2026/08/30/apple-unexpected-mac-mini-and-studio-demand/) ⭐️ 6.0/10

据报道，苹果的 Mac Mini 和 Mac Studio 机型因 AI 工作负载（如本地 LLM 推理）而面临意外需求。据说该公司缺乏专门的企业 AI 战略，这凸显了一个令人惊讶的产品市场契合度。 这标志着本地 AI 处理趋势的增长，用户出于隐私、成本和速度的考虑更倾向于设备端推理。这可能促使苹果加大对 AI 硬件和开发者关系的投入，可能重塑其产品路线图。 需求归因于苹果的统一内存架构，它允许高效运行更大的模型。然而，一些分析师指出，入门级机型可能缺乏足够的存储空间来应对严肃的 AI 工作负载，而 Mac Studio 中的 M3 Ultra 仍然是强大的本地 AI 选择。

hackernews · thm · 8月31日 12:41 · [社区讨论](https://news.ycombinator.com/item?id=49508982)

**背景**: 苹果的 Mac Mini 和 Mac Studio 采用统一内存架构，CPU 和 GPU 共享同一内存池，从而可以在本地运行更大的 AI 模型。像 LM Studio 这样的工具允许用户在这些设备上运行开源 LLM。这种需求反映了向边缘 AI 的广泛转变，尽管云替代方案仍然流行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://willitrunai.com/macs/m4-mini-32gb">Mac mini M4 32GB: Best Local LLMs — VRAM & tok/s (2026)</a></li>
<li><a href="https://savvymonk.beehiiv.com/p/ai-agents-are-creating-a-mac-mini-shortage-apple-didn-t-see-coming">AI Agents Are Creating a Mac Mini Shortage Apple Didn't See Coming</a></li>
<li><a href="https://appleinsider.com/articles/26/08/31/ai-needs-more-macs-but-not-for-the-reason-you-might-assume">Why AI is driving demand for Mac mini and Mac Studio</a></li>

</ul>
</details>

**社区讨论**: 评论者持怀疑态度，怀疑这是苹果的游击营销，因为类似的故事在没有明确来源的情况下传播。一些用户分享了真实的本地 AI 用例，如强化学习训练，而另一些用户则质疑本地设置与云订阅相比的实用性。

**标签**: `#Apple`, `#AI hardware`, `#Mac Mini`, `#Mac Studio`, `#local AI`

---

<a id="item-11"></a>
## [RavynOS：融合 macOS 与 FreeBSD 的预 alpha 开源操作系统](https://ravynos.com/) ⭐️ 6.0/10

RavynOS，一个基于 Darwin 和 FreeBSD 的预 alpha 开源操作系统，再次在 Hacker News 上被提及，旨在提供 macOS 兼容性并保留 FreeBSD 的自由。该项目持续增量开发，最近的讨论引用了 2022、2023 和 2025 年的先前报道。 该项目意义重大，因为它试图将 macOS 的精致用户体验与 FreeBSD 的开源灵活性相结合，可能为那些希望获得类似 macOS 功能但不受 Apple 硬件或许可限制的用户提供替代方案。其进展可能通过展示基于 Darwin 的系统的可行性，影响更广泛的开源操作系统生态系统。 RavynOS 是预 alpha 软件，意味着它尚不稳定或功能不完整。该项目的 FAQ 通过将其与 ReactOS、GNUstep 和 Darling 进行比较来回应法律问题，并使用 Discord 进行社区交流，一些用户认为这不太方便。

hackernews · Bluestein · 8月31日 16:19 · [社区讨论](https://news.ycombinator.com/item?id=49511534)

**背景**: Darwin 是 Apple 操作系统（包括 macOS 和 iOS）的开源类 Unix 核心，结合了 NeXTSTEP、BSD 和 Mach 的代码。FreeBSD 是一个免费开源的类 Unix 操作系统，以其稳定性和性能著称。RavynOS 旨在基于这些基础构建一个桌面操作系统，模仿 macOS 的外观和感觉，同时保持完全开源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Darwin_(operating_system)">Darwin ( operating system ) - Wikipedia</a></li>
<li><a href="https://freebsdfoundation.org/freebsd-project/what-is-freebsd/">What is FreeBSD ? | FreeBSD Foundation</a></li>
<li><a href="https://www.freebsd.org/about/">About FreeBSD | The FreeBSD Project</a></li>

</ul>
</details>

**社区讨论**: 社区评论包括关于 Darwin 相对于其他内核优势的问题，一位用户询问除了 macOS 应用兼容性之外是否还有其他优势。另一位用户指出网站上没有截图，还有一位用户对使用 Discord 进行交流表示不满。讨论还涉及法律问题，一条评论引用了 FAQ，将项目与 ReactOS 和 Darling 进行比较。

**标签**: `#operating systems`, `#open source`, `#macOS compatibility`, `#FreeBSD`, `#Darwin`

---

<a id="item-12"></a>
## [教授关于博士申请冷邮件的建议](https://www.reddit.com/r/MachineLearning/comments/1w3bwci/cold_emailing_profs_about_phd_positions_read_this/) ⭐️ 6.0/10

一位教授为潜在的博士申请者分享了关于冷邮件的实用建议，指出了常见的错误，如邮件过长、研究兴趣过于笼统以及歪曲发表成果。 这些建议有助于申请者提高被导师注意的机会，在机器学习等竞争激烈的领域至关重要。同时，它鼓励诚实和深思熟虑的沟通，使学术界受益。 教授建议不要群发邮件、避免兴趣过于笼统，不要用 LLM 代替思考，并强调查看导师网站上的具体指示。他还警告不要将研讨会论文冒充会议论文，这是一个危险信号。

reddit · r/MachineLearning · /u/tariban · 8月31日 12:09

**背景**: 在许多国家，冷邮件是博士招生中的常见环节，尤其是在 STEM 领域。一封精心撰写的邮件可以打开机会之门，但常见的错误可能导致被拒绝或被忽视。了解教授的视角有助于申请者调整自己的策略。

**标签**: `#PhD applications`, `#academic advice`, `#cold emailing`, `#machine learning`

---