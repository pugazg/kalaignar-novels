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
- directly processed / verified: **scans 50–72 / printed pages 48–70**
- not yet transcribed in this split: **scans 73–98**
- committed: **No**

These split files are access derivatives of the controlling edition, not new editions.

---

# 6. Current Tamil state

Canonical page records exist through scan **72**.

- page records created: **72**
- verified: **72** — scans 1–72
- needs-review: **0**
- unresolved readings through scan 72: **0**
- known-prefix rows not-started: **78**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md` — **13/13 verified**
- `works/pudhaiyal/notes/visual-fidelity-scans-063-072.md` — **10/10 verified**

---

# 7. Latest reconciliation — part 002 scans 50–72

The user supplied Iteration 5 for printed pages 48–60 and Iteration 6 for printed pages 61–70. Both were re-mapped to physical source scans and compared directly with part 002.

## Important physical-boundary correction

The supplied Iteration 5 accidentally continued one line into the next printed page. Source inspection establishes:

- scan 62 / printed 60 ends with: `எத்தனை மணியிருக்கும்?`
- scan 63 / printed 61 begins with: `அதற்குத்தான் ஆறுமாதமாக...`

`0062-pudhaiyal.md` and `0063-pudhaiyal.md` now preserve the actual boundary.

## Other source-established corrections

- scan 54 / printed 52: `கேட்கிறீயா`, not `சேட்கிறீயா`;
- scan 56 / printed 54: `இமைகளைத்`, not `இமைகளை த்`;
- scan 60 / printed 58: continuous `மனிதராயிற்றே`, removing the clean transcription's line-break artefact;
- scan 69 / printed 67: chapter numeral **`7`**, not `1`;
- scan 69: `எவ்வளவுதான்`, not `எவ்வளவுதான`;
- scan 70 / printed 68: `காரணத்தால்`, not `சாரணத்தால்`;
- scan 70: `குறும்புக்காரக் கிழவா`;
- scan 71 / printed 69: `பெரிய மனுஷா`, not `பெரிமனுஷா`.

Source punctuation and dash pauses were restored through scans 50–72 instead of retaining the clean extraction's systematic `..`, `!.`, `?.` punctuation.

No ambiguous old-print word was changed merely from expectation.

---

# 8. Structural state established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins;
- scan 22 / printed 20 — chapter 1 → 2 transition;
- scan 30 / printed 28 — chapter 2 → 3 transition;
- scan 40 / printed 38 — chapter 3 → 4 transition;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — embedded historical tale begins inside chapter 4;
- scan 52 / printed 50 — chapter 4 → 5 transition;
- scan 60 / printed 58 — chapter 5 → 6 transition;
- scan 68 / printed 66 — chapter 6 closes;
- scan 69 / printed 67 — chapter 7 begins;
- scan 72 / printed 70 — chapter 7 continues and ends mid-sentence at `ஆத்திரத்தோடு,`.

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

Continue directly with **scan 73 / printed page 71** from part 002.

Before advancing:

1. preserve scan 72's unfinished ending `ஆத்திரத்தோடு,`;
2. inspect scan 73's opening and verify the continuation;
3. transcribe the next controlled batch from part 002;
4. preserve physical page boundaries and printed punctuation;
5. apply only visually established source-vs-baseline corrections;
6. update page map / README / handover at the next meaningful activity boundary.

Do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.
