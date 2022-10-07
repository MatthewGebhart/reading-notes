# Class 15 Reading Notes

### Reading

(Source credit: https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html )

- What is OAuth?
    - an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential
- Give an example of what using OAuth would look like.
    - loging into a website and it allows you to log in through another website's login. 
- How does OAuth work? What are the steps that it takes to authenticate the user?
    - Webite A connects to Website B on behalf of the user, B generates a unique one-time token and secret. A gives token and secret to client software. Client presents them to authorization provider (second site). User authenticates with site B, client approves transaction. user is given access token, user gives token to A. A gives token to B as proof of authentication. B lets A access on behalf of the user. 
- What is OpenID?
    - It is about authentication instead of authorization (like 0Auth). "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."

(Source credit: https://auth0.com/docs/get-started/authentication-and-authorization-flow
)
- What is the difference between authorization and authentication?
    - Authentication is the process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor.  
    - Authorization is the process of letting a subject access resources after a successful authentication
- What is Authorization Code Flow?
    - exchanges an Authorization Code for a token
- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
    - PKCE adds an extra code verifyer and code challenge before the authorization from Auth0
- What is Implicit Flow with Form Post?
    - it allows web app requests and obtain token through the front channel without the need for secrets. Used for simple sign-ins without token access for APIs
- What is Client Credentials Flow?
    - pass along their Client ID and Client Secret to authenticate themselves and get a token.(Machine to machine)
- What is Device Authorization Flow?
    - the device asks the user to go to a link on their computer or smartphone and authorize the device. (for input-constrained devices)
- What is Resource Owner Password Flow?
    - requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information. (For highly-trusted applications)


### Things I want to know more about

- Comparison of the different authentication methods and different scenarios for their use. 