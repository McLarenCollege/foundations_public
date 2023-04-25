Given an array create a function that returns true/false depending on if the array is symmetrical.

A symmetrical array is always of odd length and the corrosponding digits to the left and right of the centre digit are equal.

For eg. 

```js
 [ 1, 2, 2, 1]  // Not symmetrical since the length is 4 (an even number)
 
 [5, 9, 8, 9, 5] // symmetrical since the corrosponding left and the right digits to the centre digit (8) are equal 
 
```

```js
function isSymmetrical(input){
 // write code here
}
console.log(isSymmetrical([ 1, 2, 2, 1])); // false
console.log(isSymmetrical([5, 9, 8, 9, 5])); // true
console.log(isSymmetrical([5, 9, 8, 9, 5, 11, 13])); // false
console.log(isSymmetrical(['a', 'c', 'm', 9, 'm', 'c', 'a'])); // true
```
