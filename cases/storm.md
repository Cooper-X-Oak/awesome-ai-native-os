# STORM

> Research-to-writing pipeline OS.
>
> Research-to-writing pipeline OS。

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

STORM turns a research topic into a staged knowledge-curation pipeline that discovers perspectives, asks grounded questions, builds an outline, and writes a long-form article with citations.

### Business Scene

Research / knowledge / evidence reporting, especially long-form article generation and structured topic synthesis.

### Core Business Object

A research topic transformed into collected sources, simulated perspectives, outline, sections, draft text, and citations.

### Production Artifact

Long-form article or report with citation-backed content.

### Operating Space

Research-writing pipeline.

The project is organized around a pipeline rather than an open-ended notebook: collect information, identify perspectives, simulate information-seeking conversations, outline, write, and polish.

### AI Operation Model

AI acts as a multi-stage research and writing system.

STORM retrieves information, generates questions, simulates expert-style conversations, synthesizes notes, builds article outlines, writes sections, and attaches citations.

### Human Control Model

Human control is topic and pipeline review.

The user sets the topic, configures pipeline/model/search options, reviews outlines and generated reports, and can inspect citations or generated intermediate artifacts.

### State And Memory

STORM preserves collected sources, questions, conversations, outline, generated sections, citations, and pipeline state.

### Delivery Boundary

The boundary is a long-form report/article plus the cited evidence and intermediate research state needed to inspect it.

### Same-Scene Contrast

STORM differs from NotebookLM by starting from a topic and producing a report through a pipeline.

NotebookLM starts from user-selected sources and supports interactive source-grounded exploration. STORM starts from a research goal and decomposes it into knowledge curation and writing stages.

### Reusable Pattern

Turn research writing into staged artifacts.

The reusable structure is:

1. topic intake,
2. source discovery,
3. perspective discovery,
4. question/conversation generation,
5. outline construction,
6. section drafting,
7. citation-backed report delivery.

### Reusable Recipe

1. Separate research collection from writing.
2. Generate diverse perspectives before outlining.
3. Preserve questions and evidence used to build the outline.
4. Write section-by-section rather than one-shot.
5. Carry citations through every synthesis stage.
6. Expose intermediate artifacts so humans can inspect failure points.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official Stanford OVAL repository describes STORM as an LLM-powered knowledge curation system that researches a topic and generates a full-length report with citations. | https://github.com/stanford-oval/storm | E3 |
| Official homepage/demo presents STORM as a research preview from Stanford OVAL for interactive knowledge curation. | https://storm.genie.stanford.edu/ | E3 |
| Repository topics and README position it around knowledge curation, report generation, retrieval-augmented generation, and deep research. | https://github.com/stanford-oval/storm | E3 |
| STORM paper/project material describes the system around pre-writing research, outline generation, and long-form article generation. | https://github.com/stanford-oval/storm | E3 |

### Inferred Pattern

- STORM's durable abstraction is the research pipeline, not the final article alone.
- Its OS lesson is that high-trust long-form generation needs intermediate artifacts: sources, perspectives, questions, outline, sections, citations.
- Its limitation is interaction style: it is stronger as a pipeline than as a general-purpose interactive notebook.

### Open Questions

- How well does STORM handle domains where search sources are sparse, noisy, or paywalled?
- How much human steering is needed to correct outline framing before drafting?
- Which citation checks are automated versus left to human review?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

STORM 把 research topic 变成 staged knowledge-curation pipeline：发现视角、提出 grounded questions、构建 outline，并写出带 citations 的 long-form article。

### 业务场景

研究 / 知识发现 / 证据报告，尤其是 long-form article generation 和 structured topic synthesis。

### 核心业务对象

被转换成 collected sources、simulated perspectives、outline、sections、draft text 和 citations 的 research topic。

### 生产产物

带 citation-backed content 的 long-form article 或 report。

### 操作空间

research-writing pipeline。

项目围绕 pipeline 组织，而不是 open-ended notebook：collect information、identify perspectives、simulate information-seeking conversations、outline、write、polish。

### AI 操作模型

AI 是 multi-stage research and writing system。

STORM retrieve information、generate questions、simulate expert-style conversations、synthesize notes、build article outlines、write sections，并附 citations。

### 人类控制模型

人类控制是 topic and pipeline review。

用户设置 topic，配置 pipeline/model/search options，review outlines 和 generated reports，并检查 citations 或 generated intermediate artifacts。

### 状态与记忆

STORM 保留 collected sources、questions、conversations、outline、generated sections、citations 和 pipeline state。

### 交付边界

交付边界是 long-form report/article，以及检查它所需的 cited evidence 和 intermediate research state。

### 同场景差异

STORM 和 NotebookLM 的区别在于：它从 topic 出发，通过 pipeline 生产 report。

NotebookLM 从用户选择的 sources 出发，支持交互式 source-grounded exploration。STORM 从 research goal 出发，把它拆成 knowledge curation 和 writing stages。

### 可复用模式

把 research writing 变成 staged artifacts。

可复用结构是：

1. topic intake，
2. source discovery，
3. perspective discovery，
4. question/conversation generation，
5. outline construction，
6. section drafting，
7. citation-backed report delivery。

### 可复用 Recipe

1. 把 research collection 和 writing 分开。
2. 在 outline 之前先生成 diverse perspectives。
3. 保留用于构建 outline 的 questions 和 evidence。
4. section-by-section 写作，而不是 one-shot。
5. 每个 synthesis stage 都携带 citations。
6. 暴露 intermediate artifacts，让人类能检查 failure points。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| Stanford OVAL 官方仓库把 STORM 描述为 LLM-powered knowledge curation system，可以 research topic 并生成带 citations 的 full-length report。 | https://github.com/stanford-oval/storm | E3 |
| 官方 homepage/demo 把 STORM 呈现为 Stanford OVAL 的 interactive knowledge curation research preview。 | https://storm.genie.stanford.edu/ | E3 |
| 仓库 topics 和 README 将其定位在 knowledge curation、report generation、retrieval-augmented generation 和 deep research。 | https://github.com/stanford-oval/storm | E3 |
| STORM paper/project material 围绕 pre-writing research、outline generation 和 long-form article generation 描述系统。 | https://github.com/stanford-oval/storm | E3 |

### 推断出的模式

- STORM 的稳定抽象是 research pipeline，而不只是 final article。
- 它的 OS 启发是：高信任 long-form generation 需要 intermediate artifacts：sources、perspectives、questions、outline、sections、citations。
- 它的限制是 interaction style：它更像 pipeline，而不是 general-purpose interactive notebook。

### 未确认问题

- 对 sources 稀缺、噪声高或 paywalled 的领域，STORM 表现如何？
- 在 drafting 前需要多少 human steering 来纠正 outline framing？
- 哪些 citation checks 是自动化的，哪些留给人类 review？
