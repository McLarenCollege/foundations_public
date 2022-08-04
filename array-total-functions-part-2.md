Part 2

Write a function called 'addTotalsToGrid' which takes an array of 3 subarrays, where each sub-array has 4 numbers. The function should add the total to the end of each sub-array and return the modified array. You should call the function `addTotal` in Part 1 three times.

Tip: To start, create a variable called 'sub' and point it to the first element in the `grid` array.  Then call the function addTotal you wrote earlier, passing `sub` as the paramter.   Then change `sub` to point to the second element in the `grid` array, etc.

```js
// copy your addTotal function here

function addTotalsToGrid(grid){
// write your code here
}

let myGrid = [[1, 2, 3, 4], [0, 0, 1, 0], [10, 12, 5, 10]];
console.log(addTotalsToGrid(myGrid));

let simpleGrid = [[0, 0, 0, 0], [3, 3, 3, 3], [5, 5, 5, 5]];
console.log(addTotalsToGrid(simpleGrid));


```
