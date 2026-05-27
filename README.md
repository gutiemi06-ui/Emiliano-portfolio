# Emiliano Gutierrez — Portfolio

Personal portfolio website for Emiliano Gutierrez, CS student at Stevens Institute of Technology. Built as a static site — no frameworks, no build step, just HTML and CSS.

**Live site:** https://gutiemi06-ui.github.io/Emiliano-portfolio/

---

## Stack

- Vanilla HTML + CSS (single-file, no dependencies)
- Google Fonts — DM Serif Display, Syne, DM Mono
- Deployed via GitHub Pages

## Features

- Editorial split-screen hero with animated info cards
- Custom cursor with lagging ring effect
- Scroll-triggered reveal animations
- Responsive down to mobile
- Grain texture overlay
- Sections: About, Projects, Experience, Skills, Contact

## Structure

```
Emiliano-portfolio/
├── index.html          # Everything — HTML + embedded CSS
├── README.md
└── assets/
    └── Emiliano_Gutierrez_Resume.pdf
```

## Updating Content

All content lives in `index.html`. Edit it directly on GitHub or locally:

```bash
git clone https://github.com/gutiemi06-ui/Emiliano-portfolio.git
cd Emiliano-portfolio
# edit index.html
git add index.html
git commit -m "Update content"
git push origin main
```

GitHub Pages auto-deploys within ~2 minutes after every push.

## Adding a Project

Find the `<!-- ── PROJECTS ──>` section in `index.html` and copy this block:

```html
<div class="project-item reveal">
  <span class="project-num">05</span>
  <div class="project-main">
    <div class="project-tags">
      <span class="project-tag">Tag</span>
    </div>
    <h3 class="project-name">Project Name</h3>
    <p class="project-desc">Description here.</p>
    <div class="project-stats">
      <span class="p-stat">Stat 1</span>
    </div>
  </div>
  <div class="project-arrow">↗</div>
</div>
```

Wrap it in `<a href="..." target="_blank" class="project-item reveal">` to make it a link.

---

© 2025 Emiliano Gutierrez
