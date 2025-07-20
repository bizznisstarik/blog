# OBS Productions Blog

A Hugo-powered blog for OBS Productions, built with the PaperMod theme and automatically deployed to GitHub Pages.

## 🚀 Quick Start

### Prerequisites
- Hugo (v0.133.1 or later)
- Git

### Local Development

1. **Navigate to the blog directory:**
   ```bash
   cd blog
   ```

2. **Install theme:**
   ```bash
   git submodule update --init --recursive
   ```

3. **Start the development server:**
   ```bash
   hugo server --buildDrafts
   ```

4. **Open your browser:**
   ```
   http://localhost:1313
   ```

## 🚀 Deployment

The blog automatically deploys to GitHub Pages when you push changes to the `main` or `master` branch that affect the `blog/` directory.

### GitHub Pages Setup

1. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: **GitHub Actions**

2. **Update baseURL in hugo.toml:**
   ```toml
   baseURL = 'https://yourusername.github.io/repository-name/'
   ```

3. **Push changes:**
   ```bash
   git add .
   git commit -m "Add Hugo blog"
   git push
   ```

## 📝 Creating Content

### New Blog Post
```bash
hugo new content/posts/my-new-post.md
```

## 🎨 Features

- 🌓 Dark/Light mode toggle
- 📱 Fully responsive design
- ⚡ Fast loading with Hugo
- 🔍 SEO optimized
- 📊 Analytics ready

---

**Powered by Hugo & PaperMod Theme**