# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

> **மூல ஸ்கேன் page/structure authority.** Source PDF files repository-யில் commit செய்யப்படாது.

## Project controls

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](SOURCE_BATCH_CHECKPOINT_WORKFLOW.md)
- [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## Active source — `அரும்பு` 1978 compilation

[`collections/arumbu-1978/`](collections/arumbu-1978/README.md) is a **92-scan first-edition 1978 compilation containing four distinct Kalaignar stories**. Collection/source intake is complete.

Component handling:

- [`அரும்பு`](works/arumbu/README.md) — scans 6–23 — **ACTIVE; page-level T1/T2/T3 complete, whole-work Tamil audit next**;
- [`சாரப்பள்ளம் சாமுண்டி`](works/sarapallam-samundi/README.md) — scans 24–48 — registered / queued;
- [`பெரிய இடத்துப் பெண்`](works/periya-idathup-pen/README.md) — scans 49–74 — additional witness to the existing work, not a duplicate;
- [`நடுத்தெரு நாராயணி`](works/nadutheru-narayani/README.md) — scans 75–90 — registered / queued.

### Current `அரும்பு` state

- canonical records: **18 / 18 — scans 6–23**;
- verified records: **18 / 18 — scans 6–23 contiguous**;
- scans 6–10 T1/T2/T3: **PASS / COMPLETE**;
- scans 11–15 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T1/T2/T3: **PASS / COMPLETE**;
- scans 16–20 T2: 1 correction / 0 unresolved;
- scans 16–20 T3: 11 additional source-fidelity corrections / 0 unresolved;
- scans 21–23 T1: **PASS / COMPLETE**;
- scans 21–23 T2: **PASS / COMPLETE — 0 corrections / 0 unresolved**;
- scans 21–23 T3: **PASS / COMPLETE — 4 additional corrections / 0 unresolved**;
- whole-work Tamil audit: **NEXT**;
- assembled Tamil / English: **BLOCKED until the Tamil audit gate passes**.

Final-batch T3 corrected two scan-21 punctuation marks, scan-22 `ஆஸ்பத்திரியிலே` → `ஆஸ்பத்திரியில்`, and scan-23 `இனி......` → `இனி:......`. T2-confirmed source readings `பேசினேன்` and `அம்மனார்` remain unchanged.

Exact next action: **run the whole-work Tamil audit gate for `அரும்பு` only**, synchronize controls, commit, and stop before assembled Tamil, English, `சாரப்பள்ளம் சாமுண்டி`, or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.

## Latest completed work — வெள்ளிக்கிழமை

[`works/vellikkizhamai/`](works/vellikkizhamai/README.md) — 1968 second edition, **179 / 179 canonical Tamil VERIFIED**, assembled Tamil **23 / 23 PASSED**, English **23 / 23 REVIEWED**, final bilingual review **PASSED**, whole-work English **VERIFIED**, Section 17 release-readiness **PASSED**.

## Completed works

| நூல் | நிலை |
|---|---|
| [வெள்ளிக்கிழமை](works/vellikkizhamai/README.md) | Tamil 179/179 verified; assembled Tamil 23/23 PASSED; English VERIFIED; **release-ready** |
| [பெரிய இடத்துப் பெண்](works/periya-idathup-pen/README.md) | 1953 controlling edition; English VERIFIED; release-ready with qualification; 1978 additional witness registered |
| புதையல் | canonical 448; 446 complete / 2 physical-loss needs-review; English VERIFIED; release-ready with qualification |
| [பலிபீடம் நோக்கி](works/balipeedam-nokki/README.md) | Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready |

## Release-status note

Repository `release-ready` is an **archival/editorial** judgment. It does not automatically determine copyright, licensing, public-domain status, republication rights or commercial-use permission for an underlying work, scan or translation.
