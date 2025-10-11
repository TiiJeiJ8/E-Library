# E-Library 📚

[EN English](./README.md) | [ZH 中文](./README.zh-CN.md)

An open, community-built GitHub repository for storing, managing, and sharing electronic book files. This project is designed to let contributors upload, curate, and maintain a collective e-book library. We provide clear folder structure, metadata templates, and contribution guidelines to keep the collection organized, discoverable, and legally compliant.

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

## 📖 About

E-Library is a centralized, version-controlled, community-maintained digital library. Perfect for:
- Individuals building personal e-book collections
- Study groups and clubs sharing reading materials
- Educators and teams distributing course readings
- Community contributors who upload and curate books to grow a shared library

Want to help build the collection? Please read [CONTRIBUTING.md](CONTRIBUTING.md) and follow copyright and licensing guidelines before adding files.

## 🗂️ Repository Structure

```
E-Library/
├── library/           # Actual e-book files (PDF/EPUB/MOBI/AZW, etc.)
├── books/
│   ├── by-genre/       # Books organized by genre (Fiction, Technical, etc.)
│   ├── by-author/      # Books organized by author's last name
│   └── by-topic/       # Books organized by specific topics
├── docs/
│   ├── summaries/      # Brief book summaries and overviews
│   └── reading-notes/  # Detailed reading notes and insights
├── templates/          # Templates for documentation and organization
├── CONTRIBUTING.md     # Contribution guidelines
├── CODE_OF_CONDUCT.md  # Community guidelines
└── README.md          # This file
```

## 🚀 Getting Started

### Quick Jump

- [Library](https://github.com/TiiJeiJ8/E-Library-Books-Repo) — Actual e-book files live here (sub-repo)
- [Books](./books/README.md) — Browse books by genre, author, or topic
- [Books by genre](./books/by-genre/README.md)
- [Books by author](./books/by-author/README.md)
- [Books by topic](./books/by-topic/README.md)
- [Summaries](./docs/summaries/README.md)
- [Reading notes](./docs/reading-notes/README.md)
- [Templates](./templates/README.md)
- [Contributing guide](./CONTRIBUTING.md)

### For Readers

Getting a book from E-Library is easy.

1.  **Find a Book to Read**
    Use our "Quick Jump" section or the links below to browse the collection:
    *   [By Genre](./books/by-genre/README.md)
    *   [By Author](./books/by-author/README.md)
    *   [By Topic](./books/by-topic/README.md)

2.  **Learn More About It**
    Want to know if a book is right for you? Check out the [summaries](./docs/summaries/README.md) for a quick overview.

3.  **Get Your Copy**
    Note: the actual ebook files have been moved to a dedicated sub-repository to keep this main repository focused on metadata, summaries and templates. Use the sub-repo below to download files.

    You have two options:
    *   **Download a Single Book**: Visit the sub-repository's `library/` directory and download a book file directly from your browser:
            https://github.com/TiiJeiJ8/E-Library-Books-Repo/tree/main/library
    *   **Download/Clone the Entire Books Repo**: If you want a copy of all ebook files, clone the sub-repository:
        ```powershell
        git clone https://github.com/TiiJeiJ8/E-Library-Books-Repo.git
        ```
    Optional: if you prefer to keep the main repo and the books repo together in your workspace, you can add the books repo as a git submodule inside this repo:
        ```powershell
        git submodule add https://github.com/TiiJeiJ8/E-Library-Books-Repo.git library
        git submodule update --init --recursive
        ```

### For Contributors

Want to help grow our library? We'd love your help! Here’s how you can add a new book:

1.  **Fork the Repository**
    Create your own copy of this project to work on.

2.  **Add the Book File**
    Place your e-book file (e.g., PDF, EPUB) into the `library/` directory. Please follow the [File Naming Convention](#-file-naming-convention).

3.  **Create Index Entries and Documentation**
    Make the book discoverable by adding it to the index files in `books/` and creating a summary in `docs/summaries/`. Use our [templates](./templates/README.md) to keep everything consistent.

4.  **Submit a Pull Request**
    Propose your changes to the main repository. We'll review them and merge them in.

For more detailed instructions, please read our full **[Contributing Guide](./CONTRIBUTING.md)**.

## 📋 File Naming Convention

Use descriptive names following this pattern:
```
AuthorLastName_BookTitle_Year.ext
```

**Examples:**
- `Orwell_1984_1949.epub`
- `Kernighan_TheCProgrammingLanguage_1988.pdf`
- `Hawking_ABriefHistoryOfTime_1988.epub`

## 📚 Supported Formats

- **PDF** (.pdf) - Portable Document Format
- **EPUB** (.epub) - Electronic Publication
- **MOBI** (.mobi) - Mobipocket
- **AZW** (.azw, .azw3) - Amazon Kindle Format
- Other text-based e-book formats

## 🎯 Features

- **Multiple Organization Methods**: Choose genre, author, or topic-based browsing
- **Rich Documentation**: Book summaries and reading notes enhance discovery
- **Templates**: Standardized templates ensure consistency
- **Version Control**: Track changes and maintain history via Git
- **Collaborative**: Open for contributions and improvements
- **Searchable**: Use GitHub's search to find books quickly

## 📖 Documentation

Each book should include:
- **Summary** (in `docs/summaries/`): Brief overview, key themes, target audience
- **Reading Notes** (optional, in `docs/reading-notes/`): Detailed insights and highlights
- **Catalog Entry**: Listed in the appropriate folder's README

Use our [templates](templates/) to maintain consistency.

## 🤝 Contributing

We encourage contributions! You can help by:

- **Adding new e-books** (respecting copyright and licensing)
- **Writing summaries** and reading notes
- **Improving documentation** and organization
- **Suggesting enhancements** via issues
- **Fixing errors** or broken links

Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## ⚖️ Copyright & Legal

**Important**: Only add books that are:
- In the **public domain**
- Licensed under **Creative Commons** or similar open licenses
- You have **explicit permission** to share

Respect copyright laws and intellectual property rights. Contributors are responsible for ensuring they have the right to share any materials they add.

## 📜 License

This repository structure and documentation are licensed under the [MIT License](LICENSE).

Individual books retain their original copyrights and licenses.

## 🌟 Getting Help

- **Questions?** Open an issue with the `question` label
- **Found a bug?** Open an issue with the `bug` label
- **Have a suggestion?** Open an issue with the `enhancement` label

## 🙏 Acknowledgments

Thank you to all contributors who help build and maintain this collaborative digital library!


<a href="https://github.com/TiiJeiJ8/E-Library/graphs/contributors">
  <p align="left">
    <img width="500" src="https://contrib.rocks/image?repo=TiiJeiJ8/E-Library" alt="A table of avatars from the project's contributors" />
  </p>
</a>

---

**Happy Reading! 📚✨**