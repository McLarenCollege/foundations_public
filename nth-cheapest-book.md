
Given an array of book objects and a number n, return the book object with the nth-cheapest price.
eg.

```js
function findNthCheapest(books, n){
// write your code here
}
console.log(findNthCheapest([
    {title:'Fox In Socks', price: 32.20},
    {title:'The Cat In The Hat', price: 16.20},
    {title:'Green Eggs and Ham', price: 5.20},
    {title:'Thinking Fast and Slow', price: 10.80},
    {title:'War and Peace', price: 52.50}
], 3)); //  {title:'The Cat In The Hat', price: 16.20}

console.log(findNthCheapest([
    {title:'Fox In Socks', price:32.20},
    {title:'War and Peace', price: 52.50},
    {title:'Green Eggs and Ham', price: 5.20}
], 1)); //  {title:'Green Eggs and Ham', price: 5.20}

console.log(findNthCheapest([])); // undefined
```



Note:
- All books will have a different price
- Do not sort the list
- The return value must point to an object in the original list, not a copy of that object
- If n is greater than the number of books, return `undefined`
