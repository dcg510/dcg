# CLAUDE.md

## Project Overview
Static HTML portfolio website for Daniel Greger (Principal Success Manager). Single self-contained file — no build step, no framework, no dependencies.

## Tech Stack
- Pure HTML5, CSS3, vanilla JavaScript
- Google Fonts (Nunito)
- Dark theme with gold accents (`#FFD700`)

## Running Locally
```bash
npx serve -l 3456 .
```
Opens at http://localhost:3456

## File Structure
```
index.html   # Entire site (~1040 lines, self-contained)
```

## Key Details
- All styles and scripts are embedded in `index.html` — no separate CSS/JS files
- CSS custom properties define the color system
- No automated tests
- Deploy by uploading `index.html` to any static host
