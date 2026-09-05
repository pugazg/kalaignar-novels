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

### Reviewed English sections

1. `translations/en/sections/01-opening.md` — scans 8–15 before `உத்தண்டி` — **REVIEWED / PASS**; review `BATCH_01_REVIEW.md`.
2. `translations/en/sections/02-uthandi.md` — scan 15 `உத்தண்டி` through scan 19 before `கண்ணம்மா` — **REVIEWED / PASS**; review `BATCH_02_REVIEW.md`.
3. `translations/en/sections/03-kannamma-first.md` — scan 19 first `கண்ணம்மா` through scan 31 — **REVIEWED / PASS**; planned Batches **3A + 3B** both complete; review `BATCH_03_REVIEW.md`.
4. `translations/en/sections/04-kumudha.md` — scans 32–37 — **REVIEWED / PASS**; review `BATCH_04_REVIEW.md`.
5. `translations/en/sections/05-veeran.md` — scans 38–44 — **REVIEWED / PASS**; review `BATCH_05_REVIEW.md`.

### Controls established through Sections 03–05

- first Kannamma account preserves her own self-justifying religious/moral rhetoric, marriage grievance, Veeran relationship, pregnancy termination and scheme against Kumudha; it is not harmonised with later testimony;
- Kumudha's signed statement preserves her letter form, coercion/violation account, Ramayana/Nalayini comparisons, diamond ingestion and final social plea;
- Veeran's section preserves his **limited and contradictory interpretation** of Kumudha. His accusations are not corrected inside his own prose using Kumudha's statement or the later Kannamma conclusion;
- harsher `வேசி / தாசி` invective is distinguished from `விபசாரி` in the glossary and remains attributed to the speaker;
- source-specific difficult forms remain documented rather than silently normalised;
- source-supported physical joins through scan 44 remain traceable in HTML comments;
- canonical historical corrections, including scan 33 `கண்ணாடி` and scan 43 `இளிச்சவாயனாக`, are reflected in the English from final Tamil readings;
- Tamil canonical corrections triggered by English Sections 01–05: **none**.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English sections drafted/source-checked/reviewed: **5 / 7**;
- English sections verified: **0 / 7**;
- translation batches completed through review: **6 / 8**.

## Exact next activity

Translate **English Batch 6 — `உலகநாதர்`**.

Required range:

- Tamil assembled source: `works/periya-idathup-pen/sections/06-ulaganathar.md`;
- source scope: **scan 45 / printed page 44**, from the source heading `உலகநாதர்` through the complete account immediately before the scan-46 `கண்ணம்மா` heading;
- canonical authority: `works/periya-idathup-pen/pages/0045-periya-idathup-pen-38.md`.

Required workflow:

1. translate the complete Ulaganathar first-person account into `translations/en/sections/06-ulaganathar.md`;
2. preserve Ulaganathar's accusation, wounded pride and limited knowledge as **his viewpoint**;
3. do not silently correct his interpretation using the later Kannamma conclusion;
4. source-check the entire account against canonical scan 45;
5. update glossary only for recurring decisions actually encountered;
6. create a Batch 6 review record and update progress/status docs;
7. keep all canonical Tamil pages `needs-review` under the active freeze;
8. do not begin Batch 7 until Batch 6 is source-checked and reviewed.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
