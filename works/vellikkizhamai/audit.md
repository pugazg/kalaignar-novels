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
| User-directed second historical-glyph re-audit | **IN PROGRESS — scans 119–163 PASS / 45 of 61** |
| Second re-audit corrections | **2 through scan 163** |
| Second re-audit next batch | **164–168 — STARTED** |
| Full Tamil source audit | **blocked pending second glyph re-audit** |
| Assembled Tamil | **not started** |
| English translation | **blocked until Tamil gate passes** |

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
- Remaining second-pass scans: **164–179**.

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

## Batch 10 — scans 164–168 — STARTED

Canonical comparison records for scans 164–168 have been loaded. Known boundaries are preserved. Direct-source confirmation remains required before closure for scan 164 `நயினாவில்`, scan 164 `என் சார்?`, and scan 165 `அவனது சவம்`; these are only locators for review and must not be grammar-corrected without source evidence.

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

`119–123 ✓ → 124–128 ✓ → 129–133 ✓ → 134–138 ✓ → 139–143 ✓ → 144–148 ✓ → 149–153 ✓ → 154–158 ✓ → 159–163 ✓ → 164–168 → 169–173 → 174–178 → 179`

## Exact next activity

Continue the started second-pass audit for **scans 164–168** only. Preserve scan 164 / 165 `கத்தி` + `னான்.` = `கத்தினான்.`, scan 165 / 166 `அதற்குள்` → `யாரோ அந்த வேலையைச் செய்து முடித்துவிட்டார்கள்!`, centered `22` on scan 166, the scan 166 / 167 physical em-dash, and scan 167 / 168 `போய்ச் சேர்ந்து` + `விடவேண்டுமென்ற`. Resolve scan 164 `நயினாவில்`, scan 164 `என் சார்?`, and scan 165 `அவனது சவம்` from direct source before closure. Do not start assembled Tamil or English.
