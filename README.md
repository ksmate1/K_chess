# K_Chess

A chess library written in Python and made for fun.

K_Chess is a custom-built chess library written entirely from scratch in Python.

The goal of the project is to implement the complete rules of chess in a clean, simple, and understandable way while keeping the code easy to read, maintain, and learn from.

Feel free to explore the code, modify it, and use it as a learning resource.

## Features

### Implemented

- Chess board representation
- Standard chess starting position
- Piece objects
- Turn tracking

### In Progress

- Legal move generation
- Move validation
- Check detection
- Checkmate detection

### Planned

- Castling
- En passant
- Pawn promotion
- Stalemate detection
- Threefold repetition
- Fifty-move rule
- FEN support
- PGN support

## Example

```python
from k_chess.game import Game
from k_chess.move import Move

game = Game()

game.board.move(Move("e2", "e4"))

print(game.board)

if game.is_check():
    print("Check!")
```

## Current Status

🚧 Work in progress.

K_Chess is currently under active development and is not feature complete.

## Author

Created by **K-S-mate1**
``
