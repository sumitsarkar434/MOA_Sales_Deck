# Mall of America® — Interactive Sales Deck

A fully interactive, browser-based sales deck for Mall of America, built for the Liat.ai screening assignment.

## Live Demo
Deploy `index.html` to any static host — no build step required.

## Tech Stack
- **Vanilla HTML/CSS/JS** — zero dependencies, no framework overhead
- **Google Fonts** — Bebas Neue (display), Playfair Display (editorial), Inter (body)
- **CSS custom properties** — full design token system for easy restyling
- **IntersectionObserver API** — scroll-triggered reveal animations
- **YouTube iframe embed** — video modal with autoplay

## Setup
```bash
# Option 1: Open directly
open index.html

# Option 2: Local server (recommended)
npx serve .
# or
python3 -m http.server 8080

# Option 3: Deploy to Vercel
npx vercel --prod
```

## Structure
```
index.html          # Complete self-contained application
README.md           # This file
```

## Sections
| Section | Purpose |
|---|---|
| Hero | Cinematic opener — immediate emotional impact |
| Numbers Ticker | Animated stats band — scale at a glance |
| Why MOA | Location, demographics, competitive differentiation |
| Video Interlude | YouTube embed modal with property overview |
| Retail | Retail environment, tenants, growth story |
| Luxury | Premium wing positioning, affluent audience data |
| Dining | F&B as lifestyle driver |
| Entertainment | Nickelodeon Universe, Sea Life, 15+ attractions |
| Events | 400+ annual events, venue capabilities, booking CTAs |
| Sponsorship | 3-tier partnership structure with audience data |
| Leasing | 4 leasing paths + spec table |
| Venues | Huntington Bank Rotunda, performing arts, corporate, activations |
| Finale CTA | 3-path conversion — leasing, sponsorship, events |

## Phase 2 Sub-Modules Built
- ✅ Events Module — full capabilities, past highlights, booking CTA
- ✅ Sponsorship Module — 3 partnership tiers, audience data, activation types
- ✅ Leasing Paths — 4 categories (luxury, fashion, F&B, pop-up) with specs
- ✅ Venue-Specific Modules — Rotunda, performing arts, corporate, activations

## Design Decisions
- **Palette:** Near-black backgrounds with MOA red (#C8102E) and antique gold (#B8963E) accents — luxury without coldness
- **Typography:** Bebas Neue for impact headings, Playfair Display for editorial editorial warmth, Inter for data legibility
- **Motion:** CSS scroll reveals, particle system in hero, accordion dining strip, magnetic cursor ring
- **Navigation:** Non-linear — all 8 sections accessible at any point via fixed nav
- **Conversion:** Every section ends with a CTA routing to one of 3 modal inquiry forms (leasing / sponsorship / events)

## AI Tools Used
- **Claude Sonnet** — architecture planning, copywriting, all code generation
- **Unsplash** — high-quality photography assets (real assets would be replaced with official MOA media)
- Data sourced from: mallofamerica.com, triplefive.com, Occupi, Britannica, Wikipedia

## What I'd Improve With More Time
1. **Real video assets** — swap YouTube embed for official MOA property tour video
2. **WebGL hero** — Three.js particle field or shader backdrop for the opening
3. **Animated data visualizations** — SVG-drawn charts for demographics and visitor origin maps
4. **Micro-interactions** — cursor morphing on hover states, magnetic button effects
5. **A/B CTA testing** — track which path (leasing/sponsorship/events) converts best

## Contact Targets (Real)
- **Leasing:** leasing@mallofamerica.com · 952.883.8800
- **Sponsorship:** natasha.freimark@moa.net · 952.456.1104
- **Events/Groups:** groupsales@mallofamerica.com · 952.883.8809
