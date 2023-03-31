Modify the below code 

```js
for (let row = 0; row < 3; row ++) {
  let n = row - 3;
  let stars = n * n;
  let x = ">";
  for (let i = 0; i < stars; i++) {
      x = x + "*";
  }
  console.log(x);
}
```
to print the following pattern

```
  *
 *
* 
```
( 2 spaces followed by a star, 1 space and a star , 1 star)
