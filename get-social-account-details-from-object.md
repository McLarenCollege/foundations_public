# Get Social Account Details

Given the login details and website name, create a function that returns the username for that website.

```js
function getUserName(website, userLoginDetails){
// write your code here
}

let loginDetails1 = {
  gmail: {
    username: "v.puppy",
    password: "password123",
  },
  facebook: {
    username: "vivek456",
    password: "passwordabc",
  }
};

let loginDetails2 = {
  gmail: {
    username: "abhishek.kumar",
    password: "monkeymonkey",
  },
  facebook: {
    username: "shrivastava",
    password: "letmein2",
  }
};

console.log(getUserName("gmail", loginDetails1));// "v.puppy"
console.log(getUserName("facebook", loginDetails2));// "shrivastava"

```
