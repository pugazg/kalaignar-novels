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
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source workflow active; part 001 scans 1–49 COMPLETE / VERIFIED; 49 Tamil page records; 0 needs-review; full-source manifest incomplete; translation blocked** |

### புதையல் — current state

The earlier **150 pages total** claim has been withdrawn. Tamil Digital Library reports **443 p.**; exact PDF scan count remains pending until all source ranges are reconciled.

Received split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Current status:

- part 001 — **49 source scans received; 49/49 transcribed and visually audited**;
- page map — **known prefix scans 1–150; full-source coverage incomplete**;
- Tamil page records — **49**;
- verified — **49** (`scans 1–49`);
- needs-review — **0**;
- unresolved through scan 49 — **0**;
- known-prefix not-started — **101**;
- Tamil whole-work audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF / splits committed — **No**.

### Fidelity correction history

After hallucinated assistant corrections were identified, scans 12–22 were reopened and corrected. Scans 23–32 were then re-audited and reconciled page by page.

The user's Iteration 4 completed the rest of split part 001. Its continuous text was mapped back to physical **scans 33–49 / printed pages 31–47** and visually checked. Important source-established corrections include:

- scan 33: `“யார்?”` restored where the clean baseline had only `“?”`;
- scan 37: `கிழவர்` rather than `கிழ்வர்`;
- scan 38: `தோணிக்கு` rather than `தொணிக்கு`;
- scan 41: `அவன் திறக்காமலாவது`;
- scan 43: `புற்று நோய்` rather than `புத்து நோய்`;
- source punctuation and dash pauses restored instead of systematic clean-draft `..`, `!.`, `?.` forms.

Physical boundaries were also restored, including source-split words `சந்தோஷ` / `மாக` across scans 47–48 and `எப்படிப்` / `யாவது` across scans 48–49.

Scan 40 / printed page 38 closes chapter 3 and begins chapter 4 on the same physical scan. Scan 46 carries a four-star internal transition; scan 47 begins an embedded historical tale inside chapter 4. It is **not** promoted to a separate work.

Scan 49 / printed page 47 ends mid-sentence at `அவள் அப்பனும்,`; this is only the end of split part 001.

Fidelity / correction records:

- [`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`](works/pudhaiyal/notes/visual-fidelity-scans-001-012.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-013-022.md`](works/pudhaiyal/notes/visual-fidelity-scans-013-022.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-023-032.md`](works/pudhaiyal/notes/visual-fidelity-scans-023-032.md)
- [`works/pudhaiyal/notes/visual-fidelity-scans-033-049.md`](works/pudhaiyal/notes/visual-fidelity-scans-033-049.md) — **split part 001 completion; 17/17 verified; unresolved 0**

Exact next source requirement: **next split beginning with original scan 50**.

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
      visual-fidelity-scans-033-049.md
    pages/
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).