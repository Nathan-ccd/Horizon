---
layout: default
title: "Horizon Summary: 2026-06-30 (ZH)"
date: 2026-06-30
lang: zh
---

> 从 20 条内容中筛选出 12 条重要资讯。

---

1. [最高法院：地理围栏搜查令需受宪法保护](#item-1) ⭐️ 9.0/10
2. [LongCat-2.0：1.6 万亿参数 MoE 模型发布](#item-2) ⭐️ 9.0/10
3. [火箭实验室以 80 亿美元收购铱星公司](#item-3) ⭐️ 8.0/10
4. [韩国将投资 1 万亿美元于存储芯片和人形机器人](#item-4) ⭐️ 8.0/10
5. [WATaBoy：将 Game Boy 指令 JIT 编译为 WASM，性能超越原生解释器](#item-5) ⭐️ 8.0/10
6. [Ornith-1.0：面向智能体编程的开源权重大模型](#item-6) ⭐️ 8.0/10
7. [DeepSeek V4 支持已合并到 llama.cpp](#item-7) ⭐️ 8.0/10
8. [拟议的.self 顶级域名旨在促进自托管](#item-8) ⭐️ 7.0/10
9. [Qwen 3.6 27B：强大的本地模型，但成本高昂](#item-9) ⭐️ 7.0/10
10. [SSH 原生图形化外壳降低延迟](#item-10) ⭐️ 7.0/10
11. [Amodei：开源模型会吃掉你的孩子](#item-11) ⭐️ 7.0/10
12. [三星、SK 海力士、美光因 DRAM 价格操纵被起诉](#item-12) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [最高法院：地理围栏搜查令需受宪法保护](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

美国最高法院裁定，要求科技公司提供特定区域内所有设备位置数据的地理围栏搜查令构成第四修正案意义上的搜查，必须基于可能原因获得搜查令。 这一里程碑式的裁决极大地限制了执法部门在无个别嫌疑情况下获取批量位置数据的能力，加强了数百万智能手机用户的数字隐私保护。 该案涉及谷歌的 Sensorvault 数据库，该数据库存储历史位置数据；法院认为，即使在公共场所，个人对其位置历史也有合理的隐私期待。

hackernews · cdrnsf · 6月29日 15:54 · [社区讨论](https://news.ycombinator.com/item?id=48720924)

**背景**: 地理围栏搜查令是一种要求谷歌等公司识别特定时间段内虚拟围栏（地理围栏）内所有设备的搜查令。第四修正案保护公民免受不合理搜查和扣押；最高法院此前在 Carpenter v. United States（2018）案中裁定，获取基站位置数据需要搜查令。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision">US supreme court rules geofence warrants require constitutional privacy protections | US supreme court | The Guardian</a></li>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>
<li><a href="https://www.scotusblog.com/2026/04/digital-location-data-heads-back-to-the-supreme-court-/">Digital location data heads back to the Supreme Court | SCOTUSblog</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，照片元数据（EXIF）也会在无法律程序的情况下泄露位置数据，并注意到法院意见引用了 Riley v. California 等来源。一些人讨论了替代识别方法，例如使用酒店客人名单交叉比对 IP 地址。

**标签**: `#privacy`, `#supreme court`, `#geofence warrants`, `#fourth amendment`, `#digital rights`

---

<a id="item-2"></a>
## [LongCat-2.0：1.6 万亿参数 MoE 模型发布](https://www.reddit.com/r/LocalLLaMA/comments/1uj7egu/introducing_longcat20_a_largescale_moe_language/) ⭐️ 9.0/10

LongCat-2.0，一个总参数量达 1.6 万亿、每个 token 激活约 480 亿参数的大规模混合专家（MoE）语言模型，现已发布。该模型此前在 OpenRouter 上以代号'owl-alpha'提供。 该模型代表了开源大语言模型在规模上的重大突破，通过 MoE 架构在保持效率的同时将模型尺寸推向新高度。它可能使研究人员和开发者能够更广泛地获得前沿 AI 能力。 LongCat-2.0 采用混合专家架构，每个 token 仅激活部分参数（480 亿），从而在总参数量巨大的情况下实现高效推理。该模型在正式发布前已在 OpenRouter 上秘密测试。

reddit · r/LocalLLaMA · /u/AnticitizenPrime · 6月29日 22:42

**背景**: 混合专家（MoE）是一种神经网络架构，它将模型划分为多个专门的子网络（专家），并通过门控机制为每个输入选择使用哪些专家。这使得模型容量可以扩展，而计算成本不会成比例增加。OpenRouter 是一个提供统一 API 访问数百个 AI 模型的平台，包括开源和专有模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>
<li><a href="https://medium.com/@rogi23696/understanding-llms-mixture-of-experts-9c250560b5b2">Understanding LLMs: Mixture of Experts | by Roger Oriol | Medium</a></li>

</ul>
</details>

**标签**: `#LLM`, `#MoE`, `#Large Language Model`, `#Open Source`, `#AI`

---

<a id="item-3"></a>
## [火箭实验室以 80 亿美元收购铱星公司](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

火箭实验室宣布以现金加股票交易方式收购铱星通信公司，交易价值约 80 亿美元，获得铱星的卫星星座、许可频谱和 255 万用户。 此次收购打造了一个垂直整合的太空基础设施领导者，结合了发射服务、卫星制造和盈利的通信网络，类似于 SpaceX 的 Starlink 战略。它为火箭实验室提供了稳定的发射需求和宝贵的频谱资产。 该交易对铱星的估值为每股 54 美元，预计于 2026 年下半年完成。火箭实验室还将接管铱星的卫星制造和未来星座替换计划。

hackernews · everfrustrated · 6月29日 14:09 · [社区讨论](https://news.ycombinator.com/item?id=48719485)

**背景**: 铱星运营着由 66 颗活跃低地球轨道卫星组成的星座，提供全球语音和数据覆盖，包括极地地区。火箭实验室最初是一家新西兰公司，现总部位于美国，提供发射服务和制造卫星。此次收购模仿了 SpaceX 与 Starlink 的垂直整合模式，即通过内部卫星网络来锚定发射需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/space/2026/06/in-a-bold-move-rocket-lab-acquires-iridium-communications/">In a bold move, Rocket Lab acquires Iridium ... - Ars Technica</a></li>
<li><a href="https://qz.com/rocket-lab-iridium-acquisition-satellite-communications-062926">Rocket Lab acquires Iridium in $8 billion satellite deal</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了与 SpaceX Starlink 作为发射需求锚点的战略相似性，并指出火箭实验室获得了频谱和盈利的卫星业务。一些人表达了对太空垃圾和卫星数量激增的担忧，而另一些人则认为这是 Peter Beck 的明智之举。

**标签**: `#space`, `#acquisition`, `#satellites`, `#Rocket Lab`, `#Iridium`

---

<a id="item-4"></a>
## [韩国将投资 1 万亿美元于存储芯片和人形机器人](https://arstechnica.com/ai/2026/06/south-korea-to-spend-1t-on-more-memory-chip-production-and-humanoid-robots/) ⭐️ 8.0/10

韩国宣布了一项 1 万亿美元的投资计划，旨在提升存储芯片产量并开发人形机器人，以巩固其在半导体和 AI 驱动机器人领域的地位。 这一巨额投资表明韩国在两项关键技术上的战略押注：存储芯片（对 AI 和数据中心至关重要）和人形机器人（可能改变劳动力和制造业格局）。此举可能加剧全球在半导体制造和机器人领域的竞争。 该投资涵盖存储芯片制造设施的扩建和人形机器人的研发，但两个领域的具体分配尚未披露。韩国企业如三星和 SK 海力士主导全球存储芯片生产，而人形机器人开发仍处于早期阶段。

hackernews · jnord · 6月29日 22:21 · [社区讨论](https://news.ycombinator.com/item?id=48726102)

**背景**: 存储芯片（如 DRAM 和 NAND 闪存）是计算机、智能手机和 AI 数据中心的关键组件。人形机器人设计为模仿人体形状，可在人类环境中工作，但其商业可行性仍不确定。韩国是存储芯片的主要生产国，但面临来自中国和美国的竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanoid_robot">Humanoid robot</a></li>
<li><a href="https://en.wikipedia.org/wiki/Semiconductor_device_fabrication">Semiconductor device fabrication - Wikipedia</a></li>
<li><a href="https://restofworld.org/2026/ai-memory-chip-explainer/">AI is dominating the world’s memory chips. That could make phones more expensive</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了将存储芯片和人形机器人合并投资的原因，有人将其比作一起购买杂货和舞蹈课。其他人质疑人形形态的价值，并好奇德国为何错过了半导体制造热潮。

**标签**: `#semiconductors`, `#humanoid robots`, `#investment`, `#South Korea`, `#AI`

---

<a id="item-5"></a>
## [WATaBoy：将 Game Boy 指令 JIT 编译为 WASM，性能超越原生解释器](https://humphri.es/blog/WATaBoy/) ⭐️ 8.0/10

一篇博文展示，将 Game Boy 模拟器指令 JIT 编译为 WebAssembly 可以超越原生解释器，甚至在 iOS 等限制传统 JIT 的平台上也能实现更快的模拟。 这种方法使得在 iOS 等受限平台上实现高性能模拟成为可能，有望扩大模拟器的覆盖范围，并启发其他复古系统的类似 JIT-to-WASM 技术。 该模拟器 WATaBoy 在运行时将 SM83（Game Boy 的 CPU）指令动态重编译为 WebAssembly，利用浏览器的 WASM 引擎进行 JIT 编译。基准测试中，Firefox 比 Chrome/Safari 慢约 25%。

hackernews · energeticbark · 6月29日 15:02 · [社区讨论](https://news.ycombinator.com/item?id=48720190)

**背景**: Game Boy 模拟器传统上使用解释执行或原生 JIT 编译。然而，苹果 iOS 限制非浏览器应用的 JIT 编译，使得高性能模拟困难。浏览器支持的 WebAssembly 允许在沙盒环境中进行 JIT 编译，从而绕过这些限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://humphri.es/blog/WATaBoy/">WATaBoy: JIT-ing Game Boy Instructions to Wasm Beats a Native Interpreter</a></li>
<li><a href="https://github.com/sysprog21/jitboy">GitHub - sysprog21/jitboy: A Game Boy emulator with dynamic recompilation (JIT) · GitHub</a></li>
<li><a href="https://rodrigodd.github.io/2023/09/02/gameroy-jit.html">GameRoy: JIT compilation in High-Accuracy Game Boy Emulation | Rodrigodd</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞该项目作为本科生作品令人印象深刻，并指出 WASM 开销（约 20%）远低于解释器开销（约 1000%），解释了性能提升的原因。一些人讨论了相关的 JIT 技术，例如使用 JavaScript 的 eval()实现简单 JIT，以及苹果在 iOS 上的 JIT 限制。

**标签**: `#JIT compilation`, `#WebAssembly`, `#emulation`, `#Game Boy`, `#performance`

---

<a id="item-6"></a>
## [Ornith-1.0：面向智能体编程的开源权重大模型](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce 发布了 Ornith-1.0，这是一个面向智能体编程的开源权重（MIT 许可）大模型系列，包含从 9B 到 397B MoE 的多个变体，基于 Gemma 4 和 Qwen 3.5 构建。在编程基准测试中，它在同等规模的开源模型中达到了最先进的性能。 此次发布为智能体编程任务提供了一个强大且许可宽松的替代方案，可能加速开源 AI 辅助软件开发。其自构建能力和强劲的基准表现可能使其成为开发者构建自主编程智能体的首选模型。 该模型系列包括 9B Dense、31B Dense、35B MoE 和 397B MoE 变体，全部采用 MIT 许可。35B MoE 变体以 20GB GGUF 文件形式提供，可通过 LM Studio 在消费级硬件上良好运行，图像生成速度达到 103 tokens/秒。

rss · Simon Willison · 6月29日 16:17

**背景**: 智能体编程是指使用 AI 智能体自主执行软件开发任务，如代码生成、调试和测试。Ornith-1.0 采用自构建训练框架，模型通过迭代自我改进学习提升自身的推理和工具使用能力，并解决了奖励作弊问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/29/ornith/">Ornith-1.0: Self - Scaffolding LLMs for Agentic Coding</a></li>
<li><a href="https://deep-reinforce.com/ornith_1_0.html">Ornith-1.0: Self - Scaffolding LLMs ... | DeepReinforce Blog | Jun. 2026</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户报告在编程任务上表现良好且能提供创造性解决方案，而另一些用户则指出在无工具聊天场景下表现不佳且存在幻觉问题。有人怀疑该模型是否只是 Qwen 或 Gemma 4 的微调版本，并对没有高端 GPU 的用户的可及性表示担忧。

**标签**: `#LLM`, `#open-source`, `#coding`, `#AI`, `#model release`

---

<a id="item-7"></a>
## [DeepSeek V4 支持已合并到 llama.cpp](https://www.reddit.com/r/LocalLLaMA/comments/1uj0fkw/deepseek_v4_pr_merged_into_llamacpp/) ⭐️ 8.0/10

一个为 DeepSeek V4 添加支持的拉取请求已合并到 llama.cpp 仓库，允许用户通过 GGUF 格式在本地运行该模型。 此次合并使开源社区能够在消费级硬件上本地运行 DeepSeek V4，极大地扩展了对这一重要新模型的访问，并促进了进一步的实验和开发。 用户现在可以拉取最新的 llama.cpp，使用 cmake 编译，并下载 GGUF 文件以在本地运行 DeepSeek V4。该 PR（编号 24162）已合并到 ggml-org/llama.cpp 仓库。

reddit · r/LocalLLaMA · /u/Squik67 · 6月29日 18:19

**背景**: llama.cpp 是一个开源的 C/C++ 库，用于在各种硬件上高效地进行 LLM 推理，已成为 Ollama 和 LM Studio 等本地推理工具的事实标准。GGUF 格式是一种自包含的文件格式，旨在存储量化模型以供基于 GGML 的库使用，从而实现高效的本地执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++ · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://huggingface.co/docs/diffusers/quantization/gguf">GGUF · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子对此次合并表示兴奋，用户们渴望在本地尝试 DeepSeek V4。评论强调了按照提供的说明（git pull、cmake、下载 GGUF）操作的简便性。

**标签**: `#llama.cpp`, `#DeepSeek V4`, `#local LLM`, `#open-source`, `#inference`

---

<a id="item-8"></a>
## [拟议的.self 顶级域名旨在促进自托管](https://hccf.onmy.cloud/2026/06/21/reclaiming-our-digital-selves-hccfs-vision-for-a-human-centered-top-level-domain/) ⭐️ 7.0/10

一项名为.self 的新顶级域名提案被提出，旨在通过向个人提供免费子域名来专门支持自托管。 如果实施，.self 可能降低个人托管自己服务的门槛，促进去中心化并减少对中心化平台的依赖。然而，它也引发了关于安全、域名抢注和声誉管理的担忧，可能影响其采用。 该提案包括“每人一个免费域名”的政策，但执行需要身份验证以防止抢注。该顶级域名将由非营利组织运营，社区指出了资金挑战。

hackernews · HumanCCF · 6月29日 19:49 · [社区讨论](https://news.ycombinator.com/item?id=48724230)

**背景**: 顶级域名是 DNS 层次结构的最高级别，如.com 或.org。自托管是指个人运行自己的服务器来提供网站或电子邮件等服务，而不是使用第三方提供商。.self 顶级域名是一个新颖的概念，旨在为自托管服务创建一个专用的命名空间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48724230">self: A new top - level domain designed to support self - hosting</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains">List of Internet top - level domains - Wikipedia</a></li>
<li><a href="https://selfhosting.sh/foundations/selfhosting-security-checklist/">Self - Hosting Security Checklist | selfhosting .sh</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的社区评论表达了复杂情绪：一些人担心.self 域名会因被认为安全水平业余而招致安全探测，而另一些人则回忆起.tk 顶级域名的历史，免费域名导致了垃圾邮件和屏蔽。建议包括使用声誉系统和挑战机制来缓解抢注问题。

**标签**: `#self-hosting`, `#DNS`, `#TLD`, `#decentralization`, `#community-discussion`

---

<a id="item-9"></a>
## [Qwen 3.6 27B：强大的本地模型，但成本高昂](https://quesma.com/blog/qwen-36-is-awesome/) ⭐️ 7.0/10

Qwen 3.6 27B 是一个针对编码和实际应用优化的密集 27B 参数模型，已发布并正在评估其用于本地开发。文章指出，虽然该模型表现良好，但本地运行需要昂贵的硬件（如 128GB MacBook Pro），且会产生明显的噪音和热量。 这很重要，因为它揭示了本地运行大型语言模型的实际权衡：高昂的硬件成本、噪音和热量，与云 API 的便利性和低成本之间的对比。这场讨论有助于开发者在投资本地硬件还是依赖云服务之间做出明智决策。 Qwen 3.6 27B 模型在 Q4_K_M 量化下需要约 40GB 显存，这意味着需要 64GB 以上统一内存的 Mac 或双 NVIDIA GPU。文章指出，128GB MacBook Pro 起售价为 6699 美元，而 OpenRouter 等云替代方案以极低的成本提供相同模型。

hackernews · stared · 6月29日 17:05 · [社区讨论](https://news.ycombinator.com/item?id=48721903)

**背景**: 像 Qwen 3.6 27B 这样的大型语言模型通常在强大的云服务器上运行，但一些开发者出于隐私、延迟或离线使用的考虑，更倾向于本地运行。本地运行 27B 模型需要大量硬件资源，通常是高端 Mac 或多个 GPU，这既昂贵又会产生热量和噪音。云 API 提供按需访问相同模型的服务，无需前期硬件投资。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen3.6-27b">Qwen3.6-27B: Flagship-Level Coding in a 27B Dense Model</a></li>
<li><a href="https://www.kunalganglani.com/blog/running-local-llms-2026-hardware-setup-guide">Local LLM Hardware Guide 2026: VRAM, GPUs, Setup [Tested]</a></li>
<li><a href="https://overchat.ai/ai-hub/llm-hardware-requirements">Local LLM Hardware Requirements in 2026 | AI Hub</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出硬件成本过高：128GB MacBook Pro 售价约 6700 美元，而 OpenRouter 的云额度则便宜得多。一些用户提到本地模型会产生过多噪音和热量，使其不适用于实际编码。其他人质疑文章中的示例是否反映了与现有代码库的“实际工作”，认为模型在复杂场景下的表现可能不那么令人印象深刻。

**标签**: `#LLM`, `#local development`, `#hardware`, `#Qwen`, `#cost analysis`

---

<a id="item-10"></a>
## [SSH 原生图形化外壳降低延迟](https://probablymarcus.com/blocks/2026/06/28/native-graphical-shell-for-SSH.html) ⭐️ 7.0/10

Marcus Lewis 发布了 Outer Shell，这是一个开源的 SSH 原生图形化外壳，通过分离前端和后端来降低延迟，使远程图形应用能以更低开销运行。 这种方法挑战了传统的远程桌面方式（如 X11 转发），为 Jupyter 和 Tensorboard 等基于 Web 的工具提供了更流畅的体验，有望改善远程服务器上的开发者工作流程。 该外壳使用一个自定义代理，随每个 X 或 Wayland 会话启动，并通过 Unix 套接字通信，允许应用以原生外框应用或传统 HTML 网页应用的形式提供服务。

hackernews · mrcslws · 6月29日 15:42 · [社区讨论](https://news.ycombinator.com/item?id=48720758)

**背景**: SSH（安全外壳）是一种用于安全远程登录和执行命令的协议。传统的 SSH 图形转发（如 X11 转发）通常存在高延迟和安全问题。Outer Shell 旨在通过分离图形前端和后端逻辑来缓解这些问题，类似于现代 Web 应用分离客户端和服务器的方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://probablymarcus.com/blocks/2026/06/28/native-graphical-shell-for-SSH.html">A native graphical shell for SSH | Marcus Lewis</a></li>
<li><a href="https://news.ycombinator.com/item?id=48720758">A native graphical shell for SSH | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区意见分歧：一些人称赞这项创新解决了实际的延迟问题，而另一些人则认为它是在重新发明已有的解决方案（如 X11 转发或 Cockpit），批评者引用了“不理解 Unix 的人注定会糟糕地重新发明它”这句话。

**标签**: `#SSH`, `#graphical shell`, `#remote desktop`, `#latency`, `#Unix`

---

<a id="item-11"></a>
## [Amodei：开源模型会吃掉你的孩子](https://www.reddit.com/r/LocalLLaMA/comments/1uiyrlq/amodei_open_source_models_will_eat_your_children/) ⭐️ 7.0/10

Anthropic CEO Dario Amodei 发表了一句挑衅性言论，称开源 AI 模型会“吃掉你的孩子”，引发了关于 AI 安全和行业动态的激烈辩论。 这位 AI 领军人物的话凸显了开源与专有 AI 之间日益紧张的关系，对 AI 行业的监管、安全和竞争具有深远影响。 Amodei 此前曾称开源 AI 是“红鲱鱼”，认为它无法提供与传统开源软件相同的社区利益。辩论的核心在于开源模型是带来安全风险还是促进创新。

reddit · r/LocalLLaMA · /u/johnnyApplePRNG · 6月29日 17:19

**背景**: Dario Amodei 是 Anthropic（Claude 大语言模型系列背后的公司）的联合创始人兼 CEO，此前曾任 OpenAI 研究副总裁。AI 安全辩论中，开源倡导者与主张控制开发以防止滥用的阵营经常对立。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dario_Amodei">Dario Amodei - Wikipedia</a></li>
<li><a href="https://digg.com/tech/vbm50qd6">Dario Amodei Warns Senate Open - Source AI Models Threaten...</a></li>
<li><a href="https://thewincentral.com/anthropic-ceo-open-source-ai-red-herring-debate/">Anthropic CEO Calls Open - Source AI a 'Red Herring' - WinCentral</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区反应不一：一些人同意开源模型若被滥用可能带来危险，而另一些人则认为 Amodei 的立场是自私的，开源通过同行评审促进了透明度和安全性。

**标签**: `#open-source`, `#AI safety`, `#LLM`, `#community debate`

---

<a id="item-12"></a>
## [三星、SK 海力士、美光因 DRAM 价格操纵被起诉](https://www.reddit.com/r/LocalLLaMA/comments/1uiwtd7/samsung_sk_hynix_micron_sued_in_us_over_memory/) ⭐️ 7.0/10

美国联邦法院提起一项集体诉讼，指控三星、SK 海力士和美光合谋操纵 DRAM 价格并限制供应，人为抬高内存成本。 该诉讼可能导致内存价格下降，直接影响 AI 硬件、个人电脑和游戏主机的成本，因为 DRAM 是关键组件。 诉讼指出，这三家公司控制着全球超过 95%的 DRAM 市场，过去也曾面临类似的价格操纵指控，包括 2018 年一起被驳回的案件。

reddit · r/LocalLLaMA · /u/johnnyApplePRNG · 6月29日 16:08

**背景**: DRAM（动态随机存取存储器）是用于计算机、服务器和 AI 加速器的一种内存。三星、SK 海力士和美光这三家公司主导着全球 DRAM 市场。价格操纵的指控时有出现，此前在不同司法管辖区已有法律诉讼和反垄断调查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DRAM_price_fixing_scandal">DRAM price fixing scandal - Wikipedia</a></li>
<li><a href="https://www.gfinityesports.com/article/federal-lawsuit-alleges-the-biggest-ram-makers-manipulated-the-entire-market">Federal Lawsuit Alleges the Biggest RAM Makers Manipulated the...</a></li>
<li><a href="https://www.videogameschronicle.com/news/ram-manufacturers-have-been-sued-for-allegedly-fixing-prices-and-supply-leading-to-increased-costs/">RAM manufacturers have been sued for allegedly fixing prices and...</a></li>

</ul>
</details>

**标签**: `#memory`, `#lawsuit`, `#AI hardware`, `#DRAM`, `#pricing`

---