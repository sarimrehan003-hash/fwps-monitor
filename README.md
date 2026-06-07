# FWPS Water Monitor — Mobile App Setup Guide

## How to Host & Install on Mobile

### Step 1 — Create GitHub Account
1. Go to **github.com**
2. Click **Sign up** — create a free account
3. Verify your email

### Step 2 — Create Repository
1. Click the **+** button (top right) → **New repository**
2. Repository name: `fwps-monitor`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload Files
1. Click **uploading an existing file** link
2. Drag and drop ALL these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** tab in your repository
2. Click **Pages** in left menu
3. Under "Source" → select **Deploy from a branch**
4. Branch: **main** → Folder: **/ (root)**
5. Click **Save**
6. Wait 2-3 minutes → your app URL will be:
   `https://YOUR-USERNAME.github.io/fwps-monitor/`

### Step 5 — Install on Mobile (Android)
1. Open Chrome on Android phone
2. Go to your GitHub Pages URL
3. Chrome will show **"Add to Home screen"** banner at bottom
4. Tap it → tap **Install**
5. FWPS icon appears on your home screen!

### Step 5 (alternative) — Install on Mobile (iOS iPhone)
1. Open **Safari** on iPhone
2. Go to your GitHub Pages URL
3. Tap the **Share** button (box with arrow)
4. Scroll down → tap **Add to Home Screen**
5. Tap **Add** — icon appears on home screen!

### Step 6 — Share with all staff
Just send everyone the URL:
`https://YOUR-USERNAME.github.io/fwps-monitor/`

Anyone who opens it can install it on their phone.

---

## Passwords
| Password | Default | Controls |
|---|---|---|
| Login | `fwps2024` | App entry |
| Admin | `fwps2024` | Schedule, operators |
| Developer | `fwps_dev_2024` | Pump records, code editor |

---

## Files in this package
| File | Purpose |
|---|---|
| `index.html` | Main app (all code inside) |
| `manifest.json` | Makes it installable as app |
| `sw.js` | Offline support |
| `icon-192.png` | App icon (small) |
| `icon-512.png` | App icon (large) |
