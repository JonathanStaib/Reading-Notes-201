# Class 09 Notes

## Class 09 Reading Notes

### Learn CSS - FlexBox

1. One-Dimensional Content is a bunch of items that have different sizes and other properties and making the best layout for that group of items. It makes it so that instead of setting rigid dimensions for the web it will instead provide felx boundaries to show how the content would display.
2. The difference between the main axis and the cross axis is that the main axis runs along the row horizontally and the corss axis runs along the column veritcally.
3. There are some things such as row-reverse and column-reverse that the reordering will only change visually but not logically. This could negatively impact accssibilty.

### CSS Layout - FlexBox

1. Some advantages to using Flexbox over float are that its more convenient and flexible. You can veritcally center a block of content inside its parent. You can make all children of a container take up equal space regardless of width or height. It can make all colums the same height no matter their content.
2. FlexBox can save us a lot of time rather than sitting their for hours trying to calculate exact measurements for our web pages. It will make styling much more effecient and reliable. This is how I can see it effecting our long term goals. It will save us a lot of time and help our pages look cleaner and both of those = money.

## Class 09 Lecture Notes

### Events

#### Browser Event Types

- click
- submit (when a form button is clicked)
- hover
- mouseover
- page load (prompt)

## JavaScript - Code: Event Listener

- Code will be triggered when the event is fired/raised
- targets some HTML
`let mycontainer.document.getEleemntbyID('my-container');`

- Specify the type of event to listen to
- Specify what function is called

`myContainer.addEventListener('click', handleClick);`

## JS - Code: Event Handler - CAllback Function

`function handleClick(){
 // do some stuff
}`

<!-- HOW TO MAKE A FORM IN HTML and some JS -->

<!-- form id="my-form">
    <fieldset>
      <legend>FieldSet Context</legend>
      < Input and labels: 2 options
       Option 1: elements are siblings 
      <label for="firstnName">Name:</label>
      <input id="firstName" type="text" name="firstName">
      < event.target.firstName.value === whatever the user inputs

       Option 2: next label and input field 
      <label>age
        <input type="number" name="age" required>
        <!-- event.target.age.value === whatever the user inputs
      </label>

      <label for="Password">Password></label>
      <input id="password" type="password" name="password">

      <select name="reality-tv" id="reality-tv">
        <option value="default">Pick a Show</option>
        <option value="bh">Beverly Hills</option>
        <option value="bachelor">Bachelor</option>
        <option value="first-sight">Married At First Site</option>
      </select>
      event.target.reality-tv.value         
      can make it so default is not acceptable

      <!-- 
        function handleSubmit(event) {
          event.preventDefault()

          let name = event.target.firstName.value;
          console.log(name);

          let age = +event.target.age.value;
          console.log(age);
        }
        
        let myForm = document.getElementById("my-form");
        myForm.addEventListener('submit', handleSubmit);

      
    </fieldset>
    <button type="submit">submit</button>
  </form> -->