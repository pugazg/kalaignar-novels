# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

User-supplied transcription visual check செய்யப்படும் போது, ambiguous old Tamil glyph அடிப்படையில் assistant தானாக canonical text-ஐ மாற்றக்கூடாது. Exact disagreement-ஐ split-source image-ல் recheck செய்து source உறுதி செய்த பிறகே மாற்ற வேண்டும்.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; scans 1–72 VERIFIED; 72 Tamil page records; 0 needs-review; part 002 available through scan 98; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The old **150 pages total** claim is withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Available splits:

- `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — **scans 1–49 COMPLETE / VERIFIED**;
- `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — **available; scans 50–72 directly reconciled / VERIFIED; scans 73–98 not yet transcribed**.

Current status:

- page map — known prefix scans **1–150**, full-source coverage incomplete;
- Tamil page records — **72**;
- verified — **72** (`scans 1–72`);
- needs-review — **0**;
- unresolved readings through scan 72 — **0**;
- known-prefix not-started — **78**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Latest source-fidelity results

The part-002 audit corrected the physical Iteration 5 → 6 boundary: scan 62 / printed 60 ends with `எத்தனை மணியிருக்கும்?`; `அதற்குத்தான் ஆறுமாதமாக...` begins scan 63 / printed 61.

Other direct source corrections include:

- scan 54 `கேட்கிறீயா`;
- scan 56 `இமைகளைத்`;
- scan 60 `மனிதராயிற்றே`;
- scan 69 chapter numeral `7` and `எவ்வளவுதான்`;
- scan 70 `காரணத்தால்`, `குறும்புக்காரக் கிழவா`;
- scan 71 `பெரிய மனுஷா`.

Source punctuation and printed dash pauses were restored across scans 50–72 rather than retaining the clean extraction's systematic `..`, `!.`, `?.` punctuation.

Fidelity records now include:

- [`works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`](works/pudhaiyal/notes/visual-fidelity-scans-050-062.md) — **13/13 verified**
- [`works/pudhaiyal/notes/visual-fidelity-scans-063-072.md`](works/pudhaiyal/notes/visual-fidelity-scans-063-072.md) — **10/10 verified**

Exact next action: continue from **scan 73 / printed page 71**, preserving scan 72's unfinished `ஆத்திரத்தோடு,` continuation.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
