<p align="center">
  <a href="https://orkas.ai/?lang=zh&amp;source=gh-orkas-docs"><img src="https://orkas.ai/res/orkas.png" width="88" height="88" alt="Orkas 标志"></a>
</p>

<h1 align="center">Orkas — 你的 AI 团队</h1>

<p align="center"><strong>用一个目标，组织研究、文档、设计、视频和开发。</strong></p>

<p align="center">
  <a href="https://orkas.ai/download/?lang=zh&amp;source=gh-orkas-docs">下载</a> ·
  <a href="https://orkas.ai/docs/?lang=zh&amp;source=gh-orkas-docs">使用文档</a> ·
  <a href="https://orkas.ai/views/marketplace/?lang=zh&amp;source=gh-orkas-docs">Agent 与 Skill</a> ·
  <a href="https://github.com/Orkas-AI/Orkas">源码</a>
</p>

<p align="center"><a href="./README.md">English</a> · <strong>简体中文</strong></p>

<p align="center"><img src="https://orkas.ai/res/home-hero-capabilities-poster.jpg" width="100%" alt="Orkas 中的研究、内容和办公成果示例"></p>

Orkas 是开源、本地优先的桌面 AI 工作区，面向独立开发者、一人公司和小型团队。描述目标后，Commander 可以处理任务、协调专业 Agent，并把报告、表格、演示文稿、代码、图片或视频交付到工作区供你检查和修改。

**Orkas-Docs 是官方指南目录。** 这里的 Issue 用于发布文章，不是问题反馈区。每个主题分别维护中文和英文版本；Open 且已锁定的 Issue 是现行指南，Closed Issue 是归档内容。

## 完成第一个任务

