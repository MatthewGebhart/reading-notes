# Class 01 Reading notes

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

## HTML Chapter 18 - Process and Design

- 