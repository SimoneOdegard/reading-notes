# Read 10

## Understanding the JavaScript Call Stack
[link](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)

The call stack is used for function invocation. Function execution is done one at a time from top to bottom making it synchronous. "Call stack is a data structure that uses last in, first out (LIFO) to temporarily store and manage function invocation." (article) LIFO meands that the last function that gets pushed into the stack is the first one pushed out. To temporarily store something, once invoked, the function, the paramets, and variables are pushed into a stack frame. The stack frame is a memory location. The memory is cleared when the function returns as it is pop off the stack. The call stack keeps a record of the position of each stack frame and know what order the functions are in in order to be executed.

"A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point." (article).

## Keys
1. Single threaded
1. Code execution is synchronous
1. Function invocation creates a stack frame
1. Works as a LIFO

## JavaScript error messages
[link](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

Most of your time as a developer will be spent debugging. The more you are programming, the more common error messages will be. Here are some of the common error messages.

- Reference errors
- Syntax errors
- Range errors: When trying to manipulate an object with length, and you give it an invalid length, this error will show up. One example is that an array cannot have a negative length.
- Type errors: Shows up when types you are trying to use or access are incompatible.

When debugging, use console.log()!

Call stack is "the path your program has taken to reach the point where you set a breaking point or where you have an error." (article).

When handling errors, remember to use try/catch! This is how to handle errors properly so that anything after the error will not be executed.

[<== Back](https://simoneodegard.github.io/reading-notes/)