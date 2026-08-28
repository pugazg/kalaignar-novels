# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

---

# 1. Mandatory startup

Before changing the current/next work:

1. read `NOVEL_PROCESSING_GUIDE.md` completely;
2. read root `README.md`;
3. read this `HANDOVER.md` completely;
4. study `works/balipeedam-nokki/` only as the completed reference implementation;
5. inspect live repository state before creating files;
6. continue existing work rather than duplicating it;
7. inspect the actual scan before accepting metadata or transcription;
8. never commit source PDFs or split source PDFs.

---

# 2. Source / transcription policy

Authority order:

1. actual scan page;
2. source-printed bibliographic/page information;
3. canonical Tamil `pages/` records;
4. audited Tamil `sections/`;
5. verified English translation;
6. metadata / review documentation.

Do not silently modernize, repair, normalize, reconstruct or improve source-supported Tamil. Preserve spelling, punctuation, spacing, colloquial forms, typographical oddities, page boundaries and internal structure. Separate printed text from handwriting, provenance marks, underlining, bleed-through and scan artefacts.

## Mandatory visual rule after earlier audit hallucinations

When the user supplies a transcription:

- use it as the comparison baseline;
- do not treat it as higher authority than the scan;
- do not replace it merely because grammar/context suggests another reading;
- inspect the actual split-source page image;
- isolate every apparent source-vs-baseline disagreement;
- change canonical text only when the scan establishes the reading;
- perform a final page-by-page visual comparison before `verified`.

OCR, grammar expectations, catalogue text and modern spelling are aids only.

---

# 3. Completed reference implementation — பலிபீடம் நோக்கி

`works/balipeedam-nokki/`

- Tamil page records: **34 / 34 verified**
- unresolved Tamil readings: **0**
- Tamil audit: **PASSED**
- assembled Tamil layer: **PASSED**
- English translation: **VERIFIED**
- release-readiness: **RELEASE-READY**
- source PDF committed: **No**

---

# 4. Current work — புதையல்

Work path: `works/pudhaiyal/`

Scan-established identity:

- title: **புதையல்**
- author: **கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.**
- publisher: **அன்புப் பதிப்பகம்**
- place: **பொறையார் :: தஞ்சை மாவட்டம்**
- edition: **மூன்றாம் பதிப்பு**
- date: **செப்டம்பர், 1961**

Original source filename: `TVA_BOK_0064097_புதையல்.pdf`

Known source facts:

- original attached size: **502,895,096 bytes**
- Tamil Digital Library bibliographic extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original SHA-256: **pending**
- source PDF committed: **No**

The former `150 pages total` conclusion was wrong. Scans 1–150 are only a known prefix and scan 150 is not treated as the source ending.

---

# 5. Split-source workflow

## Part 001

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- source scans: **1–49**
- state: **COMPLETE / VERIFIED**
- committed: **No**

## Part 002

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- source scans: **50–98**
- split pages: **49**
- runtime size: **54,231,932 bytes**
- visibly printed pages represented: **48–96**
- state: **COMPLETE / VERIFIED — 49 / 49**
- committed: **No**

These split files are access derivatives of the controlling edition, not new editions.

---

# 6. Current Tamil state

Canonical page records exist through scan **98**.

- page records created: **98**
- verified: **98** — scans 1–98
- needs-review: **0**
- unresolved readings through scan 98: **0**
- known-prefix rows not-started: **52**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records now include:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-063-072.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-073-082.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-083-098.md` — **16/16 verified**

---

# 7. Latest reconciliation — part 002 scans 83–98

The user's Iteration 8 was mapped to original scans **83–98 / printed pages 81–96** and compared directly with split part 002 pages **34–49**.

Important results:

- scan 83 begins `தற்கும் சரியாக இருந்தது`, completing scan 82's terminal `ஆக்ரமிப்ப` as `ஆக்ரமிப்பதற்கும்`; scan 83 closes chapter 8;
- scan 84 / printed 82 begins chapter **9** and prints `வேகமான நடையிலே`, not clean-baseline `வேசமான நடையிலே`;
- scan 85 supports continuous `விட்டதாகவும்`;
- scan 87 prints `அந்த உப்பரிகைத் தளத்தில்` and ends inside `நினைவுச் சுருள்கள்` at `நினைவுச் சுருள்`;
- scan 88 begins `கள்`, completing that word; a sentence supplied in the clean baseline (`குரலிலே அதிகாரம், முரட்டுத் தனம் இருந்ததே தவிர கனிவு இல்லை.`) is not printed on the inspected source page and was therefore not inserted into the canonical text;
- scan 91 prints continuous `முடியாதா`;
- scan 92 / printed 90 closes chapter 9;
- scan 93 / printed 91 begins chapter **10**;
- scan 97 supports `சில விநாடிகள்` and `தெவிட்டுவதற்கு`;
- scan 98 is visibly printed page **96**, not 98, and carries a four-star internal separator.

The part-002 filename range `50-98` refers to original **scan numbers**, not printed page numbers.

---

# 8. Structural state established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins;
- scan 22 — chapter 1 → 2;
- scan 30 — chapter 2 → 3;
- scan 40 — chapter 3 → 4;
- scan 46 — four-star internal transition;
- scan 47 — embedded historical tale begins inside chapter 4;
- scan 52 — chapter 4 → 5;
- scan 60 — chapter 5 → 6;
- scan 68 — chapter 6 closes;
- scan 69 — chapter 7 begins;
- scan 75 — chapter 7 → 8;
- scan 83 — chapter 8 closes;
- scan 84 — chapter 9 begins;
- scan 92 — chapter 9 closes;
- scan 93 — chapter 10 begins;
- scan 98 — four-star internal transition within chapter 10; **not chapter end and not source end**.

The embedded historical tale is an internal textual unit of the novel, not a separate work.

Later chapter checkpoints and the true ending remain provisional until later split pages are directly processed.

---

# 9. Translation gate

Do not begin English translation until:

- exact full-source extent is known;
- every scan has a page record;
- every body page is visually audited;
- unresolved readings are resolved or explicitly documented;
- page map / metadata / README / handover agree;
- full structure and cross-page continuity are checked;
- Tamil `audit.md` passes;
- source PDFs remain outside the repository;
- assembled Tamil `sections/` layer is created and checked.

---

# 10. Exact next activity

Part 002 is complete. The next activity is to obtain/use the next split beginning with **original scan 99 / printed page 97**.

When it is available:

1. inspect the first page directly before accepting continuity;
2. treat scan 98's four-star separator as an internal transition, not the novel ending;
3. continue chapter 10 from scan 99;
4. preserve physical scan and printed-page boundaries;
5. apply only source-established wording / punctuation / spacing corrections;
6. update page map / README / metadata / handover at the next activity boundary.

Do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant next split. Current live GitHub state and this handover govern over stale summaries.