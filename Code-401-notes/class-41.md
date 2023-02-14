# Class 41 - React 4

## Reading

[Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)
- Dynamic Routes can be created by using square brackets in the page file name, e.g. [id].js.
- The value between the brackets will be available in the page component as a query parameter.
- The getStaticPaths function is used to specify which paths should be pre-rendered at build time.
- The getStaticProps function is used to fetch the data for a specific path at build time or at request time.
- Dynamic Routes can also be created using the useRouter hook in a functional component.
- Dynamic Routes are useful for creating pages that display unique content, such as product pages, user profiles, and blog post pages.


[Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)

- Deploying a Next.js application involves hosting the application's static files and serving the dynamic content through a web server.
- There are several options for deploying a Next.js application, including:
    - Static hosting services, such as GitHub Pages or GitLab Pages, for simple and low-traffic sites.
    - Cloud platforms, such as Vercel, Heroku, or AWS, for more complex and scalable applications.
    - Custom servers, such as a VPS or a dedicated server, for full control and customization.
- Next.js provides several tools and features to make deployment easier, such as:
    - Automatic code splitting and optimized production builds.
    - Built-in support for server-side rendering and API routes.
    - Environment variables for storing sensitive information.
    - Real-time updates and automatic reloading in development mode.
- To deploy a Next.js application, you need to:
    - Create a production-ready build of the application.
    - Choose a hosting solution that fits your needs.
    - Upload the built files to the server or configure the hosting service.
    - Configure the server to serve the application using a web server, such as Node.js or Nginx.
    - Optionally, set up a custom domain name, SSL certificate, and other features.


## Videos
[ Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)
- Next 10 came out 2 years ago but offers many up improvements
  - automatic image optimization
  - images are not loaded until they are in the viewer
  - internationalization
  - Analytics
  - Commerce
  - `getStaticProps` and `getServerSideProps` not get fast refresh - automatic reloading of properties
  - importing CAS from Third Party React Components (like Tailwind CSS)
  - automatic resolving of `href`

## Bookmark and review

[Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-serving)

## Things I want to know more about
- I still have some questions about deployment. What about Docker? 