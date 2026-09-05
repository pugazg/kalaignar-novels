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
6. `translations/en/sections/06-ulaganathar.md` — scan 45 — **REVIEWED / PASS**; review `BATCH_06_REVIEW.md`.

### Batch 6 — Ulaganathar controls

- complete source-printed scan-45 account translated and source-checked;
- Ulaganathar's wounded pride, accusation and family-honour rhetoric remain his viewpoint;
- his `குமுதாவைக் காதலித்தது` is translated as his own self-description and is not harmonised with Kumudha's preceding testimony or Kannamma's later conclusion;
- `என் உப்பைத்தின்றவன்` is preserved as “the man who ate my salt”;
- unusual source punctuation `எல்லாம் அந்தத் தடவை செய்த வேலை. கண்ணம்மா.` is not silently repaired;
- `பசப்பு வார்த்தை`, `கள்ளி`, and `பத்திர காளி` are translated cautiously and documented in the Batch 6 review;
- no scan-46 Kannamma text was pulled into Section 06;
- Tamil canonical correction triggered by Batch 6: **none**.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English sections drafted/source-checked/reviewed: **6 / 7**;
- English sections verified: **0 / 7**;
- translation batches completed through review: **7 / 8**.

## Exact next activity

Translate **English Batch 7 — final `கண்ணம்மா` conclusion**.

Required range:

- Tamil assembled source: `works/periya-idathup-pen/sections/07-kannamma-conclusion.md`;
- source scope: **scans 46–49**, from the source heading `கண்ணம்மா` through the final narrative ending, with the printer colophon retained separately;
- canonical authority: scans 46–49 in `works/periya-idathup-pen/pages/`.

Required workflow:

1. translate the complete final Kannamma account into `translations/en/sections/07-kannamma-conclusion.md`;
2. preserve Kannamma's final explanation as her viewpoint while respecting the already-established narrator-isolation policy;
3. source-check the corrected historical forms on scans 46–47, including `நானா ஆள்?` and `விட வேணா?`;
4. preserve the audited joins scan 46→47 `காரணமாயிருந்தேன்!`, scan 47→48 `எழுதியிருந்தாள்.`, and scan 48→49 `ஒரு பெரிய ஜோதி நிரந்தரமாக...`;
5. preserve the final narrative ending and separate printer colophon;
6. create Batch 7 review and synchronize progress/status docs;
7. keep all canonical Tamil pages `needs-review` under the active freeze;
8. after Batch 7 review, perform whole-work bilingual review before any English `verified` decision.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
