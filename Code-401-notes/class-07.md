# Class 07 Notes

## Reading

### Python Scope
[Source Credit](https://realpython.com/python-scope-legb-rule/)
- focus on global and nonlocal keywords
- LEGB - Local, Enclosing, Global, and Built-in scopes
    - local - the code block or body of a function
    - enclosing (nonlocal) scope - special scope for nested functions. If local scope is in an inner or nested function, then enclosing scope is the outer function. 
    - Global - top-most/level. Visible from everywhere in your code
    - Built-in scope - names that are built into Python and created when you run a script
- best practices is not to modify global variables
- but if you want to, you can access global variables when in a narrower scope by using the `global` keyword (ex. global counter) this can also create global variables
- similarly the `nonlocal` keyword will allow you to access nonlocal variables from within an enclosed function. This can not create nonlocal variables however. 


## Videos

### Don’t be CONFUSED by BIG O notation anymore!
[Source Credit]()
- Video was Private. Trying to find an alternate source

## Bookmark and review
[Rolling Dice Examples](https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Program_Example_1_3)


## Things I want to know more about
- How common is it to need to use the global or nonlocal keywords to access higher scopes?
- still need to learn more about Bog O