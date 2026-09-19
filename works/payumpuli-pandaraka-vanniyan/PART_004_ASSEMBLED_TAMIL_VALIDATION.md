# Part 004 — Assembled Tamil Validation

Work: `பாயும்புலி பண்டாரக வன்னியன்`  
Repository: `pugazg/kalaignar-novels`  
Branch: `main`

## Result

**PART004 ASSEMBLED TAMIL — COMPLETE / PASS / CLOSED.**

This validation audits the readable Part004 Tamil layer under `sections/` against the already-verified canonical Part004 `pages/` records.

Pre-assembly live-main checkpoint:

`a5a05c537aab21b001f9425941a911cc0800b4f3`

No source PDF was reopened. Assembly used the canonical verified Part004 page records as the textual authority.

## Inventory gate

- newly assembled Part004 files — **5/5**
- represented Part004 physical scans — **91–120**
- canonical Part004 source-transcription pages represented — **30/30**
- omitted canonical Part004 pages — **0**
- duplicate canonical Part004 pages — **0**
- every Part004 assembled section status — **verified**
- frozen Part001–Part003 assembled files modified — **0**
- Part005 assembled/canonical content introduced — **0**

Part004 section inventory:

1. `sections/18-adhikaari-vazhangiya-aalosanai-part004.md` — scans91–94 — chapter 11 continuation/close;
2. `sections/19-mannippu-yaar-yaaridam.md` — scans95–102 — chapter 12;
3. `sections/20-maana-maraippu-marakkalaamaa.md` — scans103–109 — chapter 13;
4. `sections/21-aval-nadantha-paathai.md` — scans110–115 — chapter 14;
5. `sections/22-iruvar-ullam.md` — scans116–120 — chapter 15 continuation to the Part boundary.

## Exact canonical-text comparison

Each Part004 assembled file was constructed directly from the corresponding verified canonical `## Source transcription` blocks.

Comparison removes only:
- assembled YAML front matter;
- non-rendering physical source-boundary provenance comments;
- incoming/outgoing non-rendering Part-boundary provenance comments;
- the inline non-rendering split-word provenance marker at **113→114**.

Results:

| Section | Canonical comparison |
|---|---|
| chapter 11 continuation `அதிகாரி வழங்கிய ஆலோசனை`, scans91–94 | **EXACT / PASS** |
| `மன்னிப்பு யார்? யாரிடம்?`, scans95–102 | **EXACT / PASS** |
| `மான மறைப்பு மறக்கலாமா?`, scans103–109 | **EXACT / PASS** |
| `அவள் நடந்த பாதை`, scans110–115 | **EXACT / PASS** |
| `இருவர் உள்ளம்`, scans116–120 | **EXACT / PASS** |

Audit/review/workflow-note leakage into Part004 assembled body text — **0**.

Unsupported Tamil body insertion — **0**.

## Cross-page join gate

Verified physical continuations are retained without unsupported reconstruction, including:

- incoming **90→91 — GENUINE CONTINUATION** as provenance only;
- 91→92 — `பிரயத்தனப்பட` → `வேண்டியிருக்கும்.`;
- 95→96 — `முதல் பிரகடனமாக` → `அமையும்`;
- 100→101 — `போரிட்டுத்` → `திரும்பப் பெறும் பரம்பரையே...`;
- 105→106 — quoted speech continues;
- 106→107 — `தனது கையில் தரப்பட்ட` → `அந்த மடலைக்...`;
- 107→108 — சங்கிலித் தளபதியின் letter continues;
- 110→111 — `அந்த` → `அம்மையைத்...`;
- 112→113 — `தமிழ் இலக்கியப்` → `புலமை பெற்றிட`;
- 113→114 — verified split word rendered continuously as `பிரச்சினையைப்` with an inline non-rendering provenance marker;
- 117→118 — `கொள்பவள்` → `தானே நான்!`;
- 118→119 — `அவரைக்` → `காக்கை வன்னியன் மாளிகையில்...`;
- 119→120 — `அவர்களைத்` → `தனது விழிகளால்...`;
- outgoing **120→121 — GENUINE CONTINUATION** as provenance only.

No Part005 body text is imported to complete scan120's terminal `விலை` + scan121 witness `யாட்டுக்...`.

## Structural gate

Source-visible Part004 order is retained:

1. scans91–94 — chapter 11 continuation/close `அதிகாரி வழங்கிய ஆலோசனை`;
2. scans95–102 — chapter 12 `மன்னிப்பு யார்? யாரிடம்?`;
3. scans103–109 — chapter 13 `மான மறைப்பு மறக்கலாமா?`;
4. scans110–115 — chapter 14 `அவள் நடந்த பாதை`;
5. scans116–120 — chapter 15 `இருவர் உள்ளம்`.

Printed-page/provenance authority remains the canonical page map: scan91 → printed81 through scan120 → printed110.

## Non-body exclusion gate

Assembly excludes only matter already classified outside readable literary body/source text:

- recurring ornamental page furniture;
- intentional blank lower fields on scans94, 102 and 109;
- review/audit commentary and page-record metadata.

Meaningful source text remains represented:
- chapter numbers/titles on scans95, 103, 110 and 116;
- source-leading dash lineation on scan97;
- the displayed letter closing/signature on scan108.

No verified Part004 `## Source transcription` block is omitted.

## Boundary gates

Incoming boundary:
- **90→91 = GENUINE CONTINUATION / AUDITED**;
- frozen Part003 body text imported into Part004 assembly — **0**;
- frozen Part003 assembled files modified — **0**.

Outgoing boundary:
- scan120 terminal text remains `தனது காதல் விலை`;
- **120→121 = GENUINE CONTINUATION / AUDITED**;
- scan121 / Part005 Tamil body imported into Part004 assembly — **0**;
- unsupported completion of the split word — **0**.

## Canonical-integrity gate

Assembly is a derived reading layer only.

- canonical `pages/` mutations — **0**
- Tamil wording corrections during assembly — **0**
- punctuation corrections during assembly — **0**
- page-map authority changes caused by assembly — **0**
- canonical status changes caused by assembly — **0**
- frozen Part001–Part003 assembled-file mutations — **0**

The canonical Part004 `pages/` layer remains authoritative for any future discrepancy.

## Decision

**ASSEMBLED TAMIL MASTER — PASS / VERIFIED.**

Part004 assembled Tamil is now **PASS / CLOSED — 5/5 VERIFIED**.

## Exact next gate

Begin **Part004 English translation planning/setup**.

Do not draft English prose in this assembled-Tamil gate. Do not begin release/readiness, final Part004 closure or Part005 transcription.

## Post-assembly English planning/setup

This assembled-Tamil validation remains **PASS / CLOSED**.

Part004 English planning/setup subsequently completed without reopening canonical or assembled Tamil:

- planning/setup — **COMPLETE / PASS**
- planned English batches — **E15–E19**
- translated/source-checked files — **0/5**
- unresolved planning holds — **0**
- canonical Tamil changes caused by planning — **0**
- assembled Tamil body changes caused by planning — **0**
- frozen Part001–Part003 English body changes — **0**
- Part005 leakage — **0**

Current next gate:

**E15 — draft + source-check — scans91–94.**
