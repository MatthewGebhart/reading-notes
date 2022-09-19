# Class 7 Reading Notes

## Things I want to know more about

## Domain Modeling

- Domain modeling is the process of creating a conceptual model in code for a specific problem.
- A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.
- An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
- Explain why we need domain modeling.
  - verify and validate the understanding of a specific problem among various stakeholders. 
  - As a communication tool, it defines vocabulary that can be uses in both the technical and business teams
- 

## HTML Table Basics

- A table is a structured set of data made up of rows and columns (tabular data)
- allows you to quickly and easily look up values that indicate some kind of connection between different types of data, for example a person and their age
- for tables to be effective on the web, you need to provide some styling information with CSS, as well as good solid structure with HTML
- Why should tables not be used for page layouts?
  - Layout tables reduce accessibility for visually impaired users:
  - Tables produce tag soup
  - Tables are not automatically responsive (tables are sized according to their content by default)
- List and describe 3 different semantic HTML elements used in an HTML `<table>`.
  - `<tr>`, `<td>`, `<th>`

## Introducing Constructors

- What is a constructor and what are some advantages to using it?
  - A constructor is just a function called using the new keyword
  - allows us to create more than one object and change properties of the object easily without changing each object
- When you call a constructor, it will:
  - create a new object
  - bind this to the new object, so you can refer to this in your constructor code
  - run the code in the constructor
  - return the new object.
- Constructors, by convention, start with a capital letter and are named for the type of object they create
  - `function Person(name) {`
- To call Person() as a constructor, we use `new`
- How does the term `this` differ when used in an object literal versus when used in a constructor?
  - I think they work the same - but in a constructor it binds `this` to the new object being made

## Object Prototypes and Using A Constructor

- every function in JavaScript has a prototype property that references an object
- prototype is just a property that every function in JavaScript has and, it allows us to share methods across all instances of a function
- Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question
  - Come back to this...