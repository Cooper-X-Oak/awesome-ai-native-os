# Onlook

> Canvas/design-first AI-native React UI OS.
>
> Canvas/design-first AI 原生 React UI OS。

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

Onlook turns a running React app into a design-canvas operating space where designers and AI can visually inspect, select, edit, style, and write changes back to code.

### Business Scene

UI design to code, front-end iteration, design-system implementation, and React/Tailwind app editing.

### Core Business Object

A live React interface mapped back to source code.

The core object is not a Figma mockup or a code file alone. It is the synchronized relationship between DOM elements, component hierarchy, Tailwind styles, generated edits, and source locations.

### Production Artifact

Updated React UI code, components, pages, and visual styles.

### Operating Space

Visual editor over a running local app.

Onlook's docs describe a canvas, layers panel, properties panel, style editor, code panel, and AI chat. Its architecture docs explain that Onlook acts like a browser pointed at localhost, manipulates DOM/CSS, then writes persistent changes back to code through source mapping and AST edits.

### AI Operation Model

AI works as a design/code co-editor.

It can generate components from descriptions, suggest improvements, convert designs to code, and help debug issues. The important architectural move is that AI acts on selected visual/code objects, not only on free-form prompts.

### Human Control Model

Human control is visual selection plus code review.

The user selects elements on the canvas, inspects hierarchy and properties, edits Tailwind styles, sees code changes, asks AI for modifications, and keeps the ability to inspect or edit generated code directly.

### State And Memory

Onlook preserves project structure, live component hierarchy, selected DOM targets, style changes, code mappings, AI chat context, and generated code patches.

### Delivery Boundary

The boundary is committed or exported React code that reflects visual edits made on the live app surface.

### Same-Scene Contrast

Onlook differs from Dyad and bolt.diy because its first-class object is an existing UI surface, not a blank app-generation session.

Dyad and bolt.diy are app-builder workspaces: they optimize from idea or prompt to runnable project. Onlook is design-to-code: it optimizes from visible component to code-backed visual change.

### Reusable Pattern

Make the live product surface itself the shared human-AI workspace.

The reusable structure is:

1. visual target selection,
2. component/layer hierarchy,
3. property/style controls,
4. source-code mapping,
5. AST-backed write-to-code,
6. AI chat grounded in selected objects,
7. immediate preview and code review.

### Reusable Recipe

1. Run the user's real app inside an inspectable browser surface.
2. Inject source-location metadata so UI elements map back to code.
3. Let humans select, style, and inspect visual objects directly.
4. Let AI operate on selected components and project context.
5. Keep visual edits temporary until written back to code.
6. Present code diffs as the delivery boundary, not just a visual mockup.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official repository describes Onlook as "The Cursor for Designers" and an AI-first design tool for visually building, styling, and editing React apps. | https://github.com/onlook-dev/onlook | E3 |
| Official docs describe the visual editor, code integration, AI assistance, and Figma-to-Onlook flow. | https://docs.onlook.com/getting-started/core-features | E3 |
| Official UI overview lists canvas, layers panel, properties panel, style editor, code panel, and AI chat. | https://docs.onlook.com/getting-started/ui-overview | E3 |
| Official architecture docs explain DOM/CSS manipulation, source mapping, AST parsing, and write-back to code. | https://docs.onlook.com/developers/architecture | E3 |

### Inferred Pattern

- Onlook's durable abstraction is the visible component as a code-addressable object.
- Its AI-native OS lesson is that design operations become safer when every visual action has a route back to source code.
- Its likely constraint is framework scope: the strongest pattern currently centers on React and Tailwind-style UI work.

### Open Questions

- How well does source mapping survive complex component abstractions, generated class names, and runtime conditional rendering?
- Can the visual editor preserve design-system constraints rather than only applying local style changes?
- How robust is AI edit quality on large production codebases with custom component libraries?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

Onlook 把正在运行的 React app 变成 design-canvas 操作空间，让设计师和 AI 可以可视化 inspect、select、edit、style，并把变更写回代码。

