# NotebookLM

> Source-grounded notebook/research OS.
>
> Source-grounded notebook/research OS。

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

NotebookLM turns a user-controlled source set into a grounded research workspace where AI answers, summarizes, organizes, cites, and repackages knowledge without leaving the notebook boundary.

### Business Scene

Research / knowledge / evidence reporting, especially source-grounded reading, study, briefing, and synthesis.

### Core Business Object

A notebook made of sources, notes, questions, citations, generated summaries, and derived artifacts.

The core object is not generic web search. It is a bounded source collection that becomes the AI's operating context.

### Production Artifact

Grounded answers, study guides, notes, briefings, citations, summaries, mind maps, audio/video-style overviews, and other source-derived outputs.

### Operating Space

Notebook + source workspace.

The user imports sources, asks questions against those sources, inspects citations, saves notes, and generates derived artifacts such as Audio Overviews or other study/reporting outputs.

### AI Operation Model

AI is a source-grounded research assistant.

It retrieves from the provided sources, summarizes, compares, answers with citations, turns material into study/report artifacts, and keeps outputs anchored to the selected notebook context.

### Human Control Model

Human control is source-boundary control.

The user chooses sources, decides what belongs in the notebook, asks questions, checks citations, saves or discards notes, and controls which generated artifact becomes useful.

### State And Memory

NotebookLM preserves source set, notebook identity, notes, generated artifacts, citation state, conversation context, and source-grounded outputs.

### Delivery Boundary

The boundary is a grounded note, answer, briefing, study artifact, or exported/shareable knowledge product derived from the notebook sources.

### Same-Scene Contrast

NotebookLM differs from STORM by keeping the human in a notebook workspace rather than running a research-to-writing pipeline.

STORM is pipeline-first: it researches a topic, builds outline/sections, and produces a long-form report. NotebookLM is source-boundary-first: it operates over a user-curated source set and supports interactive Q&A and derived artifacts.

### Reusable Pattern

Constrain AI with a user-owned evidence boundary.

The reusable structure is:

1. explicit source set,
2. notebook container,
3. retrieval and citation grounding,
4. note/answer artifacts,
5. generated study/report formats,
6. human source curation,
7. citation-visible outputs.

### Reusable Recipe

1. Make sources the first object users create.
2. Keep AI answers inside the selected source boundary by default.
3. Show citations next to claims.
4. Let users save outputs back into the notebook.
5. Provide multiple derived artifact formats for the same source set.
6. Treat source curation as the main human control point.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official site describes NotebookLM as a personalized AI research assistant grounded in user-provided sources. | https://notebooklm.google/ | E3 |
| Google Help describes adding sources and using notebooks to ask questions, summarize, and work with uploaded material. | https://support.google.com/notebooklm/ | E3 |
| Official materials describe citations and source-grounded answers as part of the NotebookLM experience. | https://notebooklm.google/ | E3 |
| Official product pages and Help Center describe generated artifacts such as Audio Overviews and study-oriented outputs. | https://support.google.com/notebooklm/ | E3 |

### Inferred Pattern

- NotebookLM's durable abstraction is the bounded source set, not the chat.
- Its OS lesson is that evidence boundaries and visible citations are interaction architecture, not just safety features.
- Its tradeoff is that usefulness depends heavily on source quality and source selection.

### Open Questions

- How well can NotebookLM preserve citation reliability across long multi-source synthesis?
- What project/state export options are available for teams that need durable research handoff?
- How much of the notebook workflow can be automated or integrated into external research pipelines?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

NotebookLM 把用户控制的 source set 变成 grounded research workspace，让 AI 在 notebook boundary 内回答、总结、组织、引用并重新包装知识。

### 业务场景

研究 / 知识发现 / 证据报告，尤其是 source-grounded reading、study、briefing 和 synthesis。

### 核心业务对象

由 sources、notes、questions、citations、generated summaries 和 derived artifacts 组成的 notebook。

核心对象不是泛化 web search，而是一个 bounded source collection，成为 AI 的 operating context。

### 生产产物

grounded answers、study guides、notes、briefings、citations、summaries、mind maps、audio/video-style overviews，以及其他 source-derived outputs。

### 操作空间

notebook + source workspace。

用户导入 sources，围绕这些 sources 提问，检查 citations，保存 notes，并生成 Audio Overviews 等 study/reporting artifacts。

### AI 操作模型

AI 是 source-grounded research assistant。

它从用户提供的 sources 中 retrieve、summarize、compare，带 citations 回答，把材料转换成 study/report artifacts，并让输出保持锚定在选中的 notebook context。

### 人类控制模型

人类控制是 source-boundary control。

用户选择 sources，决定什么进入 notebook，提问，检查 citations，保存或丢弃 notes，并控制哪个 generated artifact 有用。

### 状态与记忆

NotebookLM 保留 source set、notebook identity、notes、generated artifacts、citation state、conversation context 和 source-grounded outputs。

### 交付边界

交付边界是从 notebook sources 派生出的 grounded note、answer、briefing、study artifact 或可分享 knowledge product。

### 同场景差异

NotebookLM 和 STORM 的区别在于：它让人停留在 notebook workspace，而不是运行 research-to-writing pipeline。

STORM 是 pipeline-first：研究 topic，构建 outline/sections，并产出 long-form report。NotebookLM 是 source-boundary-first：它在用户整理的 source set 上操作，支持交互式 Q&A 和 derived artifacts。

### 可复用模式

用用户拥有的 evidence boundary 约束 AI。

可复用结构是：

1. explicit source set，
2. notebook container，
3. retrieval and citation grounding，
4. note/answer artifacts，
5. generated study/report formats，
6. human source curation，
7. citation-visible outputs。

### 可复用 Recipe

1. 让 sources 成为用户创建的第一个对象。
2. 默认让 AI answers 留在 selected source boundary 内。
3. 在 claims 旁展示 citations。
4. 允许用户把 outputs 保存回 notebook。
5. 为同一 source set 提供多种 derived artifact formats。
6. 把 source curation 作为主要人类控制点。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方网站把 NotebookLM 描述为 grounded in user-provided sources 的 personalized AI research assistant。 | https://notebooklm.google/ | E3 |
| Google Help 描述添加 sources、使用 notebooks 提问、总结并处理上传材料。 | https://support.google.com/notebooklm/ | E3 |
| 官方材料把 citations 和 source-grounded answers 作为 NotebookLM experience 的一部分。 | https://notebooklm.google/ | E3 |
| 官方产品页和 Help Center 描述 Audio Overviews 等 generated artifacts 和 study-oriented outputs。 | https://support.google.com/notebooklm/ | E3 |

### 推断出的模式

- NotebookLM 的稳定抽象是 bounded source set，而不是 chat。
- 它的 OS 启发是：evidence boundaries 和 visible citations 是 interaction architecture，而不只是 safety features。
- 它的 tradeoff 是：效果高度依赖 source quality 和 source selection。

### 未确认问题

- NotebookLM 在长篇 multi-source synthesis 中能多可靠地保持 citation reliability？
- 需要 durable research handoff 的团队，有哪些 project/state export options？
- notebook workflow 有多少可以自动化或接入外部 research pipelines？
