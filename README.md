# आयुष — Ayush
### *Sacred Lifespan Clock*

> *"आयुषः क्षण एकोऽपि न लभ्यः स्वर्णकोटिभिः"*
> Not even one moment of life can be purchased with crores of gold.
> — Mahabharata, Shantiparva

---

A fullscreen, offline-first PWA that counts your **remaining heartbeats** — inspired by Hindu philosophy and the four Ashrams of life. Designed to be your phone's **lock screen or home screen**.

![Preview](https://img.shields.io/badge/PWA-Offline%20Ready-gold?style=for-the-badge&logo=pwa)
![Languages](https://img.shields.io/badge/Languages-12%20Indian-orange?style=for-the-badge)
![Quotes](https://img.shields.io/badge/Quotes-295%20Sacred-red?style=for-the-badge)

---

## ✨ Features

- **Real-time heartbeat counter** — counts down your remaining beats based on age and expected lifespan
- **12 Indian languages** — Sanskrit, Hindi, Marathi, Bengali, Telugu, Tamil, Kannada, Malayalam, Gujarati, Punjabi, Odia, English
- **295 sacred quotes** — from Bhagavad Gita, Mahabharata, Ramayana, Upanishads, Chanakya Niti
- **Four Ashrams** — Brahmacharya → Grihastha → Vanaprastha → Sannyasa, color-coded by life stage
- **Fully offline** — works with zero internet after first load
- **Installable PWA** — add to home screen, opens fullscreen

---

## 🚀 Live Demo

**[https://sai2311-eng.github.io/ayush/](https://sai2311-eng.github.io/ayush/)**

---

## 📱 Install on Phone

### Android
1. Open the URL in **Chrome**
2. Tap the three-dot menu → **Add to Home Screen**
3. Open once with internet → works offline forever

### iPhone / iPad
1. Open the URL in **Safari**
2. Tap the Share button → **Add to Home Screen**
3. Open once with internet → works offline forever

---

## 🛠 Local Setup

No build tools needed. This is a single HTML file.

```bash
git clone https://github.com/sai2311-eng/ayush.git
cd ayush
# Open index.html in any browser
```

Or just download `index.html` and open it directly.

---

## 🗂 File Structure

```
ayush/
├── index.html      ← The entire app (single file, ~93KB)
└── README.md       ← This file
```

---

## 🙏 Sources

| Source | Quotes |
|--------|--------|
| Bhagavad Gita (all 18 chapters) | 65+ |
| Mahabharata (Shantiparva, Vanaparva, Anushasanaparva) | 80+ |
| Valmiki Ramayana (all 7 Kandas) | 50+ |
| Upanishads (Katha, Mundaka, Chandogya, Brihadaranyaka) | 60+ |
| Chanakya Niti & Arthashastra | 40+ |

---

## ⚙️ How It Works

- **BPM by age:** 0–25 → 75 bpm, 25–50 → 72, 50–75 → 70, 75+ → 68
- **Total beats** = Expected age × 365.25 × 24 × 60 × BPM
- **Remaining** = Total − Beats lived since birth
- Quotes rotate every 30 seconds, translated into your selected language
- Service Worker caches everything on first load for permanent offline use

---

## 📄 License

MIT — free to use, modify and share.

---

*"जातस्य हि ध्रुवो मृत्युः" — Death is certain for those who are born. Use your beats wisely.*
