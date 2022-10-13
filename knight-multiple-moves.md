# Knight Multiple Moves

One of the chess soldiers is the `Knight`. A knight can move 2 squares vertically and one horizontally or 2 squares horizontally and one vertically.

If a chess is placed in the corner of the board, write a function called `squaresCoveredInMoves` which calculates how many squares the knight can cover in a given number of moves.  

For example, starting from the corner of the board, then it can cover 3 squares as shown her:

<img src="https://user-images.githubusercontent.com/53505683/195483253-deae23d7-18fa-40dd-9274-82f64596f1f5.png" width=200 />

```js
function squaresCoveredInMoves(moves){
  //Write your code here
}
console.log(squaresCovered(1)); //3
console.log(squaresCovered(2));//12
console.log(squaresCovered(3));//32
console.log(squaresCovered(4));//53
```

Note: The starting cell of the knight is always at the corner of the board.
