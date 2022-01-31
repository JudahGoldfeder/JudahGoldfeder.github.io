---
title: "Chess Engine in C++"
excerpt: "Powerful Chess engine using modern techniques.[image source](https://www.istockphoto.com/photos/computer-chess)<br/><img src='/images/chess.jpeg'>"


collection: portfolio
---
<br/><img src='/images/chess.jpeg'>

When I was in High School I wrote a Chess Engine, teaching myself how to code along the way, and making extensive use of the excellent [Chess Programming Wiki](https://www.chessprogramming.org/Main_Page).
Aside from learning C++, I developed a pretty complex Chess Engine using start of the art (for 2016) techniques, most of which are still used in top engines like [Stockfish](https://stockfishchess.org/) today. Aside from the basic Alpha-beta search, some fancy chess specific techniques I made us of are:

1. [Capture based move ordering](https://www.chessprogramming.org/Move_Ordering#Captures)
2. [The killer move hueristic](https://www.chessprogramming.org/Killer_Heuristic)
3. [Null move pruning](https://www.chessprogramming.org/Null_Move_Pruning)
4. [Futility pruning](https://www.chessprogramming.org/Futility_Pruning)
5. [Late move reductions](https://www.chessprogramming.org/Late_Move_Reductions)
6. [Quiescence search](https://www.chessprogramming.org/Quiescence_Search)
7. [Magic bitboard move generation](https://www.chessprogramming.org/Magic_Bitboards)
8. [Zobrist Hashing based transposition table](https://www.chessprogramming.org/Zobrist_Hashing)
9. [Principal Variation Search](https://www.chessprogramming.org/Principal_Variation_Search)


For more details, checkout the [github](https://github.com/Jgoldfeder/KingSolomonChessEngine).

