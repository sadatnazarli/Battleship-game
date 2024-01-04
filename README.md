# Battleship Game

This is a simple console-based implementation of the classic Battleship game in C++. The game is played on a 4x4 grid, and the player's objective is to sink all four hidden ships by strategically guessing their locations.

## How to Play

1. Compile the C++ code using your preferred compiler.

2. Run the compiled executable.

3. The game will prompt you to enter row and column coordinates to target a cell on the 4x4 grid.

4. If a ship is present at the chosen coordinates, it's a hit, and the ship is "sunk" by setting the corresponding grid value to zero.

5. Continue guessing until all four ships are sunk.

6. The game will display a victory message along with the number of turns it took to win.

## Code Structure

- The main logic of the game is implemented in the `main` function.

- The game uses a 4x4 array (`ships`) to represent the ocean with hidden ships.

- The player's hits and the number of turns taken are tracked with the `hits` and `numberOfTurns` variables.

- The game continues in a loop until all four ships are sunk.

## How to Compile

Use a C++ compiler to compile the source code. For example:

```bash
g++ battleship.cpp -o battleship
