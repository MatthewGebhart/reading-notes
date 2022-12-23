# Class 05 - Linked Lists

## Reading

### Big O: Analysis of Algorithm Efficiency
[Source Credit](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
- Running Time (also known as time efficiency / complexity)
The amount of time a function needs to complete.
- Memory Space (also known as space efficiency / complexity)
The amount of memory resources a function uses to store data and instructions. 
- Key areas to analyze:
    - Input Size ("n" number of elements in an array) increase time and space
    - Units of Measurement 
        - Running time is (milliseconds, operations, basic operations)
        - Memory space is space needed to hold code for algorithm, space to hold input data, space to hold output data, and "working space" - creation of variables and reference points and stack space
    - Orders of Growth
        - constant complexity O(1) - always uses the same amount of time of space
        - Logarithmic complexity O(lgn) - sees a decrease in rate of complexity growth as n increases
        - Linear Complexity O(n) - size of our inputs will directly determine the space and time
    - Best Case, Worst Case, and Average Case
- 

### Linked Lists
[Source Credit](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
- a sequence of nodes that are connected/linked to each other. 
- each node references the next node
- can not use `foreach` or `for` loop. Depends on the `Next` value in each node. 
- `while()` us the best way to traverse because it allows us to check the NEXT
- while traversing `Current` variable will tell us where we are
- 


### What's a Linked List, Anyway?
[Source Credit Part 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
[Source Credit Part 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
- linear data structures - have an order and sequence
- have to be traversed in order
- The biggest differentiator between arrays and linked lists is the way that they use memory in our machines.
- arrays ned memory that is in one contiguous block (static), linked lists have have each node scattered in different places in memory (dynamic)
- each node has data and a next reference to where the next node is
- inserting a new node at the beginning of a ll is more efficient because it is O(1) instead of O(n) by inserting midway down
- "a linked list is usually efficient when it comes to adding and removing most elements, but can be very slow to search and find a single element."


## Things I want to know more about
- Still have some questions about Big O but I'm starting to kind of maybe perhaps think it is starting to make sense. (maybe)