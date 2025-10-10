# Contributing to E-Library

[EN English](./CONTRIBUTING.md) | [CN 中文](./CONTRIBUTING.zh-CN.md)

Thank you for your interest in contributing to E-Library! This document provides guidelines for adding e-books and improving the repository.

## How to Contribute

For lightweight contributions (like updating indexes, documentation, or metadata), you can **work directly on GitHub** without cloning the repository or setting up a local environment.

#### Method 1: Use the GitHub Web Interface

1. Open the repository page (or your fork).
2. Click **"Add file" → "Create new file"** in the upper right corner.
3. Enter the full file path in the name field, e.g., `books/by-author/Orwell-George/README.md`.
   > 💡 GitHub will automatically create the necessary folder structure.
4. Add your content (like book info or a summary) in the editor.
5. At the bottom, fill in the commit message and select:
   - ✅ "Create a new branch for this commit and start a pull request"
6. Click **"Propose changes"**, and GitHub will guide you to create a Pull Request.

#### Method 2: Edit an Existing File

1. Open the file you want to modify (e.g., a `README.md`).
2. Click the **pencil icon ✏️ (Edit this file)** in the upper right corner.
3. After making your changes, commit them and create a Pull Request.

#### Method 3: Use the GitHub.dev Online Editor (Shortcut: `.`)

1. On the repository page, press the `.` (period) key.
   GitHub will open a web-based VS Code editor.
2. You can:
   - Create folders and files
   - Edit content
   - Commit changes and create a PR
3. No software installation or command-line tools are needed.

### Adding New E-Books (Full Workflow)

1. **Fork the Repository**: Create your own fork of this repository
2. **Place Files under `library/`**: Store actual e-book files under `library/` using a clear structure (e.g., `Author-Last-Name-First-Name/Book-Title-YYYY/`).
3. **Index in `books/`**: Create or update the book's entry in the appropriate index README:
   - `books/by-genre/` — list the book under the relevant genre
   - `books/by-author/` — list the book under the author's folder
   - `books/by-topic/` — list the book under relevant topics
   README template can be found [Link](./templates/README.md)
4. **Submit a Pull Request**: Describe the book you're adding and why it's valuable

### File Naming Convention

- Use descriptive names: `AuthorLastName_BookTitle_Year.ext`
- Example: `Orwell_1984_1949.epub`
- Avoid special characters and spaces (use underscores or hyphens)

### Supported Formats

- PDF (.pdf)
- EPUB (.epub)
- MOBI (.mobi)
- AZWX (.azw, .azw3)
- Other text-based formats

### Book Documentation

When adding a book, please include:
- **Title**: Full book title
- **Author**: Author name(s)
- **Year**: Publication year
- **Format**: File format
- **Description**: Brief summary (2-3 sentences)
- **Topics/Tags**: Relevant keywords

### Quality Guidelines

- Place binaries in `library/` and ensure files are not corrupted
- Respect copyright laws - only add books in the public domain or with appropriate licenses
- Maintain consistent naming and organization
- Test that files open correctly

### Bilingual Guidance

- Prefer single-file bilingual sections for small pages, or separate `README.md` and `README.zh-CN.md` for larger content. For larger content, split into two files: `README.md` and `README.<language>-<region>.md`.
- Keep metadata consistent across languages.
- Note: At least one version must be in English.

### Code of Conduct

Please be respectful and constructive in all interactions. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details.

## Improving the Repository

You can also contribute by:
- Improving documentation
- Suggesting better organization structures
- Adding reading notes or summaries
- Fixing broken links or outdated information
- Creating helpful templates

## Questions?

If you have questions, please open an issue with the `question` label.

Thank you for helping build a collaborative digital library!
