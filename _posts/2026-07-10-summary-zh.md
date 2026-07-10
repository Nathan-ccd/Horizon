---
layout: default
title: "Horizon Summary: 2026-07-10 (ZH)"
date: 2026-07-10
lang: zh
---

> 从 20 条内容中筛选出 11 条重要资讯。

---

1. [欧盟议会通过程序漏洞批准聊天控制 1.0](#item-1) ⭐️ 9.0/10
2. [OpenAI 发布 GPT-5.6，提供三种模型尺寸](#item-2) ⭐️ 9.0/10
3. [Mitchell Hashimoto 谈 Ghostty 与 Zig 和 Rust 的选择](#item-3) ⭐️ 8.0/10
4. [用 Rust 重写的 Postgres 通过全部回归测试](#item-4) ⭐️ 8.0/10
5. [Meta 发布 Muse Spark 1.1 智能体 AI 模型](#item-5) ⭐️ 8.0/10
6. [IMGNet：基于符号模式而非余弦相似度的人脸验证](#item-6) ⭐️ 8.0/10
7. [在 32GB 笔记本电脑上运行 GLM 5.2：int4 量化实现](#item-7) ⭐️ 7.0/10
8. [腾讯 Hy3：紧凑型 AI 模型挑战 DeepSeek Flash V4](#item-8) ⭐️ 7.0/10
9. [2026 年底不增加闰秒](#item-9) ⭐️ 7.0/10
10. [陆军“玻璃”后勤将在下一场战争中崩溃](#item-10) ⭐️ 7.0/10
11. [Talos-XII：手工编写的 Rust 机器学习栈用于抽卡概率建模](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [欧盟议会通过程序漏洞批准聊天控制 1.0](https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/) ⭐️ 9.0/10

2026 年 7 月 9 日，欧洲议会通过了聊天控制 1.0，允许对 Instagram、Discord 和 Gmail 等平台上的私人消息进行大规模扫描，尽管投票的欧洲议会议员多数反对（314 票反对，276 票赞成，17 票弃权）。否决动议因需要绝对多数 361 票而未获通过。 这一决定标志着欧盟数字隐私权的重大倒退，因为它允许无证大规模监控私人通信，削弱了加密和基本权利。它以儿童安全为名，开创了削弱隐私保护的先例，影响欧洲数百万用户。 该法规适用于非加密服务，如 Gmail、Instagram 私信、Discord、Snapchat 和 Xbox，而 WhatsApp、Signal 和 Telegram 等加密服务被排除在外。该法律有效期至 2028 年，投票在暑假前的最后一天进行，有 113 名欧洲议会议员缺席。

hackernews · rapnie · 7月9日 11:03 · [社区讨论](https://news.ycombinator.com/item?id=48843923)

**背景**: 聊天控制，正式名称为《儿童性虐待法规》（CSAR），由欧盟委员会于 2022 年 5 月提出，旨在打击在线儿童性虐待。该法规因其大规模扫描条款而备受争议，批评者认为这侵犯了隐私和加密。议会曾在 2026 年 3 月两次否决类似措施，但程序规则使其此次得以通过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://www.techtimes.com/articles/320010/20260709/eu-parliament-passes-chat-control-default-314-meps-couldnt-block-scanning-law.htm">EU Parliament Passes Chat Control by Default: 314 MEPs Couldn ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一不民主的程序表示愤怒，指出投票安排在暑假前以确保低出席率，而绝对多数要求使否决几乎不可能。一些人强调，这可能会削弱对欧盟机构的信任，并加速将欧盟视为极权实体的看法。

**标签**: `#privacy`, `#surveillance`, `#EU regulation`, `#digital rights`, `#encryption`

---

<a id="item-2"></a>
## [OpenAI 发布 GPT-5.6，提供三种模型尺寸](https://openai.com/index/gpt-5-6/) ⭐️ 9.0/10

OpenAI 发布了 GPT-5.6，这是一款前沿模型，提供 Luna、Terra 和 Sol 三种尺寸。其中最大的 Sol 变体在 ARC-AGI-3 基准测试中取得了 7.8% 的新最高分，成为首个在 ARC-AGI-3 游戏中获胜的经过验证的前沿模型。 GPT-5.6 在推理、token 效率和意图理解方面表现出显著改进，可能降低开发者的 API 成本和延迟。它在旨在衡量类人智能的 ARC-AGI-3 基准测试中取得成功，标志着向更强大、更高效的 AI 智能体迈出了重要一步。 每百万 token 的定价为：Luna 输入/输出 $1/$6，Terra $2.50/$15，Sol $5/$30。开发者指南强调了改进的意图理解能力，使模型无需明确的逐步指令即可推断用户目标，并保留了原始图像尺寸。

hackernews · logickkk1 · 7月9日 17:04 · [社区讨论](https://news.ycombinator.com/item?id=48849066)

**背景**: ARC-AGI-3 是一个交互式推理基准测试，挑战 AI 智能体探索新环境、推断目标并规划行动。Token 效率指最大化每个 token 携带的信息量，以降低成本和延迟。前沿模型是最先进的通用 AI 模型，训练成本通常高达数亿美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC-AGI-3</a></li>
<li><a href="https://arxiv.org/abs/2603.24621">[2603.24621] ARC-AGI-3: A New Challenge for Frontier Agentic Intelligence</a></li>
<li><a href="https://redis.io/blog/llm-token-optimization-speed-up-apps/">LLM Token Optimization: Cut Costs & Latency in 2026</a></li>

</ul>
</details>

**社区讨论**: 社区评论总体正面，用户称赞对 token 效率的关注以及新的 ARC-AGI-3 结果。一些用户讨论了使用该模型的实用技巧，而另一些用户则将其与 Claude Code 等替代方案进行比较，指出在不同模型之间切换的挑战。

**标签**: `#AI`, `#OpenAI`, `#GPT-5.6`, `#benchmarks`, `#large language models`

---

<a id="item-3"></a>
## [Mitchell Hashimoto 谈 Ghostty 与 Zig 和 Rust 的选择](https://alexalejandre.com/programming/interview-with-mitchell-hashimoto/) ⭐️ 8.0/10

Ghostty 的创建者 Mitchell Hashimoto 在一次采访中解释了他为何选择 Zig 而非 Rust 来开发终端模拟器，理由涉及 Rust 的文化和实际权衡。 这次采访凸显了 Zig 与 Rust 在系统编程领域的持续争论，表明语言选择不仅涉及技术优势，还涉及社区文化和项目特定的实用主义。 Ghostty 是一个快速、功能丰富、跨平台的终端模拟器，使用 GPU 加速和原生 UI。Hashimoto 的决定基于 Rust 的文化和实际工程考量，而不仅仅是技术特性。

hackernews · veqq · 7月9日 17:17 · [社区讨论](https://news.ycombinator.com/item?id=48849292)

**背景**: Ghostty 是一个使用平台原生 UI 和 GPU 加速以提升性能的终端模拟器。Zig 和 Rust 都是现代系统编程语言：Rust 强调无垃圾回收的内存安全，而 Zig 注重简洁性和与 C 的互操作性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ghostty.org/">Ghostty</a></li>
<li><a href="https://github.com/ghostty-org/ghostty">GitHub - ghostty-org/ghostty: 👻 Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleration.</a></li>
<li><a href="https://blog.logrocket.com/comparing-rust-vs-zig-performance-safety-more/">Comparing Rust vs. Zig: Performance, safety, and more</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些人欣赏 Hashimoto 的务实推理，而另一些人则批评他对 Rust 文化的言论显得狭隘。关于 Bun 从 Zig 重写为 Rust 的相关讨论进一步补充了语言权衡的背景。

**标签**: `#Zig`, `#Ghostty`, `#Rust`, `#Programming Languages`, `#Software Engineering`

---

<a id="item-4"></a>
## [用 Rust 重写的 Postgres 通过全部回归测试](https://github.com/malisper/pgrust) ⭐️ 8.0/10

一个名为 pgrust 的项目用 Rust 重写了 PostgreSQL 数据库，现已通过 100%的官方 Postgres 回归测试，其中大量代码由 LLM 生成。 这证明了用 Rust 这种内存安全语言重写大型成熟数据库系统的可行性，有望提升安全性和性能，同时也展示了 LLM 在复杂系统中生成代码的能力。 该项目在不到一个月内生成了 7101 次提交，使得传统代码审查变得不切实际。许可证从 PostgreSQL 许可证改为 AGPL，引发了兼容性问题。

hackernews · SweetSoftPillow · 7月9日 06:18 · [社区讨论](https://news.ycombinator.com/item?id=48841676)

**背景**: PostgreSQL 是一个有 30 年历史的开源关系型数据库，拥有全面的回归测试套件。Rust 是一种以内存安全著称的系统编程语言，无需垃圾回收。LLM（大语言模型）是能够根据提示生成代码的 AI 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.postgresql.org/docs/current/regress.html">PostgreSQL: Documentation: 18: Chapter 31. Regression Tests</a></li>

</ul>
</details>

**社区讨论**: 社区讨论中，有人担心大量 LLM 生成的提交使得代码审查不可行，也有人质疑原始 PostgreSQL 许可证与 AGPL 之间的兼容性。还有人建议通过镜像查询在生产环境中比较行为。

**标签**: `#Postgres`, `#Rust`, `#LLM`, `#database`, `#rewrite`

---

<a id="item-5"></a>
## [Meta 发布 Muse Spark 1.1 智能体 AI 模型](https://ai.meta.com/blog/introducing-muse-spark-meta-model-api/) ⭐️ 8.0/10

Meta 于 2026 年 7 月 9 日发布了 Muse Spark 1.1，这是一个专有的智能体 AI 模型，拥有 100 万 token 的上下文窗口，通过付费 API 提供，价格为每 100 万 token 1.25/4.5 美元。 这标志着 Meta 进入商业 AI 模型市场，直接与 OpenAI 和 Anthropic 竞争，如果 Meta 继续发布开放权重模型，可能会使编程模型商品化。 该模型是闭权重的，与 Meta 开放的 Llama 系列不同，并在 Terminal-Bench 2.1 上进行了评估，但社区成员指出评估使用了超出允许范围的资源限制，可能使结果无效。

hackernews · ot · 7月9日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48846184)

**背景**: 智能体 AI 模型旨在自主执行多步骤任务、使用工具并与环境交互。Meta 之前发布了 Muse Spark 作为研究模型，而 Muse Spark 1.1 是其首个商业版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ai.meta.com/blog/introducing-muse-spark-msl/">Introducing Muse Spark: Scaling Towards Personal ...</a></li>
<li><a href="https://www.datacamp.com/blog/muse-spark-1-1">Muse Spark 1.1: Meta's Agentic Model and API | DataCamp</a></li>
<li><a href="https://techcrunch.com/2026/07/09/meta-enters-the-crowded-ai-coding-battle-with-muse-spark-1-1/">Meta enters the crowded AI coding battle with Muse Spark 1 ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论关注基准测试的有效性（Terminal-Bench 资源覆盖）、实际集成（simonw 的 LLM 插件）以及定价（每 100 万 token 1.25/4.5 美元）。一些用户认为 Meta 的策略是使编程模型商品化，而另一些用户则质疑评估方法。

**标签**: `#AI`, `#Meta`, `#agentic model`, `#benchmarking`, `#open source`

---

<a id="item-6"></a>
## [IMGNet：基于符号模式而非余弦相似度的人脸验证](https://www.reddit.com/r/MachineLearning/comments/1urxvxh/i_built_imgnet_a_face_verification_model_that/) ⭐️ 8.0/10

一种名为 IMGNet 的新型人脸验证模型用滑动窗口符号模式匹配替代余弦相似度，在 LFW 上达到 96.27%的准确率，模型大小仅 10.58 MB，基于 CASIA-WebFace 训练。 这项工作挑战了人脸验证中默认使用余弦相似度的做法，提出了协同设计的度量与损失函数，有望在不牺牲准确率的前提下实现更小、更高效的模型。 该模型引入了 SW Block，在素数窗口大小{3,5,7}上计算逐像素差异，以及完全基于符号模式一致性的 IMG Sign MSE Loss。当直接应用于 ArcFace 嵌入（无需重新训练）时，IMG Sign Score 在 LFW 上达到 99.58%，仅比 ArcFace+Cosine 低 0.24%。

reddit · r/MachineLearning · /u/img-_- · 7月9日 18:00

**背景**: 人脸验证通常使用余弦相似度比较嵌入向量。IMGNet 则使用滑动窗口比较嵌入元素的符号模式，其动机是身份通过关系结构而非绝对值得以保留。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/serengil/deepface">GitHub - serengil/deepface: A Lightweight Face Recognition and Facial Attribute Analysis (Age, Gender, Emotion and Race) Library for Python · GitHub</a></li>

</ul>
</details>

**标签**: `#face verification`, `#machine learning`, `#computer vision`, `#representation learning`, `#independent research`

---

<a id="item-7"></a>
## [在 32GB 笔记本电脑上运行 GLM 5.2：int4 量化实现](https://github.com/JustVugg/colibri) ⭐️ 7.0/10

一位开发者创建了 Colibrì，这是一个轻量级的 C 语言推理引擎，通过 int4 量化和按需从磁盘流式加载专家模块，在 12 核、25GB RAM 的笔记本电脑上运行了 744B 参数的 GLM 5.2 混合专家模型。 这表明像 GLM 5.2 这样可与 GPT 和 Claude 媲美的高质量 LLM 可以在没有 GPU 的消费级硬件上运行，大大降低了本地 AI 推理的门槛。 Colibrì将密集部分（约 17B 参数）以 int4 格式常驻内存（约 9.9 GB），并从磁盘（约 370 GB）按需流式加载 21,504 个路由专家，配合 LRU 缓存，在开发者的机器上实现了约 0.1 token/秒的速度。

hackernews · vforno · 7月9日 08:05 · [社区讨论](https://news.ycombinator.com/item?id=48842459)

**背景**: GLM 5.2 是一个 744B 参数的混合专家（MoE）模型，每个 token 仅激活约 40B 参数，虽然高效但仍需大量内存。int4 量化通过使用 4 位整数代替 32 位浮点数来减小模型大小，以精度换取更低的内存占用。多 token 预测（MTP）是一种同时预测多个未来 token 的技术，可提升推理速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://docs.z.ai/guides/llm/glm-5.2">GLM-5.2 - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://huggingface.co/docs/transformers/quantization/concept_guide">Quantization concepts · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 评论者对实际 token 速率表示关注，有人指出 0.05-0.1 tok/s 对于交互式使用太慢，但可用于隔夜批处理。另有人建议剥离非必要专家以降低内存需求，同时一位正在为 Apple Silicon 开发类似项目的开发者表示愿意合作。

**标签**: `#LLM`, `#quantization`, `#local inference`, `#GLM`, `#optimization`

---

<a id="item-8"></a>
## [腾讯 Hy3：紧凑型 AI 模型挑战 DeepSeek Flash V4](https://hy.tencent.com/research/hy3) ⭐️ 7.0/10

腾讯发布了 Hy3，这是一个 295B 参数的混合专家（MoE）模型，具有 21B 激活参数，目前在 OpenRouter 上免费提供至 7 月 21 日。它直接与 DeepSeek Flash V4 竞争，后者是一个 284B 参数的 MoE 模型，具有 13B 激活参数。 Hy3 的小尺寸和强大性能使其成为本地部署和成本效益推理的有力选择，可能改变可访问的高性能 AI 模型格局。其在 OpenRouter 上的免费层级降低了开发者实验和集成的门槛。 Hy3 总参数 295B，激活参数 21B，外加 3.8B 的 MTP 层参数；而 DeepSeek Flash V4 总参数 284B，激活参数 13B。Hy3 在 OpenRouter 上的有效输入价格现已与 DeepSeek 托管的 Flash V4 相同，且其在 OpenRouter 排名中已降至第 8/9 位。

hackernews · andai · 7月9日 15:27 · [社区讨论](https://news.ycombinator.com/item?id=48847552)

**背景**: 混合专家（MoE）模型每个 token 仅激活部分参数，从而在较低计算成本下实现高容量。OpenRouter 是一个统一的 API 平台，通过单一端点提供来自多个提供商的众多 AI 模型访问。DeepSeek Flash V4 是 DeepSeek 推出的效率优化的 MoE 模型，支持 100 万 token 的上下文窗口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reddit.com/r/LocalLLM/comments/1updg0o/tencent_hy3/">Tencent Hy3 : r/LocalLLM - Reddit</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash">deepseek-ai/DeepSeek-V4-Flash · Hugging Face</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**社区讨论**: 社区成员注意到 Hy3 在较小尺寸下具有惊人的能力，一些人将其与 DeepSeek Flash V4 进行有利比较。然而，其他人质疑其长期价值，因为其排名下降，并指出定价经济学现已与 DeepSeek 托管的 Flash V4 相似。人们对其在重度量化下的性能以及本地部署的可行性感到好奇。

**标签**: `#AI`, `#LLM`, `#Tencent`, `#OpenRouter`, `#model comparison`

---

<a id="item-9"></a>
## [2026 年底不增加闰秒](https://datacenter.iers.org/data/latestVersion/bulletinC.txt) ⭐️ 7.0/10

国际地球自转与参考系统服务（IERS）宣布，2026 年 12 月底不会增加闰秒，UTC-TAI 偏移量保持为-37 秒，UTC-GPS 偏移量保持为-18 秒。 这一决定维持了金融网络、电信和卫星导航等对时间敏感系统的稳定性，这些系统依赖于可预测的时间偏移。它也反映了国际社会正在推进到 2035 年废除闰秒的趋势。 上一次闰秒添加于 2016 年 12 月 31 日，此后未再插入闰秒。IERS 公告确认，UT1 与 UTC 的差值将保持在±0.9 秒以内，无需调整。

hackernews · ChrisArchitect · 7月9日 14:16 · [社区讨论](https://news.ycombinator.com/item?id=48846281)

**背景**: 闰秒是对协调世界时（UTC）偶尔进行的一秒调整，使其与平均太阳时（UT1）保持在 0.9 秒以内，而 UT1 因地球自转的不规则性而变化。原子时（TAI）是连续的，而 UTC 因闰秒而不连续。2022 年，国际计量大会决定在 2035 年或之前废除闰秒，此后 UTC 与 TAI 将保持固定偏移。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/International_Atomic_Time">International Atomic Time - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Leap_second">Leap second - Wikipedia</a></li>
<li><a href="https://www.nist.gov/pml/time-and-frequency-division/time-realization/leap-seconds">Leap second and UT1-UTC information | NIST GPS, UTC, and TAI Clocks - LeapSecond Transformations between Time Systems - Navipedia UTCTAIOffset (OREKIT 13.1.5 API) TAI Time Calculator - International Atomic Time Converter ...</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了地球自转的不可预测性，一位用户询问地质活动或天气等是否导致自转速度变化。另一位指出，UTC-TAI 偏移量不变意味着 UTC-GPS 偏移量也保持不变。还有一条幽默评论建议用喷气发动机来调整时间。

**标签**: `#leap second`, `#timekeeping`, `#UTC`, `#Earth rotation`, `#time standards`

---

<a id="item-10"></a>
## [陆军“玻璃”后勤将在下一场战争中崩溃](https://mwi.westpoint.edu/the-glass-backbone-why-the-armys-logistics-will-break-in-the-next-war/) ⭐️ 7.0/10

现代战争研究所的一篇文章指出，美国陆军建立在脆弱“玻璃”供应链上的后勤系统将在重大冲突中失败，并且关于后勤的历史教训正被忽视。 这一分析揭示了军事战略中的一个关键弱点，可能决定未来战争的胜负，影响国防规划和资源分配。 文章批评了“牙齿与尾巴比”的概念，并指出尽管军事院校经常讨论后勤，但预算请求或现代化优先事项中很少体现这一点。

hackernews · baud147258 · 7月9日 13:24 · [社区讨论](https://news.ycombinator.com/item?id=48845442)

**背景**: 军事后勤涉及部队调动和支援的规划与执行。“玻璃骨干”比喻指在和平时期高效但在压力下脆弱的供应链，如同玻璃一般。

**社区讨论**: 评论者普遍赞同文章论点，强调如费边战略等历史例证以及后勤比战术更重要。一些人讨论了 SpaceX 星舰等新技术对未来后勤的影响。

**标签**: `#logistics`, `#military strategy`, `#systems thinking`, `#supply chain`, `#defense`

---

<a id="item-11"></a>
## [Talos-XII：手工编写的 Rust 机器学习栈用于抽卡概率建模](https://www.reddit.com/r/MachineLearning/comments/1urvxgb/talosxii_handwritten_autograd_small_rlmlp_stack/) ⭐️ 6.0/10

Talos-XII 是一个命令行模拟器，使用手工编写的自动求导引擎、强化学习算法（Dueling DQN、PPO）和自定义注意力机制（MLA）来建模《明日方舟：终末地》中的抽卡概率，全部用 Rust 实现，不依赖任何外部机器学习框架。 该项目展示了完整的机器学习栈——包括自动求导、强化学习和类 Transformer 注意力——可以用 Rust 从头构建，为抽卡概率建模等小众应用提供了轻量级、可移植的替代方案，替代 PyTorch 等重型框架。 该栈包括自定义 SIMD 调度（AVX2、AVX-512、NEON）、Rayon 并行化模拟、BF16 推理缓存，以及一种新颖的 ACHF 组件，融合了密集路径和稀疏路径。作者希望获得 ARM、AVX-512 和 GPU 平台上的基准测试数据。

reddit · r/MachineLearning · /u/zay0kami · 7月9日 16:52

**背景**: 游戏中的抽卡系统使用概率表和保底机制来保证一定次数后的抽取。传统的静态表格无法回答诸如“我现在该抽还是攒着？”这样的条件性问题。强化学习和神经网络可以建模动态决策策略，但通常需要 PyTorch 等重型框架。Talos-XII 用 Rust（一种以性能和安全性著称的系统语言）从头实现了这些功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@sainijagjit/understanding-dueling-dqn-a-deep-dive-into-reinforcement-learning-575f6fe4328c">Understanding Dueling DQN: A Deep Dive into Reinforcement ...</a></li>
<li><a href="https://machinelearningmastery.com/a-gentle-introduction-to-multi-head-latent-attention-mla/">A Gentle Introduction to Multi-Head Latent Attention (MLA)</a></li>
<li><a href="https://arxiv.org/abs/2502.07864">TransMLA: Multi-Head Latent Attention Is All You Need Towards Economical Inference: Enabling DeepSeek’s Multi-Head ... MHA vs MQA vs GQA vs MLA - Medium Multi-Latent Attention Transformer - emergentmind.com Multi-head Latent Attention (MLA): Making Transformers More ...</a></li>

</ul>
</details>

**标签**: `#Rust`, `#reinforcement learning`, `#autograd`, `#gacha`, `#machine learning`

---