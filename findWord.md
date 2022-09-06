# Find Word

Write a function `findWord` which takes a matrix of characters and a target word, 
and returns true if the word appears vertically at some position in the matrix 

Note:
* Every element in the matrix will be a string of length 1
* You should only consider the top-down direction (ie. not left-right or down-up, etc)

### Example 1
```js
let easyPuzzle = [
    ['b', 'a', 't'],
    ['i', 'i', 'p'],
    ['t', 'o', 'n']
];
console.log(findWord(easyPuzzle, 'bit')); // should print true
console.log(findWord(easyPuzzle, 'bat')); // should print false
```

### Example 2
```js
let hardPuzzle = [
    ['y', 'o', 't', 'v'],
    ['k', 'c', 'p', 's'],
    ['t', 'h', 'n', 's'],
    ['t', 'a', 'o', 'e'],
    ['t', 't', 'a', 'i'],
];
console.log(findWord(hardPuzzle, 'chat')); // should print true
console.log(findWord(hardPuzzle, 'set')); // should print false
console.log(findWord(hardPuzzle, 'i')); // should print true
```
***CODE TEMPLATE***
***********************************
```js
function findWord(puzzle,word){
// write your code here
}
let easyPuzzle = [
    ['b', 'a', 't'],
    ['i', 'i', 'p'],
    ['t', 'o', 'n']
];
console.log(findWord(easyPuzzle, 'bit')); // should print true
console.log(findWord(easyPuzzle, 'bat')); // should print false
let hardPuzzle = [
    ['y', 'o', 't', 'v'],
    ['k', 'c', 'p', 's'],
    ['t', 'h', 'n', 's'],
    ['t', 'a', 'o', 'e'],
    ['t', 't', 'a', 'i'],
];
console.log(findWord(hardPuzzle, 'chat')); // should print true
console.log(findWord(hardPuzzle, 'set')); // should print false
console.log(findWord(hardPuzzle, 'i')); // should print true
```
**********************************
