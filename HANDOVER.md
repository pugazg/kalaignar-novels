# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, fetch live `main` first and read the root guides/README/handover plus the active-work README, `audit.md`, Tamil audit records, `ASSEMBLED_TAMIL_AUDIT.md`, `sections/README.md`, translation plan/progress/glossary, completed batch reviews and relevant source/translation sections. The attached PDF remains controlling and must not be committed.

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

## Canonical / Tamil state

- page map: **49 / 49**;
- canonical page records: **49 / 49**;
- dedicated full-source audit: **COMPLETE — 49 / 49 directly reviewed**;
- assembled Tamil: **PASSED**;
- source PDF committed: **No**.

Confirmed historical corrections include scan 14 `ஆவலைக்`, `நின்றார்`; scan 16 `போகிறாயே`; corrected `நன்றாக` family; scan 25 `வேலை மட்டுந்தானா?`; scan 33 `கண்ணாடி`; scan 43 `இளிச்சவாயனாக`; scan 46 `நானா ஆள்?`; scan 47 `விட வேணா?`.

The source is one continuous work. Internal headings:

- scan 15 — `உத்தண்டி`;
- scan 19 — `கண்ணம்மா`;
- scan 32 — `குமுதா`;
- scan 38 — `வீரன்`;
- scan 45 — `உலகநாதர்`;
- scan 46 — `கண்ணம்மா`.

Assembled Tamil files:

1. `sections/01-opening.md`;
2. `sections/02-uthandi.md`;
3. `sections/03-kannamma-first.md`;
4. `sections/04-kumudha.md`;
5. `sections/05-veeran.md`;
6. `sections/06-ulaganathar.md`;
7. `sections/07-kannamma-conclusion.md`.

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

- source: `sections/01-opening.md`, scans 8–15 before `உத்தண்டி`;
- English: `translations/en/sections/01-opening.md`;
- status: **REVIEWED / PASS**;
- review: `translations/en/BATCH_01_REVIEW.md`;
- Tamil canonical correction triggered: **none**.

### Batch 2 — Uthandi

- source: `sections/02-uthandi.md`;
- range: scan 15 `உத்தண்டி` heading through scan 19 immediately before `கண்ணம்மா`;
- English: `translations/en/sections/02-uthandi.md`;
- status: **REVIEWED / PASS**;
- review: `translations/en/BATCH_02_REVIEW.md`;
- Tamil canonical correction triggered: **none**.

Batch 2 source-check confirmed:

- hereditary servitude, Ulaganathar's mortgage/debt leverage, 500-rupee debt, maid proposal and twenty-rupee wage represented;
- Uthandi's marriage/dowry plan, Kumudha's reluctance, his later remorse and final accusation represented;
- established boundaries retained: scan 15→16 `தெரிந்தது.`, scan 16→17 `நம் வீட்டு`, scan 17→18 `கண்டது போலத்தானே!`, scan 18→19 `என்றேன்.`;
- `தலையாரி` → `talaiyari`;
- `நம் வீட்டு அண்ணி` → `our house's Anni` with glossary control;
- `விபசாரி` → `adulteress` in Uthandi's accusation context;
- `பசீர்`, `சப்பைக்கட்டுகள்`, `கபோதி`, `செக்கச் செவேல்`, `பாழும்` handled cautiously and documented;
- the scan-19 `கண்ணம்மா` heading / first-person text was not pulled into Batch 2.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English sections drafted/source-checked/reviewed: **2 / 7**;
- English sections verified: **0 / 7**;
- translation batches completed through review: **2 / 8**.

## Exact next activity

Translate **English Batch 3A — first `கண்ணம்மா` account**.

Required range:

- Tamil assembled source: `works/periya-idathup-pen/sections/03-kannamma-first.md`;
- source starts at scan 19 / printed 18 heading `கண்ணம்மா`;
- Batch 3A stops at the end of scan 24;
- canonical authority: scans 19–24 in `works/periya-idathup-pen/pages/`.

Required workflow:

1. translate Batch 3A into `translations/en/sections/03-kannamma-first.md` without pulling in scans 25–31 yet;
2. preserve Kannamma's self-justifying first-person rhetoric, moral claims, religious vocabulary and contradictions as her viewpoint;
3. do **not** reconcile her account with Uthandi, Kumudha, Veeran or the later Kannamma conclusion;
4. source-check every paragraph and established page join against canonical scans 19–24;
5. update glossary only for recurring source-supported decisions actually encountered;
6. create a Batch 3A review record and update progress/status docs;
7. keep all canonical Tamil pages `needs-review` under the active freeze;
8. do not begin Batch 3B until Batch 3A is source-checked and reviewed.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
