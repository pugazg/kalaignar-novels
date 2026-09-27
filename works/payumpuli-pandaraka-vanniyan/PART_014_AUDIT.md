# Part 014 Audit — பாயும்புலி பண்டாரக வன்னியன்

## Audit decision

**PART014 PART AUDIT — PASS / COMPLETE**

This audit reconciles the live Part014 canonical records, page map and completed gate evidence after Pass1, Pass2A, Pass2B and Pass3.

No canonical Tamil body text is changed by this audit. No metadata status is promoted in this gate.

## Authoritative scope

- repository — `pugazg/kalaignar-novels`
- branch — `main`
- work — `works/payumpuli-pandaraka-vanniyan/`
- Part — **014**
- source — `TVA_BOK_0065744_பாயும்புலி_பண்டாரக_வன்னியன்_part_014_pages_391-420.pdf`
- source SHA-256 — `0111fbe0c8b8356f1735320bcf36a7354b46bc375c7e049dae5564b81f82aedf`
- canonical scans — **391–420**
- local pages — **1–30**
- observed printed-folio coverage — **384–414**
- source-layout anomaly — **scan403 carries two printed folios 396–397**
- Parts001–013 — **FINAL CLOSED / FROZEN**

## Gate prerequisites

| Gate | Audit state |
|---|---|
| Pass1 | **PASS — 30/30 TEXT-COMPLETE** |
| Pass2A | **PASS — 30/30 REVIEWED — 22 corrections** |
| Pass2B | **PASS — 30/30 REVIEWED — 13 additional corrections** |
| Pass3 | **PASS — 30/30 VISUAL / STRUCTURAL REVIEWED — 0 textual corrections** |
| incoming 390→391 | **CLEAN CHAPTER BOUNDARY / AUDITED / PASS** |
| outgoing 420→421 | **CLEAN CHAPTER BOUNDARY / AUDITED / PASS** |

## Canonical inventory audit

Live `pages/` contains exactly the expected **30** Part014 canonical paths, scans **391–420**.

Page-map reconciliation:
- Part014 rows — **30/30**
- local `part_page` sequence — **1–30 continuous**
- global `scan_page` sequence — **391–420 continuous**
- printed-folio coverage — **384–414 continuous**
- physical scan403 maps to **printed396–397**
- missing local-page entries — **0**
- duplicate scan-number entries — **0**
- missing printed folios inside 384–414 — **0**
- duplicate printed-folio assignments — **0**
- page-map textual status — **30/30 verified**

Canonical metadata state before final-status synchronization:
- textual `status: "verified"` — **30/30**
- `visual_fidelity: "needs-review"` — **30/30**
- formal Pass2A evidence — **30/30**
- formal Pass2B evidence — **30/30**
- formal Pass3 evidence — **30/30**

Missing Part014 canonical records — **0**.  
Duplicate Part014 scan records — **0**.

Result: **PASS.**

## Printed-folio mapping audit

Canonical metadata and the live page map agree on the source-observed folio sequence:

- scans391–402 → printed **384–395**
- scan403 → printed **396–397**
- scans404–420 → printed **398–414**
- no printed-folio gap inside Part014
- no duplicated printed folio
- the scan403 two-folio spread is preserved as a source-layout fact, not normalized to a one-scan/one-folio assumption

Result: **PASS — no pagination mismatch found.**

## Section / structural audit

Part014 structure is internally consistent:

1. scans391–395 — chapter63 `மாறுவேட மருத்துவர்!`; opens391 / closes395;
2. scans396–401 — chapter64 `அதிர்ந்தது போர்முரசு!`; opens396 / closes401;
3. scans402–408 — chapter65 `கண்டிக்குள் களம்!`; opens402 / closes408;
4. scans409–414 — chapter66 `வெள்ளைக் கொடியும்- வெற்றி விழாவும்!`; opens409 / closes414;
5. scans415–420 — chapter67 `இரத்தம் படிந்த வாள்!`; opens415 / closes at the audited Part014 boundary.

Displayed chapter openings — **391, 396, 402, 409, 415**.

Intentional blank lower fields confirmed by Pass3:
- scan408 — chapter65 close;
- scan420 — substantial intentional blank lower field after the final visible exclamation.

Representative physical continuation states confirmed:
- 392→393 — **`பண்டாரக` + `வன்னியனுக்குத்`**;
- 394→395 — **`உணர்வு` + `வந்தவளாக`**;
- 400→401 — sentence continuation after **`என்பதை`**;
- 402→403 — **`எனக்குப் போட்டியாக` + `முளைத்தவன்!`**;
- scan403 internal spread — printed396→397 preserved inside one physical scan;
- 403→404 — **`ஆனால் மெக்டோவலின் படை` + `நுழையும்போது`**;
- 404→405 — open quotation continuation with source-leading hyphen;
- 406→407 — **`கண்டியின்` + `உதவிக்கு`**;
- 410→411 — open dialogue **`உங்கள்` + `நெஞ்சில்`**;
- 412→413 — **`வீரனுக்கு` + `அழகுமில்லை!`**;
- 413→414 — **`சேர` + `அனுமதிக்கப்படுகிறார்.`**;
- 415→416 — **`இருப்பதை` + `உணர்ந்து கொள்ள முடிந்தது.`**;
- 418→419 — **`கொலுமண்டபத்திற்குள்` + `நுழைந்தனர்.`**;
- 419→420 — **`பீடத்திலிருக்கும்` + `வாளை`**.

