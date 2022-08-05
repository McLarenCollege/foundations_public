Modify the below code and create a function called `printChristmasTreePart1` which takes in a number `n` and prints the following tree pattern on the console.

***CODE TEMPLATE***
****************
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
*******************

For n = 4 the function `printChristmasTreePart1(4)` should produce the following output

```js
   *
  *
 *
*
```
Note this pattern

| Row | Num Spaces |
| ----|------------|
| 1   | 3          | 
| 2   | 2          | 
| 3   | 1          | 
| 4   | 0          |







