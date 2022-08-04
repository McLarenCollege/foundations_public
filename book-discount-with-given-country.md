 Given a book with the structure below and the variable `country`, reduce the price of the book for that
country by 40%.  If there is no record for that country then the book object should not be modified. 
 Check your code for different values of country. ('Australia','United States','Kenya')
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
let country = 'India';
```
