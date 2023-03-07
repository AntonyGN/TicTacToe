<p align="center">
  <img width="230" height="200" src="https://github.com/AntonyGN/TicTacToe/blob/main/image.png">
</p>

# To install and run the Tic Tac Toe game, you can follow these steps:
1. Click the "Code" button and select "Download ZIP" to download the source code as a ZIP file.
2. Extract the ZIP file to a directory or folder on the new machine.
3. Open the command prompt or terminal on the machine.
4. Navigate to the directory or folder containing the Tic Tac Toe game source code using the ```cd``` command.
5. Compile the TicTacToe.java file using the ```javac``` command.
6. Run the program using the ```java``` command. 

### Here's a summary of the functions and methodology used in the code:
 - ```TicTacToe``` class: Represents the game board and provides methods for playing the game.
 - ```board``` field: A 2D char array of size 3x3 that represents the game board.
 - ```play``` method: The main game loop that handles player input and checks if the game is over.
 - ```isValidMove``` method: Checks if a given move is valid, i.e., if the cell is empty and within the bounds of the board.
 - ```isGameOver``` method: Checks if the game is over by checking all possible winning combinations.
 - ```printBoard``` method: Prints the game board to the console.
 - ```printWinner``` method: Prints the winner (if there is one) to the console.
 - ```Main``` class: Contains the main method that runs the game.
 
 
 ### Here's an example of how to play the game:
 ```
 Welcome to Tic Tac Toe!

Here's the current board:
- - -
- - -
- - -

Player X, enter your move (row column):
1 1

Here's the current board:
X - -
- - -
- - -

Player O, enter your move (row column):
0 1

Here's the current board:
X - -
O - -
- - -

Player X, enter your move (row column):
0 0

Here's the current board:
X - -
O - -
X - -

Player O, enter your move (row column):
1 0

Here's the current board:
X - -
O - -
X O -

Player X, enter your move (row column):
2 2

Here's the current board:
X - -
O - -
X O X

Player X wins!
 ```
