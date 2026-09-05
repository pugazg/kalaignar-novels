# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: the edition uses multiple historical/pre-reform Tamil glyph forms associated with the pre-reform orthography. Earlier transcription sometimes copied the apparent modern visual shape instead of decoding the historical character identity. The first confirmed failure involved historical `றா` being read as apparent modern `று`, but the risk is broader than that single form.

Because this can affect earlier pages as well as later pages, all canonical records currently created for scans **1–27** remain `needs-review`. No page in this work is to be marked `verified` while this audit is open. Future page records must also remain `needs-review` unless the user explicitly authorizes a different verification policy.

## User-supplied Periyar reform reference

The user supplied a clear `பழைய வடிவம்` → `சீர்திருத்த வடிவம்` chart. It establishes the following **13 modern Unicode targets** that must be recognized when their historical glyph forms occur in this source:

| No. | Modern Unicode identity | Example shown by supplied chart |
|---:|---|---|
| 1 | `ணா` | `அண்ணா` |
| 2 | `ணை` | `அணை` |
| 3 | `ணொ` | `மண்ணொடு` |
| 4 | `ணோ` | `கண்ணோடு` |
| 5 | `லை` | `தலை` |
| 6 | `ளை` | `களை` |
| 7 | `றா` | `சிறார்` |
| 8 | `றொ` | `மற்றொரு` |
| 9 | `றோ` | `காற்றோடு` |
| 10 | `னா` | `மன்னா` |
| 11 | `னை` | `வினை` |
| 12 | `னொ` | `என்னொடு` |
| 13 | `னோ` | `என்னோடு` |

The historical shapes themselves are visual typeforms, not separate Unicode characters to copy literally into canonical Markdown. When the source uses one of these old forms, the archive must encode the glyph's **actual Tamil identity** using the corresponding modern Unicode sequence above.

This chart is a decoding reference, not permission for normalization. The source scan remains controlling for whether a given occurrence is actually one of these historical forms.

## Confirmed historical-glyph corrections

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

These are **glyph-identification corrections**, not spelling modernization.

## Other transcription corrections discovered during the retrospective pass

| Scan | Printed page | Earlier reading | Source-supported reading | Kind |
|---:|:---:|---|---|---|
| 4 | — | `சமூகத்தின்` | `சமுதாயத்தின்` | lexical/source-text correction, not 13-form conversion |
| 5 | — | `அற்பிய` | `அரும்பிய` | lexical/source-text correction, not 13-form conversion |
| 5 | — | `சமூகமும்` | `சமுதாயம்` | lexical/source-text correction, not 13-form conversion |

## Retrospective pass progress

| Scan | Printed page | Historical-glyph pass | Corrections from this pass | Page status |
|---:|:---:|---|---|---|
| 1 | — | complete for this one-page pass | none | `needs-review` |
| 2 | — | complete for this one-page pass | none | `needs-review` |
| 3 | — | complete for this one-page pass | none; five historical-form occurrences already encoded correctly | `needs-review` |
| 4 | — | complete for this one-page pass | `சமூகத்தின்` → `சமுதாயத்தின்`; six historical-form occurrences confirmed | `needs-review` |
| 5 | — | complete for this one-page pass | `அற்பிய` → `அரும்பிய`; `சமூகமும்` → `சமுதாயம்`; four historical-form occurrences confirmed | `needs-review` |

### Scan 1 finding

The cover was re-read in full from an enlarged source render against the complete 13-form reference. No printed occurrence requires historical-form conversion and no glyph-identity correction is required. Copy-specific handwriting was not converted into canonical printed text.

### Scan 2 finding

No original 1953 source-work printed narrative or publication text is present. The later printed gift label was checked against all 13 known forms; no conversion was required. Handwriting remains copy-specific and was not guessed or used as source-work evidence.

### Scan 3 finding

Five historical-form occurrences were positively established:

- `ஜூலை` — historical `லை`;
- `விலை` — historical `லை`;
- `விற்பனை` — historical `னை`;
- `சைனா` — historical `னா`;
- `சென்னை` — historical `னை`.

All five were already encoded with the correct modern Unicode identities, so no lexical replacement was required.

### Scan 4 finding

The full `திரை விலக` page was re-read at enlarged/high resolution.

Historical-form occurrences positively identified:

- `தலையிடுவது` — historical `லை`;
- `பார்ப்பதில்லை` — historical `லை`;
- `ஆனால்` — historical `னா`;
- `எத்தனையோ` — historical `னை`;
- `ஆனாலும்` — historical `னா`;
- `கருணாநிதி` — historical `ணா`.

All six were already represented with the correct modern Unicode identities.

The pass exposed one earlier non-glyph transcription error: the source reads `சமுதாயத்தின்`, not `சமூகத்தின்`. The canonical scan-4 record was corrected accordingly.

### Scan 5 finding

The full `பதிப்புரை` page was re-read at enlarged/high resolution.

Historical-form occurrences positively identified:

- `அதினைச்` — historical `னை`;
- `அதினை` — historical `னை`;
- `கருத்துக்களைத்` — historical `ளை`;
- `மூலை` — historical `லை`.

All four were already represented with the correct modern Unicode identities.

The pass exposed two independent earlier source-text errors:

- `அற்பிய` → **`அரும்பிய`**;
- `சமூகமும்` → **`சமுதாயம்`**.

Both corrections are supported directly by the enlarged scan and are not 13-form normalizations. Source-specific `விலாவொடியப்`, `ஏற்பட்டச்`, and `அவர்கட்கு` were rechecked and retained unchanged.

**Progress:** **5 / 27** existing canonical scans reviewed in the retrospective pass; scans **6–27** remain pending. All reviewed pages remain `needs-review` and are not called verified.

## Audit rule

For this source, do not decide a glyph from ordinary visual resemblance alone. For every page:

1. inspect the complete glyph cluster at native/high resolution;
2. explicitly check for the user-supplied historical forms corresponding to `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
3. identify whether the printed shape is a pre-reform Tamil glyph rather than a modern glyph that merely looks similar;
4. compare same-edition occurrences where useful;
5. encode the glyph's actual Tamil identity in modern Unicode;
6. do not normalize vocabulary, grammar, punctuation or spelling beyond that glyph identification;
7. if the page audit exposes an independent source-text transcription error, correct it only when the source pixels positively support the change and record it separately from glyph conversion;
8. leave the page `needs-review` even after local corrections while this project-wide audit is open.

A confirmed mapping at one occurrence must **not** be mechanically globalized. Each occurrence must be checked against its source pixels. The 13-form chart is a minimum known reference set, not evidence that no other legacy typographic ambiguity can occur.

## Scope

Retroactive audit required: **scans 1–27**.

Particular attention must be given to all 13 user-supplied historical forms, and to any earlier transcription note that described a suspicious form as an intentional oddity merely because it looked unusual in modern type.

## Gate consequence

- canonical records created: **27 / 49**;
- retrospective historical-glyph pass: **5 / 27 reviewed — scans 1–5**;
- page status for scans 1–27: **27 `needs-review`**;
- `verified`: **0**;
- `partial`: **0**;
- `not-started`: **22**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Do **not** continue to scans 28–32 yet.

Audit **scan 6 only** next, using the same one-page method: inspect the entire scan at enlarged/high resolution, check every printed glyph cluster against the complete 13-form historical reference, make only pixel-supported corrections, record findings with provenance, keep the page `needs-review`, then stop.
