# Bilingual Structure

> This repository is bilingual by default.
>
> 本仓库默认采用中英双语结构。

## Language

- [English](#english)
- [中文](#中文)

---

## English

### Rule

Public-facing documentation must be bilingual by default.

This is not an optional polish pass. It is part of the repository structure.

### Required Pattern

Use this structure for public guide documents:

```md
# Document Title

> One-line English summary.
>
> 一句话中文摘要。

## Language

- [English](#english)
- [中文](#中文)

---

## English

...complete English section...

---

## 中文

...完整中文章节...
```

### Do Not Use Inline Translation Blocks

Do not write an English document and then insert a small language-label block like:

```md
Chinese summary:
...
```

Do not mix the two languages randomly inside the same explanatory paragraph.

If a document is intended for both audiences, give each language a complete section.

### What Must Be Bilingual

These files must stay bilingual:

```text
README.md
taxonomy.md
inclusion-criteria.md
CONTRIBUTING.md
docs/*.md
scenes/README.md
cases/README.md
case-card templates
new public guide documents
```

Scene pages and case cards are public documentation. They must be bilingual by default, including stubs and templates.

### Allowed Exceptions

These may stay mostly English when a strict bilingual rewrite would reduce utility:

```text
project names
URLs
license text
GitHub issue template front matter
standard operating model labels
third-party product positioning
short table values such as A0, A1, B+, pipeline-first, repo-first
```

### Translation Standard

Chinese text should not be a stiff line-by-line translation.

It should preserve the same structure and meaning, but read naturally for Chinese readers.

Use stable terms:

| English | 中文 |
| --- | --- |
| AI-Native Production OS | AI 原生生产 OS |
| business scene | 业务场景 |
| core business object | 核心业务对象 |
| production artifact | 生产产物 |
| operating model | 操作模型 |
| operating space | 操作空间 |
| human control model | 人类控制模型 |
| state and memory | 状态与记忆 |
| delivery boundary | 交付边界 |
| reusable pattern | 可复用模式 |

### Review Checklist

Before merging a documentation change, check:

```text
Does the file have a Language section?
Does it have complete English and 中文 sections?
Is there any leftover inline translation-label block?
Are links shared consistently across both sections?
Are core terms translated consistently?
Does the Chinese section read like native documentation, not a literal dump?
```

---

## 中文

### 规则

公开文档默认必须采用中英双语结构。

这不是后续润色项，而是仓库的基本结构。

### 必须使用的结构

公开说明文档使用这个结构：

```md
# 文档标题

> One-line English summary.
>
> 一句话中文摘要。

## Language

- [English](#english)
- [中文](#中文)

---

## English

...complete English section...

---

## 中文

...完整中文章节...
```

### 不要使用夹杂式翻译块

不要先写一整篇英文文档，然后在中间插一小段语言标签块：

```md
Chinese summary:
...
```

也不要在同一个解释段落里随机混用两种语言。

如果一份文档面向中英文读者，就给两种语言各自完整章节。

### 哪些文件必须双语

这些文件必须保持双语：

```text
README.md
taxonomy.md
inclusion-criteria.md
CONTRIBUTING.md
docs/*.md
scenes/README.md
cases/README.md
case-card templates
新的公开说明文档
```

场景页和案例卡属于公开文档。它们默认必须双语，包括 stub 和模板。

### 允许例外

下面内容可以主要保留英文，因为强行翻译会降低可用性：

```text
项目名称
URL
许可证正文
GitHub issue template front matter
标准操作模型标签
第三方产品自我定位
A0、A1、B+、pipeline-first、repo-first 等短表格值
```

### 翻译标准

中文部分不要做僵硬的逐行直译。

它应该和英文部分保持相同结构与含义，但读起来像自然的中文文档。

固定术语：

| English | 中文 |
| --- | --- |
| AI-Native Production OS | AI 原生生产 OS |
| business scene | 业务场景 |
| core business object | 核心业务对象 |
| production artifact | 生产产物 |
| operating model | 操作模型 |
| operating space | 操作空间 |
| human control model | 人类控制模型 |
| state and memory | 状态与记忆 |
| delivery boundary | 交付边界 |
| reusable pattern | 可复用模式 |

### Review Checklist

合并文档修改前检查：

```text
文件是否有 Language section？
是否有完整 English 和 中文章节？
是否残留夹杂式翻译标签块？
两种语言里的链接是否一致？
核心术语是否翻译一致？
中文部分读起来是否像自然文档，而不是直译堆砌？
```
