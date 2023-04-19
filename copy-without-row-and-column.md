# Copy Without Row and Column

Create a function which takes a rectangular matrix, and a row and column index,
then returns a copy of that matrix with given row and column removed.  

**Note: The input matrix should not be modified**

### Example 1

```js

let matrix1 = [
    [2, 7, 9, 2],
    [8, 0, 7, 1],
    [8, 8, 0, 8]
];

// Should return:
// [[2, 7, 2], [8, 8, 8]]
copyWithoutRowAndColumn(matrix1, 1, 2);


```

### Example 2
```js

let matrix2 = [
  ['a', undefined, 6],
  [true, 'x', [false]]
];


// Should return:
// [['x', [false]]]
copyWithoutRowAndColumn(matrix2, 0, 0);
```

***CODE TEMPLATE***
********************************
```js
function copyWithoutRowAndColumn(matrix, row, col){
// write your code here
}
let matrix1 = [
    [2, 7, 9, 2],
    [8, 0, 7, 1],
    [8, 8, 0, 8]
];

console.log(copyWithoutRowAndColumn(matrix1, 1, 2));
let matrix2 = [
  ['a', undefined, 6],
  [true, 'x', [false]]
];
console.log(copyWithoutRowAndColumn(matrix2, 0, 0));
```
********************************

Please watch this [video](https://youtu.be/VF-VQ6B6e6s) for a hint for solving the problem.