Result: **PASS.**

## Boundary / cross-page audit

Incoming:
- **390→391 = CLEAN CHAPTER BOUNDARY / AUDITED / PASS**;
- Parts001–013 remain unchanged;
- no frozen Part013 canonical / assembled / maintained-English body was rewritten by Part014 processing.

Outgoing:
- **420→421 = CLEAN CHAPTER BOUNDARY / AUDITED / PASS**;
- scan420 closes chapter67 at the Part014 source boundary;
- Part015 scan421 opens displayed chapter68 `ஒரு பெண்ணின் பிராயச்சித்தம்!`;
- no Part015 canonical page record was created;
- no Part015 wording was imported into Part014.

Result: **PASS.**

## Correction-ledger audit

### Pass 2A

Source-supported corrections — **22** across scans **391, 392, 394, 395, 397, 401, 407, 408, 409, 410, 411, 412, 413, 415**.

Durable ledger authority:
- `PART_014_PASS2A_PROGRESS.md`

Unresolved Pass2A textual questions — **0**.

### Pass 2B

Additional source-supported corrections — **13** across scans **392, 393, 394, 400, 402, 404, 405, 409, 411, 413, 415, 416**:

- scan392 — `ஆமாம் - இனிமேல்` → **`ஆமாம்- இனிமேல்`**;
- scan392 — `கொழுக்கும் என் இளமை` → **`கொழிக்கும் என் இளமை`**;
- scan393 — `ஏற்றுப் புறப்படு!` → **`ஏற்றுப்புறப்படு!`**;
- scan394 — `கை அசைத்து விட்டு குதிரையைக் கட்டிவிட்டான்.` → **`கை அசைத்து விட்டுக் குதிரையைத் தட்டி விட்டான்.`**;
- scan400 — `நல்லதாகத்தான்` → **`நல்லதாகத் தான்`**;
- scan402 — `மெக்டோவல் உத்திரவை` → **`மெக்டோவல் உத்தரவை`**;
- scan404 — `இருமாப்புடனும்` → **`இறுமாப்புடனும்`**;
- scan405 — `உங்களை கோயில்` → **`உங்களைக் கோயில்`**;
- scan409 — `பண்டாரக வன்னியனுக்கு தெரிவிக்கப்பட்டது.` → **`பண்டாரக வன்னியனுக்குத் தெரிவிக்கப்பட்டது.`**;
- scan411 — `ஓடிவந்து` → **`ஓடி வந்து`**;
- scan413 — `உணர்த்தியிருக்காவது,` → **`உணர்ந்தபிறகாவது,`**;
- scan415 — `பெண் -நீங்களோ` → **`பெண்-நீங்களோ`**;
- scan416 — `நினைத்துப் பார்க்க வேண்டும்.` → **`நினைத்துப்பார்க்கவேண்டும்.`**.

Historical-glyph corrections — **0**.  
Unresolved Pass2B lexical / historical-glyph questions — **0**.

### Pass 3

- textual corrections — **0**
- unresolved visual / structural questions — **0**

Result: **PASS — correction history reconciled.**

## Unresolved-item accounting

- unresolved Pass1 source-reading holds — **0**
- unresolved Pass2A textual questions — **0**
- unresolved Pass2B lexical / historical-glyph questions — **0**
- unresolved Pass3 visual / structural questions — **0**
- missing canonical pages — **0**
- duplicate canonical pages — **0**
- internal pagination / chapter-structure mismatches — **0**
- pending Part014 boundary items — **0**

No blocker remains for final metadata/status synchronization.

## Frozen / leakage audit

- Parts001–013 remain **FINAL CLOSED / FROZEN**
- Part014 Part audit introduces **0** canonical Tamil body mutations
- Part014 Part audit introduces **0** textual-status promotions
- Part014 Part audit introduces **0** visual-fidelity promotions
- Part015 canonical records created — **0**
- Part015 body / structure leakage — **0**

Result: **PASS.**

## Final audit decision

**PART014 PART AUDIT — PASS / COMPLETE**

Current metadata remains:
- textual `status: "verified"` — **30/30**
- `visual_fidelity: "needs-review"` — **30/30**

Canonical body mutations caused by this audit — **0**.  
Status promotions caused by this audit — **0**.  
Part015 leakage — **0**.

## Exact next activity

Perform **Part014 final metadata/status synchronization**.

Promote only `visual_fidelity` from `needs-review` to `verified` across the 30 audited Part014 canonical records. Textual `status` is already `verified`.

Do not change Tamil body text, punctuation, structure, provenance, pagination, page type, section labels, correction-ledger decisions or boundary classifications.
