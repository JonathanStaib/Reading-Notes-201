# Class 05 Notes

[Resource Link](https://developer.mozilla.org/)

## Class 05 Reading Notes

### HTML Media

1. When you are trying to go through any website with multiple pages seeing the alt in navigation like home instead of a whole link is much easier to understand for the average user.
2. You can add an alt tag to your images to provide additional information to the viewer and it also adds a way to people to access your page/image via the search bar.
3. Figure and fig caption would be useful for screen readers so they dont need to see 30 images and captions then which caption would go with which image. Helps screen readers and the visually impared.
4. Gif images are good for simple animations and images while SVG images are ideal for user interface elements, icons and diagrams that must be accurate at different sizes.
5. For screenshots, you should use Lossless WebP or PNG, sometimes JPEG. This is because they will give the best quality and if there is text in the image it can easily become fuzzy and unclear if under lossy compression.

### Learn CSS

1. Foreground Color change text or text decoration while background color will just change the texts background color.
2. First you could add some background color, maybe border with a style and color, you could add the text color and any text decoration + color, you can add images for some color but that would be HTML then CSS not sure if thats acceptable. There are tons of options to alter the color.
3. It is best to stick to generic names for fonts such as serif, sans-serif, monospace. There are many basic alterations of these and you can also use google fonts to find custom version. Be careful and check was it accessible on each operating system, use ones that are vastly available. Be careful with cursive and fantasy because they are unpredictable.
4. Font-Size will change the size of the text in that attribute being selected, or declaration, can't think of the word at the moment. Font-weight will set how bold that text will be. Font-style can set the text to italic or back to normal from italic
5. 2 ways you could add spacing around characters in a h1 element would be margin and padding. Margin could select any direction you would like the give the text space in and how much. Padding would allow you to give padding around the whole text or text box. You could also use border I think.

## Class 05 Lecture Notes

### CSS

- Add an Alt and Title to imgs
- can also add a figcaption for words under image
- "* can be used as a global selector in css
- give width and use percentage so that it scales always at that size no matter screen size
- give width and margin auto and it will center always
- inherit tells property to take from parent!!
- max content will make it so that itll always be size of maximum content
- CSSdontstack com to find usable fonts on windows/mac
- em or percentages for font size
- vs after number in font size would take up that percentage of page
- google fonts will help you see different fonts before using.

### Branching

- to create a branch you will use command: git checkout -b nameOfYourBranch, will create a new branch and move you to it.
- Then you will ACP the git push will be: git push origin nameOfYourBranch
- PULL REQUEST - ON GITHUB: MERGE INTO MAIN IF NO CONFLICTS
- TERMINAL: git checkout main
- TERMINAL: git pull origin main