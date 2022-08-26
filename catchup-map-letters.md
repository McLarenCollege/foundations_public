## Map the Letters in a String
Given a word, create an object that stores the indexes of each letter in an array.
- Make sure the letters are the keys.
- Make sure the indexes are stored in an array and those arrays are values.

```js
function mapLetters(str){
// write your code here
}
console.log(mapLetters("dodo"));// ➞ { d: [0, 2], o: [1, 3] }

console.log(mapLetters("froggy"));// ➞ { f: [0], r: [1], o: [2], g: [3, 4], y: [5] }

console.log(mapLetters("grapes"));// ➞ { g: [0], r: [1], a: [2], p: [3], e: [4], s: [5] }
```
#### Notes
All strings given will be lowercase.
