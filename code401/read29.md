# Read 29

## Review, Research, and Discussion

**Do child components have direct access to props/state from the parent?** Yes. The parent can always pass props from the parent to child component.

**When a component “wraps” another component, how does the child component’s output get rendered?** Wrapper components are components that surround unknown components and provide a default structure to display the child components. To create wrapper components, you’ll first learn to use the rest and spread operators to collect unused props to pass down to nested components. Then you’ll create a component that uses the built-in children component to wrap nested components in JSX as if they were HTML elements. Finally, you’ll pass components as props to create flexible wrappers that can embed custom JSX in multiple locations in a component. [resource](https://www.digitalocean.com/community/tutorials/how-to-create-wrapper-components-in-react-with-props)

**Can a component, such as ```<Content />```, which is a child also be used as a standalone component elsewhere in the application?** Yes. React components can be recursive passing in a modified version of the props it received. [resource](https://www.bitovi.com/blog/recursive-react-components)

**What trick can a parent use to share all props with it’s children** You can use the ... spread operator to pass all props simultaneously. [resource](https://medium.com/coding-at-dawn/how-to-pass-all-props-to-a-child-component-in-react-bded9e38bb62)

## Terms

- **props.children** You can use props.children on components that represent ‘generic boxes’ and that ‘don’t know their children ahead of time’. It is used to display whatever you include between the opening and closing tags when invoking a component. [resource](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)
- **composition** React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop. [resource](https://formidable.com/blog/2021/react-composition/#:~:text=What%20Is%20React%20Composition%3F&text=In%20terms%20of%20refactoring%2C%20React,structure%20and%20complete%20your%20application.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Child components
1. React routers but I would like more information about them
1. Hooks although I'd like more information about using them

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Understanding the spread operator and how it passes all props simultaneously.
1. Learning more about wrapper components
1. Learning more about the different queries

**What are you most excited about trying to implement or see how it works?** I want to see the spread operator and how it passes all props simultaneously

## Readings
- [browser router tutorial](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)
- [browser router api docs](https://reactrouter.com/web/api)

**Bookmark**
- [react-if component](https://www.npmjs.com/package/react-if)
- [react testing library queries](https://testing-library.com/docs/queries/about/)
- [aria roles](https://www.w3.org/TR/html-aria/)

[<== Back](https://simoneodegard.github.io/reading-notes/)