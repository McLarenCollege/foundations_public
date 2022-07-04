  #### Operator Precedence Table
| Precedence | Type        | Example|
| ---------- | ----------- | ------  |
| 1          | Arithmetic  | ` +   * ` |
| 2          | Comparison  | ` > === ` |
| 3          | Logical     | ` && || ` |
| 4          | Assignment  | `=`       |

 Write an expression trace for the following code:
 
  ```js
  let a = 3;
  let b = 2;
  let c = true;
  a =  c || a > b + 6 - 2 * a;
  console.log(a);
```
