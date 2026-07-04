# bolt.diy

> Browser-runtime AI-native app-builder OS.
>
> Browser-runtime AI 原生 app-builder OS。

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

bolt.diy turns app building into a browser-based prompt-code-runtime loop where users can generate, run, edit, preview, and deploy full-stack web apps with their chosen LLM providers.

### Business Scene

App / website / product prototyping, especially prompt-to-runnable full-stack web app construction.

### Core Business Object

A full-stack web app project running inside a browser development environment.

The object includes chat context, file tree, generated code, WebContainer runtime, terminal state, live preview, provider configuration, and deployment path.

### Production Artifact

Runnable and deployable web application code.

### Operating Space

Browser IDE + WebContainer runtime + live preview.

Official docs describe WebContainer as a secure isolated development environment with Node.js, file system access, terminal integration, npm scripts, live preview, and error feedback.

### AI Operation Model

AI acts as a code-generating development agent inside the browser runtime.

It can generate files, edit code, help design schemas, implement auth/API flows, run commands, react to errors, and iterate against the live preview. The key loop is prompt -> code -> run -> preview -> revise.

### Human Control Model

Human control is prompt steering plus runtime inspection.

The user configures providers, reviews generated code, uses terminal and preview, tests behavior, edits prompts or files, and decides when the app is ready to export or deploy.

### State And Memory

bolt.diy preserves chat context, project files, runtime state, terminal output, provider configuration, package/dependency state, preview feedback, and deployment/export state.

### Delivery Boundary

The delivery boundary is a runnable web app project that can be deployed or continued outside the AI session.

### Same-Scene Contrast

bolt.diy differs from Dyad by centering the browser runtime rather than the local desktop folder.

Dyad emphasizes local ownership and interoperability with other desktop coding tools. bolt.diy emphasizes a browser-contained loop where generation, editing, runtime, terminal, and preview sit together. Onlook differs from both because it starts from a live UI surface and writes visual edits back to React code.

### Reusable Pattern

Unify prompt, code, runtime, and preview in one AI-operable workspace.

The reusable structure is:

1. chat as intent channel,
2. file tree as artifact state,
3. WebContainer/runtime as execution layer,
4. terminal as tool surface,
5. live preview as feedback loop,
6. provider registry as model abstraction,
7. deploy/export as delivery path.

### Reusable Recipe

1. Keep generated code immediately executable.
2. Put runtime logs and preview next to the chat/code loop.
3. Let AI revise based on real errors, not only static code.
4. Abstract model providers behind a registry.
5. Preserve the file project as the durable artifact.
6. Treat deployment as a final step in the same workspace.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official repository describes bolt.diy as a tool to prompt, run, edit, and deploy full-stack web applications using any LLM. | https://github.com/stackblitz-labs/bolt.diy | E3 |
| Official docs describe WebContainer and live preview as a secure isolated development environment with Node.js, terminal, file system, and preview. | https://stackblitz-labs.github.io/bolt.diy/ | E3 |
| Official docs describe AI help for database schemas, SQL, authentication, API endpoints, and real-time features. | https://stackblitz-labs.github.io/bolt.diy/ | E3 |
| Official FAQ describes modular provider architecture and in-app provider configuration. | https://stackblitz-labs.github.io/bolt.diy/FAQ/ | E3 |

### Inferred Pattern

- bolt.diy's durable abstraction is the runnable app project inside a browser execution loop.
- Its AI-native OS lesson is that app generation improves when code and runtime are not separated from the prompt interface.
- Its risk is that browser runtime constraints may shape what projects are convenient to build and test.

### Open Questions

- Which full-stack patterns exceed the practical boundary of WebContainer/browser execution?
- How well does long-running project state survive across sessions and provider changes?
- How much production deployment complexity can remain inside the integrated loop?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

bolt.diy 把 app building 变成 browser-based prompt-code-runtime loop，让用户用自己选择的 LLM providers 生成、运行、编辑、预览并部署 full-stack web apps。

