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

# 2. Controlling-source policy

Authority order:

1. actual scan page;
2. source-printed bibliographic/page information;
3. canonical Tamil `pages/` records;
4. audited Tamil `sections/`;
5. verified English translation;
6. metadata/review documentation.

Do not silently modernize, repair, normalize, reconstruct or improve source-supported Tamil. Preserve spelling, punctuation, spacing, colloquial forms, typographical oddities, page boundaries and internal structure. Separate printed text from handwriting, provenance marks, underlining, bleed-through and scan artefacts.

User-supplied transcription and OCR are aids only. `verified` requires direct visual comparison with the scan.

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

Work path:

`works/pudhaiyal/`

Scan-established identity:

- title: **புதையல்**
- author: **கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.**
- publisher: **அன்புப் பதிப்பகம்**
- place: **பொறையார் :: தஞ்சை மாவட்டம்**
- edition: **மூன்றாம் பதிப்பு**
- date: **செப்டம்பர், 1961**

Original source filename:

`TVA_BOK_0064097_புதையல்.pdf`

Known original-source facts:

- original attached size: **502,895,096 bytes**
- Tamil Digital Library bibliographic extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original SHA-256: **pending**
- source PDF committed: **No**

Important correction: the earlier `150 pages total` conclusion was wrong. Scans 1–150 are only a known prefix. Scan 150 / printed page 148 is **not** treated as the end of the source.

Correction note:

`works/pudhaiyal/notes/source-page-count-reconciliation.md`

---

# 5. Split-source workflow

Received access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split pages: **49**
- split size available in chat runtime: **52,760,797 bytes**
- committed to GitHub: **No**

This is an access derivative of the controlling scan, not a new edition.

---

# 6. Current Tamil state

Canonical page records now exist through scan **32**.

- page records created: **32**
- `verified`: **32**
- `needs-review`: **0**
- unresolved readings in scans 1–32: **0**
- known-prefix rows `not-started`: **118**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity reports:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`

---

# 7. Structural state established so far

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

# 8. Latest fidelity pass — scans 23–32 / printed 21–30

The user's Iteration 3 transcription was compared letter by letter with split part 001. The draft was not copied verbatim.

Important source-supported corrections include:

- scan 23: `மதகின் உள்ளேயிருந்தவர்களுக்கு`;
- scan 24: `சிறு ஆறுதல் அளித்தது`, `சற்று ஆறுதல் அளித்தது`, source oddity `அவர்களே நோக்கி`, and `அப்போது தான்`;
- scan 26: `உண்மை தான்`, `மிக கூர்மையாக`, `அவனது நடையிலே வேகம் குறைந்தது`;
- scan 27: first prayer `உதவுகிறது.` ends with a full stop;
- scan 28: `அவன் முதுகில்`, `துல்யமாகத்`;
- scan 29: `அவர்களேதான்`, `கடல் பார்த்துக்`, `அவளே அவன் காப்பாற்றித் தீர வேண்டும்`;
- scan 30: chapter `2` → `3` transition occurs on the same scan;
- scan 31: `மூர்ச்சை யடைந்தான்`, `சுவை யிருக்கத்தான்`, `அவனைத் தழுவிக்`; apparent missing punctuation after `யடைந்தான்` is preserved;
- scan 32: `தும்பைப்பூ`; page ends mid-sentence at `காலைத்`.

Physical continuities checked:

- scan 23 → 24: `நானும் சக்கிலியும்` / `இந்தப் பக்கம் போறோம்...`;
- scan 24 → 25: `கடற்கரை வந்து` / `விடும்.`;
- scan 26 → 27: `பூரணமாக விளங்குவதற்கு` / `உதவியாக நிலவு...`;
- scan 29 → 30: `சாவுக் கண்ணீர்!` / `என்ற ஒலிதான் அது!`;
- scan 32 ends `காலைத்`; continuation belongs only to scan 33.

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

**Process the user's next iteration covering printed pages 31–40, corresponding to scans 33–42 in split part 001.**

Required sequence:

1. compare scans 33–42 directly against the supplied transcription, letter by letter;
2. create `pages/0033-pudhaiyal.md` through `pages/0042-pudhaiyal.md`;
3. preserve exact source spelling, punctuation, spacing, dialogue and physical page boundaries;
4. preserve the chapter `3` → chapter `4` transition at scan **40 / printed page 38**;
5. mark any genuinely uncertain glyph `needs-review`, never guess;
6. update `indexes/page-map.md`, work README and this handover;
7. continue full-source extent reconciliation as later split parts arrive;
8. do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.
