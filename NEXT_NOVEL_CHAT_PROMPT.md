# Next Chat Prompt — அரும்பு / scans 16–20 / T2 historical-glyph checkpoint

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
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. root `HANDOVER.md`;
4. `works/arumbu/README.md`;
5. `works/arumbu/indexes/page-map.md`;
6. `works/arumbu/audit.md`;
7. `works/arumbu/T1_BATCH_016_020.md`;
8. canonical records `works/arumbu/pages/0016-arumbu-12.md` through `0020-arumbu-16.md`.

## Durable state

Scans 6–15 are CLOSED / VERIFIED after T1+T2+T3.

Scans 16–20:

- T1 — **PASS / COMPLETE**;
- T2 — **NEXT**;
- T3 — BLOCKED;
- five canonical records exist and remain `needs-review`;
- directly visible printed pages: **12, 13, 14, 15, 16**.

T1 joins/edges:

- 15→16 `செல்லக்` / `குழந்தையை—...`;
- 16→17 `அவர்களைக்-` / `கவனிக்கிறான்.`;
- 18→19 `செலவா` / `யிற்று.`;
- 19→20 `கடிந்துகொண்` / `டிருக்கிறாள்.`.

## Small-task discipline

- **T1** = one direct visual transcription pass only.
- **T2** = independent historical-glyph / character-identity re-read; targeted crops only for actual uncertainty.
- **T3** = exhaustive final source-fidelity closure.
- synchronize controls and commit after each stage, then stop.

## Exact next activity — scans 16–20 / T2 only

- independently re-read the five complete scans under the historical-glyph guide;
- check the mandatory reform-sensitive families and other genuinely ambiguous character identities;
- use same-page/same-edition comparisons when needed;
- create enlarged crops only for actual uncertainty, not routinely;
- correct only source-supported character identities;
- record every T2 correction and unresolved form in a dedicated `T2_BATCH_016_020.md`;
- leave all five page records `needs-review` because T3 remains pending;
- synchronize controls and commit T2 immediately;
- stop.

Do **not** perform T3, inspect scan 21, begin another component, or start the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
