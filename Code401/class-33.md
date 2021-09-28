## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)


### Why is the Context API useful?
Context provides a way to pass data through the component tree without having to pass props down manually at every level.
### Can a component outside of a provider get its context?
With the introduction of react-hooks in v16.8.0, you can use context in functional components by making use of useContext hook
### What are some common use cases for using the Context API?
* Theming 
* Authentication
### Describe “Context Hell”
React Context hell is the nasty code you get taking advantage of the React Context API.

|Term|Description|
|----|----|
|global state|a set of local states which are all concurrent with each other.|
|global context|Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes.|
|provider|Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes.|
|consumer|A React component that subscribes to context changes|
