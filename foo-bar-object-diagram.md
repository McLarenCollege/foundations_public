Draw the object diagram for the following code and evaluate the output.

```js
let a = [{ foo: 'x', bar: 'y', k: 0 }, 'oo', [0, 2]]
let b = [a[2], { blah: a }];
b[0][a[1] + 'p'].foo = 'k';

console.log(b[1].blah[0]['f' + a[1]] + 'p');
```

TIP: The operators . and [] have equal precedence so evaluate them from Left to Right
