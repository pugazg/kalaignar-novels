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
- `translations/en/sections/03-return-and-conclusion.md`

Whole-work `verified` status is reserved for final bilingual alignment.

## English batch status — ALL SIX REVIEWED

| Batch | Source | Status |
|---|---|---|
| 1 — opening frame | scans 4–7 | **reviewed** |
| 2 — internal title / Nayak court / battle | scans 8–13 | **reviewed** |
| 3 — Alagiri–Vengannu / Sengamaladasan | scans 14–20 | **reviewed** |
| 4 — Bijapur–Venkoji / restoration / ministership conflict | scans 21–26 | **reviewed** |
| 5 — final internal-film movement | scans 27–30 through `வணக்கம்` | **reviewed** |
| 6 — return and conclusion | scan 30 from `படம் முடிந்துவிட்டது...` through 33 | **reviewed** |

Complete English body-text coverage now runs from scan **4 through 33**.

## Batch 6 — COMPLETE + REVIEWED

Created:

`works/balipeedam-nokki/translations/en/sections/03-return-and-conclusion.md`

### Exact source boundary

The English section begins inside scan 30 at:

`படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா?`

The preceding internal-film `வணக்கம்` is **not repeated**. It remains only in English section 2.

### Batch-6 coverage

- explicit return from the internal film;
- repeated `பலிபீடம் நோக்குங்கள்` rhetoric;
- Cheran / Nayak / Rajaraja Chola / Kamban and pluralized named references;
- sacrificial-altar blood/foundation imagery;
- head / muscle / martial-ancestry passage;
- `பகுத்தறிவுச் சம்மட்டி` rationalist-hammer line;
- temples / agraharams / monasteries / epics / almanacs / afterlife concepts;
- repeated `இந்துமதந்தான்...` accusations;
- Manudharma / Shudras / capitalists / British imperialism passages;
- final religious-sword / sacrificial-altar destruction imagery;
- `படார்.. படார்..` sound effect;
- closing verse and floral ornament.

### Batch-6 fidelity decisions

- scan 30→31 `கைகூப்புவதை` + `யும்` preserved as one continuous sentence;
- `பலிபீடம்` → **sacrificial altar**; `ஆரிய பலிபீடம்` → **Aryan sacrificial altar**;
- `காமராஜர்கள் / கலியாணசுந்தரங்கள் / நாமக்கல்லார்கள்` kept as conservative pluralized English references rather than externally resolved identities;
- scan-31 unusual `வெட்டப்பட்டட்டும் / கிழித்தெறியப்பட்டட்டும் / கழிக்கப்பட்டட்டும்` left untouched in Tamil; English conveys immediate imperative sense;
- `பகுத்தறிவுச் சம்மட்டி` → **hammer of rationalism**;
- `சேரி` → *cheri*;
- `மனுதர்மம்` → **Manudharma**;
- `சூத்திரர்கள்` → **Shudras**;
- `செருப்பாண்டாலும் சரி` → **even if a sandal rules, so be it** without inserted explanatory gloss;
- `இந்துமதக் கொடுவாள்` → **cruel sword of Hinduism**;
- `மதக்கொடுவாள்` → **cruel sword of religion**;
- `படார்.. படார்..` → *padaar.. padaar..*;
- source closing `வாள்` repetition and `✾` ornament retained.

These decisions are recorded in `translations/en/GLOSSARY.md`.

## Current English state

- all six translation batches — **REVIEWED**
- all three English reading sections — **present and reviewed**
- complete English body-text coverage — **yes**
- internal film/main-frame scan-30 boundary — **preserved**
- whole-work English `verified` — **NO**

## Next exact activity — FINAL BILINGUAL REVIEW

Create:

`works/balipeedam-nokki/translations/en/TRANSLATION_REVIEW.md`

Then perform whole-work bilingual alignment across:

1. canonical Tamil page records `pages/0004` through `pages/0033`;
2. assembled Tamil sections 1–3;
3. English sections 1–3;
4. `GLOSSARY.md` terminology/source-oddity decisions;
5. the scan-30 intra-page boundary between sections 2 and 3.

### Required final checks

The review must explicitly confirm or correct:

- no substantive omissions;
- no additions presented as source content;
- no altered agency or responsibility;
- no softened political/religious/caste rhetoric;
- no intensified rhetoric beyond the Tamil;
- consistent names, titles and recurring terms;
- source oddities remain visible/documented rather than silently normalized;
- cinematic vocabulary and form remain intact;
- title-card and `வணக்கம்` end-card remain internal to the one work;
- scan 29→30 and scan 30→31 joins remain correct;
- `ராயசம் வெங்கண்ணு` remains internal, not a separate work;
- audited Tamil remains controlling authority.

### Items to revisit deliberately in final review

- Batch 5 cautious `புத்த பூதம்` → **a new demon**;
- any remaining transliterated source-bound forms such as *mitthanamathan*, *kilathirukkirathu*, *thegidu thaththakkar*, *Tharppakurar*, *Pulikkir veera*, *vanavaninam*, *pasalu*;
- Batch 6 pluralized named references;
- closing verse syntax and repeated `வாள்`.

Only after `TRANSLATION_REVIEW.md` passes may:

- all English sections be advanced to whole-work `verified`;
- `PROGRESS.md`, readmes and this handover state `verified`;
- a `RELEASE_REPORT.md` be created.

## Final release gate

No release is final until the bilingual review confirms the above and the repository still contains **no source PDF**.