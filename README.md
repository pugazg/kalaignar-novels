# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Ambiguous / damaged source reading என்றால் baseline-ஐ override செய்யாமல் `needs-review` ஆக வைத்திருக்க வேண்டும். Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

Old/historical Tamil glyphs காரணமாக ஒரு character அல்லது vowel mark source-ல் இல்லாதது போலத் தோன்றினால், correction செய்வதற்கு முன் முழு glyph cluster-ஐ high-resolution-ல் பார்க்க வேண்டும். இந்த source-ல் faint `லை` bare `ல்` போலவும், scan 264-ல் faint `ா` காரணமாக `என்னா` என்பது `என்ன` போலவும் தவறாகத் தோன்றியிருக்கிறது. Positive native-pixel evidence இல்லாமல் baseline மாற்றக்கூடாது; global normalization செய்யக்கூடாது.

**Strengthened rule:** old/faint vowel signs of **any kind**, near-identical same-word glyphs, or apparent spacing created by printed line wrapping require a second independent high-resolution inspection before a baseline difference is accepted. A line break alone is never evidence for word-internal spacing. If one reading in a batch is challenged, reopen every assistant-origin discrepancy in that batch.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **267 canonical records / 260 verified / 7 needs-review; Parts 001–005 part-complete; Part 006 in progress** |

### புதையல் — current source state

Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Access derivatives:

- part 001 — scans **1–49** — part-complete;
- part 002 — scans **50–98** — part-complete;
- part 003 — scans **99–147** — part-complete;
- part 004 — scans **148–196** — part-complete;
- part 005 — scans **197–245** — **part-complete with explicit source-damage qualification**;
- part 006 — scans **246–294 / printed 242–290** — **49-page derivative mapped; scans 246–267 verified; scans 268–294 not-started**.

Current canonical state:

- records — **267**;
- verified — **260**;
- needs-review — **7 (scans 215–219, 223–224)**;
- partial — **0**;
- clean contiguous fully verified range — through **scan 214 / printed page 212**;
- later individual source-verified records — through scan **267**, except the seven explicitly damaged scans;
- Parts 001–005 — full split workflow complete through assembled Tamil, controlled English and bilingual review;
- Part 006 — canonical/native-fidelity work in progress; **22 / 49** pages verified;
- assembled Tamil / English split-level review — still through scan **245** only;
- whole-work Tamil / English verification — not yet eligible;
- release-readiness — blocked until complete source;
- source PDF / splits committed — No.

Part 006 source structure is mapped through scan 294: chapter 28 begins at 247, a four-star internal transition occurs at scan 251, chapter 29 begins at 254 and closes at 262, chapter 30 begins at 262, chapter 31 at 271, chapter 32 at 278 and chapter 33 at 288.

Scans **260–267 / printed 256–263** are now verified from Iteration 25. Scan 267 closes scan 266's open sentence as `அதில், என் பாதியை நானும் என் காதலி பரிமளாவுந்தானே அனுபவிக்க வேண்டும்!`. Its strengthened old-glyph pass confirms `பாதிப் புதையலை` with final `லை`. Native source also establishes `கேட்டதால்தானே`, `புதைக்கப்பட்டது`, `துக்காராம் சொன்னது, இல்லையா?`, separated `பேசிக் கொள்ள வில்லையே`, and `கனவு கண்டார்களோ`.

Exact next action: reconcile **scan 268 / printed page 264**, continuing chapter 30. Do not start the Part-006 Tamil audit, assembled Tamil or English stages until all 49 pages are canonically reconciled.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |