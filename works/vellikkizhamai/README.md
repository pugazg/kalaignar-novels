# வெள்ளிக்கிழமை

**ஆசிரியர் (source cover):** மு. கருணாநிதி  
**வெளியீடு:** திராவிடப்பண்ணை, 34, சிந்தாமணி, திருச்சி-2  
**பதிப்பு:** இரண்டாம் பதிப்பு — 1968  
**Source PDF:** `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
**Source PDF committed:** No

## Current archival status

- actual PDF scan count: **179**; size **251,126,214 bytes**;
- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`;
- page manifest: **179 / 179**;
- canonical page records: **138 / 179**;
- Chapter 14 / 15 boundary: **scan 120 / printed 119**, centered `15`;
- Chapter 16 opening: **scan 127 / printed 126**, centered `16`;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 17 transcribed through **scan 138 / printed 137**;
- historical-glyph coverage: **PASS scans 1–138**;
- next forward batch: **scans 139–143**;
- batch size: **5 scans per iteration**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Mandatory historical-glyph rule

Every scan is checked directly against:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Character identity comes from source pixels first. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing, colloquial forms and physical page boundaries. Never global-replace.

The expanded corrective re-audit remains controlling: old-type `னா` / `றா` shapes must not be converted from grammatical expectation. Recurring **`நயினா`** and independently confirmed source-specific forms remain authoritative.

## Production workflow

Use the bounded 5-page workflow:

1. transcribe all five full pages straight through;
2. run one batch-level mandatory 13-family glyph sweep;
3. allow at most one targeted enlargement for a genuinely unclear token;
4. if still unresolved, record a source hold and continue;
5. create the five canonical records and synchronize status documents once;
6. make one atomic commit;
7. do not reopen prior PASS scans without new direct source evidence.

## Recent forward results

- **scan 129 / printed 128:** PASS; begins `அவளை`; ends physical `அழகப்ப`;
- **scan 130 / printed 129:** PASS; begins `னுடைய` → `அழகப்பனுடைய`; `நயினா`; bottom `9` printer/signature mark;
- **scan 131 / printed 130:** PASS; `நயினாமுகம்மது`, `நயினாவின்`; ends `பின்னிக்`;
- **scan 132 / printed 131:** PASS; begins `கொண்டன;` → `பின்னிக்கொண்டன`; `நயினாவிடமிருந்து`;
- **scan 133 / printed 132:** PASS; `நயினா முகம்மது`, `நயினாவுக்கு`, `நகை நட்டுக்களை`;
- **scan 134 / printed 133:** PASS; mixed Chapter 16 / 17 boundary, centered `17`; preserve `முழுசம்`, `எழுதியிட்டான்`; ends physical `நயினாவின்`;
- **scan 135 / printed 134:** PASS; begins `கேள்வி`; preserve `பார்த்து.`, `செளக்கியந்தானே!`, `இப்படி யென்றால்`; ends physical `வருத்தத்`;
- **scan 136 / printed 135:** PASS; begins `தோடு` → `வருத்தத்தோடு`; preserve `சொல்லுகிறாளாக்கும்`, `பதிலக் கேள்வி`;
- **scan 137 / printed 136:** PASS; preserve `சிக்கலங்கிப்போயிருக்கிறோம்`; ends inside open quotation `“இதோ,`;
- **scan 138 / printed 137:** PASS; begins `கொண்டுவருகிறேன்”`; preserve `வந்துவிட்டுமா?`; ends literal `‘மளமள’`.

## Durable physical/source boundaries

- scan 124 / 125: `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127 / 128: `வாழ்` + `விலே` = `வாழ்விலே`;
- scan 129 / 130: `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`;
- scan 131 / 132: `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`;
- scan 134 / 135: `நயினாவின்` → `கேள்வி`;
- scan 135 / 136: `வருத்தத்` + `தோடு` = `வருத்தத்தோடு`;
- scan 137 / 138: `“இதோ,` → `கொண்டுவருகிறேன்”`;
- scan 138 ends literal `‘மளமள’`; do not complete from inference.

## Key records

- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`audit.md`](audit.md)
- canonical pages through [`pages/0138-vellikkizhamai-135.md`](pages/0138-vellikkizhamai-135.md)

## Exact next activity

Process **scans 139–143** as one bounded 5-page forward iteration. Establish scan 139 only from direct source evidence, beginning from scan 138's literal final `‘மளமள’`. Do not start assembled Tamil or English.
