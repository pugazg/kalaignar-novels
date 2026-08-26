# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Critical source-extent correction

The earlier project state incorrectly treated the first **150 known/rendered scans** as the entire supplied PDF. That claim is withdrawn. Tamil Digital Library reports **443 p.**, so the archive treats scans 1–150 only as a known prefix until later split-source ranges establish the true full scan count.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Split-source verification

Received:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split PDF pages: **49**
- split file size available in the chat runtime: **52,760,797 bytes**
- committed to repository: **No**

This split is an access derivative of the controlling source, not a new edition.

## Current archival status

- source identity from scan — **confirmed**
- scan-printed edition — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- source metadata — **registered; exact full scan count + original SHA-256 pending**
- page map — **known prefix scans 1–150 mapped; full-source coverage incomplete**
- Tamil page records created — **32**
- `verified` — **22**
- `needs-review` — **10** (`scans 23–32`)
- remaining known-prefix rows `not-started` — **118**
- Tamil source audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Fidelity passes

### Scans 1–12 — front matter + `அறிமுகம்`

Current repository status remains `verified`. Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22 — chapter 1 + chapter 2 opening

Current repository status remains `verified`. Detailed review: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

Important structural result retained: scan 22 / printed page 20 closes chapter `1` and begins chapter `2` on the same physical scan.

### Scans 23–32 — Iteration 3 correction

The assistant's claimed visual-fidelity corrections for this range were **invalidated by the user**. The user explicitly confirmed that the Iteration 3 transcription they supplied is correct and that the assistant's proposed replacements were hallucinated.

Actions taken:

- restored `pages/0023-pudhaiyal.md` through `pages/0032-pudhaiyal.md` to the user's supplied Iteration 3 wording;
- withdrew all assistant-proposed source-reading corrections from that pass;
- changed scans 23–32 from `verified` to **`needs-review`** because the assistant visual verification cannot be relied upon;
- retained the source PDFs outside the repository.

Invalidation record: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

### Revised verification rule

For subsequent user-supplied transcription batches, the supplied transcription is the baseline. Visual checking must not silently replace it. If an old Tamil glyph, spacing, punctuation mark or word appears different, record that exact point as `needs-review` and surface it for confirmation instead of committing an assistant-inferred reading.

This rule is especially important for degraded print and old Tamil glyph forms.

## Physical page structure currently retained

The chapter/page-boundary structure itself remains recorded separately from disputed textual readings:

- scan 22 / printed 20 — chapter 1 closes / chapter 2 begins on the same physical scan;
- scan 30 / printed 28 — chapter 2 closes / chapter 3 begins on the same physical scan;
- scan 32 / printed 30 ends mid-sentence at `காலைத்` in the supplied transcription.

## Source structure — currently known prefix only

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins;
- scan 22 — chapter 1 closes / chapter 2 begins;
- scan 30 — chapter 2 closes / chapter 3 begins;
- scan 40 — chapter 4 begins;
- scan 52 — chapter 5 begins;
- scan 60 — chapter 6 begins;
- scan 69 — chapter 7 begins;
- scan 75 — chapter 8 begins;
- scan 84 — chapter 9 begins;
- scan 93 — chapter 10 begins;
- scan 102 — chapter 11 begins;
- scan 110 — chapter 12 begins;
- scan 119 — chapter 13 begins;
- scan 128 — chapter 14 begins;
- scan 138 — chapter 15 begins;
- scan 146 — chapter 16 begins within the known prefix.

No claim is made yet about later chapter boundaries or the true source ending.

## Important edition/catalogue distinction

The controlling scan visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**. A Tamil Digital Library summary elsewhere says `முதல் பதிப்பு, 1961`; the catalogue does not override the scan.

## Source registration

- Original filename: `TVA_BOK_0064097_புதையல்.pdf`
- Original attached-file size: **502,895,096 bytes**
- Tamil Digital Library physical description: **443 p.**
- Exact original PDF scan/page-object count: **pending**
- Original SHA-256: **pending exact byte-level calculation**
- Source PDF / split PDFs committed to repository: **No**

Full source record: [`metadata/source.md`](metadata/source.md).  
Current prefix manifest: [`indexes/page-map.md`](indexes/page-map.md).

## Authority

The source scan remains the controlling source. The user's supplied transcription must not be overridden merely because the assistant believes an ambiguous old-print glyph looks different. OCR, catalogue material, grammar expectations and assistant visual inference are aids only.

## Exact next activity

**Pause before advancing to scans 33–42.** Scans 23–32 have been restored to the user's Iteration 3 transcription and are currently `needs-review` because the previous visual pass was invalidated.

When transcription work resumes, use the user's supplied text as the baseline and flag apparent source discrepancies for confirmation rather than silently changing the canonical text. Continue full-source reconciliation as later split parts are supplied. Do not start English translation.
