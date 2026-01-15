# GitHub Pages Setup Guide

This directory contains the GitHub Pages website for HandyColorConverter (色彩助手).

## 📁 Files

- `index.html` - Marketing/Landing page
- `support.html` - Support page with FAQ
- `privacy.html` - Privacy policy page

## 🚀 Enabling GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Select branch: **main** (or your default branch)
5. Select folder: **/docs**
6. Click **Save**

Your site will be available at: `https://piscesweilun.github.io/HandyColorConverter/`

## 📝 Customization

### Update App Store Link

In `index.html`, replace the placeholder link:
```html
<a href="#" class="cta-button">📱 前往 App Store 下載</a>
```
With your actual App Store URL:
```html
<a href="https://apps.apple.com/app/idYOUR_APP_ID" class="cta-button">📱 前往 App Store 下載</a>
```

### Update Contact Email

In both `support.html` and `privacy.html`, replace:
```html
support@example.com
```
With your actual support email address.

### Add Screenshots

Replace the screenshot placeholders in `index.html` with actual screenshots:
```html
<div class="screenshot-placeholder">
    <!-- Replace with: -->
    <img src="images/screenshot1.png" alt="主介面" style="width: 100%; border-radius: 20px;">
</div>
```

Create an `images` folder inside `docs` and add your screenshots there.

## 🎨 Features

- ✅ Fully responsive design
- ✅ Mobile-friendly
- ✅ Modern gradient styling
- ✅ Consistent navigation
- ✅ SEO optimized
- ✅ Bilingual content (Chinese & English for Privacy)

## 📱 Testing Locally

Open any `.html` file in your web browser to preview the pages locally before publishing.

## 🔗 Important Links

After enabling GitHub Pages, update these in your App Store listing:
- **Support URL**: `https://piscesweilun.github.io/HandyColorConverter/support.html`
- **Privacy Policy URL**: `https://piscesweilun.github.io/HandyColorConverter/privacy.html`
- **Marketing URL**: `https://piscesweilun.github.io/HandyColorConverter/`
