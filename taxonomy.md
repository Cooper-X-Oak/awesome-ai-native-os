# Taxonomy

> The classification frame used by Awesome AI-Native OS.
> 
> Awesome AI-Native OS 使用的分类框架。

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

| 场景       | 核心业务对象                                            |
| -------- | ------------------------------------------------- |
| App 搭建   | app 项目、网站、可运行原型                                   |
| UI 设计    | screen、component、React UI、design system           |
| 视频生产     | script、shot、timeline、media asset、production stage |
| 软件工程     | issue、repo、diff、task、PR                           |
| 研究       | source set、question、outline、report、citation       |
| 内容生产     | doc、deck、page、brand asset、campaign content        |
| 数据分析     | sheet、dataset、metric、chart、dashboard              |
| 销售 / GTM | lead、account、signal、enrichment table、workflow     |

这一层可以避免图谱退化成泛泛的 AI 工具目录。

#### 第三层：AI 原生操作模型

系统如何让业务对象变成 AI 可操作对象？

常见操作模型：

| 操作模型                      | 描述                                | 示例                   |
| ------------------------- | --------------------------------- | -------------------- |
| pipeline-first            | 工作被拆成阶段、中间产物和可重复步骤。               | OpenMontage, STORM   |
| canvas-first              | 用户和 AI 在 canvas 或 graph 中空间化操作对象。 | OpenFlow, Onlook     |
| timeline/transcript-first | 媒体通过时间线、转录文本或序列结构被编辑。             | Descript             |
| repo-first                | 软件生产锚定在代码仓库和 diff/PR 边界上。         | Devin, Cursor, Cline |
| session-workspace-first   | 多个 AI session 成为可见、可管理的生产单元。      | CodeG, AgentRove     |
| notebook/source-grounded  | sources 和 notes 限定 AI 的推理与输出边界。   | NotebookLM           |
| spreadsheet-first         | 表格网格是 AI、代码、数据和输出的主要操作界面。         | Quadratic            |
| table-first               | 业务操作被组织成行、列、增强结果和工作流。             | Clay                 |
| workflow-automation-first | AI 跨工具、浏览器动作或自动化 recipe 执行业务流程。   | Bardeen              |

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

| 字段      | 问题                                     |
| ------- | -------------------------------------- |
| 业务场景    | 它解决什么业务工作？                             |
| 核心业务对象  | 系统组织的对象是什么？                            |
| 生产产物    | 它生产什么？                                 |
| 操作空间    | 人类和 AI 在哪里操作这个产物？                      |
| AI 操作模型 | AI 在里面扮演什么角色？                          |
| 人类控制模型  | 人类如何检查、约束、批准或接管？                       |
| 状态与记忆   | 系统保留什么上下文、版本、来源、痕迹或项目状态？               |
| 交付边界    | 最终具体输出是什么？                             |
| 可复用模式   | 构建者可以把什么结构复制到自己的 AI-native OS 里？# 边界规则 |



### 一个有用区分

```text
AI Tool
= 帮你完成一个动作

AI Agent
= 帮你执行一个任务或任务链

AI-Native Production OS
= 让一个领域工作流变得可重复、可检查、可控制、可交付
```
