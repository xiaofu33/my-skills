---
name: xiaofu-obsidian-writer
description: 编写符合个人 Obsidian 知识库风格的文档。
author: yumixiaofu
license: Apache-2.0
---

# xiaofu-obsidian-writer

本技能指导 Agent 如何编写符合个人知识库风格的 Obsidian 文档。

## 1. 命名

- **文件名**：简洁明了，描述文档核心内容即可，**不要带日期前缀**。
- **定期摘要**（日报、周报）：可在文件名末尾加上 `📅️` 标识，仍**不要**日期前缀。

## 2. Emoji 语意

- `🟥`：待办/未完成/待编写。
- `🟩`：已完成/已提供。
- `📅️`：定期摘要（日报、周报）。

## 3. 文档结构

所有文档**必须**包含：
1. **YAML Frontmatter**：仅包含 `date created` 和 `tags` 两个字段，标签以数组形式写在 `tags` 下。
2. **内容**：正文从 H1（`#`）开始。文档按多个 H1 平级组织，每个主要章节各为一个独立 H1，不要出现"一个 H1 下挂多个 H2"的树状结构。如需细分，在对应 H1 下用 H2 作为子标题。

## 4. 文风指南

- **资深工程师风格**：高信息密度，拒绝冗余。
- **结构化优先**：使用列表、引用块和任务项。
- **强链接**：通过双向链接建立知识网络。

## 5. 参考资源

- 详细标签与符号定义见：[references/categories.md](references/categories.md)
- 标准文档模板见：[assets/template.md](assets/template.md)
