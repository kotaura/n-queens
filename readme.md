# N-Queen Backtracker

![](./images/btconv.tiff)

## 0. About this program

The problem of placing eight chess queens on an 8×8 chessboard so that no two queens threaten each other. Thus, a solution requires that no two queens share the same row, column, or diagonal. The eight queens puzzle is an example of the more general n-queens problem of placing n queens on an n×n chessboard, where solutions exist for all natural numbers n with the exception of n=2 and n=3.

## 1. n

|n|1|2|3|4|5|6|7|8|9|10|11|12|13|14|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Fundamental|1|0|0|1|2|1|6|12|46|92|341|1,787|9,233|45,752|

The eight queens puzzle has 92 distinct solutions. If solutions that differ only by symmetry operations (rotations and reflections) of the board are counted as one, the puzzle has 12 fundamental solutions.

A fundamental solution usually has eight variants (including its original form) obtained by rotating 90, 180, or 270 degrees and then reflecting each of the four rotational variants in a mirror in a fixed position. However, should a solution be equivalent to its own 90 degree rotation (as happens to one solution with five queens on a 5x5 board) that fundamental solution will have only two variants (itself and its reflection). Should a solution be equivalent to its own 180 degree rotation (but not to its 90 degree rotation) it will have four variants (itself, its reflection, its 90 degree rotation and the reflection of that). It is not possible for a solution to be equivalent to its own reflection (except at n=1) because that would require two queens to be facing each other. (For n-queen problem's solution to be equivalent to its own mirror-image solution, the solution needs to be symmetrical by the center of the board either horizontally or vertically. Then, two queens would be facing each other, making it not a solution. ) Of the 12 fundamental solutions to the problem with eight queens on an 8x8 board, exactly one is equal to its own 180 degree rotation, and none are equal to their 90 degree rotation, thus the number of distinct solutions is 11*8 + 1*4 = 92 (where the 8 is derived from four 90-degree rotational positions and their reflections, and the 4 is derived from two 180-degree rotational positions and their reflections).

## 2. Requirement modules
update soon...

## 3. Sample
update soon...

Donate by Bitcoin : 182AK1UUgwNNur2g3h1vaY7b41MDax2C2v

## 日本語
なんか、N-Queens問題というやつです。聞いたとき謎だったのでどういうことか知りたくて。。

Bitcoinでの寄付をお待ちしております : 182AK1UUgwNNur2g3h1vaY7b41MDax2C2v
