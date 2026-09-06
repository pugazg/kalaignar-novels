# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Continuation prompt: `NEXT_NOVEL_CHAT_PROMPT.md`
- Current target: **வெள்ளிக்கிழமை**
- Active path: `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Do not repeat completed work because a copied checkpoint is older.

Current handover state: **32 / 179 canonical records = 27 verified + scans 28–32 `partial` source-review holds.** Verify the live commit carrying this state before further source work.

Before any source-dependent change, read completely:

1. `NOVEL_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. root `README.md`
4. this `HANDOVER.md`
5. `NEXT_NOVEL_CHAT_PROMPT.md`
6. `works/vellikkizhamai/README.md`
7. `works/vellikkizhamai/metadata/source.md`
8. `works/vellikkizhamai/indexes/page-map.md`
9. `works/vellikkizhamai/audit.md`
10. existing `works/vellikkizhamai/pages/*.md`

The controlling PDF must be attached/resolved before scan-level visual work. Do not commit the source PDF.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`  
File size: **251,126,214 bytes**  
Actual scans: **179**  
Image-only / no text layer  
Title: **வெள்ளிக்கிழமை**  
Author as printed: **மு. கருணாநிதி**  
Publisher: **திராவிடப்பண்ணை**  
Edition: **இரண்டாம் பதிப்பு: 1968**

## Current durable state

- manifest: **179 / 179 represented**;
- canonical records: **32 / 179**;
- verified records through scan 27; scans 28–32 are **partial**;
- Chapter 1: scans 4–12 verified / complete;
- Chapter 2: scans 13–22 verified / complete;
- Chapter 3: scans 23–27 verified; scans 28–32 partial; continues into the top of scan 33;
- printed page numbers confirmed: scans 28–32 = **27–31**, scan 33 = **32**;
- historical-glyph checks: **PASS through scan 27; pending scans 28–32**;
- full Tamil source audit / assembled Tamil / English: **not started / blocked**;
- source PDF committed: **No**.

## Important source-resolution status — scans 28–32

The physical scans were directly inspected and their printed-page numbers and Chapter 3 structure were confirmed. The currently available rendered source, however, is insufficient for reliable character-level historical-glyph verification at this project's standard. Accordingly, canonical files 0028–0032 are deliberately `partial`; they contain source-review metadata rather than a guessed full transcription.

Do **not** upgrade them to `verified` from context, OCR, web text or a low-resolution rendering. Re-open sufficient-resolution source pixels, check every difficult cluster and the mandatory historical set, then transcribe source-faithfully.

## Corrected scan-33 boundary

Scan 33 / printed page 32 contains:

1. a short **Chapter 3 carryover** passage at the top;
2. the centered source-printed **4** heading;
3. the Chapter 4 opening below the heading.

Therefore Chapter 3 does not end on scan 32. Never move the scan-33 carryover backward into scan 32.

## Source authority / historical-glyph rule

Authority: **controlling source scan → canonical `pages/` → later assembled Tamil → later English**.

Do not modernize spelling, grammar, punctuation, vocabulary, names, dialogue, or structure. Keep later marks outside printed text. Every body page must explicitly consider `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`; require positive pixel evidence and never global-replace.

## Exact next activity

1. Re-review scans **28–32** at sufficient resolution.
2. Complete their source-faithful Tamil transcription and historical-glyph checks page by page.
3. Change a page from `partial` to `verified` only after its direct visual gate passes.
4. Then process **scan 33**, preserving Chapter 3 carryover and Chapter 4 heading/opening on that same physical page.
5. Synchronize page-map, audit, work README, root README, handover and continuation prompt.
6. Commit narrowly and verify live `main`.

Do not start English or assembled Tamil. Do not reopen completed prior novels.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: 49/49 source-comparison coverage; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification; freeze remains 0 verified / 49 `needs-review`.
- **புதையல்**: 448/448 canonical; 446 complete; scans 223–224 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY.
