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
- do **not** replace it merely because a small preview appears different;
- inspect the native embedded scan image first;
- isolate every apparent source-vs-baseline difference and recheck it individually;
- change canonical text only after the native scan establishes the reading;
- after reconciliation, perform a final direct page-by-page visual comparison before using `verified`.

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

Structural lesson: `ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை` is an internal sequence, not a separate work.

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

Important correction: the earlier `150 pages total` conclusion was wrong. Scans 1–150 are only a known prefix. Scan 150 / printed page 148 is **not** treated as the end of the source.

Correction note: `works/pudhaiyal/notes/source-page-count-reconciliation.md`

---

# 5. Split-source workflow

Received access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split pages: **49**
- split size available in chat runtime: **52,760,797 bytes**
- embedded page-image size: **3146 × 4826**
- committed to GitHub: **No**

The native embedded page image, not the smaller preview renderer, must be used for textual-fidelity decisions.

---

# 6. Current Tamil state

Canonical page records exist through scan **32**.

- page records created: **32**
- `verified`: **32** — scans 1–32
- `needs-review`: **0**
- unresolved readings through scan 32: **0**
- known-prefix rows `not-started`: **118**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md` — corrected native-resolution re-audit
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md` — final native-resolution reconciliation; 10/10 verified; unresolved 0

---

# 7. Corrected native-resolution history — scans 12–22

After hallucinated assistant corrections were discovered, printed pages 10–20 / scans 12–22 were reopened using native **3146 × 4826** page images.

Several earlier assistant corrections were found to be wrong and canonical files were fixed, including:

- `அப்போது தான்`
- `கையிலேயும்`
- `நம்பிக்கை யுண்டு`
- `தன உயிருக்கே`
- `அடங்கி விட்டதாகத் தானே`
- `ஆராய்ந்து விட்டோம்`
- `நாளைத் தவற`
- `அடிபட்டு விட்டதால்`

Some earlier source readings were reconfirmed, including the four dialogue lines on scan 18 and the chapter-2 transition on scan 22.

Scans **1–22 are verified only on the basis of this corrected native-resolution state.**

---

# 8. Final native-resolution reconciliation — scans 23–32 / printed 21–30

The user's restored Iteration 3 transcription was used as the comparison baseline. Native embedded page images were inspected at **3146 × 4826**, discrepancies were isolated and repeatedly checked, source punctuation was reconciled, and a final page-by-page comparison was completed.

Final source-confirmed points include:

- scan 23: `மதகின் உள்ளேயிருந்தவர்களுக்கு`; `முரடர்களின் பேச்சு கூட` confirmed;
- scan 24: `சிறு ஆறுதல் அளித்தது`, `சற்று ஆறுதல் அளித்தது`, `அவர்களே நோக்கி`;
- scan 25: `ஏதோ`, `போனதாகவும்`, `உணர்ந்ததாகவும்` and source dialogue punctuation;
- scan 26: `உண்மை தான்`, `மிக கூர்மையாக`, `அவனது நடையிலே வேகம் குறைந்தது` confirmed;
- scan 27: `உதவுகிறது.` and `குளிர்காற்று` confirmed;
- scan 28: `அவன் முதுகில்`;
- scan 29: `அவர்களே தான்`, `கடல் பார்த்துக் கொண்டிருந்தாள்`, `அவளை அவன் காப்பாற்றித் தீர வேண்டும்`; previous assistant candidates `அவர்களேதான்` and `அவளே அவன்...` are explicitly withdrawn;
- scan 30: `பழைய பிரார்த்தனையில்`; chapter `2` → `3` transition remains on this scan;
- scan 31: punctuation after `மூர்ச்சை யடைந்தான்.`, plus `அவனைத் தழுவிக்`, `முயன்றும்—விடாமல்`, `கட்டிவிட்டார்`;
- scan 32: `தும்பைப்பூ`; physical page ends at `காலைத்`.

The supplied clean transcription's systematic doubled terminal punctuation (`..`, `!.`, `?.`) was replaced only where native visual inspection established the printed punctuation.

Final status for scans 23–32:

- `verified`: **10 / 10**
- unresolved readings: **0**
- canonical page records: synchronized
- final report: `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`

---

# 9. Structural state established so far

Within the known prefix:

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter `1` begins; no printed page number visible;
- scan 22 / printed 20 — chapter `1` closes and chapter `2` begins on the same physical scan;
- scan 30 / printed 28 — chapter `2` closes and chapter `3` begins on the same physical scan;
- scan 40 / printed 38 — chapter `4` begins;
- scan 52 / printed 50 — chapter `5` begins;
- scan 60 / printed 58 — chapter `6` begins;
- scan 69 / printed 67 — chapter `7` begins;
- scan 75 / printed 73 — chapter `8` begins;
- scan 84 / printed 82 — chapter `9` begins;
- scan 93 / printed 91 — chapter `10` begins;
- scan 102 / printed 100 — chapter `11` begins;
- scan 110 / printed 108 — chapter `12` begins;
- scan 119 / printed 117 — chapter `13` begins;
- scan 128 / printed 126 — chapter `14` begins;
- scan 138 / printed 136 — chapter `15` begins;
- scan 146 / printed 144 — chapter `16` begins within the known prefix.

Later chapter boundaries and the real ending remain open until later split parts are supplied.

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

Process the user's next transcription iteration for **scans 33–42 / printed pages 31–40** from `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`.

This batch:

- continues chapter `3` through scans 33–39;
- crosses into chapter `4` at scan 40 / printed page 38;
- continues chapter `4` through scans 41–42.

For every page:

1. use the supplied transcription as baseline;
2. inspect the native embedded page image;
3. preserve the physical scan boundary;
4. isolate and recheck apparent disagreements instead of silently changing the baseline;
5. preserve source-supported punctuation, spacing, spelling and oddities;
6. mark `verified` only after a final direct visual comparison.

Create `pages/0033-pudhaiyal.md` through `pages/0042-pudhaiyal.md`, then synchronize `indexes/page-map.md`, work README, root README and this HANDOVER.

Do not start English translation.

---

# 12. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.