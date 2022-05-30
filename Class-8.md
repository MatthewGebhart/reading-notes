# Class 7 Reading Notes

## Expressions and operators

### Assignment operators

- assignment operator assigns a value to its left operand based on the value of its right operand.
- the simple operator is =, assigns value of right operand to its left operand `x = f()`
- compound assignment operators are shorthand for certain operations
  - assignment `x = f()`
  - addition assignment `x = += f()`
  - subtraction assignment `x -+ f()`
  - multiplication assignment `x *= f()`
  - division assignment `x /= f()`
- assigning to properties
  - if a variable refers to an object, then the left side of an assignment expression may make assignments to properties of that variable.
- Destructuring
  - for more complex assignments
  - makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals (uuuummmm... what...? lol)
- Evaluation and nesting
  - In general, assignments are used within a variable declaration (i.e., with const, let, or var) or as standalone statements).
  - assignment expressions like `x = f()` evaluate into a result value. This value is usually not used, it can then be used by another expression
  - chaining assignments or nesting assignments in other expressions can result in surprising behavior.
- Avoid assignment chains
  - chaining assignments or nesting assignments in other expressions can result in surprising behavior
  - particularly putting a variable chain in a `const`,`let`, or `var` statement often does *not* work

### Comparison operators

- A comparison operator compares its operands and returns a logical value based on whether the comparison is true
- The operands can be numerical, string, logical, or object values
- In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison
  - *This behavior generally results in comparing the operands numerically*
  - The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons and do not attempt to convert the operands to compatible types
- Common comparison operators
  - equal (==)  - returns  `true` if the operands are equal
  - not equal (!==) - returns true if the operands are not equal
  - strict equal - (===)  - returns true if the operands are equal and of the same type. 
  - strict not equal - (!==) returns true if the operands are of the same type but not equal, *or are of different type*
  - greater than (>) - returns true if the left operand is greater than the right operand
  - greater than or equal (>=)  - returns true if the left operand is greater than or equal to the right operand
  - less than (<) - returns true if the left operand is less than the right operand
  - less than or equal (<=) - returns true if the left operand is less than or equal to the right operand

## Loops and iteration

- Loops offer a quick and easy way to do something repeatedly.
- You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another
  - `for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');`
- There are many different kinds of loops but they all do basically the same thing - repeat an action some number of times (that number could be zero)
- The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.
- Statements for loops in JavaScript
  - for statement
  - do...while statement
  - while statement
  - labeled statement
  - break statement
  - continue statement
  - for...in statement
  - for...of statement 
- `for` statement
  - a for loop repeats until a specified condition evaluates to false. Similar to the Java and C `for` loop
- `do..while` statement
  - repeats until a specified condition evaluates to false
  - `do
  statement
while (condition);`
- `while` statement
  - executes its statements as long as a specified condition evaluates to true
- avoid infinite loops - make sure some condition in the loops eventually becomes false
- `labeled` statement
  - A label provides a statement with an identifier that lets you refer to it elsewhere in your program.
  -  you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.
- `break` statement
  - Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.
  - When you use break without a label, it terminates the innermost enclosing while, do-while, for, or switch immediately and transfers control to the following statement.
  - When you use break with a label, it terminates the specified labeled statement.
- `continue` statements
  - The continue statement can be used to restart a while, do-while, for, or label statement.
- `for...in` statement
  - The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements.
- ` for...of` statement
- 