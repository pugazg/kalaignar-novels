# Visual-fidelity / backward-integrity audit — புதையல் scans 109–118

Date: 2026-08-28

## Result

**PASSED — 10 / 10 page records verified; unresolved readings in this range: 0.**

Controlling access split:

`TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`

- split pages inspected: **11–20 / 49**
- represented original scans: **109–118**
- visibly printed pages: **107–116**
- comparison baseline: user Iteration 10
- source/split PDF committed to repository: **No**

This batch was reopened because an earlier assistant pass had promoted the pages before completing a reliable native-image audit. Every page was therefore reset to `needs-review` and rechecked against native split-source pixels. Old-form glyphs were not replaced merely from grammar or expectation.

## Source-established results

### Scan 109 / printed 107

- user-confirmed `என்னா பிரதர்!` is retained;
- source prints `துக்கராமாக`, not the earlier assistant `துக்காராமாக`;
- source prints joined `பாழாய்ப்போன`;
- source prints `திறமை யில்லேன்னு` with the visible separation.

### Scan 110 / printed 108

- user-confirmed `போய்ட்டு வர்ரேன்` is retained; assistant `போயிட்டு வர்ரேன்` is rejected;
- the printed rule and numeral `12` occur on this scan: chapter 11 closes and chapter 12 begins.

### Scan 111 / printed 109

- source prints `நான் இருக்கிறது மருங்கப்பள்ளம்!`; the assistant proposal `மருங்கப்பள்ளம்தான்` is withdrawn;
- the page ends inside `எத்தகைய` at `எத்த`.

### Scan 112 / printed 110

- opening `கைய` completes scan 111's `எத்த`;
- source genuinely prints the standalone `காஷ்—?` line;
- the following line is `என் அனாவசியமா செலவு...`; earlier assistant `என் அவசியமா...` is withdrawn;
- page ends at `அவனுக்கு`.

### Scan 113 / printed 111

- source prints `ஆணு, பெண்ணு?`;
- source prints `இது என் இந்த புதிய கேள்வியைக்...`;
- source prints `தம்பீ!`; the later assistant proposal `தம்பி!` on this page is withdrawn.

### Scan 114 / printed 112

- source prints `காதல் லக்ஷணம்னு`;
- source prints `முன்னேயே`;
- source prints `துக்காராம் பாட்ட ஆரம்பித்து விட்டான்`;
- source prints `பாட்டை ஆரம்பித்து`;
- source prints `பாடிக் கொண்டிருக்கும்`.

### Scan 115 / printed 113

- source prints `போதும் தம்பி போதும்!`, not `தம்பீ`;
- first comparison is `மிஞ்சக் கூடியது` while the following comparison is `மிஞ்சக்கூடியது`;
- page ends at `ஒரு`, continued by scan 116.

### Scan 116 / printed 114

- opening `வாரமாகிறது.` completes scan 115;
- source prints `செத்துப்போயி கூட`;
- source prints separated `நான் தான்`;
- source prints `நல்ல முடிவு தம்பி!`;
- source prints `படித்து விட்டு`.

### Scan 117 / printed 115

- source prints `நம்ப ஊருக்கு`; it is not normalized;
- source prints `பாத்துட்டான்னு சரின்னு சொல்லிடுவான்`, correcting the supplied / earlier canonical `பாத்துட்டான்னா`.

### Scan 118 / printed 116

- source contains the four-star internal scene separator;
- source prints `மருங்கப்பள்ளத்துச் சிவன் கோயிலுக்கு`;
- source prints `வேண்டும் என்று அவசர புத்தி`;
- this is an internal transition within chapter 12, not a chapter ending.

## Physical page-boundary checks

- scan 111 `எத்த` → scan 112 `கைய`, yielding `எத்தகைய`;
- scan 112 `அவனுக்கு` → scan 113 `ஊர் சுற்றிப்...`;
- scan 115 `ஒரு` → scan 116 `வாரமாகிறது.`;
- all other boundaries in scans 109–118 were retained without importing text across physical pages.

## Canonical records

- `../pages/0109-pudhaiyal.md`
- `../pages/0110-pudhaiyal.md`
- `../pages/0111-pudhaiyal.md`
- `../pages/0112-pudhaiyal.md`
- `../pages/0113-pudhaiyal.md`
- `../pages/0114-pudhaiyal.md`
- `../pages/0115-pudhaiyal.md`
- `../pages/0116-pudhaiyal.md`
- `../pages/0117-pudhaiyal.md`
- `../pages/0118-pudhaiyal.md`

All ten records are now `verified` after the backward-integrity native-image pass.

## Remaining integrity gate

Scan **75 / printed page 73** remains `needs-review` because the old glyph sequence in அஞ்சலை's question is still unresolved. The former assistant `போயிடுச்சா?` claim has already been withdrawn and the user's `போய்ட்டுதா?` restored as the working baseline.

Forward transcription remains frozen until scan 75 is resolved.
