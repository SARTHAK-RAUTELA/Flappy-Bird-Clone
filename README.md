<div align="center">

# 🐤 HEXDRIFT — Flappy Maka

### *A Flappy Bird–style arcade game, reimagined with its own neon UI, sounds & chaos* ⚡

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install%20Now-FFD700?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=1a0a2e)](https://chromewebstore.google.com/detail/dkhbehdeohmjdbochilmckcngenokkff)
[![Version](https://img.shields.io/badge/Version-1.1-FF8800?style=for-the-badge&labelColor=1a0a2e)](https://github.com/SARTHAK-RAUTELA/Flappy-Bird-Clone)
[![Made With](https://img.shields.io/badge/Made%20With-Vanilla%20JS%20%2B%20Canvas-FF4400?style=for-the-badge&labelColor=1a0a2e)](game.js)

**🎮 [▶ PLAY NOW — Get it on the Chrome Web Store](https://chromewebstore.google.com/detail/dkhbehdeohmjdbochilmckcngenokkff?utm_source=item-share-cb) 🎮**

</div>

---

## 🕹️ What is this?

**Flappy Maka** is a fan-made parody take on the classic Flappy Bird — same one-tap, rage-inducing gameplay, but with a completely original character, a glowing neon-city vibe, meme sound effects, and juicy arcade polish. It ships as a Chrome extension: click the icon, and the game opens in a new tab. No servers, no ads, no tracking — everything runs 100% locally.

```
        ╭─────────────────────────╮
        │   ▛▀▀▜        SCORE: 42 │
        │   ▌ ● ▐  ~ flap flap ~  │
        │   ▙▄▄▟                  │
        │            █▌       ▐█  │
        │   tap to   █▌  gap  ▐█  │
        │    fly!    █▌       ▐█  │
        ╰─────────────────────────╯
```

## ✨ Features

- 🐤 **Classic one-tap gameplay** — tap / click / press Space to flap, dodge the pipes, don't die
- 🌆 **Original neon UI** — glowing hand-drawn character, scrolling city silhouette, drifting clouds & starfield
- 🔊 **Meme sound effects & music** — procedural chiptune soundtrack plus legendary death sounds 💀
- 🎆 **Arcade juice** — particle explosions, screen shake, score popups, milestone celebrations every 10 points
- 📈 **Progressive difficulty** — pipes speed up as your score climbs
- 🏆 **High score saved locally** — beat your own record, it survives restarts
- ⏱️ **Locked 60 FPS game logic** — buttery-smooth and identical speed on 60Hz, 120Hz & 144Hz monitors
- 📴 **Fully offline** — zero network calls, zero permissions abuse

## 🎮 How to Play

| Action | Control |
|--------|---------|
| Flap | 🖱️ Click / 👆 Tap / ⌨️ Spacebar |
| Start | Any flap on the title screen |
| Restart | Flap after game over |

> Get through the gap between pipes to score. Every 10 points triggers a 🌟 WAAAH! 🌟 celebration. That's it. That's the game. Good luck. 🫡

## 📦 Install

### From the Chrome Web Store (recommended)

1. Open the [**HEXDRIFT — Flappy Maka** store page](https://chromewebstore.google.com/detail/dkhbehdeohmjdbochilmckcngenokkff?utm_source=item-share-cb)
2. Click **Add to Chrome**
3. Click the 🐤 icon in your toolbar — the game opens in a new tab. Flap away!

### From source (developer mode)

1. Clone this repo:
   ```bash
   git clone https://github.com/SARTHAK-RAUTELA/Flappy-Bird-Clone.git
   ```
2. Open `chrome://extensions` in Chrome
3. Turn on **Developer mode** (top-right toggle)
4. Click **Load unpacked** and select the cloned folder

## 🗂️ Project Structure

```
Flappy-Bird-Clone/
├── manifest.json    # Chrome extension manifest (MV3)
├── background.js    # Opens the game tab on icon click
├── index.html       # Game page shell
├── game.js          # The entire game — engine, art, physics, audio
└── icon16/48/128.png
```

Built with **pure vanilla JavaScript** and the **HTML5 Canvas API** — no frameworks, no build step, no dependencies. All art is drawn procedurally in code and all audio is embedded, so the whole game is a single self-contained script.

---

<div align="center">

⚠️ *Fan-made parody game. All characters are original fictional creations for comedic purposes only.*

**✦ Made with 💛 by [Sarthak Rautela](https://github.com/SARTHAK-RAUTELA) ✦**

*If the pipes made you rage, leave a ⭐ on the repo — it heals the pain.*

</div>
