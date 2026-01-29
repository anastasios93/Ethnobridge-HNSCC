# 🚀 GitHub Pages Deployment Guide

## Step-by-Step Instructions

### Step 1: Create GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Enter email, password, username
4. Verify your email

### Step 2: Create New Repository

1. Click the green "**New**" button (or + icon → New repository)

2. Fill in details:
   - **Repository name:** `ethnobridge-hnc`
   - **Description:** "EthnoBridge - Head & Neck Cancer Care Platform"
   - **Visibility:** ✅ **Public** (required for free GitHub Pages)
   - **Initialize:** ✅ Check "Add a README file"

3. Click "**Create repository**"

### Step 3: Upload Files

#### Method A: Upload via Web Interface (Easiest)

1. In your repository, click "**Add file**" → "**Upload files**"

2. Drag and drop these files:
   - `index.html`
   - `README.md`

3. Scroll down and click "**Commit changes**"

#### Method B: Upload via Command Line

```bash
# Navigate to the folder with the files
cd /path/to/ethnobridge-hnc-github

# Initialize git
git init

# Add files
git add .

# Commit
git commit -m "Initial commit: EthnoBridge HNC platform"

# Add remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/ethnobridge-hnc.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. In your repository, click "**Settings**" (top menu bar)

2. In the left sidebar, scroll to "**Pages**" (under "Code and automation")

3. Under "**Build and deployment**":
   - **Source:** Deploy from a branch
   - **Branch:** Select `main` (or `master`)
   - **Folder:** Select `/ (root)`

4. Click "**Save**"

### Step 5: Wait for Deployment

1. **Wait 1-3 minutes** for GitHub to build your site

2. Refresh the Settings → Pages page

3. You'll see a green box with:
   ```
   ✅ Your site is live at https://username.github.io/ethnobridge-hnc/
   ```

4. Click the "Visit site" button to test!

---

## 🎉 Your Link

Your live link will be:
```
https://YOUR-USERNAME.github.io/ethnobridge-hnc/
```

**Example:** If your username is `dr-sarah-smith`, your link is:
```
https://dr-sarah-smith.github.io/ethnobridge-hnc/
```

---

## ✅ Verification Checklist

Before sharing your link, verify:

- [ ] Repository is **Public**
- [ ] File is named `index.html` (not `ethnobridge-hnc.html`)
- [ ] GitHub Pages is **enabled** in Settings
- [ ] Branch is set to `main` or `master`
- [ ] Waited 2-5 minutes for deployment
- [ ] Visited the link - site loads correctly
- [ ] Tested on mobile device

---

## 🔧 Troubleshooting

### Problem: 404 - Page Not Found

**Solutions:**
- Verify file is named `index.html` exactly
- Check GitHub Pages is enabled
- Wait 5 more minutes (sometimes takes longer)
- Check branch name is correct (main vs master)

### Problem: Repository is Private

**Solution:**
- Go to Settings → General
- Scroll to bottom "Danger Zone"
- Click "Change visibility" → Make Public
- GitHub Pages free tier only works with public repos

### Problem: Changes Not Showing

**Solution:**
- Changes can take 1-2 minutes to deploy
- Do a hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Wait up to 5 minutes

### Problem: CSS/Styling Not Working

**Solution:**
- Verify `index.html` includes Tailwind CDN link
- Check browser console (F12) for errors
- Try incognito/private browsing mode

---

## 🎨 Customization

### Update Content

1. Click on `index.html` in your repo
2. Click the pencil icon (✏️ Edit)
3. Make changes
4. Scroll down → Click "Commit changes"
5. Changes go live in 1-2 minutes

### Add Custom Domain

Want a custom domain like `ethnobridge.com`?

1. Go to Settings → Pages
2. Under "Custom domain", enter your domain
3. Follow DNS configuration instructions
4. Wait for DNS propagation (24-48 hours)

---

## 📊 Add Analytics (Optional)

Track visitors with Google Analytics:

1. Get tracking ID from https://analytics.google.com

2. Edit `index.html` on GitHub

3. Add before `</head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

4. Replace `GA_TRACKING_ID` with your actual ID

---

## 🔗 Sharing Your Link

### Create QR Code

1. Go to https://qr.io
2. Paste your GitHub Pages link
3. Download QR code
4. Add to presentations/posters

### Social Media

Share with:
```
🎗️ Check out EthnoBridge - a platform for head & neck cancer care in rural India

✅ 20+ Indian languages
✅ WhatsApp-based symptom tracking
✅ Treatment monitoring
✅ Multi-disciplinary care coordination

Try the live demo: [YOUR LINK]

#CancerCare #HealthTech #RuralIndia #DigitalHealth
```

### Email Template

```
Subject: EthnoBridge Demo - Head & Neck Cancer Care Platform

Hi [Name],

I'd like to share EthnoBridge, a culturally-aware platform for head and neck 
cancer patients in rural India.

Live Demo: [YOUR LINK]

Key Features:
- Multi-language symptom tracking (20+ Indian languages)
- Treatment protocol monitoring
- Side effect management
- Real-time patient dashboards

The platform is mobile-responsive and works on all devices. I'd appreciate 
your feedback!

Best regards,
[Your Name]
```

---

## 🚀 Next Steps

After deployment:

1. **Test thoroughly**
   - Try all tabs (Overview, Symptom Tracking, Patients, Treatment, Services)
   - Test language switching
   - Check on mobile device
   - Test in different browsers

2. **Share with stakeholders**
   - Send link to team members
   - Present in meetings
   - Gather feedback

3. **Iterate based on feedback**
   - Update content as needed
   - Add new features
   - Fix any issues reported

4. **Monitor usage** (if analytics enabled)
   - Track visitor numbers
   - See which pages are most viewed
   - Understand user behavior

---

## 📞 Need Help?

**Common Resources:**
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Community Forum](https://github.community)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/github-pages)

**Still stuck?** Create an issue in your repository with:
- What you tried
- What error message you see
- Screenshots if applicable

---

## ✨ Success!

Once deployed, your EthnoBridge platform will be:
- ✅ Live on the internet 24/7
- ✅ Accessible from any device
- ✅ Shareable with a simple link
- ✅ Free forever (on GitHub Pages)
- ✅ SSL secured (HTTPS)
- ✅ Fast and reliable

**Congratulations on deploying EthnoBridge!** 🎉
