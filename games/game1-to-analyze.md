This is a game which Stockfish Destroys Scorpio in a Computer Chess Championship match from chess.com
The video covering this game: https://www.youtube.com/watch?v=Z7thaDGVCWw  
The PGN below was generated from someone in the comments commenting on the video.

```
[White "Stockfish"]
[Black "Scorpio"]
[Result "1-0"]
[ECO "B01"]
[Opening "Scandinavian Defense: Marshall Variation"]
[Termination "Normal"]

1. e4 d5 { Stockfish 12 evaluates this move with +0.7, so it doesn't like the
Scandinavian at all}  2. exd5 Nf6 3. d4 Nxd5 4. Nf3 Bf5 5. Bd3 Bxd3 6. Qxd3 e6
7. O-O c5 $6 $16 { +1.1}  ( 7... c6 $14)8. Bg5 Qd7 $6 $16 ( 8... f6 $14)9. Nc3
f6 10. Be3 Nxc3 11. Qxc3 cxd4 12. Nxd4 e5 13. Rad1 exd4 $2 $18 { +3.5}  ( 13...
Na6 { is still better for white, but may allow black to play Be7 at some point}
 14. Nb3 Qc8 { +2.1}  )14. Bxd4 Nc6 15. Bxf6 Qf5 { +4.6}  ( 15... gxf6 { is
also playable}  16. Rxd7 Kxd7 17. Qxf6 Be7 18. Rd1+ Kc7 { +4.4}  )16. Rfe1+ Kf7
17. Re3 gxf6 18. Qc4+ Kg6 19. Rg3+ Kh5 { mate in 13}  ( 19... Qg5 { is the only
way to prevent forced mate}  20. Rxg5+ fxg5 { +5.6}  )20. Qf7+ Kh4 { mate in 6}
 ( 20... Qg6 { leads to the longest line}  21. Rh3+ Kg5 22. f4+ Kxf4 23. Qc4+
Qe4 24. Rh4+ Kg5 25. Qxe4 h5 26. Rf1 Bc5+ 27. Kh1 Bf2 28. Rxf2 Ne5 29. Qf5+ Kh6
30. Rxh5+ Kg7 31. Qxf6+ Kg8 32. Rxh8# )21. Rh3+ Kg4 ( 21... Qxh3 22. Qxf6+ Kh5
23. Rd5+ Ne5 24. Rxe5+ Qf5 25. Rxf5+ Kg4 26. h3# )22. f3+ Kf4 23. Rh4+ Ke3 24.
Qc4 Bc5 25. Re4+ ( 25. Qe4+ Qxe4 26. Rxe4# )25... Qxe4 26. Qxe4#
```

Same PGN but without sidelines nor annotations:

```
[White "Stockfish"]
[Black "Scorpio"]
[Result "1-0"]
[ECO "B01"]
[Opening "Scandinavian Defense: Marshall Variation"]
[Termination "Normal"]

1. e4 d5
2. exd5 Nf6
3. d4 Nxd5
4. Nf3 Bf5
5. Bd3 Bxd3
6. Qxd3 e6
7. O-O c5
8. Bg5 Qd7
9. Nc3 f6
10. Be3 Nxc3
11. Qxc3 cxd4
12. Nxd4 e5
13. Rad1 exd4
14. Bxd4 Nc6
15. Bxf6 Qf5
16. Rfe1+ Kf7
17. Re3 gxf6
18. Qc4+ Kg6
19. Rg3+ Kh5
20. Qf7+ Kh4
21. Rh3+ Kg4
22. f3+ Kf4
23. Rh4+ Ke3
24. Qc4 Bc5
25. Re4+ Qxe4
26. Qxe4#
```


Todo: Find the last bad move that was made which, given perfect play from both sides, would have changed the result of the game.  
Then with the adjusted move, try to prove it's perfect play by having multiple engines try to break the assumption that it is perfect play.
Then try to find the next last bad move from either side, etc...
