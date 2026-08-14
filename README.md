# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. **மூல PDF கோப்புகள் repository-யில் commit செய்யப்படாது.**

## தற்போதைய நூல்

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| பலிபீடம் நோக்கி | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **34/34 Tamil verified; assembled Tamil PASSED; English Batches 1–4 reviewed; Batch 5 next** |

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
- English Batch 1 / scans 4–7 — **reviewed**
- English Batch 2 / scans 8–13 — **reviewed**
- English Batch 3 / scans 14–20 — **reviewed**
- English Batch 4 / scans 21–26 — **reviewed**
- English Batch 5 / scans 27–30 through `வணக்கம்` — **NEXT**
- English Batch 6 — **not started**
- source PDF in repository — **No**

Key files:

- [`works/balipeedam-nokki/audit.md`](works/balipeedam-nokki/audit.md)
- [`works/balipeedam-nokki/sections/README.md`](works/balipeedam-nokki/sections/README.md)
- [`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`](works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md)
- [`works/balipeedam-nokki/translations/en/PROGRESS.md`](works/balipeedam-nokki/translations/en/PROGRESS.md)
- [`works/balipeedam-nokki/translations/en/GLOSSARY.md`](works/balipeedam-nokki/translations/en/GLOSSARY.md)
- [`works/balipeedam-nokki/translations/en/sections/01-opening-frame.md`](works/balipeedam-nokki/translations/en/sections/01-opening-frame.md)
- [`works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md`](works/balipeedam-nokki/translations/en/sections/02-rayasam-vengannu-sequence.md)

English reviewed coverage now reaches **scan 26**. The next Batch 5 continues in the same internal-sequence file through the scan-30 `வணக்கம்` end-card only. The later `படம் முடிந்துவிட்டது...` text starts Batch 6 and the return/conclusion section.

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
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய நூல்: [`works/balipeedam-nokki/README.md`](works/balipeedam-nokki/README.md).