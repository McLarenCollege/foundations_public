Given the socialAccountDetails and selectedAccount, create a function that returns the username for the selectedAccount.

```js
function getUserName(account, accountDetails){
// write your code here
}
let selectedAccount = "gmail";

let socialAccountDetails = {
  gmail: {
    username: "vivek123",
    password: "password123",
  },
  facebook: {
    username: "vivek",
    password: "password",
  },
};
console.log(getUserName(selectedAccount, socialAccountDetails));
```
