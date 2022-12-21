# Class 03 - FileIO & Exceptions

## Reading

### Read & Write Files in Python
[Source Credit](https://realpython.com/read-write-files-python/)
- file = open('filename.txt')
- close (one way) file.close()
- close (another way) with open('filename.txt', 'r') as reader:
- .write(string)	This writes the string to the file.
- .writelines(seq)	This writes the sequence to the file.
- __file__ is the pathname of the file from where it was loaded (relative)
- 


### Exceptions in Python
[Source Credit](https://realpython.com/python-exceptions/)
- A Python program terminates when it encounters a error either syntax or an exception
- Syntax - parser detects an incorrect statement
- exception error. This type of error occurs whenever syntactically correct Python code results in an error.
- can use raise to throw an exception if a condition occurs (like error?)
- assertionError can check for conditions midway through and throw an exception
- `try and except` block is used to handle exceptions
- `else` Clause only run in absence of exceptions
- `finally` allows us to always do something to clean up after executing code

## Videos

### Read and Write Files in Python - Companion Video
[Source Credit](https://realpython.com/courses/reading-and-writing-files-python/)
- file = open ("text_file.txt")
- file.close()
- DON'T FORGET TO CLOSE FILE
- Better is to use auto closing command
- `with open("text_file.txt") as file:`
    "process data and stuff here"
    "then file is automatically closed"


## Bookmark and review

[Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)

## Things I want to know more about
- Why do we want to edit text files in Python? It doesn't not seem like Python is the tool for this job. 
- are exceptions similar to error handling in JS?