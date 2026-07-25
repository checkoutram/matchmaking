# Thirumana Porutham — Tamil Astrology Matchmaking

A complete **Tamil astrology matchmaking web application** that generates horoscopes from birth details and performs **Ashtakoota** (8-factor) compatibility matching, scoring out of 100 with advantages, disadvantages, and Vedic remedies.

🌐 **Live Demo:** [https://checkoutram.github.io/matchmaking](https://checkoutram.github.io/matchmaking)

---

## ✨ Features

- **🌙 Horoscope Generation** — Enter DOB, Time, Place → instant Panchagam details
- **💕 Matchmaking** — Compare any male + female profile using Ashtakoota
- **📊 Score out of 100** — With verdict: Excellent / Good / Challenging
- **📋 Detailed Breakdown** — 8 factor bars with scores and descriptions
- **✅ Advantages & ⚠️ Disadvantages** — Clear compatibility analysis
- **🙏 Vedic Remedies** — Suggested pujas and mantras for doshas
- **🌐 English ↔ Tamil** — Full bilingual support with toggle button
- **💾 Offline Ready** — Works without internet after first load
- **📱 Mobile First** — Responsive design, works on all devices

---

## 🔮 Astrology Engine

Based on **Tamil Panchagam** principles:

| Factor | Tamil | Max | Measures |
|--------|-------|-----|----------|
| Varna | வர்ணமு | 1 | Spiritual compatibility |
| Vashya | வசியமு | 2 | Mutual attraction |
| Tara/Dina | தினமு | 3 | Destiny compatibility |
| Yoni | யோனி | 4 | Physical harmony |
| Graha Maitri | கிரக மைத்ரி | 5 | Planetary friendship |
| Gana | கணமு | 6 | Temperament match |
| Bhakoot | பாகூட் | 7 | Moon sign positions |
| Nadi | நாடி | 8 | Health/genetic compatibility |

**Score Scale:**
- **78–100%** = Excellent Match (Highly recommended)
- **50–77%** = Good Match (Minor remedies)
- **0–49%** = Challenging Match (Major remedies needed)

---

## 🚀 How to Use

1. **Add Profile** — Enter Name, DOB, Birth Time, Birth City, Gender
2. **View Horoscope** — See Nakshatra, Rasi, Gana, Yoni, Nadi, Tithi, Tamil Month
3. **Start New Match** — Select a male + female profile
4. **Calculate** — See score, factors, pros/cons, and remedies
5. **Toggle Language** — Tap "தமிழ்" / "English" in the header

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Storage:** Browser localStorage (profiles + history persist)
- **Fonts:** Google Fonts (Cinzel, Inter, Noto Sans Tamil)
- **Astrology:** Lahiri Ayanamsa, Julian Day calculations
- **Design:** Mobile-first, PWA-ready

---

## 📁 File Structure

```
matchmaking/
├── index.html          # Complete single-file app (89KB)
├── README.md           # This file
└── LICENSE             # MIT License
```

The entire app is contained in **one HTML file** — no build step, no dependencies, no server required.

---

## 📝 Notes

- Birth time should be entered in **local time**
- Latitude/Longitude are optional (defaults to Chennai: 13.08°N, 80.27°E)
- Uses simplified astronomical calculations for demonstration
- For precise matchmaking, consult a professional Tamil astrologer

---

## 📄 License

MIT License — Free for personal and commercial use.

Built with devotion to Tamil astrological traditions. 🙏
