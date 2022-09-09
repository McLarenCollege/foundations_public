Create a function `generateGreeting` that accepts `hourOfDay` as input and returns a greeting message based on the below rules:
- If the `hourOfDay` is greater than  0 and less than or equal to  12, the returned greeting should be `Good Morning`.
- If the `hourOfDay` is greater than 12 and less than or equal to 18, the returned greeting should be `Good Afternoon.
- If the `hourOfDay` is greater than 18 and less than or equal to 24, the returned greeting should be `Good Night`.

```js
function generateGreeting(hourOfDay){
//write your code here
}
console.log(generateGreeting(6));// 'Good Morning'
console.log(generateGreeting(12));// 'Good Morning'
console.log(generateGreeting(16));// 'Good Afternoon'
console.log(generateGreeting(20));// 'Good Night'
```
Create a function `createGreetingWithName` that accepts `hourOfDay` and `name` as input and generates a greeting message in the below format.
If the name is undefined just the greeting should be printed.
The function should call the `generateGreeting` function created earlier to fetch the greeting.

```js
function createGreetingWithName(hourOfDay, name){
// Write your code here
// Make sure to call the generateGreeting function here
}
console.log(createGreetingWithName(6, 'Alex'));// 'Good Morning, Alex`
console.log(createGreetingWithName(13, 'Michael'));// 'Good Afternoon, Michael`
console.log(createGreetingWithName(19, undefined));// 'Good Night`
```
