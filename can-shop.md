Implement the function canShop that takes an array of objects (groceries) and the balance amount and checks if we can purchase all the items that are listed in grocery list or not.

```js
function canShop(groceryList, balance) {
    // write code here
}

let list1 = [
    { product: "Milk", quantity: 1, price: 1.50 },
    { product: "Cereals", quantity: 1, price: 2.50 }
];

console.log(canShop(list1, 5));// ➞ true  because we have sufficient amount to purchase all the grocery items.

let list2 = [
    { product: "Milk", quantity: 1, price: 1.50 },
    { product: "Eggs", quantity: 12, price: 0.10 },
    { product: "Bread", quantity: 2, price: 1.60 },
    { product: "Cheese", quantity: 1, price: 4.50 }
];

console.log(canShop(list2, 10));// ➞ false  As we donot have sufficient amount to purchase all the grocery items.

```
