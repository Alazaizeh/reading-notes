## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)

###  Context API
Context provides a way to pass data through the component tree without having to pass props down manually at every level.

### Describe use cases useState() vs useReducer()
useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.
### Why do custom hooks need the use prefix?
This is mainly to have an extra option for sharing state and logic between components, Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.
### What do custom hooks usually do?
Custom Hooks offer the flexibility of sharing logic that wasn't possible in React components before. 
### Using any list of custom hooks, research and name one that you think will be useful in your applications
useColor();
### Describe how a hook that fetches API data might work
Put the fetchData function above in the useEffect hook and call it.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|reducer|Reducers are functions that take the current state and an action as arguments, and return a new state result. |
