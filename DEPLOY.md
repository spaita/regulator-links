# GitHub Pages Deployment Instructions

## Step 1: Create GitHub Repository
1. Go to: https://github.com/new
2. Repository name: `regulator-links`
3. Description: `One-click tool for Regulator merchant review workflow`
4. Make it **Public**
5. Don't initialize with README
6. Click "Create repository"

## Step 2: Push Code (run these commands)

```bash
cd /Users/spaita/regulator-links

# Add the remote (use YOUR repo URL from GitHub)
git remote add origin https://github.com/spaita/regulator-links.git

# Rename branch to main (GitHub's default)
git branch -M main

# Push to GitHub
git push -u origin main
```

## Step 3: Enable GitHub Pages
1. Go to your repo: https://github.com/spaita/regulator-links
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Source", select: **main** branch
5. Click **Save**
6. Wait 1-2 minutes for deployment

## Step 4: Get Your Live URL
Your site will be live at:
**https://spaita.github.io/regulator-links/**

## Step 5: Share with Team
Share this link with your team - they can bookmark it and follow the instructions!

---

## Quick Commands Reference

```bash
# If you need to make changes later:
cd /Users/spaita/regulator-links
# Edit index.html or other files
git add .
git commit -m "Update description"
git push

# Changes will be live in 1-2 minutes
```
