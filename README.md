# Awesome AI-Native OS

An atlas of AI-native production systems and domain operating layers.

This repository collects products and open-source projects that turn domain workflows into AI-operable production loops: systems where humans and AI work on durable artifacts through shared workspaces, inspectable state, repeatable operations, and concrete delivery boundaries.

This is not a list of AI tools, chatbots, model APIs, or agent frameworks.

## What This Means

An **AI-Native Production OS** is a domain-specific system that turns a business workflow into an AI-operable production loop.

It has:

1. a clear business scene,
2. a durable production object,
3. a shared human-AI workspace,
4. repeatable AI operations,
5. inspectable state and memory,
6. human control points,
7. a concrete delivery boundary.

In Chinese:

```text
AI 原生生产 OS，是一种面向具体业务场景的系统。

它把业务流程中的核心产物，放进一个人类和 AI 可以共同操作的工作空间里；
AI 可以反复执行、修改、组合、推进任务；
人类可以检查、约束、接管、批准；
系统保存状态、上下文、过程和版本；
最后交付一个明确的业务产物。
```

## Not Just Another Awesome List

Most AI lists group projects by model, framework, or feature.

This atlas groups projects by:

```text
business scene
  -> core business object
  -> production artifact
  -> operating model
  -> human control model
  -> state and memory
  -> delivery boundary
  -> reusable pattern
```

The point is not to ask which tool is "best". The point is to understand how different systems make the same business scene AI-operable.

Example:

| Business scene | Project | Operating model |
| --- | --- | --- |
| Video / media production | OpenMontage | pipeline-first production OS |
| Video / media production | OpenFlow | node-canvas-first multimodal OS |
| Video / media production | Descript | transcript/timeline-first media OS |
| Video / media production | Krea | creative-workspace-first media OS |

Same scene, different architecture and interaction model.

## Repository Map

| Path | Purpose |
| --- | --- |
| [taxonomy.md](taxonomy.md) | Core definition, classification framework, and operating-model vocabulary. |
| [inclusion-criteria.md](inclusion-criteria.md) | What qualifies, what does not, and how to grade candidates. |
| [scenes/](scenes/) | Business-scene indexes. All 100 current candidates are represented here. |
| [cases/](cases/) | Case-card templates and priority deep-dive entries. |

## Business Scenes

| Scene | What it studies | First projects to inspect |
| --- | --- | --- |
| [App / Website / Product Prototyping](scenes/app-website-product-prototyping.md) | Build apps, websites, and prototypes from prompts, sites, or product intent. | Dyad, bolt.diy, Open Lovable |
| [UI Design / Design-to-Code](scenes/ui-design-to-code.md) | Turn UI ideas, designs, and components into editable front-end artifacts. | Onlook, Plasmic |
| [Video / Media / Creative Production](scenes/video-media-creative-production.md) | Produce videos, media assets, clips, avatars, and creative variants. | OpenMontage, OpenFlow, Descript |
| [Software Engineering / Code Delivery](scenes/software-engineering-code-delivery.md) | Turn tasks, issues, bugs, and repo context into code changes or PRs. | CodeG, Devin, Cursor |
| [Game / Interactive Artifact Production](scenes/game-interactive-artifacts.md) | Generate playable games and interactive artifacts. | VibeStudio |
| [Research / Knowledge / Evidence Reporting](scenes/research-knowledge-evidence-reporting.md) | Produce grounded answers, reports, literature reviews, and long-form research. | NotebookLM, STORM, GPT Researcher |
| [Document / Presentation / Content Production](scenes/document-presentation-content-production.md) | Produce docs, decks, pages, knowledge assets, and marketing content. | Gamma, Notion AI, Writer |
| [Data Analysis / BI / Financial Analysis](scenes/data-analytics-bi-finance.md) | Produce analysis, charts, dashboards, briefs, and data apps. | Quadratic, Julius |
| [Sales / GTM / Business Automation](scenes/sales-gtm-business-automation.md) | Produce lead lists, account intelligence, outreach, and automated workflows. | Clay, Bardeen |

## Priority Case Cards

The first case-card batch focuses on projects that best define the category:

| Case | Why it matters |
| --- | --- |
| [OpenMontage](cases/openmontage.md) | Pipeline-first video production OS. |
| [Onlook](cases/onlook.md) | Canvas/design-first React UI OS. |
| [Dyad](cases/dyad.md) | Local app-builder OS. |
| [bolt.diy](cases/bolt-diy.md) | Browser runtime app-builder OS. |
| [OpenFlow](cases/openflow.md) | Node-canvas multimodal production OS. |
| [Descript](cases/descript.md) | Transcript/timeline-first media OS. |
| [CodeG](cases/codeg.md) | Multi-agent coding session OS. |
| [Devin](cases/devin.md) | Task-to-PR autonomous engineering OS. |
| [NotebookLM](cases/notebooklm.md) | Source-grounded notebook/research OS. |
| [STORM](cases/storm.md) | Research-to-writing pipeline OS. |
| [Quadratic](cases/quadratic.md) | Spreadsheet-first data OS. |
| [Clay](cases/clay.md) | Table-first GTM/business OS. |

## Fast Mental Model

```text
AI Tool
= helps with one action

AI Agent
= executes a task

AI-Native Production OS
= turns a business scene into a repeatable human-AI production loop
```

The durable question for every entry:

```text
What business object did this system make AI-operable?
```

