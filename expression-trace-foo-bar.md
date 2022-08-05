// Create an expression trace for line numbers 4 and 5  and evaluate the output.

let a = [{ foo: 'x', bar: 'y', k: 0 }, 'oo', [0, 2]]
let b = [a[2], { blah: a }];
console.log(b[1].blah[0]['f' + a[1]] + 'p');