1. [下载并打开 Orkas](https://orkas.ai/download/?lang=zh&source=gh-orkas-docs)，选择可用的官方托管模型，或连接自己的受支持供应商。
2. 新建任务，说明想得到的结果、受众和格式，只添加相关文件或资源。
3. 在任务中补充必要决定，检查交付物，并继续提出明确修改。需要长期复用背景时使用项目。

例如：

> 用这份销售表和会议记录准备月度业务复盘。先核对数字，再给出一页决策摘要和可编辑工作簿。标出缺失数据与待确认事项，不向任何人发送。

模型、项目、自动化、连接器、资料库和结果管理的具体入口见[完整使用指南](https://orkas.ai/docs/?lang=zh&source=gh-orkas-docs)。

## 按目标找到指南

| 你想完成什么 | 从这里开始 | 典型交付物 |
| --- | --- | --- |
| 比较市场、整理证据 | [市场研究](https://orkas.ai/use/researchers/?lang=zh&source=gh-orkas-docs) · [文档问答](https://orkas.ai/use/chat-with-documents/?lang=zh&source=gh-orkas-docs) | 决策简报、引用与证据表 |
| 准备经营或客户复盘 | [数据分析](https://orkas.ai/use/data-analysis/?lang=zh&source=gh-orkas-docs) · [办公报告](https://orkas.ai/use/office-documents/?lang=zh&source=gh-orkas-docs) | 工作簿、报告、演示文稿 |
| 完成产品发布内容 | [内容制作](https://orkas.ai/use/content-writing/?lang=zh&source=gh-orkas-docs) · [图片](https://orkas.ai/use/make-images/?lang=zh&source=gh-orkas-docs) · [视频](https://orkas.ai/use/make-videos/?lang=zh&source=gh-orkas-docs) | 文案、视觉素材、成片 |
| 开发应用或设计界面 | [应用开发](https://orkas.ai/use/build-apps/?lang=zh&source=gh-orkas-docs) · [产品工作流](https://orkas.ai/use/developers/?lang=zh&source=gh-orkas-docs) · [UI 设计](https://orkas.ai/use/ui-design/?lang=zh&source=gh-orkas-docs) | 源码、界面与验证结果 |
| 复盘店铺与重复运营 | [电商周复盘](https://orkas.ai/use/ecommerce/?lang=zh&source=gh-orkas-docs) · [团队周报](https://orkas.ai/use/automate-workspace/?lang=zh&source=gh-orkas-docs) | 核对后的数据、行动草稿 |
| 改善搜索与 AI 可见性 | [SEO 与 GEO](https://orkas.ai/use/seo-geo/?lang=zh&source=gh-orkas-docs) | 问题证据、修复优先级 |

### 协调本地 Agent

Orkas 可协调受支持的 Claude Code、Codex、OpenCode、OpenClaw 和 Hermes 本地安装。先按对应工具的要求安装、登录，再通过 Orkas 的外接 Agent 入口接入。外接工具使用自己的模型设置；CLI 原生权限和 Orkas 连接器权限分别生效。

从[本地 Agent 协作文章](https://orkas.ai/blog/claude-code-codex-together/?lang=zh&source=gh-orkas-docs)了解任务分工，并以[当前使用指南](https://orkas.ai/docs/?lang=zh&source=gh-orkas-docs)核对应用入口和权限。多个 Agent 可能修改相同文件时，先明确文件归属或使用隔离工作目录。

## 选择专业角色

| Agent | 主要用途 |
| --- | --- |
| Commander | 规划、协调、跟进与汇总 |
| DeepResearcher | 有引用的研究与证据整理 |
| ContentWriter | 文章、报告、发布文案 |
| OfficeWorker | 文档、表格、PDF 与数字核对 |
| PptMaker | 可编辑演示文稿 |
| ProductDeveloper | 开发、修复与代码评审 |
| UIDesigner | 产品流程和可编辑界面 |
| ImageStudio | 海报、封面与图片制作 |
| VideoStudio | 视频制作、剪辑、字幕与配音 |
| SeoGeoAgent | 搜索可见性审计与内容改进 |

下面的 Agent 指南介绍输入、适用范围和交付物；更多角色与技能可在[市场](https://orkas.ai/views/marketplace/?lang=zh&source=gh-orkas-docs)查看。

## 模型、数据与费用

- 对话、项目文件和交付物默认保存在本机。模型、连接器、同步和分享可能发送或保存各功能所需的数据。
- 自有供应商凭证留在本地，模型请求直达该供应商；可选 Orkas 托管模型使用托管服务。
- 可连接兼容 OpenAI 接口的本地模型服务，但这不自动让搜索、外部工具或整个工作流离线。
- 外接 CLI 使用其自身账号与模型设置。托管模型、自有供应商及其他服务的可用性和费用分别计算，以应用及服务商说明为准。
- 模型 API 密钥和任务附件不会随云同步迁移。需复用的受支持资料可加入资料库，并检查目标设备同步状态。

客户端源码采用 [MIT 许可证](https://github.com/Orkas-AI/Orkas)。数据边界见[安全说明](https://orkas.ai/security/?lang=zh&source=gh-orkas-docs)；当前托管套餐见[价格页](https://orkas.ai/pricing/?lang=zh&source=gh-orkas-docs)。

## 已发布指南

以下 Open、已锁定的 Issue 是持续维护的中文指南。每篇内容都会独立说明适用情况、所需输入、工作流程、交付物、限制与下一步。

### Agent 指南

| Agent | 已发布指南 |
| --- | --- |
| Commander | [阅读 Commander 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/4) |
| ContentWriter | [阅读 ContentWriter 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/6) |
| DeepResearcher | [阅读 DeepResearcher 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/2) |
| ImageStudio | [阅读 ImageStudio 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/8) |
| OfficeWorker | [阅读 OfficeWorker 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/10) |
| PptMaker | [阅读 PptMaker 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/12) |
| ProductDeveloper | [阅读 ProductDeveloper 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/14) |
| SeoGeoAgent | [阅读 SeoGeoAgent 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/16) |
| UIDesigner | [阅读 UIDesigner 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/18) |
| VideoStudio | [阅读 VideoStudio 中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/20) |

### 使用场景指南

| 工作流 | 已发布指南 |
| --- | --- |
| 每周工作区自动化 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/22) |
| 用自然语言构建应用 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/24) |
| 私有文档问答 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/26) |
| 产品发布内容 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/28) |
| CSV、Excel 与表格分析 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/30) |
| 产品设计、开发与验收 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/32) |
| 图片设计与制作 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/34) |
| 视频制作与剪辑 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/36) |
| 月度业务复盘 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/38) |
| 基于证据的市场研究 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/40) |
| SEO 与 GEO 可见性 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/42) |
| 可编辑 UI 设计 | [阅读中文指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/44) |
| 电商店铺周复盘：从订单、库存和退货数据形成行动清单 | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/132) |

