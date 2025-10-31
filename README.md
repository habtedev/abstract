# Abstract Help Center — UI Clone

This repository is a UI-only clone of the Abstract Help Center landing page. The goal is to reproduce the visual design using only HTML and CSS (mobile-first, responsive, and accessible).

Project structure

```
abstract/
├── index.html            # entry page
├── css/
│   └── styles.css       # main stylesheet (mobile-first)
├── images/              # assets and screenshots
│   ├── screenhot1.png
│   ├── screenhot2.png
│   ├── screenhot3.png
│   └── screenhot4.png
└── README.md
```

# Abstract Help Center — UI Clone

This repository is a UI-only clone of the Abstract Help Center landing page. The goal is to reproduce the visual design using only HTML and CSS (mobile-first, responsive, and accessible).

## Live demo

The site is published via GitHub Pages at:

https://habtedev.github.io/abstract/

## Project structure

```
abstract/
├── index.html            # entry page
├── css/
│   └── styles.css       # main stylesheet (mobile-first)
├── images/              # assets and screenshots
│   ├── screenhot1.png
│   ├── screenhot2.png
│   ├── screenhot3.png
│   └── screenhot4.png
└── README.md
```

## Quick start — run locally

From the project root start a simple static server and open http://localhost:8000:

```bash
# from the project root
python3 -m http.server 8000
```

## Screenshots (already included)

You already have four screenshots in `images/` (named `screenhot1.png` … `screenhot4.png`). I left them in `images/` as you requested — no need to move them into a different folder.

Current files in `images/`:

- `images/screenhot1.png` — (mobile)
- `images/screenhot2.png` — (tablet)
- `images/screenhot3.png` — (desktop)
- `images/screenhot4.png` — (large)

## How to replace or optimize these images

If you want to replace any screenshot with a new export, copy your new file over the existing name and commit. Example:

```bash
# replace mobile screenshot
cp ~/Pictures/my-mobile-shot.png images/screenhot1.png
git add images/screenhot1.png
git commit -m "Update mobile screenshot"
```

To optimize PNGs before committing (optional):

```bash
# install pngquant if not already available
# on Debian/Ubuntu: sudo apt install pngquant
pngquant --quality=70-90 --force --output images/screenhot1.png images/screenhot1.png
git add images/screenhot1.png && git commit -m "Optimize mobile screenshot"
```

Embed example (use relative paths):

```html
<img
  src="images/screenhot1.png"
  alt="Mobile screenshot"
  style="max-width:100%;border-radius:8px;box-shadow:0 12px 30px rgba(0,0,0,0.08);"
/>
```

## Submission checklist

- [ ] Code pushed to GitHub (index.html, css/styles.css, images/)
- [x] Site deployed — Live demo: https://habtedev.github.io/abstract/
- [ ] Screenshots included (mobile, tablet, desktop)
- [ ] Reflection (250–500 words) added as REFLECTION.md

Reflection template (250–500 words)

1. Challenges encountered

2. How you solved responsive design issues

3. What you learned

4. What you'd do differently next time

## Deployment notes

For a simple static deploy, connect the repository to Netlify or Vercel and point the build to the repo root (no build step required). Both services will serve `index.html` directly. Alternatively, GitHub Pages is already hosting the demo at the link above.

## Commands to commit & push (example)

```bash
git add .
git commit -m "Initial project files — Abstract UI clone"
git push -u origin main
```

## Next steps I can help with

- Replace the four screenshot files with optimized PNGs (I can convert SVG placeholders to PNGs and commit them if you want).
- Rename screenshots and move them into `images/screenshots/` (I can do this and update the README).
- Deploy the site to Netlify or Vercel and add the live URL to this README (GitHub Pages link already added).

If you want, tell me which of the four screenshot files you want renamed or replaced and I will update the repo accordingly.
