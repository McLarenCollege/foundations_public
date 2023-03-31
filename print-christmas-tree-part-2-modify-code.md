```js
let numRows = 5;
for (let row = 0; row < numRows; row++) {
    let spaces = numRows - row;
    let x = "";
    for (let i = 1; i < spaces; i++) {
        x = x + " ";
    }
    x = x + "*";
    console.log(x);
}
```
The above code produces the following output

```
    *
   *
  *
 *
* 
```

Modify the code to produce the following pattern of a Christmas Tree

```js
    *
   ***
  *****
 *******
*********
```
Note this pattern

| Row | Num Spaces | Num Stars|
| ----|------------|----------|
| 1   | 3          | 1        |
| 2   | 2          | 3        |
| 3   | 1          | 5        |
| 4   | 0          | 7        |







