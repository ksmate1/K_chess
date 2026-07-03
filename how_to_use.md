# How to Use K_Chess

## KMN

### What is KMN?

KMN (**K_Chess Move Notation**) is the move notation used by K_Chess.

It is a simple notation created for K_Chess and is primarily intended for projects developed by **K-S-mate1**.

### Syntax

A move is written using a start square and an end square:

```python
Move("e2", "e4", MOVE_NOTATION)
```

### Example

```python
from k_chess.game import Game
from k_chess.move import Move
from k_chess.values import *

game = Game()

game.board.move(
    Move("e2", "e4", MOVE_NOTATION)
)
```

### How KMN Works

The first argument is the starting square:

```text
e2
```

The second argument is the destination square:

```text
e4
```

Example:

```python
Move("g1", "f3", MOVE_NOTATION)
```

which represents the move:

```text
Knight from g1 to f3
```
``
