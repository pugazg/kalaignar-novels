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
- historical-glyph coverage on existing canonical scans: **PASS scans 1–111**;
- retrospective historical-glyph re-audit: **PASS scans 1–101 / COMPLETE**;
- corrective historical-glyph re-audit: **PASS scans 102–111**;
- forward transcription at scan 112: **UNBLOCKED / NEXT**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**.

## Critical historical-glyph rule

Mandatory set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from enlarged/native source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms after decoding the character identity. Never global-replace.

Corrective scans 102–111 remain controlling for the known failure mode, including `நன்றாகக்`, `தவறாக`, `என்றாள்`, missing-`ஆ` corrections, `சொன்னா`, and `பெண்ணா?`. Nearby forms must always be independently source-checked.

## Retrospective batches completed

- **1–5:** PASS; scan 4 ordinary source correction `பெருகிடுகிறது` → `பெருகிவிடுகிறது`.
- **6–10:** PASS; no canonical correction; preserve `அய் யோன்னு`, `குழப்பட்டு`.
- **11–15:** PASS; no canonical correction.
- **16–20:** PASS; no canonical correction; `வேலையில்ல`, `வந்துவிட்டானு` are genuine source forms.
- **21–25:** PASS; no canonical correction; `வரணும்`, `வயதினள்` retained from source pixels.
- **26–30:** PASS; no canonical correction; `காணோமே` confirms `ணோ`; `பெண்ணொருத்தி` confirms `ணொ`.
- **31–35:** PASS; no canonical correction; `அவ்விதமானாள்`, `நட்டுவனார்`, recurring `நயினா` confirmed.
- **36–40:** PASS after scan 38 `கண்ணின் மிகுதியால்` → `களைப்பின் மிகுதியால்`; scan 40 `எண்ணையாவது` → `என்னையாவது`, `அவர்களோ` → `அவர்களை`, `கைவற்றுப்போனேன்` → `கைவற்றுப்போனான்`.
- **41–45:** PASS; no historical-family substitution; scan 42 ordinary corrections `பொறுத்துச்` → `பொருத்தம்`, `சுதன` → `சனதன`.
- **46–50:** PASS; corrections include scan 46 `வேஷம் கலைந்துவிட்டதம்மா`, `தப்பி விட்டோம்`, `தடை போட்டார்களே`, `நெருப்பு மொழிகளும்`, `அசைவற்றுப் போனார்`; scan 47 `மானத்தைப்பற்றியே கவலைப்படாத`, `அளிப்பதாக`; scan 48 `அகரமம்`; scan 49 `மாசமறுவற்ற`; scan 50 no correction.
- **51–55:** PASS; scan 52 `குபு குபு`, `அவங்களுக்கே தான்`, `பாலையூர்`, `பாலையூர் மருத்துவ மனையில்`; scan 54 `விரும்பினன்`, `இந்த மன தத்துவத்தை`; scan 55 `மருத்துவ மனையிலிருந்து`; scans 51 and 53 no correction.
- **56–60:** PASS; scan 56 `எடுத்துக் காட்டும்`, `பொறுத்துக் கொள்ள`; scan 57 `நிலநாட்டும்`; scan 58 `மருத்துவ மனையில்`, `இந்த சொல்மட்டும்`; scan 59 no correction; scan 60 `அருகிலே இருந்தது`.
- **61–65:** PASS; no canonical correction; genuine source counterexamples include scan 62 `பொய்தானு`, `பேசினன்` and scan 63 `நோக்கினன்`.
- **66–70:** PASS; no historical-family substitution. Scan 66 visibly prints only page `5`; scan 67 `பிறர் கெடுவதையே`; scan 68 quoted `பாலையூர் மருத்துவ மனையில்`, `பணி புரியலாமென்று`, `தொலையமாட்டார்களா என்றும்`; scan 69 `விடக் கூடாதம்மா`; scan 70 `இருப்பது கூட`, `நயினாவிடம் கூட சொல்லிவிடலாமே`, `அவன் சற்று அழுத்தந்திருத்தமாகவே`.
- **71–75:** PASS; no canonical correction; scan 75 is the mixed Chapter 8 / 9 boundary with centered `9`.
- **76–80:** PASS; no historical-family substitution. Scans 76–78 no correction; scan 79 `தனியிலே` → **`தலையிலே`**; scan 80 `கற்பமாக` → **`கர்ப்பமாக`**.
- **81–85:** PASS with five source-supported corrections: scan 81 `கண்ணி கழியாத` → **`கன்னி கழியாத`**; scan 82 `பின்னர்ப் பிறிட்டு` → **`பின்னர் பீறிட்டு`**; scan 83 `திருமணம்?` → **`திருமணமா?`** (`ணா`); scan 84 `துணியமுடியுமா?` → **`துணிய முடியுமா?`**; scan 85 `மருத்துவ மனைின்` → **`மருத்துவ மனையின்`** (`னை`). Scan 82 bottom standalone `6` remains a printer/signature mark; scan 85 is the mixed Chapter 9 / 10 boundary with centered `10`.
- **86–90:** PASS. Scan 86 ordinary source corrections `அனேகமாக` → **`அநேகமாக`**, `முடிபுமுற்றுவிட்டது` → **`முடிவு முற்றுவிட்டது`**, `பூர்த்திசெய்து` → **`பூர்த்தி செய்து`**. Scan 87 corrected `கேட்டதுபோல்` → **`கேட்டதுபோல`** and mandatory historical-family `மாறுக` → **`மாறாக`** (`றா`). Scans 88–90 required no canonical correction. Scan 88 `நானு` remains exact; scan 89 ends `மறுத்துவிட்`; scan 90 begins `டால்`; scan 90 `மாறினள்` and `கத்தினள்` remain source-exact.
- **91–95:** PASS. Scan 91 corrected mandatory-family `கருதினலும்` → **`கருதினாலும்`** (`னா`) and source spacing `உதவிபுரிவதுபோல` → **`உதவி புரிவதுபோல`**. Scans 92–95 required no canonical correction. Preserve scan 92 `நீட்டினன்`, `துரிதப்படுத்தினன்`, `அமர்த்தினன்` and centered Chapter `11`; scan 93 `பொத்தினன்`; scan 94 `தொடங்கினார்`, `புறக்கப்போகிறேன்`; scan 95 `தொடங்கினள்`, `பயந்தோடிக்`, `முக்கிய வாசிக் கதை`.
- **96–100:** PASS. Scans 96, 97, and 100 required no canonical correction. Scan 98 corrected mandatory-family `நன்றுக` → **`நன்றாக`** (`றா`). Scan 99 corrected both `நன்றுகத்` occurrences → **`நன்றாகத்`** (`றா`). Preserve scan 96 `வெளித்தாவரத்திலே`, `கிடத்தினன்`; scan 97 `இந்நிலே காதலிக்கும் உண்டு`; scan 98 `பனிரெண்டு`, `கட்டிலண்டை` and bottom `7` printer/signature mark; scan 99 `கொண்டதானது`, `ஓசைகேட்கவே` and centered Chapter `12`; scan 100 `நடன மாடுகிறது`, `லஸ்தர் விளக்கு`.
- **101:** **PASS / RETROSPECTIVE CLOSURE.** No mandatory-family correction. Ordinary source spacing `கண்விழித்துப்` → **`கண் விழித்துப்`**. Representative source-confirmed identities include `காட்டுகிறார்களே` (`றா`), `பெண்ணாகவே` (`ணா`), `கண்களை` (`ளை`), recurring `நயினா` / `வைத்துக்கொண்டிருந்தான்` (`னா`), and `தேவையில்லையென்று` (`லை`). Preserve `வேலைகூடத்`, `முகக் கண்களை`, `சீசாமீது`, `கொப்பளித்துக்கிளம்பி`, `நாழிகைக்குப்`.

