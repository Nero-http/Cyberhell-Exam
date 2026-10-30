# CyberHell: Underground PC Lab

**Live site:** https://github.com/Nero-http/Cyberhell-Exam

## About

CyberHell is a single-page website for a local PC shop that builds custom gaming computers, repairs hardware, and sells upgrades and gear. It is made for gamers and everyday users who want a fast, honest place to get their PC built, fixed, or improved.

## Design System

### Palette (60-30-10)

| Role | Share | Color | Used for |
|---|---|---|---|
| Dominant | 60% | `#FFF4EA` (paper) | Page and card background in light mode, text in dark mode |
| Secondary | 30% | `#100604` (ink) | Text, borders, hard shadows, page and card background in dark mode |
| Accent | 10% | `#FF541E` (accent) | Buttons, section labels, ticker, highlights, glows |

The three colors are defined once as Tailwind `@theme` tokens (`--color-paper`, `--color-ink`, `--color-accent`) and reused across the whole page.

### Visual style

**Style chosen:** Neo-brutalism

**Why I chose it:** Thick borders, hard offset shadows, flat high-contrast colors, and heavy all-caps type give the shop a loud, underground gaming feel, with a small neon glow on top as the cyberpunk touch.

### Contrast check

Body text color vs. background color: `#100604` on `#FFF4EA` (light mode), `#FFF4EA` on `#100604` (dark mode)
Contrast ratio: 18.46 : 1 (needs to be at least 4.5 : 1)
Other pairs: `#100604` text on `#FF541E` buttons is 6.23 : 1, and `#FF541E` text on `#100604` in dark mode is 6.23 : 1
Tool used: WebAIM Contrast Checker

## Features

- [x] Mobile-first responsive layout
- [x] Dark mode toggle (choice remembered with localStorage)
- [x] Page-load intro animation (GSAP timeline) with a Replay intro button
- [x] Scroll reveals on every section below the hero (ScrollTrigger)
- [x] Scroll progress bar (scrub)
- [x] Reduced-motion support
- [x] Contact form with linked labels and built-in validation
- [x] Services, gear cards, and an animated hero illustration

## Built With

HTML, Tailwind CSS, JavaScript, GSAP, ScrollTrigger