---
layout: default
title: "Horizon Summary: 2026-09-25 (ZH)"
date: 2026-09-25
lang: zh
---

> 从 22 条内容中筛选出 10 条重要资讯。

---

1. [F-Droid 2.0：重大重写让开源安卓应用商店焕然一新](#item-1) ⭐️ 8.0/10
2. [谷歌 Project Suncatcher 计划将机器学习基础设施送入太空](#item-2) ⭐️ 8.0/10
3. [苹果在英国撤回高级数据保护功能](#item-3) ⭐️ 8.0/10
4. [Whiteboard（YC W26）：面向人机协作软件设计的开源 IDE](#item-4) ⭐️ 7.0/10
5. [为什么肝脏的再生能力如此奇特？](#item-5) ⭐️ 7.0/10
6. [加州财富税之争：亿万富翁能否一走了之？](#item-6) ⭐️ 7.0/10
7. [arXiv 获 1720 万美元资助，转型为独立非营利组织](#item-7) ⭐️ 7.0/10
8. [NeurIPS 录用论文提前在官网可见，通知邮件尚未发出](#item-8) ⭐️ 6.0/10
9. [Reddit 用户批评 AAAI 评审质量及 AI 生成评审意见](#item-9) ⭐️ 6.0/10
10. [NeurIPS 2025 主赛道放榜：录用率 25.7%](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [F-Droid 2.0：重大重写让开源安卓应用商店焕然一新](https://f-droid.org/2026/09/24/f-droid-2.0-a-new-chapter-for-android-freedom.html) ⭐️ 8.0/10

F-Droid 发布了 2.0 版本，这是其十年来最重大的一次更新，使用 Kotlin 和 Jetpack Compose 完全重写了应用，并采用现代化的 Material Design 界面。此次改造还逐步淘汰了特权扩展（FPE），转而全面支持 Android 内置的会话安装器（session installer），使近期版本的 Android 无需 FPE 即可进行后台更新。 作为 Google Play 商店最主要的纯自由开源软件（FOSS）替代品，F-Droid 的易用性和架构直接影响着数百万注重隐私的用户安装和更新开源应用的方式。取消对 FPE 的依赖消除了长期存在的配置痛点，可能使 F-Droid 适合更广泛、技术水平较低的用户群体。 此次重写使用 Kotlin 和 Jetpack Compose；即使已安装 FPE，F-Droid 2.0 也不会使用它，而是依靠 Android 会话安装器进行后台更新。该候选版本已引发设计方面的批评，例如截图中文本对齐不佳，以及界面各区域之间缺乏视觉区分。

hackernews · daveoc64 · 9月24日 15:26 · [社区讨论](https://news.ycombinator.com/item?id=49831968)

**背景**: F-Droid 是一个面向 Android 的自由开源（FOSS）应用商店和软件仓库，功能类似于 Google Play 商店，但只托管无广告、无追踪器的自由开源应用。其特权扩展（FPE）是一个需要以特殊系统权限安装的独立组件，用于实现无人值守的后台更新，但往往难以配置。F-Droid 2.0 是该项目的首次重大重新设计，距上一次已有约十年。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/F-Droid">F-Droid - Wikipedia</a></li>
<li><a href="https://memedata.com/post/147740">F - Droid 2 . 0</a></li>
<li><a href="https://news.ycombinator.com/item?id=49831968">F - Droid 2 . 0 : A New Chapter for Android Freedom | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍欢迎此次改造以及淘汰 FPE，有人表示由于 F-Droid 界面糟糕和 FPE 配置困难，他们已转用 Droid-ify 等替代客户端。也有人批评新设计盲目追逐潮流，例如界面各区域之间缺乏视觉分隔；还有人质疑在 Google 计划收紧 Android 生态的背景下 F-Droid 的未来，以及它是否仍主要吸引开发者和高级用户。

**标签**: `#F-Droid`, `#Android`, `#open-source`, `#app-store`, `#UI/UX`

---

<a id="item-2"></a>
## [谷歌 Project Suncatcher 计划将机器学习基础设施送入太空](https://blog.google/innovation-and-ai/models-and-research/google-research/google-project-suncatcher-facts/) ⭐️ 8.0/10

谷歌宣布了 Project Suncatcher，这是一项研究性登月计划，旨在部署搭载谷歌 TPU、并通过自由空间光通信进行星间互联的太阳能卫星星座，从而在轨道上扩展机器学习算力。该计划被《纽约时报》报道，并在谷歌研究博客和一篇 arXiv 论文中详细阐述。 这一宣布表明，主要 AI 厂商正在认真探索轨道算力，以摆脱地面在土地、电力和冷却方面的限制，这可能重塑 AI 数据中心的长期经济格局与地理分布。它也会加剧与太空数据中心初创公司的竞争，并引发关于谁掌控轨道算力的战略与地缘政治问题。 根据谷歌研究博客和 2025 年 11 月 22 日的 arXiv 论文，该架构依赖搭载太阳能电池板的紧凑卫星星座、谷歌 TPU 加速芯片以及卫星间的自由空间光通信链路。关键未解难题包括真空环境下的散热、发射经济性，以及太空数据中心通常被认为比地面数据中心更昂贵这一事实。

hackernews · xnx · 9月24日 13:53 · [社区讨论](https://news.ycombinator.com/item?id=49830606)

**背景**: 太空数据中心是一种拟议概念，即利用太空太阳能和边缘计算在轨道上建设 AI 数据中心，以绕过延迟和地面限制；这一想法在历史上可追溯到 20 世纪 80 年代战略防御计划的“智能卵石”等军事架构，以及近年来太空发展局的“扩散型作战人员太空架构”。谷歌 TPU 是专为机器学习工作负载设计的定制加速芯片，而自由空间光通信则利用激光在卫星之间传输数据，无需光纤。Project Suncatcher 是谷歌将这些技术结合为可扩展轨道机器学习基础设施的登月尝试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://research.google/blog/exploring-a-space-based-scalable-ai-infrastructure-system-design/">Exploring a space-based, scalable AI infrastructure system design</a></li>
<li><a href="https://arxiv.org/html/2511.19468v1">Towards a future space-based, highly scalable AI infrastructure system design</a></li>
<li><a href="https://en.wikipedia.org/wiki/Space-based_data_center">Space-based data center</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者大多持怀疑态度，质疑轨道数据中心的物理可行性和经济性，同时提到 Starcloud 等初创公司已经发射了小型概念验证。其他人则提出散热是尚未解决的问题，猜测该项目与军事信号情报和在轨图像处理存在重叠，甚至抛出阴谋论，将其比作中央情报局的“格洛玛探索者”号。

**标签**: `#Google`, `#ML infrastructure`, `#space computing`, `#data centers`, `#Hacker News`

---

<a id="item-3"></a>
## [苹果在英国撤回高级数据保护功能](https://macanorak.com/two-tier-encryption-in-the-uk/) ⭐️ 8.0/10

苹果已在英国撤回 iCloud 的高级数据保护（ADP）功能，将 iCloud 备份、照片、备忘录和 iCloud 云盘等受影响的数据类别恢复为标准数据保护，即由苹果持有加密密钥。此举是为了回应英国政府要求访问加密用户数据的法律命令。 这一事态为科技公司如何应对政府要求加密后门树立了先例，可能在全球范围内削弱用户隐私保护。它凸显了执法访问与端到端加密之间持续存在的紧张关系，影响数百万英国用户并引发对数据安全的担忧。 ADP 通常将端到端加密从 14 个 iCloud 数据类别扩展到 23 个，但英国用户在没有 ADP 的情况下，iCloud 备份和照片等类别将失去额外保护。英国《2016 年调查权力法》第 253 条允许政府强制公司提供加密数据访问权限，苹果选择撤回该功能而非构建后门。

hackernews · ReturnoftheHack · 9月24日 10:39 · [社区讨论](https://news.ycombinator.com/item?id=49828731)

**背景**: 高级数据保护（ADP）是一项可选的 iCloud 功能，采用端到端加密，意味着只有用户的设备能解密数据，连苹果也无法访问。英国《2016 年调查权力法》常被称为“窥探者宪章”，赋予广泛的监控权力，包括发布技术能力通知，要求公司协助访问加密通信。苹果的决定是在一项法律命令之后做出的，该命令本会迫使其破坏 ADP 的安全架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://proton.me/blog/protect-data-apple-adp-uk">How to protect your data after Apple dropped ADP in the UK | Proton</a></li>
<li><a href="https://www.hrulegal.com/insights/blog/apple-uk-encryption-backdoor-investigatory-powers-tribunal-2026">Apple vs UK Encryption Backdoor Case: What's at Stake</a></li>
<li><a href="https://penbrief.com/uk-investigatory-powers-act-encryption-backdoors">The Alarming Truth About UK Investigatory Powers Act</a></li>

</ul>
</details>

**社区讨论**: 评论者强烈担忧英国政府的举动实际上为 GCHQ 创建了后门，一些人批评苹果没有像 2015 年那样抵制。其他人指出企业面临的合规噩梦和对云安全信任的侵蚀，少数人则指出 iCloud 钥匙串和健康等基线端到端加密类别仍受保护。

**标签**: `#encryption`, `#privacy`, `#UK`, `#Apple`, `#policy`

---

<a id="item-4"></a>
## [Whiteboard（YC W26）：面向人机协作软件设计的开源 IDE](https://github.com/devdotfast/whiteboard) ⭐️ 7.0/10

由 Sid、Alex、Ketan 和 Milan 四人组成的团队发布了 Whiteboard，这是一款以 MIT 许可证开源的桌面应用，让人类与 AI 智能体在共享画布上协作设计软件架构。它可接入 Claude Code、Codex 等智能体编程工具，构建于 CodeOSS 之上，并新增了用 Rust 编写的 AST 感知语义 diff 查看器以及用于追踪智能体决策的 Decision Log。 随着智能体编程加速普及，开发者越来越多地合并自己并未完全理解的 AI 生成 PR，从而积累团队所称的“认知债务”。Whiteboard 正针对这一缺口，把架构与规格层面的评审变得可视化、可交互，Salesforce 和 Modal 等公司团队已在采用这一工作流，也预示了人机协作工具可能的演进方向。 由于构建在 CodeOSS 之上，点击时序图、ER 图或智能体轨迹引用即可直接跳转到对应代码，并享有 VSCode 的快捷键与 LSP 支持。语义 diff 查看器会把新增的大型函数概括为伪代码，并折叠单元测试和大量文档改动，且可通过 WASM 插件系统自定义；不过当前 MVP 尚不支持编辑文件，团队计划未来对托管网页版收费，同时始终保持可自托管。

hackernews · sidharthkmenon · 9月24日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=49833867)

**背景**: CodeOSS 是 Visual Studio Code 的开源内核，提供编辑器、快捷键以及语言服务器协议（LSP）支持，Whiteboard 正是复用了这些能力。Claude Code 和 Codex 分别是 Anthropic 与 OpenAI 推出的智能体编程工具，能够自主阅读代码库、编辑文件并运行命令。AST 感知 diff 依据抽象语法树结构而非原始文本行来比较代码，而“slop”则指评审者不得不费力筛选的低质量 AI 生成代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://appimage.github.io/Code_OSS/">Code OSS – AppImages</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_Codex_(AI_agent)">OpenAI Codex (AI agent) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞其流式图表与模拟手绘动画是一种很可能迅速普及的技术，也有人指出 Whiteboard 确实满足了人们对更可视化、可迭代的规划方式的需求，弥补了编程智能体 Plan Mode 的不足。主要争议集中在命名上：多位用户质疑一个无法编辑文件的工具是否配得上“IDE”这一称谓；还有人担心图表准确性，举例指出某个“wait for release”转换标签与所示 diff 不符，并提醒警惕 LLM 工具的幻觉问题。

**标签**: `#open-source`, `#AI-agents`, `#software-architecture`, `#developer-tools`, `#IDE`

---

<a id="item-5"></a>
## [为什么肝脏的再生能力如此奇特？](https://dynomight.substack.com/p/liver) ⭐️ 7.0/10

一篇在 Substack 上广受讨论的文章探讨了为什么肝脏是唯一能够真正再生的内脏器官，并引用了病理学家的专业见解以及进化生物学的视角。该文在 Hacker News 上引发了热烈讨论（262 分、158 条评论），其中包括肝移植亲历者的故事以及关于伤口愈合进化权衡的争论。 理解肝脏再生机制可为再生医学、部分肝切除术和活体肝移植的手术规划以及慢性肝病的治疗提供参考。这场讨论还凸显了一个更广泛的科学问题：为什么大多数人体器官失去了再生能力，而肝脏却保留了它。 肝脏在部分肝切除或毒性损伤后能够再生，肝细胞似乎具有几乎无限的增殖能力，动物研究中甚至观察到在多达 12 次连续部分肝切除后仍能完全再生。然而，再生并非完美：在慢性疾病中，持续的伤口愈合反应会驱动纤维化，而移植的肝脏也可能以不寻常的方向重新生长。

hackernews · jbotz · 9月24日 16:23 · [社区讨论](https://news.ycombinator.com/item?id=49832938)

**背景**: 肝脏是已知唯一能够再生的内脏器官，这意味着它可以在损伤或手术切除后替换受损或丢失的组织。这一过程涉及分化成熟的肝细胞重新进入细胞周期，而在慢性损伤中，祖细胞和胆管反应也可能参与其中。进化生物学家一直在争论，为什么人类和其他哺乳动物在很大程度上失去了再生肢体等复杂结构的能力，而肝脏却保留了这种能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Liver_regeneration">Liver regeneration - Wikipedia</a></li>
<li><a href="https://vivo.colostate.edu/hbooks/pathphys/digestion/liver/regen.html">Regeneration of the Liver</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC2760508/">Hepatic wound repair - PMC - NIH</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了多种观点：一位病理学家推荐罗伯特·温伯格的《癌症生物学》作为入门读物；其他人则认为大多数器官缺乏再生能力是由于进化压力不足，并指出即使是蝾螈的再生也有局限。一位移植接受者描述了自己接受减体积肝脏并在几个月内再生的经历，而另一位评论者则反驳了人类被优化为修复皮肤和血液的说法，强调伤口愈合在临床上的重要性。

**标签**: `#biology`, `#liver-regeneration`, `#evolution`, `#medicine`, `#hackernews`

---

<a id="item-6"></a>
## [加州财富税之争：亿万富翁能否一走了之？](https://blog.landeconomics.org/p/california-is-chasing-wealth-that) ⭐️ 7.0/10

Land Economics 博客的一篇文章认为，加州拟议的财富税效果有限，因为像拉里·佩奇、谢尔盖·布林和彼得·蒂尔这样的亿万富翁可以轻易将税务居民身份迁出加州。该文在 Hacker News 上引发了 399 条评论的激烈辩论，讨论围绕土地价值税（LVT）和税收政策展开，用户 Nevermark 和 abeppu 等人提出了详细论点。 这场辩论对加州的科技工作者和软件工程师意义重大，因为拟议的 2026 年亿万富翁税可能重塑该州的税基，并影响高收入专业人士的去留。它还凸显了一个更广泛的政策问题：当资本和人才可以轻易迁移时，对流动性财富征税是否可行。 该提案被称为 2026 年加州第 40 号提案或亿万富翁税法案，如果选民在 2026 年 11 月批准，将对亿万富翁的累积财富征收一次性 5% 的税。评论者指出，富人可以通过在其他地方建立居住地来避税，一些人认为土地价值税无法转嫁给租户，但其他人对此提出异议。

hackernews · idbnstra · 9月24日 20:34 · [社区讨论](https://news.ycombinator.com/item?id=49836419)

**背景**: 土地价值税（LVT）是对土地未改良价值征收的税，不包括建筑物和改良设施。自亚当·斯密和亨利·乔治以来的经济学家都青睐 LVT，因为它不会抑制生产活动，且被认为是累进税。加州拟议的财富税针对亿万富翁的净资产，但批评者认为，与土地不同，金融财富具有流动性，可以转移到税率较低的司法管辖区。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Land_value_tax">Land value tax</a></li>
<li><a href="https://en.wikipedia.org/wiki/2026_California_Proposition_40">2026 California Proposition 40 - Wikipedia</a></li>
<li><a href="https://www.forbes.com/sites/teresaghilarducci/2025/12/29/do-wealth-taxes-really-make-billionaires-leave/">Do Billionaires Really Move To Avoid Wealth Taxes?</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：Scottn1 等人批评亿万富翁逃避应尽的份额，而 abeppu 等人则质疑 LVT 是否真能避免转嫁给租户。binlog 认为财富税是税收体系失灵的症状，grommet_kit 指出同事们正因低税率而离开加州，带走了股权和人才。

**标签**: `#tax-policy`, `#economics`, `#california`, `#wealth-tax`, `#land-value-tax`

---

<a id="item-7"></a>
## [arXiv 获 1720 万美元资助，转型为独立非营利组织](https://www.reddit.com/r/MachineLearning/comments/1wox8kt/arxiv_receives_multiyear_philanthropic/) ⭐️ 7.0/10

arXiv 在其官方博客宣布，已获得来自 Simons Foundation International、XTX Markets 和 Siegel Family Endowment 的 1720 万美元多年期慈善资助，资助周期为三到五年。这笔资金将支持 arXiv 作为独立非营利组织正式启动。 arXiv 是科学出版的基石，也是机器学习和人工智能领域最主要的预印本平台，获得稳定的多年期资助可确保其长期可持续性和独立性。这一转型还可能为其他寻求摆脱对高校和政府拨款依赖的关键开放科学基础设施提供范例。 这笔 1720 万美元的资助为期三到五年，专门用于支持平台开发、组织能力建设，以及为 arXiv 成为独立非营利组织提供基础性支持。三家资助方分别是：资助数学与基础科学研究的 Simons Foundation International、英国算法交易公司 XTX Markets，以及由 Two Sigma 联合创始人 David M. Siegel 创立的 Siegel Family Endowment。

reddit · r/MachineLearning · /u/Nunki08 · 9月24日 09:43

**背景**: arXiv 是一个免费、开放获取的论文库，研究人员会在正式同行评审和期刊发表之前，将科学论文的预印本上传到该平台；它在计算机科学、物理学和数学领域尤为重要。arXiv 最初由康奈尔大学托管和支持，后来与西蒙斯基金会合作运营。成为独立非营利组织意味着 arXiv 将在财务和组织上实现自主治理，而不再主要依赖单一大学或赞助方。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.simonsfoundation.org/">Advancing Research in Basic Science and Mathematics | Simons Foundation</a></li>
<li><a href="https://en.wikipedia.org/wiki/XTX_Markets">XTX Markets</a></li>
<li><a href="https://mk.linkedin.com/company/siegel-family-endowment">Siegel Family Endowment | LinkedIn</a></li>

</ul>
</details>

**标签**: `#arXiv`, `#open science`, `#research infrastructure`, `#philanthropy`, `#academic publishing`

---

<a id="item-8"></a>
## [NeurIPS 录用论文提前在官网可见，通知邮件尚未发出](https://www.reddit.com/r/MachineLearning/comments/1wp6oi3/neurips_accepted_papers_are_now_visible_r/) ⭐️ 6.0/10

一位 Reddit 用户报告称，在尚未收到任何官方通知邮件之前，其论文已在 NeurIPS 会议网站上显示为“accepted”（已录用），并提到评审分数为 5-4-4。该帖子表明，本届 NeurIPS 的录用结果已在会议平台上提前可见，早于正式通知的发布。 NeurIPS 是规模最大、竞争最激烈的机器学习会议之一，因此录用结果的可见时间直接影响成千上万名等待决定的研究者，这些决定关系到论文发表、职业发展和出行安排。提前可见也让作者能在官方邮件发出前就开始规划参会和准备最终稿。 所报告的 5-4-4 分数在 NeurIPS 的 1-10 评审量表上属于中等区间（其中 10 代表前 5% 的奠基性论文），说明处于边缘的分数仍可能被录用。该用户强调当时尚未收到通知邮件，表明网站更新先于官方通知。

reddit · r/MachineLearning · /u/levydawg · 9月24日 16:41

**背景**: NeurIPS（神经信息处理系统大会）是一年一度的跨学科学术会议，涵盖神经信息处理、机器学习和人工智能领域，最早于 1986 年提出，如今每年 12 月举行。论文由志愿评审人打分，录用决定通常先通过邮件通知作者，随后才对外公布。由于该会议录用门槛很高，作者们常在等待官方决定期间追踪自己的评分，并在网络社区分享录用经验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems">Conference on Neural Information Processing Systems - Wikipedia</a></li>
<li><a href="https://neurips.cc/Conferences/2013/PaperInformation/ReviewerInstructions">Reviewer Instructions</a></li>
<li><a href="https://horace.io/willmypaperbeaccepted/">Will My (NeurIPS?) Paper get Accepted?</a></li>

</ul>
</details>

**社区讨论**: 该帖子更像是一则简短的社区公告，而非技术讨论，因此没有实质性的争论；其主要价值在于分享了 5-4-4 分数仍被录用的经验，或能给其他评审分数处于边缘的作者带来一些安慰。

**标签**: `#NeurIPS`, `#machine-learning`, `#academic-conferences`, `#research-community`, `#peer-review`

---

<a id="item-9"></a>
## [Reddit 用户批评 AAAI 评审质量及 AI 生成评审意见](https://www.reddit.com/r/MachineLearning/comments/1wphteu/whats_up_with_aaai_reviewers_and_organizers_d/) ⭐️ 6.0/10

一位 Reddit 用户在 r/MachineLearning 上详细描述了其作为 AAAI 审稿人的经历，指出其评审的多篇论文存在不完整、未匿名或违反 AAAI 模板的问题，且人类审稿意见与 AI 生成的评审高度相似。该用户还提到，其针对一篇 LLM 数学论文撰写的详细评审意见被忽视，该论文仍进入第二阶段，而 AAAI 工作流程主席也未就错误指责其共同作者“不负责任”一事道歉。 这一叙述凸显了顶级 AI 会议同行评审中的系统性问题，引发了对评审质量、AI 在评审过程中日益增长的作用以及影响研究人员职业生涯的决策公平性的担忧。随着投稿量持续增长，此类问题可能削弱人们对 AAAI 及类似会议的信任。 该用户观察到部分论文缺少必要章节、图表或代码，其中一篇论文未匿名且不符合 AAAI 模板。他们还指出，自己最详尽的一篇评审是针对一篇 LLM 数学论文，该论文尽管参考文献不足、论述不清仍进入下一轮，而其他论文仅收到两行评审意见。

reddit · r/MachineLearning · /u/OutsideSimple4854 · 9月25日 00:09

**背景**: AAAI 是人工智能领域领先的国际会议之一，在顶级 AI 出版物中名列前茅。与 NeurIPS 和 ICML 等其他主要会议一样，它使用 AI 算法将论文分配给审稿人，并采用多阶段评审流程。AAAI 评审流程包括合规筛查，在评审前移除不合规的投稿，审稿人需遵守伦理准则并使用官方 AAAI 模板。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AAAI_Conference_on_Artificial_Intelligence">AAAI Conference on Artificial Intelligence</a></li>
<li><a href="https://aaai.org/conference/aaai/aaai-26/review-process/">AAAI -26 Review Process - AAAI</a></li>
<li><a href="https://phdflow.ai/guides/aaai-review-process-explained">AAAI review process : the rejection you cannot answer</a></li>

</ul>
</details>

**社区讨论**: 该 Reddit 帖子引发了讨论，多位参与者分享了类似经历，表明所提出的问题并非个例，反映了机器学习社区对同行评审流程的更广泛担忧。

**标签**: `#peer-review`, `#AAAI`, `#machine-learning`, `#academic-publishing`, `#community-discussion`

---

<a id="item-10"></a>
## [NeurIPS 2025 主赛道放榜：录用率 25.7%](https://www.reddit.com/r/MachineLearning/comments/1wpagoe/neurips_main_track_decision_emails_are_sent_d/) ⭐️ 6.0/10

NeurIPS 2025 主赛道（Main Track）的录用决定邮件已发出，30,709 篇有效投稿中有 7,900 篇被录用，录用率为 25.7%。其中 112 篇被选为口头报告（Oral），292 篇被选为亮点报告（Spotlight）。 NeurIPS 是机器学习和人工智能领域的旗舰会议之一，其录用数据被广泛视为衡量该领域研究规模与竞争激烈程度的晴雨表。这一结果直接影响数千名研究者的论文发表记录、职业发展以及 12 月参会行程安排。 仅有 112 篇论文（约占录用论文的 1.4%）获得口头报告资格，292 篇获得亮点报告资格，这意味着绝大多数录用论文将以海报（Poster）形式展示。25.7% 的录用率基于 30,709 篇有效投稿计算，不包含被直接拒稿或撤稿的论文。

reddit · r/MachineLearning · /u/Invariant_n_Cauchy · 9月24日 19:02

**背景**: NeurIPS（神经信息处理系统大会）创办于 1987 年，如今已发展为一个多赛道的跨学科年度会议，涵盖机器学习、人工智能、统计学和计算神经科学等方向。主赛道（Main Track）是规模最大、竞争最激烈的赛道，而 2021 年新增的数据集与基准赛道（Datasets and Benchmarks Track）采用类似的评审流程。论文通常根据审稿人和领域主席的推荐被标记为口头报告或亮点报告。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems">Conference on Neural Information Processing Systems</a></li>
<li><a href="https://neurips.cc/Conferences/2025">2025 Conference - neurips.cc</a></li>
<li><a href="https://wiki.eventhosts.cc/topics/main-conference/orals-and-spotlights">Orals and Spotlights | Wiki.EventHosts NeurIPS /ICML/ICLR/CVPR...</a></li>

</ul>
</details>

**标签**: `#NeurIPS`, `#machine-learning`, `#academic-conference`, `#research-community`, `#peer-review`

---