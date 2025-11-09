# 📱 Facebook/Social Media Preview Image Setup

## What I Created For You:

I've created an **Open Graph image** (`og-image.jpg`) that will appear when your website is shared on:
- 📘 Facebook
- 💼 LinkedIn
- 🐦 Twitter/X
- 💬 WhatsApp
- 📧 Email previews
- 👾 Discord/Slack

---

## 📸 The Image:

[View your Open Graph image](og-image.jpg)

**Specifications:**
- Size: 1200x630 pixels (Facebook optimal)
- Format: JPEG
- Contains: LFR logo, services, phone number
- Matches your brand colors

---

## 🚀 Setup (3 Steps):

### Step 1: Upload Image to Your Site ✅

The file `og-image.jpg` is already in your folder. When you deploy to Netlify, it will automatically be uploaded!

### Step 2: Update the URL (IMPORTANT!)

After deploying to Netlify, you need to update the image URL in `index.html`:

**Find this line (around line 19):**
```html
<meta property="og:image" content="https://lfr-contractors.netlify.app/og-image.jpg">
```

**Replace with YOUR actual Netlify URL:**
```html
<meta property="og:image" content="https://YOUR-ACTUAL-SITE-NAME.netlify.app/og-image.jpg">
```

For example, if your site is `https://lfr-contractors-ms.netlify.app`, change it to:
```html
<meta property="og:image" content="https://lfr-contractors-ms.netlify.app/og-image.jpg">
```

**Also update these other URLs (around lines 16, 25, 37, 49):**
- `og:url`
- `twitter:url`
- Canonical URL
- Schema.org `@id` and `url`

### Step 3: Test It! 🧪

After deploying:

1. **Facebook Debugger**: https://developers.facebook.com/tools/debug/
   - Paste your website URL
   - Click "Scrape Again"
   - You should see your image!

2. **Twitter Card Validator**: https://cards-dev.twitter.com/validator
   - Paste your URL
   - Preview how it looks

3. **LinkedIn**: Just try sharing your link
   - Preview should appear automatically

---

## 🎨 What Your Preview Will Look Like:

### Facebook/LinkedIn:
```
┌─────────────────────────────────────────┐
│ [Your og-image.jpg with LFR branding]   │
│                                         │
│ LFR Contractors | Licensed MS & LA...   │
│ Licensed, bonded & insured contractor   │
│ serving Mississippi & Louisiana...      │
│                                         │
│ 🔗 lfr-contractors.netlify.app          │
└─────────────────────────────────────────┘
```

### Twitter:
```
┌─────────────────────────────────────────┐
│ [Your og-image.jpg with LFR branding]   │
│                                         │
│ LFR Contractors | Licensed MS & LA...   │
│ Licensed contractor serving MS & LA...  │
│ 🔗 lfr-contractors.netlify.app          │
└─────────────────────────────────────────┘
```

---

## 🔧 Complete URL Update Checklist:

After you deploy and know your actual URL, update these in `index.html`:

**Line 16:**
```html
<meta property="og:url" content="https://YOUR-SITE.netlify.app/">
```

**Line 19:**
```html
<meta property="og:image" content="https://YOUR-SITE.netlify.app/og-image.jpg">
```

**Line 25:**
```html
<meta property="twitter:url" content="https://YOUR-SITE.netlify.app/">
```

**Line 28:**
```html
<meta property="twitter:image" content="https://YOUR-SITE.netlify.app/og-image.jpg">
```

**Line 37:**
```html
<link rel="canonical" href="https://YOUR-SITE.netlify.app/">
```

**Line 48-49 (in Schema):**
```html
"@id": "https://YOUR-SITE.netlify.app",
"url": "https://YOUR-SITE.netlify.app",
"image": "https://YOUR-SITE.netlify.app/og-image.jpg",
```

---

## 💡 Pro Tip: Use Find & Replace

1. Open `index.html`
2. Press `Ctrl+H` (or `Cmd+H` on Mac)
3. Find: `https://lfr-contractors.netlify.app`
4. Replace with: `https://YOUR-ACTUAL-SITE.netlify.app`
5. Replace All!

---

## 🧪 Testing Checklist:

After deploying with correct URLs:

- [ ] Deploy site to Netlify
- [ ] Note your actual Netlify URL
- [ ] Update all URLs in index.html
- [ ] Redeploy
- [ ] Test with Facebook Debugger
- [ ] Test with Twitter Card Validator
- [ ] Try sharing on Facebook
- [ ] Check preview looks good

---

## 🆘 Troubleshooting:

**Problem**: "Image not showing in Facebook preview"

**Solutions:**
1. Make sure image is uploaded (check https://your-site.netlify.app/og-image.jpg loads)
2. Use Facebook Debugger and click "Scrape Again"
3. Wait 5-10 minutes for Facebook cache to update
4. Check URLs are correct (no typos)
5. Make sure file is named exactly `og-image.jpg` (case-sensitive)

**Problem**: "Old preview showing even after update"

**Solution:**
- Facebook caches for 7 days
- Use Facebook Debugger → "Scrape Again" button
- This forces Facebook to refresh

**Problem**: "Image looks wrong on mobile"

**Solution:**
- Image is optimized for 1200x630 (works on all devices)
- Test on actual mobile device, not just preview

---

## 📊 Image Specifications:

| Platform | Optimal Size | Your Image |
|----------|--------------|------------|
| Facebook | 1200x630 | ✅ 1200x630 |
| Twitter | 1200x628 | ✅ 1200x630 |
| LinkedIn | 1200x627 | ✅ 1200x630 |
| WhatsApp | 300x300+ | ✅ 1200x630 |

Your image works perfectly for all platforms! 🎉

---

## 🎨 Want to Change the Image?

If you want to customize the Open Graph image:

1. Create a new image (1200x630 pixels)
2. Name it `og-image.jpg`
3. Replace the existing file
4. Redeploy to Netlify
5. Use Facebook Debugger → "Scrape Again"

**Tip**: Use Canva.com (free) to create custom designs!

---

## ✅ Summary:

1. ✅ Image created: `og-image.jpg`
2. ✅ HTML updated with meta tags
3. ⚠️ **You need to**: Update URLs after deploying
4. ⚠️ **You need to**: Test with Facebook Debugger

**Once deployed with correct URLs, your shares will look professional!** 🎉

---

## 📱 Example of Final Result:

When someone shares your link on Facebook, they'll see:

**Image**: Your branded LFR Contractors graphic
**Title**: "LFR Contractors | Licensed MS & LA Home Repair Since 1985"
**Description**: "Licensed, bonded & insured contractor serving Mississippi & Louisiana since 1985..."
**Link**: Your website URL

Much better than just a plain link! 🚀