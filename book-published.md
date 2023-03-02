# book-published

Given an author name and a year create a function that returns true if the actor had a book published during that year.

```js
let historicalAuthors = {
  'Mark Twain': [
    { name: 'The Gilded Age', year: 1873 },
    { name: 'The American Claimant', year: 1892 }, 
    { name: 'The Mysterious Stranger', year: 1916 }
  ],
  'Leo Tolstoy': [
    { name: 'War And Peace', year: 1867 }, 
    { name: 'Two Old Men', year: 1885 }, 
    { name: 'The Forged Coupon', year: 1911 }
  ],
  'Arthur Conan Doyle': [
    { name: 'A Study in Scarlet', year: 1887 }, 
    { name: 'The Sign of Four ', year: 1890 }, 
    { name: 'The Hound of the Baskervilles', year: 1902 }
  ],
}

function bookPublished(authors, name, year) {
  // write your code here
}
console.log(bookPublished(historicalAuthors, 'Leo Tolstoy', 1911)); // true
console.log(bookPublished(historicalAuthors, 'Arthur Conan Doyle', 1891)); // false
console.log(bookPublished(historicalAuthors, 'Mark Twain', 1892)); // true

```
