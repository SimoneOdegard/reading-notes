# Read 05

## Thinking in React
[Link](https://reactjs.org/docs/thinking-in-react.html)

Steps for creating a searchable product data table.
- **Start with a mock**: Break the UI into a component hierarchy: draw boxes around components so that you can map out how components will work. When creating this, you'll want to utilize the single responsibility principle where each component is doing one thing.
    - Example of mock hierarchy:
    - FilterableProductTable
        -SearchBar
        -ProductTable
            -ProductCategoryRow
            -ProductRow
- **Build a static version in React**: Build a version of your component hierarchy that has no interactivity. You want to have a lot of typing and no thinking. Don't use state when building the static version. It's easiest to building top-down.
- **Identify the minimal representation of UI state**: You will want to trigger changes to the underlying data model with state. Remember to not repeat yourself aka use the DRY method.
- **Identify where your state should live**: We need to figure out which component will own this state. It may not be immediately clear.
    - Note: React is a one-way data flow down the component hierarchy!
- **Add inverse data flow**: By this point your app should render with props and state flowing down the hierarchy. You would next need to flow the other way.

[<== Back](https://simoneodegard.github.io/reading-notes/)