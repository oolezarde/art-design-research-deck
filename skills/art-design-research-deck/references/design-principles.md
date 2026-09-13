# 设计原则

## 必须成立的八项原则

1. **Design follows research.** 先明确研究对象、问题、事实和可用材料。不能从好看的封面倒推论点。研究未足时记录缺口，继续查证。
2. **Style is derived, not selected.** 从研究与参考建立视觉方向，同时允许可读性、编辑判断和用户约束决定具体实现。minimal / clean / premium 是形容词，不是完整概念。Derived 不等于模仿；不是每个决定都需要先例，但重要决定都需要理由。
3. **Editorial sequence.** 同时设计页与页的关系：观看距离、信息密度、证据尺度、翻页动作与章节转折。节奏允许不对称。
4. **Visual evidence before decoration.** 作品、spread、detail、binding、installation、archive、原始图表优先。图像须承担观察或论证功能。
5. **Empty space is valid.** 空白和纯文字页可以承载暂停、疑问、对照与结论；不以填充率判定完成度。密集案例也不能为了显得高级被拆得失去关系。
6. **Typography is structural.** 标题、论述、caption、source、footnote、folio 分配阅读角色，初始编排就留位置与层级。
7. **Sources remain traceable.** 作品图、案例、引文、数据、再绘图各有可追溯 ID 与出处。分析推断须与作者陈述区分。
8. **Native editability matters.** PPTX 的正文、标题、图注、基本形状、图片对象应可编辑；不把截图包成 PPTX 声称原生。复杂作品本身作为图像保留，不要求拆散作品。

## 禁止的默认行为

- 禁止默认 card-based layout。
- 禁止三 icon + 三 bullet 模板。
- 禁止无理由的 gradient、glassmorphism、blob。
- 禁止为了填空加入无意义 shape。
- 禁止用 AI-generated image 替代真实作品图，除非使用者明确要求；即使要求也须标注生成性质，不能当原作证据。
- 禁止所有页都做成相同 two-column layout。
- 禁止把 minimal、clean、premium 当成完整设计概念。
- 禁止所有图片尺寸趋同。
- 禁止所有页面密度趋同。
- 禁止为视觉统一牺牲案例应有的节奏差异。
- 禁止随便裁切艺术作品的核心内容。
- 禁止把 caption/source 当最后才补的小字垃圾区。

这些限制针对默认套用。参考中确有卡片、渐变、两栏或规则性重复时，可分析其功能并有理由地转译；不得据此启用整套预设。相同尺度有时服务严格比较，应记录为何必要。

## 统一什么、放开什么

统一证据编号、字体角色、标点、图注语法、来源索引与测量单位。允许案例改变主图尺度、文本量、背景、构图和页数。共同阅读逻辑不等于共同装饰 motif。

真实作品中的 logo、特殊字距、噪点、粗糙印刷或高密度是研究证据，不应按企业品牌 gate 自动去掉。区分“原作品属性”和“我们添加的呈现语言”，不要把观测到的作品特色伪装成自创设计。

## 推导记录

对影响整体方向的重要决定记录以下来源类别，可并列使用：

| 类别 | 依据 | 记录方式 |
|---|---|---|
| Observed | 研究对象或 reference 中可核对的特征 | 指向作品、页号或 evidence ID，记录适用范围与反例 |
| Functional | 可读性、展示环境、信息层级或技术限制 | 写明阅读需求及如何验证，不强求作品先例 |
| Interpretive | 对研究内容的编辑性转译 | 说明依据和转译关系，标为我们的解释，不冒充作者意图 |
| User-defined | 用户明确的审美或使用要求 | 记录要求及其对系统的影响 |

例如 caption 放在左下角可以是 Functional；不能为它编造某本书的先例。Observed 的旁注关系可启发 Interpretive 的分析层级，但不能用单件作品概括整个生涯。按任务规模合并记录，不要求逐个坐标填写理由。
