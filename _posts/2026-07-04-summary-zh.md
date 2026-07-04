---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> 从 12 条内容中筛选出 9 条重要资讯。

---

1. [欧盟议会间谍调查成员遭飞马间谍软件攻击](#item-1) ⭐️ 9.0/10
2. [SearXNG：一款免费、注重隐私的元搜索引擎](#item-2) ⭐️ 8.0/10
3. [Current AI 发布开源 AI 差距地图](#item-3) ⭐️ 8.0/10
4. [CDD 仅从 logits 恢复微调数据](#item-4) ⭐️ 8.0/10
5. [探讨开放权重大语言模型的微调抵抗性](#item-5) ⭐️ 8.0/10
6. [本地运行 SOTA 大模型指南引发成本争议](#item-6) ⭐️ 7.0/10
7. [AI 导致开发者课程销量下降 50%以上](#item-7) ⭐️ 7.0/10
8. [H64LM：用 PyTorch 从零构建的 249M 参数 MoE Transformer](#item-8) ⭐️ 7.0/10
9. [让 AI 编程助手自行判断](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [欧盟议会间谍调查成员遭飞马间谍软件攻击](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 9.0/10

公民实验室发现，一名参与调查间谍软件的欧洲议会成员在 2022 年和 2023 年多次被飞马间谍软件感染。 这一事件表明，一个有权在多个欧洲国家进行监控的国家行为者正在针对欧盟议员，破坏了民主进程和隐私保护。 感染发生在 2022 年 10 月 21 日和 2023 年 3 月 6 日至 7 日，并与针对欧洲俄语和白俄罗斯语流亡记者及活动家的飞马间谍软件活动重叠。

hackernews · ledoge · 7月3日 20:38 · [社区讨论](https://news.ycombinator.com/item?id=48779683)

**背景**: 飞马间谍软件是以色列 NSO 集团开发的一款强大间谍软件，能够远程入侵移动设备以提取数据、录制通话和激活摄像头。公民实验室是多伦多大学的一个研究单位，专门调查数字威胁，并已揭露多起飞马间谍软件的滥用行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**社区讨论**: 评论者指出间谍软件调查员被黑具有讽刺意味，并质疑欧盟议会为何不强制区分工作设备和个人设备。一些人将此次攻击与希腊及其他欧盟国家持续的间谍软件丑闻联系起来。

**标签**: `#cybersecurity`, `#surveillance`, `#Pegasus`, `#European Parliament`, `#spyware`

---

<a id="item-2"></a>
## [SearXNG：一款免费、注重隐私的元搜索引擎](https://github.com/searxng/searxng) ⭐️ 8.0/10

SearXNG 是一款免费、开源的元搜索引擎，它聚合多个搜索引擎的结果，同时尊重用户隐私。它是已停止维护的 Searx 的一个分支，目前仍在积极开发和社区支持中。 SearXNG 提供了一种尊重隐私的主流搜索引擎替代方案，使用户能够避免被追踪和分析。它对于注重隐私的用户、构建本地 AI 工具的开发者以及希望自建搜索基础设施的人尤其有价值。 SearXNG 支持 JSON 输出，适合与 AI 代理和 RAG 应用集成。用户可以通过 Docker 自建实例，或使用超过 70 个公共实例之一，但结果可能较慢，且偶尔因上游封锁需要解决验证码。

hackernews · theanonymousone · 7月3日 20:15 · [社区讨论](https://news.ycombinator.com/item?id=48779454)

**背景**: 元搜索引擎聚合多个搜索引擎的结果，而不维护自己的索引。SearXNG 是 Searx 的一个分支，Searx 由 asciimoo 创建但后来停止维护；SearXNG 继续其开发，专注于隐私和去中心化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Metasearch_engine">Metasearch engine</a></li>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG - Wikipedia</a></li>
<li><a href="https://github.com/searxng/searxng">GitHub - searxng/searxng: SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled. · GitHub</a></li>

</ul>
</details>

**社区讨论**: Searx 的原始创建者 asciimoo 表示，由于元搜索概念的局限性，他不再参与开发，并提到了他的新项目 Hister。用户反映 SearXNG 比直接使用搜索引擎慢，但对大多数查询来说足够好，有些人将其与 YaCY 后端结合使用或用于构建 RAG 应用。其他人讨论了将 SearXNG 与本地 AI 模型以及 TinySearch 等工具结合使用，以优化代理上下文。

**标签**: `#privacy`, `#search engine`, `#open source`, `#metasearch`

---

<a id="item-3"></a>
## [Current AI 发布开源 AI 差距地图](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 8.0/10

Current AI（一个于 2025 年 2 月在巴黎 AI 行动峰会上成立的非营利组织）发布了开源 AI 差距地图 v0.1，索引了开源 AI 生态系统中的 421 个产品和 24,400 个工件。 这份全面的地图提供了开源 AI 领域的结构化数据，帮助研究人员和开发者识别差距与机遇，并促进 AI 生态系统的透明度。 该地图详细列出了来自 228 个组织的 266 个软件工具、85 个模型、50 个数据集和 20 个硬件项目，底层数据以 MIT 许可证发布在 GitHub 上。

rss · Simon Willison · 7月3日 22:04

**背景**: Current AI 是一个全球非营利合作伙伴关系，已承诺投入 4 亿美元资金，旨在构建 AI 的公共选项。差距地图基于哥伦比亚会议、MOF、Hugging Face 等机构的工作，绘制开源 AI 技术栈并识别缺失的组件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://map.currentai.org/">Current AI – Open Source AI Gap Map</a></li>

</ul>
</details>

**标签**: `#open source`, `#AI`, `#ecosystem mapping`, `#non-profit`, `#Current AI`

---

<a id="item-4"></a>
## [CDD 仅从 logits 恢复微调数据](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 8.0/10

对比解码差异分析（CDD）仅通过 logits 访问就能从大语言模型中恢复逐字微调数据，无需模型权重或激活值，性能优于之前的白盒方法如激活差异透镜（ADL）。 该方法暴露了大语言模型中的重大隐私和安全漏洞，攻击者仅通过 API 的 logits 访问就能提取敏感的微调数据，挑战了“隐藏权重即可保护”的假设。 CDD 在 SDF 基准测试中，对四个模型家族（1B 到 32B 参数）的 19/20 个生物体×模型对实现了 4+/5 的逐字恢复分数，而 ADL 尽管需要完整权重访问，分数从未超过 3/5。

reddit · r/MachineLearning · /u/CebulkaZapiekana · 7月3日 19:01

**背景**: 模型差异分析旨在通过比较微调模型与其基础模型来检测微调模型学到了什么。先前的工作——激活差异透镜（ADL）需要白盒访问模型权重和激活值，且仅能恢复模糊的领域级描述。CDD 则利用 logits 上的对比解码（灰盒设置）直接提取微调数据中的逐字文本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2510.13900v2">Narrow Finetuning Leaves Clearly Readable Traces in Activation ...</a></li>
<li><a href="https://www.emergentmind.com/topics/activation-difference-lens-adl">Activation Difference Lens ( ADL )</a></li>
<li><a href="https://arxiv.org/html/2511.14045v1">GRPO Privacy Is at Risk: A Membership Inference Attack Against Reinforcement Learning With Verifiable Rewards</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论强调了 CDD 惊人的有效性，以及一个令人不安的发现：虚构人物“Dr. Elena Rodriguez”出现在不相关的微调中，表明来自 LLM 生成的合成数据的污染。评论者对隐私影响表示担忧，并讨论了潜在的防御措施。

**标签**: `#LLM`, `#privacy`, `#model diffing`, `#finetuning`, `#security`

---

<a id="item-5"></a>
## [探讨开放权重大语言模型的微调抵抗性](https://www.reddit.com/r/MachineLearning/comments/1um9bs7/what_does_safe_ai_look_like_d/) ⭐️ 8.0/10

Reddit 上的一场讨论质疑，对于开放权重的大语言模型，微调抵抗性是否是一个有意义的安全目标，因为坚定的用户可以轻易通过简单脚本绕过安全措施。 这场辩论挑战了当前开放权重模型安全训练的成本效益，可能影响 AI 社区的治理和发布决策。 讨论指出，新模型的“未审查”变体在发布后迅速出现，并询问即使无法完全预防，增加攻击者成本或降低安全移除的可靠性是否有价值。

reddit · r/MachineLearning · /u/Aaron_Rock · 7月3日 09:07

**背景**: 开放权重大语言模型的权重公开可用，允许用户为各种目的进行微调。安全训练旨在使模型与人类价值观对齐，但最近的研究表明，微调可以轻易移除这些安全防护，引发了对这类防御有效性的质疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2605.26526">Open - Weight LLM Fine - Tuning Defenses are Susceptible to Simple...</a></li>
<li><a href="https://www.libertify.com/interactive-library/open-weight-llm-risks-malicious-fine-tuning-analysis/">Open - Weight LLM Risks: Malicious Fine - Tuning Analysis —.</a></li>
<li><a href="https://groundy.com/articles/why-fine-tuning-strips-safety-alignment-from-open-weight-llms/">Why Fine - Tuning Strips Safety Alignment From Open - Weight LLMs...</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子可能包含多种观点，一些人认为微调抵抗性徒劳无功，因为绕过安全措施很容易，而另一些人则认为提高攻击者成本仍然值得。讨论还可能涉及治理影响和对替代安全方法的需求。

**标签**: `#AI safety`, `#open-weight models`, `#fine-tuning`, `#LLM governance`, `#adversarial robustness`

---

<a id="item-6"></a>
## [本地运行 SOTA 大模型指南引发成本争议](https://github.com/jamesob/local-llm) ⭐️ 7.0/10

Jamesob 在 GitHub 上发布了一份指南，详细介绍了如何构建昂贵的本地环境来运行最先进的大语言模型，高端配置预算从约 4 万美元起步。 该指南引发了社区关于本地部署大语言模型成本效益的讨论，许多人认为 API 订阅以更低的价格提供了更好的性能。 指南中提出的 4 万美元构建方案实际成本接近 5 万至 5.5 万美元，包括四块每块 1.2 万美元的 GPU，并依赖量化和剪枝技术将模型适配到可用显存中。

hackernews · livestyle · 7月3日 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48775921)

**背景**: 最先进的大语言模型（SOTA LLMs）是在推理和生成等任务中性能最高的 AI 模型。本地运行它们需要巨大的硬件投入，通常需要多块大显存高端 GPU，并且往往涉及量化等折衷手段，这会降低模型质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/daya-shankar/sota-ai-models">SOTA AI Models: Benchmarks, Metrics & Deployment Guide</a></li>
<li><a href="https://mofchemicals.com/local-llm-ollama-guide">Local LLM Deployment — Ollama</a></li>
<li><a href="https://talkingtech.io/running-llms-locally-with-ollama-in-2026/">Running LLMs Locally with Ollama in 2026</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍批评其成本，指出 4 万美元可以支付 16.8 年的 Claude Opus 订阅（每月 200 美元）。一些人建议采用统一内存架构（如 128GB 显存）作为更实用的折中方案。

**标签**: `#LLM`, `#local deployment`, `#hardware`, `#cost analysis`, `#AI infrastructure`

---

<a id="item-7"></a>
## [AI 导致开发者课程销量下降 50%以上](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 7.0/10

Josh W. Comeau 报告称，他的新课程《Whimsical Animations》销量预计仅为通常水平的三分之一，现有课程销售额相比去年下降超过 50%，他将这一下滑归因于 AI。 来自知名课程创作者的第一手数据表明，AI 正在显著减少对付费开发者教育的需求，可能重塑在线学习行业，并引发对开发者工作稳定性的担忧。 Comeau 指出双重打击：学习者因 AI 质疑开发者工作的未来，而 LLM 提供免费个性化辅导，降低了购买付费课程的动机。他提到其他课程创作者也面临类似 50%或以上的收入下降。

rss · Simon Willison · 7月3日 21:25

**背景**: Josh W. Comeau 是一位知名的前端开发者教育者，制作了关于 CSS 和动画的热门课程。LLM（大型语言模型）如 GPT-4 可以作为个性化导师，提供针对个体学习者的逐步解释，这与结构化的付费课程形成竞争。由于 AI 的快速发展，开发者就业市场存在不确定性，导致一些人质疑投入时间和金钱学习新技能的价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://whimsy.joshwcomeau.com/">Whimsical Animations , a new course from Josh W. Comeau</a></li>
<li><a href="https://medium.com/age-of-awareness/ai-in-education-personalized-learning-with-llms-57405e34446a">AI in Education: Personalized Learning with LLMs | Medium</a></li>

</ul>
</details>

**标签**: `#AI impact`, `#developer education`, `#online courses`, `#job market`, `#LLMs`

---

<a id="item-8"></a>
## [H64LM：用 PyTorch 从零构建的 249M 参数 MoE Transformer](https://www.reddit.com/r/MachineLearning/comments/1umqfd2/h64lm_a_249mparameter_mixtureofexperts/) ⭐️ 7.0/10

一位开发者发布了 H64LM，这是一个完全用 PyTorch 从零实现的 249M 参数混合专家 Transformer，集成了 GQA、SwiGLU、RoPE 和滑动窗口注意力，并在 WikiText-103 上训练作为概念验证。 该项目提供了一个干净、具有教育意义的现代 LLM 组件参考实现，不依赖高层抽象，帮助研究人员和从业者理解 MoE Transformer 的内部工作原理。 该模型使用 8 个专家和 Top-2 路由以及三种辅助路由损失，在 WikiText-103 上达到约 40.5 的最佳验证困惑度，并包含已知限制，如仅支持 batch-size-1 生成和使用 DataParallel 而非真正的 DDP。

reddit · r/MachineLearning · /u/Loose_Literature6090 · 7月3日 21:18

**背景**: 混合专家（MoE）是一种每输入仅激活部分模型参数的技术，从而在相似计算成本下实现更大模型。分组查询注意力（GQA）减少键/值头以加速推理，SwiGLU 是一种门控激活函数，RoPE 通过旋转编码位置。这些组件在 Llama 和 Mixtral 等现代 LLM 中很常见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2305.13245">GQA: Training Generalized Multi-Query Transformer Models ...</a></li>
<li><a href="https://github.com/rasbt/LLMs-from-scratch/blob/main/ch04/04_gqa/README.md">Grouped-Query Attention (GQA) - rasbt/LLMs-from-scratch - GitHub</a></li>
<li><a href="https://medium.com/@s_boudefel/exploring-swiglu-the-activation-function-powering-modern-llms-9697f88221e7">Exploring SwiGLU : The Activation Function Powering... | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了干净的实现和详细的文档，一些用户建议改进，如添加真正的 DDP 支持和扩展到更大数据集。其他人讨论了辅助损失的选择和滑动窗口注意力的权衡。

**标签**: `#Mixture-of-Experts`, `#Transformer`, `#PyTorch`, `#LLM`, `#Open Source`

---

<a id="item-9"></a>
## [让 AI 编程助手自行判断](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 6.0/10

Simon Willison 分享了来自 Claude Code 团队和开发者 Jesse Vincent 的建议：让 Fable 等 AI 编程助手自行判断何时编写测试以及选择更经济的模型，以节省 token。他成功让 Claude Code 将编程任务委托给运行低功耗模型的子代理。 这种方法能显著降低 AI 编程助手重度用户的 token 消耗和成本，尤其是在 Fable 即将涨价之际。它展示了一种实用的提示工程技术，可在不牺牲质量的前提下提高效率。 关键提示词是：“对于所有编程任务，自行判断并选择合适的低功耗模型，在子代理中运行。”Claude Code 将此保存为记忆文件，规定 Sonnet 用于实质性实现，Haiku 用于琐碎编辑，而需要判断的任务保留在主模型中。

rss · Simon Willison · 7月3日 18:51

**背景**: 像 Claude Code 这样的 AI 编程助手按 token 计费，而 Fable 5 等顶级模型价格昂贵。开发者常常因为让 AI 重新读取过多上下文或为琐碎更改运行测试而浪费 token。将常规编程任务委托给更便宜的模型可以大幅降低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://support.claude.com/en/articles/11940350-claude-code-model-configuration">Claude Code model configuration | Claude Help Center</a></li>
<li><a href="https://docs.bswen.com/blog/2026-06-08-reduce-ai-token-usage/">How to Reduce AI Coding Assistant Token Usage by... | BSWEN</a></li>

</ul>
</details>

**标签**: `#AI coding assistants`, `#Claude Code`, `#prompt engineering`, `#efficiency`

---