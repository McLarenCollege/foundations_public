A consecutive-run is a list of adjacent, consecutively increasing integers. Create a function that takes an array of numbers and returns the length of the longest consecutive-run.

To illustrate:
```js
longestRun([1, 2, 3, 5, 6, 7, 8, 9]) ➞ 5
// Two consecutive runs: [1, 2, 3] and [5, 6, 7, 8, 9] (longest).
```
```js

function longestRun(arr){
// write your code here
}

console.log(longestRun([1, 2, 3, 10, 11, 15]));// ➞ 3
// Longest consecutive-run: [1, 2, 3].

console.log(longestRun([3, 5, 7, 10, 15]));// ➞ 1
// No consecutive runs, so we return 1.

console.log(longestRun([1, 2, 3, 5, 6, 7, 8, 9]));// ➞ 5
// Two consecutive runs: [1, 2, 3] and [5, 6, 7, 8, 9] (longest).

```
