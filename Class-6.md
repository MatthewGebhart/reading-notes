# Class 6 Reading notes

## JavsScript intro

- lightweight, interpreted "Just-in-time" complied programming language with "first-class functions"
- object-oriented, imperative, and declarative (functional programming) styles
- Don't confuse with Jave - they are very different
- API - Application Programming Interface - like a premade building block to implement programs (like a furniture kit with all the pieces and hardware ready to go)
- Two general categories of APIs
  - Browser APIs - built into the web browser and expose data from the surrounding computer environment
    - DOM (Document Object Model) API) manipulate HTML and CSS, dunamically change styles
    - Geolocation API - retrieves geographical information (google maps)
    - Canvas and WebGL APIs allow you to create animated 2d and 3d graphics
    - Audio and Video APIs like HTMLMediaElement and WebRTC play audio or video right in a webpage
  - Third party APIs are not built into browser by default, you have to grab their code and information from somewhere
    - Twitter API - allows you to display your latest tweets on your website
    - Google Maps API allow you to embed custom maps into your website
- "execution environments" - your browser tab - where the HTML, CSS and JavaScript are run
- Interpreted vs compiled code
  - Interpreted code is frun from top to bottom then returns the result. Code does not need to be transformed before the browser runs it.
  - Compiled languages (like C/C++) are transformed (compiled) into another form before being run. the program is executed in a binary format as opposed to text-form
- JavaScript is a lightweight interpreted programming language. Uses a technique called just-in-time compiling to improve performace. Source code gets compiled into faster binary format whild script is being used for faster performance. But JS is still considered an interpreted language since compilation is handled at run time
- 