### 业务场景

UI design to code、前端迭代、design-system implementation 和 React/Tailwind app editing。

### 核心业务对象

映射回源代码的 live React interface。

核心对象不是 Figma mockup，也不是单独的代码文件，而是 DOM elements、component hierarchy、Tailwind styles、generated edits 和 source locations 之间的同步关系。

### 生产产物

更新后的 React UI code、components、pages 和 visual styles。

### 操作空间

覆盖在本地运行 app 上的 visual editor。

Onlook 文档描述了 canvas、layers panel、properties panel、style editor、code panel 和 AI chat。它的 architecture docs 说明 Onlook 像一个指向 localhost 的 browser，可以操作 DOM/CSS，再通过 source mapping 和 AST edits 把持久化变更写回代码。

### AI 操作模型

AI 是 design/code co-editor。

它可以根据描述生成 components、提出改进建议、把设计转成代码，并帮助 debug。关键架构点是：AI 操作的是被选中的视觉/代码对象，而不只是自由 prompt。

### 人类控制模型

人类控制是 visual selection + code review。

用户在 canvas 上选择元素，检查 hierarchy 和 properties，编辑 Tailwind styles，查看代码变化，让 AI 修改，并保留直接检查或编辑生成代码的能力。

### 状态与记忆

Onlook 保留 project structure、live component hierarchy、selected DOM targets、style changes、code mappings、AI chat context 和 generated code patches。

### 交付边界

交付边界是反映 live app 视觉编辑结果的 React code commit/export，而不只是视觉稿。

### 同场景差异

Onlook 和 Dyad、bolt.diy 的区别在于：它的一等对象是已有 UI surface，而不是从零开始的 app-generation session。

Dyad 和 bolt.diy 是 app-builder workspaces：优化从 idea/prompt 到 runnable project。Onlook 是 design-to-code：优化从可见 component 到 code-backed visual change。

### 可复用模式

把 live product surface 本身变成人类和 AI 共享的工作空间。

可复用结构是：

1. visual target selection，
2. component/layer hierarchy，
3. property/style controls，
4. source-code mapping，
5. AST-backed write-to-code，
6. 基于选中对象的 AI chat，
7. immediate preview 和 code review。

### 可复用 Recipe

1. 在可检查 browser surface 里运行用户真实 app。
2. 注入 source-location metadata，让 UI elements 能映射回代码。
3. 让人类直接选择、样式化、检查 visual objects。
4. 让 AI 基于 selected components 和 project context 操作。
5. visual edits 在写回代码前保持临时状态。
6. 把 code diffs 作为交付边界，而不是只交付视觉 mockup。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方仓库把 Onlook 描述为 "The Cursor for Designers"，以及用于 visually build、style、edit React apps 的 AI-first design tool。 | https://github.com/onlook-dev/onlook | E3 |
| 官方文档描述 visual editor、code integration、AI assistance 和 Figma-to-Onlook flow。 | https://docs.onlook.com/getting-started/core-features | E3 |
| 官方 UI overview 列出 canvas、layers panel、properties panel、style editor、code panel 和 AI chat。 | https://docs.onlook.com/getting-started/ui-overview | E3 |
| 官方 architecture docs 说明 DOM/CSS 操作、source mapping、AST parsing 和 write-back to code。 | https://docs.onlook.com/developers/architecture | E3 |

### 推断出的模式

- Onlook 的稳定抽象是可见 component 作为 code-addressable object。
- 它的 AI-native OS 启发是：每个视觉动作都能回到源代码时，design operation 才更可控。
- 它的约束可能是 framework scope：当前最强模式集中在 React 和 Tailwind-style UI work。

### 未确认问题

- 面对复杂 component abstraction、generated class names 和 runtime conditional rendering 时，source mapping 有多稳定？
- visual editor 能否保持 design-system constraints，而不只是应用局部 style changes？
- 在大型生产代码库和自定义 component libraries 上，AI edit quality 有多可靠？
