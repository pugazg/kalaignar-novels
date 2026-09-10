# Next Chat Prompt — அரும்பு / scans 6–10 / T1 transcription checkpoint

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

## Compilation structure — durable

- scans 1–5 — collection front matter;
- scans 6–23 — `அரும்பு` — ACTIVE;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — registered only as a second witness to existing work;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

Collection intake and all four component boundaries are **REGISTERED / COMPLETE**. No narrative transcription from this PDF has yet been durably committed.

## Mandatory startup

Read before source-dependent work:

1. `NOVEL_PROCESSING_GUIDE.md`;
2. `SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`;
3. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
4. root `HANDOVER.md`;
5. `collections/arumbu-1978/README.md`;
6. `collections/arumbu-1978/metadata/source.md`;
7. `collections/arumbu-1978/indexes/work-map.md`;
8. `works/arumbu/README.md`;
9. `works/arumbu/metadata/source.md`;
10. `works/arumbu/indexes/page-map.md`;
11. `works/arumbu/audit.md`.

## Small-task workflow — mandatory

Do **not** process transcription + historical-glyph audit + closure in one operation.

For scans 6–10 the durable sequence is:

- **T1** direct visual transcription + canonical records + exact printed-page visibility → control sync → commit;
- **T2** independent historical-glyph re-read → control sync → commit;
- **T3** final source-fidelity closure → control sync → commit;
- only then begin scans 11–15.

Each task is a separate commit. Crops/enhancements are created only for genuinely uncertain readings.

## Exact next activity — T1 only

Process physical scans **6–10**:

- visually transcribe each whole page once;
- create one canonical record per scan under `works/arumbu/pages/`;
- scan 6 opening printed page number is **not visibly present**; use `printed_page: null`;
- scans 7–10: preserve only the directly visible printed numbers;
- preserve illustrations and non-body marks separately from narrative;
- preserve physical page-boundary fragments exactly and document joins without silently moving text;
- do not use OCR/context as authority;
- do **not** run the independent historical-glyph T2 re-read yet;
- leave the five page records `needs-review` because T2 and T3 remain pending;
- synchronize controls and commit T1 immediately;
- stop.

Do **not** start scan 11, T2, another component, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in this checkpoint.
