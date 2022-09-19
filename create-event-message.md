Create a function `createEventMessage` that accepts `numOfEvents` as a parameter and returns a message based on the below rules :
 - If `numOfEvents` is 0, the function should return the string `no scheduled events`.
 - If `numOfEvents` is 1, the function should return the string `1 scheduled event`.
 - If `numOfEvents` is 2 or more, the function should return  a string like this `2 scheduled events`.

```js
function createEventMessage(numOfEvents){
// write your code here
}
console.log(createEventMessage(0));// 'no scheduled events'
console.log(createEventMessage(1));// '1 scheduled event'
console.log(createEventMessage(2));// '2 scheduled events'
console.log(createEventMessage(8));// '8 scheduled events'
```
