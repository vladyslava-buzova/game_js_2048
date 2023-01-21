# Game 2048 in JavaScript
 - [DEMO LINK](https://vladyslava-buzova.github.io/game_js_2048/)

# Game rules
Game 2048 is written in pure JavaScript.
In this game you need to combine numbered tiles in order to gain a higher numbered tile.
You need to merge equal cells with keyboard arrows until you won't get 2048.

# Implemented tasks:
1) The game field is 4 x 4
2) Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3) The player can move cells with keyboard arrows
4) All the numbers should be moved in the selected direction until all empty cells are filled in
   - 2 equal cells should be merged into a doubled number
5) The move is possible if at least one cell is changed after the move
6) When 2048 value is displayed in any cell, win message should be shown.
7) The `game over` message should be shown if there are no more available moves.
8) Hide start message when game starts.
9) Change the `Start` button to `Restart` after the first move.
10) Increase score with each move. The score should be increased by the sum of all merged cells.

# How to launch a project:
1. Clone the repo.
  - git clone the-link-from-your-forked-repo.
2. Chech your Node.js version (Recommended Node.js 14 to run the project corectry)
  - node -v
3. Run VSCode and open the project folder.
4. Open a terminal in the project folder.
5. Run npm install (or just npm i) to install the dependencies.
6. Run npm start to open the project and check if it works.
