# Class 9 Reading Notes - Forms and JS Events

## Things I want to know more about

- What is "document.querySelector"

## HTML Forms

- Forms allow users to enter data, which is generally sent to a web server for processing and storage or used on the client side to immediately update the interface in some way
- HTMl is made up of form controls (called widgets)
- can be single or multi-line text fiends, dropdown boxes, buttons, checkboxes, or radio buttons
- commonly created using the `<input>` element
- `<form action="/my-handling-form-page" method="post">`
  - The `action` attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
  - The `method` attribute defines which HTTP method to send the data with (usually get or post).
- Why are forms so important in web development?
  - They allow the page to collect user data for use locally and on the server
- When designing a form, what are some key things to keep in mind when it comes to user experience?
  - don't use the reset button attribute, keep it simple and easy to understand.
- List 5 form elements and explain their importance.
 - `<fieldset>` - a way to create groups of widgets that share the same purpose to aid in styling and semantic purposes - note: include `<legend>` element after the opening `<fieldset>` to describe the purpose
 -  `<label>` element is the formal way to define a label for an HTML form widget. Labels are clickable!
-  `<section>` defines each section of the form
- `<select>` allows for dropdown menus 

## Learn JS - Introduction to Events

- "Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them."
- You should never use the HTML event handler attributes — those are outdated, and using them is bad practice.
- 
- How would you describe events to a non-technical friend?
 - events are actions that happen in response to input from the user
- When using the addEventListener() method, what 2 arguments will you need to provide?
  - The name of the event we want to register for
  - the code that comprises the function we want to run in response to it. 
- Describe the event object. Why is the target within the event object useful?
  - A parameter specified with a name such as "e", "event", or "evt" inside an event handler function. It is passed to event handlers to provide extra features and information. 
- What is the difference between event bubbling and event capturing?
  - bubbling "bubbles up" from the innermost element that was clicked. 
  - event capturing starts checking at the elements outer-most ancestor to see if it has a click event handler
  - `Event` objects have a function called `stopPropagation()` that can stop the handler after the first event is run.