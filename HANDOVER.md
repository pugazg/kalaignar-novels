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

Known literal discontinuities remain at scans 117→118, 122→123 and 156→157. Chapter 15 ends on scan 126; Chapter 16 begins on scan 127. Scan 179 contributes final narrative only in the reading layer.

## English translation state

Working English title: **_Friday_**.

- translation plan — **COMPLETE**;
- Chapter 1 / scans 4–12 — **REVIEWED**;
- Chapter 2 / scans 13–22 — **REVIEWED**;
- Chapter 3 / scan 23 through scan 33 before centered `4` — **REVIEWED**;
- Chapter 4 / scan 33 after centered `4` through scan 45 before centered `5` — **REVIEWED**;
- English chapters present/reviewed — **4 / 23**;
- current English coverage — **scan 4 through scan 45 before centered `5`**;
- whole-work English — **NOT VERIFIED**;
- final bilingual review — **BLOCKED**;
- release report — **BLOCKED**.

Batch 2 preserved the source's mixed scan-33 Chapter 3→4 boundary and mixed scan-45 Chapter 4→5 boundary. No Chapter 5 English prose has started. Batch 2 produced **0 canonical Tamil changes** and **0 unresolved English holds**.

`translations/en/GLOSSARY.md` now locks Batch 2 choices for Azhagappan/Azhagu, Sivanesar, Sivakami, Anandi, Naina Muhammad/Naina, Tiger, Vembu, Balagangadhara Thevar, Chapter 2 mythological/literary names, `paladai`, `kendi`, `minor`, `gosha`, `Sanatana Hindu`, `panchangam`, `dosha`, `sastras`, and the source-bound Chapter 3 assault/chastity terminology.

## English batch map

1. Chapter 1 / scans 4–12 — **REVIEWED**;
2. Chapters 2–4 / scan 13 → scan 45 before centered `5` — **REVIEWED**;
3. Chapters 5–7 / scan 45 after centered `5` → scan 68 before centered `8` — **NEXT**;
4. Chapters 8–10 / scan 68 after centered `8` → scan 92 before centered `11`;
5. Chapters 11–13 / scan 92 after centered `11` → scan 115 before centered `14`;
6. Chapters 14–16 / scan 115 after centered `14` → scan 134 before centered `17`;
7. Chapters 17–19 / scan 134 after centered `17` → scan 154 before centered `20`;
8. Chapters 20–21 / scan 154 after centered `20` → scan 166 before centered `22`;
9. Chapters 22–23 / scan 166 after centered `22` → final narrative scan 179.

## Exact next activity

Run **English Batch 3 — Chapters 5–7**.

Create and fully review:

- `works/vellikkizhamai/translations/en/sections/05-chapter-05.md` — scan 45 after centered `5` through scan 51;
- `works/vellikkizhamai/translations/en/sections/06-chapter-06.md` — scan 52 through scan 59 before centered `7`;
- `works/vellikkizhamai/translations/en/sections/07-chapter-07.md` — scan 59 after centered `7` through scan 68 before centered `8`.

Use PASSED Tamil sections for continuity and canonical `pages/` as source authority. Preserve source force, provenance and glossary decisions. Commit the bounded batch before moving on. **Do not start Chapter 8 in the same default iteration.**