# tiny-chess-01

A compact deterministic Python chess engine for make.fun. It uses a 0x88 board; alpha-beta search with a transposition table, killer moves, and a history heuristic; quiescence; and search-time repetition detection.

The engine uses a fixed 30,000-node budget per move and an environment HTTP driver. Legal move generation covers promotions, castling, and en passant; terminal search recognizes checkmate and stalemate. `main.py` is an LZMA-compressed engine payload with its standard-library unpacker.
