```js
let weather = {
    London: {
        temp: 37,
        humidity: 44,
    },
    'New Delhi': {
        temp: 33,
        humidity: 85,
    },
};

let user1 = {
    firstName: 'Paul',
    lastName: 'Jones',
    location: {
        city: 'New York',
        latitude: 40.712,
        longitude: 74.006,
    }
};

let user2 = {
    firstName: 'Mahesh',
    lastName: 'Patil',
    location: {
        city: 'Patna',
        latitude: 25,
        longitude: 40,
    }
};
```
Create a function called `getUserWeatherReport` that accepts two parameters the user object and the weather object 
and returns a message in the following format

```js
function getUserWeatherReport(user, weatherObj){
// write your code here
}
console.log(getUserWeatherReport(user1, weather)); // should print 'Hello Paul it is currently 12 degrees Celcius in New York'
console.log(getUserWeatherReport(user2, weather)); // should print 'Hello Mahesh it is currently 32 degrees Celcius in Patna'
```

