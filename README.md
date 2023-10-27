# Tic-Tac-Toe Game in Python

This is a simple command-line implementation of the classic Tic-Tac-Toe game using Python. It allows two players to take turns marking the spaces on a 3x3 grid until one player wins or the game ends in a draw.

## Getting Started

### Prerequisites

- Python 3.x (https://www.python.org/downloads/)

### Running the Game

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/tic-tac-toe-python.git
Navigate to the project directory:
bash
Copy code
cd tic-tac-toe-python
Run the game:
bash
Copy code
python tic_tac_toe.py
How to Play
The game is played on a 3x3 grid.
Two players, 'X' and 'O', take turns to place their marks on the grid.
Players input their moves by specifying the row and column (e.g., 1,2 for the first row, second column).
The game ends when one player gets three of their marks in a row, column, or diagonal, or when the grid is full (resulting in a draw).
Features
Simple and intuitive command-line interface.
Validates user inputs to ensure valid moves.
Automatically detects game over conditions (win or draw).
Example Game
sql
Copy code
Welcome to Tic-Tac-Toe!

  1 | 2 | 3
  ---------
  4 | 5 | 6
  ---------
  7 | 8 | 9

Player X, enter your move (row,col): 1,1

  X |   |  
  ---------
    |   |  
  ---------
    |   |  

Player O, enter your move (row,col): 2,2

  X |   |  
  ---------
    | O |  
  ---------
    |   |  

...

Player X wins!

  X |   |  
  ---------
    | O |  
  ---------
    |   |  
Contributing
If you'd like to contribute to this project, please open an issue or fork the repository and submit a pull request.
