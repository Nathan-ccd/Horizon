---
layout: default
title: "Horizon Summary: 2026-08-10 (ZH)"
date: 2026-08-10
lang: zh
---

> 从 17 条内容中筛选出 14 条重要资讯。

---

1. [AI 语言模型首次设计出可行噬菌体基因组](#item-1) ⭐️ 9.0/10
2. [Claude Opus 5 系统提示词揭示 Fable/Mythos 暂停事件](#item-2) ⭐️ 8.0/10
3. [提示注入的机制解释与基于角色的防御](#item-3) ⭐️ 8.0/10
4. [使用 LLM 学习复杂主题：实用指南](#item-4) ⭐️ 7.0/10
5. [开发者抄袭应用后的道歉引发质疑](#item-5) ⭐️ 7.0/10
6. [研究发现出租车司机阿尔茨海默病死亡率较低](#item-6) ⭐️ 7.0/10
7. [W3C 的“酷 URI 不会改变”在链接腐烂时代依然引起共鸣](#item-7) ⭐️ 7.0/10
8. [AI 可穿戴设备与监控军备竞赛](#item-8) ⭐️ 7.0/10
9. [GitHub Models 退役，破坏 Actions 工作流](#item-9) ⭐️ 7.0/10
10. [SQLite 文本修订历史压缩原型显示出潜力](#item-10) ⭐️ 7.0/10
11. [模拟 AI 精度在噪声阈值处骤降，而非平滑退化](#item-11) ⭐️ 7.0/10
12. [约翰·C·莉莉 1978 年关于固态智能与人类消亡的论文](#item-12) ⭐️ 6.0/10
13. [Windows 11 天气应用占用超过 1 GB 内存](#item-13) ⭐️ 6.0/10
14. [Reddit 帖子称赞文章终于讲清了位置编码](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI 语言模型首次设计出可行噬菌体基因组](https://www.reddit.com/r/MachineLearning/comments/1vjj4pr/r_generative_design_of_novel_bacteriophages_with/) ⭐️ 9.0/10

研究人员使用基因组语言模型 Evo 1 和 Evo 2 生成了完整的噬菌体基因组，实验测试产生了 16 个具有显著进化新颖性的可行噬菌体。这标志着首次成功生成并实验验证了完整基因组的设计。 这一突破表明人工智能能够在全基因组规模上设计功能性生物序列，为合成生物学和治疗性噬菌体工程开辟了新的可能性。它代表了 AI 驱动生物设计的范式转变，可能加速新型抗菌剂和其他生物技术的发展。 该研究以裂解噬菌体ΦX174 为设计模板，利用了前沿基因组语言模型 Evo 1 和 Evo 2。生成的基因组表现出真实的遗传结构和理想的宿主趋向性，实验证实了 16 个可行噬菌体。

reddit · r/MachineLearning · /u/moschles · 8月9日 07:11

**背景**: 基因组语言模型（gLMs）是在 DNA 序列上训练的大型语言模型，将基因组视为生物文本，以学习其语法和调控相互作用。Evo 1 和 Evo 2 由 Arc 研究所及其合作者开发，是此类模型中最大的，其中 Evo 2 在来自超过 128,000 个基因组的 9.3 万亿个核苷酸上训练。噬菌体是感染细菌的病毒，其宿主趋向性决定了它们能感染哪些细菌菌株，这对噬菌体疗法等应用至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Evo_(AI)">Evo (AI) - Wikipedia</a></li>
<li><a href="https://arcinstitute.org/news/evo2">AI can now model and design the genetic code for all domains of life with Evo 2 | Arc Institute</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bacteriophage">Bacteriophage - Wikipedia</a></li>

</ul>
</details>

**标签**: `#genome language models`, `#synthetic biology`, `#bacteriophage design`, `#AI for biology`, `#Evo 2`

---

<a id="item-2"></a>
## [Claude Opus 5 系统提示词揭示 Fable/Mythos 暂停事件](https://simonwillison.net/2026/Aug/9/claude-opus-5-system-prompt/#atom-everything) ⭐️ 8.0/10

Simon Willison 重点介绍了 Claude Opus 5 的系统提示词，其中包含关于 Claude Fable 5 和 Mythos 5 因美国出口管制而暂时暂停的通知。该通知澄清，这两个模型于 2026 年 6 月 12 日至 7 月 1 日期间被暂停，在管制解除后恢复访问。 这很重要，因为它展示了 Anthropic 如何利用系统提示词确保模型对训练数据截止日期之后发生的事件保持准确性。同时，它也凸显了出口管制对 AI 模型的现实影响，影响到依赖这些先进模型的开发者和用户。 通知指出，Claude Fable 5 和 Mythos 5 于 2026 年 6 月 9 日发布，6 月 12 日被暂停，在美国商务部解除管制后于 7 月 1 日恢复。系统提示词指示 Claude 准确、实事求是地确认暂停事件，并引导用户查阅 Anthropic 的官方声明以获取更多细节。

rss · Simon Willison · 8月9日 23:31

**背景**: Claude Fable 5 和 Mythos 5 是 Anthropic 于 2026 年 6 月发布的先进 AI 模型，其中 Fable 5 广泛可用，而 Mythos 5 仅限有限发布。美国商务部以国家安全为由对这些模型实施出口管制，导致其被暂时暂停。系统提示词是嵌入 AI 模型中的指令，用于引导其行为并确保对训练数据截止日期之后的事件做出准确回应。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos - Wikipedia</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5">Introducing Claude Fable 5 and Claude Mythos 5</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI`, `#Claude`, `#System Prompt`, `#Anthropic`, `#Policy`

---

<a id="item-3"></a>
## [提示注入的机制解释与基于角色的防御](https://www.reddit.com/r/MachineLearning/comments/1vjvzm4/a_mechanistic_explanation_of_prompt_injection_and/) ⭐️ 8.0/10

Reddit 用户 u/katxwoods 发布了一篇帖子，从机制角度解释了提示注入，将其视为 LLM 中角色分离的失败，并主张通过研究角色来作为防御策略。 提示注入是 LLM 中的一个关键安全漏洞，从机制上理解它可能带来更稳健的防御。这一视角可能影响开发者设计基于角色的系统，并提升 AI 安全性。 该帖子可能讨论了 LLM 如何无法区分系统、用户和助手角色，从而导致注入攻击。它可能提出研究模型内部的角色表征作为缓解方法。

reddit · r/MachineLearning · /u/katxwoods · 8月9日 17:36

**背景**: 提示注入是一种攻击，通过利用模型无法区分可信指令和用户数据，使恶意输入导致 LLM 产生意外行为。机制可解释性旨在逆向工程神经网络，以理解其内部电路和算法，这可能有助于识别和修复此类漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论可能包含关于机制解释有效性和基于角色防御实用性的不同观点，一些人会争论可解释性方法的可行性。

**标签**: `#prompt injection`, `#LLM security`, `#mechanistic interpretability`, `#AI safety`

---

<a id="item-4"></a>
## [使用 LLM 学习复杂主题：实用指南](https://laurentiugabriel.github.io/blog/articles/how-i-use-llms-to-learn/) ⭐️ 7.0/10

作者分享了一种使用 LLM 学习复杂主题的个人方法，强调迭代提问和事实核查，同时承认其局限性。该文章获得了社区的高度关注，获得了 352 个点赞和 199 条评论。 这篇文章回应了利用 AI 进行教育和自学的日益增长的趋势，提供了实用的技巧，帮助学习者应对 AI 生成内容的挑战。它还引发了关于 LLM 可靠性和深度学习价值的重要讨论。 该方法包括迭代提问，即用户通过追问来加深理解，以及事实核查，即用户将 LLM 提供的信息与可靠来源进行核实。作者指出，LLM 可能产生幻觉，用户不应完全依赖它们获取准确信息。

hackernews · laurentiurad · 8月9日 19:16 · [社区讨论](https://news.ycombinator.com/item?id=49234675)

**背景**: 大型语言模型（LLM）如 GPT-4 和 Claude 是经过海量文本数据训练的人工智能系统，能够生成类似人类的回复。它们越来越多地被用于学习，但其输出可能不准确或有偏见，需要用户批判性地评估信息。文章提供了一个有效使用 LLM 并降低这些风险的框架。

**社区讨论**: 社区评论反映了热情与怀疑的混合。一些用户分享了自己的技巧，比如使用 LLM 重写 RFC 以更好地理解，而另一些用户则对 LLM 的可靠性和走捷径的诱惑表示担忧。一个反复出现的主题是，深度学习需要努力，不能完全被 AI 取代。

**标签**: `#LLM`, `#learning`, `#AI-assisted education`, `#productivity`, `#critical thinking`

---

<a id="item-5"></a>
## [开发者抄袭应用后的道歉引发质疑](https://blog.terrygodier.com/2026/08/09/mea-culpa-dark-hours.html) ⭐️ 7.0/10

开发者 Terry Godier 发表了一篇题为《Mea Culpa – Dark Hours》的博客文章，为其应用道歉，该应用被发现是开源天文应用“Dark Hours”的克隆版。这一道歉因未提及误导苹果和 John Gruber 而受到广泛批评。 这一事件凸显了人们对 AI 辅助抄袭以及 App Store 生态中开发者责任感的日益担忧。它也强调了开发者与像 John Gruber 这样的有影响力人物互动时保持透明的重要性。 原始“Dark Hours”应用可在 darkhours.app 获取。开发者的应用最初因包含占星功能而被拒绝，随后以开源应用的克隆版重新提交，甚至复制了名称。道歉文章未提及或就误导 John Gruber 一事道歉。

hackernews · satvikpendem · 8月9日 13:20 · [社区讨论](https://news.ycombinator.com/item?id=49231154)

**背景**: App Store 的指南禁止某些内容，如占星应用，这可能导致开发者修改应用以获得批准。John Gruber 是一位知名的苹果评论员，他之前曾撰文讨论过该开发者的情况，他的撤回声明加剧了争议。社区讨论表明，开发者可能使用了像 Claude 这样的 AI 工具来克隆应用，引发了对 AI 伦理的质疑。

**社区讨论**: 社区评论大多对开发者的道歉持怀疑态度。用户指出，开发者抄袭了整个项目，包括名称，并对审核过程撒谎。一些人将这一道歉称为“有限坦白”，这是一种公关策略，承认部分错误而隐瞒更严重的事实。还有人批评其未向 John Gruber 道歉。

**标签**: `#AI ethics`, `#plagiarism`, `#App Store`, `#developer accountability`, `#community discussion`

---

<a id="item-6"></a>
## [研究发现出租车司机阿尔茨海默病死亡率较低](https://theconversation.com/taxi-drivers-rarely-die-of-alzheimers-how-complex-mental-maps-and-spatial-reasoning-protect-your-brain-286650) ⭐️ 7.0/10

最近一项研究表明，与普通人群相比，严重依赖空间推理的出租车司机阿尔茨海默病死亡率较低。该研究结果发表在《The Conversation》上，并在 Hacker News 上引发了讨论。 这一发现可能对公共卫生和认知健康策略产生影响，表明从事空间推理任务可能有助于预防阿尔茨海默病。它也强调了职业因素在神经退行性疾病研究中的重要性。 该研究使用逻辑回归调整了死亡年龄、性别、种族、民族和教育程度。然而，批评者指出，出租车司机的平均预期寿命（67.8 岁）低于普通人群（74 岁），这可能会混淆结果，因为阿尔茨海默病通常在 79 岁左右被诊断。

hackernews · jader201 · 8月9日 15:21 · [社区讨论](https://news.ycombinator.com/item?id=49232253)

**背景**: 阿尔茨海默病是一种进行性神经退行性疾病，影响记忆和认知功能。空间推理涉及理解和记忆空间中物体之间关系的能力，对导航至关重要。此前的研究，如 2000 年一项关于伦敦出租车司机的里程碑式研究，表明出租车司机的海马体（参与空间记忆的大脑区域）更大。然而，像这样的观察性研究容易受到选择偏差和混杂因素的影响，这可能会影响结论的有效性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://theconversation.com/taxi-drivers-rarely-die-of-alzheimers-how-complex-mental-maps-and-spatial-reasoning-protect-your-brain-286650">Taxi drivers rarely die of Alzheimer’s – how complex mental maps and spatial reasoning protect your brain</a></li>
<li><a href="https://en.wikipedia.org/wiki/Selection_bias">Selection bias - Wikipedia</a></li>
<li><a href="https://catalogofbias.org/biases/selection-bias/">Selection bias | Catalog of Bias</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论提出了几个关键点。一位评论者指出，出租车司机的平均预期寿命较低，这可能意味着他们活不到足以患上阿尔茨海默病的年龄。另一位则提出反向因果关系：空间能力较好的人可能更有可能成为出租车司机，而不是驾驶本身提供了保护。此外，关于教育程度的调整也存在争议，因为这可能掩盖教育对阿尔茨海默病风险的影响。

**标签**: `#neuroscience`, `#alzheimers`, `#spatial reasoning`, `#public health`, `#research`

---

<a id="item-7"></a>
## [W3C 的“酷 URI 不会改变”在链接腐烂时代依然引起共鸣](https://www.w3.org/Provider/Style/URI) ⭐️ 7.0/10

蒂姆·伯纳斯-李 1998 年的 W3C 文章《酷 URI 不会改变》在 Hacker News 上重新出现，引发了关于 URL 永久性和链接腐烂的新讨论。讨论中提到了现代 URL 失效的例子，包括 NSF 的 404 错误、RSS 订阅源和微软支持链接的问题。 这篇经典文章至今仍具有高度相关性，因为链接腐烂持续困扰着网络，影响可访问性、SEO 和引用的完整性。讨论强调，尽管有重定向等技术进步，但稳定 URL 的核心原则仍常被忽视，给用户和内容创作者带来重大影响。 文章认为，酷 URI 永远不应改变，因为改变它们会破坏链接并削弱网络的基础。社区评论指出，即使是大型公司和新闻网站也经常破坏 URL，虽然 301 重定向和 CMS 功能缓解了问题，但并非完全解决。

hackernews · Klaster_1 · 8月9日 14:32 · [社区讨论](https://news.ycombinator.com/item?id=49231809)

**背景**: URL（统一资源定位符）是网络资源的地址，其稳定性对网络的可靠性至关重要。链接腐烂是指由于网站重组、域名过期或内容删除而导致 URL 随时间失效的现象。W3C 的这篇文章由蒂姆·伯纳斯-李撰写，是倡导永久、精心设计的 URL 以防止此类问题的基础性文章。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/URL_redirection">URL redirection</a></li>
<li><a href="https://en.wikipedia.org/wiki/Link_rot">Link rot - Wikipedia</a></li>
<li><a href="https://www.w3.org/Provider/Style/URI">Hypertext Style: Cool URIs don't change.</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论反映了赞同与沮丧的混合情绪。用户分享了来自大公司和新闻网站的 URL 失效的个人经历，一位用户指出 SEO 使重定向更加普遍，但永久 URL 的理想仍未完全实现。另一位用户将“永久网络”的理想与当今短暂内容的“垃圾网络”进行了对比。

**标签**: `#URL design`, `#web standards`, `#link rot`, `#SEO`, `#web architecture`

---

<a id="item-8"></a>
## [AI 可穿戴设备与监控军备竞赛](https://www.theatlantic.com/technology/2026/05/ai-wearable-surveillance-countermeasures/687203/) ⭐️ 7.0/10

《大西洋月刊》发表文章，讨论 AI 驱动的可穿戴设备如何实现无处不在的个人记录，并探讨了人们可以采取的各种反制措施。文章强调了监控技术与隐私防御之间持续的“猫鼠游戏”。 这篇文章之所以重要，是因为它指出了监控资本主义日益增长的威胁，即企业通过 AI 可穿戴设备收集和商品化个人数据。它引发了关于隐私、企业权力以及加强监管和个人反制措施必要性的重要讨论。 文章指出，由于语音处理技术的大量投资，AI 可穿戴设备可能始终在反制措施上占据优势。文章还提到缺乏全面的隐私法规，以及第四修正案判例在应对数字全景监狱方面的不足。

hackernews · ike_usawa · 8月9日 11:30 · [社区讨论](https://news.ycombinator.com/item?id=49230477)

**背景**: 监控资本主义是一个概念，描述企业广泛收集和商品化个人数据，与政府监控不同。AI 可穿戴设备，如智能眼镜和录音设备，可以持续记录音频和视频，将数据输入 AI 系统进行分析和行为预测。这引发了重大隐私问题，因为个人在未经同意的情况下被记录，而干扰设备或反监控服装等反制措施正在开发中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theatlantic.com/technology/2026/05/ai-wearable-surveillance-countermeasures/687203/">A Surveillance ‘Cat-and-Mouse’ Game With AI - The Atlantic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Surveillance_capitalism">Surveillance capitalism - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/posts/jesse-y-27a04527a_ai-enabled-wearables-are-a-growing-threat-activity-7424180745579040768-wRKz">AI Wearables Pose Surveillance Threat in Unregulated... | LinkedIn</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了沮丧和无奈的情绪。一些用户呼吁将企业与国家分离，而另一些则指出人们自愿使用具有监控功能的产品。还有人建议 EFF 等组织发起公众宣传活动，将企业描绘成跟踪狂。

**标签**: `#surveillance`, `#AI wearables`, `#privacy`, `#surveillance capitalism`, `#society`

---

<a id="item-9"></a>
## [GitHub Models 退役，破坏 Actions 工作流](https://simonwillison.net/2026/Aug/9/github-models-is-now-retired/#atom-everything) ⭐️ 7.0/10

GitHub Models，一个用于 GitHub Actions 的统一 LLM API，已于 2026 年 7 月 30 日正式退役。Simon Willison 在他的 GitHub Actions 工作流因“计划退役停电”错误而失败时发现了这一变化，随后他改用带有 GPT-5.6 Luna 的 OpenAI API 密钥。 此次退役移除了开发者在 GitHub Actions 中直接使用内置 GitHub API 密钥运行 LLM 提示的便捷方式，影响了许多基于 AI 的自动化工作流。这凸显了提供免费或补贴 LLM 令牌的财务挑战，尤其是在编码代理增加令牌消耗的情况下。 GitHub 没有公开解释关闭原因，但 Simon Willison 推测是由于编码代理模式导致免费令牌成本过高。他用带有月度支出限制的 OpenAI API 密钥替换了 GitHub Models，他的工作流现在使用 GPT-5.6 Luna 为他的研究仓库生成文件夹摘要。

rss · Simon Willison · 8月9日 22:48

**背景**: GitHub Models 是一项服务，提供模型游乐场和跨多个 LLM 提供商的统一 API，允许 GitHub Actions 中的代码使用现有的 GitHub API 密钥进行身份验证。这使得构建“持续 AI”工作流变得容易，即将 AI 任务集成到开发管道中。此次退役遵循了 AI 提供商因成本上升而重新评估免费访问的趋势。

**标签**: `#GitHub`, `#LLM`, `#API`, `#retirement`, `#developer tools`

---

<a id="item-10"></a>
## [SQLite 文本修订历史压缩原型显示出潜力](https://simonwillison.net/2026/Aug/9/sqlite-text-history-prototype/#atom-everything) ⭐️ 7.0/10

Simon Willison 通过使用 zlib 或 zstd 压缩先前版本的完整 JSON 数组，在 SQLite 中存储文本修订历史进行了原型设计。在一次包含 1000 次模拟修订的测试中，20.4 MB 的原始文本使用 Zstandard 压缩后仅为 80.3 KB。 这种方法可以显著减少跟踪文档修订的应用程序的存储开销，使得在 SQLite 等轻量级数据库中存储大量历史记录变得可行。它为更复杂的修订存储方案提供了一种简单的替代方案，可能使构建内容管理或协作编辑工具的开发者受益。 为了避免每次编辑时解压和重新压缩整个数组，原型将历史记录拆分为多行，每行最多包含 128 次修订或 3 MB 未压缩的 JSON。该方案使用两列：一列存储压缩的 JSON 文本数组，另一列存储 Unix 时间戳的 JSON 数组。

rss · Simon Willison · 8月9日 22:05

**背景**: SQLite 是一种广泛使用的嵌入式关系数据库，将数据存储在单个文件中。修订历史存储通常涉及将每个版本存储为单独的行，这对于大型文档可能效率低下。像 zlib（使用 DEFLATE）和 zstd（Zstandard）这样的压缩算法通过消除冗余来减小数据大小，其中 zstd 提供更好的压缩比和更快的解压速度。该原型利用这些算法对包含所有先前版本的 JSON 数组进行压缩，以实现高压缩率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.zlib.net/">zlib Home Site</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zstd">zstd - Wikipedia</a></li>
<li><a href="https://www.sqlite.org/datatype3.html">Datatypes In SQLite</a></li>

</ul>
</details>

**标签**: `#SQLite`, `#compression`, `#revision history`, `#prototype`, `#databases`

---

<a id="item-11"></a>
## [模拟 AI 精度在噪声阈值处骤降，而非平滑退化](https://www.reddit.com/r/MachineLearning/comments/1vjmw53/noiseaware_training_for_analog_hardware_accuracy/) ⭐️ 7.0/10

Reddit 用户 Georgiou1226 的实验表明，在模拟硬件噪声下，神经网络精度在阈值处突然下降（83%、64%，然后随机），而非平滑退化，并且噪声感知训练显著移动了该阈值（在匹配噪声下为 61%对 39%）。 这一发现挑战了噪声导致精度按比例损失的常见假设，对模拟存内计算作为数字硬件节能替代方案的可行性至关重要。理解阈值行为可指导噪声鲁棒训练方法和硬件规格的设计。 实验包括正常训练网络，然后在增加的权重噪声下评估，显示出急剧下降。噪声感知训练（在训练期间注入噪声）移动了阈值，推测是通过找到更平坦的最小值。作者质疑平坦最小值是否是正确解释，并呼吁针对硬件噪声分布的显式锐度惩罚。

reddit · r/MachineLearning · /u/Georgiou1226 · 8月9日 10:55

**背景**: 模拟存内计算将权重存储在模拟单元中，避免了在存储器和计算之间移动数据的能耗，但受到固有噪声的影响。与数字不同，模拟噪声无法通过刷新消除。神经网络损失景观中的平坦最小值与更好的泛化性和对扰动的鲁棒性相关，这就是噪声感知训练可能有所帮助的原因。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://neuralnetworklexicon.wordpress.com/comparisons-and-tradeoffs/sharp-vs-flat-minima/">Sharp vs Flat Minima – Neural Network Lexicon</a></li>
<li><a href="https://arxiv.org/html/2411.11022v3">ASiM: Modeling and Analyzing Inference Accuracy of SRAM-Based ...</a></li>
<li><a href="https://ieeexplore.ieee.org/document/11152313">ASiM: Modeling and Analyzing Inference Accuracy of SRAM-Based ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论可能集中在平坦最小值是否能完全解释阈值移动，一些评论者提出正则化或损失景观几何等替代机制。其他人可能讨论对模拟硬件设计的实际影响以及显式鲁棒性优化的必要性。

**标签**: `#analog computing`, `#noise robustness`, `#machine learning`, `#hardware`, `#training`

---

<a id="item-12"></a>
## [约翰·C·莉莉 1978 年关于固态智能与人类消亡的论文](https://kibotronics.net/unlisted/lilly-machines/) ⭐️ 6.0/10

一篇重新发现的约翰·C·莉莉 1978 年的文章推测了固态智能（SSI）的兴起以及人类可能被消灭的可能性，在 Hacker News 上引发了新的讨论。 这篇文章提供了关于 AI 推测的历史视角，将早期的远见想法与当前关于 AI 对齐和存在风险的辩论联系起来。它突显了超级智能机器和人类过时等概念在推测性思想中有着深厚的根源。 莉莉的“固态实体”（SSE）概念描述了一种网络化的计算机智能，它寻求自我复制，可能将人类视为障碍。该文章的标题呼应了 C.S.刘易斯的《人的废除》，暗示了一种哲学传承。

hackernews · Kiboneu · 8月9日 13:47 · [社区讨论](https://news.ycombinator.com/item?id=49231397)

**背景**: 约翰·C·莉莉是一位医生、精神分析学家和迷幻剂探索者，以在感官剥夺、海豚交流和迷幻剂方面的研究而闻名。他后期的著作探讨了意识以及非人类智能的可能性，包括“固态实体”——一种假设的 AI，可能超越并最终取代人类。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/John_C._Lilly">John C. Lilly - Wikipedia</a></li>
<li><a href="https://seankerrigan.com/john-c-lilly-and-the-solid-state-entity/">John C. Lilly and the Solid State Entity - S.J. Kerrigan</a></li>
<li><a href="https://www.tetragrammaton.com/article/yearofthehorse-e5lll-cct5y-mmac7-3lrpx-hrwzr-abpme-e2x8b-n37k8-4jx86-m9ly8">John C. Lilly: Solid-State Intelligence Rebel – Tetragrammaton</a></li>

</ul>
</details>

**社区讨论**: 评论者参与了文章的推测性主题，将其与现代 AI 和数据中心相提并论，并引用了 C.S.刘易斯的《人的废除》。一些人指出缩写“SSI”是伊利亚·苏茨克弗公司的严峻前兆，而其他人则思考与 AI 的共生或改造其他行星的伦理问题。

**标签**: `#AI`, `#philosophy`, `#history`, `#speculation`, `#John C. Lilly`

---

<a id="item-13"></a>
## [Windows 11 天气应用占用超过 1 GB 内存](https://www.notebookcheck.net/Windows-11-s-built-in-Weather-app-wastes-more-than-1-GB-of-RAM.1364205.0.html) ⭐️ 6.0/10

最近的一份报告显示，Windows 11 自带的天气应用因其 WebView2 框架运行多个 Chromium 子进程，内存占用可超过 1 GB。相比之下，macOS 上苹果的原生天气应用在类似条件下内存占用约为其五分之一。 这种低效现象凸显了 Windows 11 中基于 Web 的应用导致系统臃肿的普遍趋势，可能会使内存为 8-16 GB 的入门级系统变慢。这也引发了社区关于性能优化以及需要更多原生、轻量级应用的讨论。 高内存占用归因于 WebView2 框架，它会产生多个 Chromium 子进程，如“渲染器”和“GPU 进程”。文章指出，准确测量内存使用量很复杂，因为某些内存可能在进程间共享，而任务管理器并不总能明确这一点。

hackernews · akyuu · 8月9日 15:11 · [社区讨论](https://news.ycombinator.com/item?id=49232138)

**背景**: Windows 11 包含多个本质上是 Web 包装器的内置应用，它们使用基于 Chromium 的 WebView2 运行时。这种方法便于跨平台开发和频繁更新，但相比原生应用会占用更多内存。用户对臃肿软件和系统性能的担忧日益增加，因此像 Win11Debloat 这样的精简工具越来越受欢迎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://giznewsdaily.com/article/windows-11-weather-app-uses-over-1-gb-of-ram">Windows 11 Weather App Uses Over 1 GB of RAM — giznewsdaily</a></li>
<li><a href="https://pcmasterinsider.com/windows-11-weather-app-high-ram-ads/">Windows 11 Weather App Sparks Backlash Over Excessive Memory ...</a></li>
<li><a href="https://www.notebookcheck.net/Windows-11-s-built-in-Weather-app-wastes-more-than-1-GB-of-RAM.1364205.0.html">Windows 11's built-in Weather app wastes more than 1 GB of RAM</a></li>

</ul>
</details>

**社区讨论**: 社区评论既有怀旧情绪，也有实用建议。一位用户回忆起 2006 年只有 1 GB 内存的电脑能同时运行多个应用，凸显了内存使用的变化。另一位用户建议使用 Edge 和 uBlock Origin 的变通方法，将内存占用降至约 130 MB。还有关于准确测量内存使用量的难度以及高占用是否合理的讨论。

**标签**: `#Windows 11`, `#RAM usage`, `#performance`, `#bloatware`, `#web apps`

---

<a id="item-14"></a>
## [Reddit 帖子称赞文章终于讲清了位置编码](https://www.reddit.com/r/MachineLearning/comments/1vju3ym/i_never_understood_positional_encoding_until_i/) ⭐️ 6.0/10

一位 Reddit 用户分享了一篇文章，该文章以一种终于让人理解的方式解释了位置编码，正如帖子标题所示。该帖子得分为 6.0/10，表明参与度中等。 位置编码是 Transformer 模型中的基本概念，清晰的解释可以帮助学习者和从业者更好地理解这些模型如何处理序列数据。这个帖子凸显了机器学习领域对易于理解的教育资源的持续需求。 该帖子不包含文章内容或评论，因此无法获得文章的具体细节。标题表明它提供了直观的解释，可能涵盖正弦编码或学习嵌入等概念。

reddit · r/MachineLearning · /u/ImaginaryRea1ity · 8月9日 16:22

**背景**: 位置编码是 Transformer 模型中使用的一种技术，用于向序列中标记的位置注入信息，因为 Transformer 并行处理标记，缺乏固有的顺序感知。常见的方法包括正弦函数和学习嵌入，这有助于模型理解词序，用于翻译和文本生成等任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/positional-encoding">What is Positional Encoding ? | IBM</a></li>
<li><a href="https://machinelearningmastery.com/a-gentle-introduction-to-positional-encoding-in-transformer-models-part-1/">A Gentle Introduction to Positional Encoding in Transformer Models...</a></li>

</ul>
</details>

**标签**: `#positional encoding`, `#transformers`, `#machine learning`, `#tutorial`

---