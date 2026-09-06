# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Current state: **106 / 179 canonical records, all 106 verified; historical-glyph PASS through scan 106.** User-directed cadence: **5 physical scans per iteration**.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Durable state

- manifest **179 / 179**;
- canonical **106 / 179, all verified**;
- Chapter 10/11 boundary: scan 92 / printed 91;
- Chapter 11/12 boundary: scan 99 / printed 98;
- Chapter 12 verified through scan 106 / printed 105;
- historical-glyph checks: **PASS through scan 106**;
- full Tamil audit / assembled Tamil / English: **not started / not started / blocked**.

## Do not regress

- recurring name **`நயினா`**, not `நயினு`;
- scan 66 page number source-visible **`5`**;
- scan 96 `வெளித்தாவரத்திலே`;
- scan 98 bottom standalone `7` is a printer/signature mark, not a chapter heading;
- scan 99 mixed Chapter 11/12 boundary with centered `12`;
- scan 102 `கண்கொட்டாமல்`, `அடைத்துக்கொள்வானேன்?`, `ஆட்டினள்`;
- scan 103 `என்னால் உங்களுக்கு வீண் சிரமம்`; `அவள் டாக்டர்! அதனால் அதைக் கண்டுபிடித்துவிட்டாள்.`;
- scan 104 `விபத்தினில்`;
- scan 105 `விஷங்கலக்கலாம்`;
- scan 106 `தவறுக சந்தேகப்பட்டுவிட்டேன்` and final `அவள் கண்களில்`.

## Completed 5-page batch — scans 102–106

All five scans passed direct visual transcription and the 13-family historical-glyph gate. Printed pages 101–105 were inspected directly. Physical continuities: scan 101 `சிறிது நாழிகைக்குப் பிறகு ஆனந்தி` → scan 102 `புரண்டு படுத்தாள்`; scan 103 `சொல்லு` → scan 104 `கிறேன்`; scan 105 `உன்` → scan 106 `சௌந்தர்யம்!`; scan 106 ends `அவள் கண்களில்`, continuing to scan 107. No unresolved source cluster remains.

## Exact next activity

1. re-fetch live `main`;
2. resolve controlling PDF;
3. process **scans 107–111** in one 5-scan iteration;
4. inspect printed numbers directly and preserve physical boundaries;
5. apply historical-glyph gate page by page;
6. synchronize page-map/audit/status docs, commit, verify live `main`;
7. stop after scan 111 unless explicitly instructed farther.

Do not start assembled Tamil or English. Do not reopen completed prior novels.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: 49/49 source-comparison coverage; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification.
- **புதையல்**: 448/448 canonical; 446 complete; scans 223–224 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY.
