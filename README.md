# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

User-supplied transcription visual check செய்யப்படும் போது ambiguous old Tamil glyph அடிப்படையில் assistant தானாக canonical text-ஐ மாற்றக்கூடாது. Exact disagreement-ஐ native split-source image-ல் recheck செய்து source உறுதி செய்த பிறகே மாற்ற வேண்டும். Ambiguous reading என்றால் baseline-ஐ override செய்யாமல் page `needs-review` ஆக இருக்க வேண்டும்.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **187 records / 187 verified / 0 needs-review; Parts 001–003 part-complete; Part 004 in progress at 40/49 verified through scan 187** |

### புதையல் — source / integrity state

The old **150 pages total** claim remains withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Native publication-page reinspection established `நூல் நிலையப் பதிப்பு ரூ 6/-` and `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

Available access derivatives:

- part 001 — source scans **1–49** — **part-complete**;
- part 002 — source scans **50–98** — **part-complete**;
- part 003 — source scans **99–147** — **part-complete**;
- part 004 — source scans **148–196** — **in progress: scans 148–187 verified; scans 188–196 pending**.

Current canonical state:

- page records — **187**;
- verified — **187**;
- needs-review — **0**;
- partial — **0**;
- unresolved readings through scan 187 — **0**;
- Part-004 not-started — **9**: scans 188–196;
- full-source page map — **incomplete**;
- backward integrity audit — **COMPLETE through scan 118**;
- Tamil part audits — **PASSED through Part 003 / scan 147**;
- assembled Tamil — **part-reviewed continuously through scan 147**;
- English translation — **bilingual part-reviewed continuously through scan 147**;
- whole-work Tamil / English verification — **not yet eligible**;
- release-readiness — **blocked until complete source**;
- source PDF / splits committed — **No**.

Part-004 working records:

- [`works/pudhaiyal/indexes/part-004-page-map.md`](works/pudhaiyal/indexes/part-004-page-map.md)
- [`works/pudhaiyal/notes/part-004-structural-preflight-148-196.md`](works/pudhaiyal/notes/part-004-structural-preflight-148-196.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-178-187.md`](works/pudhaiyal/notes/visual-fidelity-scans-178-187.md)

Scan **187 / printed page 185** closes chapter 20 and begins chapter 21. Its physical endpoint is **`அதுகூட`**; no continuation has been inferred.

Exact next action: **continue Part 004 at scan 188 / printed page 186 / split page 41, establish the continuation of `அதுகூட` from native source pixels, and after scan 196 complete Part 004's full Tamil/assembled/English/bilingual part workflow before moving onward.**

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
