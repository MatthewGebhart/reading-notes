# Class 42 - Pythonisms

## Reading

[Dunder Methods](https://dbader.org/blog/python-dunder-methods)
- "Dunder" stands for "Double Underscore" methods in Python.
- Dunder methods are special methods in Python that have double underscores in their names (e.g. __str__).
- These methods have a specific meaning in Python and are used to define the behavior of certain operations (e.g. + operator) when used with instances of a class.
- Examples of dunder methods include __init__ (constructor), __str__ (string representation), __len__ (length of an object), and __add__ (addition of two objects).
- Dunder methods allow you to create custom classes that behave like built-in data types in Python.
- Implementing dunder methods makes your classes more "Pythonic" and easier to work with for other developers.
- Overriding dunder methods can also improve the performance and functionality of your classes.


[Iterators](https://dbader.org/blog/python-iterators)
- An iterator is an object that implements the iterator protocol in Python.
- The iterator protocol consists of two methods: __iter__ and __next__.
- The __iter__ method returns the iterator object itself and the __next__ method returns the next value from the iterator.
- When the __next__ method raises the StopIteration exception, the iteration stops.
- Iterators allow you to iterate through a collection of items one by one, without having to load all of the items into memory at once.
- Iterators can be created from many built-in Python objects, including lists, dictionaries, and strings.
- You can also create your own custom iterators by implementing the iterator protocol.
- The iter and next functions can be used to create and access iterators in Python.
- The for loop can also be used to iterate through the items in an iterator.
- Generators are a powerful tool for creating iterators in Python and can simplify your code.


[Generators](https://dbader.org/blog/python-generators)
- Generators in Python are a way to create iterators.
- They allow you to generate values one at a time, rather than generating all of them at once.
- Generators use the "yield" keyword to generate values and pause execution of the function.
- Generators can be used to simplify functions that return lists, or to handle large amounts of data efficiently.
- The advantage of generators is that they can be more memory efficient than pre-generating a list, since they only generate values as they are needed.
- Generators can be created using generator functions or generator expressions.
- Generator functions are defined using the "def" keyword, with the "yield" keyword used to return values.
- Generator expressions are similar to list comprehensions but are enclosed in parentheses instead of square brackets, and return a generator instead of a list.
- Generators are often used in combination with the "next" function or for loops to retrieve the values.


## Videos
[What are Generators](https://realpython.com/lessons/what-are-python-generators/)


## Bookmark and review

[Decorators](https://realpython.com/primer-on-python-decorators/)

## Things I want to know more about
- Generators seem really cool. I'd love to see more examples of how we might use them in practice. 