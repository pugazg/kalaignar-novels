# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Current durable state

- manifest **179 / 179**;
- canonical records **111 / 179**;
- Chapter 12/13 boundary: **scan 107 / printed 106**, centered `13`;
- Chapter 13 transcribed through **scan 111 / printed 110**;
- historical-glyph work-level gate: **REOPENED**;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- retrospective historical-glyph re-audit: **PASS scans 1–45; PENDING scans 46–101**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Retrospective batches completed

### Scans 1–5

PASS. No historical-glyph correction. Separate ordinary source correction on scan 4: `பெருகிடுகிறது` → **`பெருகிவிடுகிறது`**.

### Scans 6–10

PASS. No canonical correction. Preserve scan 8 `அய் யோன்னு` and scan 9 `குழப்பட்டு` exactly as printed.

### Scans 11–15

PASS. No canonical correction. Representative confirmed identities include `என்றாள்`, `தாமரையானாள்`, `மாப்பிள்ளை`, `எத்துணை`, `பெற்றோர்களால்`, and `அர்ச்சுனனை`.

### Scans 16–20

PASS. No canonical correction. Scan 17 `வேலையில்ல` is genuine final `ல்ல`; scan 19 `வந்துவிட்டானு` is genuine final `னு`.

### Scans 21–25

PASS. No canonical correction. Scan 21 `வரணும்` is genuine `ணு`. Scan 23 **`வயதினள்`** is genuine `னள்` and must not be expanded to `வயதினாள்` merely from later missing-`ஆ` failures.

### Scans 26–30

PASS. No canonical correction. Scan 27 `காணோமே` is confirmed `ணோ`; scan 30 `பெண்ணொருத்தி` is confirmed `ணொ`.

### Scans 31–35

PASS. No canonical correction. Scan 31 `அவ்விதமானாள்` is source-confirmed. Scan 33 line-broken `நட்டு` + `வனார்` resolves to `நட்டுவனார்`. Scans 34–35 reconfirm recurring **`நயினா`**, not `நயினு`.

### Scans 36–40

PASS after four source-supported corrections:

- scan 38: `கண்ணின் மிகுதியால்` → **`களைப்பின் மிகுதியால்`** (`ளை`);
- scan 40: `எண்ணையாவது` → **`என்னையாவது`** (`னை`);
- scan 40: `அவர்களோ` → **`அவர்களை`** (`ளை`);
- scan 40: `கைவற்றுப்போனேன்` → **`கைவற்றுப்போனான்`** (`னா`).

Scans 36, 37 and 39 required no canonical correction.

### Scans 41–45

**PASS / 5 OF 5 COMPLETE.** No historical-family substitution was required.

Representative direct source confirmations:

- scan 41: `நயினா` (`னா`), `சாகவில்லையா` (`லை`), `நல்லவேளை` / `மாப்பிள்ளை` (`ளை`), `தவறாமல்` (`றா`);
- scan 42: `மாப்பிள்ளை` (`ளை`), `சரியில்லை` (`லை`), `பையனை` (`னை`), repeated `நயினா` / `கூறினாள்` (`னா`);
- scan 43: `மனைவிக்கும்` (`னை`), `மாற்றமாகிவிடவே` (`றா`), `பெண்ணைப்` (`ணை`), `நயினாவும்` (`னா`);
- scan 44: `மாப்பிள்ளை` (`ளை`), `நல்லநாள்` / `நயினா` / `போனாள்` (`னா`), `புறப்பட்டார்கள்` / `மறுத்தாள்` (`றா`), `இல்லையா` (`லை`);
- scan 45: `அழைத்துப்போனாள்` (`னா`), `களைப்பு` / `நல்லவேளை` / `களிப்பை` (`ளை`), `தொல்லை` / `காலையிலேதான்` (`லை`), repeated `நயினா` (`னா`).

Two separate ordinary source-fidelity corrections were required on scan 42 and are not historical-glyph substitutions:

- `பொறுத்துச்` → **`பொருத்தம்`**;
- `சுதன` → **`சனதன`**.

Scans 41, 43, 44 and 45 required no canonical text correction. Scan 45 remains the verified mixed Chapter 4 / Chapter 5 boundary with centered source heading `5`. No global replacement, grammar-driven normalization or silent modernization was used.

## Critical process correction

The previous historical-glyph pass was not applied correctly in several places. Old metal-type shapes were sometimes retained as modern visual look-alikes instead of being decoded to actual character identities. Confirmed corrective work in scans 102–111 remains controlling, including `நன்றாகக்`, `தவறாக`, `என்றாள்`, multiple missing-`ஆ` corrections, `சொன்னா`, and `பெண்ணா?`.

Mandatory set on every retrospective scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Character identity must be decided from enlarged/native source pixels first. Grammar is only a locator. Never global-replace.

## Preserve these structural/source decisions

- recurring name **`நயினா`**, not `நயினு`;
- scan 23 source **`வயதினள்`** is genuine;
- scan 27 source `காணோமே` is `ணோ`;
- scan 30 `பெண்ணொருத்தி` is `ணொ`;
- scan 31 `அவ்விதமானாள்` is genuine `னா`;
- scan 33 `நட்டுவனார்` is source-supported;
- scan 38 phrase is **`களைப்பின் மிகுதியால்`**;
- scan 40 forms are **`என்னையாவது`**, **`அவர்களை`**, **`கைவற்றுப்போனான்`**;
- scan 42 source wording includes **`பொருத்தம் சரியில்லை`** and **`சனதன உள்ளம்`**;
- scan 45 is mixed Chapter 4 / Chapter 5 with centered `5`;
- scan 66 visible page number is **`5`**, never infer `65`;
- scan 98 bottom standalone `7` is a printer/signature mark, not a chapter heading;
- scan 99 is mixed Chapter 11 / Chapter 12 with centered `12`;
- scan 107 is mixed Chapter 12 / Chapter 13 with centered `13`;
- scan 111 ends physical `சிறிதா`; scan 112 begins source-visible `வது`, forming `சிறிதாவது` across the page boundary.

## Exact next activity

Forward transcription remains paused.

1. re-fetch live `main`;
2. resolve the controlling PDF;
3. perform retrospective historical-glyph audit of **scans 46–50** as one 5-scan iteration;
4. explicitly test all 13 families on source pixels;
5. correct only positively supported character identities; never infer from grammar and never global-replace;
6. synchronize page records, page-map, audit, README/status/handover documents and commit;
7. continue retrospectively in 5-scan order until scans 1–101 are cleared;
8. only then resume forward transcription at scan 112.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
