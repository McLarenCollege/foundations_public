Given the following board variable representing a tic-tac-toe board. Write a function that takes a board as an input and return true if X has won and false if X has not won.

Note: We can give you any state of the board and you will have to give correct result if X has won for that particular state of the board.

Hint: You have to check in all rows, columns and diagonals.

```js

function hasXWon(board)
{
  //write function body to check if x has won or not.
}
let board = [[' ', 'O', 'X'],['O', 'X', ' '], ['O', ' ', 'X']];
console.log(hasXWon(board));// false
board = [['X', 'O', ' '],['O', 'X', 'O'], ['X', 'O', 'X']];
console.log(hasXWon(board)); // true

```
