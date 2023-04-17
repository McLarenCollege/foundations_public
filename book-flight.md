Create a function bookFlight that takes in a flight object, a seat class and the number of tickets to be booked and returns true/false depending on whether the booking 
can be made.
Note that the number of booked tickets should always be less than or equal to the capacity of the flight after the booking has been made.

```js
function bookFlight(flightObj, seatClass, numTickets) {
  // Write your code here
}

let flights = [
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

console.log(bookFlight(flights[0], "economy", 2)); // 400.0
console.log(bookFlight(flights[0], "business", 1)); // 500.0
console.log(bookFlight(flights[1], "economy", 5)); // 500.0
console.log(bookFlight(flights[1], "business", 3)); // 900.0
console.log(bookFlight(flights[1], "first", 2)); // false
```
