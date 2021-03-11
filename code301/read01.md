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

## Hello World
[Hello World](https://reactjs.org/docs/hello-world.html)

Introduction to learning react

## Introducing JSX
[Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

Why JSX? "Instead of separating technologies by putting markup and logic in separated files, React separates concerns with loosely coupled units called "components" that contain both."

In JSX, you can put any valid JavaScript expression inside curly braces. JSX is also an expression. JSX expressions become regular JavaScript function calls and can be used inside of if statements and for loops.

**NOTE**: JSX is closer to JavaScript than to HTML. 

### Keywords
- **JSX**: a syntax extension to JavaScript. Use it with React to describe what the UI should look like. 
- **React elements**: descriptions you want to see on screen. React reads these objects and constructs the DOM.

## Rendering Elements
[Rendering Elements](https://reactjs.org/docs/rendering-elements.html)

React elements are plain objects. Elements are what components are made of. Applications built with React have a single root DOM node. In order to render a React element, you would need to pass it into ```ReactDom.render()```. It is typically only called once.

React elements are immutable. You cannot change an element's children or attributes once it has been created.

## Components and Props
[Components and props](https://reactjs.org/docs/components-and-props.html)

"Components are like JavaScript functions. They accept arbitrary inputs called props and return React elemnts describing what should appear on the screen."

Elements can represent user-defined components. It would pass JSX attributes and children to the component as a single object(props).

In React apps, a button, a form, a dialog, a screen are all components. You can split components into smaller components. A rule to follow is that if you use a part of your UI several times or it is complex, it should be extracted to a separate component.

**NOTE**: "All React components must act like pure functions with respect to their props.

[<== Back](https://simoneodegard.github.io/reading-notes/)