Write a function that encodes a given string by constructing a new string adding every third character.

Encoding process begins with the first character and every third character is added to the encoded message till we reach the end of the string.
The encoding process then starts with the second character and we jump every two characters till we reach the end of the string.
Then we start a similar process starting with the third character.

Please refer to the image to understand the encoding process.

https://raw.githubusercontent.com/McLarenCollege/public_images/main/encode.jpg

***CODE TEMPLATE***
********************************
```js
function encode(str){
// write your code here
}
let msg = 'ICE CREAM';
console.log(encode(msg)); // "I ECCAERM"
console.log(encode("Today is Monday"));// "TaiMdoysoad  ny"
```
*********************************
