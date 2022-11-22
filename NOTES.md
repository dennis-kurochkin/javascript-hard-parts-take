# Notes

### Basics of JavaScript

When JavaScript code runs, it goes through the code line-by-line and runs/executes each line - known as the **thread of execution**

**Execution context** is ceated to run the code of a function (or global code, then it called **global execution context**). Has 2 parts - **thread of execution** and (local) **memory**.

**Parameter** is a label, which when a function runs will be replaced with value known as **argument**.

**Argument** is a value, which will replace **parameter** when function is called.

**Call stack**

- JavaScript keeps track of what function is currently running (where's the thread of execution)
- Run a function - add to the top of the call stack
- Finish running a function - JavaScript removes it from the top of the call stack
- Whatever is top of the call stack - that's the function JavaScript is currently running

### Nature of functions and higher-order functions

Functions in JavaScript are **first-class objects**. Whatever features objects have, functions have them too. They can co-exist with and can be treated like any other JavaScript object, meaning:

1. Assigned to variables and properties of other objects
2. Passed as arguments into functions
3. Returned as values from functions

**Higher-order functions** take in a function or pass out a function.

Callbacks and higher-order functions simplify code and keep it DRY. Callbacks are a core aspect of asynchronous JavaScript and are under-the-hood of promises (async/await).
