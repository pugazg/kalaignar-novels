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

Current repository status remains `verified`. Scan 12 / printed page 10 was explicitly reopened and rechecked during the later high-resolution audit; no rollback was required.

Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22 — corrected high-resolution re-audit

After the Iteration 3 hallucination problem was identified, this earlier range was **not trusted automatically**. The native embedded scan images were extracted from the split PDF at **3146 × 4826** and the earlier assistant-vs-user discrepancies were rechecked.

The fresh re-audit found that several earlier assistant corrections were themselves wrong. Canonical records have been corrected.

Withdrawn assistant readings include:

- scan 13: `அப்போதுதான்` → corrected to `அப்போது தான்`;
- scan 13: `கையிலும்` → corrected to `கையிலேயும்` (`கையிலே` / `யும்` across the printed line break);
- scan 15: `நம்பிக்கையுண்டு` → `நம்பிக்கை யுண்டு`;
- scan 15: `அதனால்தான்` → `அதனால் தான்`;
- scan 15: `தன உயிருக்கு` → `தன உயிருக்கே`;
- scan 15: `அவர்களும் வந்துவிட்டார்கள்` → `அவர்களும் வந்து விட்டார்கள்`;
- scan 16: `அடங்கிவிட்டதாகத் தானே` → `அடங்கி விட்டதாகத் தானே`;
- scan 17: `இடையிலேதான்` → `இடையிலே தான்`;
- scan 17: `ஆராய்ந்து விட்டோமே` → `ஆராய்ந்து விட்டோம்`;
- scan 17: `சரியாகத்தான்` → `சரியாகத் தான்`;
- scan 19: `அவ்வளவுதான்` → `அவ்வளவு தான்`;
- scan 19: `நாளை தவற` → `நாளைத் தவற`;
- scan 21: `அடிபட்டுவிட்டதால்` → `அடிபட்டு விட்டதால்`.

The re-audit also confirmed that not every earlier correction was wrong. Still scan-supported are, among others:

- scan 13 has no visible printed page number;
- scan 14 `மருங்கப் பள்ளத்தின்` / `பூமியைத் தோண்டிப்`;
- scan 15 `மெளனமாய்` / `மெளனமாக்கியது`;
- scan 16 inscription through `கம்மாளர் கண்ணிலே......`;
- scan 18 four opening lines `அத்தான்!`, `கண்ணே!`, `ராஜா!`, `என்னடி ராஜாத்தி!`, and later `மறக்க மாட்டீர்களே கண்ணே!`;
- scan 19 `வெளவாலிடம்` / `வெளவால்`;
- scan 22 chapter `2` begins on the same physical scan after chapter `1` closes.

Scans **1–22 therefore remain `verified`**, but the verification record now reflects the corrected native-resolution re-audit rather than the earlier flawed pass.

Corrected report: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

### Scans 23–32 — Iteration 3 correction

The assistant's claimed visual-fidelity corrections for this range were **invalidated by the user**. The user's Iteration 3 wording has been restored to `pages/0023-pudhaiyal.md` through `pages/0032-pudhaiyal.md`.

These ten scans are currently **`needs-review`** because the assistant's earlier visual verification cannot be relied upon. The source PDF / split PDF remains outside the repository.

Invalidation record: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

### Revised verification rule

For subsequent user-supplied transcription batches, the supplied transcription is the baseline. Visual checking must not silently replace it. Native embedded scan images should be used before making any claim about an old-print glyph or spacing. If a reading remains ambiguous, mark the exact item `needs-review` and surface it for confirmation instead of committing an assistant inference.

## Physical page structure currently retained

- scan 22 / printed 20 — chapter 1 closes / chapter 2 begins on the same physical scan;
- scan 30 / printed 28 — chapter 2 closes / chapter 3 begins on the same physical scan;
- scan 32 / printed 30 ends mid-sentence at `காலைத்` in the restored user transcription.

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

The source scan remains the controlling source. The user's supplied transcription must not be overridden merely because an ambiguous old-print glyph appears different in a small preview. OCR, catalogue material, grammar expectations and assistant visual inference are aids only.

## Exact next activity

**Do not advance to scans 33–42 yet.** The next unresolved text range is scans **23–32**, whose user-supplied Iteration 3 transcription has been restored and is currently `needs-review`.

When work resumes, use native embedded scan images, keep the user's text as baseline, and flag only genuinely unresolved discrepancies. Continue full-source reconciliation as later split parts are supplied. Do not start English translation.
