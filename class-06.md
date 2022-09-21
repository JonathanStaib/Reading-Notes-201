# Class 6 Notes

## Class 6 Reading Notes

### Javascript object basics

1. They are Convenient and powerful way to group data and functions. You put information inside of this object and each piece of information has a name, in which you can call functions using them, a function is a way to make this information do somethinf.
2. An advantage to making an object literal is to declare information inside of a declaration, it allows you to call all of this information with just a single call, it also allows you to use the this.
3. Arrays and objects are similar in which they can both store different kinds of information. The difference is that you can select them by using a name instead of using an index number and creating a for loop.
4. You would use bracket notation over dot notation if the object property name is defined at runtime, if this is the case you will get the name by putting the variable inside brackets.
5. in the example below "this" refers to everything inside the object. So here you are calling this.name so it is the name variable inside of the object dog. It just makes things easier especially if you have a long name as the object variable. It can also allow you to copy paste this code when making another object both objects will use this.name but they will have different names, usually.

### Intro to DOM

1. DOM is Document Object Model. It is the data rep. of the objects that make the structure and content of a document on the web.
2. DOM is where html and css come together in the browser for javascript to read it as one big object. It allows you to write HTML and CSS within your javascript file.
<!-- ## Class 6 Help / Self Help

- ask for help on lab05a, my pictures not working on previous page, ask about career 2 projects
- math js
- look for random interger between two values, inclusive -->

## Class 6 Lecture Notes

### Objects

#### What are they?

- Date type/ Data structure
- Convenient and powerful way to group data and functions
- Comma seperated key/value pairs
- Functions that are stored in objects are reffered to as methods

```javascript

// Array
let myArr = ['Jonathan', 20, true, 'Student'];

let Jonathan = {
  name: 'Jonathan',
  age: 20,
  isRemote: true,
  title: 'Student'
};
```

### THIS

- THIS IS GOING TO REFER TO THE OBJECT YOU ARE IN
- THIS IS A DYNAMIC TERM

### DOM Manipulation

- 'THE DOM' = Document Object Model
- where html and css come together in the browser for javascript reads it as one big object
- console.dir(document) to see the DOM tree
- document.body.innerHTML || document.html.innerHTML = 'something'; to override and make destroy google!

#### Step for DOM manipulation in JS

```javascript

// JS needs a window into your HTML or into the DOM
// STEP !, NEEDS TO HAVE THIS WINDOW
let section = document.getElementByID('my-section');

//  STEP 2 - Create Elements // h2Element = <h2></h2>
const h2Element = document.createElement('h2');

// STEP 3 - give context if necessary
h2Element.textContent = 'Hey! I\'m an h2!'
// <h2>Hey I'm and h2!</h2>

//  STEP 4 - add it top the DOM
// parentElement.appendChild(Child)
section.appendChild(h2Element);
```
