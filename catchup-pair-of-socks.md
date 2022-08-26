### Pair of socks
Determine the number of pair of socks you can constitute from the socks you have in your drawer.

Given an array describing the color of each sock, return the number of pairs you can constitute, assuming that only socks of the same color can form pairs.

Examples:
```js
input = ["red", "green", "red", "blue", "blue", "blue"]
result = 2 (1 red pair + 1 blue pair)

input = ["red", "red", "red", "red", "red", "blue", "blue", "blue"]
result = 3 (2 red pairs + 1 blue pair)
```

### Hint
If you need to get a list of keys for an object, pass the object into the [Object.keys()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys) function

***CODE TEMPLATE***
************************
```js
function countPairs(arr){
// write your code here
}
console.log(countPairs(["red", "green", "red", "blue", "blue"])); // 2
console.log(countPairs(["red", "red", "red", "red", "red", "red"]));// 3
console.log(countPairs(["red", "green", "black", "blue", "green"])); // 1
console.log(countPairs(["red", "green", "red", "blue", "blue", "blue"])); // 2
console.log(countPairs(["red", "red", "red", "red", "red", "blue", "blue", "blue"])); // 3
```
***********************
