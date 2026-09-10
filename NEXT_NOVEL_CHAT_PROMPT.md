# Next Chat Prompt — அரும்பு / scans 11–15 / T1 transcription checkpoint

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
- scans 49–74 — `பெரிய இடத்துப் பெண்` — registered only as an additional witness;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before source-dependent work:

1. `NOVEL_PROCESSING_GUIDE.md`;
2. `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`;
3. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
4. root `HANDOVER.md`;
5. `works/arumbu/README.md`;
6. `works/arumbu/indexes/page-map.md`;
7. `works/arumbu/audit.md`;
8. `works/arumbu/T1_BATCH_006_010.md`;
9. `works/arumbu/T2_BATCH_006_010.md`;
10. `works/arumbu/T3_BATCH_006_010.md`;
11. verified canonical records `works/arumbu/pages/0006-arumbu-01.md` through `0010-arumbu-05.md` for continuity only.

## Durable closed state — scans 6–10

- T1 — **PASS / COMPLETE**;
- T2 — **PASS / COMPLETE — 4 character-identity corrections / 0 unresolved**;
- T3 — **PASS / COMPLETE — 19 additional source-fidelity corrections / 0 unresolved**;
- canonical records: **5 / 18**;
- verified canonical records: **5 / 18**;
- printed-page visibility: scan 6 `null`; scans 7–10 = **2, 3, 4, 5**.

Preserved joins:

- 7→8 `நடந்` / `தேறின.`;
- 8→9 `அபிநய` / `அசைவுகளை...`;
- 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

Do not reopen scans 6–10 unless genuinely new direct-source evidence appears.

## Small-task workflow — mandatory

For each bounded scan batch:

- **T1** direct visual transcription + canonical records + exact printed-page visibility → control sync → commit → stop;
- **T2** independent historical-glyph re-read → control sync → commit → stop;
- **T3** final source-fidelity closure → control sync → commit → stop.

Do not combine these by default.

## Exact next activity — scans 11–15 / T1 only

Process physical scans **11–15**:

- visually transcribe each whole page once from direct source pixels;
- create one canonical record per scan under `works/arumbu/pages/`;
- record a printed page number only when directly visible; **do not infer numbering from the prior sequence**;
- preserve all source spelling, punctuation, dialogue, paragraph structure and physical page-boundary fragments;
- preserve illustrations/non-body marks as observations rather than narrative text;
- use enlarged crops only for an actually uncertain reading;
- do not use OCR/context as authority;
- do **not** run the independent historical-glyph T2 pass yet;
- leave all five new records `needs-review` because T2/T3 remain pending;
- synchronize affected controls and commit T1 immediately;
- stop.

Do **not** begin scan 16, T2 for scans 11–15, another component, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in this checkpoint.
