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

Important source readings that must not be silently normalized include:

- scan 3 — `பேனுப் பிடிக்கும்`
- scan 10 — `மித்தானமத்தனுக்குக்`
- scan 13 — `முச்சுற்றுப்படுத்திருக்கும்`
- scan 21 — `மளமள வென்று`; `என்றுன் பேதை!`
- scan 23 — `களேபாரப்படுகிறது`
- scan 26 — `தர்ப்பாகூரர்`; `விபரீதத்தை ஏற்கத்`
- scan 27 — `ஒரு காரணம்!`

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

Whole-work `verified` status is reserved for final bilingual alignment after all six batches.

## Completed English batches

### Batch 1 — scans 4–7 — REVIEWED

Opening frame translated and reviewed in `translations/en/sections/01-opening-frame.md`. Pilot terminology/style lock established in `GLOSSARY.md`.

### Batch 2 — scans 8–13 — REVIEWED

Internal title-card / Nayak-court / battle sequence translated and source-checked in `translations/en/sections/02-rayasam-vengannu-sequence.md`.

### Batch 3 — scans 14–20 — REVIEWED

Appended to the same internal-sequence file and source-checked against canonical Tamil pages 0014–0020. Coverage includes the Alagiri–Vengannu treasure dispute, their rupture, the Nagai sequence, discovery of Sengamaladasan, foster-family revelation and his decision to reclaim the kingdom.

### Batch 4 — scans 21–26 — REVIEWED

Appended to the **same** `translations/en/sections/02-rayasam-vengannu-sequence.md` and source-checked against canonical Tamil pages 0021–0026.

Coverage includes:

- Vengannu's appeal to the Sultan of Bijapur;
- Shahji's son Venkoji being sent with an army;
- Sengamaladasan's restoration and Alagiri's fall;
- temple/victory sequence at Pragadeeswarar;
- sixteen lakh *poovaragans* and tax-revenue reward to Venkoji;
- Sengamaladasan's plan to make his foster father minister;
- Vengannu's ministership demand and rupture with Sengamaladasan;
- Vengannu's threat and departure;
- Mahamaham Tank / Kudanthai transition and street dialogue about Venkoji.

Batch-4 fidelity decisions:

- `மளமள வென்று` → **in rapid succession**;
- `என்றுன் பேதை!` → contextual **The fool says Bijapur is but a speck of dust to him!** without changing the Tamil;
- `வெங்காஜி` → **Venkoji**; `ஷாஜி` → **Shahji**; `பீஜபூர்` → **Bijapur**;
- `விசுவரூப` → **Visvarupa** in the screen metaphor;
- `களேபாரப்படுகிறது` → cautious **erupts into commotion**;
- `பூவராகன்` → *poovaragan*, no currency conversion;
- `மன்னுக்கியது` → contextual **who made you king**;
- `தர்ப்பாகூரர்` → retained as *Tharppakurar*;
- `விபரீதத்தை ஏற்கத்` → **be ready to face the calamity**;
- `தீவணங்குகிறான்` → conservative **bows**;
- `காற்று முறிந்து` → cautious **breaks in the air and falls**;
- `குடந்தை` remains **Kudanthai** while `கும்பகோணம்` remains **Kumbakonam**.

All of these are recorded in `translations/en/GLOSSARY.md` and `PROGRESS.md`.

## Translation batch status

| Batch | Source | Status |
|---|---|---|
| 1 — pilot opening frame | scans 4–7 | **reviewed** |
| 2 — title card / Nayak court / battle | scans 8–13 | **reviewed** |
| 3 — Alagiri–Vengannu / Sengamaladasan | scans 14–20 | **reviewed** |
| 4 — Bijapur–Venkoji / restoration / ministership conflict | scans 21–26 | **reviewed** |
| 5 — final internal-film movement | scans 27–30 through `வணக்கம்` | **NEXT** |
| 6 — return and conclusion | scan 30 from `படம் முடிந்துவிட்டது...` through 33 | not-started |

## Next exact activity — Batch 5

Translate **scans 27–30 only through the internal film's `வணக்கம்` end-card** by appending to:

`works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md`

### Batch-5 requirements

1. Do not create a new work or a new internal-sequence file.
2. Read canonical Tamil pages `0027`, `0028`, `0029`, and `0030` before translating.
3. Translate every substantive unit from scan 27 through the `வணக்கம்` end-card on scan 30.
4. **Stop exactly at `வணக்கம்`.** Do not translate the following `படம் முடிந்துவிட்டது...` passage in Batch 5.
5. The `படம் முடிந்துவிட்டது...` passage begins Batch 6 and belongs in a new `translations/en/sections/03-return-and-conclusion.md` file.
6. Preserve dialogue, cinematic movement, screen text, sound effects and source punctuation.
7. Pay particular attention to the verified scan-27 source form `ஒரு காரணம்!`; do not silently normalize it.
8. Keep source-scan provenance visible and explicitly document the intra-page split on scan 30.
9. After drafting, source-check against canonical Tamil pages 0027–0030.
10. Update `GLOSSARY.md` only for genuinely new recurring/source-bound choices.
11. Advance `PROGRESS.md`, readmes and this handover only after Batch 5 passes its review gate.
12. Do not begin Batch 6 until that gate is satisfied.

## Final release gate

No English translation is final until all batches are complete and `TRANSLATION_REVIEW.md` confirms:

- no omissions/additions;
- no altered agency or responsibility;
- no softened or intensified political rhetoric;
- consistent names and recurring terms;
- cinematic form preserved;
- scan-30 internal-film/main-frame transition intact;
- `ராயசம் வெங்கண்ணு` remains internal;
- audited Tamil remains authoritative.