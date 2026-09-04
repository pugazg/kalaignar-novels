# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: the edition uses multiple historical/pre-reform Tamil glyph forms associated with the pre-reform orthography. Earlier transcription sometimes copied the apparent modern visual shape instead of decoding the historical character identity. The first confirmed failure involved historical `றா` being read as apparent modern `று`, but the risk is broader than that single form.

Because this can affect earlier pages as well as later pages, all canonical records currently created for scans **1–27** remain `needs-review`. No page in this work is to be marked `verified` while this audit is open. Future page records must also remain `needs-review` unless the user explicitly authorizes a different verification policy.

## User-supplied Periyar reform reference

The user supplied a clearer `பழைய வடிவம்` → `சீர்திருத்த வடிவம்` chart. It establishes the following **13 modern Unicode targets** that must be recognized when their historical glyph forms occur in this source:

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

## Confirmed corrections

The following corrections are supported by the user's glyph identification and direct source reinspection:

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

These are **glyph-identification corrections**, not spelling modernization.

## Retrospective pass progress

| Scan | Printed page | Historical-glyph pass | Corrections from this pass | Page status |
|---:|:---:|---|---|---|
| 1 | — | complete for this one-page pass | none | `needs-review` |
| 2 | — | complete for this one-page pass | none | `needs-review` |
| 3 | — | complete for this one-page pass | none; five historical-form occurrences already encoded correctly | `needs-review` |

### Scan 1 finding

The cover was re-read in full from an enlarged source render. The printed lexical units were checked individually as:

- `பெரிய இடத்துப் பெண்`
- `மு. கருணாநிதி`
- `திராவிடன் பதிப்பகம்`
- `வேலூர் (வ. ஆ.)`

The scan-1 pass was interpreted using the complete 13-form reference above. No printed occurrence on this cover requires historical-form conversion and no glyph-identity correction is required. Copy-specific handwriting was not converted into canonical printed text.

### Scan 2 finding

Scan 2 was re-read in full at enlarged resolution. No original 1953 source-work printed narrative or publication text is present on this scan. The page consists of copy-specific handwriting plus a later printed gift label.

The later label was checked as:

- `பேராசிரியர்.`
- `தி.வ.`
- `மெய்கண்டார்`
- `அவர்களின்`
- `அன்பளிப்பு`

None of these clearly printed label units requires conversion from the 13 known historical forms. The handwritten Tamil remains outside the canonical printed-source layer and was not guessed or used as evidence for source-work glyph conversion.

### Scan 3 finding

Scan 3 was re-read in full at enlarged/high resolution. Unlike scans 1–2, this page contains multiple clear historical-form occurrences from the user-supplied reference set.

The following source glyph identities were positively established:

- `ஜூலை` — final historical form corresponds to modern Unicode `லை`;
- `விலை` — final historical form corresponds to modern Unicode `லை`;
- `விற்பனை` — final historical form corresponds to modern Unicode `னை`;
- `சைனா` — final historical form corresponds to modern Unicode `னா`;
- `சென்னை` — final historical form corresponds to modern Unicode `னை`.

All five were already represented with the correct modern Unicode character identities in the canonical page record. Therefore this pass required **no text replacement**, but it provides the first page-level positive confirmation that the 1953 source is actually using several of the supplied historical forms, not merely the previously identified `றா` form.

Other printed text, punctuation, numerals and bibliographic structure on scan 3 were checked; no additional legacy-glyph mismatch was identified in this pass.

**Progress:** **3 / 27** existing canonical scans reviewed in the retrospective pass; scans **4–27** remain pending. All reviewed pages remain `needs-review` and are not called verified.

## Audit rule

For this source, do not decide a glyph from ordinary visual resemblance alone. For every page:

1. inspect the complete glyph cluster at native/high resolution;
2. explicitly check for the user-supplied historical forms corresponding to `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
3. identify whether the printed shape is a pre-reform Tamil glyph rather than a modern glyph that merely looks similar;
4. compare same-edition occurrences where useful;
5. encode the glyph's actual Tamil identity in modern Unicode;
6. do not normalize vocabulary, grammar, punctuation or spelling beyond that glyph identification;
7. leave the page `needs-review` even after local corrections while this project-wide audit is open.

A confirmed mapping at one occurrence must **not** be mechanically globalized. Each occurrence must be checked against its source pixels. The 13-form chart is a minimum known reference set, not evidence that no other legacy typographic ambiguity can occur.

## Scope

Retroactive audit required: **scans 1–27**.

Particular attention must be given to all 13 user-supplied historical forms, and to any earlier transcription note that described a suspicious form as an intentional oddity merely because it looked unusual in modern type.

## Gate consequence

- canonical records created: **27 / 49**;
- retrospective historical-glyph pass: **3 / 27 reviewed — scans 1–3**;
- page status for scans 1–27: **27 `needs-review`**;
- `verified`: **0**;
- `partial`: **0**;
- `not-started`: **22**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Do **not** continue to scans 28–32 yet.

Audit **scan 4 only** next, using the same one-page method: inspect the entire scan at enlarged resolution, check every printed glyph cluster against the complete 13-form historical reference, make only pixel-supported glyph-identity corrections, record any corrections with provenance, and keep the page `needs-review`.
