# K_Chess

A chess library written in Python and made for fun.

K_Chess is a custom-built chess engine/library written from scratch in Python.

The goal is to implement all standard chess rules in a clean, simple, and understandable way.

## Features

- Chess board representation
- All standard chess pieces
- Legal move generation (in progress)
- Check and checkmate detection (in progress)
- Castling, en passant, and promotion (planned)

## Current Status

🚧 Work in progress.

The project is under active development and not yet feature complete.

## License

All rights reserved.

## Author

Created by **K-S-mate1**

## Example

```python
from k_chess.game import Game
game = Game()

game.move("e2 e4")

print(game.board)

if game.is_check():
  print("Check!")
```
