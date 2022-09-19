# Convert False to True

Given an array of booleans change any false values to true that occur before the first true value.


```js
function falseToTrue(booleans){
  // write your code here
}

let bools1 = [false, false, false, true, false, false, true];
console.log(falseToTrue(bools1)); // should print [true, true, true, true, false, false, true]

let bools2 = [false, false, false];
console.log(falseToTrue(bools2));// should print [true, true, true]

let bools3 = [true, false, true];
console.log(falseToTrue(bools3));// should print [true, false, true]
```

