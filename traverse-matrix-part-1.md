#### Traverse Matrix Part1

Given a matrix, a starting position (row and column) and an instruction, move left/right/up/down according to the instruction and return the value of the element at the position reached after making the move.

Note: You can assume that you will never be given an input that will overrun the boundaries.

In the instruction,

d: means move "down";

r: means move "right";

l : means move 'left',

u : means move 'up'

***CODE TEMPLATE***
*****************************

```js
function makeMove(arr, initialRowPosition, initialColPosition, instruction){
// write your code here
}
let arr = [
[1,-1,0],
[2,1,-2],
[3,2,-12]
];

console.log(makeMove(arr, 0, 0, 'd'));//2
console.log(makeMove(arr, 1, 2, 'u'));//0
console.log(makeMove(arr, 2, 1, 'r'));//-12
console.log(makeMove(arr, 0, 1, 'l'));//1
```
***************************
