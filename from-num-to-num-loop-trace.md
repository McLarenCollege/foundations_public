// Create a loop trace for the following piece of code
// Here is a sample loop trace for your reference: https://gist.github.com/McLarenCollege/1c9ab3a99fe631ddd65921107e68aeee

// Tip: Here is the first line of the loop trace:
// 1. while 5 <= 10 (true), fromNum=5, toNum=10, sum=0
```
let fromNum = 5;
let toNum = 10;

let sum = 0;

while (fromNum <= toNum){
 if (fromNum % 3 === 0){
   sum = sum + fromNum + 1;
 } 
 fromNum++;
}

console.log(sum);
```
