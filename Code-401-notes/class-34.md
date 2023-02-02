# Class 34 - API Deployment

## Reading

### Django Settings Best Practices
[Source Credit](https://djangostars.com/blog/configuring-django-settings-best-practices/)
- It's recommended to use environment variables to store sensitive information such as database credentials, secret keys, and others.
- Django Settings supports multiple configuration options, including using a single file, multiple files, and using environment variables.
- Use a .env file to store environment variables in development and use tools such as python-decouple to access these variables in your code.
- In production, use an appropriate method to set environment variables, such as using export in a Unix shell or using environment variable management tools.
- It's good practice to use a base settings file and extend it with environment-specific settings files.
- Use debug = False in production and make sure to properly configure logging and error handling to ensure maximum security.
- Finally, be mindful of the order of execution of your settings, as some settings may depend on others.
- 12 Factors is a collection of recommendations on how to build distributed web-apps that will be easy to deploy and scale in the Cloud. It was created by Heroku
    - Codebase
    - Dependencies
    - Config
    - Backing services
    - Build, release, run
    - Processes
    - Port binding
    - Concurrency
    - Disposability
    - Dev/prod parity
    - Logs
    - Admin processes
- The main rule is to store configuration in the environment to get a separation of config from code. 
- Use Django-environ to store .env variables (like API keys)

## Bookmark and review
- [White Noise](https://whitenoise.evans.io/en/stable/)
- [Cross-origin resource sharing (CORS)](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)

## Things I want to know more about