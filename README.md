# Tic Tac Toe - Java Console Game

This is a simple console-based **Tic Tac Toe** game implemented in Java. It allows two players to take turns marking spaces on a 3×3 grid until one wins or the game ends in a draw.

## 🕹️ Features

- Two-player mode (`X` and `O`)
- Input validation for illegal moves
- Win detection for rows, columns, and diagonals
- Simple and clean text-based UI in the console

Main.java->
All the logic and UI are contained in a single Java file.

## 🚀 How to Run

### Prerequisites

- Java Development Kit (JDK) installed
- A terminal or IDE (like IntelliJ IDEA, Eclipse, or VS Code with Java support)

### Steps

1. Clone this repository or copy the `Main.java` file.
2. Open a terminal and navigate to the directory containing `Main.java`.
3. Compile the program:

```bash
javac Main.java

How to run-> 
java Main

🎮 How to Play
1) The game prompts each player to enter the row and column (from 0 to 2) where they want to place their mark.
2) Example input: 1 2 (places a mark on row 1, column 2)
3) The board updates after each move.
4) If a player wins, the game announces the winner.
5) If an invalid move is attempted (e.g., cell already occupied), it will prompt the player to try again.

