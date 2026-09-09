# Transcription / Source Audit — வெள்ளிக்கிழமை

> Detailed second-pass audit history through scan 153 is preserved in [`AUDIT_HISTORY_THROUGH_153.md`](AUDIT_HISTORY_THROUGH_153.md). This file is the current authoritative audit state from batch 154–158 onward.

## Current gate

| Check | Status |
|---|---|
| Source identity / checksum / page count | **complete** |
| Initial scan manifest | **179 / 179 represented** |
| Canonical page records | **179 / 179 — COMPLETE** |
| Body transcription | **through final scan 179 / printed 178** |
| Printed-page map | **directly confirmed through scan 179; scan 66 visibly prints only `5`** |
| Chapter map | **direct through Chapter 23; Chapter 23 opens at scan 172** |
| Forward historical-glyph coverage | **PASS scans 1–179** |
| User-directed second historical-glyph re-audit | **COMPLETE — scans 119–179 PASS / 61 of 61** |
| Second re-audit corrections | **5 total / 0 unresolved** |
| Full Tamil source audit | **PASSED** |
| Assembled Tamil | **IN PROGRESS — Chapter 1 / 23 VERIFIED; scans 4–12** |
| English translation | **blocked until assembled Tamil passes** |

## Full Tamil source audit — PASSED

The complete canonical Tamil page layer was audited after closure of the second historical-glyph re-audit. This is a structural/source-consistency gate over the already source-audited canonical records; it does not silently retranscribe or normalize the work.

### Final page-layer coverage gate

| Check | Result |
|---|---|
| Source identity / checksum | **PASS** — source metadata agrees on filename, SHA-256, 251,126,214 bytes and 179 scans |
| Canonical page-tree coverage | **PASS — 179 / 179**, continuous filenames `0001` through `0179`; page tree is not truncated |
| Canonical completion / unresolved state | **PASS — 179 / 179 COMPLETE; 0 unresolved source holds** |
| Work identity | **PASS — single work `vellikkizhamai`** |
| Printed-page mapping | **PASS** — source-confirmed exceptions retained, especially scan 66 printed `5` and scans 67–179 → printed 66–178 |
| Chapter structure | **PASS — Chapters 1–23**, with final Chapter 23 narrative on scan 179 |
| Historical-glyph gates | **PASS** — forward scans 1–179; second re-audit 119–179 = 61/61 PASS |
| Second-pass corrections | **PASS — 5 source-supported corrections present; 0 unresolved** |
| Cross-page continuity | **PASS** — durable physical joins preserved without grammar-driven reconstruction |
| Printed text vs non-body material | **PASS** — printer/signature marks, scan-179 illustration and later handwriting remain excluded from body text |
| Metadata / README / page-map / audit synchronization | **PASS after audit synchronization** — stale `metadata/source.md` progress state was updated to the completed 179-page state |

### Page metadata / manifest consistency

The live `pages/` Git tree contains exactly the continuous record sequence `0001`–`0179`, beginning with three front-matter records and continuing through the final body/illustration record. Representative live front-matter and body records across the work confirm `work: "vellikkizhamai"`, Tamil language, the controlling source filename, and `status: "verified"`; the completed project state records no remaining `needs-review`, `not-started`, or unresolved source hold. Legacy descriptive filename suffixes are preserved and are not treated as printed-page numbers; `scan_page` / `printed_page` front matter remains authoritative.

### Structural / printed-page audit

The work remains one novel with **23 chapters**. The confirmed printed-page exceptions are preserved: front matter scans 1–3; scan 4 without a printed body-page number; scans 5–8 printed 4–7; scan 9 without a visible printed number; scans 10–65 printed 9–64; scan 66 visibly prints only `5`; scans 67–179 map to printed 66–178. No missing number is silently inferred.

### Source-correction audit

The five second-pass corrections are present in the canonical layer and remain individually source-supported:

1. scan 151 `அங்கே வந்து.` → `அங்கே வந்து,`;
2. scan 163 `மேனித்தின்மீது` → `பிணத்தின் மீது`;
3. scan 164 `நயினாவில்` → `நயினாவால்`;
4. scan 164 `“என் சார்?”` → `“ஏன் சார்?”`;
5. scan 165 `அவனது சவம்` → `அவளது சவம்`.

No additional canonical text change was required by this full Tamil source audit.

### Continuity audit

Durable page-boundary joins recorded in this audit and the page map were checked as structural decisions, not rewritten prose. Important late-work examples include `புகை` + `வண்டி`, `வாழ்` + `விலே`, `அழகப்ப` + `னுடைய`, `பின்னிக்` + `கொண்டன`, `புறப்` + `பட்டுவிட்டாயே!`, `தேவ` + `லோகத்தில்`, `சோலை` + `யில்`, `கத்தி` + `னான்.`, and the deliberately literal scan 156/157 transition `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`. No grammatical reconstruction was introduced.

