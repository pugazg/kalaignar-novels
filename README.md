# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Ambiguous / damaged source reading என்றால் baseline-ஐ override செய்யாமல் `needs-review` ஆக வைத்திருக்க வேண்டும். Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

Old/historical Tamil glyphs காரணமாக character / vowel mark source-ல் இல்லாதது போலத் தோன்றினால், correction செய்வதற்கு முன் முழு glyph cluster-ஐ high-resolution-ல் பார்க்க வேண்டும். இந்த source-ல் faint `லை`, faint `ா`, மற்றும் `ே` / `ோ` வேறுபாடுகள் demonstrated hazards. **Any** old/faint vowel sign, near-identical same-word glyph, or apparent spacing created by printed line wrapping requires a second independent high-resolution inspection before a baseline difference is accepted.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **274 canonical records / 267 verified / 7 needs-review; Parts 001–005 part-complete; Part 006 in progress** |

### புதையல் — current source state

Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Access derivatives:

- parts 001–005 — scans **1–245** — split-level workflow complete, with seven source-damage qualifications in Part 005;
- part 006 — scans **246–294 / printed 242–290** — **49-page derivative mapped; scans 246–274 verified; scans 275–294 not-started**.

Current canonical state:

- records — **274**;
- verified — **267**;
- needs-review — **7 (scans 215–219, 223–224)**;
- partial — **0**;
- Part 006 — **29 / 49** pages verified;
- assembled Tamil / English split-level review — still through scan **245** only;
- whole-work Tamil / English verification — not yet eligible;
- release-readiness — blocked until complete source;
- source PDF / splits committed — No.

Part 006 source structure is mapped through scan 294: chapter 28 begins at 247, a four-star internal transition occurs at scan 251, chapter 29 begins at 254 and closes at 262, chapter 30 begins at 262 and closes at 271, chapter 31 begins at 271, chapter 32 at 278 and chapter 33 at 288.

Scan **274 / printed 270** is now source-verified. It closes scan 273's mid-word `மறு` as **`மறுபடியும்`**, restores source punctuation `“புதையல்! புதையல்!! புதையல் ரகசியம்!!!”—`, confirms source `எரியும்போது`, and preserves source-specific `புதையல் ரகசியந்தான்`, `பிரக்ஞை`, `பார்வைப் பட்டது`, `அவளோட`, and `இல்லியே`. No unresolved Part-006 glyph remains through scan 274.

Exact next action: reconcile **scan 275 / printed page 271**, continuing chapter 31. Do not start the Part-006 Tamil audit, assembled Tamil or English stages until all 49 pages are canonically reconciled.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |