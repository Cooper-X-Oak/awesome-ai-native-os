# Case Cards

> Architecture reads for priority AI-native production systems.
>
> 第一批 AI 原生生产系统的架构案例卡。

## Language

- [English](#english)
- [中文](#中文)

---

## English

Case cards are not product reviews.

They are compact architecture reads that explain how a project turns a business scene into a repeatable human-AI production loop.

### Deep-Dive Task Map

```text
case cards deep-dive
├─ A. finalize the deep-dive schema
├─ B. collect public evidence and mark evidence levels
├─ C. deepen the first 12 A0 case cards
├─ D. calibrate cases inside each business scene
├─ E. extract cross-scene operating patterns
├─ F. run bilingual and public-repo quality checks
└─ G. prepare release notes and contribution entry points
```

### Current Progress

The first 12 A0 case cards are now at `standard` depth.

Next useful work is not adding more detail blindly. It is scene-level calibration: compare cases inside the same business scene and decide which cards deserve `deep` status.

### Case Status

| Status | Meaning |
| --- | --- |
| `stub` | Skeleton card; useful as a placeholder but not yet reusable. |
| `standard` | Evidence-backed architecture read with reusable patterns and open questions. |
| `deep` | Standard card plus stronger peer contrast, operating model detail, and reusable recipe. |
| `needs evidence` | Interesting candidate, but public evidence is too thin or unclear. |
| `needs peer review` | Draft is complete enough to review, but claims need another pass. |

### Evidence Levels

| Level | Meaning |
| --- | --- |
| `E3 strong` | Official docs, official repo, product docs, or directly observable product surface. |
| `E2 medium` | Credible secondary source, demo, changelog, README claim, or public technical explanation. |
| `E1 weak` | Inference from limited material; keep claims conservative. |

### First Batch

| Case | Scene | Architecture lens | Status |
| --- | --- | --- | --- |
| [OpenMontage](openmontage.md) | Video / media / creative production | Pipeline-first AI-native video production OS. | standard |
| [OpenFlow](openflow.md) | Video / media / creative production | Node-canvas-first multimodal AI production OS. | standard |
| [Descript](descript.md) | Video / media / creative production | Transcript/timeline-first AI-native media editing OS. | standard |
| [Onlook](onlook.md) | UI design to code | Canvas/design-first AI-native React UI OS. | standard |
| [Dyad](dyad.md) | App / website / product prototyping | Local AI-native app-builder OS. | standard |
| [bolt.diy](bolt-diy.md) | App / website / product prototyping | Browser-runtime AI-native app-builder OS. | standard |
| [CodeG](codeg.md) | Software engineering / code delivery | Multi-agent coding session OS. | standard |
| [Devin](devin.md) | Software engineering / code delivery | Task-to-PR autonomous engineering OS. | standard |
| [NotebookLM](notebooklm.md) | Research / knowledge / evidence reporting | Source-grounded notebook/research OS. | standard |
| [STORM](storm.md) | Research / knowledge / evidence reporting | Research-to-writing pipeline OS. | standard |
| [Quadratic](quadratic.md) | Data analytics / BI / finance | Spreadsheet-first AI-native data OS. | standard |
| [Clay](clay.md) | Sales / GTM / business automation | Table-first GTM/business OS. | standard |

Use [_template.md](_template.md) for new case cards.

---

## 中文

案例卡不是产品评测。

它们是紧凑的架构拆解，用来说明一个项目如何把业务场景变成可重复的人机协同生产循环。

### 深拆任务图

```text
case cards 深拆
├─ A. 收口深拆字段规范
├─ B. 收集公开证据并标注证据等级
├─ C. 深拆第一批 12 个 A0 案例卡
├─ D. 在同一业务场景内校准案例
├─ E. 提炼跨场景操作模式
├─ F. 运行双语和公开仓库质量检查
└─ G. 准备发布说明和贡献入口
```

### 当前进度

第一批 12 个 A0 案例卡已经达到 `standard` 深度。

下一步有价值的工作不是盲目加细节，而是做场景级校准：比较同一业务场景里的案例，并决定哪些卡值得升级到 `deep`。

### 案例状态

| 状态 | 含义 |
| --- | --- |
| `stub` | 骨架卡片；可以占位，但还不能直接复用。 |
| `standard` | 有证据支撑的架构拆解，包含可复用模式和未确认问题。 |
| `deep` | 在 standard 基础上补足同场景对比、操作模型细节和可复用 recipe。 |
| `needs evidence` | 候选有价值，但公开证据太少或不清晰。 |
| `needs peer review` | 草稿已基本完成，但关键判断需要二次检查。 |

### 证据等级

| 等级 | 含义 |
| --- | --- |
| `E3 strong` | 官方文档、官方仓库、产品文档或可直接观察的产品界面。 |
| `E2 medium` | 可信二手来源、演示、更新日志、README 说明或公开技术解释。 |
| `E1 weak` | 基于有限材料的推断；结论必须保守。 |

### 第一批

| 案例 | 场景 | 架构视角 | 状态 |
| --- | --- | --- | --- |
| [OpenMontage](openmontage.md) | 视频 / 媒体 / 创意生产 | Pipeline-first AI 原生视频生产 OS。 | standard |
| [OpenFlow](openflow.md) | 视频 / 媒体 / 创意生产 | Node-canvas-first 多模态 AI 生产 OS。 | standard |
| [Descript](descript.md) | 视频 / 媒体 / 创意生产 | Transcript/timeline-first AI 原生媒体编辑 OS。 | standard |
| [Onlook](onlook.md) | UI design to code | Canvas/design-first AI 原生 React UI OS。 | standard |
| [Dyad](dyad.md) | App / website / product prototyping | Local AI 原生 app-builder OS。 | standard |
| [bolt.diy](bolt-diy.md) | App / website / product prototyping | Browser-runtime AI 原生 app-builder OS。 | standard |
| [CodeG](codeg.md) | Software engineering / code delivery | Multi-agent coding session OS。 | standard |
| [Devin](devin.md) | Software engineering / code delivery | Task-to-PR autonomous engineering OS。 | standard |
| [NotebookLM](notebooklm.md) | Research / knowledge / evidence reporting | Source-grounded notebook/research OS。 | standard |
| [STORM](storm.md) | Research / knowledge / evidence reporting | Research-to-writing pipeline OS。 | standard |
| [Quadratic](quadratic.md) | Data analytics / BI / finance | Spreadsheet-first AI 原生数据 OS。 | standard |
| [Clay](clay.md) | Sales / GTM / business automation | Table-first GTM/business OS。 | standard |

新增案例卡使用 [_template.md](_template.md)。
