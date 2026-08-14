# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Verify current `main` before further changes.

## Mandatory startup

Before continuing:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read `works/balipeedam-nokki/README.md`.
4. Read `works/balipeedam-nokki/metadata/source.md`.
5. Read `works/balipeedam-nokki/indexes/page-map.md` and `audit.md`.
6. Read `works/balipeedam-nokki/sections/README.md`.
7. For English work, read `works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`, `README.md`, `PROGRESS.md`, `GLOSSARY.md`, and `TRANSLATION_REVIEW.md`.
8. Continue existing work; do not create duplicate structures.
9. Treat audited Tamil `pages/` as controlling textual authority.
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
2. scan 7 — narrator introduces the film-like lesson;
3. scans 8–29 + opening of scan 30 — internal `ராயசம் வெங்கண்ணு` sequence;
4. scan 30 — internal film reaches `வணக்கம்`, then `படம் முடிந்துவிட்டது...` returns to the main frame;
5. scans 31–33 — conclusion;
6. scan 34 — blank/back matter.

## Tamil archival state — COMPLETE + PASSED

- page records: **34 / 34**
- verified: **34 / 34**
- unresolved readings: **0**
- Tamil source audit: **PASSED**
- assembled Tamil reading layer: **PASSED**

Canonical source layer: `works/balipeedam-nokki/pages/`.

Assembled Tamil sections:

- `sections/01-opening-frame.md` — scans 4–7
- `sections/02-rayasam-vengannu-sequence.md` — scans 8–29 + scan 30 through `வணக்கம்`
- `sections/03-return-and-conclusion.md` — scan 30 from `படம் முடிந்துவிட்டது...` through scan 33

## English translation state — VERIFIED

Working English title: **_Towards the Sacrificial Altar_**.

Existing English files:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/README.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/TRANSLATION_REVIEW.md`
- `translations/en/sections/01-opening-frame.md`
- `translations/en/sections/02-rayasam-vengannu-sequence.md`
- `translations/en/sections/03-return-and-conclusion.md`

Batch status:

| Batch | Source | Status |
|---|---|---|
| 1 | scans 4–7 | reviewed |
| 2 | scans 8–13 | reviewed |
| 3 | scans 14–20 | reviewed |
| 4 | scans 21–26 | reviewed |
| 5 | scans 27–30 through `வணக்கம்` | reviewed |
| 6 | scan 30 after `வணக்கம்` through 33 | reviewed |

Final whole-work bilingual alignment: **PASSED**.  
Whole-work English status: **VERIFIED**.

## Final bilingual review result

`translations/en/TRANSLATION_REVIEW.md` confirms:

- complete body-text coverage for scans 4–33;
- no material source omission or duplication;
- no source-like additions requiring removal;
- no altered speaker assignment or material agency change;
- no whole-work softening/intensification of the political, religious or caste rhetoric;
- stable recurring names and terms;
- cinematic form, title card, screen text and end-card preserved;
- scan 29→30 and scan 30→31 joins preserved;
- scan-30 internal-film/main-frame boundary preserved exactly;
- `ராயசம் வெங்கண்ணு` remains internal;
- audited Tamil remains controlling authority.

The final review explicitly revisited `புத்த பூதம்`; the existing cautious contextual **“a new demon”** was retained without treating it as a correction of the canonical Tamil.

Other difficult forms remain transliterated or cautiously rendered as documented in `GLOSSARY.md`, including *virudha*, *mitthanamathan*, *kilathirukkirathu*, *thegidu thaththakkar*, *Tharppakurar*, *Pulikkir veera*, *vanavaninam* and *pasalu*.

## Current repository status for this work

- Tamil source-preservation layer — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English translation — **VERIFIED**
- source PDF in repository — **NO**
- release report — **not yet created**

## Next exact activity — RELEASE READINESS

Create:

`works/balipeedam-nokki/translations/en/RELEASE_REPORT.md`

The release-readiness pass should:

1. verify reader-facing navigation among all three English sections;
2. verify links from root README, work README and English README;
3. record the final release inventory for Tamil page records, Tamil assembled sections and English translation artifacts;
4. state the authority hierarchy clearly: Tamil audited `pages/` > Tamil assembled `sections/` > English translation;
5. record that source-specific oddities are deliberately preserved/documented;
6. confirm the source PDF remains outside GitHub;
7. identify any non-blocking editorial limitations without changing canonical Tamil;
8. declare whether the archival package is release-ready.

Do not reopen verified Tamil readings merely for stylistic modernization. Any future reader-facing edition must derive from the verified layers and keep provenance clear.
