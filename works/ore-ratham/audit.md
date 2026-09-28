# Transcription / Translation Audit — ஒரே இரத்தம்

## Current gate

| Check | Current result |
|---|---|
| Source identity inspected | **COMPLETE / PASS** |
| File integrity recorded | **COMPLETE** |
| Physical source pages | **136** |
| Full page manifest | **NOT STARTED — NEXT** |
| Canonical page records | **0 / 136** |
| Historical-glyph policy | **ACTIVE** |
| Pass1 Tamil transcription | **NOT STARTED** |
| Pass2A source review | **BLOCKED** |
| Pass2B independent review | **BLOCKED** |
| Pass3 visual/structural review | **BLOCKED** |
| Whole-work Tamil audit | **BLOCKED** |
| Assembled Tamil | **BLOCKED** |
| English translation | **BLOCKED** |

## Source

- source ID — `TVA_BOK_0064094`
- filename — `TVA_BOK_0064094_ஒரே_இரத்தம்.pdf`
- SHA-256 — `4480aa8b95fb16b8f8b9a1877514774e2b13ee7ce9b496a9a4121027625c3426`
- file size — **170,923,550 bytes**
- pages — **136**
- source PDF committed — **No**

## Historical-glyph rule

Apply `../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Mandatory minimum check set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

**Glyph decoding is not spelling correction.**

Historical character identity must be established from source pixels, with same-edition comparison where useful. Do not infer from modern lexical expectation, do not global-replace, and do not silently modernize wording.

## Known source structure — provisional

Directly confirmed:
- scan1 cover;
- scan2 publication details;
- scan3 `பதிப்புரை`;
- scan4 author photograph/handwritten text;
- scan5 narrative chapter1;
- scan131 displayed chapter23;
- scan135 / printed133 closes narrative with `(முற்றும்)`;
- scan136 back cover.

The intervening printed-folio map and chapter-start map are not yet complete.

## Verification policy

During baseline transcription:
- `not-started` — no canonical text;
- `partial` — incomplete text;
- `needs-review` — baseline exists but has not passed visual verification;
- `verified` — only after explicit visual-verification gate;
- `blocked` — source evidence insufficient.

No page may be promoted merely because OCR or language context appears plausible.

## Exact next activity

Complete the **136-scan page map**, then open Pass1.
