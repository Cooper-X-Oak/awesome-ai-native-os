# Taxonomy

> The classification frame used by Awesome AI-Native OS.
>
> Awesome AI-Native OS 使用的分类框架。

## Language

- [English](#english)
- [中文](#中文)

---

## English

### Core Category

```text
AI-Native Production OS
= a domain-specific operating layer for repeatable human-AI production work
```

More explicitly:

```text
An AI-Native Production OS is a domain-specific system that turns a business workflow into an AI-operable production loop.

It makes a core business object durable, editable, inspectable, and deliverable through a shared human-AI workspace.
```

### Three-Layer Classification

Every project is classified through three layers.

#### Layer 1: Business Scene

What work does this system help a user complete?

Examples:

```text
app building
UI design and front-end delivery
video and media production
software engineering
research and evidence reporting
document and content production
data analysis and BI
sales and GTM automation
interactive artifact generation
```

This is the primary entry point for the atlas.

#### Layer 2: Business Core Abstraction

What business object does the system organize?

Examples:

| Scene | Core business object |
| --- | --- |
| App building | app project, website, runnable prototype |
| UI design | screen, component, React UI, design system |
| Video production | script, shot, timeline, media asset, production stage |
| Software engineering | issue, repo, diff, task, PR |
| Research | source set, question, outline, report, citation |
| Content production | doc, deck, page, brand asset, campaign content |
| Data analysis | sheet, dataset, metric, chart, dashboard |
| Sales / GTM | lead, account, signal, enrichment table, workflow |

This layer prevents the atlas from becoming a generic AI tool directory.

#### Layer 3: AI-Native Operating Model

How does the system make the business object AI-operable?

Common operating models:

| Operating model | Description | Examples |
| --- | --- | --- |
| pipeline-first | Work is split into stages, intermediate artifacts, and repeatable steps. | OpenMontage, STORM |
| canvas-first | Users and AI operate objects spatially through a canvas or graph. | OpenFlow, Onlook |
| timeline/transcript-first | Media is edited through time, transcript, or sequence structure. | Descript |
| repo-first | Software production is anchored in a repository and diff/PR boundary. | Devin, Cursor, Cline |
| session-workspace-first | Multiple AI sessions become visible and manageable production units. | CodeG, AgentRove |
| notebook/source-grounded | Sources and notes bound the AI's reasoning and outputs. | NotebookLM |
| spreadsheet-first | The grid is the primary interface for AI, code, data, and outputs. | Quadratic |
| table-first | Business operations are organized as rows, columns, enrichments, and workflows. | Clay |
| workflow-automation-first | AI operates across tools, browser actions, or automation recipes. | Bardeen |

### Seven Required Signals

A strong AI-Native Production OS usually has all seven signals:

1. **Business scene**: a clear job-to-be-done.
2. **Durable production object**: an artifact that survives beyond a prompt response.
3. **Shared operating space**: a place where humans and AI both work.
4. **Repeatable AI operations**: generate, edit, route, critique, enrich, test, publish, etc.
5. **Human control model**: review, approve, constrain, override, or directly edit.
6. **State and memory**: saved sources, versions, traces, project files, sessions, or histories.
7. **Delivery boundary**: app, PR, video, report, deck, spreadsheet, lead list, workflow, etc.

### Project Card Fields

Each case card should answer:

| Field | Question |
| --- | --- |
| Business scene | What business work does it solve? |
| Core business object | What object does the system organize? |
| Production artifact | What does it produce? |
| Operating space | Where do humans and AI operate the artifact? |
| AI operation model | What role does AI play? |
| Human control model | How does a human inspect, constrain, approve, or take over? |
| State and memory | What context, versions, sources, traces, or project state are preserved? |
| Delivery boundary | What is the concrete output? |
| Reusable pattern | What can builders copy into their own AI-native OS? |

### Boundary Rules

Do not classify something as an AI-Native Production OS only because it has AI features.

Common downgrades:

| Kind | Why it is downgraded |
| --- | --- |
| single-shot generator | no durable artifact or repeatable workspace |
| chatbot | no business object or delivery boundary |
| model API | infrastructure, not production OS |
| agent framework | building block, not domain production layer |
| ordinary SaaS with AI features | AI is an enhancement, not the operating layer |
| demo repository | not enough state, workflow, or repeatable production evidence |

### Useful Distinction

```text
AI Tool
= helps with one action

AI Agent
= executes one task or task chain

AI-Native Production OS
= makes a domain workflow repeatable, inspectable, controllable, and deliverable
```

---

## 中文

### 核心类别

```text
AI-Native Production OS
= 面向具体业务场景、支撑可重复人机协同生产的领域操作层
```

更明确地说：

```text
AI-Native Production OS 是一种面向具体业务场景的系统。

它把一个业务流程改造成 AI 可操作的生产循环，并让核心业务对象在共享的人机工作空间中变得可持久、可编辑、可检查、可交付。
```

### 三层分类框架

每个项目都通过三层来分类。

#### 第一层：业务场景

这个系统帮助用户完成什么工作？

例如：

```text
App 搭建
UI 设计和前端交付
视频和媒体生产
软件工程
研究和证据报告
文档和内容生产
数据分析和 BI
销售和 GTM 自动化
互动产物生成
```

这是本图谱的主要入口。

#### 第二层：业务核心抽象

这个系统组织的核心业务对象是什么？

示例：

| 场景 | 核心业务对象 |
| --- | --- |
| App 搭建 | app 项目、网站、可运行原型 |
| UI 设计 | screen、component、React UI、design system |
| 视频生产 | script、shot、timeline、media asset、production stage |
| 软件工程 | issue、repo、diff、task、PR |
| 研究 | source set、question、outline、report、citation |
| 内容生产 | doc、deck、page、brand asset、campaign content |
| 数据分析 | sheet、dataset、metric、chart、dashboard |
| 销售 / GTM | lead、account、signal、enrichment table、workflow |

这一层可以避免图谱退化成泛泛的 AI 工具目录。

#### 第三层：AI 原生操作模型

系统如何让业务对象变成 AI 可操作对象？

常见操作模型：

| 操作模型 | 描述 | 示例 |
| --- | --- | --- |
| pipeline-first | 工作被拆成阶段、中间产物和可重复步骤。 | OpenMontage, STORM |
| canvas-first | 用户和 AI 在 canvas 或 graph 中空间化操作对象。 | OpenFlow, Onlook |
| timeline/transcript-first | 媒体通过时间线、转录文本或序列结构被编辑。 | Descript |
| repo-first | 软件生产锚定在代码仓库和 diff/PR 边界上。 | Devin, Cursor, Cline |
| session-workspace-first | 多个 AI session 成为可见、可管理的生产单元。 | CodeG, AgentRove |
| notebook/source-grounded | sources 和 notes 限定 AI 的推理与输出边界。 | NotebookLM |
| spreadsheet-first | 表格网格是 AI、代码、数据和输出的主要操作界面。 | Quadratic |
| table-first | 业务操作被组织成行、列、增强结果和工作流。 | Clay |
| workflow-automation-first | AI 跨工具、浏览器动作或自动化 recipe 执行业务流程。 | Bardeen |

### 七个必要信号

强 AI-Native Production OS 通常具备全部七个信号：

1. **业务场景**：明确的 job-to-be-done。
2. **可持久化生产对象**：产物能在一次 prompt response 之后继续存在。
3. **共享操作空间**：人类和 AI 在同一个工作空间里操作。
4. **可重复 AI 操作**：生成、编辑、路由、批判、增强、测试、发布等。
5. **人类控制模型**：检查、批准、约束、覆盖、直接编辑。
6. **状态与记忆**：保存 sources、versions、traces、project files、sessions、histories 等。
7. **交付边界**：app、PR、video、report、deck、spreadsheet、lead list、workflow 等。

### 案例卡字段

每张案例卡应该回答：

| 字段 | 问题 |
| --- | --- |
| 业务场景 | 它解决什么业务工作？ |
| 核心业务对象 | 系统组织的对象是什么？ |
| 生产产物 | 它生产什么？ |
| 操作空间 | 人类和 AI 在哪里操作这个产物？ |
| AI 操作模型 | AI 在里面扮演什么角色？ |
| 人类控制模型 | 人类如何检查、约束、批准或接管？ |
| 状态与记忆 | 系统保留什么上下文、版本、来源、痕迹或项目状态？ |
| 交付边界 | 最终具体输出是什么？ |
| 可复用模式 | 构建者可以把什么结构复制到自己的 AI-native OS 里？ |

### 边界规则

不要因为一个项目“有 AI 功能”，就把它归类为 AI-Native Production OS。

常见降级类型：

| 类型 | 为什么降级 |
| --- | --- |
| single-shot generator | 没有可持久产物或可重复 workspace |
| chatbot | 没有清楚的业务对象或交付边界 |
| model API | 属于基础设施，不是生产 OS |
| agent framework | 是构建模块，不是领域生产层 |
| ordinary SaaS with AI features | AI 只是增强功能，不是操作层 |
| demo repository | 状态、工作流或可重复生产证据不足 |

### 一个有用区分

```text
AI Tool
= 帮你完成一个动作

AI Agent
= 帮你执行一个任务或任务链

AI-Native Production OS
= 让一个领域工作流变得可重复、可检查、可控制、可交付
```
