---
layout: default
title: "Horizon Summary: 2026-06-21 (ZH)"
date: 2026-06-21
lang: zh
---

> 从 15 条内容中筛选出 12 条重要资讯。

---

1. [SMPTE 免费开放其标准库](#item-1) ⭐️ 8.0/10
2. [时间序列建模需要动力系统视角](#item-2) ⭐️ 8.0/10
3. [大规模 LLM 推理开源手册](#item-3) ⭐️ 8.0/10
4. [F-15 Strike Eagle II 逆向工程招募测试员](#item-4) ⭐️ 7.0/10
5. [CSSQuake：用 CSS 渲染在浏览器中玩《雷神之锤》](#item-5) ⭐️ 7.0/10
6. [免费工作坊教你从零构建 LLM](#item-6) ⭐️ 7.0/10
7. [ML 博士生没有顶会论文能否毕业？](#item-7) ⭐️ 7.0/10
8. [DVD-JEPA：开源 JEPA 世界模型演示](#item-8) ⭐️ 7.0/10
9. [TSAuditor：时间序列数据验证工具](#item-9) ⭐️ 7.0/10
10. [minFLUX：FLUX 扩散模型的极简 PyTorch 实现](#item-10) ⭐️ 7.0/10
11. [全球 PM2.5 预测模型通过水平对齐架构解决方差陷阱](#item-11) ⭐️ 7.0/10
12. [UHF X11 将 X11 带到 Apple Vision Pro](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [SMPTE 免费开放其标准库](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 8.0/10

SMPTE 宣布，自 2026 年 6 月 17 日起，其全部标准、推荐实践、工程指南和注册披露文档已向全球媒体技术社区免费开放。 此举消除了获取关键媒体技术标准的经济障碍，促进了整个行业的创新和互操作性，类似于 IETF 开放标准模式的成功。 免费访问包括所有已发布的 SMPTE 标准、推荐实践、工程指南和注册披露文档 (RDD)，以及所有未来版本。SMPTE 还通过采用 GitHub 工作流、结构化 HTML 编写和集成发布管道来现代化其开发流程。

hackernews · zdw · 6月20日 17:01 · [社区讨论](https://news.ycombinator.com/item?id=48610827)

**背景**: SMPTE（电影与电视工程师协会）是一个国际公认的标准组织，为媒体技术行业制定了 800 多项标准。此前，获取这些标准需要购买单个文档，成本高昂且阻碍了广泛采用。通过免费开放，SMPTE 与推动互联网等其他技术领域成功的开放标准运动保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community">SMPTE Makes Its Standards Freely Accessible, Opening ...</a></li>
<li><a href="https://www.tvtechnology.com/standards/smpte-makes-its-standards-freely-accessible-to-the-global-media-technology-community">SMPTE Makes Its Standards Freely Accessible to the Global ...</a></li>
<li><a href="https://www.smpte.org/standards/overview">Standards Overview | Society of Motion Picture & Television ...</a></li>

</ul>
</details>

**社区讨论**: 社区普遍对这一举措表示赞赏，评论者指出它消除了障碍并可能激发创新，将其与 IETF 成功的开放标准模式相提并论。一些人表示惊讶这并非默认做法，而另一些人则对 GitHub 集成等现代化努力表示赞赏。

**标签**: `#standards`, `#media technology`, `#open access`, `#SMPTE`

---

<a id="item-2"></a>
## [时间序列建模需要动力系统视角](https://www.reddit.com/r/MachineLearning/comments/1uark0u/time_series_modeling_needs_a_dynamical_systems/) ⭐️ 8.0/10

一篇在 ICML 2026 上发表的立场论文认为，时间序列建模应采用动力系统视角，建议关注动力系统重建（DSR）训练技术、在动力系统模拟上预训练，并从 Transformer 回归到现代 RNN。 这一范式转变可能实现真正的域外泛化和长期预测，解决当前时间序列基础模型的根本性局限。 论文比较了自定义训练模型和近期基础模型在短期和长期预测上的表现，并提出了五个具体方向，包括广义教师强制和应对拓扑变化。

reddit · r/MachineLearning · /u/DangerousFunny1371 · 6月20日 08:47

**背景**: 时间序列建模旨在基于过去观测预测未来值。动力系统理论通过递归规则描述系统如何随时间演化，从数据中重建这些规则称为动力系统重建（DSR）。当前基础模型常使用 Transformer，可能丢失关键的时间结构。

**标签**: `#time series`, `#dynamical systems`, `#machine learning`, `#ICML`, `#foundation models`

---

<a id="item-3"></a>
## [大规模 LLM 推理开源手册](https://www.reddit.com/r/MachineLearning/comments/1uavduv/an_open_handbook_on_llm_inference_at_scale_gpu/) ⭐️ 8.0/10

一本关于大规模 LLM 推理的开源、进行中的手册已发布，涵盖 GPU 内部原理、KV 缓存、批处理以及 vLLM、SGLang 和 TensorRT-LLM 等生产框架。 该手册为工程师和研究人员提供了全面、结构清晰的资源，帮助他们理解和优化 LLM 推理，解决生产部署中的关键瓶颈。 该手册包含用于架构可视化的 mermaid 图表，并通过 GitHub issues 和 PR 积极寻求社区反馈。

reddit · r/MachineLearning · /u/YouFirst295 · 6月20日 12:27

**背景**: 大规模 LLM 推理涉及高效服务大型语言模型，需要理解 GPU 内存层次结构（HBM、L2 缓存、SRAM）、KV 缓存以避免冗余计算，以及连续批处理等批处理策略。vLLM（使用 PagedAttention）和 TensorRT-LLM（采用 CUDA 图融合）等生产框架可优化吞吐量和延迟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youngju.dev/blog/gpu-cuda/2026-03-17-gpu-memory-inference-optimization-guide.en">GPU Memory Management & LLM Inference Optimization: vLLM ...</a></li>
<li><a href="https://medium.com/@joaolages/kv-caching-explained-276520203249">Transformers KV Caching Explained | by João Lages | Medium</a></li>
<li><a href="https://medium.com/synthetic-futures/vllm-vs-tensorrt-llm-the-definitive-2026-comparison-for-llm-inference-ed0943fb81d2">vLLM vs TensorRT - LLM : The Definitive 2026 Comparison ... | Medium</a></li>

</ul>
</details>

**标签**: `#LLM inference`, `#GPU internals`, `#KV cache`, `#batching`, `#production ML`

---

<a id="item-4"></a>
## [F-15 Strike Eagle II 逆向工程招募测试员](https://neuviemeporte.github.io/f15-se2/2026/06/20/needyou.html) ⭐️ 7.0/10

一个针对 DOS 游戏《F-15 Strike Eagle II》的逆向工程项目正在将其汇编代码转换为二进制等效的 C 代码，并正在招募测试人员来查找逆向代码中的错误。 该项目旨在将这款经典游戏完整移植到 Linux 和 Windows 等现代平台，为后代保存它，并实现模拟器无法提供的增强功能。 该过程首先将游戏完全逆向为汇编代码，然后将汇编代码转换为编译后二进制文件完全相同的 C 代码，整个过程仍在 DOS 上运行，直到没有汇编代码残留。

hackernews · LowLevelMahn · 6月20日 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48609766)

**背景**: 《F-15 Strike Eagle II》是 MicroProse 于 1989 年发布的一款战斗飞行模拟游戏。从汇编到 C 的逆向工程是一个复杂的过程，常常会引入新错误，因此测试至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/F-15_Strike_Eagle_II">F-15 Strike Eagle II - Wikipedia</a></li>
<li><a href="https://www.myabandonware.com/game/f-15-strike-eagle-ii-n6">Download F-15 Strike Eagle II - My Abandonware</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了反编译与模拟的价值，一些人指出反编译便于移植。还有人询问是否可以使用 AI 从反编译代码中推断结构，一名测试者分享说该项目需要原始游戏文件。

**标签**: `#reverse engineering`, `#DOS games`, `#retro computing`, `#software preservation`

---

<a id="item-5"></a>
## [CSSQuake：用 CSS 渲染在浏览器中玩《雷神之锤》](https://cssquake.com/) ⭐️ 7.0/10

CSSQuake 是一个基于网页的经典游戏《雷神之锤》（1996）的重制版，它完全使用 CSS 3D 变换和 HTML 渲染游戏世界，由 PolyCSS 引擎驱动，不依赖 WebGL 或 canvas。 该项目展示了现代 CSS 和浏览器的卓越能力，突破了仅用 Web 标准所能达到的界限，并激发了游戏开发和渲染方面的创造性方法。 CSSQuake 将原始《雷神之锤》数据预处理为浏览器可用的 JSON 和图像资源，并将 BSP 世界渲染为真实的 HTML/CSS 3D 几何体。不过，部分游戏行为与原版不同，例如某些按钮需要射击而非触碰才能激活。

hackernews · msalsas · 6月20日 10:49 · [社区讨论](https://news.ycombinator.com/item?id=48608223)

**背景**: 《雷神之锤》是 1996 年的一款标志性第一人称射击游戏，以其全 3D 引擎而闻名。CSS（层叠样式表）是一种用于设置 HTML 元素样式的 Web 技术，现代 CSS 包含可创建 3D 场景的 3D 变换。PolyCSS 是一个使用 CSS 变换在浏览器中渲染 3D 图形的引擎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cssquake.com/">cssQuake - Powered by PolyCSS</a></li>
<li><a href="https://github.com/LayoutitStudio/cssQuake">GitHub - LayoutitStudio/cssQuake: A port of Quake (1996), powered by the PolyCSS 3D engine. · GitHub</a></li>
<li><a href="https://trendshift.io/repositories/59891">LayoutitStudio/cssQuake — GitHub trending stats & insights</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一技术成就表示惊叹，有人指出其运行速度比 90 年代的 PC 还慢。其他人觉得退出比 vim 还难，并欣赏其怀旧感，同时有人指出了与原版游戏玩法的差异。

**标签**: `#CSS`, `#game development`, `#web technology`, `#retro gaming`

---

<a id="item-6"></a>
## [免费工作坊教你从零构建 LLM](https://www.reddit.com/r/MachineLearning/comments/1uazlnd/hi_reddit_i_posted_my_build_your_own_llm_workshop/) ⭐️ 7.0/10

JustinAngel 在 YouTube 上发布了一个录播工作坊，教授如何从零构建大型语言模型，涵盖机器学习基础、Transformer 架构和训练，无需数学或机器学习先修知识。 该资源降低了初学者理解和构建 LLM 的门槛，有望扩大能够为 AI 开发做出贡献的开发者社区。 工作坊包含幻灯片、基于 Excel 的数学直觉练习以及 PyTorch 编码示例，涵盖 SwiGLU、RMSNorm 和 Triton 等主题。最初在旧金山线下举办，现可免费在线观看。

reddit · r/MachineLearning · /u/JustinAngel · 6月20日 15:36

**背景**: 从零构建 LLM 需要理解神经网络、注意力机制和训练流程。许多现有教程假设读者具备机器学习或高等数学的先修知识，导致初学者难以入门。本工作坊旨在通过代码和 Excel 示例从头教授概念，填补这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@s_boudefel/exploring-swiglu-the-activation-function-powering-modern-llms-9697f88221e7">Exploring SwiGLU : The Activation Function Powering Modern LLMs | by Selssabil | Medium</a></li>
<li><a href="https://openai.com/index/triton/">Introducing Triton: Open-source GPU programming for neural networks | OpenAI</a></li>
<li><a href="https://sebastianraschka.com/faq/docs/rmsnorm-vs-layernorm.html">Why do many modern LLMs use RMSNorm instead of LayerNorm?</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子获得了积极反响，作者积极回答问题。评论者赞赏其全面且对初学者友好的方法，以及提供幻灯片和练习供自学使用。

**标签**: `#LLM`, `#Machine Learning`, `#Tutorial`, `#Deep Learning`, `#Transformer`

---

<a id="item-7"></a>
## [ML 博士生没有顶会论文能否毕业？](https://www.reddit.com/r/MachineLearning/comments/1uazlhg/would_you_let_an_ml_phd_student_graduate_without/) ⭐️ 7.0/10

Reddit 上的一场讨论提出：如果一名 ML 博士生有扎实的工作和 3 篇一作 A 类论文，但没有 NeurIPS、ICML、ICLR 或 CVPR 等顶会发表，导师是否应允许其毕业。 这场辩论凸显了 ML 学术界在发表指标与真实研究质量之间的张力，影响博士项目如何评估学生，并可能改变整个领域的毕业标准。 该学生有三篇一作 A 类论文和连贯的论文主题，但缺少 NeurIPS、ICML、ICLR 或 CVPR 等 A*级 ML 会议发表。核心问题是：仅凭扎实的毕业论文是否足以毕业。

reddit · r/MachineLearning · /u/Hope999991 · 6月20日 15:36

**背景**: 在机器学习学术界，NeurIPS、ICML、ICLR 和 CVPR 等顶会被视为发表的金标准，常被用作博士毕业的关键指标。然而，越来越多的人质疑这种对会议声望的强调是否低估了其他贡献，例如扎实但不那么耀眼的工作，或发表在声誉良好但非顶会上的论文。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://algoverseairesearch.org/blog/icml-iclr-aaai-student-guide">Beyond NeurIPS: A Student's Guide to ICML, ICLR, AAAI, and ...</a></li>
<li><a href="https://backpropagation.ai/posts/notable-papers-icml-iclr-neurips-cvpr-emnlp-2025-2026/">Notable Papers from ICLR, ICML, NeurIPS, CVPR, EMNLP (2025 ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 评论呈现分歧：有人认为顶会发表对职业前景至关重要，应作为毕业要求；另一些人则认为扎实的工作和好的论文就已足够，过度强调会议等级可能有害。多位评论者指出“A 类”的定义很重要，学生的成果应基于其自身价值来评判。

**标签**: `#machine learning`, `#PhD`, `#academia`, `#publications`, `#graduate education`

---

<a id="item-8"></a>
## [DVD-JEPA：开源 JEPA 世界模型演示](https://www.reddit.com/r/MachineLearning/comments/1uatlzx/dvdjepa_an_opensource_fullyreproducible_jepa/) ⭐️ 7.0/10

研究人员发布了 DVD-JEPA，这是一个最小化的开源联合嵌入预测架构（JEPA）世界模型实现，它学习预测 16×16 网格中弹跳 DVD 标志的表征，通过线性探针实现了 0.73 像素的位置恢复。 这项工作提供了一个完全可复现的最小化 JEPA 示例，JEPA 是一种新颖的自监督学习范式，预测潜在表征而非像素，使世界建模更高效、可扩展。它降低了研究人员和从业者基于 JEPA 进行世界模型实验的门槛。 该模型由一个上下文编码器、一个 EMA 目标编码器和一个潜在预测器组成，无需标签或解码器即可训练。它完全在浏览器客户端运行，训练好的 MLP 用约 40 行 JavaScript 重新实现，并能检测瞬移等异常，异常信号峰值达到基线的 88 倍。

reddit · r/MachineLearning · /u/NielsRogge · 6月20日 10:52

**背景**: JEPA（联合嵌入预测架构）是 Yann LeCun 于 2022 年提出的一种自监督学习方法，它预测未来观测的抽象嵌入（潜在表征），而非重建像素。这种方法避免了建模不可预测的像素级细节，已被应用于 Meta 的 I-JEPA 和 V-JEPA 模型中，用于图像和视频理解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Joint_Embedding_Predictive_Architecture">Joint Embedding Predictive Architecture</a></li>
<li><a href="https://arxiv.org/abs/2301.08243">[2301.08243] Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture</a></li>
<li><a href="https://www.emergentmind.com/topics/linear-probes">Linear Probes: Neural Network Diagnostics</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论内容充实，用户询问了与 I-JEPA 的关系以及选择简单域的原因。作者澄清说，DVD-JEPA 是一个最小化演示，用于说明 JEPA 的核心思想，扩展到复杂环境是未来的工作。

**标签**: `#world model`, `#JEPA`, `#self-supervised learning`, `#representation learning`, `#open source`

---

<a id="item-9"></a>
## [TSAuditor：时间序列数据验证工具](https://www.reddit.com/r/MachineLearning/comments/1ub15wf/tsauditor_a_timeseries_auditing_framework_p/) ⭐️ 7.0/10

一位从业者发布了开源 Python 库 TSAuditor，用于检测时间序列数据集中的时间顺序断裂、数据泄露和序列异常，并提供结构化报告和修复建议。 该工具解决了时间序列机器学习中常见但常被忽视的模型失败根源，帮助从业者避免帖子中描述的因数据泄露导致准确率高达 99%等代价高昂的错误。 TSAuditor 轻量级、可在 PyPI 上获取，且无需定义领域即可使用；它包含一个示例笔记本，将其输出与标准分析工具进行对比。

reddit · r/MachineLearning · /u/severecaseofsarcarsm · 6月20日 16:41

**背景**: 时间序列数据需要谨慎处理，以避免数据泄露（未来信息无意中影响训练）和时间顺序断裂（时间顺序被打乱）。标准分析工具常常遗漏这些问题，导致模型性能过于乐观。TSAuditor 专门针对这些陷阱，通过扫描结构问题和特征-目标泄露来检测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/imann128/tsauditor">GitHub - imann128/tsauditor: A data quality auditing library ...</a></li>
<li><a href="https://machinelearningmastery.com/3-subtle-ways-data-leakage-can-ruin-your-models-and-how-to-prevent-it/">3 Subtle Ways Data Leakage Can Ruin Your Models (and How to ...</a></li>
<li><a href="https://arxiv.org/abs/2512.06932">Hidden Leaks in Time Series Forecasting: How Data Leakage ... Avoiding Data Leakage in Timeseries 101 - Towards Data Science Data Leakage - GeeksforGeeks Data Leakage in Machine Learning: Causes, Examples, and ... What is data leakage in machine learning? - IBM</a></li>

</ul>
</details>

**标签**: `#time-series`, `#data validation`, `#machine learning`, `#open source`

---

<a id="item-10"></a>
## [minFLUX：FLUX 扩散模型的极简 PyTorch 实现](https://www.reddit.com/r/MachineLearning/comments/1ub1db3/studying_flux_in_diffusers_library_was_hard_so_i/) ⭐️ 7.0/10

一位开发者发布了 minFLUX，这是 FLUX 扩散模型的极简 PyTorch 实现，提供了清晰的训练和推理循环，并逐行映射到官方的 HuggingFace diffusers 库。 该项目通过剥离官方 diffusers 库的复杂性，使研究 FLUX 架构变得更加容易，使研究人员和从业者能够更有效地理解和实验最先进的扩散模型。 minFLUX 包含 FLUX.1 和 FLUX.2 的实现，突出了架构差异，如改进的 Transformer 块、调制、FFN、VAE 归一化和位置 ID。它使用流匹配（flow matching）和速度 MSE 损失进行训练，推理时采用 Euler ODE 求解器。

reddit · r/MachineLearning · /u/Other-Eye-8152 · 6月20日 16:50

**背景**: FLUX 是一系列文本到图像扩散模型，采用多模态和并行扩散 Transformer 块的混合架构，参数量达 120 亿。流匹配（flow matching）是一种与扩散模型密切相关的生成框架，而 Euler 方法是一种简单的数值 ODE 求解器，常用于扩散模型推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2507.09595v1">Demystifying Flux Architecture</a></li>
<li><a href="https://medium.com/@drmarcosv/how-does-flux-work-the-new-image-generation-ai-that-rivals-midjourney-7f81f6f354da">How does Flux work? The new image generation AI that rivals Midjourney | by Marcos V. Conde | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Euler_method">Euler method - Wikipedia</a></li>

</ul>
</details>

**标签**: `#diffusion models`, `#FLUX`, `#PyTorch`, `#open-source`, `#machine learning`

---

<a id="item-11"></a>
## [全球 PM2.5 预测模型通过水平对齐架构解决方差陷阱](https://www.reddit.com/r/MachineLearning/comments/1uar4vc/built_a_global_aq_pm25_forecaster_ml_model_p/) ⭐️ 7.0/10

一位开发者利用来自 OpenAQ 和 NASA 的 160 万+行数据构建了全球 PM2.5 预测管道，通过使用自回归滞后解耦预测水平解决了方差陷阱，使全球 MASE 低于 1.0。 该模型使用水平对齐架构，包含针对 h=1、7、14、30 天的严格自回归滞后向量，以及一个 3 天滚动波动率矩阵以防止数据泄漏。当前栈使用 scikit-learn GBR，计划迁移到 XGBoost 或 LightGBM。

reddit · r/MachineLearning · /u/Divyanshailani · 6月20日 08:20

**背景**: 方差陷阱发生在高方差环境中预测模型表现差于朴素基线（如简单延续猜测）时，表现为 MASE > 1.0。MASE（平均绝对缩放误差）将模型误差与朴素预测进行比较；低于 1.0 的值表示模型优于基线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tech.ajinhub.com/en/blog/the-forecasting-trap-navigating-latent-chaos-in-time-series/">The Forecasting Trap: Navigating Latent Chaos in Time Series</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mean_absolute_scaled_error">Mean absolute scaled error - Wikipedia</a></li>
<li><a href="https://insightful-data-lab.com/2025/08/19/mase-mean-absolute-scaled-error/">MASE (Mean Absolute Scaled Error) – Your Gateway to Data Mastery</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#time series forecasting`, `#air quality`, `#gradient boosting`, `#MLOps`

---

<a id="item-12"></a>
## [UHF X11 将 X11 带到 Apple Vision Pro](https://www.lispm.net/apps/uhf-x11/) ⭐️ 6.0/10

UHF X11 将 X11 窗口系统移植到 visionOS，使得经典 Unix GUI 应用能够以空间窗口的形式在 Apple Vision Pro 上运行。 该项目弥合了传统 Unix 软件与现代空间计算之间的鸿沟，可能使大量现有的 X11 应用能够在 AR/VR 环境中使用。 每个 X11 顶级窗口都会作为独立的 visionOS 窗口打开，OpenGL 客户端可以通过 X11 使用 GLX 渲染，但兼容性因情况而异。该项目目前较为小众，并非突破性进展。

hackernews · zdw · 6月20日 17:04 · [社区讨论](https://news.ycombinator.com/item?id=48610853)

**背景**: X11 是一种用于位图显示的窗口系统，常见于类 Unix 操作系统，最初于 1984 年发布。visionOS 是苹果为其 Apple Vision Pro 头显开发的混合现实操作系统，于 2024 年推出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48610853">UHF X11: X11 Built for VisionOS and Apple Vision Pro | Hacker ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/X_Windowing_System">X Windowing System</a></li>
<li><a href="https://en.wikipedia.org/wiki/VisionOS">VisionOS</a></li>

</ul>
</details>

**社区讨论**: 评论者认为该项目在技术上很有趣，有人提到“3D 中的 2D 中的 3D”，还有人遗憾截图中没有 xeyes。部分人讨论了 Linux AR 头显的替代方案（如 WayVR），而另一些人则质疑 visionOS 的寿命能否比肩 X11。

**标签**: `#X11`, `#VisionOS`, `#Apple Vision Pro`, `#AR/VR`, `#Linux`

---