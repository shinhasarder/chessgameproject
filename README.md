**Chess Game**

# **Abstract**

This project presents the design and development of a web-based chess
game using HTML. The game allows a human player (white) to play against
a simple computer opponent (black). Core chess functionalities, such as
piece movement, pawn promotion, and win/loss detection, are implemented.
The computer opponent makes random legal moves, providing a basic
artificial intelligence component. The project demonstrates the
application of front-end technologies to create an interactive,
browser-based game with an intuitive user interface.

# **Introduction**

**Background:** Chess is one of the most popular strategy games in the
world, requiring critical thinking and planning. With the rise of web
technologies, creating an online chess platform has become an attractive
project for students and developers.

### **Problem Statement:** Traditional chess applications often rely on large frameworks or external libraries. This project addresses the challenge of implementing a lightweight, browser-based chess game using only HTML without external chess engines.

### **Objectives**

-   To design and develop a playable chess game in the browser.

-   To implement fundamental chess rules, including valid moves and pawn
    > promotion.

-   To integrate a basic AI that plays as black.

-   To ensure responsive design for multiple devices.

**Scope:**The scope of this project is limited to a single-player chess
game (player vs computer). Advanced rules like castling and en passant
are not implemented. The computer AI plays random valid moves, making it
suitable for casual play rather than professional-level strategy.

## 

## **Literature Review**

Several online chess platforms, such as Lichess and Chess.com, offer
advanced chess engines like Stockfish. However, these systems rely on
complex algorithms and external libraries. Prior research shows that
simplified chess programs can be implemented using basic grid-based
logic in JavaScript. Existing academic projects often highlight user
interaction and board rendering as major challenges. This project
contributes to this area by creating a self-contained, lightweight chess
game using only web technologies.

## **Methodology**

The project followed a structured development approach:

1.  Requirement Analysis -- Identifying features such as board creation,
    > piece rendering, move validation, and AI logic.

2.  Design -- Implementing an 8×8 chess grid with alternating colors and
    > Unicode chess symbols for pieces.

3.  Implementation -- Using JavaScript functions for board
    > initialization, move validation, and AI moves.

4.  Testing -- Manually testing all piece movements, win/loss
    > conditions, and restart functionality.

5.  Deployment -- Hosting the project as a standalone HTML file that
    > runs on any modern browser.



## **Implementation**

-   **Frontend (HTML):**The chessboard was created using a CSS grid.
    
    -   Piece movement rules were coded in functions.

    -   AI move selection was implemented using a random choice from all
        > valid moves.

    -   Game over detection checks whether a king is captured.\
        

-   **User Interaction:**

    -   Players select and move pieces by clicking on the board.

    -   The current game state is displayed via a status message.

    -   A restart button resets the board.


## **Results and Analysis**

-   The project successfully creates a fully functional chess game where
    > the player competes against a simple AI.

-   All major pieces (King, Queen, Rook, Bishop, Knight, Pawn) follow
    > correct movement rules.

-   Pawn promotion is implemented, automatically promoting pawns to
    > queens.

-   The AI provides a moderate challenge for beginners but lacks
    > advanced strategy.

-   The design is responsive, allowing play on both desktop and mobile
    > devices.

**Strengths:**

-   Lightweight and browser-based.

-   No external dependencies.

-   Intuitive and visually appealing design.

**Limitations:**

-   No castling or en passant.

-   AI lacks depth and strategy (random moves).

-   No move history or undo functionality.

**Discussion**

The project highlights how fundamental web technologies can be used to
build an engaging game without external libraries. While the
implementation is basic compared to professional chess engines, it
serves as a foundation for further development. Future improvements may
include implementing advanced chess rules, adding move history/undo
functionality, and integrating a stronger AI algorithm such as Minimax
with Alpha-Beta pruning.

## **Conclusion**

This project successfully demonstrates the development of a web-based
chess game using HTML . It achieves the objective of providing a
playable chess interface with rule-based movement and AI-based gameplay.
While limited in advanced features, it serves as a stepping stone toward
more sophisticated chess systems. The project emphasizes the power of
front-end web technologies in creating interactive applications.

## **References**

1.  Chess Programming Wiki --
    > [[https://www.chessprogramming.org/]{.underline}](https://www.chessprogramming.org/)

2.  Lichess --
    > [[https://lichess.org/]{.underline}](https://lichess.org/)

3.  Chess.com --
    > [[https://www.chess.com/]{.underline}](https://www.chess.com/)
