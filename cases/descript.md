# Descript

> Transcript/timeline-first AI-native media editing OS.
>
> Transcript/timeline-first AI 原生媒体编辑 OS。

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

Descript turns audio/video into text-addressable, scene-addressable, and timeline-addressable media objects, then lets humans and AI co-edit those objects through the editor, Underlord, API, and MCP integrations.

### Business Scene

Video / media / creative production, especially podcast editing, talking-head video, screen recordings, social clips, captions, dubbing, cleanup, and repurposing.

### Core Business Object

A media project composed of transcript, scenes, layers, timeline, assets, edits, speakers, captions, and export targets.

The core object is not a raw video file. It is an editable composition where speech, visuals, layout, audio cleanup, B-roll, captions, clips, and publishing state are all addressable.

### Production Artifact

Edited video, audio, clips, captions, translations, share pages, or downloadable exports.

Descript can also produce intermediate artifacts such as rough cuts, social clips, generated B-roll, cleaned audio, and captioned versions.

### Operating Space

Transcript + scene editor + timeline + AI/action sidebar + API/MCP surface.

The human-facing editor combines a script editor for text-based media edits, a scene editor for visual layers, a timeline for precise timing and trimming, and sidebars for layouts, media, AI tools, and Underlord. The automation-facing surface exposes similar work through the Descript API and MCP-compatible integrations.

### AI Operation Model

AI acts as a co-editor and production operator.

Underlord handles editing instructions inside the product. Descript's AI tools cover cleanup, clip finding, captions, generative media, translation/dubbing, layout and video design assistance, and other editing actions. The API extends this into external automation: importing media, applying edits, creating clips, captions, rough cuts, Studio Sound, translations, and publishing/download flows.

### Human Control Model

Human control is direct manipulation plus review.

The user can edit by changing transcript text, manipulating scenes and layers, trimming in the timeline, selecting layers or ranges, asking Underlord to perform operations, reviewing results, and exporting or publishing only after inspection. AI proposes or executes edits, but the user keeps project-level editorial control.

### State And Memory

Descript preserves transcript alignment, scenes, layers, media assets, timeline edits, AI actions, generated assets, speakers, captions, project versions, and export targets.

The key state shift is that media becomes addressable by text and composition structure, not just by frame time.

### Delivery Boundary

The delivery boundary can be a rendered file, share page, clip set, captioned/dubbed variant, or automated export URL.

For AI-native OS design, this matters because the same project can serve both interactive editing and automated production workflows.

### Same-Scene Contrast

Descript differs from OpenMontage and OpenFlow by starting from editable media rather than a production contract or generation graph.

OpenMontage is best read as pipeline-first: the system stages work before the final video exists. OpenFlow is graph-first: the system composes generation steps across providers. Descript is transcript/timeline-first: the system turns existing or recorded media into structured objects that humans and AI can edit.

### Reusable Pattern

Make opaque media addressable.

Descript's reusable idea is to convert a hard-to-operate artifact into multiple synchronized control planes:

1. transcript as semantic control,
2. scenes and layers as visual composition control,
3. timeline as precision control,
4. AI actions as operation shortcuts,
5. API/MCP as external automation,
6. export/share targets as delivery control.

### Reusable Recipe

1. Transform raw media into a structured project model before AI operates on it.
2. Give users more than one control plane: text, visual composition, timeline, and automation.
3. Keep AI actions grounded in editable project objects rather than only prompt output.
4. Preserve alignment between transcript, timeline, scenes, captions, and exports.
5. Expose the same production actions through UI and API/MCP when possible.
6. Make generated or automated edits reviewable before final delivery.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official homepage describes Descript as a video/audio editor where editing is as easy as typing, with recording, transcription, editing, publishing, and AI video editing. | https://www.descript.com/ | E3 |
| Official Underlord page describes Underlord as Descript's AI video and podcast editing assistant for clips, show notes, audio fixes, and edits. | https://www.descript.com/underlord | E3 |
| Official AI video page describes Underlord as an AI co-editor that can create or edit video under user direction. | https://www.descript.com/ai-video | E3 |
| Descript API docs state the API can create projects, import media, and edit projects without opening the app. | https://docs.descriptapi.com/ | E3 |
| Official API page positions the API for automated video workflows, clips, captions, rough cuts, Studio Sound, translation, dubbing, publishing, and download URLs. | https://www.descript.com/api | E3 |

### Inferred Pattern

- Descript's durable abstraction is the editable media project, not the transcript alone.
- Its architecture bridges manual editing and automated production because the same underlying project object can be operated through UI, Underlord, API, and MCP.
- Its UI lesson is that AI-native media systems work best when AI actions land on inspectable objects: text, layers, scenes, timeline ranges, clips, captions, and exports.

### Open Questions

- Which Underlord/API actions are stable enough for high-volume production without manual repair?
- How much of Descript's internal project model is accessible to external automation versus locked inside the editor?
- Can the transcript/timeline abstraction handle highly visual, non-speech-heavy video as well as speech-led content?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

Descript 把音视频变成 text-addressable、scene-addressable、timeline-addressable 的媒体对象，再让人类和 AI 通过 editor、Underlord、API、MCP integrations 共同编辑这些对象。

### 业务场景

视频 / 媒体 / 创意生产，尤其是 podcast editing、talking-head video、screen recordings、social clips、captions、dubbing、cleanup 和 repurposing。

### 核心业务对象

由 transcript、scenes、layers、timeline、assets、edits、speakers、captions 和 export targets 组成的 media project。

核心对象不是原始视频文件，而是一个 editable composition：speech、visuals、layout、audio cleanup、B-roll、captions、clips 和 publishing state 都可以被寻址和操作。

### 生产产物

编辑后的视频、音频、clips、captions、translations、share pages 或 downloadable exports。

Descript 也可以生产中间产物，例如 rough cuts、social clips、generated B-roll、cleaned audio 和 captioned versions。

### 操作空间

transcript + scene editor + timeline + AI/action sidebar + API/MCP surface。

面向人的 editor 结合了用于文本化媒体编辑的 script editor、用于 visual layers 的 scene editor、用于精确 timing/trimming 的 timeline，以及 layouts、media、AI tools、Underlord 等 sidebar。面向自动化的表面，则通过 Descript API 和 MCP-compatible integrations 暴露类似能力。

### AI 操作模型

AI 扮演 co-editor 和 production operator。

Underlord 在产品内处理编辑指令。Descript 的 AI tools 覆盖 cleanup、clip finding、captions、generative media、translation/dubbing、layout/video design assistance 等编辑动作。API 把这些延伸到外部自动化：import media、apply edits、create clips、captions、rough cuts、Studio Sound、translations、publishing/download flows。

### 人类控制模型

人类控制是 direct manipulation + review。

用户可以通过改 transcript text、操作 scenes 和 layers、在 timeline 里 trim、选择 layers 或 ranges、让 Underlord 执行动作、审查结果、最后 export 或 publish。AI 可以建议或执行编辑，但用户保留 project-level editorial control。

### 状态与记忆

Descript 保留 transcript alignment、scenes、layers、media assets、timeline edits、AI actions、generated assets、speakers、captions、project versions 和 export targets。

关键状态变化是：媒体不再只能按 frame time 操作，也可以按文本和 composition structure 操作。

### 交付边界

交付边界可以是 rendered file、share page、clip set、captioned/dubbed variant 或 automated export URL。

对 AI-native OS 设计来说，这一点重要：同一个 project 可以同时支撑交互式编辑和自动化生产 workflow。

### 同场景差异

Descript 和 OpenMontage、OpenFlow 的区别在于：它从可编辑媒体出发，而不是从 production contract 或 generation graph 出发。

OpenMontage 是 pipeline-first：系统在最终视频存在前先分阶段组织生产。OpenFlow 是 graph-first：系统跨 providers 编排生成步骤。Descript 是 transcript/timeline-first：系统把已有或录制媒体变成结构化对象，让人类和 AI 都能编辑。

### 可复用模式

让不透明媒体变得可寻址。

Descript 最值得复用的想法，是把一个难以操作的 artifact 转换成多个同步控制平面：

1. transcript 作为 semantic control，
2. scenes 和 layers 作为 visual composition control，
3. timeline 作为 precision control，
4. AI actions 作为 operation shortcuts，
5. API/MCP 作为 external automation，
6. export/share targets 作为 delivery control。

### 可复用 Recipe

1. 先把 raw media 转成 structured project model，再让 AI 操作。
2. 给用户不止一种控制平面：文本、视觉 composition、timeline 和自动化。
3. 让 AI actions 落到可编辑 project objects 上，而不是只生成 prompt output。
4. 保持 transcript、timeline、scenes、captions 和 exports 之间的 alignment。
5. 尽量通过 UI 和 API/MCP 暴露同一组 production actions。
6. 让生成或自动化编辑在最终交付前可审查。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方首页把 Descript 描述为 editing is as easy as typing 的 video/audio editor，覆盖 recording、transcription、editing、publishing 和 AI video editing。 | https://www.descript.com/ | E3 |
| 官方 Underlord 页面把 Underlord 描述为 Descript 的 AI video and podcast editing assistant，用于 clips、show notes、audio fixes 和 edits。 | https://www.descript.com/underlord | E3 |
| 官方 AI video 页面把 Underlord 描述为可在用户指令下 create 或 edit video 的 AI co-editor。 | https://www.descript.com/ai-video | E3 |
| Descript API docs 说明 API 可以 create projects、import media，并在不打开 app 的情况下 edit projects。 | https://docs.descriptapi.com/ | E3 |
| 官方 API page 把 API 定位为自动化视频 workflow，可做 clips、captions、rough cuts、Studio Sound、translation、dubbing、publishing 和 download URLs。 | https://www.descript.com/api | E3 |

### 推断出的模式

- Descript 的稳定抽象是 editable media project，而不只是 transcript。
- 它能连接 manual editing 和 automated production，因为同一个底层 project object 可以被 UI、Underlord、API、MCP 操作。
- 它的 UI 启发是：AI-native media system 最好让 AI actions 落在可检查对象上：text、layers、scenes、timeline ranges、clips、captions 和 exports。

### 未确认问题

- 哪些 Underlord/API actions 足够稳定，可以支撑高频生产而不需要大量人工返修？
- Descript 内部 project model 有多少能被外部自动化访问，多少仍然锁在 editor 里？
- transcript/timeline 抽象是否同样适合高度视觉化、非 speech-led 的视频？
