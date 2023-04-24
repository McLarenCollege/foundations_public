Create a function that takes an array of objects representing employees, with properties `name`, `title`, and `department`. The department property should be an object with properties `name` and `location`.

The function should return an array of strings, where each string is a formatted message about the employee, like this:

```js
const employees = [
  {
    name: "John Doe",
    title: "Software Engineer",
    department: {
      name: "Engineering",
      location: "San Francisco"
    }
  },
  {
    name: "Jane Smith",
    title: "Product Manager",
    department: {
      name: "Product",
      location: "New York"
    }
  }
];

formatEmployees(employees);
/* should return [
  "John Doe, Software Engineer, Engineering - San Francisco",
  "Jane Smith, Product Manager, Product - New York"
] */
```
Each string should include the employee's name, title, department name, and department location, formatted in a readable way. You can assume that the department object will always have both properties.


