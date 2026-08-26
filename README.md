# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. **மூல PDF / split PDF கோப்புகள் repository-யில் commit செய்யப்படாது.**

User-supplied transcription-ஐ visual check செய்யும்போது ambiguous old Tamil glyph அடிப்படையில் assistant தானாக canonical text-ஐ மாற்றக்கூடாது. Small preview-ஐ மட்டும் நம்பாமல் native embedded scan image-ஐ பார்க்க வேண்டும். இன்னும் ambiguity இருந்தால் `needs-review` ஆக flag செய்து உறுதிப்படுத்த வேண்டும்.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; part 001 scans 1–49 received; 32 Tamil page records; scans 1–22 verified after corrected native-resolution re-audit; scans 23–32 restored to user transcription and needs-review; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The earlier **150 pages total** claim has been withdrawn. Tamil Digital Library reports **443 p.**; exact PDF scan count remains pending until all source ranges are reconciled.

Received split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Current status:

- part 001 — **49 source scans received**;
- page map — **known prefix scans 1–150; full-source coverage incomplete**;
- Tamil page records — **32**;
- verified — **22**;
- needs-review — **10** (`scans 23–32`);
- known-prefix not-started — **118**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Important fidelity correction

After hallucinated assistant corrections were identified in scans 23–32, printed pages **10–20 / scans 12–22** were reopened at native embedded-image resolution.

That re-audit found several earlier assistant mistakes and corrected the canonical files, including `அப்போது தான்`, `கையிலேயும்`, `நம்பிக்கை யுண்டு`, `தன உயிருக்கே`, `அடங்கி விட்டதாகத் தானே`, `ஆராய்ந்து விட்டோம்`, `நாளைத் தவற`, and `அடிபட்டு விட்டதால்`.

The re-audit also confirmed some earlier source readings, including the four dialogue lines on scan 18 and the chapter-2 transition on scan 22.

Fidelity / correction records:

- [`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`](works/pudhaiyal/notes/visual-fidelity-scans-001-012.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`](works/pudhaiyal/notes/visual-fidelity-scans-013-022.md) — **corrected native-resolution re-audit**
- [`works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`](works/pudhaiyal/notes/visual-fidelity-scans-023-032.md) — **assistant correction claims invalidated; user transcription restored**

Physical structural checkpoints currently retained:

- scan 13 begins chapter 1 but has no visible printed page number;
- scan 22 / printed 20 closes chapter 1 and begins chapter 2 on the same scan;
- scan 30 / printed 28 closes chapter 2 and begins chapter 3 on the same scan;
- scan 40 / printed 38 begins chapter 4.

Do not advance the fidelity workflow to scans 33–42 yet. The unresolved range is scans 23–32, whose user transcription is restored and remains `needs-review`.

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
      source-page-count-reconciliation.md
      visual-fidelity-scans-001-012.md
      visual-fidelity-scans-013-022.md
      visual-fidelity-scans-023-032.md
    pages/
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
