# CodeG

> Multi-agent coding session OS.
>
> Multi-agent coding session OS。

## Language

- [English](#english)
- [中文](#中文)

---

## English

### Case Status

standard

### Evidence Level

E3 strong

### One-Line Positioning

CodeG turns multiple AI coding agents and terminal sessions into a collaborative coding workspace where humans can aggregate, supervise, route, and inspect parallel agent work.

### Business Scene

Software engineering / code delivery, especially multi-agent coding, agent session management, and self-hosted coding operations.

### Core Business Object

A set of coding sessions attached to repositories, worktrees, agents, messages, tasks, and outputs.

The core object is not a single chat. It is the operational state of many coding agents working on codebases under human supervision.

### Production Artifact

Code changes, task outputs, session transcripts, repository updates, and agent-delivered work.

### Operating Space

Collaborative multi-agent coding workspace.

The public repo positions CodeG as a desktop app, self-hosted server, or Docker-deployable workspace that aggregates sessions from Claude Code, Codex, OpenCode, Pi, and similar agents.

### AI Operation Model

AI agents remain specialized workers, while CodeG provides the operating layer around them.

The system's role is not to replace every coding agent with one model. It manages sessions, repo/worktree context, agent outputs, and communication surfaces so multiple agents can be used in parallel.

### Human Control Model

Human control is supervisory.

The human starts sessions, assigns or monitors work, checks agent outputs, compares progress across agents, inspects repository state, and decides what work should be accepted or continued.

### State And Memory

CodeG preserves session state, repository/worktree state, agent outputs, messages, task traces, integrations, and workspace-level coordination context.

### Delivery Boundary

The delivery boundary is code work that can be inspected and merged, plus the session evidence needed to understand how it was produced.

### Same-Scene Contrast

CodeG differs from Devin by focusing on many-agent session orchestration rather than one autonomous task-to-PR worker.

Devin is task-delivery-first: a user delegates an engineering task and reviews the result. CodeG is workspace-first: a user operates many coding agents/sessions and coordinates them. Both are AI-native engineering OS patterns, but their core control objects are different.

### Reusable Pattern

Treat AI coding agents as sessions that need an operating workspace.

The reusable structure is:

1. session registry,
2. repo/worktree binding,
3. agent adapter layer,
4. message/output capture,
5. human supervision surface,
6. multi-channel integrations,
7. mergeable code boundary.

### Reusable Recipe

1. Do not reduce AI coding to one chat transcript.
2. Model each agent run as a session with repo, task, state, output, and owner.
3. Keep repository/worktree state visible next to messages.
4. Support multiple agent backends through adapters.
5. Preserve session traces so humans can audit results.
6. Make accepted output flow back into normal Git/code review paths.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official repository describes CodeG as a collaborative multi-agent AI coding workspace aggregating sessions from Claude Code, Codex, OpenCode, Pi, and others. | https://github.com/xintaofei/codeg | E3 |
| GitHub metadata describes desktop app, self-hosted server, and Docker deployment modes. | https://github.com/xintaofei/codeg | E3 |
| Repository topics include agent, Claude Code, Codex, Gemini CLI, OpenCode, worktree, Git, GUI, and messaging integrations. | https://github.com/xintaofei/codeg | E3 |

### Inferred Pattern

- CodeG's durable abstraction is the coding session as a manageable operating object.
- Its OS lesson is that agent productivity depends on supervision, routing, and state visibility, not only model quality.
- Its public evidence is official but less mature than large SaaS products, so production-readiness claims should remain conservative.

### Open Questions

- How deeply does CodeG understand code/repo state versus aggregating external agent sessions?
- What conflict-resolution model exists when multiple agents touch related code?
- How much review automation is built in before work reaches Git/PR boundaries?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

CodeG 把多个 AI coding agents 和 terminal sessions 变成 collaborative coding workspace，让人类可以聚合、监督、路由并检查并行 agent work。

### 业务场景

软件工程 / 代码交付，尤其是 multi-agent coding、agent session management 和 self-hosted coding operations。

### 核心业务对象

绑定到 repositories、worktrees、agents、messages、tasks 和 outputs 的一组 coding sessions。

核心对象不是单个 chat，而是多个 coding agents 在人类监督下操作代码库的运行状态。

### 生产产物

code changes、task outputs、session transcripts、repository updates 和 agent-delivered work。

### 操作空间

协作式 multi-agent coding workspace。

官方仓库把 CodeG 定位为 desktop app、self-hosted server 或 Docker-deployable workspace，用来聚合 Claude Code、Codex、OpenCode、Pi 等 agent 的 sessions。

### AI 操作模型

AI agents 仍然是 specialized workers，CodeG 提供围绕它们的 operating layer。

系统角色不是用一个模型替代所有 coding agent，而是管理 sessions、repo/worktree context、agent outputs 和 communication surfaces，让多个 agents 可以并行使用。

### 人类控制模型

人类控制是 supervisory。

人类启动 sessions，分配或监控工作，检查 agent outputs，对比 agents 进展，检查 repository state，并决定哪些工作接受或继续。

### 状态与记忆

CodeG 保留 session state、repository/worktree state、agent outputs、messages、task traces、integrations 和 workspace-level coordination context。

### 交付边界

交付边界是可检查、可 merge 的 code work，以及理解其生产过程所需的 session evidence。

### 同场景差异

CodeG 和 Devin 的区别在于：它关注 many-agent session orchestration，而不是单个 autonomous task-to-PR worker。

Devin 是 task-delivery-first：用户委派工程任务并 review 结果。CodeG 是 workspace-first：用户操作许多 coding agents/sessions 并协调它们。二者都是 AI-native engineering OS pattern，但核心控制对象不同。

### 可复用模式

把 AI coding agents 视为需要 operating workspace 管理的 sessions。

可复用结构是：

1. session registry，
2. repo/worktree binding，
3. agent adapter layer，
4. message/output capture，
5. human supervision surface，
6. multi-channel integrations，
7. mergeable code boundary。

### 可复用 Recipe

1. 不要把 AI coding 简化成一个 chat transcript。
2. 把每次 agent run 建模成带 repo、task、state、output、owner 的 session。
3. 让 repository/worktree state 和 messages 一起可见。
4. 通过 adapters 支持多个 agent backends。
5. 保留 session traces，让人类可以 audit results。
6. 让被接受的 output 回到正常 Git/code review 路径。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方仓库把 CodeG 描述为 collaborative multi-agent AI coding workspace，聚合 Claude Code、Codex、OpenCode、Pi 等 sessions。 | https://github.com/xintaofei/codeg | E3 |
| GitHub metadata 描述 desktop app、self-hosted server 和 Docker deployment modes。 | https://github.com/xintaofei/codeg | E3 |
| 仓库 topics 包含 agent、Claude Code、Codex、Gemini CLI、OpenCode、worktree、Git、GUI 和 messaging integrations。 | https://github.com/xintaofei/codeg | E3 |

### 推断出的模式

- CodeG 的稳定抽象是 coding session as manageable operating object。
- 它的 OS 启发是：agent productivity 依赖 supervision、routing 和 state visibility，而不只是模型质量。
- 它的公开证据来自官方仓库，但成熟度低于大型 SaaS，所以 production-readiness 结论应保守。

### 未确认问题

- CodeG 对 code/repo state 的理解有多深，还是主要聚合外部 agent sessions？
- 多个 agents 修改相关代码时，冲突解决模型是什么？
- 工作到达 Git/PR 边界前，内置了多少 review automation？
