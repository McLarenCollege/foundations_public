Create a function `getNewDelhiWeatherReport` that accepts the weather object as a parameter and returns a string in the following format:

`In New Delhi the temperature is 32 and the humidity is 80.`

```js

let weather = {
    London: {
        temp: 37,
        humidity: 44,
    },
    'New Delhi': {  
        temp: 32,
        humidity: 80,
    }
};

function getNewDelhiWeatherReport(weatherObj){
 // write code here
}

console.log(getNewDelhiWeatherReport(weather)); // 'In New Delhi the temperature is 32 and the humidity is 80.'

```
