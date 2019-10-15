# ChessBoardGame

The main classes will be:

    Spot: A spot represents one block of the 8×8 grid and an optional piece.
    
    Piece: The basic building block of the system, every piece will be placed on a spot. Piece class is an abstract class. The extended classes (Pawn, King, Queen, Rook, Knight, Bishop) implements the abstracted operations.
    
    Board: Board is an 8×8 set of boxes containing all active chess pieces.
    
    Player: Player class represents one of the participants playing the game.
    
    Move: Represents a game move, containing the starting and ending spot. The Move class will also keep track of the player who made the move.
    
    Game: This class controls the flow of a game. It keeps track of all the game moves, which player has the current turn, and the final result of the game.
    
    --->
    
    Spot: To represent a cell on the chess board
    
    Piece: An abstract class to represent common functionality of all chess pieces:
    
    King: To represent King as a chess piece:
    
    Knight: To represent Knight as a chess piece
    Similarly, we can create classes for other pieces like Queen, Pawns, Rooks, Bishops etc.
    
    Board: To represent a chess board:
    
    Player: An abstract class for player, it can be a human or a computer.
    
    Move: To represent a chess move:
    
    Game: To represent a chess game:
