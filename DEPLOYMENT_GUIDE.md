# Website Deployment Guide - Kavat Art Studio

This guide will help you host your website for **FREE** using various platforms.

## Option 1: GitHub Pages (Recommended) ⭐

GitHub Pages is completely free and perfect for static websites like yours.

### Step-by-Step Instructions:

#### 1. Create a GitHub Account
- Go to [github.com](https://github.com)
- Click "Sign up" and create a free account
- Verify your email address

#### 2. Create a New Repository
- Click the "+" icon in the top right corner
- Select "New repository"
- Repository name: `kavat-art-studio` (or any name you prefer)
- Description: "Kavat Art Studio - Professional Art Teaching Website"
- Make it **Public** (required for free GitHub Pages)
- ✅ Check "Add a README file"
- Click "Create repository"

#### 3. Upload Your Website Files

**Method A: Using GitHub Web Interface (Easiest)**
1. In your repository, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Add a commit message: "Initial website upload"
4. Click "Commit changes"

**Method B: Using Git Command Line**
```bash
# Navigate to your project folder
cd /Users/nvenugopal/Documents/kavat

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Kavat Art Studio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/kavat-art-studio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### 4. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

#### 5. Access Your Website
Your website will be live at:
```
https://YOUR-USERNAME.github.io/kavat-art-studio/
```

Example: If your GitHub username is "keerthitajaswini", your URL will be:
```
https://keerthitajaswini.github.io/kavat-art-studio/
```

### Custom Domain (Optional)
You can use a custom domain like `kavatartstudio.com`:
1. Buy a domain from Namecheap, GoDaddy, or Google Domains ($10-15/year)
2. In GitHub repository Settings → Pages → Custom domain
3. Enter your domain name
4. Update DNS settings at your domain registrar

---

## Option 2: Netlify (Very Easy) 🚀

Netlify offers free hosting with automatic deployments.

### Steps:
1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub account
3. Click "Add new site" → "Import an existing project"
4. Connect to GitHub and select your repository
5. Click "Deploy site"
6. Your site will be live at: `random-name.netlify.app`
7. You can change the subdomain in Site settings

**Advantages:**
- Automatic deployments when you update GitHub
- Free SSL certificate
- Custom domain support
- Form handling (your contact form will work!)

---

## Option 3: Vercel (Fast & Modern) ⚡

Similar to Netlify, great for static sites.

### Steps:
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"
6. Live at: `kavat-art-studio.vercel.app`

---

## Option 4: Cloudflare Pages 🌐

### Steps:
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Sign up for free
3. Connect GitHub account
4. Select your repository
5. Deploy
6. Live at: `kavat-art-studio.pages.dev`

---

## Option 5: Render (Simple) 🎯

### Steps:
1. Go to [render.com](https://render.com)
2. Sign up with GitHub
3. New → Static Site
4. Connect repository
5. Deploy
6. Live at: `kavat-art-studio.onrender.com`

---

## Quick Comparison

| Platform | Speed | Custom Domain | SSL | Best For |
|----------|-------|---------------|-----|----------|
| **GitHub Pages** | Fast | Yes (free) | Yes | Simple hosting |
| **Netlify** | Very Fast | Yes (free) | Yes | Forms & features |
| **Vercel** | Very Fast | Yes (free) | Yes | Modern sites |
| **Cloudflare** | Fastest | Yes (free) | Yes | Global CDN |
| **Render** | Fast | Yes (paid) | Yes | Easy setup |

---

## Recommended Workflow

### For Beginners:
1. **Start with GitHub Pages** - It's free and simple
2. Your URL: `username.github.io/kavat-art-studio`

### For Better Features:
1. **Use Netlify** - Better for contact forms
2. Automatic deployments
3. Better analytics

---

## Making Your Contact Form Work

Your current form is client-side only. To make it actually send emails:

### Option A: Use Netlify Forms (Free)
1. Deploy to Netlify
2. Add `netlify` attribute to your form:
```html
<form class="contact-form" name="contact" method="POST" data-netlify="true">
```
3. Netlify will handle form submissions

### Option B: Use Formspree (Free tier available)
1. Sign up at [formspree.io](https://formspree.io)
2. Get your form endpoint
3. Update form action:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR-ID" method="POST">
```

### Option C: Use EmailJS (Free)
1. Sign up at [emailjs.com](https://emailjs.com)
2. Add EmailJS to your JavaScript
3. Configure email template

---

## Step-by-Step: Deploy to GitHub Pages NOW

### Quick Commands (Copy & Paste):

```bash
# 1. Navigate to your project
cd /Users/nvenugopal/Documents/kavat

# 2. Initialize git
git init

# 3. Add all files
git add .

# 4. Commit
git commit -m "Initial commit - Kavat Art Studio"

# 5. Create repository on GitHub first, then:
git remote add origin https://github.com/YOUR-USERNAME/kavat-art-studio.git

# 6. Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings!

---

## Updating Your Website

After initial deployment, to update your website:

```bash
# Make changes to your files
# Then:
git add .
git commit -m "Updated contact information"
git push
```

Your website will automatically update!

---

## Free SSL Certificate

All these platforms provide **free HTTPS/SSL** certificates automatically, so your website will be secure with the padlock icon 🔒

---

## Cost Summary

- **Hosting:** $0 (FREE)
- **SSL Certificate:** $0 (FREE)
- **Custom Domain:** $10-15/year (optional)
- **Total:** **FREE** (or $10-15/year with custom domain)

---

## Need Help?

If you need help with deployment, I can:
1. Help you set up Git
2. Create the GitHub repository
3. Push your code
4. Enable GitHub Pages

Just let me know! 🚀

---

## Your Website URLs (After Deployment)

Once deployed, share your website:
- GitHub Pages: `https://YOUR-USERNAME.github.io/kavat-art-studio/`
- Netlify: `https://kavat-art-studio.netlify.app`
- Vercel: `https://kavat-art-studio.vercel.app`
- Custom Domain: `https://kavatartstudio.com` (if you buy one)

---

**Recommended:** Start with GitHub Pages, it's the easiest and completely free! 🎉