1. What does thread of execution means in JavaScript?
Ans- The thread of execution we go through the code in the function line by line.

2. Where the JavaScript code gets executed?
Ans- The JavaScript code is executed one line at a time inside the Code Component (also known as the Thread of execution) of Execution Context. 

3. What does context means in Global Execution Context?
Ans- The environment in which the JavaScript code is executed. By environment, I mean the value of this , variables, objects, and functions JavaScript code has access to at a particular time.

4. When do you create a global execution context.

Ans- The Global Execution Context gets created when we load the JavaScript file, even when it is empty.In Global Execution context, the window object and this are equal.

5. Execution context consists of what all things?
Ans- Execution context is a concept in the language spec that—in layman's terms—roughly equates to the 'environment' a function executes in; that is, variable scope (and the scope chain, variables in closures from outer scopes), function arguments, and the value of the this object.

6. What are the different types of execution context?
Ans- We have three different types of JavaScript execution contexts: Global execution context – This execution context is created by default by the JavaScript engine.

7. When global and function execution context gets created?
Ans-The Global Execution Context gets created when we load the JavaScript file, even when it is empty. It creates two special things for us in its creation phase, that is the window object and this .

8. Function execution gets created during function execution or while declaring a function.



9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)

