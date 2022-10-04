# Class 12 Reading Notes - CRUD

## Reading

(Source credit: https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

- In your own words, describe what each group of status code represents:
    - 100’s = informational codes - tell the client the header part of the request has been received
    - 200’s = success codes - tell the client that its request was accepted
    - 300’s = redirection codes - tell the client that the requested resource isn't available at the location anymore
    - 400’s = client error codes - invalid requests a client sent to a server.
    - 500’s = server error codes - often indicate problems with overwhelmed or unreachable servers.
- What is a status code 202? accepted. Often used for asynchronous processing request
- What is a status code 308? Permanent Redirect. Tells client to use another URL to access the resource.
- What code would you use if an update didn’t return data to a client? 
    - 204 - No Content
- What code would you use if a resource used to exist but no longer does?
    - 204 - No Content
- What is the ‘Forbidden’ status code? 403 - Forbidden


## Videos

(Source credit: https://www.youtube.com/watch?v=fgTGADljAeg)

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
    - so we can change the location of our server for deployment
- What is middleware?
    - code that is used when a server gets a request but before it is passed to routes
- What does app.use(express.json()) do?
    - lets our server accept JSON
- What does the /:id mean in a route?
    - it is a parameter that we can access with req.params
- What is the difference between PUT and PATCH?
    - PATCH only passes what the user provides. PUT updates all the information
- How do you make a default value in a schema?
    - default: (ex. default: Date.now)
- What does a 500 error status code mean?
    - there is an error on the server
- What is the difference between a status 200 and a status 201?
    - 201 means successfully created an object which is more specific than 200 which is a generic success message


## Things I want to know more about

- What is the `error` in catch (error) and the `error.response`
