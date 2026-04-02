# 🚀 Deploy Tracker Made Easy as PWA on GitHub Pages

## Step-by-Step Guide (No Terminal Needed)

---

### STEP 1: Create GitHub Account (skip if you have one)

1. Go to **github.com**
2. Click **Sign Up**
3. Create your account

---

### STEP 2: Create a New Repository

1. Go to **github.com** → click the **+** button (top right) → **New repository**
2. Fill in:
   - **Repository name:** `tracker-made-easy`
   - **Description:** `Shift & Sales Tracker PWA by Vysakh`
   - **Public** ✅ (must be public for free GitHub Pages)
   - ✅ Check **"Add a README file"**
3. Click **Create repository**

---

### STEP 3: Upload Your Files

You need to upload **4 files** to the repository. Here's how:

1. On your repository page, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL 4 files at once:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Scroll down → type commit message: `Initial PWA upload`
4. Click **"Commit changes"**

---

### STEP 4: Enable GitHub Pages

1. Go to your repository → click **Settings** (tab at the top)
2. In the left sidebar, click **Pages**
3. Under **"Source"**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes ⏳

---

### STEP 5: Get Your Live URL

1. After saving, the page will show your URL:

   ```
   https://YOUR-USERNAME.github.io/tracker-made-easy/
   ```

2. Click the link — your PWA is now LIVE! 🎉

---

### STEP 6: Install as PWA on iPhone

1. Open the URL in **Safari** on your iPhone
2. Tap the **Share button** (square with arrow ↑)
3. Scroll down → tap **"Add to Home Screen"**
4. Name it → tap **Add**
5. The app icon appears on your home screen! 💊

---

### STEP 7: Install as PWA on Android

1. Open the URL in **Chrome**
2. You'll see a banner: **"Add to Home Screen"**
3. Or tap the **⋮ menu** → **"Install app"**
4. Done!

---

## 📁 Files Included

| File | What it does |
|------|-------------|
| `index.html` | The complete app (HTML + CSS + JS all in one) |
| `manifest.json` | PWA config (name, icons, theme color) |
| `sw.js` | Service Worker (makes it work offline) |
| `icon-192.png` | App icon (192×192) |
| `icon-512.png` | App icon (512×512) |

---

## 🔄 How to Update the App Later

1. Go to your repository on GitHub
2. Click on the file you want to update (e.g., `index.html`)
3. Click the **pencil icon** ✏️ (top right of the file)
4. Make your changes
5. Click **"Commit changes"**
6. GitHub Pages auto-deploys in ~1 minute

---

## 💡 Tips

- **Data is saved in localStorage** — it stays on the device permanently
- **Works offline** after first visit (service worker caches everything)
- **Share the URL** — anyone with the link can use it
- **Custom domain**: In Settings → Pages, you can add a custom domain

---

## ⚠️ If the Site Doesn't Load

1. Make sure the repository is **Public**
2. Check Settings → Pages → Source is set to `main` / `/ (root)`
3. Wait 2-3 minutes after enabling Pages
4. Try: `https://YOUR-USERNAME.github.io/tracker-made-easy/`
5. Hard refresh: Ctrl+Shift+R (or clear Safari cache on iPhone)

---

**Tracker Made Easy** — by Vysakh 💊
