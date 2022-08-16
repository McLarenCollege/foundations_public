Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it.

Your task is to write a function `maskify`, which changes all but the last four characters of a given string into '#'. The space characters need to be igonered.

eg.
```
console.log(maskify('4207 9992 8701 4443')) 
```
<pre>
should print `#### #### #### 4443`
</pre>
```
console.log(maskify('abcdefghijklmnopqrstuvwxyz'));
```
<pre>
should print `######################wxyz`
</pre>

```
console.log(maskify('abcdefghijklmnopqrstuv       wxyz'));
```
<pre>
should print `######################       wxyz`
</pre>
```
console.log(maskify('abcdefghijklmnopqrstuv       w x  y   z'));
```
<pre>
should print `######################       w x  y   z`
</pre>

```js
function maskify(str){
// write your code here
}
console.log(maskify('4207 9992 8701 4443'));//`#### #### #### 4443`
console.log(maskify('abcdefghijklmnopqrstuvwxyz'));// `######################wxyz`
console.log(maskify('abcdefghijklmnopqrstuv       wxyz'));//`######################       wxyz`
console.log(maskify('abcdefghijklmnopqrstuv       w x  y   z'));// `######################       w x  y   z`
```
