# Convert Last Three Falses to True
Create a function that accepts a boolean array and converts the last 3 false values to true.

If there are 3 or less than 3 false values in the array it converts all of them to true.

The function should return the updated array.

```js
function convertLastThree(bools){
// write your code here
}
let booleans = [true, false, true, false, true, false, false, false, true, false];

console.log(convertLastThree(booleans));// [true, false, true, false, true, false, true, true, true, true]
booleans = [false,false,true];
console.log(convertLastThree(booleans));// [true, true, true]
```
