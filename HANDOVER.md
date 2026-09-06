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

Current handover state: **33 / 179 canonical records, all 33 verified; historical-glyph PASS through scan 33.** Scans 28–32 former `partial` holds are resolved, and scan 33's mixed Chapter 3 / Chapter 4 boundary is verified. Verify live `main` before further source work.

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
- canonical records: **33 / 179, all verified**;
- Chapter 1: scans 4–12 verified / complete;
- Chapter 2: scans 13–22 verified / complete;
- Chapter 3: scans 23–32 plus the carryover at top of scan 33 verified;
- Chapter 4: source heading/opening begins on scan 33 and is verified through that physical page;
- printed page numbers confirmed: scans 28–32 = **27–31**, scan 33 = **32**;
- historical-glyph checks: **PASS through scan 33**;
- full Tamil source audit / assembled Tamil / English: **not started / not started / blocked**;
- source PDF committed: **No**.

## Resolved source-resolution hold — scans 28–32

The former `partial` records for scans 28–32 were re-opened at enlarged/native source resolution. Each page now has source-faithful Tamil transcription and a completed check of the mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No OCR/context reading was promoted without direct pixel evidence. Important physical continuities remain preserved:

- scan 28 `விஷயத்தை வெளி` → scan 29 `யில் சொல்லாதே...`;
- scan 31 `மூன்றாவது` → scan 32 `ஆள் வேம்பு!`.

## Verified scan-33 boundary

Scan 33 / printed page 32 contains, in this exact order:

1. a short **Chapter 3 carryover** dialogue paragraph;
2. the centered source-printed **`4`** heading;
3. the Chapter 4 opening.

The carryover was not moved backward into scan 32. The page ends `பெண்வீடு பார்ப்பதற்குத் தாயார் மட்டுமே`, whose continuation remains for scan 34.

Historical-glyph clearance on scan 33 includes the source line-split old-form cluster `நட்டு` + `வனர்`, decoded as **`நட்டுவனார்`** (`னா` family) from the source pixels.

## Source authority / historical-glyph rule

Authority: **controlling source scan → canonical `pages/` → later assembled Tamil → later English**.

Do not modernize spelling, grammar, punctuation, vocabulary, names, dialogue, or structure. Keep later marks outside printed text. Every body page must explicitly consider `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`; require positive pixel evidence and never global-replace.

## Exact next activity

**Stop at scan 33 unless the user explicitly instructs farther.** When continuation is authorized:

1. re-fetch live `main`;
2. resolve the controlling PDF;
3. process **scan 34** directly from source pixels, continuing Chapter 4 from scan 33;
4. populate scan 34's printed-page value only from its own visible source number;
5. apply the full historical-glyph gate;
6. synchronize page-map/audit/status docs and commit narrowly.

Do not start English or assembled Tamil. Do not reopen completed prior novels.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: 49/49 source-comparison coverage; assembled Tamil PASSED; English VERIFIED; release-ready with canonical-Tamil verification qualification; freeze remains 0 verified / 49 `needs-review`.
- **புதையல்**: 448/448 canonical; 446 complete; scans 223–224 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY.
