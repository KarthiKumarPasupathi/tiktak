# Tic-Tac-Toe Game

A simple command-line Tic-Tac-Toe game implemented in Java. The game supports two players taking turns to make their moves until one player wins or the board is full.

---

## Features

- **Two-player Mode**:
  - Players take turns making moves.
  - Supports `X` and `O` as player markers.

- **Game Logic**:
  - Detects when a player has won (rows, columns, or diagonals).
  - Prevents invalid moves (e.g., attempting to place a marker on an already occupied space).

- **Game Board**:
  - A 3x3 grid displayed after each move.

---

## How to Play
1. Run the program.
2. Players are prompted to enter their move by specifying the row and column indices (0, 1, or 2).
3. The program checks for winning conditions after each move.
4. The game ends when:
   - One player wins.
   - The board is full, resulting in a draw.

---

## Project Structure

### Main Class
The main class contains the following methods:

1. **`main`**:
   - Initializes the game board.
   - Handles player turns and game flow.

2. **`printBoard`**:
   - Prints the current state of the board.
   - Example board output:
     ```
     X | O | X |
     O | X |   |
       |   |   |
     ```

3. **`haveWon`**:
   - Checks if the current player has won by evaluating rows, columns, and diagonals.

4. **`board`**:
   - A 2D array representing the Tic-Tac-Toe board.

---

## Technologies Used
- **Java**: Core programming language.
- **Scanner**: For reading player input from the console.

---

## How to Run

### Prerequisites
- Install Java Development Kit (JDK).

### Steps
1. Save the code in a file named `TicTacToe.java`.
2. Compile the program:
   ```bash
   javac TicTacToe.java
   ```
3. Run the program:
   ```bash
   java TicTacToe
   ```

---

## Future Enhancements
- **AI Player**:
  - Add a single-player mode with an AI opponent.

- **Graphical Interface**:
  - Create a GUI using JavaFX or Swing.

- **Dynamic Board Size**:
  - Allow different board sizes (e.g., 4x4 or 5x5).

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Author
**Your Name**
- GitHub: [KarthiKumarPasupathi](https://github.com/KarthiKumarPasupathi)
- Email: Karthikumarpasupathi@gmail.com

---

### Have fun playing Tic-Tac-Toe!
