# Govind Kumar — Portfolio Website

Interactive resume/portfolio website built for GitHub Pages.

## 🚀 Live URLs (after deployment)

| Version | URL |
|---------|-----|
| V1 — Dark Terminal | `https://govind618.github.io/` |
| V2 — Editorial | `https://govind618.github.io/v2.html` |

---

## 📦 Files

| File | Description |
|------|-------------|
| `index.html` | V1 — Dark terminal/network aesthetic (primary) |
| `v2.html` | V2 — Editorial/magazine aesthetic |
| `README.md` | This file |

---

## ⚡ Deploy in 3 Steps

### Step 1 — Create GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **"New repository"** (green button, top right)
3. Name it exactly: `YOUR_USERNAME.github.io`
   - Replace `YOUR_USERNAME` with your actual GitHub username
   - Example: if username is `govind618` → repo name is `govind618.github.io`
4. Set to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Files

**Option A — Drag & Drop (easiest, no terminal needed):**
1. Open your new repository on GitHub
2. Click **"uploading an existing file"** link
3. Drag all files from this folder (`index.html`, `v2.html`, `README.md`) into the upload area
4. Scroll down → click **"Commit changes"**

**Option B — GitHub Desktop App:**
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your new repository
3. Copy these files into the cloned folder
4. Commit and push

**Option C — Git CLI (if you have Git installed):**
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io
cd YOUR_USERNAME.github.io
# copy index.html, v2.html, README.md here
git add .
git commit -m "Add portfolio website"
git push origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. Scroll to **"Pages"** in the left sidebar
3. Under **"Source"** → select **"Deploy from a branch"**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait 2-3 minutes → your site is live!

---

## 🔗 Add URL to LinkedIn

Once live, add your URL to LinkedIn:
1. Go to your LinkedIn profile → **Edit**
2. Click **"Contact info"**
3. Add website → paste `https://YOUR_USERNAME.github.io`
4. Label it: **"Portfolio"**

Also add to your email signature and resume header.

---

## 🎨 Customise Your Subdomain (Optional)

Instead of `govind618.github.io`, you can get a custom domain like `govindkumar.dev`:

1. Buy a domain from Namecheap / GoDaddy (~₹800/year for .dev or .tech)
2. In your repo → Settings → Pages → Custom domain → enter your domain
3. Follow the DNS instructions shown

---

## ✏️ Making Changes

To update content (change your email, add a new project, etc.):
1. Edit `index.html` or `v2.html` directly on GitHub (click the file → pencil icon)
2. Commit the change
3. GitHub Pages auto-deploys within 1-2 minutes

---

*Built with pure HTML/CSS/JS — no frameworks, no build step, no dependencies.*
