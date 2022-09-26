# Boxes In Rows

There is an array of boxes where each element of an array represents the number of boxes stacked on top of each other in that column.
For eg. `boxes=[4,1,2,3,2,1]`.

This is a row of boxes where the first column of boxes has 4 boxes stacked on top of each other. The second column has 1 box, the third column
has 2 boxes stacked on top of each other and the fourth column has 3 boxes stacked on top of each other and so on.
So the boxes look like this:
```js
              B
              B     B
              B   B B B
              B B B B B B
 ```
 Your task is to write a function that accepts this array and returns an array containing the number of boxes present in each row starting 
 from the bottom.
 For eg. the result for the above eg. would be `[6,4,2,1]` as there are 6 boxes in the bottom-most row, 4 boxes in the row above the bottom row , 2 boxes in the row above it and 1 box in the topmost row.
 
 Hence.
 ```js
 console.log(boxesInRows([4,1,2,3,2,1])) // returns [6,4,2,1]
 ```
 ***CODE TEMPLATE***
 **************************
 ```js
 function boxesInRows(boxes){
 // write your code here
 }
 console.log(boxesInRows([4, 1, 2, 3, 2, 1]));// returns [6, 4, 2, 1]
 console.log(boxesInRows([4, 0, 3, 1, 2]));// returns [4, 3, 2, 1]
 console.log(boxesInRows([0, 0, 3]));// returns [1, 1, 1]
 ```
 **************************
