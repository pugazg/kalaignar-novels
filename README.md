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
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; scans 1–98 VERIFIED; 98 Tamil page records; 0 needs-review; parts 001 and 002 complete; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The old **150 pages total** claim is withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Available splits:

- `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — **scans 1–49 COMPLETE / VERIFIED**;
- `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — **scans 50–98 COMPLETE / VERIFIED**.

Current status:

- page map — known prefix scans **1–150**, full-source coverage incomplete;
- Tamil page records — **98**;
- verified — **98** (`scans 1–98`);
- needs-review — **0**;
- unresolved readings through scan 98 — **0**;
- known-prefix not-started — **52**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Latest source-fidelity results

Iteration 8 was mapped to original scans **83–98 / printed pages 81–96** and directly compared with part 002. Important findings include:

- scan 83 completes scan 82's `ஆக்ரமிப்ப` with `தற்கும்` and closes chapter 8;
- scan 84 / printed 82 begins chapter 9 and prints `வேகமான நடையிலே`;
- scan 87 prints `அந்த உப்பரிகைத் தளத்தில்` and ends inside `நினைவுச் சுருள்கள்`;
- scan 88 completes that word with `கள்`; one clean-baseline sentence not present in the scan was not inserted;
- scan 91 prints continuous `முடியாதா`;
- scan 92 closes chapter 9;
- scan 93 / printed 91 begins chapter 10;
- scan 97 supports `சில விநாடிகள்` and `தெவிட்டுவதற்கு`;
- scan 98 is printed page **96**, carries a four-star internal separator, and is **not the end of the novel**.

Latest fidelity record:

- [`works/pudhaiyal/notes/visual-fidelity-scans-083-098.md`](works/pudhaiyal/notes/visual-fidelity-scans-083-098.md) — **16/16 verified**

Exact next action: obtain/use the next split beginning with **scan 99 / printed page 97** and continue the source-verified Tamil page layer.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).