# Read 09

## Functional Programming Concepts
[link](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

"Complexity is anything that makes softward hard to understand or to modify." - John Outerhout, article link.

"Functional programming is a programming paradigm - a style of building the structure and elements of computer programs - that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data" - [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)

**Pure Functions** A pure function will return the same result if given the same arguments. I will not cause side effects. ```const calculateArea = (radius, pi) => radius * radius * pi;``` would be a pure function because you're passing in radius and PI as parameters to the function.

**Other impure functions:**
- If a function reads external files, it is not a pure function because the contents can change.
- Random number generation
- No observable side effects

### Keywords
**Immutability** "Unchanging over time or unable to be changed" (from article). It's state cannont change after being created. You would need to create a new object because immutable objects cannot be changed.
**Referential transparency** Pure function + immutable data = referential transparency. A function consistently yields the same result for the same input.
**Functions as first-class entities** Functions are also treated as values and used as data. They can refer to it from constants and variables, pass it as parameters to other functions, and return it as a result from other functions.
**Higher-order functions** Functions can either take one or more functions as arguments or return a function as a result.
**Filter** we want to filter by an attribute. It will expect a true or false value to determine if the element should be included in the end result.
**Map** Used to transform a collection.
**Reduce** Receive a function and a collection, and return a value created by combining the items.

## Refactoring JavaScript for Readability
[link](https://dev.to/healeycodes/refactoring-javascript-for-performance-and-readability-with-examples-1hec)

Strategies of refactoring code. You would want to do this to make code easier to read.
- Return early from functions
- Use variables so functions can be read like sentences. This is similar to us changing req to request on our backend server.
- Use web APIs

[<== Back](https://simoneodegard.github.io/reading-notes/)