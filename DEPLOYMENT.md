# 🚀 Deployment Guide for Saniya's Portfolio

## Method 1: GitHub Pages (Recommended - FREE)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Sign up for a free account

### Step 2: Create New Repository
1. Click "+" in top right → "New repository"
2. Repository name: `saniya-portfolio` (or any name)
3. Make it **Public**
4. Click "Create repository"

### Step 3: Push Your Code
Run these commands in PowerShell (in your portfolio folder):

```powershell
git remote add origin https://github.com/YOUR-USERNAME/saniya-portfolio.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Click "Pages" in left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be live at: `https://YOUR-USERNAME.github.io/saniya-portfolio`

⏱️ Wait 2-3 minutes for deployment to complete!

---

## Method 2: Netlify (Alternative - FREE)

### Quick Deploy:
1. Go to [netlify.com](https://www.netlify.com)
2. Sign up with GitHub
3. Click "Add new site" → "Import an existing project"
4. Connect GitHub → Select your repository
5. Click "Deploy site"
6. Your site is live! (Custom domain available)

---

## Method 3: Vercel (Alternative - FREE)

### Quick Deploy:
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Click "New Project"
4. Import your repository
5. Click "Deploy"
6. Live in seconds!

---

## 🎯 After Deployment

### Update Links:
1. Replace `YOUR-USERNAME` in README.md with your GitHub username
2. Update the live demo link
3. Add your actual email in contact section
4. Upload your real resume PDF

### Share Your Portfolio:
- LinkedIn: Add to "Featured" section
- Resume: Include portfolio link
- Email signature: Add portfolio URL
- Twitter/Social media: Share your work!

---

## 🔧 Updating Your Portfolio

After making changes:

```powershell
git add .
git commit -m "Update portfolio"
git push
```

Changes will automatically deploy in 1-2 minutes!

---

## 📝 Custom Domain (Optional)

### With GitHub Pages:
1. Buy domain (Namecheap, GoDaddy, etc.)
2. In GitHub repo → Settings → Pages
3. Add your custom domain
4. Update DNS records at domain provider

### With Netlify/Vercel:
1. Go to site settings
2. Add custom domain
3. Follow DNS instructions

---

## ✅ Checklist Before Going Live

- [ ] Add your professional photo to `images/saniya-photo.jpg`
- [ ] Replace sample resume with your actual resume
- [ ] Update email address in contact form
- [ ] Update LinkedIn URL
- [ ] Add GitHub username
- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Update project descriptions with real projects

---

## 🆘 Need Help?

Common issues:
- **404 Error**: Wait 2-3 minutes after enabling GitHub Pages
- **Styles not loading**: Clear browser cache (Ctrl+Shift+R)
- **Photo not showing**: Make sure file is named `saniya-photo.jpg` in `images` folder

---

## 🎉 Your Portfolio is Ready!

Share it with:
- Recruiters
- Professional networks
- College placement cell
- Social media
- Email signature

**Good luck with your job search!** 🚀
