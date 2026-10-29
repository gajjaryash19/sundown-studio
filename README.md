<div align="center">

  <img src="./assets/images/logo/logo.svg" alt="Sundown Studio Logo" width="220" />

  <br />
  <br />

  <h1>Sundown Studio</h1>

  <p>
    <strong>A high-impact, design-driven experiential portfolio and spatial studio website.</strong>
  </p>

  <p>
    Crafted with semantic HTML5, modern CSS3 animations, and vanilla ES6+ JavaScript — inspired by contemporary editorial design, organic fluid gradients, and ambient micro-interactions.
  </p>

  <p>
    <a href="#overview">Overview</a> •
    <a href="#key-features">Key Features</a> •
    <a href="#design-system">Design System</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#project-structure">Structure</a> •
    <a href="#getting-started">Getting Started</a> •
    <a href="#core-architecture">Architecture</a> •
    <a href="#author">Author</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript ES6+" />
    <img src="https://img.shields.io/badge/Locomotive_Scroll-3.5.4-black?style=flat-square" alt="Locomotive Scroll" />
    <img src="https://img.shields.io/badge/Swiper-v12-6332F6?style=flat-square&logo=swiper&logoColor=white" alt="Swiper" />
    <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License: MIT" />
  </p>

</div>

---

## Overview

**Sundown Studio** is a multi-disciplinary spatial and experiential design showcase. It captures the essence of an award-winning creative agency specializing in end-to-end environments, brand experiences, and digital content.

Built entirely with clean, vanilla web technologies without heavyweight front-end frameworks or build pipelines, this project demonstrates high-fidelity web animation, seamless interactive feedback, and responsive layout craftsmanship.

---

## Key Features

- **Typographic Discipline Preloader**: A minimalist full-screen overlay cycling through the studio's primary disciplines (*Environments*, *Experiences*, *Content*) with timed cubic transitions before revealing the canvas.
- **Ambient Morphing Liquid Gradients**: Organic fluid gradient shapes with multi-point keyframe deformation and high-radius Gaussian blurs running in both the hero section and footer.
- **Kinetic Infinite Marquee**: Pure CSS kinetic typography ticker running in an uninterrupted, seamless loop.
- **Cursor-Follower Project Preview**: Interactive featured project directory featuring work for Nike, Arc'teryx, Converse, and Afterpay. Moving the mouse reveals a floating preview image interpolated smoothly (LERP) to cursor coordinates.
- **Tabbed Capability Showcase**: Interactive capability switcher (*Design*, *Project*, *Execution*) with dynamic DOM image overlay cross-fading and smooth text content replacement.
- **Client Showcase Carousel**: Touch-friendly horizontal slider powered by Swiper.js, showcasing partnerships with brands including Nike, Converse, Arc'teryx, Hunter, MediaLink, and Afterpay across New York, Chicago, and Los Angeles.
- **Mobile-First Staggered Menu**: Full-screen responsive slide-down menu overlay with staggered link animations, accessible ARIA attributes, and intuitive toggle behavior.
- **Momentum Scrolling**: Powered by Locomotive Scroll v3.5.4 for fluid spatial pacing and smooth inertial scrolling.

---

## Design System

### Color Palette

