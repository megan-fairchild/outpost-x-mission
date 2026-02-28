# ⚔️ Operation OutpostX

> *A long time ago in a galaxy far, far away...*

An immersive, Star Wars–themed interactive experience built with vanilla HTML, CSS, and JavaScript. Designed as a cinematic mission briefing delivered via QR code.

<p align="center">
  <img src="qr-code-transmission.png" alt="Scan to begin transmission" width="280">
  <br>
  <em>Scan to begin transmission</em>
</p>

---

## 🌌 What's Inside

**Jedi Council Transmission** — A full-screen, scroll-driven briefing encoded in [Aurebesh](https://starwars.fandom.com/wiki/Aurebesh) (the Star Wars alphabet). Each section auto-decodes to Galactic Basic with a glitch animation. Features a starfield background, scanline overlay, and Star Wars theme audio.

**Holocron Archives** — A multi-page mission briefing hub containing:

| Page | Description |
|------|-------------|
| 📋 **Itinerary** | Day-by-day timeline with color-coded mission, meal, and photo tags |
| ⚔️ **Training Missions** | 8 structured missions with narrative dialogue, activities, and rewards |
| 🍽️ **Galactic Provisions** | Themed recipes with a categorized grocery checklist |
| 👕 **Wardrobe Briefing** | Day-by-day clothing guide with weather considerations and packing list |

---

## ✨ Features

- **Aurebesh font rendering** via [CDNFonts](https://fonts.cdnfonts.com/css/aurebesh) — real Star Wars script that maps to Latin characters
- **Auto-decode animation** — glitch-style font transition from Aurebesh to English
- **Scroll-snap panels** with fade-in visibility and progress indicators
- **Local audio playback** with browser autoplay gate and floating toggle
- **Dot navigation** and scroll progress bar for accessibility
- **Dark space theme** — gold (#FFD700) on deep space (#0A0A14), fully responsive
- **Print-friendly** styles for offline reference
- **External links** to real-world locations and experiences

---

## 🛠️ Tech

Zero dependencies. No frameworks. No build step.

- Vanilla HTML5 / CSS3 / ES6
- CSS `scroll-snap`, `@keyframes`, `backdrop-filter`
- `IntersectionObserver` for visibility-triggered animations
- HTML5 `<audio>` with autoplay policy compliance
- Google Fonts (Orbitron + Inter) + CDNFonts (Aurebesh)
- Hosted on GitHub Pages

---

## 🚀 Deployment

Hosted via [GitHub Pages](https://pages.github.com/). Push to `main` and the site updates automatically.

---

<p align="center">
  <strong>MAY THE FORCE BE WITH YOU. ALWAYS.</strong>
</p>
