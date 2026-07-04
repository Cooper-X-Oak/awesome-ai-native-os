# OpenMontage

> Pipeline-first AI-native video production OS.
>
> Pipeline-first AI 原生视频生产 OS。

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

OpenMontage turns a video brief into a staged production pipeline that an AI coding agent can operate through manifests, skills, tools, checkpoints, review gates, and render runtimes.

### Business Scene

Video / media / creative production, especially repeatable production of explainers, ads, trailers, documentary montages, shorts, podcast clips, and localized media.

### Core Business Object

A staged video production run.

The object is not just a generated clip. It includes the brief, pipeline manifest, stage plan, script, assets, provider choices, cost decisions, checkpoints, review criteria, render plan, and final media output.

### Production Artifact

A finished video or a complete production package with assets, traces, decisions, and render output.

### Operating Space

An agent-operable project repository plus a production board.

The key surface is not a traditional editor timeline. The operating space is a repo where the agent reads YAML pipeline manifests, Markdown stage skills, JSON schemas, provider configuration, Python tools, and render infrastructure. The human can inspect the run through project files, logs, checkpoints, approvals, and the Backlot board/replay surface.

### AI Operation Model

The AI coding assistant is the orchestrator.

The agent reads the pipeline contract, chooses and calls tools, generates or retrieves assets, writes scripts, plans scenes, runs validation, checkpoints state, selects render paths, and performs post-render review. Python tools and render engines are the hands; Markdown/YAML instructions are the operating manual.

### Human Control Model

Human control is stage-gated.

The human gives the initial brief, approves creative decisions, can inspect readable manifests and skills, reviews intermediate outputs, constrains budget/provider choices, and accepts or rejects the final render. Control comes from explicit contracts and checkpoints, not only from editing pixels on a canvas.

### State And Memory

OpenMontage preserves pipeline state, stage outputs, decision logs, cost snapshots, provider alternatives, assets, schemas, render runtime choices, and review traces.

This makes the production run replayable and auditable rather than a one-shot prompt result.

### Delivery Boundary

The boundary is a rendered video plus the production evidence needed to rerun, inspect, or adapt the workflow.

### Same-Scene Contrast

OpenMontage differs from OpenFlow and Descript by making the pipeline itself the primary product surface.

OpenFlow starts from a visual node graph: the user controls structure through canvas nodes and edges. Descript starts from editable media: the user controls transcript, scenes, layers, and timeline. OpenMontage starts from an agent-readable production contract: the user controls stages, gates, provider choices, and review criteria while the AI agent executes the production.

### Reusable Pattern

Turn a creative workflow into an agent-operable production contract.

The strongest reusable idea is not "AI video generation"; it is the split between:

1. executable tools,
2. pipeline manifests,
3. stage director skills,
4. schema validation,
5. checkpoints and decision logs,
6. human approval gates,
7. render/review runtimes.

### Reusable Recipe

1. Define each business scene as a pipeline manifest.
2. Give every stage an input contract, output contract, review criteria, and success gate.
3. Put execution knowledge in readable skills instead of hiding it in application code.
4. Expose tools as narrow actions that agents can call and humans can audit.
5. Persist checkpoints, costs, provider choices, and failed alternatives.
6. Add pre-delivery and post-delivery quality gates before presenting output as done.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official repository describes OpenMontage as an open-source agentic video production system and says the agent handles research, scripting, asset generation, editing, and composition. | https://github.com/calesthio/OpenMontage | E3 |
| README "How It Works" states that the AI coding assistant is the orchestrator and shows manifest, skill, tool, checkpoint, approval, render, and review stages. | https://github.com/calesthio/OpenMontage#how-it-works | E3 |
| Repository structure exposes `tools/`, `pipeline_defs/`, `skills/`, `schemas/`, `remotion-composer/`, `lib/`, and tests as separate operating layers. | https://github.com/calesthio/OpenMontage | E3 |
| Agent compatibility files target Claude Code, Cursor, Copilot, Codex, and Windsurf through shared agent guidance. | https://github.com/calesthio/OpenMontage#agent-compatibility | E3 |

### Inferred Pattern

- OpenMontage is closer to an AI-operable production operating layer than a single-purpose video app.
- Its durable abstraction is the production run: a stateful, auditable, stage-gated path from brief to rendered artifact.
- Its UI lesson is that an AI-native OS does not always need to begin with a canvas; a readable repository plus replayable board can be the operating surface.

### Open Questions

- How stable are the pipeline contracts across real production use, beyond README demos?
- Which parts are robust for non-developer creators, and which still depend on coding-agent literacy?
- How much quality comes from the architecture versus hand-authored skills and curated examples?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

OpenMontage 把一个视频需求变成分阶段 production pipeline，让 AI coding agent 通过 manifests、skills、tools、checkpoints、review gates 和 render runtimes 持续操作。

