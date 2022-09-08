# Book Discount

### Part 1 
Draw the Object Diagram for the below book Object.

```js
let book = {
    author: 'Daniel Kahneman',
    title: 'Thinking, Fast And Slow',
    yearPublished: 2012,
    bestseller: false,
    pricePerCountry:
        {
            'Australia': {amount: 20.0, currency: 'AUD'},
            'India': {amount: 500, currency: 'INR'},
            'United States': {amount: 16.5, currency: 'USD'}
        }
};
```
### Part2
Given the book structure above, if the book was published before 2017 and is not a bestseller, reduce the Indian price by 10% and the United States price by 20%.
 
 Hint: Use an if statement.
 
### Part3
If the book was published before 2017 and is not a bestseller, write the code to increase the Australian price by 20% by creating a reference to the object which is a value for the 'Australia` property.
