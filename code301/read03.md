# Read 03

## Lifting State Up
[link](https://reactjs.org/docs/lifting-state-up.html)

Sometimes you need multiple components to reflect the same changing data. You would lift the shared state to the closest common ancestor. When adding a second input, we are able to keep them in sync. This is done by "lifting state up" which is moving up to the closest common ancestor. 

**NOTE:** props are read-only. When something is coming from the parent of a prop, it often has no control over it. You would solve this by making a component controlled.

There needs to be a single "source of truthe" for any data that changes in a React application. One option instead of "trying to sync the state between different components, you should rely on the 'top-down data flow'."

## Lists and Keys
[link](https://reactjs.org/docs/lists-and-keys.html)

Usually you render lists inside a component. A key needs to be provided for list items. A key is a string attribute that is needed when creating lists of elements. A key helps React identify which items have changed, been added, or removed. Give the elements inside the array keys. Use a string to identify a list item among the siblings. The string needs to be unique. Usually you would use ID. Don't use indexes for keys if the order will change. If you do not assign a key to list items, React will automatically use indexes as keys. Keys within arrays should be unique among siblings.

## Tutorial
[link](https://reactjs.org/tutorial/tutorial.html)

Tutorial building an interactive tic-tac-toe game with React. Notes on this tutorial can be found here: [Read 01](code301/read01.md)

[Starter Code](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)

[Final Code](https://codepen.io/gaearon/pen/gWWZgR?editors=0010)

## The Spread Operator
[link](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

"When ```...arr``` is used in the function call, it 'expands' an iterable object ```arr``` into the list of arguments" - [JavaScript.info](https://javascript.info/rest-parameters-spread)

Things that ```...``` can do: (from website)
- Copy an array
- Concatenating or combining arrays
- Use math functions
- Use array as arguments
- Add item to a list
- Add state in React
- Combing object
- Convert NodeList to an array

[<== Back](https://simoneodegard.github.io/reading-notes/)