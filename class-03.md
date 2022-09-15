# Reading Notes For Class 3

## Learn HTML/Ordered and Unordered lists

- 1. Unoredered Lists should be used for grouping items with no numerical ordering and no meaningless order.
- 2. In CSS you can use circle, disc, square. If there is no CSS applied then the the user agent will select a bullet type based on the nesting level of list.
- 3. You should use unordered lists when there is no order to the things you are grouping. You should use a ordered list when you want them to be in order (ex: directions on how to make something)
- 4. Ways taht you can change the numbers on an ordered list are roman numerals using type "i" after ol, you can also use the start command to start you list at a certain number such as... start "4"

## Learn CSS

- 1. Padding sits around content as white space so all of your content wont be sitting on top of eachother. Gives your content room to breathe. The margin is the outermsot layer that wraps the text padding and all content. You can use margin-color on your body to change the color of the margin of your page
- 2. The four elements reffering to the box model would be inline-size, block-size, or width and height attributes. Any padding and border will be added to these to get the total size of the box.

## JavaScript

- 1. Arrays can store many kinds of data types including strings, numbers, objects etc.
- 2. No because I dont think there should be two [[]]
- 3. 5 different shorthand operators are the addition assignment written as x += f(), this means x = x + f(). Another is subraction written as x -= f(), this means x = x + f(). Another is multiplication written as x *= f(), meaning x = x * f(). Another one is division written as x /= f(). meaning x = x / f(). Lastly, which there are more but not listed here, we have remainder written as x%= f() meaning x = x % f(). All of these are pretty self explanatory.
- 4. The result would be 10dog because you cant add a boolean and it just takes the number 10 and adds the string dog after it. such as 2 + '2' would be 22.
- 5. when doing algebra
- 6. An exmaple of when a loop is useful in Javascript would be entering a password.

# Class 03 Lecture Noets

## Arrays

- Data Type // Data Structure **special type of object**
- Array is a collection or a list of elements
  - can be mixed -  I can store strings, booleans, numbers, other arrays

 <!-- ```js
// anatomy of an array
               0      1    2      3 -->
let array = ['hello', 4, true, [1,2,3]]; 
let myString = array[0]; - string will have the value of hello


- dont have to determine the size of array, you can but dont need to
- every element has a position in the array
  - Zero based index

- Arrays have built in methods!
 -`.push()` - alows us to add elements to our array at the end
 -`.pop()` - remove the last element in the array

- Array property
 -`.length` - this is going to tell how many elements live in the array

## Loops

### For

- Great for looping or iterating and doing something for a certain number of times
- Great for looping through arrays! (arrays have a length)

```javascript
// anatomy of an for loop
for(starting value; condition; increment){
   do something until that condition is no longer true;
}
```

### While

- Doing something until a condition is no longer true
- Beware of infinite loops!

```javascript
// anatomy of a while loop
while(condition){
 run until that condition is no longer true
}
```

