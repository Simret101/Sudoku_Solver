# Documentation for Sudoku Algorithm Game

## Overview

The **Sudoku Algorithm Game** is a Python-based application that allows users to interact with a Sudoku puzzle solver. The game features an algorithm that solves Sudoku puzzles using backtracking, and it provides an interactive console interface for users to play Sudoku or generate new puzzles. 

For more information about Sudoku and the solving algorithm, refer to this article: [Sudoku Backtracking - GeeksforGeeks](https://www.geeksforgeeks.org/sudoku-backtracking-7/).

---

## Features

- **Sudoku Puzzle Generation**: Automatically generates random Sudoku puzzles of varying difficulty levels.
- **Puzzle Solver**: Uses the backtracking algorithm to solve any valid Sudoku puzzle.
- **Interactive Console Interface**: Users can input their solutions and check if they match the algorithm’s solution.
- **Difficulty Levels**: Choose from easy, medium, and hard levels to test different solving skills.
- **Timer**: Tracks the time taken to solve the puzzle.
- **Reset and Restart**: Allows users to reset or restart a new puzzle.

---

## Algorithm

The Sudoku puzzle is solved using the **Backtracking Algorithm**, which works as follows:

1. **Empty Cell Identification**: Search for an empty cell in the Sudoku grid.
2. **Value Assignment**: Try assigning a value (1-9) to the empty cell.
3. **Validation**: Ensure that the value does not violate Sudoku rules — it should not already exist in the current row, column, or 3x3 grid.
4. **Recursive Solving**: If the value is valid, recursively try to solve the next empty cell.
5. **Backtrack**: If a conflict arises (i.e., no valid values can be assigned), backtrack and try a different value for the previous cells.
6. **Completion**: The algorithm completes when all cells are filled in without conflicts.

The algorithm stops and provides a solution when the entire puzzle is solved.

---

## Game Interface

### 1. **Grid Representation**
   - The Sudoku puzzle is represented as a 9x9 grid, where users can input their guesses for empty cells.
   - Users interact with the grid through the console interface.

### 2. **Commands and Controls**
   - **Solve**: Solves the current puzzle using the backtracking algorithm.
   - **Clear**: Clears all inputs on the grid.
   - **New Puzzle**: Generates a new random puzzle with a selected difficulty level.
   - **Reset**: Resets the puzzle, keeping the current state.
   - **Timer**: Displays the time elapsed since the user started the puzzle.

---

## Technologies Used

- **Programming Language**: Python 3.x
- **Algorithm**: Backtracking algorithm for solving Sudoku puzzles.
- **CLI Interface**: The game uses a simple command-line interface (CLI) for interaction.

---

## Installation

### Prerequisites

1. **Python 3.x**: Ensure that Python is installed on your machine. You can check this by running the following command:

   ```bash
   python --version
   ```

2. **Dependencies**: This project does not require any additional dependencies. However, if you want to use extra features like logging or timing, you may need to install Python libraries.

---

### Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/YourUsername/Sudoku-Algorithm-Game.git
cd Sudoku-Algorithm-Game
```

### Running the Game

To run the game, simply execute the `sudoku_game.py` file:

```bash
python sudoku_game.py
```

This will start the Sudoku Algorithm Game in your terminal.

---

## How to Play

1. **Choose Difficulty**: The game will present you with a Sudoku puzzle of a random difficulty level.
2. **Start Solving**: Input your guesses for empty cells by typing numbers (1-9) and pressing Enter.
3. **Solve**: Type `solve` to let the algorithm solve the puzzle for you.
4. **New Puzzle**: Type `new` to generate a new puzzle with a different difficulty.
5. **Clear or Restart**: Type `clear` to clear your inputs or `reset` to reset the puzzle.

---

## Troubleshooting

If you run into any issues while running the game:

1. **Game not loading**: Ensure that Python is installed and that you're running the correct command (`python sudoku_game.py`).
2. **Solver not working**: Make sure that the puzzle you're inputting is solvable.

---

## Contributing

Contributions to the Sudoku Algorithm Game are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature or fix"
   ```
4. Push your changes to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request to merge your changes into the main repository.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

