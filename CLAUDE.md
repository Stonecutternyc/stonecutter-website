# Stonecutter Website

## Purpose
Official website for Stonecutter NYC — a premium Amazon brand management agency targeting DTC brands looking for Amazon growth partners.

## Tech Stack
- Single-file HTML/CSS/JS (no frameworks)
- Fonts: DM Serif Display (headings) + Inter (body)
- Deployed on Vercel — auto-deploys from `main` branch
- Root `index.html` is what Vercel serves

## Color Palette (FINAL — March 2026)

**Background:** Cream `#EDE8E0` — this is THE background color. Wall-to-wall cream. No full-bleed colored sections.

**Pop colors (used as accents/bubbles on cream, NOT as section backgrounds):**

| Token | Hex | Usage |
|-------|-----|-------|
| Deep Teal | `#033F63` | Primary headings, nav, text, contained elements |
| Teal | `#28666E` | Secondary headings, badges, accent elements |
| Sage | `#7C9885` | Cards, borders, decorative accents |
| Olive-Sage | `#B5B682` | Eyebrow labels, subtle highlights, tags |
| Gold | `#FEDC97` | Buttons, stat numbers, underlines, warm pops |

### Critical Design Rules
1. **Cream is the base everywhere.** Colors appear as "bubbles" — contained cards, badges, buttons, text — floating on cream. NOT painted wall-to-wall as section backgrounds.
2. **Stats row:** Numbers should be centered and evenly spread across full width
3. **Service cards (Advertising, Catalog, Strategy etc):** No white card/bubble backgrounds. Let them sit directly on the cream background.
4. **Underlines must look hand-drawn** — organic, slightly wavy/imperfect like a marker or pencil stroke. Use an SVG path with natural curves, NOT a straight CSS border-bottom.
5. **No client names or logos anywhere** — anonymized case studies only (e.g. "a P&G-owned skincare brand")

## Design Inspiration
- https://www.aisle3.com/ — warm cream base, bold whitespace, confident, spacious
- The vibe: editorial, premium, clean, not corporate

## Key Files
- `src/index.html` — source (edit this)
- `index.html` — root copy for Vercel (copy src/index.html here after changes)
- `src/versions/` — previous versions saved here
- `WEBSITE_BRIEF.md` — full design brief with copy and structure
- `STONECUTTER_CONTEXT.md` — agency background and context

## Brand Context
- **Agency:** Stonecutter NYC — boutique Amazon agency
- **Stats:** $220M+ managed revenue, 14 premium brands, 92%+ retention
- **Founder:** Lee Assoulin
- **No client names on site** — use anonymous descriptors with real metrics

## Deployment
- Vercel (free tier) — auto-deploys from GitHub main branch
- Live at: stonecutter-website.vercel.app
- After editing src/index.html, copy to root: `cp src/index.html index.html`
- Then commit and push to deploy

## Conventions
- Keep it single-file (HTML + inline CSS + inline JS)
- Mobile responsive
- Smooth scroll, subtle animations
- Save previous version before major edits: `cp src/index.html src/versions/vN-description.html`
