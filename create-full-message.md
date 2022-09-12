Create a function `createEventMessage` that accepts `numOfEvents` as a parameter and returns a message based on the below rules :
 - If `numOfEvents` is 0, the function should return the string `no scheduled events`.
 - If `numOfEvents` is 1, the function should return the string `1 scheduled event`.
 - If `numOfEvents` is 2, the function should return the string `2 scheduled events`.

```js
function createEventMessage(numOfEvents){
// write your code here
}
console.log(createEventMessage(0));// 'no scheduled events'
console.log(createEventMessage(1));// '1 scheduled event'
console.log(createEventMessage(2));// '2 scheduled events'
```
Create a function `createFullMessage` that accepts `name`, `hourOfDay` and `numOfEvents` as the parameters generates the appropriate message.
Reuse the functions `generateGreeting`, `createGreetingWithName` & `createEventMessage` created earlier.
Please find the gist link for the generateGreeting exercise [here](https://github.com/McLarenCollege/foundations_public/blob/main/generate-greeting.md).
Please find the gist link for the createGreetingName exercise [here](https://github.com/McLarenCollege/foundations_public/blob/main/create-greeting-with-name.md).

```js
// copy the generateGreeting function here
// copy the createGreetingWithName function here
// copy the createEventMessage function here
function createFullMessage(name, hourOfDay, numOfEvents){
// write your code here
// Make sure to call the createGreetingWithName and createEventMessage function here
}
console.log(createFullMessage('Yousuf', 6, 0));// 'Good Morning, Yousuf! You have no scheduled events today.'
console.log(createFullMessage('Max', 20, 5));// 'Good Night, Yousuf! You have 5 scheduled events today.'
console.log(createFullMessage(undefined, 15, 1));// 'Good Afternoon! You have 1 scheduled event today.'
```
## CODE TEMPLATE
***********************************************************
```js
// copy the generateGreeting function here
// copy the createGreetingWithName function here
// copy the createEventMessage function here

function createFullMessage(name, hourOfDay, numOfEvents){
// write your code here
// Make sure to call the createGreetingWithName and createEventMessage function here
}
console.log(createFullMessage('Yousuf', 6, 0));// 'Good Morning, Yousuf! You have no scheduled events today.'
console.log(createFullMessage('Max', 20, 5));// 'Good Night, Yousuf! You have 5 scheduled events today.'
console.log(createFullMessage(undefined, 15, 1));// 'Good Afternoon! You have 1 scheduled event today.'
```
