# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் page/structure authority. தற்போதைய புதையல் work-ல் scan 280 onward lexical words Gemini baseline-ல் இருந்து மாற்றப்படாது.**

Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

### புதையல் scan 280 onward policy

User instruction படி:

- **words / spelling / suffix / lexical forms / supplied lexical spacing:** Gemini transcription exactly;
- **source scan:** heading, punctuation, quote marks, long dash, speaker-label spacing, paragraph structure, physical line/page breaks, separators, chapter/scene transitions and other structural findings;
- source scan வைத்து Gemini lexical text-ஐ silently correct செய்யக்கூடாது;
- Gemini lexical span omitted என்றால் flag செய்ய வேண்டும்; source words silently supply செய்யக்கூடாது.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **294 canonical records / 287 verified-complete / 7 needs-review; Parts 001–005 part-complete; Part 006 Tamil + assembled Tamil + controlled English source check PASSED; bilingual review next** |

### புதையல் — current source state

Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Access derivatives:

- parts 001–005 — scans **1–245** — split-level workflow complete, with seven source-damage qualifications in Part 005;
- part 006 — scans **246–294 / printed 242–290** — **49/49 canonical/structurally verified; Tamil audit PASSED; assembled Tamil check PASSED; controlled English source check PASSED**.

Current state:

- canonical records — **294**;
- verified / completed — **287**;
- needs-review — **7 (Part 005 scans 215–219, 223–224)**;
- partial — **0**;
- Part 006 — English **`source-checked`**, bilingual review pending;
- assembled Tamil — part-reviewed continuously through scan **294**;
- source-checked English — continuously through scan **294**;
- bilingual-reviewed / part-complete English — continuously through scan **245** only;
- whole-work Tamil / English verification — not yet eligible;
- release-readiness — blocked until complete source;
- source PDF / splits committed — No.

Part-006 records:

- Tamil audit: `works/pudhaiyal/notes/part-006-tamil-audit.md` — **PASSED**;
- assembled Tamil check: `works/pudhaiyal/notes/part-006-assembled-tamil-check.md` — **PASSED**;
- controlled English check: `works/pudhaiyal/translations/en/PART_006_ENGLISH_CHECK.md` — **PASSED**;
- chapter 27 now closes on scan 247 in both assembled Tamil and English;
- chapters 28–33 are translated through scan 294;
- the scan-251 four-star internal transition and all real chapter boundaries are retained;
- scan 294 / printed 290 ends at open Tamil `‘லாக்` / English `‘Lock` inside dialogue, with no closing punctuation. It is an access-derivative boundary, **not** the ending of chapter 33 or the novel.

Exact next action: run the **Part-006 bilingual review for scans 246–294**. Compare audited Tamil and source-checked English for complete sentence/dialogue coverage, meaning alignment, names/terms, satire/humour/violence/romance fidelity, all page joins, chapter/internal-transition structure and the open scan-294 endpoint. Only after that review passes may Part 006 be marked `part-complete`.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |