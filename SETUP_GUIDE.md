# 🚀 Quick Setup Guide for GitHub Pages

## Step-by-Step Instructions to Deploy Your Portfolio

### 1️⃣ Customize Your Website

Before pushing to GitHub, update your personal information:

**In `index.html`, replace:**
- [x] Your name (already set to "Dibyajyoti Mohanty")
- [x] Job title (already set to "AI/ML Engineer | Generative AI Specialist")
- [x] About me text (already filled with your profile)
- [x] Work experience (all 5 positions added: Movius, ATG, Freelance, Cognizant, Stack System)
- [x] Skills and technologies (all AI/ML skills added)
- [x] Projects (6 major projects added)
- [x] Education (Ravenshaw University added)
- [ ] Email address: Search for `your.email@example.com` and replace with your real email
- [ ] GitHub URL: Replace `https://github.com/yourusername` with your GitHub profile
- [ ] LinkedIn URL: Replace `https://linkedin.com/in/yourprofile` with your LinkedIn profile
- [ ] Update project GitHub links with your actual repository URLs

### 2️⃣ Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `yourusername.github.io` (use your actual GitHub username)
   - Example: If your username is "john-doe", name it `john-doe.github.io`
3. Select **Public**
4. Do NOT initialize with README (we already have one)
5. Click **Create repository**

### 3️⃣ Push Your Code

Open Terminal in this folder and run these commands one by one:

```bash
# Initialize git
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: My portfolio website"

# Link to your GitHub repository (REPLACE with your actual URL)
git remote add origin https://github.com/YOURUSERNAME/YOURUSERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**⚠️ Important:** Replace `YOURUSERNAME` with your actual GitHub username!

### 4️⃣ Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under **Branch**: Select `main` and folder `/ (root)`
5. Click **Save**
6. Wait 2-3 minutes

### 5️⃣ View Your Live Website! 🎉

Your portfolio will be live at:
```
https://YOURUSERNAME.github.io
```

Replace `YOURUSERNAME` with your GitHub username.

---

## 📝 Making Updates Later

Whenever you want to update your website:

```bash
# Make your changes to the files
# Then run:

git add .
git commit -m "Update: describe your changes"
git push
```

Wait 1-2 minutes and your changes will be live!

---

## 🎨 Quick Customization Checklist

- [x] Update name and title in hero section ✅
- [ ] Add your email and social media links (update placeholders)
- [x] Write your "About Me" section ✅
- [x] Add work experience (5 positions added) ✅
- [x] List your skills (comprehensive AI/ML skills added) ✅
- [x] Add your projects with links (6 projects added) ✅
- [x] Include education details ✅
- [x] Resume PDF is already in place ✅
- [x] Matte black & green theme applied ✅
- [ ] Update GitHub/LinkedIn URLs
- [ ] Update project repository links
- [ ] Test all links work correctly
- [ ] Check website on mobile phone

---

## 💡 Pro Tips

### Add a Custom Domain (Optional)
1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In GitHub Settings → Pages → Custom domain, enter your domain
3. Update your domain's DNS settings (instructions in GitHub docs)

### Track Visitors (Optional)
Add Google Analytics to see how many people visit your site:
1. Create a Google Analytics account
2. Add the tracking code to `index.html` before `</head>`

### Improve SEO
- Update the meta description in `index.html`
- Add keywords related to your skills
- Share your portfolio link on LinkedIn and Twitter

---

## ❓ Troubleshooting

**Website not showing up?**
- Wait 5 minutes after enabling GitHub Pages
- Check Settings → Pages to see if it says "Your site is published"
- Make sure repository is Public, not Private

**Changes not appearing?**
- Wait 1-2 minutes after pushing
- Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)
- Clear browser cache

**404 Error?**
- Check the repository name matches your username exactly
- Make sure `index.html` is in the root folder, not in a subfolder

---

## 🆘 Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Git Basics: https://git-scm.com/book/en/v2/Getting-Started-Git-Basics
- Font Awesome Icons: https://fontawesome.com/icons

---

**Good luck with your portfolio! 🚀**
