# Eduardo Torres — Portfolio Website

Personal portfolio and resume website for Eduardo Torres, a software developer based in San Juan, Puerto Rico, focused on backend systems, reliability, and data-driven operations.

**Live site:** single-page static HTML, no build step required.

## Features

- Swiss-minimal design with light/dark mode toggle
- Custom cursor with blend-mode effect
- Scroll-driven progress indicator and section spy navigation
- Smooth reveal animations on scroll
- Downloadable CV (`Eduardo_Torres_Resume.pdf`)
- Fully responsive (desktop + mobile)
- Tweaks panel for font size and spacing adjustments

## Sections

| # | Section | Contents |
|---|---------|----------|
| 01 | Summary | Bio, stats, go-to tech |
| 02 | Skills | Languages, frameworks, tools, databases |
| 03 | Experience | Work history |
| 04 | Projects | 5 selected GitHub projects |
| 05 | Education | B.S. CS — UPR Bayamón |
| 06 | Contact | Email and social links |

## Stack

Pure HTML/CSS/JS — no frameworks, no bundler, no dependencies beyond Google Fonts.

| Concern | Choice |
|---------|--------|
| Fonts | Inter (sans) + JetBrains Mono |
| Color | OKLCH custom properties, two themes |
| Animations | CSS transitions + IntersectionObserver |
| Hosting | Any static host (GitHub Pages, Netlify, Vercel) |

## Projects featured

- **Turn Management System** — Python · Flask · Tkinter
- **Multiplayer Hangman** — Java · Sockets · Networking
- **Freakymon Database** — PL/SQL · Database Design
- **CSV Cleaner** — Python · Automation
- **Dynamic Programming** — Java · Algorithms

## Usage

```bash
# Clone and open locally
git clone https://github.com/EduardoTorresAlamo/resume-website.git
cd resume-website
open index.html   # or serve with any static file server
```

No install step. Drop it on any static host and it works.

## Customization

All content lives in `index.html`. CSS custom properties at the top of the `<style>` block control colors, fonts, and spacing — edit `:root` and `[data-theme="dark"]` to retheme.

## License

Personal portfolio — all rights reserved.
