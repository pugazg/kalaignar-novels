# Next Chat Prompt — அரும்பு / scans 6–10 / T3 source-fidelity closure

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
10. canonical records `works/arumbu/pages/0006-arumbu-01.md` through `0010-arumbu-05.md`.

## Durable T1/T2 state — scans 6–10

- T1 direct transcription/canonical records: **PASS / COMPLETE**;
- T2 independent historical-glyph re-read: **PASS / COMPLETE**;
- canonical records: **5 / 18 total work scans**;
- printed pages: scan 6 `null`; scans 7–10 **2, 3, 4, 5**;
- all five page records remain `needs-review`; none is verified yet;
- T2 corrections: **4 / unresolved glyphs 0**.

T2 corrections:

- scan 7 `மனத்திற்குப்` → `மணத்திற்குப்`;
- scan 8 `கிழவனுக்குவா` → `கிழவனாகவா`;
- scan 8 `கிழவனுக்குவும்` → `கிழவனாகவும்`;
- scan 10 `அவனுடைய` → `அவளுடைய`.

The two scan-8 corrections are historical `னா` decoding corrections. The scan-7 and scan-10 changes are additional direct character-identity corrections found during the independent page re-read.

Preserved physical joins:

- 7→8 `நடந்` / `தேறின.`;
- 8→9 `அபிநய` / `அசைவுகளை...`;
- 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

## Exact next activity — T3 only

Perform the **final independent source-fidelity closure for physical scans 6–10**.

- compare every complete canonical page directly against source pixels;
- check for omissions, duplicated text, accidental normalization and misplaced fragments;
- verify the three physical page joins without moving fragments between records;
- reconfirm printed-page visibility and scan 6 title-illustration/body separation;
- reconfirm the four T2 character-identity corrections from the source;
- resolve only direct-source-supported issues;
- if all mandatory checks pass, change scans 6–10 from `needs-review` to `verified`;
- create `T3_BATCH_006_010.md`;
- synchronize work README, page map, audit, root HANDOVER, next prompt and root README;
- commit T3 separately and stop.

Do **not** begin scan 11, start another component, or compare the 1978 `பெரிய இடத்துப் பெண்` witness in the same checkpoint.
