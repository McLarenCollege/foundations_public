Given a book with the structure below and the variable `country`, reduce the price of the book for that
country by 40%.  If there is no existing price for that country then a new key with the country name should be created 
and the default book price set to 10 and default currency set to 'USD'. 

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
let country = 'Nepal';
```
