# Class 10 reading notes - Readings: In memory storage

## Reading

### Understanding the JavaScript Call Stack
(source credit: https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

- What is a ‘call’?
  - a function invocation
- How many ‘calls’ can happen at once?
  - only one at a time. JS is single-threaded
- What does LIFO mean?
  - Last In First Out - it means the last function pushed into the stack is the first one to pop out when the function returns. 
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
  - Insert drawing here
- What causes a Stack Overflow?
  - a recursive function which is a function that calls itself without an exit point. 

### JavaScript Error Messages
(Source credit: https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- What is a ‘reference error’?
  - when you try to use a variable that is not declared
- What is a ‘syntax error’?
  - something that cannot be parsed in terms of syntax
- What is a ‘range error’?
  - an array with negative length or invalid length
- What is a ‘type error’?
  - when the types (number string boolean etc.) are incompatible (like undefined)
- What is a breakpoint?
  - a place to intentionally stop the code from running further for debugging purposes
- What does the word ‘debugger’ do in your code?
  - it allows you to debug up to that line and gives you options in the browser developer tools. 

### Things I want to know more about

- The debugging article was a bit hard to follow. I need some real-world examples. 
