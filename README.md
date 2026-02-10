# PGN Fixer

Fix your chess PGNs' erroneous, ambiguous, and missing moves with this handy tool!
Paste your PGN into the `Original PGN` box and hit `Load PGN`. When erroneous moves are found, the tool will wait for you to play the correct move, then continue until there are no more erroneous/ambiguous moves.


## Example PGN

```
[Event "Broken PGN Example"]
[White "Alice"]
[Black "Bob"]
[Result "*"]

1. e4 e5 2. Nf3 Nc6 3. Bc4 Bc5 4. d3 Nf6 5. O-O O-O 6. Bg5 h6 7. Bh4 g5 8. Bg3 Nh5 9. Nd2 *
```

This PGN is broken because `9. Nd2` does not specify which knight is moved, as both of White's knights can move to the same spot.
When you load this, the position will be loaded up until this error, and you will have the opportunity to specify which knight you wanted to move by moving one on the chess board.
