# Manosree N | Portfolio

Personal portfolio of **Manosree N**, a third-year B.Tech Information Technology student at Bannari Amman Institute of Technology, focused on software engineering, AI/ML and full-stack development.

**Live site:** https://manosree30.github.io/portfolio/ *(update this link if your URL is different)*

## Overview

A single-page, dark-themed portfolio built with plain HTML, CSS and JavaScript. There is no build step and no framework, so it loads fast and can be hosted anywhere that serves static files.

## Sections

- **Hero** with introduction, call-to-action buttons and an animated portrait frame
- **About** with four focus areas
- **Skills** grouped by category (taken from the resume, with no invented proficiency scores)
- **Experience** timeline
- **Projects**: SHAP-Guard AI, Real-Time Server Health Dashboard, AyurGuard and SortRight AI
- **Machine Learning Lab** with category filters; entries are learning notebooks, not production systems
- **Research**: the ICSIE 2026 publication
- **Achievements**, certifications, education and DSA/LeetCode
- **Contact** with copy-email and a validated form that opens the visitor's email app

## Features

- Particle-network background and mouse-following glow
- 3D tilt effect on the portrait
- Sticky glass navbar with an active-section indicator
- Scroll-triggered reveal animations
- Responsive layout for desktop, tablet and mobile
- Respects the `prefers-reduced-motion` setting

## Project structure

```
portfolio/
├── index.html                 # the entire website
├── Manosree_N_Resume.pdf      # resume used by the Download Resume button
└── README.md
```

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

**GitHub Pages:** go to Settings, then Pages, choose *Deploy from a branch*, select `main` and `/ (root)`, and save.

Netlify and Vercel also work: drag the folder onto Netlify Drop, or import the repo on Vercel with no build settings.

## Updating content

All text lives directly in `index.html`:

- Skills are in the `skills` object in the script at the bottom
- ML Lab entries are in the `lab` array in the same script
- The portrait is embedded as a base64 image in the `#photo` element

## Contact

- Email: manosreenagarajan@gmail.com
- LinkedIn: https://www.linkedin.com/in/manosree-nagarajan-3a5781326/
- GitHub: https://github.com/Manosree30
- LeetCode: https://leetcode.com/u/Manosree30/

## License

© 2026 Manosree N. All rights reserved.
