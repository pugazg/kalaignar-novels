# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. Source PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.

User-supplied transcription visual check செய்யப்படும் போது, ambiguous old Tamil glyph அடிப்படையில் assistant தானாக canonical text-ஐ மாற்றக்கூடாது. Exact disagreement-ஐ split-source image-ல் recheck செய்து source உறுதி செய்த பிறகே மாற்ற வேண்டும். Supplied transcription physical scan page முடியும் முன் நின்றுவிட்டால், missing remainder-ஐ guess செய்யாமல் அந்த page `partial` ஆகவே இருக்க வேண்டும்.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; scans 1–107 VERIFIED; scan 108 PARTIAL; 108 Tamil page records; parts 001–002 complete; part 003 active; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The old **150 pages total** claim is withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Available splits:

- `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — **scans 1–49 COMPLETE / VERIFIED**;
- `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — **scans 50–98 COMPLETE / VERIFIED**;
- `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf` — **available; scans 99–107 VERIFIED; scan 108 PARTIAL**.

Current status:

- page map — known prefix scans **1–150**, full-source coverage incomplete;
- Tamil page records — **108**;
- verified — **107** (`scans 1–107`);
- partial — **1** (`scan 108`);
- needs-review — **0**;
- unresolved readings through verified scan 107 — **0**;
- known-prefix not-started — **42**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Latest source-fidelity results

Iteration 9 was mapped to original scans **99–108 / printed pages 97–106** and compared against part 003.

Important findings include:

- scan 99 prints `இப்ப யாருடைய பெயரைச் சொன்னேன் தெரியுமா?` and contains a four-star internal transition;
- scan 100 → 101 splits `தோழர்களைத்` as `தோழர்` / `களைத்`;
- scan 101 prints `அவரைப் பற்றி நான் நன்கு விசாரிக்கவேண்டும் என்ற, ஒரு ஆவல்...` and closes chapter 10;
- scan 102 / printed 100 begins chapter 11;
- scan 104 prints `நெடு நாளா பழக்கமா?` and `உடல் வளர்த்து`;
- scan 105 prints `தொண்ணூறு` and `ஆசையா யிருந்தது`;
- scan 106 prints `நான் வரத்தான் வேண்டுமோ?`;
- scan 107 contains a four-star internal transition and ends at `கடை`;
- scan 108 begins `யாக`, completing `கடையாக`, but the supplied Iteration 9 text stops after `பேசிக்கொண்டிருந்தான் துக்காராம்.` while the source page visibly continues.

Latest fidelity record:

- [`works/pudhaiyal/notes/visual-fidelity-scans-099-108.md`](works/pudhaiyal/notes/visual-fidelity-scans-099-108.md) — **9/10 verified; scan 108 partial**

Exact next action: complete the lower portion of **scan 108 / printed page 106** from part 003, re-audit the full page, then continue from **scan 109 / printed page 107**.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).