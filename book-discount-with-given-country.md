# Book Discount With Given Country
Given a book with the structure below and the variable `country`, create a function that accepts the book object and a country name as a parameter,reduces the price of the book for that country by 40% and returns the book object.
If there is no record for that country then the book object should not be modified. 

```js
let book = {
    author: 'Daniel Kahneman',
    title: 'Thinking, Fast And Slow',
    yearPublished: 2012,
    bestseller: true,
    pricePerCountry:
        {
            'Australia': {amount: 20.0, currency: 'AUD'},
            'India': {amount: 500, currency: 'INR'},
            'United States': {amount: 16.5, currency: 'USD'},
            'Canada' :{amount :19, currency :'CAD'}
        }
};
function reducePrice(bookObj, country){
    // write your code here
    return bookObj;
}
console.log(JSON.stringify(reducePrice(book, "India")));
console.log(JSON.stringify(reducePrice(book, "United States")));
console.log(JSON.stringify(reducePrice(book, "Brazil")));
```
