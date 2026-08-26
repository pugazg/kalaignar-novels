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
4. Study `works/balipeedam-nokki/` as the completed reference implementation, especially its README, source metadata, page map, audit, assembled Tamil layer and English plan/progress/glossary/review/release documents.
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

Do not silently modernize, correct, normalize, reconstruct or improve source-supported Tamil. Preserve source-supported spelling, punctuation, unusual grammar, names/titles/numbers, repetitions, typographical forms, cinematic/dramatic notation and source oddities. Separate printed text from stamps, handwriting, underlines, later annotations, bleed-through and scan artefacts.

User-supplied draft transcription and OCR are aids only. A page may be `verified` only after direct visual comparison with the scan.

Web/catalogue information may help establish bibliographic context or reveal that a renderer is incomplete, but it must never silently override exact wording printed in the controlling scan.

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

Source PDF in repository: **No**.

Final status:

- source registration — **complete**
- Tamil page records — **34 / 34**
- Tamil direct visual verification — **34 / 34 verified**
- unresolved Tamil readings — **0**
- Tamil source audit — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English translation batches — **6 / 6 reviewed**
- final bilingual alignment — **PASSED**
- whole-work English — **VERIFIED**
- release-readiness — **RELEASE-READY within this repository**

Reference release report:

`works/balipeedam-nokki/translations/en/RELEASE_REPORT.md`

Structural lesson retained: `ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை` is an internal cinematic-historical sequence inside `பலிபீடம் நோக்கி`, not a separate work.

---

# 4. Current target work — புதையல்

Work path:

`works/pudhaiyal/`

Source identity established directly from scans 1 and 3:

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

The user supplied Tamil Digital Library references for the same work. Reconciliation established:

- TDL legacy bibliographic record: **physical description `443 p.`**;
- current TDL item page: **PDF — 2 Files**;
- scan 150 / printed page 148 is not a valid source-ending claim;
- `150` is only the known initial prefix, not the full scan count.

Correction record:

`works/pudhaiyal/notes/source-page-count-reconciliation.md`

Do **not** automatically equate `443 p.` with exact PDF scan count. Covers, blank scans, inserts or other scan objects may make the scan count differ from printed-page extent.

## Split-source workflow

The user is now providing non-recompressed page-range splits of the controlling source for reliable visual inspection.

Received:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split PDF page count: **49**
- split file size available in chat runtime: **52,760,797 bytes**
- committed to repository: **No**

The split is an access derivative of the controlling source, not a new edition and not an authority independent of the original scan.

## Edition/catalogue discrepancy

The controlling scan visibly states:

