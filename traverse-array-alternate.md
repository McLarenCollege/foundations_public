Given an multi-dimensional array, traverse the array row-wise in alternate fashion and keep pushing the elements in the result array.
Your function should return the result array.

```js
function traverseAlternate(arr){
// write your code here
}
let arr1 = [[1,2,3],
           [4,5,6],
           [7,8,9]];
let arr2 = [[1,2,3,4],
            [5,6,7,8],
            [9,10,11,12],
            [13,14,15,16]];
console.log(traverseAlternate(arr1));// [1, 2, 3, 6, 5, 4, 7, 8, 9]
console.log(traverseAlternate(arr2));// [1, 2, 3, 4, 8, 7, 6, 5, 9, 10, 11, 12, 16, 15, 14, 13]
```
