# Transcription / Translation Audit — ஒரே இரத்தம்

## Current gate

| Check | Current result |
|---|---|
| Source identity inspected | **COMPLETE / PASS** |
| File integrity recorded | **COMPLETE** |
| Physical source pages | **136** |
| Full page manifest | **COMPLETE / PASS — 136 / 136** |
| Canonical page records | **9 / 136** |
| Historical-glyph policy | **ACTIVE** |
| Displayed chapter starts | **23 / 23 mapped** |
| Repeated physical captures | **2 — scans118–119** |
| Processing split manifest | **14 / 14 VERIFIED** |
| Pass1 Tamil transcription | **ACTIVE — Batch1 scans1–10; 5 text-complete / 4 partial / 1 pending** |
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

## Source structure — mapped / authoritative

- scans1–4 — front matter / paratext;
- scans5–135 — narrative physical captures;
- distinct printed narrative folios — **5–133 / 129**;
- displayed chapters — **1–23 / all starts mapped**;
- scans118–119 — repeated physical captures of printed pp.116–117;
- scan135 / printed133 — narrative closes with `(முற்றும்)`;
- scan136 — back cover / source endpoint.

See `indexes/page-map.md` for the one-row-per-scan manifest and `SOURCE_SPLIT_MANIFEST.md` for processing splits.

## Verification policy

During baseline transcription:
- `not-started` — no canonical text;
- `partial` — incomplete text;
- `needs-review` — baseline exists but has not passed visual verification;
- `verified` — only after explicit visual-verification gate;
- `blocked` — source evidence insufficient.

No page may be promoted merely because OCR or language context appears plausible.

## Exact next activity

Resolve **Pass1 Batch1 holds — scans4, 7, 8, 9, 10** before scan11.
