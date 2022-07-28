Create a function 'checkPrime' that checks if the given number is prime or not and returns true/false accordingly.
For Example:

To check if a number is prime or not , we start from 2 and go uptil one less that number and check if its modulus is equal to zero or not.

For the Number 5
```
5 % 2 !== 0
5 % 3 !== 0
5 % 4 !== 0
```
Hence 5 is prime.

For the Number 25
```
25 % 2 !== 0
25 % 3 !== 0
25 % 4 !== 0
25 % 5 === 0

```
Hence 25 is not prime.

Now consider 7, what modulo operations will be performed ?

***CODE TEMPLATE***
***************************
```js
function checkPrime(num){
// write your code here
}
console.log(checkPrime(2));// true
console.log(checkPrime(3));// true
console.log(checkPrime(4));// false
console.log(checkPrime(5));// true
console.log(checkPrime(29));// true
console.log(checkPrime(33));// false
console.log(checkPrime(90));// false
console.log(checkPrime(101));// true
```
******************************
