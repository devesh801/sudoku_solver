# 🧠 Sudoku Solver (Java)

This project is a **console-based Sudoku solver** written in Java. It uses the **backtracking algorithm** to solve any standard 9x9 Sudoku puzzle with zeros representing empty cells.

---

## 🔧 How It Works

- The solver recursively fills each empty cell by trying numbers 1 to 9.
- It checks whether placing a number is **valid** based on Sudoku rules (row, column, 3x3 box).
- If a number leads to a dead end, it **backtracks** and tries the next number.
- When the board is complete, it prints the solved puzzle.

---

## 📂 Code Highlights

- `solveSudoku()` - the main recursive backtracking function
- `isValid()` - checks if a number can be placed at a given position
- `main()` - contains a sample unsolved Sudoku board and prints the solution

---

## 💻 How to Run

1. Make sure you have Java installed.
2. Save the code in a file named `Sudoku_Solver.java`
3. Compile and run:

```bash
javac Sudoku_Solver.java
java Sudoku_Solver
