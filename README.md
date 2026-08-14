# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. **மூல PDF கோப்புகள் repository-யில் commit செய்யப்படாது.**

## தற்போதைய நூல்

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| பலிபீடம் நோக்கி | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **34/34 Tamil verified; assembled Tamil PASSED; English Batches 1–6 reviewed; final bilingual review next** |

### முக்கிய structural note

`பலிபீடம் நோக்கி` **ஒரே தொடர்ச்சியான படைப்பு**. Scan 8-ல் வரும் **`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை`** தனி work அல்ல; `பலிபீடம் நோக்கி` நூலுக்குள் அமைந்த embedded cinematic-historical sequence.

Source continuity:

- scans 4–7 — opening `பலிபீடம்` frame;
- scan 7 — narrator internal film-ஐ அறிமுகப்படுத்துகிறார்;
- scans 8–29 + scan 30 opening — `ராயசம் வெங்கண்ணு` cinematic sequence, `வணக்கம்` end-card வரை;
- scan 30 — `படம் முடிந்துவிட்டது...` என்று main frame-க்கு திரும்புதல்;
- scans 31–33 — conclusion;
- scan 34 — blank/back matter.

### தற்போதைய status

- Tamil page records — **34 / 34**
- Tamil `verified` — **34 / 34**
- Tamil source audit — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English translation plan — **COMPLETE**
- English Batches 1–6 — **reviewed**
- English body-text coverage — **scans 4–33 complete**
- Internal `ராயசம் வெங்கண்ணு` English sequence — **COMPLETE + REVIEWED**
- English return/conclusion — **COMPLETE + REVIEWED**
- Whole-work English `verified` — **No; final bilingual review pending**
- source PDF in repository — **No**

Key files:

- [`works/balipeedam-nokki/audit.md`](works/balipeedam-nokki/audit.md)
- [`works/balipeedam-nokki/sections/README.md`](works/balipeedam-nokki/sections/README.md)
- [`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`](works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md)
- [`works/balipeedam-nokki/translations/en/PROGRESS.md`](works/balipeedam-nokki/translations/en/PROGRESS.md)
- [`works/balipeedam-nokki/translations/en/GLOSSARY.md`](works/balipeedam-nokki/translations/en/GLOSSARY.md)
- [`works/balipeedam-nokki/translations/en/sections/01-opening-frame.md`](works/balipeedam-nokki/translations/en/sections/01-opening-frame.md)
- [`works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md`](works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md)
- [`works/balipeedam-nokki/translations/en/sections/03-return-and-conclusion.md`](works/balipeedam-nokki/translations/en/sections/03-return-and-conclusion.md)

English Batch 6 starts exactly inside scan 30 at `படம் முடிந்துவிட்டது...` and runs through scan 33. The internal film's preceding `வணக்கம்` remains only in section 2, so the source's narrative boundary is preserved without duplication.

அடுத்த activity: **final whole-work bilingual review**. Create `works/balipeedam-nokki/translations/en/TRANSLATION_REVIEW.md`, align all three English sections against the audited Tamil source, and only then decide whether English can be marked `verified`.

## களஞ்சிய அமைப்பு

```text
README.md
NOVEL_PROCESSING_GUIDE.md
HANDOVER.md
works/
  balipeedam-nokki/
    README.md
    metadata/
    indexes/
    pages/
    audit.md
    sections/
    translations/
      en/
        README.md
        TRANSLATION_PLAN.md
        PROGRESS.md
        GLOSSARY.md
        sections/
          01-opening-frame.md
          02-rayasam-vengannu-sequence.md
          03-return-and-conclusion.md
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய நூல்: [`works/balipeedam-nokki/README.md`](works/balipeedam-nokki/README.md).