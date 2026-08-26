# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary reusable guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

---

# 1. Mandatory startup in a new chat

Before doing any work on the current/next novel or story:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read this `HANDOVER.md` completely.
4. Study `works/balipeedam-nokki/` only as the completed reference implementation, especially its README, source metadata, page map, audit, assembled Tamil layer and English plan/progress/glossary/review/release documents.
5. Inspect repository state before creating a work directory.
6. If the target work already exists, continue it; do not create a duplicate.
7. Inspect the actual source scan before metadata/transcription decisions. Do not trust filename, OCR or supplied text alone.
8. Do not upload or commit source PDFs or split source PDFs.

---

# 2. Controlling source policy

Authority order:

1. actual source scan page;
2. source-printed bibliographic / page information;
3. canonical Tamil `pages/` records;
4. audited assembled Tamil `sections/`;
5. verified English translation;
6. metadata / glossary / review documentation.

Do not silently modernize, correct, normalize, reconstruct or improve source-supported Tamil. Preserve source-supported spelling, punctuation, unusual grammar, names/titles/numbers, repetitions, typographical forms, dialogue, cinematic/dramatic notation and source oddities. Separate printed text from stamps, handwriting, underlines, later annotations, bleed-through and scan artefacts.

User-supplied draft transcription and OCR are aids only. A page may be `verified` only after direct visual comparison with the scan.

Printed page numbers must also be source-visible. **Never infer a page number merely from sequence.**

---

# 3. Completed reference implementation — பலிபீடம் நோக்கி

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**  
Source edition: **First edition, April 1947**  
Source scan: **34 pages**

External source filename:

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

SHA-256:

`c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`

Final status:

- Tamil page records — **34 / 34 verified**
- Tamil source audit — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English — **VERIFIED**
- combined archival package — **RELEASE-READY**
- source PDF in repository — **No**

Structural lesson: `ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை` is an internal cinematic-historical sequence inside `பலிபீடம் நோக்கி`, not a separate work.

---

# 4. Current target work — புதையல்

Work path:

`works/pudhaiyal/`

Source identity established directly from scans:

- Title: **புதையல்**
- Author line: **கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.**
- Publisher: **அன்புப் பதிப்பகம்**
- Place: **பொறையார் :: தஞ்சை மாவட்டம்**
- Edition: **மூன்றாம் பதிப்பு**
- Edition date: **செப்டம்பர், 1961**

Original external source filename:

`TVA_BOK_0064097_புதையல்.pdf`

Original-source facts currently available:

- file size: **502,895,096 bytes**
- Tamil Digital Library bibliographic extent: **443 p.**
- exact full-PDF scan/page-object count: **pending complete source reconciliation**
- original SHA-256: **pending exact byte-level calculation**
- source PDF committed to repository: **No**

## Critical source-extent correction

The earlier project state incorrectly treated scans **1–150** as the complete source. That conclusion is withdrawn.

TDL reconciliation established:

- bibliographic physical description: **443 p.**;
- current item page: **PDF — 2 Files**;
- scan 150 / printed page 148 is not a valid source-ending claim;
- `150` is only the known initial prefix, not the full scan count.

Correction record:

`works/pudhaiyal/notes/source-page-count-reconciliation.md`

Do **not** automatically equate `443 p.` with exact PDF scan count.

## Split-source workflow

Received:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split PDF page count: **49**
- split file size available in runtime: **52,760,797 bytes**
- committed to repository: **No**

This split is an access derivative of the controlling source, not a new edition.

## Edition/catalogue discrepancy

The controlling scan visibly states **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**. A TDL catalogue summary labels the work `முதல் பதிப்பு, 1961`.

For this repository edition, the **scan governs**.

---

# 5. Current source structure — known prefix only

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scans 13–21 — chapter 1;
- scan 22 — chapter 1 closes and chapter 2 begins on the same physical page;
- scans 23–30 — chapter 2 continues;
- scans 31–39 — chapter 3;
- scans 40–51 — chapter 4;
- scans 52–59 — chapter 5;
- scans 60–68 — chapter 6;
- scans 69–74 — chapter 7;
- scans 75–83 — chapter 8;
- scans 84–92 — chapter 9;
- scans 93–101 — chapter 10;
- scans 102–109 — chapter 11;
- scans 110–118 — chapter 12;
- scans 119–127 — chapter 13;
- scans 128–137 — chapter 14;
- scans 138–145 — chapter 15;
- scan 146 — chapter 16 begins within the known prefix.

No claim is made about later chapter starts, final chapter number, final printed page, closing matter or back cover.

## Printed-page behaviour — corrected direct evidence

- scans 1–7: no visible printed page number → `null` / `—`;
- scans 8–12 visibly print pages **6–10**;
- scan 13: chapter-1 opening page; **no printed page number is visible** → `null` / `—`; do **not** infer 11;
- scan 14: printed **12**;
- scans 15–22 visibly continue through printed **13–20**.

