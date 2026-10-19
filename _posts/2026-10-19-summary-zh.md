---
layout: default
title: "Horizon Summary: 2026-10-19 (ZH)"
date: 2026-10-19
lang: zh
---

> 从 17 条内容中筛选出 11 条重要资讯。

---

1. [Together Computer 发布在潜在空间中思考的混合推理智能体](#item-1) ⭐️ 8.0/10
2. [RepRapMicron：开源微米级分辨率 3D 打印机项目](#item-2) ⭐️ 8.0/10
3. [谷歌开源 Harness2，让 AI 智能体自我改进](#item-3) ⭐️ 8.0/10
4. [72 小时内四款开放权重模型发布，仅英伟达一款适配 24GB 显存](#item-4) ⭐️ 8.0/10
5. [文章认为软件的价值在于人的决策而非代码](#item-5) ⭐️ 7.0/10
6. [DeepSeek 推出搜索与抓取 API，每千次请求仅 0.75 美元](#item-6) ⭐️ 7.0/10
7. [AuroraASR-1M：94.9 万参数语音识别模型在单 CPU 线程上实现 436 倍实时](#item-7) ⭐️ 7.0/10
8. [Free Pascal 编译器现已支持动态包](#item-8) ⭐️ 6.0/10
9. [Java 密封类与穷尽模式匹配解析](#item-9) ⭐️ 6.0/10
10. [EmbeddingGemma2 通过余弦相似度实现图像内文本搜索](#item-10) ⭐️ 6.0/10
11. [Reddit 用户警告：RTX 5090 需限制功耗，否则可能烧熔墙壁插座](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Together Computer 发布在潜在空间中思考的混合推理智能体](https://arxiv.org/abs/2610.18861) ⭐️ 8.0/10

Together Computer 发布了混合推理智能体（HybridAgents），这是一种新型模型系列，能在单次生成过程中动态切换潜在空间推理和基于文本的交互。该发布包括 GitHub 上的开源代码、Hugging Face 上的模型以及 arXiv 论文 2610.18861 中的详细评估。 这项工作连接了两个主要研究方向——潜在推理（如 Coconut）和基于文本的思维链——有可能在保持可解释性的同时减少 token 使用并加速推理。如果成功，它可能影响未来 LLM 智能体的架构设计，尤其是在冗长推理造成浪费的任务中。 混合方法使用“混合链接”在潜在模式和文本模式之间切换，但社区成员指出，文本生成仍然需要承担运行潜在模式模型的全部成本。早期用户报告表明，在 llama.cpp 中使用 8 位量化的 14B 模型在简单任务上可能重复循环，暗示可能存在兼容性或调优问题。

hackernews · allinonai · 10月18日 20:48 · [社区讨论](https://news.ycombinator.com/item?id=50145337)

**背景**: 潜在推理是指 LLM 在连续向量空间中进行中间推理步骤，而不是生成显式的文本 token，这在 Coconut（连续思维链）等范式中已有探索。相比之下，思维链提示使推理可见，但可能在语言脚手架方面浪费 token。HybridAgents 旨在将潜在推理的效率与基于文本交互的透明性和控制性结合起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2610.18861">Abstract page for arXiv paper 2610.18861: Hybrid Reasoning Agents</a></li>
<li><a href="https://arxiv.org/pdf/2412.06769">Training Large Language Models to Reason in a Continuous Latent ...</a></li>
<li><a href="https://www.arunbaby.com/ai-agents/0064-when-llms-stop-talking-to-themselves/">When LLMs stop talking to themselves: latent -space reasoning and...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 评论者讨论了架构替代方案，例如始终将潜在向量和 token 嵌入一起传入模型（amluto），或者使用向量相加而不是加宽嵌入。一些人对将该方法应用于 Qwen 3.8 27B 等模型以减少冗余复述表示兴奋，而另一些人报告了实际失败案例，例如 14B 模型在 llama.cpp 中循环。一条 Reddit 评论将潜在优势总结为更快的推理、更少的 token 和更高的智能。

**标签**: `#LLM agents`, `#latent reasoning`, `#AI research`, `#open-source models`, `#Together AI`

---

<a id="item-2"></a>
## [RepRapMicron：开源微米级分辨率 3D 打印机项目](https://github.com/VikOlliver/RepRapMicron/wiki) ⭐️ 8.0/10

RepRapMicron 是由 RepRap 先驱 Vik Olliver 领导的开源项目，旨在构建微米级分辨率的 DIY 3D 打印机，目前处于可部署原型阶段。该项目在布拉格 Fab25 上展示，使用标准 3D 打印机或 CNC 硬件实现了 10 至 20 微米的分辨率。 如果成功，这将使得芯片设计和其他微尺度硬件的廉价和可持续打印成为可能，可能彻底改变硬件制造并让自我复制更接近现实。它还将微制造开放给开源社区，而这一领域传统上仅限于昂贵的工业设备。 该打印机采用基于柔性机构的设计，运行在标准 3D 打印机或 CNC 硬件上，实现了 10-20 微米的分辨率。它是一个可部署的原型，项目 wiki 提供了其开发和规格的详细信息。

hackernews · RobotToaster · 10月18日 13:48 · [社区讨论](https://news.ycombinator.com/item?id=50141076)

**背景**: RepRap 是一个长期运行的开源项目，旨在创建自我复制的 3D 打印机，以实现制造民主化。RepRapMicron 将此目标扩展到微米尺度，即特征尺寸以百万分之一米为单位，从而能够打印集成电路等微结构。传统的微制造技术，如光刻，复杂且昂贵，因此低成本、开源的替代方案可能具有颠覆性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://reprap.org/wiki/RepRapMicron">RepRapMicron - RepRap</a></li>
<li><a href="https://www.printables.com/model/1692745-reprapmicron-pika-micron-resolution-3d-printer">RepRapMicron PIKA Micron Resolution 3 D Printer ... | Printables.com</a></li>
<li><a href="https://www.linkedin.com/posts/all3dp_reprap-pioneer-returns-with-a-diy-3d-printer-activity-7358565470368595969-YeGF">RepRap Pioneer Returns With a DIY 3 D Printer That Hits Micro-Level...</a></li>

</ul>
</details>

**社区讨论**: 评论者将其与 18 世纪 90 年代末的精密制造进步相提并论，如拉姆斯登的分度机和莫兹利的螺纹车床，认为这可能是一次类似的飞跃。一些人对打印定制 RAM 和芯片设计表示兴奋，而另一些人则质疑在如此小尺度上实现自我复制的可行性。

**标签**: `#3D printing`, `#open hardware`, `#microfabrication`, `#RepRap`, `#precision engineering`

---

<a id="item-3"></a>
## [谷歌开源 Harness2，让 AI 智能体自我改进](https://www.reddit.com/r/LocalLLaMA/comments/1x9gfnb/google_open_sources_harness2_for_self_improving/) ⭐️ 8.0/10

谷歌开源了 Harness2 框架，使 AI 智能体能够针对每个任务迭代优化自身的运行框架（包括系统提示、工具、记忆、技能和子智能体），而无需更改模型权重。在 Gemini 3.5 Flash 和 GLM-5 上针对法律、办公和专业基准进行测试时，即使仅一轮编辑也优于原始框架，更多轮次则带来更高分数。 该发布展示了一条切实可行的路径，让智能体无需重新训练即可在任务间自我改进，这可能显著提升复杂专业工作流的性能，并降低构建自适应智能体系统的门槛。它对开源 LLM 社区高度相关，因为它能在任何模型（包括 GLM-5 等开放权重模型）之上实现框架优化。 Harness2 不需要正确答案或评分器；它提出更改、运行候选版本，并通过比较性能来选择最佳版本。每个任务完成后，它会保存改进后的框架和经验教训，使未来的编辑从更智能的基线开始，并且只要底层模型支持所需交互，该方法就与模型无关。

reddit · r/LocalLLaMA · /u/chemist_slime · 10月18日 22:33

**背景**: AI 运行框架（harness）指的是模型周围的一切——系统提示、工具、记忆、技能和子智能体——它定义了智能体的运作方式。传统上，人类一次性设计固定框架，智能体在每个任务中都使用它。Harness2 颠覆了这一模式，让智能体自身针对每个任务优化框架，同时保持模型权重冻结。Gemini 3.5 Flash 是谷歌 DeepMind 推出的快速、高性价比模型，GLM-5 是 Z.ai 的开源权重模型系列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/agent-framework/concepts/harness">Agent Harness | Microsoft Learn</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3.5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://github.com/zai-org/GLM-5">GitHub - zai-org/GLM-5: GLM-5: From Vibe Coding to Agentic ...</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#self-improvement`, `#open-source`, `#Google Research`, `#LLM tooling`

---

<a id="item-4"></a>
## [72 小时内四款开放权重模型发布，仅英伟达一款适配 24GB 显存](https://www.reddit.com/r/LocalLLaMA/comments/1x9d23j/72_hours_four_big_open_weights_drops_the_only_one/) ⭐️ 8.0/10

在 72 小时内，Meta 发布了 Muse Spark Open（总参数 816B/激活 42B，100 万上下文），英伟达推出了 Nemotron 3.5 Bolt（总参数 74B/激活 9B，2 比特量化感知训练，占用 22GB），Reflection 发布了 Beam（总参数 501B/激活 23B，Apache 2.0 许可），DeepSeek 则发布了 V4.1 Flash 1017（MIT 许可，仓库 510GB）。其中只有 Nemotron 3.5 Bolt 是专门为适配 24GB 显存而设计的。 这一波发布凸显了开放权重 AI 领域日益扩大的分化：大多数新旗舰模型需要数万美元的多 GPU 配置，而英伟达的 Nemotron 3.5 Bolt 是少数针对消费级 24GB GPU 优化的模型。这种对比还表明，对于实际采用而言，许可条款（MIT/Apache 2.0 对比自定义署名和收入条款）可能与原始参数数量同样重要。 Nemotron 3.5 Bolt 采用低至 2 比特的量化感知训练，模型大小为 22GB，外加 1.7GB 的视觉投影器，首日即提供 Unsloth GGUF，并兼容 llama.cpp、Ollama 和 LM Studio。Meta 的 Muse Spark Open 需要两台 512GB 的 M5 Ultra Mac Studio（或四台 256GB 设备，约 3.8 万美元），采用自定义许可，要求强制署名，并在收入超过 2000 万美元时需单独签约，在 Artificial Analysis 指数上得分为 39，落后于 GLM 5.3（45）和 Kimi K3（44）。

reddit · r/LocalLLaMA · /u/BTA_Labs · 10月18日 20:10

**背景**: 开放权重模型是指训练后的参数可公开下载的模型，允许本地部署和微调，不同于仅提供 API 的封闭模型。这四款发布均采用混合专家（MoE）架构，该架构将总参数（决定内存占用和下载大小）与激活参数（决定每 token 计算量）区分开来。量化通过降低数值精度来缩小模型体积，而量化感知训练则将这种降低融入训练过程，以在低比特宽度下获得更好的精度。GGUF 是一种流行的文件格式，可通过 llama.cpp、Ollama 和 LM Studio 等工具在本地运行量化模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/unsloth/NVIDIA-Nemotron-3.5-Bolt-74B-A9B-GGUF">unsloth/NVIDIA- Nemotron - 3 . 5 - Bolt -74B-A9B-GGUF · Hugging Face</a></li>
<li><a href="https://ollama.com/library/nemotron-3.5-bolt">nemotron - 3 . 5 - bolt</a></li>
<li><a href="https://www.automataai.com.au/blog/moe-architecture-active-vs-total-parameters-explained">MoE Architecture: Active vs Total Parameters Explained</a></li>

</ul>
</details>

**标签**: `#open-weights`, `#local-llm`, `#quantization`, `#nvidia`, `#model-releases`

---

<a id="item-5"></a>
## [文章认为软件的价值在于人的决策而非代码](https://karrisaarinen.com/posts/someone-behind-the-software/) ⭐️ 7.0/10

Karri Saarinen 发表了一篇题为《软件背后的人》的文章，认为软件的真正价值来自其背后的人类决策、愿景和品味，而非代码本身。该文章在 Hacker News 上引发了 316 分、134 条评论的热烈讨论，辩论了 AI 在价值观、意图、品味和工艺方面的局限性，以及软件商品化的问题。 这篇文章及随后的辩论凸显了软件行业日益增长的担忧：随着 GitHub Copilot 和 ChatGPT 等 AI 代码生成工具变得越来越强大，决定构建什么以及为什么构建的独特人类贡献成为关键差异化因素。它影响着开发者、产品经理以及所有参与软件创建的人，促使人们反思在 AI 增强的世界中人类工艺的未来角色。 讨论中引用了多萝西·塞耶斯的著作《创造者的心灵》，弗雷德·布鲁克斯在《人月神话》中引用该书，将创造性活动分为理念、实现和互动三个阶段。评论者还指出，AI 缺乏价值观、意图和品味，即使在人类之间这些也各不相同，使得人类元素在软件创造中不可替代。

hackernews · tosh · 10月18日 16:32 · [社区讨论](https://news.ycombinator.com/item?id=50142573)

**背景**: 软件工艺运动起源于 20 世纪 90 年代的敏捷开发，强调软件开发既是一门工艺也是一门工程学科，重视精心打造的软件和专业社区。随着 AI 代码生成工具日益普及，关于 AI 效率与人类工艺之间平衡的争论愈演愈烈，一些人认为 AI 优化了速度，但无法解决大规模构建优质软件的更深层次问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Software_craftsmanship">Software craftsmanship - Wikipedia</a></li>
<li><a href="https://research.thinknimble.com/notes/software-craft-vs-ai-generation/">ThinkNimble Research Institute · Software Craft vs. AI Generation</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意文章的前提。SaaS 作者 jwr 表示，价值在于决定构建什么并定义产品的特性，而不在于代码或架构，AI 在这些方面正在迎头赶上。allenu 指出，AI 缺乏价值观、意图和品味，这些本质上是人类的，并且因人而异。zeroq 警告不要混淆观点，他以陶艺家为例，其杯子售价 200 美元是因为故事而非杯子本身；ajrouvoet 则引用多萝西·塞耶斯的《创造者的心灵》，将创造性活动分为理念、实现和互动。

**标签**: `#software-engineering`, `#AI`, `#product-design`, `#craftsmanship`, `#human-values`

---

<a id="item-6"></a>
## [DeepSeek 推出搜索与抓取 API，每千次请求仅 0.75 美元](https://api-docs.deepseek.com/guides/search/) ⭐️ 7.0/10

DeepSeek 推出了由自研搜索引擎驱动的托管式搜索与抓取 API，定价为每 1000 次成功请求 0.75 美元。该 API 支持网页搜索和网页抓取，并兼容 OpenAI/Anthropic 的 API 格式。 这一定价显著低于 Brave Search API（每千次 5 美元）和 Kagi API（每千次 12 美元）等竞争对手，为 AI 智能体开发者和将网页搜索集成到应用中的开发者提供了高性价比的选择。这可能加剧搜索 API 市场的价格竞争。 该 API 由 DeepSeek 自研搜索引擎驱动，支持搜索和抓取功能。定价基于成功请求，且 API 格式兼容 OpenAI/Anthropic，便于集成。

hackernews · fagnerbrack · 10月18日 06:50 · [社区讨论](https://news.ycombinator.com/item?id=50138531)

**背景**: 搜索 API 允许开发者通过程序查询网络并获取结果，这对于需要实时信息的 AI 智能体至关重要。DeepSeek 是一家以大型语言模型闻名的 AI 公司，此举将其业务扩展到搜索基础设施领域。Brave 和 Kagi 等竞争服务提供类似的 API，但价格更高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://api-docs.deepseek.com/api/search/">Search | DeepSeek API Docs</a></li>
<li><a href="https://api-docs.deepseek.com/">Your First API Call | DeepSeek API Docs</a></li>
<li><a href="https://awesomeagents.ai/pricing/search-api-pricing/">Search API Pricing Compared 2026 | Awesome Agents</a></li>

</ul>
</details>

**社区讨论**: HN 评论者讨论了使用场景，一些人更喜欢像 SearXNG 这样的免费替代品用于个人用途。其他人推测，随着提供商争夺对 AI 驱动搜索的影响力，搜索 API 价格可能会变为负值，并指出这些服务的存在是因为谷歌缺乏付费搜索 API。还与 Brave（5 美元）和 Kagi（12 美元）进行了比较。

**标签**: `#search-api`, `#deepseek`, `#ai-agents`, `#pricing`, `#web-search`

---

<a id="item-7"></a>
## [AuroraASR-1M：94.9 万参数语音识别模型在单 CPU 线程上实现 436 倍实时](https://www.reddit.com/r/LocalLLaMA/comments/1x92ejs/auroraasr1m_releases/) ⭐️ 7.0/10

一位社区开发者发布了 AuroraASR-1M，这是一个拥有 94.9 万参数的 Conformer-CTC 语音识别模型，INT8 权重仅 1.06 MB，在单 CPU 线程上实现约 436 倍实时推理，在 LibriSpeech test-clean 上使用无外部语言模型的贪心解码达到 11.43%的词错误率。该模型以 Apache 2.0 许可证发布。 这一发布表明，实用的语音识别可以完全在单 CPU 线程上以不足 1MB 的模型运行，使得始终在线的语音识别在无需 GPU 或云连接的嵌入式、边缘和低功耗设备上成为可能。它降低了开发者在资源受限环境中构建离线语音界面的门槛。 对于如此小的模型，11.43%的词错误率相当不错，但远非最先进水平；该结果是在干净的朗读有声书语音上使用贪心 CTC 解码且无外部语言模型测得的，因此实际场景中的准确率可能会更差。权重共享的 Conformer-CTC 架构是缩减参数数量同时保持合理准确率的关键。

reddit · r/LocalLLaMA · /u/Tall_Abrocoma_3533 · 10月18日 12:48

**背景**: Conformer 是一种语音识别架构，它将 Transformer 的自注意力与卷积层结合，以同时捕捉局部和全局音频模式；Conformer-CTC 是其非自回归变体，使用连接时序分类（CTC）损失进行无需对齐的训练。LibriSpeech test-clean 是一个标准基准，包含约 5.4 小时的干净英语朗读语音，当前前沿系统已能达到非常低的词错误率，但微型模型通常以准确率换取模型大小。近期研究中的权重共享通过跨层复用参数来减小模型大小，且准确率损失有限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2005.08100">Conformer: Convolution-augmented Transformer for Speech ... Conformer: Convolution-augmented Transformer for Speech ... GitHub - LuluW8071/Conformer: End-to-End Speech Recognition ... Speech Recognition: Conformer GitHub - SurajDonthi/Conformer: Implementation of the ... STT En Conformer-CTC Large | NVIDIA NGC nvidia/stt_en_conformer_ctc_large · Hugging Face</a></li>
<li><a href="https://vexascribe.com/blog/transcription-accuracy-comparison">Transcription Accuracy Compared: 2026 WER Benchmarks by Engine</a></li>
<li><a href="https://www.bruguier.com/pub/weight_sharing_conformer.pdf">Sharing Low Rank Conformer Weights for Tiny Always-On Ambient ...</a></li>

</ul>
</details>

**标签**: `#speech-recognition`, `#lightweight-models`, `#edge-ai`, `#conformer`, `#asr`

---

<a id="item-8"></a>
## [Free Pascal 编译器现已支持动态包](https://www.getlazarus.org/dynamic/) ⭐️ 6.0/10

Free Pascal 编译器和 Lazarus IDE 现已获得完整的动态包支持，允许开发者创建和安装组件、控件及扩展，而无需重新构建整个 IDE。这是自由开源软件社区经过 20 多年努力后的首个正式版本。 这一里程碑通过支持快速组件安装和插件系统，显著改善了 Pascal 程序员的开发流程，可能吸引更多开发者加入 Free Pascal/Lazarus 生态系统。它使工具链更接近现代 IDE 的期望，但其影响主要仍局限于 Pascal 领域。 动态包可以构建为适用于 Linux、Windows 和 macOS 的共享库，并且可以在程序运行时替换。但存在一些限制：单元名称不能与包名称相同，且单元名称在不同包之间必须唯一。

hackernews · sysrpl · 10月18日 18:48 · [社区讨论](https://news.ycombinator.com/item?id=50144066)

**背景**: Free Pascal 是一个开源 Pascal 编译器，支持多种架构，而 Lazarus 是其跨平台 IDE。传统上，在 Lazarus 中安装新组件需要重新构建整个 IDE，这非常耗时。动态包通过允许在运行时加载组件（类似于插件）解决了这个问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://upstract.com/x/193d1d042c24dde0">Free Pascal Compiler Now Supports Dynamic Packages</a></li>
<li><a href="https://www.toolkuy.com/blog/free-pascal-dynamic-packages-lazarus-plugin-tanpa-rebuild">Free Pascal Dynamic Packages — Toolkuy</a></li>
<li><a href="https://wiki.freepascal.org/packages">packages - Free Pascal wiki</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体积极，用户赞扬团队的努力，并对 Pascal 的设计哲学表示怀念。一些人质疑 Pascal 如今是否仍有相关性，而另一些人指出 AI 代码模型难以处理 Pascal，凸显其独特的语法。一位评论者指出这可能是一个 Lazarus 的分支，并引用了官方 Lazarus IDE 网站。

**标签**: `#Free Pascal`, `#Lazarus`, `#compilers`, `#IDE`, `#open source`

---

<a id="item-9"></a>
## [Java 密封类与穷尽模式匹配解析](https://neilmadden.blog/2026/04/24/java-sealed-classes-and-exhaustive-pattern-matching/) ⭐️ 6.0/10

Neil Madden 的博客文章解释了 Java 17 引入的密封类如何与 switch 表达式结合实现穷尽模式匹配，使编译器能够验证所有允许的子类型都被处理。 这一特性改变了开发者设计 API 的方式，通过封闭类型层次结构并实现编译时安全，可以减少运行时错误并提高代码可维护性，尤其适用于负载多变的事件驱动系统。 密封类需要使用`sealed`修饰符和`permits`子句列出允许的子类，当与 switch 中的模式匹配结合使用时，编译器会强制穷尽性，无需 default 分支，但一些开发者会错误地添加不必要的 default。

hackernews · hnisjafx40 · 10月18日 14:47 · [社区讨论](https://news.ycombinator.com/item?id=50141579)

**背景**: Java 17 引入了密封类（JEP 409），通过限制哪些类可以扩展或实现某个类型，让开发者对继承进行细粒度控制。Java 21 最终确定的 switch 模式匹配允许根据对象的运行时类型进行切换并提取组件，当与密封类型结合时，编译器可以检查所有可能的子类型是否都被覆盖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.oracle.com/en/java/javase/17/language/sealed-classes-and-interfaces.html">Sealed Classes | Oracle Help Center</a></li>
<li><a href="https://www.baeldung.com/java-sealed-classes-interfaces">Sealed Classes and Interfaces in Java | Baeldung</a></li>
<li><a href="https://docs.oracle.com/en/java/javase/25/language/pattern-matching.html">Pattern Matching - docs.oracle.com</a></li>

</ul>
</details>

**社区讨论**: 评论者赞赏 Java 的进步，一些人更喜欢 TypeScript 通过 ts-pattern 等库实现的穷尽模式匹配。其他人强调了实际好处，如访问控制和处理事件驱动消息，还有人指出对于密封类型，switch 中的 default 分支是不必要的。

**标签**: `#Java`, `#pattern matching`, `#sealed classes`, `#language features`, `#TypeScript`

---

<a id="item-10"></a>
## [EmbeddingGemma2 通过余弦相似度实现图像内文本搜索](https://www.reddit.com/r/LocalLLaMA/comments/1x9acj4/embedding_model_can_be_used_to_search_text_inside/) ⭐️ 6.0/10

一位 Reddit 用户演示了 EmbeddingGemma2（330MB Q8 量化、768 维嵌入模型）可通过计算文本查询与图像嵌入之间的余弦相似度来搜索图像内的文本。该用户索引了超过 3000 张视觉小说截图，并展示模型能检索出包含特定韩语对话的图像，但结果仍是初步且非科学的。 该实验表明，一个紧凑的、可在本地运行的嵌入模型无需专门的 OCR 流程即可执行跨模态的图像内文本检索，这有望为个人图像集实现轻量且保护隐私的搜索。它也凸显了小规模多模态嵌入模型在多语言语义搜索中的潜力与局限。 该模型通过 llama.cpp 运行，采用 Q8_0 量化、4096 上下文长度，在 RX 7900GRE GPU 上使用 Vulkan 后端，约 510 秒索引了 3003 张图像。作者指出，文本语义在余弦相似度中往往比视觉特征更具主导性，需要谨慎措辞（例如 blond 与 blonde），并且跨语言相似度较低，可能归因于模型规模较小。

reddit · r/LocalLLaMA · /u/jupiterbjy · 10月18日 18:22

**背景**: EmbeddingGemma2 是 Google DeepMind 推出的开源多模态嵌入模型，可将文本、图像、视频和音频映射到统一的 768 维向量空间，从而支持跨模态的相似度比较。余弦相似度是衡量嵌入向量之间夹角的标准指标，常用于文本检索。Q8 量化将模型大小降至约 330MB，且质量损失极小，使其能够在消费级硬件上运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/google/embeddinggemma-2">google/ embeddinggemma - 2 · Hugging Face</a></li>
<li><a href="https://ollama.com/library/embeddinggemma-2">EmbeddingGemma 2 is a multimodal embedding model from Google...</a></li>
<li><a href="https://www.dataquest.io/blog/measuring-similarity-and-distance-between-embeddings/">Measuring Similarity and Distance between Embeddings</a></li>

</ul>
</details>

**标签**: `#embedding-models`, `#multimodal-search`, `#image-text-retrieval`, `#local-llm`, `#experimental`

---

<a id="item-11"></a>
## [Reddit 用户警告：RTX 5090 需限制功耗，否则可能烧熔墙壁插座](https://www.reddit.com/r/LocalLLaMA/comments/1x98bby/psa_power_limit_your_5090s/) ⭐️ 6.0/10

一位 Reddit 用户在 r/LocalLLaMA 上报告，在对搭载四块 RTX 5090 GPU 的主机进行性能调优时，熔化了标准的 13A 墙壁插头和插座。该用户建议改用 16A 或 20A 插座，并对 GPU 进行功耗限制，以避免标准电路过载。 这对本地 LLM 社区来说是一个实用的安全警告，因为多 GPU 主机很常见，功耗很容易超过标准家用电路的额定值。它提醒人们，即使 12VHPWR 连接器尚未失效，墙壁插座本身如果额定值不足也可能成为火灾隐患。 该用户表示惊讶，因为 12VHPWR 连接器并没有先熔化，这表明墙壁插座是最薄弱的环节。他们建议升级到 16A 或 20A 插座，并使用功耗限制来减轻电路负载。

reddit · r/LocalLLaMA · /u/Zo0x78 · 10月18日 17:02

**背景**: 随 NVIDIA RTX 4090 引入的 12VHPWR 连接器因插入不当或负载过高而容易熔化，后来推出了修订版 12V-2x6 设计。同时，标准墙壁插座（例如英国的 13A）有连续负载限制，多块 GPU 的高瓦数消耗可能超过这些限制，导致过热。在本地 LLM 社区中，对 GPU 进行功耗限制和降压是常见做法，可以在性能损失最小的情况下减少发热和功耗。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/12VHPWR">12 VHPWR - Wikipedia</a></li>
<li><a href="https://electricalflux.com/wire-switches/wall-outlet-wattage-limits-15a-20a">How Many Watts Is a Wall Outlet? 15A and 20A Circuit Limits</a></li>
<li><a href="https://my-intuition.com/science-research/undervolting-your-gpu-for-local-inference-lower-heat-same-tokens-sec/">Undervolting Your GPU for Local Inference: Lower Heat... - My Intuition</a></li>

</ul>
</details>

**标签**: `#GPU`, `#power-management`, `#local-llm`, `#hardware`, `#safety`

---