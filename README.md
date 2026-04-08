<div align="center">

<br />
<br />

<h1>BLUU</h1>

<p>Legal pages for Bluu, a Discord bot built for communities.</p>

<br />

![Status](https://img.shields.io/badge/status-live-6378ff?style=flat-square&labelColor=0a0a14)
![Pages](https://img.shields.io/badge/github%20pages-deployed-8a4fff?style=flat-square&labelColor=0a0a14)
![License](https://img.shields.io/badge/license-all%20rights%20reserved-6378ff?style=flat-square&labelColor=0a0a14)
![Dependencies](https://img.shields.io/badge/dependencies-none-8a4fff?style=flat-square&labelColor=0a0a14)

<br />

[Terms of Service](https://alohomora-bot.github.io/terms.html) · [Privacy Policy](https://alohomora-bot.github.io/privacy.html)

<br />
<br />

</div>

---

<br />

## Overview

Official **Terms of Service** and **Privacy Policy** pages for **Bluu**. Both pages are built entirely with raw WebGL and vanilla JavaScript, no frameworks, no external dependencies.

<br />

## Pages

| Page | Path | Description |
|---|---|---|
| Terms of Service | `/terms.html` | Usage rules, conduct policy, and liability |
| Privacy Policy | `/privacy.html` | Data collection, storage, and user rights |

<br />

## Visual Implementation

- **WebGL Silk Shader** — real-time GLSL fragment shader rendering a flowing background, unique per page
- **Variable Proximity Title** — each letter responds to cursor distance, morphing font weight 200 to 900 via `font-variation-settings`
- **Border Beam** — a light arc that travels the card border on hover using CSS `@property` conic gradient animation
- **3D Card Tilt** — cards tilt on both axes relative to cursor using CSS `perspective` transforms
- **Spinning Accent Ring Cursor** — custom cursor with a glow dot and a lagging ring with rotating conic gradient border
- **Magnetic Button** — navigation button pulled toward the cursor via JS translate offsets
- **ShinyText Badge** — animated light sweep using `background-position` keyframes
- **Fade-up Sections** — each section enters viewport with upward reveal via `IntersectionObserver`
- **Film Grain Texture** — SVG fractal noise overlay for visual depth
- **Custom Scrollbar** — minimal, matches the dark theme

<br />

## Tech

```
Rendering     WebGL 1.0
Shaders       GLSL ES 1.00
Font          Inter Variable  (wght 100-900)
Animations    CSS @property + requestAnimationFrame
Hosting       GitHub Pages
Dependencies  None
```

<br />

## Structure

```
alohomora-bot.github.io/
├── terms.html
├── privacy.html
└── README.md
```

<br />

---

<div align="center">

<br />

Operated by **Alohomora**. Not affiliated with Discord Inc.

<br />

![Made with care](https://img.shields.io/badge/made%20with-care-6378ff?style=flat-square&labelColor=0a0a14)

</div>
