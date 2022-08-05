#### Part1

Given a matrix, a starting position (row and column) and an instruction, move left/right/up/down according to the instruction and return the value of the element at the position reached after making the move.

Note: You can assume that you will not overrun the boundaries.

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
#### Part2
Given a matrix and an instruction string, traverse the array according to the instruction string and return the sum of the elements traversed.
Traversing starts from the element with ithe element at the first row and first column : arr[0][0]

Note: You can assume that you will not be given an instruction that makes you  overrun the boundaries.
For eg.

```js
function traverse(arr,instruction){
// write your code here
}
let arr = [
[1,-1,0],
[2,1,-2],
[3,2,-12]
];
let instruction1 = 'drrldr'; 
let instruction2 = 'ddudrl';
let instruction3 = 'rrdldr';
console.log(traverse(arr,instruction1));//-7
console.log(traverse(arr,instruction2));//16
console.log(traverse(arr,instruction3));// -11
```