## Historical-glyph closure

Retrospective scans **1–101 are complete / PASS**. Together with the already completed corrective scans **102–111**, all existing canonical scans **1–111** now have direct source-pixel historical-glyph coverage. This closes the retrospective hold and unblocks forward transcription. The same 13-family source-pixel check remains mandatory for every new forward scan.

## Preserve these structural/source decisions

- recurring name **`நயினா`**, not `நயினு`;
- scan 23 `வயதினள்` genuine;
- scan 27 `காணோமே` = `ணோ`;
- scan 30 `பெண்ணொருத்தி` = `ணொ`;
- scan 31 `அவ்விதமானாள்` genuine;
- scan 33 `நட்டுவனார்` source-supported; mixed Chapter 3 / 4 with centered `4`;
- scan 38 `களைப்பின் மிகுதியால்`;
- scan 40 `என்னையாவது`, `அவர்களை`, `கைவற்றுப்போனான்`;
- scan 42 `பொருத்தம் சரியில்லை`, `சனதன உள்ளம்`;
- scan 45 mixed Chapter 4 / 5 with centered `5`;
- scan 52 Chapter 6 opening with centered `6`; source `பாலையூர்`;
- scan 53 `பருவத்தினள்` genuine;
- scan 54 `விரும்பினன்`, `இந்த மன தத்துவத்தை`;
- scan 55 `மருத்துவ மனையிலிருந்து`, `வேறுயிற்றே`, `பேசினர்கள்`;
- scan 56 `எடுத்துக் காட்டும்`, `பொறுத்துக் கொள்ள`;
- scan 57 `நிலநாட்டும்`;
- scan 58 `மருத்துவ மனையில்`, `இந்த சொல்மட்டும்`;
- scan 59 mixed Chapter 6 / 7 with centered `7`;
- scan 60 `அருகிலே இருந்தது`;
- scan 62 `பொய்தானு`, `பேசினன்` genuine;
- scan 63 `நோக்கினன்` genuine;
- scan 66 visible page `5`, never infer `65`;
- scan 68 mixed Chapter 7 / 8 with centered `8`;
- scan 75 mixed Chapter 8 / 9 with centered `9`;
- scan 79 `மானேந்தி மழுவேந்தி தலையிலே கங்கையேந்திப்...`;
- scan 80 `நீ கல்யாணத்துக்குள் கர்ப்பமாக வேண்டுமென்று...`;
- scan 82 bottom standalone `6` printer/signature mark;
- scan 83 `திருமணமா?` source-confirmed `ணா`;
- scan 85 mixed Chapter 9 / 10 with centered `10`; `மருத்துவ மனையின்`;
- scan 86 `அநேகமாக முடிவு முற்றுவிட்டது`, `பூர்த்தி செய்து`;
- scan 87 `கேட்டதுபோல`, `மாறாக` (`றா`);
- scan 88 `நானு` genuine source form;
- scan 89 ends physical `மறுத்துவிட்`; scan 90 begins `டால்`;
- scan 90 `மாறினள்`, `கத்தினள்` remain source-exact;
- scan 91 `கருதினாலும்` (`னா`), `உதவி புரிவதுபோல`;
- scan 92 mixed Chapter 10 / 11 with centered `11`; `நீட்டினன்`, `துரிதப்படுத்தினன்`, `அமர்த்தினன்` genuine;
- scan 93 `பொத்தினன்` genuine;
- scan 94 `புறக்கப்போகிறேன்` preserved;
- scan 95 `தொடங்கினள்`, `பயந்தோடிக்`, `முக்கிய வாசிக் கதை` preserved;
- scan 98 `நன்றாக` (`றா`); bottom standalone `7` printer/signature mark;
- scan 99 both `நன்றாகத்` (`றா`); mixed Chapter 11 / 12 with centered `12`;
- scan 101 `கண் விழித்துப்`; ends `சிறிது நாழிகைக்குப் பிறகு ஆனந்தி`, continued on scan 102;
- scan 107 mixed Chapter 12 / 13 with centered `13`;
- scan 111 ends physical `சிறிதா`; scan 112 begins `வது`.

## Exact next activity

Forward transcription may now resume.

1. re-fetch live `main`;
2. resolve the controlling PDF;
3. resume forward canonical processing at **scan 112**;
4. preserve the scan-111/112 physical continuation `சிறிதா` + `வது`;
5. apply the mandatory 13-family historical-glyph check directly from source pixels on every newly transcribed scan;
6. preserve source spelling, punctuation, spacing, colloquial forms, and page/chapter boundaries;
7. synchronize page records, page-map, audit, README/status/handover documents and commit.

Do not start assembled Tamil or English.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.