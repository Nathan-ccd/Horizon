---
layout: default
title: "Horizon Summary: 2026-06-22 (ZH)"
date: 2026-06-22
lang: zh
---

> 从 17 条内容中筛选出 12 条重要资讯。

---

1. [我过去的工作是否仅因欺诈而存在？](#item-1) ⭐️ 8.0/10
2. [宁可重复，不要错误的抽象](#item-2) ⭐️ 8.0/10
3. [发布 GPT-2 中等规模的无 Softmax 注意力模型](#item-3) ⭐️ 8.0/10
4. [对数：科学中的统一概念](#item-4) ⭐️ 7.0/10
5. [Anthropic 对 Claude 的身份验证引发争议](#item-5) ⭐️ 7.0/10
6. [sqlite-utils 4.0rc1 增加迁移和嵌套事务](#item-6) ⭐️ 7.0/10
7. [Cloudflare 推出面向 AI 代理的临时账户](#item-7) ⭐️ 7.0/10
8. [矩阵循环单元更新：稳定性修复与局限性](#item-8) ⭐️ 7.0/10
9. [个人网站 JSON-LD 教程](#item-9) ⭐️ 6.0/10
10. [改进的 DVD-JEPA 演示添加噪声和基线对比](#item-10) ⭐️ 6.0/10
11. [微调 Whisper 以适应领域特定词汇的最佳方法](#item-11) ⭐️ 6.0/10
12. [LoRA 上的 EMA 自蒸馏问题](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [我过去的工作是否仅因欺诈而存在？](https://david.newgas.net/did-my-old-job-only-exist-because-of-fraud/) ⭐️ 8.0/10

一篇个人文章及 Hacker News 上的社区讨论探讨了虚假计费、预算虚增和承包商轮换如何制造不必要的技术岗位，质疑许多企业职位的合法性。 这凸显了企业和政府技术支出中的系统性低效和道德问题，可能影响工作保障、项目质量和公众信任。 作者描述了一种模式：承包商被解雇后通过外包公司以加价方式重新聘用；社区成员分享了政府项目中的虚假计费以及以避税为目的的亏损公司的经历。

hackernews · advisedwang · 6月21日 21:40 · [社区讨论](https://news.ycombinator.com/item?id=48622867)

**背景**: 虚假计费是指对未提供的服务开具发票或虚增工时，而预算虚增是指使预算提案大于实际估算。承包商轮换是指为了满足预算或人员编制目标而频繁更换承包商的做法。这些做法可能创造出主要为了消耗分配资金而非创造价值的岗位。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/False_billing">False billing - Wikipedia</a></li>
<li><a href="https://www.pindrop.com/glossary/billing-fraud/">What is billing fraud? | Pindrop</a></li>
<li><a href="https://www.tookitaki.com/glossary/false-billing">False Billing</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了关于虚假计费、预算虚增和承包商轮换的个人经历，一些人指出这些做法在私营和政府部门都很常见。大家一致认为这些问题损害了效率和道德，但也有人争论是否所有此类角色都纯粹是欺诈性的，或者有时是管理不善的结果。

**标签**: `#fraud`, `#software engineering`, `#corporate culture`, `#ethics`, `#tech industry`

---

<a id="item-2"></a>
## [宁可重复，不要错误的抽象](https://sandimetz.com/blog/2016/1/20/the-wrong-abstraction) ⭐️ 8.0/10

Sandi Metz 在 2016 年的博文中指出，过早或错误的抽象比代码重复危害更大，主张只有在清晰、正确的抽象出现时才进行重构。 这篇文章挑战了软件工程中长期存在的“重复总是坏的”教条，影响了开发者对代码设计和重构决策的思考方式。 文章强调过早消除重复会导致僵化、难以修改的抽象，并建议在至少有三个重复实例后再进行抽象。

hackernews · rafaepta · 6月21日 16:08 · [社区讨论](https://news.ycombinator.com/item?id=48620090)

**背景**: 在软件工程中，抽象是一种通过隐藏实现细节来降低复杂性的技术。然而，创建错误的抽象会引入耦合，使代码更难修改。代码重复虽然常被视为坏味道，但有时是更安全的中间状态。

**社区讨论**: 评论者普遍认同文章的观点，有些人强调“单一事实来源”原则仍应指导何时可以接受重复。其他人指出函数式编程和 TypeScript 可以减少重复问题，还有一些人分享了过早抽象导致问题的个人经验。

**标签**: `#software engineering`, `#abstraction`, `#code quality`, `#refactoring`, `#OOP`

---

<a id="item-3"></a>
## [发布 GPT-2 中等规模的无 Softmax 注意力模型](https://www.reddit.com/r/MachineLearning/comments/1ubmybr/i_released_a_softmaxfree_attention_model_at_gpt2/) ⭐️ 8.0/10

一个 GPT-2 中等规模（约 3.54 亿参数，在 115 亿 token 上训练）的无 Softmax 注意力模型已发布，包含开放权重和自定义 Triton 内核，通过结构稀疏性和 tile-skipping 技术节省长上下文 VRAM。 这项工作表明，无 Softmax 注意力可以扩展到数亿参数规模，同时减少长序列的内存占用，有望在消费级硬件上实现更高效的大语言模型推理。 该模型使用结构稀疏模式和 tile-skipping 内核来避免计算无关 tile 的注意力，从而减少长上下文推理期间的 VRAM 消耗。自定义 Triton 内核与模型权重一起开源。

reddit · r/MachineLearning · /u/NonGameCatharsis · 6月21日 10:46

**背景**: 标准 Transformer 注意力使用 Softmax 函数归一化注意力分数，这需要计算所有查询-键点积，对于长序列来说内存密集。无 Softmax 注意力用更简单的归一化（如 L1 范数）替代 Softmax，减少计算开销。结构稀疏性和 tile-skipping 通过跳过不必要的计算进一步提高效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2206.08898">SimA: Simple Softmax-free Attention for Vision Transformers</a></li>
<li><a href="https://github.com/deepseek-ai/TileKernels">GitHub - deepseek-ai/TileKernels: A kernel library written in tilelang · GitHub</a></li>

</ul>
</details>

**标签**: `#attention`, `#efficient-transformers`, `#open-source`, `#Triton`, `#long-context`

---

<a id="item-4"></a>
## [对数：科学中的统一概念](https://alexkritchevsky.com/2026/05/25/everything-is-logarithms.html) ⭐️ 7.0/10

一篇题为《万物皆对数》的文章认为，对数是数学、科学和工程中一个基础且统一的概念，强调了它们在简化复杂运算中的作用。 这一观点可能重塑数学的教学和理解方式，通过对数的视角强调不同领域之间的深层联系。 文章从历史、计算和理论角度探讨对数，包括它们在计算尺中的应用以及向复数和李理论的扩展。

hackernews · E-Reverance · 6月21日 21:10 · [社区讨论](https://news.ycombinator.com/item?id=48622626)

**背景**: 对数是幂运算的逆运算，可以将乘法简化为加法。在电子计算器出现之前，它们历史上被用于简化计算，并出现在许多科学公式中，如里氏震级和 pH 值。

**社区讨论**: 评论者称赞文章的深度，有人提到历史上使用对数表来简化运算。另一位讨论了作为 torsor 的复对数，还有一位建议文章需要类型系统来明确每个对数的底数和参数。

**标签**: `#mathematics`, `#logarithms`, `#computer science`, `#physics`, `#education`

---

<a id="item-5"></a>
## [Anthropic 对 Claude 的身份验证引发争议](https://support.claude.com/en/articles/14328960-identity-verification-on-claude) ⭐️ 7.0/10

Anthropic 更新了隐私政策，明确允许对 Claude 用户进行身份验证，通过第三方提供商 Persona 收集政府身份证件、照片和生物识别数据。 尽管该政策并非新规，但它重新引发了人们对美国 AI 出口限制和用户隐私的担忧，非美国用户可能被阻止访问顶级模型，从而转向国际替代方案。 Anthropic 表示不会将身份数据用于模型训练，但 Persona 可能使用这些数据改进欺诈预防。OpenAI 也有类似政策，验证失败可能导致用户永久无法使用顶级模型。

hackernews · bathory · 6月21日 12:44 · [社区讨论](https://news.ycombinator.com/item?id=48618455)

**背景**: 美国政府一直在收紧 AI 出口管制，最近指示 Anthropic 限制某些国家访问其最强模型。身份验证通过确认用户位置和资格来帮助执行这些限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.claude.com/en/articles/14328960-identity-verification-on-claude">Identity verification on Claude | Claude Help Center</a></li>
<li><a href="https://cybernews.com/ai-news/anthropic-privacy-policy-id-verification/">Anthropic updates privacy policy, includes ID verification for Claude users</a></li>
<li><a href="https://digg.com/tech/0c4r13bx">White House directs Anthropic to restrict export of Mythos 5 and...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出该政策自 4 月以来就已存在，但许多人将其与最近的美国出口限制联系起来。一些人批评关于永久锁定和 Persona 数据使用的不透明性，而另一些人则将其与网络中立性问题相比较。

**标签**: `#AI policy`, `#identity verification`, `#Anthropic`, `#privacy`, `#export controls`

---

<a id="item-6"></a>
## [sqlite-utils 4.0rc1 增加迁移和嵌套事务](https://simonwillison.net/2026/Jun/21/sqlite-utils-40rc1/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0 的候选版本引入了数据库迁移功能，并通过 db.atomic() 支持嵌套事务。 这一主要版本升级为广泛使用的 SQLite Python 库带来了关键的 schema 迁移功能，使开发者更容易管理数据库变更。 迁移功能移植自现有的 sqlite-migrate 包，不支持反向迁移；嵌套事务通过 SQLite 的 savepoint 实现。

rss · Simon Willison · 6月21日 23:35

**背景**: sqlite-utils 是一个 Python 库和 CLI 工具，在 Python 的 sqlite3 模块之上提供更高级的操作。SQLite 本身不支持真正的嵌套事务，但可以通过 savepoint 模拟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/sqlite-migrate">GitHub - simonw/sqlite-migrate: A simple database migration system for SQLite, based on sqlite-utils · GitHub</a></li>
<li><a href="https://www.slingacademy.com/article/using-nested-transactions-to-simplify-complex-workflows-in-sqlite/">Using Nested Transactions to Simplify Complex Workflows in SQLite</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#python`, `#database`, `#migrations`, `#cli`

---

<a id="item-7"></a>
## [Cloudflare 推出面向 AI 代理的临时账户](https://simonwillison.net/2026/Jun/21/temporary-cloudflare-accounts/#atom-everything) ⭐️ 7.0/10

Cloudflare 宣布推出临时、短暂的账户，允许任何人无需注册即可通过命令 `npx wrangler deploy --temporary` 部署 Workers 项目。部署后项目保持在线 60 分钟，并可认领以延长其生命周期。 该功能大幅降低了尝试 Cloudflare Workers 的门槛，尤其适合需要快速原型开发而无需管理账户的 AI 代理和开发者。它还能在 CI/CD 流水线或 AI 工作流中实现自动化的脚本驱动部署。 临时部署功能完整但仅限 60 分钟；用户可通过生成的 URL 认领项目以使其永久化。该功能适用于任何 Workers 项目，正如 Simon Willison 所演示的，他使用 GPT-5.5 构建了一个重定向解析器并通过临时标志部署。

rss · Simon Willison · 6月21日 22:01

**背景**: Cloudflare Workers 是一个无服务器计算平台，在靠近用户的边缘运行代码。Wrangler 是管理 Workers 项目的官方 CLI 工具。临时部署是短暂、隔离的环境，常用于测试或预览，但这是 Cloudflare 首次提供无需账户即可使用的临时部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.cloudflare.com/workers/wrangler/">Wrangler · Cloudflare Workers docs</a></li>

</ul>
</details>

**社区讨论**: 在 Hacker News 上，社区普遍欢迎该功能的简洁性及其在 AI 代理用例中的潜力。一些评论者认为 60 分钟的限制对于临时需求是合理的，而另一些人则讨论了允许未经身份验证的部署所带来的安全隐患。

**标签**: `#cloudflare`, `#serverless`, `#ai agents`, `#deployment`, `#workers`

---

<a id="item-8"></a>
## [矩阵循环单元更新：稳定性修复与局限性](https://www.reddit.com/r/MachineLearning/comments/1ubz5o8/an_update_on_matrix_recurrent_units_an_attention/) ⭐️ 7.0/10

作者重新审视了矩阵循环单元（MRU），这是一种线性时间的注意力替代方案，并根据社区关于在大数据集上训练不稳定的反馈，实现了多种稳定训练的方法，包括 LDU 分解和 Cayley 映射正交化。 MRU 为 Transformer 中的二次注意力提供了一种潜在的线性时间替代方案，可降低长序列的计算成本；然而，此次更新表明，在更大任务上的稳定性和性能仍然具有挑战性，凸显了在实践中替代注意力的困难。 作者测试了斜对称矩阵指数、LDU 分解和带 Cayley 映射的 QR 分解等方法，发现 LDU 表现最佳。在 TinyStories 数据集上，MRU 的表现不如 GPT-2 基线，而正交矩阵出人意料地阻碍了学习，表明剪切变换至关重要。

reddit · r/MachineLearning · /u/mikayahlevi · 6月21日 19:39

**背景**: 矩阵循环单元（MRU）是一种循环神经网络，它使用矩阵乘法而非向量操作来处理序列。它们利用并行扫描算法实现线性时间复杂度，从而在现代硬件上高效运行。注意力机制虽然强大，但具有二次复杂度，这促使研究人员寻找更快的替代方案，如 MRU。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recurrent_neural_network">Recurrent neural network - Wikipedia</a></li>
<li><a href="https://developer.nvidia.com/gpugems/gpugems3/part-vi-gpu-computing/chapter-39-parallel-prefix-sum-scan-cuda">Chapter 39. Parallel Prefix Sum ( Scan ) with CUDA | NVIDIA Developer</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子收到了建设性的反馈，评论者指出了训练不稳定的问题，并建议了限制矩阵状态的方法。作者采纳了这些建议，从而提高了稳定性，但在更大数据集上性能仍然较差，这表明社区持续参与并进行了迭代改进。

**标签**: `#machine learning`, `#sequence modeling`, `#attention alternative`, `#recurrent neural networks`, `#linear-time architecture`

---

<a id="item-9"></a>
## [个人网站 JSON-LD 教程](https://hawksley.dev/blog/json-ld-explained-for-personal-websites/) ⭐️ 6.0/10

一篇教程解释了如何在个人网站上使用 JSON-LD 结构化数据来改善 SEO 并在搜索结果中启用丰富摘要。 这有助于个人网站所有者通过显示面包屑导航和星级评分等增强的搜索结果功能，获得更好的可见性和点击率。 JSON-LD 是实现 Schema.org 词汇的几种格式之一（与 RDFa 和 Microdata 并列），Google 提供了关于其在搜索外观中使用的具体文档。

hackernews · ethanhawksley · 6月21日 18:51 · [社区讨论](https://news.ycombinator.com/item?id=48621517)

**背景**: 结构化数据是一种帮助搜索引擎理解网页内容的标记。JSON-LD（用于链接数据的 JavaScript 对象表示法）是一种轻量级格式，可以嵌入 HTML 中描述人物、文章或事件等实体。丰富摘要是增强的搜索结果，显示超出标准蓝色链接的额外信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://json-ld.org/">JSON - LD - JSON for Linked Data</a></li>
<li><a href="https://search.google.com/test/rich-results">Rich Results Test - Google Search Console</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，Google 转向 LLM 生成的摘要可能会降低传统 SEO 的价值，并建议查阅 Google 关于结构化数据的官方文档。一些人还指出 JSON-LD 只是其中一种方法，还有 RDFa 和 Microdata 等替代方案。

**标签**: `#JSON-LD`, `#structured data`, `#SEO`, `#web development`

---

<a id="item-10"></a>
## [改进的 DVD-JEPA 演示添加噪声和基线对比](https://www.reddit.com/r/MachineLearning/comments/1ubtf09/a_slightly_improved_dvdjepa_demo_p/) ⭐️ 6.0/10

一位 Reddit 用户发布了改进版的 DVD-JEPA 演示，增加了环境噪声和公平的像素空间基线对比，更好地展示了 JEPA 忽略无关细节的能力。 此次更新直接回应了 JEPA 演示的一个关键批评——缺乏噪声，并更清晰地展示了 JEPA 相对于像素空间方法的优势，这对推进自监督学习研究至关重要。 演示中 JEPA 和像素空间基线使用了大致相同的参数数量和计算预算，确保公平对比。作者移除了网页演示和异常检测部分，以聚焦于 JEPA 的核心概念。

reddit · r/MachineLearning · /u/Kirne · 6月21日 15:49

**背景**: JEPA（联合嵌入预测架构）是一种自监督学习方法，它在学习到的嵌入空间中预测表示，而非生成像素。这使其能够忽略背景噪声等不可预测的细节，这与 MAE 等像素空间模型不同。原始的 DVD-JEPA 演示是一个最小的、可在 CPU 上训练的世界模型，用于模拟弹跳标志。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dvd-jepa.vercel.app/">DVD - JEPA — a world model that dreams a bouncing logo</a></li>
<li><a href="https://github.com/moudrkat/jepa-demo">GitHub - moudrkat/ jepa - demo : Playing with jepa models to show the...</a></li>
<li><a href="https://arxiv.org/abs/2301.08243">[2301.08243] Self - Supervised Learning from Images with...</a></li>

</ul>
</details>

**社区讨论**: 原帖的评论指出了缺乏噪声的问题，这促使了本次改进。新演示因弥补了这一不足并提供公平基线而获得积极反馈。

**标签**: `#JEPA`, `#self-supervised learning`, `#machine learning`, `#demo`

---

<a id="item-11"></a>
## [微调 Whisper 以适应领域特定词汇的最佳方法](https://www.reddit.com/r/MachineLearning/comments/1ubvmdx/best_current_methods_for_finetuning_whisper_on/) ⭐️ 6.0/10

一位 Reddit 用户向社区询问，针对领域特定的西班牙语词汇，微调 OpenAI 的 Whisper 模型的最佳当前方法，提到了 LoRA、QLoRA 和 Spectrum，但寻求更新或更有效的技术。 针对领域特定词汇微调 Whisper 对于医疗或法律转录等应用至关重要，这些场景中技术术语的准确性必不可少，而这一讨论凸显了持续需要高效的适配方法。 该用户专门处理西班牙语，需要模型可靠地检测某些技术术语；他们还询问了收敛所需的标注音频数据量，这反映了实际部署中的关切。

reddit · r/MachineLearning · /u/gothenjoyer_ · 6月21日 17:18

**背景**: Whisper 是 OpenAI 在多语言数据上训练的通用语音识别模型，但可能在领域特定术语上表现不佳。LoRA（低秩适配）和 QLoRA（量化 LoRA）等微调技术通过仅更新一小部分参数，允许在有限计算资源下进行高效适配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/axinc-ai/whisper-fine-tuning-to-transcribe-jargon-976164a5eac8">Whisper Fine Tuning To Transcribe Jargon | by David... | Medium</a></li>
<li><a href="https://github.com/Vaibhavs10/fast-whisper-finetuning">GitHub - Vaibhavs10/fast- whisper - finetuning · GitHub</a></li>
<li><a href="https://github.com/kartikmunjal/whisper-domain-adaptation">GitHub - kartikmunjal/ whisper - domain - adaptation · GitHub</a></li>

</ul>
</details>

**标签**: `#Whisper`, `#fine-tuning`, `#speech recognition`, `#domain adaptation`, `#Spanish`

---

<a id="item-12"></a>
## [LoRA 上的 EMA 自蒸馏问题](https://www.reddit.com/r/MachineLearning/comments/1ubv0f5/ema_on_lora_r/) ⭐️ 6.0/10

一位 Reddit 用户询问是否有论文成功地将指数移动平均（EMA）应用于 LoRA 适配器进行同策略自蒸馏，其中 EMA 适配器作为自教师为可训练适配器生成软标签。 将 EMA 与 LoRA 结合可以实现微调模型的高效自蒸馏，可能在不进行全参数微调的情况下提升性能。这对于通常使用 LoRA 的资源受限场景尤为重要。 用户引用了论文《On-Policy Self-Distillation》（arXiv:2601.19897），该论文使用 EMA 进行自蒸馏，但采用的是全参数微调，而非 LoRA。问题特别询问在 LoRA 或 left 模型上的实证结果。

reddit · r/MachineLearning · /u/South-Conference-395 · 6月21日 16:54

**背景**: LoRA（低秩适应）是一种参数高效的微调方法，向预训练模型添加小型可训练适配器。EMA（指数移动平均）是一种技术，其中教师模型作为学生权重的移动平均值维护，常用于自蒸馏以生成稳定的软目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/lora-adapters">LoRA Adapters : Efficient Model Fine-Tuning</a></li>
<li><a href="https://blog.speechmatics.com/distirbuted-self-distillation">Distributed Self - Distillation | Speechmatics</a></li>

</ul>
</details>

**标签**: `#LoRA`, `#EMA`, `#self-distillation`, `#fine-tuning`, `#machine learning`

---