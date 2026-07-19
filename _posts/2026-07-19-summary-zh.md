---
layout: default
title: "Horizon Summary: 2026-07-19 (ZH)"
date: 2026-07-19
lang: zh
---

> 从 20 条内容中筛选出 13 条重要资讯。

---

1. [LG 显示器通过 Windows Update 静默安装软件](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 Sol Pro 协助解决 30 年凸优化猜想](#item-2) ⭐️ 8.0/10
3. [Kimi K3 在 SpreadsheetBench 2 上超越 Claude Fable 5 排名第一](#item-3) ⭐️ 8.0/10
4. [Basalt Labs 被指控欺诈性 HLE 基准测试声明](#item-4) ⭐️ 8.0/10
5. [字节精确 KV 缓存嫁接提升 Gemma 4 准确率](#item-5) ⭐️ 8.0/10
6. [SQLite 查询解释器：浏览器工具揭秘查询计划](#item-6) ⭐️ 7.0/10
7. [Anthropic 改变策略，永久保留 Claude Fable 5](#item-7) ⭐️ 7.0/10
8. [DeepSeek 的高效是真实还是补贴？](#item-8) ⭐️ 7.0/10
9. [为 openPangu-2.0-Flash 92B MoE 模型添加 GGUF 支持](#item-9) ⭐️ 7.0/10
10. [FastFlowLM 加入 AMD 以推进 AI 推理](#item-10) ⭐️ 7.0/10
11. [社区建设需要主动付出](#item-11) ⭐️ 6.0/10
12. [纽约市长要求租房广告披露 AI 生成图片](#item-12) ⭐️ 6.0/10
13. [指南：用闲置 Mac 作为 Claude Code 代理](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LG 显示器通过 Windows Update 静默安装软件](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 9.0/10

LG 显示器利用 Windows Update 在未经用户同意的情况下静默安装软件，Gamers Nexus 使用 LG UltraGear 34GX900A-B 确认了这一行为。当通过 HDMI 连接显示器或已连接旧款 LG 显示器时，系统会自动安装包括 LG 扩展和软件组件包在内的软件。 这构成了重大安全风险，因为该软件拥有完全的系统访问权限、随系统启动并具有网络访问能力，实际上成为来自可信供应商的恶意软件。这暴露了 Windows Update 信任模型的关键缺陷，即硬件制造商可以在未经用户同意的情况下推送任意软件。 当插入新 LG 显示器或已连接旧款 LG 显示器时，软件会自动安装，无需用户交互。安装通过 Windows Update 进行，下载 LG 扩展和软件组件包，且该软件未经过沙盒隔离。

hackernews · baranul · 7月18日 10:21 · [社区讨论](https://news.ycombinator.com/item?id=48956688)

**背景**: Windows Update 旨在从硬件制造商处提供驱动程序和软件更新，以确保设备兼容性和安全性。然而，如果制造商推送非设备运行必需的软件，这一机制可能被滥用，正如本例所示。LG 显示器安装的软件具有完全的系统访问权限（类似于驱动程序），但包含可能非必要的附加应用程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent">LG monitors silently install software through Windows Update without user consent - VideoCardz.com</a></li>
<li><a href="https://www.lg.com/us/support/help-library/lg-monitor-how-to-update-monitor-firmware--20153819322140">LG Monitor - How to Update Monitor Firmware | LG USA Support</a></li>
<li><a href="https://learn.microsoft.com/en-us/defender-endpoint/malware/supply-chain-malware">Supply chain attacks - Microsoft Defender for Endpoint</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈担忧，一位用户指出其严重性：软件无需交互即可安装，拥有完全系统和网络访问权限，并随系统启动。另一位用户提供了通过组策略或设备安装设置禁用自动下载制造商应用的解决方法。部分评论者认为微软最终应对允许此行为负责。

**标签**: `#security`, `#privacy`, `#Windows`, `#LG`, `#supply chain attack`

---

<a id="item-2"></a>
## [GPT-5.6 Sol Pro 协助解决 30 年凸优化猜想](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐️ 8.0/10

有用户报告称，GPT-5.6 Sol Pro 通过精心设计的提示词，帮助解决了凸优化领域一个存在 30 年的猜想，该猜想涉及在球形域上最小化凸 Lipschitz 函数的迭代复杂度。证明过程消耗了 148 分钟的 AI 计算时间，但此前已有一年的人类研究积累。 这标志着 AI 辅助数学发现的又一实例，可能加速优化理论及相关领域的研究。同时，它也凸显了提示工程和人机协作的重要性，而非完全自主的 AI 研究。 该用户此前已用 GPT-5.4 和 GPT-5.5 尝试该问题一年之久，最终提示词中包含了解决问题所需的具体技术。使用的模型是 Sol Pro 而非更高级的 Ultra，声称的 148 分钟并未计入此前大量的人类工作。

hackernews · mbustamanter · 7月18日 13:00 · [社区讨论](https://news.ycombinator.com/item?id=48957779)

**背景**: 凸优化是数学优化的一个子领域，研究在凸集上最小化凸函数的问题，许多问题可在多项式时间内求解。这里解决的猜想涉及一阶方法最小化凸 Lipschitz 函数的迭代复杂度，这是一个 30 年来悬而未决的基本问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Convex_optimization">Convex optimization</a></li>
<li><a href="https://www.reddit.com/r/ChatGPTPro/comments/1usqw2q/gpt_56_sol_pro_vs_max_vs_ultra_doubts/">GPT 5.6 SOL: Pro vs Max vs Ultra - Doubts : r/ChatGPTPro - Reddit</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这一成就并非完全自主，因为用户已花费一年时间研究该问题，且提示词中包含了关键技术。一些人认为 AI 将把研究者的注意力转向更新颖的问题，另一些人则质疑 Sol Pro 与 Ultra 模型之间的区别。

**标签**: `#AI`, `#mathematics`, `#convex optimization`, `#LLM`, `#research`

---

<a id="item-3"></a>
## [Kimi K3 在 SpreadsheetBench 2 上超越 Claude Fable 5 排名第一](https://www.reddit.com/r/LocalLLaMA/comments/1uzzecz/kimi_k3_ranks_1_on_afterquerys_spreadsheetbench_2/) ⭐️ 8.0/10

Moonshot AI 推出的 2.8T 参数模型 Kimi K3 在 SpreadsheetBench 2 排行榜上取得第一名，超越了 Anthropic 的 Claude Fable 5。 这标志着 AI 格局的重大转变，一个相对较新的模型超越了主要 AI 实验室的领先模型，凸显了电子表格操作和智能体任务的快速进步。 SpreadsheetBench 2 使用真实场景评估模型在生产力、智能体和工具调用方面的能力。Kimi K3 拥有 100 万 token 的上下文窗口，并基于 Kimi Delta Attention 和 Attention Residuals 构建。

reddit · r/LocalLLaMA · /u/Charuru · 7月18日 15:50

**背景**: SpreadsheetBench 是一个具有挑战性的电子表格操作基准，包含 912 个真实世界问题。Claude Fable 5 于 2026 年 6 月发布，是 Anthropic 最强大的广泛可用模型，擅长长程推理和编码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spreadsheetbench.github.io/">SpreadsheetBench</a></li>
<li><a href="https://llm-stats.com/benchmarks/spreadsheetbench-2">SpreadsheetBench 2 Leaderboard | LLM Stats</a></li>
<li><a href="https://openlm.ai/kimi-k3/">Kimi K3 - openlm.ai</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论可能包括对 Kimi K3 性能的兴奋以及与其他模型的比较，但未提供具体评论。

**标签**: `#LLM`, `#benchmark`, `#Kimi K3`, `#AI competition`, `#spreadsheet`

---

<a id="item-4"></a>
## [Basalt Labs 被指控欺诈性 HLE 基准测试声明](https://www.reddit.com/r/LocalLLaMA/comments/1uztylz/basalt_labs_pulling_a_generationally_dumb_scam/) ⭐️ 8.0/10

Basalt Labs 被指控欺诈性地声称在人类最后一次考试（HLE）基准测试中达到 99.44% 的成绩，而实际使用的模型是基于 Qwen2.5-7B-Instruct 微调的，同时在其网站上提供的是不同的模型（DeepSeek）。 这一事件削弱了人们对 AI 基准测试声明的信任，并凸显了 AI 研究中透明度和可重复性的必要性。这可能导致对基准测试提交实施更严格的验证流程。 声称的模型基于 Qwen2.5-7B-Instruct（一个 70 亿参数的指令微调模型），而实际提供的模型是 DeepSeek（一个 6710 亿参数的模型）。HLE 基准测试包含 2500 个专家级问题，旨在测试前沿 AI 知识。

reddit · r/LocalLLaMA · /u/WithoutReason1729 · 7月18日 11:58

**背景**: 人类最后一次考试（HLE）是一个包含 2500 个跨学科专家级问题的基准测试，由 AI 安全中心和 Scale AI 创建。Qwen2.5-7B-Instruct 是阿里巴巴的一个 70 亿参数的开源模型，而 DeepSeek 是一个来自私人 AI 公司的更大的 6710 亿参数模型。声称的模型与实际提供的模型之间的差异表明存在故意欺骗。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanity's_Last_Exam">Humanity's Last Exam - Wikipedia</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen2.5-7B-Instruct">Qwen/Qwen2.5-7B-Instruct · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区表达了愤怒和难以置信，称这一骗局“世代级的愚蠢”，并指出其极易被识破。许多用户指出用一个小模型声称如此高分是荒谬的，并呼吁追究责任。

**标签**: `#AI ethics`, `#scam`, `#LLM`, `#community discussion`, `#fraud`

---

<a id="item-5"></a>
## [字节精确 KV 缓存嫁接提升 Gemma 4 准确率](https://www.reddit.com/r/LocalLLaMA/comments/1v07tib/byte_exact_kv_cache_grafting_on_frozen_gemma_4/) ⭐️ 8.0/10

研究人员发布了一种名为 Taliesin 的方法，可在冻结的 Gemma 4 上实现字节精确的 KV 缓存嫁接，将 AIME 2025 上的路由准确率从 76.7%提升至 90.0%。 该技术能够将经过验证的知识存储为 KV 状态并字节精确地恢复，有望降低推理成本，并实现跨会话的知识复用而无需重新训练。 该方法还能在零额外加速器内存的情况下，将可用上下文从 32,768 个 token 扩展到 2,854,766 个 token，并可在相同架构的机器之间移动字节完全相同的缓存。

reddit · r/LocalLLaMA · /u/MindPsychological140 · 7月18日 21:24

**背景**: KV 缓存存储先前 token 的键值对，以避免自回归生成过程中的重复计算，从而加速推理。字节精确嫁接意味着恢复的缓存与全新计算完全一致，精确保持模型行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2607.14431">Smarter and Cheaper at Once: Byte - Exact KV - Cache Grafting Turns...</a></li>
<li><a href="https://huggingface.co/papers/2607.14431">Paper page - Smarter and Cheaper at Once: Byte - Exact KV - Cache ...</a></li>
<li><a href="https://deepmind.google/models/gemma/gemma-4/">Gemma 4 is a family of open models , purpose-built for advanced...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论包括关于实现细节的技术问题以及作者的参与，总体对该新颖方法持积极态度。

**标签**: `#KV cache`, `#LLM`, `#knowledge storage`, `#Gemma 4`, `#efficiency`

---

<a id="item-6"></a>
## [SQLite 查询解释器：浏览器工具揭秘查询计划](https://simonwillison.net/2026/Jul/18/sqlite-query-explainer/#atom-everything) ⭐️ 7.0/10

Simon Willison 发布了一个基于浏览器的 SQLite 查询解释器工具，该工具通过 Pyodide/WebAssembly 运行 SQLite，并为 EXPLAIN 和 EXPLAIN QUERY PLAN 的输出添加解释性注释。该工具的灵感来自 Julia Evans 关于学习 SQLite 查询计划的博客文章。 理解 SQLite 查询计划是开发者的常见痛点；该工具通过在浏览器中提供通俗易懂的解释，无需任何服务器端设置，降低了门槛。它展示了 WebAssembly 的一个实际应用，将复杂的数据库内部机制带给更广泛的受众。 该工具在浏览器中运行编译为 WebAssembly 的完整 Python 解释器（通过 Pyodide），执行 SQLite 的 EXPLAIN 和 EXPLAIN QUERY PLAN 命令，然后添加人类可读的解释。作者提醒说，他尚未完全验证这些解释，因此用户应谨慎使用。

rss · Simon Willison · 7月18日 17:19

**背景**: SQLite 的 EXPLAIN 命令输出底层的虚拟机指令，而 EXPLAIN QUERY PLAN 则提供查询引擎如何执行查询的高级摘要。对于不熟悉 SQLite 内部机制的开发者来说，这两种输出可能难以理解。Pyodide 是一个基于 WebAssembly 的浏览器 Python 发行版，使 Python 代码能够在客户端运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pyodide.org/en/stable/console.html">pyodide .org/en/stable/console.html</a></li>
<li><a href="https://www.sqlite.org/eqp.html">EXPLAIN QUERY PLAN</a></li>
<li><a href="https://sqlite.org/lang_explain.html">EXPLAIN</a></li>

</ul>
</details>

**社区讨论**: 该文章引用了 Julia Evans 的博客，表明社区对学习查询计划感兴趣。作者承认验证有限，这可能会吸引社区贡献以提高准确性。

**标签**: `#sqlite`, `#query-plan`, `#webassembly`, `#tool`, `#sql`

---

<a id="item-7"></a>
## [Anthropic 改变策略，永久保留 Claude Fable 5](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 7.0/10

Anthropic 宣布，自 2026 年 7 月 20 日起，Claude Fable 5 将永久包含在 Max 和 Team Premium 订阅计划中，使用额度为原限额的 50%，推翻了此前移除该模型的计划。这一决定是在 OpenAI 的 GPT-5.6 Sol 和 Moonshot AI 的 Kimi 3 的竞争压力下做出的。 此举确保 Anthropic 高级订阅用户仍可使用其最强模型，防止用户大量流失到竞争对手。这凸显了 AI 模型市场的激烈竞争正迫使企业重新思考定价和访问策略。 每月 20 美元计划的用户仍无法访问 Fable 5；只有 Max（每月 100 美元）和 Team Premium（每月 200 美元）计划包含该模型。Pro 和 Team Standard 用户将获得一次性 100 美元积分，可通过使用额度使用 Fable 5。

rss · Simon Willison · 7月18日 06:00

**背景**: Claude Fable 5 是 Anthropic 的 Mythos 级模型的公开版本，于 2026 年 6 月 9 日与私有版本 Claude Mythos 5 一同发布。Anthropic 最初因计算能力问题计划从订阅计划中移除 Fable 5，但来自 GPT-5.6 Sol 和 Kimi 3 的竞争压力迫使公司改变了决定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#subscription`, `#competition`

---

<a id="item-8"></a>
## [DeepSeek 的高效是真实还是补贴？](https://www.reddit.com/r/LocalLLaMA/comments/1uzqspl/what_kind_of_dark_magic_is_deepseek_using/) ⭐️ 7.0/10

一篇 Reddit 帖子指出 DeepSeek 在 Artificial Analysis 排行榜上具有卓越的性价比，质疑其成本效率是源于真正的模型优化还是 API 补贴。 这场辩论很重要，因为如果 DeepSeek 的效率是真实的，它可能以极低的成本提供前沿性能，从而颠覆 AI 市场；如果是补贴的，则引发关于可持续性和公平竞争的质疑。 DeepSeek 的 API 定价极低：V4 Pro 输入每百万 token 0.435 美元，输出 0.87 美元，缓存命中输入低至 0.003625 美元。Artificial Analysis 排行榜显示 DeepSeek 模型在价格调整指标上优于竞争对手。

reddit · r/LocalLLaMA · /u/Fuckinglivemealone · 7月18日 08:58

**背景**: Artificial Analysis 排行榜在智能、速度和价格方面比较 LLM。DeepSeek 一直提供低成本的 API 访问，而 OpenAI 和 Anthropic 等竞争对手收费更高。社区对于 DeepSeek 的定价是反映真实效率还是为了抢占市场份额的亏本策略存在分歧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/leaderboards/models">LLM Leaderboard - Comparison of AI models from OpenAI, Anthropic...</a></li>
<li><a href="https://chat-deep.ai/pricing/">DeepSeek API Pricing: V4 Flash, V4 Pro, Cache Hit, Cache Miss ...</a></li>
<li><a href="https://artificialanalysis.ai/models/kimi-k3">Kimi K 3 - Intelligence, Performance & Price Analysis</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子引发了辩论：一些用户认为 DeepSeek 的效率源于 MoE 和激进量化等架构创新，而另一些人则怀疑是中国政府或风险资本的补贴。少数评论者指出 DeepSeek 的缓存命中定价异常低，暗示可能是亏本策略。

**标签**: `#DeepSeek`, `#AI pricing`, `#model efficiency`, `#LLM comparison`

---

<a id="item-9"></a>
## [为 openPangu-2.0-Flash 92B MoE 模型添加 GGUF 支持](https://www.reddit.com/r/LocalLLaMA/comments/1v03psf/model_add_openpangu20flash_92ba6b_with_mlalatent/) ⭐️ 7.0/10

joelfarthing 提交的拉取请求为 openPangu-2.0-Flash 模型添加了 GGUF 支持，该模型是一个总参数量 92B、激活参数量 6B 的混合专家（MoE）模型，支持 512K 上下文窗口，从而可通过 ik_llama.cpp 进行本地推理。 这将一个具有先进注意力机制（MLA、DSA/SWA）和多头 MTP 的最先进 92B MoE 模型引入本地硬件，极大扩展了设备端 LLM 推理的能力。 该模型在华为昇腾 NPU 上训练，是首批不依赖 NVIDIA 硬件的大规模模型之一。GGUF 转换支持 MLA 潜在缓存、DSA/SWA、mHC 和多头 MTP，均针对高效本地推理进行了优化。

reddit · r/LocalLLaMA · /u/pmttyji · 7月18日 18:38

**背景**: GGUF 是一种二进制文件格式，专为快速加载和保存模型张量及元数据而设计，常用于 llama.cpp 进行本地 LLM 推理。像 openPangu-2.0-Flash 这样的 MoE 模型每个 token 只激活部分参数，从而以较低计算成本实现高性能。该模型的 512K 上下文窗口和先进注意力机制（MLA、DSA/SWA）使其能够高效处理极长序列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/openpangu/openPangu-2.0-Flash/blob/main/README_EN.md">README_EN.md · openpangu/ openPangu - 2 . 0 - Flash at main</a></li>
<li><a href="https://en.wikipedia.org/wiki/GGUF">GGUF - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>

</ul>
</details>

**标签**: `#LLM`, `#MoE`, `#GGUF`, `#openPangu`, `#local inference`

---

<a id="item-10"></a>
## [FastFlowLM 加入 AMD 以推进 AI 推理](https://www.reddit.com/r/LocalLLaMA/comments/1v0axkk/fastflowlm_joins_amd_to_advance_ai_inference/) ⭐️ 7.0/10

AMD 宣布 FastFlowLM 团队加入公司，以推进 AI 推理能力，特别是针对 AMD Ryzen AI NPU。 此举通过引入针对其 NPU 优化的专业知识，加强了 AMD 在 AI 推理市场的地位，可能挑战 NVIDIA 在 AI 硬件领域的主导地位。 FastFlowLM 提供专为 AMD Ryzen AI NPU 设计的 Ollama 风格开发者体验，支持轻松本地运行大型语言模型。

reddit · r/LocalLLaMA · /u/jfowers_amd · 7月18日 23:40

**背景**: AI 推理是训练好的模型使用新数据生成预测或输出的过程。NPU（神经网络处理单元）是用于加速 AI 工作负载的专用硬件。FastFlowLM 是一个简化在 AMD NPU 上运行 LLM 的工具，类似于 Ollama 在其他硬件上的工作方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/FastFlowLM/FastFlowLM">GitHub - FastFlowLM/FastFlowLM: Run LLMs on AMD Ryzen™ AI NPUs in minutes. Just like Ollama - but purpose-built and deeply optimized for the AMD NPUs.</a></li>
<li><a href="https://fastflowlm.com/">FastFlowLM · FastFlowLM</a></li>

</ul>
</details>

**标签**: `#AMD`, `#AI inference`, `#FastFlowLM`, `#acquisition`

---

<a id="item-11"></a>
## [社区建设需要主动付出](https://www.benlandautaylor.com/p/if-you-build-it-they-will-come) ⭐️ 6.0/10

一篇论文指出，社区并非自动形成，而是需要主动努力去建设和维护，挑战了现代社会中普遍存在的被动消费者心态。 这一观点意义重大，因为它将社会疏离重新定义为被动消费的后果，鼓励个人成为社区的积极贡献者。 该文章借鉴个人轶事和观察，指出许多人将社交场景视为自然发生的现象，而非需要维护的事物。

hackernews · barry-cotter · 7月18日 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48959090)

**背景**: 社区建设是指有意创造和维持社会联系、活动和机构的努力。相比之下，消费者心态则期望这些无需个人投入就能存在。

**社区讨论**: 评论者大多同意文章的论点，分享了组织活动时感到脆弱的个人经历，并指出草根社会机构在代际间的衰落。

**标签**: `#community`, `#social dynamics`, `#essay`, `#culture`

---

<a id="item-12"></a>
## [纽约市长要求租房广告披露 AI 生成图片](https://petapixel.com/2026/07/16/mayor-mamdani-says-landlords-cant-secretly-use-ai-images-to-advertise-properties/) ⭐️ 6.0/10

纽约市长佐兰·马姆达尼宣布一项政策，要求房东在出租房源广告中披露是否使用了 AI 生成或修改的图片，这是更广泛的住房改革方案的一部分。 该法规旨在打击“房屋钓鱼”——即用 AI 布置的照片歪曲房间大小和布局来误导租客——并为房地产广告中的 AI 透明度树立先例，可能影响其他城市。 该政策是“租房欺诈报告”的一部分，还包括承认租户工会和加强对疏忽房东的执法。它并未完全禁止 AI 图片，而是要求明确披露，类似于英国的广告标准。

hackernews · gnabgib · 7月18日 22:13 · [社区讨论](https://news.ycombinator.com/item?id=48962983)

**背景**: AI 生成的“虚拟布置”在房地产广告中已很常见，软件会添加家具并改变房间尺寸，使房产看起来更大或更吸引人。这种做法可能误导潜在租客，他们后来发现实际单元与图片不符。纽约市的举措紧随对广告中 AI 使用的日益关注，并与英国现有规则类似。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nyc.gov/mayors-office/news/2026/07/mayor-mamdani-releases--rental-ripoff-report---outlining-new-act">Mayor Mamdani Releases "Rental Ripoff Report," Outlining New ...</a></li>
<li><a href="https://www.theverge.com/policy/966706/new-york-rental-ai-disclosure-policies">New York City is cracking down on AI real estate listings ...</a></li>
<li><a href="https://www.ibtimes.co.uk/nyc-targets-housefishing-ai-disclosure-rules-1809133">What Is 'Housefishing'? Mamdani's New Plan Targets Misleading ...</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些人称赞披露要求是必要的消费者保护措施，而另一些人则认为这可能面临第一修正案的法律挑战。少数人指出英国已有类似的标注规则，并建议将 AI 披露扩展到赌博和招聘等其他领域。

**标签**: `#AI regulation`, `#real estate`, `#advertising`, `#ethics`, `#New York`

---

<a id="item-13"></a>
## [指南：用闲置 Mac 作为 Claude Code 代理](https://ykdojo.github.io/claude-controls-mac/) ⭐️ 6.0/10

一篇逐步指南已发布，展示如何设置闲置 Mac 让 Claude Code 远程控制，从而在专用硬件上实现 AI 驱动的自动化。 这种方法提供了一种在隔离硬件上运行 AI 代理的实用方式，降低系统损坏风险，并能在不影响主机器的情况下实现持续自动化。 该指南涵盖硬件要求、网络配置和 Claude Code 设置；社区评论建议使用基于 libvirt 的虚拟机等替代方案以实现更快的恢复。

hackernews · ykev · 7月18日 16:12 · [社区讨论](https://news.ycombinator.com/item?id=48959392)

**背景**: Claude Code 是 Anthropic 的代理式编码工具，可以编辑文件、运行命令并与系统交互。在闲置 Mac 上运行它可提供隔离性和持续可用性，适用于测试或家庭自动化等任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent , Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了替代隔离方法，有人分享了用于快速重新安装虚拟机的 libvirt 脚本。其他人分享了 Home Bridge 集成等用例，而一些人质疑专用硬件相对于虚拟化的必要性。

**标签**: `#AI agents`, `#Claude Code`, `#macOS`, `#automation`, `#virtualization`

---