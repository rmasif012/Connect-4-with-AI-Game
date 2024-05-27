# Connect 4 Game with AI

Welcome to the Connect 4 Game with AI! This repository contains the code for a Connect 4 game where you can play against an AI opponent. The AI uses the Minimax algorithm with alpha-beta pruning to make its moves. The game is built using Python and the Pygame library for the graphical interface.

## Features

- **Single Player Mode:** Play against the AI.
- **AI Opponent:** The AI uses Minimax algorithm with alpha-beta pruning for optimized moves.
- **Graphical Interface:** Built with Pygame for an interactive gaming experience.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/connect4-ai.git
   cd connect4-ai
   ```

2. **Install dependencies:**
   Make sure you have Python installed. Install the required packages using pip:
   ```sh
   pip install numpy pygame
   ```

## How to Play

1. **Run the game:**
   ```sh
   python connect4.py
   ```

2. **Gameplay:**
   - The game window will open, and you'll see the Connect 4 board.
   - Player 1 (human) uses the red discs, and the AI uses the yellow discs.
   - On your turn, move the mouse to position your disc and click to drop it into the desired column.
   - The game will alternate turns between you and the AI until there is a winner or the board is full.

## Code Overview

### Main Functions

- **create_board():** Initializes the game board.
- **drop_piece(board, row, col, piece):** Drops a piece into the specified column.
- **is_valid_location(board, col):** Checks if a column is a valid move.
- **get_next_open_row(board, col):** Finds the next open row in a column.
- **winning_move(board, piece):** Checks if the current move is a winning move.
- **score_position(board, piece):** Evaluates the board and scores it for the AI.
- **minimax(board, depth, alpha, beta, maximizingPlayer):** Implements the Minimax algorithm with alpha-beta pruning.
- **get_valid_locations(board):** Returns a list of valid columns for the next move.
- **pick_best_move(board, piece):** Chooses the best move for the AI based on the current board state.
- **draw_board(board):** Draws the board using Pygame.

### Game Loop

The game loop handles user inputs, updates the board, and alternates turns between the player and the AI. It also checks for win conditions and updates the display accordingly.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgements

- This project uses the Pygame library for the graphical interface.
- The AI algorithm is based on the Minimax algorithm with alpha-beta pruning.

## Contact

If you have any questions or feedback, feel free to reach out to asifrm364@gmail.com.

Enjoy the game!

