# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: pugazg/kalaignar-novels
- Branch: main
- **Live main is authoritative.**
- Active source: **1978 அரும்பு four-story compilation**.
- Active work: **works/sarapallam-samundi/**.
- works/arumbu/ is **RELEASE-READY / CLOSED**.

## Controlling source

TVA_BOK_0064361_அரும்பு.pdf

- SHA-256: 04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc
- size: **117,270,339 bytes**
- physical scans: **92**
- image-only
- தமிழ்க்கனி பதிப்பகம், சென்னை-28
- முதற் பதிப்பு 1978
- source PDF: **DO NOT COMMIT**.

## Component state

1. அரும்பு scans 6–23 — **RELEASE-READY / CLOSED**.
2. சாரப்பள்ளம் சாமுண்டி scans 24–48 — **ACTIVE**.
3. பெரிய இடத்துப் பெண் scans 49–74 — additional 1978 witness only.
4. நடுத்தெரு நாராயணி scans 75–90 — queued.

## சாரப்பள்ளம் சாமுண்டி durable state

- component span: **25 physical scans — 24–48**;
- canonical records: **5 / 25 — scans 24–28**;
- verified: **0 / 25**;
- T1 scans 24–28: **PASS / COMPLETE**;
- T2 scans 24–28: **NEXT**;
- T3 scans 24–28: **BLOCKED by T2**;
- scans 29–48: **NOT STARTED**.

Direct source findings:

- scan 24 opens title சாரப்பள்ளம் சாமுண்டி; printed number null;
- scan 25 = printed 21;
- scan 26 = printed 22;
- scan 27 = printed 23;
- scan 28 is a landscape two-page illustration spread with **no visible printed number**; do not infer 24/25;
- physical joins 24→25, 25→26, 26→27 and 27→28 are recorded in T1_BATCH_024_028.md.

No OCR/context authority was used for T1. All five records remain needs-review.

## Exact next activity

Execute **T2 independent historical-glyph / character-identity re-read for scans 24–28 only** under HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md. Check the complete pages, explicitly cover the sensitive glyph families, correct only with source-pixel evidence, synchronize controls, commit, and stop before T3.

Do not begin scan 29 or the 1978 பெரிய இடத்துப் பெண் witness comparison in the same checkpoint.