**`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**.

A Tamil Digital Library Kalaignar special-page catalogue summary labels the work `முதல் பதிப்பு, 1961`.

For this repository edition, the **scan governs**. Do not change the repository edition to first edition based on catalogue metadata.

---

# 5. Current source structure — known prefix only

Current direct source inspection establishes this prefix:

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scans 13–21 — chapter 1;
- scans 22–30 — chapter 2;
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

No claim is currently made about later chapter starts, final chapter number, final printed page, closing matter or back cover.

## Printed-page behaviour — known prefix

- scans 1–7: no visible printed page number → `null` / `—`;
- scan 8 visibly prints page 6;
- within the known prefix, scans 8–150 visibly run through printed page **148**.

No printed number after scan 150 may be inferred until that scan page is directly inspected from a later split/native source range.

---

# 6. Current artifacts and Tamil transcription state

Created/maintained:

- `works/pudhaiyal/README.md`
- `works/pudhaiyal/metadata/source.md`
- `works/pudhaiyal/indexes/page-map.md` — known prefix map for scans 1–150; full-source coverage incomplete
- `works/pudhaiyal/notes/source-page-count-reconciliation.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/pages/0001-cover.md`
- `works/pudhaiyal/pages/0002-provenance.md`
- `works/pudhaiyal/pages/0003-title-page.md`
- `works/pudhaiyal/pages/0004-publication.md`
- `works/pudhaiyal/pages/0005-publisher-note.md`
- `works/pudhaiyal/pages/0006-blank.md`
- `works/pudhaiyal/pages/0007-pudhaiyal.md`
- `works/pudhaiyal/pages/0008-pudhaiyal.md`
- `works/pudhaiyal/pages/0009-pudhaiyal.md`
- `works/pudhaiyal/pages/0010-pudhaiyal.md`
- `works/pudhaiyal/pages/0011-pudhaiyal.md`
- `works/pudhaiyal/pages/0012-pudhaiyal.md`

Current Tamil page-record state:

- page records actually created: **12**
- `verified`: **12**
- `needs-review`: **0**
- remaining known-prefix rows `not-started`: **138**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked by Tamil audit gate**
- English translation: **blocked by Tamil audit gate**

## Completed fidelity pass — scans 1–12

Split part 001 enabled a fresh letter-by-letter visual-fidelity pass through the end of the `அறிமுகம்`.

Detailed report:

`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`

Material scan-supported corrections include:

- scan 4: `ஸ்பெஷல் பதிப்பு ரூ 6/-`, not supplied `நூல் நிலையப் பதிப்பு`;
- scan 4: `மூன்றாம் பதிப்பு, செப்டம்பர், 1961.`, not supplied `முதற் பதிப்பு`;
- scan 4: no source-supported full stop after `ரூ`;
- scan 5: `எம். எல். ஏ.`, not `எம்.எ.ஏ.`;
- scan 5: `தமிழர்கள் ஆதரிக்க வேண்டுகின்றோம்.`;
- scans 7–12: supplied repeated `..` punctuation was not accepted; source punctuation controls;
- scan 10: `பெறுமானமுள்ள` retained from the visible print;
- scan 11: colloquial `இருக்கிறாள்ன்னு` retained from the visible print.

Copy-specific handwriting on scan 3 remains separated from printed title-page text.

## Cross-page continuity already checked

- scan 7 ends `காய்ந்த மீனின் வாசம்`; scan 8 continues `‘கம கம’ வென்று வந்துகொண்டிருக்கும்.`;
- scan 8 ends `அடை`; scan 9 begins `யாளமாக` → continuous `அடையாளமாக`;
- scan 10 quotation continues onto scan 11;
- scan 11 `கனவு` continues with scan 12 `காண்பவர்களின்`;
- scan 12 ends the `அறிமுகம்`; scan 13 begins chapter 1.

Do not reflow these physical boundaries in canonical page records.

---

# 7. Public source references used only for extent reconciliation

- Kalaignar special page: `https://tamildigitallibrary.in/kalaignar/01.literature/navalkal/005_புதையல்.html`
- Tamil Digital Library item: `https://tamildigitallibrary.in/Articles/நூல்-64097-புதையல்#book1/`
- legacy item page: `https://www.tamildigitallibrary.in/book-detail.php?id=jZY9lup2kZl6TuXGlZQdjZU7luI1`

These may corroborate bibliographic extent, but the source scan remains controlling for exact text and edition wording.

---

# 8. Required page-status values

Use only:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` requires direct visual comparison with the source scan. OCR and supplied transcription are only aids.

---

# 9. Tamil / translation gates

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

# 10. Git practice

Prefer narrow descriptive commits. Do not include source PDFs. Do not modify source-supported Tamil for stylistic modernization.

---

# 11. Current exact next action

**Transcribe and directly visually verify `புதையல்` scans 13–16 / printed pages 11–14 from split part 001 as the first Chapter 1 batch.**

Required sequence:

1. inspect scans 13–16 at readable source resolution;
2. create `works/pudhaiyal/pages/0013-pudhaiyal.md` through `0016-pudhaiyal.md`;
3. preserve exact spelling, punctuation, paragraph/dialogue structure, chapter ornament and physical page boundaries;
4. check every scan-to-scan continuation before marking the pages `verified`;
5. leave any genuinely uncertain glyph `needs-review` rather than guessing from the user's draft or context;
6. update `indexes/page-map.md`, work README and this handover;
7. continue source-extent reconciliation as later split parts are supplied; extend the manifest beyond scan 150 when those scans become available;
8. calculate the exact original-source SHA-256 when byte-level access becomes available.

Do **not** start English translation.

---

# 12. Fresh-chat continuation prompt

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source PDF. Current live repository state and this handover govern over stale summaries.
