# Website Rebuild Brief

## What Exists
- `src/index.html` — single-page site, 2100 lines, solid structure and animations
- `src/versions/v1-original.html` — original version for reference
- `STONECUTTER_CONTEXT.md` — full company context
- `CLAUDE.md` — project conventions

## Changes Required

### 1. Color Palette Update
Replace gold (#C9A84C) with this new palette:
- Navy: #1E3A5F (keep)
- Emerald: #2E8B6A (keep)
- Cool Silver: #94A3B8 (new accent, replaces gold for secondary elements)
- Ice Gray: #E2E8F0 (light backgrounds)
- Snow: #F8FAFC (cards/white space)
- Terracotta: #D4956A (use VERY sparingly — a subtle hover state, a thin divider accent, or one small highlight. Less is more.)
- Remove all gold/gold-light references

### 2. Remove Client Names
- Remove the scrolling client logos section entirely OR replace with anonymous category descriptors
- Keep the "$220M+" stat but remove brand names
- The second marquee row (categories: "Beauty & Wellness", "Health Supplements", etc.) can stay — those are categories, not clients
- Remove any client names from case studies

### 3. Case Studies (Vague but Real)
Replace current case studies with anonymized versions. Format:
- "A P&G-owned skincare brand" instead of "First Aid Beauty"  
- "A DTC supplement brand" instead of specific names
- Use real metrics where possible (revenue growth %, ACOS reduction, etc.)
- 3-4 case studies max

### 4. Content Enhancements (from competitive research)
Reference `/Users/aiva1/.openclaw/workspace/amazon-agency-website-research.md` for competitive intel.

Key additions:
- Stronger hero CTA (free audit/strategy call)
- Add a "Who We Work With" section describing ICP (not naming clients) — $10M+ Amazon brands, beauty/wellness/CPG
- Add a brief "Our Approach" or "How We Work" section showing the partnership model
- Testimonial section (can use placeholder quotes for now, marked as [PLACEHOLDER])
- Contact/CTA section should be compelling

### 5. Design Polish
- Keep the existing animations and reveal effects — they're good
- Ensure mobile responsiveness
- The hero image placeholder needs to stay (Lee will add imagery later)
- Keep DM Serif Display + Inter font pairing

### 6. DO NOT
- Add any client names or logos
- Use gold anywhere
- Change the fundamental page structure dramatically — enhance, don't rebuild
- Add any framework dependencies — keep it vanilla HTML/CSS/JS
