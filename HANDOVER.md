# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Verify current `main` before future changes.

## Mandatory startup for future work

Before continuing this repository:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read the target work README and source metadata.
4. Continue existing work rather than creating duplicate structures.
5. Treat audited Tamil `pages/` records as controlling textual authority.
6. Do **not** upload or commit supplied source PDFs unless the repository policy is explicitly changed.

---

# Completed work — பலிபீடம் நோக்கி

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

Never promote `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` to a separate work. It is the internal cinematic-historical sequence used inside the same text.

Source flow:

1. scans 4–7 — opening ideological/polemical frame;
2. scan 7 — narrator introduces the film-like lesson;
3. scans 8–29 + opening of scan 30 — internal `ராயசம் வெங்கண்ணு` sequence through `வணக்கம்`;
4. scan 30 — `படம் முடிந்துவிட்டது...` returns to the main frame;
5. scans 31–33 — conclusion;
6. scan 34 — blank/back matter.

## Tamil archival state — COMPLETE + PASSED + RELEASE-READY

- page records: **34 / 34**
- verified: **34 / 34**
- unresolved readings: **0**
- Tamil source audit: **PASSED**
- assembled Tamil reading layer: **PASSED**

Canonical source layer:

`works/balipeedam-nokki/pages/`

Assembled Tamil sections:

- `sections/01-opening-frame.md` — scans 4–7
- `sections/02-rayasam-vengannu-sequence.md` — scans 8–29 + scan 30 through `வணக்கம்`
- `sections/03-return-and-conclusion.md` — scan 30 from `படம் முடிந்துவிட்டது...` through scan 33

## English translation state — VERIFIED + RELEASE-READY

Working English title: **_Towards the Sacrificial Altar_**.

English files:

- `translations/en/README.md`
- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/TRANSLATION_REVIEW.md`
- `translations/en/RELEASE_REPORT.md`
- `translations/en/sections/01-opening-frame.md`
- `translations/en/sections/02-rayasam-vengannu-sequence.md`
- `translations/en/sections/03-return-and-conclusion.md`

English body-text coverage: **scans 4–33 complete**.  
All six batches: **reviewed**.  
Final bilingual alignment: **PASSED**.  
Whole-work English: **VERIFIED**.

## Final release-readiness result

`works/balipeedam-nokki/translations/en/RELEASE_REPORT.md` records the final release pass.

Passed checks:

- reader-facing navigation across all three English sections;
- root README → work README navigation;
- work README → Tamil/English artifacts navigation;
- English README → reading sections/review/glossary/progress/release report navigation;
- Tamil page inventory: **34 / 34 verified**;
- Tamil assembled-section inventory: **3 / 3**;
- English reading-section inventory: **3 / 3**;
- exact scan-30 internal-film/main-frame boundary;
- source-specific oddities remain documented rather than normalized;
- canonical Tamil unchanged during release pass;
- repository tree contains **no committed `.pdf` file**.

### Release verdict

**Tamil archival package: RELEASE-READY.**  
**English translation package: RELEASE-READY.**  
**Combined repository edition: RELEASE-READY within this archive.**

This is an editorial/archival readiness verdict. It is not a determination of copyright, licensing, republication or commercial-use rights.

## Authority hierarchy for all future derived work

1. audited Tamil `pages/` — controlling source text;
2. verified assembled Tamil `sections/` — continuous reading layer;
3. verified English translation — derived source-bound translation;
4. metadata, glossary, reviews and release report — provenance and editorial documentation.

Do not silently modernize, correct or reconstruct verified Tamil forms in a future reader-facing edition.

## Difficult source forms that remain intentional

Examples include:

- `மித்தானமத்தனுக்குக்` / *mitthanamathan*;
- `கிளத்திருக்கிறது` / *kilathirukkirathu*;
- `தெகிடு தத்தக்கார்களுக்கு` / *thegidu thaththakkar*;
- `தர்ப்பாகூரர்` / *Tharppakurar*;
- `புலிக்கிர் வீரா` / *Pulikkir veera*;
- `வானவாணினம்` / *vanavaninam*;
- `பசலுக்கு` / *pasalu*;
- `புத்த பூதம்` with the documented cautious English “a new demon”.

See `translations/en/GLOSSARY.md` and `TRANSLATION_REVIEW.md` for the complete policy.

## Current exact next action

**No mandatory transcription, audit or translation activity remains for this source edition.**

When another Kalaignar novel/story source is supplied, begin the normal source-registration workflow in a new `works/<slug>/` directory after first checking that the work has not already been started.

A separate reader-facing ebook/print/web edition of `பலிபீடம் நோக்கி` should be created only when explicitly requested, and must derive from these verified layers while preserving provenance and the Tamil source authority.
