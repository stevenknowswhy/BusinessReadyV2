# Cornerstone — what we're building (2026-09-29)

A proactive readiness journal for small businesses. Where the personal Journal is silent unless asked, this app talks first: it takes the owner on a guided journey of bite-sized steps ("pills"), documenting what the business **has** versus what it **needs** to be an established, fundable operation — ready to sell, borrow, raise, or win grants.

## The core loop

1. Pick a **path**: sell the business, get a loan, raise from investors, or win grants.
2. Work through **pills** — small interactive steps, one topic each, completable in minutes.
3. For every item, mark **HAVE** (with evidence attached) or **NEED** (with a next action).
4. Watch the **readiness score** climb. The app nudges, reminds, and celebrates.

## Folder structure

- `journeys/` — the pill content: five foundation pills every business needs, plus path-specific pills under `journeys/paths/`.
- `docs/adr/` — the load-bearing decisions.
- `GLOSSARY.md` — the language.

## Key decisions (docs/adr/)

- **0001 — Proactive by design.** This app nudges, reminds, and celebrates. A readiness coach that stays silent fails its job. (Deliberate inverse of the Journal's ADR-0003.)
- **0002 — The have-vs-need ledger.** Every readiness item is HAVE (with evidence attached — no self-certification without proof) or NEED (with a next action). The readiness score derives from this ledger.
- **0003 — Paths, not one checklist.** Five destinations (open a business, sell, loan, investors, grants) share the foundation pills and diverge on path-specific pills. One journey engine, five destinations. (ADR-0006 added the open-a-business path.)
- **0004 — Niche: small retail businesses in California.** Retail has roughly double the compliance surface of SaaS, most of it city-specific and blocking. Compliance density is the wedge. First content: `journeys/california-retail/sf-startup-matrix.md` — SaaS vs. retail vs. nonprofit startup requirements in San Francisco.

## The fun

- Readiness score per category and overall: HAVE ÷ (HAVE + NEED).
- Levels: 0–25 Dreamer, 26–50 Getting Legit, 51–75 Fundable, 76–100 Deal Ready.
- Streaks for daily actions, celebrations on pill completion.
- The tone is a coach, not an auditor.

## Open questions

- App name: Cornerstone (decided 2026-09-29).
- How evidence is stored (photos of documents? links? uploads?).
- Whether pills unlock in sequence or are all open from the start.
- Reminder frequency controls.
