# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Current state: **101 / 179 canonical records, all 101 verified; historical-glyph PASS through scan 101.** User-directed cadence: **5 physical scans per iteration**.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Durable state

- manifest **179 / 179**;
- canonical **101 / 179, all verified**;
- Chapter 9/10 boundary: scan 85 / printed 84;
- **Chapter 10/11 boundary: scan 92 / printed 91**;
- Chapter 11 verified through scan 99 pre-heading carryover / printed 98;
- **Chapter 11/12 boundary: scan 99 / printed 98**;
- Chapter 12 verified through scan 101 / printed 100;
- full Tamil audit / assembled Tamil / English: **not started / not started / blocked**.

## Do not regress

- recurring name **`நயினா`**, not `நயினு`;
- scan 66 page number source-visible **`5`**;
- scan 93 `பெண்ணாகப்` historical `ணா`;
- scan 94 `புறக்கப்போகிறேன்`;
- scan 95 Ramayana paragraph source-specific forms retained after enlarged review;
- scan 96 `வெளித்தாவரத்திலே` and `நயினா முகம்மது`;
- scan 98 bottom standalone `7` is a printer/signature mark, not a chapter heading;
- scan 99 mixed Chapter 11/12 boundary with centered `12`;
- scan 100 source `நடன மாடுகிறது`, `கிழிபட்ட`;
- scan 101 poison-to-medicine passage ends `சிறிது நாழிகைக்குப் பிறகு ஆனந்தி`.

## Completed 5-page batch — scans 92–96

All five scans passed direct visual transcription and the 13-family historical-glyph gate. No unresolved source cluster remains. Scan 96 ends `ஒரு நாற்காலியில் உட்`, continuing to scan 97.

## Completed 5-page batch — scans 97–101

All five scans passed direct visual transcription and the 13-family historical-glyph gate. Printed pages 96–100 were inspected directly. Durable physical continuities: scan 96 `ஒரு நாற்காலியில் உட்` → scan 97 `கார்ந்துகொண்டு`; scan 97 final `நயினா` → scan 98 `வைத் தாக்காமல் இல்லை`; scan 98 `இருந்` → scan 99 `தால்......`. Scan 99 preserves Chapter 11 carryover followed by centered `12` and Chapter 12 opening. Scan 101 ends `சிறிது நாழிகைக்குப் பிறகு ஆனந்தி`, continuing to scan 102. No unresolved source cluster remains.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling PDF;
3. process **scans 102–106** in one 5-scan iteration;
4. inspect printed numbers directly and preserve physical boundaries;
5. apply historical-glyph gate page by page;
6. synchronize page-map/audit/status docs, commit, verify live `main`;
7. stop after scan 106 unless explicitly instructed farther.

Do not start assembled Tamil or English. Do not reopen completed prior novels.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: 49/49 source-comparison coverage; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification.
- **புதையல்**: 448/448 canonical; 446 complete; scans 223–224 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY.
