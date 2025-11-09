# 📱 Facebook/Social Media Preview Image Setup

## ✅ What I Did:

I created an **Open Graph image** (`og-image.jpg`) from your flyer that will show up when you share your website on:
- 📘 Facebook
- 📱 Twitter/X  
- 💼 LinkedIn
- 📲 Text messages (iMessage, WhatsApp)
- 💬 Slack
- And most other platforms!

---

## 🎨 Your Preview Image:

**File**: `og-image.jpg` (included in your site folder)
**Size**: 1200x630px (optimal for all social platforms)
**Based on**: Your LFR Contractors flyer

---

## 🚀 How to Deploy:

### Step 1: Upload the Image

When you deploy your site, make sure `og-image.jpg` is in the **root folder** (same level as `index.html`):

```
lfr-contractors-site-seo/
├── index.html
├── og-image.jpg          ← This file!
├── netlify.toml
├── robots.txt
└── ...
```

### Step 2: Update Your Domain (If Different)

If your Netlify URL is different than `lfr-contractors.netlify.app`, update these lines in `index.html`:

**Find** (around line 19):
```html
<meta property="og:image" content="https://lfr-contractors.netlify.app/og-image.jpg">
```

**Replace** with your actual domain:
```html
<meta property="og:image" content="https://YOUR-ACTUAL-DOMAIN.netlify.app/og-image.jpg">
```

Do the same for line 31 (Twitter image).

### Step 3: Deploy

```bash
git add .
git commit -m "Added Open Graph preview image"
git push
```

---

## 📱 What It Will Look Like:

### On Facebook:
```
┌─────────────────────────────────┐
│  [Your Flyer Image]             │
│                                 │
│  LFR Contractors | Licensed     │
│  MS & LA Home Repair Since 1985 │
│                                 │
│  Licensed, bonded & insured     │
│  contractor serving Mississippi │
│  & Louisiana since 1985...      │
│                                 │
│  lfr-contractors.netlify.app    │
└─────────────────────────────────┘
```

### On Twitter/X:
```
┌─────────────────────────────────┐
│  [Your Flyer Image]             │
│                                 │
│  LFR Contractors | Licensed     │
│  MS & LA Home Repair            │
│                                 │
│  Licensed contractor serving    │
│  MS & LA since 1985...          │
│                                 │
│  lfr-contractors.netlify.app    │
└─────────────────────────────────┘
```

### On Text Message (iMessage):
```
┌─────────────────────────┐
│  [Flyer Thumbnail]      │
│                         │
│  LFR Contractors        │
│  Click to open →        │
└─────────────────────────┘
```

---

## 🧪 How to Test:

### Facebook Debugger (Best Way):
1. Deploy your site with the `og-image.jpg` file
2. Go to: https://developers.facebook.com/tools/debug/
3. Enter your URL: `https://lfr-contractors.netlify.app`
4. Click **"Scrape Again"** to refresh the cache
5. See your preview! 🎉

### Twitter Card Validator:
1. Go to: https://cards-dev.twitter.com/validator
2. Enter your URL
3. See your Twitter preview!

### LinkedIn Post Inspector:
1. Go to: https://www.linkedin.com/post-inspector/
2. Enter your URL
3. See your LinkedIn preview!

### Quick Test (Mobile):
1. Deploy your site
2. Text the link to yourself
3. See the preview in your message! 📱

---

## 🎯 What's Already Set Up:

### In your HTML, I added these tags:

```html
<!-- Open Graph / Facebook -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://lfr-contractors.netlify.app/">
<meta property="og:title" content="LFR Contractors | Licensed MS & LA Home Repair Since 1985">
<meta property="og:description" content="Licensed, bonded & insured contractor...">
<meta property="og:image" content="https://lfr-contractors.netlify.app/og-image.jpg">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:image:type" content="image/jpeg">

<!-- Twitter -->
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:image" content="https://lfr-contractors.netlify.app/og-image.jpg">
```

---

## 🔧 Troubleshooting:

### Problem: "I don't see the image when I share"

**Solutions:**

1. **Make sure og-image.jpg is uploaded**
   - Check: `https://your-site.netlify.app/og-image.jpg`
   - Should show your flyer image

2. **Clear Facebook's cache**
   - Go to: https://developers.facebook.com/tools/debug/
   - Enter your URL
   - Click "Scrape Again"

3. **Wait a few minutes**
   - Sometimes it takes 5-10 minutes for the image to show

4. **Check the file size**
   - Facebook requires images under 8MB (yours is ~300KB ✓)

5. **Verify HTTPS**
   - Make sure your site uses `https://` not `http://`

---

## 💡 Want a Custom Image Instead?

If you want to create a different preview image:

### Option 1: Use Canva (Easy)
1. Go to: https://canva.com
2. Create new design: **1200 x 630 px**
3. Design your preview image
4. Download as JPG
5. Replace `og-image.jpg` with your new image

### Option 2: Hire a Designer
Get a professional social media graphic:
- Fiverr: $5-50
- Upwork: $20-100
- 99designs: $100-300

### What Makes a Good OG Image:
- ✅ Your logo prominently displayed
- ✅ Phone number visible
- ✅ "Licensed" or key trust signals
- ✅ High contrast colors
- ✅ Large text (readable on mobile)
- ✅ 1200x630px size
- ✅ Under 8MB file size

---

## 📊 Current Setup:

**Your og-image.jpg includes:**
- ✅ LFR Contractors logo
- ✅ "Building With Integrity Since 1985"
- ✅ License numbers: MS #19004, LA #555 826
- ✅ Phone: (228) 344-4300
- ✅ All services listed
- ✅ "Licensed, Bonded & Insured"
- ✅ Professional design from your flyer

**Perfect for social sharing!** 🎉

---

## ✅ Checklist:

- [x] Created og-image.jpg from your flyer
- [x] Added to website folder
- [x] Updated HTML meta tags
- [x] Set correct image dimensions
- [ ] You: Deploy with og-image.jpg file
- [ ] You: Test on Facebook Debugger
- [ ] You: Share and see your beautiful preview!

---

## 🎯 Before vs After:

### BEFORE (Without OG Image):
```
When shared on Facebook:
- Just a plain link
- No image
- Generic text
- Boring 😴
```

### AFTER (With OG Image):
```
When shared on Facebook:
- Your beautiful flyer image 🎨
- Professional title
- Compelling description
- Phone number visible
- Eye-catching! 🔥
```

---

**Your site will now look amazing when shared anywhere! 🚀**

Test it and watch those clicks roll in! 📱📞