### Exercise
Write a function `getStudentGrade` which takes in a student object and returns the grade for that student.

**Example**

```js
console.log(getStudentGrade({ name: 'Vivek', scores: [70, 90, 60, 91] })); // should print C
console.log(getStudentGrade({ name: 'Akshat', scores: [90, 80, 80, 60] })); // should print C

// To calculate the grade obtained by the student look at below explanation.
// Average score greater than or equal to 91 -> A grade
// Average score greater than or equal to 81 -> B grade
// Average score greater than or equal to 71 -> C grade
// Average score greater than or equal to 61 -> D grade
// For other average scores -> E
```
