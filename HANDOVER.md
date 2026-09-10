# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Active work: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Do not reopen completed Tamil source/glyph/assembly gates without genuinely new direct-source evidence.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`

- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`
- bytes: **251,126,214**
- scans: **179**
- second edition: **1968**
- image-only
- do **not** commit the PDF.

## Durable Tamil state

- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **PASSED — Chapters 1–23 / 23 VERIFIED**;
- final assembled consistency gate: **PASSED — 0 unresolved / 0 canonical changes**.

Known literal discontinuities remain at scans 117→118, 122→123 and 156→157. Chapter 15 ends on scan 126; Chapter 16 opens cleanly on scan 127. Scan 179 contributes final narrative only in the reading layer.

## English planning state

Working English title: **_Friday_**.

- `translations/en/TRANSLATION_PLAN.md` — **COMPLETE**;
- English `README.md` — initialized;
- `PROGRESS.md` — initialized;
- `GLOSSARY.md` — initialized with seed consistency decisions;
- `sections/README.md` — planned 23-chapter inventory;
- `TRANSLATION_REVIEW.md` — initialized / **BLOCKED**;
- `RELEASE_REPORT.md` — initialized / **BLOCKED**;
- English chapter prose — **NOT STARTED — 0 / 23**.

Final English structure mirrors the Tamil chapters one-to-one. Batch 1 is a single-chapter pilot. Subsequent default batches contain at most three contiguous chapters unless the user explicitly authorizes a larger batch.

The plan requires source-bound readable English; no summarization; preservation of agency, dialogue, emotional/rhetorical force, religious/caste/social language and source oddities; page provenance; and no silent repair of the three known physical discontinuities.

## Batch map

1. Chapter 1 / scans 4–12 — **pilot / NEXT**;
2. Chapters 2–4 — scan 13 → scan 45 before centered `5`;
3. Chapters 5–7 — scan 45 after centered `5` → scan 68 before centered `8`;
4. Chapters 8–10 — scan 68 after centered `8` → scan 92 before centered `11`;
5. Chapters 11–13 — scan 92 after centered `11` → scan 115 before centered `14`;
6. Chapters 14–16 — scan 115 after centered `14` → scan 134 before centered `17`;
7. Chapters 17–19 — scan 134 after centered `17` → scan 154 before centered `20`;
8. Chapters 20–21 — scan 154 after centered `20` → scan 166 before centered `22`;
9. Chapters 22–23 — scan 166 after centered `22` → final narrative scan 179.

## Exact next activity

Run **English Batch 1 pilot — Chapter 1 only**.

Create:

`works/vellikkizhamai/translations/en/sections/01-chapter-01.md`

Source: PASSED Tamil `works/vellikkizhamai/sections/01-chapter-01.md`, scans **4–12**, with canonical `pages/` as source-check authority.

Requirements:

- translate all substantive Tamil content; no summary/omission;
- retain source provenance comments;
- preserve narrator voice, rhetorical questions, repetition, religious references and source punctuation force;
- source-check every English paragraph/dialogue unit against canonical Tamil pages;
- review readability without modernization;
- update `GLOSSARY.md` with locked pilot decisions;
- update `PROGRESS.md`, English/work/root status docs;
- commit the bounded pilot before Batch 2.