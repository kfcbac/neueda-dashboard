# Neueda CEO Dashboard

A standalone Progressive Web App (PWA) for weekly CEO tracking across all business functions.

## Features
- Focus wheel with six business functions
- RAG status per function
- Action tracking with due dates and priorities
- AI-powered note extraction
- Works offline
- Add to home screen on iPhone, iPad, and Mac

---

## Setup — GitHub Pages (5 minutes)

### Step 1 — Create a GitHub account
Go to github.com and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the + button (top right) → New repository
2. Name it: `neueda-dashboard`
3. Set it to **Public**
4. Click Create repository

### Step 3 — Upload the files
1. Click **uploading an existing file** on the repository page
2. Drag and drop all four files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `README.md`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository Settings
2. Click **Pages** in the left sidebar
3. Under Source, select **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Click Save

### Step 5 — Get your URL
After 1-2 minutes, your dashboard will be live at:
`https://YOUR-GITHUB-USERNAME.github.io/neueda-dashboard`

---

## Add to home screen

### iPhone / iPad
1. Open the URL in Safari
2. Tap the Share button
3. Tap **Add to Home Screen**
4. Tap Add — it'll appear as an app icon

### Mac
1. Open the URL in Safari
2. File menu → **Add to Dock**

---

## Notes
- Data is stored locally on each device (browser localStorage)
- The AI note extraction requires an internet connection
- All other features work offline once loaded
