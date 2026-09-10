# Next Chat Prompt — அரும்பு / whole-work Tamil audit gate

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
- scans 6–23 — `அரும்பு` — ACTIVE, page-level source gates complete;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before the audit:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Section 12 Tamil audit gate;
2. `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`;
3. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
4. root `HANDOVER.md`;
5. `collections/arumbu-1978/README.md`;
6. `works/arumbu/README.md`;
7. `works/arumbu/metadata/source.md`;
8. `works/arumbu/indexes/page-map.md`;
9. `works/arumbu/audit.md`;
10. `works/arumbu/T1_BATCH_021_023.md`;
11. `works/arumbu/T2_BATCH_021_023.md`;
12. `works/arumbu/T3_BATCH_021_023.md`;
13. canonical page records under `works/arumbu/pages/` as needed to reconcile the complete inventory and continuity.

## Durable state

Page-level source processing for `அரும்பு` is complete:

- canonical records: **18 / 18 — scans 6–23**;
- verified records: **18 / 18 — scans 6–23 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1/T2/T3: **PASS / COMPLETE**;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- scans 21–23 T3: **PASS / COMPLETE — 4 corrections / 0 unresolved**;
- whole-work Tamil audit: **NEXT**;
- assembled Tamil / English remain BLOCKED.

Final-batch T3 corrections:

- scan 21 `பார்த்தான்:` → `பார்த்தான்.`;
- scan 21 `கிடந்தன:` → `கிடந்தன.`;
- scan 22 `ஆஸ்பத்திரியிலே` → `ஆஸ்பத்திரியில்`;
- scan 23 `இனி......` → `இனி:......`.

Source-confirmed unusual readings remain:

- scan 22 — `பேசினேன்`;
- scan 23 — `அம்மனார்`.

Scan 23 is the final physical page of `அரும்பு`; no explicit `முற்றும்` is printed.

## Exact next activity — whole-work Tamil audit only

Run the Section 12 Tamil audit gate for `அரும்பு`:

- confirm all **18 / 18** source scans have canonical records and page-map coverage with no gap;
- confirm all 18 records are `verified` and every required page-level T1/T2/T3 gate is durably recorded;
- reconcile `works/arumbu/metadata/source.md` and collection provenance with the controlling source identity;
- confirm visible printed-page mapping, including unnumbered scan 6 and final visible printed page 19 on scan 23;
- confirm cross-page joins and component boundaries are coherent and reversible;
- confirm illustrations/footer/non-body observations are separated from narrative text;
- confirm historical-glyph coverage is complete and unresolved historical/source readings are **0**;
- confirm no silent modernization, context reconstruction or unsupported normalization remains in the canonical layer;
- confirm the source PDF remains excluded from the repository;
- update `works/arumbu/audit.md` with an explicit whole-work Tamil audit PASS/hold result;
- synchronize `works/arumbu/README.md`, page map if needed, root `HANDOVER.md`, `NEXT_NOVEL_CHAT_PROMPT.md`, root `README.md`, and collection status if affected;
- commit the audit checkpoint and stop.

Do **not** create assembled Tamil sections, start English, begin `சாரப்பள்ளம் சாமுண்டி`, or perform the 1978 `பெரிய இடத்துப் பெண்` witness comparison in this checkpoint.
