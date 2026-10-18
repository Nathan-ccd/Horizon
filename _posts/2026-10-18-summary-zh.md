---
layout: default
title: "Horizon Summary: 2026-10-18 (ZH)"
date: 2026-10-18
lang: zh
---

> 从 14 条内容中筛选出 8 条重要资讯。

---

1. [DeepSeek 发布 V4.1-Flash-1017，编码能力大幅提升](#item-1) ⭐️ 8.0/10
2. [爱沙尼亚开源其网络投票系统代码](#item-2) ⭐️ 8.0/10
3. [全球太阳能发电量首次超越核能](#item-3) ⭐️ 8.0/10
4. [Pele 将 Mermaid 图表渲染为可主题化的 SVG](#item-4) ⭐️ 6.0/10
5. [家庭实验者用多力多滋染料使鸡胸肉变透明](#item-5) ⭐️ 6.0/10
6. [Reddit 帖子探讨如何批评 ICLR 投稿中的 AI 生成写作](#item-6) ⭐️ 6.0/10
7. [17 款 AI 模型在 7700 手扑克中对决：前沿、廉价、本地与 Jev](#item-7) ⭐️ 6.0/10
8. [EpochGo：基于离线 LLM 和确定性流水线的本地优先 AutoML](#item-8) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DeepSeek 发布 V4.1-Flash-1017，编码能力大幅提升](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017) ⭐️ 8.0/10

DeepSeek 于 2026 年 10 月 17 日发布 DeepSeek-V4.1-Flash-1017，这是对 V4.1-Flash 的一次小版本更新，但在推理、编码和智能体任务上带来了显著提升；根据公司新闻页，该模型在 11 项编码基准中有 10 项击败了 Sol 5.6。该模型以 deepseek-flash 的 API ID 提供服务且价格不变，其 MIT 许可的权重已在 Hugging Face 和 ModelScope 上发布。 此次发布增强了开放权重模型生态，以宽松的 MIT 许可证提供具有竞争力的编码和智能体性能，为开发者提供了相比 GPT 和 Gemini 等专有模型更快、更透明的替代方案。其速度和开放性可能改变开发者在编码工作流中的偏好，并加大对闭源模型提供商的压力。 该模型是拥有 7630 亿参数的稀疏混合专家模型，基于 DeepSeek 的因果编码器-解码器（CED）架构，支持文本和图像输入、100 万上下文窗口、最高 38.4 万输出、默认开启思考、工具调用和 JSON 输出。尽管基准测试有所提升，但社区中的独立实测对比表明，在复杂代码审查任务上，其实际表现无论在速度还是问题相关性上仍落后于 GPT 5.6/6.1 Sol。

hackernews · theykk · 10月17日 08:21 · [社区讨论](https://news.ycombinator.com/item?id=50129045)

**背景**: DeepSeek 是一家以发布开放权重大语言模型闻名的中国 AI 公司，V4.1-Flash 是其新架构家族中最小、具备原生视觉理解能力的模型。这里引用的编码基准是用于比较大语言模型编程能力的标准化测试，但研究者提醒基准结果未必能完全反映现实世界的可靠性。OpenRouter 是一个统一的 API 平台，让开发者通过单一接口访问包括该模型在内的众多模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash">deepseek-ai/DeepSeek-V4.1-Flash · Hugging Face</a></li>
<li><a href="https://www.testmuai.com/blog/deepseek-v4-1-flash/">DeepSeek V4.1 Flash 1017: Benchmarks, Pricing and Setup</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者讨论热烈，许多人称赞 DeepSeek 的 token 吞吐速度快、首 token 延迟低，以及其开放性——思维链可见、不会被随意的网络安全审查拦截——这让它比得分更高的对手“感觉”更好。也有人强调在监管障碍下生态多样性的价值；而一位实测者发现，在大型 C++ 代码审查中 DeepSeek 比 GPT 5.6/6.1 Sol 更慢且不够精准，另有人调侃发布说明中“小版本更新、大幅提升”的措辞。

**标签**: `#deepseek`, `#llm`, `#ai-models`, `#benchmarks`, `#coding`

---

<a id="item-2"></a>
## [爱沙尼亚开源其网络投票系统代码](https://github.com/valimised/ivxv) ⭐️ 8.0/10

爱沙尼亚在 GitHub 上的 valimised 组织下发布了其国家网络投票系统 IVXV 的源代码，供公众审查。 此次发布是电子投票透明化的重要里程碑，因为它允许安全研究人员和公众审查一个国家用于具有约束力选举的系统，可能增强信任并影响全球关于电子投票的讨论。 IVXV 自 2017 年起在爱沙尼亚选举中使用，采用 3072 位素数模的 ElGamal 加密在投票时保护个人选票；然而，系统的安全性最终取决于程序保障和对选举机构的信任。

hackernews · theanonymousone · 10月17日 03:18 · [社区讨论](https://news.ycombinator.com/item?id=50127586)

**背景**: 爱沙尼亚于 2005 年成为首个引入全国性网络投票（i-voting）的国家，并且仍是唯一在所有选举中使用该系统的国家。IVXV 系统于 2017 年部署，是当前这一网络投票平台的迭代版本，旨在让选民可以从任何地方在线投票。端到端可验证（E2E）投票系统使用密码学技术，让选民能够验证其选票被如实统计而不泄露他们的选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/valimised/ivxv">GitHub - valimised/ ivxv : IVXV online voting system · GitHub</a></li>
<li><a href="https://grokipedia.com/page/Electronic_voting_in_Estonia">Electronic voting in Estonia — Grokipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/End-to-end_auditable_voting">End-to-end auditable voting - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者就电子投票的安全性和信任假设展开了辩论。一些人认为仅靠软件无法保证选举安全，通过统计抽样进行选举后验证至关重要；而爱沙尼亚居民指出该系统被广泛接受和信任，但也担心信任侵蚀后的后果。其他人提到了 ElectionGuard 等现有可验证系统，并警告任何有足够动机的系统都会被黑客攻击。

**标签**: `#e-voting`, `#open-source`, `#security`, `#elections`, `#Estonia`

---

<a id="item-3"></a>
## [全球太阳能发电量首次超越核能](https://www.pv-magazine.com/2026/09/29/solar-surpasses-nuclear-power-globally-for-first-time/) ⭐️ 8.0/10

全球太阳能发电量首次超过核能，风能也即将达到这一门槛。从 2025 年 3 月到 2026 年 6 月，太阳能或风能每月单独发电量都超过核能，而在 2026 年 3 月、4 月和 5 月，这两种技术各自独立地超过了核能发电量。 这一里程碑标志着全球电力结构的重大转变，凸显了可再生能源的快速增长和核能的停滞。它表明太阳能和风能正成为清洁电力的主要来源，对能源政策、投资和气候目标具有深远影响。 全球太阳能装机容量增加了 510 GW，达到 2,383 GW（同比增长 27%），而风能新增了创纪录的 159 GW，达到 1,291 GW（增长 14%）。相比之下，核电装机容量仅增加 1.5 GW 至 399.5 GW，而运行中的核电容量下降了 0.5 GW。

hackernews · xbmcuser · 10月17日 14:01 · [社区讨论](https://news.ycombinator.com/item?id=50131256)

**背景**: 容量系数衡量的是电厂实际发电量相对于其最大潜力的比例；太阳能的容量系数低于核能，因为它只在白天发电。然而，太阳能的装机容量增长如此之快，以至于其总发电量现已超过核能。电力结构指的是用于发电的能源组合，这一转变反映了全球能源转型的更广泛趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Capacity_factor">Capacity factor - Wikipedia Solar capacity and capacity factor - Life by Numbers Solar Capacity Factor Before ROI: Start With a 1 MW Example How to Calculate Solar Power Plant Capacity Factor</a></li>
<li><a href="https://ourworldindata.org/electricity-mix">Electricity Mix | Our World in Data</a></li>

</ul>
</details>

**社区讨论**: 评论者强调，这一里程碑是基于实际发电的太瓦时数，而不仅仅是装机容量，并指出太阳能在飞速发展，风能也即将超过核能。一些人对核能的停滞表示遗憾，而另一些人则强调，需要更多的清洁能源来完全取代化石燃料，包括用于合成石化原料。

**标签**: `#energy`, `#solar`, `#nuclear`, `#climate`, `#renewables`

---

<a id="item-4"></a>
## [Pele 将 Mermaid 图表渲染为可主题化的 SVG](https://pele.run/) ⭐️ 6.0/10

Pele 是一个轻量级开源 JavaScript 库，可直接将 Mermaid 图表渲染为 SVG，并通过 CSS 变量实现主题化，而不依赖外部布局引擎或 UI 框架。其压缩后体积为 230 kB，且没有直接依赖。 Mermaid 内置的样式能力通常有限，而将颜色暴露为可覆盖的 CSS 变量，有助于把图表更轻松地集成到文档站点和设计系统中，并保持明暗主题一致。这对需要在文档中嵌入图表并希望更精细控制外观的开发者很有价值。 Pele 是开源的（托管于 github.com/obsidianmd/pele），但社区反馈指出其示例对深色模式不够友好，并且对于复杂图表仍会继承 Mermaid 的布局局限。

hackernews · dchest · 10月17日 15:55 · [社区讨论](https://news.ycombinator.com/item?id=50132193)

**背景**: Mermaid 是一种流行的类 Markdown 语言，用于从文本生成图表和流程图，广泛用于文档和开发者工具中。默认情况下，Mermaid 使用自带的样式渲染图表，难以针对不同主题进行定制。Pele 通过输出 SVG 并将颜色定义为 CSS 变量来解决这一问题，任何样式表都可以覆盖这些变量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pele.run/">Pele · Mermaid diagrams as themeable SVG</a></li>
<li><a href="https://elsolitario.org/en/2026/10/17/pele-render-mermaid-diagrams-svg/">Mermaid Diagrams to SVG: What Is Pele and How to Use It</a></li>
<li><a href="https://mermaid.js.org/">Mermaid | Diagramming and charting tool</a></li>

</ul>
</details>

**社区讨论**: 评论者认可其主题化思路，但也提出了一些担忧：有人指出 Mermaid 对复杂图表的布局往往很差，样式只是次要问题；另一人表示示例对深色模式不够友好；还有人指出存在无样式内容闪烁（FOUC）。其他人询问是否开源，并建议在项目页面上添加 GitHub 链接。

**标签**: `#mermaid`, `#svg`, `#diagrams`, `#theming`, `#visualization`

---

<a id="item-5"></a>
## [家庭实验者用多力多滋染料使鸡胸肉变透明](https://chillphysicsenjoyer.substack.com/p/making-chicken-transparent-using) ⭐️ 6.0/10

一位爱好物理的博主通过将生鸡胸肉浸泡在多力多滋中的黄色染料酒石黄溶液中，复现了一项组织透明化研究，并在 6-12 小时后观察到部分透明。该实验记录在 Substack 的一篇文章中，在 Hacker News 上引发了热烈讨论，获得 255 分和 66 条评论。 这项家庭复现展示了一种低成本实现生物组织透明化实验室技术的方法，而该技术通常昂贵且需要专业设备。它还凸显了食品科学与易于进行的实验如何吸引广泛社区并激发实用技巧。 由于设备限制，实验仅实现了部分透明，作者还指出切生鸡胸肉薄片的难度。评论者建议将鸡肉轻微冷冻以便切片，并使用真空低温烹饪法进行更长时间的浸泡。

hackernews · crescit_eundo · 10月17日 13:55 · [社区讨论](https://news.ycombinator.com/item?id=50131213)

**背景**: 组织透明化是一种生物学技术，通过使周围介质的折射率与组织相匹配，使不透明组织变得透明，从而允许光线通过以进行成像。酒石黄（又称黄色 5 号）是一种合成食用色素，常用于多力多滋等零食中。该实验的灵感来自一篇关于用酒石黄使活体组织透明的论文。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://daily.dev/posts/making-chicken-transparent-using-dorito-dust-etrr3nyea">Making Chicken Transparent Using Dorito Dust - daily.dev</a></li>
<li><a href="https://news.lavx.hu/article/amateur-scientist-uses-dorito-dye-to-partially-clarify-chicken-breast">Amateur Scientist Uses Dorito Dye to Partially Clarify ...</a></li>
<li><a href="https://zeli.app/story/50131213">A home experimenter turns raw chicken · Hacker News | Zeli</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了实用技巧，如冷冻鸡肉以便切片和使用真空低温烹饪法，其他人则开玩笑说这道菜的起源故事是为了制作多力多滋风味鸡肉。一位评论者指出，欧洲的多力多滋不含酒石黄，且含有该色素的产品必须标注可能对儿童活动和注意力产生不良影响的警告标签。

**标签**: `#food science`, `#experiment`, `#Hacker News`, `#community discussion`, `#novelty`

---

<a id="item-6"></a>
## [Reddit 帖子探讨如何批评 ICLR 投稿中的 AI 生成写作](https://www.reddit.com/r/MachineLearning/comments/1x8oksb/what_is_wrong_with_ai_writing_iclr_edition_d/) ⭐️ 6.0/10

一位 Reddit 用户在 r/MachineLearning 上发布了一个来自其正在审阅的 ICLR 论文的匿名 AI 生成文本示例，并询问社区如何实质性地批评此类写作，因为仅仅称其为“AI 写作”并不合理，因为 AI 编辑是允许的。 这凸显了同行评审中日益增长的挑战：随着 AI 生成文本在学术投稿中越来越普遍，审稿人需要共同的标准来批评糟糕的写作，而不是仅仅因为其是 AI 辅助就予以否定。 示例文本被描述为“难以理解”，包含令人困惑的短语，如“在六个操作点中的零个上以不更高的成本优于最佳基线，并且在三个中的零个上优于置换安慰剂，增益高达约 1.5 未被排除”，这说明了 AI 模型可能产生的那种模糊、充满术语的行文。

reddit · r/MachineLearning · /u/bobrodsky · 10月17日 23:40

**背景**: ICLR（国际学习表征会议）是机器学习领域的顶级会议，审稿人会对提交的论文进行评估。像 Claude 这样的 AI 写作工具越来越多地被用于起草或编辑学术文本，这引发了人们对同行评审中清晰度和真实性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/International_Conference_on_Learning_Representations">International Conference on Learning Representations - Wikipedia</a></li>
<li><a href="https://iclr.cc/">2027 Conference</a></li>

</ul>
</details>

**标签**: `#AI writing`, `#peer review`, `#academic writing`, `#ICLR`, `#machine learning`

---

<a id="item-7"></a>
## [17 款 AI 模型在 7700 手扑克中对决：前沿、廉价、本地与 Jev](https://www.reddit.com/r/MachineLearning/comments/1x8j8kg/17_ais_7700_hands_of_poker_frontier_vs_cheap_vs/) ⭐️ 6.0/10

一位 Reddit 用户发布了一项大规模评估，让 17 款 AI 模型打了 7700 手扑克，比较了前沿模型、廉价模型、本地模型和 Jev 模型。该帖子提供了这些模型类别在性能和成本权衡方面的实证比较。 这项评估为不同类别的 AI 模型在战略性多步骤任务上的表现提供了实用见解，帮助开发者和研究人员根据成本和能力做出明智的模型选择决策。它还凸显了在扑克这一测试不确定性下推理能力的领域中对 LLM 进行基准测试的日益增长的兴趣。 该评估涵盖了 7700 手牌，为比较模型性能提供了可观的样本量。然而，该帖子是 Reddit 上的提交，技术深度有限，且扑克领域较为小众，因此结果可能无法推广到其他任务。

reddit · r/MachineLearning · /u/Civil-Demand555 · 10月17日 19:41

**背景**: 扑克已成为评估 LLM 战略推理和不确定性下决策能力的热门基准，出现了 PokerBench 和 Poker Eval 等基准。比较的模型包括前沿模型（最先进、高成本）、廉价模型（低成本 API 模型）、本地模型（在本地硬件上运行）以及 Jev——TypeSafe AI 开发的一种专有判别模型，它返回带有置信分数的类型化决策，而不是生成文本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jev_(AI_model)">Jev (AI model)</a></li>
<li><a href="https://huggingface.co/papers/2501.08328">Paper page - PokerBench: Training Large Language Models to become...</a></li>
<li><a href="https://ibrahimahmed.ca/evals/poker/">Poker Eval</a></li>

</ul>
</details>

**标签**: `#AI evaluation`, `#LLM comparison`, `#poker`, `#benchmarking`, `#model performance`

---

<a id="item-8"></a>
## [EpochGo：基于离线 LLM 和确定性流水线的本地优先 AutoML](https://www.reddit.com/r/MachineLearning/comments/1x8c2sq/epochgo_localfirst_multiagent_automl_engine_using/) ⭐️ 6.0/10

EpochGo 是一个开源、本地优先的 AutoML 系统，它使用离线的 Ollama LLM（qwen2.5-coder:7b）作为编排器来生成特征工程和建模策略，而所有数据转换和模型拟合都通过 Scikit-Learn 流水线确定性地执行。它完全在 16GB 内存的消费级硬件上运行，无需云 API，并能自动生成容器化的 FastAPI 端点用于服务。 这种方法解决了应用机器学习中的两大痛点：云 API 成本以及将表格数据发送给第三方服务带来的数据隐私风险，还有 LLM 在数学推理中的幻觉问题。通过保持一切本地化并使用确定性执行，它可能吸引有 GDPR 或 DPDP 等严格合规要求的企业。 LLM 仅对模式元数据（列分布、基数、缺失情况）进行推理，从不接触原始数据行；生成的 Python 代码在执行前被解析为抽象语法树（AST）以强制安全，防止任意命令或数据泄露。系统使用隔离的 K 折交叉验证评估 XGBoost、随机森林和逻辑回归等流水线，但作者寻求关于离线处理高基数分类数据的反馈。

reddit · r/MachineLearning · /u/Grouchy-Excitement28 · 10月17日 14:48

**背景**: AutoML（自动化机器学习）旨在自动选择预处理步骤、模型和超参数。Ollama 是一个简化本地运行大语言模型的工具，而 Qwen2.5-Coder 是通过 Ollama 可用的代码专用 LLM。Scikit-Learn 是一个流行的经典机器学习 Python 库，提供将预处理和建模步骤链接起来的 Pipeline 对象。本地优先架构优先在用户设备上运行计算，减少对云服务的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ollama.com/library/qwen2.5-coder:7b">qwen2.5-coder:7b - ollama.com</a></li>
<li><a href="https://github.com/huggingface/Qwen2.5-Coder">GitHub - huggingface/Qwen2.5-Coder: Qwen2.5-Coder is the code ...</a></li>
<li><a href="https://github.com/mljar/mljar-supervised">GitHub - mljar/mljar-supervised: Python package for AutoML on...</a></li>

</ul>
</details>

**标签**: `#AutoML`, `#Local LLM`, `#Ollama`, `#Scikit-Learn`, `#Privacy`

---