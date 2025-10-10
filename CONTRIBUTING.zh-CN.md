# 参与贡献 — E-Library

[EN English](./CONTRIBUTING.md) | [CN 中文](./CONTRIBUTING.zh-CN.md)

感谢你对 E-Library 的关注与贡献！本文件为添加电子书与改进仓库提供指南。

## 如何贡献

### 添加新电子书

如果你只想进行轻量贡献（如修改索引、更新文档、添加元数据），可以**直接在线上完成**，无需克隆仓库或配置本地环境。

#####  方法一：使用 GitHub 网页界面

1. 打开仓库页面（或你的 Fork）。
2. 点击右上角 **“Add file” → “Create new file”**。
3. 在文件名输入框中输入完整路径，例如：`books/by-author/Orwell-George/README.md`。
> 💡 GitHub 会自动创建对应文件夹结构。
4. 在编辑区填写内容（如书籍信息或简介）。
5. 在底部填写提交说明（commit message），并选择：
- ✅ “Create a new branch for this commit and start a pull request”
6. 点击 **“Propose changes”**，GitHub 会自动引导你创建 Pull Request。

#####  方法二：修改现有文件

1. 打开要修改的文件（如某个 `README.md`）。
2. 点击右上角的 **铅笔图标 ✏️（Edit this file）**。
3. 修改内容后，直接提交（commit）并发起 Pull Request。

#####  方法三：使用 GitHub.dev 在线编辑器（快捷键：`.`）

1. 在仓库页面按下键盘 `.`（英文句号）。
GitHub 会打开网页版 VS Code 编辑器。
2. 你可以：
- 创建文件夹、文件
- 修改内容
- 提交 commit 与发起 PR
3. 无需安装任何软件或命令行工具。

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

### 双语写作建议

- 内容较少时可在同一文件中分段呈现英语与您的母语两版；内容较多时可分为 `README.md` 与 `README.<language>-<region>.md` 两个文件。
- 两种语言的元数据与关键信息需保持一致。
- 注意！至少一版必须为英语。

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
