# Class 2 notes

## React lifecycle

(source credit: https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - the "render phase" happens first
- What is the very first thing to happen in the lifecycle of React?
  - Mounting -> Updating -> Unmounting. So Mounting happens first. 
- Put the following things in the order that they happen: `constructor`, `render`, `React Updates`, `componentDidMount`, `componentWillUnmount`: Done (put in order)
- What does componentDidMount do?
  - It is invoked immediately after a component is mounted. This is where network requests go or to initalize the DOM. Also a good place to set up any subscriptions. 

## React State Vs. Props

- What types of things can you pass in the props?
  - starting number, titles, subtitles, 
- What is the big difference between props and state?
  - state is something inside a component. Props you pass into a component, State is handled inside of the component and can be updated inside the component. Props are handled outside and must be updated outside. When you change a state, it's going to rerender that section
- When do we re-render our application? 
  - if we want to change something we do it in a state so it re-renders
- What are some examples of things that we could store in state?
  - input elements in a form, counters

## Things I want to know more about

- How does the React lifecycle determine how we build out our components?
- How to manipulate states in components. 
