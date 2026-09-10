# Next Chat Prompt — அரும்பு / scans 21–23 / T1 transcription checkpoint

Continue in `pugazg/kalaignar-novels`, branch `main`, active source `collections/arumbu-1978/`, active work `works/arumbu/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- **117,270,339 bytes**
- **92 physical scans**
- image-only
- தமிழ்க்கனி பதிப்பகம், சென்னை-28
- முதற் பதிப்பு 1978
- source PDF must **not** be committed.

## Durable compilation structure

- scans 1–5 — collection front matter;
- scans 6–23 — `அரும்பு` — ACTIVE;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before source-dependent work:

1. `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`;
2. root `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/indexes/page-map.md`;
5. `works/arumbu/audit.md`;
6. `works/arumbu/T3_BATCH_016_020.md`;
7. verified scan-20 record only for physical continuity.

## Durable state

Scans **6–20 are CLOSED / VERIFIED** after T1+T2+T3.

Scans 16–20:

- T1 — PASS / COMPLETE;
- T2 — PASS / COMPLETE — 1 correction / 0 unresolved;
- T3 — PASS / COMPLETE — 11 additional corrections / 0 unresolved;
- directly visible printed pages: **12, 13, 14, 15, 16**.

Current totals:

- canonical records: **15 / 18**;
- verified records: **15 / 18 — scans 6–20 contiguous**;
- unresolved source readings in verified range: **0**;
- scans 21–23: not started.

Do not reopen scans 6–20 without genuinely new source evidence.

## Small-task discipline

- **T1** = one direct visual transcription pass only; create canonical `needs-review` records, sync controls, commit, stop.
- **T2** = independent historical-glyph / character-identity re-read; targeted crops only for actual uncertainty; sync, commit, stop.
- **T3** = exhaustive final source-fidelity closure; sync, commit, stop.

Do not fold T2/T3 work into T1.

## Exact next activity — scans 21–23 / T1 only

Process the final three physical scans of `அரும்பு`, **21–23**:

- visually transcribe each whole page once from direct source pixels;
- create one canonical record per scan under `works/arumbu/pages/`;
- record a printed page number only when directly visible; never infer numbering;
- preserve source spelling, punctuation, dialogue, paragraph structure and physical page-boundary fragments on a first-pass basis;
- preserve illustrations/non-body marks as observations rather than narrative text;
- if a difficult first-pass reading remains, mark it for T2/T3 instead of running repeated crop loops;
- do **not** run T2 or T3 in this checkpoint;
- leave all three new records `needs-review`;
- synchronize controls and commit T1 immediately;
- stop.

Do **not** begin `சாரப்பள்ளம் சாமுண்டி`, perform the 1978 `பெரிய இடத்துப் பெண்` witness comparison, or start English/assembly work in this checkpoint.
