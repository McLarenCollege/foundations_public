Given an array of names, write a function that returns the index of the given target name using a `for` loop.
If the name is not present return `-1`.

Note: There can be duplicate names in the array you have to return first occurence of a given name.

```js
function targetNameIndex(names,target){
  // write your code here
}
let names = ['Vivek','Mark','Pawan','Arnav','Akshat','Zhen','Arnav'];
let targetName = 'Arnav';
console.log(targetNameIndex(names,targetName)); // 3
console.log(targetNameIndex(names,"Abhishek")); // -1
```
