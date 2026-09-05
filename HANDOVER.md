# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, fetch live `main` first and read the root guides/README/handover plus the active-work README, `audit.md`, `FULL_TAMIL_SOURCE_AUDIT.md`, `HISTORICAL_GLYPH_AUDIT.md`, `ASSEMBLED_TAMIL_AUDIT.md`, `sections/README.md`, translation plan/progress/glossary and relevant source/translation sections. The attached PDF remains controlling and must not be committed.

## பெரிய இடத்துப் பெண் — source identity

- source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`;
- SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`;
- size: **70,952,481 bytes**;
- scans: **49**;
- title: **பெரிய இடத்துப் பெண்**;
- author: **மு. கருணாநிதி**;
- publisher/place: **திராவிடன் பதிப்பகம் / வேலூர் (வ. ஆ.)**;
- edition: **எட்டாம் பதிப்பு: ஜூலை 1953**;
- price: **விலை 0—8—0**;
- sales rights: **எம். எஸ். ராஜுலு கம்பெனி, 286, சைனா பஜார், சென்னை-1**;
- final printer colophon: **ஸ்ரீமகள் அச்சகம், சென்னை-1**.

## Verification freeze

**Do not mark any canonical page in this work as `verified`.**

Known user-supplied Periyar-reform reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, punctuation or vocabulary.

The assembled Tamil layer's **PASSED** status and English-layer review states are independent of canonical verification. Canonical state remains **0 verified / 49 `needs-review`**.

## Historical-glyph checkpoint

Confirmed historical corrections include:

- scan 14 `ஆவலைக்`, `நின்றார்`;
- scan 16 `போகிறாயே`;
- scans 20–24 the corrected `நன்றாக` family and `விழுவேன் என்றானா?`;
- scan 25 `வேலை மட்டுந்தானா?`;
- scan 33 `கண்ணடி` → **`கண்ணாடி`** (`ணா`);
- scan 43 `இளிச்சவாயனுக` → **`இளிச்சவாயனாக`** (`னா`);
- scan 46 `நானு ஆள்?` → **`நானா ஆள்?`** (`னா`);
- scan 47 `விட வேணு?` → **`விட வேணா?`** (`ணா`).

The last four were discovered during the dedicated whole-work source audit by enlarged-pixel and same-edition comparison.

## Canonical / source-audit state

- page map: **49 / 49**;
- canonical page records: **49 / 49**;
- dedicated full-source audit: **COMPLETE — 49 / 49 directly reviewed**;
- remaining full-source audit coverage: **0**;
- source PDF committed: **No**.

Final-source continuities directly established include:

