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
- inspect the actual split-source page image whenever available;
- isolate every apparent source-vs-baseline difference and recheck it individually;
- change canonical text only after the scan establishes the reading;
- after reconciliation, perform a final direct page-by-page visual comparison before using `verified`.

If the native split is **not available**, use the full-PDF renderer only for safe structural facts such as visible printed page number, chapter transition and physical page boundary. Do **not** silently impose small-print glyph or punctuation readings from the reduced renderer. Preserve the user baseline and keep the page `needs-review` until native split verification is possible.

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

Available access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split pages: **49**
- split size available in chat runtime: **52,760,797 bytes**
- previously established embedded page-image dimensions: **3146 × 4826**
- transcription / direct visual audit: **49 / 49 COMPLETE / VERIFIED**
- committed to GitHub: **No**

User-named next split:

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

Current tool-visible file state:

- this part-002 PDF is **not attached in the current conversation**;
- the original full PDF remains available through the renderer for scans 50–150;
- therefore scans 50–62 have only a renderer-level structural check, not native letter-by-letter verification.

User supplied Iteration 5 for **printed pages 48–60 / scans 50–62**. Those 13 pages have been created as baseline records with `status: needs-review`.

---

# 6. Current Tamil state

Canonical page records exist through scan **62**.

- page records created: **62**
- `verified`: **49** — scans 1–49
- `needs-review`: **13** — scans 50–62
- known-prefix rows `not-started`: **88**
- split part 001: **COMPLETE / VERIFIED**
- scans 50–62: **user baseline loaded; native part-002 audit pending**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md` — corrected re-audit
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md` — final reconciliation; 10/10 verified; unresolved 0
- `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md` — split part 001 completion; 17/17 verified; unresolved 0
- `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md` — Iteration 5 baseline loaded; native part-002 verification pending

---

# 7. Corrected audit history — scans 12–32

After hallucinated assistant corrections were discovered, scans 12–22 were reopened and several assistant errors were corrected. The four dialogue lines on scan 18 and chapter-2 transition on scan 22 were reconfirmed.

Scans 23–32 were then re-audited from the restored user baseline, source-vs-baseline candidates were isolated and repeatedly checked, source punctuation was reconciled, and a final page-by-page comparison was completed.

Important final points include:

- `அவர்களே தான்` rather than the withdrawn assistant candidate `அவர்களேதான்`;
- `அவளை அவன் காப்பாற்றித் தீர வேண்டும்` rather than the withdrawn assistant candidate `அவளே அவன்...`;
- `பழைய பிரார்த்தனையில்`;
- `அவனைத் தழுவிக்`;
- `தும்பைப்பூ`;
- chapter `2` → `3` transition on scan 30 / printed page 28.

Scans **1–32 are verified only on the basis of the corrected/reconciled state.**

---

# 8. Iteration 4 / split part 001 completion — scans 33–49

The user supplied a continuous Iteration 4 described as “Pages 31–49.” Physical source inspection establishes that this text corresponds to **source scans 33–49 / visibly printed pages 31–47**. The split PDF itself ends at scan 49 / printed page 47.

The continuous transcription was mapped back to physical scan boundaries and each page was directly visually compared with split part 001.

Source-established corrections include:

- scan 33: printed `“யார்?”` restored where the clean transcription had only `“?”`;
- scan 37: `கிழவர்`, not clean-baseline `கிழ்வர்`;
- scan 38: `தோணிக்கு`, not `தொணிக்கு`;
- scan 41: `அவன் திறக்காமலாவது`;
- scan 43: `புற்று நோய்`, not `புத்து நோய்`;
- source punctuation / dash pauses restored instead of the clean transcription's systematic `..`, `!.`, `?.` forms.

Physical boundaries explicitly preserved include scan 47 `சந்தோஷ` → scan 48 `மாக...` and scan 48 `எப்படிப்` → scan 49 `யாவது...`.

Final status for scans 33–49:

- `verified`: **17 / 17**
- unresolved readings: **0**
- canonical page records: `0033-pudhaiyal.md` through `0049-pudhaiyal.md`
- final report: `works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`

---

# 9. Iteration 5 baseline — scans 50–62 / printed 48–60

The user supplied Iteration 5 naming `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` and covering printed pages 48–60. The actual part-002 file is not currently tool-visible in this conversation.

The controlling full-PDF renderer was therefore used only to establish safe structural facts and physical page boundaries. The user's wording and punctuation were retained as the canonical **baseline** without silent assistant corrections.

Renderer-established structure:

- scan 50 / printed 48 continues scan 49's unfinished embedded historical tale;
- scan 52 / printed 50 closes chapter `4` and begins chapter `5` on the same physical page;
- scan 60 / printed 58 closes chapter `5` and begins chapter `6` on the same physical page;
- scans 61–62 / printed 59–60 continue chapter `6`.

Physical boundaries preserved include:

1. scan 52 `அந்த` → scan 53 `வீட்டிற்கு...`;
2. scan 54 `போயி` → scan 55 `யைப்பாரு...`;
3. scan 55 `வெளியேறியிருந்தாலும்-` → scan 56 `அவர்கள்...`;
4. scan 56 `பிறகு` → scan 57 `பாடினாள்...`;
5. scan 57 `ஆசைப்` → scan 58 `படுகிறோம்...`.

Current status for scans 50–62:

- records created: **13 / 13**
- status: **needs-review**
- native part-002 audit: **pending**
- no claim of zero unresolved textual readings is made yet
- preliminary report: `works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`

Do **not** promote these pages to `verified` from the reduced full-PDF renderer alone.

---

# 10. Structural state established so far

Within the processed / renderer-checked prefix:

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter `1` begins; no printed page number visible;
- scan 22 / printed 20 — chapter `1` closes and chapter `2` begins on the same physical scan;
- scan 30 / printed 28 — chapter `2` closes and chapter `3` begins on the same physical scan;
- scan 40 / printed 38 — chapter `3` closes and chapter `4` begins on the same physical scan;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — மாயாண்டியின் embedded historical tale about the மருங்கப்பள்ளம் கொல்லர் begins inside chapter `4`;
- scan 49 / printed 47 — split part 001 ends mid-sentence at `அவள் அப்பனும்,`;
- scan 50 / printed 48 — renderer confirms continuation of that embedded tale;
- scan 52 / printed 50 — renderer confirms chapter `4` → `5` transition; native part-002 audit pending;
- scan 60 / printed 58 — renderer confirms chapter `5` → `6` transition; native part-002 audit pending.

The embedded historical tale is an **internal textual unit of chapter 4**, not a separate work.

Known-prefix chapter checkpoints after scan 62 remain provisional until the relevant later split pages are actually inspected. The real ending remains open.

---

# 11. Translation gate

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

# 12. Exact next activity

Make `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` available in this conversation.

Then:

1. inspect native split scans 50–62 / printed pages 48–60;
2. use the current page records as the user-supplied baseline;
3. isolate and recheck every apparent source-vs-baseline disagreement;
4. apply only source-established spelling / spacing / punctuation differences;
5. perform a final page-by-page comparison;
6. promote a page to `verified` only when that direct native check passes;
7. synchronize the fidelity note, page map, work README, root README and this handover.

Only after scans 50–62 are verified should the project advance to scan **63 / printed page 61** onward.

Do not start English translation.

---

# 13. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.