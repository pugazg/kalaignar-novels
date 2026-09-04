# Historical Glyph Audit — பெரிய இடத்துப் பெண்

## Status

**OPEN — blocking page verification.**

The user identified a systematic transcription risk in this 1953 source: a historical pre-reform Tamil glyph corresponding to modern Unicode `றா` can visually resemble modern `று`. Earlier transcription treated the visual form literally as `று` in several places instead of decoding the historical glyph identity.

Because this can affect earlier pages as well as later pages, all canonical records currently created for scans **1–27** have been reclassified to `needs-review`. No page in this work is to be marked `verified` while this audit is open. Future page records must also remain `needs-review` unless the user explicitly authorizes a different verification policy.

## Confirmed corrections

The following corrections are supported by the user's glyph identification and direct source reinspection:

| Scan | Printed page | Incorrect transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

These are **glyph-identification corrections**, not spelling modernization. The source's historical glyph is being represented by its correct modern Unicode character sequence.

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
- page status for scans 1–27: **27 `needs-review`**;
- `verified`: **0**;
- `partial`: **0**;
- `not-started`: **22**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **blocked**;
- English translation: **blocked**.

## Exact next activity

Do **not** continue to scans 28–32 yet.

Perform a systematic historical-glyph re-audit of existing canonical scans **1–27**, in source order, with special attention to pre-reform `றா` and related legacy glyph forms. Record every correction with scan/printed-page provenance. Keep every page `needs-review`. Only after the retrospective audit is complete should new-page transcription resume.