### Printed text vs copy-specific marks

Printer/signature marks at scans 82 `6`, 98 `7`, 114 `8`, 130 `9`, 146 `10`, and 162 `11—A` remain observations rather than narrative. Scan 179's lower printed illustration and faint later handwritten marks/numbers remain non-body material.

## Canonical Tamil source result

**Transcription coverage: COMPLETE — 179 / 179.**  
**Historical-glyph/source review: COMPLETE.**  
**Page/metadata/manifest consistency audit: PASSED.**  
**Unresolved source readings: 0.**  
**Tamil source layer: PASSED.**

The audited `pages/` records remain the canonical preservation layer. The derived **assembled Tamil reading layer** is now **IN PROGRESS**. Chapter 1 (scans 4–12) has been assembled and verified; English remains blocked until all 23 chapters and the final assembled-layer consistency audit pass.

## Historical-glyph rule

Mandatory family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Character identity is decided from source pixels first; grammar is only a locator. Never global-replace or silently modernize source wording. Recurring source forms and direct colloquial variants are preserved scan by scan.

## Second re-audit coverage

- **119–123:** PASS — 0 corrections / 0 unresolved.
- **124–128:** PASS — 0 corrections / 0 unresolved.
- **129–133:** PASS — 0 corrections / 0 unresolved.
- **134–138:** PASS — 0 corrections / 0 unresolved.
- **139–143:** PASS — 0 corrections / 0 unresolved.
- **144–148:** PASS — 0 corrections / 0 unresolved.
- **149–153:** PASS — 1 correction / 0 unresolved. Scan 151 source punctuation corrected `அங்கே வந்து.` → `அங்கே வந்து,`; historical-glyph corrections 0.
- **154–158:** PASS — 0 corrections / 0 unresolved. Canonical Tamil unchanged.
- **159–163:** PASS — 1 correction / 0 unresolved. User-authorized closure using the existing direct-source forward audit plus the user direct-source correction on scan 163: `மேனித்தின்மீது` → `பிணத்தின் மீது`.
- **164–168:** PASS — 3 corrections / 0 unresolved. User direct-source corrections: `நயினாவில்` → `நயினாவால்`; `என் சார்?` → `ஏன் சார்?`; `அவனது சவம்` → `அவளது சவம்`.
- **169–173:** PASS — 0 corrections / 0 unresolved. User-instructed closure using the existing direct-source forward audit; preserve scan-171 `அங்கிருந்த வாறு`.
- **174–178:** PASS — 0 corrections / 0 unresolved. User-instructed closure using the already-completed direct-source forward audit; canonical Tamil unchanged.
- **179:** PASS — 0 corrections / 0 unresolved. Final `திரும்பினர்கள்.` preserved; lower illustration and faint later handwriting excluded as non-body material.
- Second re-audit final: **COMPLETE — 61/61 scans PASS, 5 total corrections, 0 unresolved**.

## Batch 8 — scans 154–158

Method: each physical scan was independently re-read from the rendered controlling-source pixels against all 13 mandatory families, with the canonical page record used only as the comparison target. Source pixels controlled; no grammar-based repair, global replacement, or silent normalization was used.

### Scan 154 / printed 153

**SECOND-PASS PASS — 0 corrections / 0 unresolved.** Chapter 19 text directly precedes centered `20`, which opens Chapter 20 mid-scan. Source reconfirms `நயினாவுக்குக்`, `நயினா`, `என்னை`, `உன்னை`, `அவனை`, and `தழுதழுத்த`; source-specific `சோகடிப்புமானான்` and `ஈனசுரத்தில்` remain unchanged.

### Scan 155 / printed 154

**SECOND-PASS PASS — 0 corrections / 0 unresolved.** Source reconfirms `நீயாக`, `என்னை`, `நானும்`, `நல்லவள்`, `நடந்துகொண்டதாகக்கருதி`, and `தீக் காட்டால்`. Physical end `சோலை` remains correct.

### Scan 156 / printed 155

**SECOND-PASS PASS — 0 corrections / 0 unresolved.** Physical beginning `யில்` completes scan 155 `சோலை` as `சோலையில்`. Source reconfirms recurring `நயினா`, `விட்டானா`, `நின்றான்`, `தாங்கிக்கொள்ள`, `நயினாமீது`, and `கன்றிப்போய்விட்டது`. Physical end remains literal `தலையிலும் காயம்` with no supplied punctuation.

### Scan 157 / printed 156

