# 书库（Library）

此文件夹用于存放实际的电子书文件（PDF/EPUB/MOBI/AZW 等）。

- 仓库中的 `books/` 仅作为索引/目录视图（按作者/类别/主题）。
- 请将所有二进制书籍文件放在 `library/` 下，并使用清晰的子目录结构（如 作者/书名/年份）。
- 文档（摘要、阅读笔记）存放在 `docs/`，并由 `books/` 索引页面链接到相应条目。

## 推荐结构

```
library/
  Author-Last-Name-First-Name/
    Book-Title-YYYY/
      AuthorLastName_BookTitle_Year.pdf
      AuthorLastName_BookTitle_Year.epub
```

## 建议使用 Git LFS

为避免仓库膨胀，大文件建议使用 Git LFS 跟踪。
可以考虑跟踪的扩展名：
- *.pdf, *.epub, *.mobi, *.azw, *.azw3

## 注意

- 不要提交受版权保护且无授权的内容；仅提交公有领域、开源许可或已获明确授权的资料。
- 请遵循命名规范并保持一致性。
