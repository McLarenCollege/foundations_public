
## Anagram
An anagram is a word formed by rearranging the letters of a different word using all the original letters exactly once.


Write a function that accepts two strings and checks whether the first string is an anagram of the second string. If yes, the function   returns true , else it returns false.
The words passed to the function will always be lowercase.

NOTE: Do not use the `sort` method.

```js
  
function isAnagram(word1, word2) {
  // write your code here
}
console.log(isAnagram("silent", "listen")); // true
 
console.log(isAnagram("stressed", "deserts"));
  
  
  
  
console.log(isAnagram("stressed", "desserts")); // true
  
console.log(isAnagram("grab", "brag")); // true
  
```
HINT:
- For each word create an Object where the keys are the letters of the word and the values are the number of times the letter appears in the word. Then compare the two Objects.
- You can use the Object.keys() method to create an array containing the name of each property in an Object:
 
  ```js
  let myObj = {name:'Raj', age:20, isConnected:true };
  let keys = Object.keys(myObj);
  // keys is now ['name', 'age', 'isConnected']
  

 