**SECOND-PASS PASS — 0 corrections / 0 unresolved.** Physical beginning is direct source `நயினா எதிர்த்தே அடிக்கவில்லை.` after scan 156's literal end; no missing grammar or punctuation is reconstructed. Source reconfirms recurring `நயினா`, `ஒன்றாக`, `குற்றவாளிக்கூண்டு`, `ஆக்ரோஷத்தோடு`, and `குமுறின`. Physical end `பயங்கரமாக—` remains correct.

### Scan 158 / printed 157

**SECOND-PASS PASS — 0 corrections / 0 unresolved.** Physical beginning `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.` continues scan 157's `பயங்கரமாக—`. Source reconfirms `நயினா`, `மாறாக`, `தள்ளாடியபடியே`, `நாற்காலியில்`, and `சமயங்கூட`. Physical end `வராத` remains correct; scan 159 continues `கண்ணீர்,`.

**Batch verdict: PASS — 5/5 scans, 0 corrections, 0 unresolved. Canonical Tamil unchanged; cumulative second-pass corrections remain 1.**

## Batch 9 — scans 159–163

Closure basis: the user explicitly instructed that this batch be closed. The five canonical records already had completed direct-source forward audits; during this second-pass review the user directly corrected scan 163. This closure is therefore recorded as a user-authorized second-pass closure and is **not** described as a fresh independent pixel re-read of every scan.

- scan 159 / printed 158: begins `கண்ணீர்,`, completing scan 158 `வராத`; ends `அழகப்பனுக்கும்`;
- scan 160 / printed 159: begins `ஒன்றும் புரியவில்லை.`; centered `21`; ends `நமது தூய நட்பு`; earlier targeted source review preserves `மன்னித்துவிடடா`;
- scan 161 / printed 160: begins `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது`; complete ending;
- scan 162 / printed 161: bottom `11—A` is a printer/signature mark, not body text; complete ending;
- scan 163 / printed 162: direct-source correction `ஆனந்தியின் மேனித்தின்மீது` → `ஆனந்தியின் பிணத்தின் மீது`; ends `கொலைகாரா!”`.

**Batch verdict: PASS — 5/5 scans, 1 correction, 0 unresolved. Cumulative second-pass corrections: 2.**

## Batch 10 — scans 164–168

Closure basis: all five canonical records had completed direct-source forward audits; during this second-pass review the user directly confirmed the three suspicious source readings.

- scan 164 / printed 163: corrected `நயினாவில்` → `நயினாவால்` and `“என் சார்?”` → `“ஏன் சார்?”`; physical end `கத்தி`;
- scan 165 / printed 164: begins `னான்.` completing `கத்தினான்.`; corrected `அவனது சவம்` → `அவளது சவம்`; physical end `அதற்குள்`;
- scan 166 / printed 165: begins `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`; centered `22`; physical em-dash ending preserved;
- scan 167 / printed 166: direct continuation after the em-dash preserved; physical end `போய்ச் சேர்ந்து`;
- scan 168 / printed 167: begins `விடவேண்டுமென்ற`; complete ending.

**Batch verdict: PASS — 5/5 scans, 3 corrections, 0 unresolved. Cumulative second-pass corrections: 5.**

## Batch 11 — scans 169–173

Closure basis: user instructed continuation using the existing direct-source forward audit. **Batch verdict: PASS — 5/5 scans, 0 corrections, 0 unresolved.** Preserve scan-171 `அங்கிருந்த வாறு` exactly as recorded; no silent normalization was introduced.

## Batch 12 — scans 174–178

Closure basis: the five canonical records already had completed direct-source forward audits, and the user instructed continuation. No new suspicious reading remained after reviewing the recorded source decisions.

- scan 174 / printed 173: begins `எழுந்த குமுறல்கள்!...`; preserves `பாழ்வன மாக்கிவிட்டார்` and `நயினு முகம்மதும்`; ends `உண்மையான பாலகங்காதரத் தேவரை`;
- scan 175 / printed 174: begins `சிக்கவைக்கவேண்டுமென்றும்,`; preserves `வந்து இறங்கினர்`; ends `போலீசார் அவரைச் சூழ்ந்து`;
- scan 176 / printed 175: begins `கொண்டார்கள்.`; preserves `விளக்கினன்` and unusual `வருந்தி வருந்தி`; complete ending;
- scan 177 / printed 176: preserves `அள்ளி வீசினன்`, `நயினுவிடம்`, `நயினுவுக்கோ`, `நயினுவும்`; complete ending;
- scan 178 / printed 177: preserves `இழுமூச்சைத்தாள்`, `நயினுவும்`, and closing `புள்ளி மயில்`; complete ending.

**Batch verdict: PASS — 5/5 scans, 0 corrections, 0 unresolved. Cumulative second-pass corrections remain 5.**

## Final iteration — scan 179

Closure basis: canonical scan 179 already had a completed direct-source forward audit and was loaded for this final iteration. No conflicting source evidence or unresolved reading remained.

