#Minesweeper : -
Features: It has grid of clickable squares with hidden mines, It has reset functionality, Responsive UI.

Tech Stack Used: HTML, CSS, JavaScript.

Contribution: Minesweeper is single-player logic-based computer game played on rectangular board,if player click on squares which contain bombs then player lose the game otherwise score increase by one.

Acceptance Criteria-:
0. Each of 81 grid cells must have id attribute cell_{i}, where is i = {1, 2, 3, . . . , 81}.
1. Create a window. random variable inside which 10 unique random numbers will be there showing the location of the bomb.
2. Use "https://img.icons8.com/emoji/48/000000/bomb-emoji.png" this as a bomb image after clicking on the bomb all the bombs will be shown as the background image. Note: background-image css-style property.
3. Player who selects all 71 grids without bombs will be the winner.
4. Create an element with the id "resultDisplay" inside which the text result will be shown as "win" for the winner and "game over" for the loser. Change text-content of "resultDispaly" to final-message. Note: In case of no-result of the game, make it empty(no-content inside it).
5. Create an element with the id "gameScore" inside which text points will be incremented after every successful click in which the bomb is not clicked
6. Create a reset button with id resetButton after which the game should restart
7. Reset button should be visible all the time.
