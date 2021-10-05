## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)


### How granular should your reducers be?
Reducer functions should only depend on their state and action arguments, subscribed to the Redux store and reading data at a more granular level.
### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
Well, it is a Pro more than a Con since we have to change multiple states in multiple components, the fact that all the reducers can listen when the action is dispatched can reduce a lot of work, each reducer can provide a different logic to the same dispatcher.
### Name a strategy for preventing the above
Redux middleware

|Term|Description|
|----|----|
|store|A store is an immutable object tree in Redux. A store is a state container which holds the application's state.|
|combined reducers|The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore .|
