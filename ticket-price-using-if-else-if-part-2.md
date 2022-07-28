### Part2
Below is the solution for the code and it  uses if-else. 
Modify the Code and use if-else-if to make it cleaner
```js
let age = 21;
let day = "Monday";
let price;
if (age < 12) {
    price = 50;
}
if (age >= 65) {
    if (day === "Saturday" || day === "Sunday") {
        price = 70;
    }
    else {
        price = 80;
    }
}
if (age > 12 && age < 65) {
    price = 100;
}
console.log("Ticket price is " + price);
```
