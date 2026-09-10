# Next Chat Prompt — வெள்ளிக்கிழமை / assembled Tamil Chapter 5

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Durable state

- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **IN PROGRESS — Chapters 1–4 / 23 VERIFIED**;
- assembled source coverage reaches **scan 45 before centered `5`**;
- English: **blocked until assembled Tamil passes its final consistency gate**.

Do not reopen completed source/glyph work without genuinely new direct-source evidence.

## Completed assembly

- `sections/01-chapter-01.md` — scans 4–12 — VERIFIED;
- `sections/02-chapter-02.md` — scans 13–22 — VERIFIED;
- `sections/03-chapter-03.md` — scan 23 through scan 33 before centered `4` — VERIFIED;
- `sections/04-chapter-04.md` — scan 33 after centered `4` through scan 45 before centered `5` — VERIFIED.

Chapter 4 preserves canonical source oddities and verified joins. Scan 45 is split at centered `5`; only pre-heading text is in Chapter 4. No canonical page record changed during assembly.

## Assembly rules

1. Derive assembled prose only from verified canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical and colloquial forms.
3. Exclude audit notes, printer/signature marks, illustration descriptions and later handwriting.
4. Retain reversible source provenance with HTML comments.
5. Join only already-verified page-boundary continuities; never repair grammar by inference.
6. Split mixed boundary scans at the source-printed centered chapter heading.
7. Canonical `pages/` remain controlling authority and must not be edited merely for reading-flow smoothness.
8. One source chapter per iteration / commit.
9. English remains blocked until all 23 assembled chapters and the final consistency gate pass.

## Exact next activity

Create and verify **Chapter 5 only**:

`works/vellikkizhamai/sections/05-chapter-05.md`

Coverage: **scan 45 after centered `5` through scan 51**.

Then synchronize `sections/README.md`, work `README.md`, `audit.md`, `HANDOVER.md`, this prompt and `indexes/page-map.md` to **5 / 23**. Do not begin Chapter 6 or English in the same iteration.
