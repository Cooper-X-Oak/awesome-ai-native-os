# Awesome AI-Native OS

> An atlas of AI-native production systems and domain operating layers.
>
> AI 原生生产系统与领域操作层图谱。

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Candidates](https://img.shields.io/badge/candidates-100-blue.svg)](scenes/)
[![Scenes](https://img.shields.io/badge/scenes-9-green.svg)](scenes/)
[![Case Cards](https://img.shields.io/badge/case%20cards-12-orange.svg)](cases/)

## Language

- [English](#english)
- [中文](#中文)

## Start Here

| If you want to... | Go to |
| --- | --- |
| Understand the category | [taxonomy.md](taxonomy.md) |
| Check what qualifies | [inclusion-criteria.md](inclusion-criteria.md) |
| Browse by business scene | [scenes/](scenes/) |
| Read priority case-card stubs | [cases/](cases/) |
| Follow the bilingual documentation structure | [docs/bilingual-structure.md](docs/bilingual-structure.md) |
| Suggest a project | [Project suggestion issue](.github/ISSUE_TEMPLATE/project-suggestion.md) |

## Current Coverage

```text
9 business scenes
100 candidate systems
12 priority case cards
1 classification frame: Scene x Core Object x Operating Model
```

---

## English

### What This Is

Awesome AI-Native OS is a curated atlas of AI-native production systems.

It collects products and open-source projects that turn domain workflows into AI-operable production loops: systems where humans and AI work on durable artifacts through shared workspaces, inspectable state, repeatable operations, and concrete delivery boundaries.

This is not a list of AI tools, chatbots, model APIs, or agent frameworks.

### Core Definition

An **AI-Native Production OS** is a domain-specific system that turns a business workflow into an AI-operable production loop.

It has:

1. a clear business scene,
2. a durable production object,
3. a shared human-AI workspace,
4. repeatable AI operations,
5. inspectable state and memory,
6. human control points,
7. a concrete delivery boundary.

### The Classification Frame

```text
Scene x Core Object x Operating Model
```

This means each project is read through three questions:

1. What business scene does it solve?
2. What business object does it make durable and operable?
3. What operating model lets humans and AI produce together?

### Why This Exists

Most AI lists group projects by model, framework, feature, or provider.

This atlas groups projects by:

```text
business scene
  -> core business object
  -> production artifact
  -> operating model
  -> human control model
  -> state and memory
  -> delivery boundary
  -> reusable pattern
```

The point is not to ask which tool is "best". The point is to understand how different systems make the same business scene AI-operable.

Example:

| Business scene | Project | Operating model |
| --- | --- | --- |
| Video / media production | OpenMontage | pipeline-first production OS |
| Video / media production | OpenFlow | node-canvas-first multimodal OS |
| Video / media production | Descript | transcript/timeline-first media OS |
| Video / media production | Krea | creative-workspace-first media OS |

Same scene, different architecture and interaction model.

### Repository Map

| Path | Purpose |
| --- | --- |
| [taxonomy.md](taxonomy.md) | Core definition, classification framework, and operating-model vocabulary. |
| [inclusion-criteria.md](inclusion-criteria.md) | What qualifies, what does not, and how to grade candidates. |
| [scenes/](scenes/) | Business-scene indexes. All 100 current candidates are represented here. |
| [cases/](cases/) | Case-card templates and priority deep-dive entries. |

### Business Scenes

| Scene | What it studies | First projects to inspect |
| --- | --- | --- |
| [App / Website / Product Prototyping](scenes/app-website-product-prototyping.md) | Build apps, websites, and prototypes from prompts, sites, or product intent. | Dyad, bolt.diy, Open Lovable |
| [UI Design / Design-to-Code](scenes/ui-design-to-code.md) | Turn UI ideas, designs, and components into editable front-end artifacts. | Onlook, Plasmic |
| [Video / Media / Creative Production](scenes/video-media-creative-production.md) | Produce videos, media assets, clips, avatars, and creative variants. | OpenMontage, OpenFlow, Descript |
| [Software Engineering / Code Delivery](scenes/software-engineering-code-delivery.md) | Turn tasks, issues, bugs, and repo context into code changes or PRs. | CodeG, Devin, Cursor |
| [Game / Interactive Artifact Production](scenes/game-interactive-artifacts.md) | Generate playable games and interactive artifacts. | VibeStudio |
| [Research / Knowledge / Evidence Reporting](scenes/research-knowledge-evidence-reporting.md) | Produce grounded answers, reports, literature reviews, and long-form research. | NotebookLM, STORM, GPT Researcher |
| [Document / Presentation / Content Production](scenes/document-presentation-content-production.md) | Produce docs, decks, pages, knowledge assets, and marketing content. | Gamma, Notion AI, Writer |
| [Data Analysis / BI / Financial Analysis](scenes/data-analytics-bi-finance.md) | Produce analysis, charts, dashboards, briefs, and data apps. | Quadratic, Julius |
| [Sales / GTM / Business Automation](scenes/sales-gtm-business-automation.md) | Produce lead lists, account intelligence, outreach, and automated workflows. | Clay, Bardeen |

### Priority Case Cards

The first case-card batch focuses on projects that best define the category:

| Case | Why it matters |
| --- | --- |
| [OpenMontage](cases/openmontage.md) | Pipeline-first video production OS. |
| [Onlook](cases/onlook.md) | Canvas/design-first React UI OS. |
| [Dyad](cases/dyad.md) | Local app-builder OS. |
| [bolt.diy](cases/bolt-diy.md) | Browser runtime app-builder OS. |
| [OpenFlow](cases/openflow.md) | Node-canvas multimodal production OS. |
| [Descript](cases/descript.md) | Transcript/timeline-first media OS. |
| [CodeG](cases/codeg.md) | Multi-agent coding session OS. |
| [Devin](cases/devin.md) | Task-to-PR autonomous engineering OS. |
| [NotebookLM](cases/notebooklm.md) | Source-grounded notebook/research OS. |
| [STORM](cases/storm.md) | Research-to-writing pipeline OS. |
| [Quadratic](cases/quadratic.md) | Spreadsheet-first data OS. |
| [Clay](cases/clay.md) | Table-first GTM/business OS. |

### Fast Mental Model

```text
AI Tool
= helps with one action

AI Agent
= executes a task

AI-Native Production OS
= turns a business scene into a repeatable human-AI production loop
```

The durable question for every entry:

```text
What business object did this system make AI-operable?
```

### License

This atlas is licensed under [Creative Commons Attribution 4.0 International](LICENSE).

---

## 中文

### 这是什么

Awesome AI-Native OS 是一个 AI 原生生产系统图谱。

它收集的不是普通 AI 工具，而是那些把具体业务流程改造成 AI 可操作生产循环的产品和开源项目：人类和 AI 在同一个工作空间里，共同操作可持久化的产物；系统保留可检查的状态；AI 可以重复执行生产动作；人类可以监督、接管和批准；最后交付明确的业务产物。

这不是 AI 工具列表、聊天机器人列表、模型 API 列表，也不是 agent 框架列表。

### 核心定义

**AI-Native Production OS** 是一种面向具体业务场景的系统。它把业务流程改造成 AI 可操作的生产循环。

它通常具备：

1. 明确的业务场景，
2. 可持久化的生产对象，
3. 人类和 AI 共享的操作空间，
4. 可重复的 AI 操作，
5. 可检查的状态与记忆，
6. 人类控制点，
7. 明确的交付边界。

### 分类框架

```text
业务场景 x 核心业务对象 x 操作模型
```

也就是每个项目都要回答三个问题：

1. 它解决什么业务场景？
2. 它把什么业务对象变成了可持久、可操作的对象？
3. 它用什么操作模型让人类和 AI 一起生产？

### 为什么需要这个仓库

大多数 AI 列表按模型、框架、功能或供应商分类。

这个图谱按下面的结构理解项目：

```text
业务场景
  -> 核心业务对象
  -> 生产产物
  -> 操作模型
  -> 人类控制模型
  -> 状态与记忆
  -> 交付边界
  -> 可复用模式
```

重点不是判断哪个工具“更强”，而是理解不同系统如何把同一个业务场景变成 AI 可操作的生产系统。

例如：

| 业务场景 | 项目 | 操作模型 |
| --- | --- | --- |
| 视频 / 媒体生产 | OpenMontage | pipeline-first production OS |
| 视频 / 媒体生产 | OpenFlow | node-canvas-first multimodal OS |
| 视频 / 媒体生产 | Descript | transcript/timeline-first media OS |
| 视频 / 媒体生产 | Krea | creative-workspace-first media OS |

同一个业务场景，不同的架构和交互模型。

### 仓库结构

| 路径 | 用途 |
| --- | --- |
| [taxonomy.md](taxonomy.md) | 核心定义、分类框架、操作模型词汇表。 |
| [inclusion-criteria.md](inclusion-criteria.md) | 收录标准、降级标准、候选分级方式。 |
| [scenes/](scenes/) | 按业务场景组织的项目索引。目前覆盖 100 个候选。 |
| [cases/](cases/) | 案例卡模板和第一批重点深拆入口。 |

### 业务场景

| 场景 | 研究对象 | 优先查看 |
| --- | --- | --- |
| [建站 / App 搭建 / 产品原型](scenes/app-website-product-prototyping.md) | 从 prompt、已有网站或产品意图构建 app、网站和原型。 | Dyad, bolt.diy, Open Lovable |
| [UI 设计 / 设计到代码](scenes/ui-design-to-code.md) | 把 UI 想法、设计稿、组件需求变成可编辑的前端产物。 | Onlook, Plasmic |
| [视频 / 媒体 / 创意生产](scenes/video-media-creative-production.md) | 生产视频、媒体素材、短片、头像视频和创意变体。 | OpenMontage, OpenFlow, Descript |
| [软件工程 / 代码交付](scenes/software-engineering-code-delivery.md) | 把任务、issue、bug 和 repo 上下文变成代码改动或 PR。 | CodeG, Devin, Cursor |
| [游戏 / 互动内容生产](scenes/game-interactive-artifacts.md) | 生成可玩的游戏和互动产物。 | VibeStudio |
| [研究 / 知识发现 / 证据报告](scenes/research-knowledge-evidence-reporting.md) | 生产有依据的回答、报告、文献综述和长文研究。 | NotebookLM, STORM, GPT Researcher |
| [文档 / 演示 / 内容生产](scenes/document-presentation-content-production.md) | 生产文档、演示稿、页面、知识资产和营销内容。 | Gamma, Notion AI, Writer |
| [数据分析 / BI / 财务分析](scenes/data-analytics-bi-finance.md) | 生产分析、图表、dashboard、brief 和数据应用。 | Quadratic, Julius |
| [销售 / GTM / 业务自动化](scenes/sales-gtm-business-automation.md) | 生产线索列表、账号情报、销售动作和自动化流程。 | Clay, Bardeen |

### 第一批案例卡

第一批案例卡优先覆盖最能定义这个类别的项目：

| 案例 | 为什么重要 |
| --- | --- |
| [OpenMontage](cases/openmontage.md) | Pipeline-first 视频生产 OS。 |
| [Onlook](cases/onlook.md) | Canvas/design-first React UI OS。 |
| [Dyad](cases/dyad.md) | Local app-builder OS。 |
| [bolt.diy](cases/bolt-diy.md) | Browser runtime app-builder OS。 |
| [OpenFlow](cases/openflow.md) | Node-canvas multimodal production OS。 |
| [Descript](cases/descript.md) | Transcript/timeline-first media OS。 |
| [CodeG](cases/codeg.md) | Multi-agent coding session OS。 |
| [Devin](cases/devin.md) | Task-to-PR autonomous engineering OS。 |
| [NotebookLM](cases/notebooklm.md) | Source-grounded notebook/research OS。 |
| [STORM](cases/storm.md) | Research-to-writing pipeline OS。 |
| [Quadratic](cases/quadratic.md) | Spreadsheet-first data OS。 |
| [Clay](cases/clay.md) | Table-first GTM/business OS。 |

### 快速理解

```text
AI Tool
= 帮你完成一个动作

AI Agent
= 帮你执行一个任务

AI-Native Production OS
= 把一个业务场景变成可重复的人机协同生产循环
```

每个项目都应该回答一个稳定问题：

```text
这个系统把哪个业务对象变成了 AI 可操作对象？
```

### 许可证

本图谱采用 [Creative Commons Attribution 4.0 International](LICENSE) 许可。
