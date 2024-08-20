# The_Labyrinth

A console-based maze game implemented in C. Navigate through a dynamically generated maze using keyboard inputs and avoid obstacles to reach the exit.

## Features

- **Player Movement**: Move up, down, left, or right using 'W', 'A', 'S', and 'D' keys. Move four blocks at a time with the spacebar.
- **Obstacle Avoidance**: Avoid obstacles marked by '#' symbols.
- **Win Condition**: Reach the exit marked by the 'O' symbol to win the game.
- **Game Over**: The game ends if you collide with an obstacle.

## Gameplay

```bash
  L         A     BBBBB  Y   Y  RRRR   I  N   N  TTTTT  H   H 
  L        A A    B   B   Y Y   R   R  I  NN  N    T    H   H 
  L       AAAAA   BBBBB    Y    RRRR   I  N N N    T    HHHHH
  L      A     A  B   B    Y    R   R  I  N  NN    T    H   H
  LLLLL A       A BBBBB    Y    R   R  I  N   N    T    H   H

      EEEEE  X   X  PPPP  L      OOO   RRRR   EEEEE  RRRR
      E       X X   P   P L     O   O  R   R  E      R   R
      EEEE     X    PPPP  L     O   O  RRRR   EEEE   RRRR
      E       X X   P     L     O   O  R   R  E      R   R
      EEEEE  X   X  P     LLLLL  OOO   R   R  EEEEE  R   R
```

## How to Play

1. **Start the Game**: Choose '1' from the menu to start a new game.
2. **Move the Player**: Use 'W', 'A', 'S', 'D' for movement, and the spacebar to move four blocks.
3. **Avoid Obstacles**: Navigate around '#' symbols to prevent collisions.
4. **Reach the Exit**: Find and reach the 'O' to win.

## Usage

1. **Compilation**: Compile the program using a C compiler like GCC:
    ```bash
    gcc Laby.c Laby.h -o maze_game
    ```
2. **Execution**: Run the compiled program:
    ```bash
    ./maze_game
    ```

## Files

- `Laby.c`: Contains the main game logic and loop.
- `Laby.h`: Header file with function prototypes and constants for player movement.

## Notes

- Adjust `Maze_Size` and `Maze_width` constants to change the maze dimensions.
- For Unix-like systems, replace `system("cls")` with `printf("\033[2J \033[H")` to clear the screen.

## Contributing

Contributions are welcome! Please submit pull requests to improve the game.

## Contact

- Email: [akshichaudhary.16@gmail.com](mailto:akshichaudhary.16@gmail.com)
- GitHub: [GitHub Profile](https://github.com/Aksh2908)
