# tiny-chess-01 entry

A chess engine in 4 KB of Python (`main.py`, an LZMA-packed payload).
120-square mailbox board, piece-square tables, iterative-deepening PVS with
a transposition table, quiescence search, null-move pruning, late-move
reductions, killer/history ordering and check extension. Fixed node budget
per move (no clock), so every game replays the same.
