# கலைஞர் புதினங்கள் / கதைநூல்கள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் புதினங்கள், வரலாற்றுக் கதைகள் மற்றும் தொடர்புடைய கதைநூல்களை source provenance காக்கும் வகையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் page/structure authority.** Source PDF / split PDF / uploaded baseline files repository-யில் commit செய்யப்படாது.

## Project continuation documents

- [`NOVEL_PROCESSING_GUIDE.md`](NOVEL_PROCESSING_GUIDE.md)
- [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`NEXT_NOVEL_CHAT_PROMPT.md`](NEXT_NOVEL_CHAT_PROMPT.md)

## Active work

### [வெள்ளிக்கிழமை](works/vellikkizhamai/README.md)

- source edition: **இரண்டாம் பதிப்பு, 1968**;
- source PDF: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`;
- actual PDF scans: **179**;
- page manifest: **179 / 179 represented**;
- canonical page records: **143 / 179**;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 18 opening: **scan 142 / printed 141**, centered `18`;
- Chapter 18 transcribed through **scan 143 / printed 142**;
- historical-glyph coverage: **PASS scans 1–143**;
- next forward iteration: **scans 144–148**;
- batch size: **5 scans**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

### Historical Tamil glyph handling

Mandatory family set on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Source pixels decide identity. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing, colloquial forms and physical boundaries. Never global-replace.

### Current production workflow

Five-page batches use a bounded pipeline: transcribe all five full pages first, run one batch-level 13-family sweep, allow at most one targeted enlargement for a genuinely unclear token, record a source hold if still unresolved, then update page records and status documents together in one atomic commit. Prior PASS pages are not reopened without new direct source evidence.

Recent durable boundaries include scan 138 / 139 `‘மளமள’` → `வென்று...`, scan 139 / 140 `புயலால் தாக்குண்டவன்போல` → `ஆனேன் அன்று!`, scan 140 / 141 `நயினா` → `எதுவும் பேசவில்லை.`, and scan 142 / 143 `வாசகங்கள்` → `இருந்தன.`. Source-specific forms newly preserved include `வழங்கினை`, `சூறாவளி`, `காணத் வேண்டிப்போலவே`, `கைகாரியானாள்`, `நனைந்துபோன`, `அனைவருங்கூடி`, `விளக்கமுறைக்கவேண்டுமென்று`, and `எங்ஙனம்`.

## Completed works

| நூல் | நிலை |
|---|---|
| பெரிய இடத்துப் பெண் | **49/49 canonical complete; Tamil source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification** |
| புதையல் | **448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification** |
| பலிபீடம் நோக்கி | **Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready** |

## Next activity

Process **scans 144–148** as one bounded 5-page iteration. Establish scan 144 only from direct source evidence after scan 143's complete final sentence. Do not start assembled Tamil or English.
