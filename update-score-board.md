Create a function `updateScoreboard` that takes in an array of `scoreboard` objects and a game result object, and updates the scoreboard array with the new result. The game result object contains the names of the two teams that played and the score of the game.

Each scoreboard object has the name of a team, its win-loss record.

The function should update the win/loss record for both teams in the scoreboard array based on the game result. If a team is not found in the scoreboard array, it should be added with a win/loss record of 0-0.

The function should return the updated scoreboard array.

```js
function updateScoreboard(scoreboard, gameResult) {
  // write your code here
}

const scoreboard = [
  { team: 'Bears', record: '3-1'},
  { team: 'Packers', record: '2-2'},
  { team: 'Vikings', record: '1-3'}
];

const gameResult = { homeTeam: 'Packers', awayTeam: 'Bears', homeScore: 21, awayScore: 14 };

console.log(updateScoreboard(scoreboard, gameResult));
// [
//   { team: 'Bears', record: '3-2' },
//   { team: 'Packers', record: '3-2' },
//   { team: 'Vikings', record: '1-3' }
// ]
```
