Write a function that takes an array of integers and returns the two indices of the numbers that add up to a given target. You may assume that each input has exactly one solution, and you may not use the same element twice.

For example, given the array `[2, 7, 11, 15]` and the target `9`, the function should return `[0, 1]` because `2 + 7 = 9`.


```js
function targetSum(nums, target){
  // write your code here
}

targetSum([2, 7, 11, 15], 9); // should return [0, 1]
targetSum([2, 7, 11, 15], 22); // should return [1, 3]
targetSum([1, 3, 99, 41], 102); // should return [1, 2]
```
