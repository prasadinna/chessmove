A chessboard comprises a 8x8 grid.  Squares on the board are notated using a letter and a number, where the letter indicates the column (or "file") and the number indicates the row (or "rank").  a1 is located in the bottom left corner, and h8 in the top right:

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   |   |   |   |   |
   ---------------------------------
 4 |   |   |   |   |   |   |   |   |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

Chess pieces are of one of two colours: white and black.  There are six different types of chess pieces: kings, queens, rooks, bishops, knights and pawns.  Different chess pieces move in different ways.  For instance, the knight (notated as "N") moves in an "L" shape: two squares in one direction, and then one square perpendicular to that.  So a knight located on d5 can move to the following squares marked "n":

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   | n |   | n |   |   |   |
   ---------------------------------
 6 |   | n |   |   |   | n |   |   |
   ---------------------------------
 5 |   |   |   | N |   |   |   |   |
   ---------------------------------
 4 |   | n |   |   |   | n |   |   |
   ---------------------------------
 3 |   |   | n |   | n |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the knight on d5 is given by the set [b4, b6, c3, c7, e3, e7, f4, f6].

The pawn (notated as "P") can only move forward.  By convention, the white pieces are initially set up on the bottom of the board and the black pieces at the top of the board.  So white pawns move "up" and black pawns move "down".  Pawns also have special rules regarding placement and movement.  Pawns normally move one square forward at a time.  However, pawns occupying their initial position have the choice of moving one square forward or two.  White pawns start on the second rank, and black pawns start on the seventh rank.

So a white pawn located on e2 can move to either of the following squares marked "p":

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   |   |   |   |   |
   ---------------------------------
 4 |   |   |   |   | p |   |   |   |
   ---------------------------------
 3 |   |   |   |   | p |   |   |   |
   ---------------------------------
 2 |   |   |   |   | P |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the white pawn on e2 is given by the set [e3, e4].

A black pawn located on c7 can move to either of the following squares marked "p":

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   | P |   |   |   |   |   |
   ---------------------------------
 6 |   |   | p |   |   |   |   |   |
   ---------------------------------
 5 |   |   | p |   |   |   |   |   |
   ---------------------------------
 4 |   |   |   |   |   |   |   |   |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the black pawn on c7 is given by the set [c5. c6].

A white pawn located on b6 can move to the following square marked "p":

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   | p |   |   |   |   |   |   |
   ---------------------------------
 6 |   | P |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   |   |   |   |   |
   ---------------------------------
 4 |   |   |   |   |   |   |   |   |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the white pawn on b6 is given by the set [b7].

A black pawn located on f2 can move to the following square marked "p":

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   |   |   |   |   |
   ---------------------------------
 4 |   |   |   |   |   |   |   |   |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   | P |   |   |
   ---------------------------------
 1 |   |   |   |   |   | p |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the black pawn on f2 is given by the set [f1].

No two pieces can simultaneously occupy the same square.  If a piece of one colour moves to a square occupied by a piece of the other colour, then it is said to have "captured" the piece on the target square, and the existing piece is removed from the board.  This is a legal move.  A piece, however, may not capture a piece of the same colour, so a move to a square occupied by a piece of the same colour is illegal.

Knights capture in the same manner in which they move.  The white knight located on h4 may capture the black pawn located on f5:

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   |   | P |   |   |
   ---------------------------------
 4 |   |   |   |   |   |   |   | N |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the white knight on h4 is given by the set [f3, f5, g2, g6].  Note that if the pawn on f5 was instead a white piece, then the knight would not be able to move to f5, since that square is already occupied by a piece of the same colour.

Pawns capture in a different manner to which they move.  While their normal movement is forward, their capturing movement is one square forward ("up" for white and "down" for black) and one square to the left or right.  So a black pawn located on e5 may capture the white knight on f4:

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   |   |   | P |   |   |   |
   ---------------------------------
 4 |   |   |   |   |   | N |   |   |
   ---------------------------------
 3 |   |   |   |   |   |   |   |   |
   ---------------------------------
 2 |   |   |   |   |   |   |   |   |
   ---------------------------------
 1 |   |   |   |   |   |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

The valid target squares for the black pawn on e5 is given by the set [e4, f4], since it may move to e4 or capture the white piece on f4.  Note that if the knight on f4 was instead a black piece, then the pawn would not be able to capture it.  Additionally, if there were piece on e4 of either colour, then the pawn would not be able to move to that square, since it may only capture on the diagonal squares in front of it.

Pawns may not move "through" a piece, so if a pawn is blocked by a piece in front of it, then it may not move further along that file.  This constraint does not apply to knights, which are allowed to "jump" over pieces in between it and the target square.  So given the following setup with a white pawn on d2 and a white knight on d3, the knight can move to the squares marked "n", while the pawn has no valid moves:

   ---------------------------------
 8 |   |   |   |   |   |   |   |   |
   ---------------------------------
 7 |   |   |   |   |   |   |   |   |
   ---------------------------------
 6 |   |   |   |   |   |   |   |   |
   ---------------------------------
 5 |   |   | n |   | n |   |   |   |
   ---------------------------------
 4 |   | n |   |   |   | n |   |   |
   ---------------------------------
 3 |   |   |   | N |   |   |   |   |
   ---------------------------------
 2 |   | n |   | P |   | n |   |   |
   ---------------------------------
 1 |   |   | n |   | n |   |   |   |
   ---------------------------------
     a   b   c   d   e   f   g   h

When setting up a position, knights may be placed on any square on the board, but pawns may not be placed on the first or last ranks (i.e. they can only be placed on ranks 2-7).

Given these rules, write a program that will output the set of valid target squares for one or more knights and pawns given an initial setup.  The program must have a console interface that prompts the user for information related to the initial board setup:

    > FindValidMoves

    Enter number of pieces: 2

    Piece 1
    Enter colour (W/B): W
    Enter type (N/P): P
    Enter position: e4

    Piece 2
    Enter colour (W/B): B
    Enter type (N/P): N
    Enter position: c5

    Valid moves
    White P on e4: [e5]
    Black N on c5: [a4, a6, b3, b7, d3, d7, e4, e6]

    Continue (Y/N)?: Y

    Enter number of pieces: 3

    Piece 1
    Enter colour (W/B): B
    Enter type (N/P): P
    Enter position: g7

    Piece 2
    Enter colour (W/B): W
    Enter type (N/P): P
    Enter position: h6

    Piece 3
    Enter colour (W/B): B
    Enter type (N/P): P
    Enter position: h7

    Valid moves
    Black P on g7: [g5, g6, h6]
    White P on h6: [g7]
    Black P on h7: []

    Continue (Y/N)?: Y

    Enter number of pieces: 3

    Piece 1
    Enter colour (W/B): W
    Enter type (N/P): P
    Enter position: f8

    Pawns may not be placed on the first or last ranks.  Please re-enter.

    Piece 1
    Enter colour (W/B): W
    Enter type (N/P): P
    Enter position: f7

    Piece 2
    Enter colour (W/B): B
    Enter type (N/P): N
    Enter position: e8

    Piece 3
    Enter colour (W/B): B
    Enter type (N/P): P
    Enter position: g7

    Valid moves
    White P on f7: [e8, f8]
    Black N on e8: [c7, d6, f6]
    Black P on g7: [g5, g6]

    Continue (Y/N)?: N
