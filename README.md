# Medes Project 2 — Kabankalan Catholic College landing page

This is May-Ann T. Medes’ Project 2 landing page for Kabankalan Catholic College, Inc. The page uses a Bootstrap-inspired structure with Bootstrap 5.3 responsive utilities, a project-owned stylesheet, the official KCC logo, and a dark-blue / clear-blue / heritage-gold visual system.

## Included sections

The single-page site includes a responsive navigation, hero message, KCC identity panel, faith/formation/service proof strip, school story, KCCIAN values, college program groups, four-step admissions timeline, contact CTA, and footer. The copy is based on public wording from KCC’s official website; the source URLs and fact notes are preserved in `RESEARCH.md`.

## Structure

```text
Medes-project-2/
├── assets/kcc-logo.png
├── dist/
├── index.html
├── manus-routes.json
├── plan.md
├── RESEARCH.md
├── TODO.md
└── styles/main.css
```

`dist/` is the committed static output. It mirrors the page, stylesheet, official logo, and route manifest so the project can be served by GitHub Pages or any static host without a build step.

## Local preview

From this folder, run:

```bash
python3 -m http.server 3001
```

Then open `http://localhost:3001/` in a browser. The page loads Bootstrap and Google Fonts from their public CDNs, while the KCC logo and project CSS are local assets.

## GitHub Pages handoff

The new public repository has been created at `https://github.com/mayannmedes-stack/Medes-Project-2` with the full 12-commit history. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. The resulting Pages URL will be `https://mayannmedes-stack.github.io/Medes-Project-2/`; submit both URLs through the assignment Google Form.

## Official sources

- [KCC homepage](https://kcc.edu.ph/)
- [About KCC](https://kcc.edu.ph/about)
- [College Programs](https://kcc.edu.ph/programs)
- [Admissions](https://kcc.edu.ph/admissions)
- [Contact KCC](https://kcc.edu.ph/contact)

## Local validation

The page was checked with a local static server. The homepage, route manifest, and official logo each returned HTTP 200, all 12 internal anchor links resolved to page IDs, and the committed `dist/` output was confirmed to contain the page, stylesheet, logo, and route manifest.
