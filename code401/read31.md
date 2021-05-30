# Read 31

## Review, Research, and Discussion

**Why do we not need more .html pages in a multi-page React app?** When you're using React, you can create routes instead of adding .html pages. The route acts as a new page.

**If we wanted a component to show up on every page, where would we put it and why?** Inside the ```<BrowserRouter />```, outside a ```<Route />```. ```<BrowserRouter />``` is needed to wrap the components that you want to render but ```<Route />``` is used for specific routes/pages. If you want something to show up on all pages, do not wrap it in ```<Route />``` because it will only show up to that specific route.

**What does props.children contain?** The React docs say that you can use props.children on components that represent ‘generic boxes’ and that don’t know their children ahead of time. this.props.children is used to display whatever you include between the opening and closing tags when invoking a component. [resource](https://www.semicolonworld.com/question/71475/what-is-this-props-children-and-when-you-should-use-it)

## Terms

- **Composition** React composition is a pattern that can be used to break a complex component down to smaller components, and then composing those smaller components to structure and complete your application. [resource](https://formidable.com/blog/2021/react-composition/#:~:text=What%20Is%20React%20Composition%3F&text=In%20terms%20of%20refactoring%2C%20React,structure%20and%20complete%20your%20application.)
- **Children / Child Components** The React docs say that you can use props.children on components that represent ‘generic boxes’ and that don’t know their children ahead of time. this.props.children is used to display whatever you include between the opening and closing tags when invoking a component. [resource](https://www.semicolonworld.com/question/71475/what-is-this-props-children-and-when-you-should-use-it)
- **Hash Routing** It uses the hash in the URL to render the component. [resource](https://stackoverflow.com/questions/51974369/what-is-the-difference-between-hashrouter-and-browserrouter-in-react)
- **Link Routing** To add the link in the menu, use the ```<NavLink />``` component by react-router-dom . The NavLink component provides a declarative way to navigate around the application. It is similar to the Link component, except it can apply an active style to the link if it is active. [resource](https://www.freecodecamp.org/news/react-router-tutorial/)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Browser Router and Router
1. props.children
1. multi pages using React

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Hooks
1. Hash and Link routing
1. Understanding props.children more

**What are you most excited about trying to implement or see how it works?** I'm interested in seeing how hooks work

## Readings

- [making sense of hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)
- [the state hook](https://reactjs.org/docs/hooks-state.html)
- [hooks api](https://reactjs.org/docs/hooks-overview.html)
- [hooks api reference](https://reactjs.org/docs/hooks-reference.html)
- [effects hook](https://reactjs.org/docs/hooks-effect.html)

[<== Back](https://simoneodegard.github.io/reading-notes/)