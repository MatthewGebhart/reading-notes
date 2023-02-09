# Class 39 - React 3

## Reading

[NextJs](https://nextjs.org/learn/basics/create-nextjs-app)
- The basic file structure of a Next.js app includes the "pages" directory, where you define the routes of your application, and the "public" directory, where you can store static assets such as images and stylesheets.
- Next.js provides automatic code splitting, optimized asset loading, and other performance optimizations out of the box.
- You can also add custom server-side logic to your Next.js app, including APIs, and use built-in features such as CSS-in-JS, environment variables, and more.
- Next.js supports both client-side and server-side rendering, making it a versatile choice for a variety of use cases.
- In Next.js, navigating between pages is done using the Link component from the next/link package.
- To use the Link component, simply wrap the target URL or component with the Link component and specify the href attribute.
- The Link component supports both absolute and relative URLs.
- Next.js also provides a Router component for programmatic navigation, which allows you to navigate to different pages based on certain conditions or user actions.
- You can use the useRouter hook to access the current router state and perform navigation in response to user interactions.
- In Next.js, static assets (such as images, fonts, and other files) can be added to the public folder, which will be served under the root URL.
- Metadata about a page can be added using the head component from the next/head package.
- CSS styles can be added in multiple ways in Next.js:
- Global styles can be added to the pages/_app.js file.
- Page-specific styles can be added as a style tag in the head component.
- PostCSS libraries (like Tailwind!) can be used in combination with Next.js.

[React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)
- React Context is a feature in React that provides a way to pass data through the component tree without having to pass props down manually at every level.
- It allows components to access data that is defined at a higher level in the component tree, making it available to all components within the tree.
- React Context is created using the `React.createContext` method, which returns an object with a Provider and a Consumer.
- The Provider is used to store the data that should be made available to the components, and the Consumer is used to access the data from the Provider.
- The Provider can be wrapped around multiple components in the tree to make the data available to all of them.
- React Context can be used for various purposes, including managing global state, providing themes, and handling authentication.
- React Context should be used judiciously, as it can make the codebase complex and harder to debug if not used properly.
- It is best used for data that is not updated often such as (theme data like dark mode, user data like currently authenticated user, location specific data like language)

## Videos
[Why I’m using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)
- This is a repeat of a previously assigned video. It is an overview of why Next.js is great

[Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)
- good overview of how to utilize useContext in React

## Bookmark and review

[Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)
- a GH repository with very handy examples (templates) for useing Next.js in a variety of applications

## Things I want to know more about
- useContext is best for data that does not need to be updated often, is there a better way to share states or data that does need to be updated often between components?