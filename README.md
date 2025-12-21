# Andy's Blog (Hexo)

This is the source code for [Andy's Blog](https://andy78644.com).

## 🚀 Branch Structure

- **`main`**: Contains the **source code** (Markdown files, themes, configurations).
- **`gh-pages`**: Contains the **generated static files** (HTML, CSS, JS) served by GitHub Pages.

---

## 🛠 Workflow

### 1. Write or Edit Posts
- Create a new post: `hexo new "My New Post"`
- Edit the Markdown file in `source/_posts/`.

### 2. Local Preview
```bash
hexo clean && hexo server
```
Visit http://localhost:4000/ to see changes.

### 3. Save Source Code (Push to GitHub `main`)
Always keep your `main` branch updated with your source code.
```bash
git add .
git commit -m "feat: add new post about XYZ"
git push origin main
```

### 4. Deploy to Live Site (Push to GitHub `gh-pages`)
This updates the actual website.
```bash
hexo clean && hexo generate && hexo deploy
```

---

## 📋 Prerequisites

- **Node.js**: v22.x
- **Hexo CLI**: `npm install -g hexo-cli`

## ⚙️ Setup

```bash
npm install
```

---

## 🔧 Technical Details
- **Theme**: [Redefine v2.8.5](https://github.com/EvanNotFound/hexo-theme-redefine)
- **Framework**: [Hexo 8.1.1](https://hexo.io/)
- **Visitor Count**: Powered by [Vercount](https://vercount.one/)
