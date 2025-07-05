# GitHub Pages Deployment Guide

This guide will help you deploy your personal website to GitHub Pages in just a few steps.

## 🚀 Quick Deployment Steps

### 1. Push Your Code to GitHub

If you haven't already, push your website files to a GitHub repository:

```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial website setup"

# Add your GitHub repository as remote
git remote add origin https://github.com/[your-username]/[your-repo-name].git

# Push to GitHub
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to your GitHub repository
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch (or **master** if that's your default)
6. Select **/(root)** folder
7. Click **Save**

### 3. Wait for Deployment

- GitHub will automatically build and deploy your site
- This usually takes 1-2 minutes
- You'll see a green checkmark when deployment is complete

### 4. Access Your Website

Your website will be available at:
```
https://[your-username].github.io/[your-repo-name]
```

For example, if your username is `shayan223` and repo name is `shayan223.github.io`, your site will be at:
```
https://shayan223.github.io
```

## 🔧 Custom Domain (Optional)

If you want to use a custom domain:

1. In your repository Settings > Pages
2. Under **Custom domain**, enter your domain name
3. Click **Save**
4. Add a `CNAME` file to your repository root with your domain name
5. Update your DNS settings with your domain provider

## 📝 Important Notes

- **File Structure**: Make sure `index.html` is in the root directory
- **Case Sensitivity**: GitHub Pages is case-sensitive, so ensure all file names match exactly
- **Updates**: Any changes you push to the main branch will automatically trigger a new deployment
- **HTTPS**: GitHub Pages automatically provides SSL certificates

## 🐛 Troubleshooting

### Site Not Loading
- Check that `index.html` is in the root directory
- Verify the repository is public (or you have GitHub Pro for private repos)
- Wait a few minutes for initial deployment

### Images Not Showing
- Ensure image file names match exactly (case-sensitive)
- Check that image files are included in your repository

### Styling Issues
- Verify all CSS and JavaScript files are properly linked
- Check browser console for any errors

## 📱 Testing

After deployment:
1. Test on desktop and mobile devices
2. Check all navigation links work
3. Test the contact form
4. Verify all images load properly

## 🔄 Updating Your Site

To update your website:
1. Make changes to your local files
2. Commit and push to GitHub:
```bash
git add .
git commit -m "Update website content"
git push
```
3. GitHub Pages will automatically redeploy

---

**Your website should now be live! 🎉** 