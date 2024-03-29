# Class 9 notes - Functional Programming

## Reading

(Source credit: https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

- What is functional programming?
    - a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 
- What is a pure function and how do we know if something is a pure function?
    - It returns the same result if given the same arguments
    - It does not cause any observable side effects
- What are the benefits of a pure function?
    - Pure functions are stable, consistent, and predictable.
    - We don’t need to think of situations when the same parameter has different results
    - The code is easier to test
- What is immutability?
    - immutable data cannot change after it is created, you create a new object instead
- What is Referential transparency?
    - if a function consistently yields the same result for the same input, it is referentially transparent.


## Videos

(Source credit: https://www.youtube.com/watch?v=xHLd36QoS4k)

- What is a module?
    - a seperate JS file that does one thing
- What does the word ‘require’ do?
    - 
- How do we bring another module into the file the we are working in?
    - on the main page (app.js) we create a variable for the function = require(FILEPATH OF THE MODULE)
- What do we have to do to make a module available?
    - module.exports = FUNCTIONNAME in the module


## Things I would like to know more about

- modules. I can see how they might be useful to clean up code for big complicated functions but are modules only a NODE.JS thing or can we use them in other runtimes?