# Filter Tennis Players

Write a function `filterTennisPlayers` which takes a list of objects representing tennis players and a filter criteria, and 
returns the **last n** tennis players that match the filter criteria.  It should take three parameters:

- a list of tennis player details including name and whether the player is retired
- a boolean representing whether to return only active players (ie. not retired) or both active and retired players
- a number n representing the number of players to return

For example, given the following list

```js
let groupA = [
  { name: 'Pete Sampras', isRetired: true, age: 51 },
  { name: 'Zverev Alexander', isRetired: false, age: 25 },
  { name: 'Naomi Osaka', isRetired: false, age: 24 },
  { name: 'Martina Navratilova', isRetired: true, age: 65 },
  { name: 'Rafael Nadal', isRetired: false, age: 36 },
  { name: 'Martina Hingis', isRetired: true, age: 41 },
];
```

Calling the function `filterTennisPlayers(groupA, false, 2)` 
should return this array:

```js
[
  { name: 'Naomi Osaka', isRetired: false, age: 24 },
  { name: 'Rafael Nadal', isRetired: false, age: 36 }
]
```

Calling the function `filterTennisPlayers(groupA, false, 10)` 
should return a shallow copy of the `groupA` array.
 
```js
function filterTennisPlayers(group, isRetired, age){
// write your code here
}
let groupA = [
  { name: 'Pete Sampras', isRetired: true, age: 51 },
  { name: 'Zverev Alexander', isRetired: false, age: 25 },
  { name: 'Naomi Osaka', isRetired: false, age: 24 },
  { name: 'Martina Navratilova', isRetired: true, age: 65 },
  { name: 'Rafael Nadal', isRetired: false, age: 36 },
  { name: 'Martina Hingis', isRetired: true, age: 41 },
];
console.log(filterTennisPlayers(groupA, false, 2));
/*
should return 
[
  { name: 'Naomi Osaka', isRetired: false, age: 24 },
  { name: 'Rafael Nadal', isRetired: false, age: 36 }
]
*/
console.log(filterTennisPlayers(groupA, true, 3));
/*
should return 
[
 { name: 'Martina Hingis', isRetired: true, age: 41 },
{ name: 'Martina Navratilova', isRetired: true, age: 65 },
{ name: 'Pete Sampras', isRetired: true, age: 51 },
]
*/
```



