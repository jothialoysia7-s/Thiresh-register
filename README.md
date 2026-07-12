# Thiresh Pharmaceuticals — Field Register (installable app)

This folder is a complete installable web app. To get the "app icon on your
phone, opens full-screen, works offline" experience, the files need to be
served from a real web address (https://something) — phones won't install
a PWA straight from a file sitting in Downloads or from a chat attachment.

## Fastest free ways to host it (pick one)

**Netlify Drop** (no account needed)
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page
3. You'll get a live https:// link in a few seconds

**GitHub Pages** (if you already use GitHub)
1. Create a new repository and upload all these files to it
2. Repo Settings → Pages → set source to the main branch
3. Your app will be live at https://<yourusername>.github.io/<repo-name>/

**Your own web host / cPanel**
- Upload all files (keeping them in the same folder together) to your
  domain's public folder, e.g. https://yourdomain.com/register/

## Installing it on your phone

**iPhone (Safari)**
1. Open the hosted link in Safari
2. Tap the Share icon → "Add to Home Screen" → Add

**Android (Chrome)**
1. Open the hosted link in Chrome
2. Tap the ⋮ menu → "Install app" (or "Add to Home screen")

Once installed, it opens full-screen with its own icon, and keeps working
without internet — your stock, expenses, doctor, stockist and visit data
is saved to your account automatically as you use it.

## Files in this package
- `index.html` — the app itself
- `manifest.json` — tells the phone the app's name, icon, and colors
- `service-worker.js` — caches the app so it opens instantly and works offline
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` — home-screen icons
