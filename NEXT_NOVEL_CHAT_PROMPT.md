# Next Chat Prompt — சுருளிமலை / terminal-boundary intake audit

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/surulimalai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064107_சுருளிமலை_1968 2.pdf`

Source intake state:

- title: **சுருளிமலை**;
- author: **கலைஞர் மு. கருணாநிதி**;
- publisher: **திராவிடப்பண்ணை**;
- edition: **இரண்டாம் பதிப்பு — 1968**;
- size: **268,529,598 bytes**;
- physical scans: **150**;
- SHA-256: **PENDING**;
- source PDF committed: **No**;
- image-only source.

Front matter scans **1–4** are already **VERIFIED** and recorded. Scan **5** is the source-visible body opening but body T1 has not started.

## Mandatory startup

Read:

- root `NOVEL_PROCESSING_GUIDE.md`;
- root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
- root `HANDOVER.md`;
- `works/surulimalai/README.md`;
- `works/surulimalai/metadata/source.md`;
- `works/surulimalai/indexes/page-map.md`.

## Exact next activity

Perform a **direct visual terminal-boundary audit of scans 145–150**.

Determine, only from source pixels:

- which scans remain narrative body;
- where the story visibly ends;
- whether any publisher advertisement/back matter follows;
- visible printed-page numbers, if any;
- illustrations / blank areas / later marks;
- any cross-page continuation at the terminal boundary.

Do not infer the ending from scan count or expected page numbering.

Also compute and register the SHA-256 if the runtime permits.

After the boundary is source-confirmed, update the page map and controls, commit, and set the next bounded task to **T1 scans 5–9** (or another equally small first body batch if source structure requires it).
