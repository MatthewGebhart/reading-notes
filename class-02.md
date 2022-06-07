# Class 2 Reading Notes

## Things I want to know more about
- JS variables: book used `var` but we learned `let` or `const`
- ~~do we have to declare variables or just assign them? (let time = 3) vs (var time; time = 3)~~ Answered later - can declare and assign value in the same statement


## HTML Chapter 2: “Text” (pp.40-61)

- HTML elements are used to describe the structure of the page - headings, subheadings, paragraphs
- Elements also provide semantic information - where emphasis should be placed, definitions of acronyms, what text is a quotation
- 6 levels of headings h1-6
- `<p>` for paragraph, `<i>` for italic, `<b>` for bold, `<sub or sup>` for sub or super script
- `<br />` adds a line break in the middle of a paragraph
- `<hr />` creates a break between themes
- Semantic markup
  - `<strong>` `<em>` `<blockquote>` `<p>``<abbr>` - abbreviation `<cite>` - citation `<dfn>` definition of new terminology `<address>` `<ins>` `<del>` `<s>` - strikethrough

## HTML Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)

- Associating rules with HTML elements
  - Selector and declaration
  - p {font-family: Arial;}
- Declarations have a property and value
  - {font-family(property): Arial (value); }
- Linking to external CSS style sheet
  - `<link href="stylesheet.css" type="text/css" rel="stylesheet" />`
- internal (inline style)
  - `<style>` tags
- Selectors
  - identifies what elements to apply CSS to
  - h1, class="note", id="top", Can let you selectively target certain elements with id or class tags
- CSS rules cascade and will follow the bottom most rules
- CSS can be inherited by child elements

## JS Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

- A Statement is each individual step in a script
- Write comments to explain what your code does so other developers can understand what is going on
- Variable stores data for a script to call upon
- Declare variables var (or let?) then the variable name "time" 
- Assign a value to the variable (quantity = 3)
- JS distinguishes between numbers, "strings" (words), and Booleans (true/false)
- Pay attention to single or double quotes inside strings
- array - a list of values (number, string, or Boolean) in brackets and separated by commas
- you can call upon a value stored in an array by it's number in the list (starting with 0) 
  - `itemthree = colors[2];`

## JS Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)

- Flowcharts can help determine what decisions should be made next 
- two components to a decision
  - expression is evaluated and returns a value
  - a conditional statement says what to do in a given situation
- `if (score > 50) {document.write("something here");} else {document.write("try again");}`
- comparison operators == (equal to), === (strict equal to must be same data type - string, number, Boolean), != not equal to, !== strict not equal to, > greater than, < less than, >= greater than or equal to etc. 
- Comparison operators usually return true or false
- Logical operators compare the results of more than one comparison operator ( && both true or false, || if either condition is true, ! takes a single Boolean and reverses it)
- `if` statements checks if a condition is true then executes subsequent code block
- `if...else` statements executes different code if the condition is false
  - `if (score >=50) {congratulate ();} else {encourage();}`
- Switch statements start with variable called switch value, then code that should run if the variable matches that value. `break` keyword ends the script

