# Transcription / Source Audit — வெள்ளிக்கிழமை

## Current gate

| Check | Status |
|---|---|
| Source identity / checksum / page count | **complete** |
| Initial scan manifest | **179 / 179 represented** |
| Canonical page records | **111 / 179** |
| Body transcription | **through scan 111** |
| Printed-page map | **directly confirmed through scan 111; scan 66 visibly prints only `5`** |
| Chapter map | **direct through Chapter 13 continuation at scan 111** |
| Historical-glyph work-level gate | **REOPENED** |
| Corrective historical-glyph re-audit | **PASS scans 102–111** |
| Retrospective historical-glyph re-audit | **PASS scans 1–45; PENDING scans 46–101** |
| Full Tamil source audit | **not started** |
| Assembled Tamil | **not started** |
| English translation | **blocked until Tamil gate passes** |

## Why the gate was reopened

The historical-glyph guide requires character identity to be decoded from old type before Unicode transcription. The earlier pass failed this rule in multiple places by treating old glyphs as modern look-alikes. Because the same typeface is used across the work, the earlier work-level PASS claim remains withdrawn pending retrospective review.

Mandatory set on every retrospective scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Families without a relevant occurrence are still explicitly considered. Every present form is decided from source pixels, not grammar. Never global-replace.

## Retrospective re-audit — scans 1–5

**PASS / 5 OF 5 COMPLETE.** No historical-family correction. Separate ordinary source-fidelity correction on scan 4: `பெருகிடுகிறது` → **`பெருகிவிடுகிறது`**.

## Retrospective re-audit — scans 6–10

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Scan 8 `அய் யோன்னு` and scan 9 `குழப்பட்டு` retained as printed.

## Retrospective re-audit — scans 11–15

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Representative source-confirmed families include `என்றாள்`, `தாமரையானாள்`, `மாப்பிள்ளை`, `எத்துணை`, `பெற்றோர்களால்`, `அர்ச்சுனனை`.

## Retrospective re-audit — scans 16–20

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Scan 17 `வேலையில்ல` retained as genuine final `ல்ல`; scan 19 `வந்துவிட்டானு` retained as genuine final `னு`.

## Retrospective re-audit — scans 21–25

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Scan 21 `வரணும்` is genuine `ணு`; scan 23 `வயதினள்` is genuine `னள்`, not `வயதினாள்`.

## Retrospective re-audit — scans 26–30

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Scan 27 `காணோமே` confirms `ணோ`; scan 30 `பெண்ணொருத்தி` confirms `ணொ`.

## Retrospective re-audit — scans 31–35

**PASS / 5 OF 5 COMPLETE.** No canonical correction. Scan 31 `அவ்விதமானாள்` is source-confirmed; scan 33 `நட்டுவனார்` is confirmed; scans 34–35 reconfirm `நயினா`, not `நயினு`.

## Retrospective re-audit — scans 36–40

**PASS / 5 OF 5 COMPLETE after four source-supported corrections.**

| Scan | Earlier canonical | Source-supported | Type |
|---:|---|---|---|
| 38 | `கண்ணின் மிகுதியால்` | **`களைப்பின் மிகுதியால்`** | `ளை` family / source fidelity |
| 40 | `எண்ணையாவது` | **`என்னையாவது`** | `னை` family |
| 40 | `அவர்களோ` | **`அவர்களை`** | `ளை` family |
| 40 | `கைவற்றுப்போனேன்` | **`கைவற்றுப்போனான்`** | `னா` family |

Scans 36, 37 and 39 required no correction.

## Retrospective re-audit — scans 41–45

**PASS / 5 OF 5 COMPLETE. No historical-family substitution was required.**

| Scan | Representative source check | Historical family / result |
|---:|---|---|
| 41 | `நயினா`, `சாகவில்லையா`, `நல்லவேளை`, `மாப்பிள்ளை`, `தவறாமல்` | `னா`, `லை`, `ளை`, `றா` confirmed; no correction |
| 42 | `மாப்பிள்ளை`, `சரியில்லை`, `பையனை`, `நயினா`, `கூறினாள்` | `ளை`, `லை`, `னை`, `னா` confirmed; no historical-family correction |
| 43 | `மனைவிக்கும்`, `சரியில்லை`, `மாற்றமாகிவிடவே`, `பெண்ணைப்`, `நயினாவும்` | `னை`, `லை`, `றா`, `ணை`, `னா` confirmed; no correction |
| 44 | `மாப்பிள்ளை`, `நல்லநாள்`, `நயினா`, `புறப்பட்டார்கள்`, `மறுத்தாள்`, `இல்லையா`, `போனாள்` | `ளை`, `னா`, `றா`, `லை` confirmed; no correction |
| 45 | `அழைத்துப்போனாள்`, `களைப்பு`, `தொல்லை`, `நல்லவேளை`, `நயினா`, `காலையிலேதான்`, `களிப்பை` | `னா`, `ளை`, `லை` confirmed; no correction |

Two separate **ordinary source-fidelity corrections** were positively supported on scan 42:

| Scan | Earlier canonical | Source-supported | Classification |
|---:|---|---|---|
| 42 | `பொறுத்துச்` | **`பொருத்தம்`** | ordinary source-text correction, not glyph substitution |
| 42 | `சுதன` | **`சனதன`** | ordinary source-text correction, not glyph substitution |

The source-visible `சரியில்லை` on scan 42 was independently checked and remains unchanged; it must not be shortened merely because the old `லை` form can be visually deceptive. Scan 45's centered `5` remains the Chapter 4 / Chapter 5 boundary. No global replacement, lexical modernization or grammar-driven repair was used.

## Corrective re-audit — scans 102–111

**PASS for the ten-scan corrective range.** Confirmed historical corrections include `ஆட்டினாள்`, `நன்றாகக்`, `கத்தினாள்`, `கூறினாள்`, `திருப்பினாள்`, `என்றாள்`, `தவறாக`, `கொட்டினான்`, `ஓடினான்`, `ஓடினார்கள்`, `திமிறினான்`, `நடுங்கினாள்`, `சொன்னா`, `பொய்தானா?`, and `பெண்ணா?`. Scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were independently rechecked and retained. No global replacement was used.

## Structural results to preserve

- scan 33: mixed Chapter 3 / Chapter 4 with centered `4`;
- scan 45: mixed Chapter 4 / Chapter 5 with centered `5`;
- scan 66: source visibly prints only page number `5`; never infer `65`;
- scan 92: mixed Chapter 10 / Chapter 11 with centered `11`;
- scan 99: mixed Chapter 11 / Chapter 12 with centered `12`;
- scan 107: mixed Chapter 12 / Chapter 13 with centered `13`;
- scan 111 ends physical `சிறிதா`; scan 112 begins `வது`, yielding assembled `சிறிதாவது` only in a reversible assembled layer.

## Unresolved project items

- **retrospective historical-glyph re-audit scans 46–101**;
- scans **112–179** forward canonical processing;
- final complete Tamil audit;
- assembled Tamil;
- English after Tamil gate.

## Exact next activity

Do **not** resume forward transcription yet. Process **scans 46–50** as the next retrospective 5-scan historical-glyph audit batch, update only positively source-supported corrections, synchronize page/status documents, and continue chronologically.
