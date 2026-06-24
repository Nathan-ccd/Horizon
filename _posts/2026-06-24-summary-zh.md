---
layout: default
title: "Horizon Summary: 2026-06-24 (ZH)"
date: 2026-06-24
lang: zh
---

> 从 18 条内容中筛选出 12 条重要资讯。

---

1. [TikZ 编辑器：LaTeX 图形的所见即所得工具](#item-1) ⭐️ 8.0/10
2. [即将到来的循环：AI 代理需要人类规范](#item-2) ⭐️ 8.0/10
3. [Unlimited OCR：长文档解析的恒定内存方案](#item-3) ⭐️ 8.0/10
4. [Datasette 1.0a35 新增创建/修改表功能及 JSON API](#item-4) ⭐️ 8.0/10
5. [FUTO Swipe：采用优化布局的新型滑行输入模型](#item-5) ⭐️ 7.0/10
6. [苹果收购 Swift Package Index](#item-6) ⭐️ 7.0/10
7. [极端高温会议因高温警告取消](#item-7) ⭐️ 7.0/10
8. [维生素 D：对缺乏者有益，被网红夸大](#item-8) ⭐️ 7.0/10
9. [ML 团队跳过模型安全对抗测试](#item-9) ⭐️ 7.0/10
10. [艺术家自 1963 年起用纸牌手绘虚构地图](#item-10) ⭐️ 6.0/10
11. [Simon Willison 测试 OPFS + Pyodide 实现浏览器持久化 SQLite](#item-11) ⭐️ 6.0/10
12. [ICLR 2026 博客文章疑似错误](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [TikZ 编辑器：LaTeX 图形的所见即所得工具](https://tikz.dev/editor/) ⭐️ 8.0/10

一款开源的所见即所得 TikZ 编辑器已发布，用户可以通过拖拽和调整元素来直观地编辑 TikZ 源代码，同时源代码和渲染图形保持同步。该编辑器几乎完全由 Codex 编码代理构建。 该工具解决了学术界和 LaTeX 用户手动调整坐标并重新编译以创建图形的主要痛点，可能节省大量时间。它还展示了 AI 编码代理如何能够构建人类手动实现过于繁琐的软件。 该编辑器通过解析 TikZ 代码并跟踪每个对象的精确源代码位置来工作，当拖拽元素时仅覆盖坐标数字。实现需要重新实现 TikZ 的大部分功能，包括从 SVG/pptx/ipe 的转换器和 LaTeX 断字算法。

hackernews · DominikPeters · 6月23日 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48645437)

**背景**: TikZ 是一个强大的 LaTeX 包，用于使用声明式命令创建矢量图形，广泛应用于学术论文中。传统上，用户编写如 \draw (0,0) -- (1,2); 的代码并重新编译以查看结果，使得迭代调整变得繁琐。所见即所得（WYSIWYG）编辑器允许直接操作视觉输出，但将源代码编辑与 WYSIWYG 结合用于 TikZ 一直具有挑战性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://en.wikipedia.org/wiki/WYSIWYG_editor">WYSIWYG editor</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了该项目的创新性和开源性质，一些用户指出其对学生的潜力。然而，也有批评指出生成的 TikZ 代码不必要地使用了绝对坐标，一些用户请求支持 Typst 的 CeTZ 等替代格式。

**标签**: `#LaTeX`, `#TikZ`, `#editor`, `#academic`, `#open-source`

---

<a id="item-2"></a>
## [即将到来的循环：AI 代理需要人类规范](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Armin Ronacher 认为，AI 编程代理在人类明确规范的前提下最为有效，并且迭代的“循环”无法完全自动化。 这一见解挑战了关于完全自主 AI 编程的炒作，强调人类理解和规范仍然是软件开发中的关键瓶颈。 文章指出，即使使用先进的代理，在编写出合适的规范之前，通常需要 5-6 次失败的迭代，并且代理擅长执行定义明确的任务，但在美学和品味方面存在困难。

hackernews · ingve · 6月23日 11:06 · [社区讨论](https://news.ycombinator.com/item?id=48643180)

**背景**: 像 Claude Code 或 GitHub Copilot 这样的 AI 编程代理可以从自然语言提示生成代码，但其有效性取决于规范的质量。“循环”指的是完善规范和代码的迭代过程，Ronacher 认为这一过程无法完全自动化，因为人类理解需要时间和经验。

**社区讨论**: 评论者普遍认为编写规范是瓶颈，一些人指出，当给出明确的规范时，代理表现良好，但编写规范本身仍然是人类密集型任务。其他人讨论了过度空值检查的挑战以及需要更好的语言建模。

**标签**: `#AI-assisted programming`, `#software engineering`, `#LLM agents`, `#coding workflows`

---

<a id="item-3"></a>
## [Unlimited OCR：长文档解析的恒定内存方案](https://github.com/baidu/Unlimited-OCR) ⭐️ 8.0/10

百度研究人员提出了 Unlimited OCR，该方法通过修改 KV 缓存实现长文档 OCR 一次解析中的恒定内存使用，无需分页处理。 这一突破使得长 PDF（如 100 页以上）的 OCR 高效可行，内存不再增长，大幅降低了文档数字化及下游任务（如 RAG）的复杂度。 该方法基于 DeepSeek-OCR 和 PaddleOCR，论文见 arXiv（2606.23050）。KV 缓存修改避免了内存随序列长度线性增长。

hackernews · ingve · 6月23日 11:35 · [社区讨论](https://news.ycombinator.com/item?id=48643426)

**背景**: 在基于 Transformer 的 OCR 模型中，键值（KV）缓存为每个 token 存储注意力向量，导致内存随文档长度线性增长。这常迫使开发者将文档分页处理，增加复杂性。Unlimited OCR 通过保持 KV 缓存大小恒定解决了这一问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/baidu/Unlimited-OCR">GitHub - baidu/Unlimited- OCR : Unlimited OCR Works: Welcome the...</a></li>
<li><a href="https://arxiv.org/html/2606.23050">Unlimited OCR Works Welcome the Era of One-shot Long - horizon ...</a></li>
<li><a href="https://huggingface.co/docs/transformers/kv_cache">Cache strategies · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了这一巧妙的架构技巧，并指出了实际应用如乐谱 OCR。评论者还赞赏了对 DeepSeek-OCR 和 PaddleOCR 的致谢，有人指出项目名称引用了《Fate/stay night》。

**标签**: `#OCR`, `#AI`, `#memory optimization`, `#long-document parsing`, `#KV cache`

---

<a id="item-4"></a>
## [Datasette 1.0a35 新增创建/修改表功能及 JSON API](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 1.0a35 引入了新的创建表界面和修改表界面，两者均通过 JSON API 支持，允许用户以编程方式管理 SQLite 数据库模式。该版本还包含了用于自定义模板的稳定模板上下文文档。 这些功能通过直接在 Web UI 和 API 中管理数据库模式，显著提升了 Datasette 的易用性，减少了对外部工具的依赖。稳定的模板上下文文档为自定义模板开发者提供了可靠的基础，确保在 Datasette 2.0 之前的兼容性。 创建表 API 支持定义列、主键、自定义列类型、NOT NULL 约束、字面量默认值和表达式默认值以及单列外键。修改表 API 允许添加、重命名、重新排序和删除列，以及更改列类型、默认值、约束、主键、外键和表名。

rss · Simon Willison · 6月23日 21:34

**背景**: Datasette 是一个开源工具，用于将 SQLite 数据库探索和发布为交互式网页和 JSON API。在此版本之前，模式更改需要外部 SQLite 客户端或插件。新的内置界面简化了偏好图形界面或 API 驱动工作流的用户的模式管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.datasette.io/en/latest/json_api.html">JSON API - Datasette documentation</a></li>
<li><a href="https://docs.datasette.io/en/stable/json_api.html">JSON API - Datasette documentation</a></li>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and publishing data</a></li>

</ul>
</details>

**标签**: `#datasette`, `#release`, `#database`, `#JSON API`, `#open source`

---

<a id="item-5"></a>
## [FUTO Swipe：采用优化布局的新型滑行输入模型](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO Swipe 推出了一种新的滑行输入模型，其键盘布局经过优化以减少单词重叠，在准确性上相比现有方案显示出有希望的改进。 这解决了滑行输入中长期存在的痛点——单词重叠问题，有望使滑行输入速度与准确性媲美 Gboard，同时保持完全离线且注重隐私。 该模型用于 FUTO Keyboard（一款完全离线的 Android 键盘应用），滑行库以 GPLv3 开源，但 Android 键盘应用使用单独的 FUTO 许可证。

hackernews · futohq · 6月23日 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48648619)

**背景**: 滑行输入允许用户在字母上滑动手指来组成单词，但 QWERTY 等现有布局导致许多单词共享相似的滑动路径，从而产生错误。FUTO Swipe 的布局旨在最小化此类重叠，提高准确性。该系统完全在设备上运行，确保隐私。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://keyboard.futo.org/">FUTO Keyboard</a></li>
<li><a href="https://github.com/futo-org/android-keyboard/releases">Releases · futo -org/android- keyboard</a></li>

</ul>
</details>

**社区讨论**: 社区成员报告称 FUTO Swipe 现在感觉与 Gboard 一样好，有些人已完全切换。但仍存在随机大写和缺乏上下文感知建议等问题。一位用户指出许可问题：滑行库是 GPLv3，但 Android 键盘使用不同的许可证。

**标签**: `#keyboard`, `#swipe typing`, `#mobile input`, `#open source`, `#privacy`

---

<a id="item-6"></a>
## [苹果收购 Swift Package Index](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 7.0/10

苹果已收购 Swift Package Index（SPI），这是一个社区运营的、为支持 Swift Package Manager 的 Swift 包提供搜索和注册服务的平台。 此次收购表明苹果对 Swift 生态系统和 Swift Package Manager 的进一步投入，但也引发了关于治理和开源承诺的担忧，因为一个社区资源将置于企业控制之下。 Swift Package Index 是一个开源项目，索引了超过 11,000 个包的元数据，其团队将加入苹果。苹果明确将开发者身份作为未来方向，这在社区中引发了不安。

hackernews · JDevlieghere · 6月23日 18:00 · [社区讨论](https://news.ycombinator.com/item?id=48648779)

**背景**: Swift Package Manager (SPM) 是苹果官方的 Swift 代码分发和管理工具，集成在 Xcode 中。Swift Package Index 由社区创建，用于帮助发现包，因为 SPM 本身缺乏集中式注册中心。其他语言也有类似的包注册中心，例如 JavaScript 的 npm 和 Python 的 PyPI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swiftpackageindex.com/">Swift Package Index</a></li>
<li><a href="https://www.swift.org/packages/">Packages | Swift.org</a></li>
<li><a href="https://github.com/SwiftPackageIndex">Swift Package Index · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：有人为 SPI 团队感到高兴，也有人担心苹果在开源和开发者服务方面的过往表现。担忧包括可能对索引包进行监管，以及将开发者身份作为未来方向的强调。

**标签**: `#Swift`, `#Apple`, `#Package Manager`, `#Open Source`, `#Acquisition`

---

<a id="item-7"></a>
## [极端高温会议因高温警告取消](https://www.lse.ac.uk/granthaminstitute/events/extreme-heat-improving-governance-and-strengthening-action-around-the-world/) ⭐️ 7.0/10

一场名为“极端高温：改善治理并加强全球行动”的会议因伦敦地区发布极端高温警告而取消。 这种讽刺性的取消凸显了在气候变暖背景下组织活动的现实挑战，并引发了关于各地区热准备和基础设施差异的讨论。 该会议由伦敦政治经济学院格兰瑟姆研究所与苏黎世气候韧性联盟合作举办，原计划包括一场“炉边谈话”。

hackernews · rendx · 6月23日 23:26 · [社区讨论](https://news.ycombinator.com/item?id=48653060)

**背景**: 由于气候变化，极端高温事件变得更加频繁和强烈。许多地区，尤其是欧洲，缺乏广泛使用的空调，使得热浪尤其危险。一场关于极端高温的会议因极端高温本身而取消，是气候变化带来挑战的一个鲜明例子。

**社区讨论**: 评论者指出了其中的讽刺意味，一些人批评欧洲对空调的抵制，另一些人则强调了地区间耐热性的差异。一位评论者比较了希腊与热相关的死亡率与密西西比州的枪支死亡人数，而一位澳大利亚人则认为 37-40°C 很平常。

**标签**: `#climate change`, `#extreme heat`, `#irony`, `#conference`, `#adaptation`

---

<a id="item-8"></a>
## [维生素 D：对缺乏者有益，被网红夸大](https://dynomight.net/vitamin-d/) ⭐️ 7.0/10

一项对维生素 D 研究的详细分析指出，补充剂对严重缺乏者确实有益，但健康网红对普通人群的广泛益处声称被夸大了。 这很重要，因为维生素 D 补充剂是一个价值数十亿美元的产业，该分析有助于澄清证据，可能避免人们不必要的支出和错误的健康决策。 文章强调，维生素 D 最有力的证据是针对严重缺乏者，而许多网红转而声称大多数人缺乏，以解释负面研究结果。

hackernews · surprisetalk · 6月23日 16:30 · [社区讨论](https://news.ycombinator.com/item?id=48647486)

**背景**: 维生素 D 是一种脂溶性维生素，对骨骼健康和免疫功能至关重要。它通过皮肤暴露于阳光产生，也可从饮食和补充剂中获得。在日照有限的地区缺乏很常见，但最佳水平和补充益处仍有争议。

**社区讨论**: 评论者称赞了平衡的分析，其中一位指出健康网红经常转而声称普遍缺乏以否定负面研究。另一位指出了研究设计的潜在问题，如 NHANES 数据中的季节和纬度调整。一些人讨论了 K2 在维生素 D 吸收中的作用以及试验中监测血液水平的必要性。

**标签**: `#vitamin D`, `#health`, `#science communication`, `#nutrition`, `#evidence-based medicine`

---

<a id="item-9"></a>
## [ML 团队跳过模型安全对抗测试](https://www.reddit.com/r/MachineLearning/comments/1uddtws/are_model_security_risks_extraction_poisoning/) ⭐️ 7.0/10

一篇 Reddit 帖子揭示，许多机器学习团队在将模型部署到生产环境时，并未针对模型提取和投毒等安全风险进行对抗性测试，尽管这些是已知威胁。 这一缺口使已部署的模型容易受到攻击，攻击者可能窃取知识产权或操纵模型行为，在医疗和自动驾驶等关键应用中构成严重风险。 该帖子将 ML 模型缺乏对抗性测试与常规软件安全实践进行对比，后者安全审查是常规操作。模型提取攻击旨在窃取模型的功能或参数，而投毒攻击则通过破坏训练数据来改变模型行为。

reddit · r/MachineLearning · /u/Xorphian · 6月23日 10:52

**背景**: 对抗性机器学习涉及利用 ML 模型漏洞的攻击，如规避、提取和投毒。模型提取攻击通过查询模型来重建其功能，而投毒攻击则在训练期间注入恶意数据以导致误分类或后门。尽管意识在提高，许多生产系统仍缺乏针对这些威胁的稳健防御。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2508.15031">A Systematic Survey of Model Extraction Attacks and Defenses...</a></li>
<li><a href="https://owasp.org/www-project-machine-learning-security-top-10/docs/ML10_2023-Model_Poisoning">OWASP Machine Learning Security Top Ten 2023 | ML10:2023 Model Poisoning | OWASP Foundation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Adversarial_machine_learning">Adversarial machine learning - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 帖子下的评论普遍认为对抗性测试实践不足，一些人指出团队因时间和资源限制而优先考虑功能而非安全。少数从业者分享他们确实进行此类测试，但这仍然罕见。

**标签**: `#ML Security`, `#Adversarial Testing`, `#Model Deployment`, `#MLOps`

---

<a id="item-10"></a>
## [艺术家自 1963 年起用纸牌手绘虚构地图](http://www.jerrysmap.com/the-map) ⭐️ 6.0/10

Jerry Gretzinger 自 1963 年以来一直手绘一张虚构土地的地图，使用一副特制纸牌来指导每个方块的创作。这个名为“Jerry's Map”的项目随着每次抽牌决定下一个方块的特征而不断演变。 该项目体现了程序化生成与人类创造力的独特结合，启发了对生成艺术和地图制作感兴趣的艺术家和开发者。它展示了简单规则如何在数十年间产生复杂、不断演变的艺术作品。 该地图由数百个手绘方块组成，每个方块根据从特制牌组中抽取的卡片指令创作。这一过程将随机性与艺术家的个人风格相结合，形成了一个不断扩展的虚构世界。

hackernews · turtleyacht · 6月23日 18:40 · [社区讨论](https://news.ycombinator.com/item?id=48649435)

**背景**: 程序化生成是一种通过算法或规则自动创建内容的技术，常用于视频游戏中生成关卡或纹理。使用纸牌进行创意决策让人联想到 Brian Eno 的《Oblique Strategies》，这是一种基于纸牌的促进创造力的方法。Jerry's Map 将类似概念应用于地图制作，每次抽牌为下一个方块引入约束或提示。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Procedural_generation">Procedural generation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Oblique_Strategies">Oblique Strategies - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了地图的数字版本、视频纪录片和相关项目的链接。一位用户称赞该系统推动了创作过程，同时没有放弃实际的创意部分。

**标签**: `#art`, `#procedural generation`, `#maps`, `#creative process`

---

<a id="item-11"></a>
## [Simon Willison 测试 OPFS + Pyodide 实现浏览器持久化 SQLite](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 6.0/10

Simon Willison 构建了一个使用 Origin Private File System (OPFS) 和 Pyodide 的测试工具，探索在基于浏览器的 Python 应用 Datasette Lite 中实现持久化 SQLite 文件编辑。 该实验可能使 Datasette Lite 能够编辑存储在浏览器本地的持久化 SQLite 数据库，从而消除对服务器的需求，扩展其在离线数据分析中的实用性。 该测试工具使用 OPFS（提供页面源私有的低级逐字节文件访问）和 Pyodide（CPython 到 WebAssembly 的移植）在浏览器中运行 Python。

rss · Simon Willison · 6月23日 18:58

**背景**: Datasette Lite 是 Datasette 数据探索工具的一个版本，通过 WebAssembly 和 Pyodide 完全在浏览器中运行，无需服务器。OPFS 是一种浏览器存储 API，允许 Web 应用在沙盒化、特定源的虚拟文件系统中管理文件，提供比 File System Access API 更快的访问速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://github.com/simonw/datasette-lite">GitHub - simonw/datasette-lite: Datasette running in your browser using WebAssembly and Pyodide · GitHub</a></li>
<li><a href="https://pyodide.com/">Home - Pyodide</a></li>

</ul>
</details>

**标签**: `#Pyodide`, `#WebAssembly`, `#OPFS`, `#Datasette Lite`, `#Browser Storage`

---

<a id="item-12"></a>
## [ICLR 2026 博客文章疑似错误](https://www.reddit.com/r/MachineLearning/comments/1ud9i2g/found_a_potential_mistake_in_an_iclr_2026/) ⭐️ 6.0/10

一位用户报告了 ICLR 2026 博客文章中可能存在的一个错误，并创建了 GitHub issue，但数周未收到作者或组织者的回复。 如果确认，该错误可能影响 ICLR 博客文章轨道的可信度，该轨道旨在解决机器学习中的可重复性和审稿危机。 该 issue 发布在 ICLR 2026 博客文章的官方 GitHub 仓库中，用户正在寻求社区反馈以验证其理解是否正确。

reddit · r/MachineLearning · /u/metalwhaledev · 6月23日 06:39

**背景**: ICLR 引入了博客文章轨道，为发表解释或评论研究的科学博客文章提供场所。该轨道采用开放审稿流程，且规模显著增长，ICLR 2026 收到了超过 19,000 篇投稿。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://iclr-blogposts.github.io/2025/about/">Home to the 2025 ICLR Blogposts track</a></li>
<li><a href="https://iclr.cc/">2026 Conference</a></li>

</ul>
</details>

**标签**: `#ICLR`, `#peer review`, `#machine learning`, `#academic publishing`

---