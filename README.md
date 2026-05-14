# Eduardo Torres — Portfolio

Personal portfolio and resume website. Single-page static site, no build step.

**Live:** open `index.html` in any browser or drop it on a static host.

## Stack

Pure HTML, CSS, and JavaScript — no frameworks, no bundler, no npm.

| Concern | Detail |
|---------|--------|
| Fonts | Inter (sans-serif) + JetBrains Mono, via Google Fonts |
| Color system | OKLCH custom properties, light and dark themes |
| Animations | CSS transitions + `IntersectionObserver` for scroll reveals |
| Hosting | Any static host — GitHub Pages, Netlify, Vercel, etc. |

## Sections

| # | Section | Contents |
|---|---------|----------|
| 01 | Summary | Bio, stats, go-to tech |
| 02 | Skills | Languages, frameworks, tools, infra |
| 03 | Experience | Work history |
| 04 | Projects | 5 selected GitHub projects |
| 05 | Education | B.S. CS — UPR Bayamón |
| 06 | Contact | Email form and social links |

## UI details

- Light/dark toggle (persisted to `localStorage`), keyboard shortcut `D`
- Custom cursor with `mix-blend-mode: difference` (auto-disabled on touch devices)
- Scroll progress indicator
- Active section spy on the nav links
- Tweaks panel (press `T`): accent color swatches, cursor toggle, density toggle
- Responsive — single-column layout on mobile

## Usage

```bash
git clone https://github.com/EduardoTorresAlamo/portfolio.git
cd portfolio
open index.html
```

All content is in `index.html`. CSS custom properties at the top of the `<style>` block control colors and fonts.

## License

Personal portfolio — all rights reserved.
