# Next Chat Prompt — அரும்பு / scans 21–23 / T3 final source-fidelity checkpoint

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
8. `works/arumbu/T2_BATCH_021_023.md`;
9. canonical scan records `works/arumbu/pages/0021-arumbu-17.md`, `0022-arumbu-18.md`, `0023-arumbu-19.md`.

## Durable state

Scans **6–20 are CLOSED / VERIFIED** after T1+T2+T3.

Final scans **21–23**:

- directly visible printed pages: **17, 18, 19**;
- T1 — **PASS / COMPLETE**;
- T2 — **PASS / COMPLETE — 0 character-identity corrections / 0 unresolved historical glyphs**;
- canonical records — **3 / 3 present**, all `needs-review` pending T3;
- T3 — **NEXT**.

Current totals:

- canonical records: **18 / 18 — scans 6–23**;
- verified records: **15 / 18 — scans 6–20 contiguous**;
- assembled Tamil / English remain BLOCKED.

The independent T2 pass explicitly checked the full known set `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` on every complete page.

Important source-confirmed readings:

- scan 22 — **`பேசினேன்`** is directly visible in enlarged source pixels; do not context-normalize it;
- scan 23 — **`அம்மனார்`** is directly visible and its `னா` identity is confirmed; do not context-normalize it.

Do not reopen scans 6–20 without genuinely new source evidence.

## Small-task discipline

- **T1** = COMPLETE for scans 21–23.
- **T2** = COMPLETE for scans 21–23.
- **T3** = current checkpoint: exhaustive final source-fidelity closure.

Do not begin the next component within T3.

## Exact next activity — scans 21–23 / T3 only

Independently compare complete physical scans **21, 22 and 23** against direct source pixels:

- check the entire printed text for omissions, duplicates, unsupported words or misplaced fragments;
- check source spelling, punctuation, dialogue marks, paragraph structure and spacing where source-visible;
- confirm printed-page numbers **17, 18, 19**, page type and final-page behavior;
- confirm 20→21, 21→22 and 22→23 physical continuity;
- confirm illustrations/non-body material remain separate from narrative text;
- confirm T2 findings are represented correctly;
- preserve source-confirmed `பேசினேன்` and `அம்மனார்` unless direct pixels positively prove a different reading;
- resolve only what the scan directly supports; do not modernize or reconstruct from context;
- record every T3 correction and any unresolved source reading;
- if all mandatory gates pass, mark all three records `verified`, making `அரும்பு` **18 / 18 VERIFIED**;
- synchronize work/root controls and commit T3 immediately;
- stop.

Do **not** begin `சாரப்பள்ளம் சாமுண்டி`, perform the 1978 `பெரிய இடத்துப் பெண்` witness comparison, or start English/assembly work in this checkpoint.
