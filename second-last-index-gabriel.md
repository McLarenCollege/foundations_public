# Second Last Index Of Gabriel

Given an array of names create a function `secondLastIndex` that returns the second last index of  the name `Gabriel`  in the array.

If the name `Gabriel` does not exist at least twice, return -1.


```js
function secondLastIndex(namesList){
// write your code here
}

let names = ["John", "Gabriel", "Steve", "Sam", "Gabriel"];
console.log(secondLastIndex(names)); // should return 1
names = ["John", "Gabriel", "Garry", "Steve", "Sam", "Gabriel", "Gabriel"];
console.log(secondLastIndex(names)); // should return 5
names = ["John", "Gabriel", "Steve", "Sam"];
console.log(secondLastIndex(names)); // should return -1
names = ["John", "Gary", "Steve", "Sam"];
console.log(secondLastIndex(names)); // should return -1

```
