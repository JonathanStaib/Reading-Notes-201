# Class 11 Notes

## Class 11 Lecture Notes

### CSS Grid

- display:grid;
- grid-template-colums: amount of px for 3 columns or 4 etc.; set how many columns you want. If nothing then it will be 12x12.
- Auto will grow and shrink with size of page
- 1fr, 1fr, 1fr will give fraction of 90% for each. 2fr for bigger etc.
- .grid-container to declare
- grid-template-rows: 200px 500px, first row will be 200 second will be 500
- row-gap: 20px;
- column-gap: 20px;
- gap: 20px; for shortcut
-grid-auto-rows: minmax(200px, auto);

.grid-item1{
  grid-column: 1/4;   1/-1 for whole page length
}

.grid-item2{
  <!-- grid-area: sidebar -->
  grid-row: 2/6
}

.grid-item3{
  <!-- grid-area: content -->
  grid-column: 2/-1;
  grid:row 2/5;
}
.grid-item4{
  grid-area:article
}

#### Trick for using it for different users (mobile, tablet, pc)

- repeat(3, 1fr), repeat(2, 1fr 2fr)
- @media(max-width: 960px){
  main{
    width: blank;
  }
}

## lab 11

### what do we need?

#### Globals - Goat Objects

- Voting Rounds 15 times
- storage - goat array,
- DOM Windows - render images
- DOM Window to render our results list

#### Constructor

- Properties
  - Goat Imgs
  - Views
  - Clicks
  - Names

#### Exectuable Code

- Method to calculate views and clicks
- 2 random images to display
  - make sure they're uinque
- render function to get images on the page (DOM)
- eventListeners
  - click - count votes and rerender new images
  - click - results button to render a list of all of our calculated data

### Additional CSS

gradient linear or linear gradient to make a rainbow border!!!
also an @glowing to make it seem glowing