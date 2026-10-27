# 🪔 Shree Lakshmi Puja 2026 | Welcoming Goddess Mahalakshmi

> **ॐ श्रीं ह्रीं क्लीं महालक्ष्म्यै नमः**  
> A digital festive tribute to Goddess Mahalakshmi — celebrating the timeless spiritual traditions of **Kojagari Purnima** and **Deepavali Lakshmi Puja**.

---

## ✨ Overview

**Shree Lakshmi Puja 2026** is a single-page, zero-build static web experience designed to honor Goddess Mahalakshmi, the divine embodiment of grace, purity, spiritual light, and auspicious abundance. Built with semantic HTML5, Tailwind CSS, and vanilla JavaScript, the site blends traditional Indian aesthetics (Alpanā borders, Rangoli patterns, and temple-gold motifs) with interactive web features.

---

## 🌸 Key Features

### 1. 🏛️ Festive Hero & Animated Diya Medallion
- Welcoming announcement banner in Sanskrit/Hindi and English.
- Custom SVG clay diya with a flickering CSS flame (`flameFlicker` animation) and floating lotus motif (`subtleFloat` animation).
- Quick-fact counters highlighting the **8 Divine Forms (Ashta)**, **14 Sacred Diyas Lit**, and **108 Cosmic Names**.

### 2. 📜 Divine Significance & Philosophy
- **Samudra Manthan:** The emergence of Goddess Mahalakshmi from the cosmic ocean (*Kshira Sagara*).
- **Kojagari & Deepavali:** Cultural context across eastern India's full-moon Kojagari Purnima and nationwide Kartik Deepavali.
- **Wealth Beyond Gold:** The Vedic philosophy of *Lakshya* (higher purpose, intellectual clarity, courage, and inner harmony) and *"Alakshmi Pariharam, Lakshmi Pravesham"*.

### 3. 🪷 The Sacred Ashta Lakshmi Showcase
Detailed cards presenting the eightfold manifestations of Goddess Mahalakshmi, complete with Devanagari numerals (`०१`–`०८`), attributes, and sacred symbols:
1. **Adi Lakshmi** — Primordial Source & Consciousness (*Abhaya Mudra & Pink Lotus*)
2. **Dhanya Lakshmi** — Agricultural Nourishment (*Paddy Sheaves & Sugarcane*)
3. **Dhairya Lakshmi** — Courage, Valor & Equanimity (*Bow, Arrow & Chakra*)
4. **Gaja Lakshmi** — Sovereignty & Animal Wealth (*Sacred Elephants & Kalash*)
5. **Santana Lakshmi** — Progeny, Family & Heritage (*Child upon Her Lap*)
6. **Vijaya Lakshmi** — Triumph Over Hurdles (*Conch, Disc & Sword*)
7. **Vidya Lakshmi** — Wisdom, Intellect & Fine Arts (*Sacred Veda Manuscripts*)
8. **Dhana Lakshmi** — Material Abundance & Gold (*Golden Pitcher & Coins*)

### 4. 🏺 Core Rituals & Traditions (*Pavitra Vidhi*)
- **Alpanā & Charan Paduka:** Sacred threshold rice-paste patterns and inward footprints.
- **Kalash Sthapana:** Enshrining universal vitality with copper/brass pot, mango leaves, and coconut.
- **14 Diyas & Deep Daan:** Illuminating homes to dispel autumnal darkness and stagnation.
- **Satvik Bhog & Naivedya:** Traditional offerings including *khoi/muri*, *batasha*, *narkel naru*, seasonal fruits, and *kheer*.

### 5. 🔔 Sacred Shlokas, Mantras & Web Audio Bell
- Features the **Lakshmi Gayatri Mantra**, **Mahalakshmi Beej Mantra**, and an excerpt from the **Mahalakshmi Ashtakam (*Indra Rachita*)** with Devanagari script, transliteration, and English meanings.
- **Interactive Temple Bell (`playMantraBell`):** Uses the browser's native **Web Audio API** to synthesize a resonant `587.33 Hz` (D5 note) temple bell chime with exponential decay—requiring zero external audio files.