- final narrative remains `வெள்ளிக்கிழமையிலே பெண் வீடு பார்க்க வந்த நண்பர்கள் இருவரும்......தங்கள் வாழ்க்கை ஏட்டிலே அழியாத இடம் பெற்றுவிட்ட இரண்டு பெண்மணிகளையும் நினைத்து நினைத்து நெஞ்சு நெகிழ்ந்தவாறு பெங்களூர் திரும்பினர்கள்.`;
- source-specific closing `திரும்பினர்கள்.` is preserved exactly;
- lower printed illustration is non-body visual material;
- faint later handwritten marks/numbers are non-body annotations and remain excluded from canonical body text.

**Final iteration verdict: PASS — 1/1 scan, 0 corrections, 0 unresolved. Second historical-glyph re-audit COMPLETE — 61/61 scans PASS, 5 cumulative corrections, 0 unresolved.**

## Structural/source decisions to preserve

- scan 66 visibly prints only `5`; never infer `65`;
- printer/signature marks: scans 82 `6`, 98 `7`, 114 `8`, 130 `9`, 146 `10`, 162 `11—A`;
- scan 149 / 150 `புறப்` + `பட்டுவிட்டாயே!`;
- scan 150 / 151 `தேவ` + `லோகத்தில்`;
- scan 151 source punctuation: `அங்கே வந்து,`;
- scan 152 / 153 `வழக்கமாக உறங்கும்` → `அறைக்கல்லவா போகிறாள்!`;
- scan 155 / 156 `சோலை` + `யில்` = `சோலையில்`;
- scan 156 / 157 literal `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`; no reconstruction;
- scan 157 / 158 `பயங்கரமாக—` → `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.`;
- scan 158 / 159 `வராத` + `கண்ணீர்,`;
- scan 159 / 160 `அழகப்பனுக்கும்` → `ஒன்றும் புரியவில்லை.`;
- scan 160 / 161 `நமது தூய நட்பு` → `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது...`;
- scan 163 source correction: `மேனித்தின்மீது` → `பிணத்தின் மீது`; do not restore former reading;
- scan 164 / 165 `கத்தி` + `னான்.` = `கத்தினான்.`;
- scan 165 / 166 `அதற்குள்` → direct source continuation;
- scan 166 / 167 physical em-dash → direct source continuation;
- scan 167 / 168 `போய்ச் சேர்ந்து` → direct source continuation;
- scan 169 / 170 `ஒலி வந்த திக்கையே நோக்கியவாறு` → direct source continuation;
- scan 170 / 171 `“எஜமான்!....இடும்பன்...”` → `என்றான்.`;
- scan 171 / 172 `வம்புச் சண்டையெல்லாம்` + `நடந்தது.`;
- scan 173 / 174 `அவள் நெஞ்சிலே` → direct source continuation;
- scan 174 / 175 `உண்மையான பாலகங்காதரத் தேவரை` → direct source continuation;
- scan 175 / 176 `போலீசார் அவரைச் சூழ்ந்து` → `கொண்டார்கள்.`;
- scan 179 lower illustration and faint handwriting are non-body material.

## Second re-audit sequence

`119–123 ✓ → 124–128 ✓ → 129–133 ✓ → 134–138 ✓ → 139–143 ✓ → 144–148 ✓ → 149–153 ✓ → 154–158 ✓ → 159–163 ✓ → 164–168 ✓ → 169–173 ✓ → 174–178 ✓ → 179 ✓`

## Assembled Tamil audit — Chapter 1

**Chapter 1 / scans 4–12: VERIFIED.**

Checks completed:

- source-chapter boundary: PASS — scan 4 opens Chapter 1; scan 12 completes it; scan 13 opens Chapter 2;
- canonical derivation: PASS — reading prose derived only from verified `pages/` records;
- source wording/punctuation: PASS — no modernization or grammar repair introduced;
- verse structure: PASS — source-printed Tiruppavai lines preserved;
- non-body material exclusion: PASS — historical-glyph/audit notes and scan observations excluded from reading prose;
- provenance: PASS — scan/printed-page comments retained and joins are reversible;
- verified joins: PASS — 4→5 `ஏதோ`/`இன்பக்கனவுகளோ`, 5→6 `அவைகளே`/`கேலிக்குரியதாக`, 8→9 `கிழக்கு வானம் வெளுக்கத்`/`துவங்கிவிட்டது.`, 10→11 `இருந்தாள்—`/quoted continuation;
- canonical mutation: PASS — no `pages/` file changed.

Whole assembled layer status remains **IN PROGRESS — 1 / 23 chapters**.

## Exact next activity

Assemble and verify **Chapter 2 only — scans 13–22** as `sections/02-chapter-02.md`. Then advance the assembly audit to **2 / 23**. Do not begin Chapter 3 or English in the same iteration.
