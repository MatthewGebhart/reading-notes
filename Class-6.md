# Class 6 Reading notes

## JavsScript intro

- lightweight, interpreted "Just-in-time" complied programming language with "first-class functions"
- object-oriented, imperative, and declarative (functional programming) styles
- Don't confuse with Java - they are very different
- API - Application Programming Interface - like a pre-made building block to implement programs (like a furniture kit with all the pieces and hardware ready to go)
- Two general categories of APIs
  - Browser APIs - built into the web browser and expose data from the surrounding computer environment
    - DOM (Document Object Model) API) manipulate HTML and CSS, dynamically change styles
    - Geolocation API - retrieves geographical information (google maps)
    - Canvas and WebGL APIs allow you to create animated 2d and 3d graphics
    - Audio and Video APIs like HTMLMediaElement and WebRTC play audio or video right in a webpage
  - Third party APIs are not built into browser by default, you have to grab their code and information from somewhere
    - Twitter API - allows you to display your latest tweets on your website
    - Google Maps API allow you to embed custom maps into your website
- "execution environments" - your browser tab - where the HTML, CSS and JavaScript are run
- Interpreted vs compiled code
  - Interpreted code is run from top to bottom then returns the result. Code does not need to be transformed before the browser runs it.
  - Compiled languages (like C/C++) are transformed (compiled) into another form before being run. the program is executed in a binary format as opposed to text-form
- JavaScript is a lightweight interpreted programming language. Uses a technique called just-in-time compiling to improve performance. Source code gets compiled into faster binary format whose script is being used for faster performance. But JS is still considered an interpreted language since compilation is handled at run time
- Server side vs Client side
  - Client side is code run on the users computer.
  - Server side is run on the server. Server side languages include PHP, Python, Ruby, ASP.NET and JavaScript
- Dynamic vs Static code
  - Dynamic code - update the display of a web page/app to show different things in different circumstances, generating new content as required.
  - Static - A web page with no dynamically updating content is referred to as static — it just shows the same content all the time.

  ## JavaScript Variables

  - 4 ways to declare a JS variable
    - Using `var`
    - using `let`
    - Using `const`
    - Using `nothing`
- Variables are containers for storing data (data values)
- Always declare JavaScript variables with `var`,`let`, `or const`
- `var`
  - The var keyword is used in all JavaScript code from 1995 to 2015.
  - The let and const keywords were added to JavaScript in 2015.
  - If you want your code to run in older browser, you must use var.
- `const` vs `let`
  - If you want a general rule: always declare variables with `const`
  - If you think the value of the variable can change, use `let`
- JavaScript Identifiers
  - All JavaScript variables must be identified with unique names.
  - These unique names are called *identifiers*
  - Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume)
  - The general rules for constructing names for variables (unique identifiers) are:
    - Names can contain letters, digits, underscores, and dollar signs.
    - Names must begin with a letter
    - Names can also begin with $ and _ (but we will not use it in this tutorial)
    - Names are case sensitive (y and Y are different variables)
    - Reserved words (like JavaScript keywords) cannot be used as names
- In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.
  - x = x+5
- JavaScript variables can hold numbers like 100 and text values like "John Doe"
- In programming, text values are called text strings
- Strings are written inside double or single quotes. Numbers are written without quotes.
- If you put a number in quotes, it will be treated as a text string.
- Declare a JS variable with `var` or `let`
  - it is undefined until it is assigned a value with the = sign
- Note - It's a good programming practice to declare all variables at the beginning of a script
- You can declare many variables in one statement. seperate them by a comma.
  - let person = "John Doe", carName = "Volvo", price = 200;
- 