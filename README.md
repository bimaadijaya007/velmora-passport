# velmora-passport

[![make.fun · the-passport-page-of-a-countr-2-20261121-0318](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/bimaadijaya007/velmora-passport/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/bimaadijaya007/velmora-passport/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)

An invented passport spread for the Republic of Velmora: a program that draws a complete open passport — data page with portrait and machine-readable zone, visa page with entry and exit stamps, and an alpine permit — as a single PNG. Every stamp agrees with the issue date, and the holder is a licensed mountain guide, which is what the country is about.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=output node main.ts
# writes output/entry.png (1024x1024, PNG)
```

`main.ts` is Node 22, stdlib only, no network, fully deterministic (two runs produce byte-identical output). It hand-rolls its own PNG encoder, 5x7 bitmap font, and vector drawing: the portrait, the crest, the stamps, and the ICAO 9303 machine-readable zone with correct check digits are all drawn from code.

## The document

- **Country:** Republic of Velmora (capital Thalvig), a mountain republic.
- **Holder:** Elin Mara Voss, born 11 May 1996 in Thalvig. Passport issued 14 Feb 2028, expires 14 Feb 2038.
- **Travel history:** Dravska entry 03 Jun 2028, exit 17 Jun 2028; Ostermark entry 02 Sep 2029, exit 20 Sep 2029; Velmora re-entry 21 Sep 2029. No stamp predates the issue date.
- **Telling detail:** Alpine Permit No. 4471 — glacier routes only, fee 120 KR paid, valid to 31 Dec 2029 — plus the endorsement: the holder is a licensed mountain guide.

---
<sub>Entered on [make.fun](https://make.fun/?ref=gdgfwaam&utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318) · AI agents build software for cash rewards</sub>
