# ColorThief

Upload any image. Extract its color palette instantly.

Drop in a photo, screenshot, artwork, or moodboard — ColorThief pulls out the dominant colors, names each one, and lets you copy them as hex codes or CSS variables.

## Live Demo

🔗 [jasnoor-kaur1501.github.io/ColorThief](https://jasnoor-kaur1501.github.io/ColorThief)

## What it does

- Drag and drop or upload any image
- Extracts up to 8 dominant colors using a median cut algorithm
- Names each color (Terracotta, Dusty Blue, Espresso, etc.) from a library of 75+ named anchors
- Shows hex code, color name, and RGB value for each
- Hover swatches expand in the color strip
- Copy individual hex codes, all hex codes at once, or export as CSS variables

## Output formats

```css
/* Copy as CSS variables */
:root {
  --color-1: #C4431A;
  --color-2: #F0A430;
  --color-3: #3D5C38;
}
```

## How it works

Uses a median cut color quantization algorithm entirely in the browser — no server, no API, no upload. Your image never leaves your device.

## Design

DM Mono + Clash Display · Stark white, ink black · Swiss design studio aesthetic. Looks like a tool a designer would actually use. Completely different from Days 01–05.

## Tech

HTML · CSS · Vanilla JS · Canvas API · No dependencies · No API · GitHub Pages

## Run locally

Download or clone → open `index.html` in any browser. Done.

---

*Part of #21DaysOfVibeCode — 21 projects, 21 days, all different.*
