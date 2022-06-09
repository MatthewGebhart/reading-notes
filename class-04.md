# Class 4 Reading Notes

## Things I want to know more about

- I want to learn more about writing and calling from arrays and how this can simplify my code
- 

## HTML Chapter 4: Ch.4 “Links” (pp.74-93)
- Links are created in a <a> element
- Linking to other sites 
  - `<a href="http:www.coollinkylink.com">Cool Link</a>`
- links to pages on the same site can use a "relative" URL (href="index.html")
- organize pages in folders
- Open link in a new window add `target="_blank" to link
- Link to specific parts of a page by giving them id attributes (id="top") and linking with href=#top can also work when linking to other sites

## HTML Chapter 15: “Layout” (pp.358-404)

- CSS treats each HTML element as its own box, these can be block-level box (start on new line) or inline box (float in between surrounding text)
- block-level elements can sit inside another - parent and child - "nesting
- positioning
  - normal positioning, relative positioning (moves it top, right, bottom, or left), absolute positioning (taken out of normal flow and move as users scroll up and down), fixed positioning (form of absolute that positions in relation to the browser window, does not move when scrolling, floating elements (becomes block level elements that other content flows around - float-left)

## JS Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)

- a Function is a group pf statements together to perform a specific task
- not always executed when a page loads so they can store the steps needed for a task
- Declaring a function - function sayHello() {
    document.write('hello');
    }
- Calling a function `sayHello();
- if a function needs information you outline the parameters in the ()
- Functions can return a single value or multiple values using an array
- Variables defined within a function will only be used by that function (Variable scope)
- Global variables use memory and can interfere if the same variable name is used elsewhere - local function scope variables avoid that conflict 

## Article: “6 Reasons for Pair Programming”

1. Greater efficiency
  - Takes slightly longer but produces higher-quality code that will save more time later
2. Engaged collaboration
  - More likely to stay on task and not waste time. 
  - Problem solving together boosts confidence
3. Learning from fellow students
  - Can learn from others with different skill sets
4. Social skills
  - develop interpersonal skills, employers want to hire people who work well with others
5. Job interview readiness
  - Common in interviews to pair program with a current employee. Stellar communication skills are important
6. Work environment readiness
  - Being familiar with pairing are ready to hit the ground running at a new company without having to learn it afterwards


