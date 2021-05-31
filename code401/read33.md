# Read 33

## Review, Research, and Discussion

**Describe use cases for useMemo() and useReducer()**

- **useMemo()**: You're noticing a component's render is frustratingly slow, and you're passing a calculation to an unknowable number of children, such as when rendering children using ```Array.map()``` *AND/OR* Your app often becomes unresponsive because you're fetching a large amount of data, and having to transform it into a usable format. [resource](https://maxrozen.com/understanding-when-use-usememo)
- **useReducer()**: useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks. [resource](https://reactjs.org/docs/hooks-reference.html#:~:text=useReducer%20is%20usually%20preferable%20to,dispatch%20down%20instead%20of%20callbacks.)

**Why do custom hooks need the use prefix?**  Its name should always start with use so that you can tell at a glance that the rules of Hooks apply to it. Now let's see how we can use our custom Hook. [resource](https://reactjs.org/docs/hooks-custom.html)

**What do custom hooks usually do?** You can extract and share logic in a way that was not possible with class components. [resource](https://dev.to/damcosset/how-to-create-custom-hooks-in-react-44nd#:~:text=Custom%20hooks%20allows%20you%20to,not%20possible%20with%20class%20components.)

**Using any list of custom hooks, research and name one that you think will be useful in your applications** useArray hook - this would be useful for array manipulation.

**Describe how a hook that fetches API data might work** It looks like you could use useEffect with axios to fetch data from an API. I'm curious to see how that works! [resource](https://www.robinwieruch.de/react-hooks-fetch-data)

## Terms

- **reducer** A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently. [resource](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/#:~:text=A%20reducer%20is%20a%20function,so%20that%20they%20behave%20consistently.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Hooks but I want more clarification on them
1. useEffect but I want more clarification on it
1. fetching data from APIs

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. custom hooks
1. redux
1. context

**What are you most excited about trying to implement or see how it works?** Understanding useEffect a bit more sounds interesting.

## Readings

- [context api](https://reactjs.org/docs/context.html)
- [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [react context links](https://github.com/diegohaz/awesome-react-context)

[<== Back](https://simoneodegard.github.io/reading-notes/)