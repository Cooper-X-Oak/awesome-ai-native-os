# Taxonomy

This taxonomy defines the frame used by Awesome AI-Native OS.

## Core Category

```text
AI-Native Production OS
= a domain-specific operating layer for repeatable human-AI production work
```

More explicitly:

```text
An AI-Native Production OS is a domain-specific system that turns a business workflow into an AI-operable production loop.

It makes a core business object durable, editable, inspectable, and deliverable through a shared human-AI workspace.
```

## Three-Layer Classification

Every project is classified through three layers.

### Layer 1: Business Scene

What work does this system help a user complete?

Examples:

```text
app building
UI design and front-end delivery
video and media production
software engineering
research and evidence reporting
document and content production
data analysis and BI
sales and GTM automation
interactive artifact generation
```

This is the primary entry point for the atlas.

### Layer 2: Business Core Abstraction

What business object does the system organize?

Examples:

| Scene | Core business object |
| --- | --- |
| App building | app project, website, runnable prototype |
| UI design | screen, component, React UI, design system |
| Video production | script, shot, timeline, media asset, production stage |
| Software engineering | issue, repo, diff, task, PR |
| Research | source set, question, outline, report, citation |
| Content production | doc, deck, page, brand asset, campaign content |
| Data analysis | sheet, dataset, metric, chart, dashboard |
| Sales / GTM | lead, account, signal, enrichment table, workflow |

This layer prevents the atlas from becoming a generic AI tool directory.

### Layer 3: AI-Native Operating Model

How does the system make the business object AI-operable?

Common operating models:

| Operating model | Description | Examples |
| --- | --- | --- |
| pipeline-first | Work is split into stages, intermediate artifacts, and repeatable steps. | OpenMontage, STORM |
| canvas-first | Users and AI operate objects spatially through a canvas or graph. | OpenFlow, Onlook |
| timeline/transcript-first | Media is edited through time, transcript, or sequence structure. | Descript |
| repo-first | Software production is anchored in a repository and diff/PR boundary. | Devin, Cursor, Cline |
| session-workspace-first | Multiple AI sessions become visible and manageable production units. | CodeG, AgentRove |
| notebook/source-grounded | Sources and notes bound the AI's reasoning and outputs. | NotebookLM |
| spreadsheet-first | The grid is the primary interface for AI, code, data, and outputs. | Quadratic |
| table-first | Business operations are organized as rows, columns, enrichments, and workflows. | Clay |
| workflow-automation-first | AI operates across tools, browser actions, or automation recipes. | Bardeen |

## Seven Required Signals

A strong AI-Native Production OS usually has all seven signals:

1. **Business scene**: a clear job-to-be-done.
2. **Durable production object**: an artifact that survives beyond a prompt response.
3. **Shared operating space**: a place where humans and AI both work.
4. **Repeatable AI operations**: generate, edit, route, critique, enrich, test, publish, etc.
5. **Human control model**: review, approve, constrain, override, or directly edit.
6. **State and memory**: saved sources, versions, traces, project files, sessions, or histories.
7. **Delivery boundary**: app, PR, video, report, deck, spreadsheet, lead list, workflow, etc.

## Project Card Fields

Each case card should answer:

| Field | Question |
| --- | --- |
| Business scene | What business work does it solve? |
| Core business object | What object does the system organize? |
| Production artifact | What does it produce? |
| Operating space | Where do humans and AI operate the artifact? |
| AI operation model | What role does AI play? |
| Human control model | How does a human inspect, constrain, approve, or take over? |
| State and memory | What context, versions, sources, traces, or project state are preserved? |
| Delivery boundary | What is the concrete output? |
| Reusable pattern | What can builders copy into their own AI-native OS? |

## Boundary Rules

Do not classify something as an AI-Native Production OS only because it has AI features.

Common downgrades:

| Kind | Why it is downgraded |
| --- | --- |
| single-shot generator | no durable artifact or repeatable workspace |
| chatbot | no business object or delivery boundary |
| model API | infrastructure, not production OS |
| agent framework | building block, not domain production layer |
| ordinary SaaS with AI features | AI is an enhancement, not the operating layer |
| demo repository | not enough state, workflow, or repeatable production evidence |

## Useful Distinction

```text
AI Tool
= helps with one action

AI Agent
= executes one task or task chain

AI-Native Production OS
= makes a domain workflow repeatable, inspectable, controllable, and deliverable
```

