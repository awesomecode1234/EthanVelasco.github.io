# Complete Deployment Guide - Free Hosting & Free Domain

This guide will help you deploy your personal site for **100% FREE** without requiring any credit card.

## 🚀 Quick Start Options

### Option 1: GitHub Pages (Recommended - Easiest)

**Free Domain**: `yourusername.github.io` (100% free, no credit card)

#### Steps:

1. **Create GitHub Account** (if you don't have one)
   - Go to [github.com](https://github.com) and sign up (free)

2. **Create a New Repository**
   - Click the "+" icon → "New repository"
   - Repository name: `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it **Public**
   - Don't initialize with README
   - Click "Create repository"

3. **Upload Your Files**
   
   **Method A: Using GitHub Desktop (Easiest)**
   - Download [GitHub Desktop](https://desktop.github.com/)
   - Install and sign in
   - Click "File" → "Add Local Repository"
   - Select your `personal site` folder
   - Click "Publish repository"
   - Make sure it's Public
   - Click "Publish repository" again

   **Method B: Using Git Command Line**
   ```bash
   cd "D:\personal site"
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

   **Method C: Using GitHub Web Interface**
   - In your repository, click "uploading an existing file"
   - Drag and drop all files from your `personal site` folder
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to your repository → "Settings" tab
   - Scroll to "Pages" section (left sidebar)
   - Under "Source", select "Deploy from a branch"
   - Branch: `main` → Folder: `/ (root)`
   - Click "Save"

5. **Your Site is Live!**
   - Wait 1-2 minutes
   - Visit: `https://yourusername.github.io`
   - ✅ **100% FREE - No credit card needed!**

---

### Option 2: Netlify (Easiest Drag & Drop)

**Free Domain**: `your-site-name.netlify.app` (100% free, no credit card)

#### Steps:

1. **Create Netlify Account**
   - Go to [netlify.com](https://netlify.com)
   - Click "Sign up" → Use GitHub, Email, or Google (all free, no credit card)

2. **Deploy Your Site**
   - After signing in, you'll see a drag-and-drop area
   - Simply drag your entire `personal site` folder onto the page
   - Wait 30 seconds
   - Your site is live at `random-name-12345.netlify.app`

3. **Customize Domain Name**
   - Click on your site → "Site settings" → "Change site name"
   - Choose a name like `ethan-velasco-portfolio`
   - Your new URL: `ethan-velasco-portfolio.netlify.app`

4. **Auto-Deploy from GitHub (Optional)**
   - Connect your GitHub repository
   - Every time you push changes, site auto-updates
   - No credit card required!

---

### Option 3: Vercel (Great for Performance)

**Free Domain**: `your-site-name.vercel.app` (100% free, no credit card)

#### Steps:

1. **Create Vercel Account**
   - Go to [vercel.com](https://vercel.com)
   - Click "Sign up" → Use GitHub (recommended)
   - No credit card required

2. **Deploy**
   - Click "Add New" → "Project"
   - Import your GitHub repository OR
   - Drag and drop your folder
   - Click "Deploy"
   - Your site is live in 30 seconds!

---

### Option 4: Cloudflare Pages (Fastest CDN)

**Free Domain**: `your-site-name.pages.dev` (100% free, no credit card)

#### Steps:

1. **Create Cloudflare Account**
   - Go to [cloudflare.com](https://cloudflare.com)
   - Sign up (free, no credit card)

2. **Deploy**
   - Go to "Pages" → "Create a project"
   - Upload your folder or connect GitHub
   - Click "Deploy site"
   - Your site is live!

---

## 🌐 Free Custom Domain Options (No Credit Card)

### Option 1: Freenom (.tk, .ml, .ga, .cf domains)

**100% Free Domain** - No credit card required

#### Steps:

1. **Get Free Domain**
   - Go to [freenom.com](https://freenom.com)
   - Create free account
   - Search for a domain (e.g., `ethanvelasco.tk`)
   - Select "Get it now" → "Checkout" → "Complete Order"
   - Domain is FREE for 1 year (renewable)

2. **Connect to Your Hosting**
   
   **For GitHub Pages:**
   - In your repository → Settings → Pages
   - Under "Custom domain", enter your domain (e.g., `ethanvelasco.tk`)
   - Add a file named `CNAME` in your repository root with content: `ethanvelasco.tk`
   - Go to Freenom → Manage Domain → Manage Freenom DNS
   - Add A record: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Add CNAME record: `www` → `yourusername.github.io`

   **For Netlify:**
   - Site settings → Domain management → Add custom domain
   - Enter your domain
   - Follow Netlify's DNS instructions

---

### Option 2: GitHub Pages Subdomain (Already Free!)

- You already get: `yourusername.github.io`
- This is a real domain, 100% free forever
- No credit card, no expiration

---

### Option 3: Free Subdomain Services

1. **No-IP** (noip.com) - Free subdomains
2. **DuckDNS** (duckdns.org) - Free subdomains
3. **FreeDNS** (freedns.afraid.org) - Free subdomains

---

## 📋 Complete Deployment Checklist

### Before Deploying:

- [ ] Test your site locally (open `index.html` in browser)
- [ ] Ensure all images are in correct folders
- [ ] Check all links work
- [ ] Verify resume PDF is in `resume/` folder
- [ ] Make sure company logos are in `logos/` folder

### After Deploying:

- [ ] Visit your live site URL
- [ ] Test all navigation links
- [ ] Check download resume button works
- [ ] Verify all images load correctly
- [ ] Test on mobile device
- [ ] Share your portfolio URL!

---

## 🔧 Troubleshooting

### Images Not Loading?
- Make sure image paths are correct (case-sensitive)
- Check file extensions match exactly (.jpg vs .JPG)
- Ensure images are uploaded to repository

### Resume Download Not Working?
- Verify `Ethan_Velasco_Resume.pdf` exists in `resume/` folder
- Check file name matches exactly (case-sensitive)

### Custom Domain Not Working?
- DNS changes can take 24-48 hours
- Double-check DNS records are correct
- Verify domain is connected in hosting settings

---

## 🎯 Recommended Setup (Best Free Option)

**For Beginners:**
1. Use **GitHub Pages** (easiest, most reliable)
2. Use free subdomain: `yourusername.github.io`
3. No credit card, no expiration, 100% free forever

**For Custom Domain:**
1. Use **GitHub Pages** for hosting
2. Get free domain from **Freenom** (.tk domain)
3. Connect them together
4. Total cost: **$0.00** (no credit card needed)

---

## 📞 Need Help?

- GitHub Pages Docs: https://docs.github.com/pages
- Netlify Docs: https://docs.netlify.com
- Vercel Docs: https://vercel.com/docs

---

## ✅ Summary

**Easiest Free Deployment:**
1. Sign up for GitHub (free)
2. Create repository: `yourusername.github.io`
3. Upload your files
4. Enable GitHub Pages
5. Done! Site live at `https://yourusername.github.io`

**Total Cost: $0.00**
**Credit Card Required: NO**
**Time to Deploy: 5-10 minutes**

Good luck with your deployment! 🚀

