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

Create a new repository named `Medes-Project-2` under `mayannmedes-stack`, push the full Git history, and configure Pages to publish from the `main` branch using the repository root or the committed `dist/` folder, depending on the selected GitHub Pages source. The repository URL and final Pages URL should be submitted through the assignment Google Form.

## Official sources

- [KCC homepage](https://kcc.edu.ph/)
- [About KCC](https://kcc.edu.ph/about)
- [College Programs](https://kcc.edu.ph/programs)
- [Admissions](https://kcc.edu.ph/admissions)
- [Contact KCC](https://kcc.edu.ph/contact)
