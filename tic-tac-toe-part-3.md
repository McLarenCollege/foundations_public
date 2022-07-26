Given the following board variable representing a tic-tac-toe board. Write a function to check if X has won in the last column. That is, whether all 3 cells in the last column are 'X' Your function should return the correct boolean value for any given board.

```js
function hasXWonInLastCol(board) {
//write your code here
}

console.log(hasXWonInLastCol([[' ', 'O', 'X'],
                              ['O', 'X', ' '],
                              ['O', ' ', 'X']]));// false

console.log(hasXWonInLastCol([['O', 'X', 'X'],
                              ['O', 'X', ' '],
                              ['O', 'X', 'X']]));// false

console.log(hasXWonInLastCol([['X', 'O', 'O'],
                              ['O', 'X', 'X'], 
                              ['O', ' ', 'X']]));// false
                              
console.log(hasXWonInLastCol([[' ', 'O', 'X'],
                              ['O', 'X', 'X'], 
                              ['O', ' ', 'X']]));// true
```
