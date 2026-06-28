# 🌌 Dream Weaver

> *A journey through impossible worlds*

A surreal arcade game built with pure HTML5 Canvas and Web Audio API — no frameworks, no libraries, zero cost to run. Guide your glowing orb through 10 dream worlds, collect fragments, absorb energy, and defeat bosses.

---

## 🎮 Play It Now

**[► Open dreamweaver.html in any browser to play instantly](./dreamweaver.html)**

Works on desktop and mobile. No install needed.

---

## 🕹️ How to Play

| Action | Control |
|--------|---------|
| Move your orb | Click & drag / Touch & drag |
| Destroy enemies | Hold drag — your orb absorbs them when Dream Energy is high |
| Collect fragments | Touch the glowing diamonds |
| Absorb orbs | Touch the pulsing circles for big energy boosts |
| Defeat boss | Hold drag into the boss while your energy is up |

**Dream Energy** (the bar at the bottom) powers your destruction ability. It refills when you're not dragging and when you collect items.

---

## ✨ Features

- **10 unique dream worlds** — each with its own colour palette, named theme, and increasing difficulty
- **4 enemy types** — circle, triangle, diamond, ring — each behaves differently
- **Boss fights** every 5 levels with health bars and bullet patterns
- **Combo system** — chain collections for multiplied score
- **Generative audio** — all sound effects made with Web Audio API, no audio files needed
- **Ambient drone music** — procedural background atmosphere
- **Screen shake**, particle bursts, glowing trails, pulsing stars
- **High score saved** locally in browser (localStorage)
- **Fully responsive** — works on any screen size

---

## 🌈 Dream Worlds

| Level | World Name | Colour |
|-------|-----------|--------|
| 1 | The Violet Drift | Purple |
| 2 | Coral Mindscape | Orange |
| 3 | Lucid Ocean | Cyan |
| 4 | Neon Void | Green |
| 5 ★ | Rose Gravity + BOSS | Pink |
| 6 | Amber Cosmos | Gold |
| 7 | Indigo Storm | Indigo |
| 8 | Crimson Dream | Red |
| 9 | Twilight Surge | Magenta |
| 10 ★ | The Final Ether + BOSS | White |

---

## 🛠️ Tech Stack

| Part | Technology |
|------|-----------|
| Rendering | HTML5 Canvas API |
| Audio | Web Audio API |
| Storage | localStorage |
| Styling | Pure CSS |
| Libraries | **None** — zero dependencies |
| File size | Single HTML file (~25KB) |

---

## 📱 Publishing to App Stores (Free)

This game can be wrapped into a native Android/iOS app using **Capacitor** (free & open source):

### Step 1 — Install Capacitor
```bash
npm install -g @capacitor/cli
npm install @capacitor/core @capacitor/android @capacitor/ios
npx cap init "Dream Weaver" "com.yourname.dreamweaver"
```

### Step 2 — Add Platforms
```bash
npx cap add android
npx cap add ios
```

### Step 3 — Copy Game File
Put `dreamweaver.html` inside the `www/` folder (rename it to `index.html`).

### Step 4 — Add AdMob (for ad revenue)
```bash
npm install @capacitor-community/admob
```
Then follow the [AdMob Capacitor docs](https://github.com/capacitor-community/admob) to add your Ad Unit IDs.

### Step 5 — Build
```bash
npx cap sync
npx cap open android   # opens Android Studio
npx cap open ios       # opens Xcode
```

---

## 💰 Monetisation

- **Google AdMob** — banner ads at bottom, interstitial between game overs
- **Google Play Store** — $25 one-time developer fee
- **Apple App Store** — $99/year developer fee

---

## 📁 File Structure

```
dream-weaver/
├── dreamweaver.html   ← The entire game (HTML + CSS + JS in one file)
├── README.md          ← This file
└── LICENSE            ← MIT License
```

---

## 🤝 Contributing

Pull requests welcome. Ideas for new dream worlds, enemy types, or power-ups are appreciated.

---

## 📄 License

MIT License — free to use, modify, and distribute. See [LICENSE](./LICENSE).

---

*Made with zero budget and a lot of imagination.*
