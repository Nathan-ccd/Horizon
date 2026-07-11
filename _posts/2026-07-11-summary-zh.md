---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> 从 17 条内容中筛选出 15 条重要资讯。

---

1. [苹果起诉 OpenAI，指控前员工窃取商业机密](#item-1) ⭐️ 9.0/10
2. [QuadRF：开源射频相机可穿墙探测 WiFi 信号](#item-2) ⭐️ 8.0/10
3. [GPT-5.6 Sol Ultra 声称证明了循环双覆盖猜想](#item-3) ⭐️ 8.0/10
4. [Unsloth NVFP4 量化使 Qwen3.6 速度提升 2.5 倍](#item-4) ⭐️ 8.0/10
5. [腾讯 HY3 MoE 模型在 Macbook M5 Max 128GB 上运行良好](#item-5) ⭐️ 8.0/10
6. [USB 上的本地 LLM 生存工具包](#item-6) ⭐️ 8.0/10
7. [《终结者 2》特效口述史：改变电影的技术](#item-7) ⭐️ 7.0/10
8. [好工具是隐形的](#item-8) ⭐️ 7.0/10
9. [Nilay Patel：AR 眼镜必然侵犯隐私](#item-9) ⭐️ 7.0/10
10. [用 19 世纪文本训练大语言模型初见成效](#item-10) ⭐️ 7.0/10
11. [Strix Halo 每日电力成本仅需 0.48 美元](#item-11) ⭐️ 7.0/10
12. [DeepSeek V4 Flash 在 RTX 4090 + DDR5 上的用户实测](#item-12) ⭐️ 7.0/10
13. [纽约市禁止欺骗性订阅行为](#item-13) ⭐️ 6.0/10
14. [青铜时代晚期崩溃：简要介绍](#item-14) ⭐️ 6.0/10
15. [NVIDIA 准备推出 GeForce RTX 5090 SE 显卡](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [苹果起诉 OpenAI，指控前员工窃取商业机密](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 9.0/10

苹果已对 OpenAI 提起诉讼，指控这家 AI 公司系统性地招募苹果员工，并鼓励他们窃取商业机密，包括机密硬件信息和内部文件。 这场两大科技巨头之间的高调法律战可能严重影响 OpenAI 即将进行的 IPO，并削弱企业对 OpenAI 产品的信任，同时为 AI 行业如何保护商业机密树立先例。 苹果声称 OpenAI 指示新员工在离开苹果时如何避免被发现，例如不向苹果透露他们在 OpenAI 的新工作。诉讼还指控 OpenAI 利用窃取的苹果硬件信息接触苹果的供应商。

hackernews · stock_toaster · 7月10日 20:47 · [社区讨论](https://news.ycombinator.com/item?id=48865019)

**背景**: 商业机密窃取是指不当获取或披露机密商业信息的行为。苹果历来积极保护其知识产权，此次诉讼针对的是以 ChatGPT 闻名的领先 AI 研究和部署公司 OpenAI。

**社区讨论**: 社区评论强烈支持苹果的诉讼，许多人认为证据确凿，并预测 OpenAI 将面临严重后果。一些评论者强调企业使用 OpenAI 产品的风险，而另一些人则指出一名在苹果工作 25 年的老员工为此放弃职业生涯的讽刺意味。

**标签**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI`

---

<a id="item-2"></a>
## [QuadRF：开源射频相机可穿墙探测 WiFi 信号](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 8.0/10

QuadRF 是一款由 Raspberry Pi 5 驱动的开源 4x4 MIMO 软件定义无线电，通过相控阵波束成形和皮秒级定时，已演示可穿墙探测无人机并可视化 WiFi 信号。 该工具使射频感知技术大众化，让爱好者和安全研究人员能够检测隐藏的无线设备和无人机，有望提升隐私和安全意识。 QuadRF 使用 FPGA 板进行高级信号处理和波束成形，其开源特性允许用户自定义界面和算法。演示展示了穿墙探测无人机控制信号并可视化附近 WiFi 网络的能力。

hackernews · speckx · 7月10日 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48861717)

**背景**: 射频感知利用无线电波检测和定位物体或信号，类似于雷达但频率较低。像 QuadRF 这样的软件定义无线电（SDR）可以在软件中处理宽频段信号，使其适用于多种应用。相控阵天线无需移动部件即可实现波束成形，聚焦特定方向。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/">QuadRF can spot drones and see WiFi through my wall - Jeff Geerling</a></li>
<li><a href="https://www.crowdsupply.com/scale-rf/quadrf">QuadRF | Crowd Supply</a></li>
<li><a href="https://eucloudservers.com/security-encryption/quadrf-can-spot-drones-and-see-wifi-through-my-wall/">QuadRF can spot drones and see WiFi through my... - EU Cloud Servers</a></li>

</ul>
</details>

**社区讨论**: 项目创建者直接参与评论，回答问题并指出根据反馈改进了界面。一些评论者对标题的清晰度提出质疑，指出 WiFi 本身就能穿墙，而其他人则讨论了潜在的监控影响以及与热成像相机的比较。

**标签**: `#RF sensing`, `#open source`, `#drone detection`, `#WiFi`, `#hardware`

---

<a id="item-3"></a>
## [GPT-5.6 Sol Ultra 声称证明了循环双覆盖猜想](https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf) ⭐️ 8.0/10

OpenAI 发布了一篇预印本，声称其 GPT-5.6 Sol Ultra 模型生成了图论中一个长期未解决的开放问题——循环双覆盖猜想的证明。 如果得到验证，这将是人工智能首次自主生成一个重大数学猜想的正确证明，可能改变数学研究的方式。 该证明极其简洁，暗示了一个专家可能忽略的巧妙技巧，但社区因需要大量提示工程且缺乏独立验证而持怀疑态度。

hackernews · scrlk · 7月10日 18:29 · [社区讨论](https://news.ycombinator.com/item?id=48863490)

**背景**: 循环双覆盖猜想询问是否每个无桥无向图都有一个循环集合，使得每条边恰好出现两次。该猜想已开放数十年，与图嵌入和圆形嵌入猜想相关。GPT-5.6 Sol Ultra 是 OpenAI 于 2026 年 7 月发布的最新模型，在编程、科学和网络安全方面树立了新标杆。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycle_double_cover_conjecture">Cycle double cover conjecture</a></li>
<li><a href="https://openai.com/index/gpt-5-6/">GPT‑5.6: Frontier intelligence that scales with your ambition</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_engineering">Prompt engineering</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，提示中包含大量指令以迫使模型真正解决问题，包括拒绝模糊的乐观情绪。一些人认为社区本身并不关心这个猜想，因为它之前很少被讨论。另一些人指出，证明的简洁性引发了怀疑，而真正的人工智能成就应该是自主构建理论的证明。

**标签**: `#AI`, `#mathematics`, `#GPT-5`, `#conjecture`, `#proof`

---

<a id="item-4"></a>
## [Unsloth NVFP4 量化使 Qwen3.6 速度提升 2.5 倍](https://www.reddit.com/r/LocalLLaMA/comments/1usniqh/25x_faster_qwen36_nvfp4_unsloth_quants/) ⭐️ 8.0/10

Unsloth 发布了 Qwen3.6 27B 和 35B-A3B 模型的 NVFP4 量化版本，相比 NVIDIA 的 NVFP4 实现，27B 模型速度提升高达 2.5 倍，35B-A3B 模型提升高达 1.79 倍，且精度无损失。他们还提供了 FP8 KV 缓存校准，支持 2 倍更长的上下文窗口。 这一突破显著提升了 NVIDIA Blackwell GPU 上大语言模型的推理速度，使高性能本地 LLM 推理更加普及。W4A4 矩阵乘法与 FP8 KV 缓存的结合为量化 LLM 树立了新的效率标准。 Unsloth 的 NVFP4 使用 W4A4（4 位权重和激活）矩阵乘法，而 NVIDIA 的实现使用 W4A16（4 位权重，16 位激活）。对于 35B-A3B 模型，Unsloth 提供了两个变体：NVFP4-Fast（完全 W4A4，快 1.79 倍）和 NVFP4（混合精度，快 1.56 倍，精度略高）。

reddit · r/LocalLLaMA · /u/danielhanchen · 7月10日 13:20

**背景**: NVFP4 是 NVIDIA Blackwell GPU 架构引入的 4 位浮点量化格式，比均匀 INT4 量化具有更高的动态范围。W4A4 指将权重和激活都量化为 4 位，从而在张量核心上实现更快的矩阵乘法。FP8 KV 缓存减少了键值缓存的内存占用，无需额外显存即可支持更长的上下文长度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://build.nvidia.com/spark/nvfp4-quantization">NVFP4 Quantization | DGX Spark</a></li>
<li><a href="https://developers.redhat.com/articles/2026/02/04/accelerating-large-language-models-nvfp4-quantization">Accelerating large language models with NVFP4 quantization | Red Hat Developer</a></li>
<li><a href="https://docs.vllm.ai/projects/llm-compressor/en/latest/examples/quantization_w4a4_fp4/">fp4 Quantization with NVFP4 - LLM Compressor Docs</a></li>

</ul>
</details>

**标签**: `#quantization`, `#LLM inference`, `#Qwen`, `#performance optimization`, `#NVFP4`

---

<a id="item-5"></a>
## [腾讯 HY3 MoE 模型在 Macbook M5 Max 128GB 上运行良好](https://www.reddit.com/r/LocalLLaMA/comments/1usy9ie/tencenthy3_is_the_real_deal_on_128gb/) ⭐️ 8.0/10

一位 Reddit 用户成功在 Macbook M5 Max（128GB 内存）上运行腾讯新发布的 295B-A21B MoE 模型（HY3），使用了自定义的 Unsloth 动态量化（UD128）和修补版的 llama.cpp，令牌生成速度达到 DeepSeek V4 Flash 的两倍，且质量相当或更优。 这表明前沿开源 MoE 模型现在可以在高端消费级硬件上运行，使个人开发者和研究人员无需昂贵的服务器级 GPU 即可获得先进的 AI 能力。 用户使用了 107GB 的 UD128 量化（动态 3 位），并修复了 GGUF 架构字符串不匹配问题（hy-v3 vs hy_v3）后才成功加载模型。基准测试显示，在 M5 Max 上，空上下文时解码速度为 32.4 tokens/s，16K 上下文时为 16.3 tokens/s。

reddit · r/LocalLLaMA · /u/returnity · 7月10日 19:53

**背景**: 腾讯 HY3 是一个 295B 参数的混合专家（MoE）模型，具有 21B 活跃参数和 3.8B 的 MTP 投机解码层，专为推理和智能体任务设计。它使用 192 个专家（top-8 激活），支持 256K 上下文窗口。Unsloth 动态量化是一种选择性跳过某些参数量化的方法，在减小模型大小的同时保持精度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Tencent-Hunyuan/Hy3">GitHub - Tencent-Hunyuan/Hy3: Hy3 (295B A21B), a leading reasoning and agent model in its size, with great cost efficiency. · GitHub</a></li>
<li><a href="https://unsloth.ai/docs/basics/unsloth-dynamic-2.0-ggufs">Unsloth Dynamic 2.0 GGUFs | Unsloth Documentation</a></li>
<li><a href="https://mer.vin/2026/07/tencent-hy3-295b-moe-agent-model-free-on-nous-portal/">Tencent Hy3: 295B MoE Agent Model Free on Nous Portal - Mervin Praison</a></li>

</ul>
</details>

**标签**: `#Tencent-HY3`, `#MoE`, `#local LLM`, `#quantization`, `#Macbook`

---

<a id="item-6"></a>
## [USB 上的本地 LLM 生存工具包](https://www.reddit.com/r/LocalLLaMA/comments/1uspcg0/has_anyone_created_a_local_llm_survival_kit/) ⭐️ 8.0/10

一位 Reddit 用户提出将 llama.cpp、量化 LLM（Qwen3.5 35B-A3B 和 Gemma 4 E4B）以及压缩的 Wikipedia SQLite 数据库放入便携式 U 盘，无需互联网即可在任何 PC 上实现离线 AI 知识访问。 这一概念满足了便携式离线 AI 知识库的需求，有可能在连接受限或无连接的环境中普及基于 LLM 的信息检索。 该工具包可放入 64 GB U 盘（价格低于 10 美元），在过去 15 年的 CPU 上以 5-20 tokens/s 运行，并包含适用于 Windows、macOS 和 Linux 的 llama.cpp 二进制文件。

reddit · r/LocalLLaMA · /u/-p-e-w- · 7月10日 14:30

**背景**: llama.cpp 是一个开源的 C/C++ 库，用于在 CPU 上高效推理 LLM，广泛用于 Ollama 等本地 AI 工具。量化模型（如 Q4_K_M）可在质量损失极小的情况下减少内存占用。sqlite-zstd 实现了 SQLite 数据库的透明压缩，可将 120 GB 的 Wikipedia 数据压缩至约 30 GB。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++ · GitHub</a></li>
<li><a href="https://github.com/phiresky/sqlite-zstd">GitHub - phiresky/sqlite-zstd: Transparent dictionary-based ...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论（超过 100 条评论）总体积极，许多人称赞该想法的实用性，并建议加入医学教科书或离线搜索工具等改进。一些人担心存储限制以及旧硬件上推理速度不足的问题。

**标签**: `#local-llm`, `#offline-ai`, `#portable-llm`, `#llama.cpp`, `#knowledge-base`

---

<a id="item-7"></a>
## [《终结者 2》特效口述史：改变电影的技术](https://vfxblog.com/2017/08/23/the-tech-of-terminator-2-an-oral-history/) ⭐️ 7.0/10

一篇 2017 年的口述历史文章详细介绍了工业光魔（ILM）如何为《终结者 2：审判日》中的液态金属 T-1000 发明新技术，包括用于子弹撞击的定制弹丸和使用 Softimage 软件。 《终结者 2》是视觉特效的里程碑，连接了实际效果和数字效果，并影响了现代 CGI。了解其创新为电影中计算机图形学的演变提供了背景。 CGI 团队从《深渊》的 6 人扩大到《终结者 2》的 35 人。该片获得了 1992 年奥斯卡最佳视觉效果奖和最佳化妆奖，其 4K 重制版在 35 周年之际重新在影院上映。

hackernews · markus_zhang · 7月10日 16:48 · [社区讨论](https://news.ycombinator.com/item?id=48862365)

**背景**: 《终结者 2：审判日》（1991 年）是一部由詹姆斯·卡梅隆执导的科幻电影，以其开创性地使用计算机生成图像（CGI）来创造变形角色 T-1000 而闻名。当时，许多视觉效果必须从零开始发明，结合了实际效果（如电子动画和烟火）与早期的数字合成和 3D 渲染。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Special_effects_of_Terminator_2:_Judgment_Day">Special effects of Terminator 2: Judgment Day - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Terminator_2:_Judgment_Day">Terminator 2 : Judgment Day - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞这篇文章揭示了有多少技术必须从零开始发明，其中一人指出液态金属子弹撞击的定制弹丸是有史以来最好的实际效果之一。其他人则强调了 Softimage 的使用，并推荐了关于该片特效关键人物史蒂夫·威廉姆斯的纪录片《侏罗纪朋克》。

**标签**: `#VFX`, `#computer graphics`, `#film technology`, `#practical effects`, `#history`

---

<a id="item-8"></a>
## [好工具是隐形的](https://www.gingerbill.org/article/2026/07/10/good-tools-are-invisible/) ⭐️ 7.0/10

一篇论文认为，好的工具通过最小化摩擦变得隐形，让用户专注于工作本身而非工具。 这一理念挑战工具设计者优先考虑用户体验并减少认知负荷，影响软件工程和用户体验实践。 论文强调，隐形工具并不意味着没有界面，而是指需要最少有意识努力来操作的界面。

hackernews · theanonymousone · 7月10日 10:32 · [社区讨论](https://news.ycombinator.com/item?id=48858121)

**背景**: 工具隐形的概念植根于人机交互和设计哲学。好的工具，如设计精良的锤子或文本编辑器，会淡出背景，让用户专注于任务。这一理念常在开发者工具和生产力讨论中被提及。

**社区讨论**: 评论者大多同意这一论点，并分享个人经验。一些人指出，隐形也可能来自长期使用的熟悉感，而必要的摩擦（如合并冲突）仍可接受。关于键盘与鼠标效率存在争论，有人认为生产力主张往往未经测量。

**标签**: `#tool design`, `#developer experience`, `#UX`, `#software engineering`

---

<a id="item-9"></a>
## [Nilay Patel：AR 眼镜必然侵犯隐私](https://simonwillison.net/2026/Jul/10/nilay-patel/#atom-everything) ⭐️ 7.0/10

Nilay Patel 认为，增强现实眼镜本质上需要摄像头持续记录用户所见的一切，并通过云端处理来叠加信息，这使得隐私侵犯不可避免。他提出，这种社会代价可能过高，我们应考虑停止开发。 这一论点挑战了 AR 眼镜是下一代计算平台的主流叙事，揭示了一个可能产生广泛社会影响的基本隐私缺陷。它迫使行业和消费者权衡 AR 的好处与隐私的丧失。 Patel 指出，目前没有足够小、能塞进眼镜腿的芯片能同时满足实时本地处理所需的性能和功耗，因此必须依赖云端处理。唯一的替代方案是像 Apple Vision Pro 那样笨重的设备，并配有外接电池包。

rss · Simon Willison · 7月10日 17:05

**背景**: 增强现实（AR）眼镜将数字信息叠加到现实世界上，通常使用摄像头和传感器来理解环境。包括 Meta 和 Apple 在内的许多公司正在大力投资 AR，将其视为下一个主要计算平台。然而，要实现轻便、可全天佩戴的外形，需要在处理能力和电池续航方面做出重大妥协，从而导致对云计算的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.alibaba.com/product-insights/smart-glasses-with-on-device-ai-vs-cloud-dependent-ar-which-preserves-privacy-and-delivers-snappy-response-times.html">Smart Glasses With On-device AI Vs Cloud-dependent AR: Which ...</a></li>
<li><a href="https://eyeware.store/ar-and-smart-lenses-why-your-home-router-and-phone-matter-mo">AR Glasses : Why Your Router & Phone Matter</a></li>

</ul>
</details>

**标签**: `#augmented reality`, `#privacy`, `#technology ethics`, `#AR glasses`

---

<a id="item-10"></a>
## [用 19 世纪文本训练大语言模型初见成效](https://www.reddit.com/r/LocalLLaMA/comments/1uswlq8/training_an_llm_from_scratch_on_1800s_texts_160gb/) ⭐️ 7.0/10

一位 Reddit 用户仅用 160GB 的 19 世纪英文文本（400 亿 token）预训练了一个 5 亿参数的大语言模型，并在合成问答对上微调以回答历史问题，计划进一步训练 20 亿参数模型。 这证明了在历史数据上进行领域特定预训练的可行性，有望为历史研究提供准确的问答能力，并保留过去的语言模式。 数据集涵盖 1800 年至 1875 年英国和美国的英文文本，共 400 亿 token。5 亿参数的评估模型在 50 亿 token 样本上训练，并使用从同一数据集中生成的合成问题进行微调。

reddit · r/LocalLLaMA · /u/Remarkable-Trick-177 · 7月10日 18:51

**背景**: 预训练是大语言模型训练的第一阶段，教会模型语法、句法和世界知识。领域特定预训练使用聚焦的语料库来专业化模型，通常随后在任务特定数据上进行微调。合成问答对常用于使大语言模型适应回答特定领域的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2407.14076v1">Domain - Specific Pretraining of Language Models: A Comparative...</a></li>
<li><a href="https://blog.algomaster.io/p/how-llms-are-actually-trained">How LLMs are Actually Trained</a></li>
<li><a href="https://genai.stackexchange.com/questions/1880/how-do-people-fine-tune-llms-to-only-answer-domain-specific-questions">How do people fine tune LLMs to only answer domain specific...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#pretraining`, `#historical NLP`, `#domain-specific`, `#open source`

---

<a id="item-11"></a>
## [Strix Halo 每日电力成本仅需 0.48 美元](https://www.reddit.com/r/LocalLLaMA/comments/1ussasa/at_most_my_strix_halo_uses_048_a_day/) ⭐️ 7.0/10

一位 Reddit 用户报告称，AMD 的 Strix Halo APU 满负荷运行 24 小时，电费最多仅需 0.48 美元，使其成为本地 LLM 推理中极其节能的平台。 这凸显了集成 APU 在本地 AI 工作负载中相对于独立 GPU 的主要优势，因为在比较性能时，能源成本和热量输出常常被忽视。这可能会将用户偏好转向更高效的硬件，用于持续运行的推理任务。 该用户在 Q8_XL 量化的 Qwen 3.6 35B 模型上实现了每秒 50 个 token，同时系统保持静音且节能。相比之下，NVIDIA RTX A6000 单卡功耗为 300W，是 Strix Halo 系统总功耗预算的两倍。

reddit · r/LocalLLaMA · /u/Forward_Jackfruit813 · 7月10日 16:18

**背景**: Strix Halo 是 AMD 的高端 APU 代号，在一个芯片上集成了 Zen 5 CPU 核心、强大的集成 Radeon 8060S GPU 和 XDNA 2 NPU。它旨在取代紧凑型工作站中的独立 GPU，提供高达 50 TOPS 的 AI 性能。Qwen 3.6 35B 模型是一个大型语言模型，可以通过量化减少内存和计算需求，使其能够在集成硬件上运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Strix_Halo">Strix Halo</a></li>
<li><a href="https://acemagic.com/blogs/about-ace-mini-pc/amd-strix-halo">AMD Strix Halo Mini PCs: Specs, Benchmarks, and Top Ryzen AI Max Build – ACEMAGIC</a></li>
<li><a href="https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF">unsloth/Qwen3.6-35B-A3B-GGUF · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论普遍认为，Strix Halo 因其低功耗和多功能性，为本地 LLM 推理提供了卓越的价值，尽管有人指出初始硬件成本较高。用户还将其与 Mac 和高端 GPU 进行对比，认为在持续运行或多服务场景中更具优势。

**标签**: `#Strix Halo`, `#local LLM`, `#energy efficiency`, `#hardware comparison`, `#inference`

---

<a id="item-12"></a>
## [DeepSeek V4 Flash 在 RTX 4090 + DDR5 上的用户实测](https://www.reddit.com/r/LocalLLaMA/comments/1ustyas/deepseek_v4_flash_on_4090_ddr5_my_experience/) ⭐️ 7.0/10

一位用户成功在 RTX 4090 和 128GB DDR5 内存上，使用 llama.cpp 运行 DeepSeek V4 Flash（UD-Q2_K_XL 量化），实现了 10.9 token/s 的生成速度和 132.5 token/s 的提示处理速度。 这表明像 DeepSeek V4 Flash 这样的大型 MoE 模型可以在消费级硬件上以可接受的性能运行，可能使先进 LLM 对爱好者和小型用户更易获取。 将 CPU 绑定到物理核心使生成速度从 6.8 t/s 翻倍至 10.9 t/s；使用--no-mmap 更慢，某些上下文/批次设置导致 CUDA 缓冲区爆炸（90 GB 以上）。IQ4_NL 量化太慢且上下文限制在约 10k token。

reddit · r/LocalLLaMA · /u/kevin_1994 · 7月10日 17:17

**背景**: DeepSeek V4 Flash 是一个具有数千亿参数的混合专家（MoE）大型语言模型。在消费级 GPU 上运行此类模型需要激进量化和将层卸载到系统内存，llama.cpp 通过 GGUF 格式支持这一点。CPU 绑定通过确保线程在专用核心上运行来提高性能，减少缓存未命中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/unsloth/GLM-5.2-GGUF/discussions/9">unsloth/GLM-5.2-GGUF · Issues with UD-Q2_K_XL quant</a></li>
<li><a href="https://deepwiki.com/ggml-org/llama.cpp/2.3-configuration-and-parameters">Configuration and Parameters | ggml-org/llama.cpp | DeepWiki</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp/issues/10052">Bug: Can't run even the smallest model due to CUDA OOM without...</a></li>

</ul>
</details>

**标签**: `#DeepSeek`, `#LLM inference`, `#consumer hardware`, `#llama.cpp`, `#performance optimization`

---

<a id="item-13"></a>
## [纽约市禁止欺骗性订阅行为](https://www.theguardian.com/us-news/2026/jul/10/new-york-city-deceptive-subscriptions-ban) ⭐️ 6.0/10

纽约市颁布了一项具有里程碑意义的消费者保护法规，禁止欺骗性订阅行为，包括隐藏费用和难以取消的流程。 这项法规通过简化取消订阅流程和消除意外费用来加强消费者权益，可能为其他城市和州树立先例。 该法规由市长 Mamdani 宣布，包含“一键取消”要求，并针对垃圾费用。它似乎没有加州类似法律中的餐厅豁免条款。

hackernews · randycupertino · 7月10日 18:26 · [社区讨论](https://news.ycombinator.com/item?id=48863464)

**背景**: 订阅服务经常使用复杂的取消流程和隐藏费用来留住客户。加州已有类似法律，FTC 也提出了全国性规则，但执行力度不一。

**社区讨论**: 评论者对执法力度表示怀疑，指出加州类似法律存在餐厅豁免等漏洞。一些人称赞此举是亲消费者治理的信号，而另一些人则分享了取消订阅失败的亲身经历。

**标签**: `#consumer protection`, `#regulation`, `#subscriptions`, `#NYC`

---

<a id="item-14"></a>
## [青铜时代晚期崩溃：简要介绍](https://acoup.blog/2026/01/30/collections-the-late-bronze-age-collapse-a-very-brief-introduction/) ⭐️ 6.0/10

ACOUP 的一篇博客文章简要介绍了青铜时代晚期崩溃，探讨其原因并与现代社会的依赖性进行类比。 这一历史分析揭示了复杂社会如何因相互关联的脆弱性而崩溃，这与当前对技术和全球供应链系统性风险的担忧产生共鸣。 文章强调了贸易网络中断和资源稀缺（例如青铜所需的锡）在崩溃中的作用，并与现代对石油和人工智能的依赖进行类比。

hackernews · dmonay · 7月10日 11:59 · [社区讨论](https://news.ycombinator.com/item?id=48858737)

**背景**: 青铜时代晚期崩溃（约公元前 1200-1150 年）见证了东地中海多个文明的衰落，可能由气候变化、入侵和经济破坏等多种因素共同导致。该时代严重依赖长途贸易获取锡等关键资源，因此容易受到供应链中断的影响。

**社区讨论**: 评论者将其与现代风险（如人工智能驱动的崩溃或石油依赖）进行类比，并推荐了 Eric Cline 和 Patrick Wyman 的相关书籍。一条幽默评论认为崩溃是由于众神发怒所致。

**标签**: `#history`, `#systems collapse`, `#ancient civilizations`, `#societal risk`

---

<a id="item-15"></a>
## [NVIDIA 准备推出 GeForce RTX 5090 SE 显卡](https://www.reddit.com/r/LocalLLaMA/comments/1ustlrg/nvidia_readies_geforce_rtx_5090_se_graphics_card/) ⭐️ 6.0/10

据报道，NVIDIA 正在准备一款新的 GeForce RTX 5090 SE 显卡，它是旗舰 RTX 5090 的缩减版本，旨在填补 RTX 5080 和 RTX 5090 之间的空白。 这款新 SKU 可能为高端游戏和 AI 推理提供更实惠的选择，通过平衡性能和价格，可能对本地 LLM 社区产生影响。 据传，RTX 5090 SE 的功耗为 500W，而 RTX 5090 为 575W，RTX 5080 为 360W，并且预计将成为全球产品，不限于中国市场。

reddit · r/LocalLLaMA · /u/panchovix · 7月10日 17:05

**背景**: GeForce RTX 50 系列基于 NVIDIA 的 Blackwell 架构，于 2025 年 CES 上发布，包括 RTX 5070、RTX 5080 和 RTX 5090。这些 GPU 采用第四代 RT 核心和第五代 Tensor 核心，并由台积电定制 4N 工艺制造。RTX 5090 SE 将是一款定位在 RTX 5080 和 RTX 5090 之间的新变体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.techpowerup.com/350658/nvidia-readies-geforce-rtx-5090-se-graphics-card">NVIDIA Readies GeForce RTX 5090 SE Graphics Card | TechPowerUp</a></li>
<li><a href="https://tech4gamers.com/nvidia-geforce-rtx-5090-se/">NVIDIA GeForce RTX 5090 SE : A Middle Ground Between RTX 5080...</a></li>
<li><a href="https://en.wikipedia.org/wiki/GeForce_RTX_50_series">GeForce RTX 50 series</a></li>

</ul>
</details>

**标签**: `#NVIDIA`, `#GPU`, `#hardware`, `#rumor`

---