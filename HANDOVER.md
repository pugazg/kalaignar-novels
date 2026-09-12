# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **Live main is authoritative.**
- Active work: **`works/nadutheru-narayani/`**
- Prior `பெரிய இடத்துப் பெண்` 1978 witness comparison: **PASS / COMPLETE / CLOSED**

## Active source — நடுத்தெரு நாராயணி

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- work physical span: **75–90 / 16 scans**
- source PDF committed: **No**

## Durable Tamil state

- source intake: **COMPLETE**;
- component boundary: **CONFIRMED**;
- canonical page records: **5 / 16**;
- T1 coverage: **scans 75–79 — COMPLETE**;
- verified pages: **0 / 16**;
- current statuses: **5 needs-review / 11 not started**;
- Batch N1 commit scope: **scan75 unnumbered opening; scans76–79 printed 74–77**;
- no scan80 text imported.

Confirmed joins:

- scan76→77: `வாணச் சத்தம் அவள்` → `காதைத் துளைத்துக்கொண்டுதானிருந்தது.`;
- scan78→79: `...ஜீவித்திருக்க ஏன்` → `விட்டாய் ?`.

Targeted later review item:

- scan79 `அப்பிரதக்ஷிணமாகச்`: middle glyph cluster is partly affected by a source/print blemish; T1 reading is provisional and page remains **needs-review**.

Source-specific odd forms and dialect have been retained without modernization, including `ஆளுக்கு ஆளு-காணுவுக்குக் காணு`, `எக்கண விசினிலோ ; என்ன வக்கண பேசினிலோ`, `வாசரோஜாவேலியின்றிப்-பாதுகாக்க`, `புரு வலுவிலே`, and `நோக்கு ... நேக்கு ... நன்னுகத்`.

## Exact next activity

Process **Batch N2 — scans 80–84 only**.

For each scan:

1. visually transcribe the complete source page;
2. preserve source spelling, punctuation, dialect and historical glyph identity;
3. continue scan79's open quotation only from directly visible scan80 pixels;
4. create canonical page records for scans80–84;
5. update page map / audit / README / handover / collection controls;
6. commit immediately after the five-scan batch;
7. stop before scan85.

Do not promote N1 records to verified during N2 unless a separately scoped review explicitly does so.
