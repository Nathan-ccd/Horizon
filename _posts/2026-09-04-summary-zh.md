---
layout: default
title: "Horizon Summary: 2026-09-04 (ZH)"
date: 2026-09-04
lang: zh
---

> 从 14 条内容中筛选出 11 条重要资讯。

---

1. [OpenAI 发布 GPT-6 Astra，ARC-AGI-3 得分近乎完美](#item-1) ⭐️ 10.0/10
2. [Verisign 提议终止三级 .name 域名](#item-2) ⭐️ 8.0/10
3. [用 LLM 读取 68000 汇编，将 1993 年 Amiga 游戏移植到 Godot](#item-3) ⭐️ 8.0/10
4. [Audacity 4.0 发布，采用 Qt6 界面与全新剪辑功能](#item-4) ⭐️ 8.0/10
5. [Qwen 3.8 27B 在 Cerebras 上达到 1500 tok/s，但速率限制和成本引发批评](#item-5) ⭐️ 7.0/10
6. [人工海狸坝将银鲑存活率从 8%提升至 60%](#item-6) ⭐️ 7.0/10
7. [K2 Horizon：六个完全开放模型，社区反响不一](#item-7) ⭐️ 7.0/10
8. [用仿真训练的 JEPA 世界模型为 LLM 提供物理基础](#item-8) ⭐️ 7.0/10
9. [任何曾经活着的人：从历史中随机抽取的生命](#item-9) ⭐️ 6.0/10
10. [Mol-JEPA：基于 JEPA 的多模态分子基础模型](#item-10) ⭐️ 6.0/10
11. [AAAI-27 因微小摘要修改遭拒引发担忧](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 发布 GPT-6 Astra，ARC-AGI-3 得分近乎完美](https://openai.com/index/gpt-6-astra/) ⭐️ 10.0/10

OpenAI 发布了新前沿 AI 模型 GPT-6 Astra，在 ARC-AGI-3 基准测试中取得 99.9%的得分，并在编码和逆向工程任务上取得显著进步。该模型在 Artificial Analysis Coding Agent Index 和 SRE-Bench 上也表现出色，单次尝试解决了 88.0%的逆向工程任务。 GPT-6 Astra 代表了 AI 发展的一个重要里程碑，推动了推理和智能体能力的边界。其在 ARC-AGI-3 上近乎完美的表现表明向通用人工智能迈进，而编码和逆向工程方面的改进可能对软件开发和网络安全产生广泛影响。 该模型在 SRE-Bench 上进行了测试，该基准衡量在没有源代码的情况下对软件二进制文件进行逆向工程的能力，单次尝试解决了 88.0%的任务，四次尝试内解决了 99.2%，而 GPT-5.6 Sol 分别为 55.9%和 68.7%。OpenAI 还发布了部署安全系统卡，社区讨论中对基准测试方法表示担忧，特别是使用响应 API harness 可能影响可比性。

hackernews · kibae · 9月3日 18:41 · [社区讨论](https://news.ycombinator.com/item?id=49554643)

**背景**: ARC-AGI-3 是一个交互式推理基准，旨在衡量 AI 智能体的人类智能水平，要求它们探索新环境并推断目标。Artificial Analysis Coding Agent Index 通过多个基准评估编码智能体的性能。SRE-Bench 等逆向工程基准测试 AI 是否能在没有源代码的情况下理解二进制代码，这对网络安全和软件分析至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC-AGI-3</a></li>
<li><a href="https://arxiv.org/abs/2603.24621">[2603.24621] ARC-AGI-3: A New Challenge for Frontier Agentic Intelligence</a></li>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 ARC-AGI-3 评分卡表示怀疑，指出用于 GPT-6 Astra 的 harness 可能相对于 GPT-5.6 Sol 等先前模型夸大分数。一些用户质疑这些改进是否真正达到 AGI 水平，因为其他基准仅显示适度提升。还有人呼吁 OpenAI 开源其模型，鉴于其逆向工程能力。

**标签**: `#AI`, `#OpenAI`, `#GPT-6`, `#machine learning`, `#benchmarks`

---

<a id="item-2"></a>
## [Verisign 提议终止三级 .name 域名](https://neil.fraser.name/news/2026/09/03/) ⭐️ 8.0/10

Verisign 提议终止三级 .name 域名（如 john.smith.name）及相关的电子邮件转发服务，这将影响现有注册。该提案于 2026 年 5 月报道，终止后相应的二级域名（如 smith.name）将被释放。 这一政策变化威胁到现有域名注册的稳定性，并可能助长域名抢注，与 ICANN 确保唯一标识符系统稳定安全运行的使命相悖。它影响到数千名多年来依赖这些域名的注册者，并引发了对注册机构权力和 ICANN 监管的更广泛担忧。 该提案专门针对三级 .name 域名，而非整个 .name 顶级域，现有的二级域名（如 dvt.name）不受影响。Verisign 计划停止销售三级域名和电子邮件转发服务，但提案未提及保留二级域名以防止抢注。

hackernews · pavel_lishin · 9月3日 14:54 · [社区讨论](https://news.ycombinator.com/item?id=49550772)

**背景**: .name 顶级域于 2001 年推出，作为个人姓名的命名空间，允许在二级和三级注册，如 john.smith.name。三级域名与电子邮件转发捆绑，但这种结构一直因其混乱和利用率低而受到批评。ICANN 负责监督域名政策，Verisign 运营 .name 注册局，因此任何变更都需要与 ICANN 协调。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://domainincite.com/31699-verisign-to-delete-name-3lds-and-email-addresses">Verisign to delete .name 3LDs and email addresses - Domain Incite</a></li>
<li><a href="https://support.opensrs.com/support/solutions/articles/201000063568--name-domain-policies">A Domain Resellers Guide to . NAME Domain Policies : OpenSRS...</a></li>
<li><a href="https://support.enom.com/support/solutions/articles/201000127176--name-domain-policies">NAME Domain Policies : Enom Customer Support</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了震惊和沮丧，有些人指出他们拥有此类域名已超过十年。许多人认为终止现有注册是不公平的，且与 ICANN 的稳定性使命相悖，而另一些人建议停止新注册但尊重现有注册更为合适。一些人还强调，一旦二级域名被释放，存在域名抢注的风险，并将其与关于租赁域名和注册局权力的更广泛担忧联系起来。

**标签**: `#ICANN`, `#domain names`, `#policy`, `#internet governance`, `#Verisign`

---

<a id="item-3"></a>
## [用 LLM 读取 68000 汇编，将 1993 年 Amiga 游戏移植到 Godot](https://babyloniantwins.com/blog/porting-a-1993-amiga-game-to-godot/) ⭐️ 8.0/10

一位开发者成功地将他们 1993 年用 MC68000 汇编编写的 Amiga 游戏，通过 LLM（Claude）反汇编和翻译代码，移植到了 Godot 引擎。整个过程花了一个晚上，后续几个周末用于打磨，并且原版游戏已免费发布。 这展示了 LLM 在逆向工程和移植遗留汇编代码方面的新颖且实用的应用，可能降低经典游戏保存和现代化的门槛。它凸显了 AI 处理复杂低级编程任务的能力日益增强，这可能对游戏保存和软件迁移工作产生影响。 开发者使用 vasm 在 Mac 上汇编代码，并反复迭代直到二进制与原始版本字节一致，除了 108 字节的差异，这归因于原始 AsmOne 汇编器在游戏运行后保存了内存快照。开发者还将 33 年的个人记忆、笔记和 git 仓库提供给 LLM，以辅助移植过程。

hackernews · rabahs · 9月3日 14:28 · [社区讨论](https://news.ycombinator.com/item?id=49550375)

**背景**: Amiga 是 20 世纪 80 年代末和 90 年代初流行的个人电脑，以其先进的图形和声音而闻名。游戏通常用 MC68000 汇编编写以获得性能。Godot 是一个现代开源游戏引擎，支持多种平台。像 Claude 这样的 LLM 可以分析和翻译代码，包括汇编这种复杂的低级语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Godot_(game_engine)">Godot (game engine)</a></li>
<li><a href="https://godotengine.org/">Godot Engine - Free and open source 2D and 3D game engine</a></li>
<li><a href="https://en.wikipedia.org/wiki/Amiga_programming_languages">Amiga programming languages - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对原始的汇编工作表示钦佩，并分享了类似经历。一位用户成功使用 Claude 将 ZX81 内存转储转换为 Go，其他人则对移植旧的 Atari 游戏表示兴趣。一些人询问调试过程的更多细节，并建议为类似的移植导出工程指南。

**标签**: `#LLM`, `#reverse engineering`, `#game development`, `#legacy code`, `#Godot`

---

<a id="item-4"></a>
## [Audacity 4.0 发布，采用 Qt6 界面与全新剪辑功能](https://github.com/audacity/audacity/releases/tag/Audacity-4.0.0) ⭐️ 8.0/10

Audacity 4.0 已正式发布，其重大 UI 改版将框架从 wxWidgets 迁移到 Qt6。此次更新引入了新的剪辑编辑模型、专用的分割工具以及新的项目文件格式。 这是最广泛使用的开源音频编辑器多年来首次重大版本更新，Qt6 迁移有望带来更好的性能和更现代、一致的界面。新的剪辑编辑工作流可能显著提升音乐人和播客制作者的易用性，同时也使 Audacity 与 Muse Group 旗下 MuseScore 等其他工具保持一致。 新界面复用了 MuseScore Studio 4 的架构基础，Audacity 4.0 还包含 Windows ASIO 支持和旧项目导入功能。然而，项目文件格式已更改，部分用户对 audio.com 服务的整合表示担忧。

hackernews · ClydeN · 9月3日 10:53 · [社区讨论](https://news.ycombinator.com/item?id=49548395)

**背景**: Audacity 是一款免费开源的数字音频编辑器，支持 Windows、macOS 和 Linux。二十多年来，它一直是录音和音频编辑的主流工具，但其旧界面依赖老旧的 wxWidgets 工具包。迁移到 Qt6 是 Muse Group（2021 年收购 Audacity）为现代化该应用并与其他产品统一开发所做的更广泛努力的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Audacity-4.0-Released">Audacity 4.0 Audio Editor Released With Qt6 Based UI - Phoronix</a></li>
<li><a href="https://www.omgubuntu.co.uk/2026/09/audacity-4-released">Audacity 4 . 0 released with brand- new look, clip editing features</a></li>
<li><a href="https://www.linuxcompatible.org/story/audacity-40-beta-4-ships-with-qt6-ui-windows-asio-and-legacy-imports">Audacity 4.0 Beta 4 Ships With Qt6 UI, Windows ASIO, and Legacy Imports</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些用户称赞界面更简洁、修复了 bug，而另一些用户则感叹长期存在的技术问题（如 JACK/Pipewire 集成）仍未解决。还有用户提及过去的遥测争议及由此产生的分支（Tenacity、Sneedacity），表明信任问题依然存在。

**标签**: `#Audacity`, `#audio editing`, `#open source`, `#software release`, `#Qt6`

---

<a id="item-5"></a>
## [Qwen 3.8 27B 在 Cerebras 上达到 1500 tok/s，但速率限制和成本引发批评](https://inference-docs.cerebras.ai/models/overview) ⭐️ 7.0/10

Qwen 3.8 27B 现已在 Cerebras 推理平台上可用，每秒可处理高达 1500 个 token。然而，用户反映在编程任务中存在严格的速率限制和高昂的成本。 此次部署展示了 Cerebras 对热门模型的超快推理能力，可能推动实时 AI 应用的发展。然而，速率限制和成本等实际限制可能会阻碍其在繁重编程工作负载中的采用，影响开发者和企业。 公共端点的速率限制为每分钟 150k token（TPM），且缓存 token 也计入该限制，导致用户迅速耗尽配额并产生费用。例如，一位用户在 90 秒内达到限制，花费 1.10 美元，而类似任务在 DeepSeek-V4-Flash 上仅花费 0.024 美元并在 172 秒内完成。

hackernews · altertable · 9月3日 18:32 · [社区讨论](https://news.ycombinator.com/item?id=49554520)

**背景**: Cerebras Inference 是一项使用晶圆级引擎提供极高 token 生成速度的服务，此前在 Llama 3.1 8B 上达到了每秒 1800 token。Qwen 3.8 27B 是基于 Qwen 3.5 架构的密集视觉语言模型，专为编程、专业工作和智能体任务设计。该模型也可在 Hugging Face 和 Ollama 等其他平台上使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cerebras.ai/blog/introducing-cerebras-inference-ai-at-instant-speed">Introducing Cerebras Inference: AI at Instant Speed - Cerebras</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen / Qwen 3 . 8 - 27 B · Hugging Face</a></li>
<li><a href="https://ollama.com/library/qwen3.8:27b">qwen 3 . 8 : 27 b</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人称赞输出速度，但批评速率限制和成本，指出缓存 token 计入限制。另一些人建议使用本地模型（如 RTX 5090 上的 ninfer，约 200 tok/s），或希望该模型能通过 OpenRouter 提供。一位用户在编程任务中测试发现，输入处理并未更快，但输出非常快。

**标签**: `#AI inference`, `#Qwen`, `#Cerebras`, `#LLM deployment`, `#performance`

---

<a id="item-6"></a>
## [人工海狸坝将银鲑存活率从 8%提升至 60%](https://www.discoverwildlife.com/animal-facts/artificial-beaver-dams-california) ⭐️ 7.0/10

在加利福尼亚州，安装人工海狸坝将幼年银鲑的存活率从 8%大幅提升至 60%。这些坝创造了约 9000 平方米的新栖息地，能够支持超过 8500 条幼鲑。 这一结果凸显了一种有前景且成本低廉的修复技术，有助于在退化的溪流中恢复濒危鲑鱼种群。同时，它也强调了海狸的生态重要性，并为全球栖息地修复提供了可扩展的解决方案。 这些人工坝被称为海狸坝模拟物（BDAs），模仿天然海狸坝。有趣的是，筑坝后水温反而下降，可能是因为水更多地渗透到地下，与较冷的地下温度进行热交换。

hackernews · speckx · 9月3日 16:21 · [社区讨论](https://news.ycombinator.com/item?id=49552572)

**背景**: 银鲑是溯河洄游鱼类，在淡水溪流中产卵，然后迁徙到海洋。幼年银鲑需要凉爽、含氧量高的水以及具有深潭和遮蔽物的复杂栖息地才能度过第一年。历史上，海狸通过筑坝创造了这样的栖息地，但过度捕猎和栖息地丧失导致其数量减少。人工海狸坝旨在复制这些益处，而不依赖活体海狸。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.discoverwildlife.com/animal-facts/artificial-beaver-dams-california">People started building artificial beaver dams in California. Now something "mind blowing" is happening | Discover Wildlife</a></li>
<li><a href="https://en.wikipedia.org/wiki/Beaver_dam">Beaver dam - Wikipedia</a></li>
<li><a href="https://www.worldwildlife.org/news/stories/artificial-beaver-dams-help-montana-ranchers-restore-streams-and-protect-wildlife/">Artificial Beaver Dams Aid Montana Streams | WWF</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了热情和额外资源，例如一本关于不列颠哥伦比亚省一位自耕农修复被炸毁水坝的书。有人好奇为什么不直接重新引入活海狸，还有人质疑对生态系统和食物来源可能产生的连锁反应。

**标签**: `#ecology`, `#conservation`, `#wildlife`, `#restoration`, `#salmon`

---

<a id="item-7"></a>
## [K2 Horizon：六个完全开放模型，社区反响不一](https://ifm.ai/blog/k2/) ⭐️ 7.0/10

IFM 发布了 K2 Horizon，这是一个包含六个完全开放模型的系列，参数规模从 0.9B 到 375B 不等，声称在各规模上达到前沿性能。该发布包括全部源代码、训练数据和流程，定位为迄今为止最全面的开放模型发布之一。 此次发布对 AI 社区意义重大，因为它推动了开源 AI 的边界，可能挑战封闭模型，并为研究人员提供完全透明性。然而，社区对性能声明和编码可靠性的怀疑可能影响其采用和信任。 该系列包括 0.9B、3.7B、7B、32B、36B-A4B（MoVA）和 375B-A23B 等模型，声称在其规模类别中达到世界领先性能。值得注意的是，375B 模型支持 512K 上下文，发布强调完全开放，包括训练数据和代码。

hackernews · karimf · 9月3日 15:36 · [社区讨论](https://news.ycombinator.com/item?id=49551760)

**背景**: 开源 AI 模型作为 GPT-4 等封闭模型的替代品越来越受欢迎，提供透明性和定制性。完全开放的模型（包括训练数据和代码）很少见；Nvidia 的 Nemotron 是另一个突出的例子。K2 Horizon 旨在通过发布跨规模的完整系列来树立新标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ifm.ai/blog/k2/">Introducing K 2 Horizon : Frontier Performance , Radically Open</a></li>
<li><a href="https://artificialanalysis.ai/models/k2-horizon-375b-a23b">K 2 Horizon 375B A23B - Intelligence, Performance ... | Artificial Analysis</a></li>
<li><a href="https://huggingface.co/IFM/K2-Horizon-MoVA-36B-A4B-GGUF">IFM/ K 2 - Horizon -MoVA-36B-A4B-GGUF · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对完全开放模型的支持，但质疑性能基准，一位用户指出 32B 模型落后于 Qwen3.8 27B。另一位用户报告了 3.7B 模型的编码可靠性问题，包括幻觉 API，而其他人则开玩笑说模型疲劳和图表可读性差。

**标签**: `#open-source`, `#AI`, `#models`, `#machine-learning`, `#LLM`

---

<a id="item-8"></a>
## [用仿真训练的 JEPA 世界模型为 LLM 提供物理基础](https://www.reddit.com/r/MachineLearning/comments/1w69gvd/grounding_llms_with_jepabased_world_models/) ⭐️ 7.0/10

一位 Reddit 用户提出在物理模拟器（如 MuJoCo）中训练 JEPA 风格的世界模型，预测未来状态的表征，然后将这些有物理基础的表征作为条件信号附加到 LLM 上。这种组合旨在赋予 LLM 真正的物理直觉，解决“玛丽房间”问题。 这一想法可能解决 LLM 的一个根本局限：缺乏对物理现实的有基础的理解。如果成功，它可能使物理任务的学习和推理更高效，可能惠及机器人、具身 AI 以及其他需要物理常识的应用。 该提议建议使用 JEPA 风格的预测（预测未来状态的表征而非像素或 token）来创建一个编码物理原理（如物体恒存性和动量）的嵌入空间。作者指出 V-JEPA 和 DreamerV3 是相关工作，但具体与 LLM 结合的组合似乎尚未被探索。

reddit · r/MachineLearning · /u/Full_Promotion4522 · 9月3日 14:45

**背景**: JEPA（联合嵌入预测架构）是 Meta AI 开发的一系列模型，通过在抽象嵌入空间中预测未来状态来学习表征，而不是重建原始输入。“玛丽房间”思想实验强调了了解某事物的事实与拥有直接体验知识之间的区别。像 MuJoCo 这样的物理模拟器提供了受控环境，可以在其中训练此类世界模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/world-models-jepa-next-evolution-ai-architecture-dmitry-shapiro-1xcsc">World Models and JEPA : The Next Evolution in AI Architecture</a></li>
<li><a href="https://www.turingpost.com/p/jepamap">All JEPA Models : 14 Milestones From I- JEPA to ThinkJEPA</a></li>
<li><a href="https://en.wikipedia.org/wiki/MuJoCo">MuJoCo - Wikipedia</a></li>

</ul>
</details>

**标签**: `#LLM`, `#JEPA`, `#world models`, `#grounding`, `#AI research`

---

<a id="item-9"></a>
## [任何曾经活着的人：从历史中随机抽取的生命](https://anyhumanever.com/) ⭐️ 6.0/10

新网站 anyhumanever.com 从人类历史中随机选择一个人，并利用历史数据和 AI 生成其生活叙述。该项目强调了大多数出生发生在近代的统计可能性。 这一创意可视化激发了公众对人口统计历史和 AI 叙事能力的兴趣，但也引发了对数据准确性以及将 AI 生成的传记呈现为事实的伦理问题的担忧。它展示了将 AI 用于历史教育的潜力和陷阱。 该网站使用概率分布来选择出生年份，但社区成员指出，随机选择可能无法准确反映真实分布，因为在测试中大多数抽取来自古代。生成的叙述包含具体统计数据（如结婚率、死亡率）并附有引用，但部分引用不完整或链接到无关来源，且 AI 可能虚构细节。

hackernews · thinkingemote · 9月3日 14:51 · [社区讨论](https://news.ycombinator.com/item?id=49550698)

**背景**: 该项目利用历史人口数据和 AI 语言模型来创建个性化的生活故事。它基于这样一个概念：由于人口增长，大多数曾经生活过的人都是近代出生的，这一事实令许多人惊讶。该网站旨在通过关注个体的生活而非广泛事件，使历史更具亲和力。

**社区讨论**: 社区评论既表达了赞赏也表达了怀疑。一些用户欣赏其情感冲击力以及在角色扮演游戏中的创意用途，而另一些用户则指出出生年份分布中的统计不准确以及生成事实中的逻辑不一致。还有人担心引用的可靠性和 AI 幻觉的可能性。

**标签**: `#data visualization`, `#history`, `#AI`, `#demographics`, `#web app`

---

<a id="item-10"></a>
## [Mol-JEPA：基于 JEPA 的多模态分子基础模型](https://www.reddit.com/r/MachineLearning/comments/1w6i8pr/moljepa_multimodal_molecular_foundation_model_r/) ⭐️ 6.0/10

一位研究者分享了一篇论文，介绍了 Mol-JEPA，这是一个利用联合嵌入预测架构（JEPA）的多模态分子基础模型。该模型通过一个摘要网站展示，作者邀请反馈，并指出性能仍有待提升。 这项工作将 Yann LeCun 倡导的 JEPA 范式应用于分子建模，可能提供一种无需像素级或标记级预测的学习表示的新方法。如果成功，它可能通过更高效地从分子结构和相关数据中学习，推动药物发现和材料科学的发展。 该模型是多模态的，意味着它整合了多种类型的分子数据，如结构和文本描述，类似于 MolFM 和 MoMu 等其他多模态分子基础模型。作者承认当前性能并非最优，并计划进一步改进。

reddit · r/MachineLearning · /u/TerribleAntelope9348 · 9月3日 19:56

**背景**: JEPA（联合嵌入预测架构）是一种自监督学习方法，由 Yann LeCun 提出，它在抽象表示空间中进行预测，而不是在输入空间中进行预测。多模态分子基础模型旨在从分子图和相关文本或知识图谱中学习联合表示，从而支持性质预测和分子生成等任务。Mol-JEPA 结合了这些思想，可能为分子表示学习提供一种新颖的架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rohitbandaru.github.io/blog/JEPA-Deep-Dive/">Deep Dive into Yann LeCun’s JEPA | Rohit Bandaru</a></li>
<li><a href="https://arxiv.org/abs/2307.09484">[2307.09484] MolFM: A Multimodal Molecular Foundation Model</a></li>
<li><a href="https://hunterheidenreich.com/notes/chemistry/molecular-representations/multimodal/momu-molecular-multimodal-foundation/">MoMu: Bridging Molecular Graphs and Natural Language</a></li>

</ul>
</details>

**标签**: `#JEPA`, `#molecular modeling`, `#foundation model`, `#multimodal learning`, `#machine learning`

---

<a id="item-11"></a>
## [AAAI-27 因微小摘要修改遭拒引发担忧](https://www.reddit.com/r/MachineLearning/comments/1w6kcp6/aaai27_desk_rejection_over_incredibly_minor/) ⭐️ 6.0/10

一名研究人员报告称，因在摘要注册截止日期和全文截止日期之间对标题或摘要进行了微小修改，而收到 AAAI-27 的桌面拒稿。拒稿通知称该决定为最终决定，不接受申诉。 这一事件引发了对 AAAI-27 政策执行一致性和公平性的担忧，可能影响许多可能无意中违反模糊指南的研究人员。它凸显了在 AI 研究社区中，会议政策需要更清晰的沟通和一致的应用。 该研究人员强调，提交内容几乎完全相同，修改非常微小，这与政策中关于禁止实质性变更的警告不符。拒稿通知明确表示不接受申诉，使受影响的作者没有补救途径。

reddit · r/MachineLearning · /u/Dansilly · 9月3日 21:12

**背景**: AAAI-27 是第 41 届 AAAI 人工智能会议，计划于 2027 年 2 月 16 日至 23 日在蒙特利尔举行。会议政策通常允许在注册后对标题和摘要进行微小编辑，但禁止改变所描述研究的实质性变更；桌面拒稿是执行此类规则的常见机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aaai.org/conference/aaai/aaai-27/">AAAI - 27 - AAAI</a></li>
<li><a href="https://aaai.org/aaai-publications/aaai-publication-policies-guidelines/">AAAI Publication Policies & Guidelines - AAAI</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子中可能包含其他研究人员分享类似经历或讨论政策模糊性的评论。由于没有具体评论，总体情绪似乎是对修改规则严格且看似不一致的执行表示担忧。

**标签**: `#AAAI`, `#conference policy`, `#desk rejection`, `#academic publishing`, `#machine learning`

---