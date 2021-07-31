# Game_of_life
solving Game of life problem using python
1. Any live cell with fewer than two live neighbors dies, as if by loneliness.
2. Any live cell with more than three live neighbors dies, as if by overcrowding.
3. Any live cell with two or three live neighbors lives, unchanged, to the next generation.
4. Any dead cell with exactly three live neighbors comes to life.
The initial pattern constitutes the 'seed' (randomly placed 500 cells) of the system. The first generation is
created by applying the above rules simultaneously to every cell in the seed — births and deaths happen
simultaneously, and the discrete moment at which this happens is called a tick. (In other words, each
generation is a pure function of the one before.)
