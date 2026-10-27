# Sundown Studio

A modern, design-driven experiential website and creative portfolio for **Sundown Studio** — a multi-disciplinary studio focused on creating unique, end-to-end environments, experiences, and digital content.

![Sundown Studio Logo](./assets/images/logo/logo.svg)

---

## Overview

**Sundown Studio** is an award-winning style creative showcase built with clean, vanilla web technologies. Inspired by minimal editorial design and contemporary spatial branding, the website pairs bold typography with organic motion, ambient background elements, and interactive micro-interactions.

### Highlights & Key Experiences

- **Typographic Preloader**: Minimalist full-screen loader cycling dynamically through the studio's core disciplines: *Environments*, *Experiences*, and *Content*.
- **Hero Canvas with Ambient Motion**: Dramatic oversized headline (*"Spaces that inspire"*) juxtaposed with organic morphing gooey gradient shapes and looped cinematic video.
- **Kinetic Infinite Marquee**: Seamless moving typography ticker reinforcing brand identity.
- **Interactive Project Showcase**: Dynamic project directory featuring activations for Nike, Arc'teryx, Converse, and Afterpay, complete with smooth cursor-following floating image previews.
- **Tabbed Capability Showcase**: Interactive tab switcher (*Design*, *Project*, *Execution*) with smooth image cross-fading and narrative descriptions.
- **Partner Showcase Carousel**: Swiper-powered horizontal slider displaying client relationships across New York, Chicago, and Los Angeles.
- **Full-Screen Responsive Overlay Navigation**: Accessible mobile-first overlay navigation with staggered entrance animations.
- **Smooth Momentum Scrolling**: Locomotive Scroll integration for fluid spatial storytelling.

---

## Tech Stack

- **Core**: HTML5, CSS3, Modern ES6+ JavaScript
- **Smooth Scroll**: [Locomotive Scroll](https://github.com/locomotivemtl/locomotive-scroll) v3.5.4 (CDN)
- **Sliders & Carousels**: [Swiper](https://swiperjs.com/) v12 (CDN)
- **Typography**: Custom local *Neue Haas Grotesk Display* typeface
- **Media**: Optimized WebP photography, vector SVGs, and MP4 video

No complex build pipelines, bundlers, or package managers are required.

---

## Project Structure

```text
.
├── assets/
│   ├── fonts/
│   │   ├── NeueHaasDisplayMediu.ttf
│   │   └── NeueHaasDisplayRoman.ttf
│   ├── images/
│   │   ├── Footer Logo.svg
│   │   ├── list images/
│   │   │   ├── 1.webp
│   │   │   ├── 2.webp
│   │   │   ├── 3.webp
│   │   │   ├── 4.webp
│   │   │   ├── 5.webp
│   │   │   ├── 6.webp
│   │   │   ├── 7.webp
│   │   │   └── 8.webp
│   │   ├── logo/
│   │   │   ├── favicon.png
│   │   │   └── logo.svg
│   │   ├── slider images/
│   │   │   ├── AfterPay.svg
│   │   │   ├── Arc'teryx.svg
│   │   │   ├── Converse.svg
│   │   │   ├── Hunter.svg
│   │   │   ├── MediaLink.svg
│   │   │   └── Nike.svg
│   │   ├── page-2.webp
│   │   ├── page4-1.webp
│   │   ├── page4-2.webp
│   │   └── page4-3.webp
│   └── videos/
│       └── video.mp4
├── index.html
├── script.js
├── style.css
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/gajjaryash19/sundown-studio.git
cd sundown-studio
```

### 2. Run Locally

You can open `index.html` directly in any modern web browser:

```bash
# Windows PowerShell
Start-Process index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Or serve the directory using a lightweight local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then navigate to:
```text
http://localhost:8000
```

> **Note**: An active internet connection is recommended when viewing locally to load external libraries (Locomotive Scroll and Swiper) from their respective CDNs.

---

## Core Architecture & Features

### 1. Cursor-Tracking Follower (`script.js`)
The featured projects list features a smooth, floating preview image that tracks user cursor coordinates via linear interpolation (LERP):
```javascript
currentX += (mouseX - currentX) * 0.1;
currentY += (mouseY - currentY) * 0.1;
```

### 2. Ambient Gradient Blends (`style.css`)
Custom keyframe animations (`#hero-shape` and `#gooey`) produce organic morphing heat gradients utilizing Gaussian filters and blended radial gradients:
- `#fe330b` (Sundown Ember Red)
- `#ff9831` (Warm Amber Glow)

### 3. Cross-Fading Capability Tabs
The capability box on Page 4 uses an overlay image approach with cubic-bezier easing to cross-fade between project stages (*Design*, *Project*, *Execution*) without layout shifts or flashes.

### 4. Accessibility & Responsiveness
- Implements `prefers-reduced-motion` media queries to tone down or disable intense animations.
- Accessible `:focus-visible` outlines for keyboard navigators.
- Fully responsive across desktop displays, tablets, and mobile smartphones.

---

## Browser Support

Tested and supported across all modern evergreen browsers:
- Google Chrome
- Mozilla Firefox
- Apple Safari
- Microsoft Edge

---

## Deployment

Because this project is built entirely with static assets, it can be deployed instantly to any static host:

- **GitHub Pages**
- **Vercel** (`npx vercel`)
- **Netlify** (`npx netlify deploy`)
- **Cloudflare Pages**

---

## Author & Maintainer

- **Yash Gajjar** — [@gajjaryash19](https://github.com/gajjaryash19)  
  Email: [gajjaryash19@outlook.com](mailto:gajjaryash19@outlook.com)

---

## License

This project is open source and available under the [MIT License](LICENSE).
