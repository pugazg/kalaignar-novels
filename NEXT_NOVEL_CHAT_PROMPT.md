# Next Chat Prompt — அரும்பு / scans 6–10 / T2 historical-glyph checkpoint

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
9. canonical records `works/arumbu/pages/0006-arumbu-01.md` through `0010-arumbu-05.md`.

## Durable T1 state — scans 6–10

T1 direct transcription/canonical-record checkpoint is **PASS / COMPLETE**.

- canonical records: **5 / 18 total work scans**;
- scan 6 printed page: `null`;
- scans 7–10 printed pages: **2, 3, 4, 5**;
- all five records remain `needs-review`;
- no page is verified;
- T2 and T3 remain separate commits.

Preserved physical joins:

- 7→8 `நடந்` / `தேறின.`;
- 8→9 `அபிநய` / `அசைவுகளை...`;
- 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

## Exact next activity — T2 only

Perform an **independent historical-glyph re-read of physical scans 6–10**.

- re-read every complete page from source pixels rather than merely proofreading T1 text;
- explicitly check the full known sensitive-family set:
  `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- compare clearer same-edition forms when needed;
- correct Unicode character identity only where the source directly supports it;
- do not modernize spelling, grammar, punctuation or vocabulary;
- create crops/enhancements only when an actual glyph reading is uncertain;
- update page-level notes and work audit with every correction or unresolved form;
- keep pages `needs-review` because T3 has not yet run;
- synchronize controls and commit T2 immediately;
- stop.

Do **not** perform T3, begin scan 11, start another component, or compare the 1978 `பெரிய இடத்துப் பெண்` witness in the same checkpoint.
