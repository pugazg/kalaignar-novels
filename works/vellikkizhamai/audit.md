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
| Retrospective historical-glyph re-audit | **PASS scans 1–55; PENDING scans 56–101** |
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

## Retrospective re-audit — scans 46–50

**PASS / 5 OF 5 COMPLETE after source-supported corrections on scans 46–49. Scan 50 required no correction.**

All five scans were re-inspected directly against the complete 13-family set. Character identities and ordinary lexical readings were accepted only where positively supported by enlarged/native source pixels.

| Scan | Earlier canonical | Source-supported | Classification |
|---:|---|---|---|
| 46 | `தோஷம் கழந்துவிட்டதம்மா` | **`வேஷம் கலைந்துவிட்டதம்மா`** | source fidelity; `லை` identity directly confirmed in `கலைந்த...` |
| 46 | first `தப்பிவிட்டோம்` | **`தப்பி விட்டோம்`** | ordinary source spacing |
| 46 | `தடையோட்டார்களே` | **`தடை போட்டார்களே`** | ordinary source-text correction |
| 46 | `நெருப்புமொழிகளும்` | **`நெருப்பு மொழிகளும்`** | ordinary source spacing |
| 46 | `அசைவற்று போனார்` | **`அசைவற்றுப் போனார்`** | ordinary source-text correction |
| 47 | `மானத்தைப்பற்றிய கவலையுண்டு` | **`மானத்தைப்பற்றியே கவலைப்படாத`** | source-text correction; `லை` confirmed in `கவலை...` |
| 47 | `அனுப்பதாக` | **`அளிப்பதாக`** | ordinary source-text correction |
| 48 | `அக்ரமம்` | **`அகரமம்`** | source spelling retained exactly |
| 49 | `மாசுமறுவற்ற` | **`மாசமறுவற்ற`** | ordinary source-text correction |

Representative historical-family confirmations include scan 46 `மாப்பிள்ளை` / `நல்ல வேளை` (`ளை`), `நயினா` (`னா`), `கலைந்துவிட்டதம்மா` (`லை`); scan 47 `மாப்பிள்ளை` (`ளை`), `என்னை` (`னை`), `கவலைப்படாத` (`லை`), `நயினா` (`னா`), `தாயாகியிருக்கிறாள்` (`றா`); scan 48 `நயினாவும்` (`னா`) and `களைப்பால்` (`ளை`); scan 49 `கல்யாணம்` (`ணா`), `மாற்றிக்கொள்ளுங்கள்` (`றா`), `மாப்பிள்ளை` (`ளை`), `நாள்தோறும்` (`றோ`); and scan 50 `நயினா` (`னா`), `பெண்ணை` / `கண்ணை` (`ணை`), `பரவாயில்லை` (`லை`), `மாசற்றவள்` (`றா`).

No global replacement, grammar-driven normalization, or silent modernization was used. Source-specific scan-50 forms `ஏமுட்டான்` and `புறப்படடா` were retained exactly as printed.

## Retrospective re-audit — scans 51–55

**PASS / 5 OF 5 COMPLETE.** Scans 52, 54 and 55 received positively source-supported corrections; scans 51 and 53 required no canonical text correction.

| Scan | Earlier canonical | Source-supported | Classification |
|---:|---|---|---|
| 52 | `குபுகுபு` | **`குபு குபு`** | ordinary source spacing |
| 52 | `அவங்களுக்கேதான்` | **`அவங்களுக்கே தான்`** | ordinary source spacing |
| 52 | `பாலூர்` (two occurrences) | **`பாலையூர்`** | source fidelity; historical `லை` directly confirmed in `பாலை...` |
| 52 | `பாலூர் மருத்துவமனையில்` | **`பாலையூர் மருத்துவ மனையில்`** | source wording / spacing |
| 54 | `விரும்பினான்` | **`விரும்பினன்`** | source-specific `னன்`; explicit counterexample to automatic `னா` expansion |
| 54 | `இந்த மனத் தத்துவத்தை` | **`இந்த மன தத்துவத்தை`** | source sandhi fidelity; no inserted `த்` |
| 55 | `மருத்துவமனையிலிருந்து` | **`மருத்துவ மனையிலிருந்து`** | ordinary source spacing |

Representative historical-family confirmations include scan 51 `மண்ணாய்ப்` (`ணா`), `நயினா` (`னா`), `மாறி மாறிச்` (`றா`), `நல்லவேளை` (`ளை`); scan 52 `அவளை` (`ளை`), `பாலையூர்` / `தலையை` (`லை`), `நயினா` (`னா`); scan 53 `வளைப்பாள்` (`ளை`), `உளறுகிறாள்` (`றா`), `தாயில்லை` (`லை`); scan 54 `மாப்பிள்ளை` (`ளை`), `தவறில்லைதான்` / `கவலை` (`லை`), `மறுத்துரைத்தாள்` (`றா`); and scan 55 `இல்லையென்றாலும்` / `புரியவில்லையே` (`லை`), `கவலைப்பட்டுக்கொண்டிருந்தாள்` (`லை`, `றா`), `தொடங்கினாள்` (`னா`).

Two source-specific counterexamples were deliberately preserved: scan 53 `பருவத்தினள்` is genuine final `னள்`, and scan 54 `விரும்பினன்` is genuine `னன்`; neither was expanded from grammar. Scan 55 source-specific `வேறுயிற்றே` and `பேசினர்கள்` also remain unchanged. No global replacement or silent modernization was used.

## Corrective re-audit — scans 102–111

**PASS for the ten-scan corrective range.** Confirmed historical corrections include `ஆட்டினாள்`, `நன்றாகக்`, `கத்தினாள்`, `கூறினாள்`, `திருப்பினாள்`, `என்றாள்`, `தவறாக`, `கொட்டினான்`, `ஓடினான்`, `ஓடினார்கள்`, `திமிறினான்`, `நடுங்கினாள்`, `சொன்னா`, `பொய்தானா?`, and `பெண்ணா?`. Scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were independently rechecked and retained. No global replacement was used.

## Structural results to preserve

- scan 33: mixed Chapter 3 / Chapter 4 with centered `4`;
- scan 45: mixed Chapter 4 / Chapter 5 with centered `5`;
- scan 52: source-printed Chapter 6 opening with centered `6`;
- scan 66: source visibly prints only page number `5`; never infer `65`;
- scan 92: mixed Chapter 10 / Chapter 11 with centered `11`;
- scan 99: mixed Chapter 11 / Chapter 12 with centered `12`;
- scan 107: mixed Chapter 12 / Chapter 13 with centered `13`;
- scan 111 ends physical `சிறிதா`; scan 112 begins `வது`, yielding assembled `சிறிதாவது` only in a reversible assembled layer.

## Unresolved project items

- **retrospective historical-glyph re-audit scans 56–101**;
- scans **112–179** forward canonical processing;
- final complete Tamil audit;
- assembled Tamil;
- English after Tamil gate.

## Exact next activity

Do **not** resume forward transcription yet. Process **scans 56–60** as the next retrospective 5-scan historical-glyph audit batch, update only positively source-supported corrections, synchronize page/status documents, and continue chronologically.
