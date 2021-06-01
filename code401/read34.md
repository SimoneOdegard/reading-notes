# Read 34

## Review, Research, and Discussion

**Why is the Context API useful?** It allows you to share state down a component tree. [resource](https://hashinteractive.com/blog/understanding-react-context-api/)

**Can a component outside of a provider get its context?** Yes, the most common way to access Context from a class component is via the static contextType. If you need the value from Context outside of render , or in a lifecycle method, you'll use it this way. The traditional way to retrieve Context values was by wrapping the child component in the Consumer. [resource](https://www.taniarascia.com/using-context-api-in-react/)

**What are some common use cases for using the Context API?** Context is primarily used when some data needs to be accessible by many components at different nesting levels. [resource](https://reactjs.org/docs/context.html)

**Describe “Context Hell”** It sounds like it's the nasty code you get taking advantage of the React Context API. It looks like it's a lot of code nesting in nesting in nesting. [resource](https://dev.to/alfredosalzillo/the-react-context-hell-7p4#:~:text=What%20is%20the%20React%20Context,of%20the%20React%20Context%20API.)

## Terms

- **global state** State at a global level. You can use it by starting at the top of the component tree and Hooks will update their state from there.
- **global context** Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React. [resource](https://reactjs.org/docs/context.html#:~:text=Context%20is%20designed%20to%20share,class%20App%20extends%20React.)
- **provider** The component that makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a ```<Provider>``` at the top level, with the entire app's component tree inside of it. [resource](https://react-redux.js.org/api/provider#:~:text=Overview,component%20tree%20inside%20of%20it.)
- **consumer** A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. [resource](https://reactjs.org/docs/context.html#:~:text=Context.Consumer&text=A%20React%20component%20that%20subscribes,context%20within%20a%20function%20component.&text=The%20function%20receives%20the%20current%20context%20value%20and%20returns%20a%20React%20node.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. context
1. roll based access
1. cookies but interested to learn more about react-cookies

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Context API
1. Context hell and more about how to avoid it and/or fix it!
1. Redux

**What are you most excited about trying to implement or see how it works?** I'm excited to use Context API! It seems like it makes doing things like passing state around different components easier.

## Readings

- [what is role based access control?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
- [react-cookies component](https://www.npmjs.com/package/react-cookies)
- [react-cookie library](https://www.npmjs.com/package/react-cookie)

[<== Back](https://simoneodegard.github.io/reading-notes/)