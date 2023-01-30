# Class 31 - Django REST Framework & Docker

## Reading

### Beginner’s Guide to Docker
[Source Credit](https://wsvincent.com/beginners-guide-to-docker/)
- Docker is a way to isolate and run entire applications
- The entire development environment is isolated: programming language, software packages, databases, and more.
- Docker is really just Linux containers which are a type of virtualization.
- Most computers rely on the same Linux operating system. Docker is a way to implement Linux Containers
- virtual environments can only isolate Python packages. They still rely on a global, system-level installation of Python
- we can’t run a production database or other services within virtual environments so compared to Docker containers they are far more limited.
- Images and containers are the two fundamental concepts to grasp when you start with Docker. 
- An image is a snapshot in time of what a project contains. 
- A container is a running instance of the image.
- Every image is made up of one or more image layers. The base layer is often a flavor of Linux, like alpine
- image layering exists for two main reasons. 
  - First, each image layer is immutable–unchanged–like a git commit.
  - second reason is performance. Docker caches the steps in a Dockerfile to speed up subsequent builds.
- Typically you want to put code that won’t change often at the top and code that will change at the end
- Important take-aways:
- Docker is a way to run Linux containers
- Containers are a lightweight alternative to Virtual Machines
- `Dockerfile` is a list of instructions for creating an image
- Images are made up of one or more layers
- Containers are a running instance of an image
- `docker-compose.yml` controls how to run the container
- Containers are stateless and ephemeral in nature. We can link the local filesystem via `volumes` but things become more complex with databases (which we didn’t cover here).

### Django for APIs - Library Website
[Source Credit](https://djangoforapis.com/library-website-and-api/)
- Django REST Framework works alongside the Django web framework to create web APIs
- We cannot build a web API with only Django Rest Framework. It always must be added to a project after Django itself has been installed and configured.
- differences between traditional Django and Django REST Framework:
  - Django creates websites containing webpages
  - Django REST Framework creates web APIs which are a collection of URL endpoints containing available HTTP verbs that return JSON
- The rest is a tutorial on setting up a django project and app ready to accept django REST APIs'  

## Bookmark and review

[Official Django REST Framework Tutorial - A Beginners Guide](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)

[REST, Hypermedia & HATEOAS](https://www.django-rest-framework.org/topics/rest-hypermedia-hateoas/)

[Serializers](https://www.django-rest-framework.org/api-guide/serializers/)

## Things I want to know more about
- I have lots of questions about Docker that I'm sure we will get to in class. suck as - How do you share a Docker container with another dev or across devices? 