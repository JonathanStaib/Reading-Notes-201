# Class 07 Notes

## Class 07 Reading Notes

### Domain Modeling

1. We need Domain Modeling because it allows us to make HTML in our JavaScript like object literals and constructs and allows us to apply functions into our HTML like our Cookie-Stand. We are able to implement Javascript and arrays into text. This would be unachievable with just HTML. There is a lot that it helps with but these examples were the first that came to mind.

### HTML Table Basics

1. Tables should not be used for page layouts because thye should only be used for tabular data not for creating a header row, a content row and a footer row.
2. 3 Semantic Elements used in a table are table, tr and td. Table makes the basic construct and lets your code know that you will be making a table (usually for data). Tr allows you to create rows within your table. td is a way to make lists within your table to add data needed.

### Introducing Constructors

1. You would use a construct when you have multiple object literals. Constructs are a function that allow you to array multiple objects and their data. The advantages to using these are that you can grab information from all of your objects in a single function like how we did in our charts. 
2. In an object "this" refers to whatever object you are inside so this.name will only be this for one object. This a Construct this can refer to all of the objects in the order of the array that the objects are placed in. You will need a for loop function inside of your construct for this to work but it is very handy.

### Object Prototypes Using a Constructor

<!-- common interview question -->
1. Prototypes are every function in JavaScript taht refers to an object has a prototype property. We use prototypes so that we don't have to create a seperate object for all of our methods. I used a prototype to create all of my functions for math within my table. Also, I created another to create my td's and tr's in order to render them under this function.

## Class 07 Lecture Notes

### Constructors

#### What are they?

- A special type of functions
- Instantiate object for us
- acts like a blueprint/'factory' for objects
- starts with the keyword function

#### Why we use them?

- keep our code dry
- helps us prevent bugs
- give us more unified/uniform objects

### Prototypes

- Inherits === prototype