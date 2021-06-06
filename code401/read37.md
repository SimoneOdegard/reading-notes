# Read 37

## Review, Research, and Discussion

**Why choose Redux instead of the Context API for global state?** Redux works around the idea of having a central state called a store. To change the state, a component has to dispatch an action. The action is then passed on to the reducer, which changes the state of our application. [resource](https://betterprogramming.pub/why-use-redux-when-we-have-context-api-95be70581148)

**What is the purpose of a reducer?** A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently [resource](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/#:~:text=A%20reducer%20is%20a%20function,so%20that%20they%20behave%20consistently.)

**What does an action contain?** An action carries a payload of information from your application to store. [resource](https://www.tutorialspoint.com/redux/redux_actions.htm)

**Why do we need to copy the state in a reducer?** The reducer uses a switch statement to determine which type of action it's dealing with. If there is an unknown action, then it should return the state, so that the application doesn't lose its current state. [resource](https://www.pluralsight.com/guides/how-to-write-redux-reducer)

## Term

- **immutable state** Immutable state is state that cannot be changed.
- **time travel in redux** The Redux DevTools records dispatched actions and the state of the Redux store at every point in time. This makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or restarting the app. [resource](https://medium.com/the-web-tub/time-travel-in-react-redux-apps-using-the-redux-devtools-5e94eba5e7c0)
- **action creator** An action creator is a function that literally creates an action object. In Redux, action creators simply return an action object and pass the argument value if necessary. [resource](https://www.educative.io/courses/building-teslas-battery-range-calculator-with-react-and-redux/7nVVPYOGVPr)
- **reducer** A reducer is a function that determines changes to an application's state. [resource](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/#:~:text=A%20reducer%20is%20a%20function,receives%20to%20determine%20this%20change.&text=Redux%20relies%20heavily%20on%20reducer,to%20execute%20the%20next%20state.)
- **dispatch** Dispatch is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. [resource](https://react-redux.js.org/using-react-redux/connect-mapdispatch#:~:text=dispatch%20is%20a%20function%20of,connect%20does%20it%20for%20you.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Immutable state
1. Redux for global state
1. Reducer

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. combineReducers
1. dispatch
1. actions

**What are you most excited about trying to implement or see how it works?** I'm curious about using actions and reducers

## Readings

- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

[<== Back](https://simoneodegard.github.io/reading-notes/)