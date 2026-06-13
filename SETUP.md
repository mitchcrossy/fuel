# fuel. — PWA Setup Guide

## What you need
- A free GitHub account (github.com)
- 5 minutes

---

## Step 1 — Create a GitHub repo

1. Go to github.com and sign in
2. Click the **+** icon → **New repository**
3. Name it exactly: `fuel`
4. Set it to **Public**
5. Click **Create repository**

---

## Step 2 — Upload the files

In your new repo, click **uploading an existing file** (or drag and drop).

Upload ALL of these files, keeping the folder structure:
```
index.html
manifest.json
sw.js
icons/
  icon-192.png
  icon-512.png
```

Click **Commit changes**.

---

## Step 3 — Enable GitHub Pages

1. In your repo, go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**

Wait about 60 seconds, then your app will be live at:
**https://YOUR-USERNAME.github.io/fuel**

---

## Step 4 — Install on your iPhone

1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your URL: `https://YOUR-USERNAME.github.io/fuel`
3. Tap the **Share** button (box with arrow pointing up)
4. Scroll down and tap **Add to Home Screen**
5. Name it **fuel.** and tap **Add**

It'll appear on your home screen like a real app — full screen, no browser bar, dark status bar.

---

## Step 5 — Android (optional)

1. Open **Chrome** on Android
2. Go to your URL
3. Tap the **⋮** menu → **Add to Home screen**
4. Tap **Add**

---

## Updating the app

When you make changes to the files, just re-upload them to GitHub and wait ~60 seconds for Pages to rebuild. The app will update automatically next time you open it with internet.

---

## Notes

- Your meal plan saves locally on each device (localStorage)
- The app shell works offline — but generating plans and recipes requires internet
- The app icon is a dark square with "f." — you can replace icons/icon-192.png and icon-512.png with your own design if you want
- Each person who uses the app gets their own private plan stored on their own device
