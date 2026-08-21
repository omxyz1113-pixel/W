# ⚒ The Gaming Forge

**A free online gaming platform with 15 fully playable browser games — built entirely in HTML5/CSS3/JavaScript. No downloads, no external dependencies, no broken iframes.**

## 🎮 Games Included
1. 🐍 Snake
2. 🟦 Tetris
3. 🏏 Breakout
4. 🔢 2048
5. 🚀 Space Shooter
6. 🏓 Pong
7. 🐦 Flappy Bird
8. 🦕 Dino Run
9. 🧠 Memory Match
10. ☄️ Asteroids
11. 💣 Minesweeper
12. 🦔 Whack-a-Mole
13. ⚽ Ball Bounce
14. 🎨 Color Rush
15. ⌨️ Typing Speed

## 🚀 Deploy to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm install -g vercel
vercel
```

### Option 2 — GitHub + Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new
3. Import the repo → Deploy (zero config needed)

### Option 3 — Drag & Drop
1. Go to https://vercel.com/new
2. Drag this entire folder into the browser
3. Click Deploy

## 💰 Google AdSense Setup
1. Get approved at https://adsense.google.com
2. Replace `ca-pub-XXXXXXXX` in `index.html` with your Publisher ID
3. Replace each `data-ad-slot="XXXXXXXX"` with your real slot IDs
4. Uncomment the AdSense `<script>` tag in the `<head>`
5. Redeploy

## 📁 Project Structure
```
gaming-forge/
├── index.html      ← Entire site + all 15 games
├── vercel.json     ← Vercel deployment config
├── package.json    ← Project metadata
├── .gitignore      ← Git ignore rules
└── README.md       ← This file
```

## ⚡ Tech Stack
- Pure HTML5 / CSS3 / JavaScript (no frameworks)
- Canvas API for all games
- LocalStorage for favorites + high scores
- Google Fonts (Audiowide, Rajdhani, Nunito)
- Zero external game dependencies

## 📜 License
MIT — free to use, modify, and deploy.
