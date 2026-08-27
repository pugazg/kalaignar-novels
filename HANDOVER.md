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
6. continue an existing work rather than duplicating it;
7. inspect the actual scan before accepting metadata or transcription;
8. never commit source PDFs or split source PDFs.

---

# 2. Controlling-source and supplied-transcription policy

Authority order:

1. actual scan page;
2. source-printed bibliographic/page information;
3. canonical Tamil `pages/` records;
4. audited Tamil `sections/`;
5. verified English translation;
6. metadata/review documentation.

Do not silently modernize, repair, normalize, reconstruct or improve source-supported Tamil. Preserve spelling, punctuation, spacing, colloquial forms, typographical oddities, page boundaries and internal structure. Separate printed text from handwriting, provenance marks, underlining, bleed-through and scan artefacts.

## Mandatory visual rule after discovered audit hallucinations

When the user supplies a transcription:

- use it as the comparison baseline;
- do **not** treat it as higher authority than the scan;
- do **not** replace it merely because a preview appears different;
- inspect the split-source page image whenever available;
- isolate every apparent source-vs-baseline difference and recheck it individually;
- change canonical text only after the scan establishes the reading;
- perform a final direct page-by-page visual comparison before using `verified`.

OCR, grammar expectations, catalogue text and modern spelling are aids only.

---

# 3. Completed reference implementation — பலிபீடம் நோக்கி

`works/balipeedam-nokki/`

Final state:

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

Known original-source facts:

- original attached size: **502,895,096 bytes**
- Tamil Digital Library bibliographic extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original SHA-256: **pending**
- source PDF committed: **No**

Important correction: the earlier `150 pages total` conclusion was wrong. Scans 1–150 are only a known prefix; scan 150 is not treated as the end of the source.

---

# 5. Split-source workflow

## Part 001

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split pages: **49**
- transcription / direct visual audit: **49 / 49 COMPLETE / VERIFIED**
- committed to GitHub: **No**

## Part 002

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- represented source scans: **50–98**
- split pages: **49**
- split is now **available in the current conversation**
- Iteration 5 baseline loaded: **scans 50–62 / printed 48–60**
- Iteration 6 baseline loaded: **scans 63–72 / printed 61–70**
- fine-grained wording / spacing / punctuation reconciliation: **pending for scans 50–72**
- committed to GitHub: **No**

---

# 6. Current Tamil state

Canonical page records exist through scan **72**.

- page records created: **72**
- `verified`: **49** — scans 1–49
- `needs-review`: **23** — scans 50–72
- known-prefix rows `not-started`: **78**
- split part 001: **COMPLETE / VERIFIED**
- split part 002: **AVAILABLE; baselines loaded through scan 72**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-063-072.md`

---

# 7. Corrected audit history — scans 12–49

Earlier assistant visual-correction errors were identified and withdrawn. Scans 12–22 and 23–32 were re-audited from the source / restored user baseline. Scans 33–49 were then mapped to physical split-part-001 pages and directly checked.

Standing lesson: apparent old-print Tamil differences must be isolated and rechecked; never silently replace the user's baseline from expectation.

Scans **1–49 are verified only on the corrected/reconciled state.**

---

# 8. Part 002 baseline state — scans 50–72

## Iteration 5 — scans 50–62 / printed 48–60

Records `0050-pudhaiyal.md` through `0062-pudhaiyal.md` exist and remain `needs-review`.

Direct structure:

- scan 50 continues scan 49's embedded historical tale;
- scan 52 / printed 50 closes chapter `4` and begins chapter `5` on the same scan;
- scan 60 / printed 58 closes chapter `5` and begins chapter `6` on the same scan.

The part-002 split is now available, so the old source-availability blocker is resolved. The actual fine-grained text audit still needs to be performed before promotion to `verified`.

## Iteration 6 — scans 63–72 / printed 61–70

Records `0063-pudhaiyal.md` through `0072-pudhaiyal.md` now exist and remain `needs-review`.

Physical boundaries established:

- scan 64 → 65: `மோகினிப் பிசாசு` / `இப்படி யெல்லாம்...`;
- scan 67 → 68: `அவர் அந்த உண்மையை` / `தாண்டவனிடம் வெளியிடவில்லை...`;
- scan 70 → 71: `...கேட்பதற்கு அவன்` / `மிகவும் தயங்கினான்...`;
- scan 71 → 72: `...போய்க் கொண்டிருக்கிறார்கள்` / `என்னுடைய சாவில்...`;
- scan 72 ends at `ஆத்திரத்தோடு,`.

### Unambiguous structural correction

The user's clean Iteration 6 displayed chapter numeral **`1`** before `கள்ளத் தோணிகள் இலங்கைக் கரையை...`.

The source scan 69 / printed page 67 visibly prints **`7`**. The canonical structure uses chapter `7`. No ambiguous word-level source substitution was silently imposed during baseline loading.

---

# 9. Structural state established through scan 72

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter `1` begins; no visible printed page number;
- scan 22 / printed 20 — chapter `1` closes and chapter `2` begins on the same scan;
- scan 30 / printed 28 — chapter `2` closes and chapter `3` begins on the same scan;
- scan 40 / printed 38 — chapter `3` closes and chapter `4` begins on the same scan;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — embedded historical tale begins inside chapter `4`;
- scan 52 / printed 50 — chapter `4` closes and chapter `5` begins;
- scan 60 / printed 58 — chapter `5` closes and chapter `6` begins;
- scan 68 / printed 66 — chapter `6` closes;
- scan 69 / printed 67 — chapter `7` begins.

The embedded historical tale remains an internal textual unit, not a separate work.

Later chapter boundaries and the real ending remain open until the relevant later split ranges are directly reconciled.

---

# 10. Translation gate

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

# 11. Exact next activity

Perform one controlled fine-grained source-fidelity reconciliation of **scans 50–72 / printed pages 48–70** against `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`.

Order:

1. reconcile Iteration 5 scans **50–62** first;
2. reconcile Iteration 6 scans **63–72** second;
3. isolate every source-vs-baseline disagreement;
4. do not alter ambiguous Tamil from expectation;
5. apply only source-established spelling / spacing / punctuation differences;
6. preserve all physical page boundaries;
7. perform a final direct page-by-page comparison;
8. promote individual pages to `verified` only when no unresolved reading remains;
9. synchronize the fidelity notes, page map, work README, root README and this handover.

After that gate, continue from scan **73 / printed page 71**.

Do not start English translation.

---

# 12. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.