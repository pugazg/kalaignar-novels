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
- user-directed second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **PASSED — Chapters 1–23 / 23 VERIFIED**;
- final assembled consistency gate: **PASSED — 0 unresolved / 0 canonical changes**.

## Final assembled Tamil gate closure

The gate confirmed exactly 23 chapter section files, contiguous coverage from scan 4 through final narrative scan 179, correct centered-heading splits, source-supported reversible joins, preservation of literal source discontinuities and source oddities, exclusion of printer/signature marks and non-body visual/later-handwritten material, and canonical-authority integrity.

Important preserved discontinuities remain:

- scan 117→118: `உட்` → `எவ்வளவோ முயன்றும் நடக்கவில்லை.`;
- scan 122→123: `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`;
- scan 156→157: `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`.

Chapter 15 ends on scan **126**; Chapter 16 opens cleanly on centered `16` at scan **127**.

Repository comparison from passed source-audit checkpoint `591fe29f7ce6bb7f814f165b757098e89fe25aa5` through completed assembly head `52d7dcd9d6c5d561ca14f69fd850d37a55963310` shows **no canonical `works/vellikkizhamai/pages/` changes** during assembly.

## English state

English prose is **NOT STARTED**.

The Tamil gates now permit translation planning, but `NOVEL_PROCESSING_GUIDE.md` requires a mandatory plan before any English prose.

## Exact next activity

Create:

`works/vellikkizhamai/translations/en/TRANSLATION_PLAN.md`

The plan must define at minimum:

- working English title;
- source authority hierarchy;
- chapter/section and batch plan;
- translation style;
- name/transliteration policy;
- political, religious and caste terminology policy;
- historical office / ritual term handling;
- punctuation and dialogue policy;
- source oddity policy;
- page/source traceability;
- review states and gates.

Do **not** begin English prose in that same planning iteration.