# Maskify

Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it.

Your task is to write a function `maskify`, which changes all but the last four characters of a given string into '#'. The space characters need to be igonered.

#### Example 1
```
console.log(maskify('4207 9992 8701 4443')) 
```

should print `#### #### #### 4443`

#### Example 2
```
console.log(maskify('0 848 943'));






```
should print `# ##8 943`

#### Example 3
```
console.log(maskify('abcdefghijklmnopqrstuvwxyz'));
```

should print `######################wxyz`

#### Example 4
```
console.log(maskify('abcdefghijklmnopqrstuv       wxyz'));
```

should print `######################       wxyz`

#### Example 5
```
console.log(maskify('abcdefghijklmnopqrstuv       w x  y   z'));
```

should print `######################       w x  y   z`

#### CODE TEMPLATE

```js
function maskify(str){
// write your code here
}
console.log(maskify('0 848 943'));// `# ##8 943`
console.log(maskify('4207 9992 8701 4443'));// `#### #### #### 4443`
console.log(maskify('abcdefghijklmnopqrstuvwxyz'));// `######################wxyz`
console.log(maskify('abcdefghijklmnopqrstuv       wxyz'));// `######################       wxyz`
console.log(maskify('abcdefghijklmnopqrstuv       w x  y   z'));// `######################       w x  y   z`
```
