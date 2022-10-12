# Possible Knight Moves

Given a square chessboard and a knight occupying a cell return the number of the possible positions it can take after making a move.

The letter 'K' denotes the current knight position.

For eg.
```js
let chessBoard=[[' ',' ',' ',' '],
                [' ',' ',' ',' '],
                [' ','K',' ',' '],
                [' ',' ',' ',' ']];
let chessBoard2=[[' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' '],
                 [' ','K',' ',' ',' '],
                 [' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ']];
let chessBoard3=[['K',' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ',' '],
                 [' ',' ',' ',' ',' ',' ']];
             
 function possibleKnightMoves(chessBoard){
 //write your code here
 }
 console.log(possibleKnightMoves(chessBoard));//returns 4 becuase possible moves are[[0,0],[0,2],[1,3],[3,3]];
 console.log(possibleKnightMoves(chessBoard2));// returns 6 because possible moves are[[0,0],[0,2],[1,3],[3,3],[4,0],[4,2]];
 console.log(possibleKnightMoves(chessBoard3));// returns 2 because possible moves are [[2,1],[1,2]]
 
```
Please refer the image to understand the possible moves of a knight.

![image](https://i.imgur.com/1pv0Ye3.jpg)


Please watch this [video](https://youtu.be/m9DWEa6YvpQ) for a hint for solving the problem:

