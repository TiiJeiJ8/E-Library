# Library

[EN English](./README.md) | [CN 中文](./README.zh-CN.md)

This folder is the canonical location for storing actual e-book files (PDF/EPUB/MOBI/AZW, etc.).

- The `books/` folder in the repo acts as an index/catalog only (author/genre/topic views).
- Place all binary book files under `library/` using clear subfolders (e.g., Author/Title/Year or similar).
- Keep documentation (summaries, notes) under `docs/` and use links from `books/` indexes.

## Suggested Structure

```
library/
  Author-Last-Name-First-Name/
    Book-Title-YYYY/
      AuthorLastName_BookTitle_Year.cn.pdf
      AuthorLastName_BookTitle_Year.en.epub
      AuthorLastName_BookTitle_YYYY.<language>.ext
```

## Notes

- Do not commit copyrighted materials unless they are public domain, under open licenses, or you have explicit permission.
- Keep filenames descriptive and consistent with the naming convention.
