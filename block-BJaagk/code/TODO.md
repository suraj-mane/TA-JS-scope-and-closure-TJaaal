1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

var totalMarks = (marks, total) => {
  return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

```
this is function declaration 
```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
This function Expression that no name need
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
This function Expression that no name need.
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
this valid function Expression.
```js
let percentage = (marks, total) => (marks * 100) / total;
```
this arrow function.
3. Why is a function definition an expression in JavaScript? Give one example of function expression.
let fullName = (firstName, lasrName) => (firstName + lastName);
4. Why is a function call an expression in JavaScript?
fullName('suraj', 'mane');
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); valid
five = add; valid 
five = five(10, 11); valid
five = function () {
  return 'Hello';
}; valid
```

6. What is the difference between function definition and function call? Explain with an example.
the function has name this is called functin definition and function call is function with parameter.
7. What is the similarities between function definition and function call?
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // invalid
```

9. What is higher order function explain with an example.
A function that accepts and return the funtion this is called higher order function.
10. Explain what is callback function. Why you can pass a function inside a function?
The function accepts a function as an arguments it is called callback function. 