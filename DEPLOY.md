# Deployment Guide

## Deploy to GitHub Pages

1. **Create a GitHub repository:**
   ```bash
   # On GitHub, create a new repository named "cv-generator"
   ```

2. **Add remote and push:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/cv-generator.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Select source: "Deploy from a branch"
   - Select branch: "main" and folder: "/ (root)"
   - Your CV generator will be live at: `https://YOUR_USERNAME.github.io/cv-generator/cv-generator.html`

## Deploy to Vercel

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy:**
   ```bash
   cd cv-generator
   vercel
   ```

3. **Follow the prompts** - Your site will be live instantly!

## Deploy to Netlify

1. **Drag and drop** the `cv-generator` folder to [Netlify Drop](https://app.netlify.com/drop)

2. **Or use Netlify CLI:**
   ```bash
   npm install -g netlify-cli
   netlify deploy --prod
   ```

## Deploy to Any Static Host

Since this is pure HTML/CSS/JS, you can deploy to:
- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages
- AWS S3 + CloudFront
- Any static hosting service

Just upload the files and point to `cv-generator.html` as the entry point.

