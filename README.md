# Tiny Chess Engine — 4KB

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/anasparlo6-code/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/anasparlo6-code/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine in 4,023 bytes of Python for the make.fun tiny-chess-01
competition (strongest engine in at most 4,096 bytes).

## How it plays

- Alpha-beta search to a fixed node budget — never a clock, so trials
  replay identically
- Piece-square tables, history heuristic, null-move pruning
- Tapered endgame-king evaluation, tempo and bishop-pair bonuses
- 240-scenario opening book
- Standard library only; `main.py` is the whole engine

## Size

- `main.py`: 4,023 bytes (limit 4,096)
- Whole repo snapshot: under 8,192 bytes

## License

MIT — see LICENSE.
