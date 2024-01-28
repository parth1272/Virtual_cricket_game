# Virtual_cricket_game

Header Files and Namespace:

The code includes necessary C++ standard and system header files for input/output, random number generation, and sleep functionality.
The using namespace std; statement is used to simplify the use of standard C++ elements.
Team Class:

Defines a class named Team with attributes such as name (team name), players (array of player names), and runs (total runs scored by the team).
Global Variables:

currentBatsman and currentBowler are global variables to keep track of the current batsman and bowler during the game.
Main Function:

Welcomes users to the Gully Cricket game.
Creates instances of two teams, teamA and teamB, with predefined player names and team names.
Displays players of both teams using the displayPlayers function.
Starts the first inning for teamA.
Selects batsman and bowler for teamA.
Simulates the first inning and calculates runs scored by teamA using the playInning function.
Displays the runs scored by teamA.
Displays the target for teamB to win.
Starts the second inning for teamB.
Selects batsman and bowler for teamB.
Simulates the second inning and calculates runs scored by teamB using the playInning function.
Displays the runs scored by teamB.
Decides the winner based on the total runs scored by both teams using the decideWinner function.
The program then ends with a return statement.
Functions:

welcomeUsers:

Displays a welcome message for users.
displayPlayers:

Prompts the user to press Enter to display players.
Displays players of both teams in a formatted manner.
selectBatsmanAndBowler:

Prompts the user to press Enter to select batsman and bowler.
Randomly selects batsman and bowler from the provided teams and displays their names.
selectPlayer:

Randomly selects a player from the given array of player names.
startInning:

Displays a message to start an inning with the specified inning number, batting team, and bowling team.
playInning:

Simulates playing an inning (6 balls) for the batting team.
Generates random runs for each ball bowled and displays the runs for each ball.
displayScore:

Displays the runs scored by a team in the inning.
decideWinner:

Compares the total runs scored by both teams and declares the winner or if it's a draw.
Output Formatting:

The code uses various formatting techniques to display messages and information in a structured manner, making it more user-friendly.
User Interaction:

The program involves user interaction by prompting the user to press Enter at certain points, creating a more interactive experience.
Overall, the code simulates a simple cricket game between two teams (TeamA and TeamB) in a gully cricket setting, where the user can observe the gameplay and see the final outcome of the match.
