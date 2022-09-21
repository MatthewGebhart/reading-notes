# Class 3 notes

## React Docs - lists and keys

(source credit: https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?
  - an array that looped through the array it was fed after performing a function on each value in sequence
- If I want to loop through an array and display each value in JSX, how do I do that in React?
  - using curly braces {}
- Each list item needs a unique ____.
  - "key"
- What is the purpose of a key?
  - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity


## The Spread Operator

(source credit: https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?
  - it "expands" an array into a list of separate arguments that can be used in JS
- List 4 things that the spread operator can do.
  - passing an array into a JS function that is expecting separate arguments
  - copying an array
  - concatenating or combining arrays
  - using math functions
  - adding to a state in React
  - combining objects
- Give an example of using the spread operator to combine two arrays.
  - const myArray = [`🤪`,`🐻`,`🎌`]
  - const yourArray = [`🙂`,`🤗`,`🤩`]
  - const ourArray = [...myArray,...yourArray]
  - console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
- Give an example of using the spread operator to add a new item to an array.
  - const startArray = [1,3,5,7]
  - const newArray = [9, 11, ...startArray]
  - console.log(newArray) // Array (6) [9, 11, 1, 3, 5, 7]
- Give an example of using the spread operator to combine two objects into one. 
  - const fewFruit = ['🍏','🍊','🍌']
  - const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
  - console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

## How to Pass Functions Between Components

(source credit: https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?
  - create the function wherever the state is that we want to change
- In your own words, what does the `increment` function do?
  - It looks through an array using the map function to find an object with a state that needs to be changed and it changes the state on that object
- How can you pass a method from a parent component into a child component?
  - by making the method a prop on the parent component
- How does the child component invoke a method that was passed to it from a parent component?
  - through the onclick event

## Things I Want to Know More About

- I think I will just need some practice with these new concepts. I "think" I understand them but I need to practice to "really" understand them. 