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
3. audited Tamil `pages/` records;
4. verified assembled Tamil `sections/`;
5. verified English translation;
6. metadata / glossary / review documentation.

Do not silently modernize, correct, normalize, reconstruct or improve source-supported Tamil. Preserve source-supported spelling, punctuation, unusual grammar, names/titles/numbers, repetitions, typographical forms, cinematic/dramatic notation and source oddities. Separate printed text from stamps, handwriting, underlines, later annotations, bleed-through and scan artefacts.

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

Source scan facts:

- scan pages: **150**
- file size: **502,895,096 bytes**
- SHA-256: **pending exact byte-level calculation**
- source PDF committed to repository: **No**

Why SHA-256 is pending: the current file service refuses raw materialization of the 502,895,096-byte PDF because it exceeds the 100 MiB materialization limit, and the normal local hashing runtime was unavailable during onboarding. Do not invent a checksum. Calculate it from the actual attachment bytes at the first activity where byte-level access works.

## Current source structure

Direct visual inspection of all supplied scans supports one continuous work:

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
- scans 146–150 — chapter 16 as supplied.

No inspected internal heading establishes a separate bibliographic work.

## Printed-page behaviour

- scans 1–7: no visible printed page number → `null` / `—`;
- scan 8 visibly prints page 6;
- scans 8–150 visibly run continuously from printed pages **6–148**.

## Supplied-scan ending caution

The PDF ends at scan 150 / printed page 148 while body prose is still present. No explicit `முற்றும்`, back cover, advertisement or blank ending leaf appears in the supplied PDF. Treat physical/bibliographic completeness as an audit item and do not reconstruct a continuation.

---

# 5. Current artifacts for புதையல்

Created:

- `works/pudhaiyal/README.md`
- `works/pudhaiyal/metadata/source.md`
- `works/pudhaiyal/indexes/page-map.md` — covers all **150 / 150** supplied scans
- `works/pudhaiyal/pages/0001-cover.md`
- `works/pudhaiyal/pages/0002-provenance.md`
- `works/pudhaiyal/pages/0003-title-page.md`
- `works/pudhaiyal/pages/0004-publication.md`
- `works/pudhaiyal/pages/0005-publisher-note.md`
- `works/pudhaiyal/pages/0006-blank.md`

Current Tamil page-record state:

- page records: **6 / 150**
- `verified`: **6**
- `needs-review`: **0**
- `not-started`: **144**
- Tamil audit: **not started**
- assembled Tamil layer: **blocked by Tamil audit gate**
- English translation: **blocked by Tamil audit gate**

Front matter scans 1–6 were directly visually compared before being marked `verified`.

---

# 6. Required page-status values

Use only:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` requires direct visual comparison with the source scan. OCR is only an aid and never authority.

---

# 7. Tamil / translation gates

Before translation:

- every supplied scan must have a page record;
- all body pages must be directly visually audited;
- unresolved readings must be resolved or explicitly documented;
- page map / metadata / README statuses must agree;
- cross-page continuity and supplied-source completeness cautions must be audited;
- internal structure must be correct;
- Tamil `audit.md` must pass;
- source PDF must remain outside the repository.

Only after that create the assembled Tamil `sections/` layer, then the English translation plan and controlled translation workflow.

---

# 8. Git practice

Prefer narrow descriptive commits. Do not include the source PDF. Do not modify source-supported Tamil for stylistic modernization.

---

# 9. Current exact next action

**Transcribe and directly visually verify `புதையல்` scans 7–8 as the first body-text batch (`அறிமுகம்`).**

For that activity:

1. inspect scans 7 and 8 at readable/enlarged resolution;
2. create `pages/0007-pudhaiyal.md` and `pages/0008-pudhaiyal.md`;
3. preserve exact punctuation, paragraph breaks and printed oddities;
4. leave any uncertain glyph `needs-review` rather than guessing;
5. update `indexes/page-map.md`, `works/pudhaiyal/README.md` and this handover;
6. separately retry exact SHA-256 calculation if byte-level runtime access becomes available.

Do not start English translation.

---

# 10. Fresh-chat continuation prompt

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the attached source PDF. Current live repository state and this handover govern over stale summaries.
