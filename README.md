# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை மூல ஸ்கேன்களின் பக்க வரிசையைக் காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் இருப்பதை அமைதியாகச் சீர்திருத்தவோ, நவீனப்படுத்தவோ, ஊகித்து நிரப்பவோ கூடாது. **மூல PDF கோப்புகள் repository-யில் commit செய்யப்படாது.**

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md) — reusable archival + translation + release workflow
- [`HANDOVER.md`](HANDOVER.md) — current project state and exact next action
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md) — fresh-chat continuation prompt

`works/balipeedam-nokki/` completed reference implementation ஆக பயன்படுத்தலாம்; ஆனால் புதிய source structure-ஐ அதற்கு force-fit செய்யக்கூடாது.

## தற்போது செயல்படும் work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [புதையல்](works/pudhaiyal/README.md) | கலைஞர் மு. கருணாநிதி, எம். எல். ஏ. | மூன்றாம் பதிப்பு, செப்டம்பர் 1961 | **Split-source fidelity workflow active; part 001 scans 1–49 received; scans 1–12 verified; 12 Tamil page records; full-source manifest still incomplete; translation blocked** |

### புதையல் — current source state

The repository previously treated **150 known/rendered scans** as the complete PDF. That claim has been withdrawn.

Tamil Digital Library's bibliographic record reports **443 p.** and the item is exposed there as **PDF — 2 Files**. The exact PDF scan/page-object count therefore remains pending until the remaining source ranges are reconciled.

The first split has now been supplied:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Current state:

- part 001 — **49 pages / source scans 1–49 received**;
- page map — **known prefix scans 1–150; full-source coverage incomplete**;
- Tamil page records created — **12**;
- verified — **12**;
- needs-review — **0**;
- complete `அறிமுகம்` scans 7–12 — **verified**;
- exact full-source scan count — **pending**;
- original SHA-256 — **pending**;
- Tamil audit — **not started**;
- assembled Tamil — **blocked**;
- English translation — **blocked**;
- source PDF committed — **No**.

Source-extent correction: [`works/pudhaiyal/notes/source-page-count-reconciliation.md`](works/pudhaiyal/notes/source-page-count-reconciliation.md).  
Latest fidelity review: [`works/pudhaiyal/notes/visual-fidelity-scans-001-012.md`](works/pudhaiyal/notes/visual-fidelity-scans-001-012.md).

The scan remains controlling for exact edition wording. It visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**, even though a catalogue summary elsewhere labels the work `முதல் பதிப்பு, 1961`; catalogue wording does not override the scan.

Exact next transcription batch: **scans 13–16 / printed pages 11–14** from split part 001.

## நிறைவு பெற்ற reference work

| நூல் | ஆசிரியர் | பதிப்பு | நிலை |
|---|---|---|---|
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | மு. கருணாநிதி | முதல் பதிப்பு, ஏப்ரல் 1947 | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY** |

### முக்கிய structural note

`பலிபீடம் நோக்கி` **ஒரே தொடர்ச்சியான படைப்பு**. Scan 8-ல் வரும் **`ராயசம் வெங்கண்ணா — தஞ்சை சரித்திரக் கதை`** தனி work அல்ல; `பலிபீடம் நோக்கி` நூலுக்குள் அமைந்த embedded cinematic-historical sequence.

Source continuity:

- scans 4–7 — opening `பலிபீடம்` frame;
- scan 7 — internal film introduction;
- scans 8–29 + scan 30 opening — `ராயசம் வெங்கண்ணா` sequence through `வணக்கம்`;
- scan 30 — `படம் முடிந்துவிட்டது...` return to the main frame;
- scans 31–33 — conclusion;
- scan 34 — blank/back matter.

### இறுதி status

- Tamil page records — **34 / 34**
- Tamil `verified` — **34 / 34**
- Tamil source audit — **PASSED**
- assembled Tamil reading layer — **PASSED**
- English translation plan — **COMPLETE**
- English Batches 1–6 — **reviewed**
- final bilingual alignment — **PASSED**
- whole-work English — **VERIFIED**
- release-readiness pass — **PASSED**
- combined archival package — **RELEASE-READY**
- source PDF in repository — **No**

Key files:

- [`works/balipeedam-nokki/audit.md`](works/balipeedam-nokki/audit.md)
- [`works/balipeedam-nokki/sections/README.md`](works/balipeedam-nokki/sections/README.md)
- [`works/balipeedam-nokki/translations/en/README.md`](works/balipeedam-nokki/translations/en/README.md)
- [`works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md`](works/balipeedam-nokki/translations/en/TRANSLATION_PLAN.md)
- [`works/balipeedam-nokki/translations/en/PROGRESS.md`](works/balipeedam-nokki/translations/en/PROGRESS.md)
- [`works/balipeedam-nokki/translations/en/GLOSSARY.md`](works/balipeedam-nokki/translations/en/GLOSSARY.md)
- [`works/balipeedam-nokki/translations/en/TRANSLATION_REVIEW.md`](works/balipeedam-nokki/translations/en/TRANSLATION_REVIEW.md)
- [`works/balipeedam-nokki/translations/en/RELEASE_REPORT.md`](works/balipeedam-nokki/translations/en/RELEASE_REPORT.md)

`RELEASE-READY` is an editorial/archival repository status and is not, by itself, a copyright or republication-rights determination.

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
    pages/
```

விரிவான workflow: [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md).  
தற்போதைய exact next action: [`HANDOVER.md`](HANDOVER.md).
