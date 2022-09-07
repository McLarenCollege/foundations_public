
# Student Object Exercise Part - 2
### Task1
Write a function `getStudentGrade` which takes in a student object and returns the grade for that student.

**Example**

```js
function getStudentGrade(stuObj){
// write your code here
}
console.log(getStudentGrade({ name: 'Vivek', scores: [70, 90, 60, 91] })); //  C
console.log(getStudentGrade({ name: 'Akshat', scores: [90, 80, 80, 60] })); // C
```
// To calculate the grade obtained by the student look at below explanation.
// Average score greater than or equal to 91 -> A grade
// Average score greater than or equal to 81 -> B grade
// Average score greater than or equal to 71 -> C grade
// Average score greater than or equal to 61 -> D grade
// For other average scores -> E

## Task2
Write a function `addGrades` which takes in an array of student objects and adds 'grade' as the new property to each student object which stores the calculated grade.

```js
let students = [
 { name: 'Vivek', scores: [70, 90, 60, 91] },
 { name: 'Akshat', scores: [90, 80, 80, 60] },
 { name: 'Arnav', scores: [70, 60, 90, 90] },
];
function addGrades(studentObjArray){
// write your code here
}
addGrades(students);
console.log(students);
```
