# Chess Game

A fully functional chess game built from scratch using HTML, CSS, and vanilla JavaScript. This implementation includes complete chess rules, move validation, check detection, and checkmate functionality.

## Features

- **Complete Chess Rules**: All pieces move according to standard chess rules
- **Turn-Based Gameplay**: Alternating turns between white and black players
- **Move Validation**: Legal move detection for all piece types
- **Check Detection**: Identifies when a king is under attack
- **Checkmate Detection**: Recognizes when the game ends in checkmate
- **Visual Feedback**: Highlighted selected pieces and clear game state messages
- **Responsive Design**: Clean, modern interface with a dark theme

## How to Play

1. Open `index.html` in your web browser
2. White moves first
3. Click on a piece to select it (it will be highlighted in yellow)
4. Click on a valid destination square to move the piece
5. The game enforces all chess rules including:
   - Piece-specific movement patterns
   - Blocking rules for sliding pieces
   - Capture mechanics
   - Check and checkmate conditions

## Game Rules Implemented

### Piece Movement
- **Pawn**: Moves forward one square (two on first move), captures diagonally
- **Rook**: Moves horizontally or vertically any number of squares
- **Knight**: Moves in an L-shape (2 squares in one direction, 1 in perpendicular)
- **Bishop**: Moves diagonally any number of squares
- **Queen**: Combines rook and bishop movement
- **King**: Moves one square in any direction

### Special Rules
- **Check**: When a king is under attack, the player must move to resolve the check
- **Checkmate**: Game ends when a king is in check and cannot escape
- **Turn Enforcement**: Players can only move their own pieces

## Technical Details

- **Language**: HTML5, CSS3, JavaScript (ES6+)
- **Architecture**: Single-file application with embedded styles and scripts
- **Board Representation**: 8x8 2D array storing piece positions
- **Piece Notation**: Unicode chess symbols (♔♕♖♗♘♙ for white, ♚♛♜♝♞♟ for black)
- **Grid Layout**: CSS Grid for the chessboard (60px x 60px squares)

## File Structure

```
Project01/
├── index.html          # Complete game implementation
└── README.md          # This file
```

## Getting Started

No installation required! Simply:

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing chess immediately

## Browser Compatibility

This game works in all modern browsers that support:
- CSS Grid Layout
- ES6 JavaScript features
- Unicode chess symbols

## Future Enhancements

Potential improvements for future versions:
- Castling moves
- En passant captures
- Pawn promotion
- Move history
- Undo/redo functionality
- AI opponent
- Online multiplayer
- Timer functionality
- Sound effects

## Contributing

This project was written entirely from scratch as a learning exercise. Feel free to fork, modify, or suggest improvements!

## License

This project is open source and available under the MIT License.