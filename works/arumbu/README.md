# அரும்பு

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**Source volume:** `அரும்பு` — தமிழ்க்கனி பதிப்பகம், முதற் பதிப்பு 1978  
**Source physical range:** scans **6–23** of `TVA_BOK_0064361_அரும்பு.pdf`  
**Source PDF committed:** No

## Current state

- work identity: **CONFIRMED from component title page**;
- collection/source intake: **COMPLETE**;
- physical component span: **18 scans**;
- canonical page records: **5 / 18** — scans **6–10**;
- scans 6–10 T1 direct visual transcription: **PASS / COMPLETE**;
- scans 6–10 T2 independent historical-glyph re-read: **PASS / COMPLETE**;
- T2 character-identity corrections: **4 total** — 2 historical `னா` occurrences + 2 additional direct character corrections;
- unresolved T2 glyphs: **0**;
- page status: **5 `needs-review` / 0 verified**;
- final source-fidelity closure: **T3 NEXT for scans 6–10**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). A five-scan batch is processed as three separately committed checkpoints:

1. **T1 — direct transcription / canonical records** → synchronize controls → commit;
2. **T2 — independent historical-glyph re-read** → synchronize controls → commit;
3. **T3 — final source-fidelity closure** → synchronize controls → commit;
4. only after T3 may the next batch begin.

## Completed checkpoints — scans 6–10

### T1 — PASS

- five canonical page records created under `pages/`;
- printed-page visibility preserved exactly: scan 6 `null`; scans 7–10 show **2, 3, 4, 5**;
- scan 6 title illustration documented separately from narrative;
- physical joins preserved without moving text:
  - 7→8 `நடந்` / `தேறின.`;
  - 8→9 `அபிநய` / `அசைவுகளை...`;
  - 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`.

Checkpoint record: [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md).

### T2 — PASS

Independent full-page historical-glyph re-read completed across all five scans using the 13-family reference set.

Corrections:

- scan 7: `மனத்திற்குப்` → `மணத்திற்குப்`;
- scan 8: `கிழவனுக்குவா` → `கிழவனாகவா`;
- scan 8: `கிழவனுக்குவும்` → `கிழவனாகவும்`;
- scan 10: `அவனுடைய` → `அவளுடைய`.

The two scan-8 corrections are historical `னா` decoding corrections. The scan-7 and scan-10 changes are additional direct character-identity corrections caught during the independent page re-read. **0 unresolved glyphs** remain after T2.

Checkpoint record: [`T2_BATCH_006_010.md`](T2_BATCH_006_010.md).

All five pages remain `needs-review` because T3 has not yet run.

## Exact next activity

**T3 for physical scans 6–10 only.**

Perform the final independent source-fidelity closure: check omissions, duplication, misplaced fragments, page joins, printed-page visibility, illustration/body separation and the applied T2 corrections against the scans. Resolve only direct-source-supported issues; mark pages verified only if the gate fully passes. Synchronize controls and commit T3 separately. Stop before scan 11.
