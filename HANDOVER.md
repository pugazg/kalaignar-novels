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
- if the native image and baseline appear to disagree, record the exact candidate as `needs-review` and surface it for explicit reconciliation rather than silently changing canonical text;
- after reconciliation, perform a final direct visual comparison before using `verified`.

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

The native embedded page image, not the smaller preview renderer, should be used for textual-fidelity decisions.

---

# 6. Current Tamil state

Canonical page records exist through scan **32**.

- page records created: **32**
- `verified`: **22** — scans 1–22
- `needs-review`: **10** — scans 23–32
- known-prefix rows `not-started`: **118**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- assembled Tamil layer: **blocked**
- English translation: **blocked**

Fidelity records:

- `works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`
- `works/pudhaiyal/notes/visual-fidelity-scans-013-022.md` — corrected native-resolution re-audit
- `works/pudhaiyal/notes/visual-fidelity-scans-023-032.md` — fresh native-resolution re-audit; canonical user baseline intentionally unchanged pending reconciliation

---

# 7. Corrected earlier re-audit — scans 12–22

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

# 8. Fresh native-resolution re-audit — scans 23–32 / printed 21–30

The user's restored Iteration 3 transcription was used as the baseline. Native embedded page images were inspected at **3146 × 4826**. No OCR reading was treated as authority.

**No canonical body text was changed in this pass.** All ten pages remain `needs-review` until the candidates below are explicitly reconciled.

## High-confidence candidates recorded, not applied

- scan 23: native scan appears to include `மதகின் உள்ளேயிருந்தவர்களுக்கு`; baseline omits the first `மதகின்`;
- scan 24: native scan clearly has `சிறு ஆறுதல் அளித்தது` and `சற்று ஆறுதல் அளித்தது`; baseline uses `ஆறுதலை`;
- scan 24: native image strongly appears to print `அவர்களே நோக்கி`; baseline has `அவர்களை நோக்கி`; kept explicitly unresolved because this was previously disputed;
- scan 28: source `அவன் முதுகில்`; baseline `அவன முதுகில்`;
- scan 29: source `அவர்களேதான்`, `கடல் பார்த்துக் கொண்டிருந்தாள்`, `அவளே அவன் காப்பாற்றித் தீர வேண்டும்`; baseline differs;
- scan 30: source `பழைய பிரார்த்தனையில்`; baseline `பழைய பிரார்ந்தனையில்`;
- scan 31: source word-boundary / dash forms include `அவனைத் தழுவிக்`, `முயன்றும்—விடாமல்`, `கட்டிவிட்டார்`;
- scan 32: source `தும்பைப்பூ தாடியிலே`; baseline `தும்பை பூ தாடியிலே`.

## Confirmed user readings after native recheck

The fresh pass also confirms that some user readings previously changed by the assistant are source-supported, including:

- scan 26: `உண்மை தான்`;
- scan 26: `மிக கூர்மையாக`;
- scan 26: `அவனது நடையிலே வேகம் குறைந்தது`;
- scan 27: first prayer `உதவுகிறது.`;
- scan 27: `குளிர்காற்று`.

## Punctuation issue

The supplied clean transcription systematically contains terminal forms such as `..`, `!.`, and `?.`. The native scan generally prints ordinary single stops, question/exclamation marks, and source dashes/long pauses instead.

This punctuation mismatch is **not yet silently normalized**. It is part of the explicit reconciliation needed before scans 23–32 can be verified.

Detailed report:

`works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`

Page records `0023`–`0032` have been updated only in their review metadata/notes to record that the native-resolution audit is complete; their canonical Tamil body remains the restored user baseline.

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

**Do not process scans 33–42 yet.**

Next action is to reconcile the explicit native-scan candidates for scans **23–32** with the user, including the systematic punctuation issue. Apply only readings the source review confirms, then perform one final native-image page-by-page comparison of scans 23–32 before changing any page to `verified`.

After scans 23–32 are fully reconciled and verified, proceed to the user's next transcription iteration for scans 33–42 / printed pages 31–40.

Do not start English translation.

---

# 12. Fresh-chat rule

Use `NEXT_NOVEL_CHAT_PROMPT.md` together with the relevant split source. Current live GitHub state and this handover govern over stale summaries.