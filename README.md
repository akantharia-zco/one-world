# One-World — International Groceries & Halal Meats

This is the fully optimized, self-contained website for **One-World** (Fry Road location), offering international groceries and premium halal meats for scheduled pickup or neighborhood delivery.

## 🚀 Key Improvements & Optimizations
We took the single-file demo HTML (8.2 MB) and transformed it into a premium, production-ready codebase:
1. **Extracted Base64 Assets**: All 3 embedded images (hero background, logo, location photo) have been parsed, decoded, and saved to the `assets/` folder, reducing `index.html` from **8.2 MB to ~19 KB** for near-instant page loads.
2. **Image Compression**: Converted the large photographic PNGs (hero background, location) to optimized JPEGs, cutting their combined size by over 85% with no visible quality loss.
3. **Vercel Integration**: Added `vercel.json` to enable clean URLs and configure high-performance caching for local assets.

---

## 🛠️ Step-by-Step Deployment Guide

Follow these steps to push your website to GitHub and host it live on Vercel for free:

### Step 1: Initialize Git and Make First Commit
We have already initialized a local Git repository and created the initial commit for you. The files are ready to go.

### Step 2: Create a New GitHub Repository
1. Go to [github.com](https://github.com) and log in.
2. Click the **"+"** icon in the top-right corner and select **"New repository"**.
3. Name your repository (e.g., `one-world`) and keep it Public or Private as you prefer.
4. Leave "Add a README file", "Add .gitignore", and "Choose a license" **unchecked** (we already have these in our code).
5. Click **"Create repository"**.

### Step 3: Link Local Project to GitHub and Push
Open your terminal, navigate to the project directory, and run the following commands (replacing `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name):

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

### Step 4: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com) and log in (you can sign up using your GitHub account).
2. On your Vercel Dashboard, click **"Add New..."** and choose **"Project"**.
3. Import the repository you just pushed (`YOUR_REPO_NAME`).
4. Keep the default settings (Vercel will automatically detect it as a static website).
5. Click **"Deploy"**.

Within seconds, your site will be live on a custom `.vercel.app` domain, and Vercel will automatically redeploy it every time you push changes to your GitHub repository!

---

## 📂 Project Structure
```text
├── assets/            # All optimized local images & design assets
├── .gitignore         # Ignores OS-specific cache files (like .DS_Store)
├── index.html         # Homepage (Optimized)
├── vercel.json        # Vercel-specific routing & headers config
└── README.md          # This instruction file
```
