# Class 4 notes - React and Forms

## React Docs - Forms

(source credit: https://reactjs.org/docs/forms.html)

- What is a ‘Controlled Component’?
  - an input form controlled by React to determine what happens in user input. 
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  - a `handlechange` function on the event handler will update state with each keystroke. I'm not sure why this is valuable?
- How do we target what the user is entering if we have an event handler on an input field?
  - The handleChange function will update state with each keystroke. a seperate handle submit event can trigger alerts or trigger other events. 


## The Conditional (Ternary) Operator Explained

(source credit: https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- Why would we use a ternary operator?
  - to simplify if-then statements and write them on one line
- Rewrite the following statement using a ternary statement:
- `if(x===y){
  console.log(true);
} else {
  console.log(false);
}`
- `x===y ? true : false;`

## Things I want to know more about

- I'd like to know the advantages of setting each keystroke of a form input to state as they come in. Seems like this could have nefarious uses by unsavorary characters. 