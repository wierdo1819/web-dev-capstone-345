# Capstone Project - Online Learning Platform
**Student:** Anuroop Singh Arora  
**Roll No:** 2501660001

## Project Title
Online Learning Platform — Landing page with courses, testimonials, pricing and contact form.

## Short description
This is a responsive, semantic HTML5 + CSS3 static landing page for an online learning platform. It demonstrates real-world layout, accessibility, and visual design using Flexbox and CSS Grid. The site includes a hero banner with animation, a course grid, testimonials, pricing cards, a contact form, and footer with accessible navigation links.

## Files
- `index.html` — Main HTML file (uses semantic elements: header, nav, main, section, article, aside, footer)
- `style.css` — All styles (variables, layout, breakpoints, animations)
- `images/` — (place screenshots and images here; images used in markup are placeholders)
- `README.md` — This file

## Sections implemented
- Header / Navigation with "Skip to main content" link
- Hero / Banner with animated headline and CTA
- Course grid (CSS Grid) — multiple course cards with details and CTA
- Testimonials (carousel-like stacked cards — no JS required)
- Pricing plans (cards) with features
- Contact / Sign-up form (labels, required fields, placeholders)
- Footer with contact and social SVG icons (inline SVG placeholders)

## Layout techniques & responsive design
- **Flexbox** used for: header alignment, hero layout, footer, cards alignment.
- **CSS Grid** used for: course listing, pricing grid.
- CSS variables defined in `:root` for colors, spacing and fonts.
- Relative units: `rem`, `%`, `vw` used across the site.
- **Breakpoints** implemented:
  - Desktop: `>= 1024px` (multi-column grids)
  - Tablet: `~768px` (two-column grid adjustments)
  - Mobile: `<= 600px` (single-column stacked layout)
- Subtle hover effects, transitions and a keyframe animation on the hero headline.

## Accessibility & performance
- All images include `alt` attributes (use meaningful alt text when you replace placeholders).
- Navigation includes a "Skip to main content" link for keyboard users.
- Form fields have associated `<label>` and use `required` attributes.
- Use of semantic HTML elements improves screen-reader behavior.

## How to run / view locally
1. Clone or copy the project folder to your machine.  
2. Ensure files are: `index.html`, `style.css` (and optional `images/`).  
3. Open `index.html` in any modern browser (Chrome / Edge / Firefox).  
4. (Optional) Publish via GitHub Pages by pushing repository to GitHub and enabling Pages for the `main` branch.

## Optional
- Add `screenshot-desktop.png` and `screenshot-mobile.png` to the repo for evaluation.
- Replace placeholder images with optimized images (webp/png/jpg) in `images/`.

## Notes
This is a static front-end only project (no JavaScript required to meet assignment criteria). The site is designed to be easily extended — you can add more course details or wire it up to a backend later.

---

**Submitted by:**  
Anuroop Singh Arora — Roll No: 2501660001  

