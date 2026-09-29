# Cornerstone

Legally Built. Fully Compliant. Lender Ready.

A proactive readiness journal for small businesses — bite-sized guided steps ("pills") that document what a business already has (**HAVE**, with evidence) versus what it still needs (**NEED**, with a next action) to become established and ready to sell, borrow, raise investment, or win grants.

## What's here

- `SUMMARY.md` — the project overview: core loop, key decisions, open questions
- `GLOSSARY.md` — the product language (pills, journeys, paths, have/need, readiness score)
- `docs/adr/` — architecture decision records (the load-bearing choices)
- `journeys/` — the pill content: five foundation pills every business needs, plus path-specific pills under `journeys/paths/`
- `journeys/california-retail/` — the California retail niche: SF startup-requirements matrix (SaaS vs. retail vs. nonprofit)
- `brainstorming/` — raw, unedited LLM brainstorming replies used to iterate on the product

## Current state

Design docs and journey content. A private working prototype (v0.1) exists separately — guided SF retail setup, four paths, have/need ledger, readiness score.

## Key decisions

- **Proactive by design** — the app nudges, reminds, and celebrates (deliberate inverse of a silent journal)
- **Have-need-desirable ledger** — every item is HAVE (with evidence), NEED (with a next action), or DESIRABLE (tracked, aspirational); the readiness score derives from HAVE and NEED only
- **Paths, not one checklist** — sell, loan, investors, grants share foundation pills and diverge on path pills
- **Niche: small retail in California** — compliance density is the wedge, starting with San Francisco
