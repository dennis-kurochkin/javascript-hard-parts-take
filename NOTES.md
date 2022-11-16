# Notes

When JavaScript code runs, it goes through the code line-by-line and runs/executes each line - known as the **thread of execution**

#### Execution Context
Created to run the code of a function (or global code, then it called **global execution context**). Has 2 parts - **thread of execution** and (local) **memory**.

**Parameter** is a label, which when a function runs will be replaced with value known as **argument**.

**Argument** is a value, which will replace **parameter** when function is called.

#### Call stack
- JavaScript keeps track of what function is currently running (where's the thread of execution)
- Run a function - add to the top of the call stack
- Finish running a function - JavaScript removes it from the top of the call stack
- Whatever is top of the call stack - that's the function JavaScript is currently running
