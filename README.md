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
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **128 records / 128 verified / 0 needs-review through scan 128; backward integrity audit COMPLETE through scan 118; forward transcription resumes at scan 129; full-source manifest incomplete; translation blocked** |

### புதையல் — source / integrity state

The old **150 pages total** claim remains withdrawn. Tamil Digital Library reports **443 p.**; exact original PDF scan count remains pending complete split reconciliation.

Native publication-page reinspection established `நூல் நிலையப் பதிப்பு ரூ 6/-` and `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

Available splits:

- part 001 — source scans **1–49**;
- part 002 — source scans **50–98**;
- part 003 — source scans **99–147**.

Current canonical state:

- page records — **128**;
- verified — **128**;
- needs-review — **0**;
- partial — **0**;
- unresolved readings through scan 128 — **0**;
- known-prefix not-started — **22**: scans 129–150;
- full-source page map — **incomplete**;
- backward integrity audit — **COMPLETE through scan 118**;
- forward transcription — **UNBLOCKED from scan 129**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

Central integrity record:

- [`works/pudhaiyal/notes/backward-integrity-audit-001-118.md`](works/pudhaiyal/notes/backward-integrity-audit-001-118.md)

The final unresolved old-glyph item on scan 75 is closed. The source word crosses a line boundary as `போயிட்` / `டுதா?`, establishing **`போயிட்டுதா?`**. The earlier assistant `போயிடுச்சா?` and temporary baseline `போய்ட்டுதா?` are both superseded.

The Iteration-10 re-audit is complete: scans **109–118 are 10 / 10 verified** against native part-003 images. Detailed record: [`works/pudhaiyal/notes/visual-fidelity-scans-109-118.md`](works/pudhaiyal/notes/visual-fidelity-scans-109-118.md).

Iteration 11 is also complete: scans **119–128 / printed pages 117–126 are 10 / 10 verified** against native part-003 split pages 21–30, including the source-confirmed chapter **13 → 14** transition on scan 128. Detailed record: [`works/pudhaiyal/notes/visual-fidelity-scans-119-128.md`](works/pudhaiyal/notes/visual-fidelity-scans-119-128.md).

Exact next action: **resume from scan 129 / printed page 127 using split part 003 page 31 and the next user-supplied baseline.**

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
