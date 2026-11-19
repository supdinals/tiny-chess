# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/supdinals/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/supdinals/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 negamax with transposition table,
quiescence (with its own in-check evasion search), null-move pruning and
late-move reductions, and a tapered eval (material, PSTs, king safety,
bishop pair, passed/doubled pawns, endgame mop-up).
`main.py` is the whole engine: the readable source, lzma-packed with the
make.fun kit's `compress` into a stdlib-only entrypoint under the 4 KB cap.
