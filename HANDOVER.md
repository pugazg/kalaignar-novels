# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Completed current work: `works/pudhaiyal/`

## புதையல் — source identity

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- received source scans: **1–448**
- narrative ending: **scan 447 / printed 443**
- scan 448: separate printer colophon

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators, chapter transitions, narrative ending and back matter.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms/spacing:

- Part 007 — `p7.md`
- Part 008 — `p8.md`
- Part 009 — `p9.md`
- Part 010 — `p10.md`

Complete source-visible lexical spans absent from the baseline require explicit user disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## Final durable state

- canonical records: **448 / 448**
- verified / completed: **446**
- `needs-review`: **2 — scans 223–224 only**
- partial: **0**
- Parts **001–010: part-complete**
- assembled Tamil narrative: through scan **447 / printed 443**
- assembled back matter: through scan **448**
- source-checked English: through scan **448**
- bilingual-reviewed English: through scan **448**
- whole-work English: **VERIFIED**
- repository package: **RELEASE-READY WITH TWO PART-005 PHYSICAL-LOSS QUALIFICATIONS**

## Part 005 — 2026-09-03 direct user review

The previously tape-obstructed scans **215–219** are now closed.

### Scan 215 / printed 213

User-supplied source corrections:

- `பாமளாவும்` → `பரிமளாவும்`
- `கொழுந்தே` → `கொழுந்தாம்`
- `என்று தழுதழுத்த குரலிலே கேட்டான்` → `என்று தழுதழுத்த குரலிலே அவன் கேட்டான்`

### Scan 216 / printed 214

User-supplied source corrections:

- `புண்ணுக்கு மருந்து கேட்கிறாய்.` → `புண்ணுக்கு மருந்து கேள்; தருகிறேன்.`
- `அவன் வீறுகொண்டு` → `அவன் வீரனாக`

### Scans 217–219

- scan 217: user confirmed retained reading;
- scan 218: duplicate witness of printed 214, synchronized to corrected scan 216;
- scan 219: duplicate witness of printed 215, user confirmed retained reading.

Only scans **223–224** remain `needs-review`, because substantial source paper is physically missing. A stronger source witness is required to close them.

## English correction impact

Chapter 24 English has been re-synchronized:

- **Pamala** → **Parimala**;
- corrected `கொழுந்தாம்` removed the prior vocative handling;
- `புண்ணுக்கு மருந்து கேள்; தருகிறேன்.` → **“Ask for medicine for the wound; I'll give it.”**;
- `அவன் வீரனாக நின்று சமர் புரியவில்லை` → **“he did not stand as a warrior and fight.”**

The added Tamil subject `அவன்` before `கேட்டான்` requires no new English wording because the translation already explicitly says “he asked”.

## Final records

- complete-source map: `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`
- Part-005 page map: `works/pudhaiyal/indexes/part-005-page-map.md`
- whole-work Tamil audit: `works/pudhaiyal/audit.md`
- Part-005 audit: `works/pudhaiyal/notes/part-005-tamil-audit.md`
- Part-005 bilingual review: `works/pudhaiyal/translations/en/PART_005_REVIEW.md`
- final bilingual review: `works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md`
- release report: `works/pudhaiyal/translations/en/RELEASE_REPORT.md`

## Exact next activity

There is **no remaining `புதையல்` workflow gate**. If a stronger witness for scans 223–224 becomes available, re-open only those two physical-loss records and propagate any proven corrections. Otherwise begin the next novel/story using `NEXT_NOVEL_CHAT_PROMPT.md`.
