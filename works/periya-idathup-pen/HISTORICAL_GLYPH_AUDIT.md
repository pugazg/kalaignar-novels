# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: a historical pre-reform Tamil glyph corresponding to modern Unicode `றா` can visually resemble modern `று`. Earlier transcription treated the visual form literally as `று` in several places instead of decoding the historical glyph identity.

Because this can affect earlier pages as well as later pages, all canonical records currently created for scans **1–27** remain `needs-review`. No page in this work is to be marked `verified` while this audit is open. Future page records must also remain `needs-review` unless the user explicitly authorizes a different verification policy.

## Confirmed corrections

The following corrections are supported by the user's glyph identification and direct source reinspection:

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

These are **glyph-identification corrections**, not spelling modernization. The source's historical glyph is being represented by its correct modern Unicode character sequence.

## Retrospective pass progress

| Scan | Printed page | Historical-glyph pass | Corrections from this pass | Page status |
|---:|:---:|---|---|---|
| 1 | — | complete for this one-page pass | none | `needs-review` |

### Scan 1 finding

The cover was re-read in full from an enlarged source render. The printed lexical units were checked individually as:

- `பெரிய இடத்துப் பெண்`
- `மு. கருணாநிதி`
- `திராவிடன் பதிப்பகம்`
- `வேலூர் (வ. ஆ.)`

No printed `றா` cluster occurs on scan 1, so the specific historical-`றா` / apparent-modern-`று` ambiguity does not arise on this page. No other glyph-identity mismatch was found in the printed cover text during this pass. Copy-specific handwriting was not converted into canonical printed text.

**Progress:** 1 / 27 existing canonical scans reviewed in the retrospective pass; scans 2–27 remain pending. The reviewed page still remains `needs-review` and is not called verified.

## Audit rule

For this source, do not decide a glyph from ordinary visual resemblance alone. For every suspect historical form:

1. inspect the complete glyph cluster at native/high resolution;
2. identify whether the shape is a pre-reform Tamil glyph rather than a modern glyph that merely looks similar;
3. compare same-edition occurrences where useful;
4. encode the glyph's actual Tamil identity in modern Unicode;
5. do not normalize vocabulary, grammar, punctuation or spelling beyond that glyph identification;
6. leave the page `needs-review` even after local corrections while this project-wide audit is open.

A confirmed mapping at one occurrence must **not** be mechanically globalized. Each occurrence must be checked against its source pixels.

## Scope

Retroactive audit required: **scans 1–27**.

Particular attention must be given to legacy vowel-bearing forms, beginning with the user-confirmed `றா` issue, and to any earlier transcription note that described a suspicious form as an intentional oddity merely because it looked unusual in modern type.

## Gate consequence

- canonical records created: **27 / 49**;
- retrospective historical-glyph pass: **1 / 27 reviewed — scan 1 only**;
- page status for scans 1–27: **27 `needs-review`**;
- `verified`: **0**;
- `partial`: **0**;
- `not-started`: **22**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Do **not** continue to scans 28–32 yet.

Audit **scan 2 only** next, using the same one-page method: inspect the entire scan at enlarged resolution, separate copy-specific handwriting/label material from source printed text, check any printed glyph clusters for historical typeforms, record any corrections with provenance, and keep the page `needs-review`.
