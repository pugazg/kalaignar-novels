# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, fetch live `main` first and read the root guides/README/handover plus the active-work README, `audit.md`, Tamil audit records, `ASSEMBLED_TAMIL_AUDIT.md`, `sections/README.md`, translation plan/progress/glossary, all batch reviews, `TRANSLATION_REVIEW.md` and relevant Tamil/English sections. The attached PDF remains controlling and must not be committed.

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

Canonical state remains **0 verified / 49 `needs-review`**. The assembled Tamil layer's **PASSED** status and English whole-work **VERIFIED** status are independent of that freeze.

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
- `works/periya-idathup-pen/translations/en/GLOSSARY.md`;
- `works/periya-idathup-pen/translations/en/TRANSLATION_REVIEW.md` — **PASSED / ENGLISH VERIFIED**.

### English section / batch state

1. `translations/en/sections/01-opening.md` — **REVIEWED / PASS**.
2. `translations/en/sections/02-uthandi.md` — **REVIEWED / PASS**.
3. `translations/en/sections/03-kannamma-first.md` — Batches 3A + 3B — **REVIEWED / PASS**.
4. `translations/en/sections/04-kumudha.md` — **REVIEWED / PASS**.
5. `translations/en/sections/05-veeran.md` — **REVIEWED / PASS**.
6. `translations/en/sections/06-ulaganathar.md` — **REVIEWED / PASS**.
7. `translations/en/sections/07-kannamma-conclusion.md` — **REVIEWED / PASS**.

All **8 / 8** planned translation batches are reviewed. Section files retain batch-level `reviewed`; whole-work status is **VERIFIED** through the completed `TRANSLATION_REVIEW.md` cross-section alignment.

### Final bilingual review controls

The final review confirmed:

- no substantive omission/duplication across scans 8–49;
- source-printed section order and transitions preserved;
- narrator isolation preserved across Uthandi, both Kannamma accounts, Kumudha, Veeran and Ulaganathar;
- Veeran's contradictory interpretation is not retroactively rewritten from Kumudha or final Kannamma evidence;
- Ulaganathar's `குமுதாவைக் காதலித்தது` remains his own self-description;
- names, `Aththan`, `Anni`, `talaiyari`, Calcutta, class/debt and moral/sexual terminology remain controlled;
- final `கற்பழிக்கப்பட்டாள்` is translated directly as “was raped”;
- religious/mythological rhetoric remains source-bound;
- source-specific difficult forms remain documented/cautious, not normalized;
- page joins and provenance remain intact;
- final narrative ending remains separate from the printer colophon.

One English-only consistency correction was made during final review: scan-49 `ரதி` is now **Rati**, replacing the earlier **Rathi** romanisation and matching `TRANSLATION_PLAN.md`. No Tamil text changed.

## Current stage

- source registration: complete;
- canonical Tamil: **49 / 49**;
- full Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- canonical `verified`: **0**;
- canonical `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- English translation plan: **COMPLETE**;
- English section files: **7 / 7 reviewed**;
- translation batches: **8 / 8 reviewed**;
- final bilingual review: **PASSED**;
- **whole-work English: VERIFIED**;
- release report: **not yet created**.

## Exact next activity

Create `works/periya-idathup-pen/translations/en/RELEASE_REPORT.md` and perform a release-readiness pass.

Required workflow:

1. verify all reader-facing English navigation targets and control-document links;
2. verify root/work/English README and handover status synchronization;
3. confirm source PDF remains excluded from the repository;
4. state clearly that English is whole-work **VERIFIED**;
5. carry the canonical Tamil qualification **0 verified / 49 `needs-review` — verification freeze ACTIVE**;
6. do not call the full archival package unqualified release-ready while that freeze remains active;
7. distinguish editorial/archival release-readiness from copyright/licensing/republication rights;
8. preserve live `main` as authoritative and do not change Tamil page statuses.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