### 6. 🔥 Interactive Virtual Diya & Blessing Card Generator
- **Light a Virtual Diya (`lightVirtualDiya`):** Devotees enter their name/family name and choose a *Sankalpa* (intention):
  - *Dhana & Dhanya* (Abundance & Sustenance)
  - *Vidya & Buddhi* (Knowledge & Clear Vision)
  - *Arogya & Shanti* (Health, Vitality & Inner Peace)
  - *Santana & Harmony* (Domestic Bliss & Unity)
  - *Vijaya & Courage* (Triumph in Righteous Endeavors)
- **Visual & Audio Feedback:** Ignites the interactive altar diya flame, chimes the temple bell, and launches a 45-particle golden & lotus-petal confetti shower (`triggerFestiveConfetti`).
- **Personalized Mahaprasad & Divine Blessing Card:**
  - **Save Card as High-Res PNG (`downloadBlessingCardPNG`):** Renders a crisp 2x Retina greeting card via the HTML5 **Canvas 2D API**, complete with radial glows, ornate borders, custom vector lotus emblem, wrapped typography, and dynamic date stamp.
  - **Copy to Clipboard (`copyBlessingText`):** One-click formatted blessing text copying.
  - **Social Sharing:** Direct pre-filled share intents for **WhatsApp** and **X (Twitter)**.
  - **Print-Ready Stylesheet:** Dedicated `@media print` rules that isolate `#blessingPrintArea` for clean physical printing or PDF saving.

---

## 🎨 Design System & Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Markup** | Semantic HTML5 (`index.html`) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) (via CDN) + Custom CSS Keyframes & Print Media Queries |
| **Typography** | Google Fonts: `Playfair Display`, `Cinzel Decorative`, and `Poppins` |
| **Icons** | [Font Awesome 6.5.2](https://fontawesome.com/) + Custom inline SVGs |
| **Interactivity** | Vanilla JavaScript (ES6+), HTML5 Canvas 2D API, Web Audio API, Clipboard API |

### Custom Color Palette
| Token | Hex | Usage |
| :--- | :--- | :--- |
| `sacred-pink` | `#E91E63` | Primary lotus accents, badges, and highlights |
| `lotus-soft` | `#FCE4EC` | Soft card icon backgrounds |
| `lotus-rose` | `#F06292` | Secondary borders and interactive states |
| `temple-gold` | `#D4AF37` | Ornate borders, medallions, and sacred accents |
| `deep-gold` | `#AA820A` | Subheadings and symbolic metadata |
| `vermilion` | `#8B0000` | Deep festive gradients |
| `kumkum` | `#B71C1C` | Traditional auspicious crimson accents |
| `marigold` | `#FF8F00` | Festive warm highlights and confetti |
| `ivory` | `#FFFDF8` | Warm paper-like primary page background |
| `deep-maroon` | `#4A0E17` | Primary display typography and dark cards |
| `night-temple`| `#240810` | Footer and deep altar backgrounds |

---

## 🚀 Getting Started

No build tools, package managers, or local servers are required.

1. **Clone or download** this repository:
   ```bash
   git clone <repository-url>
   cd LakshmiPuja2026
   ```
2. **Open directly in any modern browser:**
   - Double-click `index.html`, or
   - Serve locally with any static file server (e.g., VS Code Live Server, `npx serve`, or `python -m http.server`).

> **Note:** An active internet connection is recommended on first load to fetch Google Fonts, Font Awesome icons, and the Tailwind CSS CDN script.

---

## 📂 Project Structure

```text
LakshmiPuja2026/
├── index.html             # Complete application (HTML structure, OG meta, Tailwind config, CSS animations, and JS logic)
├── favicon.svg            # Vector sacred diya & lotus medallion favicon
├── apple-touch-icon.png   # 180×180 iOS/mobile home screen icon
├── og-image.png           # 1200×630 Open Graph & X (Twitter) social share preview banner
├── LICENSE                # The Unlicense (Public Domain dedication)
└── README.md              # Project documentation
```

---

## 📜 License

This project is released into the public domain under **[The Unlicense](LICENSE)**. You are free to copy, modify, publish, use, and distribute this work for any purpose.

---

<p align="center">
  🪔 <em>॥ सर्वमंगलमांगल्ये शिवे सर्वार्थसाधिके ॥</em> 🪔<br>
  <strong>Shubh Maha Lakshmi Puja! May prosperity and peace illumine your path.</strong>
</p>

