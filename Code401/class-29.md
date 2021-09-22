## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)

###  Advanced State with Reducers
Reducers are pure functions in that they produce the same output for a given input. They are without side effects and handle each state transition synchronously. 

### How can we ensure that an effect hook runs only once?
If we pass an empty array [] , it just renders the component only once like componentDidMount
### Can useState() update more than one state variable at the same time?
The setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.
### Is useState() synchronous
useState and setState both are asynchronous.
### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|State Hook|A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.|
|Component Lifecycle|We are born, grow, and then die. Almost everything follows this cycle in its life, and React components do as well. Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.|
