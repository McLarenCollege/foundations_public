Write a function `updateProfile` that takes in a profile object and a key-value pair, and modifies that profile object with the given key-value pair added or updated. Also return the profile object from function. 

```js
function updateProfile(profile, key, value) {
  // write your code here
}

const profile = {
  name: 'John Doe',
  age: 30,
  email: 'john.doe@example.com',
  address: {
    street: '123 Main St',
    city: 'Anytown',
    state: 'CA',
    zip: '12345'
  }
};

const updateProfileProperty = updateProfile(profile, 'email', 'jane.doe@example.com');
console.log(updateProfileProperty); // { name: 'John Doe', age: 30, email: 'jane.doe@example.com', address: { ...

const newProfileProperty = updateProfile(profile, 'phone', '555-555-5555');
console.log(newProfileProperty); // { name: 'John Doe', age: 30, email: 'jane.doe@example.com', phone: '555-555-5555', ...

```
