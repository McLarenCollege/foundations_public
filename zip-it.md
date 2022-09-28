# Zip It

Write a function called `zipIt` that accepts two **already** sorted arrays and returns a new array which contains all the elements
present in both the arrays in a sorted order.

Note: Do not use a sorting algorithm

Eg. 
```js
zipIt([1,5,9,10], [2,4,7])
```
will return `[1,2,4,5,7,9,10]`

```js
function zipIt(arr1,arr2){
// write your code here
}
console.log(zipIt([1, 5, 9, 10], [2, 4, 7])); // should return `[1, 2, 4, 5, 7, 9,10]`
console.log(zipIt([1, 2, 3, 4], [4, 5, 6, 7])); // should return `[1, 2, 3, 4, 4, 5, 6, 7]`
console.log(zipIt([5, 5, 5],[5, 6, 6, 6, 6, 6]));//  should return `[5, 5, 5, 5, 6, 6, 6, 6, 6 ]`

```
