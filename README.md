# Enviro Enablers — Premium VFX Landing Page

[![Three.js](https://img.shields.io/badge/Three.js-3D-%2300f0ff)](https://threejs.org)
[![GSAP](https://img.shields.io/badge/GSAP-Animations-%2300ff88)](https://gsap.com)
[![License](https://img.shields.io/badge/License-MIT-%237c3aed)](#license)

An immersive, VFX-driven landing page for **Enviro Enablers / Climate Circle** — an enterprise intelligence company that builds custom AI agents, manufacturing analytics, HR intelligence systems, and climate analytics platforms.

> **Live:** [https://thunacare-alt.github.io/custom-agent-makers](https://thunacare-alt.github.io/custom-agent-makers)

---

## ✦ Overview

This site is a premium single-page experience that combines real-time 3D graphics with sophisticated scroll-driven animations. It showcases Enviro Enablers' six solution domains through interactive visual storytelling.

![Preview](https://img.shields.io/badge/dynamic/json?color=00f0ff&label=hero&query=.)

## ✨ Features

### 🎯 3D Rendering (Three.js)
- **Hero centerpiece** — A rotating torus knot with emissive materials, nested wireframe overlay, and orbiting ring geometry
- **Interactive particles** — 1,800-vertex GPU-accelerated particle field with multi-color vertex shading
- **Per-card 3D shapes** — Six unique geometric primitives (torus knot, icosahedron, octahedron, dodecahedron, sphere, knot) inside service cards, each responding to mouse hover with rotation and scale

### 🎬 Scroll Animations (GSAP + ScrollTrigger)
- **Reveal animations** — Each section, card, and stat entrance-triggers with `power3.out` easing
- **Parallax hero** — Content drifts upward on scroll for depth
- **Animated counters** — Stats (50+ Deployments, 30+ Enterprise Clients, 99.9% Uptime) count up on scroll entry
- **Scroll indicator** — Animated mouse wheel icon at hero bottom

### 🖱️ Interactive Elements
- **Custom cursor glow** — 400px radial gradient that follows mouse with trailing interpolation
- **Hover effects** — Cursor scales and changes color on interactive elements
- **Card glow tracking** — Radial gradient inside each service card follows mouse position
- **3D shape interactivity** — All six card shapes respond to mouse with rotation tracking and scale pulse

### 🎨 Design System
- **Dark-but-warm palette** — `#0f0f1a` background with cyan `#00f0ff`, amber `#ff6a00`, emerald `#00ff88`, and purple `#7c3aed`
- **Typography** — Space Grotesk (headings) + Inter (body) via Google Fonts
- **Gradient text** — Multi-stop animated gradient on hero headline
- **Glassmorphism** — Frosted nav bar with backdrop blur
- **Animated input labels** — Floating labels that transition on focus/fill

## 🧩 Sections

| Section | Content |
|---|---|
| **Hero** | Full-screen 3D scene with rotating torus knot, particle field, gradient headline, dual CTAs |
| **Solutions** | Six service cards with emoji icons, descriptions, and interactive 3D shapes |
| **About** | Company story + animated stats counters (50+ / 30+ / 99.9%) |
| **Contact** | Animated form with floating labels + contact details |
| **Footer** | Company name, copyright, tagline |

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **Three.js r128** | GPU-accelerated 3D rendering (WebGL) |
| **GSAP 3.12.5** | Scroll-triggered animations, counters, reveals |
| **HTML5 / CSS3** | Semantic markup, Grid layout, custom properties |
| **Google Fonts** | Space Grotesk + Inter typefaces |

## 🚀 Deployment

This is a zero-build static site. Deploy anywhere:

```bash
# Clone
git clone https://github.com/thunacare-alt/custom-agent-makers.git

# Open directly
open index.html

# Or serve locally
python3 -m http.server 8000
# → http://localhost:8000
```

### GitHub Pages

Push to `master` branch — the site is served via GitHub Pages automatically.

## 📁 Project Structure

```
├── index.html        # Single-file site (HTML + CSS + JS + Three.js scenes)
├── README.md         # This file
├── .gitignore        # Git ignore rules
```

## 📄 License

MIT — free to use, modify, and adapt.

---

*Built with ✦ by the Enviro Enablers team*
