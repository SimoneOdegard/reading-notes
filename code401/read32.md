# Read 32

## Review, Research, and Discussion

**What does a component’s lifecycle refer to?** Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is reffered to as a component lifecycle. [resource](https://www.freecodecamp.org/news/how-to-understand-a-components-lifecycle-methods-in-reactjs-e1a609840630/#:~:text=We%20are%20born%2C%20grow%2C%20and,to%20as%20a%20component%20lifecycle.)

**Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect** By wrapping it around a function declaration and defining the dependencies of the function, it ensures that the function is only re-created if its dependencies changed. Hence the function is NOT re-built on every render cycle anymore. No more infinite loop! [resource](https://medium.com/@infinitypaul/reactjs-useeffect-usecallback-simplified-91e69fb0e7a3#:~:text=useCallback()%20helps%20you%20prevent,out%20of%20the%20infinite%20loop!)

**Why are functional components preferred over class components?** Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks. You end up with less code. They help you to use best practices. [resource](https://djoech.medium.com/functional-vs-class-components-in-react-231e3fbd7108#:~:text=Functional%20component%20are%20much%20easier,you%20to%20use%20best%20practices.)

**What is wrong with the following code?**

```
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```

To my understanding, you want to avoid your useEffect from looping because it will become infinite. You'll want to implement useCallback to break the infinite loop and wrap the whole function with useCallback.

## Terms

- **state hook** A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. [resource](https://reactjs.org/docs/hooks-state.html#:~:text=A%20Hook%20is%20a%20special,React%20state%20to%20function%20components.s)
- **effect hook** What does useEffect do? By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates. [resource](https://reactjs.org/docs/hooks-effect.html#:~:text=What%20does%20useEffect%20do%3F,after%20performing%20the%20DOM%20updates.)
- **reducer hook** useReducer is one of a handful of React hooks that shipped in React 16.7. 0. It accepts a reducer function with the application initial state, returns the current application state, then dispatches a function. [resource](https://css-tricks.com/getting-to-know-the-usereducer-react-hook/#:~:text=useReducer%20is%20one%20of%20a,state%2C%20then%20dispatches%20a%20function.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. component lifecycles
1. functional components vs class components
1. state hook, effect hook, and reducer hook but I want to learn more about hooks in general

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. useEffect
1. useCallback
1. hooks

**What are you most excited about trying to implement or see how it works?** I'm excited to learn more about useEffect and useCallback. I'm excited to use and learn more about hooks.

## Readings

Authoring

- [custom hooks - all you need to know](https://www.telerik.com/kendo-react-ui/react-hooks-guide/#toc-custom-react-hooks)
- [async hooks](https://dev.to/vinodchauhan7/react-hooks-with-async-await-1n9g)
- [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)
- [react custom hooks](https://reactjs.org/docs/hooks-custom.html)

Hooks Lists/Collections

- [use hooks](https://usehooks.com/)
- [hooks list](https://github.com/rehooks/awesome-react-hooks)
- [10 essential react hooks](https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d)

[<== Back](https://simoneodegard.github.io/reading-notes/)