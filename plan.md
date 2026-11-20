# Project 2 plan — Kabankalan Catholic College landing page

## Implementation approach

Build a responsive, static one-page landing page in the existing Bootstrap-style convention requested by the assignment. Use semantic HTML in `index.html`, Bootstrap 5.3 from its CDN for responsive layout and utility primitives, and a project-owned `styles/main.css` for the branded system and custom interactions. Keep all user-facing behavior client-side: mobile navigation collapse, smooth anchor links, and a small year stamp. Avoid a backend so the page remains deployable to GitHub Pages.

Use only public KCC wording that has been checked against the official site. The page will summarize the school philosophy, 1927 history, current program groups, admissions steps, and published contact information. The layout will include a hero, proof strip, story/mission section, value cards, program cards, admissions timeline, contact CTA, and footer.

## Project structure

- `index.html` — single-page markup and Bootstrap CDN integration.
- `styles/main.css` — custom tokens, responsive styling, motion, and component details.
- `assets/` — reserved for project-owned static assets. This prototype uses CSS-built seal and icons so it does not invent or redistribute an unofficial logo.
- `dist/` — committed static deployment copy for no-build GitHub Pages / Manus static publishing.
- `manus-routes.json` — route manifest for the single `/` page.
- `RESEARCH.md` — source notes and public URLs used for factual copy.
- `README.md` / `TODO.md` — handoff and acceptance documentation.

## Design direction

### Alternative styles considered

- **Heritage editorial / Catholic seal** — probability 0.05. Formal, print-inspired, crest-forward, and more traditional.
- **Clear-blue academic minimal** — probability 0.04. Light, spacious, and mostly institutional with restrained color.
- **Modern campus signal** — probability 0.06. A confident blue-and-gold editorial landing page with offset panels, circular seal geometry, and a warm human tone.

### Chosen style: Modern campus signal

- **Design movement:** modern editorial institutional design with a quiet Swiss-grid backbone and subtle collegiate sign-painting details.
- **Core principles:** clarity before ornament; heritage translated into geometry; purposeful contrast; warm, student-centered language.
- **Color philosophy:** deep navy and ink anchor trust and Catholic-school seriousness; clear blue adds energy and digital relevance; gold is used as a small signal for heritage, truth, and achievement; warm paper keeps the page human rather than corporate.
- **Layout paradigm:** a staggered, asymmetrical flow where the hero overlaps an orbital seal panel, section headings sit on an offset vertical rail, and cards alternate between wide narrative blocks and compact data blocks instead of a uniform centered grid.
- **Signature elements:** a CSS-built circular “KCC / 1927” seal; gold rule markers and numbered steps; a blue-to-ink “campus horizon” band behind the hero.
- **Interaction philosophy:** links should feel like invitations, not controls; hover states reveal a gold underline or a small directional shift; no distracting carousels or auto-playing motion.
- **Animation:** use restrained `transform` and opacity transitions only; respect `prefers-reduced-motion`; reveal visual emphasis through hover/focus rather than looping effects.
- **Typography system:** `Plus Jakarta Sans` for UI and body copy, `DM Serif Display` for major headlines, with uppercase micro-labels for navigation and eyebrow text.
- **Brand essence:** a Christ-centered learning community forming capable, accountable people for service and positive change. Personality: grounded, hopeful, purposeful.
- **Brand voice:** direct, welcoming, and service-oriented. Example lines: “Build what the future needs.” and “Start your KCC journey with purpose.”
- **Wordmark & logo:** use an accessible text wordmark paired with a CSS seal, not a fabricated official logo asset.
- **Signature brand color:** `#174ea6` clear blue, supported by `#102a56` ink navy and `#e7b94b` heritage gold.

## Acceptance requirements carried from the assignment

- Create a Kabankalan Catholic College, Inc. landing page.
- Start from a Bootstrap landing-page structure and customize content, images, colors, text, and static assets for KCC.
- Use the folder naming convention `Medes-project-2`.
- Organize the project in a template-like structure.
- Keep a Git repository with at least 10 meaningful commits.
- Prepare the page for GitHub Pages deployment and preserve the source plus committed `dist/` output.
- Provide the GitHub repository URL and published Pages URL after the repository is created and Pages is enabled.
