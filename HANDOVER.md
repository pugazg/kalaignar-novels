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
7. Inspect the actual attached PDF scan before metadata creation. Do not trust filename alone.
8. Do not upload or commit the source PDF.

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

External source filename:

`TVA_BOK_0064097_புதையல்.pdf`

Attached-file facts currently available:

- file size: **502,895,096 bytes**
- exact PDF scan/page-object count: **pending full-file/native inspection**
- currently rendered page-image window in this chat: **scans 1–150 only**
- SHA-256: **pending exact byte-level calculation**
- source PDF committed to repository: **No**

## Critical source-extent correction

The earlier handover incorrectly stated that the source contained only **150 scans** and that scan 150 / printed page 148 was the supplied PDF ending. That conclusion is **withdrawn**.

The user supplied two Tamil Digital Library references for the same work. Source reconciliation established:

- Tamil Digital Library legacy bibliographic record: **physical description `443 p.`**;
- current Tamil Digital Library item page: **PDF — 2 Files**;
- the chat Files renderer currently returns page images only through scan 150;
- requesting scan 151 onward returns no rendered images, but this is a renderer/tool limitation, not evidence of source termination.

Therefore:

> **150 = currently exposed rendered prefix, NOT total source extent.**

Correction record:

`works/pudhaiyal/notes/source-page-count-reconciliation.md`

## Edition/catalogue discrepancy

The controlling attached scan visibly states:

**`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**.

The Kalaignar special-page catalogue summary labels the work `முதல் பதிப்பு, 1961`.

For this repository edition, the **scan governs**. Do not change the repository edition to first edition based on catalogue metadata.

## Current source structure — prefix only

Direct visual inspection of scans 1–150 establishes only this prefix:

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
- scan 146 — chapter 16 begins and continues beyond the rendered prefix.

No claim is currently made about later chapter starts, final chapter number, final printed page, closing matter or back cover.

## Printed-page behaviour — verified prefix only

- scans 1–7: no visible printed page number → `null` / `—`;
- scan 8 visibly prints page 6;
- within the currently inspected prefix, scans 8–150 visibly run through printed page **148**.

No printed number after scan 150 may be inferred until that scan page is directly inspected.

---

# 5. Current artifacts for புதையல்

Created/maintained:

- `works/pudhaiyal/README.md`
- `works/pudhaiyal/metadata/source.md`
- `works/pudhaiyal/indexes/page-map.md` — **provisional prefix map for scans 1–150 only; full-source coverage incomplete**
- `works/pudhaiyal/notes/source-page-count-reconciliation.md`
- `works/pudhaiyal/pages/0001-cover.md`
- `works/pudhaiyal/pages/0002-provenance.md`
- `works/pudhaiyal/pages/0003-title-page.md`
- `works/pudhaiyal/pages/0004-publication.md`
- `works/pudhaiyal/pages/0005-publisher-note.md`
- `works/pudhaiyal/pages/0006-blank.md`
- `works/pudhaiyal/pages/0007-pudhaiyal.md`
- `works/pudhaiyal/pages/0008-pudhaiyal.md`

Current Tamil page-record state:

- page records actually created: **8**
- `verified`: **6**
- `needs-review`: **2** — scans 7–8
- full-source page-map coverage: **INCOMPLETE**
- Tamil audit: **not started**
- assembled Tamil layer: **blocked by Tamil audit gate**
- English translation: **blocked by Tamil audit gate**

## Scans 7–8 review state

Both scans were directly inspected as the first `அறிமுகம்` body-text batch.

- scan 7 clearly shows `அறிமுகம்:` and no visible printed page number;
- scan 8 continues the introduction and visibly prints page **6**;
- the currently available rendered images are not sufficiently legible for reliable full character-by-character transcription;
- no uncertain Tamil body wording has been guessed, normalized, reconstructed from context or copied from an external source;
- both page records remain **`needs-review`** pending enlarged/native source inspection.

Do not resume ordinary transcription expansion until the full source extent is reconciled and the page map can be extended beyond scan 150.

---

# 6. Public source references used only for extent reconciliation

- Kalaignar special page: `https://tamildigitallibrary.in/kalaignar/01.literature/navalkal/005_புதையல்.html`
- Tamil Digital Library item: `https://tamildigitallibrary.in/Articles/நூல்-64097-புதையல்#book1/`
- legacy item page: `https://www.tamildigitallibrary.in/book-detail.php?id=jZY9lup2kZl6TuXGlZQdjZU7luI1`

These may corroborate bibliographic extent, but the attached scan remains controlling for exact source text and edition wording.

---

# 7. Required page-status values

Use only:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` requires direct visual comparison with the source scan. OCR is only an aid and never authority.

---

# 8. Tamil / translation gates

Before translation:

- exact source extent must be known;
- every scan page must have a record;
- full page map must have no coverage gap;
- all body pages must be directly visually audited;
- unresolved readings must be resolved or explicitly documented;
- metadata / README / handover statuses must agree;
- cross-page continuity must be checked;
- full internal structure must be correctly identified;
- Tamil `audit.md` must pass;
- source PDF must remain outside the repository.

Only after that create the assembled Tamil `sections/` layer, then the English translation plan and controlled translation workflow.

---

# 9. Git practice

Prefer narrow descriptive commits. Do not include the source PDF. Do not modify source-supported Tamil for stylistic modernization.

---

# 10. Current exact next action

**Recover and register the full `புதையல்` source extent before further normal transcription.**

Required sequence:

1. obtain native/full source access beyond scan 150 (attached full PDF or Tamil Digital Library source files);
2. determine the exact PDF scan/page-object count — do not equate `443 p.` automatically with scan count;
3. inspect scan 151 onward directly;
4. identify later chapter boundaries and the true final printed/back-matter pages from the scan;
5. extend `works/pudhaiyal/indexes/page-map.md` to **every scan page** without inferring printed numbers;
6. calculate the exact SHA-256 from the real PDF bytes when byte-level access becomes available;
7. synchronize `metadata/source.md`, work README, root README and this handover;
8. only after full manifest coverage is established, resume Tamil transcription, beginning by resolving scans 7–8 at enlarged/native resolution.

Do **not** start English translation.

---

# 11. Fresh-chat continuation prompt

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the attached source PDF. Current live repository state and this handover govern over stale summaries.
