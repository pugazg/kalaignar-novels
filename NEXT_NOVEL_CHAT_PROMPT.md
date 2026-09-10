# Next Chat Prompt — அரும்பு / scans 21–23 / T2 historical-glyph checkpoint

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
7. `works/arumbu/T1_BATCH_021_023.md`;
8. canonical scan records `works/arumbu/pages/0021-arumbu-17.md`, `0022-arumbu-18.md`, `0023-arumbu-19.md`.

## Durable state

Scans **6–20 are CLOSED / VERIFIED** after T1+T2+T3.

Final scans **21–23**:

- directly visible printed pages: **17, 18, 19**;
- T1 — **PASS / COMPLETE**;
- canonical records — **3 / 3 present**, all `needs-review`;
- T2 — **NEXT**;
- T3 — BLOCKED by T2.

Current totals:

- canonical records: **18 / 18 — scans 6–23**;
- verified records: **15 / 18 — scans 6–20 contiguous**;
- unresolved source readings in verified range: **0**;
- assembled Tamil / English remain BLOCKED.

Scan 21 T1 was committed separately at `89c41ba57f634bf222cb484d605f32217ccb7176`; the completed T1 batch record is `works/arumbu/T1_BATCH_021_023.md`.

T2 should independently re-check the first-pass source readings `பேசினேன்` (scan 22) and `அம்மனார்` (scan 23) without context-normalizing them.

Do not reopen scans 6–20 without genuinely new source evidence.

## Small-task discipline

- **T1** = direct visual transcription only — COMPLETE for scans 21–23.
- **T2** = independent historical-glyph / character-identity re-read — current checkpoint.
- **T3** = exhaustive final source-fidelity closure — blocked until T2 is durably committed.

Do not fold T3 into T2.

## Exact next activity — scans 21–23 / T2 only

Independently re-read complete physical scans **21, 22 and 23** against `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`:

- check the complete pages, not only already-suspected words;
- explicitly cover the sensitive families `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- compare same-edition forms only when necessary;
- correct character identity only when directly supported by source pixels;
- do not modernize spelling, grammar or vocabulary;
- create crops/enhancements only for genuinely uncertain readings;
- record every correction and any unresolved glyph in the T2 batch/work audit;
- keep all three page records `needs-review`;
- synchronize affected controls and commit T2 immediately;
- stop before T3.

Do **not** begin `சாரப்பள்ளம் சாமுண்டி`, perform the 1978 `பெரிய இடத்துப் பெண்` witness comparison, or start English/assembly work in this checkpoint.
