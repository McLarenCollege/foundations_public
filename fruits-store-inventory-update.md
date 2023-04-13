Write a function `recordSale(store, product, quantity)` which updates the `store` object by decreasing the inventory quantity for the given product and increasing the sales quantity for that product. The product will always match one of the items in inventory and sales. 

If the given quantity is more than the available inventory then the function should return `false` and not update the store object, otherwise it should update it and return `true`

```js
function recordSale(store, product, quantity){
  // Write your code here
  
}

let fruitShop = {
  name: 'Fresh Fruits Market',
  location: 'New York',
  inventory: {
    apple: { price: 1.5, quantity: 100 },
    banana: { price: 0.75, quantity: 150 },
    orange: { price: 1.0, quantity: 75 }
  },
  sales: {
    apple: { quantity: 25 },
    banana: { quantity: 40 },
    orange: { quantity: 30 }
  }
};
recordSale(fruitShop, 'orange', 140); // should return false
recordSale(fruitShop, 'orange', 50); // should return false, and fruitShop object should be updated
```
