#### Note : Do not use a loop

Given a Tic Tac Toe board of  size 3X3 create a function that prints all the elements of the Left to Right Diagonal.
```js
function printLRDiagonal(board){
// write your code here
}
let marksBoard = [['X', 'O', 'X'],['O', 'X', ' '], ['O', 'X', 'X']];
printLRDiagonal(marksBoard);

let abhisheksBoard = [['X', 'O', ' '],['O', 'O', 'O'], ['O', ' ', 'X']];
printLRDiagonal(abhisheksBoard);
```
The first call to `printLRDiagonal` should produce the following output
```
X
X 
X
```
The second call to `printLRDiagonal` should produce the following output
```
X 
O
X
```
