# Read: Class 02

## State and Props 

### React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? Render happens first.
2. What is the very first thing to happen in the lifecycle of React? Mounting is the first step in the lifecycle.
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates. Constructor, render, react updates, componentDidMount, and componentWillUnmount
4. What does componentDidMount do? If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.

### React State Vs Props

1. What types of things can you pass in the props? Title and subtitle
2. What is the big difference between props and state? With props you pass into a component and state is handled inside that component, props are handled outside the component and must be updated outside the component.
3. When do we re-render our application? We would re-render when we want to store something in state based on something the user has done.
4. What are some examples of things that we could store in state? user input in a forum or a counter application.
