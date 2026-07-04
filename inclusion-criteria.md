# Inclusion Criteria

> What qualifies for Awesome AI-Native OS, what gets downgraded, and what evidence is required.
>
> Awesome AI-Native OS 的收录标准、降级标准和证据要求。

## Language

- [English](#english)
- [中文](#中文)

---

## English

### Principle

This atlas is selective.

A project should not be included only because it says "AI", "agent", "copilot", or "workflow".

The central question is:

```text
Does this system turn a business workflow into a repeatable human-AI production loop?
```

### Include

Include a project when it clearly shows at least four of these signals, and prioritize it when it shows six or seven:

| Signal | What to look for |
| --- | --- |
| Business scene | The project solves a recognizable business or production workflow. |
| Core business object | There is a stable object: repo, video project, app, report, sheet, table, deck, etc. |
| Operating space | There is a workspace, canvas, IDE, notebook, table, timeline, pipeline, or editor. |
| AI operation model | AI repeatedly edits, generates, critiques, routes, enriches, tests, or composes. |
| Human control model | The user can review, approve, override, directly edit, or constrain AI work. |
| State and memory | The system keeps project state, history, source set, sessions, traces, versions, or runs. |
| Delivery boundary | The output is concrete: PR, app, video, report, dataset, deck, workflow, lead list, etc. |

### Exclude Or Downgrade

Downgrade a project when it is mainly:

```text
a one-shot generator
a chatbot
a prompt collection
a model API
an agent framework without a domain workspace
a generic SaaS product with a thin AI feature
a demo with no durable artifact
a workflow automation component without a clear production object
```

### Priority Grades

| Grade | Meaning | Action |
| --- | --- | --- |
| A0 | Strong category-defining case | Create a full case card and compare it against peers. |
| A1 | Strong comparison case | Use as a peer or contrast case. |
| B+ | Interesting but not first batch | Keep for later or as an edge case. |
| B | Candidate | Keep in scene index; verify later. |
| C | Weak candidate | Keep only if it clarifies a boundary. |
| D | Downgrade / exclude | Do not include in the main narrative. |

### Evidence Standard

For every included project, prefer direct evidence:

```text
official website
official documentation
GitHub README
demo video
product screenshots
technical blog or launch post
```

Separate:

```text
observed evidence
inferred pattern
open question
```

Do not blur those together.

### Good Entry Format

When adding a project, include:

| Field | Required content |
| --- | --- |
| Name | Project or product name. |
| URL | Official site, docs, or repository. |
| Business scene | The business work it belongs to. |
| Core business object | The object it makes durable and operable. |
| Operating model | How humans and AI operate the object. |
| Why it belongs | Why it is more than a tool, chatbot, API, or demo. |
| Evidence | Direct links. |
| Suggested grade | A0, A1, B+, B, C, or D. |

### Quick Test

Ask these questions before including a project:

```text
Can I name the business scene?
Can I name the durable artifact?
Can I point to the workspace where humans and AI operate it?
Can I describe repeated AI operations?
Can I identify human control points?
Can I identify saved state or memory?
Can I state the delivery boundary?
```

If most answers are unclear, keep the project out of the main list or mark it as C/D.

---

## 中文

### 原则

这个图谱是有选择性的。

不要因为一个项目写了 “AI”、“agent”、“copilot” 或 “workflow”，就把它收录进来。

核心问题是：

```text
这个系统是否把一个业务流程变成了可重复的人机协同生产循环？
```

### 收录

当一个项目清楚满足至少四个信号时，可以收录；满足六个或七个信号时，应优先处理：

| 信号 | 判断方式 |
| --- | --- |
| 业务场景 | 项目解决一个可识别的业务流程或生产流程。 |
| 核心业务对象 | 存在稳定对象：repo、video project、app、report、sheet、table、deck 等。 |
| 操作空间 | 存在 workspace、canvas、IDE、notebook、table、timeline、pipeline 或 editor。 |
| AI 操作模型 | AI 会重复编辑、生成、批判、路由、增强、测试或组合。 |
| 人类控制模型 | 用户可以检查、批准、覆盖、直接编辑或约束 AI 工作。 |
| 状态与记忆 | 系统保存项目状态、历史、source set、sessions、traces、versions 或 runs。 |
| 交付边界 | 输出是具体的：PR、app、video、report、dataset、deck、workflow、lead list 等。 |

### 排除或降级

如果项目主要是下面这些类型，应降级：

```text
一次性生成器
聊天机器人
prompt collection
模型 API
没有领域 workspace 的 agent framework
只有薄 AI 功能的普通 SaaS
没有可持久产物的 demo
没有清楚生产对象的 workflow automation component
```

### 优先级分级

| 等级 | 含义 | 动作 |
| --- | --- | --- |
| A0 | 强类别定义案例 | 写完整案例卡，并和同场景项目比较。 |
| A1 | 强对照案例 | 作为 peer 或 contrast case 使用。 |
| B+ | 有意思但不是第一批 | 后续保留，或作为边界案例。 |
| B | 候选 | 保留在场景索引里，后续复核。 |
| C | 弱候选 | 只在它能帮助说明边界时保留。 |
| D | 降级 / 排除 | 不进入主叙事。 |

### 证据标准

每个收录项目都应优先使用直接证据：

```text
官方网站
官方文档
GitHub README
demo video
产品截图
技术博客或发布文章
```

要分开写：

```text
观察到的证据
推断出的模式
尚未确认的问题
```

不要把这三者混在一起。

### 好的条目格式

新增项目时，应包含：

| 字段 | 必要内容 |
| --- | --- |
| 名称 | 项目名或产品名。 |
| URL | 官网、文档或仓库。 |
| 业务场景 | 它属于哪类业务工作。 |
| 核心业务对象 | 它让哪个对象变得可持久、可操作。 |
| 操作模型 | 人类和 AI 如何操作这个对象。 |
| 为什么属于这里 | 为什么它不只是工具、聊天机器人、API 或 demo。 |
| 证据 | 直接链接。 |
| 建议等级 | A0、A1、B+、B、C 或 D。 |

### 快速测试

收录项目前先问：

```text
我能说清它的业务场景吗？
我能说清它的可持久产物吗？
我能指出人类和 AI 在哪里共同操作它吗？
我能描述可重复的 AI 操作吗？
我能指出人类控制点吗？
我能指出保存的状态或记忆吗？
我能说清最终交付边界吗？
```

如果大多数答案都不清楚，就不要把它放入主列表，或者标记为 C/D。
