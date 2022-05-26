# Class 4 Reading Notes

## **Wireframe and Design**

### An introduction to wireframing

- What is a wireframe?
  - process used by UX designers to sketch out a rough idea of what a website will look like
  - black and white diagrams
  - intentionally simplistic
- Wireframe examples
  -Can be hand drawn, paper-prototypes, or created in software
- Things to consider before you start wireframing
  - Complexity of the process is determined by the goals of the page - how much emphasis on design does it need or have budget for
- The best tools for wireframing
  - Pen and paper
  - UXPin
  - InVision
  - Wireframe.cc - free within browser

### 6 Steps to make a wireframe

1. Do your research

- UX design is a process - who is your audience, requirements for the page

2. Prepare your research for quick reference

  - keep thinking about the purpose and audience of the page

3. Make sure you have your user flow mapped out

 - have an idea of where users will be coming from and how they might be using the page/website. Users should easily be able to figure everything out themselves

4.  Draft, don’t draw. Sketch, don’t illustrate

  - time to draw, focus on simple. Sharpie. Functional blocks and basic info
  - organize content to support users' goals
  - which information should be prominent?
  - What buttons will the user need to complete desired actions?

5.  Add some detail and get testing

  - add detail like reading a book top-to-bottom and left-to-right
  - basic usability conventions: navigation at top, search box at top right
  - a wireframe serves as a common language between designers, stakeholders and web and app developers
  
6. Start turning your wireframes into prototypes
 - start developing high-fidelity prototypes
  - software - Adobe XD, Proro.io, Framer
  - industry-leading tool for prototyping is InVision

### How to make your wireframe good: Three key principles

1. Maintain clarity
  - answer the questions of what the site page is and what a user can do there
2. Gain user confidence
  - ease of navigation, clear calls-to-action
  - placing navigation and buttons in predictable and intuitive places
3. Simplicity is key
  - too much information can be distracting to the user
  - as little extra "fluff" as possible. 

## **Mozilla HTML Basics**

- What is HTML?
  - HTML is the code used to structure a web page and its content. 
  - Paragraphs, bullet points, images, data and tables
- an element is a whole line or command together
- attribute is extra information about the element (class="editor-note" class is an attribute that can be targeted)
- HTML comment `<!--sample html comment: -->` to add comments to HTML that will not be visible on the page
- Lists
  - `<ul></ul>` unordered list
  - `<ol></ol>` Ordered list
  - each list element is inside `<li></li>`
  - Links`<a></a>` = anchor brackets the link - href(hypertext reference) is element attribute `<a href="https://www.cheeseisgood.com/">Cheesemaking guide</a>`
  
  ----

## **Semantics**

- Semantics refers to the *meaning* of a piece of code
  - What effect does running that line of JavaScript have?
- HTML should be coded to represent the data that will be populated - H1 headers are a title for example

----

## **Mozilla HTML Docs**

- HTML markups include  `<head>, <title>, <body>, <header>, <footer>, <article>, <section>, <p>, <div>, <span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li>` and many others.
- tags are not case sensitive `<title>` vs `<Title>`

----

## **Mozilla HTML elements**

- `<html>`  - main root  - all other elements must be descendants of this element
- `<style>` - CSS style information 
- `<nav>` - navigation links
- `<p>`  - paragraph
