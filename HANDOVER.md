# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
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

## Critical structural correction after full read

**`பலிபீடம் நோக்கி` is one continuous work across scans 4–33.**

The previous handover incorrectly treated scans 8–33 (`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை`) as a separate textual entity. Do not repeat that split.

Source-supported structure:

1. **Scans 4–7:** opening ideological / polemical frame built around சேரன் செங்குட்டுவன், Aryan ritual power, Tamil self-respect and the `பலிபீடம்` metaphor.
2. **Scan 7:** narrator explicitly introduces the next material as a film-like lesson: `வேதியர் வெங்கண்ணு! திரைப் படமாக உருப்பெற்றிருக்கிறார்... படக்காட்சி ஆரம்பமாகிறது பாருங்கள். படம் உங்களுக்கு ஒரு பாடம் தரட்டும்.`
3. **Scan 8:** internal title-card page — `ராயசம் வெங்கண்ணு`, `தஞ்சை சரித்திரக் கதை`, `எரிமலை 'ரிலீஸ்'`, screenplay/dialogue-style credits and rights line.
4. **Scans 9–29:** the embedded Thanjavur historical episode is narrated in cinematic / screenplay-like form.
5. **Scan 30:** explicit exit from the internal film: `படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா? பலிபீடம் நோக்க...`
6. **Scans 31–33:** direct concluding address returns fully to the main `பலிபீடம்` argument and closes the work.

Archival rule:

```text
work: balipeedam-nokki
```

must be used for **every body page scans 4–33**.

`ராயசம் வெங்கண்ணு` is **not** a separate work, repository item, translation project or metadata entity. Preserve the printed heading only as an internal `section` / cinematic-sequence label.

Direct enlarged inspection of scan 8 reads the printed heading as `ராயசம் வெங்கண்ணு`; preserve that source form in transcription.

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

## Completed transcription batch — scans 4–7

The opening segment has been transcribed and directly compared with enlarged source scans.

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

Continue **the same `பலிபீடம் நோக்கி` work** with scans **8–12**.

This batch should:

1. create continuous page records `0008-balipeedam-nokki-05.md` through `0012-balipeedam-nokki-09.md`;
2. keep `work: "balipeedam-nokki"` on every page;
3. use `section` to identify the embedded `ராயசம் வெங்கண்ணு` cinematic-historical sequence without promoting it to work-level identity;
4. verify scan 8's internal title card, subtitle `தஞ்சை சரித்திரக் கதை`, `எரிமலை 'ரிலீஸ்'`, credit lines and rights line character by character;
5. transcribe scans 8–12 page by page from the controlling scan;
6. preserve cinematic narration, dialogue, scene/action description, punctuation, historical spelling, source-specific names and unusual grammar;
7. record bleed-through, stamps, handwritten marks or other copy-specific marks separately from printed text;
8. direct-visual-verify each page before marking it `verified`;
9. update `indexes/page-map.md`, work `README.md`, root `README.md`, and this handover when the batch is complete.

## Translation gate

English translation remains blocked until the complete Tamil transcription and direct visual audit of the source are finished. Translation/review files should not be created during the current stage.
