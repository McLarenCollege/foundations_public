# Second-Cheapest Book

Given an array of book objects, return the book object with the second-cheapest price.
eg.

```js
function findSecondCheapest(books){
// write your code here
}
console.log(findSecondCheapest([
    {title:'Fox In Socks', price: 32.20},
    {title:'The Cat In The Hat', price: 16.20},
    {title:'Green Eggs and Ham', price: 5.20},
    {title:'Thinking Fast and Slow', price: 10.80},
    {title:'War and Peace', price: 52.50}
])); // {title:'Thinking Fast and Slow', price: 10.80}

console.log(findSecondCheapest([
    {title:'Fox In Socks', price:32.20}
])); //  {title:'Fox In Socks', price:32.20}

console.log(findSecondCheapest([])); // undefined
```



Note:
- If the array is empty, return `undefined`
- If there is only one item in the array, return that item
- All books will have a different price
- Do not sort the list
- The return value must point to an object in the original list, not a copy of that object
