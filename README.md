# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. தெளிவில்லாத வாசிப்புகள் வெளிப்படையாக `needs-review`, `partial`, அல்லது `blocked` எனக் குறிக்கப்பட வேண்டும்.

**மூல PDF கோப்புகள் இந்த repository-யில் commit செய்யப்படாது.** அவற்றின் filename, checksum, edition identity, scan condition மற்றும் page mapping மட்டும் metadata-வில் பதிவு செய்யப்படும்.

## தற்போதைய நூல்

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| பலிபீடம் நோக்கி | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **34/34 verified; Tamil source + assembled layer PASSED; English translation plan COMPLETE; pilot next** |

### முக்கிய structural note

`பலிபீடம் நோக்கி` **ஒரே தொடர்ச்சியான படைப்பு**. Scan 8-ல் வரும் source-printed **`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை`** தனி work அல்ல; நூலின் மைய வாதத்தை எடுத்துக்காட்ட கலைஞர் திரைப்பட வடிவில் அமைத்துள்ள embedded historical sequence.

Source continuity:

- scan 7 — narrator திரைப்படக் காட்சியைத் தானே அறிமுகப்படுத்துகிறார்;
- scans 8–29 மற்றும் scan 30-ன் தொடக்கம் — cinematic-historical sequence, `வணக்கம்` end-card வரை;
- scan 30 — `படம் முடிந்துவிட்டது...` என்று main frame-க்கு திரும்புகிறது;
- scans 31–33 — `பலிபீடம்` argument-ன் conclusion;
- scan 34 — blank/back matter.

அதனால் scans 4–33 அனைத்தும் ஒரே `work: balipeedam-nokki` identity-யின் கீழ் archive செய்யப்பட்டுள்ளன. `ராயசம் வெங்கண்ணு` source heading internal `section` label ஆக மட்டும் பாதுகாக்கப்பட்டுள்ளது.

### தற்போதைய status

- page records — **34 / 34**
- `verified` — **34 / 34**
- `needs-review` — **0**
- targeted character-level review — **complete**
- full page/metadata consistency audit — **passed**
- assembled Tamil reading layer — **complete + passed**
- English translation plan — **complete**
- English prose translation — **not started**
- source PDF in repository — **No**

Final audit: [`works/balipeedam-nokki/audit.md`](works/balipeedam-nokki/audit.md).  
Assembled reading layer: [`works/balipeedam-nokki/sections/README.md`](works/balipeedam-nokki/sections/README.md).  
English translation plan: [`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`](works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md).

அடுத்த activity: **Batch 1 pilot English translation — scans 4–7 / opening frame**. Pilot source-check முடிந்த பின் glossary/style decisions lock செய்யப்பட வேண்டும்; அதன் பிறகே Batch 2 தொடங்க வேண்டும்.

## களஞ்சிய அமைப்பு

```text
README.md
NOVEL_PROCESSING_GUIDE.md
HANDOVER.md
works/
  balipeedam-nokki/
    README.md
    metadata/
      source.md
    indexes/
      page-map.md
    pages/
    audit.md
    sections/
      README.md
      01-opening-frame.md
      02-rayasam-vengannu-sequence.md
      03-return-and-conclusion.md
    translations/
      en/
        TRANSLATION_PLAN.md
```

ஒவ்வொரு நூலும் தனித்த `works/<work-slug>/` அடைவில் பதிவாகும். பக்கவாரி records முதன்மை archival layer; assembled reading text, audit, translation மற்றும் review files derived layers ஆக சேர்க்கப்படும்.

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய நூல்: [`works/balipeedam-nokki/README.md`](works/balipeedam-nokki/README.md).
