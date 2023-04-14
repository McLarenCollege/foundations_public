Write a function that takes an array of integers and returns the difference between the sum of all the even numbers in the array and sum of all odd numbers in the array. 


For example, given the array `[11, 32, 13, 4, 50]`, the function should return 62
**Explanation**
- The sum of even numbers in the array is `32 + 4 + 50 = 86` 
- The sum of odd numbers in the array is `11 + 13 = 24` 
- Difference of these two sums is `86 - 24 = 62` 

```js
function diffOddEvenSum(nums){
  // write your code here

}
console.log(diffOddEvenSum([11, 32, 13, 4, 50])); // should return 62
console.log(diffOddEvenSum([1, 2, 3, 4, 5])); // should return -3
console.log(diffOddEvenSum([100, 129, 33, 408, 56])); // should return 402
```
