# Contributing to E-Library

[EN English](./CONTRIBUTING.md) | [ZH 中文](./CONTRIBUTING.zh-CN.md)

Thank you for your interest in contributing to E-Library! This document provides guidelines for adding e-books and improving the repository.

## How to Contribute

All contributions are made via Pull Requests. Whether you are adding a new book or improving documentation, the basic workflow is as follows:

1.  **Fork the repository**: Create your own fork.
2.  **Create a new branch**: Make your changes in a separate branch.
3.  **Commit your changes**: Complete and commit your modifications.
4.  **Open a Pull Request**: Merge your branch into the main repository.

### Adding a New Book

Adding a new book involves two main steps: uploading the book file and creating its index entry.

#### Step 1: Add the Book File to `library/`

Place the e-book file (e.g., `.epub`, `.pdf`) into the sub-repository [E-Library-Books-Repo](https://github.com/TiiJeiJ8/E-Library-Books-Repo) `library/` directory. Please follow a clear directory structure, such as `library/Author-LastName-FirstName/Book-Title-YYYY/`.
For online uploads, refer to GitHub's "Creating new files" tutorial: [Creating new files](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)

> 💡 **Tip**: For small files (< 25MB), you can use the **"Add file" → "Upload files"** feature on the GitHub website to upload them directly. For larger files, you will need to clone the repository locally to add them.

#### Step 2: Create the Index and Documentation

After the book file is uploaded, you need to create its index and related documentation. **This step can be done entirely through the web interface, without cloning the repository.**

> You will need to prepare:
> - Basic book information (author, title, year, format, etc.)
> - A README document for the author category (if the author already exists, add to their file; otherwise, create a new one).
> - A README document for the genre category (if the genre already exists, add to its file; otherwise, create a new one).
> - A README document for the topic category (if the topic already exists, add to its file; otherwise, create a new one).
> - A book summary document (stored in the `docs/summaries/` directory).
> **Additionally, you must check and update the parent folder's `README` file**:
    - If you add a new sub-genre `Political-Fiction` under `books/by-genre/Fiction/`, ensure you add a link to it in `Fiction`'s `README.md`.
    - If you add a new author under `books/by-author/`, ensure you add a link to the author's folder in `by-author/README.md`.

1.  **Create an index in `books/`**:
    -   Create or update the corresponding `README.md` file under `books/by-author/`, `books/by-genre/`, and `books/by-topic/` to add the book's information.
    -   When creating an index entry, please ensure you include the following information:
        -   **Title**: Full book title
        -   **Author**: Author name(s)
        -   **Year**: Publication year
        -   **Format**: File format
        -   **Description**: Brief summary (2-3 sentences)
        -   **Topics/Tags**: Relevant keywords
    -   You can use a template to get started quickly: [`author-readme-template.md`](./templates/author-readme-template.md)

2.  **Add a summary in `docs/`**:
   -   Create a new Markdown file under `docs/summaries/`, named `AuthorLastName_BookTitle_Year.md`.
   -   Include a brief summary of the book, key themes, and any other relevant information.
   -   You can use [`summary-template.md`](./templates/book-summary-template.md) as a starting point.

3.  **(Optional) Add a notes in `docs/`**:
    -   Create a corresponding file under `docs/summaries/` or `docs/reading-notes/`.
    -   Please follow the file naming conventions specified in the `README.md` of those directories.

**How to create and edit these files online?**

You can use any of the following methods to create and edit the text files mentioned above:

-   **Method 1: Create a New File**
    1.  On the GitHub repository page, click **"Add file" → "Create new file"**.
    2.  Enter the **full path** in the filename box, e.g., `books/by-author/Orwell-George/README.md`. GitHub will create the folders automatically.
    3.  After editing the content, open a Pull Request.

-   **Method 2: Edit an Existing File**
    1.  Open the target file (e.g., a `README.md`).
    2.  Click the **pencil icon ✏️ (Edit this file)** in the upper right corner.
    3.  After making changes, open a Pull Request.

-   **Method 3: Use the GitHub.dev Online Editor**
    1.  On the repository page, press the `.` key on your keyboard.
    2.  In the web-based VS Code editor that opens, you can freely create, edit, and commit files.

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
