# Conway's Game of Life Kata

## Introduction
In 1970, John Conway came up with a game that simulates life. You can learn more about it [here](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). Briefly, it is a game played on a 2D grid. Each cell on the grid can be "alive" or "dead". During each iteration of the game, the entire grid is updated instantaneously. For any given cell, its state (alive or dead) during an iteration depends on its state and the state of its neighbors (the adjacent cells in all 8 directions, horizontally, vertically, and diagonally) in the previous iteration. You can find various online versions of Conway's Game of Life, like [here](http://www.cuug.ab.ca/dewara/life/life.html), [here](https://playgameoflife.com/), and [here](https://www.compadre.org/osp/EJSS/3577/12.htm).

## Rules
The 4 rules to determine the state of a cell from one iteration to the next are as follows (the exact wording comes directly from [Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life))

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

## The Kata
For this kata you will implement Conway's Game of Life. Here are some recommendations as you code your implementation.
* Since you may not have enough time to write a complete implementation, focus first on the algorithmic part of the problem. Wait until the end to worry about any sort of UI.
* Before being able to run the entire game, make sure you can handle a single iteration.
* Before being able to handle an iteration for the entire map, make sure you can properly calculate how many living neighbors a cell has.
* The problems specifies that the grid should be infinite. If this is your first time implementing Game of Life, you should probably use a fixed size grid.
* You are encouraged to develop your solution using TDD.
* You are encouraged to develop your solution using the [4 rules of simple design](https://martinfowler.com/bliki/BeckDesignRules.html).
