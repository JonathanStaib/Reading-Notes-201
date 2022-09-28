# Class 10 Notes

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
