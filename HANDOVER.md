# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Always fetch live `main` first. Before continuing the active work, read the root guides/README/handover plus the active-work README, Tamil audit records, assembled-Tamil audit/reader index, and the English translation plan. The source PDF remains controlling and must not be committed.

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

## Canonical verification freeze

**Do not mark any canonical page in this work as `verified`.**

Current canonical state:

- page records: **49 / 49**;
- `verified`: **0**;
- `needs-review`: **49**;
- verification freeze: **ACTIVE**.

The passed assembled Tamil layer and future English statuses are separate derived-layer states and must not change this freeze.

Known historical-form reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Confirmed historical corrections include `ஆவலைக்`, `நின்றார்`, `போகிறாயே`, the `நன்றாக` family, `விழுவேன் என்றானா?`, `வேலை மட்டுந்தானா?`, scan 33 `கண்ணாடி`, scan 43 `இளிச்சவாயனாக`, scan 46 `நானா ஆள்?`, and scan 47 `விட வேணா?`.

## Tamil source / assembly state

- source registration: complete;
- page map: **49 / 49**;
- canonical Tamil: **49 / 49**;
- dedicated full-source comparison: **COMPLETE — 49 / 49 directly reviewed**;
- assembled Tamil: **PASSED**;
- source PDF committed: **No**.

Source-printed internal headings, all within one continuous work:

1. scan 15 — `உத்தண்டி`;
2. scan 19 — `கண்ணம்மா`;
3. scan 32 — `குமுதா`;
4. scan 38 — `வீரன்`;
5. scan 45 — `உலகநாதர்`;
6. scan 46 — `கண்ணம்மா`.

Passed assembled reader:

1. `works/periya-idathup-pen/sections/01-opening.md` — scan 8 → scan 15 before `உத்தண்டி`;
2. `sections/02-uthandi.md` — scan 15 `உத்தண்டி` → scan 19 before `கண்ணம்மா`;
3. `sections/03-kannamma-first.md` — scan 19 first `கண்ணம்மா` → scan 31;
4. `sections/04-kumudha.md` — scans 32–37;
5. `sections/05-veeran.md` — scans 38–44;
6. `sections/06-ulaganathar.md` — scan 45;
7. `sections/07-kannamma-conclusion.md` — scans 46–49 + separate printer colophon.

Key Tamil records:

- `works/periya-idathup-pen/FULL_TAMIL_SOURCE_AUDIT.md`
- `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md`
- `works/periya-idathup-pen/ASSEMBLED_TAMIL_AUDIT.md`
- `works/periya-idathup-pen/sections/README.md`

## English translation plan — COMPLETE

Plan:

`works/periya-idathup-pen/translations/en/TRANSLATION_PLAN.md`

Planning index:

`works/periya-idathup-pen/translations/en/README.md`

Working English title:

**The Woman of the Great House**

This is provisional; Tamil `பெரிய இடத்துப் பெண்` remains authoritative.

### Authority hierarchy

1. controlling source scan;
2. canonical Tamil `pages/`;
3. passed assembled Tamil `sections/`;
4. English translation;
5. editorial/glossary metadata.

### Structural / viewpoint rule

The seven English reader files will mirror the seven Tamil assembled files. Character accounts must remain contradictory where the source is contradictory. Do **not** reconcile Veeran, Kannamma, Kumudha, Uthandi or Ulaganathar using knowledge from later sections.

### Planned English batches

- **Batch 1 — pilot:** `01-opening.md`, scan 8 → scan 15 before `உத்தண்டி`;
- **Batch 2:** `02-uthandi.md`, scan 15 heading → scan 19 before `கண்ணம்மா`;
- **Batch 3A:** first Kannamma section, scan 19 heading → scan 24;
- **Batch 3B:** same English section, scans 25–31;
- **Batch 4:** Kumudha, scans 32–37;
- **Batch 5:** Veeran, scans 38–44;
- **Batch 6:** Ulaganathar, scan 45;
- **Batch 7:** final Kannamma, scans 46–49.

### Translation policy highlights

- no summarising or literary modernization;
- preserve first-person voice, satire, melodrama, insults, religious/mythological comparisons and rhetorical repetition;
- source-specific/odd Tamil forms remain source-specific; if interpretation is uncertain, use cautious English and document the exact Tamil instead of inventing a normalized source;
- preserve scan provenance and audit-established joins through HTML comments;
- names: Ulaganathar, Kannamma, Uthandi, Kumudha / Kumudam, Veeran; `உலகநாத முதலியார்` → Ulaganatha Mudaliar when explicitly printed;
- kinship/status terms such as `அத்தான்`, `அண்ணி`, `தலையாரி`, `எஜமான்`, `எஜமானி` require controlled glossary decisions rather than automatic modern equivalents;
- social/moral/sexual terms including `கற்பு`, `பத்தினி`, `விபசாரி`, `வேசி`, `சீதனம்`, `கற்பழிக்கப்பட்டாள்` must not be softened or intensified beyond context;
- religious/mythological allusions must be translated only from what the source states, without importing outside narrative knowledge;
- canonical Tamil verification freeze remains unchanged even if English sections later become `reviewed` or `verified` at the English layer.

## Current stage

- Tamil source comparison: **COMPLETE**;
- assembled Tamil: **PASSED**;
- English translation plan: **COMPLETE**;
- translation planning README: **created**;
- `PROGRESS.md`: **not yet created**;
- `GLOSSARY.md`: **not yet created**;
- English prose: **NOT STARTED**;
- English sections drafted: **0 / 7**.

## Exact next activity

Begin **English Batch 1 — pilot translation of `works/periya-idathup-pen/sections/01-opening.md`**, covering scan 8 through scan 15 immediately before the source heading `உத்தண்டி`.

Required actions for Batch 1:

1. re-read `TRANSLATION_PLAN.md` and the Tamil `01-opening.md` before drafting;
2. create `translations/en/PROGRESS.md`;
3. create the initial `translations/en/GLOSSARY.md` from actual pilot decisions, not hypothetical dictionary entries;
4. create `translations/en/sections/01-opening.md` with source provenance;
5. translate every source paragraph / dialogue unit without omission or modernization;
6. source-check the pilot against canonical pages for scans 8–15 up to the heading boundary;
7. review title/status language, names, household/class terms, dialogue tone, rhetorical punctuation and initial glossary choices;
8. update durable status documents;
9. do not start Batch 2 until the pilot is source-checked/reviewed;
10. keep all 49 canonical pages `needs-review`.

---

## Completed prior work — புதையல்

`புதையல்` remains at its durable release state: 448/448 canonical records, 446 verified-complete, two physical-loss scans 223–224 `needs-review`, assembled Tamil complete, English verified, release-ready with those two qualifications.
