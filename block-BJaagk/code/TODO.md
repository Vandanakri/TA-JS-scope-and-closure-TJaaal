1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

// function expression
let totalMarks = function percentage(marks, total) {
  return (marks * 100) / total;
}
// Arrow function
let totalMarks = (marks, total) => {
  return (marks * 100) / total;
}
// function declaraton
function percentage(marks, total) {
  return (marks * 100) / total;
}
// function Anonymous
let totalMarks = function percentage(marks, total) {
  return (marks * 100) / total;
}



```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Ans- The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions.

4. Why is a function call an expression in JavaScript?

Ans- A function call expression is used to execute a specified function with the provided arguments. If the function being called is overloaded, the compiler will attempt to match the argument types with the function parameter types. If there are no matching function declarations, a compile-time error will be raised.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); 
Ans- undefined

five = add;
Ans- ƒ add(a, b) {
  return a + b;
}

five = five(10, 11); 
Ans- 21

five = function () {
  return 'Hello';
};
 Ans- ƒ () {
  return 'Hello';
}
```

6. What is the difference between function definition and function call? Explain with an example.

Ans- function defination will start with function and function execution when we call with parentheses and we will passing parameter.


7. What is the similarities between function definition and function call?

Ans- The difference between the function and function call is, A function is procedure to achieve a particular result while function call is using this function to achive that task.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}
invalid

hello.user = 'Sam'; // validxz
```

9. What is higher order function explain with an example.

Ans- Higher-order functions are functions that take other functions as arguments or return functions as their results.
Examples:-
sort, reduce, filter, forEach.

10. Explain what is callback function. Why you can pass a function inside a function?
Ans- A callback is a function that you pass into another function as an argument for executing later.


