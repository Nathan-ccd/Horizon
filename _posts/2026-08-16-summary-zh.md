---
layout: default
title: "Horizon Summary: 2026-08-16 (ZH)"
date: 2026-08-16
lang: zh
---

> 从 18 条内容中筛选出 13 条重要资讯。

---

1. [Stripe 以超过 70 亿美元收购 AI 公司 OpenRouter](#item-1) ⭐️ 9.0/10
2. [Anthropic 公开 Claude 系统提示词，引发透明度讨论](#item-2) ⭐️ 8.0/10
3. [AI 模型故意变笨以依赖外部工具](#item-3) ⭐️ 8.0/10
4. [Cloudflare 在切换域名服务器时静默注入分析脚本](#item-4) ⭐️ 8.0/10
5. [Qwen 3.8 27B 表现出色但默认过度思考](#item-5) ⭐️ 8.0/10
6. [Dario Amodei：公众对 AI 的不信任是信任危机，而非营销问题](#item-6) ⭐️ 8.0/10
7. [推理强化学习仅改变 1-3%的令牌；无需强化学习即可复现收益](#item-7) ⭐️ 8.0/10
8. [特立尼达嵌入式工程师为 RISC-V 辩护，称其适合发展中国家](#item-8) ⭐️ 7.0/10
9. [新兴的 AI 额度转售经济](#item-9) ⭐️ 7.0/10
10. [圣露西核电站 1 号机组因控制棒掉落而停堆](#item-10) ⭐️ 7.0/10
11. [开源 30B 模型预计 2027 年 1 月达到前沿水平](#item-11) ⭐️ 7.0/10
12. [Firefox for iOS 新增原生广告拦截器](#item-12) ⭐️ 6.0/10
13. [Qwen 35B 模型从提交中移除，发布前景不明](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Stripe 以超过 70 亿美元收购 AI 公司 OpenRouter](https://www.bloomberg.com/news/articles/2026-08-16/stripe-nears-deal-to-buy-ai-firm-openrouter-for-over-7-billion) ⭐️ 9.0/10

Stripe Inc. 已敲定协议，以超过 70 亿美元收购帮助企业在 AI 模型之间切换的初创公司 OpenRouter Inc.。该交易由彭博社于 2026 年 8 月 16 日报道。 此次收购标志着 Stripe 在支付领域之外的最大举措之一，表明其成为 AI 基础设施关键参与者的雄心。它可能重塑 AI 支付和 API 路由的处理方式，影响开发者及更广泛的 AI 生态系统。 OpenRouter 通过单一 API 为开发者提供 500 多个 AI 模型的访问，并采用分布式基础设施以确保可靠性，以及边缘路由以降低延迟。该交易对 OpenRouter 的估值超过 70 亿美元，较几个月前报道的 13 亿美元估值大幅跃升。

hackernews · zacharyozer · 8月16日 20:31 · [社区讨论](https://news.ycombinator.com/item?id=49323381)

**背景**: Stripe 是一家主要的在线支付处理公司，以其对开发者友好的 API 而闻名。OpenRouter 充当大型语言模型（LLM）的统一接口，允许开发者将请求路由到不同的 AI 提供商。此次收购与 Stripe 在处理高容量、延迟敏感 API 请求方面的专长相契合，可能将其金融轨道的抽象扩展到 AI 模型路由。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-08-16/stripe-nears-deal-to-buy-ai-firm-openrouter-for-over-7-billion">Stripe Nears Deal to Buy AI Firm OpenRouter for Over $7 Billion</a></li>
<li><a href="https://openrouter.ai/about">About - The Unified Interface For LLMs | OpenRouter</a></li>
<li><a href="https://www.digitimes.com/news/a20260724VL207/infrastructure-startup-acquisition-demand.html">Stripe reportedly eyes OpenRouter in potential US$10B AI infrastructure deal</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了战略动机，如 Stripe 抽象 LLM 轨道的雄心，以及对支付量的担忧，尤其是在 OpenAI 将其支付提供商更换为 Adyen 之后。一些人质疑高估值，而另一些人则指出投资者获得了快速回报。还有人担心对客户的影响，并建议寻找替代方案。

**标签**: `#acquisition`, `#AI`, `#payments`, `#OpenRouter`, `#Stripe`

---

<a id="item-2"></a>
## [Anthropic 公开 Claude 系统提示词，引发透明度讨论](https://platform.claude.com/docs/en/release-notes/system-prompts) ⭐️ 8.0/10

Anthropic 在其官方文档网站上公开了 Claude 模型使用的系统提示词，让公众前所未有地接触到塑造 Claude 行为的隐藏指令。此次发布包括多个 Claude 模型的提示词，如 Opus 4.8 以及新提到的 Claude Fable 5 和 Claude Mythos 5。 这一透明度举措意义重大，因为它让 AI 从业者和研究人员难得地窥见主流商业 AI 模型的内部运作，可能影响提示工程实践和行业规范。同时，它也加剧了关于模型透明度与竞争优势之间平衡，以及系统提示词最佳长度和具体性的持续争论。 公布的提示词明显很长，一些社区成员认为这与近期建议保持提示词简短和专注的建议相矛盾。Simon Willison 创建了提示词的 git 历史以追踪版本间变化，并强调了新增内容，如对新模型（如 Claude Fable 5 和 Claude Mythos 5）的引用，以及指示 Claude 自行验证图像是否存在而非假设其存在。

hackernews · tosh · 8月16日 12:48 · [社区讨论](https://news.ycombinator.com/item?id=49319556)

**背景**: 系统提示词是在对话开始时提供给 AI 模型的初始指令，用于设定上下文和行为准则。AI 供应商通常对其保密，以防止滥用并保持竞争优势，但泄露和自愿披露引发了公众兴趣。Anthropic 决定公开这些提示词，符合 AI 开发中更广泛的透明度趋势，但也引发了对潜在越狱和此类披露有效性的质疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/release-notes/system-prompts">System Prompts - Claude Platform Docs</a></li>
<li><a href="https://github.com/Piebald-AI/claude-code-system-prompts">GitHub - Piebald-AI/claude-code-system-prompts: All parts of Claude Code's system prompt, 27 builtin tool descriptions, sub agent prompts (Plan/Explore/Task), utility prompts (CLAUDE.md, compact, statusline, magic docs, WebFetch, Bash cmd, security review, agent creation). Updated for each Claude Code version. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人称赞透明度并认为提示词对分析有用，而另一些人则批评其长度并质疑冗长指令的必要性。Simon Willison 的 git 历史方法受到好评，一些评论者对论坛对 AI 相关故事的审核表示担忧，尽管这与主要话题无关。

**标签**: `#AI`, `#LLM`, `#Anthropic`, `#System Prompts`, `#Transparency`

---

<a id="item-3"></a>
## [AI 模型故意变笨以依赖外部工具](https://w4g1.dev/blog/models-are-getting-dumber-on-purpose) ⭐️ 8.0/10

文章认为，AI 模型正有意地不再将事实知识存储在权重中，而是依赖外部工具和知识库。这一趋势被视为模型设计上的重大转变，对模型架构和减少幻觉有重要影响。 这一转变可能从根本上改变 AI 模型的构建、评估和部署方式，有望减少幻觉并提高适应性。同时，它也引发了对模型规模、知识截止日期以及 RAG 等外部检索系统作用的思考。 文章引用了 SimpleQA 基准测试结果，指出即使像 Gemini 2.5 Pro 这样的最佳模型，在不使用工具的情况下事实回忆准确率也仅为 53%。文章还提到，随着存储知识变得不那么重要，模型卡片可能最终不再列出知识截止日期。

hackernews · hruvhwe · 8月16日 19:04 · [社区讨论](https://news.ycombinator.com/item?id=49322695)

**背景**: 大型语言模型（LLM）传统上在训练期间将大量事实知识存储在参数中。然而，这种方法存在局限性，包括知识过时和幻觉问题。检索增强生成（RAG）和工具使用正成为替代方案，使模型能够按需访问外部的最新信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation">Retrieval-augmented generation - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2608.00006">Enhancing LLMs with Context-Specific Knowledge for Mitigating...</a></li>
<li><a href="https://medium.com/@kushagra.1300/when-ai-imagines-understanding-hallucinations-in-large-language-models-308687f9aafc">When AI Imagines: Understanding Hallucinations in Large... | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者表示对可插拔知识库感兴趣，允许用户按需添加特定领域的知识。一些人指出文章中的数据已过时，因为 SimpleQA 未更新，Gemini 2.5 Pro 已有 16 个月的历史。其他人则争论推理和事实是否真的可以分离，并提到了像 Cactus 的 Needle 这样的最新工具调用模型。

**标签**: `#AI`, `#LLM`, `#model design`, `#knowledge bases`, `#hallucination`

---

<a id="item-4"></a>
## [Cloudflare 在切换域名服务器时静默注入分析脚本](https://news.ycombinator.com/item?id=49322107) ⭐️ 8.0/10

有用户报告称，在将域名服务器切换到 Cloudflare 后，该服务静默地在其纯 HTML、无 JavaScript 的网站中注入了分析脚本。用户必须通过分析仪表板手动选择退出，他们认为这种做法具有侵入性。 此问题凸显了一家大型科技公司在透明度和隐私方面的担忧，影响了许多可能未意识到 Cloudflare 默认注入分析功能的用户。这强调了此类功能应选择加入而非选择退出的重要性，并可能促使 Cloudflare 重新考虑其默认设置。 注入的脚本来自 static.cloudflareinsights.com/beacon.min.js，用户可以通过 Content-Security-Policy meta 标签阻止它。评论指出，只有在使用 Cloudflare 作为代理（而非仅 DNS 模式）时才会发生注入。

hackernews · stagas · 8月16日 17:49

**背景**: Cloudflare Web Analytics 是一项免费、注重隐私的分析服务，提供基本的网站使用统计。当网站使用 Cloudflare 的代理时，Cloudflare 可以自动将分析脚本注入 HTML 响应中，但此行为在设置过程中并未向用户明确披露。不希望使用该功能的用户必须手动在仪表板中禁用它，或使用 CSP 来阻止它。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cloudflare.com/web-analytics/">Cloudflare Web Analytics | Cloudflare</a></li>

</ul>
</details>

**社区讨论**: 社区表达了担忧，并分享了技术解决方案，例如使用 Content-Security-Policy meta 标签来阻止脚本。一些用户澄清说，只有在使用 Cloudflare 作为代理时才会发生注入，而非仅 DNS 模式，其他人则确认在他们的网站上看到了注入的脚本。

**标签**: `#Cloudflare`, `#privacy`, `#analytics`, `#DNS`, `#web development`

---

<a id="item-5"></a>
## [Qwen 3.8 27B 表现出色但默认过度思考](https://simonwillison.net/2026/Aug/16/qwen-38-27b/) ⭐️ 8.0/10

阿里巴巴 Qwen 实验室于 2026 年 8 月 14 日发布了 Apache 2 许可的 27B 参数视觉语言模型 Qwen 3.8 27B，其基准测试成绩较前代和闭源模型有显著提升。Simon Willison 在本地测试后发现，其默认的“xhigh”推理强度会导致大量 token 消耗和极长的生成时间。 此次发布对开源权重 LLM 社区意义重大，因为它提供了一个紧凑、易于部署的模型，可在消费级硬件上运行，可能使先进 AI 能力更加普及。默认的过度思考行为凸显了本地部署中效率和速度方面的实际挑战。 该模型默认使用“xhigh”推理强度，导致 LM Studio 默认的 8,192 token 上下文限制在处理简单任务时被耗尽；将上下文增加到完整的 262,144 后问题得以解决。在一次测试中，生成一只骑自行车的鹈鹕的 SVG 图像耗时 21 分钟，使用了 22,276 个推理 token 生成了 3,223 个输出 token。

rss · Simon Willison · 8月16日 22:00

**背景**: Qwen 3.8 27B 基于 Qwen3.5 架构，是一款密集视觉语言模型，专为在笔记本电脑和边缘设备上部署而设计。Apache 2 许可允许自由使用、修改和分发，使其对开发者和研究人员具有吸引力。该模型支持可调的推理强度级别（xhigh、medium、low），以平衡准确性和速度，但默认的 xhigh 设置针对复杂任务优化，不适合日常使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://lmstudio.ai/models/qwen/qwen3.8-27b">qwen/qwen3.8-27b • LM Studio</a></li>
<li><a href="https://aireleasetracker.com/model/qwen/qwen3.8-27b">Qwen3.8-27B — Benchmarks, Specs & Release Date</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Open Source`, `#AI`, `#Qwen`, `#Benchmarks`

---

<a id="item-6"></a>
## [Dario Amodei：公众对 AI 的不信任是信任危机，而非营销问题](https://simonwillison.net/2026/Aug/16/dario-amodei/) ⭐️ 8.0/10

Anthropic CEO Dario Amodei 在 Twitter 上表示，公众对 AI 的不信任源于对机构更广泛的信任危机，而非 AI 领袖对风险的警告。他指出，重建信任需要切实的成就，如真正治愈癌症，而非营销活动。 作为 AI 领域领军人物，这一观点挑战了“AI 领袖的风险警告是公众反弹主因”的普遍假设。它将讨论转向提供切实利益，可能影响 AI 公司处理公众关系和产品开发的方式。 Amodei 明确拒绝了为 Anthropic 开展“光鲜亮丽、正面宣传的营销活动”的想法，称此类信息陈词滥调且具有欺骗性。他承认包括 Anthropic 在内的 AI 公司尚未兑现造福世界的重大承诺，并称这是最准确的批评。

rss · Simon Willison · 8月16日 15:05

**背景**: 随着 AI 的快速发展以及行业领袖对生存风险的高调警告，公众对 AI 的信任度有所下降。Amodei 的评论发表之际，AI 公司正面临对其社会影响的审查，并常被指责夸大能力。他的论点表明，科技行业与公众之间长期存在的信任赤字早于 AI 出现，需要实质性行动来修复。

**标签**: `#AI ethics`, `#public trust`, `#Anthropic`, `#AI industry`, `#Dario Amodei`

---

<a id="item-7"></a>
## [推理强化学习仅改变 1-3%的令牌；无需强化学习即可复现收益](https://www.reddit.com/r/LocalLLaMA/comments/1vpuhh1/paper_claims_rl_for_reasoning_only_changes_13_of/) ⭐️ 8.0/10

最近一篇论文声称，用于推理的强化学习（RL）仅改变轨迹中 1-3%的令牌，并且作者以约 1000 倍更少的计算量在无需 RL 的情况下复现了性能提升。这对 RL 在提升大语言模型推理能力方面的必要性提出了挑战。 这一发现可能显著影响推理模型的训练方式，有可能降低与 RL 相关的巨大计算成本。如果可以通过更简单的方法复现收益，可能会使高级推理能力的获取更加普及，并将研究重点从依赖 RL 的方法上转移。 论文表明，令牌级别的 RL 目标可以被稀疏估计，随机 20%的令牌子集保留了大部分全令牌性能，表明更新存在冗余。作者证明，替代训练方法可以用约 1000 倍更少的计算量实现类似的收益，但摘要中未详细说明具体方法。

reddit · r/LocalLLaMA · /u/juanviera23 · 8月16日 11:21

**背景**: 强化学习（RL）已被用于增强大语言模型的推理能力，常用方法包括 PPO 和 GRPO。在推理 RL 中，轨迹是单次 LLM 生成，通常从简单问题的约 500 个令牌到高难度竞赛数学的 10,000-30,000+个令牌不等。RL 的高计算成本促使研究人员探索更高效的替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2604.09459">From Reasoning to Agentic: Credit Assignment in Reinforcement...</a></li>
<li><a href="https://huggingface.co/papers/2605.07660">Paper page - Not All Tokens Learn Alike: Attention Entropy Reveals...</a></li>
<li><a href="https://magazine.sebastianraschka.com/p/the-state-of-llm-reasoning-model-training">Understanding GRPO and New Insights from Reasoning Model Papers</a></li>

</ul>
</details>

**标签**: `#reinforcement learning`, `#reasoning`, `#LLM training`, `#efficiency`, `#research`

---

<a id="item-8"></a>
## [特立尼达嵌入式工程师为 RISC-V 辩护，称其适合发展中国家](https://rvembedded.com/blog_post/12/) ⭐️ 7.0/10

一位来自特立尼达的嵌入式工程师发表博客文章，回应了对 RISC-V 的批评，认为尽管存在运输和碎片化挑战，其低成本和灵活性对发展中国家的开发者至关重要。 这一观点凸显了 RISC-V 开放且免版税的特性如何使硬件开发民主化，让成本是主要障碍的地区的工程师更容易获得。它拓宽了讨论范围，超越了典型的硅谷中心视角，并强调了开源硬件的全球影响。 作者指出，小批量芯片的运输成本可能高达 60 至 200 美元，但认为 RISC-V 芯片可以以每片 10 美分的价格到达，这使得成本差异对发展中国家的开发者意义重大。文章还讨论了碎片化问题，认为对于嵌入式用途，二进制分发不如桌面或服务器市场那么关键。

hackernews · Narishma · 8月16日 17:01 · [社区讨论](https://news.ycombinator.com/item?id=49321717)

**背景**: RISC-V 是一种基于 RISC 原则的免费开放指令集架构（ISA），于 2010 年在加州大学伯克利分校开发，由 RISC-V International 维护。与 ARM 和 x86 等专有 ISA 不同，RISC-V 可以免版税实现，使其对成本敏感的应用具有吸引力，尤其是在嵌入式系统和微控制器领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RISC-V_architecture">RISC-V architecture</a></li>
<li><a href="https://moschip.com/blog/semiconductor/getting-started-with-risc-v-and-its-architecture/">Getting started with RISC - V and its Architecture</a></li>

</ul>
</details>

**社区讨论**: 评论者大多欣赏这一新颖视角，但指出了逻辑上的不一致，特别是运输成本与芯片成本之间的对比。有人指出，运往尼日利亚或孟加拉国的费用可能没有声称的那么高，还有人认为作者回应的是与原始批评不同的观点。

**标签**: `#RISC-V`, `#embedded systems`, `#hardware`, `#cost analysis`, `#developer perspective`

---

<a id="item-9"></a>
## [新兴的 AI 额度转售经济](https://vectoral.com/blog/who-are-the-token-brokers) ⭐️ 7.0/10

这篇文章探讨了转售未使用的 AI API 额度的新兴市场，强调了其中的风险、滥用模式以及模型蒸馏的作用。文章讨论了个人和平台如何交易额度，这通常违反服务条款。 这一趋势对 AI 平台具有重要意义，因为它可能导致收入损失、安全风险和账户滥用。它还引发了对免费额度提供可持续性以及需要更好执行机制的问题。 文章指出，转售额度通常违反服务条款，平台可以通过 IP 地址识别和标记账户。模型蒸馏被强调为一个独特的方面，转售的额度被用于训练较小的模型，这可能损害原始提供商的业务。

hackernews · mlenhard · 8月16日 14:44 · [社区讨论](https://news.ycombinator.com/item?id=49320611)

**背景**: AI API 额度通常免费或以折扣提供以吸引开发者，但这些额度可能在二级市场上转售。模型蒸馏是一种技术，利用更大、更强模型输出来训练较小的模型，使用转售额度可以低成本实现。这种做法类似于其他行业长期存在的滥用模式，如航空公司忠诚度计划。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://openai.com/index/api-model-distillation/">Model Distillation in the API | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了信任第三方转售商的风险，一位用户指出可能存在黑客攻击和数据隐私问题。另一位评论者指出蒸馏是一个独特的方面，而其他人则提到类似滥用模式在其他行业已存在数十年。一些用户还批评研究过于肤浅，建议查看 linux.do 等平台以了解更广泛的额度转售经济。

**标签**: `#AI`, `#economics`, `#security`, `#API`, `#marketplace`

---

<a id="item-10"></a>
## [圣露西核电站 1 号机组因控制棒掉落而停堆](https://www.wptv.com/news/treasure-coast/region-st-lucie-county/saint-lucie-nuclear-power-plant-unit-1-manually-shut-down-after-3-control-rods-drop-into-reactor-core) ⭐️ 7.0/10

佛罗里达州圣露西核电站 1 号机组因三根控制棒意外掉入反应堆堆芯而被手动停堆。该事件最近发生，为确保安全而进行了手动停堆。 这一事件凸显了反应堆安全机制的有效性，控制棒的自动插入防止了潜在的事态升级。同时，它也强调了核电运营中持续警惕和调查的重要性，以维护公众信任和安全。 控制棒是反应堆停堆系统的一部分，其插入可降低反应性。掉落原因正在调查中，可能因素包括程序问题或电气故障，正如 2024 年该电厂发生的类似事件。

hackernews · toomuchtodo · 8月16日 15:16 · [社区讨论](https://news.ycombinator.com/item?id=49320856)

**背景**: 控制棒用于核反应堆中吸收中子并控制裂变速率。在像圣露西这样的压水堆中，反应堆停堆（或紧急停堆）涉及插入控制棒以快速关闭反应堆。手动停堆是应对意外情况并确保安全的常规程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Scram">Scram - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shutdown_(nuclear_reactor)">Shutdown (nuclear reactor) - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=49320856">St Lucie Nuclear Reactor Unit 1 manually shutdown, 3 control rods ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍认为这一事件是安全性的体现，指出美国反应堆设计为在控制棒掉落时进入次临界状态。一些评论者提到了 2024 年的类似事件并讨论了可能的根本原因，而另一些人则指出公众缺乏简单的风险参考。

**标签**: `#nuclear energy`, `#reactor safety`, `#control rods`, `#incident`

---

<a id="item-11"></a>
## [开源 30B 模型预计 2027 年 1 月达到前沿水平](https://www.reddit.com/r/LocalLLaMA/comments/1vq279o/based_on_an_accelerating_frontier_local/) ⭐️ 7.0/10

Reddit 上的一项分析预测，到 2027 年 1 月，一个约 300 亿参数的开源模型将匹配当前前沿模型的能力，基于本地模型达到早期前沿性能的加速趋势。该帖子详细比较了过去的尖端模型与开源对应模型，显示时间滞后正在缩短。 这一预测凸显了前沿模型与开源模型之间差距的迅速缩小，这可能使尖端 AI 能力的获取民主化，并削弱专有实验室的竞争优势。如果实现，它将使高端消费硬件能够运行具有前沿智能水平的模型，从而改变本地 AI 应用。 该分析结合了 Arena-Hard、SWE-bench 和 GPQA 等基准来比较模型，指出 Qwen3.6-27B 在 SWE-bench Verified 上得分 77.2，超过了 Opus 4 的 72.5。作者承认这一预测是推测性的，取决于近期效率提升的持续。

reddit · r/LocalLLaMA · /u/PetersOdyssey · 8月16日 16:55

**背景**: 开源 LLM 历来落后于专有前沿模型，但最近的发布如 Llama 3.3 70B 和 Qwen3 系列在各种基准上表现出竞争力。这一趋势表明，模型效率和开源能力正在快速提升，可能加速追赶的时间线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reddit.com/r/singularity/comments/1h89wje/llama33_70b_beats_gpt4o_claude35sonner_and/">r/singularity on Reddit: Llama-3.3 70b beats gpt-4o, claude-3,5-sonner, and Llama-3.1 405b on almost all benchmarks. And it's open source</a></li>
<li><a href="https://www.datacamp.com/blog/llama-3-3-70b">What Is Meta's Llama 3.3 70B? How It Works, Use Cases & More | DataCamp</a></li>
<li><a href="https://www.helicone.ai/blog/meta-llama-3-3-70-b-instruct">Llama 3.3 just dropped — is it better than GPT-4 or Claude-Sonnet-3.5?</a></li>

</ul>
</details>

**标签**: `#LLM`, `#open-source`, `#model scaling`, `#prediction`, `#local models`

---

<a id="item-12"></a>
## [Firefox for iOS 新增原生广告拦截器](https://support.mozilla.org/en-US/kb/block-ads-firefox-ios) ⭐️ 6.0/10

Mozilla 已在 Firefox for iOS 中添加了原生广告拦截器，用户无需安装单独的应用程序或扩展即可直接在浏览器中拦截广告。该功能现已在浏览器设置中提供。 这简化了 iOS 用户的广告拦截操作，此前他们必须依赖第三方内容拦截器或 Firefox Focus 等单独浏览器。这增强了 Firefox 的隐私吸引力，并可能吸引寻求内置解决方案的用户。 原生广告拦截器取代了增强跟踪保护（ETP）的广告拦截功能，可在设置中切换。它拦截网页上的广告，但不拦截搜索引擎结果页面（包括 Google、Bing 和 DuckDuckGo）上的广告。

hackernews · pentagrama · 8月16日 12:58 · [社区讨论](https://news.ycombinator.com/item?id=49319633)

**背景**: 由于 App Store 的限制，Firefox for iOS 使用 Apple 的 WebKit 浏览器引擎，这限制了扩展支持。此前，用户必须使用单独的内容拦截器或 Firefox Focus，后者通过 iOS 内容拦截器提供系统级广告拦截。此次更新将广告拦截直接集成到 Firefox 主应用中，减少了额外工具的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49319633">Firefox for iOS now has a native adblocker | Hacker News</a></li>
<li><a href="https://github.com/mozilla-mobile/firefox-ios/issues/5198">Firefox for iOS should ship with a content blocker · Issue #5198 · mozilla-mobile/firefox-ios</a></li>
<li><a href="https://piunikaweb.com/2026/06/25/firefox-ios-built-in-ad-blocker/">Firefox for iOS will get a built-in ad blocker very soon, team confirms</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 Firefox Focus 已经提供了系统级广告拦截器，并质疑为什么 iOS 上仍不支持扩展，以 Orion 为例。其他人指出 Safari 的 uBlock Origin Lite 仍然是一个强大的替代方案，而一些人则希望 iOS 上能支持 Gecko 引擎。

**标签**: `#Firefox`, `#iOS`, `#adblocker`, `#privacy`, `#browser`

---

<a id="item-13"></a>
## [Qwen 35B 模型从提交中移除，发布前景不明](https://www.reddit.com/r/LocalLLaMA/comments/1vpxbm8/newer_commits_removed_the_qwen_35b/) ⭐️ 6.0/10

Qwen 仓库最近的提交中移除了 35B 模型，暗示备受期待的 Qwen 35B 发布可能被取消。这一变化引发了开源 LLM 社区的担忧。 Qwen 35B 模型，尤其是具有 3B 激活参数的 MoE 变体，因其高效能和性能在社区中被广泛使用。如果它不发布，依赖它进行本地部署和微调的开发者和研究人员将受到重大影响，可能减缓高效 LLM 部署领域的创新。 移除出现在 Qwen 官方仓库的提交中，但尚未有官方公告。涉及的模型很可能是 Qwen 3.5-35B-A3B，这是一个混合专家（MoE）模型，总参数 35B，每个 token 仅激活 3B 参数，可在 24GB 显存的消费级 GPU 上运行。

reddit · r/LocalLLaMA · /u/Local-Cardiologist-5 · 8月16日 13:39

**背景**: Qwen 是阿里巴巴云开发的大语言模型系列，以发布开源权重模型而闻名，在开源社区中广受欢迎。Qwen 3.5 系列包括高效的 MoE 模型，如 35B-A3B，它在性能和资源需求之间取得平衡，适合本地部署。社区经常依赖这些模型进行微调和推理，而无需依赖云端。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/Qwen">Org profile for Qwen on Hugging Face, the AI community building the...</a></li>
<li><a href="https://lovableapp.org/blog/2026-qwen35-models-guide">Qwen 3 . 5 Model Series 2026: Complete Guide to... | Lovable APP Blog</a></li>
<li><a href="https://insiderllm.com/guides/best-way-run-qwen-3-6-35b-moe-locally/">Best Way to Run Qwen 3.6 35 B MoE Locally: VRAM... | InsiderLLM</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子表达了担忧，并敦促社区在社交媒体和 Hugging Face 上发声，向 Qwen 施压以发布该模型。评论者可能持有相同观点，强调该模型的受欢迎程度以及开发者透明度的必要性。

**标签**: `#Qwen`, `#open-source LLM`, `#model release`, `#community`

---