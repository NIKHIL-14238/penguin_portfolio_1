# 🐧 Pratishtha Sharma — Windows 95 Portfolio
Link : https://pratishtha-portfolio.vercel.app/

A fully interactive **Windows 95-style portfolio website** built with pure HTML, CSS and JavaScript.  
No frameworks, no build tools — just open `index.html` and it works. ✨

---

## 🖥️ Features

| Feature | Details |
|---|---|
| 🗂️ Windows | Draggable, minimisable, maximisable, closeable |
| 🎵 Sounds | Web Audio API — startup, clicks, errors, shutdown |
| 🐧 Wallpaper | Tiled cute penguin (your image, embedded) |
| 🐍 Snake Game | Fully playable retro snake — built-in |
| 📝 Notepad | Full resume as editable .txt |
| ⏻ Shutdown | Animated shutdown / restart screen |
| 🕐 Clock | Live system tray clock |
| 📋 Start Menu | All sections accessible from the Start button |

---

## 🚀 Deploy to Vercel via GitHub

### Step 1 — Push to GitHub

```bash
# 1. Create a new repo on github.com (e.g. "pratishtha-portfolio")
#    Make it PUBLIC

# 2. In your terminal:
git init
git add .
git commit -m "🐧 Initial commit — Windows 95 Portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pratishtha-portfolio.git
git push -u origin main
```

### Step 2 — Deploy on Vercel

1. Go to **[vercel.com](https://vercel.com)** and sign in with your GitHub account
2. Click **"Add New Project"**
3. Select your **`pratishtha-portfolio`** repository
4. Vercel will auto-detect it as a **Static Site** — no configuration needed
5. Click **"Deploy"** 🚀
6. Your site will be live at:  
   `https://pratishtha-portfolio.vercel.app` (or a custom URL you choose)

### Step 3 — Custom Domain (optional)

In Vercel dashboard → **Settings → Domains** → add your own domain (e.g. `pratishtha.dev`)

---

## 📁 File Structure

```
pratishtha-portfolio/
├── index.html      ← Main HTML (boot screen, desktop, windows, shutdown)
├── style.css       ← All Windows 95 styles
├── app.js          ← All logic: windows, sounds, Snake game, content
├── vercel.json     ← Vercel static deployment config
└── README.md       ← This file
```

---

## 🎮 How to Use

| Action | How |
|---|---|
| Open a window | Double-click a desktop icon |
| Move a window | Drag the title bar |
| Minimise | Click `_` button |
| Maximise | Click `□` button |
| Close | Click `✕` button |
| Start Menu | Click the **Start** button |
| Snake Game | Double-click 🐍 icon → click ▶ Start |
| Shutdown | Start → Shut Down… |

---

## 🛠️ Customising

- **Update contact links**: Edit `contentContact()` in `app.js`
- **Add projects**: Edit `contentProjects()` in `app.js`
- **Change wallpaper**: Replace the `PENGUIN_B64` base64 string in `app.js`
- **Add windows**: Add entry to `WIN_CONFIGS` and a `case` in `buildContent()`

---

Made with 🐧 and Windows 95 nostalgia.
