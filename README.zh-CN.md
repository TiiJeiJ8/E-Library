# E-Library 📚

[US English](./README.md) | [CN 中文](./README.zh-CN.md)

一个开放的、由社区共建的 GitHub 仓库，用于存储、管理和共享电子书文件。本项目鼓励贡献者上传、整理并维护共享书库。我们提供清晰的文件结构、元数据模板和贡献指南，帮助保持收藏的有序、易查找并符合法律合规要求。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributors](https://img.shields.io/github/contributors/TiiJeiJ8/E-Library.svg)](https://github.com/TiiJeiJ8/E-Library/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/TiiJeiJ8/E-Library.svg)](https://github.com/TiiJeiJ8/E-Library/commits/main)
[![Downloads](https://img.shields.io/github/downloads/TiiJeiJ8/E-Library/total.svg)](https://github.com/TiiJeiJ8/E-Library/releases)

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

- [书库](./library/README.zh-CN.md) — 实际电子书文件存放处
- [按流派浏览书籍](./books/by-genre/README.md)
- [按作者浏览书籍](./books/by-author/README.md)
- [按主题浏览书籍](./books/by-topic/README.md)
- [书籍摘要](./docs/summaries/README.md)
- [阅读笔记](./docs/reading-notes/README.md)
- [模板](./templates/README.md)
- [贡献指南](./CONTRIBUTING.md)

### 读者

1. **浏览收藏**：通过 `books/` 中的组织方式浏览：
   - `by-genre/` - 按流派浏览（小说、技术、科学等）
   - `by-author/` - 查找特定作者的书籍
   - `by-topic/` - 探索特定主题的书籍

2. **阅读摘要**：在 `docs/summaries/` 查看快速概述

3. **克隆或下载：**
   ```bash
   git clone https://github.com/TiiJeiJ8/E-Library.git
   ```

### 贡献者

我们欢迎贡献！添加书籍的步骤：

1. **Fork** 本仓库
2. **选择** 合适的组织文件夹
3. **添加** 电子书文件，遵循命名规范
4. **记录** 你的添加（更新 README，添加摘要）
5. **提交** Pull Request

详见 [CONTRIBUTING.md](CONTRIBUTING.md)

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
