# 🚀 Quick Deployment Guide

## Deploy to Vercel (Recommended)

### Step 1: Install Vercel CLI
```bash
npm i -g vercel
```

### Step 2: Deploy
```bash
cd portfolio
vercel
```

### Step 3: Add Custom Domain
1. Go to [vercel.com](https://vercel.com)
2. Select your project
3. Settings → Domains
4. Add your domain (e.g., usamarasool.com)
5. Follow DNS instructions

---

## Deploy to Netlify

### Option A: Drag & Drop
1. Go to [netlify.com](https://netlify.com)
2. Drag the `portfolio` folder to deploy

### Option B: Netlify CLI
```bash
npm i -g netlify-cli
netlify deploy --prod --dir=portfolio
```

---

## Deploy to GitHub Pages

### Step 1: Create Repository
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

### Step 2: Enable Pages
1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Select `main` branch
4. Your site will be live at `https://YOUR_USERNAME.github.io/portfolio`

---

## 🔐 Admin Dashboard Access

- URL: `https://yourdomain.com/admin/`
- Password: `admin123` (change in admin/index.html)

---

## 📧 Contact Form Setup

1. Create free account at [formspree.io](https://formspree.io)
2. Create new form
3. Copy your form endpoint (e.g., `https://formspree.io/f/xxxxxxxx`)
4. Replace `YOUR_FORM_ID` in index.html with your form ID

---

## 🎨 Customization

### Change Colors
Edit CSS variables in index.html:
```css
:root {
    --accent: #10b981;        /* Main green color */
    --accent-light: #34d399;  /* Light green */
    --bg: #000000;            /* Background */
}
```

### Change Password
Edit in `admin/index.html`:
```javascript
const ADMIN_PASSWORD = 'your-new-password';
```

---

## 📱 SEO Checklist

- [ ] Add Google Analytics tracking code
- [ ] Submit sitemap to Google Search Console
- [ ] Add meta description for each page
- [ ] Create `robots.txt` file
- [ ] Add Open Graph images for social sharing

---

Built with ❤️ for agriculture professionals
