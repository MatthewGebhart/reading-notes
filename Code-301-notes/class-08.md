# Class 8 notes - APIs

## API DEsign Best Practices

(Source Credit: https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

- What does REST stand for?
  - Representational State Transfer
- REST APIs are designed around a ____. RESOURCE
- What is an identifier of a resource? Give an example.
  - a URI that uniquely identifies the resources 
  - for example: `https://adventure-works.com/orders/1`
- What are the most common HTTP verbs?
  - GET, POST, PUT, PATCH, and DELETE.
- What should the URIs be based on?
  - nouns (the resource) and not on verbs (the operations)
- Give an example of a good URI.
  - `https://adventure-works.com/orders`
- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - expose a large number of small resources. It's a bad thing because it may require a client to sent multiple requests for find all of the data it needs
- What status code does a successful GET request return? 200(OK)
- What status code does an unsuccessful GET request return? 404 (Not Found)
- What status code does a successful POST request return? 201 (Created)
- What status code does a successful DELETE request return? 204 (No Content)


## Things i want to know more about
  - Are the HTML verbs GET, POST, PUT, PATCH, and DELETE implemented differently depending on the language they are being used in? For example in our lab we used axios.get(). 