# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- State immediately before this handover update: commit `f238adfcd783a19c5aec020c3cc077ddb4a7931a`
- When resuming, verify current `main` before making changes.

## Permanent startup rule

Before any new work:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read the target work's `README.md`, `metadata/source.md`, and `indexes/page-map.md`.
4. Inspect current repository state and continue existing work rather than creating duplicates.
5. Treat the source scan as controlling authority.
6. Do **not** upload/commit source PDF files to this repository.

## Current source

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**

Source filename (external to repository):

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

- SHA-256: `c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`
- File size: 69,724,254 bytes
- Scan pages: 34
- Edition visible in scan: முதல் பதிப்பு, ஏப்ரல் 1947
- Publisher visible in scan: எரிமலைப் பதிப்பகம், துறையூர்
- PDF committed to repository: **No**

## Internal textual units

- scans 4–7: **பலிபீடம் நோக்கி** — complete + verified
- scans 8–33: **ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை** — not started
- scan 34: blank/back matter

### Source-title correction

Direct inspection of scan 8 confirms the printed title **`ராயசம் வெங்கண்ணு`**. Earlier working references to `ராயசம் வெங்கண்ணா` were corrected in source metadata, README files and the page manifest before transcription of that unit begins.

`ராயசம் வெங்கண்ணு` begins with source-printed cinema-style credits. Preserve these exactly; do not recast them into modern prose or bibliographic language inside the transcription.

## Completed work

Repository currently contains:

- `README.md`
- `NOVEL_PROCESSING_GUIDE.md`
- `works/balipeedam-nokki/README.md`
- `works/balipeedam-nokki/metadata/source.md`
- `works/balipeedam-nokki/indexes/page-map.md`
- page records `0001` through `0007`

Page status:

- scan 1: `verified`
- scan 2: `verified`
- scan 3: `needs-review`
- scans 4–7: `verified`
- scans 8–34: `not-started`

Totals:

- page records created: **7 / 34**
- verified: **6**
- needs-review: **1**
- not-started: **27**

## Completed batch — scans 4–7

The complete `பலிபீடம் நோக்கி` textual unit has been transcribed and directly compared with enlarged source scans.

Source-specific readings deliberately preserved include:

- scan 5: `குதுமன்றி`;
- scan 5: `மாடலவறையவன்`;
- scans 5 → 6: page-break fragment `அணுக்` + `களிலிருந்து`;
- scan 6: `மாடலவறையன்`, `தணலில்`, and printed `அன்பு(?)`;
- scans 6 → 7: `உதிர` + `ஆறுகளைப் பாருங்கள்`;
- scan 7: `வேதியர் வெங்கண்ணு!` and the final printed star ornament.

Do not normalize these forms from memory or modern usage.

## Open issue — scan 3

One short phrase in the final paragraph of the publisher's note remains visually unresolved. The page file explicitly marks the gap instead of guessing from context. Resolve it only through clearer direct visual inspection; do not use inferred meaning as replacement text.

## Next exact activity

Process **scans 8–12 as one batch** — the first `ராயசம் வெங்கண்ணு` batch.

This batch should:

1. create page records `0008` through `0012` using the `rayasam-vengannu` filename slug already reserved in `indexes/page-map.md`;
2. verify scan 8 title **`ராயசம் வெங்கண்ணு`**, subtitle **`தஞ்சை சரித்திரக் கதை`**, `எரிமலை 'ரிலீஸ்'`, credit lines and rights line character by character;
3. transcribe scans 8–12 page by page from the controlling scan;
4. preserve cinematic narration, dialogue, scene/action description, punctuation, historical spelling, source-specific names and unusual grammar;
5. record bleed-through, stamps, handwritten marks or other copy-specific marks separately from printed text;
6. direct-visual-verify each page before marking it `verified`;
7. update `indexes/page-map.md`, work `README.md`, root `README.md`, and this handover when the batch is complete.

## Translation gate

English translation remains blocked until the complete Tamil transcription and direct visual audit of the source are finished. Translation/review files should not be created during the current stage.
