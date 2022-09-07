# Create object from string
### Part1
Write a function that creates an Object from the given string with the characters as keys and the values as 'true' for the given key.

The function should return the consturcted Object.

```js
function createObject(str){
// write your code here
}
console.log(createObject("hello")); // {'h' :true, 'e' :true, 'l' :true, 'o' :true}
console.log(createObject("aeroplane"));//{'a': true, 'e' :true,'r' :true, 'o' :true, 'p' :true, 'l' :true,'n' :true}
```
# Check repetition in string
#### Part2
Write a function that checks if a key is repeated in the string by creating an Object for the given string. If a key is repeated 
the function will return true. If no key is repeated it will return false.

```js
function checkRepetition(str){
// write your code here
}
console.log(checkRepetition("hello"));// true
console.log(checkRepetition("zebra"));// false

```
# Create object showing repetitions
#### Part3
Write a function that creates an Object from the given string with the characters as keys and the repetitions for the key as values for the key.

```js
function createObjectShowingRepetitions(str){
// write your code here
}
console.log(createObjectShowingRepetitions("hello")); // {'h' :1,'e' :1, 'l' : 2, 'o' :1}
console.log(createObjectShowingRepetitions("aeroplane"));// {'a' :2, 'e' :2, 'r' :1, 'o' :1, 'p' :1, 'l' :1,'n':1}
```
