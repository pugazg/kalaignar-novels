# Source Batch Checkpoint Workflow

This workflow breaks each bounded source-page batch into smaller durable tasks. It applies to active Tamil source transcription work unless a work-specific control explicitly overrides it.

The purpose is to avoid doing transcription, historical-glyph audit, final verification, control synchronization and commit preparation as one large operation.

## Batch size

A source batch may still contain a small contiguous range such as **5 physical scans**, but the batch is processed through separate checkpoints.

Every checkpoint MUST end with:

1. synchronize the work-level and repository-level controls that are affected by that checkpoint;
2. commit immediately;
3. report the exact durable state;
4. stop before beginning the next checkpoint unless the user explicitly asks to continue further in the same turn.

Do not hold multiple completed checkpoints in an uncommitted state.

## Checkpoint T1 — direct transcription / canonical records

For the bounded scan range:

- visually read each whole source page once;
- create or complete one canonical `pages/` record per physical scan;
- preserve `scan_page` and **only visibly printed** `printed_page` values;
- preserve title treatments, illustrations and non-body marks as separate observations;
- transcribe the complete printed text directly from the source;
- preserve source spelling, punctuation, dialogue, paragraph structure and page-boundary fragments;
- do not use OCR/context as authority;
- do not perform the independent historical-glyph re-read in this checkpoint;
- leave pages `needs-review` (or another non-final status) until the later gates pass.

Use enlarged crops only when an actual reading is uncertain; do not generate crops mechanically for every line/page.

Then synchronize controls, commit **T1**, and stop.

## Checkpoint T2 — independent historical-glyph re-read

Re-read the same bounded scan range independently against `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

- check the complete page, not only words already suspected;
- explicitly cover the known sensitive families `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- compare same-edition forms where necessary;
- correct character identity only when direct source pixels support it;
- do not modernize spelling/grammar/vocabulary;
- create crops/enhancements only for genuinely uncertain readings;
- record corrections and unresolved glyphs in the page/work audit.

Then synchronize controls, commit **T2**, and stop.

## Checkpoint T3 — final source-fidelity closure for the batch

Perform one final independent source re-read of the same scans:

- check omissions, duplicated text, misplaced fragments and page joins;
- confirm printed-page visibility and page type;
- confirm illustrations/non-body marks are not mixed into narrative text;
- confirm historical-glyph T2 findings are reflected correctly;
- resolve only what the scan directly supports;
- leave genuinely unresolved readings `needs-review`;
- mark a page/batch `verified` only when the project policy permits it and all mandatory gates have passed.

Create/update the bounded batch audit record, synchronize controls, commit **T3**, and stop.

Only after T3 is durable may the next source batch begin.

## Control synchronization after every checkpoint

At minimum update whichever of these are affected:

- work `README.md`;
- work `indexes/page-map.md`;
- work `audit.md`;
- batch/checkpoint audit file if used;
- root `HANDOVER.md`;
- `NEXT_NOVEL_CHAT_PROMPT.md`;
- root `README.md` when its active-state summary changes.

Controls must describe the exact checkpoint reached. They must not claim a later gate has passed.

## Active example — `அரும்பு` scans 6–10

The first batch is therefore:

- **T1:** direct visual transcription + canonical records + exact printed-page visibility for scans 6–10; sync + commit;
- **T2:** independent historical-glyph re-read of scans 6–10; sync + commit;
- **T3:** final source-fidelity closure of scans 6–10; sync + commit;
- only then move to scans 11–15.

This replaces the earlier instruction to perform all of those activities in one combined five-scan operation.
