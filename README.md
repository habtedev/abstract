# Abstract Help Center — UI Clone

This repository is a UI-only clone of the Abstract help center landing page. It focuses on pixel-accurate layout, responsive behavior, and clean semantic HTML/CSS — no backend or interactive features beyond small hover and responsive behaviors.

Project structure

```
abstract-clone/
├── index.html
├── css/
│   └── styles.css
└── images/
    ├── logo.svg
    └── placeholder-illustration.svg
```

How to use

- Open `index.html` in your browser. For development, serve the folder with a static server (optional):

  python3 -m http.server 8000

- Replace placeholder images in `images/` with assets downloaded from the Frontend Practice project page.

Development notes

- This project uses a mobile-first approach: base styles apply to all sizes; media queries at 768px, 1024px, and 1440px adapt layout for larger screens.
- Colors and font stack are set via CSS variables at the top of `css/styles.css`. Replace `--accent` and font-family with the project's exact values if available.

Submission checklist (follow when finishing):

- [ ] Code pushed to GitHub (index.html, css/styles.css, images/)
- [ ] Site deployed (Vercel / Netlify) and live URL added
- [ ] Screenshots at: mobile (375px), tablet (768px), desktop (1440px)
- [ ] Reflection (250-500 words) added to repository

Reflection template (250-500 words) — paste into `REFLECTION.md` or your submission:

1. Challenges encountered

2. How you solved responsive design issues

3. What you learned

4. What you'd do differently next time

Next steps you may want me to do (I can implement any of these):

- Replace placeholder images with the official assets and adjust sizing
- Improve typography to match exact font metrics (add Google Fonts or the provided font files)
- Add more detailed hover/transition micro-interactions
- Create automated visual regression tests or a small test harness
