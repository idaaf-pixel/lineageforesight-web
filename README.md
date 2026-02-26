# Lineage Foresight — Website

Landing page for [lineageforesight.eu](https://lineageforesight.eu). Intelligence infrastructure for Europe's Cultural and Creative Industries.

## What this builds

One landing page. Full section structure built in a single pass. Some interactive elements (Supabase form, barometer widget) deploy as static placeholders first and get connected as backend pieces are ready.

**Sections:** Hero and tagline → who we are, what we build, who we serve → the method (one integrated system, three reinforcing layers) → Decision Readiness Assessment → interest-capture form → research partner invitation → pilot invitation → contact and footer.

## Tech stack

- Static HTML/CSS (single page, no framework)
- Deployment: Vercel
- Domain: `lineageforesight.eu` (registered at domene.no)
- Database: Supabase (connected when form and barometer are wired)

## Related repos

- `lineageforesight-readiness` — Decision Readiness Assessment, deployed on Vercel

## Build brief

The `/context` folder contains four documents that form the complete build brief:

1. `website-campaign-synthesis.md` — **Primary document.** Owns page structure, content sequence, and build order.
2. `market-pilots-addendum.md` — Commercial logic, pull mechanisms, segmentation.
3. `funding-capital-addendum.md` — Capital strategy, investor signalling, what the page must imply without stating.
4. `company-os-addendum.md` — Operating principles, engagement philosophy, tone constraints, what must not appear.

The main synthesis owns structure and content. The three addenda add constraints and requirements that reinforce the primary document but do not override it.

## Status

Pre-build. Context documents complete. Ready for first Claude Code session.
