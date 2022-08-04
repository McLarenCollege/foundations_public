Create a function that accepts a boolean array and converts the last 3 false values to true.
If there are less than 3 false values in the array it converts all of them to true .
```js
function lastThreeFalses(booleans){
// write your code here
}
let booleans = [true, false,true,false,true,false,false,false,true,false]);
console.log(lastThreeFalses(booleans));
booleans = [false,false,true];
console.log(lastThreeFalses(booleans));
```
