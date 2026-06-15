# 📚 HSC 2026 — The Last Fight

> *"We Will Try our best"*

A beautiful, mobile-friendly study platform built for HSC 2026 students — featuring video classes, PDF notes, live exam countdown, and an admin panel to manage everything.

🔗 **Live Site:** [nishat-jihad.github.io/HSClastmoment](https://nishat-jihad.github.io/HSClastmoment/)

---

## ✨ Features

- 🎬 **Video Classes** — YouTube-embedded lectures organized by subject
- 📄 **PDF Notes** — Direct download links for every class
- ⏳ **Live Countdown** — Real-time countdown to July 2, 2026
- 🔒 **Public / Private toggle** — Hide videos from students until ready
- ✏️ **Admin Panel** — Add, edit, and remove videos on the fly
- 💾 **Persistent Storage** — All changes saved via `localStorage` (survive refresh)
- 📱 **Mobile + Desktop** — Fully responsive, touch-optimized
- ⚡ **Zero dependencies** — Pure HTML, CSS, JavaScript. No frameworks.

---

## 🗂️ Subjects Covered

| # | Subject | বাংলা নাম |
|---|---------|-----------|
| 1 | Bangla | বাংলা |
| 2 | English | ইংরেজি |
| 3 | ICT | তথ্য ও যোগাযোগ প্রযুক্তি |
| 4 | Physics | পদার্থবিজ্ঞান |
| 5 | Chemistry | রসায়ন |
| 6 | Higher Math | উচ্চতর গণিত |
| 7 | Biology | জীববিজ্ঞান |

---

## 🚀 Getting Started

This is a **single HTML file** — no build tools, no install required.

### Run locally
Just open `index.html` in any browser. That's it.

### Deploy to GitHub Pages
1. Upload `index.html` to your GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Save — your site will be live at `https://<username>.github.io/<repo>/`

---

## ⚙️ Admin Panel

Click the **⚙ Admin** button in the top-right navbar to enter admin mode.

### What you can do in admin mode:

| Action | How |
|--------|-----|
| ➕ Add a video | Click **＋ Add Video** in the video page header |
| ✏️ Edit a video | Click **✏ Edit** on any video card |
| ✕ Remove a video | Click **✕ Remove** on any video card |
| 🌐 Toggle public/private | Click **🌐 Public** or **🔒 Make Public** on any card |

### Adding a video — what you need:
- **Video Title** — বাংলা বা English যেকোনো ভাষায়
- **YouTube Video ID** — the part after `youtu.be/` e.g. `jegosLHD8vs`
- **Duration** — e.g. `45:30`
- **PDF Link** — Google Drive share link
- **Description** — short summary
- **Public toggle** — on = visible to all, off = admin only

> 💡 All changes are automatically saved to `localStorage` and persist across browser sessions.

---

## 🏗️ Project Structure

```
index.html          ← the entire app (HTML + CSS + JS, single file)
README.md           ← this file
```

Everything lives in one file — styles, logic, and data — making it dead simple to edit and deploy.

---

## 🎨 Design

Built with a bold **neo-brutalist** aesthetic:
- **Fonts:** Black Han Sans (display) + Space Grotesk (body) + Noto Sans Bengali
- **Colors:** Black `#0a0a0a`, Blue `#1a56ff`, Yellow `#ffd000`
- Hard borders + box shadows for that raw, graphic feel
- No rounded corners, no gradients — intentionally sharp

---

## 📱 Browser Support

Works on all modern browsers. Tested on:
- ✅ Chrome / Edge (desktop + Android)
- ✅ Safari (iOS + macOS)
- ✅ Firefox

---

## 🤝 Made with ❤️ for HSC 2026 Batch

Good luck on **July 2, 2026**. You've got this. 💪

---

*Built with pure HTML/CSS/JS · Hosted on GitHub Pages · Zero cost*
