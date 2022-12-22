# Class 04 - Classes and Pytest

## Reading

### Classes and Objects
[Source Credit](https://www.learnpython.org/en/Classes_and_Objects)
- Objects are an encapsulation of variables and functions into a single entity
- Objects get their variables and functions from classes. Classes are essentially a template to create your objects.
- variables are accessed with dot notation (myobject.variable)
- same for Class functions (myobject.function)


### Thinking Recursively
[Source Credit](https://realpython.com/python-thinking-recursively/)
- Splits the problem down into smaller pieces using the same function repeatedly inside itself
- "A recursive function is a function defined in terms of itself via self-referential expressions."
- maintain state by keeping global scope, declare variables outside of the function first


### Pytest Fixtures and Coverage
[Source Credit](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)
- fixtures provide a test with the objects they need to run without declaring global variables
- coverage is an option of pytest that can show you how much coverage your tests are providing, if there are different input examples that you aren't testing for. 
- `pytest --cov=(your program .)` 
- `coverage html` will create an html fils with your testing coverage. neat!. 

## Bookmark and review
[Pytest Fixtures]()


## Things I want to know more about
- Are there any ways that Classes in Python are different than JavaScript?