| Swatch | Name | Hex Code | Role |
| :---: | :--- | :--- | :--- |
| ![#EFEAE3](https://via.placeholder.com/14/EFEAE3?text=+) | **Canvas Cream** | `#EFEAE3` | Primary warm background color |
| ![#0B0500](https://via.placeholder.com/14/0B0500?text=+) | **Obsidian Black** | `#0B0500` | Footer background & high-contrast containers |
| ![#FE330A](https://via.placeholder.com/14/FE330A?text=+) | **Sundown Ember Red** | `#FE330A` | Primary accent, animated gradient core, indicators |
| ![#FF9831](https://via.placeholder.com/14/FF9831?text=+) | **Warm Amber Glow** | `#FF9831` | Secondary gradient blend & highlight glow |
| ![#000000](https://via.placeholder.com/14/000000?text=+) | **Deep Black** | `#000000` | Primary typography & structural borders |
| ![#868686](https://via.placeholder.com/14/868686?text=+) | **Neutral Grey** | `#868686` | Subheadings, dates, and secondary metadata |

### Typography

- **Primary Display Font**: *Neue Haas Grotesk Display Pro*
  - `NeueHaasDisplayRoman.ttf` (Regular text, body descriptions, navigation)
  - `NeueHaasDisplayMediu.ttf` (Display headlines, numbers, buttons, active states)

---

## Tech Stack

| Category | Technology | Source / Version |
| :--- | :--- | :--- |
| **Markup** | HTML5 Semantic Elements | Native |
| **Styling** | CSS3 (Flexbox, Grid, Keyframes, Custom Properties, Media Queries) | Native (`style.css`) |
| **Logic** | Vanilla JavaScript (ES6+ Modules, DOM Events, LERP) | Native (`script.js`) |
| **Smooth Scrolling** | [Locomotive Scroll](https://github.com/locomotivemtl/locomotive-scroll) | CDN v3.5.4 |
| **Touch Sliders** | [Swiper](https://swiperjs.com/) | CDN v12 |
| **Assets & Media** | WebP Photography, Scalable Vector Graphics (SVG), H.264 Video (MP4) | Local repository |

---

## Project Structure

```text
sundown-studio/
├── assets/
│   ├── fonts/
│   │   ├── NeueHaasDisplayMediu.ttf
│   │   └── NeueHaasDisplayRoman.ttf
│   ├── images/
│   │   ├── Footer Logo.svg
│   │   ├── page-2.webp
│   │   ├── page4-1.webp
│   │   ├── page4-2.webp
│   │   ├── page4-3.webp
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
│   │   └── slider images/
│   │       ├── AfterPay.svg
│   │       ├── Arc'teryx.svg
│   │       ├── Converse.svg
│   │       ├── Hunter.svg
│   │       ├── MediaLink.svg
│   │       └── Nike.svg
│   └── videos/
│       └── video.mp4
├── index.html
├── script.js
├── style.css
└── README.md
```

---

## Getting Started

Because Sundown Studio uses zero build tools, bundlers, or package managers, running the project locally is instantaneous.

### 1. Clone the Repository

```bash
git clone https://github.com/gajjaryash19/sundown-studio.git
cd sundown-studio
```

### 2. Launch Locally

#### Option A: Direct Browser Execution
Double-click `index.html` or launch it via the terminal:

```bash
# Windows (PowerShell)
Start-Process index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

#### Option B: Local HTTP Server (Recommended)
Running via an HTTP server ensures optimal asset loading and CDN resolution:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js npx
npx serve .

# Using VS Code
# Install the "Live Server" extension, right click index.html, and click "Open with Live Server"
```

Once running, navigate to:
```text
http://localhost:8000
```

> **Note**: An active internet connection is recommended during local runs to resolve Locomotive Scroll and Swiper stylesheets and scripts from CDN.

---

## Core Architecture & Implementation Highlights

### 1. Cursor Follower with Linear Interpolation (LERP)
In `script.js`, the floating preview image moves toward the user's cursor on every frame using a linear interpolation easing formula:

```javascript
// Damping factor (10% movement towards mouse target per frame)
currentX += (mouseX - currentX) * 0.1;
currentY += (mouseY - currentY) * 0.1;

fixed.style.left = `${currentX - offsetWidth / 2}px`;
fixed.style.top = `${currentY - offsetHeight / 2}px`;
```

### 2. Dynamic Image Cross-Fade Engine
The Page 4 capability switcher dynamically constructs and appends an overlay image layer, triggers a synchronous reflow, smoothly transitions the opacity, and removes temporary nodes once settled. This eliminates layout jank or white flashes:

```javascript
const tempImg = document.createElement("img");
tempImg.src = newImg;
tempImg.style.transition = "opacity 0.6s cubic-bezier(0.16, 1, 0.3, 1)";
tempImg.style.opacity = "0";
boxRight.appendChild(tempImg);
tempImg.offsetHeight; // Force reflow
tempImg.style.opacity = "1";
```

### 3. Ambient Fluid Heat Gradients
Liquid gradient blobs utilize high-intensity radial color stops combined with Gaussian blurs and CSS keyframes for continuous organic morphing:

```css
#hero-1 {
  background: radial-gradient(#fe330a, #fe370a);
  filter: blur(25px);
  animation: anime1 2s linear infinite alternate;
}
#hero-2 {
  background: radial-gradient(#fe330a, #ff9831);
  filter: blur(20px);
  animation: anime2 2s linear infinite alternate;
}
```

### 4. Accessibility & Performance Considerations
- **Hardware Acceleration**: Key transforms (`translateY`, `translate3d`, `opacity`) are offloaded to the GPU to guarantee 60 FPS animation cycles.
- **Reduced Motion Support**: Accommodates users with motion sensitivities via media queries.
- **Accessible ARIA States**: Menus and tab buttons include descriptive ARIA roles and keyboard focus styles (`:focus-visible`).

---

## Page Architecture

1. **Page 1 (Hero)**: Brand header navigation, studio value proposition, oversized editorial typography, ambient fluid gradient, and looping cinematic video.
2. **Page 2 (Marquee & Philosophy)**: Infinite kinetic marquee ticker (*Refined • Timeless • Essential*), studio manifesto, and fluid background blob animation.
3. **Page 3 (Featured Projects)**: Interactive project index (Nike, Arc'teryx, Converse, Afterpay) with cursor-following hovering image previews.
4. **Page 4 (Capabilities & Partners)**: Two-column capability module (*Design*, *Project*, *Execution*) with live cross-fade images, followed by the responsive Swiper client carousel.
5. **Footer**: Ambient red/amber gooey light source, newsletter input prompt, studio navigation, location tags, and SVG footer branding.

---

## Deployment

Deploying Sundown Studio requires only static file hosting:

- **GitHub Pages**: Go to `Settings` > `Pages` > select branch `main` and root `/`.
- **Vercel**: Run `npx vercel` or link your GitHub repository.
- **Netlify**: Drag and drop the folder into the Netlify dashboard or use `npx netlify deploy`.

---

## Author & Maintainer

- **Yash Gajjar**
  - GitHub: [@gajjaryash19](https://github.com/gajjaryash19)
  - Email: [gajjaryash19@outlook.com](mailto:gajjaryash19@outlook.com)

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
