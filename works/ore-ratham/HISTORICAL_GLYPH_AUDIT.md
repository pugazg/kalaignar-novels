# Historical Glyph Audit — ஒரே இரத்தம்

## Status

**POLICY ACTIVE / PAGE-LEVEL AUDIT NOT STARTED**

This work adopts the repository root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` before any bulk Tamil transcription.

## Core rule

> **Read character identity, not modern visual resemblance.**

The task is to decode historical type into the correct modern Unicode character identity without modernizing the source text.

## Mandatory known families

Every narrative/text page must explicitly consider:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

This is a minimum set, not an exhaustive claim about the 1980 typeface.

## Required workflow

For each page:
1. inspect the whole page;
2. use enlarged/native source pixels;
3. check the 13 known families;
4. read complete glyph clusters;
5. compare same-edition occurrences where useful;
6. keep lexical expectation separate from evidence;
7. encode only proven Unicode character identity;
8. preserve all other source wording;
9. leave unresolved clusters `needs-review`;
10. never global-replace.

## Correction ledgers

Maintain separate ledgers for:
- historical-glyph identity corrections;
- ordinary lexical/source-text corrections;
- punctuation/spacing/source-structure corrections.

A glyph correction is not authorization to modernize a word.

## Verification rule

A page may complete a historical-glyph pass and still remain `needs-review`.

`verified` requires the explicit visual-verification gate.

## Current accounting

- pages audited — **0 / 136**
- historical-glyph corrections — **0**
- ordinary source-text corrections — **0**
- unresolved historical-glyph clusters — **0 recorded yet**
- exact next — **full page map, then Pass1 with glyph-aware notes**
