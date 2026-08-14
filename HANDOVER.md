# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- State at handover preparation: commit `6176f04240f47ec6fa51e58846033fc754b73f0c`
- This `HANDOVER.md` is committed immediately after that state; when resuming, verify current `main` before making changes.

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

- scans 4–7: **பலிபீடம் நோக்கி**
- scans 8–33: **ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை**
- scan 34: blank/back matter

`ராயசம் வெங்கண்ணா` begins with source-printed cinema-style credits. Preserve these exactly; do not recast them into modern prose or bibliographic language inside the transcription.

## Completed work

Repository initialized with:

- `README.md`
- `NOVEL_PROCESSING_GUIDE.md`
- `works/balipeedam-nokki/README.md`
- `works/balipeedam-nokki/metadata/source.md`
- `works/balipeedam-nokki/indexes/page-map.md`
- `works/balipeedam-nokki/pages/0001-cover.md`
- `works/balipeedam-nokki/pages/0002-title-page.md`
- `works/balipeedam-nokki/pages/0003-publisher-note.md`

Page status:

- scan 1: `verified`
- scan 2: `verified`
- scan 3: `needs-review`
- scans 4–34: `not-started`

The full 34-page scan manifest has been created.

## Open issue — scan 3

One short phrase in the final paragraph of the publisher's note remains visually unresolved. The page file explicitly marks the gap instead of guessing from context. Resolve it only through clearer direct visual inspection; do not use inferred meaning as replacement text.

## Next exact activity

Process **scans 4–7 as one batch**.

This batch should:

1. create page records `0004` through `0007`;
2. transcribe the complete `பலிபீடம் நோக்கி` textual unit;
3. preserve source spelling, punctuation, paragraph boundaries and unusual forms;
4. record handwritten/library/bleed-through marks separately from printed text;
5. direct-visual-verify every page before marking it `verified`;
6. update `indexes/page-map.md`, work `README.md`, root `README.md`, and this handover.

Do **not** begin scan 8 / `ராயசம் வெங்கண்ணா` until scans 4–7 are complete and the first unit has passed its page-level visual check.

## Translation gate

English translation is blocked until the complete Tamil transcription and direct visual audit of the source are finished. Translation/review files should not be created during the current stage.
