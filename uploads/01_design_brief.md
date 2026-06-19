# Portfolio Site — Design Brief for Claude Design

## Who this is for

**Leila Sayah Sparks** — Group Product Manager (8+ years across B2B InsurTech, public sector, and B2C telecom). Currently leading the full product organization at Embroker. Actively job-searching for GPM, Director of Product, and Head of Product roles. Will also consider strong Senior PM roles at companies with real product culture and growth runway.

## What this site needs to do

A portfolio site that earns a recruiter's 30-second scan and a hiring manager's 5-minute read. Three jobs:

1. **Signal level instantly** — visually and through content, this should read as a Director/GPM-track candidate, not a junior or mid PM
2. **Make the work scannable** — five case studies need to be discoverable and skimmable without overwhelming the reader
3. **Make the metrics impossible to miss** — recruiters pattern-match on numbers; the site needs to give them obvious proof points

## Site structure (single-page scroll with anchor nav)

In this order, top to bottom:

1. **Hero** — name, title, positioning statement, CTA to case studies and contact
2. **Bio** — 2–3 short paragraphs (the "About" section)
3. **Case Studies** — five case studies presented as cards in a grid, with expandable detail (either inline or modal/sub-page)
4. **How I Work With AI** — supplementary section showcasing the AI-augmented PM operating model, with a visual diagram of the four workflows
5. **How I Work / Philosophy** — four punchy beliefs
6. **Selected Experience** — visual timeline of roles
7. **Resume + LinkedIn** — clean CTAs
8. **Contact** — email-first, no overengineered form

Site navigation should be sticky/persistent for the anchor links.

## Design direction

**The brand system is already defined.** See `03_design_system.html` for the full spec. Key constraints to enforce:

- **Light base** (`#FAFAF7` Paper, not stark white)
- **One accent color, forest green** (`#2D4A3E`) — used strictly for data, tags, CTAs, active states. Never decorative.
- **Type carries the weight** — Syne 800 for display, DM Sans 300 for body, DM Mono for metadata/labels
- **One bold dark moment** somewhere on the page (the brand system suggests using it for metrics highlights — see `bold-section-demo` in the design system)
- **Generous whitespace** — `64px` standard, `96px` for section breaks
- **No gradients, no glow effects, no illustrations** — see the "What to Avoid" section of the design system

The brand personality is: **Structured. Precise. Delivered.**

## Case study card requirements

Each case study card on the main page must show:

- **Tag** (e.g., "Case Study — 01") in DM Mono caps with forest accent
- **Company / context** (e.g., "Embroker / B2B InsurTech")
- **Headline** in Syne 800
- **One-line "what this demonstrates"** (Strategy / Leadership / Range / Craft / Modern Craft)
- **2–3 hero metrics** prominently displayed (where they exist — Protego and Embroker AI Ops don't have hard metrics, design must handle this gracefully)
- **CTA: "Read Case Study →"** in forest

When expanded (or on a sub-page), each case study uses the same eight-section skeleton — see `02_content.md` for the full content of each.

## The case studies, in order

1. **Protego** — Strategy (Head of Product interview case study, offer extended)
2. **Embroker (Growth Function)** — Leadership (built + right-sized a growth function)
3. **CDS** — Range (two-act: COVID Alert + cross-government consulting squad)
4. **TELUS** — Craft (10% renewal share lift through journey-level personalization)
5. **Embroker (AI Ops)** — Modern Craft + Operating System Design (includes the workflow diagram)

## Tone and voice

- **Confident but not boastful** — the numbers and case studies do the talking
- **Direct, not jargon-heavy** — no "passionate about product" or "data-driven decision making"
- **First-person, present tense where appropriate** — "I build systems, not just outputs"
- **Opinionated where the content earns it** — POV is a seniority signal

## Specific design moments to nail

- **The Hero positioning statement** needs to feel anchored and confident — Syne 800 doing the heavy lifting
- **The Case Study grid** should feel intentional, not template — varied card layouts (one featured larger, others standard) is acceptable as long as it doesn't compromise scanability
- **The "Bold Moment"** is the metrics highlight — likely showcasing the strongest 3–4 stats across the work (e.g., +85.3% conversion, +102.5% submissions, 10% renewal share, etc.). This is the dark panel that breaks the light base.
- **The AI Ops workflow diagram** needs to live cleanly inside its case study without overwhelming the page. The diagram itself is provided.
- **The Selected Experience timeline** should be horizontal/visual rather than a vertical list — feels more like product work, less like a résumé.

## What I'm asking for

A high-fidelity mockup of the full single-page site:

- Above-the-fold hero with positioning
- Bio
- Case Study grid (showing all 5 cards) — with one example of an expanded case study view
- AI Work section with the workflow diagram
- How I Work / Philosophy section
- Selected Experience timeline
- Footer (resume, LinkedIn, contact)

After the mockup is approved, the next step is handing the design to Claude Code to build a working site.

## Files in this package

- `01_design_brief.md` — this document
- `02_content.md` — all written content for the site (positioning, bio, case studies, philosophy, etc.)
- `03_design_system.html` — the full brand identity system (colors, typography, components, principles)
