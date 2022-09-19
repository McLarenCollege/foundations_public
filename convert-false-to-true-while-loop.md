# Convert False to True

Given an array of booleans update the first chunk of false values to true until you reach a true value or undefined.

The function should return the modified array


```js
function falseToTrue(booleans){
  // write your code here
}

let bools1 = [false, false, false, true, false, false, true];
console.log(falseToTrue(bools1)); // should print [true, true, true, true, false, false, true]

let bools2 = [false, false, false];
console.log(falseToTrue(bools2));// should print [true, true, true]

let bools3 = [true, false, false, true, false];
console.log(falseToTrue(bools3));//[true, true, true, true, false]


```
