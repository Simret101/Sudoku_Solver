# **Sudoku Algorithm Game with Timer and Strikes**
![Sudoku Algorithm Game](https://github.com/Simret101/Sudoku_Solver/blob/main/assets/photo_2025-01-27_16-27-44.jpg).

A simple Sudoku game built using the Pygame library. This game includes an interactive board where users can play Sudoku, with additional features such as a timer and a strike system for errors. The underlying algorithm uses backtracking to solve the Sudoku puzzle.

### **Learn More About Sudoku**
To understand how the Sudoku backtracking algorithm works, you can refer to this [GeeksforGeeks article on Sudoku Backtracking](https://www.geeksforgeeks.org/sudoku-backtracking-7/).

---

## **Features**

- **Sudoku Puzzle**: A grid-based puzzle game where users solve the puzzle by filling in numbers from 1 to 9.
- **Timer**: A countdown timer that tracks how long it takes for the player to solve the puzzle.
- **Strike System**: The game counts errors made by the player and displays the number of strikes (mistakes).
- **Backtracking Algorithm**: The game uses a backtracking algorithm to generate and solve Sudoku puzzles.
- **Graphical Interface**: Built using Pygame, providing an easy-to-use and intuitive graphical interface for solving the puzzle.

---

## **Setup**

### **1. Install Dependencies**

Ensure you have Python installed. Install the necessary dependencies by running the following command:

```bash
pip install pygame
```

### **2. Running the Game**

Clone or download the repository, navigate to the project folder, and then execute the game using:

```bash
python main.py
```

This will launch the game window, where you can begin solving the Sudoku puzzle.

---

## **How It Works**

- **Backtracking Algorithm**: The game generates and solves the puzzle using the backtracking algorithm, a popular method for solving constraint satisfaction problems like Sudoku.
- **Timer**: The countdown timer starts once the game begins, tracking the time the player takes to finish the puzzle.
- **Strike System**: If the player enters an incorrect number in the puzzle, a strike is recorded. The number of strikes is displayed on the screen.
- **Sudoku Board**: The game board is a 9x9 grid, where the player can fill in numbers from 1 to 9. The game interface is created using Pygame's drawing functions.

---

## **Customizing the Game**

- **Adjust Timer**: Modify the `time` variable in the game code to change the countdown timer.
- **Strike System**: You can change the number of allowed mistakes or adjust how the strikes are displayed by modifying the `strikes` variable.
- **Puzzle Difficulty**: The game generates Sudoku puzzles at random. You can modify the difficulty by adjusting the puzzle generation or by pre-setting different grids.
- **Sudoku Generation Algorithm**: You can tweak the backtracking algorithm used for generating puzzles and solving them.

---

## **License**

This project is licensed under the MIT License.

---

Feel free to modify the game, improve the features, and dive deeper into how the backtracking algorithm works for Sudoku puzzles.

