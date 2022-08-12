Write code to remove all the `true` values from the begining of a boolean array until you encounter a `false` and returns the modified array.
 
HINT : Consider using a while loop instead of a for loop

***CODE TEMPLATE***
*************************

```js
function deleteTrueFromBeginning(arr){
// write your code here
}
let arr = [true,true,false,false,false,true,true,false];
console.log(deleteTrueFromBeginning(arr));// should return [false,false,false,true,true,false]
arr = [true,true,true,true,true];
console.log(deleteTrueFromBeginning(arr));// should return []
```
***************************
