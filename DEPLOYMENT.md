# 🚀 GitHub Pages Deployment Guide

## Quick Deployment Steps

### 1. Upload to GitHub
1. Create a new repository on GitHub (name it something like `portfolio` or `abrar-portfolio`)
2. Upload all files from this folder to the repository
3. Make sure all files are in the root directory of the repository

### 2. Enable GitHub Pages
1. Go to your repository **Settings** tab
2. Scroll down to **Pages** section in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** (or **master**) branch
5. Select **/ (root)** folder
6. Click **Save**

### 3. Access Your Website
- Your website will be available at: `https://your-username.github.io/repository-name`
- It may take 5-10 minutes for changes to appear
- GitHub will show you the URL in the Pages settings

### 4. Add Required Images
Before the website is fully functional, add these images to `assets/images/`:
- `profile.jpg` - Professional headshot (350x350px)
- `about.jpg` - Additional photo (350x400px)
- `favicon.ico` - Browser icon (optional)

### 5. Update URLs (Optional)
If you want to update the Open Graph URLs for social media sharing:
1. Open `index.html`
2. Find the `<meta property="og:url"` line
3. Replace with your actual GitHub Pages URL

## ✅ Verification Checklist

- [ ] All files uploaded to GitHub repository
- [ ] GitHub Pages enabled in repository settings
- [ ] Images added to `assets/images/` folder
- [ ] Website loads correctly at GitHub Pages URL
- [ ] All sections work properly
- [ ] Contact links (WhatsApp, LinkedIn, etc.) function correctly
- [ ] CV download works
- [ ] Responsive design works on mobile devices

## 🔧 Troubleshooting

**Website not loading?**
- Check that files are in the root directory (not in a subfolder)
- Verify GitHub Pages is enabled in repository settings
- Wait 5-10 minutes for GitHub to build the site

**Images not showing?**
- Ensure image files are exactly named as specified
- Check file extensions (.jpg, .png, .ico)
- Verify images are in the `assets/images/` folder

**Links not working?**
- All internal links use relative paths and should work automatically
- External links (social media) should work immediately

## 📱 Mobile Testing

Test your website on different devices:
- Desktop computer
- Tablet
- Mobile phone
- Different browsers (Chrome, Firefox, Safari, Edge)

## 🎯 Performance Tips

- Images should be optimized (compressed) for web
- Total page size should be under 3MB for fast loading
- Test internet speed on mobile networks

---

**Need help?** Check the GitHub Pages documentation: https://docs.github.com/en/pages 