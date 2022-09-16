Create a function generateGreeting that accepts hourOfDay as input and returns a greeting message based on the below rules:

- If the hourOfDay is less than or equal to 12, the returned greeting should be 'Good Morning'.
- If the hourOfDay is greater than 12 and less than or equal to 18, the returned greeting should be 'Good Afternoon'.
- If the hourOfDay is greater than 18, the returned greeting should be 'Good Night'.

```js
function generateGreeting(hourOfDay){
//write your code here
}
console.log(generateGreeting(6));// 'Good Morning'
console.log(generateGreeting(12));// 'Good Morning'
console.log(generateGreeting(16));// 'Good Afternoon'
console.log(generateGreeting(20));// 'Good Night'
```
