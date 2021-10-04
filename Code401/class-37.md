## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)


### Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle.
### What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state
### What does an action contain?
An action is a plain JavaScript object that has a type field. You can think of an action as an event that describes something that happened in the application.
### Why do we need to copy the state in a reducer?
If the new state is different, the reducer must create new object

|Term|Description|
|----|----|
|immutable state|an object whose state cannot be modified after it is created|
|time travel in redux|Time travel is the ability to move back and forth among the previous states of an application and view the results in real time.|
|action creator|An action creator is merely a function that returns an action object|
|reducer|A reducer is a function that determines changes to an application's state.|
|dispatch|dispatch is a function of the Redux store. You call store.dispatch to dispatch an action. This is the only way to trigger a state change. |
