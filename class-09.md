# Class 09 Notes

## Class 09 Reading Notes

### HTML Forms

1. Web Forms are important because They are a good way  of interaction between a suer and the website or app. They can be used to store information based on user input and then gather data based on whos coming to your page. This can be used for advertising and marketing teams. They can use this data to see who their audience is, this could be used for every team in the company actually.
2. When designing a form, some key points to keep in mind for the user are the length of the page, you don't want to frustrate them with an overwhelming form, keep it simple. Before you coee your form think about it and what you want to ask your users. 
3. 5 form elements are form, label, input, textarea, and button. The importance of these are form is to create a form, label is to give a caption or what this line will say, input is to create what they will be doing with this label such as a button or a checkbox or a date or email, etc. , textarea will provide them with a text box in whcih they can input their text, button would be a way to submit the data that the user has entered.

### Learn JS

1. If I had to explain events to a non-techincal friend I would say if you click a button or something of the sort and it creates an action or some type of "event" to do something that is an event. Like youtube with a play/pause button if they are still confused.
2. The two minimum arguments with an addEventListener are the name of the event and a function to handle this said event.
3. Event objects are used to automatically pass additional information or features to your event handlers. Your target is useful within the event beacuse it references which element the event should occur on.
4. The difference between the bubbling phase and the capturing phase is that they are complete opposites. The capturing phase once the click event occurs it moves on to the next element in the html element and runs until it reaches the parent that the element was clicked. In bubbling it does the same with starting when the click event occurs but it then starts at the next immediate element and runs until it reaches the html element.

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