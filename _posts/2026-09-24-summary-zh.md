---
layout: default
title: "Horizon Summary: 2026-09-24 (ZH)"
date: 2026-09-24
lang: zh
---

> 从 22 条内容中筛选出 12 条重要资讯。

---

1. [高通为骁龙 X2 系列带来 Linux 支持](#item-1) ⭐️ 8.0/10
2. [Claude 发现具有类 CRISPR 重复序列的新型酶系统](#item-2) ⭐️ 8.0/10
3. [Radicle 披露网络协议严重漏洞：节点间流量未加密](#item-3) ⭐️ 8.0/10
4. [Meta 发布新款 VR 眼镜，隐私争议引发社区反弹](#item-4) ⭐️ 7.0/10
5. [VSCode 的 SSH 代理架构：强大却令人意外](#item-5) ⭐️ 7.0/10
6. [意大利议会投票决定重返核能](#item-6) ⭐️ 7.0/10
7. [谷歌发布 Gemini 3.8 文本转语音，支持 30 秒声音克隆](#item-7) ⭐️ 7.0/10
8. [文章称 LLM token 成本或将低于 grep](#item-8) ⭐️ 7.0/10
9. [修复波托贝洛警察局的钟表](#item-9) ⭐️ 6.0/10
10. [Raymond Chen 追溯 Windows 滚动条快捷操作的历史](#item-10) ⭐️ 6.0/10
11. [Reddit 帖子称 Jev 只是零样本分类器的重新包装，并非新 AI 范式](#item-11) ⭐️ 6.0/10
12. [MiMo-V3 采用 HySparse2 混合稀疏注意力架构](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [高通为骁龙 X2 系列带来 Linux 支持](https://www.qualcomm.com/news/onq/2026/09/snapdragon-summit-agentic-ai-pcs-linux) ⭐️ 8.0/10

高通在骁龙峰会上宣布，骁龙 X2 系列将获得 Linux 支持，公司正将 Hexagon NPU 和 Adreno GPU 的核心驱动上游到 Linux 主线内核。社区成员指出，OpenBSD 开发者 Tobias Heider 已提交了针对骁龙 X2 Elite 笔记本的早期 OpenBSD/arm64 支持代码，并且 Ubuntu 已被演示可在 ARM EL2（KVM）模式下运行。 这是 ARM 笔记本开源硬件支持的重要一步，因为此前的骁龙 X Elite 的 Linux 支持基本未能兑现，导致许多用户只能继续使用 Windows。如果高通能够兑现承诺，X2 系列有望成为笔记本形态下最有实力、可运行 Linux 的苹果 M 系列竞争者，为消费者提供英特尔和 AMD 机型之外的真正替代选择。 高通明确表示正在上游 Hexagon NPU 和 Adreno GPU 驱动，而不是像 Chromebook 那样提供半专有方案，这将使各发行版和开发者能够直接支持该硬件。早期社区报告显示，在 OpenBSD 下 HP EliteBook X G2q 的 USB、键盘和触控板已在 ACPI 模式下工作，而 ARM EL2 支持意味着 KVM 虚拟化应当可用，这一点与之前几代产品不同。

hackernews · aaronday · 9月23日 22:38 · [社区讨论](https://news.ycombinator.com/item?id=49823582)

**背景**: 骁龙 X2 系列是高通面向 Windows 笔记本的第二代 ARM 处理器家族，接替骁龙 X Elite 和 X Plus，它将高通的 Oryon CPU 核心与 Adreno 集成显卡以及算力最高达 45 TOPS 的 Hexagon NPU 结合在一起，用于端侧 AI 任务。ARM 笔记本上的 Linux 支持历来参差不齐，因为 GPU、NPU 和电源管理驱动必须先被编写并合入 Linux 主线内核，各发行版才能妥善支持某款设备。因此，将这些驱动上游化是一台笔记本能够开箱即用运行 Linux 的关键前提。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/List_of_Qualcomm_Snapdragon_systems_on_chips">List of Qualcomm Snapdragon systems on chips - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/Snapdragon_X2_series">Snapdragon X2 series</a></li>
<li><a href="https://www.qualcomm.com/processors/hexagon">Qualcomm Hexagon NPU | Snapdragon NPU Details</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍欢迎这一消息，有人指出高通的 X2 芯片是笔记本领域最接近苹果 M 系列的竞争者，并且优于英特尔和 AMD 的最强产品。其他人强调，真正上游驱动非常重要，因为初代 X Elite 承诺的 Linux 支持从未兑现；还有用户引用 Geekbench 结果称，骁龙 X2 Elite Extreme X2E-96-100 与苹果 M5 Pro 差距不大。

**标签**: `#Linux`, `#Qualcomm`, `#Snapdragon`, `#ARM`, `#Open Source`

---

<a id="item-2"></a>
## [Claude 发现具有类 CRISPR 重复序列的新型酶系统](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system) ⭐️ 8.0/10

Anthropic 宣布，其 AI 模型 Claude 在新建的生命科学研究实验室中作为智能体工作时，发现了一个此前未知的酶系统，其基因旁边有一段类似 CRISPR 的长重复 DNA 序列。该发现来自实验室的早期成果，该酶系统的功能目前仍不清楚。 这是 AI 智能体推动基因组学科学发现的一个显著案例，并在 Hacker News 上引发了关于 AI 主导研究的意义以及 Anthropic 大举进军生物医学的广泛讨论。它可能影响 AI 在生命科学中的应用方式，并引发关于 AI 在生物工程中双重用途风险的疑问。 社区成员指出，该发现围绕一种已知的类逆转录子（retron-like）逆转录酶展开，Claude 识别出的是其周围此前未描述的基因组排列，而非一种全新的酶。该酶系统的功能仍未知，此类系统的治疗应用在很大程度上受递送难题的限制。

hackernews · raahelb · 9月23日 18:06 · [社区讨论](https://news.ycombinator.com/item?id=49820134)

**背景**: CRISPR 是存在于细菌和古菌中的一类 DNA 序列家族，帮助它们抵御病毒，并已被改造为强大的基因编辑工具。Anthropic 最近通过新建研究实验室和 Claude Science 等工具扩展到生命科学领域，旨在利用 AI 智能体加速生物医学发现。Claude 发现的酶系统包含一种逆转录酶（将 RNA 转换为 DNA 的酶）以及一段类 CRISPR 重复序列阵列，其作用尚不清楚。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-discovers-novel-enzyme-system">Claude discovers a novel enzyme system with CRISPR-like repeats - Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/CRISPR">CRISPR - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/news/claude-science-ai-workbench">Claude Science, an AI workbench for scientists - Anthropic</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者大多对该发现的新颖性持怀疑态度，有人指出它围绕一种已知的类逆转录子逆转录酶展开，并呼吁进行冷静的表述。其他人则对通过智能体记录重温 AI 发现感到兴奋，质疑 Anthropic 在禁止将 Claude 用于生物工程与自身发现之间的矛盾立场，并争论未来科学突破将由 AI 智能体还是人机协作推动。

**标签**: `#AI`, `#CRISPR`, `#bioengineering`, `#scientific discovery`, `#Anthropic`

---

<a id="item-3"></a>
## [Radicle 披露网络协议严重漏洞：节点间流量未加密](https://radicle.dev/2026/09/23/disclosure-of-vulnerability-in-network-protocol) ⭐️ 8.0/10

Radicle 披露了一个影响其迄今所有已发布版本的关键漏洞：节点之间的网络流量既未加密也未认证。该漏洞由 Konstantinos Maninakis 于 2026 年 6 月 24 日报告，但公开公告直到约三个月后的 2026 年 9 月 23 日才发布，且官方给出的唯一建议是在安全更新发布前停止通过网络使用私有仓库。 这一披露动摇了人们对 Radicle 核心卖点的信心——即加密身份与去中心化、抗审查的代码协作，因为私有仓库数据可能在传输过程中被暴露或篡改。它也引发了人们对点对点开发者基础设施安全实践的更广泛质疑：用户可能误以为存在端到端保护，而实际上并没有。 Radicle 迄今发布的所有版本均受影响，官方建议的变通方案只是停止通过网络使用私有仓库，并假定它们可能已被攻破。跨节点流量缺乏加密和认证属于根本性的设计缺陷，而非细小的实现漏洞，且公告中并未给出修复版本的具体发布时间。

hackernews · lostmsu · 9月23日 15:23 · [社区讨论](https://news.ycombinator.com/item?id=49817524)

**背景**: Radicle 是一个基于 Git 构建的开源点对点代码协作栈，目标是成为“主权锻造厂”（sovereign forge），让用户运行自己的节点，而不必依赖 GitHub 这类中心化托管平台。其网络层使用名为 Radicle Link 的 gossip 协议在对等节点之间转发消息、发现仓库并复制数据，并通过基于密钥的加密身份系统扩展 Git。由于整个设计都依赖加密身份和去中心化，用户自然会期望节点之间的通信同样受到保护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://radicle.dev/2026/09/23/disclosure-of-vulnerability-in-network-protocol.html">Disclosure of Vulnerability in the Network Protocol - Radicle</a></li>
<li><a href="https://radicle.dev/guides/protocol">Radicle Protocol Guide</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论者批评声强烈，难以理解一个围绕加密身份和去中心化构建的项目竟然从未验证过载荷是否加密。许多人强调 6 月报告到 9 月披露之间长达三个月的延迟，认为“停止使用私有仓库”的变通方案远远不够，并表示这一事件印证了他们此前对 Radicle 安全成熟度和可信度的怀疑。

**标签**: `#security`, `#vulnerability`, `#decentralized`, `#radicle`, `#network-protocol`

---

<a id="item-4"></a>
## [Meta 发布新款 VR 眼镜，隐私争议引发社区反弹](https://www.meta.com/vr-glasses/) ⭐️ 7.0/10

Meta 在其官方产品页面上发布了一款新的 VR 眼镜，将其定位为比苹果 Vision Pro 更轻、更便宜的替代品。公告本身几乎没有技术细节，而社区的回应几乎完全集中在 Meta 的账户和隐私做法上，而非硬件本身。 这次发布凸显了 XR 市场中日益加剧的矛盾：即使硬件广受好评，也可能因公司在账户政策上对用户不友好的声誉而受损。对于依赖大规模普及的 Meta VR 业务而言，围绕强制 Meta 账户、身份验证和突然封号等问题的持续不信任，可能直接限制其设备的潜在市场。 社区成员指出，这款眼镜的视场角明显偏窄，约为 70 x 66 度，而 Quest 3 约为 103 x 96 度，后者已被部分用户认为过于受限。公告还预告了包括新款 Beat Saber 游戏和《逆转裁判》VR 作品在内的新内容，但目前尚不清楚这些内容是否会登陆 Quest 3 或 PCVR。

hackernews · polymorph1sm · 9月23日 23:47 · [社区讨论](https://news.ycombinator.com/item?id=49824268)

**背景**: Meta 于 2021 年从 Facebook 更名，随后用强制性的 Meta 账户取代了 Oculus 账户，用户需要提供电子邮箱、电话号码和支付信息才能使用 VR 头显。Meta 还因旗下平台上的封号问题屡遭批评，包括一次大规模 Threads 封号事件，导致用户无法登录 Facebook、Messenger 及关联设备。这些账户政策正是许多用户表示即使觉得硬件不错也会避开 Meta 产品的主要原因。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reddit.com/r/cybersecurity/comments/1rjmcbz/metas_ai_smart_glasses_and_data_privacy_concerns/">Meta's AI smart glasses and data privacy concerns: Workers say “we see everything” : r/cybersecurity - Reddit</a></li>
<li><a href="https://communityforums.atmeta.com/blog/AnnouncementsBlog/introducing-meta-accounts-a-new-login-for-vr/972079">Introducing Meta Accounts : A New Login for VR | Meta Community...</a></li>
<li><a href="https://support.hegias.com/en/article/meta-account-pairing-with-the-meta-quest-vr-headset-1829zy3/">Meta Account & Pairing with the Meta Quest VR ... | HEGIAS Support</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为硬件看起来不错，有人称其为更轻、更便宜的苹果 Vision Pro 替代品，但主流情绪是对 Meta 的深度不信任。用户提到强制上传身份证件、从 Oculus 账户被迫迁移，以及最近一次大规模 Threads 封号导致其 Portal、Oculus 和眼镜设备变砖，这些都是他们完全避开该产品的理由。多人指出，如果换作其他任何公司，这款设备都会受到热烈欢迎，而 Meta 的声誉如今已成为其最大障碍。

**标签**: `#VR`, `#Meta`, `#hardware`, `#privacy`, `#user-experience`

---

<a id="item-5"></a>
## [VSCode 的 SSH 代理架构：强大却令人意外](https://fly.io/blog/vscode-ssh-wtf/) ⭐️ 7.0/10

Fly.io 的一篇博客文章分析了 VSCode 的 SSH 代理架构，解释了它如何通过 SSH 自举并在远程主机上安装 VS Code Server，再通过隧道建立 WebSocket 连接回本地 VSCode 前端，从而能够遍历文件系统、编辑文件、启动 shell PTY 进程并自我持久化。文章认为这些设计选择既强大又可能令人意外，引发了 86 条评论的讨论。 这很重要，因为 VSCode Remote-SSH 被开发者广泛用于远程开发，理解其代理的能力和安全影响有助于团队在访问控制和部署环境方面做出明智决策。讨论凸显了远程开发工具在便利性与安全性之间的更广泛矛盾。 该代理通过端口转发的 SSH 运行，并建立 WebSocket 连接回本地 VSCode 前端；底层协议可以执行文件系统操作、编辑任意文件、启动 shell PTY 进程并自我持久化。一个关键警告是，虽然远程到本地的方向对某些人来说可以接受，但反方向——即被攻陷的远程主机可能影响本地机器——则令人担忧。

hackernews · Rapzid · 9月23日 21:01 · [社区讨论](https://news.ycombinator.com/item?id=49822555)

**背景**: VSCode 的 SSH 远程开发允许开发者使用本地 VSCode 实例在远程机器上工作，该扩展会在远程操作系统上独立于任何现有 VS Code 安装来安装 VS Code Server。SSH 代理通过 SSH 连接自举服务器，而隧道是功能集的一部分，用于实现端口转发和远程命令执行。这种架构旨在让远程机器成为本地机器的延伸，但它假设远程是开发环境，而非生产服务器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.visualstudio.com/docs/remote/ssh">Remote Development using SSH</a></li>
<li><a href="https://docs.rc.fas.harvard.edu/kb/vscode-remote-development-via-ssh-or-tunnel/">VSCode Remote Development via SSH and Tunnel – FASRC DOCS</a></li>
<li><a href="https://uptrakit.org/docs/end-user/ssh-agent-bootstrap/">SSH Agent Bootstrap — Uptrakit</a></li>

</ul>
</details>

**社区讨论**: 总体情绪褒贬不一：一些评论者认为 SSH 代理对远程开发是天赐之物，所列的缺点实际上是优点，而另一些人则质疑鉴于该工具的用途，为何其行为会令人意外。一个值得注意的担忧是反方向，即被攻陷的远程主机可能对本地机器为所欲为，还有人澄清说将其安装在生产服务器上并感到意外是用户自己的责任。

**标签**: `#VSCode`, `#SSH`, `#remote-development`, `#security`, `#developer-tools`

---

<a id="item-6"></a>
## [意大利议会投票决定重返核能](https://apnews.com/article/italy-nuclear-chernobyl-4891b6b7c7791ae84db6b0bf0f7cf567) ⭐️ 7.0/10

意大利议会投票推翻了切尔诺贝利事故后实施的核能禁令，为未来以小型模块化反应堆（SMR）和其他先进技术为重点的项目建立了监管框架。该立法并未授权建设任何反应堆，而是为未来的项目提案、评估和批准奠定了法律基础。 这一政策转变标志着意大利这个数十年来无核国家的重大逆转，可能重塑其能源结构并减少对化石燃料进口的依赖。这也可能预示着欧洲更广泛地转向核能，将其作为脱碳和能源安全的工具。 该立法侧重于 SMR 和先进反应堆设计，而非传统大型反应堆，但在日益由太阳能主导的电网中，这些反应堆将如何融资仍不明确。批评者指出，SMR 的经济性尚未得到验证，尚无项目证明其能在无补贴情况下实现盈利。

hackernews · geox · 9月23日 17:06 · [社区讨论](https://news.ycombinator.com/item?id=49819221)

**背景**: 意大利在 1987 年切尔诺贝利灾难后不久举行的公投中禁止了核能，其四座现有核电站被关闭。小型模块化反应堆（SMR）是一类电功率低于 300 兆瓦的核裂变反应堆，设计为工厂制造并可灵活部署。先进反应堆技术，如第四代设计，旨在比旧式反应堆提高安全性、效率和燃料利用率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Small_modular_reactor">Small modular reactor - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Generation_IV_reactor">Generation IV reactor - Wikipedia</a></li>
<li><a href="https://www.energy.gov/ne/advanced-small-modular-reactors-smrs">Advanced Small Modular Reactors (SMRs) - Department of Energy</a></li>

</ul>
</details>

**社区讨论**: 评论者对 SMR 的经济性表示怀疑，有人指出没有任何提案能在无补贴情况下实现从部署到退役全生命周期的盈利。一位意大利评论者称赞此次投票是对切尔诺贝利后情绪化决策的理性纠正，而其他人则担心在太阳能主导的电网中为反应堆融资以及该问题被政治化。

**标签**: `#nuclear energy`, `#Italy`, `#SMR`, `#energy policy`, `#regulation`

---

<a id="item-7"></a>
## [谷歌发布 Gemini 3.8 文本转语音，支持 30 秒声音克隆](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/) ⭐️ 7.0/10

谷歌发布了 Gemini 3.8 文本转语音模型，其中包括面向创意指导和角色设计的 Gemini 3.8 Flash TTS，仅需 30 秒音频样本即可重建一致的声音特征。该版本内置了同意验证、SynthID 水印和 C2PA 凭证，以保护开发者和配音人才。 这标志着谷歌正式进入已由其他厂商提供的声音克隆领域，可能加速有声书、游戏和无障碍工具中的采用，同时引发伦理和监管问题。这也加剧了生成式音频市场的竞争，并促使平台标准化同意和来源保护措施。 声音复制仅需 30 秒样本，并配有同意验证、SynthID 水印和 C2PA 凭证；但该功能在谷歌的消费者、专业消费者和云平台上的可用性不同，且各平台能力并不一致。这些模型既面向深度创意控制，也面向大规模部署。

hackernews · swolpers · 9月23日 15:29 · [社区讨论](https://news.ycombinator.com/item?id=49817615)

**背景**: 文本转语音（TTS）系统将书面文本转换为语音，而近期的零样本声音克隆工具仅需几秒参考音频即可模仿说话者的声音。SynthID 是谷歌用于 AI 生成内容的水印技术，而 C2PA 是一项用于认证媒体来源和编辑历史的开放标准。这些保护措施旨在防止通过克隆声音进行欺诈或诽谤等滥用行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-text-to-speech/">Gemini 3.8 text-to-speech says hello</a></li>
<li><a href="https://news.ycombinator.com/item?id=49817615">Gemini 3.8 text-to-speech says hello | Hacker News</a></li>
<li><a href="https://www.respeecher.com/news/ethics-in-ai-making-voice-cloning-safe">Ethics in AI: Making Voice Cloning Safe - Respeecher</a></li>

</ul>
</details>

**社区讨论**: 评论者批评谷歌在消费者、专业消费者和云平台上的发布不一致，指出模型在各平台上的能力往往不同。一些人认为声音克隆现已足够普遍，谷歌不再犹豫推出该功能；另一些人则分享了本地托管的 KeenLore 有声书创作器等项目，并称赞 Gemini 3.8 庞大的声音库和精确控制适合创意用途。

**标签**: `#AI`, `#text-to-speech`, `#Google Gemini`, `#voice cloning`, `#Hacker News`

---

<a id="item-8"></a>
## [文章称 LLM token 成本或将低于 grep](https://jyn.dev/tokens-too-cheap-to-meter/) ⭐️ 7.0/10

jyn.dev 上一篇题为《Tokens too cheap to meter》的文章认为，LLM token 正变得极其便宜，其成本可能很快低于 grep 等传统工具调用，并在 Hacker News 上引发热议，获得 235 分和 179 条评论。 如果 LLM 调用比传统命令行工具更便宜，可能会改变开发者构建和调度软件工作流的方式，使日常文本处理从确定性工具转向概率性模型。 作者观察到，调用 GPT-5.6 Luna 这类模型的成本仅比 grep 贵 4 到 5 个数量级，并按当前进步速度推断 LLM 调用很快会更便宜；评论者则以斯坦定律和对商业模式可持续性的质疑进行反驳。

hackernews · teoruiz · 9月23日 09:21 · [社区讨论](https://news.ycombinator.com/item?id=49813482)

**背景**: grep 是已有数十年历史的 Unix 命令行工具，用正则表达式搜索文本，以快速、确定且几乎零成本著称。相比之下，LLM 通过运行在 GPU 上的神经网络处理文本，其成本按输入和输出的 token（大致相当于词片段）计费。近期行业分析显示，LLM 推理价格已大幅下降，自 2025 年年中以来 API 价格下跌了 40% 至 60%，但不同任务之间的降幅并不均衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://epoch.ai/data-insights/llm-inference-price-trends">LLM inference prices have fallen rapidly but unequally across tasks | Epoch AI</a></li>
<li><a href="https://gigagpu.com/ai-inference-cost-trends-2026/">AI Inference Cost Trends 2026: What’s Changed (Updated April 2026) GIGAGPU</a></li>
<li><a href="https://github.com/karlkurzer/llm_grep">GitHub - karlkurzer/llm_grep: LLM-powered alternative to grep | pipe any command output through an LLM for intelligent text filtering, transformation, and analysis using natural language. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍对这一外推持怀疑态度：jetrink 引用斯坦定律（“无法永远持续的事情终将停止”）认为效率提升不会无限延续；cs702 指出文章在巨额基础设施投资背景下对商业模式可行性分析不足；abirch 则将“便宜到无需计量”的说法与 1954 年核电承诺的落空相类比。

**标签**: `#LLM`, `#AI economics`, `#cost trends`, `#Hacker News`, `#technology forecasting`

---

<a id="item-9"></a>
## [修复波托贝洛警察局的钟表](https://pointinthecloud.com/2026-04-11-211700.html) ⭐️ 6.0/10

一篇详细的博客文章讲述了修复波托贝洛警察局历史钟表的过程，该文章在 Hacker News 上分享后引发了讨论，获得了 379 分和 88 条评论，内容涵盖维护技巧、安全改进和个人联系。 这个故事凸显了保护历史机械基础设施的价值，并展示了小众修复项目如何促进在线社区参与和知识共享。 这座钟是传统的塔钟，很可能是重锤驱动的，评论者指出备用电池可能即将耗尽，并建议进行低成本的安全升级，例如在梯级上增加防滑踏板和安装 PoE IP 摄像头进行远程监控。

hackernews · avidly · 9月23日 15:18 · [社区讨论](https://news.ycombinator.com/item?id=49817469)

**背景**: 波托贝洛警察局所在的建筑曾是旧市政厅，后来成为公共图书馆。传统的塔钟是由悬挂重锤驱动的大型摆钟，不过现代版本通常使用电力。修复这类钟表需要机械专业知识，并需要精心维护以确保其准确运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Portobello_Police_Station">Portobello Police Station - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Turret_clock">Turret clock - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=49817469">Fixing the Portobello Police Station Clock | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者对这个故事表示热情，有人称其为“我想要的互联网”。实用的建议包括在梯级上增加防滑踏板以提高安全性，以及安装 PoE 摄像头来监控机械装置，还有一位评论者分享了与警察局的个人联系，并提醒注意备用电池的寿命。

**标签**: `#hardware`, `#restoration`, `#hackernews`, `#community`, `#engineering`

---

<a id="item-10"></a>
## [Raymond Chen 追溯 Windows 滚动条快捷操作的历史](https://devblogs.microsoft.com/oldnewthing/20260922-00/?p=112719/) ⭐️ 6.0/10

Raymond Chen 在其博客“The Old New Thing”上发表文章，追溯了 Windows 滚动条快捷操作的演变历史，其中包括 Windows 7 为滚动条添加的右键菜单，该菜单提供四个与现有鼠标操作对应的选项。这篇文章引发了社区对现代框架用不一致的自定义实现取代原生 Win32 滚动条的广泛讨论。 这篇文章揭示了软件开发中的一个更广泛趋势：各框架自定义的滚动条实现侵蚀了曾经在 Windows 应用程序中普遍存在的一致用户体验。这对开发者和 UX 设计师很重要，因为不一致的滚动行为每天影响着数百万用户，也代表着精心设计的平台惯例的流失。 Windows 7 为滚动条引入了右键上下文菜单，提供四个映射到现有鼠标操作的选项，反映了微软让滚动条交互更易被发现的努力。Chen 指出，如今几乎没有人使用真正的 Win32 滚动条，因为大多数应用程序依赖提供自定义滚动条的框架，而这些滚动条的功能往往不同或有所减少。

hackernews · tybulewicz · 9月23日 18:02 · [社区讨论](https://news.ycombinator.com/item?id=49820065)

**背景**: Win32 滚动条是 Windows API 提供的原生滚动控件，历史上提供了一套标准化的交互方式，例如点击箭头、拖动滑块、点击滑槽进行翻页，以及右键调出上下文菜单。Raymond Chen 是微软的资深工程师，以其博客“The Old New Thing”闻名，专门解释 Windows API 背后的历史与设计决策。随着 Qt、GTK、Electron 和网页浏览器等跨平台框架占据主导地位，它们用各自的实现取代了原生滚动条，从而导致了文章中所讨论的 UX 不一致问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://devblogs.microsoft.com/oldnewthing/20260922-00/?p=112719/">A brief history of Windows scroll bar shortcuts - The Old New Thing</a></li>
<li><a href="https://news.ycombinator.com/item?id=49820065">A brief history of Windows scroll bar shortcuts | Hacker News</a></li>
<li><a href="https://www.osnews.com/story/146018/the-state-of-scrollbars-in-windows-makes-even-longtime-microsoft-engineers-sad/">The state of scrollbars in Windows makes even longtime Microsoft engineers sad - OSnews</a></li>

</ul>
</details>

**社区讨论**: 评论者大多认同 Chen 的感叹：bartread 指出框架的滚动条实现往往更差，因为创建者缺乏用心；mrob 认为“滚动到此处”应成为点击滚动条的默认行为，因为键盘快捷键已经覆盖了翻页功能。其他人则对网站上过细或隐藏的滚动条表示担忧，butz 推荐通过 Firefox 的 about:config 设置禁用细滚动条，而 chrismorgan 详细描述了 Linux/GTK 应用程序中各种不一致的滚动条点击行为。

**标签**: `#Windows`, `#UI/UX`, `#scrollbars`, `#history`, `#Win32`

---

<a id="item-11"></a>
## [Reddit 帖子称 Jev 只是零样本分类器的重新包装，并非新 AI 范式](https://www.reddit.com/r/LocalLLaMA/comments/1woe70t/jev_isnt_new_tech_its_marketing_targets_people/) ⭐️ 6.0/10

r/LocalLLaMA 上的一篇 Reddit 帖子认为，'Jev'并非一类新的决策模型，而是标准的零样本分类器技术，其营销误导性地将其与 LLM 而非现有分类器进行比较。作者引用了一个 Banking77 实验：BGE-small 加逻辑回归达到 93.3%，而 Jev 为 83.2%，本地约 9 毫秒，并指出 Jev 尚未在 BTZSC 基准上得到恰当评测。 这一批评之所以重要，是因为它挑战了将'System One Models'视为新颖 AI 范式的说法，敦促从业者用强大的现有零样本分类器而非自回归 LLM 来评估新的分类器产品。它揭示了营销比较如何掩盖真实的性能差异，并误导买家对真正创新之处的判断。 帖子指出，Jev 在受限选项上输出概率，不进行自回归生成，无法输出无效类别，并可使用推理时定义的标签——这些都是零样本/NLI 分类器、嵌入模型、交叉编码器和重排序器多年来已有的行为。它还指出，Jev 的'0%幻觉'说法并非实证结论，仅保证输出符合模式，并不保证答案正确。

reddit · r/LocalLLaMA · /u/tiensss · 9月23日 18:33

**背景**: 零样本分类是指预测模型未明确训练过的类别，通常借助自然语言推理（NLI）或嵌入相似度实现。BTZSC 是一个零样本文本分类基准，在 22 个数据集上评估交叉编码器、嵌入模型、重排序器和 LLM。Jev 由 Typesafe AI 营销为'System One Model'，被宣传为分类任务中比 LLM 更快、更便宜的替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.11991">[2603.11991] BTZSC : A Benchmark for Zero-Shot Text Classification...</a></li>
<li><a href="https://huggingface.co/tasks/zero-shot-classification">What is Zero-Shot Classification? - Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-shot_learning">Zero-shot learning - Wikipedia</a></li>

</ul>
</details>

**标签**: `#zero-shot-classification`, `#LLM-comparison`, `#AI-marketing`, `#benchmarking`, `#NLP`

---

<a id="item-12"></a>
## [MiMo-V3 采用 HySparse2 混合稀疏注意力架构](https://www.reddit.com/r/LocalLLaMA/comments/1wo7mr6/mimov3_is_getting_a_new_architecture_the_core_of/) ⭐️ 6.0/10

MiMo-V3 即将采用新架构，其核心组件 HySparse2 于今日发布，并同步公开了 arXiv 论文（2609.26368），将其描述为一种带有两级 KV 共享的混合稀疏注意力架构。该论文用 token 级稀疏取代了块级稀疏，并在外层引入了 KV Bridging。 这一点很重要，因为据报道 HySparse2 在更低预填充成本和更小 KV 缓存占用下实现了更好的长上下文性能，这直接惠及受内存和算力限制的本地大模型用户。如果 MiMo-V3 采用该架构，长上下文推理在消费级硬件上将变得更加可行。 HySparse2 被描述为 HySparse 和 Hybrid SWA 的更高效继任者，提供更好的长上下文与多轮检索能力，以及更快的预填充速度。关键技术转变是从块级稀疏转向 token 级稀疏，并结合通过外层 KV Bridging 实现的两级 KV 共享。

reddit · r/LocalLLaMA · /u/Recoil42 · 9月23日 14:31

**背景**: MiMo 是小米的大语言模型系列，近期发布了 MiMo-V2.6-Pro-RL 等版本并已在 Hugging Face 上提供。稀疏注意力是一种通过让每个 token 只关注部分其他 token 而非全部，从而降低长序列处理计算成本的技术。KV 缓存是推理过程中存储的键值内存，缩小其体积对于在有限硬件上本地运行模型至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.26368">[2609.26368] HySparse2: Hybrid Sparse Attention with Two-Level KV Sharing - arXiv</a></li>
<li><a href="https://www.alphaxiv.org/abs/2609.26368">HySparse2: Hybrid Sparse Attention with Two-Level KV Sharing | alphaXiv</a></li>
<li><a href="https://arxiv.org/html/2609.26368v1">HySparse2 delivers better long-context performance at lower prefill cost and smaller KV-cache storage. - arXiv</a></li>

</ul>
</details>

**标签**: `#LLM`, `#architecture`, `#MiMo-V3`, `#HySparse2`, `#local-llama`

---