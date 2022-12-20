# Class 02 - Testing and Modules

## Reading

### In Tests We Trust - TDD with Python
(Source: https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)
- Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.
- Test-Driven Development is a strategy to think (and write!) tests first.
- test name needs to be descriptive about it and to say what is expected and what we are testing, long test function names.
- separate the tests folder from production code (the implementation)
- AAA: Arrange, Act and Asser
    - Arrange: you need to organize the data needed to execute that piece of code (input);
    - Act: here you will execute the code being tested (exercise the behavior);
    - Assert: after executing the code, you will check if the result (output) is the same as you were expecting.
- suggest the lib `pytest`


### If name equals main
(Source:https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)
- if running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”
- If this file is being imported from another module, __name__ will be set to the module’s name
- Python files can act as either reusable modules, or as standalone programs
- 

### Introduction to Recursion
(Source: https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)
- the process in which a function calls itself directly or indirectly
- essential to provide a case to terminate the recursion process
- Properties of Recursion:
    - Performing the same operations multiple times with different inputs.
    - In every step, we try smaller inputs to make the problem smaller.
    - Base condition is needed to stop the recursion otherwise infinite loop will occur.

## Videos

### Recursion
(Source: https://www.youtube.com/watch?v=Mv9NEXX1VHc)
- factorials are only defined for positive integers

## Things I want to know more about

- Recursion makes my head hurt, I need a different explanation preferably with pretty pictures and colors.

