# மூலப் பதிவு — புதையல்

## Source identity

- Source filename: `TVA_BOK_0064097_புதையல்.pdf`
- Source PDF committed to repository: **No**
- SHA-256: **pending — exact byte-level calculation not yet available; do not invent a checksum**
- File size of attached full PDF: **502,895,096 bytes**
- Exact full-PDF scan/page-object count: **pending full-source reconciliation**
- Tamil Digital Library bibliographic extent for this item: **443 p.**
- Language: Tamil
- Script: Tamil
- Controlling textual source: the supplied scanned PDF

> **Correction:** the earlier `Scan pages: 150` claim was wrong. `150` is only the known prefix initially exposed by the renderer. It must not be treated as the complete PDF/source extent.

Detailed correction record: [`../notes/source-page-count-reconciliation.md`](../notes/source-page-count-reconciliation.md).

## Split-source verification parts

The source is being handled through page-range access derivatives so the full work can be checked at usable visual resolution. These splits remain outside the repository and do not establish a new edition.

### Part 001 — complete

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- source scan range represented: **1–49**
- split PDF page count: **49**
- split file size available in chat runtime: **52,760,797 bytes**
- transcription / direct visual audit: **49 / 49 COMPLETE / VERIFIED**
- committed to repository: **No**

### Part 002 — available

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- source scan range represented: **50–98**
- split PDF page count: **49**
- materialized split size in chat runtime: **54,231,932 bytes**
- Iteration 5 baseline loaded: **scans 50–62 / printed pages 48–60**
- Iteration 6 baseline loaded: **scans 63–72 / printed pages 61–70**
- fine-grained wording / spacing / punctuation reconciliation: **pending for scans 50–72**
- committed to repository: **No**

## Title / authorship visible in the scan

Direct inspection establishes:

- Title: **புதையல்**
- Author line: **கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.**

The filename was not used as authority for this identification.

## Publication details visible in the scan

Direct reinspection of the front matter establishes:

- Publisher / imprint: **அன்புப் பதிப்பகம்**
- Place line: **பொறையார் :: தஞ்சை மாவட்டம்**
- Edition: **மூன்றாம் பதிப்பு**
- Edition date: **செப்டம்பர், 1961**
- Price lines visible on scan 4:
  - **சாதாரணப் பதிப்பு ரூ 5/-**
  - **ஸ்பெஷல் பதிப்பு ரூ 6/-**
- Scan 5 is headed **`பதிப்புரை`**.
- Scan 5 prints **`தமிழர்கள் ஆதரிக்க வேண்டுகின்றோம்.`**

### Catalogue discrepancy — do not override the scan

A Tamil Digital Library summary elsewhere says `முதல் பதிப்பு, 1961`, while the controlling scan visibly says `மூன்றாம் பதிப்பு, செப்டம்பர், 1961`.

For this repository edition, the **scan-printed edition statement governs**.

## External source-extent corroboration

The same Tamil Digital Library item is publicly catalogued with physical description **443 p.** and the item page lists **PDF — 2 Files** for `TVA_BOK_0064097`.

These catalogue facts establish that the first 150 known scans are not the full source extent. They are used only for source-completeness reconciliation; they do not replace direct scan readings.

## Printed-page numbering behaviour

Record a printed page number only where the numeral is actually visible.

Established processed examples:

- scans **1–7**: no visible printed page number;
- scan **8**: printed **6**;
- scans **9–12**: printed **7–10**;
- scan **13**: chapter-1 opening with **no visible printed page number** — do not infer 11;
- scan **14**: printed **12**;
- processed body scans then visibly continue through scan **72 / printed page 70**.

The page map remains the controlling per-scan record.

## Work-level structure — current evidence

`புதையல்` is one continuous work. Current directly established structure through scan 72:

```text
புதையல்
├── scans 7–12: அறிமுகம்
├── scan 13: chapter 1 begins
├── scan 22: chapter 1 closes; chapter 2 begins on same scan
├── scan 30: chapter 2 closes; chapter 3 begins on same scan
├── scan 40: chapter 3 closes; chapter 4 begins on same scan
├── scan 46: four-star internal transition
├── scan 47: embedded historical tale begins inside chapter 4
├── scan 52: chapter 4 closes; chapter 5 begins on same scan
├── scan 60: chapter 5 closes; chapter 6 begins on same scan
├── scan 68: chapter 6 closes
└── scan 69: chapter 7 begins
```

