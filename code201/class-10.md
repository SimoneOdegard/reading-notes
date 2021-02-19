# Read 10

## JS Ch 10
The order of execution is important. It helps to know how scripts are processed. You need to pay attention to the order that statements are executed since some tasks can't be completed until another statement runs.

Execution Context:
- Global context: Code that is in script but not a function.
- Function context: Code that is being run within a function.
- Eval context: Text executed like code in an internal function.
Variable Scope:
- Global scope: variable declared outside a funtion, it can be used anywhere
- Function-level scope: variable declared within a function, it can only be used within that function.

JavaScript processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task. (Javascript & Jquery, Duckett pg 454).

Execution Context
1. Prepare: new scope is created. Variables, functions, and arguments are created.
1. Execute: assign values to variables, reference functions and run their code, execute statements.

Error Objects
- SyntaxError: incorrect syntax
- ReferenceError: variable does not exist
- EvalError: incorrect use of ```eval()``` function
- URIError: incorrect use of URI fuctions
- TypeError: unexpected data type
- RangeError: number outside of range
- Error: generic error object
- NaN: not an error but it means not a number

Dealing with errors you need to debug the script or handle errors gracefully using ```try```, ```catch```, ```throw```, and ```finally``` statements. To debug, you need to look at where is the probelm and what exactly is the problem? It involves a process of deduction. 

**USE THE CONSOLE** That will help you find areas where you need to debug or fix errors.

Handling expections: (Javascript & Jquery, Duckett pg. 480)
- Try: Specify the code that you think might throw an exception
- Catch: If the Try code block throws an exception, catch steps in with an alternative set of code
- Finally: The contents of the finally code block will run either way
- Use when giving your users helpful feedback!

### Keywords
- **Lexical scope** Functions are linked to the object they were defined within. The scope is the current execution context.
- **Exception** When a JavaScript statement generates an error.

[<== Back](https://simoneodegard.github.io/reading-notes/)