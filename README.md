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

[`collections/arumbu-1978/`](collections/arumbu-1978/README.md) is a **92-scan first-edition 1978 compilation containing four distinct Kalaignar stories**.

Component handling:

- [`அரும்பு`](works/arumbu/README.md) — scans 6–23 — **TAMIL / ASSEMBLED TAMIL PASSED; SECTION 17 NOT READY — scan-17 English correction required**;
- [`சாரப்பள்ளம் சாமுண்டி`](works/sarapallam-samundi/README.md) — scans 24–48 — registered / queued;
- [`பெரிய இடத்துப் பெண்`](works/periya-idathup-pen/README.md) — scans 49–74 — additional witness to the existing work, not a duplicate;
- [`நடுத்தெரு நாராயணி`](works/nadutheru-narayani/README.md) — scans 75–90 — registered / queued.

### Current `அரும்பு` state

- canonical Tamil: **18 / 18 VERIFIED**;
- all T1/T2/T3 source batches: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **1 / 1 PASSED**;
- English batches: **4 / 4 REVIEWED / COMPLETE**, full scans 6–23 coverage;
- Section 17 release-readiness: **NOT READY**;
- blocker: canonical scan 17 affirmative `எனக்குப் பொய் அம்மா வேணும்!` is currently translated with an inserted negative `I don't want a fake Amma!`;
- whole-work English VERIFIED label: **SUSPENDED pending narrow corrective recheck**;
- canonical Tamil changes during release preflight: **0**.

[`works/arumbu/translations/en/RELEASE_REPORT.md`](works/arumbu/translations/en/RELEASE_REPORT.md) records the release-preflight failure. The source PDF remains excluded from the repository; no `.pdf` path was found in the live recursive tree.

Exact next action: **narrow Section 16 corrective re-open for scan 17 only**, then rerun Section 17. Do not start another component before release closure.

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
