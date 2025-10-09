# Contributing to E-Library 📚

Thank you for your interest in contributing to E-Library! This document provides guidelines for adding books and improving the repository.

## 📖 How to Contribute

### Adding Books

1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/E-Library.git
   cd E-Library
   ```

2. **Create a New Branch**
   ```bash
   git checkout -b add-book-name
   ```

3. **Add Your Book(s)**
   - Place the book file in the appropriate category folder under `books/`
   - Follow the naming convention: `Author_Last_Name - Book_Title.extension`
   - Ensure the file is in a supported format (PDF, EPUB, MOBI, AZW3, DJVU, TXT)

4. **Commit Your Changes**
   ```bash
   git add books/category/Author_Name - Book_Title.pdf
   git commit -m "Add: Author Name - Book Title"
   ```

5. **Push and Create Pull Request**
   ```bash
   git push origin add-book-name
   # Then create a pull request on GitHub
   ```

## 📋 Contribution Guidelines

### File Requirements

- **Format**: Use supported e-book formats (PDF, EPUB, MOBI, AZW3, DJVU, TXT)
- **Quality**: Ensure books are readable and of good quality
- **Size**: For files larger than 100MB, consider using Git LFS (Large File Storage)
- **Naming**: Follow the standard naming convention

### Naming Convention

Use this format for consistency:
```
Author_Last_Name - Book_Title.extension
```

**Examples:**
- ✅ `Knuth_Donald - The_Art_of_Computer_Programming.pdf`
- ✅ `Austen_Jane - Pride_and_Prejudice.epub`
- ❌ `book1.pdf` (too vague)
- ❌ `The Art of Computer Programming.pdf` (missing author)

**Special Cases:**
- Multiple authors: Use first author's name, e.g., `Smith_John_et_al - Book_Title.pdf`
- Multiple volumes: Include volume number, e.g., `Author - Book_Title_Vol_1.pdf`
- Editions: Include edition if relevant, e.g., `Author - Book_Title_2nd_Edition.pdf`

### Category Selection

Choose the most appropriate category for your book:

| Category | Description | Examples |
|----------|-------------|----------|
| `computer-science` | Programming, algorithms, software engineering | "Clean Code", "Introduction to Algorithms" |
| `fiction` | Novels, short stories, literary fiction | "1984", "The Great Gatsby" |
| `non-fiction` | History, biography, self-help | "Sapiens", "The Diary of Anne Frank" |
| `technology` | Tech guides, IT manuals, emerging tech | "The Pragmatic Programmer", "Networking Basics" |
| `business` | Management, entrepreneurship, finance | "The Lean Startup", "Good to Great" |
| `science` | Natural sciences, mathematics, physics | "A Brief History of Time", "Calculus" |
| `arts` | Visual arts, music, design | "The Art Book", "Interaction Design" |
| `reference` | Dictionaries, encyclopedias, manuals | "Oxford Dictionary", "Grammar Guide" |

If a book fits multiple categories, choose the primary focus or create a subdirectory if needed.

### Copyright and Legal Considerations

**⚠️ IMPORTANT**: Only add books that you have the legal right to share.

Acceptable sources:
- ✅ Public domain books (published before 1928 in the US, or other jurisdictions)
- ✅ Books with open licenses (Creative Commons, GPL for documentation, etc.)
- ✅ Author-authorized free distributions
- ✅ Books you authored and own the copyright to
- ✅ Educational materials explicitly licensed for sharing

**DO NOT** add:
- ❌ Copyrighted books without permission
- ❌ Pirated or illegally obtained materials
- ❌ Books that violate any copyright laws

When in doubt, do not add the book. Contributors are responsible for ensuring their contributions comply with copyright laws.

### Pull Request Guidelines

When creating a pull request:

1. **Title Format**: Use "Add: [Book Title] by [Author Name]"
   - Example: "Add: Clean Code by Robert C. Martin"
   - For multiple books: "Add: Multiple books in Computer Science category"

2. **Description**: Include:
   - Book title and author
   - Brief description (optional but helpful)
   - Source/proof of legal availability (if not obvious)
   - Any relevant notes

3. **Example PR Description:**
   ```markdown
   ## Books Added
   
   ### Computer Science
   - **Clean Code** by Robert C. Martin
   - **The Pragmatic Programmer** by Andrew Hunt and David Thomas
   
   ### Notes
   These books are from my personal collection and are being shared under fair use for educational purposes.
   ```

## 🔧 Improving the Repository

Contributions aren't limited to adding books! You can also:

- **Improve Documentation**: Enhance README, add category descriptions
- **Suggest Structure Changes**: Propose new categories or reorganization
- **Fix Issues**: Report or fix broken links, incorrect filenames
- **Add Features**: Suggest metadata files, indexing systems, search improvements

## 📝 Code of Conduct

- Be respectful and professional
- Follow all guidelines and conventions
- Respect copyright and intellectual property
- Help maintain a welcoming environment

## ❓ Questions?

If you have questions or need help:
1. Check existing issues for answers
2. Open a new issue with your question
3. Tag it appropriately (e.g., "question", "help wanted")

## 🙏 Thank You!

Your contributions help build a valuable resource for everyone. Thank you for following these guidelines and contributing responsibly!

---

Happy Contributing! 📚✨
