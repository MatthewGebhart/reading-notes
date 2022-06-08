# Class 3 Reading Notes

## Things I want to know more about

## HTML Chapter 3: “Lists” (pp.62-73)

- Ordered lists `<ol>` , unordered lists `<ul>`
- definition lists `<dl>` contain term being defined `<dt>` and definition `<dd>`
- Lists can be nested inside each other

## HTML Chapter 13: “Boxes” (pp.300-329)

- Set box (HTML element) size with width and height (width: 400px; height: 300px;)
- min-width and max-width and min-height, max-height can be useful for smaller screens (like phones)
- overflow property tells the browser what to do if the content doesn't fit into a box (hidden, scroll)
- Margin is space outside the border, padding is space inside the border before content
- centering a box on a page with left-margin and right-margin to auto after setting a width for the box
- centering text in a box with the text-align: center property (can also be left or right)
- display inline causes block-level elements to display in line,
- box-shadow - to create drop shadow on boxes
- border-radius: (10px) to created rounded corners (can also use percentages)

## JS Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)

- Arrays - store a list of values listed in [brackets]
  - ex. - colors = ['white', 'black', 'custom'];
  - values are listed as an index - first value is 0, second value is 1, and so on
- accessing arrays - retrieve based on the index number
  - ex. - let itemThree = colors[2];

## JS Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

- Switch statements can run different code based on a possible value for a variable
- each case will execute different code then a break keyword will end the script
- The entire statement lives in one set of curly braces and can simplify the computation requirements for the code
- JS will use type coercion to try to "make sense of" data types it did not expect
- Truthy and Falsy values
  - Falsy is Boolean false, the number 0, and empty value ' ', not a number, or a variable with no value assigned
  - everything else is a truthy value
  - strict equality operators (===) and (!===) result in fewer unexpected values
- Loops - check a condition, if it returns true, a code block will run, then it will run again until the condition is false
- `for (var i = 0; i < 10; i++) {document.write(i);}`
- Three types of loops - `for`, `while`, and `do while`
- a `for` loop uses a counter as a condition, the code runs a specified number of times
- Keywords in loops
  - break - terminates the loop and moves on to the next statement of code outside the loop (also use in functions)
  - continue - tells to stop the current iteration and check the condition again - if true it runs again
- Loops are useful in arrays to run the same code for each item in an array
- `while` loops run as long as the condition in () is true
- `do while` loops run a code block before the condition so it is run at least once
