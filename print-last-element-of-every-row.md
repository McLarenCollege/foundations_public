#### Note: Do not use a loop

Given a Tic Tac Toe board of  size 3X3 create a function that prints the last element of each row.

```js
function printLastElementEveryRow(board){
// write your code here
}
let marksBoard = [['X', 'O', 'X'],['O', 'X', ' '], ['O', 'X', 'X']];
printLastElementEveryRow(marksBoard);

let abhisheksBoard = [['X', 'O', ' '],['O', 'X', 'O'], ['O', ' ', 'X']];
printLastElementEveryRow(abhisheksBoard);
```
The first call to `printLastElementEveryRow` should produce the following output
```
X
 
X
```
The second call to `printLastElementEveryRow` should produce the following output
```
 
O
X
```
