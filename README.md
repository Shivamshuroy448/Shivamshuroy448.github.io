# 🚀 Shivamshu Roy — Portfolio Deployment Guide

Your production-ready portfolio is prepared inside:
`/Users/roy/.gemini/antigravity/scratch/portfolio/index.html`

---

## ⚡ Option 1: Free Hosting on GitHub Pages (Recommended)

Since your GitHub username is **`Shivamshuroy448`**, you can host this permanently for free at **`https://shivamshuroy448.github.io`**.

### Step 1: Create the GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Set the repository name to: **`Shivamshuroy448.github.io`** *(must match your username)*.
3. Keep it **Public** and click **Create repository**.

### Step 2: Push Your Code
Open your terminal in `/Users/roy/.gemini/antigravity/scratch/portfolio`:
```bash
cd /Users/roy/.gemini/antigravity/scratch/portfolio
git init
git add index.html
git commit -m "feat: Initial release of modern portfolio"
git branch -M main
git remote add origin https://github.com/Shivamshuroy448/Shivamshuroy448.github.io.git
git push -u origin main
```

Your site will be live at `https://shivamshuroy448.github.io` in under 60 seconds!

---

## ⚡ Option 2: Deploy to Vercel (1-Click)

1. Push your code to any GitHub repository (e.g. `portfolio`).
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your `portfolio` repo.
4. Click **Deploy** — Vercel gives you an instant `https://shivamshu-portfolio.vercel.app` domain with automatic SSL and fast global CDN.

---

## 📄 Adding Your Resume PDF
To make the **Resume (PDF)** button work:
1. Export your latest Overleaf resume as a PDF.
2. Rename the file to **`resume.pdf`**.
3. Place it in `/Users/roy/.gemini/antigravity/scratch/portfolio/resume.pdf`.
4. Commit and push it alongside `index.html`!
