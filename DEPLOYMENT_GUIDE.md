# LFR Contractors - Netlify Deployment Guide

## Quick Start

This guide will walk you through deploying your LFR Contractors website to Netlify via GitHub.

## Step 1: Push to GitHub

1. Create a new repository on GitHub:
   - Go to https://github.com/new
   - Name it something like `lfr-contractors-website`
   - Choose Public or Private
   - Do NOT initialize with README (we already have one)
   - Click "Create repository"

2. In your terminal/command prompt, navigate to this folder and run:

```bash
git init
git add .
git commit -m "Initial commit - LFR Contractors website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/lfr-contractors-website.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 2: Deploy to Netlify

### Option A: Connect GitHub Repository (Recommended)

1. Go to https://app.netlify.com (sign up/login with GitHub)
2. Click "Add new site" → "Import an existing project"
3. Choose "Deploy with GitHub"
4. Authorize Netlify to access your GitHub account
5. Select your `lfr-contractors-website` repository
6. Netlify will auto-detect settings from `netlify.toml`
7. Click "Deploy site"

Your site will be live in 1-2 minutes!

### Option B: Drag and Drop (Quick Test)

1. Go to https://app.netlify.com
2. Simply drag this entire folder onto the deployment area
3. Your site goes live immediately!

## Step 3: Configure Your Site

After deployment:

1. **Change Site Name:**
   - Go to Site settings → General → Site details
   - Click "Change site name"
   - Choose something like `lfr-contractors`
   - Your URL will be: `https://lfr-contractors.netlify.app`

2. **Add Custom Domain (Optional):**
   - Go to Site settings → Domain management
   - Click "Add custom domain"
   - Follow instructions to point your domain to Netlify

## Files Included

- `index.html` - Main website file
- `netlify.toml` - Netlify configuration
- `_headers` - Security and caching headers
- `robots.txt` - SEO configuration
- `.gitignore` - Git ignore rules
- `README.md` - Project documentation
- `DEPLOYMENT_GUIDE.md` - This file

## Updating Your Site

After making changes:

```bash
git add .
git commit -m "Description of your changes"
git push
```

Netlify will automatically rebuild and deploy your changes!

## Support

- Netlify Docs: https://docs.netlify.com
- Netlify Support: https://answers.netlify.com

## Site Information

- **Phone:** (228) 344-4300
- **Licenses:** MS #19004, LA #555 826
- **Status:** Licensed, Bonded & Insured
