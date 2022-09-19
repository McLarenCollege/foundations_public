
# Create Greeting With Name

Create a function `createGreetingWithName` that accepts `hourOfDay` and `name` as input and generates a greeting message in the below format.

If the name is undefined just the greeting should be printed.

Your code should reuse the `generateGreeting` function as described in this exercise.

- [generateGreeting](https://github.com/McLarenCollege/foundations_public/blob/main/generate-greeting.md)

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
Note: Please notice the exclaimation symbol (!) at the end of the greeting.
