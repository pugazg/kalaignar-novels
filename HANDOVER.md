# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Active work: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Do not reopen completed source/glyph gates without genuinely new direct-source evidence.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`

- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`
- bytes: **251,126,214**
- scans: **179**
- second edition: **1968**
- image-only
- do **not** commit the PDF.

## Durable source-layer state

- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- user-directed second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**.

## Assembled Tamil reading layer

- **IN PROGRESS — Chapters 1–20 / 23 VERIFIED**;
- Chapters 1–4 were completed in chapter-sized commits;
- Chapters 5–9 were assembled together under explicit user authorization;
- Chapters 10–19 were assembled together under explicit user authorization;
- Chapter 20 was assembled and verified in the default one-chapter workflow;
- assembled source coverage now reaches **scan 160 immediately before centered `21`**;
- canonical `pages/` remain controlling authority;
- no canonical page record changed during assembled-layer work;
- English remains **blocked** until all 23 chapters and the final assembled-layer consistency gate pass.

## Chapter 20 closure

Verified coverage: **scan 154 after centered `20` → scan 160 before centered `21`**.

The reading layer preserves reversible joins for scan 155 `சோலை` + scan 156 `யில்`, scan 157 `பயங்கரமாக—` → scan 158 `ஆனந்தியிருக்கும்`, scan 158 `வராத` + scan 159 `கண்ணீர்,`, and scan 159 `அழகப்பனுக்கும்` + scan 160 `ஒன்றும் புரியவில்லை.` The scan 156→157 discontinuity remains literal: `தலையிலும் காயம்` followed by `நயினா எதிர்த்தே அடிக்கவில்லை.` with no supplied punctuation or inferred repair.

Mixed boundary scans 154 and 160 were split at centered `20` and `21`. Chapter 20 assembly verification: **PASS — 0 unresolved / 0 canonical changes**.

## Assembly workflow

Derive only from audited canonical `pages/`, preserve reversible provenance, join only verified page continuities, and never normalize source wording merely for reading flow. The default is one chapter per iteration; process multiple chapters only when the user explicitly authorizes a larger batch.

## Exact next activity

Assemble and verify **Chapter 21** as:

`works/vellikkizhamai/sections/21-chapter-21.md`

Coverage: **scan 160 after centered `21` through scan 166 before centered `22`**. English remains blocked.
