# Part 012 — Assembled Tamil Validation

Work: `பாயும்புலி பண்டாரக வன்னியன்`  
Repository: `pugazg/kalaignar-novels`  
Branch: `main`

## Result

**PART012 ASSEMBLED TAMIL — COMPLETE / PASS / CLOSED**

This validation audits the readable Part012 Tamil layer under `sections/` against the verified canonical Part012 `pages/` records.

Tamil literary prose was assembled from verified canonical Part012 `## Source transcription` blocks. Verified source-visible chapter numbers/titles were carried from the canonical structural record.

## Inventory gate

- newly assembled Part012 files — **6/6**
- represented physical scans — **331–360 / 30**
- canonical Part012 page records represented — **30/30**
- omitted canonical Part012 pages — **0**
- duplicate canonical Part012 pages — **0**
- every new Part012 assembled section status — **verified**
- frozen Parts001–011 assembled files modified — **0**
- Part013 assembled/canonical body introduced — **0**

Part012 section inventory:

1. `sections/67-mayangukiraal-oru-maadhu-part012.md` — scans331–335 — chapter52 continuation/close `மயங்குகிறாள் ஒரு மாது!`;
2. `sections/68-matroru-madurai.md` — scans336–341 — chapter53 `மற்றொரு மதுரை?`;
3. `sections/69-aval-kanda-sorgam.md` — scans342–346 — chapter54 `அவள் கண்ட சொர்க்கம்!`;
4. `sections/70-veerargal-saavathillai.md` — scans347–351 — chapter55 `வீரர்கள் சாவதில்லை!`;
5. `sections/71-kozhumbil-kondattam.md` — scans352–355 — chapter56 `கொழும்பில் கொண்டாட்டம்!`;
6. `sections/72-thappiththu-vandha-vidham.md` — scans356–360 — chapter57 `தப்பித்து வந்த விதம்!`, continuing beyond Part012.

## Canonical-text comparison

Post-construction regeneration checks rebuilt all six assembled files from the live canonical Part012 page inputs and compared them byte-for-byte with the maintained assembled files.

| Section | Canonical comparison |
|---|---|
| chapter52 continuation/close, scans331–335 | **EXACT / PASS** |
| `மற்றொரு மதுரை?`, scans336–341 | **EXACT / PASS** |
| `அவள் கண்ட சொர்க்கம்!`, scans342–346 | **EXACT / PASS** |
| `வீரர்கள் சாவதில்லை!`, scans347–351 | **EXACT / PASS** |
| `கொழும்பில் கொண்டாட்டம்!`, scans352–355 | **EXACT / PASS** |
| `தப்பித்து வந்த விதம்!`, scans356–360 | **EXACT TAMIL BODY / PASS** |

All **30/30** canonical Part012 page records are represented exactly once in source order across the six assembled files.

Audit/review/workflow-note leakage into literary body — **0**.  
Unsupported Tamil body insertion — **0**.

## Structural / provenance gate

Source-visible order is retained:

- scans331–335 continue and close chapter52;
- scans336–341 carry chapter53;
- scans342–346 carry chapter54;
- scans347–351 carry chapter55;
- scans352–355 carry chapter56;
- scans356–360 begin chapter57 and stop at the Part012 boundary.

Special cases:
- scans335, 341 and 360 preserve no invented content for intentional blank lower fields;
- scan339→340 preserves the physical split `மான அடி வாங்கி` + `யிருந்த`;
- scan342→343 preserves `முடிய` + `மென்றால்`;
- scan345→346 preserves `பின்னி` + `விரித்தாள்!`;
- scan352→353 preserves `ஒரு தமிழ்` + `நாட்டு மாவீரனின்`;
- scan357→358 preserves `அந்த ஒருவன்` + `மட்டும் பல்லைக் காட்டி`;
- scan358→359 preserves `மற்ற` + `மூவரும்`;
- scan359→360 preserves the physical split `சொல்லு` + `கிறான்.`;
- scan355 stops at the directly visible source text through `பண்டாரகனின் மாளிகையை`; footer-obscured wording is not reconstructed.

## Boundary gates

Incoming:
- **330→331 = GENUINE CONTINUATION / AUDITED / PASS**;
- frozen Part011 body imported into Part012 assembly — **0**;
- frozen Part011 assembled files modified — **0**;
- Part012 continuation is carried only by new Part012-owned `67-mayangukiraal-oru-maadhu-part012.md`;
- frozen `sections/66-mayangukiraal-oru-maadhu.md` was not modified.

Outgoing:
- **360→361 = PENDING direct audit**;
- Part013 body imported into Part012 assembly — **0**;
- unsupported completion from scan361 — **0**;
- `72-thappiththu-vandha-vidham.md` terminates at verified scan360 and records the pending boundary only as provenance.

## Canonical-integrity gate

Assembly is a derived reading layer only.

- canonical Part012 `pages/` mutations caused by assembly — **0**
- Tamil wording corrections during assembly — **0**
- punctuation corrections during assembly — **0**
- page-map authority changes caused by assembly — **0**
- canonical status changes caused by assembly — **0**
- frozen Parts001–011 assembled-file mutations — **0**
- Part013 body leakage — **0**

Canonical Part012 `pages/` remain authoritative for any future discrepancy.

## Assembly commits

- `0741f0e36c68fac66876c6ce4c5df4011538f13d` — section67
- `ac84d0429b812ebc09ad88daf60193b929a742b4` — section68
- `253ff1823716bdc56010054d6db4d929b4d4bc68` — section69
- `9e6aafcbeba27332e98d58a0fae04c7892a9b3df` — section70
- `44d96f1c4d965d0a2adece4558fbea478aa08e52` — section71
- `bcac9d4bf0d1a553265458c5313e8a8de273e29a` — section72

## Decision

**ASSEMBLED TAMIL MASTER — PASS / VERIFIED**

Part012 assembled Tamil is now **PASS / CLOSED — 6/6 VERIFIED**.

Final audit targets:
- omissions — **0**
- duplicates — **0**
- unsupported Tamil body insertion — **0**
- audit-note leakage — **0**
- canonical Part012 page mutations — **0**
- frozen prior-section mutations — **0**
- Part013 body leakage — **0**
- unresolved assembly blockers — **0**

## Exact next gate

Begin **Part012 English translation planning/setup**.

Perform a live English batch-number/source-check and maintained-English section collision check before reserving the Part012 sequence. Create planning/glossary/progress controls only; do not draft English prose in the setup gate.

## Part012 English planning/setup checkpoint

**PART012 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS.**

- prior source-check frontier — **E63**
- existing source-check controls — **E1–E63 contiguous / 63**
- reserved Part012 sequence — **E64–E69 / 6**
- maintained English section frontier before setup — **66**
- reserved English section range — **67–72 / 6**
- batch / section collisions — **0 / 0**
- translated / source-checked at setup closure — **0/6 / 0/6**
- English literary prose drafted in setup — **0**
- canonical / assembled Tamil edits — **0 / 0**
- frozen Parts001–011 English body edits — **0**
- incoming **330→331 — GENUINE CONTINUATION / AUDITED / PASS**
- outgoing **360→361 — PENDING direct audit**
- Part013 leakage — **0**
- unresolved planning holds — **0**
- active controls — `translations/en/PART_012_TRANSLATION_PLAN.md`, `PART_012_GLOSSARY.md`, `PART_012_PROGRESS.md`
- exact next gate — **E64 draft + source-check — section67 / scans331–335**
