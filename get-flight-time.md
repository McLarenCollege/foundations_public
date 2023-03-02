Create a function `flightTimeMessage` that accepts 3 parameters, the given `aviationInfo` object, the source `fromAirportCode` 
and the destination `toAirportCode`and returns the flight duration in the given format.

```js

let aviationInfo = {
  airports: {
    DEN: {
      name: 'Denver Airport',
      country: 'United States'
    },
    DFW: {
      name: 'Dallas Fort Worth Airport',
      country: 'United States'
    },
    LAX: {
      name: 'Los Angeles Airport',
      country: 'United States'
    },
    DEL: {
      name: 'New Delhi Indira Gandhi Airport',
      country: 'India'
    },
    SHA: {
      name: 'Shanghai Hongqiao Airport',
      country: 'China'
    },
    SYD: {
      name: 'Sydney Kingsford Smith Airport',
      country: 'Australia'
    },
    DXB: {
      name: 'Dubai Airport',
      country: 'United Arab Emirates'
    },
    HND: {
      name: 'Tokyo Haneda Airport',
      country: 'Japan'
    },
  },

  flightDurationMins: {
    'SYD-HND': 585,
    'LAX-HND': 730,
    'LAX-DEN': 140,
    'DEL-HND': 455,
    'DXB-DEL': 190,
    'LAX-SYD': 825,
  }
};


function flightTimeMessage(aviation, fromAirportCode, toAirportCode) {
  // Write your code here
}

// Should print 'Flight time from Los Angeles Airport to Sydney Kingsford
// Smith Airport is 13 hours and 45 minutes'
console.log(flightTimeMessage(aviationInfo, 'LAX', 'SYD'));

// Should print 'Flight time from Dubai Airport to New Delhi Indira
// Gandhi Airport is 3 hours and 10 minutes'
console.log(flightTimeMessage(aviationInfo, 'DXB', 'DEL'));
```
