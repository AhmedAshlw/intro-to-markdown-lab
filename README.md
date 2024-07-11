# Writing a Function in JavaScript

## Name: Ahmed Darwish

### Date: 2/7/2024
***

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. **Basic syntax**

```JavaScript
const functionName = (params) => {
  // code to be executed
}
```

* __const__: const should be used whenever a function expression is assigned to a variable.
* __The function name__: The name you choose for the function.
* __Parameters__: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* __The arrow syntax__: Indicates that this will be a function.
* __The body__: The statements that make up the function itself. Surrounded by curly braces.

***Example:***
```
const greet = (name) => {
  `console.log("Hello, " + name + "!");`
}
```

>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. **Calling a function**

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

***Example:***

`greet('Alice');` // Outputs: Hello, Alice!

3. __Return values__

Functions can process data input and output a value using the _return_ keyword.

***Example:***
```
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

>For more information on functions and how they are used in JS, check out the MDN docs. 
>>Click Me! [mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

4. __Another Examples__

![JavaScript](https://images.unsplash.com/photo-1555949963-ff9fe0c870eb?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)


| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~. 



