# Class 01 Reading notes

## Things I want to know more about

- Clarity on the `<div>` tag and how it is used in modern web design
- when to add JS right in the HTML with `<SCRIPT>` tag vs referencing a seperate .js file
- Would you ever have multiple .js files? How would they interact with the order the code is run?

## HTML Chapter 1 - Structure

- Tags act like containers, they tell you something about the information that lies between them
- The terms "tag" and "element" are often used interchangeably
- Attributes provide additional information about an element
  - they are in the opening tag and contain an attribute name and value
  - `<p lang="en-us">paragraph in english</p>`

## HTML Chapter 8 - Extra Markup

- Begin every page with HTML declaration `<!DOCTYPE html>`
- <!-- add comments like this--> (or cmd + ? on my mac)
- id attributes identify the elements from other elements 
  - a "global attribute" that can be used on any element
  - `<p id="pullquote">`
- Class attributes can identify several elements and help with applying CSS
- Block level elements always start on a new line 
  - `<h1>, <p>, <ul>, <li>`
- inline elements will appear to continue on the same line
  - `<a>, <b>, <em>, <img>`
- `<div>` allows you to group a set of element together in one box
- `<span>` is like the inline version of div and usually contains a class or id attribute
- `<iframe>` is like a little window that shows a link to another page
- `<meta>` lives in the head and contains hidden information about the page
- To use some of the characters that are reserved by HTML (escape characters) you can use a special code to display them (usually starts with &)

## HTML Chapter 17 - HTML5 Layout

- replaces many of the `<div>` elements 
- `<nav>` major navigational blocks
- `<article>` Container for a section of a page that could stand alone "blog post"
- `<aside>`  sidebar with content about article or entire page
- `<section>` groups related content together and typically have its own heading
- `<hgroup>` group set of heading tags together 
- `<figure>` images, videos, graphs, diagrams, code examples
- `<div>` a holdout from HTML4 that groups related elements together
- `<a>` allows linking around block level elements

## HTML Chapter 18 - Process and Design (pp.452-475)

- Things to think about when designing a website
  - *who* is the site for (target audience)
  - *why* people are visiting
  - *what* are they trying to achieve?
  - *what information* do visitors need?
  - *how often* will they visit my site
- Site maps - create a a flow of sections or pages to meet the needs of a side
- Wireframes - simple sketch of the key information for a page, how much space it might require. Can help for collaboration and simplify the technical site creation based on your design goals
- Visual Hierarchy
  - Larger elements will grab attention first
  - color (foreground and background) can draw attention to key elements
  - style (bold, italics) can make text stand out
- Group similar elements together
- Navigation element should be clear, concise, selective, provide context, interactive, and consistent

## JS Chapter 1 - The ABC of Programming (pp.11-52)

- A script is a "series of instructions that a computer can follow to achieve a goal. (like a recipe or manual)
- Determine the goal and then decide the steps required to reach it. 
- Vocabulary - words the computer can understand
- Syntax - how to put those words together to create instructions the computer can follow
- Think *programatically* -  like a computer - don't assume the computer will know anything you don't tell it

- Computers create models of the world using data
  - objects (things) - hotel or car etc. 
  - properties (characteristics) - hotel rating, car model etc. 
  - events - let you know something just happened
  - methods - interactions that make events happen
  - ex. "When this event occurs, run that code"
  - Web browsers use HTML markup to create a model of the web page, JS makes the pages interactive
  
  - best practice is to keep HTML (.html), CSS(.css), and JS(.js) files separate
  - "Progressive Enhancement" HTML --> add CSS --> add JS
  - source code (HTML) is not changed by .js file
  - Javascript runs where it is found in the HTML
    - `<script src="js/add-content.js"></script>`