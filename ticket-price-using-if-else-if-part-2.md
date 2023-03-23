### Part1

Given two variables age and day, write code to determine the ticket price as per the following rules :
- For a child (age less than 12) the ticket price is always 50. 

- For a senior citizen(age greater than or equal to 65):

      i) if it is weekend (Saturday/Sunday) the price is 70.
      
      ii)if it is a  weekday the price is 80.

- For everybody else the price is always 100. 
```js
let age = 21;
let day = 'Monday';
let price;  

//write your code here to determine the price for the given age and day.

console.log("Ticket price is " + price);
```
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
