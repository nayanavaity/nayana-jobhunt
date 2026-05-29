# 🚀 Nayana Vaity — Job Hunt Dashboard

Live, searchable job dashboard with 22 curated Senior PM / Director roles in India.

## ⚡ Deploy to Render (Free · Permanent URL · 5 Minutes)

### Step 1 — Create a GitHub Repo
1. Go to **https://github.com/new**
2. Name it: `nayana-jobhunt`
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Push This Folder
Open your terminal in this folder and run:

```bash
git init
git add .
git commit -m "Job hunt dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/nayana-jobhunt.git
git push -u origin main
```

### Step 3 — Deploy on Render
1. Go to **https://render.com** → Sign up free (use GitHub login)
2. Click **New → Static Site**
3. Connect your GitHub → select `nayana-jobhunt`
4. Settings:
   - **Name:** nayana-jobhunt
   - **Branch:** main
   - **Publish directory:** `.`
5. Click **Create Static Site**

✅ Your permanent URL will be: **`https://nayana-jobhunt.onrender.com`**

---

## ⚡ Alternative: GitHub Pages (Even Faster)

1. Push to GitHub (Step 1 & 2 above)
2. Go to your repo → **Settings → Pages**
3. Source: **Deploy from branch → main → / (root)**
4. Click **Save**

✅ Your URL: **`https://YOUR_USERNAME.github.io/nayana-jobhunt`**

---

## ⚡ Fastest Option: Netlify Drag & Drop (30 seconds, No account needed)

1. Go to **https://app.netlify.com/drop**
2. Drag this entire folder onto the page
3. Get an instant URL like `https://random-name-123.netlify.app`

---

## What's Inside

| File | Purpose |
|------|---------|
| `index.html` | Full interactive dashboard (22 jobs, search, filter, tracker) |
| `render.yaml` | Render.com auto-configuration |
| `.github/workflows/deploy.yml` | GitHub Pages auto-deploy |

## Features
- 🔍 Live search by company, role, skill
- 🟢🔵🟡 Filter by High / Medium / Stretch probability
- 📊 Fit scores (63–92) with match reasoning
- ✅ Click-to-track application status
- 📅 Weekly action plan
- 📱 Mobile responsive
