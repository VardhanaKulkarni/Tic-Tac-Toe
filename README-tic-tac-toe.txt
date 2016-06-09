
The game has been implemented by using HTML, CSS and javascript.

Instructions to Run and Play the game:
1. Open the .html file in a web browser. It has been tested in Chrome and Firefox web browsers.
2. Start playing the game. The game requires two players and does not support playing from multiple tabs/windows.
   The player starting the game is addressed as "Player X" and the second player is addressed as "Player O".
3. If a player wins or in the case of Draw, click Restart game option to restart the game.

Logic:
When a player clicks a cell in the table, the javascript function is called and the state information
is maintained for each player in a matrix. If a player clicks on 3 cells which are on the same column or
same row or same diagonal, he is announced as winner and the game is stopped.
