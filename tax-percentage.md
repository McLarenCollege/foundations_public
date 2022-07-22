
Given the income of a person and whether he or she has children, calculate the tax percentage based on the following rules:

- If income is above 50,000 the tax is 45% otherwise 40%
- If there are children then the tax percentage decreases by 2%.

For example, 

- If a person with children has an income of 60,000 then the tax is 43%
- If a person without any children has an income of 20,000 then the tax is 40%
- If a person with children has an income of 15,000 then the tax is 38%


```js
let income = 60000;
let hasChildren = true;
let taxPercentage;

// write your code here

console.log("The applicable tax percentage is " + taxPercentage + "%");
```
