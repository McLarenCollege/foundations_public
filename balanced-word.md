
We can assign a value to each character in a word, based on their position in the alphabet (a = 1, b = 2, ... , z = 26). A balanced word is one where the sum of values on the left-hand side of the word equals the sum of values on the right-hand side. For odd length words, the middle character (balance point) is ignored.

Write a function that returns true if the word is balanced, and false if it's not.

HINT : you are given a string  str = "abcdefghijklmnopqrstuvwxyz"

Examples:

balanced("zips") ➞ true

// "zips" = "zi|ps" = 26+9|16+19 = 35|35 = true

balanced("brake") ➞ false

// "brake" = "br|ke" = 2+18|11+5 = 20|16 = false

```js
function balanced(word){
let str = "abcdefghijklmnopqrstuvwxyz";
// write your code here
}
console.log(balanced("a");//true
console.log(balanced("aa");//true
console.log(balanced("zips"));// true
console.log(balanced("brake"));//false
console.log(balanced("azby"));//true
```
