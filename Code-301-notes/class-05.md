# Class 5 notes - Putting it all together

## React Doc - Thinking in React

(source credit: https://reactjs.org/docs/thinking-in-react.html)

- What is the `single responsibility principle` and how does it apply to components?
  - a component should only do one thing
- What does it mean to build a ‘static’ version of your application?
  - Build the UI but no interactivity
- Once you have a static application, what do you need to add?
  - `state`  to add interactivity 
- What are the three questions you can ask to determine if something is state?
  - Is it passed in from a parent via props? If so, it probably isn’t state.
  - Does it remain unchanged over time? If so, it probably isn’t state.
  - Can you compute it based on any other state or props in your component? If so, it isn’t state.
- How can you identify where state needs to live?
  - By identifying every component that renders something on that state
  - Find a common owner component in the hierarchy. 

## Higher-Order Functions

(Source Credit: https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

- What is a “higher-order function”?
  - functions that operate on other functions
- Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?
  - it creates a new function to see if m is greater than n
- Explain how either `map` or `reduce` operates, with regards to higher-order functions.
  - `map ` transforms an array by applying a function to all of its elements and putting them into a new array.