### 业务场景

视频 / 媒体 / 创意生产，尤其是 explainer、广告、trailer、documentary montage、shorts、podcast clips 和本地化媒体的可重复生产。

### 核心业务对象

分阶段视频生产 run。

这个对象不只是一个生成出来的 clip，而是包含 brief、pipeline manifest、stage plan、script、assets、provider choices、cost decisions、checkpoints、review criteria、render plan 和最终媒体输出。

### 生产产物

完成的视频，或带有素材、痕迹、决策和渲染结果的完整生产包。

### 操作空间

agent 可操作的项目仓库 + production board。

关键界面不是传统剪辑 timeline，而是一个 repo：AI 读取 YAML pipeline manifests、Markdown stage skills、JSON schemas、provider config、Python tools 和 render infrastructure。人类通过项目文件、日志、checkpoints、approvals 和 Backlot board/replay surface 来检查生产过程。

### AI 操作模型

AI coding assistant 是 orchestrator。

agent 读取 pipeline contract，选择并调用工具，生成或检索素材，写脚本，规划 scenes，运行 validation，保存 checkpoints，选择 render path，并做 post-render review。Python tools 和 render engines 是手，Markdown/YAML instructions 是操作手册。

### 人类控制模型

人类控制是 stage-gated 的。

人类给初始 brief，批准创意决策，检查可读的 manifests 和 skills，审查中间产物，约束预算和 provider choices，最后接受或拒绝 render。控制来自显式 contracts 和 checkpoints，而不只是直接在 canvas 上改像素。

### 状态与记忆

OpenMontage 保留 pipeline state、stage outputs、decision logs、cost snapshots、provider alternatives、assets、schemas、render runtime choices 和 review traces。

这让一次生产 run 成为可 replay、可审计的过程，而不是一次性 prompt 结果。

### 交付边界

交付边界是渲染完成的视频，以及足以 rerun、inspect、adapt workflow 的生产证据。

### 同场景差异

OpenMontage 和 OpenFlow、Descript 的区别在于：它把 pipeline 本身作为第一产品界面。

OpenFlow 从可视化 node graph 出发：用户通过 canvas nodes 和 edges 控制结构。Descript 从可编辑媒体出发：用户控制 transcript、scenes、layers 和 timeline。OpenMontage 从 agent-readable production contract 出发：用户控制 stages、gates、provider choices 和 review criteria，AI agent 执行生产。

### 可复用模式

把创意 workflow 变成 agent 可操作的 production contract。

最值得复用的不是“AI 视频生成”，而是这一组分层：

1. executable tools，
2. pipeline manifests，
3. stage director skills，
4. schema validation，
5. checkpoints and decision logs，
6. human approval gates，
7. render/review runtimes。

### 可复用 Recipe

1. 把每个业务场景定义成 pipeline manifest。
2. 给每个 stage 定义 input contract、output contract、review criteria 和 success gate。
3. 把执行知识写进可读 skills，而不是藏在应用代码里。
4. 把工具暴露成 agent 可调用、人类可审计的窄动作。
5. 持久化 checkpoints、costs、provider choices 和 failed alternatives。
6. 在交付前后都加质量 gates，再把产物呈现为 done。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方仓库把 OpenMontage 描述为 open-source agentic video production system，并说明 agent 处理 research、scripting、asset generation、editing 和 composition。 | https://github.com/calesthio/OpenMontage | E3 |
| README 的 How It Works 明确说 AI coding assistant 是 orchestrator，并展示 manifest、skill、tool、checkpoint、approval、render、review 阶段。 | https://github.com/calesthio/OpenMontage#how-it-works | E3 |
| 仓库结构把 `tools/`、`pipeline_defs/`、`skills/`、`schemas/`、`remotion-composer/`、`lib/` 和 tests 拆成独立操作层。 | https://github.com/calesthio/OpenMontage | E3 |
| Agent compatibility 文件面向 Claude Code、Cursor、Copilot、Codex 和 Windsurf，并指向共享 agent guidance。 | https://github.com/calesthio/OpenMontage#agent-compatibility | E3 |

### 推断出的模式

- OpenMontage 更接近 AI 可操作的 production operating layer，而不是单点视频工具。
- 它的稳定抽象是 production run：从 brief 到 rendered artifact 的有状态、可审计、stage-gated 路径。
- 它的 UI 启发是：AI-native OS 不一定必须从 canvas 开始；可读仓库 + 可 replay board 也可以成为操作界面。

### 未确认问题

- pipeline contracts 在真实生产中的稳定性如何，而不只是 README demo？
- 哪些部分适合非开发者创作者直接使用，哪些仍然依赖 coding-agent literacy？
- 质量主要来自架构，还是来自手写 skills 和精心整理的 examples？
