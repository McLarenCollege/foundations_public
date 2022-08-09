
Given an multi-dimensional array, traverse the array column-wise and push  the maximum value of every column into a result array.
The function should return the result array.

```js
function traverseColumnwise(arr){
// write your code here
}
let arr1 = [[11, 2, 3],
            [ 4,15, 6],
            [ 7, 8, 9]];
let arr2 = [[ 1, 2, 3,44],
            [25, 6, 7, 8],
            [ 9,10,11,12],
            [13,14,15,16]];
traverseColumnwise(arr1);//[11, 15, 9]
traverseColumnwise(arr2);// [25, 14, 15, 44]
```
