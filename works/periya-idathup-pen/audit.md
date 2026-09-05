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
| Historical-glyph retrospective audit | **OPEN — 13 / 27 reviewed; scans 1–13** |
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
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`.

Full occurrence-level tracking is maintained in [`HISTORICAL_GLYPH_AUDIT.md`](HISTORICAL_GLYPH_AUDIT.md).

## Retrospective audit progress

- **Scans 1–8:** completed previously; all remain `needs-review`.
- **Scan 9 / printed 8:** complete; historical `லை / ளை / னா / னை / ணை` occurrences checked; no text correction.
- **Scan 10 / printed 9:** complete; historical `றா` in `என்றான்` checked explicitly plus other `ணை / னை / னா / லை` forms; no text correction.
- **Scan 11 / printed 10:** complete; `னா / னை / லை / ளை` forms checked; no text correction.
- **Scan 12 / printed 11:** complete; historical forms encoded correctly; two independent source-text corrections made.
- **Scan 13 / printed 12:** complete; `ணை / னை / னா / லை` forms checked; no text correction.

### Scan 12 correction detail

Direct enlarged source inspection shows:

`உறியில் தாவும்போது பயப்படாத பூனை உறியை அடைந்ததும் பயப்பட்டதுபோல - சுவரைத் துளைத்தபோது...`

The previous canonical reading had both `பயப்பட்ட பூனை` and `பயப்பட்டது போல -`; both have now been corrected to the source-supported wording above.

## Existing transcription coverage

- scans 1–7: front matter records exist, all `needs-review`;
- scans 8–27: narrative records exist, all `needs-review`;
- scans 28–49: `not-started`.

Existing page-boundary joins and internal-heading observations remain provisional evidence only; they do not confer verification.

## Boundary observations retained provisionally

- scan 9 final sentence continues into scan 10;
- scan 11 `கிடப்ப` + scan 12 `தாகக்` → `கிடப்பதாகக்`;
- scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!`;
- scan 15 `தெரிந்` + scan 16 `தது.` → `தெரிந்தது.`;
- scan 16 `நம்` + scan 17 `வீட்டு` → `நம் வீட்டு`;
- later joins through scan 27 remain recorded in the page map/handover and are still provisional until the retrospective pass reaches them.

## Structural finding

The source continues as one work, `பெரிய இடத்துப் பெண்`. Internal headings already observed include `உத்தண்டி` and `கண்ணம்மா`; this does not alter page status.

## Next activity

Audit **scans 14–18 / printed pages 13–17** as the next five-page batch. Inspect each complete page at enlarged/high resolution against all 13 historical forms, make only pixel-supported corrections, record each result, and keep every page `needs-review`. Do not advance beyond scan 18 in that activity.
