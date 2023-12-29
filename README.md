#First class: Position

Checklist:
 Class Position [public]
 OOP Topics:
    o Encapsulation
    o Constructors
    o ToString (Object / overriding)
Starting to implement Board and Piece

Checklist:
 Classes Piece, Board [public]
 OOP Topics:
    o Associations
    o Encapsulation / Access Modifiers
 Data Structures Topics:
    o Matrix
Chess layer and printing the board
8 - - - - - - - -
7 - - - - - - - -
6 - - - - - - - -
5 - - - - - - - -
4 - - - - - - - -
3 - - - - - - - -
2 - - - - - - - -
1 - - - - - - - -
 a b c d e f g h
 
Checklist:
 Methods: Board.Piece(row, column) and Board.Piece(position)
     Enum Chess.Color
     Class Chess.ChessPiece [public]
     Class Chess.ChessMatch [public]
     Class ChessConsole.UI
 OOP Topics:
    o Enumerations
    o Encapsulation / Access Modifiers
    o Inheritance
    o Downcasting
    o Static members
    o Layers pattern
 Data Structures Topics:
o Matrix
Placing pieces on the board
Checklist:
 Method: Board.PlacePiece(piece, position)
 Classes: Rook, King [public]
 Method: ChessMatch.InitialSetup
 OOP Topics:
    o Inheritance
    o Overriding
    o Polymorphism (ToString)
BoardException and defensive programming
Checklist:
 Class BoardException [public]
 Methods: Board.PositionExists, Board.ThereIsAPiece
 Implement defensive programming in Board methods
 OOP Topics:
    o Exceptions
    o Constructors (a string must be informed to the exception)
ChessException and ChessPosition
Checklist:
 Class ChessException [public]
 Class ChessPosition [public]
 Refactor ChessMatch.InitialSetup
 OOP Topics:
    o Exceptions
    o Encapsulation
    o Constructors (a string must be informed to the exception)
    o Overriding
    o Static members
    o Layers pattern
Little improvement in board printing
Color in terminal:
 Windows: Git Bash
 Mac: Google "osx terminal color"
Checklist:
 Place more pieces on the board
 Distinguish piece colors in UI.PrintPiece method
Moving pieces
Checklist:
 Method Board.RemovePiece
 Method UI.ReadChessPosition
 Method ChessMatch.PerformChessMove
    o Method ChessMatch.MakeMove
    o Method ChessMatch.ValidadeSourcePosition
 Write basic logic on Program.cs
 OOP Topics:
    o Exceptions
    o Encapsulation
Handling exceptions and clearing screen
Clear screen using Java:
// https://stackoverflow.com/questions/2979383/java-clear-the-console
public static void clearScreen() {
 System.out.print("\033[H\033[2J");
 System.out.flush();
}
Checklist:
 ChessException
 InputMismatchException