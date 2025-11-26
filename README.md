# Ryan Portfolio

A single-page portfolio for Ryan, a Utah State University master’s student, highlighting machine learning explorations, future fintech projects, and global experiences.

## Structure
- `index.html`: Main page with hero, projects, about, and contact sections.
- `styles.css`: Global styling, layout, and responsive rules.

## Getting started
1. Open `index.html` in your browser directly, or run a simple static server:
   ```bash
   python -m http.server 8000
   ```
2. Visit `http://localhost:8000`.

## Customization
- Update the hero text, project cards, and contact links in `index.html`.
- Adjust colors, spacing, or fonts in `styles.css` (root CSS variables at the top).
- Replace placeholder project links (`aria-disabled="true"` with `tabindex="-1"`) once you have live demos and source repos available.

## Accessibility & meta
- Semantic sections, skip link, and focus styles are included.
- Basic metadata (title, description, Open Graph) is set up in the `<head>`.
