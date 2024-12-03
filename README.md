This Python project creates an interactive Connect 4 game where the user plays against an AI. It uses the Pygame library for graphical user interface (GUI) and NumPy for board data manipulation. The game board consists of a 6x7 grid, and the objective is to connect four discs of the same color in a row, column, or diagonal.

# Key Features and Functionalities:

Board Setup:

The game board is represented as a 6x7 grid, with each cell either empty, filled with the player's piece (red), or the AI's piece (yellow).
The board is displayed using Pygame, and pieces are dropped in columns based on user clicks.
User vs AI:

The player controls a red piece, while the AI plays with a yellow piece.
The player chooses columns to drop their pieces, and the AI chooses its move using the Minimax algorithm with alpha-beta pruning.
Minimax Algorithm:

The AI uses the Minimax algorithm for decision-making, which evaluates all possible moves to select the optimal column to place its piece.
The algorithm is enhanced with alpha-beta pruning for efficiency.
Winning Condition:

The game checks for a win after each move by scanning horizontally, vertically, and diagonally for a line of four consecutive pieces of the same color.
Game Flow:

The game alternates turns between the player and the AI.
When a player wins, a message is displayed, and the game ends. The winner is determined based on the first player to align four pieces in a row.
Graphics and Display:

Pygame is used to visually represent the board and animate the placement of pieces.
The grid is drawn, and the pieces are represented as circles in red or yellow.
Game Over and Restart:

After a win or a draw (no valid moves left), the game announces the result and waits for a brief moment before resetting for a new game.
# Technologies Used:

Programming Language: Python
Libraries:
Pygame for game graphics and UI
NumPy for board data manipulation
Math for game logic and calculations (e.g., Minimax)
# Applications: 
This project is a fun implementation of the Connect 4 game that combines basic game mechanics with AI decision-making. It can be extended for educational purposes to teach algorithms like Minimax and is a great introductory project for those learning AI and game development.

