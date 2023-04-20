Create a function `searchAndBookFlight` that takes in a `flights` array, a `source` airport, a `destination` aiport, a seat class and the number of tickets to be booked and returns `true/false` depending on whether the booking can be made.
If the given source and destination flight doesn't exist then return false.
Note that the number of booked tickets should always be less than or equal to the capacity of the flight after the booking has been made.

**Note**: You must use the previously written `bookFlight` function

```js
function searchAndBookFlight(flights, source, destination, seatClass, numTickets) {
  // Write your code here
}

let allFlights = [
  {
    flightNumber: "AA123",
    origin: "LAX",
    destination: "JFK",
    durationMins: 360,
    seats: {
      economy: {
        price: 200.0,
        capacity: 50,
        booked: 25
      },
      business: {
        price: 500.0,
        capacity: 20,
        booked: 10
      }
    }
  },
  {
    flightNumber: "BA456",
    origin: "LHR",
    destination: "CDG",
    durationMins: 180,
    seats: {
      economy: {
        price: 100.0,
        capacity: 100,
        booked: 50
      },
      business: {
        price: 300.0,
        capacity: 40,
        booked: 20
      }
    }
  }
];

console.log(bookFlight(allFlights, "LHR", "CDG", "economy", 2)); // 200.0
console.log(bookFlight(allFlights, "LON", "JFK", "economy", 2)); // false
console.log(bookFlight(allFlights, "LHR", "CDG", "first", 2)); // false
console.log(bookFlight(allFlights, "LAX", "JFK", "business", 2)); // 1000.0
console.log(bookFlight(allFlights, "LAX", "CDG", "business", 2)); // false
```
