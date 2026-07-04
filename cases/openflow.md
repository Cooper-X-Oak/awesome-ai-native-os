# OpenFlow

> Node-canvas-first multimodal AI production OS.
>
> Node-canvas-first 多模态 AI 生产 OS。

## Language

- [English](#english)
- [中文](#中文)

---

## English

### Case Status

standard

### Evidence Level

E2 medium

### One-Line Positioning

OpenFlow turns multimodal AI production into an editable node canvas where humans compose generation pipelines and an AI canvas agent can add nodes, choose models, connect steps, run generations, and organize outputs.

### Business Scene

Video / media / creative production, with emphasis on generative image, video, audio, and text workflows.

### Core Business Object

A multimodal generation graph.

The core object is a typed workflow made of nodes, edges, prompts, provider choices, parameters, intermediate results, annotations, and exported JSON workflow state.

### Production Artifact

Generated media assets and reusable generation workflows.

The artifact may be a final image, video, audio clip, text output, or a saved graph that can be rerun, shared, or used as a preset.

### Operating Space

A visual node canvas.

The user drags nodes onto an infinite canvas, connects compatible handles, configures model and generation parameters, runs nodes or full workflows, reviews generated outputs, annotates results, and saves or imports workflow JSON.

### AI Operation Model

The AI operates inside the canvas rather than outside it.

OpenFlow's README describes `openAgent` as an AI agent inside the Flow canvas. The intended model is conversational canvas control: describe the desired result, and the agent can add nodes, pick models, connect pipelines, run generations, and organize output.

### Human Control Model

Human control is structural and visual.

The human decides graph topology, node parameters, connection rules, execution timing, grouping, locks, annotations, review marks, and whether a workflow is reusable. AI can assist in constructing and running the graph, but the graph remains visible and editable.

### State And Memory

OpenFlow preserves workflow graph state, node configuration, generation history, annotations, run state, and import/export JSON.

This makes creative generation repeatable at the workflow level instead of only the prompt level.

### Delivery Boundary

The boundary is either a generated multimodal asset or a reusable workflow graph.

This is different from a timeline editor: a run can stop at any intermediate node if the output is valuable, and the graph itself can be the reusable deliverable.

### Same-Scene Contrast

OpenFlow differs from OpenMontage and Descript by treating graph topology as the main control surface.

OpenMontage is pipeline-contract-first: it optimizes for staged, auditable production runs. Descript is transcript/timeline-first: it optimizes for editing existing or recorded media through text, scenes, and timeline. OpenFlow is node-canvas-first: it optimizes for composing generative steps across providers and modalities.

### Reusable Pattern

Represent AI production as a typed graph.

The reusable structure is:

1. nodes as AI/tool actions,
2. typed handles as compatibility rules,
3. edges as artifact routing,
4. node-local parameters as human control points,
5. run state as operational feedback,
6. JSON export as portability,
7. AI canvas agent as graph co-builder.

### Reusable Recipe

1. Model every AI action as a node with explicit inputs, outputs, parameters, and provider binding.
2. Use typed handles so humans can see which artifacts can flow into which actions.
3. Store intermediate outputs on nodes instead of only keeping the final result.
4. Make run state visible at node level and workflow level.
5. Let users export/import workflow state as JSON.
6. Add a canvas agent that edits the same graph the human sees.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| GitHub repository description says OpenFlow is an open-source node-based AI studio for images, video, audio, and text, with local/cloud models and an AI canvas agent named `openAgent`. | https://github.com/nazihkhelifa/openflow | E2 |
| README lists visual node editor, multi-provider models, workflow chaining, saving/sharing JSON, and execution controls. | https://github.com/nazihkhelifa/openflow#features | E2 |
| README lists Next.js 16, TypeScript, React Flow, Konva/react-konva, Zustand, Tailwind CSS, Gemini, OpenAI, Replicate, and fal.ai. | https://github.com/nazihkhelifa/openflow#tech-stack | E2 |
| Repository is public and active but currently low maturity by public signals, so claims should remain conservative. | https://github.com/nazihkhelifa/openflow | E1 |

### Inferred Pattern

- OpenFlow's durable abstraction is the generation graph, not any single provider or model.
- Its UI lesson is that AI-native production can expose model orchestration as a visible, editable object instead of hiding it behind chat.
- Its risk is maturity: the architecture is clear, but public adoption and production hardening are not yet proven by the current evidence.

### Open Questions

- How much can `openAgent` reliably edit and execute complex graphs today?
- Are graph runs deterministic and replayable enough for production workflows?
- Does the canvas scale when workflows include many media assets, large histories, or collaborative review?

---

## 中文

### 案例状态

standard

### 证据等级

E2 中

### 一句话定位

OpenFlow 把多模态 AI 生产变成可编辑 node canvas：人类编排生成 pipeline，AI canvas agent 可以添加节点、选择模型、连接步骤、运行生成并整理输出。

### 业务场景

视频 / 媒体 / 创意生产，重点是生成式图像、视频、音频和文本 workflow。

### 核心业务对象

多模态生成 graph。

核心对象是由 nodes、edges、prompts、provider choices、parameters、intermediate results、annotations 和导出的 JSON workflow state 组成的 typed workflow。

### 生产产物

生成的媒体资产和可复用 generation workflows。

产物可以是最终 image、video、audio clip、text output，也可以是一个可 rerun、share、作为 preset 使用的 saved graph。

### 操作空间

可视化 node canvas。

用户把节点拖到 infinite canvas，连接兼容 handles，配置 model 和 generation parameters，运行单个节点或整条 workflow，审查生成结果，给结果做 annotations，并保存或导入 workflow JSON。

### AI 操作模型

AI 在 canvas 内部操作，而不是站在 canvas 外面。

OpenFlow 的 README 把 `openAgent` 描述为 Flow canvas 内部的 AI agent。它的目标模型是 conversational canvas control：用户描述想要的结果，agent 可以添加节点、选择模型、连接 pipeline、运行生成并整理输出。

### 人类控制模型

人类控制是结构化、可视化的。

人类决定 graph topology、node parameters、connection rules、execution timing、grouping、locks、annotations、review marks，以及 workflow 是否可复用。AI 可以协助构建和运行 graph，但 graph 仍然是可见、可编辑对象。

### 状态与记忆

OpenFlow 保留 workflow graph state、node configuration、generation history、annotations、run state 和 import/export JSON。

这让创意生成在 workflow 层面可重复，而不只是 prompt 层面可重复。

### 交付边界

交付边界可以是生成的多模态资产，也可以是可复用 workflow graph。

这和 timeline editor 不同：一次 run 可以停在任何有价值的中间节点，graph 本身也可以成为可复用交付物。

### 同场景差异

OpenFlow 和 OpenMontage、Descript 的区别在于：它把 graph topology 当作主要控制界面。

OpenMontage 是 pipeline-contract-first：优化分阶段、可审计的生产 run。Descript 是 transcript/timeline-first：优化通过文本、scenes 和 timeline 编辑已有或录制媒体。OpenFlow 是 node-canvas-first：优化跨 provider、跨 modality 的生成步骤编排。

### 可复用模式

把 AI production 表示成 typed graph。

可复用结构是：

1. nodes 是 AI/tool actions，
2. typed handles 是 compatibility rules，
3. edges 是 artifact routing，
4. node-local parameters 是人类控制点，
5. run state 是操作反馈，
6. JSON export 是可移植性，
7. AI canvas agent 是 graph co-builder。

### 可复用 Recipe

1. 把每个 AI action 建模成有明确 inputs、outputs、parameters 和 provider binding 的 node。
2. 用 typed handles 让人类看见哪些 artifact 可以流向哪些 action。
3. 把 intermediate outputs 保存在节点上，而不是只保留最终结果。
4. 让 run state 在 node level 和 workflow level 都可见。
5. 允许用户把 workflow state 导出/导入为 JSON。
6. 加一个能编辑同一张可视 graph 的 canvas agent。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| GitHub 仓库描述说 OpenFlow 是 open-source node-based AI studio，面向 images、video、audio、text，支持本地/云模型，并带有名为 `openAgent` 的 AI canvas agent。 | https://github.com/nazihkhelifa/openflow | E2 |
| README 列出 visual node editor、multi-provider models、workflow chaining、saving/sharing JSON 和 execution controls。 | https://github.com/nazihkhelifa/openflow#features | E2 |
| README 列出 Next.js 16、TypeScript、React Flow、Konva/react-konva、Zustand、Tailwind CSS、Gemini、OpenAI、Replicate 和 fal.ai。 | https://github.com/nazihkhelifa/openflow#tech-stack | E2 |
| 仓库公开且在开发中，但从公开信号看成熟度较低，所以结论需要保守。 | https://github.com/nazihkhelifa/openflow | E1 |

### 推断出的模式

- OpenFlow 的稳定抽象是 generation graph，而不是某个 provider 或 model。
- 它的 UI 启发是：AI-native production 可以把模型编排暴露成可见、可编辑对象，而不是藏在 chat 后面。
- 它的风险是成熟度：架构方向清楚，但当前证据还不足以证明生产级硬化和大规模采用。

### 未确认问题

- `openAgent` 当前能多可靠地编辑和执行复杂 graph？
- graph runs 是否足够 deterministic 和 replayable，能支撑生产 workflow？
- 当 workflow 包含很多媒体资产、大量历史记录或协作审查时，canvas 是否仍然可扩展？
