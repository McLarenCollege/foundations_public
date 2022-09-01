# Get Full Name from User Object

Write a function that returns the 'full name' of the given user from the userObject.

```js
function getFullName(userObj){
// write your code here
}
let user1 = {
  age: 22,
  hasVoted: false,
  name: "vivek",
  location: "India",
  hobbies: ["dance", "music"],
  "full name": "vivek kumar",
};
let user2 = {
  age: 32,
  hasVoted: true,
  name: "Alex",
  location: "Germany",
  hobbies: ["dance", "music"],
  "full name": "Alex Smith",
};
console.log(getFullName(user1)); // "vivek kumar"
console.log(getFullName(user2)); // "Alex Smith"
```
