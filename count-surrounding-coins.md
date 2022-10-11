# Count Surrounding Coins
You are given a square board with coins ($) at certain positions.

Your task is to fill the empty boxes(' ') with appropriate numbers.

For every empty box you have to count the number of coins ($) present in the immediate surrounding blocks.

For example,
```js
[[' ',' ','$'],
 [' ','$',' '],
 ['$',' ','$']]
```
should return 
```js
[[ 1 , 2 ,'$'],
 [ 2 ,'$', 3 ],
 ['$', 3 ,'$']]
```

***CODE TEMPLATE***
***********************
```js
function countNeighbouringCoins(board){

 //write your code here
 
}
console.log(countNeighbouringCoins([[' ',' ','$'],
                                    [' ','$',' '],
                                    ['$',' ','$']]));
//should return 
//[[ 1 , 2 ,'$'],
// [ 2 ,'$', 3 ],
// ['$', 3 ,'$']]

console.log(countNeighbouringCoins([[' ',' '],
                                    [' ','$']]));
//should return 
//[[ 1 , 1 ],
// [ 1 ,'$']]

console.log(countNeighbouringCoins([[' ',' ','$',' '],
                                    [' ','$',' ',' '],
                                    ['$',' ','$',' '],
                                    [' ',' ','$',' ']]));
//should return 
//[[ 1 , 2 ,'$', 1 ],
// [ 2 ,'$', 3 , 2 ],
// ['$', 4 ,'$', 2 ],
// [ 1 , 3 ,'$', 2 ]]

```
**************************

Please watch this [video](https://youtu.be/6VmMPf73znA) for a hint for the problem

