# How to Deploy Your Portfolio to GitHub Pages

Your portfolio is ready to go online! Follow these steps to get a shareable link.

## Step 1: Create a GitHub Repository

1. Go to https://github.com/new
2. Repository name: `portfolio` (or any name you like)
3. Make it **Public**
4. Check "Add a README file" (optional)
5. Click "Create repository"

## Step 2: Upload Your Files

### Option A: Using GitHub Web Interface
1. Click "uploading an existing file"
2. Drag and drop all your files:
   - index.html
   - style.css
   - script.js
   - image.jpg
3. Click "Commit changes"

### Option B: Using Git (Command Line)
```bash
cd C:\Users\Asus\OneDrive\Desktop\portfolio\portfolio
git init
git add .
git commit -m "Initial commit - Portfolio website"
git branch -M main
git remote add origin https://github.com/jevison-js/portfolio.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Select branch: `main`
6. Select folder: `/ (root)`
7. Click "Save"

## Step 4: Get Your Link!

Your website will be live at:
**https://jevison-js.github.io/portfolio/**

(Replace `portfolio` with your repository name if different)

Wait 2-3 minutes for the site to deploy, then share this link with everyone! 🎉

---

**Quick Alternative: Netlify (Even Easier!)**
1. Go to https://netlify.com
2. Drag and drop your portfolio folder
3. Get instant link!!

