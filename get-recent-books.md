Write a function that takes an array of objects representing books and returns a new array that contains only the books that have been published in the last 5 years.

Each book object will have the following properties:

- `title`: a string representing the book's title
- `author`: a string representing the book's author
- `publisher`: a string representing the book's publisher
- `year`: a number representing the year the book was published


```js
function recentBooks(books) {
  // write your code here
}

const books = [
  {
    title: 'The Catcher in the Rye',
    author: 'J.D. Salinger',
    publisher: 'Little, Brown and Company',
    year: 1951
  },
  {
    title: 'The Girl on the Train',
    author: 'Paula Hawkins',
    publisher: 'Riverhead Books',
    year: 2019
  },
  {
    title: '1984',
    author: 'George Orwell',
    publisher: 'Secker & Warburg',
    year: 1949
  },
  {
    title: 'The Hunger Games',
    author: 'Suzanne Collins',
    publisher: 'Scholastic Press',
    year: 2021
  },
  {
    title: 'The Great Gatsby',
    author: 'F. Scott Fitzgerald',
    publisher: 'Scribner',
    year: 1925
  }
];

console.log(recentBooks(books)); // [{title: 'The Girl on the Train', author: 'Paula Hawkins', publisher: 'Riverhead Books', year: 2019}, {title: 'The Hunger Games', author: 'Suzanne Collins', publisher: 'Scholastic Press', year: 2021}]
```
