# 💎 GemSlayer

A neon match-3 puzzle game — like Candy Crush, but cooler. Single self-contained HTML file, no build step, no dependencies, works offline on mobile and desktop.

**▶️ [Play it live](https://YOUR-USERNAME.github.io/gemslayer/)** *(enable GitHub Pages — see below)*

![GemSlayer](banner.png)

## ✨ Features

- **Create your hero** — pick a character, aura color, headgear, and name
- **36 levels across 6 themed worlds** — Neon City, Candy Cove, Cosmic Drift, Coral Deep, Volcano Core, Astral Void — each with its own animated background, ramping from a gentle intro to a brutal final world
- **Multiple goal types** — score targets, collect-the-gem, jelly-clear objectives, and **boss battles** (one per world, with HP bars)
- **Shape-based boosters**
  - Match 4 → **Line Blaster** (clears a row/column)
  - Match 5 → **Color Bomb** (clears a whole color)
  - L/T shape → **Bomb Gem** (3×3 blast)
  - Booster + booster swaps → Cross Blast, Mega Bomb, Supernova, Board Wipe
- **5 unlockable blaster power-ups** — Hammer, Shuffle, Bomb, Bolt, Prism
- **Ice obstacles** that lock gems, re-lock in layers, and drift across the board
- **Creeping-fire urgency** on senior levels — a blaze rises up the board if you stall; every match beats it back, but let it reach the top and you're burned out
- **Title/start screen** with a one-tap rules guide (auto-shown for first-timers)
- **Endless Survival mode** — keep your move budget alive by chaining big matches
- **Timed Challenge** + **weekly & all-time leaderboards** with a reset countdown
- **3 mini-games** — Lucky Wheel, Gem Memory, Gem Rush
- **Economy & progression** — coins, daily-streak rewards, lives/energy system, loot chests, win-streak multiplier
- **5 buyable gem skins**, a **trophy/achievements page**, and a **settings screen** (volume, SFX, colorblind symbols, reset)
- **Share your score** as a generated image card
- Background music + sound effects (Web Audio, generated live)
- Progress saves automatically to the browser (localStorage)

## 🎮 How to play

Tap or swipe two adjacent gems to swap them. Line up 3+ matching gems to clear them. Hit each level's goal before you run out of moves. Full recipes are in the in-game **❓ How to Play** menu.

## 🚀 Run locally

It's one file — just open `index.html` in any modern browser. No server required.

```bash
git clone https://github.com/YOUR-USERNAME/gemslayer.git
cd gemslayer
# then open index.html in your browser
```

## 🌐 Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then **Save**.
5. Your game goes live at `https://YOUR-USERNAME.github.io/gemslayer/`.

## 🛠️ Tech

Vanilla HTML, CSS, and JavaScript in a single file (~82 KB). No frameworks, no build tooling, no external requests. Audio is synthesized with the Web Audio API; the share card is rendered with Canvas.

## 📄 License

[MIT](LICENSE) — do whatever you like.