The previous blanket claim that every scan from 8 onward visibly carried a continuous page number is corrected.

---

# 6. Current artifacts and Tamil transcription state

Core files:

- `works/pudhaiyal/README.md`
- `works/pudhaiyal/metadata/source.md`
- `works/pudhaiyal/indexes/page-map.md`
- `works/pudhaiyal/notes/source-page-count-reconciliation.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`

Canonical page records now exist through:

`works/pudhaiyal/pages/0022-pudhaiyal.md`

Current Tamil page-record state:

- page records actually created: **22**
- `verified`: **22**
- `needs-review`: **0**
- unresolved readings in scans 1–22: **0**
- remaining known-prefix rows `not-started`: **128**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked by Tamil audit gate**
- English translation: **blocked by Tamil audit gate**

## Completed fidelity pass — scans 1–12

Detailed report:

`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`

Notable corrections include `ஸ்பெஷல் பதிப்பு`, `மூன்றாம் பதிப்பு`, `எம். எல். ஏ.`, `தமிழர்கள் ஆதரிக்க வேண்டுகின்றோம்.`, `பெறுமானமுள்ள`, and `இருக்கிறாள்ன்னு`, plus source punctuation replacing draft `..` punctuation.

## Completed fidelity pass — scans 13–22

Detailed report:

`works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`

Material source-supported corrections include:

- scan 13: `கையிலும்`, not `கையிலேயும்`;
- scan 13: printed-page number suppressed; `printed_page: null`;
- scan 14: `பூமியைத் தோண்டிப்`;
- scan 15: `நம்பிக்கையுண்டு`, `தன உயிருக்கு`, `மெளனமாய்`;
- scan 16: inscription ends `கம்மாளர் கண்ணிலே......`;
- scan 17: `ஆராய்ந்து விட்டோமே`;
- scan 18: omitted dialogue lines `கண்ணே!` and `ராஜா!` restored;
- scan 19: `வெளவாலிடம்` / `வெளவால்`;
- scan 21: `அடிபட்டுவிட்டதால்`;
- scan 22: printed horizontal rule followed by chapter `2` on the same scan; chapter 2 begins `அணா நாணயத்தின் விளிம்பு போல...`.

## Cross-page continuity checked through scan 22

- scan 7 `காய்ந்த மீனின் வாசம்` → scan 8 `‘கம கம’...`;
- scan 8 `அடை` → scan 9 `யாளமாக`;
- scan 11 `கனவு` → scan 12 `காண்பவர்களின்`;
- scan 13 `அவன் மீதுள்ள` → scan 14 `அன்பால்`;
- scan 14 `அவரே குறித்துக்கொண்ட நாள்` → scan 15 `அல்ல; ஜோசியர் குறித்த நாள்.`;
- scan 15 `அவர்கள்` → scan 16 `ஒவ்வொருவரிடமும்`;
- scan 16 `படபடப்பை` → scan 17 `உண்டாக்கியது தெரியுமா?`;
- scan 20 `அந்தப் பயலும்` → scan 21 `சிறுக்கியும்...`.

Do not reflow these physical boundaries in canonical page records.

---

# 7. Required page-status values

Use only:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` requires direct visual comparison with the source scan.

---

# 8. Tamil / translation gates

Before translation:

- exact full-source extent must be known;
- every scan page must have a record;
- full page map must have no coverage gap;
- all body pages must be directly visually audited;
- unresolved readings must be resolved or explicitly documented;
- metadata / README / handover statuses must agree;
- cross-page continuity must be checked;
- full internal structure must be correctly identified;
- Tamil `audit.md` must pass;
- source PDFs/splits must remain outside the repository.

Only after that create the assembled Tamil `sections/` layer, then the English translation plan and controlled translation workflow.

---

# 9. Git practice

Prefer narrow descriptive commits. Do not include source PDFs. Do not modify source-supported Tamil for stylistic modernization.

---

# 10. Current exact next action

**Transcribe and directly visually verify `புதையல்` scans 23–26 / printed pages 21–24 from split part 001, continuing chapter 2.**

Required sequence:

1. inspect scans 23–26 at readable source resolution;
2. create `works/pudhaiyal/pages/0023-pudhaiyal.md` through `0026-pudhaiyal.md`;
3. preserve exact spelling, punctuation, paragraph/dialogue structure and physical page boundaries;
4. check every scan-to-scan continuation before marking pages `verified`;
5. leave any genuinely uncertain glyph `needs-review` rather than guessing from supplied draft/context;
6. update `indexes/page-map.md`, work README and this handover;
7. as later split parts are supplied, extend the manifest beyond scan 150 and establish the exact full-source scan count;
8. calculate the exact original-source SHA-256 when byte-level access becomes available.

Do **not** start English translation.

---

# 11. Fresh-chat continuation prompt

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source PDF. Current live repository state and this handover govern over stale summaries.
