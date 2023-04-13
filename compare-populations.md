```js
let countries = {
    "United States": {
        population: 331449281,
        capital: "Washington, D.C.",
        largestCity: "New York City",
        currency: "USD"
    },
    China: {
        population: 1444216106,
        capital: "Beijing",
        largestCity: "Shanghai",
        currency: "CNY"
    },
    India: {
        population: 1393409038,
        capital: "New Delhi",
        largestCity: "Mumbai",
        currency: "INR"
    },
    Russia: {
        population: 146171015,
        capital: "Moscow",
        largestCity: "Moscow",
        currency: "RUB"
    }
}

function comparePopulations(countryObj, firstCountry, secondCountry) {
    // write your code here
}
console.log(comparePopulations(countries, 'China', 'Russia')); // "China has more people than Russia"
console.log(comparePopulations(countries, 'United States', 'India')); // "India has more people than United States"

```

Write a function`comparePopulations` which takes the country data, and two country names like "Russia", "China" then returns a message like:
"China has more people than Russia" or "India has more people than United States".
