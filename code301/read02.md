# Read 02

## State and Lifecycle
[State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

```ReactDOM.render()``` is a way to update the UI by changing the rendered output. When making an updated clock UI with every second showing, you ened to consider many things. One is adding "state" to the clock component.

**Converting a function to a class:** (from web article)
1. Create ES6 class with the same name that extends ```React.Component```
1. Add a single empty method to it called ```render()```
1. Move the body of the function into the ```render()``` method
1. Replace ```props``` with ```this.props``` in the ```render()``` body
1. Delete the remaining empty function declaration

When using ```setState()```
- Do not modify state directly. It will not re-render a component.
- State update may be asynchronous. Do not rely on the values of ```this.props``` and ```this.state``` to calculate the next state.
- State updates are merged.

State is called local or encapsulated because it is not accessible to other components other than the one that sets it. Due to "top-down" or "unidirectional" data flow, any data or UI from that state can affect components below them.

### Keywords
- **State**: Similar to props but is private and controlled by the component.
- **Lifecycle Methods**:
    - **Mounting**: Example is setting up a timer the first time that the clock is rendered to the DOM ```componentDidMount()```.
    - **Unmounting**: Example is clearing the timer whenever the DOM produced by the clock is removed. ```componentWillUnmount()```.

## Handling Events
[Handling Events](https://reactjs.org/docs/handling-events.html)

Handling events with React elements is similar to events on DOM elements. Instead of using lowercase, you would use camelCase. JSX would also pass a function as the event handler instead of a string. You need to call ```preventDefault``` to prevent default behavior in React instead of returning false. You don't need to call ```addEventListener```, you just provide a listener when the element is rendered. You can also toggle component redners with on and off.

'this' is something that you have to be careful about using. 'this' will be undefined when a function is called if you forget to bind 'this'. Two ways you can get around bind. One, using class fields to bind callbacks. Two, using an arrow function in the callback.

## Conditional Rendering
[Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

Conditional rending in React works the same as conditions in JS. You can create a stateful component which depending on its current state, it will render different options. You can use if statements to conditionally render components. When you want to hide a component, return null instead of the render output. Null will not affect the component's lifecycle methods.

## Tutorial: Intro to React
[Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

Tutorial building an interactive tic-tac-toe game with React. Notes on this tutorial can be found here: [Read 01](code301/read01.md)

[Starter Code](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)

[Final Code](https://codepen.io/gaearon/pen/gWWZgR?editors=0010)


# Skim

## React Bootstrap
[React Bootstrap](https://react-bootstrap.github.io/)

- Front-end framework rebuilt with React.

## Netlify
[netlify](https://www.netlify.com/)

- Git-based workflow and serverless platform. Used to create web apps.

How does it work?
1. Connect your repo
1. Add build settings
1. deploy

[<== Back](https://simoneodegard.github.io/reading-notes/)