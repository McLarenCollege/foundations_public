# Sum of Diagonals of a Square Matrix
Write a function that accepts a two dimensional matrix and returns the sum of the two diagonals.
* The matrix should be a square matrix (ie. equal number of rows and columns)
* You can use only one loop.

### Example 1:
```js
[[1,2,3],
 [4,5,6],
 [7,8,9]]
```
Sum of the two diagonals is 1 + 5 + 9 + 3 + 5 + 7 = 30

### Example 2:

```js
[[1,-2, 1,-4],
 [5, 6, 7, 8],
 [1,-3, 2, 0],
 [3, 4, 5,-1]]
 
```

Sum of the two diagonals is 1 + 6 + 2 -1 -4 + 7 -3 + 3 = 11

### Example 3:
```js
[[-1,-2],
 [ 3, 4]]
```
Sum of the two diagonals is -1 + 4 -2 + 3 = 4


### Example 4:

```js
[[5]]

```
Sum = 10


***STARTING ANSWER***
****************************

```js
function sumOfDiagonals(matrix){
// write your code here
}

console.log(sumOfDiagonals([[1,2,3],
                            [4,5,6],
                            [7,8,9]])); // 30
                            
console.log(sumOfDiagonals([[1,-2, 1,-4],
                            [5, 6, 7, 8],
                            [1,-3, 2, 0],
                            [3, 4, 5,-1]])); // 11 
                            
console.log(sumOfDiagonals([[-1,-2],
                            [ 3, 4]])); // 4
                            
console.log(sumOfDiagonals([[1]])); // 2
                            
```
*******************************
