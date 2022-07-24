# Weather Report

Print the location and temperature in Celsius or Fahrenheit based on the users preference.
Prefix the temprature with an emoji as follows:
 ```
🥵 if temperature in Celsius is above 30
😊 if temperature in Celsius is between 12 and 30
🥶 if temperature in Celsius is below 12
```

Your output should be in the following format:
```
In ________ it is currently ______
```

For example:

```
In Vancouver it is currently 🥶 37.4°F 
In New Delhi it is currently 🥵 35°C 
In Sydney it is currently 😊 17°C 
In Miami it is currently 🥵 104°F
```

Starting code: 

```js
let preferCelsius = false;
let tempC = 3;
let location = 'Vancouver';

// Write your code here

```



Tip: Here's how to solve this problem: 
 
1. Create a variable called `emojiFace` and the use an if-else-if 
 expression to set the value to "🥵" or "😊" or "🥶" 
 (note that these emojis are regular characters like "A" or "#" and 
 can be copy-pasted into your javascript code)

2. Create another variable called `temperatureString` and use an if-else 
 expression to set the value to a formatted string like "37.4°F" or "17°C" 
 (again note that the degree symbol ° is just a regular character)

3. Combine the variables `location`, `emojiFace` and `temperatureString` 
 into a string which is printed to the console
