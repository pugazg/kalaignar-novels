# Part 015 — Assembled Tamil Validation

Work: `பாயும்புலி பண்டாரக வன்னியன்`  
Repository: `pugazg/kalaignar-novels`  
Branch: `main`

## Result

**PART015 ASSEMBLED TAMIL — COMPLETE / PASS / CLOSED**

This validation audits the readable Part015 Tamil layer under `sections/` against the verified canonical Part015 `pages/` records and the direct rendered-source structure.

## Inventory gate

- assembled Part015 files — **5/5**
- assembled section range — **83–87**
- represented physical scans — **421–450 / 30**
- canonical Part015 page records represented — **30/30**
- omitted canonical Part015 pages — **0**
- duplicate canonical Part015 pages — **0**
- every Part015 assembled section status — **verified**
- frozen Parts001–014 assembled files modified — **0**
- Part016 literary/canonical body introduced — **0**

Part015 section inventory:

1. `sections/83-oru-pennin-piraayachchiththam.md` — scans421–426 — chapter68 `ஒரு பெண்ணின் பிராயச்சித்தம்!`;
2. `sections/84-manaththai-maatriya-madal.md` — scans427–432 — chapter69 `மனத்தை மாற்றிய மடல்!`;
3. `sections/85-thottaththil-ketta-oli.md` — scans433–437 — chapter70 `தோட்டத்தில் கேட்ட ஒலி!`;
4. `sections/86-inbam-imaippozhuthu.md` — scans438–446 — chapter71 `இன்பம், இமைப்பொழுது!`; scan439 illustration-only;
5. `sections/87-pagaivar-kaiyil-panangamam.md` — scans447–450 — chapter72 `பகைவர் கையில் பனங்காமம்!`; scan448 illustration-only; chapter continues into Part016.

## Canonical-text comparison

For each assembled section, YAML metadata and non-rendering provenance comments were excluded from the literary-body comparison. The remaining assembled literary payload was compared against the concatenated live canonical `## Source transcription` blocks in scan order. Chapter number/title and declared scan range were verified separately.

| Section | Scan range | Canonical literary payload |
|---|---:|---|
| section83 — `ஒரு பெண்ணின் பிராயச்சித்தம்!` | 421–426 | **EXACT / PASS** |
| section84 — `மனத்தை மாற்றிய மடல்!` | 427–432 | **EXACT / PASS** |
| section85 — `தோட்டத்தில் கேட்ட ஒலி!` | 433–437 | **EXACT / PASS** |
| section86 — `இன்பம், இமைப்பொழுது!` | 438–446 | **EXACT / PASS** |
| section87 — `பகைவர் கையில் பனங்காமம்!` | 447–450 | **EXACT / PASS** |

All **30/30** canonical Part015 records are represented exactly once in source order across sections83–87.

- unsupported Tamil body insertion — **0**
- audit/review/workflow-note leakage into visible literary body — **0**
- unsupported spelling/punctuation/semantic normalization — **0**

## Illustration-only gate

- scan439 — **full-page colour narrative illustration / no printed Tamil body / no visible folio**
- scan448 — **full-page colour battle illustration / no printed Tamil body / no visible folio**
- assembled literary body invented for scan439 — **0**
- assembled literary body invented for scan448 — **0**
- illustration provenance is retained only through non-rendering comments at the physical boundaries — **PASS**

## Structural / provenance gate

Source-visible chapter order is retained:

- scans421–426 — chapter68;
- scans427–432 — chapter69;
- scans433–437 — chapter70;
- scans438–446 — chapter71;
- scans447–450 — chapter72 Part015 segment.

Chapter labels/titles and `source_scans` metadata for sections83–87 were checked and all five are **PASS**.

Cross-page source fragments remain in canonical order; physical page boundaries are represented only by non-rendering comments and do not alter literary wording.

## Boundary gates

Incoming:
- **420→421 — CLEAN CHAPTER BOUNDARY / AUDITED / PASS**
- frozen Part014 body imported into Part015 assembly — **0**
- section83 begins with displayed chapter68 at scan421

Outgoing:
- **450→451 — CLEAN CONTINUATION / AUDITED / PASS**
- scan450 ends on a complete departure sentence inside chapter72
- scan451 begins a fresh paragraph in the same chapter72
- Part016 literary text imported into section87 — **0**
- section87 ends exactly at verified scan450

## Canonical-integrity gate

Assembly remains a derived reading layer only.

- canonical Part015 `pages/` mutations caused by validation — **0**
- canonical Tamil wording corrections during validation — **0**
- canonical status/visual-fidelity changes during validation — **0**
- page-map authority changes during validation — **0**
- frozen Parts001–014 body mutations — **0**
- Part016 canonical records created — **0**

## Assembly provenance

- construction commit — `18b2305a710fbda8019741de29b38c1bffb545e1`
- assembled files validated — **5/5**

## Decision

**ASSEMBLED TAMIL MASTER — PASS / VERIFIED / CLOSED**

Final audit targets:
- omissions — **0**
- duplicates — **0**
- unsupported Tamil body insertion — **0**
- workflow-note leakage — **0**
- canonical Part015 mutations — **0**
- frozen prior-Part mutations — **0**
- Part016 body leakage — **0**
- unresolved assembly blockers — **0**

## Exact next gate

Begin **Part015 English translation planning/setup**.

Perform a live English batch-number/source-check and maintained-English section collision check before reserving the Part015 sequence. Create planning/glossary/progress controls only; do not draft English literary prose in the setup gate. Do not begin Part016 Pass1.
