# From Num To Num Loop Trace

Create a loop trace for the following piece of code

```js
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
-------------------------------------------------------------------------------------
Here is a sample loop trace for your reference
### Code
```js
let fromNum = 2;
let toNum = 6;

let sum = 0;

while (fromNum <= toNum){
  if (fromNum % 2 === 0){
   sum += fromNum;
  } 
  fromNum++;
}

console.log(sum);
```

### LOOP TRACE
```
1. while 2 <= 6 (true), sum = 0, fromNum = 2, toNum = 6
2. while 3 <= 6 (true), sum = 2, fromNum = 3, toNum = 6
3. while 4 <= 6 (true), sum = 2, fromNum = 4, toNum = 6
4. while 5 <= 6 (true), sum = 6, fromNum = 5, toNum = 6
5. while 6 <= 6 (true), sum = 6, fromNum = 6, toNum = 6
6. while 7 <= 6 (false), sum = 7, fromNum =7, toNum = 6
```
CONSOLE
```
12
```
