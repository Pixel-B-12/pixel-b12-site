# 🕹️ PIXEL B-12 | Retro Stream Protocol

> **The official landing page for the PIXEL B-12 broadcast.** > A retro-styled, single-page site designed to track daily game streams, fee buybacks, and supply burns.

🟢 **Live Site:** [https://pixel-b-12.github.io/pixel-b12-site/](https://pixel-b-12.github.io/pixel-b12-site/)  

---

## 📖 About
This website serves as the daily hub for the **$PIXEL** ecosystem. It features a CRT-terminal aesthetic, live chart integration, and a clear breakdown of the "Game Over" tokenomics.

**Key Features:**
* **Dynamic Daily Updates:** Designed to swap "Cartridges" (Contract Addresses) daily.
* **Retro Aesthetics:** Scanline overlays, VT323 pixel fonts, and neon terminal styling.
* **Mobile Responsive:** Stacks perfectly for mobile viewers (Logo Top / Text Bottom).
* **Live Chart Embed:** seamless integration with Pump.fun or DexScreener charts.

---

## 🛠️ Customization Guide

### Changing Colors
To change the "System Theme," edit the `:root` variables at the top of the CSS:
```css
:root {
    --terminal-green: #33ff00; /* Main text color */
    --terminal-gold: #ffcc00;  /* Glow color for $PIXEL */
    --bg-color: #0a0a0a;       /* Background */
}
