# Weather Report Function

Create a function formatWeatherReport which
takes 3 parameters: cityName, tempC and showFahrenheit
and returns the weather report string in the followoing format:

```
In ________ it is currently ______
```

For example:

```
In Vancouver it is currently 🥶 37.4°F 
In New Delhi it is currently 🥵 35°C 
In Dubai it is currently 🥵 39°C 
In Sydney it is currently 😊 17°C 
In Miami it is currently 🥵 104°F
```

Note: Your function formatWeatherReport **must call the functions you wrote earlier**
 - ie. convertToEmojiFace and formatTemperatureAsString

[Please refer to this diagram while writing the code](https://raw.githubusercontent.com/McLarenCollege/public_images/main/dc41e5976e1acf77.png)


```js
// Copy the convertToEmoji function you wrote earlier here:

// Copy the convertToFahrenheit function you wrote earlier here:

// Copy the formatTemperatureAsString function you wrote earlier here:

// Write your new formatWeatherReport function here:


let msgForRajOnMonday = formatWeatherReport('Vancouver', 3, true);
console.log(msgForRajOnMonday);

let msgForTonyOnMonday = formatWeatherReport('Sydney', 17, false);
console.log(msgForTonyOnMonday);

let msgForJohnOnSunday = formatWeatherReport('Miami', 40, true);
console.log(msgForJohnOnSunday);



```