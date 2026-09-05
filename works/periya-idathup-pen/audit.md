# Transcription Audit — பெரிய இடத்துப் பெண்

## Audit scope

Source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`  
Source pages: **49**  
Source PDF committed to repository: **No**

This audit is **open**. Canonical transcription exists through scan 27, but historical/pre-reform Tamil glyph misidentification invalidated the former verification state.

## Current gate

| Check | Current result |
|---|---|
| Source identity inspected | complete |
| Scan pages mapped | **49 / 49** |
| Canonical page records | **27 / 49** |
| `verified` | **0** |
| `needs-review` | **27 — scans 1–27** |
| `partial` | **0** |
| `not-started` | **22 — scans 28–49** |
| Historical-glyph retrospective audit | **OPEN — 23 / 27 reviewed; scans 1–23** |
| Tamil source layer | **NOT PASSED** |
| Assembled Tamil | **BLOCKED** |
| English translation | **BLOCKED** |

## Historical-glyph rule

Known user-supplied Periyar-reform reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Decode historical character identity into modern Unicode only after direct source-pixel confirmation. Do not global-replace and do not modernize spelling, grammar, punctuation, vocabulary, or wording. Every page remains `needs-review` while this audit is open.

## Confirmed historical-glyph corrections

| Scan | Printed page | Earlier | Correct |
|---:|:---:|---|---|
| 14 | 13 | `ஆவிலைக்` | `ஆவலைக்` |
| 14 | 13 | `நின்றூர்` | `நின்றார்` |
| 16 | 15 | `போகிறயே` | `போகிறாயே` |
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

## Independent source-text corrections found during re-audit

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`;
- scan 7 / printed 6: `உள்ளங்களை` → `உள்ளங்களே`;
- scan 12 / printed 11: `தாவும்போது பயப்பட்ட பூனை` → `தாவும்போது பயப்படாத பூனை`;
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`;
- scan 19 / printed 18: `செக்கச் செவேலென்றோன்றின.` → `செக்கச் செவேலென்றேதோன்றின.`.

Full occurrence-level tracking is maintained in [`HISTORICAL_GLYPH_AUDIT.md`](HISTORICAL_GLYPH_AUDIT.md).

## Retrospective audit progress

- **Scans 1–13:** completed previously; all remain `needs-review`.
- **Scan 14 / printed 13:** historical `லை` corrected `ஆவிலைக்` → `ஆவலைக்`; historical `றா` corrected `நின்றூர்` → `நின்றார்`.
- **Scan 15 / printed 14:** full 13-form sweep; no canonical text correction; `உத்தண்டி` remains an internal heading.
- **Scan 16 / printed 15:** historical `றா` corrected `போகிறயே` → `போகிறாயே`.
- **Scans 17–18 / printed 16–17:** full 13-form sweep; no canonical text correction.
- **Scan 19 / printed 18:** direct source-text correction to `செக்கச் செவேலென்றேதோன்றின.`; `கண்ணம்மா` remains an internal heading.
- **Scans 20–21 / printed 19–20:** known `நன்றாகத்` / `நன்றாகத்தான்` `றா` corrections re-confirmed; no new correction.
- **Scans 22–23 / printed 21–22:** full 13-form sweep; no canonical text correction.

Retrospective progress is therefore **23 / 27 scans reviewed; scans 24–27 pending**.

## Existing transcription coverage

- scans 1–7: front matter records exist, all `needs-review`;
- scans 8–27: narrative records exist, all `needs-review`;
- scans 28–49: `not-started`.

Existing page-boundary joins and internal-heading observations remain provisional evidence only; they do not confer verification.

## Boundary observations retained provisionally

- scan 11 `கிடப்ப` + scan 12 `தாகக்` → `கிடப்பதாகக்`;
- scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!`;
- scan 15 `தெரிந்` + scan 16 `தது.` → `தெரிந்தது.`;
- scan 16 `நம்` + scan 17 `வீட்டு` → `நம் வீட்டு`;
- scan 17 `கண்டது` + scan 18 `போலத்தானே!`;
- scan 18 `என்` + scan 19 `றேன்.`;
- scan 19 `என்` + scan 20 `னிலே` → `என்னிலே`;
- scan 21 `காலக்ஷேபங்` + scan 22 `கூட`;
- scan 22 `மட்` + scan 23 `டும்` → `மட்டும்`.

## Structural finding

The source continues as one work, `பெரிய இடத்துப் பெண்`. Internal headings `உத்தண்டி` and `கண்ணம்மா` remain internal structure only; this does not alter page status.

## Next activity

Audit **scans 24–27 / printed pages 23–26** as the remaining four-page retrospective batch. Re-confirm the known scan-24 `றா` corrections from the source, inspect each page against all 13 historical forms, make only pixel-supported corrections, record each result, and keep every page `needs-review`. Stop after scan 27.
