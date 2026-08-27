# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. **மூல PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.**

User-supplied transcription-ஐ visual check செய்யும்போது ambiguous old Tamil glyph அடிப்படையில் assistant தானாக canonical text-ஐ மாற்றக்கூடாது. Source page image-ஐ பார்த்து exact disagreement-ஐ தனியாக recheck செய்து, source உறுதி செய்த பிறகே canonical text மாற்ற வேண்டும்.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; part 001 scans 1–49 COMPLETE / VERIFIED; part 002 scans 50–98 available; Iterations 5–6 baselines loaded through scan 72; 72 Tamil page records; 49 verified; 23 needs-review; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The earlier **150 pages total** claim has been withdrawn. Tamil Digital Library reports **443 p.**; exact PDF scan count remains pending until all source ranges are reconciled.

Available splits:

- `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — **49/49 COMPLETE / VERIFIED**
- `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — **49-page split now available**

Current status:

- Iteration 5 baseline — **scans 50–62 / printed pages 48–60 loaded**;
- Iteration 6 baseline — **scans 63–72 / printed pages 61–70 loaded**;
- fine-grained part-002 source-fidelity audit — **pending for scans 50–72**;
- page map — **known prefix scans 1–150; full-source coverage incomplete**;
- Tamil page records — **72**;
- verified — **49** (`scans 1–49`);
- needs-review — **23** (`scans 50–72`);
- known-prefix not-started — **78**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Fidelity / structure status

Scans 1–49 are verified after the corrected source-fidelity history documented in the work notes. Part 002 is now available, but scans 50–72 remain deliberately `needs-review` until one controlled wording / spacing / punctuation reconciliation is completed.

Iteration 6 also exposed one unambiguous structural error in the clean transcription: the chapter numeral before `கள்ளத் தோணிகள் இலங்கைக் கரையை...` is **`7`**, not `1`. The source page at scan 69 / printed page 67 clearly prints `7`; that structural correction has been applied.

Current fidelity records:

- [`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`](works/pudhaiyal/notes/visual-fidelity-scans-001-012.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`](works/pudhaiyal/notes/visual-fidelity-scans-013-022.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`](works/pudhaiyal/notes/visual-fidelity-scans-023-032.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`](works/pudhaiyal/notes/visual-fidelity-scans-033-049.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-050-062.md`](works/pudhaiyal/notes/visual-fidelity-scans-050-062.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-063-072.md`](works/pudhaiyal/notes/visual-fidelity-scans-063-072.md)

Exact next activity: **fine-grained source-fidelity reconciliation of scans 50–72 against split part 002, then continue from scan 73 / printed page 71.**

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

`பலிபீடம் நோக்கி`-இல் `ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை` ஒரு internal cinematic-historical sequence; தனி work அல்ல.

## களஞ்சிய அமைப்பு

```text
README.md
NOVEL_PROCESSING_GUIDE.md
HANDOVER.md
NEXT_NOVEL_CHAT_PROMPT.md
works/
  balipeedam-nokki/
    ...
  pudhaiyal/
    README.md
    metadata/source.md
    indexes/page-map.md
    notes/
    pages/
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).