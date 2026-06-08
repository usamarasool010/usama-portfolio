# Muhammad Usama Rasool - Premium Portfolio

## 🚀 World-Class Interactive Portfolio

Apple-level design with Three.js 3D animations, WhatsApp chat, admin dashboard, and CV download system.

## 📁 File Structure

```
portfolio/
├── index.html          # Main portfolio website
├── admin/
│   └── index.html      # Admin dashboard (messages)
└── assets/
    └── cv.pdf          # Downloadable CV
```

## 🌐 Deployment Guide

### Option 1: Vercel (Recommended)
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow prompts to deploy

### Option 2: Netlify
1. Drag & drop the `portfolio` folder to [netlify.com](https://netlify.com)
2. Or use Netlify CLI: `npm i -g netlify-cli && netlify deploy`

### Option 3: GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select source: Deploy from a branch (main)

## 🔧 Custom Domain Setup

### Vercel
1. Buy domain from Namecheap/GoDaddy
2. In Vercel dashboard: Project > Settings > Domains
3. Add your domain and follow DNS instructions
4. SSL/HTTPS is automatic

### Netlify
1. Go to Site settings > Domain management
2. Add custom domain
3. Configure DNS records as instructed
4. SSL certificate auto-provisioned

## 📋 Features

- ✅ Apple-level dark UI/UX design
- ✅ Three.js 3D animated hero background
- ✅ WhatsApp floating chat widget
- ✅ CV download system (PDF + Print)
- ✅ Contact form with validation
- ✅ Admin dashboard with login
- ✅ Message management system
- ✅ Scroll animations & reveal effects
- ✅ Mobile responsive design
- ✅ SEO optimized structure

## 🔐 Admin Dashboard

- URL: `/admin/index.html`
- Default password: `admin123`
- Features: View messages, export CSV, delete/archive

## ⚡ Performance

- Lazy loading images
- Optimized Three.js with intersection observer
- CSS animations with GPU acceleration
- Minimal external dependencies

## 📧 Contact Form Setup

1. Create free account at [formspree.io](https://formspree.io)
2. Create new form and get endpoint URL
3. Replace `YOUR_FORM_ID` in index.html with your form ID

---

Built with passion for agriculture 🌱