The embedded historical tale is an internal textual unit, not a separate work.

Important Iteration 6 structural correction: the supplied clean transcription showed chapter numeral `1` at scan 69 / printed 67; the source visibly prints **`7`**.

Later chapter checkpoints in the 150-row prefix remain provisional until their split-source ranges are directly inspected.

## Canonical Tamil layer — current state

- scans **1–49**: **verified** after direct split-source visual audit and correction history;
- scans **50–62**: Iteration 5 baseline loaded; **needs-review** pending fine-grained part-002 reconciliation;
- scans **63–72**: Iteration 6 baseline loaded with physical boundaries and chapter-7 structure established; **needs-review** pending fine-grained reconciliation;
- page records created: **72**;
- verified: **49**;
- needs-review: **23**;
- known-prefix not-started: **78**.

Fidelity records:

- [`../notes/visual-fidelity-scans-001-012.md`](../notes/visual-fidelity-scans-001-012.md)
- [`../notes/visual-fidelity-scans-013-022.md`](../notes/visual-fidelity-scans-013-022.md)
- [`../notes/visual-fidelity-scans-023-032.md`](../notes/visual-fidelity-scans-023-032.md)
- [`../notes/visual-fidelity-scans-033-049.md`](../notes/visual-fidelity-scans-033-049.md)
- [`../notes/visual-fidelity-scans-050-062.md`](../notes/visual-fidelity-scans-050-062.md)
- [`../notes/visual-fidelity-scans-063-072.md`](../notes/visual-fidelity-scans-063-072.md)

Important currently preserved part-002 boundaries include:

- scan 52 `அந்த` → scan 53 `வீட்டிற்கு...`;
- scan 54 `போயி` → scan 55 `யைப்பாரு...`;
- scan 57 `ஆசைப்` → scan 58 `படுகிறோம்...`;
- scan 64 `மோகினிப் பிசாசு` → scan 65 `இப்படி யெல்லாம்...`;
- scan 67 `அவர் அந்த உண்மையை` → scan 68 `தாண்டவனிடம் வெளியிடவில்லை...`;
- scan 70 `...கேட்பதற்கு அவன்` → scan 71 `மிகவும் தயங்கினான்...`;
- scan 71 `...போய்க் கொண்டிருக்கிறார்கள்` → scan 72 `என்னுடைய சாவில்...`;
- scan 72 ends at `ஆத்திரத்தோடு,`.

## Source extent / completeness status

Current state:

- source is known to extend beyond the first 150 known scans;
- Tamil Digital Library describes the item as **443 p.**;
- exact full-PDF scan/page-object count is unresolved;
- scan 150 / printed page 148 is **not** treated as the source ending;
- no closing-page, `முற்றும்`, advertisement, blank end leaf or back cover claim may be made until later scans are directly inspected.

The page manifest is therefore a **provisional prefix manifest**, not a complete-source map.

## Technical limitations still open

### Full page count

The exact full scan count remains pending. Page-range splitting is the working access method.

### SHA-256

The project requires an exact SHA-256 checksum for the original full source. Byte-level hashing of the 502,895,096-byte original remains pending.

**Do not fabricate or approximate either the exact scan count or SHA-256.**

## Source authority rule

The supplied scan is the controlling source for edition text. OCR, filename, catalogue summaries, memory, later editions, web text, grammar expectations or historical knowledge may assist navigation or source-extent reconciliation but may not silently replace what is visibly printed.

## Exact next source-registration / transcription action

1. fine-grained reconcile Iteration 5 scans **50–62 / printed 48–60** against split part 002;
2. then reconcile Iteration 6 scans **63–72 / printed 61–70**;
3. apply only source-established spelling / spacing / punctuation differences;
4. run a final direct page-by-page comparison before promotion to `verified`;
5. after that gate, continue from scan **73 / printed page 71**;
6. extend the page map beyond the current 150-row prefix as later split parts establish the full source;
7. calculate the original-source SHA-256 when byte-level access becomes available;
8. do not start English translation.