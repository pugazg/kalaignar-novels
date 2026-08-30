# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Ambiguous / damaged source reading என்றால் baseline-ஐ override செய்யாமல் `needs-review` ஆக வைத்திருக்க வேண்டும். Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

Old/historical Tamil glyphs காரணமாக ஒரு character அல்லது vowel mark source-ல் இல்லாதது போலத் தோன்றினால், correction செய்வதற்கு முன் முழு glyph cluster-ஐ high-resolution-ல் பார்க்க வேண்டும். Faint marks / old typeforms காரணமாக `லை` bare `ல்` போலத் தோன்றலாம் என்பதைக் `புதையல்` retrospective audit நிரூபித்தது. Positive native-pixel evidence இல்லாமல் baseline மாற்றக்கூடாது; global normalization செய்யக்கூடாது.

**Scans 256–259 strengthened rule:** old/faint vowel signs, near-identical same-word glyphs, or apparent spacing created by printed line wrapping require a second independent high-resolution inspection before a baseline difference is accepted. A line break alone is never evidence for word-internal spacing. If one reading in a batch is challenged, reopen every assistant-origin discrepancy in that batch.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **263 canonical records / 256 verified / 7 needs-review; Parts 001–005 part-complete; Part 006 in progress** |

### புதையல் — current source state

Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Access derivatives:

- part 001 — scans **1–49** — part-complete;
- part 002 — scans **50–98** — part-complete;
- part 003 — scans **99–147** — part-complete;
- part 004 — scans **148–196** — part-complete;
- part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**;
- part 006 — scans **246–294 / printed 242–290** — **49-page derivative mapped; scans 246–263 verified; scans 264–294 not-started**.

Current canonical state:

- records — **263**;
- verified — **256**;
- needs-review — **7 (scans 215–219, 223–224)**;
- partial — **0**;
- clean contiguous fully verified range — through **scan 214 / printed page 212**;
- later individual source-verified records — through scan **263**, except the seven explicitly damaged scans;
- Parts 001–005 — full split workflow complete through assembled Tamil, controlled English and bilingual review;
- Part 006 — canonical/native-fidelity work in progress; **18 / 49** pages verified;
- assembled Tamil / English split-level review — still through scan **245** only; Part 006 is not yet eligible for downstream gates;
- whole-work Tamil / English verification — not yet eligible;
- release-readiness — blocked until complete source;
- source PDF / splits committed — No.

The Part-005 endpoint at scan **245 / printed 241** ends `இருக்கவே`. Native scan **246 / printed 242** begins `இருக்கிறாள் பரிமளா, ...`; the source therefore establishes the cross-split continuation `இருக்கவே இருக்கிறாள் பரிமளா, ...` without a derivative-created boundary.

Part 006 source structure is mapped through scan 294: chapter 28 begins at 247, a four-star internal transition occurs at scan 251, chapter 29 begins at 254 and closes at 262, chapter 30 begins at 262, chapter 31 at 271, chapter 32 at 278 and chapter 33 at 288.

A corrected second high-resolution inspection of scans **256–259 / printed 252–255** confirms the user's baseline forms `காட்டுகிறாயா?`, `நன்றாகப் பார்த்தான்`, `அநாவசியமாக`, and `மண்ணாங் கட்டியாவது!`; the earlier assistant alternatives are withdrawn.

Scans **260–263 / printed 256–259** are now verified from Iteration 25. Scan 260 ends `வெள்ளியம்பலம்`; scan 261 closes that sentence and ends `விடிந்த`; scan 262 begins `தும்`, establishing `விடிந்ததும்`, closes chapter 29 and begins chapter 30. Scan 263 then closes `துக்காராமுக்கோ, ஆனந்தம் தாங்கவில்லை.` Native scan 263 establishes `நடந்தவைகள்` rather than baseline `நடந்தவைகளை`, and `புதையலைக் கண்டுபிடிப்பதற்காகவே` rather than baseline `புதையல் ரகசியத்தைக் கண்டுபிடிப்பதற்காகவே`; full `மறந்து விடவில்லை` is confirmed on the second old-typeform pass.

Exact next action: reconcile **scan 264 / printed page 260**, continuing chapter 30. Do not start the Part-006 Tamil audit, assembled Tamil or English stages until all 49 pages are canonically reconciled.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |