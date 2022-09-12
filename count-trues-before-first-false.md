# Count trues before first false

Given an array consisting of true and false values, write a function that returns 
the number of true values present before the first false value using a while loop.
If the array does not contain any false value return the number of true values.

```js
function numberOfTrues(booleans){
// write your code here
}
console.log(numberOfTrues([true, true, false, false, true, true]));// 2
console.log(numberOfTrues([false, true, false, false, true, true]));// 0
console.log(numberOfTrues([true, true, true, true, true, true]));// 6
console.log(numberOfTrues([]));// 0
console.log(numberOfTrues([false, false, false]));// 0
```
