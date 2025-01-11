# Advanced Chess Program

## Overview
This project is a command-line chess game written in C. It supports basic chess functionalities, including piece movement, board display, and turn management. The program allows two players to play chess in an interactive way with input in standard chess notation (e.g., `e2 e4`).

## Features
- **Board Initialization**: Sets up the chessboard with all pieces in their standard starting positions.
- **Move Validation**: Includes basic move validation for pawns. Rules for other pieces can be extended.
- **Turn Management**: Alternates turns between White and Black players.
- **Check/Checkmate**: Placeholder functions are included for future implementation.
- **User-Friendly Input**: Moves are entered in algebraic notation (e.g., `e2 e4`).

## How to Use
1. Clone or download the repository.
2. Compile the program using a C compiler, such as GCC:
   ```
   gcc chess.c -o chess
   ```
3. Run the executable:
   ```
   ./chess
   ```
4. Enter your moves in standard chess notation. For example, to move a pawn from e2 to e4, input:
   ```
   e2 e4
   ```

## Game Rules
- The game starts with White's turn.
- Each move should be entered in the format: `<from> <to>`. For example:
  - `e2 e4` to move the piece at e2 to e4.
- Invalid moves will be rejected with a prompt to try again.

## File Structure
- **chess.c**: The main C file containing the chess game logic.

## Future Improvements
- Implement advanced move validation for all chess pieces.
- Add support for special moves like castling, en passant, and pawn promotion.
- Integrate a check/checkmate detection algorithm.
- Enhance the user interface.

## Example Gameplay
```plaintext
Welcome to Advanced Chess!

   a b c d e f g h
  +-----------------+
8 | r n b q k b n r |
7 | p p p p p p p p |
6 | . . . . . . . . |
5 | . . . . . . . . |
4 | . . . . . . . . |
3 | . . . . . . . . |
2 | P P P P P P P P |
1 | R N B Q K B N R |
  +-----------------+

White's turn (e.g., e2 e4):
```

## Requirements
- A C compiler (e.g., GCC).
- Basic understanding of chess.

## Contributing
Feel free to fork this repository and contribute by submitting pull requests. Suggestions and feature requests are welcome!

## License
This project is licensed under the MIT License.

---
Enjoy playing chess!

