# Function Trace Full Name

Write a function trace (not expression trace) for the following code

```js
function fullName(fname, lname) {
 return fname + ' ' + lname;
}

function bar(fname) {
 return fname;
}

function foo(lname) {
 console.log(lname);
}

let res = fullName(bar('John'), foo('Tree'));
console.log(res);
```
