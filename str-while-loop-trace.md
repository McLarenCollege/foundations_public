Write the loop trace for the following piece of code: 

```js
let i = 1;
while (i <= 3) {
  let j = 1;
  let str = '';
  while (j <= i) {
    str = str + j;
    j++;
  }
  console.log(str);
  i++;
}
```

LOOP TRACE
1. while 1 <= 3 (true), i = 1
  1.1 while 1 <= 1 (true), i = 1, j = 1, str = ""
  1.2 while 2 <= 1 (false), i = 1,//TODO
2. while 2 <= 3 (true), i = 2, j = 1, str =""
  2.1 while ...
  2.2 while ...
  ...
3. while ...
  3.1 while ...
  3.2 while ...
  ...
...
