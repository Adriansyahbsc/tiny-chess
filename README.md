# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/adriansyahbsc/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/adriansyahbsc/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 3,025 bytes of Python. Negamax search with alpha-beta pruning, quiescence, a transposition table and piece-square tables at a fixed 50,000-node budget per move — every move derived from the position alone, no clock, fully deterministic. `main.py` is the readable source packed with the kit's `makefun compress` (LZMA); it speaks the make.fun env protocol (`POST /game`, `/move`) and nothing else. Kit practice trial (real env + scorer): Elo 1,279 — above the 1,154 floor for the final.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:<port> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kj9js265&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
