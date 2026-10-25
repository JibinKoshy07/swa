# P. Sowmiya — Portfolio

A single-page portfolio for **P. Sowmiya**, Software Developer (Python · Django · React · MySQL).

Built as one self-contained `index.html` — no build step, no dependencies. Open the file
directly, or serve the folder with any static host (GitHub Pages, Netlify, Vercel, S3).

## Design

Dark botanical green with an acid-lime accent, editorial serif display type, and monospaced
data labels. The hero carries a real plot of the elliptic curve `y² = x³ − x`, drawn from the
same mathematics behind her VLSI elliptic-curve-cryptography processor project — including
the tangent-at-P and vertical-chord constructions. Coordinates were computed exactly, so the
figure is mathematically correct rather than decorative.

## Features

- Fully responsive, verified from 360px to 1440px with no horizontal overflow
- Scroll-reveal and hero draw-on animations, all disabled under `prefers-reduced-motion`
- Content remains visible without JavaScript (`<noscript>` fallback)
- Accessible contrast (WCAG AA), semantic landmarks, and keyboard-navigable links
- No tracking, no third-party scripts beyond Google Fonts

## Structure

```
index.html    the entire site (markup, styles, and script)
```

## Running locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
