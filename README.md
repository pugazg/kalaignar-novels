# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. தெளிவில்லாத வாசிப்புகள் வெளிப்படையாக `needs-review`, `partial`, அல்லது `blocked` எனக் குறிக்கப்பட வேண்டும்.

**மூல PDF கோப்புகள் இந்த repository-யில் commit செய்யப்படாது.** அவற்றின் filename, checksum, edition identity, scan condition மற்றும் page mapping மட்டும் metadata-வில் பதிவு செய்யப்படும்.

## தற்போதைய நூல்

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| பலிபீடம் நோக்கி | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | source registered; 34-page manifest complete; 3/34 page records created |

இந்த scan-இல் `பலிபீடம் நோக்கி`க்கு பின்பு **`ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை`** இடம்பெறுகிறது. இரண்டும் ஒரே scanned publication-ன் பகுதிகளாக source identity-யுடன் பாதுகாக்கப்படும்.

### தற்போதைய page status

- scan 1 — `verified`
- scan 2 — `verified`
- scan 3 — `needs-review` (ஒரு குறும் சொற்றொடர் unresolved; ஊகித்து நிரப்பப்படவில்லை)
- scans 4–34 — `not-started`

அடுத்த batch: **scans 4–7**, அதாவது `பலிபீடம் நோக்கி` textual unit முழுவதும்.

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
    sections/
```

ஒவ்வொரு நூலும் தனித்த `works/<work-slug>/` அடைவில் பதிவாகும். பக்கவாரி records முதன்மை archival layer; பின்னர் தேவையான section/chapter assemblies, audit, translation மற்றும் review files சேர்க்கப்படும்.

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய நூல்: [`works/balipeedam-nokki/README.md`](works/balipeedam-nokki/README.md).
