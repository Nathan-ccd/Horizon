---
layout: default
title: "Horizon Summary: 2026-10-05 (ZH)"
date: 2026-10-05
lang: zh
---

> 从 13 条内容中筛选出 9 条重要资讯。

---

1. [Strata 在 RTX 4090 上以 100+ tok/s 运行 125B Qwen 3.8 Flash Next](#item-1) ⭐️ 8.0/10
2. [ARC-AGI-3 Kaggle 分数 30 天内从 7%跃升至 56%](#item-2) ⭐️ 8.0/10
3. [GitHub 工具可从 macOS 27 移除 Apple Intelligence 以回收磁盘空间](#item-3) ⭐️ 7.0/10
4. [不当脱敏泄露谷歌数据中心用水与用电数据](#item-4) ⭐️ 7.0/10
5. [Show HN：为 macOS 上每张照片和每一帧视频提供 AI 语义搜索](#item-5) ⭐️ 7.0/10
6. [DynaBase：单参数架构实现动力系统零样本重建](#item-6) ⭐️ 7.0/10
7. [Nonobench：开源基准测试 49 个大模型解数织谜题](#item-7) ⭐️ 7.0/10
8. [425 张镜像服装数据集瞄准高光 CV 边缘案例](#item-8) ⭐️ 6.0/10
9. [交互式演示展示前缀注入越狱大语言模型](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Strata 在 RTX 4090 上以 100+ tok/s 运行 125B Qwen 3.8 Flash Next](https://github.com/Niko1221/Strata) ⭐️ 8.0/10

一位用户分享了通过 GitHub 项目 Strata 在单张消费级 RTX 4090 上以超过 100 tokens/秒运行 125B 参数 Qwen 3.8 Flash Next 模型的方法，另有用户在配备 128GB DDR5 和 Ryzen 7950X3D 的 4090 上报告了 124 tok/s 的速度。 在消费级硬件上以 100+ tok/s 运行 125B 模型是本地 LLM 推理的一个重要里程碑，可能让爱好者和小型团队无需租用数据中心 GPU 即可运行前沿规模的模型。 Qwen 3.8 Flash Next 总参数量为 125B，但每个 token 仅激活 6B，另有 51B n-gram 嵌入和 4B MTP；所报告的速度依赖激进的低比特量化，其质量权衡仍存在争议。

hackernews · snehesht · 10月4日 12:51 · [社区讨论](https://news.ycombinator.com/item?id=49953495)

**背景**: Qwen 3.8 Flash Next 是阿里巴巴 Qwen 团队推出的混合专家模型，每个 token 仅激活一小部分参数，因此运行成本低于其规模所暗示的水平。量化将模型权重压缩到较低精度（如 4-bit），以便将大模型装入有限的显存，但可能降低输出质量。Strata 是一个新的本地推理引擎，声称比 llama.cpp 有大幅加速，但独立基准测试仍在涌现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-Flash-Next">Qwen / Qwen 3 . 8 - Flash - Next · Hugging Face</a></li>
<li><a href="https://github.com/qwenlm/qwen3.8-flash-next">GitHub - QwenLM/ Qwen 3 . 8 - Flash - Next : Qwen 3 . 8 - Flash - Next is the...</a></li>
<li><a href="https://www.youtube.com/watch?v=m0VHx73SAG0">The New Way to Run 125 B Models 6× Faster Than... - YouTube</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：一些人报告了强劲结果（4090 上 124 tok/s，RTX 6000 Pro 上解码 255 tok/s），而另一些人则对低于 4-bit 的量化质量持怀疑态度，并指出在一项视觉基准测试中，相同权重下 Strata 的中位误差为 154.8 像素，而 llama.cpp 为 46.5；还有用户警告存在炒作和 Strata 链接刷屏。

**标签**: `#LLM inference`, `#quantization`, `#consumer hardware`, `#Qwen`, `#performance optimization`

---

<a id="item-2"></a>
## [ARC-AGI-3 Kaggle 分数 30 天内从 7%跃升至 56%](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arc%CE%B1gi3_scores_on_kaggle_just_went_from_7_to/) ⭐️ 8.0/10

在过去 30 天里，Kaggle ARC-AGI-3 竞赛排行榜的最高分从约 7%跃升至 56%，这些成绩由运行在特定框架（harness）中的小型本地模型取得。这意味着小型、可在本地运行的模型如今在一个专门为测试类人推理而设计的基准上，已经超过了普通人类的平均水平。 ARC-AGI-3 的设立初衷是展示人类在新颖推理任务上的优势，因此小型本地模型仅用一个月就超过普通人类水平，表明 AI 推理能力取得了出乎意料的快速进展。这可能改变研究人员和公众对 AGI 时间表以及基准评测价值的看法。 Kaggle 竞赛规则限制参赛者只能使用小型本地模型，因此 56%的成绩反映的是受限算力下的表现，而非前沿规模系统；发帖者也指出所附排行榜图略有过时。ARC-AGI-3 是一个交互式基准，智能体必须探索全新环境、即时获取目标并构建可适应的世界模型。

reddit · r/MachineLearning · /u/we_are_mammals · 10月4日 10:24 · [社区讨论](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arcαgi3_scores_on_kaggle_just_went_from_7_to/)

**背景**: ARC-AGI 是 ARC Prize 基金会推出的一系列基准，旨在衡量通用流体智能与推理能力，而非记忆性知识。最新版本 ARC-AGI-3 是交互式的：智能体必须探索陌生环境、即时推断目标并持续学习，因此比静态谜题类基准困难得多。相关的 Kaggle 竞赛设有奖金池，并要求解决方案在严格算力限制下运行，这正是成绩来自小型本地模型的原因。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC - AGI - 3</a></li>
<li><a href="https://benchlm.ai/benchmarks/arcAgi3">ARC - AGI - 3 Leaderboard & Scores — July 2026 | BenchLM.ai</a></li>
<li><a href="https://pasqualepillitteri.it/en/news/606/arc-agi-3-benchmark-ai-test">ARC - AGI - 3 : The Test No AI Can Pass (Humans 100%, AI 0.37%)</a></li>

</ul>
</details>

**标签**: `#ARC-AGI`, `#AI benchmarks`, `#reasoning`, `#Kaggle`, `#machine learning`

---

<a id="item-3"></a>
## [GitHub 工具可从 macOS 27 移除 Apple Intelligence 以回收磁盘空间](https://github.com/omlahore/RemoveMacAI) ⭐️ 7.0/10

一个名为 RemoveMacAI 的 GitHub 项目提供脚本，可从 macOS 27 中移除 Apple Intelligence 并回收其占用的磁盘空间。该工具在 Hacker News 上引发热议，获得 388 分和 247 条评论，讨论苹果的产品方向与用户控制权。 该工具凸显出用户日益不满：macOS 如今需要第三方脚本才能移除不想要的预装软件，这与长期以来 Windows 上的“去臃肿”文化如出一辙。它还引发了一个问题：苹果是否应像部分竞争对手那样，提供一个简单的开关来禁用 AI 功能。 据报道，在部分运行 macOS 27 的 Mac 上，Apple Intelligence 占用 30GB 甚至更多空间，因为 Golden Gate 会在安装后自动下载数 GB 的 AI 模型。该功能需要 Apple 芯片（M1 或更新），Intel 芯片的 Mac 无法使用。

hackernews · privacyisntdead · 10月4日 19:42 · [社区讨论](https://news.ycombinator.com/item?id=49957116)

**背景**: Apple Intelligence 是苹果集成到 macOS、iOS 等平台的一套 AI 功能，提供写作工具、摘要以及升级版 Siri。在 macOS 上，它仅支持 Apple 芯片的 Mac，从 macOS Sequoia 15.1 开始，并延续到 2026 年的 macOS Tahoe 和 macOS 27 Golden Gate 版本。由于端侧模型体积庞大，会占用大量存储空间，因此一些用户寻求将其移除的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence - Wikipedia</a></li>
<li><a href="https://9to5mac.com/2026/09/14/macos-27-golden-gate-now-available-here-is-everything-new/">macOS 27 Golden Gate now available, here is everything new - 9to5 Mac</a></li>
<li><a href="https://digg.com/tech/ddf23423-fc26-4aa6-98bc-21327b3b7840">Apple Intelligence reportedly takes up 30GB-plus on some Macs ...</a></li>

</ul>
</details>

**社区讨论**: 评论者将这一情况比作 Windows 上的 O&O ShutUp10 等去臃肿工具，批评 iOS 缺乏简单的 AI 开关，并争论在本地模型具备隐私优势的情况下将其移除是否明智。一些人认为真正的问题在于苹果默认 SSD 容量太小，而非 AI 本身。

**标签**: `#macOS`, `#Apple Intelligence`, `#privacy`, `#bloatware`, `#disk space`

---

<a id="item-4"></a>
## [不当脱敏泄露谷歌数据中心用水与用电数据](https://www.1011now.com/2026/09/30/more-questions-than-answers-about-lincolns-google-data-center-water-electricity-usage/) ⭐️ 7.0/10

内布拉斯加州林肯市的一篇报道披露了谷歌数据中心本应被脱敏处理的用水和用电数据，这些数字因文件脱敏不当而被公开。文章特别指出，林肯市的一座设施用水约 1300 万加仑，而该州另一座数据中心用水超过 5 亿加仑。 这一事件凸显出公众对 AI 基础设施环境足迹的审查日益严格，数据中心周边社区要求获得当地用水和能耗的透明度。同时它也表明，糟糕的文档脱敏做法可能意外泄露敏感企业信息，这对谷歌及其他面临类似披露争议的运营商都有影响。 披露的 1300 万加仑这一数字放在整体背景下其实相对较小，而文章聚焦于单一本地设施，可能低估了其他数据中心的用水规模，例如那座用水超过 5 亿加仑的数据中心。由于这些数字是通过脱敏失误而非主动披露曝光的，数据的准确性和完整性仍存疑。

hackernews · sensanaty · 10月4日 19:37 · [社区讨论](https://news.ycombinator.com/item?id=49957068)

**背景**: 数据中心需要大量水资源，主要用于冷却服务器，同时还需要电力来供电和散热；业界使用“水资源使用效率”（WUE）等指标，衡量每千瓦时 IT 能耗所消耗的水量（升）。脱敏是指在文件发布前移除或遮盖敏感内容的过程，如果操作不当——例如仅在文本上画黑框而未删除底层数据——机密信息仍可能被恢复。随着 AI 工作负载增长，数据中心的能耗和水耗已成为科技公司与所在社区之间争论的焦点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datacenterknowledge.com/cooling/data-center-water-use-from-efficiency-metrics-to-real-world-resilience">Data Center Water Use: From WUE to Real-World Resilience</a></li>
<li><a href="https://www.intralinks.com/guides/digital-redaction-fails-best-practices">Digital Redaction Tips to Avoid Critical Security Failures</a></li>
<li><a href="https://trendsgroup.org/insight/the-energy-demand-of-ai-and-server-hubs/">TRENDS Group - The Energy Demand of AI and Server Hubs</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者观点不一：一位前数据中心员工表示，当地关于用水和用电的指责往往被夸大；另一位则认为 1300 万加仑并非有实质影响的水量。还有人批评文章聚焦于一个相对较小的本地设施，并引发了更广泛的争论：用水和能耗是否是批评 AI 数据中心的正确指标，一些人认为真正的问题在于能源浪费或 AI 本身，而非其副作用。

**标签**: `#data-centers`, `#google`, `#water-usage`, `#energy-consumption`, `#ai-infrastructure`

---

<a id="item-5"></a>
## [Show HN：为 macOS 上每张照片和每一帧视频提供 AI 语义搜索](https://github.com/allenv0/SCM) ⭐️ 7.0/10

一位开发者发布了 SCM，这是一款开源 macOS 应用，利用 CLIP 风格的嵌入模型，为每一张照片和每一帧视频提供 AI 驱动的语义搜索，可将自然语言查询与视觉内容匹配。该项目在 Hacker News 上获得 141 分和 66 条评论，讨论集中在 OCR 框架选择、LLM 代码生成以及视频帧采样权衡上。 对个人媒体进行语义搜索是一个日益增长的应用场景，该项目展示了单个开发者如何结合 CLIP 嵌入与苹果原生框架，在 macOS 上构建实用的本地工具。它还凸显了更广泛的争论：LLM 生成的代码能否复制现有产品，以及版权如何适用于 AI 辅助开发。 该应用会索引每一帧视频，计算成本很高；一位评论者指出，在 M1 上对 1.2 万个视频按每秒一帧采样需要数天，而仅采样关键帧可缩短到一夜完成。评论者还建议在 macOS 上使用苹果的 Vision 框架而非 Tesseract 进行 OCR，因为其速度和准确率更优。

hackernews · allenleee · 10月4日 09:24 · [社区讨论](https://news.ycombinator.com/item?id=49952111)

**背景**: CLIP（对比语言-图像预训练）是 OpenAI 的模型，它学习图像和文本的共享嵌入空间，从而实现零样本语义搜索——例如用“有棕榈树的房子”这样的文本查询就能检索到匹配图像，无需针对特定任务训练。视频语义搜索通过提取帧并嵌入来扩展这一能力，但帧采样率是覆盖范围与计算成本之间的关键权衡。苹果的 Vision 框架提供针对 macOS 硬件优化的设备端 OCR 和图像分析 API。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ente.in/blog/image-search-with-clip-ggml/">Running OpenAI's CLIP with GGML on Ente's desktop apps</a></li>
<li><a href="https://developer.apple.com/documentation/vision">Vision | Apple Developer Documentation</a></li>
<li><a href="https://arxiv.org/html/2408.03340v1">An Empirical Comparison of Video Frame Sampling Methods</a></li>

</ul>
</details>

**社区讨论**: 评论者强烈建议在 macOS 上使用苹果的 Vision 框架而非 Tesseract 进行 OCR，指出其更快更准确；一位用户还发现，当要求多个 LLM 设计此类技术栈时，它们也都推荐 Vision。一个跑题的讨论质疑 LLM 生成的代码是否能规避版权，让大科技公司克隆小创业公司的创意；另一位评论者则指出 Immich 是跨平台的 AI 照片和视频搜索替代方案。一位在 M1 上构建过类似 CLIP 工具的开发者强调，帧采样率是决定性因素，仅采样关键帧远比逐秒采样实用。

**标签**: `#AI Search`, `#macOS`, `#Computer Vision`, `#CLIP`, `#Show HN`

---

<a id="item-6"></a>
## [DynaBase：单参数架构实现动力系统零样本重建](https://www.reddit.com/r/MachineLearning/comments/1wxex8n/a_minimal_interpretable_architecture_for_zeroshot/) ⭐️ 7.0/10

一篇 NeurIPS 2026 论文提出了 DynaBase，这是一种极简的可解释架构，由仅含单个参数 α 的分段仿射映射和一个从上下文信号中选取最接近当前状态数据点的上下文选择器组成。仅凭这两个机制，DynaBase 就能重现不动点（α<1）、极限环（α=1）和混沌吸引子（α>1），并在零样本模式下超越大多数时间序列和动力系统基础模型。 这项工作表明，大型动力系统基础模型的复杂行为或许可以归结为一个极其简单且数学上可处理的机制，从而为分析、改进和理解这类模型提供抓手。如果得到验证，它可能改变研究人员处理零样本时间序列预测和科学机器学习可解释性的方式。 训练成本极低：既可以通过对前向预测做线性回归一步解析完成，也可以直接针对动力系统重建目标进行单参数网格搜索，而不同的训练机制会带来有趣的性能差异。论文声称 DynaBase 能保持正确的动力学机制，不像上下文鹦鹉学舌（context parroting）等更简单的机制，不过该预印本尚未得到广泛验证。

reddit · r/MachineLearning · /u/DangerousFunny1371 · 10月4日 12:49

**背景**: 动力系统是描述天气模式、大脑活动或化学反应等量随时间演化的数学模型，它们可以表现出性质不同的行为，称为动力学机制，包括收敛到不动点、在极限环中振荡或呈现混沌。动力系统重建（DSR）旨在从观测数据中学习一个能重现这些长期统计和几何性质的模型，但传统方法需要为每个系统单独训练新模型。零样本重建受大语言模型上下文学习能力的启发，试图仅凭上下文推断新系统的动力学而无需额外训练；而分段仿射映射是在不同区域表现为线性的简单函数，因此对可解释建模很有吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2607.14937">A Minimal Interpretable Architecture for Zero - Shot Reconstruction of ...</a></li>
<li><a href="https://gist.science/paper/2607.14937">A Minimal Interpretable Architecture for Zero - Shot ... | Gist.Science</a></li>
<li><a href="https://papers.nips.cc/paper_files/paper/2025/hash/1419d8554191a65ea4f2d8e1057973e4-Abstract-Conference.html">True Zero - Shot Inference of Dynamical Systems Preserving...</a></li>

</ul>
</details>

**标签**: `#dynamical-systems`, `#machine-learning`, `#interpretability`, `#zero-shot-learning`, `#NeurIPS`

---

<a id="item-7"></a>
## [Nonobench：开源基准测试 49 个大模型解数织谜题](https://www.reddit.com/r/MachineLearning/comments/1wxa2bs/nonobench_an_open_benchmark_of_49_llms_on/) ⭐️ 7.0/10

Nonobench 是一个全新的开源基准测试，用数织（picross）谜题评估 49 个大语言模型：每个模型只拿到一次行与列的线索，必须在无工具、每题仅一次尝试的条件下返回完整网格。结果显示解题率从 5x5 的 85% 骤降到 10x10 的 46%、15x15 的 20%；GPT-6 Astra 解出全部 30 道标准题，而 Claude Opus 5.5 在 10 道 20x20 困难题中解出 8 道，另有 11 个模型一道都解不出。 该基准提供了一项不易被数据污染的逻辑推理任务，清晰揭示了随着网格规模和逻辑深度增加，大模型性能急剧下降的现象，为当前模型在多步约束推理上的能力边界提供了具体证据。对于需要持续演绎而非模式匹配的任务，这项结果对研究人员和选型实践者都有参考价值。 标准模式采用 Moyà-Alcover 的 Nonograms 数据集（CC BY 4.0）中 5x5 到 15x15 的 30 道题；困难模式使用十道随机 20x20 题，每道都验证过只有唯一解，其中五道无法仅靠行逻辑解出。测试通过 OpenRouter 运行了 130 个不同推理强度变体，并尽量固定到各实验室自己的端点；由于每题只尝试一次，单个结果存在噪声，因此给出了 95% 置信区间。

reddit · r/MachineLearning · /u/mauricekleine · 10月4日 07:57

**背景**: 数织是一种逻辑谜题，玩家根据每行每列的数字线索（表示连续填充格的长度和顺序）来填涂网格。行逻辑求解是最基础的技术，即单独分析每一行或每一列来推断格子；无法仅靠这种方法解出的谜题需要更深的演绎链条。OpenRouter 是一个统一 API，可规范化众多模型提供商的接口，该基准正是借助它来一致地运行大量模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nonogram.online/guides/nonogram-line-solving-method">The Line-Solving Method: A Core Nonogram Technique</a></li>
<li><a href="https://openrouter.ai/docs/api_reference/overview">OpenRouter API Reference - Complete Documentation</a></li>
<li><a href="https://www.puzzle-nonograms.com/">Nonograms - online puzzle game</a></li>

</ul>
</details>

**标签**: `#LLM evaluation`, `#benchmark`, `#reasoning`, `#nonograms`, `#open source`

---

<a id="item-8"></a>
## [425 张镜像服装数据集瞄准高光 CV 边缘案例](https://www.reddit.com/r/MachineLearning/comments/1wx7jg6/here_are_some_pictures_of_a_robot_costume_wearing/) ⭐️ 6.0/10

一个新发布的开放数据集包含 425 张 RAW 和 JPEG 图像，展示了一个穿着定制多面镜面服装的机器人服装，在强对比户外环境中拍摄，以刻意触发高光眩光和几何反射。该档案包含 100%专有的未压缩 Camera-Master RAW 文件、高分辨率 JPEG 以及块缓冲的 SHA-256 取证清单，用于完整性验证。 高光反射和镜面表面是计算机视觉中已知的难题，可能导致深度估计和分割失败，因此该数据集为针对极端眩光压力测试模型提供了有针对性的基准。它可以帮助构建空间 AI、深度相机和检测系统的研究人员和从业者识别并修复标准数据集中很少出现的故障模式。 该数据集规模适中，仅有 425 个资产，且 Reddit 帖子缺乏详细验证或讨论，这限制了其即时影响力。其价值在于刻意设计的对抗性拍摄设置——在高对比户外光线下穿着多面镜面服装——旨在导致边界框丢失和分割失败。

reddit · r/MachineLearning · /u/5500kelvin · 10月4日 05:21

**背景**: 高光反射发生在光线从光亮或镜面表面反弹时，会遮挡底层物体并迷惑那些假设表面为漫反射的视觉算法。深度估计算法从传感器数据或图像推断距离，但在反射表面上常常失败，因为反射的几何形状与物理表面不匹配。当检测器或分割模型因这类误导性视觉线索而丢失目标时，就会出现边界框丢失和分割失败。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://link.springer.com/article/10.1007/s10462-025-11233-7">A comprehensive survey of specularity detection: state-of-the ...</a></li>
<li><a href="https://arxiv.org/abs/2603.05152">[2603.05152] SSR-GS: Separating Specular Reflection in ... A comprehensive survey of specularity detection: state-of-the ... A comprehensive survey of specularity detection: state-of ... 5 Imaging – Foundations of Computer Vision A fast specular removal method for a single real image SSR-GS: Separating Specular Reflection in Gaussian Splatting ... Toward Specular Removal from Natural Images Based on ...</a></li>
<li><a href="https://fiveable.me/autonomous-vehicle-systems/unit-3/depth-estimation/study-guide/qSiUyDsiHPsyod2g">Depth estimation | Autonomous Vehicle Systems Class... | Fiveable</a></li>

</ul>
</details>

**标签**: `#computer-vision`, `#dataset`, `#depth-estimation`, `#specular-reflections`, `#benchmarking`

---

<a id="item-9"></a>
## [交互式演示展示前缀注入越狱大语言模型](https://www.reddit.com/r/MachineLearning/comments/1wxm5p3/interactive_demonstration_of_prefix_injection/) ⭐️ 6.0/10

Reddit 的 r/MachineLearning 版块上发布了一个交互式网页演示，展示用于越狱大语言模型的前缀注入攻击，作者提醒如果页面卡住可以刷新，因为有时加载较慢。 前缀注入是一种实用且低成本的越狱技术，无需梯度访问即可绕过安全对齐，因此公开的交互式演示能帮助研究人员和防御方实时理解和测试这些漏洞。 该演示是一个基于浏览器的工具，允许用户直接尝试前缀注入，但帖子本身除刷新和加载缓慢的提示外几乎没有技术细节；前缀注入的原理是在模型输出开头注入固定 token，从而引导其后续生成。

reddit · r/MachineLearning · /u/big_hole_energy · 10月4日 18:03

**背景**: 提示注入是一种网络安全攻击方式，通过精心构造的输入使大语言模型产生非预期行为。前缀注入是其中一种具体变体，它迫使模型以攻击者选定的文本开头作答，利用了大语言模型应用往往无法清晰区分开发者指令与用户输入这一弱点。越狱则指绕过模型的安全训练以诱导其输出受限内容，是 AI 安全研究的核心议题之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/output-prefix-injection">Output- Prefix Injection in LLMs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2307.02483v1">Jailbroken: How Does LLM Safety Training Fail?</a></li>

</ul>
</details>

**标签**: `#LLM security`, `#jailbreaking`, `#prompt injection`, `#adversarial attacks`, `#AI safety`

---