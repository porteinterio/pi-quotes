# PORTE INTERIO Quotation App — PWA Setup Guide

## Files in this folder
```
porte-interio-pwa/
├── index.html      ← The app
├── manifest.json   ← Makes it installable
├── sw.js           ← Makes it work offline
├── icon-192.png    ← App icon
└── icon-512.png    ← App icon (large)
```

---

## Step 1 — Host on GitHub Pages (free, takes 5 mins)

1. Go to https://github.com and create a free account
2. Click **New Repository** → name it `pi-quotes` → Public → Create
3. Click **uploading an existing file**
4. Drag ALL 5 files into the upload area → Commit
5. Go to **Settings** → **Pages** → Source: `main` branch → Save
6. Your app URL will be: `https://YOUR-USERNAME.github.io/pi-quotes`

Share this URL with all staff. That's it.

---

## Step 2 — Staff install it on their phone

### Android (Chrome):
1. Open the URL in Chrome
2. Tap the 3-dot menu (⋮) → **Add to Home Screen**
3. Tap **Install**
4. The app icon appears on the home screen

### iPhone (Safari):
1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow)
3. Scroll down → **Add to Home Screen**
4. Tap **Add**

---

## After installation
- Opens full screen, no browser bar
- Works completely **offline** after first load
- Each staff member's quotes are saved on their own phone
- To update the app, just replace the files on GitHub

---

## Notes
- Each phone stores its own quotes independently (localStorage)
- Data is NOT shared between phones — this is by design for mobile staff
- If a phone is reset, quotes on that phone are lost
