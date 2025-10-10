# 按流派浏览

[EN English](./README.md) | [ZH 中文](./README.zh-CN.md)

此目录按流派组织我们收藏的书籍。每个流派都有一个专门的子文件夹，其中包含一个 `README.md` 文件，列出了 [`../../library`](../../library/README.zh-CN.md) 目录中该类型的所有可用书籍。

## 工作原理

- **流派文件夹**：每个子文件夹都以一个流派命名（例如，`Fiction`、`Technical`）。流派可以**嵌套**以创建更具体的分类（例如，`Fiction/Science-Fiction`）。
- **书籍列表**：在每个流派的文件夹内，一个 `README.md` 文件提供了相关书籍的详细信息和链接。对于宽泛的流派，此文件也可以作为其子流派的索引。

该系统使您可以根据自己的兴趣发现书籍并探索不同的类别。

## 如何添加流派或子流派

1.  在 `by-genre/` 或现有流派文件夹内**创建新文件夹**（例如，`Fiction` 或 `Fiction/Science-Fiction`）。
2.  在新文件夹内**添加 `README.md` 文件**。
    -   对于**顶层流派**，请使用 [`genre-readme-template.zh-CN.md`](../../templates/genre-readme-template.zh-CN.md)。
    -   对于**子流派**，请使用 [`sub-genre-readme-template.zh-CN.md`](../../templates/sub-genre-readme-template.zh-CN.md) 以确保路径正确。
3.  在 `README.md` 中**列出该流派的书籍**。

## 示例结构

```
by-genre/
├── Fiction/
│   ├── README.md            (列出所有小说类书籍，或作为子流派的索引)
│   ├── Science-Fiction/
│   │   └── README.md        (列出所有科幻小说)
│   └── Fantasy/
│       └── README.md        (列出所有奇幻小说)
├── Technical/
│   └── README.md            (列出所有技术类书籍)
└── Science/
    └── README.md            (列出所有科学类书籍)
```

有关浏览馆藏的不同方法的更多信息，请参阅[书籍组织主页](../README.zh-CN.md)。

## 流派列表（按字母顺序）
- [经典文学](./Fiction/Classic-Literature/README.zh-CN.md)
- [小说](./Fiction/README.zh-CN.md)
