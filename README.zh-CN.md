# E-Library 📚

[EN English](./README.md) | [ZH 中文](./README.zh-CN.md)

一个开放的、由社区共建的 GitHub 仓库，用于存储、管理和共享电子书文件。本项目鼓励贡献者上传、整理并维护共享书库。我们提供清晰的文件结构、元数据模板和贡献指南，帮助保持收藏的有序、易查找并符合法律合规要求。

希望你能在这里找到有价值的资源，并乐于为这个项目做出贡献。

<div align="center">
   <a href="https://opensource.org/licenses/MIT">
      <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
   </a>
   <a href="https://github.com/TiiJeiJ8/E-Library/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/TiiJeiJ8/E-Library.svg" alt="Contributors" />
   </a>
   <a href="https://github.com/TiiJeiJ8/E-Library/commits/main">
      <img src="https://img.shields.io/github/last-commit/TiiJeiJ8/E-Library.svg" alt="Last Commit" />
   </a>
</div>

## 📖 关于

E-Library 是一个集中、受版本控制、由社区维护的数字图书馆，适合：
- 构建个人电子书收藏的个人
- 共享阅读资料的学习小组和读书会
- 分发课程阅读材料的教育者和团队
- 希望贡献并整理书籍以共同扩展书库的社区成员

想要参与共建吗？在添加文件前请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)，并遵守版权与许可要求。

## 🗂️ 仓库结构

```
E-Library/
├── library/           # 实际电子书文件存放处
├── books/
│   ├── by-genre/       # 按流派组织的书籍（小说、技术等）
│   ├── by-author/      # 按作者姓氏组织的书籍
│   └── by-topic/       # 按专题组织的书籍
├── docs/
│   ├── summaries/      # 简要书籍摘要和概述
│   └── reading-notes/  # 详细笔记与见解
├── templates/          # 文档与组织模板
├── CONTRIBUTING.md     # 贡献指南
├── CODE_OF_CONDUCT.md  # 社区行为规范
└── README.md           # 英文原始文件
```

## 🚀 快速开始

<a id="zh-getting-started"></a>

### 快速跳转

