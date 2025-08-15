#  README

##  Student Information
- **Name:** Fernando Gorostieta Vargas  
- **ID:** 3065928  
- **Program:** Software Development Engineering  

##  Subject Information
- **Subject:** Web Application Design  
- **Professor:** Ricardo Gonzalez Alvarez  

---

##  What is Markdown?
Markdown is a lightweight markup language that uses plain text formatting syntax.  
It’s designed to be easy to read and write, while being convertible to HTML and other formats.  
Common uses include:
- **Documentation** (e.g., `README.md` files)
- **Technical writing** (guides, manuals)
- **Content creation** (blogs, notes)

---

## 🏷 Markdown Tagging & Formatting Options

Below are **core syntax elements** supported by most Markdown processors (including GitHub Flavored Markdown):

| Feature | Syntax | Example | Rendered Output |
|---------|--------|---------|-----------------|
| **Heading 1–6** | `#` to `######` | `## Heading 2` | ## Heading 2 |
| **Bold** | `**text**` or `__text__` | `**bold**` | **bold** |
| **Italic** | `*text*` or `_text_` | `*italic*` | *italic* |
| **Bold + Italic** | `***text***` | `***bold italic***` | ***bold italic*** |
| **Blockquote** | `> text` | `> Quote` | > Quote |
| **Ordered List** | `1. item` | `1. First` | 1. First |
| **Unordered List** | `- item` or `* item` | `- Bullet` | - Bullet |
| **Code (inline)** | `` `code` `` | `` `print("Hi")` `` | `print("Hi")` |
| **Code Block** | ```` ```lang ```` | ```python\nprint("Hi")\n``` | (code block) |
| **Link** | `[title](url)` | `[GitHub](https://github.com)` | [GitHub](https://github.com) |
| **Image** | `![alt](url)` | `![Logo](logo.png)` | ![Logo](logo.png) |
| **Table** | `| col1 | col2 |` | see table | see table |
| **Horizontal Rule** | `---` | `---` | --- |
| **Task List** (GFM) | `- [ ]` / `- [x]` | `- [x] Done` | - [x] Done |

 *Tip:* GitHub Flavored Markdown also supports syntax highlighting in fenced code blocks and task lists.

---

##  Git Commands Reference

Below are **essential Git commands** for common tasks:

### 1️ Check the status of a local repository
```bash
git status
```
Shows modified, staged, and untracked files.

---

### 2️ Add files to the staging area
- **Individual file:**
```bash
git add filename.ext
```
- **All changes:**
```bash
git add .
```

---

### 3️ Commit changes with a message
```bash
git commit -m "Your descriptive commit message"
```
💡 *Use short, meaningful messages in present tense.*

---

### 4️ Upload (push) changes to the remote repository
```bash
git push origin branch-name
```
Example for main branch:
```bash
git push origin main
```

---

### 5️ Branch management
- **Create a new branch:**
```bash
git branch branch-name
```
- **Switch to a branch:**
```bash
git checkout branch-name
```
- **Create & switch in one step:**
```bash
git checkout -b branch-name
```
- **List branches:**
```bash
git branch
```
- **Delete a branch (local):**
```bash
git branch -d branch-name
```

---

### 6️ Roll back to a specific commit
- **Soft reset** (keeps changes staged):
```bash
git reset --soft commit-hash
```
- **Hard reset** (discards changes):
```bash
git reset --hard commit-hash
```
 *Hard reset is destructive — use with caution.*

---

##  Notes
- Always run `git status` before committing to review changes.
- Use `.gitignore` to avoid committing unnecessary files.
- Commit often in logical chunks for easier tracking.

---

##  References
- [Markdown Basic Syntax Guide](https://www.markdownguide.org/basic-syntax/)  
- [Git Cheat Sheet – GeeksforGeeks](https://www.geeksforgeeks.org/git/git-cheat-sheet/)  
- [Laravel GitHub Repository README](https://github.com/laravel/laravel#readme)