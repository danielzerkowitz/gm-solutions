# GM Solutions Website

Static marketing website for GM Solutions B.V.: medical and logistics solutions and training for austere, complex and high-risk environments (close protection, humanitarian and special assignment missions), based in The Hague, Netherlands.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages

This site can be published with GitHub Pages from the repository root. Use `index.html`, `styles.css`, `script.js`, and the `assets/` and `documents/` folders as the published files.

## Contact form

The contact form posts to Formspree (`https://formspree.io/f/xaqgoevk`). Update the `action` in `index.html` to point at your own Formspree form if needed.

## Asset note

The hero background image is saved at `assets/gm-solutions-hero.png`.

## Legal documents

Legally required documents live in `documents/` and are linked from the site footer and the contact section:

- `documents/gm-solutions-general-terms-and-conditions.pdf` (Algemene Voorwaarden, EN/NL)
- `documents/gm-solutions-complaints-procedure.pdf` (Klachtenregeling, EN/NL)

To publish a new version, replace the PDF in place and keep the filename so existing links stay valid.
