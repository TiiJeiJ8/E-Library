# 参与贡献 — E-Library

[EN English](./CONTRIBUTING.md) | [ZH 中文](./CONTRIBUTING.zh-CN.md)

感谢你对 E-Library 的关注与贡献！本文件为添加电子书与改进仓库提供指南。

## 如何贡献

所有贡献都通过拉取请求（Pull Request）完成。无论您是添加新书还是改进文档，基本流程如下：

1.  **Fork 仓库**：创建您自己的仓库分支。
2.  **创建新分支**：为您的修改创建一个独立的分支。
3.  **提交修改**：完成您的修改并提交。
4.  **发起拉取请求**：将您的分支合并到主仓库。

### 添加新书

添加一本新书主要包含两个步骤：上传书籍文件和创建索引条目。

#### 步骤 1：将书籍文件添加到子仓 [E-Library-Books-Repo](https://github.com/TiiJeiJ8/E-Library-Books-Repo)中的 `library/`

将电子书文件（如 `.epub`, `.pdf`）放入 `library/` 目录。请遵循清晰的目录结构，例如：`library/作者姓-名/书名-出版年份/`。
相关线上上传可参考 [上传教程](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)

> 💡 **提示**：对于体积较小的文件（< 25MB），您可以使用 GitHub 网页上的 **"Add file" → "Upload files"** 功能直接上传。对于大文件，则需要克隆仓库到本地再添加。

#### 步骤 2：创建索引与文档

书籍文件上传后，您需要为它创建索引和相关文档。**此步骤完全可以通过网页界面完成，无需克隆仓库。**

> 您需要准备：
> - 书籍的基本信息（作者、标题、年份、格式等）
> - 按作者分类README文档（如果当前仓库中已有该作者，直接在该文档中添加即可；若无，则新建一个）
> - 按流派分类README文档（如果当前仓库中已有该流派，直接在该文档中添加即可；若无，则新建一个）
> - 按专题分类README文档（如果当前仓库中已有该专题，直接在该文档中添加即可；若无，则新建一个）
> - 书籍摘要文档（存放在 `docs/summaries/` 目录下）
> **此外，请务必检查并更新父文件夹的 `README` 文件**：
    - 如果您在 `books/by-genre/Fiction/` 下添加了一个子流派 `Political-Fiction`，请确保在 `Fiction` 的 `README.md` 中添加指向 `Political-Fiction` 的链接。
    - 如果您在 `books/by-author/` 下添加了一个新作者，请确保在 `by-author/README.md` 中添加指向该作者文件夹的链接。


1.  **在 `books/` 目录下创建索引**：
    -   在 `books/by-author/`、`books/by-genre/` 和 `books/by-topic/` 下创建或更新对应的 `README.md` 文件，将书籍信息添加进去。
    -   在创建索引条目时，请确保包含以下信息：
        -   **书名**：完整书名
        -   **作者**：作者姓名
        -   **年份**：出版年份
        -   **格式**：文件格式
        -   **描述**：简短摘要（2–3 句）
        -   **主题/标签**：相关关键词
    -   您可以使用模板来快速开始：[`author-readme-template.md`](./templates/author-readme-template.zh-CN.md)

2.  **在 `docs/` 目录下添加摘要**：
	-   在 `docs/summaries/` 下创建一个新的 Markdown 文件，命名为 `AuthorLastName_BookTitle_Year.md`。
	-   在文件中包含书籍的简要摘要、主要主题和任何其他相关信息。
	-   您可以使用 [`summary-template.md`](./templates/book-summary-template.zh-CN.md) 作为起点。

3.  **（可选）在 `docs/` 目录下添加笔记**：
    -   在 `docs/summaries/` 或 `docs/reading-notes/` 下创建对应的文件。
    -   请遵循这两个目录中 `README.md` 规定的文件命名约定。

**如何在线创建和编辑这些文件？**

您可以使用以下任意一种方法来完成上述文本文件的创建和编辑：

-   **方法一：创建新文件**
    1.  在 GitHub 仓库页面，点击 **"Add file" → "Create new file"**。
    2.  在文件名输入框中输入**完整路径**，例如 `books/by-author/Orwell-George/README.md`。GitHub 会自动创建文件夹。
    3.  编辑内容后，发起 Pull Request。

-   **方法二：编辑现有文件**
    1.  打开目标文件（如某个 `README.md`）。
    2.  点击右上角的**铅笔图标 ✏️ (Edit this file)**。
    3.  修改后，发起 Pull Request。

-   **方法三：使用 GitHub.dev 在线编辑器**
    1.  在仓库页面，按下键盘上的 `.` 键。
    2.  在打开的网页版 VS Code 编辑器中，您可以自由地创建、编辑和提交文件。

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
