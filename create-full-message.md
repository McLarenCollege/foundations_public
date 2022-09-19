# Create Full Message

Create a function called `createFullMessage` that accepts `name`, `hourOfDay` and `numOfEvents` as the parameters and returns the appropriate message as shown in the code below.

Your code should reuse the following functions `generateGreeting`, `createGreetingWithName` & `createEventMessage` from these exercises.

- [createEventMessage](https://github.com/McLarenCollege/foundations_public/blob/main/create-event-message.md).

- [generateGreeting](https://github.com/McLarenCollege/foundations_public/blob/main/generate-greeting.md).

- [createGreetingWithName](https://github.com/McLarenCollege/foundations_public/blob/main/create-greeting-with-name.md).



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

