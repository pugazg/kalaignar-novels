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
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Backward integrity audit OPEN; 118 records; 107 verified; 11 needs-review; forward transcription frozen; full-source manifest incomplete; translation blocked** |

### புதையல் — source / integrity state

The old **150 pages total** claim remains withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Native publication-page reinspection corrected an earlier assistant misread: the source prints `நூல் நிலையப் பதிப்பு ரூ 6/-` and `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

Available splits:

- part 001 — source scans **1–49**;
- part 002 — source scans **50–98**;
- part 003 — source scans **99–147**.

Current canonical state:

- page records — **118**;
- verified — **107**;
- needs-review — **11**: scan 75 and scans 109–118;
- partial — **0**;
- known-prefix not-started — **32**: scans 119–150;
- full-source page map — **incomplete**;
- backward integrity audit — **OPEN**;
- forward transcription — **FROZEN**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

Central integrity record:

- [`works/pudhaiyal/notes/backward-integrity-audit-001-118.md`](works/pudhaiyal/notes/backward-integrity-audit-001-118.md)

The repair pass has already withdrawn multiple false assistant readings, including scan 11 `இருக்கிறாள்ன்னு`, scan 24 `அவர்களே நோக்கி`, scan 25 `ஏதோ`, scan 75 `போயிடுச்சா?`, scan 99 `இப்ப யாருடைய...`, scan 104 `நெடு நாளா...`, and scan 106 `வேண்டுமோ?`.

Exact next action: **re-audit scans 109–118 / printed pages 107–116 against native part-003 images, then resolve scan 75. Do not begin scan 119 until all 11 needs-review pages are closed.**

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
