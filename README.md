# scrabble_scoreboard
An android app for scrabble scoring

This scoreboard will be written in React for android.

It will have the following series of screens:
1. A welcome screen with some options:
    a. A button to start a new game.
    b. A button to view old games.
    c. A button to continue a game in progress.
2. (a) A button to start a new game will kick off a wizard with some steps. Each step will have a back button.
    Step 1: Choose number of players.
    Step 2: Type players names in play order.
    Step 3: Select if you would like the app to randomly decide who goes first.
    Step 4: Ensure play order is correct.
    Step 5: Begin game!
3. (b) A button to view old games will show a selectable list of old games by name and date. Selecting one of these will bring      you to a score chart for the game.
4. (c) A button to continue a game in progress. This will only be enabled when there was a paused game. You can pause up to 5       games at a time. When you pause a game, there is an option to take a store a picture so you can reconfigure the board for       next time.
5. Once a game is begun, the score entering will be turn based. You can review the entire score board at any time by hitting a      button. Once you're viewing the whole score board, you can go back to whoever's turn it is. 
6. A turn screen will have the player's name, their current score, and a numeric text box to enter a score (up to 3 digits).
7. Once the score is entered, it will calculate the new score, flash it on the screen, and proceed to the next player.
8. When a player reaches over 100 and over 200 points, there will be a little cheer animation with sound effect.
9. On the player screen, there will be a little symbol for "Finish Game". The game will then calculate the scores and determine the winner.
10. Once the winner is determined, there will be a screen to type in a name for the game. The default name will be "Game X - Date".
