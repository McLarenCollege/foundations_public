Given an array consisting of true and false values, write a function that returns 
the number of true values present after the last false value using a while loop.
If the array does not contain any false value, just return the number of true values in the array
```js
function numberOfTruesAfterLastFalse(arr){
// write your code here
}
console.log(numberOfTruesAfterLastFalse([true, true, false, false, true, true]));// 2
console.log(numberOfTruesAfterLastFalse([false, true, false, false, true, false]));// 0
console.log(numberOfTruesAfterLastFalse([true, true, true, true, true, true]));// 6
console.log(numberOfTruesAfterLastFalse([]));// 0
console.log(numberOfTruesAfterLastFalse([false, false, false]));// 0
```
