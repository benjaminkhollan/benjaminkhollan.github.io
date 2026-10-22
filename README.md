# Benjamin Holland — personal website

A static portfolio for benjaminholland.com, built for GitHub Pages with HTML, CSS, and vanilla JavaScript.

## Preview

Run `python3 -m http.server 8765 --bind 127.0.0.1` from this directory and open http://127.0.0.1:8765.

## Editing

- `index.html`: homepage, project cards, about, and outdoor photography.
- `scripts/site.js`: project story content, filters, dialogs, and resume print action.
- `styles/site.css`: responsive design and print styles.
- `personal.html`: running records and personal archive, retaining the original external links.
- `resume.html`: current career summary, printable using the browser's Save as PDF option.
- `assets/`: optimized copies of the existing photos and the new favicon.

Project visuals are illustrative diagrams rather than screenshots of proprietary software. The public edition omits employer commercial figures and pending-patent details. The personal job-search workflow is identified as in progress. Existing legacy project files remain in the repository.

## Verification

Checked at 1440 × 1000 and 390 × 844: homepage and photo loading, project filtering, dialog opening/closing including Escape, personal archive navigation, and resume layout. No horizontal overflow observed on the homepage, personal archive, or resume at the phone width. JavaScript syntax checked with `node --check scripts/site.js`.

Google Fonts supplies DM Sans and Manrope; system sans-serif fallbacks are included. No build step, API key, or backend is required.
