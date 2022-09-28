# Class 10 Notes

## CLass 10 Reading Notes

### What Went Wrong? Troubleshooting JavaScript

1. The difference between syntax errors and logic errors is that syntax errors are misspells in the code that cause it to not work. Logic errors are errors where the syntax is correct but the code is not what it should be and it runs successfully but does not give the right results out of this code. Logic errors sound scary. :(
2. I have had many different syntax errors, usually just a missed closing curly brace or a missing semi-colon. I first check my code and see if the lint points out anything and if nothing I will then check the console on my live server. If still nothing then I will console log at different points and see where the problem is.
3. Bug fixing can be quite fun, it is kind of like a puzzle or a maze trying to find where and why the problem is occuring. I hope that in the long term I dont have many bugs to fix but I would say I can do it rather quickly and enjoying it can never be a bad thing.

### The JavaScript Debugger

1. The JavaScript Debugger tool is a good and easy way to find where your problems are and why your code may not be running as you intend for it to. You can make breakpoints so that your code will run up to a certain point and see if certain sections are working and wittle down where the problem is.
2. I just went over it above, You can make breakpoints so that your code will run up to a certain point and see if certain sections are working and wittle down where the problem is.
3. The call stack shows what code was used to get to a certain line that you are on.

## Class 10 Lecture Notes

### Ways to Debug

- console.logs
- repl
- terminal errors using git//github
- debugger tool!
  - breakpoints, debugger
- linter - reading linter errors
- control f - finding variables in code and making sure youre using correctly
- rubber duck, code reviewing talking about it
- using your classmates, TA, instructor

### Types of errors

- Syntax Errors
- logic errors
- undefined - reference error
- fatal error - git error
- type Error - NaN or run a method on a string when it can only run on a number
 String=Good/Number=noGood.toUpperCase()

### Replit Notes

//  ***ARRAY METHODS***

let months = ['Apr', 'June', 'July'];

//  ADD TO AN ARRAY

//  .push() adds to end of array

let pushReturn = months.push('Aug', 'Dec');

console.log(months);

// .unshift() adds to start of the array

months.unshift('Jan');
console.log(months);

//  REMOVE ELEMENT FROM ARRAY

//  .pop()  REMOVES THE VERY LAST ELEMENT FROM THE ARRAY

let poppedElem = months.pop();
// arr.push(months.shift()); to store shifted months into a new array
console.log(poppedElem);

//  .shift()  REMOVES THE FIRST ELEMENT FROM THE ARRAY

months.shift();
console.log(months);

// ADD or REMOVE from anywhere in my Array

//  .splice()
//  arg - what index to start at, # of elements we want to remove(if any), what to add(if any).

months.splice(4, 0, 'Sept', 'Oct');
console.log(months);

let splicedMonths = months.splice(1,2);
console.log(splicedMonths);

//  SLICE allows you to remove inbetween two index's

//  .includes() -  RETURN A BOOLEAN VALUE IF THE ARG YOU PASS IN IS IN THE ARRAY

let isItThere = months.includes('Oct');

console.log(isItThere);

//  SIDE NOTE FOR NEXT WEEK
//  STACK - first in last out
// push() then pop()
//  unshift() then shift()

//  QUEUE - first in first out
// [3,2,1]
//  unshift() then pop()
//  push() then shift()
