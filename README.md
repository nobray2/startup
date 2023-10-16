# Startup
Startup repo cs260 fall 2023


## Pitch
Match master is an online game that allows **anyone anywhere** to test their memory to its limit. It allows players to track their prpogress and compare their performance to others. 
## Features
  * Multiple game modes. Players will have the option between two ways to play. The first is having a time limit of 10 minutes to beat as many boards as they can. Accuracy matters and is calculated into leaderboard position, but too many errors will not end the play. The other option is infinite mode. There is no time limit, however accuracy matters and after a certain number of errors the playthrough will be ended.
  * Difficulty levels. Along with the game mode, players will be able to choose between two difficulty levels. The hard difficulty is a 10x10 board while easy is 6x6.

## Technology
  * Authentication
    * All players will be able to create an account with a username and password. Players are allowed to make multiple accounts if they wish. Scores will be saved and tied to each account. 
  * Database
    * A data base will store the user names and passwords of users so they can keep track of their scores and progress.
    * Leaderboard information will be stored on a database and will display the all time high scores for each game mode.
  * Websocket Data
    * Players will be notified when others finish a play through for either game mode, along with that users score and accuracy.
    * Players will be notified in real time when a new high score or leaderboard entry is made.
    * There will be a running count that players can see of how many players are currently in a game.


## Example Images