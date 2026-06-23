# NeonSync - Cyberpunk Landing Page

A simple interactive landing page showing off front-end animations using GSAP, ScrollTrigger, and HTML5 Canvas.

![Demo Preview](demo.webp)

## Features

- **Spaceship Animations:** Custom SVGs that fly across the viewport immediately on page load, with subsequent random delays.
- **Scroll Reveals:** Sections fade and slide into view smoothly as you scroll down (via GSAP ScrollTrigger).
- **Interactive Background:** A lightweight 2D Canvas particle system that draws connecting lines between close particles.
- **Glow Effects:** CSS cards with grid-based hover glows tracking the mouse cursor.
- **Wobbly Sphere:** A physics-like SVG/CSS morphing sphere in the interaction section that reacts to clicks.

## How to Run

1. Clone this repository.
2. Open `index.html` directly in any web browser.

Alternatively, spin up a local server:
```bash
# Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

## Assets & Libraries
- GSAP & ScrollTrigger (loaded via CDN)
- FontAwesome Icons (loaded via CDN)
- Fonts: Google Fonts (Outfit, Space Grotesk)
