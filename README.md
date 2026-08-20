# Portfolio

Personal portfolio site  **Vasanth Kumar**, Senior Data Engineer.

**Live:** https://vasanthkumarpulkam.github.io/portfolio/

## What this is

One self-contained `index.html`. No build step, no framework, no dependencies to install.
Everything lives in a single file: markup, design tokens, layout and behaviour.

| | |
|---|---|
| Hosting | GitHub Pages, deployed from `main` at the repository root |
| CSS | Custom properties for theming, no framework |
| JavaScript | ~180 lines of vanilla JS, no libraries |
| Fonts | Inter and JetBrains Mono via Google Fonts |
| Analytics | None. No trackers, no cookies |

## Design notes

- **Light and dark themes** driven by CSS custom properties, honouring `prefers-color-scheme` and remembering an explicit choice in `localStorage`
- **Responsive** from 360px upward, with the hero architecture diagram hidden below 760px rather than squashed
- **Accessible**: semantic landmarks, a skip link, visible focus rings, ARIA on the tablist and live region
- **Reduced motion** respected, every animation and transition collapses under `prefers-reduced-motion`
- Scroll reveals use `IntersectionObserver` with a no-JS-needed fallback

## Editing

Content is data at the bottom of the file. Update the `SKILLS`, `PROJECTS` and `CERTS
` objects in the inline script to change the toolkit, project cards or credentials.
Experience entries are plain markup in the `#experience` section.

## Running locally

```bash
git clone https://github.com/vasanthkumarpulkam/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then open http://localhost:8000
# Portfolio

Personal portfolio site for **Vasanth Kumar**, Senior Data Engineer.

**Live:** https://vasanthkumarpulkam.github.io/portfolio/

## What this is

One self-contained `index.html`. No build step, no framework, no dependencies to install.
Everything lives in a single file: markup, design tokens, layout and behaviour.

| | |
|---|---|
| Hosting | GitHub Pages, deployed from `main` at the repository root |
| CSS | Custom properties for theming, no framework |
| JavaScript | Around 180 lines of vanilla JS, no libraries |
| Fonts | Inter and JetBrains Mono via Google Fonts |
| Analytics | None. No trackers, no cookies |

## Design notes

- **Light and dark themes** driven by CSS custom properties, honouring `prefers-color-scheme` and remembering an explicit choice in `localStorage`
- **Responsive** from 360px upward, with the hero architecture diagram hidden below 760px rather than squashed
- **Accessible**: semantic landmarks, a skip link, visible focus rings, ARIA on the tablist and live region
- **Reduced motion** respected, every animation and transition collapses under `prefers-reduced-motion`
- Scroll reveals use `IntersectionObserver` with a fallback when it is unavailable

## Editing

Content is data at the bottom of the file. Update the `SKILLS`, `PROJECTS` and `CERTS` objects in the inline script to change the toolkit, project cards or credentials. Experience entries are plain markup inside the `#experience` section.

## Running locally

```bash
git clone https://github.com/vasanthkumarpulkam/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then open http://localhost:8000
# portfolio
Personal portfolio site — Senior Data Engineer. Static single page, deployed on GitHub Pages.
