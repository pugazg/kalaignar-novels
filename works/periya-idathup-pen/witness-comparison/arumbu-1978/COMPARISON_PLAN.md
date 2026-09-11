# 1978 Additional-Witness Comparison Plan — பெரிய இடத்துப் பெண்

Status: **PLAN / MAPPING COMPLETE — W4 COMPLETE / W5 NEXT**.

## Purpose

Compare the 1978 `அரும்பு` printing of `பெரிய இடத்துப் பெண்` against the already completed 1953 eighth-edition archival package without changing the controlling edition.

This is **witness comparison**, not retranscription and not canonical repair.

## Authority

### Controlling edition

`TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`

- SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`
- scans: **49**
- edition: **எட்டாம் பதிப்பு — ஜூலை 1953**
- publisher: **திராவிடன் பதிப்பகம்**
- status: **controlling**
- canonical page-status freeze: **ACTIVE — 0 verified / 49 needs-review**

### Additional witness

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- compilation scans: **92**
- compilation edition: **முதற் பதிப்பு — 1978**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- witness physical scans: **49–74 / 26 scans**
- status: **additional witness only**

The 1978 source pixels control only what the 1978 witness reads. They do not override the 1953 controlling edition.

## Non-mutation rule

This pass is record-only.

Do **not** alter:

- `works/periya-idathup-pen/pages/`;
- assembled Tamil `sections/`;
- English translation;
- whole-work English VERIFIED status;
- qualified 1953 release verdict;
- canonical `needs-review` freeze.

Any possible later editorial action requires a separate explicit decision after the witness evidence has been fully recorded.

## Directly established structural anchors

Direct inspection of the 1978 source scans establishes:

- scan **49** — title/opening `பெரிய இடத்துப் பெண்`; no visible printed number assigned;
- opening text begins with `“குமுதா! அவளுக்கு அவன்தான் அமுதா?”`, aligning with the 1953 narrative opening;
- scan **53 / printed 50** — internal heading `உத்தண்டி`;
- scan **56 / printed 53** — internal heading `கண்ணம்மா`;
- scan **57** — one physical landscape scan containing **two printed pages, 54–55**, with illustration material;
- scan **64 / printed 62** — internal heading `குமுதா`;
- scan **67 / printed 65** — internal heading `வீரன்`;
- scan **71 / printed 69** — internal heading `உலகநாதர்`;
- scan **72 / printed 70** — internal heading `கண்ணம்மா`;
- scan **74 / printed 72** — narrative ending, including `...எங்களிடம் வரவேண்டும், தெரியுமா?`.

The six internal headings occur in the same narrative order as the controlling 1953 edition, but at different page locations.

A directly visible paratext difference is already established: the 1953 controlling scan 49 separately prints `ஸ்ரீமகள் அச்சகம், சென்னை-1`; the 1978 witness scan 74 ends with the narrative and does **not** print that 1953 printer colophon.

## Comparison unit

For every 1978 physical scan:

1. visually read the complete printed text from source pixels;
2. identify the corresponding controlling 1953 span from canonical/assembled Tamil;
3. compare wording, spelling, punctuation, order and structural markers;
4. record differences before making any interpretation;
5. if a reading is uncertain, record **UNRESOLVED** — never infer from context;
6. record layout-only and non-textual differences separately from textual variants;
7. do not treat page-break differences as wording variants.

For scan 57, compare printed page 54 text independently and record printed page 55 illustration/non-textual content separately.

## Variant classes

Use only these classes:

- **WORDING** — lexical wording differs;
- **SPELLING / GLYPH** — source-visible orthographic or character-identity difference;
- **PUNCTUATION** — punctuation differs while wording is otherwise the same;
- **OMISSION** — text present in one witness but absent in the other;
- **ADDITION** — text present only in the 1978 witness;
- **ORDER** — same material appears in a different order;
- **HEADING / STRUCTURE** — internal heading or structural boundary differs;
- **PARATEXT** — title-page, colophon or other non-narrative printed matter differs;
- **NON-TEXTUAL** — illustration/layout feature; not a lexical variant;
- **UNRESOLVED** — source pixels do not support a confident classification.

Do not collapse spelling, punctuation and wording into a generic “difference.”

## Variant record schema

Each confirmed entry in `VARIANTS.md` must record:

- variant ID;
- 1978 physical scan;
- 1978 printed page / page faces;
- 1978 exact source reading;
- controlling 1953 scan / printed page / section;
- 1953 exact controlling reading;
- variant class;
- source confidence;
- comparison note;
- action: **record-only / no canonical change**.

If a variant crosses a page boundary, record all contributing source scans/pages on both sides.

## Batch plan

| Batch | 1978 scans | Printed mapping | Structural anchor |
|---|---:|---|---|
| W1 | 49–53 | unnumbered opening; 47–50 | opening → `உத்தண்டி` begins on scan 53 |
| W2 | 54–58 | 51–53; scan57 = 54–55; scan58 = 56 | `உத்தண்டி` → `கண்ணம்மா`; illustrated spread |
| W3 | 59–63 | 57–61 | `கண்ணம்மா` first narration |
| W4 | 64–67 | 62–65 | `கண்ணம்மா` tail → `குமுதா` → `வீரன்` |
| W5 | 68–72 | 66–70 | `வீரன்` → `உலகநாதர்` → final `கண்ணம்மா` |
| W6 | 73–74 | 71–72 | final `கண்ணம்மா` → narrative ending |

Batch boundaries are workflow controls only. They do not create source sections.

## Gate rule

A batch is complete only when:

- every physical scan in that batch has been directly inspected;
- corresponding 1953 text has been identified;
- all confirmed variants are entered in `VARIANTS.md`;
- unresolved source readings are explicitly listed;
- the progress record is synchronized;
- no controlling/assembled/English text has changed.

## Current state

- source identity: **CONFIRMED**;
- physical/printed mapping: **COMPLETE**;
- structural heading alignment: **COMPLETE**;
- comparison plan: **COMPLETE**;
- line-by-line witness comparison: **19 / 26 scans**;
- comparison batches completed: **4 / 6**;
- canonical / assembled / English changes: **0**.

**Next: W5 — scans 68–72 only.**
