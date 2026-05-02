# 🌸 Happy Birthday, Anureet

A minimalist, heartfelt birthday website built with pure HTML, CSS & JavaScript.  
Deployed as a live webpage via GitHub Pages — no server needed.

---

## ✨ Features

- **Love letter** — A personal message section you can fully customize
- **Photo gallery** — 6 photo frames with click-to-upload (or hardcode images)
- **"Reasons I love you"** — A numbered list of personal reasons
- **Music player** — Add a background song via URL or file upload
- **Elegant animations** — Subtle fade-ins and heartbeat effects
- **Fully responsive** — Works beautifully on mobile

---

## 🚀 How to Deploy (Step by Step)

### Step 1 — Create the repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon → **New repository**
3. Name it something like `happy-birthday-anureet`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files
1. On your new repo page, click **Add file** → **Upload files**
2. Drag and drop `index.html` (and `song.mp3` if you have one)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings** (top tab of your repo)
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select `Deploy from a branch`
4. Choose **main** branch → **/ (root)**
5. Click **Save**

### Step 4 — Get the link 🎉
After ~1 minute, your site will be live at:
```
https://YOUR_GITHUB_USERNAME.github.io/happy-birthday-anureet/
```
Share this link with Anureet!

---

## 🎨 Customization Guide

Open `index.html` in any text editor (Notepad, VS Code, etc.)

### 💌 Personalize the love letter
Find the section labelled `<!-- LOVE LETTER -->` and rewrite the `<p>` paragraphs with your own words. Be specific — mention a real memory, an inside joke, something only you two share.

### 💝 Change the "Reasons I love you"
Find `<!-- ✏️ CUSTOMIZE -->` near the `<ul class="reason-list">` and replace each `<span class="reason-text">` with your real reasons. The more specific, the more meaningful.

### 📸 Add photos permanently
Instead of clicking to upload each time, add your images to the repo:
1. Upload your photos (e.g. `photo1.jpg`, `photo2.jpg`, etc.) to the repository
2. In `index.html`, find each `<img src="" style="display:none;">`
3. Replace `src=""` with `src="photo1.jpg"` and change `style="display:none;"` to `style="display:block;"`
4. You can also update the `.photo-caption` text below each slot

### 🎵 Add background music
**Option A — Upload a file:**
1. Add `song.mp3` to your repository
2. In `index.html`, find `<source src="YOUR_MUSIC_URL" ...>`
3. Replace `YOUR_MUSIC_URL` with `song.mp3`

**Option B — Use a URL:**
Replace `YOUR_MUSIC_URL` with a direct link to any `.mp3` file online.

> **Tip:** Use a soft instrumental or a song that means something to both of you.

### 📅 Birthday date
The date auto-fills from today's date. If you want to hardcode it, find:
```js
document.getElementById('birthday-date').textContent = ...
```
And replace it with:
```js
document.getElementById('birthday-date').textContent = "May 2, 2025";
```

---

## 📁 File Structure

```
happy-birthday-anureet/
├── index.html      ← The entire website (edit this)
├── song.mp3        ← (Optional) Your background music
├── photo1.jpg      ← (Optional) Your photos
├── photo2.jpg
└── README.md       ← This file
```

---

## 💛 Made with love

Built from scratch with HTML, CSS & vanilla JavaScript.  
Inspired by the open-source birthday website community on GitHub.  
No frameworks. No dependencies. Just heart.