- [书库](https://github.com/TiiJeiJ8/E-Library-Books-Repo) — 实际电子书文件存放处（子仓）
- [书籍](./books/README.zh-CN.md) — 按流派、作者或主题浏览书籍
- [按流派浏览书籍](./books/by-genre/README.zh-CN.md)
- [按作者浏览书籍](./books/by-author/README.zh-CN.md)
- [按主题浏览书籍](./books/by-topic/README.zh-CN.md)
- [书籍摘要](./docs/summaries/README.zh-CN.md)
- [阅读笔记](./docs/reading-notes/README.zh-CN.md)
- [模板](./templates/README.zh-CN.md)
- [贡献指南](./CONTRIBUTING.zh-CN.md)

### 读者

从 E-Library 获取书籍非常简单。

1.  **找到想读的书**
    通过“快速跳转”或以下链接浏览书库：
    *   [按流派浏览](./books/by-genre/README.zh-CN.md)
    *   [按作者浏览](./books/by-author/README.zh-CN.md)
    *   [按主题浏览](./books/by-topic/README.zh-CN.md)

2.  **了解书籍内容**
    想知道一本书是否适合你？可以先查看 [书籍摘要](./docs/summaries/README.zh-CN.md) 来快速了解。

3.  **获取你的副本**
    注意：为使主仓聚焦于元数据、摘要与模板，实际的电子书文件已迁移到独立的子仓。请使用下方的子仓获取电子书文件。

    你有两种选择：
    *   **下载单本书**：访问子仓的 `library/` 目录并直接从浏览器下载：
        [前往子仓](https://github.com/TiiJeiJ8/E-Library-Books-Repo/README.zh-CN.md)
    *   **下载/克隆整个书库**：如果你想获取所有电子书文件，可以克隆子仓：
    ```powershell
    git clone https://github.com/TiiJeiJ8/E-Library-Books-Repo.git
    ```
    可选：如果你希望在本地工作区中将主仓与书籍仓并列管理，可以将子仓作为本仓的子模块添加：
    ```powershell
    git submodule add https://github.com/TiiJeiJ8/E-Library-Books-Repo.git library
    git submodule update --init --recursive
    ```

### 贡献者

想帮助我们扩充书库吗？我们非常欢迎你的加入！以下是添加新书的步骤：

1.  **Fork 本仓库**
    创建你自己的项目副本以便开展工作。

2.  **添加书籍文件**
    将你的电子书文件（如 PDF、EPUB）放入 `library/` 目录。请务必遵循我们的[文件命名规范](#-文件命名规范)。

3.  **创建索引条目和文档**
    在 `books/` 目录下的索引文件中添加书籍条目，并在 `docs/summaries/` 中为其创建摘要，以便他人发现。请使用我们的[模板](./templates/README.zh-CN.md)来保持格式统一。

4.  **提交 Pull Request**
    将你的更改提议到主仓库，我们会进行审核并合并。

关于自动化 PR 检查

当你发起 Pull Request 时，仓库会自动运行一系列检查（GitHub Actions），用于校验格式、链接、拼写以及仓库自定义规范。详情请参阅 `CONTRIBUTING.zh-CN.md`，其中说明了检查内容以及如何修复 CI 报告的问题。

更详细的说明，请阅读完整的 **[贡献指南](./CONTRIBUTING.zh-CN.md)**。

## 📋 文件命名规范

使用如下模式的描述性文件名：
```
AuthorLastName_BookTitle_Year.ext
```

**示例：**
- `Orwell_1984_1949.epub`
- `Kernighan_TheCProgrammingLanguage_1988.pdf`
- `Hawking_ABriefHistoryOfTime_1988.epub`

## 📚 支持格式

- **PDF** (.pdf)
- **EPUB** (.epub)
- **MOBI** (.mobi)
- **AZW** (.azw, .azw3)
- 其他基于文本的电子书格式

## 🎯 功能

- **多种组织方式**：按流派、作者或主题浏览
- **丰富文档**：书籍摘要和阅读笔记提高发现效率
- **模板**：保持一致性的文档模板
- **版本控制**：通过 Git 跟踪更改和历史
- **协作**：开放贡献与改进
- **可搜索**：使用 GitHub 搜索快速定位书籍

## 📖 文档要求

每本书应包含：
- **摘要**（放在 `docs/summaries/`）：简要概述、关键主题、目标读者
- **阅读笔记**（可选，放在 `docs/reading-notes/`）：详细见解和要点
- **目录条目**：列在相应文件夹的 README 中

使用 `templates/` 中的模板以保证一致性。

## 🤝 贡献

欢迎贡献：

- **添加新电子书**（请遵守版权与许可）
- **撰写摘要** 与阅读笔记
- **改进文档** 与组织结构
- **通过 issues 建议改进**
- **修复错误或坏链接**

请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 和 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

## ⚖️ 版权与法律

**重要**：仅添加以下书籍：
- 已进入 **公有领域** 的书籍
- 采用 **Creative Commons** 或类似开放许可的书籍
- 你有 **明确授权** 可分享的书籍

请尊重版权法。贡献者需保证其添加材料的共享权限。

## 📜 许可证

本仓库的文档和结构采用 [MIT License](LICENSE)。

单独书籍保留其原始版权和许可。

## 🌟 求助

- **有问题？** 提 issue，并标注 `question`
- **发现 bug？** 提 issue，并标注 `bug`
- **有建议？** 提 issue，并标注 `enhancement`

## 🙏 致谢

感谢所有贡献者，帮助建立并维护这个协作数字图书馆！

<a href="https://github.com/TiiJeiJ8/E-Library/graphs/contributors">
  <p align="left">
    <img width="500" src="https://contrib.rocks/image?repo=TiiJeiJ8/E-Library" alt="A table of avatars from the project's contributors" />
  </p>
</a>

---

祝阅读愉快！📚✨
