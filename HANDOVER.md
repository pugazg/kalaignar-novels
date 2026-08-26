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

# 2. Controlling-source and user-transcription policy

Authority order:

1. actual scan page;
2. source-printed bibliographic/page information;
3. canonical Tamil `pages/` records;
4. audited Tamil `sections/`;
5. verified English translation;
6. metadata/review documentation.

Do not silently modernize, repair, normalize, reconstruct or improve source-supported Tamil. Preserve spelling, punctuation, spacing, colloquial forms, typographical oddities, page boundaries and internal structure. Separate printed text from handwriting, provenance marks, underlining, bleed-through and scan artefacts.

**Important correction to workflow after Iteration 3:** when the user supplies a transcription, use it as the baseline during visual checking. If an old-print glyph, spacing or punctuation appears to disagree, do not silently replace the user's reading with an assistant inference. Flag that exact point as `needs-review` and surface it for confirmation. This is mandatory for ambiguous old Tamil glyphs and degraded print.

`verified` requires dependable direct visual comparison with the scan. A visual pass later shown to contain assistant hallucinations must be invalidated and must not remain `verified`.

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
- `verified`: **22** — scans 1–22
- `needs-review`: **10** — scans 23–32 after invalidation of the assistant visual-correction pass
- known-prefix rows `not-started`: **118**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity / correction records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md` — **invalidated previous correction claims; user Iteration 3 transcription restored**

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

# 8. Iteration 3 correction — scans 23–32 / printed 21–30

The previous assistant pass claimed a series of scan-supported corrections against the user's Iteration 3 transcription. The user explicitly rejected those corrections and stated that their supplied transcription is correct and the assistant had hallucinated.

The previous correction claims are therefore **withdrawn**.

Repository action already taken:

- restored `pages/0023-pudhaiyal.md` through `pages/0032-pudhaiyal.md` to the user's supplied Iteration 3 transcription;
- removed the previous assistant-inferred replacement readings from the canonical page layer;
- downgraded scans 23–32 from `verified` to `needs-review` because the assistant's visual verification is invalid;
- replaced the previous fidelity report with an invalidation/audit record.

Do not reintroduce claims such as `மதகின் உள்ளேயிருந்தவர்களுக்கு`, `அவர்களே நோக்கி`, `அவன் முதுகில்`, `அவர்களேதான்`, `அவளே அவன்...`, `தும்பைப்பூ`, or other previous assistant substitutions as verified readings merely because they appeared in the invalidated pass. The user's supplied forms now remain canonical for this range pending any future confirmed source review.

Structural page boundaries remain preserved; textual disagreements are not to be silently resolved by the assistant.

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

**Pause at the Iteration 3 correction boundary. Do not process scans 33–42 until the user accepts this restored state or supplies the next iteration.**

When work resumes:

1. treat the user's supplied transcription as the baseline;
2. use the scan for verification, not for speculative replacement;
3. when a glyph/word appears different, flag the exact item as `needs-review` rather than altering canonical text;
4. preserve page boundaries and chapter transitions;
5. continue full-source reconciliation as later split parts arrive;
6. do not start English translation.

---

# 11. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.
