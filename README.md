# PACT Project Page Template

This repository contains the static website template used by the PACT project page.

Live example: <https://ethan-iai.github.io/pact/>

The template is a single-page academic project website designed for robotics, machine learning, and embodied AI papers. It uses plain HTML/CSS/JavaScript and can be deployed directly with GitHub Pages.

## Features

- Dark, responsive academic project-page layout.
- Hero section with title, authors, venue badge, and action links.
- Abstract, TL;DR, method, results, video, and citation sections.
- Folded detailed-results block for large figures or supplementary visuals.
- MathJax support for LaTeX equations.
- Copyable BibTeX block.
- SEO, Open Graph, Twitter Card, and citation metadata.
- GitHub Pages friendly: no build step required.

## Contents

- `index.html`: main page with layout, styling, metadata, MathJax setup, and BibTeX copy behavior.
- `static/images/`: favicon, social preview, and figure assets.
- `static/images/pact/`: example project figures used by the current page.
- `static/pdfs/`: paper PDF or supplementary PDFs.
- `static/videos/`: optional local demo videos.

## Customization

Edit `index.html` directly to replace:

- Paper title, authors, affiliation, and venue badge.
- Paper, code, and BibTeX links.
- Abstract and TL;DR content.
- Method cards, equations, and footnotes.
- Result metrics, videos, and detailed-result figures.
- Citation metadata and social sharing metadata.

Recommended assets to replace:

- `static/images/social_preview.png`
- `static/images/favicon.ico`
- `static/pdfs/paper.pdf`
- project-specific files under `static/images/` and `static/videos/`

## Deployment

The template works as a static GitHub Pages site. For the example deployment:

<https://ethan-iai.github.io/pact/>

Push updates to the branch configured for GitHub Pages to publish changes.

## Acknowledgments

This template was originally adapted from academic project page templates inspired by the Nerfies project page, then substantially redesigned for the PACT website.

## License

The website template source code is released under the GNU General Public License v2.0 (GPL-2.0).

Project-specific paper text, figures, videos, and other research assets are not part of the template license unless explicitly stated otherwise and remain copyright of their respective authors.
