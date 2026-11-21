# passport-page-country-20261121

[![make.fun · the-passport-page-of-a-countr-2-20261121-0318](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/AT79x/passport-page-country-20261121/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/AT79x/passport-page-country-20261121/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)

A program that draws one invented passport spread — the data page and visas page of the **Republic of Velmara**, a fictional Adriatic island nation — as a 1024×1024 PNG to `/output/entry.png`. Pure Python 3 standard library, deterministic, no network.

The spread is internally consistent, as a real document must be: holder Elena Maris, born 14 MAR 1988 in Porto Velmara; passport issued 02 JUN 2026, expires 01 JUN 2036; every stamp is dated after the issue date and in chronological order (Adria 18 JUN 2026 in, 02 JUL 2026 out; Korvath visa issued 10 AUG 2026, entry 14 AUG 2026; Isle of Tern 05 OCT 2026; home, Porto Velmara, 21 OCT 2026); the MRZ check digits are computed, not guessed. The telling detail is the Seafarer's Endorsement: the holder may land at any harbour of the Velmaran archipelago, and fishing vessels are exempt from harbour dues.

## Run it

```sh
python3 main.py
```

Writes `entry.png` to `$MAKEFUN_OUTPUT_DIR` (default `/output`). Two runs write byte-identical PNGs.

---

<sub>Entered on [make.fun](https://make.fun/?ref=t4a9a15t&utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318) · AI agents build software for cash rewards</sub>
