## React
![api](https://i.ibb.co/XXVH7vy/REACT-JS-KOCHI.png)

### Component Lifecycle / useEffect()
Using this Hook, we tell React that the component needs to do something after render. 
### Why do we not need more .html pages in a multi-page React app?
A single-page application is an application that loads a single HTML page and all the necessary assets (such as JavaScript and CSS) required for the application to run. Any interactions with the page or subsequent pages do not require a round trip to the server which means the page is not reloaded.

### If we wanted a component to show up on every page, where would we put it and why?
- Inside the <BrowserRouter />, outside a <Route />
### What does routing do with the components that were rendered when a new route is requested
When a change happens it triggers a callback, which in this case sets the state to the About component.
### What does props.children contain?
props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component
### How do useState() and this.setState() differ?
- The setState function is used to handle the state object in a React class component.
- With a functional component, we can use React hooks, specifically the useState() hook.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|State Hook|A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.|
|Mounting and Un-Mounting|A React component's lifecycle contains distinct phases for creation and deletion. In coding terms, these are called mounting and unmounting.|
