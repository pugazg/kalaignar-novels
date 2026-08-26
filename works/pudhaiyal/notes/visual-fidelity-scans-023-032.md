# Visual-fidelity pass invalidated — புதையல் scans 23–32

Date: 2026-08-26

## Status

**INVALIDATED — do not use the previous assistant-proposed textual corrections as source readings.**

The user reviewed the Iteration 3 result and explicitly stated that the transcription they supplied for printed pages 21–30 is correct and that the assistant's proposed corrections were hallucinated.

Accordingly:

- every assistant-proposed textual correction from the previous version of this note is withdrawn;
- canonical page records `0023-pudhaiyal.md` through `0032-pudhaiyal.md` have been restored to the user's supplied Iteration 3 transcription;
- these ten pages are no longer labelled `verified` from the invalidated visual pass;
- their current status is `needs-review` pending a fresh direct source comparison;
- the source PDF / split PDF remains outside the repository.

## Affected range

| Scan | Printed page | Structure | Current status |
|---:|:---:|---|---|
| 23 | 21 | chapter 2 | needs-review |
| 24 | 22 | chapter 2 | needs-review |
| 25 | 23 | chapter 2 | needs-review |
| 26 | 24 | chapter 2 | needs-review |
| 27 | 25 | chapter 2 | needs-review |
| 28 | 26 | chapter 2 | needs-review |
| 29 | 27 | chapter 2 | needs-review |
| 30 | 28 | chapter 2 closes / chapter 3 begins | needs-review |
| 31 | 29 | chapter 3 | needs-review |
| 32 | 30 | chapter 3 | needs-review |

## Withdrawn correction claims

All claims in the previous version that said the scan required replacing the user's supplied wording are withdrawn, including claims involving forms such as:

- `மதகின் உள்ளேயிருந்தவர்களுக்கு` versus the user's `உள்ளேயிருந்தவர்களுக்கு`;
- `ஆறுதல் அளித்தது` versus `ஆறுதலை அளித்தது`;
- `அவர்களே நோக்கி` versus `அவர்களை நோக்கி`;
- `அவன் முதுகில்` versus `அவன முதுகில்`;
- `அவர்களேதான்`, `கடல் பார்த்துக்`, `அவளே அவன்...` versus the user's supplied forms;
- `தும்பைப்பூ` versus the user's `தும்பை பூ`;
- punctuation, spacing and other assistant-normalized/source-inferred substitutions introduced during that pass.

None of those withdrawn claims should be cited as verified source evidence.

## Revised working rule

For subsequent user-supplied transcription batches:

1. preserve the user's supplied transcription as the baseline text;
2. compare against the scan only as a verification exercise;
3. if an old-print glyph, spacing, punctuation mark or word appears to differ, **do not silently replace the user's reading**;
4. record the apparent discrepancy as `needs-review` and surface the exact word/glyph for confirmation;
5. change canonical text only after the reading is genuinely established rather than inferred from visual ambiguity, grammar or expected modern spelling.

This rule is particularly important for old Tamil glyph forms and degraded print where a modern-looking interpretation can be misleading.

## Current gate state

- page records created through scan 32: **32**
- `verified`: **22** — scans 1–22 only
- `needs-review`: **10** — scans 23–32
- unresolved disputed range: **scans 23–32**
- Tamil whole-work audit: **not started**
- full-source manifest: **incomplete**
- English translation: **blocked**

## Next action

Do not proceed to the next transcription range until this correction state is accepted. When work resumes, the user's transcription must not be overridden by assistant-inferred visual readings; discrepancies should be flagged rather than silently corrected.
