# Sparkquest — Marketing Landing Page

Static marketing site for [Sparkquest](https://sparkquest.netlify.app), a calm habit-tracking app for families. Parents configure daily tasks and rewards; kids check things off and trade points for the things they want.

## What's here

A single-page HTML/CSS landing with no build step, no framework, no dependencies:

| File | Purpose |
|---|---|
| `index.html` | Full landing page — hero, how it works, for kids, for parents, pricing, footer CTA |
| `styles.css` | Design tokens + all section styles + mobile breakpoint |
| `fonts/` | Apercu (Regular / Italic / Medium / Bold) — marketing-only typeface |
| `assets/` | Brand mark and logo SVGs |

## Design system

Visual foundations live in the [Kiddoscore repo](https://github.com/kristiankim/Kiddoscore) (the product codebase). This site uses the marketing subset:

- **Typeface:** Apercu throughout — never used in the product UI
- **Accent:** Brand indigo `hsl(250 75% 55%)`, dark `hsl(250 75% 35%)`, light `hsl(250 75% 95%)`
- **Surfaces:** Warm off-white page `hsl(250 20% 98%)`, white cards — never pure `#fff` as page bg
- **Corners:** No sharp edges. Cards at 24px, buttons at 14px, pills at 9999px
- **Voice:** Calm, encouraging, unhurried. Sentence case everywhere. No streak shaming, no urgency

## Running locally

Open `index.html` directly in a browser — no server required.

```bash
open index.html
```

Or serve it with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Deployment

Deploys automatically via Netlify on push to `main`. The app itself (Next.js) is at [sparkquest.netlify.app](https://sparkquest.netlify.app). All CTAs on this page point to `/auth/signup`.

## Related

- **Product codebase:** [kristiankim/Kiddoscore](https://github.com/kristiankim/Kiddoscore) — Next.js 14 App Router + Tailwind v4
- **Live app:** [sparkquest.netlify.app](https://sparkquest.netlify.app)
