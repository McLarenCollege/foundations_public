## Bubble Sort Algorithm with tracing
Write a function that sorts a given array using the Bubble Sort Algorithm and returns the sorted Array.
For e.g.
```js
bubbleSort([1,5,3,0])
```
should return `[ 0, 1, 3, 5 ]` and should console log the following:
```
comparing 1 and 5
comparing 5 and 3
comparing 5 and 0
comparing 1 and 3
comparing 3 and 0
comparing 1 and 0
[ 0, 1, 3, 5 ]
```
```js
bubbleSort([4, 3, 5, 9, 7, 2, 6])
```
should return `[ 2, 3, 4, 5, 6, 7, 9 ]` and should console log the following:
```
comparing 4 and 3
comparing 4 and 5
comparing 5 and 9
comparing 9 and 7
comparing 9 and 2
comparing 9 and 6
comparing 3 and 4
comparing 4 and 5
comparing 5 and 7
comparing 7 and 2
comparing 7 and 6
comparing 3 and 4
comparing 4 and 5
comparing 5 and 2
comparing 5 and 6
comparing 3 and 4
comparing 4 and 2
comparing 4 and 5
comparing 3 and 2
comparing 3 and 4
comparing 2 and 3
BREAK
[ 2, 3, 4, 5, 6, 7, 9 ]
```


```js
function bubbleSort(nums){
// write your code here
}
```
Note: You must use `break` keyword to break out of the loop if there is no swap happening in current iteration.
