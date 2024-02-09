Java code encapsulates a classic Tic-Tac-Toe game, featuring a 3x3 game board where two players, a human player named Bob ('X') and an artificial intelligence (AI) player ('O'), take turns making moves. The game is initialized through the TicTacToe class, which manages the game board, player actions, and win/draw conditions. The abstract Player class serves as a blueprint for both human and AI players, ensuring a consistent structure for player details and move validation.

The HumanPlayer class extends the Player class and enables user interaction, allowing Bob to input his moves via the console. On the other hand, the AIPlayer class represents an automated opponent making random moves.

The game is orchestrated by the Launchgame class, where turns alternate between Bob and the AI until there is a conclusive outcome. The console displays the current state of the game board after each move. The game concludes when either player achieves a winning combination in a row, column, or diagonal, or when the game results in a draw.

This Tic-Tac-Toe implementation successfully combines object-oriented principles with simple console-based user interaction, creating an engaging and timeless game experience.
