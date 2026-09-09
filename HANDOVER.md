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
- canonical records **163 / 179**;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 19 opens: **scan 149 / printed 148**, centered `19`;
- Chapter 20 opens: **scan 154 / printed 153**, centered `20`;
- Chapter 21 opens: **scan 160 / printed 159**, centered `21`;
- Chapter 21 transcribed through **scan 163 / printed 162**;
- historical-glyph coverage: **PASS scans 1–163**;
- next forward iteration: **scans 164–168**;
- batch size: **5 scans**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace.

The expanded corrective re-audit remains controlling. Apparent short-looking old type must be checked against same-edition forms before classification. Independently source-confirmed forms such as `வேலையில்ல`, `வரணும்`, `நானு`, recurring **`நயினா`**, scan 114 `அப்படித்தான் ஆவள்`, and later source-specific clusters remain unchanged.

## Production workflow

For each 5-scan batch:

1. fetch live `main` once;
2. transcribe all five full pages first;
3. run one batch-level mandatory 13-family glyph sweep;
4. allow at most one targeted enlargement for a genuinely unclear token;
5. if still unresolved, record a source hold and continue;
6. create five page records and synchronize audit/page-map/README/HANDOVER/prompt together;
7. make one atomic commit;
8. do not reopen prior PASS scans without new source evidence.

## Recent durable results

- scan 154: Chapter 19 / 20 boundary, centered `20`; targeted enlargement confirms `சோகடிப்புமானான்`; preserve `ஈனசுரத்தில்`, `மலை மலையாக`, `அலை அலையாக`;
- scan 155: preserve `சஞ்சீவி`, `சிபாரிசு`, `அபாக்கியவதி`, `அழுக்கேறிய`, `நிலைமைகண்டு`, `நடந்துகொண்டதாகக்கருதி`, `தீக் காட்டால்`; ends physical `சோலை`;
- scan 156: begins `யில்`, completing `சோலையில்`; preserve `அவ்வளவுங்`, `பண்டமாற்று`, `கன்றிப்போய்விட்டது`, `நயினாமீது`; ends physical `தலையிலும் காயம்`;
- scan 157: begins direct source `நயினா எதிர்த்தே அடிக்கவில்லை.`; old-type `றா` in `ஒன்றாக` confirmed; preserve `அலட்சியச்`, `குற்றவாளிக்கூண்டு`, `ஆக்ரோஷத்தோடு`, `குமுறின`; ends `பயங்கரமாக—`;
- scan 158: begins `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.`; preserve `மாறாக`, `ஸ்தம்பித்து`, `ஆருயிர்த் தோழனிடத்திலே`, `சமயங்கூட`; ends physical `வராத`;
- scan 159: begins `கண்ணீர்,`, completing `வராத கண்ணீர்,`; preserve `உள்ளங்`, `உதயமாயிற்று`, `ஜோடியாக`, `தம்பதிகளாக்குகிறேன்`; ends physical `அழகப்பனுக்கும்`;
- scan 160: begins `ஒன்றும் புரியவில்லை.`; centered `21` opens Chapter 21; one targeted enlargement confirms source-specific `மன்னித்துவிடடா`; preserve `குடிமுழுகிவிடவில்லை`, `இவ்வளவுதூரம்`, `இப்படி யொரு`, `தீயசக்தி`, `காதல்வீடு`; ends physical `நமது தூய நட்பு`;
- scan 161: begins `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது`; historical `றா` in `சூறாவளியை` confirmed; preserve `பழி-பாவம்`, `பிராயச்சித்தம்`, `மனச்சாட்சியைக்`; ends complete question-and-attribution;
- scan 162: preserve `பத்தரைமாற்றுப் பசும்பொன்`, `அஸ்தமித்துப்போகும்`, `அவகாசமெடுத்துக்கொண்டு`, `அறைநோக்கிச்`, `புயலுக்குப்பின்`; bottom `11—A` is a printer/signature mark; ends complete sentence;
- scan 163: preserve `‘குபு குபு’`, `சண்டாளப்பட்டம்`, `முழு நிலவு ஒளியாக்கப்பட்டது போல்`, `மேனித்தின்மீது`, `காரண கர்த்தாவானேன்`, `இருக்கவேண்டாமென்று`; ends complete `கொலைகாரா!”` quote.

No unresolved source holds remain through scan 163.

## Structural/source decisions to preserve

- scan 66 visible printed number only `5`;
- scan 82 bottom `6` printer/signature mark;
- scan 89 / 90 `மறுத்துவிட்` + `டால்`;
- scan 98 bottom `7` printer/signature mark;
- scan 111 / 112 `சிறிதா` + `வது` = `சிறிதாவது`;
- scan 114 bottom `8` printer/signature mark;
- scan 117 / 118 literal `உட்` → `எவ்வளவோ...` source discontinuity;
- scan 119 / 120 `கவனித்து` → `விட்டான்.`;
- scan 122 / 123 literal `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`; no grammatical reconstruction;
- scan 124 / 125 `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127 / 128 `வாழ்` + `விலே` = `வாழ்விலே`;
- scan 129 / 130 `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`;
- scan 130 bottom `9` printer/signature mark;
- scan 131 / 132 `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`;
- scan 134 / 135 `நயினாவின்` → `கேள்வி`;
- scan 135 / 136 `வருத்தத்` + `தோடு` = `வருத்தத்தோடு`;
- scan 137 / 138 `“இதோ,` → `கொண்டுவருகிறேன்”`;
- scan 138 / 139 `‘மளமள’` → `வென்று...`;
- scan 139 / 140 `புயலால் தாக்குண்டவன்போல` → `ஆனேன் அன்று!`;
- scan 140 / 141 `நயினா` → `எதுவும் பேசவில்லை.`;
- scan 142 / 143 `வாசகங்கள்` → `இருந்தன.`;
- scan 144 / 145 `வரவழைத்துக்` + `கொண்டான்` = `வரவழைத்துக் கொண்டான்`;
- scan 145 / 146 `ஏது` → `அவ்வளவு அக்கறை!`;
- scan 146 bottom `10` printer/signature mark;
- scan 146 / 147 `கூறியதுதான்` + `தாமதம்;`;
- scan 147 / 148 `சந்திப்` + `பதற்காக!` = `சந்திப்பதற்காக!`;
- scan 148 ends complete sentence;
- scan 149 opens Chapter 19, centered `19`;
- scan 149 / 150 `புறப்` + `பட்டுவிட்டாயே!` = `புறப்பட்டுவிட்டாயே!`;
- scan 150 / 151 `தேவ` + `லோகத்தில்` = `தேவலோகத்தில்`;
- scan 151 ends completed question `பிடித்து விட்டால்...?`;
- scan 152 / 153 `வழக்கமாக உறங்கும்` → `அறைக்கல்லவா போகிறாள்!`;
- scan 153 ends complete sentence;
- scan 154 opens Chapter 20, centered `20`;
- scan 155 / 156 `சோலை` + `யில்` = `சோலையில்`;
- scan 156 / 157 literal `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`; no grammatical reconstruction;
- scan 157 / 158 `பயங்கரமாக—` → `ஆனந்தியிருக்கும் அறையை நோக்கி நடக்கத் தொடங்கினாள்.`;
- scan 158 / 159 `வராத` + `கண்ணீர்,` = `வராத கண்ணீர்,`;
- scan 159 / 160 `அழகப்பனுக்கும்` → `ஒன்றும் புரியவில்லை.`;
- scan 160 opens Chapter 21, centered `21`;
- scan 160 / 161 `நமது தூய நட்பு` → `ஒரு பெண்ணால் பிரிக்கப்பட்டுவிட்டது...`;
- scan 161 ends complete question-and-attribution;
- scan 162 bottom `11—A` printer/signature mark; ends complete sentence;
- scan 163 ends complete quoted accusation `கொலைகாரா!”`.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling source;
3. process **scans 164–168** in one bounded 5-page iteration;
4. establish scan 164 only from direct source pixels after scan 163's complete `கொலைகாரா!”` ending;
5. run one batch glyph sweep and bounded ambiguity handling;
6. synchronize page records and status documents and commit atomically.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
