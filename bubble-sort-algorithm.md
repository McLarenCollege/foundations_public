Write a function that sorts a given array using the Bubble Sort Algorithm and returns the sorted Array.
For eg.
```js
bubbleSort([1,5,3,0])
```
should return `[0,1,3,5]`
```js
bubbleSort([-1,0,-5,5,8])
```
should return `[-5,-1,0,5,8]`


```js
function bubbleSort(nums){
// write your code here
}
console.log(bubbleSort([4, 3, 5, 9, 7, 2, 6]));
console.log(bubbleSort([1,5,3,0])); // should return `[0,1,3,5]`
console.log(bubbleSort([-1,0,-5,5,8])); // should return `[-5,-1,0,5,8]`

```
Note 1: You must use `break` keyword to break out of the loop if there is no swap happening in current iteration.

Note 2: Whenever you compare two numbers a and b you must print a statement like this : `comparing a and b`. For example, `bubbleSort([1, 5, 3, 0])`
should print
```
comparing 1 and 5
comparing 5 and 3
comparing 5 and 0
comparing 1 and 3
comparing 3 and 0
comparing 1 and 0
```
And then the function should  return the sorted array `[0, 1, 3, 5]`