- scan 41 `கல்யா` + scan 42 `ணத்தை` → `கல்யாணத்தை`;
- scan 43 `கடவுள்` + scan 44 `பொறுப்பாரா?`;
- scan 46 `காரண` + scan 47 `மாயிருந்தேன்!` → `காரணமாயிருந்தேன்!`;
- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → `எழுதியிருந்தாள்.`;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...`.

Narrative ends at `...எங்களிடம் வரவேண்டும், தெரியுமா?`; separate printer colophon: `ஸ்ரீமகள் அச்சகம், சென்னை-1`.

## Structural observations

The source is one continuous work. Directly confirmed internal headings:

- scan 15 / printed 14 — `உத்தண்டி`;
- scan 19 / printed 18 — `கண்ணம்மா`;
- scan 32 / printed 31 — `குமுதா`;
- scan 38 / printed 37 — `வீரன்`;
- scan 45 / printed 44 — `உலகநாதர்`;
- scan 46 / printed 45 — `கண்ணம்மா`.

These are internal textual structure, not separate works.

## Assembled Tamil reading layer — PASSED

Reading-layer scope:

- scans **1–7** remain canonical front matter and are not duplicated into the continuous narrative reader;
- narrative assembled from scan **8 through scan 49**;
- scan-49 printer colophon retained separately as non-narrative source matter.

Files:

1. `works/periya-idathup-pen/sections/01-opening.md` — scan 8 → scan 15 before `உத்தண்டி`;
2. `works/periya-idathup-pen/sections/02-uthandi.md` — scan 15 `உத்தண்டி` → scan 19 before `கண்ணம்மா`;
3. `works/periya-idathup-pen/sections/03-kannamma-first.md` — scan 19 first `கண்ணம்மா` → scan 31;
4. `works/periya-idathup-pen/sections/04-kumudha.md` — scans 32–37;
5. `works/periya-idathup-pen/sections/05-veeran.md` — scans 38–44;
6. `works/periya-idathup-pen/sections/06-ulaganathar.md` — scan 45;
7. `works/periya-idathup-pen/sections/07-kannamma-conclusion.md` — scans 46–49 + colophon.

Assembly rules/results:

- derived only from final audited canonical pages;
- scan-15 and scan-19 mid-page heading transitions split without source duplication or omission;
- only source-audit-established boundary fragments joined;
- reversible HTML scan provenance retained;
- all source-specific wording and historical-glyph corrections carried through;
- canonical `pages/` files and statuses left unchanged;
- detailed check: `works/periya-idathup-pen/ASSEMBLED_TAMIL_AUDIT.md`;
- reader map/rules: `works/periya-idathup-pen/sections/README.md`;
- **ASSEMBLED TAMIL CONSISTENCY: PASSED**.

## English translation state

Working English title: **The Woman of the Great House**.

Authority hierarchy:

`source scan → canonical pages/ → assembled sections/ → English`

Translation control files:

- `works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md` — **COMPLETE**;
- `works/periya-idathup-pen/translations/en/README.md`;
- `works/periya-idathup-pen/translations/en/PROGRESS.md`;
- `works/periya-idathup-pen/translations/en/GLOSSARY.md`.

### Batch 1 — opening pilot

Source: `works/periya-idathup-pen/sections/01-opening.md` — scan 8 through scan 15 immediately before `உத்தண்டி`.

English:

`works/periya-idathup-pen/translations/en/sections/01-opening.md`

State:

- draft translation: **COMPLETE**;
- canonical source-check: **COMPLETE**;
- English review: **COMPLETE**;
- status: **REVIEWED**;
- final whole-work English `verified`: **not yet**;
- Tamil canonical correction triggered by pilot: **none**.

Pilot review:

`works/periya-idathup-pen/translations/en/BATCH_01_REVIEW.md`

Important locked pilot decisions:

- names: Ulaganathar, Kannamma/Kannammal, Veeran, Uthandi, Kumudha/Kumudam;
- `அத்தான்` retained as **Aththan** when important, with cross-cousin/prospective-husband gloss;
- `தலையாரி` retained as **talaiyari** rather than over-specifying an office;
- `மண்டிக்கடை` pilot: **Mandi Shop**;
- `நைவேத்தியம் / பிரசாதம்` → **naivedyam / prasadam** with controlled glossing;
- `ராஜபார்ட் / ஸ்திரீபார்ட்` → **king's part / female part**;
- source oddities are recorded, not silently normalized;
- `அந்த மகானுபாவன் மாதிரி பார்க்கக்கூட இல்லை` reviewed as **“this great soul was not even much to look at”** in context;
- source `சங்கார` and `வீரனத்திக்கு முக்காட` remain explicitly documented as cautious English decisions;
- scan provenance and established joins remain invisible HTML comments.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English sections drafted/source-checked/reviewed: **1 / 7**;
- English sections verified: **0 / 7**.

## Exact next activity

Translate **English Batch 2 — `உத்தண்டி`**.

Required range:

- Tamil assembled source: `works/periya-idathup-pen/sections/02-uthandi.md`;
- source starts at scan 15 / printed 14 heading `உத்தண்டி`;
- source ends on scan 19 immediately before heading `கண்ணம்மா`;
- canonical authority: corresponding page records in `works/periya-idathup-pen/pages/`.

Required workflow:

1. translate the complete Uthandi first-person account into `translations/en/sections/02-uthandi.md`;
2. preserve Uthandi's class/debt vocabulary and limited viewpoint without importing later narrator knowledge;
3. source-check every paragraph against canonical scans 15–19;
4. preserve established physical page joins, including scan 15 `தெரிந்` + scan 16 `தது.` and scan 18 `என்` + scan 19 `றேன்.`;
5. update `GLOSSARY.md` only for source-supported recurring decisions encountered in Uthandi's section;
6. update `PROGRESS.md`, translation README, work README/audit and this handover;
7. keep all Tamil canonical pages `needs-review` under the active freeze;
8. do not begin Kannamma Batch 3A until Batch 2 is source-checked and reviewed.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
