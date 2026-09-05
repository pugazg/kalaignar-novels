# Transcription / Source Audit — வெள்ளிக்கிழமை

## Source

- file: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`
- scans: **179**
- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`
- source PDF committed: **No**

## Current gate

| Check | Status |
|---|---|
| Source identity inspected | **complete for intake** |
| Actual PDF page count / size / checksum | **complete** |
| Initial scan manifest | **179 / 179 represented** |
| Canonical page records | **8 / 179** |
| Front matter scans 1–3 | **verified** |
| Body transcription | **scans 4–8 verified** |
| Printed-page map | **partial — scan 4 unnumbered; scans 5–8 = printed 4–7** |
| Chapter map | **partial — Chapters 1–8 directly located** |
| Historical-glyph policy | **enabled; first body batch passed** |
| Full Tamil source audit | **not started** |
| Assembled Tamil | **not started** |
| English translation | **blocked until Tamil gate passes** |

## Front-matter intake verification

Scans 1–3 remain verified: cover identity, copy-specific donor label, and second-edition publication/price/printer page were directly inspected. Copy-specific material is not merged into novel text.

## First narrative batch — scans 4–8

**Result: PASS / VERIFIED page records created.**

- scan 4: source title + Chapter 1; no visible printed page number;
- scan 5: printed page 4;
- scan 6: printed page 5;
- scan 7: printed page 6;
- scan 8: printed page 7.

All five scans were directly compared at enlarged/native resolution. Later markings were excluded from printed transcription; notably the underline beneath `சிந்தாமணி` on scan 6 is recorded as copy-specific marking only.

### Historical-glyph checkpoint

Every page was checked against the known minimum set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The held scan-8 cluster was resolved without contextual guessing. Native/enlarged pixels and same-edition `ளை` evidence establish:

- source-supported Unicode: **`களைத்துத் தூங்கிவிட்டால்`**;
- historical family: **`ளை`**;
- action: character identity decoded only; source wording not modernized.

No global replacement was used. No unresolved glyph cluster remains in scans 4–8.

### Cross-page continuity

- scan 4 `ஏதோ` continues into scan 5;
- scan 5 `அவைகளே` continues into scan 6 `கேலிக்குரியதாக ஆக்கிய என்னை...`;
- scan 8 `கிழக்கு வானம் வெளுக்கத்` continues into scan 9.

The canonical page layer retains these physical boundaries instead of moving text across scans.

## Source marks / contamination risks

Later underlining, ticks and handwriting occur in the copy and must remain outside canonical novel text. Age-toning, stains, bleed-through and uneven ink remain glyph-reading risks for later batches.

## Structural checkpoint

Directly confirmed chapter openings: scan 4 (1), 13 (2), 23 (3), 33 (4), 45 (5), 52 (6), 60 (7), 68 (8). This is not yet the full chapter map.

## Unresolved project items

- scans **9–179** canonical transcription;
- printed-page mapping for remaining scans;
- chapter openings after Chapter 8;
- historical-glyph decisions for later body pages;
- later cross-page joins and any damaged clusters;
- final complete Tamil audit, assembly and English stages.

## Exact next activity

Process scans **9–12** to continue and finish the current Chapter 1 span before scan 13 / Chapter 2. Perform direct high-resolution transcription, historical-glyph checks, page-map/status synchronization and a narrow commit. English work remains blocked.
