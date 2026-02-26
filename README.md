# QI Presentation — Integrating Quality Improvement into Daily Clinical Practice

A polished, single-file web-based presentation built with HTML, CSS, and vanilla JavaScript. Created by [Nelson Chimdiadi C. (Youngman-d-coder)](https://github.com/Youngman-d-coder) for **Mr. Uzoma R.I., M.Sc (Cardiovascular Physiologist)**.

---

## 📋 Overview

This interactive slideshow covers the fundamentals of **Quality Improvement (QI)** in healthcare, with a focus on cardiovascular clinical practice. It replaces a traditional PowerPoint deck with a responsive, themeable, and keyboard-navigable web presentation that works in any modern browser — no installation required.

---

## 🗂️ Slides

| # | Title |
|---|-------|
| 1 | **Title Slide** — Integrating QI into Daily Clinical Practice |
| 2 | **What is Quality Improvement?** — Definition and core principles |
| 3 | **Why Quality Improvement Matters** — Strategic imperatives |
| 4 | **Core QI Methodologies & PDSA Cycle** — Clinical Audit, Root Cause Analysis, Lean, Six Sigma, and the Plan-Do-Study-Act framework |
| 5 | **Integrating QI into Daily Practice** — Identify, Measure, Implement, Embed |
| 6 | **Team-Based Approach** — Clinicians, Nurses & Allied Staff, Managers, Patients |
| 7 | **Sustaining Improvement** — KPIs, standardisation, protocol updates, culture of learning |
| 8 | **Thank You & Key Takeaways** — Executive summary and Q&A |

---

## ✨ Features

- **Single-file delivery** — the entire presentation lives in one `index.html` file; no build step, no dependencies to install.
- **7 built-in themes** — switch themes at any time via the palette button (🎨) in the navigation bar:
  - Clinical Light *(default)* — white & teal
  - Midnight Navy — deep blue & gold
  - Slate & Ember — charcoal & warm orange
  - Forest & Cream — dark green & amber
  - Dusk Purple — deep violet & lavender
  - Arctic — cool grey-blue & cobalt
  - Warm Parchment — cream & burgundy
- **Smooth slide navigation** — progress dots, slide counter, and animated transitions.
- **Full keyboard support**:
  - `→` / `↓` / `Space` — next slide
  - `←` / `↑` — previous slide
  - `Home` — first slide
  - `End` — last slide
- **Touch / swipe support** — works on mobile and tablet.
- **Print / PDF friendly** — clean print styles strip the navigation chrome and render each slide as a full page.
- **Accessible** — ARIA labels on all interactive elements and slides; keyboard-accessible theme and navigation controls.
- **Scroll-driven animations** — content cards animate in as each slide enters the viewport.
- **Google Fonts** — *Playfair Display*, *DM Sans*, and *DM Serif Display* for professional typography.

---

## 🚀 Getting Started

### View locally

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

```bash
git clone https://github.com/Youngman-d-coder/QI_Presentation.git
cd QI_Presentation
# Open in your default browser (macOS)
open index.html
# Open in your default browser (Linux)
xdg-open index.html
# Open in your default browser (Windows)
start index.html
```

> **No web server or build tools needed.** The only external dependency is Google Fonts, loaded over CDN — an internet connection is required the first time the page is opened for optimal typography.

### Deploy

Because the project is a single static HTML file it can be hosted anywhere:

- **GitHub Pages** — push to a `gh-pages` branch or enable Pages from the repository settings.
- **Netlify / Vercel** — drag-and-drop the file or connect the repository.
- Any static file host or CDN.

---

## 🖨️ Printing / Exporting to PDF

Open `index.html` in a browser and use **File → Print** (or `Ctrl+P` / `Cmd+P`). The print stylesheet hides navigation elements and renders each slide as a full A4/letter page, suitable for saving as a PDF handout.

---

## 🗃️ Project Structure

```
QI_Presentation/
├── index.html   # Complete presentation (HTML + CSS + JS, self-contained)
└── README.md    # This file
```

---

## 🛠️ Customisation

All content, styles, and themes are contained within `index.html`. Common customisations:

| What to change | Where to look in `index.html` |
|----------------|-------------------------------|
| Presenter name / credentials | `<div class="presenter-name">` and `<div class="presenter-credentials">` in Slide 1 |
| Slide content | `<section class="slide" data-index="...">` blocks inside `<main>` |
| Theme colours | CSS custom properties under each `[data-theme="..."]` block |
| Footer details | `<footer class="slide-footer">` near the bottom of the file |
| Add a new theme | Copy an existing `[data-theme="..."]` block, give it a unique name, and add a corresponding button in the theme panel |

---

## 📄 Licence

This project was created for educational and presentation purposes. All rights reserved © 2026 Nelson Chimdiadi C.

---

## 👤 Author

**Nelson Chimdiadi C.**
GitHub: [@Youngman-d-coder](https://github.com/Youngman-d-coder)

Presentation prepared for **Mr. Uzoma R.I., M.Sc (Cardiovascular Physiologist)** — *February 2026*.