### 业务场景

App / website / product prototyping，尤其是 prompt-to-runnable full-stack web app construction。

### 核心业务对象

运行在 browser development environment 里的 full-stack web app project。

这个对象包含 chat context、file tree、generated code、WebContainer runtime、terminal state、live preview、provider configuration 和 deployment path。

### 生产产物

可运行、可部署的 web application code。

### 操作空间

Browser IDE + WebContainer runtime + live preview。

官方文档把 WebContainer 描述为 secure isolated development environment，包含 Node.js、file system access、terminal integration、npm scripts、live preview 和 error feedback。

### AI 操作模型

AI 是 browser runtime 内部的 code-generating development agent。

它可以生成文件、编辑代码、帮助设计 schemas、实现 auth/API flows、运行命令、响应错误，并围绕 live preview 迭代。关键循环是 prompt -> code -> run -> preview -> revise。

### 人类控制模型

人类控制是 prompt steering + runtime inspection。

用户配置 providers，审查生成代码，使用 terminal 和 preview，测试行为，编辑 prompts 或 files，并决定何时 export/deploy。

### 状态与记忆

bolt.diy 保留 chat context、project files、runtime state、terminal output、provider configuration、package/dependency state、preview feedback 和 deployment/export state。

### 交付边界

交付边界是 runnable web app project，可以部署，也可以离开 AI session 后继续开发。

### 同场景差异

bolt.diy 和 Dyad 的区别在于：它以 browser runtime 为中心，而不是本地 desktop folder。

Dyad 强调 local ownership 以及和其他 desktop coding tools 协作。bolt.diy 强调 browser-contained loop，把 generation、editing、runtime、terminal、preview 放在一起。Onlook 则从 live UI surface 出发，把视觉编辑写回 React code。

### 可复用模式

把 prompt、code、runtime 和 preview 统一到一个 AI-operable workspace。

可复用结构是：

1. chat 作为 intent channel，
2. file tree 作为 artifact state，
3. WebContainer/runtime 作为 execution layer，
4. terminal 作为 tool surface，
5. live preview 作为 feedback loop，
6. provider registry 作为 model abstraction，
7. deploy/export 作为 delivery path。

### 可复用 Recipe

1. 让生成代码立即可执行。
2. 把 runtime logs 和 preview 放在 chat/code loop 旁边。
3. 让 AI 根据真实错误修正，而不是只看静态代码。
4. 用 registry 抽象 model providers。
5. 把 file project 作为 durable artifact。
6. 把 deployment 放进同一个 workspace 的最后一步。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方仓库描述 bolt.diy 可以使用任意 LLM prompt、run、edit、deploy full-stack web applications。 | https://github.com/stackblitz-labs/bolt.diy | E3 |
| 官方文档描述 WebContainer 和 live preview 是带 Node.js、terminal、file system、preview 的 secure isolated development environment。 | https://stackblitz-labs.github.io/bolt.diy/ | E3 |
| 官方文档描述 AI 可以帮助 database schemas、SQL、authentication、API endpoints 和 real-time features。 | https://stackblitz-labs.github.io/bolt.diy/ | E3 |
| 官方 FAQ 描述 modular provider architecture 和 in-app provider configuration。 | https://stackblitz-labs.github.io/bolt.diy/FAQ/ | E3 |

### 推断出的模式

- bolt.diy 的稳定抽象是 browser execution loop 中的 runnable app project。
- 它的 AI-native OS 启发是：当 code/runtime 不和 prompt interface 分离时，app generation 更容易形成闭环。
- 它的风险是 browser runtime constraints 可能决定哪些项目更适合构建和测试。

### 未确认问题

- 哪些 full-stack patterns 会超过 WebContainer/browser execution 的实用边界？
- long-running project state 在跨 session 和跨 provider 后能保持多稳定？
- 生产部署复杂度有多少能留在 integrated loop 里？
