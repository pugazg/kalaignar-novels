# Next Chat Prompt — அரும்பு / assembled Tamil reading layer

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
- scans 6–23 — `அரும்பு` — **TAMIL SOURCE LAYER PASSED**;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before assembled-layer work:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Section 13 assembled Tamil reading layer;
2. root `HANDOVER.md`;
3. `collections/arumbu-1978/README.md`;
4. `works/arumbu/README.md`;
5. `works/arumbu/audit.md`;
6. `works/arumbu/indexes/page-map.md`;
7. all verified canonical page records under `works/arumbu/pages/` needed to derive the continuous reading layer.

Do not reopen source transcription unless genuinely new direct source evidence appears.

## Durable `அரும்பு` state

- physical source span: **scans 6–23 / 18 scans**;
- canonical records: **18 / 18**;
- verified records: **18 / 18 — scans 6–23 contiguous**;
- all T1/T2/T3 page-level gates: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- Tamil source layer: **PASSED**;
- unresolved historical glyphs: **0**;
- unresolved source readings: **0**;
- assembled Tamil: **NEXT**;
- English: **BLOCKED**.

Important source facts to preserve:

- scan 6 has no directly visible printed number; keep it unnumbered in provenance;
- scan 13 / printed 8 → scan 14 / printed 10 is a source-visible pagination jump; do not invent page 9;
- the 13→14 narrative join is `ஊற்றெடுத்துக் கிளம்பிவரும்` / `அருவி!`;
- scan 22 source-confirmed `பேசினேன்` remains unchanged;
- scan 23 source-confirmed `அம்மனார்` remains unchanged;
- scan 23 is the final physical page and has no explicit `முற்றும்`;
- no source-backed chapter divisions have been identified for this work.

## Exact next activity — assembled Tamil only

Build the readable Tamil derivation under `works/arumbu/sections/`:

- create `works/arumbu/sections/README.md` describing the derivation/provenance rules and section inventory;
- create `works/arumbu/sections/01-arumbu.md` as one continuous source-faithful reading section unless the verified canonical records directly demonstrate a different structural division;
- derive text **only** from the 18 audited canonical page records; do not independently re-transcribe from the PDF;
- preserve source spelling, punctuation, paragraphing, dialogue, rhetoric, period forms and documented unusual readings;
- join only positively established cross-page word/sentence continuations for readability;
- retain reversible source-page provenance comments so every assembled passage can be traced back to its physical scan/page record;
- do not modernize, silently correct, invent chapters, or fabricate printed page 9;
- synchronize `works/arumbu/README.md`, `works/arumbu/audit.md`, root `HANDOVER.md`, root `README.md`, and this prompt as affected;
- commit the assembled-Tamil checkpoint and stop.

Do **not** begin English translation, `சாரப்பள்ளம் சாமுண்டி`, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
