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

If the user's supplied iteration ends before the physical source page ends, do **not** infer or reconstruct the omitted remainder. Keep that page `partial` until the missing text is directly transcribed and checked.

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
- visibly printed pages represented: **48–96**
- state: **COMPLETE / VERIFIED — 49 / 49**
- committed: **No**

## Part 003

`TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`

- source scans: **99–147**
- split pages: **49**
- directly processed so far: **scans 99–108 / printed pages 97–106**
- verified: **scans 99–107**
- partial: **scan 108 / printed page 106**
- reason for partial state: supplied Iteration 9 stops after `பேசிக்கொண்டிருந்தான் துக்காராம்.` but the physical page visibly continues
- committed: **No**

These split files are access derivatives of the controlling edition, not new editions.

---

# 6. Current Tamil state

Canonical page records exist through scan **108**.

- page records created: **108**
- verified: **107** — scans 1–107
- partial: **1** — scan 108
- needs-review: **0**
- unresolved readings through verified scan 107: **0**
- known-prefix rows not-started: **42**
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
- `works/pudhaiyal/notes/visual-fidelity-scans-083-098.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-099-108.md` — **9/10 verified; scan 108 partial**

---

# 7. Latest reconciliation — part 003 scans 99–108

The user's Iteration 9 was mapped to original scans **99–108 / printed pages 97–106** and compared directly with split part 003 pages **1–10**.

Important results:

- scan 99 / printed 97 prints `இப்ப யாருடைய பெயரைச் சொன்னேன் தெரியுமா?`; the clean baseline had a second `நான் யாருடைய...`. The page also contains a printed four-star internal transition.
- scan 100 / printed 98 ends inside `தோழர்களைத்` at `தோழர்`; scan 101 begins `களைத்`.
- scan 101 / printed 99 prints `அவரைப் பற்றி நான் நன்கு விசாரிக்கவேண்டும் என்ற, ஒரு ஆவல்...`; the page closes chapter **10**.
- scan 102 / printed 100 begins chapter **11**.
- scan 104 / printed 102 prints `நெடு நாளா பழக்கமா?` and `உடல் வளர்த்து`.
- scan 105 / printed 103 prints `தொண்ணூறு` and the separated `ஆசையா யிருந்தது`.
- scan 106 / printed 104 prints `நான் வரத்தான் வேண்டுமோ?`.
- scan 107 / printed 105 begins `துப்`, completing scan 106's `இழுத்`; it contains a four-star internal scene transition and ends at `கடை`.
- scan 108 / printed 106 begins `யாக`, completing `கடையாக`.
- **Critical gate:** the supplied Iteration 9 text ends part-way through scan 108 after `பேசிக்கொண்டிருந்தான் துக்காராம்.`. The source image has additional printed paragraphs below. Those lines were not guessed or silently imported, so `0108-pudhaiyal.md` is `partial`.

Physical boundary checkpoints:

1. scan 100 `தோழர்` → scan 101 `களைத்`;
2. scan 104 `அல்லது பேரன் பேத்தி` → scan 105 `ஆள் இல்லையே...`;
3. scan 105 `அழைத்துக் கொண்டு` → scan 106 `போக முடியாது...`;
4. scan 106 `இழுத்` → scan 107 `துப்`;
5. scan 107 `கடை` → scan 108 `யாக`.

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
- scan 98 — four-star internal transition within chapter 10;
- scan 101 — chapter 10 closes;
- scan 102 — chapter 11 begins;
- scan 107 — four-star internal transition within chapter 11;
- scan 108 — chapter 11, partial canonical page.

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

Do **not** advance directly to scan 109 yet.

First:

1. reopen **scan 108 / printed page 106** from split part 003;
2. transcribe the remaining lower portion beneath `பேசிக்கொண்டிருந்தான் துக்காராம்.` directly from the source image;
3. perform a full-page letter-by-letter visual comparison of scan 108;
4. if no unresolved reading remains, change `0108-pudhaiyal.md` from `partial` to `verified` and synchronize page-map / README / metadata / handover;
5. only then continue with **scan 109 / printed page 107**.

Do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.