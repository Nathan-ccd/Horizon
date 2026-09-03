---
layout: default
title: "Horizon Summary: 2026-09-03 (ZH)"
date: 2026-09-03
lang: zh
---

> 从 21 条内容中筛选出 16 条重要资讯。

---

1. [Meta 的 Muse Spark 1.3 登顶 DeepSWE，赢得开发者好评](#item-1) ⭐️ 8.0/10
2. [谷歌发布 Gemini 3.8 Flash 及 Cyber 版本](#item-2) ⭐️ 8.0/10
3. [AI 搜索引擎引用 21.5 万个机器生成的“最佳软件”页面](#item-3) ⭐️ 8.0/10
4. [世界最大暗物质探测器探测到单个异常粒子事件](#item-4) ⭐️ 8.0/10
5. [Paint.NET 借助 AI 从头重写 Direct2D 以支持 WINE](#item-5) ⭐️ 8.0/10
6. [Perplexity 开源面向 Qwen 3.6 的 Mac 推理服务器](#item-6) ⭐️ 8.0/10
7. [谷歌在美国反垄断案中避免广告技术业务拆分](#item-7) ⭐️ 7.0/10
8. [Fable 5.1 世界建模：AI 3D 世界生成工具](#item-8) ⭐️ 7.0/10
9. [Mistral 用户争论默认选择加入数据训练](#item-9) ⭐️ 7.0/10
10. [Anthropic 发布 Claude 系统提示词，新增歌词限制](#item-10) ⭐️ 7.0/10
11. [H3-World：语言原生控制的视频生成](#item-11) ⭐️ 7.0/10
12. [DeepSeek-V4-Flash-Vision-Exp 视觉支持合并，Unsloth GGUF 量化可用](#item-12) ⭐️ 7.0/10
13. [衰老大脑融合记忆而非遗忘](#item-13) ⭐️ 6.0/10
14. [llm-gemini 0.34 新增对 Gemini 3.8 Flash 的支持](#item-14) ⭐️ 6.0/10
15. [GLM 5.3 Flash 在本地生成《我的世界》黑洞模组](#item-15) ⭐️ 6.0/10
16. [将 Q8 N-gram 替换进 IQ4 Qwen 未出现速度下降](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Meta 的 Muse Spark 1.3 登顶 DeepSWE，赢得开发者好评](https://developer.meta.com/ai/models/muse-spark/) ⭐️ 8.0/10

Meta 发布了 Muse Spark 1.3，这是一个针对智能体工作流和竞技编程优化的新 AI 模型，在 DeepSWE 上取得了 75.4 分，为目前最高分。该模型还以低成本著称，一次测试运行仅需 4.2266 美分。 此次发布标志着 Meta 在竞争激烈的 AI 编程模型领域强势发力，提供了一个高性能且价格实惠的选择，可能促使其他提供商降低价格。这也表明开放权重模型在特定基准测试上可以媲美专有模型，惠及开发者及整个 AI 生态系统。 Muse Spark 1.3 针对智能体工作流训练，并针对竞技编程优化，具有更高的首次尝试准确率和可靠的工具调用能力。它还具备“最大推理”功能，用于处理具有挑战性的推理和智能体任务，并且 Meta 提供了“贡献者”定价层级，明确说明他们会使用用户数据进行训练。

hackernews · bvaldivielso · 9月2日 19:35 · [社区讨论](https://news.ycombinator.com/item?id=49541256)

**背景**: Muse Spark 是 Meta 通过其 Meta 超级智能实验室（MSL）开发的大型语言模型（LLM），于 2026 年 4 月首次推出。DeepSWE 是 Datacurve 推出的一个长期软件工程基准测试，用于测试编码智能体在活跃开源仓库中解决真实未解决问题，要求它们阅读错误报告、编辑代码并通过基于程序的验证器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepswe.datacurve.ai/">DeepSWE</a></li>
<li><a href="https://developer.meta.com/ai/models/muse-spark/">Muse Spark 1.3 | Meta</a></li>
<li><a href="https://research.meta.ai/blog/introducing-muse-spark-1-3">Introducing Muse Spark 1.3 | Meta AI Research</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了热情，有人指出该模型成本低且 DeepSWE 得分高，还有人称赞 Meta 在数据训练定价上的透明度。一位开发者分享了一项实际测试，显示与上一版本相比，SVG 生成质量有所提升，而另一位则强调该模型在非前沿任务中的实用性及其尊重用户的行为。

**标签**: `#AI`, `#Meta`, `#Muse Spark`, `#LLM`, `#benchmarks`

---

<a id="item-2"></a>
## [谷歌发布 Gemini 3.8 Flash 及 Cyber 版本](https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/) ⭐️ 8.0/10

谷歌发布了 Gemini 3.8 Flash 和 Gemini 3.8 Flash Cyber，这是一个快速且成本高效的新模型系列。Cyber 版本针对自主漏洞发现与修复进行了调优，在谷歌内部真实漏洞基准上成功率超过 70%。 此次发布表明，紧凑且价格实惠的模型也能达到前沿性能，挑战了顶级能力必须依赖大规模计算的传统观念。同时，它推出了专攻网络安全的模型，有望大幅降低漏洞发现的成本并提高速度，对 AI 从业者和安全团队都将产生重要影响。 Gemini 3.8 Flash 在 Artificial Analysis 智能指数上得分为 59，与 Opus 5 medium 持平，并在 DeepSwe 基准上超越 Opus 5 位居榜首。Cyber 版本在 Wiz 内部渗透测试基准上，相比其他领先前沿模型，召回率提高 7.5-9.7%，成本降低 2.3-5.2 倍。该模型已通过 Gemini API 和 AI Studio 提供。

hackernews · bratao · 9月2日 15:12 · [社区讨论](https://news.ycombinator.com/item?id=49537553)

**背景**: Gemini 3.8 Flash 是谷歌 Gemini 模型系列的一部分，该系列以多模态能力著称，支持音频和视频输入，而 OpenAI 和 Anthropic 的旗舰模型仅支持图像。Flash 模型旨在快速且成本高效，适合媒体分析和结构化数据提取等高容量任务。Cyber 版本是专为网络安全任务调优的变体，基于相同的基础智能，但针对漏洞发现与修复进行了优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-8-flash/">Gemini 3 . 8 Flash - Model Card — Google DeepMind</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/">Introducing Gemini 3.8 Flash and 3.8 Flash Cyber</a></li>
<li><a href="https://www.datacamp.com/blog/gemini-3-8-flash-cyber">Gemini 3.8 Flash: Features, Benchmarks, and Pricing | DataCamp</a></li>

</ul>
</details>

**社区讨论**: 社区成员对该模型的速度和 HTML/JavaScript 生成质量感到兴奋，simonw 提到仅花费 1.8 美分和 13 秒就生成了结果。其他人则强调其强劲的基准表现，mattlondon 指出它在 DeepSwe 上超越 Opus 5，在智能指数上与 Opus 5 medium 持平。simonw 还指出 Gemini 系列的多模态支持仍是关键差异化优势，同时有人担心低思考努力级别相比 3.7 可能有所退步。

**标签**: `#AI`, `#Gemini`, `#model release`, `#benchmarks`, `#LLM`

---

<a id="item-3"></a>
## [AI 搜索引擎引用 21.5 万个机器生成的“最佳软件”页面](https://trellner.com/reports/manufactured-sources-behind-ai-recommendations/) ⭐️ 8.0/10

Trellner 的一项调查显示，像 Perplexity 这样的 AI 搜索引擎经常引用来自仅三个网站的 215,128 个机器生成的“最佳软件”页面，揭示了 AI 内容来源的系统性问题。 这很重要，因为它削弱了人们对 AI 搜索推荐的信任，用户可能收到低质量、程序化生成的内容，而非真正有用的信息。这也引发了对 AI 作为主要信息来源可靠性的担忧，以及 SEO 垃圾信息可能操纵 AI 输出的问题。 这三个网站共生成了 215,128 个页面，这些页面经常被 Perplexity 等 AI 搜索引擎引用。调查表明，这些页面是针对 AI 检索而非人类读者优化的，利用了 RAG 管道中的来源选择标准。

hackernews · jakobgreenfeld · 9月2日 13:59 · [社区讨论](https://news.ycombinator.com/item?id=49536375)

**背景**: AI 搜索引擎使用检索增强生成（RAG）管道来检索和总结网页内容，通常依赖算法信号来决定引用哪些来源。SEO 垃圾信息（也称为 spamdexing）涉及操纵搜索索引以提高排名，而机器生成的页面是在没有人工干预的情况下自动创建的。这项调查揭示了此类低质量内容如何渗透到 AI 搜索结果中，可能降低用户获得的信息质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Spamdexing">Spamdexing - Wikipedia</a></li>
<li><a href="https://authoritytech.io/blog/how-ai-search-engines-decide-what-to-cite">How AI Search Engines Decide What to Cite</a></li>
<li><a href="https://surferseo.com/blog/how-do-ai-engines-choose-sources/">How AI Search Engines Find, Summarize, and Cite Content</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 AI 搜索的可靠性表示怀疑，用户分享了 LLM 偏爱自己生成内容以及幻觉不存在地点的轶事。一些用户报告称 Perplexity 的结果随时间推移而恶化，而另一些人则对 Perplexity 受到的负面关注表示欢迎，指出它从来就不可信。一位评论者批评该报告本身是 Claude 的产物，质疑其可信度。

**标签**: `#AI`, `#search engines`, `#content quality`, `#SEO spam`, `#LLM`

---

<a id="item-4"></a>
## [世界最大暗物质探测器探测到单个异常粒子事件](https://www.science.org/content/article/world-s-biggest-dark-matter-detector-spots-single-weird-particle) ⭐️ 8.0/10

世界上最大的暗物质探测器 LUX-ZEPLIN（LZ）观测到一个无法用已知背景解释的异常粒子事件。合作组已发布预印本，并正在收集更多数据以调查这一异常。 这一事件可能暗示暗物质或其他新物理，但现在断言发现还为时过早。该结果凸显了当前探测器的灵敏度，以及验证此类异常所需的严谨过程。 LZ 探测器位于南达科他州前金矿的桑福德地下研究设施地下 1480 米处，使用 7 吨液态氙寻找弱相互作用大质量粒子（WIMP）。观测到的事件统计显著性约为 3 西格玛，不足以确认发现。

hackernews · randycupertino · 9月2日 13:40 · [社区讨论](https://news.ycombinator.com/item?id=49536079)

**背景**: 暗物质是一种不可见的物质，约占宇宙物质的 85%，但从未被直接探测到。LZ 实验是最灵敏的暗物质探测器之一，旨在观测暗物质粒子与氙核之间的稀有相互作用。3 西格玛的结果只是一个提示，但粒子物理学通常需要 5 西格玛才能宣称发现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LZ_experiment">LZ experiment - Wikipedia</a></li>
<li><a href="https://lz.lbl.gov/">The LZ Dark Matter Experiment | The status and science of the ...</a></li>
<li><a href="https://interestingengineering.com/science/dark-matter-detector-spots-rare-particle-event">Dark matter finally found? Detector spots rare unexplained event</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍称赞预印本的严谨性和合作组的谨慎态度。一些人基于历史上 3 西格玛结果后来消失的情况表示怀疑，另一些人则赞赏对前金矿的再利用。一位评论者质疑暗物质的存在，认为当前物理模型可能存在缺陷。

**标签**: `#dark matter`, `#particle physics`, `#LZ detector`, `#scientific discovery`, `#physics`

---

<a id="item-5"></a>
## [Paint.NET 借助 AI 从头重写 Direct2D 以支持 WINE](https://simonwillison.net/2026/Sep/2/rick-brewster/) ⭐️ 8.0/10

Paint.NET 开发者 Rick Brewster 宣布，该应用现在包含一个内部、从零开始、净室逆向工程的 Direct2D 重写版本，在通过 /wine 标志运行于 WINE 时使用。这个约 18 万行代码的重写主要由 Anthropic 的 Claude AI 模型编写。 这一成就展示了 AI 辅助编程在复杂系统中的潜力，因为 Direct2D 此前是 Paint.NET 在 WINE 上运行的主要障碍。同时，它也引发了关于 AI 生成大量未经审查代码时，代码审查和可靠性的重要问题。 该重写版本位于 PaintDotNet.Windows.Direct2D1.Managed.dll 中，并通过 /wine 标志触发。Brewster 指出，这些代码是“vibe coding”的，未经审查，他不得不监督 Claude 以确保正确的资源管理，例如对 COM 对象正确调用 AddRef()。

rss · Simon Willison · 9月2日 05:50

**背景**: Direct2D 是微软为 Windows 设计的 2D 矢量图形 API，而 WINE 是一个兼容层，允许 Windows 应用程序在类 Unix 操作系统上运行。“Vibe coding”一词由 Andrej Karpathy 于 2025 年提出，指的是 AI 辅助软件开发，其中代码生成并被接受而无需彻底审查。这一新闻展示了这些技术的交汇，表明 AI 如何应对复杂的逆向工程任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Direct2D">Direct2D - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Wine_compatibility_layer">Wine compatibility layer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>

</ul>
</details>

**标签**: `#Direct2D`, `#WINE`, `#AI-assisted coding`, `#Paint.NET`, `#reverse engineering`

---

<a id="item-6"></a>
## [Perplexity 开源面向 Qwen 3.6 的 Mac 推理服务器](https://www.reddit.com/r/LocalLLaMA/comments/1w5ozl4/perplexity_opensourced_their_mac_inference_server/) ⭐️ 8.0/10

Perplexity 已开源其 Mac 推理服务器“lily”，该服务器针对在 Apple Silicon 上运行 Qwen 3.6 模型进行了优化。代码可在 GitHub 上的 pplx-garden 仓库中获取。 这一开源贡献为本地 LLM 社区提供了针对 Apple Silicon 高度优化的推理实现，可能提升 Mac 用户运行 Qwen 3.6 的性能和效率。同时也展示了 Perplexity 对混合计算和本地优先 AI 的承诺。 该服务器专门针对单一模型进行优化，以在 Apple Silicon 上实现最佳性能。它是 Perplexity 更广泛的混合计算计划的一部分，该计划将某些任务路由到本地硬件以保护隐私和提高效率。

reddit · r/LocalLLaMA · /u/Specter_Origin · 9月2日 22:13

**背景**: Perplexity 最近在 Mac 上推出了混合计算功能，允许 AI 任务在本地 Apple Silicon 和云服务器之间分配。这个开源服务器是该系统的一个组件，支持 Qwen 3.6 的本地推理。Qwen 3.6 模型家族包括密集和 MoE 变体，支持工具使用、视觉和推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.perplexity.ai/hub/blog/introducing-hybrid-compute-on-mac">Introducing Hybrid Compute on Mac - perplexity.ai</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.6-27B">Qwen / Qwen 3 . 6 -27B · Hugging Face</a></li>
<li><a href="https://lmstudio.ai/models/qwen3.6">Qwen 3 . 6</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论可能包含开发者测试该服务器的技术见解，对 Perplexity 对本地 LLM 生态系统的贡献持积极态度。一些人可能会讨论性能基准和潜在的改进。

**标签**: `#LLM`, `#Open Source`, `#Apple Silicon`, `#Inference`, `#Perplexity`

---

<a id="item-7"></a>
## [谷歌在美国反垄断案中避免广告技术业务拆分](https://www.nytimes.com/2026/09/02/technology/google-ad-tech-remedies.html) ⭐️ 7.0/10

2026 年 9 月 2 日，美国联邦法官裁定不支持司法部要求谷歌剥离其广告技术业务的请求，使谷歌得以避免业务拆分。该裁决是在针对谷歌在数字广告技术领域主导地位的漫长反垄断审判后作出的。 这一裁决是美国对大型科技公司反垄断执法的一次重大挫折，表明像拆分这样的结构性救济措施难以实施。它可能影响针对其他科技巨头的正在进行和未来的反垄断案件，塑造数字市场的监管格局。 谷歌的广告技术业务去年收入达 300 亿美元，约占 Alphabet 总收入的 8%，但估计利润贡献不到 1%，且收入已连续 16 个季度下滑。司法部曾要求剥离谷歌的 AdX 交易所，但法官认为政府证据不足以支持拆分。

hackernews · donohoe · 9月2日 14:46 · [社区讨论](https://news.ycombinator.com/item?id=49537131)

**背景**: 此案是美国政府遏制大型科技公司市场力量的更广泛努力的一部分。在另一起案件中，法官裁定谷歌非法维持在线搜索垄断，但该案的救济措施也被认为有限。反垄断专家争论在快速变化的技术市场中，拆分等结构性救济是否有效，因为即使拆分后主导地位也可能重新出现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kten.com/story/50418217/doj-antitrust-case-targeting-googles-ad-tech-business-will-go-to-trial-in-september-federal-judge-rules">DOJ antitrust case targeting Google's ad - tech business will go...</a></li>
<li><a href="https://sites.suffolk.edu/jhtl/2026/04/13/breaking-up-is-hard-to-do-antitrust-remedies-in-the-age-of-big-tech/">Breaking Up Is Hard to Do: Antitrust Remedies in the Age of ...</a></li>
<li><a href="https://www.justice.gov/atr">Antitrust Division - United States Department of Justice</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了对结果的失望，一些人认为反垄断法使解除合并变得过于困难，并建议对垄断企业征收累进税等替代方案。其他人质疑谷歌广告技术业务的重要性，指出其收入下滑和利润占比小，而一些人指出科技巨头经常通过“预先布局”来规避反垄断执法。

**标签**: `#antitrust`, `#Google`, `#ad tech`, `#regulation`, `#tech policy`

---

<a id="item-8"></a>
## [Fable 5.1 世界建模：AI 3D 世界生成工具](https://github.com/PhiloLabs/fable51-worlds) ⭐️ 7.0/10

Fable 5.1 World Modeling 是一款 AI 工具，用于生成 3D 世界，已在 GitHub 的 PhiloLabs 仓库中发布。它引发了社区关于其在游戏开发中实际应用的讨论。 该工具代表了 AI 驱动的 3D 世界生成领域的显著进步，可能简化游戏开发流程。社区的热烈讨论表明，AI 建模和游戏开发行业对此有高度兴趣和相关性。 社区反馈指出，生成的模型未针对游戏就绪资产进行优化，简单几何体往往具有高多边形数量。一些用户建议使用该工具生成低多边形轮廓，并通过烘焙纹理来获得更好的效果。

hackernews · surreal_ · 9月2日 19:49 · [社区讨论](https://news.ycombinator.com/item?id=49541458)

**背景**: AI 3D 世界生成工具利用机器学习从文本提示或图像创建 3D 场景，将构建详细世界的时间从数周缩短到数天。这些工具越来越多地用于游戏开发中的快速原型制作和概念可视化，但通常需要手动优化才能用于生产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=67M02CnIbtk">Claude Fable 5 . 1 | First impressions - YouTube</a></li>
<li><a href="https://www.datacamp.com/blog/claude-fable-5-1">Claude Fable 5 . 1 : Features, Benchmarks, and Pricing | DataCamp</a></li>
<li><a href="https://www.anthropic.com/claude-fable-and-mythos-5-1">Introducing Claude Fable 5 . 1 and Claude Mythos 5 . 1 \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了复杂的情绪：一些人称赞该工具令人印象深刻的演示和 NPC 密度，而另一些人则质疑其在简单演示之外的可用性，指出拓扑混乱和纹理处理困难。一位用户建议 Opus 5 同样有能力且更便宜，并推荐使用该工具生成低多边形轮廓并烘焙纹理。

**标签**: `#AI`, `#3D modeling`, `#game development`, `#world generation`, `#machine learning`

---

<a id="item-9"></a>
## [Mistral 用户争论默认选择加入数据训练](https://help.mistral.ai/en/articles/455207-can-i-opt-out-of-my-input-or-output-data-being-used-for-training) ⭐️ 7.0/10

一位用户在 Hacker News 上表达了对 Mistral Team 层级现在默认将用户纳入数据训练的不满，尽管此前承诺提供中央隐私控制。这引发了关于 AI 服务中退出机制有效性的讨论。 这凸显了企业对 AI 供应商隐私实践日益增长的不信任，尤其是依赖合同保证的企业。这场辩论强调了 AI 训练中透明且可执行的数据治理的必要性。 Mistral 的帮助中心指出，输入/输出数据默认可能用于训练，但用户可以随时选择退出。该用户指出，Team 层级的设置发生了变化，失去了集中禁用训练的能力，这与之前的预期相矛盾。

hackernews · teekert · 9月2日 12:30 · [社区讨论](https://news.ycombinator.com/item?id=49535284)

**背景**: AI 公司通常使用用户数据训练模型以提高性能，但 GDPR 等隐私法规要求获得同意或提供退出选项。Mistral 是一家欧洲 AI 公司，提供不同服务层级，具有不同的隐私控制，但用户报告称这些控制的实施存在不一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://help.mistral.ai/en/articles/455207-can-i-opt-out-of-my-input-or-output-data-being-used-for-training">Can I opt out of my input or output data being used for training?</a></li>
<li><a href="https://help.mistral.ai/en/articles/347617-do-you-use-my-user-data-to-train-your-artificial-intelligence-models">Do you use my user data to train your Artificial Intelligence ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对 AI 公司是否真正尊重退出选择表示怀疑，并引用了微软 Copilot 更改设置的例子。一些人建议通过“知识探测”进行法律诉讼可能是未来的补救措施，而另一些人则批评了文章标题的误导性。

**标签**: `#AI privacy`, `#data training`, `#opt-out`, `#Mistral`, `#enterprise AI`

---

<a id="item-10"></a>
## [Anthropic 发布 Claude 系统提示词，新增歌词限制](https://simonwillison.net/2026/Sep/2/claudes-new-system-prompt/) ⭐️ 7.0/10

Anthropic 已将其为 Claude 消费级应用发布的系统提示词重新组织为按模型分页的页面，并包含历史版本，同时新增了禁止复制歌词、诗歌和书籍段落的章节。Simon Willison 强调了这一更新，指出提示词现在包含严格禁止复制歌词的规则，以及 2026 年 6 月的截止日期。 这种透明度实践对 AI 政策和开发者研究具有重要意义，因为它可以轻松比较提示词随时间的变化。新的歌词限制反映了持续的版权担忧，并可能影响其他 AI 公司处理类似内容政策的方式。 系统提示词可在 platform.claude.com/docs 上获取，任何页面添加 '.md' 即可返回 Markdown 内容，便于比较。新的歌词政策包括对 1929 年前出版作品的例外，当 Claude 不确定作品日期时会拒绝请求。重组按模型（如 Haiku 4.5 和 Fable 5.1）分离提示词，并包含带日期的历史版本。

rss · Simon Willison · 9月2日 14:16

**背景**: 系统提示词是在用户交互之前给 AI 模型的隐藏指令，塑造其行为和约束。Anthropic 发布这些提示词的实践是不寻常且对透明度有价值的，因为大多数公司将其保密。platform.claude.com/docs 网站设计为可供 LLM 使用，允许轻松访问文档的 Markdown 版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Cowork">Claude Cowork</a></li>
<li><a href="https://en.wikipedia.org/wiki/System_prompt">System prompt</a></li>
<li><a href="https://github.com/asgeirtj/system_prompts_leaks">GitHub - asgeirtj/ system _ prompts _leaks: Extracted system prompts ...</a></li>

</ul>
</details>

**标签**: `#Anthropic`, `#Claude`, `#system prompts`, `#AI transparency`, `#developer tools`

---

<a id="item-11"></a>
## [H3-World：语言原生控制的视频生成](https://www.reddit.com/r/LocalLLaMA/comments/1w5akpy/h3world_turning_language_understanding_into_world/) ⭐️ 7.0/10

H3-World 提出了一种通过将文本动作提示注入 MiniMax-H3 语言模型的预训练文本路径来控制视频生成中角色和摄像机运动的方法。它仅使用 8,000 个游戏样本、10,000 步 LoRA 和 0.199% 的可训练参数，实现了对视频潜在表示的时间性控制。 该方法表明语言模型可以作为视频生成的原生控制接口，有望简化可控视频内容的创作。其高效性——仅需最少的数据和参数——可能使高级视频控制对研究人员和开发者更加普及。 该方法为每个视频潜在区间分配一个动作提示，从而在动作变化时实现精确的时间控制。发布的代码和模型可在 GitHub 和 Hugging Face 上获取，论文可在 arXiv 上查看。

reddit · r/LocalLLaMA · /u/sachasayan · 9月2日 13:35

**背景**: MiniMax-H3 是一个开放的全模态生成模型，能够理解和生成文本、图像、视频和音频。LoRA（低秩适应）是一种参数高效的微调技术，通过引入小型可训练矩阵，以最小的计算开销实现大型模型的适配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/MiniMax-AI/MiniMax-H3">GitHub - MiniMax-AI/MiniMax-H3 · GitHub</a></li>
<li><a href="https://www.minimax.io/blog/minimax-h3">MiniMax H3: An Open Model Breaking the Boundaries Between ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/LoRA_(machine_learning)">LoRA (machine learning) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#video generation`, `#language control`, `#efficient fine-tuning`, `#AI research`

---

<a id="item-12"></a>
## [DeepSeek-V4-Flash-Vision-Exp 视觉支持合并，Unsloth GGUF 量化可用](https://www.reddit.com/r/LocalLLaMA/comments/1w5e9fi/vision_support_merged_for_deepseekv4flashvisionexp/) ⭐️ 7.0/10

实验性模型 DeepSeek-V4-Flash-Vision-Exp 的视觉支持已合并，Unsloth GGUF 量化版本现已在 Hugging Face 上提供。这使得该多模态模型能够以优化的量化形式进行本地部署。 这一进展对本地 LLM 社区意义重大，因为它将 DeepSeek 最新实验模型的能力扩展至视觉领域，使开发者能够在本地运行多模态任务。Unsloth GGUF 量化版本的提供使其在资源受限的环境中更易用且更高效。 该模型是 DeepSeek-V4-Flash 的实验性多模态变体，专为图像理解和视觉代理设计。Unsloth 的 GGUF 量化以其高精度和与多种推理引擎的兼容性而闻名，如其 Dynamic v2.0 和 v3.0 版本所示。

reddit · r/LocalLLaMA · /u/fmillar · 9月2日 15:52

**背景**: DeepSeek-V4-Flash-Vision-Exp 是 DeepSeek 模型系列的一部分，该系列包括 V4 Pro、Flash 和 Vision Exp 等变体。GGUF 是一种用于量化模型的文件格式，使其能够在消费级硬件上高效运行，而 Unsloth 是一个为流行模型提供优化量化的工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/collections/unsloth/unsloth-dynamic-20-quants">Unsloth Dynamic 2.0 Quants - a unsloth Collection - Hugging Face</a></li>
<li><a href="https://unsloth.ai/blog/dynamic-v2">Unsloth Dynamic v2.0 GGUFs</a></li>
<li><a href="https://pixomi.ai/blog/deepseek-v4-flash-vision-exp/">DeepSeek V 4 Flash Vision Exp : New Multimodal Model | Pixomi AI</a></li>

</ul>
</details>

**标签**: `#DeepSeek`, `#Vision`, `#GGUF`, `#LocalLLaMA`, `#Model Release`

---

<a id="item-13"></a>
## [衰老大脑融合记忆而非遗忘](https://studyfinds.com/aging-brains-blend-memories-together-instead-of-forgetting-them-study-finds/) ⭐️ 6.0/10

一项新研究表明，随着年龄增长，大脑倾向于将相似记忆融合在一起，而不是简单地遗忘它们，这为与年龄相关的记忆衰退提供了更细致的视角。 这一发现挑战了传统观点，即衰老中的记忆丧失主要是存储或提取信息的失败。它可能重塑我们对认知衰老的理解，并为未来的记忆干预研究提供参考。 该研究涉及 61 名参与者，但年龄分布不均，30 至 50 岁之间的人很少，这限制了对连续衰退得出结论的能力。值得注意的是，注意力测量与年龄或观察到的大脑模式无关。

hackernews · mdp2021 · 9月2日 12:59 · [社区讨论](https://news.ycombinator.com/item?id=49535548)

**背景**: 记忆衰退是衰老的常见方面，但其潜在机制很复杂。传统模型通常关注遗忘，但这项研究表明，记忆干扰——即相似记忆合并——可能起重要作用。理解这些过程有助于区分正常衰老与阿尔茨海默病等病理状况。

**社区讨论**: 评论者分享了个人轶事，并提出了对研究局限性的质疑，如样本量小和年龄范围缺失。一些人讨论了记忆融合的概念，并将其与记忆的存储和回忆方式联系起来，指出回忆本身会改变记忆。

**标签**: `#neuroscience`, `#memory`, `#aging`, `#cognitive science`

---

<a id="item-14"></a>
## [llm-gemini 0.34 新增对 Gemini 3.8 Flash 的支持](https://simonwillison.net/2026/Sep/2/llm-gemini/) ⭐️ 6.0/10

llm-gemini 0.34 已发布，新增了对 Google 新模型 Gemini 3.8 Flash 的支持，并提供了低、中、高三种可配置的思考级别。该更新还修复了异步响应未能记录已解析模型版本的问题。 此次发布使 LLM 用户能够快速使用 Google 最新的 Flash 模型，该模型在软件工程和智能体工作流方面性能有所提升。这凸显了模型快速迭代的趋势，以及工具链跟上新模型发布步伐的重要性。 Gemini 3.8 Flash 基于 Gemini 3.7 Flash 构建，支持可自定义的思考级别，以平衡质量、成本和延迟。该插件更新还包含了由 Charlie Tonneslan 贡献的修复，解决了异步响应模型版本记录的问题。

rss · Simon Willison · 9月2日 16:39

**背景**: llm-gemini 是 Simon Willison 的 LLM 工具的一个插件，该工具提供了与各种语言模型交互的命令行界面。Gemini Flash 模型以快速、廉价且擅长 HTML 和 JavaScript 生成等任务而闻名，因此常用于原型设计和实际应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-8-flash/">Gemini 3.8 Flash - Model Card — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/generate-content/thinking">Gemini thinking - generateContent API | Google AI for Developers</a></li>
<li><a href="https://github.com/simonw/llm-gemini">GitHub - simonw/ llm - gemini : LLM plugin to access Google's Gemini...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Gemini`, `#release`, `#plugin`

---

<a id="item-15"></a>
## [GLM 5.3 Flash 在本地生成《我的世界》黑洞模组](https://www.reddit.com/r/LocalLLaMA/comments/1w5gk2b/glm_53_flash_makes_a_black_hole_minecraft_mod/) ⭐️ 6.0/10

一位用户使用本地 GLM 5.3 Flash 模型（Q4 量化）在租用的 4x RTX PRO 6000 机器上迭代开发了一个《我的世界》模组，该模组添加了一把黑洞步枪，可生成黑洞吸入方块并造成巨大爆炸坑。整个过程经过多轮反馈，耗时约 9 小时，输出 760 万 tokens，平均解码速度约 96 tok/s。 这展示了本地 LLM 在复杂迭代代码生成任务中的实际能力，表明像 GLM 5.3 Flash 这样的模型能够在用户指导下处理真实的模组开发。这凸显了使用强大本地模型进行创意编程项目的趋势，可能降低业余开发者的门槛。 该模组使用 Fabric API，并在 atomic.chat 中开发，用户提供参考图片以改善视觉效果。最终成果包括一把黑洞步枪，可生成带有光环的黑洞并造成大规模破坏，模组已在 GitHub 上发布。

reddit · r/LocalLLaMA · /u/Top-Eye-8104 · 9月2日 17:13

**背景**: GLM 5.3 Flash 是一款原生多模态模型，总参数 320B，激活参数 18B，设计用于高效低成本运行。Fabric API 是《我的世界》的轻量级模块化模组框架，而 RTX PRO 6000 是一款高端专业 GPU，配备 96GB 显存，适合运行大型本地模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.3-Flash">zai-org/GLM-5.3-Flash · Hugging Face</a></li>
<li><a href="https://z.ai/blog/glm-5.3-flash">GLM-5.3-Flash: Frontier Intelligence, Flash Cost - z.ai</a></li>
<li><a href="https://github.com/FabricMC">Next generation, highly modular and open Minecraft modding API ....</a></li>
<li><a href="https://www.techpowerup.com/gpu-specs/rtx-pro-6000-blackwell.c4272">NVIDIA RTX PRO 6000 Blackwell Specs - TechPowerUp</a></li>

</ul>
</details>

**标签**: `#local-llm`, `#code-generation`, `#minecraft-mod`, `#GLM-5.3`

---

<a id="item-16"></a>
## [将 Q8 N-gram 替换进 IQ4 Qwen 未出现速度下降](https://www.reddit.com/r/LocalLLaMA/comments/1w5isz3/confirmed_bolting_q8_ngram_into_iq4_qwen_no_speed/) ⭐️ 6.0/10

一位用户将 Qwen 3.8 模型中低精度的 N-gram 层替换为 Q8 版本，并观察到在 IQ4_XS 量化下推理速度没有明显下降，稳态速度约为 10.1 tokens/s。该实验在 RTX 3090 上进行，模型 state_dict 大小从约 90 GB 增加到 115 GB。 该实验表明，在不牺牲速度的情况下，可以将更高精度的 N-gram 层集成到量化模型中，从而可能提高在消费级硬件上运行本地 LLM 的用户输出质量。这为 Qwen 等特定模型架构提供了一条小众但有前景的优化路径。 由于存储限制，用户将 Qwen 3.8 模型（原始量化精度为 IQ4_XS）中的 N-gram 部分替换为 Q8 精度，而非先前实验中使用的 BF16 版本。速度测量在有和没有 Q8 N-gram 的情况下进行，state_dict 大小从约 90 GB 增加到 115 GB；输出质量测试仍在进行中。

reddit · r/LocalLLaMA · /u/Altruistic_Heat_9531 · 9月2日 18:32

**背景**: 量化通过降低权重精度来减小模型大小并加速推理，但可能会降低输出质量。N-gram 语言模型是基于前 n-1 个词预测下一个词的统计模型，Qwen 等一些 LLM 集成了 N-gram 层以提升性能。IQ4_XS 是一种 4 位量化格式，在大小和质量之间取得平衡，而 Q8 是 8 位格式，提供更高精度但代价是更大的体积。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantization_(signal_processing)">Quantization (signal processing)</a></li>
<li><a href="https://kaitchup.substack.com/p/choosing-a-gguf-model-k-quants-i">GGUF Quantization Compared: Q4_K_M vs IQ4_XS vs IQ4_NL</a></li>
<li><a href="https://en.wikipedia.org/wiki/Word_n-gram_language_model">Word n-gram language model - Wikipedia N-Gram Language Modelling with NLTK - GeeksforGeeks N-Gram Language Model | Springer Nature Link CHAPTER N-gram Language Models - Stanford University N-Gram Language Models — Computational Linguistics Reference N-Gram Language Model | Springer Nature Link</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子对该实验表现出积极兴趣，用户指出 Q8 N-gram 似乎更快，并将在稍后上传拼接代码。然而，目前还没有广泛的讨论，用户也承认输出质量尚未测试。

**标签**: `#quantization`, `#Qwen`, `#inference`, `#LLM optimization`

---