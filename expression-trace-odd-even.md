Write the expression trace for the last line and evaluate the output

```js
let arr = [1, 3, 4, 2, 9, 8, 7, 6, 5, 10]
let data = {
    numbers: [
        { odd: [arr[0], arr[4], arr[1], arr[6], arr[8]] },
        { even: [arr[3], arr[2], arr[7], arr[5], arr[9]] }
    ],
    primeNumbers: {
        first10: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29]
    }
}
console.log(data.primeNumbers.first10[data.numbers[0].odd[3] % 4])
```
