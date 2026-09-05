# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: historical/pre-reform Tamil typeforms can be mistaken for modern glyphs by visual resemblance. All canonical records for scans **1–27** remain `needs-review`. No page may be marked `verified` while this audit is open unless the user explicitly changes that policy.

## User-supplied Periyar reform reference

Known historical forms must be decoded to these modern Unicode identities:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The chart is a decoding reference, not permission to modernize spelling, grammar, punctuation, vocabulary, or wording. Every occurrence must be checked against its own source pixels; no global replacement is allowed.

## Confirmed historical-glyph corrections

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

## Other source-text corrections found during the retrospective pass

| Scan | Printed page | Earlier reading | Source-supported reading | Kind |
|---:|:---:|---|---|---|
| 4 | — | `சமூகத்தின்` | `சமுதாயத்தின்` | lexical/source-text correction |
| 5 | — | `அற்பிய` | `அரும்பிய` | lexical/source-text correction |
| 5 | — | `சமூகமும்` | `சமுதாயம்` | lexical/source-text correction |
| 7 | 6 | `உள்ளங்களை` | `உள்ளங்களே` | line-break/source-text correction |
| 12 | 11 | `தாவும்போது பயப்பட்ட பூனை` | `தாவும்போது பயப்படாத பூனை` | lexical/source-text correction |
| 12 | 11 | `பயப்பட்டது போல -` | `பயப்பட்டதுபோல -` | source-word/spacing correction |

## Retrospective pass progress

| Scan | Printed page | Historical-glyph pass | Result | Page status |
|---:|:---:|---|---|---|
| 1 | — | complete | no correction | `needs-review` |
| 2 | — | complete | no source-work print; later label checked, no correction | `needs-review` |
| 3 | — | complete | `லை / னை / னா` occurrences already encoded correctly | `needs-review` |
| 4 | — | complete | six historical-form occurrences confirmed; one lexical correction | `needs-review` |
| 5 | — | complete | four historical-form occurrences confirmed; two lexical corrections | `needs-review` |
| 6 | — | complete | five historical-form occurrences confirmed; no text correction | `needs-review` |
| 7 | 6 | complete | seven historical-form occurrences confirmed; one source-text correction | `needs-review` |
| 8 | — | complete | nine historical-form occurrences confirmed; no text correction | `needs-review` |
| 9 | 8 | complete | eleven historical-form occurrences checked; no text correction | `needs-review` |
| 10 | 9 | complete | historical `றா` in `என்றான்` plus other forms checked; no text correction | `needs-review` |
| 11 | 10 | complete | `னா / னை / லை / ளை` forms checked; no text correction | `needs-review` |
| 12 | 11 | complete | historical forms encoded correctly; two independent text corrections | `needs-review` |
| 13 | 12 | complete | `ணை / னை / னா / லை` forms checked; no text correction | `needs-review` |

### Scans 1–8

Earlier one-page findings remain authoritative in their canonical page records. Confirmed historical-typeform decoding through scan 8 includes examples such as `ஜூலை`, `விற்பனை`, `கருணாநிதி`, `போகிறாள்`, and `நினைத்தவாறே`. Independent corrections through scan 8 are recorded in the table above. All scans remain `needs-review`.

### Scan 9 / printed page 8

The complete page was re-read at enlarged/high resolution. Positive historical-form occurrences checked include `ஊஞ்சலை` (`லை`), `உந்தலினால்` (`னா`), `கண்ணம்மாளைக்` (`ளை`), `இல்லை` (`லை`), `ஆனாலும்` (`னா`), `வேதனையைக்` (`னை`), `கருணை` (`ணை`), `அவளைத்` (`ளை`), `தூக்கினார்` (`னா`), `கூட்டினால்` (`னா`), and the final `அவளை` (`ளை`). All were already encoded correctly. No text correction required.

### Scan 10 / printed page 9

The complete page was re-read at enlarged/high resolution. Historical forms checked include `பேசாமலில்லை` (`லை`), four occurrences of `ஆனால்` (`னா`), `மாட்டினான்` (`னா`), `விசாரணைக்கு` (`ணை`), `போகவில்லை` (`லை`), `பூனை` (`னை`), `என்றான்` (`றா`), `குறையவில்லை` (`லை`), `நிலை` (`லை`), `சோதிக்கநினைப்பதில்லை` (`னை` + `லை`), and `கருதத்தானில்லை` (`லை`). The old `றா` shape in `என்றான்` was checked specifically against the user-supplied chart. No correction required.

### Scan 11 / printed page 10

Historical forms checked include three `ஆனால்` (`னா`) occurrences, `வீரனைக்` (`னை`), `காணவில்லையே` (`லை`), two `மாடுகளை` (`ளை`) occurrences, `காளை` (`ளை`), `வெதறலைத்` (`லை`), and `மனவேதனையைக்` (`னை`). All were already encoded correctly. No independent text correction required. The final `கிடப்ப` remains a physical continuation into scan 12.

### Scan 12 / printed page 11

Historical forms checked include `அணைப்பு` (`ணை`), two `ஆனால்` (`னா`) occurrences, `பூனை` (`னை`), `துளைத்தபோது` (`ளை`), `நிலை` (`லை`), `பின்னால்` (`னா`), `நினைத்தாள்` (`னை`), `நினைப்பு` (`னை`), `பேனா` (`னா`), and `இல்லையே` (`லை`). These historical identities were already encoded correctly.

Two independent transcription errors were corrected directly from the enlarged source:

- `தாவும்போது பயப்பட்ட பூனை` → **`தாவும்போது பயப்படாத பூனை`**;
- `பயப்பட்டது போல -` → **`பயப்பட்டதுபோல -`**.

The source-supported corrected sequence is `உறியில் தாவும்போது பயப்படாத பூனை உறியை அடைந்ததும் பயப்பட்டதுபோல - சுவரைத் துளைத்தபோது...`.

### Scan 13 / printed page 12

Historical forms checked include `பண்ணையில்` (`ணை`), `வேலை` (`லை`), `தலையாரி` (`லை`), `விலை` (`லை`), `இல்லை` (`லை`), `போனால்` (`னா`), `நினைத்துவிட்டார்` (`னை`), `நினைத்துவிட்டதாகக்` (`னை`), `தன்னைக்` (`னை`), `அறியவில்லை` (`லை`), `கற்சிலை` (`லை`), `கருத்துமில்லை` (`லை`), and `கவனிப்புமில்லை` (`லை`). All were already encoded correctly. No independent text correction required.

**Progress: 13 / 27 existing canonical scans reviewed; scans 14–27 pending.** All reviewed pages remain `needs-review`.

## Audit rule

For every page:

1. inspect complete glyph clusters at enlarged/native resolution;
2. check all 13 known historical forms explicitly;
3. identify character identity rather than copying apparent modern shape;
4. compare same-edition occurrences where useful;
5. encode the proven identity in modern Unicode;
6. do not normalize anything beyond proven glyph identity;
7. correct any independent transcription mismatch only with positive source-pixel support and record it separately;
8. keep the page `needs-review` while the work-wide audit remains open.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Gate consequence

- canonical records: **27 / 49**;
- retrospective historical-glyph pass: **13 / 27 — scans 1–13**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Audit **scans 14–18 / printed pages 13–17** next as a five-page batch. Inspect each page independently at enlarged/high resolution against the complete 13-form reference, make only pixel-supported corrections, record each result, keep every page `needs-review`, and stop after scan 18.
