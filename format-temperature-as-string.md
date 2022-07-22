Write a function called formatTemperatureAsString which takes two parameters
The first parameter is the temperature in celsius
The second parameter is whether to convert to fahrenheit
The function should return a formatted string like "37.4°F" or "17°C"

Note: If the second parameter is true, the function should call 
the convertToFahrenheit function you wrote earlier.

```js
let result = formatTemperatureAsString(12, false);
console.log(result);  // should print 12°C
result = formatTemperatureAsString(37, true);
console.log(result);  // should print 98.6°F
```
