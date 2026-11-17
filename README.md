# Knight Owl

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Tenguu0/knight-owl/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Tenguu0/knight-owl/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python for the [make.fun](https://make.fun/bounty/tiny-chess-01) tiny-chess-01 bounty. It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`.

## Engine

`main.py` is the whole engine: bitboards, PVS + iterative deepening to a fixed node budget, null-move pruning, quiescence search, transposition table, history heuristic, and an evaluation with material, formula piece-square terms, pawn structure, king shield and bishop pair. Deterministic: no clock, no unseeded randomness.

## License

MIT — see [LICENSE](LICENSE).
