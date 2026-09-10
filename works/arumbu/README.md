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
- direct visual transcription: **T1 COMPLETE for scans 6–10**;
- page status: **5 `needs-review` / 0 verified**;
- historical-glyph gate: **T2 NEXT for scans 6–10**;
- final source-fidelity closure: **T3 BLOCKED by T2**;
- assembled Tamil: **BLOCKED**;
- English: **BLOCKED**.

This work is the first component of the 1978 four-story compilation and shares its title with the volume itself. Collection provenance is recorded at `../../collections/arumbu-1978/`.

## Active checkpoint workflow

Source batches follow root [`SOURCE_BATCH_CHECKPOINT_WORKFLOW.md`](../../SOURCE_BATCH_CHECKPOINT_WORKFLOW.md). A five-scan batch is processed as three separately committed checkpoints:

1. **T1 — direct transcription / canonical records** → synchronize controls → commit;
2. **T2 — independent historical-glyph re-read** → synchronize controls → commit;
3. **T3 — final source-fidelity closure** → synchronize controls → commit;
4. only after T3 may the next batch begin.

Crops/enhancements are created only for genuinely uncertain readings.

## Completed checkpoint — scans 6–10 / T1

- five canonical page records created under `pages/`;
- printed-page visibility preserved exactly: scan 6 `null`; scans 7–10 show **2, 3, 4, 5**;
- scan 6 title illustration documented separately from narrative;
- physical joins preserved without moving text:
  - 7→8 `நடந்` / `தேறின.`;
  - 8→9 `அபிநய` / `அசைவுகளை...`;
  - 9→10 `...வைத்தியரை அழைத்து` / `வந்துவிடுகிறேன்”...`;
- all five pages remain `needs-review` because T2 and T3 have not yet passed.

Checkpoint record: [`T1_BATCH_006_010.md`](T1_BATCH_006_010.md).

## Exact next activity

**T2 for physical scans 6–10 only.**

Independently re-read all five scans under `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, explicitly check the full known sensitive-family set, correct only source-supported character identity, record any corrections/unresolved glyphs, synchronize controls and commit. Stop before T3 and do not begin scan 11.
