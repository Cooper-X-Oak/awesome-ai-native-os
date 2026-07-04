# Dyad

> Local AI-native app-builder OS.
>
> Local AI 原生 app-builder OS。

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

Dyad turns app generation into a local-first desktop workspace where users build, preview, own, and export AI-generated applications without locking the project into a hosted builder.

### Business Scene

App / website / product prototyping, especially local AI app building for power users who want code ownership, model choice, and low lock-in.

### Core Business Object

A local app project.

The object includes prompt history, generated files, preview state, model configuration, local project folder, optional imported repo, and deployment path.

### Production Artifact

Runnable app code that lives on the user's machine and can be edited with other coding tools.

### Operating Space

Local desktop app-builder workspace.

Dyad is positioned as a downloadable Mac/Windows app. It runs locally, supports bring-your-own API keys and local models, and can point at existing folders or GitHub repos so AI works with the user's real code.

### AI Operation Model

AI is an app-building pair inside a local project loop.

It generates code from chat, modifies files, works with selected project context, supports multiple AI providers, and can use local models such as Ollama according to Dyad's public material.

### Human Control Model

Human control comes from local ownership.

The user owns the project folder, chooses models/API keys, can inspect generated files, can use external tools like VS Code/Cursor, can import existing projects, and can deploy through their own preferred workflow.

### State And Memory

Dyad preserves local project files, prompt context, generated changes, model/provider settings, preview state, and Git/project history when used with existing repos.

### Delivery Boundary

The boundary is a runnable local app project, not a hosted-only artifact.

### Same-Scene Contrast

Dyad differs from bolt.diy by making locality and ownership the central product promise.

bolt.diy emphasizes a browser/WebContainer loop with integrated runtime and deployment. Dyad emphasizes a local desktop builder where files remain on the user's machine and can interoperate with other developer tools. Onlook differs from both by editing an existing UI surface rather than generating full apps from a chat/app-builder loop.

### Reusable Pattern

Make local ownership the control layer of an AI app OS.

The reusable structure is:

1. local project folder as source of truth,
2. user-owned model credentials,
3. chat-to-files generation loop,
4. live preview,
5. import/export of existing code,
6. compatibility with external IDEs,
7. optional local model path.

### Reusable Recipe

1. Store the generated app as normal files on disk.
2. Let users bring their own cloud or local model.
3. Make preview and code inspection part of the same loop.
4. Allow existing folders and repos to become AI-operable projects.
5. Avoid proprietary project formats when the intended artifact is app code.
6. Treat deployment as an output path, not the only place the project can live.

### Observed Evidence

| Evidence | Link | Level |
| --- | --- | --- |
| Official site describes Dyad as a flexible, local, open-source AI app builder with model/tool choice and zero lock-in. | https://www.dyad.sh/ | E3 |
| Official repository describes Dyad as a local, open-source AI app builder that runs on the user's machine, with bring-your-own keys and cross-platform support. | https://github.com/dyad-sh/dyad | E3 |
| Official blog says Dyad can point at an existing folder or pull a repo from GitHub so AI works with code without uploading it to a cloud service. | https://www.dyad.sh/blog/import-project-ai-app-builder | E3 |
| Official blog describes Dyad as an open-source desktop app with support for multiple AI providers and switching between them. | https://www.dyad.sh/blog/bring-your-own-api-key-ai-app-builder | E3 |

### Inferred Pattern

- Dyad's durable abstraction is the local app project as an AI-operable workspace.
- Its OS lesson is that ownership, portability, and model choice can be first-class architecture, not just pricing claims.
- Its tradeoff is that local-first control may shift setup, model configuration, and deployment responsibility back to the user.

### Open Questions

- How robust is Dyad's project understanding on large imported production apps?
- Which generated app stacks are first-class versus template-driven?
- How far does local model support go for serious app-building tasks compared with frontier hosted models?

---

## 中文

### 案例状态

standard

### 证据等级

E3 强

### 一句话定位

Dyad 把 app generation 变成 local-first desktop workspace，让用户在不被 hosted builder 锁定的情况下构建、预览、拥有并导出 AI-generated applications。

