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

**Mandatory rule after the discovered visual-audit errors:** when the user supplies a transcription, use it as the baseline. Do not replace it merely because a small renderer preview appears different. For old-print Tamil, inspect the native embedded page image first. If the reading remains ambiguous, mark the exact item `needs-review` and surface it instead of asserting an assistant correction.

`verified` requires dependable direct visual comparison with the scan. A pass later shown to contain assistant hallucinations must be corrected or invalidated.

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
- committed to GitHub: **No**

The split's embedded page images are available at **3146 × 4826** and should be used for fidelity decisions instead of relying only on the smaller preview renderer.

---

# 6. Current Tamil state

Canonical page records exist through scan **32**.

- page records created: **32**
- `verified`: **22** — scans 1–22, after corrected high-resolution re-audit
- `needs-review`: **10** — scans 23–32 after invalidation of the Iteration 3 assistant visual pass
- known-prefix rows `not-started`: **118**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity / correction records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md` — **corrected native-resolution re-audit**
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md` — **invalidated assistant corrections; user Iteration 3 text restored**

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

# 8. Fresh re-audit requested by user — printed pages 10–20 / scans 12–22

After the user identified hallucinated corrections in Iteration 3, they explicitly requested that the earlier pages 10–20 also be checked again.

The range was reopened using the **native embedded scan images**, not just the preview renderer.

## Re-audit result

Scan 12 / printed page 10 was rechecked and did not require rollback.

Several earlier assistant corrections in scans 13–21 were confirmed to be wrong and have now been fixed in the canonical page files:

- scan 13: `அப்போதுதான்` → **`அப்போது தான்`**;
- scan 13: `கையிலும்` → **`கையிலேயும்`** (`கையிலே` / `யும்` across a printed line break);
- scan 15: `நம்பிக்கையுண்டு` → **`நம்பிக்கை யுண்டு`**;
- scan 15: `அதனால்தான்` → **`அதனால் தான்`**;
- scan 15: `தன உயிருக்கு` → **`தன உயிருக்கே`**;
- scan 15: `அவர்களும் வந்துவிட்டார்கள்` → **`அவர்களும் வந்து விட்டார்கள்`**;
- scan 16: `அடங்கிவிட்டதாகத் தானே` → **`அடங்கி விட்டதாகத் தானே`**;
- scan 17: `இடையிலேதான்` → **`இடையிலே தான்`**;
- scan 17: `ஆராய்ந்து விட்டோமே` → **`ஆராய்ந்து விட்டோம்`**;
- scan 17: `சரியாகத்தான்` → **`சரியாகத் தான்`**;
- scan 19: `அவ்வளவுதான்` → **`அவ்வளவு தான்`**;
- scan 19: `நாளை தவற` → **`நாளைத் தவற`**;
- scan 21: `அடிபட்டுவிட்டதால்` → **`அடிபட்டு விட்டதால்`**.

The re-audit also established that some earlier corrections were genuine and should remain:

- scan 13: no printed page number visible;
- scan 14: `மருங்கப் பள்ளத்தின்`, `பூமியைத் தோண்டிப்`;
- scan 15: `மெளனமாய்` / `மெளனமாக்கியது`;
- scan 16: inscription continues through `கம்மாளர் கண்ணிலே......`;
- scan 18: four opening dialogue lines `அத்தான்!`, `கண்ணே!`, `ராஜா!`, `என்னடி ராஜாத்தி!`; later `மறக்க மாட்டீர்களே கண்ணே!`;
- scan 19: `வெளவாலிடம்` / `வெளவால்`;
- scan 22: chapter 1 closes and chapter 2 begins on the same scan.

Scans **1–22 remain `verified` only because this fresh native-resolution re-audit has now replaced the flawed earlier assumptions.**

Detailed corrected report:

`works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`

---

# 9. Iteration 3 correction — scans 23–32 / printed 21–30

The previous assistant pass claimed a series of scan-supported corrections against the user's Iteration 3 transcription. The user rejected those corrections and stated that the supplied transcription is correct and the assistant had hallucinated.

Repository action already taken:

- restored `pages/0023-pudhaiyal.md` through `pages/0032-pudhaiyal.md` to the user's supplied Iteration 3 transcription;
- removed the assistant-inferred replacement readings;
- downgraded scans 23–32 from `verified` to `needs-review`;
- replaced the fidelity report with an invalidation record.

Do not reintroduce the withdrawn Iteration 3 substitutions as verified source readings.

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

**Do not process scans 33–42 yet.** The next unresolved text range remains scans **23–32**.

When work resumes:

1. use the user's restored Iteration 3 transcription as the baseline;
2. inspect native embedded scan images at full available resolution;
3. do not silently replace a user reading from visual inference;
4. flag any genuinely uncertain glyph/spacing/punctuation as `needs-review`;
5. preserve page boundaries and chapter transitions;
6. continue full-source reconciliation as later split parts arrive;
7. do not start English translation.

---

# 12. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.
