# Read 01

## Intro to React
[Intro to React](https://reactjs.org/tutorial/tutorial.html)

This is a tutorial showing how to build an interactive tic-tac-toe game.

Setting up the tutorial
1. Write code in the browser
1. Local development environment

**What Is React?** "React is a declarative, efficient, and flexible JavaScript library for building user interfaces."

[Link to starter code](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)

**JS code**
- Square component will render a button
- Board component will render 9 squares
- Game component renders a board with placeholder values

**Note:**
- To collect data or have multiple children communicate, you need to declare the shared state in the parent component. The parent component passes the state back down to the children using props. This keeps everything in sync.
- Immutability makes complex features easier to implement. It also helps you build pure components. It will help determine when a compenent needs to re-render.

[Link to finished code](https://codepen.io/gaearon/pen/gWWZgR?editors=0010)

### Keywords
- **component** takes in parameters and "props" that are short for properties.
- **render** returns a description of what you want to see on screen.
- **key** is a special and reserved property in React. "When an element is created, React extracts the key property and stores the key directly on the returned element"

[<== Back](https://simoneodegard.github.io/reading-notes/)