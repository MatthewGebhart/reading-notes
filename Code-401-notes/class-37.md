# Class 37 - React 1

## Reading ES6 overview

### ES6 Syntax and Feature Overview
[Source Credit](https://www.taniarascia.com/es6-syntax-and-feature-overview/)
- Some key features of ES6 include:
    - let and const keywords for variable declaration
    - Arrow functions
    - Template literals
    - Destructuring
    - Classes
    - Modules
    - Promises
    - Maps and Sets
- The let and const keywords allow for block-scoped variable declaration, whereas the var keyword is function scoped.
  - array iteration looping
    ```
    for (let i of arr) {
      console.log(i)
    }
    ```

## Reading - React

[Hello World](https://reactjs.org/docs/hello-world.html)


[JSX](https://reactjs.org/docs/introducing-jsx.html)
- JSX produces React “elements” like `const element = <h1>Hello, world!</h1>;`
- After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.
- you can use JSX inside if statements and for loops, assign to variables


[Rendering Elements](https://reactjs.org/docs/rendering-elements.html)
- React allows you to build reusable UI components.
- In React, elements are the smallest building blocks of a UI.
- Rendering an element into a DOM node is done using the `ReactDOM.render()` method.

[Components & Props](https://reactjs.org/docs/components-and-props.html)
- components allow you to split the UI into reusable and independent parts.
- Components can be either class components or functional components, depending on the use case.
- Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.
- Props are data that are passed from a parent component to a child component.
- Components can render other components, allowing for complex UIs to be built up from simple components. 
- Components can also manage their own state, which allows them to keep track of changes in their data and update the UI accordingly. 
- Components should aim to be reusable, composable, and modular, making it easier to build and maintain complex applications.

[State & Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
- React state is an object that holds data that can change within a React component.
- The state can be updated using setState(), which will trigger a re-render of the component.
- Lifecycle methods include: `constructor`, `componentDidMount`, `shouldComponentUpdate`, `render`, `componentDidUpdate`, and `componentWillUnmount`.
- `constructor` is called before the component is mounted and is used to initialize the state and bind event handlers.
- `componentDidMount` is called after the component is mounted and is used to initiate any data fetching or setup that requires the component to be fully rendered.
- `shouldComponentUpdate` is called before render and can be used to optimize performance by avoiding unnecessary re-renders.
- `render` returns a description of what the component should render.
- `componentDidUpdate` is called after render and is used to perform any post-render operations, such as updating the state based on the updated DOM.
- `componentWillUnmount` is called before the component is unmounted and is used to perform any necessary cleanup.

[Handling Events](https://reactjs.org/docs/handling-events.html)
- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.
- Another difference is that you cannot return `false` to prevent default behavior in React. You must call `preventDefault` explicitly
- Event handlers are passed as props to components and are triggered by specific events, such as "onClick" or "onChange."
- It is recommended to use arrow functions when defining event handlers in order to preserve the value of "this."
  - `<button onClick={(e) => this.deleteRow(id, e)}>Delete Row</button>`
  - instead of `<button onClick={this.deleteRow.bind(this, id)}>Delete Row</button>`

## Reading - Tailwind CSS
[Utility First CSS](https://tailwindcss.com/docs/utility-first)
- Tailwind CSS is a utility-first CSS framework. 
- It prioritizes utility classes over pre-designed UI components, allowing developers to easily add styles to their HTML elements. 
- The framework provides a large number of pre-designed CSS classes, covering various styles such as spacing, colors, typography, and more. 
- These classes can be composed to create custom designs without having to write custom CSS code. 
- The utility-first approach leads to fast development, increased consistency in design, and improved maintainability of the code.

## Reading - Next.js
[Learn Next.js](https://nextjs.org/learn/basics/create-nextjs-app)
- Next.js is a React-based framework for building server-side rendered and statically generated web applications.
- The basic file structure of a Next.js app includes pages, components, public, and node_modules directories.
- Pages are React components that define the routes of your app and serve as the entry point for each page.
- Components are reusable UI elements that can be used throughout your app.
- The public directory holds static files, such as images and fonts, that should be accessible to the client.
- The node_modules directory contains all the packages that your app depends on, installed via npm or yarn.

[Why to use Next.js]()
- Next.js is a framework built on top of react that abstracts away some complexity while still giving you the flexibility to build scalable react applications
- traditional react can only render on the client side, Next.js lets you render on the server or client or both
- it allows you to choose which data fetching strategy makes the most sense give your use case
- analogy - react is like Linux and Next.js is like a distribution of linux
- it makes performance easier
- code-splitting determines which sections need certain parts of JS and extracts it out into shared chunks
- it is built on top of webpack and allows you to customize webpack
- react fast refresh allows the React state to be preserved when making changes to components
- debugging - a modal pops up showing a source map of where errors are occurring 
- common misconception that you can only deploy to Vercel
- Next.js has a great developer community including members of the React core team
- it is used in production at 5 of the fortune 12 companies


## Things I want to know more about
- Excited to learn more about Next.js