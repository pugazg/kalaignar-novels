# Next Chat Prompt — வெள்ளிக்கிழமை / second historical-glyph re-audit

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Durable state

- canonical page records: **179 / 179 — COMPLETE**;
- final narrative: **scan 179 / printed 178**;
- forward mandatory historical-glyph coverage: **PASS scans 1–179**;
- unresolved source holds: **0**;
- second historical-glyph re-audit: **IN PROGRESS — scans 119–123 PASS / 5 of 61 complete**;
- second-pass corrections through scan 123: **0**;
- assembled Tamil / English: **not started / blocked**.

## Controlling phase — second historical-Tamil-glyph re-audit

The user explicitly requested one more independent glyph audit from **scan 119 through the end**, exactly **5 scans per iteration**.

Sequence:

`119–123 ✓ → 124–128 → 129–133 → 134–138 → 139–143 → 144–148 → 149–153 → 154–158 → 159–163 → 164–168 → 169–173 → 174–178 → 179`

Mandatory families on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Rules:
1. source pixels first; grammar only a locator;
2. compare each canonical page record against the source scan;
3. no global replacements or silent normalization;
4. one targeted enlargement per genuinely unclear token if needed;
5. if still unresolved, record a source hold instead of guessing;
6. record every correction, or explicitly record zero-correction PASS;
7. update affected page records plus `audit.md`, page map / README / HANDOVER / this prompt when phase state changes;
8. one atomic commit per 5-scan iteration;
9. do not start assembled Tamil or English until the entire second re-audit 119–179 is complete.

## Completed second-pass batch — scans 119–123

**PASS — 0 corrections / 0 unresolved.** Canonical Tamil is unchanged. Preserve the already verified physical joins `கவனித்து` → `விட்டான்.` and literal `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`.

## Exact next activity

Process **scans 124–128** only. Preserve known physical/structural evidence:

- scan 124 / 125: `புகை` + `வண்டி` = `புகைவண்டி`;
- scan 127: centered `16` opens Chapter 16;
- scan 127 / 128: `வாழ்` + `விலே` = `வாழ்விலே`.

Do not reopen scans 119–123 without new direct source evidence. Do not start assembled Tamil or English.