### 对比指南

| 与 Orkas 对比的产品 | 已发布指南 |
| --- | --- |
| Activepieces | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/46) |
| AnythingLLM | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/48) |
| AutoGPT | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/50) |
| Bolt.new | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/52) |
| ChatGPT | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/54) |
| Claude Code | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/56) |
| Cline | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/58) |
| Codex | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/60) |
| CrewAI | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/62) |
| DeepSeek Harness | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/64) |
| Devin | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/66) |
| Dify | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/68) |
| Flowise | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/70) |
| Goose | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/72) |
| Hermes Agent | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/74) |
| LangChain | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/76) |
| LibreChat | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/78) |
| Lovable | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/80) |
| n8n | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/82) |
| OpenClaw | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/84) |
| OpenCode | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/86) |
| Orca | [阅读中文对比 →](https://github.com/Orkas-AI/Orkas-Docs/issues/88) |
| HeyGen | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/116) |
| OpenMontage | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/118) |
| OpusClip | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/120) |
| Remotion | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/122) |

### 博客指南

| 文章 | 已发布指南 |
| --- | --- |
| 上下文压缩是按 token 数切的，跟「什么该忘」没有关系 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/90) |
| 把模型变成产品的那一层：Orkas 的 Agent Harness 工程实现 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/92) |
| 声明完成不等于验证完成：长程 Agent 的里程碑设计 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/94) |
| 多 Agent 编排实战：Orkas 如何调度一个主 Agent 和它的子 Agent | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/96) |
| 循环检测不等于停滞检测：抓住那些不重复却在原地打转的 Agent | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/98) |
| 如何让 Claude Code 和 Codex 一起用——一个对话同时指挥两个 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/100) |
| 云端同步实战：Orkas 如何做好数据同步 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/102) |
| 重写 Agent 的地基：Orkas 的一次底层重构 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/104) |
| 如何被 ChatGPT 引用：到底是什么决定了你会不会被引到 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/106) |
| 变大不是重点：Kimi K3 在三个方向上扩展信息流 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/108) |
| 什么是本地优先 AI？你的数据、你的密钥、你的机器 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/110) |
| BEACON：用里程碑引导的长程 Agent | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/112) |
| 一个会自己变好用的 Agent：拆解 Orkas 的自演进机制 | [阅读中文文章指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/114) |
| 客户月报怎么写：先核对数字，再形成结论和下月行动 | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/124) |
| 自由职业营销报价：先算可计费产能，再确定项目范围 | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/126) |
| 营销自己做、招人还是找代理：拆开产能、专业能力与责任 | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/128) |
| AI 视频预算怎么做：把尝试、修改和可用镜头都算进去 | [阅读指南 →](https://github.com/Orkas-AI/Orkas-Docs/issues/130) |

## 常见问题

**一定要有自己的模型 Key 吗？**

不一定。可以选择可用的官方托管模型，也可以连接自己的受支持供应商；两种方式的账号和计费边界不同。

**本地优先等于完全离线吗？**

不等于。应分别检查模型推理、外部工具、搜索与同步。使用本地模型，也不代表其他服务不会出网。

**能每周自动执行吗？**

可以使用自动化设置单次或周期任务，但指定设备、账号访问和输入数据必须在执行时可用。先检查首轮结果，再依赖后续运行。

**支持哪些平台？**

官网提供 macOS 与 Windows 安装包。源码构建与其他平台说明以[主仓库](https://github.com/Orkas-AI/Orkas)及[下载页](https://orkas.ai/download/?lang=zh&source=gh-orkas-docs)为准。

**怎样比较工具？**

用相同输入、目标和权限比较完整交付、修改与恢复过程。对比指南是适用性分析，不是性能排名；功能、模型和套餐以当前一手文档为准。

---

[下载 Orkas](https://orkas.ai/download/?lang=zh&source=gh-orkas-docs) · [阅读使用指南](https://orkas.ai/docs/?lang=zh&source=gh-orkas-docs) · [查看源码](https://github.com/Orkas-AI/Orkas)
