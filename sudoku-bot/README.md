the code provides an algorithm able to solve any valid sudoku scheme inserted from the user.
the user prompts the scheme via cli.
at first, the algo will check if the provided scheme is compatible hence valid.
Then it proceeds to find the corrisponding solution with a recursive approach, with the help of an accessory function which
checks whether the inserted value in unique among cols, recs and subcells (for all istances)
