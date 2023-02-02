# Class 33 - Authentication & Production Server

## Reading

### JSON Web Tokens
[Source Credit](https://jwt.io/introduction/)
- JWT (JSON Web Token) is an open standard that defines a compact and self-contained way for securely transmitting information between parties.
- JWT consists of three parts: header, payload, and signature.
- Header specifies the type of token and the signing algorithm being used.
- Payload contains the claims, which are statements about an entity (typically, the user) and additional metadata.
- Signature is created by using the header and payload and a secret key, which verifies the authenticity of the token and provides integrity protection.
- JWT can be used for authentication, information exchange, and server-to-server communication.
- JWT has a number of advantages, including being stateless, scalable, and easy to use.
- The standard is widely supported by various technologies, including OAuth 2.0, OpenID Connect, and many others.

### DRF JWT Authentication
[Source Credit](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
- This article provides a tutorial on how to use JWT (JSON Web Token) authentication with Django Rest Framework.
- JWT authentication provides a way to securely transmit information between client and server.
- The tutorial covers the following steps:
    - Installing Django Rest Framework and PyJWT packages.
    - Creating a Django app to store user data and generate JWT tokens.
    - Configuring Django Rest Framework to use JWT authentication.
    - Implementing user registration and login endpoints to obtain JWT tokens.
    - Using JWT tokens for authentication in further API calls.
- The tutorial uses Python and Django to implement JWT authentication, but the concepts can be applied to other programming languages and frameworks as well.
- The article provides a good starting point for developers looking to implement JWT authentication in their Django projects.

### Django Runserver Is Not Your Production Server
[Source Credit](https://vsupalov.com/django-runserver-in-production/)
- Running the Django development server in production is not recommended as it's not designed for production use and lacks security features.
- A better approach is to use a production-ready web server like Gunicorn, uWSGI, or mod_wsgi.
- These web servers provide security, performance, and scaling features necessary for production environments.
- When deploying a Django application, it's important to consider various factors such as security, performance, reliability, and scalability.
- A common production setup involves deploying the Django application behind a reverse proxy server, such as Nginx or Apache, which serves as an intermediary between the client and the application server.
- The reverse proxy server can handle tasks such as SSL termination, static file serving, and load balancing.
- Proper configuration of the web server and the reverse proxy server is crucial for a secure and efficient deployment.
- Regular security and performance monitoring should also be carried out to ensure that the application remains secure and efficient.


## Videos
[JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

## Bookmark and review

[Gunicorn](https://gunicorn.org/)
[Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)

## Things I want to know more about

- How does JWT compare to other authentication methods like Auth0?