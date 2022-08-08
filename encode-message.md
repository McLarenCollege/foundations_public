Write a function that encodes a given string by constructing a new string adding every third character.

The encoding process is as follows:
- Begin with the first character and add every third character to the encoded message until we reach the end of the string.
- Then start with the second character and we jump every two characters until we reach the end of the string
- Then start a similar process starting with the third character

Please refer to the image to understand the encoding process:
https://raw.githubusercontent.com/McLarenCollege/public_images/main/encode.jpg

Tip: If you are struggling, first write your code without a loop and assume the input has exactly 9 characters, 
then check you get the correct output for 'ICE CREAM'

```js
function encode(str){
  // write your code here
}

console.log(encode('ICE CREAM')); // "I ECCAERM"

console.log(encode('Today is Monday'));// "TaiMdoysoad  ny"

```
