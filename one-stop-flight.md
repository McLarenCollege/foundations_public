Given a flights object where the keys are the starting point and the values are the possible ending points of the journey,
create a function that returns a true/false depending on whether a ONE-STOP flight is possible between the source and 
the destination.

HINT: You can reuse the checkDirectFlight function we created earlier.

```js
function checkOneStopFlight(source,destination,flightObj){
// write your code here
}
let flights= {
     "BOM" : ["DEL", "NYK", "SYD"],
     "DEL" : ["LON", "WAS", "LAH"],
     "RPR" : ["BAN", "BOM", "BRA"]
     };
console.log(checkOneStopFlight("BOM", "LAH",flights));// TRUE
console.log(checkOneStopFlight("RPR", "WAS",flights));// FALSE
console.log(checkOneStopFlight("RPR", "SYD",flights));// TRUE
```
