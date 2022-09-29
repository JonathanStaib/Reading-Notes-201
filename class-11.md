# Class 11 Notes

## Class 11 Reading Notes

### Video and Audio Content

1. The differences in the evolution of video and audio on the web has they have changed drastically in terms of security and accessibility from Flash and Silverlight to video and audio elements
2. In a video element the src contains the path to the video you want embeded. the control element is used to control the video with things such as play pause and a volume level adjustment.
3. The fallback content is a paragraph inside the video tags, this is important for users using older browsers taht dont support the video element, You can at least provide some text in which they will know what it was and you can add a link to the direct video file for them as well.
4. There once was two brothers Audio Element and Video Element. They both wanted to be stars but could not work together! Audio Element was a great singer and had a great voice for media but he was never able to get a way to display himself. Video Element was a great gfx designer and was trying to make it onto the big screen with the videos he was making. After many years the brothers were never able to achieve success until they paired together and put themselves together in a brand called Metadata! Now they are living their dreams. I am not an Author.

### A Complete Guide To Grid

1. The difference between Grid and FlexBox is that grid is a two-dimensional layout system that is grid like, while flexbox is a one-dimensional CSS styling type. They do work very well together though!
2. Grid container is all of the content you would like to be inside of your grid and be able to style as pleased. Grid item would be your items within your grid such as pictures that you can assign the column and row you would like it to be placed. Grid lines are the lines that seperate each column and row and you can write 2,3 for your grid items to place it in the unit you would like it to be in.

### Responsive Images

1. Other than changing the size of the image with the browser responsive images also help improve performance across different devices and also give access to other featrues.
2. srcset is used to add image sources foe the user agent to use. Sizes can be used to set the size of an image.
3. srcset is better than using CSS or JavaScript when using responsive images because without srcset, you are unable to use the sizes attribute because it will have no effect.

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