# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் page/structure authority. தற்போதைய புதையல் work-ல் scan 280 onward lexical words Gemini baseline-ல் இருந்து மாற்றப்படாது.**

Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

### புதையல் scan 280 onward policy

User instruction படி:

- **words / spelling / suffix / lexical forms:** Gemini transcription exactly;
- **source scan:** heading, punctuation, quote marks, long dash, speaker-label spacing, paragraph structure, physical line/page breaks, separators, chapter/scene transitions and other structural findings;
- source scan வைத்து Gemini word-ஐ silently correct செய்யக்கூடாது;
- Gemini lexical span omitted என்றால் flag செய்ய வேண்டும்; source words silently supply செய்யக்கூடாது;
- இந்த policy scan 280 onward prospective; scans 246–279-ஐ இதற்காக மட்டும் reopen செய்யக்கூடாது.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **283 canonical records / 275 verified-complete / 8 needs-review; Parts 001–005 part-complete; Part 006 in progress** |

### புதையல் — current source state

Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Access derivatives:

- parts 001–005 — scans **1–245** — split-level workflow complete, with seven source-damage qualifications in Part 005;
- part 006 — scans **246–294 / printed 242–290** — **49-page derivative mapped; scans 246–282 verified/complete; scan 283 needs-review; scans 284–294 not-started**.

Current canonical state:

- records — **283**;
- verified / completed — **275**;
- needs-review — **8 (Part 005 scans 215–219, 223–224; Part 006 scan 283)**;
- partial — **0**;
- Part 006 — **37 verified/completed + 1 needs-review / 49**;
- assembled Tamil / English split-level review — still through scan **245** only;
- whole-work Tamil / English verification — not yet eligible;
- release-readiness — blocked until complete source;
- source PDF / splits committed — No.

Part 006 source structure is mapped through scan 294: chapter 28 begins at 247, four-star internal transition at 251, chapter 29 begins 254 and closes 262, chapter 30 begins 262 and closes 271, chapter 31 begins 271 and closes 278, chapter 32 begins 278, chapter 33 begins 288.

Scans **280–283** are processed under the Gemini-lexical/native-structure rule. On scan 283, the native source contains the word `பார்` after `ஓடிப் போகிறேன்`, but that word is absent from the Gemini baseline. In accordance with the user's policy, it was not silently inserted; scan 283 is explicitly `needs-review` pending user disposition. The page otherwise preserves native punctuation/long-dash/paragraph and physical-line findings while leaving Gemini lexical wording unchanged.

Exact next action: process **scan 284 / printed page 280**, continuing chapter 32 under the same hybrid policy. Keep scan 283's `பார்` omission open unless the user resolves it. Do not start Part-006 Tamil audit, assembled Tamil or English stages until all 49 pages have canonical dispositions.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |