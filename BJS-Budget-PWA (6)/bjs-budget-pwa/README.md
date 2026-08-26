# BJS Budget PWA — Deployment Guide

## Files in this package
```
index.html       ← main app
manifest.json    ← PWA config
sw.js            ← service worker (offline support)
icons/
  icon-192.png
  icon-512.png
README.md        ← this file
```

## Deploy to Netlify (FREE, easiest — 2 minutes)

1. Go to https://netlify.com and sign up (free)
2. Click "Add new site" → "Deploy manually"
3. Drag the entire BJS-Budget-PWA folder onto the page
4. Netlify gives you a URL like: https://bjs-budget.netlify.app

## Install on iPhone

1. Open the Netlify URL in Safari on your iPhone
2. Tap the Share button (box with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add" — done!

The app now works fully offline and looks like a native app.

## Install on Android

1. Open the URL in Chrome
2. Tap the 3-dot menu → "Add to Home Screen"
3. Tap "Add"

## Other free hosting options
- GitHub Pages: push files to a repo, enable Pages in settings
- Cloudflare Pages: similar drag-and-drop to Netlify
