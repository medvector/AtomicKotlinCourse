## Interfaces (#1)

The `MazeImpl` class implements the `Maze` interface. It stores game elements
in a "table" of the size `height * width`, which is implemented as a `List` of
`List`s, where the outer `List` is of `height` size and each inner `List` is of
`width` size. Each cell holds a set of `GameElement`s. `MazeImpl` also keeps a
record of the `Cell`s of all the elements by storing a `cellMap` `Map`
which has `GameElement` keys and `Cell` values.

Your task is to implement the `add(GameElement, Cell)` and
`remove(GameElement, Cell)` functions that add and remove `GameElement`s
at a given `Cell`.