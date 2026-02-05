# Getting Started with Your Knowledge Garden

Your digital garden is set up and ready to grow! 🌱

## 📂 Where to write

All your notes live in the `content` folder:

- `/Users/0x1348c59/Documents/knowledge-garden/content`

## ✍️ How to write

1. Create a new `.md` file in the `content` folder.
2. Use standard Markdown syntax.
3. Link to other notes using `[[Note Name]]`.

## 🚀 How to preview locally

Run this command in your terminal from the `knowledge-garden` folder:

```bash
npx quartz build --serve
```

Then open `http://localhost:8080` in your browser.

## 💎 Setting up Obsidian (Parallel Workflow)

1.  Open **Obsidian**.
2.  Click **"Open folder as vault"**.
3.  Select this folder: `/Users/0x1348c59/Documents/knowledge-garden`.
4.  **Start Writing**:
    - Create files inside the `content/` folder.
    - Quartz will automatically rebuild and refresh your browser preview!

## 🌐 How to publish (GitHub Pages)

1. Create a new repository on GitHub.
2. Push this folder to the repository.
3. Enable GitHub Actions for deployment (Quartz includes a ready-to-use workflow).

## 📚 Learn More

- [Quartz Documentation](https://quartz.jzhao.xyz/)
- [Obsidian](https://obsidian.md/) (Recommended editor)
