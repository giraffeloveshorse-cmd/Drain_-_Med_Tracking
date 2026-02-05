# Tracie's Recovery Tracker - PWA Setup

## What's in this folder
- `index.html` - The complete app
- `manifest.json` - PWA configuration  
- `sw.js` - Service worker (enables offline use)
- `icon-192.png` / `icon-512.png` - App icons
- `README.md` - This file

## How to deploy on GitHub Pages (free, ~5 minutes)

### Step 1: Create a GitHub account (if you don't have one)
1. Go to https://github.com
2. Sign up for a free account

### Step 2: Create a new repository
1. Click the **+** button (top right) > **New repository**
2. Name it: `drain-tracker`
3. Make sure **Public** is selected
4. Click **Create repository**

### Step 3: Upload the files
1. On the repository page, click **uploading an existing file**
2. Drag ALL 5 files from this folder into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** tab (top of the repo page)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/drain-tracker/`

### Step 5: Add to Home Screen (iPhone)
1. Open the URL above in **Safari** on your iPhone
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**
5. The app icon will appear on your home screen!

## How it works
- All data is stored locally on YOUR device using localStorage
- Nobody else can see your data
- Works offline once loaded (the service worker caches everything)
- The app looks and feels like a native app when launched from the home screen

## Need to update?
Just upload new files to the same GitHub repository and the site will update automatically within a few minutes.
