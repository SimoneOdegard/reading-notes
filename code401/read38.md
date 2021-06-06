# Read 38

## Review, Research, and Discussion

**How granular should your reducers be?** When a change of any of those attributes would trigger a separate kind of action such as CHANGE_EMAIL or CHANGE_NAME. And sometimes such granularity is good and sometimes it might be much easier for reducers if they can distinguish between those two particular use-cases. [resource](https://reactkungfu.com/2016/11/how-granular-are-your-redux-actions/)

**Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched** Con - Try to avoid dispatching several times synchronously in a row in the places where you're concerned about performance. [resource](https://redux.js.org/faq/actions)

**Name a strategy for preventing the above** Ask if these actions are related but independent, or should actually be represented as one action. Try to balance the readability of reducers with readability of the action log. For example, an action that includes the whole new state tree would make your reducer a one-liner, but the downside is now you have no history of why the changes are happening, so debugging gets really difficult. On the other hand, if you emit actions in a loop to keep them granular, it's a sign that you might want to introduce a new action type that is handled in a different way. [resource](https://redux.js.org/faq/actions)

## Terms

- **store** A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it. A store is not a class. It's just an object with a few methods on it. To create it, pass your root reducing function to createStore. [resource](https://redux.js.org/api/store)
- **combined reducers** The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object. [resource](https://redux.js.org/api/combinereducers#:~:text=The%20combineReducers%20helper%20function%20turns,into%20a%20single%20state%20object.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Reducers. However, I feel like a lot of what we're going over for this reading is brand new.

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. async actions
1. Store
1. thunk

**What are you most excited about trying to implement or see how it works?** I'm curious about using reducers and understanding more about how they work.

## Readings

- [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
- [thunk middleware](https://github.com/reduxjs/redux-thunk)
- [redux thunk](https://www.digitalocean.com/community/tutorials/redux-redux-thunk)

[<== Back](https://simoneodegard.github.io/reading-notes/)