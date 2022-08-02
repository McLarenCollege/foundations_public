

```js
function printPattern(n) {
    let str = '';
    let i = 0;
    while (i < n) {
        str += '*';
        console.log(str);
        i++;
    }
}
printPattern(4);
```
The above code prints the following pattern .
Your task is to convert the while loop to the for loop. 

```js
For rows = 2, the pattern should print like this:
*
**
```
```js
For rows = 4, the pattern should print like this:
*
**
***
****
```
rows will always be a positive integer.

***CODE TEMPLATE***
*******************

```js
function printPattern(rows){
// write your code here
}
printPattern(2);
printPattern(4);
```
**************

Here is a sample for loop for your reference

<img src = "https://github.com/McLarenCollege/foundations_public/blob/main/images/guess-output-for-loop-star-hash.png" width =800 />
