Given an array of booleans update the first chunk of false values to true until you reach a true value or undefined.


```js
function falseToTrue(booleans){
// write your code here
}
let val = [false,false,false,true,false,false,true];
console.log(falseToTrue(val));// should return [true,true,true,true,false,false,true]
let val2 = [false,false,false];
console.log(falseToTrue(val2));// should return [true,true,true]
```
