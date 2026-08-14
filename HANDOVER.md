# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- When resuming, verify current `main` before making changes.

## Mandatory startup

Before continuing:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read `works/balipeedam-nokki/README.md`.
4. Read `works/balipeedam-nokki/metadata/source.md`.
5. Read `works/balipeedam-nokki/indexes/page-map.md` and `audit.md`.
6. Read `works/balipeedam-nokki/sections/README.md`.
7. For English work, read `works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`, `README.md`, `PROGRESS.md`, and `GLOSSARY.md`.
8. Continue existing work; do not create duplicate structures.
9. Treat audited Tamil `pages/` as controlling textual authority; assembled `sections/` are for reading continuity.
10. Do **not** upload or commit the source PDF.

## Source identity

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**

External source filename:

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

- SHA-256: `c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`
- File size: 69,724,254 bytes
- Scan pages: 34
- First edition visible in scan: ஏப்ரல் 1947
- Publisher: எரிமலைப் பதிப்பகம், துறையூர்
- PDF in repository: **No**

## Critical structural rule

**`பலிபீடம் நோக்கி` is one continuous work.**

Never promote `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` to a separate work. It is the internal cinematic-historical sequence used by the same work.

Source flow:

1. scans 4–7 — opening ideological/polemical frame;
2. scan 7 — narrator introduces a film-like lesson;
3. scans 8–29 + opening of scan 30 — internal `ராயசம் வெங்கண்ணு` film sequence;
4. scan 30 — internal film reaches `வணக்கம்`, then `படம் முடிந்துவிட்டது...` returns to the main frame;
5. scans 31–33 — conclusion;
6. scan 34 — blank/back matter.

Every body page and English translation section remains under:

```text
work: balipeedam-nokki
```

## Tamil archival state — COMPLETE

- page records: **34 / 34**
- verified: **34 / 34**
- unresolved readings: **0**
- Tamil source audit: **PASSED**
- assembled Tamil reading layer: **PASSED**

Canonical source layer: `works/balipeedam-nokki/pages/`.

## Assembled Tamil layer — COMPLETE

- `sections/01-opening-frame.md` — scans 4–7
- `sections/02-rayasam-vengannu-sequence.md` — scans 8–29 + scan 30 through `வணக்கம்`
- `sections/03-return-and-conclusion.md` — scan 30 from `படம் முடிந்துவிட்டது...` through scan 33

Scan 30 is intentionally split at the work's own narrative boundary.

## English translation infrastructure

Working English title: **_Towards the Sacrificial Altar_**.

Existing files:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/README.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/sections/01-opening-frame.md`
- `translations/en/sections/02-rayasam-vengannu-sequence.md`

Whole-work `verified` status is reserved for final bilingual alignment after Batch 6.

## English batches completed

| Batch | Source | Status |
|---|---|---|
| 1 — opening frame | scans 4–7 | **reviewed** |
| 2 — internal title / Nayak court / battle | scans 8–13 | **reviewed** |
| 3 — Alagiri–Vengannu / Sengamaladasan | scans 14–20 | **reviewed** |
| 4 — Bijapur–Venkoji / restoration / ministership conflict | scans 21–26 | **reviewed** |
| 5 — final internal-film movement | scans 27–30 through `வணக்கம்` | **reviewed** |
| 6 — return and conclusion | scan 30 after `வணக்கம்` through 33 | **NEXT** |

## Batch 5 — COMPLETE + REVIEWED

Batch 5 was appended to the existing:

`works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md`

The internal cinematic sequence is therefore now **fully translated and reviewed from scan 8 through scan 30's `வணக்கம்` end-card**.

Batch-5 coverage includes:

- Vengannu's poisoned-feast claim to Venkoji;
- Venkoji's decision to seize Thanjavur;
- Maratha assault and burning Nayak flag;
- Sengamaladasan's hallucinated Vengannu heads;
- the crown / `பலிபீடம்` callback;
- Sengamaladasan's final collapse;
- `மராட்டிய சாம்ராஜ்யம் உதயம்` screen text;
- `வணக்கம்` end-card and Vengannu garlanding Venkoji.

### Batch-5 fidelity decisions

- scan 27 `ஒரு காரணம்!` → literal **a reason!**; do not silently replace it with a more expected scene-transition word;
- scan 28 `நானுக்கே` → contextual **I myself will muster our army**;
- `புலிக்கிர் வீரா` retained as *Pulikkir veera*;
- `வானவாணினம்` retained as *vanavaninam*;
- source `.????` punctuation retained literally;
- scan 29 `புத்த பூதம்` handled cautiously as **a new demon** and flagged for final bilingual review;
- `பட்டமும் கட்டும் — பலிபீடத்தையும் காட்டும்` preserves both crown and sacrificial-altar poles;
- scan 29→30 `அப்படித்` + `தத்தளிக்கிறான்` treated as one cross-page sentence;
- scan 30 `பசலுக்கு` retained as *pasalu*;
- `மராட்டிய சாம்ராஜ்யம் உதயம்` → **Rise of the Maratha Empire**;
- `வணக்கம்` → **Vanakkam** as the internal-film end-card.

Most importantly, **Batch 5 stops inside scan 30 at `வணக்கம்`.** It does not translate the following `படம் முடிந்துவிட்டது...` sentence.

## Next exact activity — Batch 6

Create:

`works/balipeedam-nokki/translations/en/sections/03-return-and-conclusion.md`

### Exact source boundary

Begin inside canonical scan/page 30 at:

`படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா?`

Continue through scan 33.

Do **not** repeat the preceding internal-film `வணக்கம்` end-card.

### Batch-6 requirements

1. Read canonical Tamil pages `0030`–`0033` before translating.
2. Begin exactly at `படம் முடிந்துவிட்டது...` on scan 30.
3. Translate every remaining substantive unit through scan 33; do not summarise.
4. Preserve the governing `பலிபீடம்` metaphor, repetitions, rhetorical questions, named people/institutions and political/religious polemical force.
5. Preserve the scan 30→31 page continuation beginning with the end of `கைகூப்புவதை...`.
6. Keep source-scan provenance visible.
7. Source-check the complete Batch-6 English against canonical pages `0030`–`0033`.
8. Update `GLOSSARY.md` only for genuinely new recurring decisions.
9. Update `PROGRESS.md`, readmes and this handover only after the Batch-6 review gate passes.
10. After Batch 6 is reviewed, create `translations/en/TRANSLATION_REVIEW.md` and perform final whole-work bilingual alignment across all English sections before setting whole-work English to `verified`.

## Final release gate

`TRANSLATION_REVIEW.md` must confirm:

- no omissions/additions;
- no altered agency or responsibility;
- no softened or intensified political rhetoric;
- consistent names and recurring terms;
- cinematic form preserved;
- scan-30 internal-film/main-frame transition intact;
- `ராயசம் வெங்கண்ணு` remains internal;
- audited Tamil remains authoritative.