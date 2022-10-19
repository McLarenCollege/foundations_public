A cinema is showing movie to childeren (age < 18) for free and charging adults (age >= 18) with $10 per ticket.

For adults:
```
Please pay $10.
Please proceed to the cinema hall.
```
For children:
```
 Please proceed to the cinema hall.
```
#### CODE
```js
let age = 34;
if(age >= 18){
  console.log("Please pay $10.");
  console.log("Please proceed to the cinema hall.");
}
else{
  console.log("Please proceed to the cinema hall.");
}
```

Write code to achieve the same output  WITHOUT using an else block.
Note: You can use just a single if statement
