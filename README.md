**# Connect 4**

**Description**:
We are setting out to develop a desktop application called as "Connect 4" which will enable two users to engage in this classic game. 
This application will be crafted using C# to provide a dynamic and interactive gaming experience. 
Tailored for 2-player gameplay where they engage in a battle of wits to achieve a line of four of their symbols in a row, column, or diagonal on the game board. 
This application will boast a suite of features designed to deliver a seamless and enjoyable gaming session.

The main class and the functionality of this progran is as follows:
1. **ConnectFour class**: This is the main class which represents the logic of the game.It initializes the game board, manages player details, handles player turns, checks for win conditions, and manages the game loop.
2. **Initialization**: The game board is declared as 6*7 grid with 6 rows and 7 columns using two-dimensional character array. 
Both the Players provide their names, and the first letter of their names is used as their unique symbols on the board. If the first letter of both the players are same then ensure the second player gets a unique symbol.
3. **Game Loop (PlayGame())**: Game will be played alternatively between 2 players.
Players choose a column to drop their symbol into. Checks for win conditions and a full board to determine the end of the game.
4. **Win Condition Checking (CheckWin())**: win conditions can be checked by verifying for four consecutive symbols in horizontal, vertical, and diagonal directions.
5. **Console Output (PrintBoard())**: Prints the game board with colored symbols for each player. Displays messages about the player turns and status of the game.
6. **User Interface (Main())**: Provides a simple text-based menu for starting the game or quitting the application.
Handles user input to initiate the game or exit from the game.

**Installation Guidelines**:
To run the Connect 4 game, we need to follows the below installation process:
1. **Installing Visual Studio**: We have to first download and install visula studio if we have not installed the software already.
2. **Create new project**: To create a new project, open the Visual studio and click on "Create a New Project" console. Then, Choose C# as the programming language.
3. **Build the code for connect 4 game**: Plan and write a code for connect 4 game.
4. **Execute and test the code**: Build the project to ensure there are no errors.
Next Run the application and we should see the initial greeting and options to start the game or quit the game.
5. **Play the game**:  Follow the prompts to start the game or quit.
During the game, enter column numbers (1-7) to drop player's symbol into a column.

