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

- [`அரும்பு`](works/arumbu/README.md) — scans 6–23 — **TAMIL SOURCE + ASSEMBLED TAMIL + ENGLISH PLAN PASSED / ENGLISH BATCHES 1–4 REVIEWED / SECTION 16 BILINGUAL REVIEW NEXT**;
- [`சாரப்பள்ளம் சாமுண்டி`](works/sarapallam-samundi/README.md) — scans 24–48 — registered / queued;
- [`பெரிய இடத்துப் பெண்`](works/periya-idathup-pen/README.md) — scans 49–74 — additional witness to the existing work, not a duplicate;
- [`நடுத்தெரு நாராயணி`](works/nadutheru-narayani/README.md) — scans 75–90 — registered / queued.

### Current `அரும்பு` state

- canonical / verified Tamil records: **18 / 18 — scans 6–23 contiguous**;
- all T1/T2/T3 source batches: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **PASS / COMPLETE — 1 / 1 section**;
- English translation plan: **PASS / COMPLETE**;
- English Batches 1–4: **4 / 4 REVIEWED / COMPLETE**;
- English prose coverage: **18 / 18 source scans — scans 6–23**;
- whole-work bilingual review: **NEXT — Section 16**;
- whole-work English: **NOT YET VERIFIED**.

The complete English reading layer is [`works/arumbu/translations/en/sections/01-arumbu.md`](works/arumbu/translations/en/sections/01-arumbu.md). The final Batch 4 checkpoint was checked against canonical Tamil pages 0021–0023 and closed with **0 omissions, 0 source-like additions and 0 unresolved translation items**.

Source-visible pagination remains exact: scan 6 is unnumbered; scans 7–13 show 2–8; scan 14 shows 10; scans 15–23 show 11–19. No printed page 9 is inferred. Final protected handling preserves `பேசினேன்` → **I spoke**, `அம்மனார்` → **Ammanar**, `இனி:......` → **from now on:......**, and adds no **The End** because no explicit `முற்றும்` is printed.

Exact next action: **create `TRANSLATION_REVIEW.md` and execute the Section 16 whole-work bilingual review for `அரும்பு` only**. Mark English VERIFIED only if that gate passes, then stop before Section 17 release-readiness or another component work.

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
