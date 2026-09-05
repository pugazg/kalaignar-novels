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
| Canonical page records | **3 / 179** |
| Front matter scans 1–3 | **verified** |
| Body transcription | **not started** |
| Printed-page map | **partial / sampled only** |
| Chapter map | **partial — Chapters 1–8 directly located** |
| Historical-glyph policy | **enabled** |
| Full Tamil source audit | **not started** |
| Assembled Tamil | **not started** |
| English translation | **blocked until Tamil gate passes** |

## Front-matter intake verification

### Scan 1 — PASS

Direct visual inspection confirms title, author, publisher and address. No printed page number is visible.

### Scan 2 — PASS

The scan is largely blank with a later donor label `பேராசிரியர். தி.வ. மெய்கண்டார் அவர்களின் / அன்பளிப்பு`. It is copy-specific matter and is not merged into novel text.

### Scan 3 — PASS

Direct visual inspection confirms `இரண்டாம் பதிப்பு: 1968`, rights line, price `ரூ. 2-50`, and `சக்திவேல் பிரஸ், திருச்சிராப்பள்ளி-2.` No printed page number is visible.

## Historical-glyph gate

The source uses older Tamil print and must be read under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Every body page must explicitly consider:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

A visual resemblance is not enough to correct a word. Positive source-pixel evidence is required; otherwise retain/mark `needs-review`. No global replacement is permitted.

## Source marks / contamination risks

Sampled body pages show later underlining, ticks and handwriting in addition to the printed text. These marks must be kept outside canonical novel transcription. Age-toning, stains, faint bleed-through and uneven ink may also affect glyph reading.

## Structural checkpoint

Directly confirmed early chapter openings:

1. scan 4;
2. scan 13;
3. scan 23;
4. scan 33;
5. scan 45;
6. scan 52;
7. scan 60;
8. scan 68.

This is not yet the full chapter map. The source is provisionally one continuous novel; later structure must be established from direct source inspection rather than assumed.

## Unresolved intake items

- direct printed-page number for every remaining scan;
- chapter openings after Chapter 8;
- full page-by-page transcription;
- historical-glyph decisions for body pages;
- cross-page word/sentence joins;
- any damaged or genuinely unreadable source clusters;
- final complete Tamil audit.

## Exact next activity

Transcribe scans **4–8** from the source image. For each scan:

1. inspect at enlarged/native resolution;
2. record visible printed page number only if actually printed;
3. separate later marks from printed text;
4. apply the historical-glyph pre-correction check;
5. create/update canonical page records;
6. update `indexes/page-map.md` and this audit;
7. keep any uncertain cluster `needs-review` rather than guessing.

English work remains blocked.