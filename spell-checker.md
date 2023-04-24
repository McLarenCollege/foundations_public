# Spell Checker

## Part 1
Write a function called `closeMatch` which takes two strings and returns true if they 
have the same length and differ by only one character.

***CODE TEMPLATE***
**************************
```js
function closeMatch(str1, str2){
// write your code here
}
console.log(closeMatch('bard', 'barn')); // should return true
console.log(closeMatch('broad', 'road')); // should return false
console.log(closeMatch('rated', 'barn')); // should return false
console.log(closeMatch('strength', 'steength')); // should return true
console.log(closeMatch('yesterday', 'yesterday')); // should return false
```  
**********************************

## Part 2
Write a function called `spellCheck` which takes two parameters:
1. A test word which may or may not be spelled correctly
2. A list of dictionary words

The function should return the list of dictionary words where the test word is a close match as defined in Part 1.

If the word is present in the dictionary it should return an empty array.

***CODE TEMPLATE***
************************
```js
function spellCheck(word, dictionary){
// write your code here
}
let smallDictionary = [
    "jail",
    "sail",
    "cat",
    "table",
    "safe",
    "call",
    "sane",
];
console.log(spellCheck('cail', smallDictionary)); // should return ['jail', 'sail', 'call']
console.log(spellCheck('sane', smallDictionary)); // should return [] because it's correctly spelled
console.log(spellCheck('sate', smallDictionary)); // should return ['safe', 'sane']
```
********************************

Please watch this [video](https://youtu.be/mFcWQj3PQ3E) for a hint for the problem:

