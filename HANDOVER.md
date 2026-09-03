# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Completed current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators, chapter transitions, narrative ending and back matter.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms/spacing:

- Part 007 — `p7.md`
- Part 008 — `p8.md`
- Part 009 — `p9.md`
- Part 010 — `p10.md`

Complete source-visible lexical spans absent from the baseline require explicit user disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## புதையல் source identity

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- received source scans: **1–448**
- narrative ending: **scan 447 / printed 443**
- scan 448: separate printer colophon
- exact original full-file SHA-256: still not calculated; do not invent it

Complete-source map: `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`.

## Final durable state — புதையல்

- canonical page records: **448 / 448**
- native-verified / completed: **441**
- source-damage `needs-review`: **7 — scans 215–219 and 223–224 only**
- partial: **0**
- assembled Tamil narrative: continuous through scan **447 / printed 443**
- assembled Tamil back matter: through scan **448**
- source-checked English narrative/back matter: through scan **448**
- bilingual-reviewed English narrative/back matter: through scan **448**
- Parts **001–010**: **`part-complete`**
- whole-work bilingual review: **PASSED**
- whole-work English translation: **VERIFIED**
- repository release status: **RELEASE-READY WITH EXPLICIT PART-005 SOURCE-DAMAGE QUALIFICATION**

The seven damaged Part-005 records remain qualified. No release status upgrades missing/damaged native pixels to verified text.

## Final review / release records

- `works/pudhaiyal/audit.md` — whole-work archival audit, qualified PASS
- `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md` — complete-source 1–448 manifest
- `works/pudhaiyal/sections/README.md` — complete assembled Tamil reading index
- `works/pudhaiyal/translations/en/README.md` — verified English reader index
- `works/pudhaiyal/translations/en/GLOSSARY.md` — whole-work controlled terminology
- `works/pudhaiyal/translations/en/PROGRESS.md` — translation/review history
- `works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md` — final whole-work bilingual verdict
- `works/pudhaiyal/translations/en/RELEASE_REPORT.md` — final release-readiness report

## Split-level closure

- Parts 001–004: `part-complete`
- Part 005: `part-complete` **with source-damage qualification**
- Parts 006–010: `part-complete`

Key late records:

- Part 009 Tamil audit + assembled check + English source check + bilingual review: **PASSED**
- Part 010 Tamil audit + assembled check + English source check + bilingual review: **PASSED**

## Verified cross-split joins

- 49→50 — Chapter 4 continues
- 98→99 — Chapter 10 continues
- 147→148 — Chapter 16 continues
- 196→197 — Chapter 22 continues
- 245→246 — Chapter 27 continues
- 294→295 — Chapter 33 continues
- 343→344 — Tamil `அதிர்ஷ்` + `டம்` → **`அதிர்ஷ்டம்`**; English `luc` + `k` → **luck**
- 392→393 — `நமது` + `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**
- 441→442 — `அம்ப` + `லமே` → **`அம்பலமே`**; English `Amb` + continuation → **Ambalam**

## Authorized restoration ledger

User-authorized source-visible baseline omissions retained as narrow exceptions:

1. Part 007 scan 304 — `நீ`
2. Part 007 scan 305 — `என்ன`
3. Part 007 scan 315 — `சரி...... வா! வா!......`
4. Part 008 scan 384 — `தகட்டில் இருக்கிறபடி`
5. Part 010 scan 445 — `விடு` in `தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`

No broader lexical-normalization authority follows from these restorations.

## Source-specific English decisions retained

The verified English deliberately preserves source-specific / source-era wording rather than externally correcting it, including:

- Chapter-46 disguise inconsistency and Laila/Qais-in-London tale;
- Chapter-48 Aravan/Bhima statement, `kalappali` and caste-marked wording;
- Chapter-42 source-era racial descriptor with provenance;
- Chapter-50 `சாவுக் கண்ணீர்` → **tears of death**;
- Chapter-51 `Mayarandi`, scan-446 `Agar!`, and the final wording that Durai goes to report that **“Velliyambalam had returned”**;
- scan-445 `இந்தப் பாவி` represented as **“this sinner”** after the Part-010 bilingual review.

## Exact next activity

`புதையல்` has no remaining archival, translation, bilingual-review or release-readiness gate in the current workflow.

For the next source work:

1. fetch live `main` first;
2. preserve this completed `புதையல்` release state;
3. read `NOVEL_PROCESSING_GUIDE.md`, root `README.md`, this `HANDOVER.md`, and `NEXT_NOVEL_CHAT_PROMPT.md`;
4. attach/resolve the next controlling source PDF;
5. start the new work from source inspection rather than modifying `புதையல்` unless a new source-supported correction is explicitly requested.
