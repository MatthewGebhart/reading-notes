# Class 38 - React 2

## Reading

[React - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)
- React supports conditional rendering of components, allowing you to render a component based on some condition.
- Conditional rendering can be achieved using if-else statements, ternary operators, or logical && operator.
- The use of if-else statements or ternary operators can be used within the render method to conditionally render components.
- The logical && operator can be used to conditionally render components by using a truthy expression.
- In some cases, it's useful to render a component only when a certain condition is met, and use a placeholder component in other cases.
- React also provides short-circuiting techniques, such as the use of the && operator or conditional render functions, to render components conditionally.
- It is important to keep in mind that conditional rendering should be used sparingly and should be used to control the display of UI elements rather than data.

[React - Lists & Keys](https://reactjs.org/docs/lists-and-keys.html)
- Lists and keys are an important concept in React for rendering a dynamic set of elements.
- Keys are used by React to track the items in a list, and ensure that updates to the list are efficient and correct.
- The key should be a unique identifier for each item in the list, such as an ID from a database.
- Keys are assigned using the key prop, and can be added to any component that is rendered as part of the list.
- When updating a list, React uses the keys to determine which items have changed, added, or removed, which allows for efficient updates.
- If a key is not provided, React will generate a default key based on the item's index in the list, but this may not be optimal and can lead to performance issues.
- Lists can be rendered using the built-in map function, or using a looping structure like for or forEach.
- When working with lists, it's important to consider performance, such as avoiding re-rendering the entire list when only a single item changes.
- Keys should only be used within a list, and should not be used as a general-purpose means of tracking state between renders.


[React - Forms](https://reactjs.org/docs/forms.html)
- A controlled component is a form element whose value is controlled by React, rather than by the DOM.
- React provides two main ways to handle forms: Controlled components and Uncontrolled components.
- Controlled components use state to store the input values and handle changes to the input elements.
- Uncontrolled components use refs to access the values of form elements directly from the DOM.
- React provides several built-in form-related components, such as input, textarea, select, and others.
- React also provides event handlers for handling changes to form elements, such as onChange, onBlur, onFocus, and others.
- React provides a way to validate form inputs through use of libraries or custom validation functions.
- React's form handling capabilities can be combined with other React features, such as conditional rendering and integration with other libraries.

[React - Lifting State](https://reactjs.org/docs/lifting-state-up.html)
- "Lifting state up" in React refers to moving shared state from multiple components to their closest common ancestor.
- Sharing state between components can be challenging and make code difficult to maintain.
- By lifting state up, components become easier to reason about and manage, as well as more reusable.
- To lift state up, create a new component that will hold the shared state, then pass data and functions down to child components via props.
- The child components can then call the functions passed down via props to modify the state, and the state changes will be reflected in all components that use the shared state.
- This pattern can be repeated as needed, with state being lifted up to higher and higher levels of the component tree as needed.
- Lifting state up makes it easier to understand the relationships between components and their data, and allows for greater control over how data is managed and updated in a React application.

[React - Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
- React uses a concept of "composition" to build UI components.
- Composition refers to creating complex components by combining simpler, smaller components.
- In React, components can receive data (props) from their parent components, allowing for reusability.
- Inheritance, in contrast, is a way to extend a class to create a new class with additional properties and methods.
- React does not use inheritance in the traditional sense, as components are not classes that can inherit from other components.
- Composition is favored in React because it provides a cleaner and more flexible way to manage the data flow and behavior of components.
- React also provides a way to share functionality between components through "Higher-Order Components".
- Higher-Order Components are functions that take a component as an argument and return a new component with additional props.
- The choice between composition and inheritance will depend on the specific requirements of the components being built.

[Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- Thinking in React is a guide to understand the basic principles of building applications with React.
- It emphasizes breaking down a user interface into components, which represent a piece of the UI, and managing their state and behavior.
- The guide suggests a 5-step process for building a React application:
    - Start with a mock, a hand-drawn sketch, or a wireframe of the UI
    - Break the UI into a component hierarchy
    - Build a static version of the UI using components, without worrying about interactivity or data
    - Identify the state and where it should live
    - Add interactivity by passing data from state and props down the component tree
- The guide also highlights the importance of unidirectional data flow and keeping the state minimal and non-redundant.
- This approach helps to keep the code organized, maintainable, and easy to debug.
- The guide concludes by suggesting to continue iterating on the design and development process, refining and improving the components as necessary.

## Bookmark and review
- [React - Comprehensive Guide](https://ui.dev/classic-react)
- [Heroicons](https://heroicons.com/)

## Things I want to know more about
- Wow, that is a lot to take in. I'm sure I'll have more questions later.