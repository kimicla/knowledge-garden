---
title: How to Organize
tags:
  - knowledge-management
---

# 📂 Organization & Asset Management

To keep your garden healthy, we recommend this simple structure.

## 🗂 Recommended Folder Structure

- **`content/`**: The root of your garden.
  - **`assets/`**: Store images, PDFs, and other attachments here.
  - **`journals/`**: Daily notes, thoughts, and logs.
  - **`projects/`**: Active projects you are working on right now.
  - **`topics/`**: Knowledge sorted by topic (e.g., Coding, Cooking).
  - `index.md`: Your home page.

## 🖼 Handling Images (Assets)

### In Obsidian

1.  Go to **Settings > Files & Links**.
2.  Set **Default location for new attachments** to: `In folder below current folder`.
3.  Subfolder name: `assets`.

**Why?**
When you paste an image into Obsidian, it will automatically go into `assets/` instead of cluttering your root folder.

### In Markdown

To include an image:

```markdown
![[my-image.png]]
```

Quartz will automatically find `my-image.png` inside `assets/` and display it.

## 🏷 Using Tags

Use tags for status rather than folders.

- `#seed`: A new, rough idea.
- `#budding`: Developing thought.
- `#evergreen`: Polished, finished note.
