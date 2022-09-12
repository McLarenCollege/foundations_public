
Create a function `createGreetingWithName` that accepts `hourOfDay` and `name` as input and generates a greeting message in the below format.

If the name is undefined just the greeting should be printed.

The function should call the `generateGreeting` function  to fetch the greeting.

Please find the gist link for the generateGreeting function [here](https://github.com/McLarenCollege/foundations_public/blob/main/generate-greeting.md)

```js
// copy the generateGreeting function here
function createGreetingWithName(hourOfDay, name){
// Write your code here
// Make sure to call the generateGreeting function here
}
console.log(createGreetingWithName(6, 'Alex'));// 'Good Morning, Alex!`
console.log(createGreetingWithName(13, 'Michael'));// 'Good Afternoon, Michael!`
console.log(createGreetingWithName(19, undefined));// 'Good Night!`
```