### 业务场景

App / website / product prototyping，尤其适合想要 code ownership、model choice 和低 lock-in 的 power users。

### 核心业务对象

本地 app project。

这个对象包含 prompt history、generated files、preview state、model configuration、local project folder、可选 imported repo 和 deployment path。

### 生产产物

运行在用户机器上的 app code，并且可以被其他 coding tools 继续编辑。

### 操作空间

本地 desktop app-builder workspace。

Dyad 被定位为可下载的 Mac/Windows app。它本地运行，支持 bring-your-own API keys 和 local models，也可以指向 existing folders 或 GitHub repos，让 AI 操作用户真实代码。

### AI 操作模型

AI 是本地 project loop 里的 app-building pair。

它通过 chat 生成代码、修改文件、结合选中的 project context 工作，支持多个 AI providers，并根据公开材料支持 Ollama 等 local models。

### 人类控制模型

人类控制来自 local ownership。

用户拥有 project folder，选择 models/API keys，检查 generated files，使用 VS Code/Cursor 等外部工具，导入现有项目，并按自己的工作流部署。

### 状态与记忆

Dyad 保留 local project files、prompt context、generated changes、model/provider settings、preview state，以及使用现有 repo 时的 Git/project history。

### 交付边界

交付边界是 runnable local app project，而不是只能留在 hosted builder 里的 artifact。

### 同场景差异

Dyad 和 bolt.diy 的区别在于：它把 locality 和 ownership 作为核心产品承诺。

bolt.diy 强调 browser/WebContainer loop，以及 integrated runtime/deployment。Dyad 强调本地 desktop builder，文件保留在用户机器上，并能和其他 developer tools 协作。Onlook 则不同，它编辑已有 UI surface，而不是从 chat/app-builder loop 生成完整 app。

### 可复用模式

把 local ownership 做成 AI app OS 的控制层。

可复用结构是：

1. local project folder 作为 source of truth，
2. 用户自有 model credentials，
3. chat-to-files generation loop，
4. live preview，
5. existing code 的 import/export，
6. 与外部 IDE 兼容，
7. 可选 local model path。

### 可复用 Recipe

1. 把生成的 app 存成磁盘上的普通文件。
2. 允许用户带自己的 cloud/local model。
3. 把 preview 和 code inspection 放进同一个 loop。
4. 让 existing folders 和 repos 可以变成 AI-operable projects。
5. 当目标产物是 app code 时，避免 proprietary project format。
6. 把 deployment 当作输出路径之一，而不是项目唯一归宿。

### 观察到的证据

| 证据 | 链接 | 等级 |
| --- | --- | --- |
| 官方网站把 Dyad 描述为 flexible、local、open-source AI app builder，强调 model/tool choice 和 zero lock-in。 | https://www.dyad.sh/ | E3 |
| 官方仓库描述 Dyad 是在用户机器上运行的 local open-source AI app builder，支持 bring-your-own keys 和 cross-platform。 | https://github.com/dyad-sh/dyad | E3 |
| 官方 blog 说明 Dyad 可以指向 existing folder 或从 GitHub 拉 repo，让 AI 操作代码而不是上传到 cloud service。 | https://www.dyad.sh/blog/import-project-ai-app-builder | E3 |
| 官方 blog 描述 Dyad 是 open-source desktop app，支持多个 AI providers 并可切换。 | https://www.dyad.sh/blog/bring-your-own-api-key-ai-app-builder | E3 |

### 推断出的模式

- Dyad 的稳定抽象是 local app project as AI-operable workspace。
- 它的 OS 启发是：ownership、portability、model choice 可以成为架构一等公民，而不只是定价话术。
- 它的 tradeoff 是：local-first control 也会把 setup、model configuration 和 deployment responsibility 交还给用户。

### 未确认问题

- Dyad 对大型 imported production apps 的项目理解有多稳定？
- 哪些 generated app stacks 是 first-class，哪些主要依赖模板？
- local model support 在严肃 app-building 任务里和 frontier hosted models 相比能走多远？
