# Cornerstone

A proactive readiness journal that takes a small business owner on a guided journey from "idea with a name" to fundable, sellable, established business.

## Language

**Pill**:
A single bite-sized interactive step in a journey — one topic, completable in a few minutes. The unit of progress.
_Avoid_: lesson, module, task

**Journey**:
The full guided sequence of pills from where the business is now to ready. One journey engine, four paths.
_Avoid_: course, program

**Path**:
The destination the owner picks: sell the business, get a loan / financing, raise from investors, or win grants. Paths share foundation pills and diverge on path-specific pills.
_Avoid_: track, funnel

**Have**:
A readiness item the business already satisfies, with evidence attached. Claims without evidence don't count.
_Avoid_: done, checked

**Need**:
A readiness item still missing, always paired with a concrete next action.
_Avoid_: todo, gap

**Desirable**:
A readiness item that would strengthen the business but isn't required for readiness on the chosen path. Tracked, no next action or evidence required. Excluded from the readiness score.
_Avoid_: nice-to-have, wishlist

**Readiness score**:
HAVE ÷ (HAVE + NEED), per category and overall. The number the whole app revolves around.
_Avoid_: grade, rating

**Evidence**:
The proof behind a HAVE — a document, photo, link, or record. Lenders and buyers ask for proof, not promises.
_Avoid_: attachment, file

**Nudge**:
A proactive prompt from the app — a reminder, a celebration, a "you're one item from Fundable." Bounded: the user controls frequency.
_Avoid_: notification, alert

## Two apps, one language contract

Cornerstone and the Journal are separate apps in separate repositories with a shared language contract — same tech-stack principles, no shared code, no borrowed words.

- **Cornerstone** (this repo) — a *proactive* readiness journal for small businesses. Its reserved words: pill, journey, path, HAVE, NEED, DESIRABLE, evidence, next action, readiness score, nudge.
- **Journal** (Stefano's personal app; its own repository to come) — a *silent, reactive* journal. Its reserved words: daily note, capture, 5Ws, people / places / things, conversation mode.

Rules:

1. Neither app borrows the other's reserved words. A Journal entry is never a "pill"; a Cornerstone prompt is never a "notification."
2. Shared words mean the same thing in both: *journal* (a dated record that compounds), *entry* (one unit of record), *proactive* vs. *silent* (whether the app speaks first).
3. Similar tech stack, separate codebases: local-first, Markdown-canonical, git-versioned. Neither repository depends on the other.
