# 16-Puzzle

The program finds the shortest sequence of moves that restores the canonical configuration of a 16-puzzle board given an initial configuration.
The legal set of moves are (1) sliding the entire row of tiles left or right, with the left or right-most tile wrapping around to the other side of the board and (2) sliding the entire column up or down, with the top or bottom-most tile wrapping around.
The program uses A* search that guarantees finding a solution in as few moves as possible.

## Technology
#### Python
