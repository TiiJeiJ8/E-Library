# 按作者组织的书籍

[US English](./README.md) | [CN 中文](./README.zh-CN.md)

**说明**：本目录仅作为索引视图。实际电子书文件存放在 [library/](../../library/README.zh-CN.md)。

本文件夹按作者姓氏组织电子书。每位作者都有自己的子文件夹。

## 组织方式

- 使用作者**姓氏**创建子文件夹
- 对于有多部作品的作者，将所有作品放在同一子文件夹中
- 文件夹命名格式示例：`LastName-FirstName/`

## 添加书籍

1. 使用格式 `LastName-FirstName/` 创建作者子文件夹
2. 将电子书文件添加到作者文件夹中
3. 更新该作者文件夹的  [README](../../templates/author-readme-template.zh-CN.md)，添加书籍信息和必要的元数据

## 示例结构

```
by-author/
├── Orwell-George/
│   ├── README.md
│   ├── Orwell_1984_1949.epub
│   └── Orwell_AnimalFarm_1945.epub
├── Hawking-Stephen/
│   ├── README.md
│   └── Hawking_ABriefHistoryOfTime_1988.epub
└── Kernighan-Brian/
    ├── README.md
    └── Kernighan_TheCProgrammingLanguage_1988.pdf
```

## 优点

- 容易查找特定作者的全部作品
- 简单的字母顺序浏览
- 适合以作者为中心的收藏
