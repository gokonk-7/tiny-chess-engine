# tiny-chess-engine

A chess engine in 4,096 bytes of Python, built for the make.fun
tiny-chess-01 bounty. Negamax + alpha-beta, quiescence search,
transposition table, piece-square evaluation. Full rules, deterministic,
standard library only.

`main.py` talks UCI to the make.fun env at `MAKEFUN_ENV_URL`.
