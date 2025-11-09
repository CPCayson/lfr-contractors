# 🔗 URL Update Checklist

## ⚠️ IMPORTANT: After Deploying to Netlify

You need to update URLs in `index.html` with your ACTUAL Netlify URL.

---

## 🎯 Your Netlify URL Will Look Like:

`https://your-site-name.netlify.app`

For example:
- `https://lfr-contractors.netlify.app`
- `https://lfr-contractors-ms.netlify.app`
- `https://lfr-ms-la.netlify.app`

---

## ✏️ Easy Method: Find & Replace

1. Open `index.html` in any text editor
2. Press `Ctrl+H` (Windows) or `Cmd+H` (Mac)
3. **Find**: `https://lfr-contractors.netlify.app`
4. **Replace with**: `https://YOUR-ACTUAL-URL.netlify.app`
5. Click "Replace All"
6. Save
7. Redeploy

**Done! All URLs updated at once!** 🎉

---

## 📝 Manual Method (If You Prefer):

Update these lines in `index.html`:

### Line 16 - Open Graph URL:
```html
<meta property="og:url" content="https://YOUR-SITE.netlify.app/">
```

### Line 19 - Open Graph Image:
```html
<meta property="og:image" content="https://YOUR-SITE.netlify.app/og-image.jpg">
```

### Line 25 - Twitter URL:
```html
<meta property="twitter:url" content="https://YOUR-SITE.netlify.app/">
```

### Line 28 - Twitter Image:
```html
<meta property="twitter:image" content="https://YOUR-SITE.netlify.app/og-image.jpg">
```

### Line 37 - Canonical URL:
```html
<link rel="canonical" href="https://YOUR-SITE.netlify.app/">
```

### Line 48 - Schema @id:
```html
"@id": "https://YOUR-SITE.netlify.app",
```

### Line 49 - Schema url:
```html
"url": "https://YOUR-SITE.netlify.app",
```

### Line 50 - Schema image:
```html
"image": "https://YOUR-SITE.netlify.app/og-image.jpg",
```

---

## 🚀 Deployment Flow:

1. Deploy to Netlify (first time)
2. Note your Netlify URL (example: `https://lfr-ms.netlify.app`)
3. Update URLs in `index.html` (use Find & Replace)
4. Update Google Analytics ID: `G-NLKF8E5L1F`
5. Redeploy with updates
6. Test with Facebook Debugger

---

## ✅ Quick Test:

After deploying with correct URLs:

1. Visit: `https://your-site.netlify.app/og-image.jpg`
   - Should show your LFR image ✅

2. Go to: https://developers.facebook.com/tools/debug/
   - Paste your URL
   - Click "Scrape Again"
   - Should show your preview image ✅

---

## 💡 What Each URL Does:

- **og:url** → Tells Facebook what URL to link to
- **og:image** → The preview image Facebook shows
- **twitter:url** → URL for Twitter cards
- **twitter:image** → Twitter preview image
- **canonical** → Tells Google this is the main URL
- **Schema @id** → Unique identifier for search engines
- **Schema url** → Business website in structured data
- **Schema image** → Business logo/image for search

---

## 🎯 Current Placeholder URLs:

All instances of:
```
https://lfr-contractors.netlify.app
```

Need to be replaced with YOUR actual Netlify URL!

---

**Total replacements needed: 8 URLs**

Use Find & Replace = 30 seconds ⚡

Manual = 5 minutes 🐢

**Your choice!** 😊