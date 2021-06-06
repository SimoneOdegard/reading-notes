# Read 39

## Review, Research, and Discussion

**What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?** Fire off the asynchronous action in the lifecycle method (probably componentWillMount) of a Higher Order Component that wraps your app. You will not use the results of the API call directly in that component - it needs to be handled with a reducer that puts it into your app store. This will require you to use some sort of a thunk middleware to handle the asynchronous action. Then you will use mapStateToProps to simply pass it down to the component that renders the data. [resource](https://stackoverflow.com/questions/39356517/correct-way-to-pre-load-component-data-in-reactredux)

**When using a thunk/async action that dispatches the actual action, which do you export from your reducer?** It looks like you would export all reducers [resource](https://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux)

## Terms

- **middleware** Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system [resource](https://www.redhat.com/en/topics/middleware/what-is-middleware)
- **thunk** If you want an action to do something, that code needs to live inside a function. That function (the “thunk”) is a bundle of work to be done. [resource](https://daveceddia.com/what-is-a-thunk/)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Middleware
1. Thunk and how it's a middleware but I would like to learn more
1. HookState

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Pre-loading data in a Redux app
1. Exporting from the reducer. I had a hard time trying to find an answer for the second question above.
1. Dispatches

**What are you most excited about trying to implement or see how it works?**

## Readings

- [Redux Toolkit (RTK)](https://redux-toolkit.js.org/)
  - [Tutorial](https://mobx.js.org/getting-started.html)

Alternative State Managers
- [MobX](https://mobx.js.org/getting-started.html)
- [HookState](https://hookstate.js.org/)

[<== Back](https://simoneodegard.github.io/reading-notes/)