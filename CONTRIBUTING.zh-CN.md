# 参与贡献 — E-Library

[🇺🇸 English](./CONTRIBUTING.md) | [🇨🇳 中文](./CONTRIBUTING.zh-CN.md)

感谢你对 E-Library 的关注与贡献！本文件为添加电子书与改进仓库提供指南。

## 如何贡献

### 添加新电子书

1. **Fork 仓库**：先将本仓库 fork 到你的账户
2. **将文件放入 `library/`**：实际电子书（二进制）文件请放在 `library/` 下，并使用清晰结构（如 `Author-Last-Name-First-Name/Book-Title-YYYY/`）。
3. **在 `books/` 建立索引**：在相应索引 README 中创建或更新该书目的条目：
	- `books/by-genre/` — 将书籍列在对应类别下
	- `books/by-author/` — 将书籍列在对应作者下
	- `books/by-topic/` — 将书籍列在相关主题下
  README 模板位于 [Link](./templates/README.zh-CN.md)
4. **提交 Pull Request**：描述你添加的电子书及其价值

### 文件命名规则

- 使用有描述性的名称：`AuthorLastName_BookTitle_Year.ext`
- 例如：`Orwell_1984_1949.epub`
- 避免特殊字符和空格（使用下划线或连字符）

### 支持的格式

- PDF (.pdf)
- EPUB (.epub)
- MOBI (.mobi)
- AZW (.azw, .azw3)
- 其他基于文本的格式

### 图书文档要求

在添加图书时，请包括：
- **书名**：完整书名
- **作者**：作者姓名
- **年份**：出版年份
- **格式**：文件格式
- **描述**：简短摘要（2–3 句）
- **主题/标签**：相关关键词

### 质量指南

- 二进制文件放在 `library/` 中，并确保文件未损坏
- 尊重版权——仅添加属于公有领域、使用适当开源许可，或你有明确授权共享的书籍
- 保持命名和组织的一致性
- 测试文件能否正确打开

### 社区准则

请在所有互动中保持尊重和建设性。详细规则请参见 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。

## 改进仓库

你还可以通过以下方式贡献：
- 改进文档
- 建议更好的组织结构
- 添加阅读笔记或书籍摘要
- 修复损坏的链接或过时信息
- 创建有用的模板

## 有问题？

如有问题，请创建一个标签为 `question` 的 issue。

感谢你为建设这个协作性数字图书馆所做的贡献！
