Guess the output of the following code :

```js
let a = 1;
let b = 5;
function foo() {
  let a = 10;
  if (true) {
    let a = 15;
    let b = 20;
    console.log(a);
    console.log(b);
  }
  console.log(a);
  console.log(b);
}
foo();
console.log(a);
console.log(b);
```
