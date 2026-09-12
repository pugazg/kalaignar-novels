# Next Chat Prompt — நடுத்தெரு நாராயணி / T1 Batch N2 scans 80–84

Continue directly in `pugazg/kalaignar-novels`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- work span: **scans 75–90 / 16 scans**
- source PDF committed: **No**

## Durable state

- source intake: **COMPLETE**;
- canonical page records: **5 / 16**;
- T1 scans 75–79: **COMPLETE**;
- verified pages: **0 / 16**;
- current statuses: **5 needs-review / 11 not started**;
- scan75 printed page: null;
- scans76–79 printed pages: **74–77**.

Confirmed joins:

- 76→77: `வாணச் சத்தம் அவள்` → `காதைத் துளைத்துக்கொண்டுதானிருந்தது.`;
- 78→79: `...ஜீவித்திருக்க ஏன்` → `விட்டாய் ?`.

Scan79 ends inside an open quotation. **Do not reconstruct its continuation from context; read scan80 directly.**

Targeted later review item:

- scan79 `அப்பிரதக்ஷிணமாகச்` middle glyph cluster is partly source/print obscured; T1 reading is provisional.

## Mandatory startup

Read:

1. `NOVEL_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. root `HANDOVER.md`;
4. this prompt;
5. `works/nadutheru-narayani/README.md`;
6. `works/nadutheru-narayani/audit.md`;
7. `works/nadutheru-narayani/metadata/source.md`;
8. `works/nadutheru-narayani/indexes/page-map.md`;
9. canonical page records for scans75–79 for continuity only.

## Exact next activity — N2 only

Process **scans 80–84 / printed pages expected 78–82**.

- visually transcribe each whole page from source pixels;
- preserve exact wording, punctuation, dialect and historical-glyph identity;
- continue scan79's open quotation only from scan80 pixels;
- do not silently normalize or context-correct;
- uncertain readings remain `needs-review`;
- create canonical page records for scans80–84;
- synchronize page map / audit / work README / root handover / collection controls;
- commit immediately after the five-scan batch;
- stop before scan85.

Do not run T2/T3 or promote N1 pages to verified in the same checkpoint unless separately authorized.
