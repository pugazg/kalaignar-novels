# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, fetch live `main` first and read the root guides/README/handover plus the active-work README, `audit.md`, Tamil audit records, `ASSEMBLED_TAMIL_AUDIT.md`, `sections/README.md`, translation plan/progress/glossary, all completed batch reviews and relevant Tamil/English sections. The attached PDF remains controlling and must not be committed.

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
6. `translations/en/sections/06-ulaganathar.md` — scan 45 — **REVIEWED / PASS**; review `BATCH_06_REVIEW.md`.
7. `translations/en/sections/07-kannamma-conclusion.md` — scans 46–49 + separate printer colophon — **REVIEWED / PASS**; review `BATCH_07_REVIEW.md`.

### Batch 7 — final Kannamma controls

- complete final Kannamma account translated and source-checked against canonical scans 46–49;
- historical corrections `நானா ஆள்?` and `விட வேணா?` are reflected from the canonical layer;
- joins `காரணமாயிருந்தேன்!`, `எழுதியிருந்தாள்.` and `ஒரு பெரிய ஜோதி நிரந்தரமாக...` are retained with provenance;
- explicit source `கற்பழிக்கப்பட்டாள்` is translated directly as “was raped”;
- source-specific `வக்குப் பேதி` is retained as `vakkup-bethi` rather than silently normalized;
- Kannamma's concealment of the diamond evidence, destruction of Kumudha's letter, departure with Veeran, funeral-pyre scene and Calcutta/Indra-world boast are all represented;
- final narrative ending is kept separate from the printer colophon;
- later Kannamma disclosures do not retroactively rewrite earlier narrators;
- Tamil canonical correction triggered by Batch 7: **none**.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English sections drafted/source-checked/reviewed: **7 / 7**;
- English sections verified: **0 / 7**;
- translation batches completed through review: **8 / 8**.

## Exact next activity

Perform the **whole-work bilingual review**.

Required scope:

- English Sections 01–07;
- passed assembled Tamil Sections 01–07;
- canonical page records as final textual authority where a wording or boundary question arises.

Required workflow:

1. confirm complete narrative coverage with no English omission or duplication;
2. confirm all source-printed section transitions and final section ordering;
3. audit narrator isolation across Uthandi, Kannamma, Kumudha, Veeran and Ulaganathar;
4. reconcile recurring English terminology only where source meaning and speaker context permit it—do not flatten speaker-specific language;
5. check names, kinship/address forms, class/debt vocabulary, moral/sexual vocabulary, religious/mythological allusions and source-specific period terms;
6. check paragraphing, punctuation, reversible HTML provenance and all established page joins;
7. check the final narrative ending and separate printer colophon;
8. record a dedicated whole-work bilingual review result;
9. only after a PASS decide whether English sections may be promoted to `verified`;
10. keep all canonical Tamil pages `needs-review` under the active freeze regardless of English outcome.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
