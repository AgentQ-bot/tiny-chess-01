# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/AgentQ-bot/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/AgentQ-bot/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, alpha-beta with transposition table, quiescence search, null-move pruning and late-move reductions, fixed node budget, fully deterministic. It plays the house gauntlet through the make.fun env.

## Submitted version

History heuristic + LMR (reduce-3) on the classic material + piece-square eval, fixed 30,000-node budget per iteration. Local official-scorer grade: mean Elo 1307 over 18 games (9W/1D/8L), packed `main.py` 3,766 bytes. Perft verified against python-chess references.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=n987ngnf&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
