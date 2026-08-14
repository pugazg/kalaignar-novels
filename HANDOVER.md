# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- State immediately before this handover update: commit `c5c205aa995492d4ba8a98167924fd38b83d46ce`
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

## Critical structural rule

**`பலிபீடம் நோக்கி` is one continuous work across scans 4–33.**

Do not treat `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` as a separate work. It is the embedded cinematic-historical sequence within the same novel.

Source-supported structure:

1. **Scans 4–7:** opening ideological / polemical frame.
2. **Scan 7:** narrator explicitly introduces the next material as a film-like lesson.
3. **Scan 8:** internal title-card page — `ராயசம் வெங்கண்ணு`, `தஞ்சை சரித்திரக் கதை`, `எரிமலை ‘ரிலீஸ்’`, screenplay/dialogue-style credits and `விநியோக உரிமை`.
4. **Scans 9–29:** embedded Thanjavur historical episode in cinematic / screenplay-like form.
5. **Scan 30:** `படம் முடிந்துவிட்டது... பாடம் கற்றுக்கொண்டீர்களா? பலிபீடம் நோக்க...` — explicit return to the main frame.
6. **Scans 31–33:** concluding direct address and close of the same work.

Archival rule for all body pages scans 4–33:

```text
work: balipeedam-nokki
```

`ராயசம் வெங்கண்ணு` may appear only as an internal `section` label preserving the printed heading.

## Completed work

Repository currently contains page records `0001` through `0012`.

Page status:

- scan 1: `verified`
- scan 2: `verified`
- scan 3: `needs-review`
- scans 4–9: `verified`
- scan 10: `needs-review`
- scans 11–12: `verified`
- scans 13–34: `not-started`

Totals:

- page records created: **12 / 34**
- verified: **10**
- needs-review: **2**
- not-started: **22**

## Completed transcription batch — scans 4–7

The opening segment has been transcribed and directly compared with enlarged source scans.

Source-specific readings deliberately preserved include:

- scan 5: `குதுமன்றி`;
- scan 5: `மாடலவறையவன்`;
- scans 5 → 6: page-break fragment `அணுக்` + `களிலிருந்து`;
- scan 6: `மாடலவறையன்`, `தணலில்`, and printed `அன்பு(?)`;
- scans 6 → 7: `உதிர` + `ஆறுகளைப் பாருங்கள்`;
- scan 7: `வேதியர் வெங்கண்ணு!` and the final printed star ornament.

## Completed transcription batch — scans 8–12

These pages continue the same `பலிபீடம் நோக்கி` work and begin its internal film-like historical sequence.

Created:

- `pages/0008-balipeedam-nokki-05.md`
- `pages/0009-balipeedam-nokki-06.md`
- `pages/0010-balipeedam-nokki-07.md`
- `pages/0011-balipeedam-nokki-08.md`
- `pages/0012-balipeedam-nokki-09.md`

Key verified source details:

- scan 8 title card: `ராயசம் வெங்கண்ணு` / `தஞ்சை சரித்திரக் கதை`;
- scan 8 credit vocabulary: `எரிமலை ‘ரிலீஸ்’`, `டைரக்ஷன், திரைக்கதை அமைப்பு, வசனம்`, `விநியோக உரிமை`;
- scan 9: darbar scene and marriage-alliance dialogue with `மன்னரு நாயக்கர்`, `குமார தாத்தாச்சார்யா`, `விசயராகவர்` / `விசய` role labels;
- scan 10: `பெருக்கெடுக்கும் ரத்தவெள்ளத்தில்` and the unusual current reading `மித்தானமத்தனுக்குக்`;
- scan 11: battle sequence, `சிகப்புத்தண்ணீர்`, bracketed `[விசயராகன் ஆசையோடு]`, and cinematic action narration;
- scan 12: battle climax, `குளோசப்பில்`, `முணு முணுக்கிறது`, and the beginning of Vijay Raghava's dying speech.

The final quotation on scan 12 remains open and continues onto scan 13. Do not insert a closing quotation mark or reconstruct the continuation from memory.

## Open review items

### Scan 3

One short phrase in the final paragraph of the publisher's note remains visually unresolved. The page file explicitly marks the gap instead of guessing from context.

### Scan 10

The printed lexical form in `மகள் அந்த மித்தானமத்தனுக்குக் கொடுத்து...` is unusual. The current direct visual reading is `மித்தானமத்தனுக்குக்`. It has **not** been normalized or replaced from context, but the page remains `needs-review` for a later character-level audit.

## Next exact activity

Continue **the same `பலிபீடம் நோக்கி` work** with scans **13–17**.

This batch should:

1. create `pages/0013-balipeedam-nokki-10.md` through `pages/0017-balipeedam-nokki-14.md`;
2. continue the open dying-speech quotation from scan 12 directly into scan 13;
3. keep `work: "balipeedam-nokki"` on every page;
4. use `section: "ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை"` only as the internal sequence label;
5. preserve cinematic narration, dialogue, scene/action description, punctuation, historical spelling, source-specific names and unusual grammar;
6. record bleed-through, stamps, handwritten marks or other copy-specific marks separately from printed text;
7. direct-visual-verify each page before marking it `verified`;
8. update `indexes/page-map.md`, work `README.md`, root `README.md`, and this handover when the batch is complete.

## Translation gate

English translation remains blocked until the complete Tamil transcription and direct visual audit of the source are finished. Translation/review files should not be created during the current stage.
