# Class 6 Notes

## Class 6 Help / Self Help

- ask for help on lab05a, my pictures not working on previous page, ask about career 2 projects
- math js
- look for random interger between two values, inclusive

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
