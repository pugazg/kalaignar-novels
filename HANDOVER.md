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

## Batch 1 — COMPLETE + REVIEWED

Source: scans **4–7**.  
English: `translations/en/sections/01-opening-frame.md`.  
Status: **reviewed**.

Pilot terminology/style lock is recorded in `GLOSSARY.md`, including `பலிபீடம்` → **sacrificial altar**, `ஆரியம்` → **Aryanism** when ideological, `தன்மானம்` → **self-respect**, `மறம்` → **valour**, `கொற்றம்` → **triumph**, and source-bound treatment of `குதுமன்றி`, `விருதா`, `மஹா கனம்`, `அன்பு(?)`.

## Batch 2 — COMPLETE + REVIEWED

Source: scans **8–13**.  
English: `translations/en/sections/02-rayasam-vengannu-sequence.md`.  
Status for current coverage: **reviewed**.

Batch 2 includes:

- internal `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` title card;
- `எரிமலை ‘ரிலீஸ்’`, direction/screenplay/dialogue/distribution credits;
- Kumar Tatacharya palanquin/durbar entrance;
- Vijayaraghava–Mannaru marriage/war discussion;
- blessing and battle transition;
- deaths of Mannaru, Vijayaraghava and the queen;
- Vijayaraghava dying speech across scans 12→13;
- palace fire sequence and Sengamaladasan's escape.

### Batch-2 fidelity decisions

- no substantive paragraph, dialogue turn, action direction or cinematic unit omitted;
- `ராயசம் வெங்கண்ணு` remains explicitly internal to the one work;
- scan 10 `மித்தானமத்தனுக்குக்` retained as *mitthanamathan*, not guessed;
- scan 13 `முச்சுற்றுப்படுத்திருக்கும்` documented; English uses cautious contextual **encircling it**;
- `கன்னிகாதானம்` → *kanyadanam*;
- `சந்தர்ப்பணம்` → *santharpanam*;
- `அக்கிரகாரம்` → *agraharam*;
- `குளோசப்` → **close-up**;
- source sound effects and bracketed directions remain visible;
- open quotation continuity scan 10→11 and 12→13 preserved.

`GLOSSARY.md` has been updated with these decisions and Batch-2 names/film vocabulary.

## Translation batch status

| Batch | Source | Status |
|---|---|---|
| 1 — pilot opening frame | scans 4–7 | **reviewed** |
| 2 — title card / Nayak court / battle | scans 8–13 | **reviewed** |
| 3 — Alagiri–Vengannu / Sengamaladasan | scans 14–20 | **NEXT** |
| 4 — Bijapur–Venkoji / restoration / ministership conflict | scans 21–26 | not-started |
| 5 — final internal-film movement | scans 27–30 through `வணக்கம்` | not-started |
| 6 — return and conclusion | scan 30 from `படம் முடிந்துவிட்டது...` through 33 | not-started |

## Next exact activity — Batch 3

Translate **scans 14–20** by **appending to the existing**:

`works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md`

### Batch-3 requirements

1. Do not create a new work or a new internal-sequence file.
2. Read canonical Tamil pages `0014` through `0020` before translating.
3. Append every substantive unit from scans 14–20; do not summarise.
4. Preserve dialogue, bracketed directions, scene/screen movement, sound effects and rhetorical tone.
5. Preserve source oddities rather than reconstructing them from history or grammar.
6. Keep source-scan provenance comments visible.
7. After drafting, compare the appended English against canonical Tamil pages `0014`–`0020`.
8. Update `GLOSSARY.md` only for genuinely new recurring choices.
9. Advance `PROGRESS.md`, readmes and this handover only after Batch 3 passes the source check.
10. Do not begin Batch 4 until that gate is satisfied.

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
