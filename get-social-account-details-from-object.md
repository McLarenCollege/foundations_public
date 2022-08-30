# Get Social Account Details

Given the socialAccountDetails and selectedAccount, create a function that returns the username for the selectedAccount.

```js
function getUserName(account, accountDetails){
// write your code here
}

let selectedAccount1 = "gmail";
let selectedAccount2 = "facebook";
let selectedAccount3 = "yahoo";

let socialAccountDetails1 = {
  gmail: {
    username: "vivekgmail",
    password: "password123",
  },
  facebook: {
    username: "vivekfacebook",
    password: "passwordabc",
  },
  yahoo: {
    username: "vivekyahoo",
    password: "passwordxyz",
  },
};

let socialAccountDetails2 = {
  gmail: {
    username: "abhishekgmail",
    password: "password123",
  },
  facebook: {
    username: "abhishekfacebook",
    password: "passwordabc",
  },
  yahoo: {
    username: "abhishekyahoo",
    password: "passwordxyz",
  },
};

console.log(getUserName(selectedAccount1, socialAccountDetails1));// "vivekgmail"
console.log(getUserName(selectedAccount2, socialAccountDetails2));// "abhishekfacebook"
console.log(getUserName(selectedAccount2, socialAccountDetails1));// "vivekyahoo"
```
