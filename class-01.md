# Reading-Notes-201-class1

## Getting Started

- Text editors are a big help
- Plan first before making website, sketch it out called a wireframe. Keep it simple
- HTML is HyperText Markup Language, its the structure of the page
- CSS is Cascading Style Sheets, its the design of the website
- JavaScript is the interactive language of the website
- After the website is finsihed you need to upload it, ACP to github. Not sure how to make it a normal website with a normal link yet though, can use web hosting to rent file space on a hosting companies server. Domain name is the "normal link" I refered to before.

## How The Web Works

- Clients and Servers, Client Requests and Server Responds. Clients are the people using the web or the internet. The server are the computers storing the webpages, siters and or apps. When the client requests, a copy of the webpage is downloaded from server and onto the clients computer/phone/etc and displayed to them.
- TCP is Transmission Control Protocol
- IP is Internet Protocol
- DNS is Domain Name System, address book for websites. When you type in web address it finds webs IP and brings you to it.
- HTTP is HyperText Transfer Protocol, it defines a language for clients and server to communicate. This is the language you use when making a pruchase.
- [This website explains further on how all these properties above work in detail](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

## Oops I was just taking notes

- 1. The clients request, the server returns. As the client requests, the server makes a copy of the webpage downloaded from the server and displays this information to the client. The client then can utilize this webpage.
- 2. The browser parses the HTML first, then asks the server for any CSS files found from 'link' elements, then it asks for any javascript files found thought 'script' elements and then parses the CSS and JavaScript. Then the browser builds the in memory DOM tree with that parsed HTML, generates an in memory CSSOM structure with that parsed CSS, and gathers and uses the parsed javascript. When the browser creates the DOM tree and applies the styles form CSSOM tree and uses the JavaSCript then it is put onto the clients screen and it becomes visible and interactive.
- 3. Use the Google license Filter to remove any copyrighted photos and look for the image you would like. When you find it get an enlarged view of it, save image as and copy the image address for possible later use
- 4. To create a string in JavaScript use single quotes and to create a number just put the number
- 5. A variable in JavaScript declares something to be something like x = 2, this declares that x will always be 2. These are important to hold a value and store data

## Intro to HTML

- 1. An attribute in HTMl is a way to adjust the display of your HTML. It would contain the element then a space then the attribute name followed by =, 'a' can enclose a hyperlink in a text etc.
- 2. The anatomy of an HTML element is the opening tag the content then the closing tag, unless an img or something or the sort.
- 3. Both 'artcle' and 'section' are content subsections of the 'main'. The difference between the two is that section is more for grouping together one part if the page showing one functionality.
- 4. A Typical website will include the doctype, a head with a title, a header with a nav and header, a main with articles, p's, images, etc. and a footer. Much more but this is just the base.
- 5. Meta will bring you to a website in your selected language of your browser/computer. This is just a guess but maybe there is a way in meta that you can add keywords to the search engine to bring people looking for a specific word or phrase to your article? Yes, it can. Just found out.
- 6. Meta tag can be used to specify a lot of data, the language, it can also show the author and a description of the article.

## Miscellaneous

- 1. The first things you need to do before making a website is planning the website. Think of how you want it structured the layout maybe a few colors, keep it simple ( a wireframe).Some ideas you can have in mind are what do you need to accomplish, how will this site help you reach your goals and what needs to be done to reach them. Also, maybe the audience your'e trying to bring in to your site.

- 2. I feel the most important question to ask yourself when making a website is "What exactly do I want to accomplish?"

## Semantics

- 1. You should use a H1 element over a span elemnt in your top level heading because it would lose semantic value even if it may look like a top level heading.
- 2. Important reasons to use semantics are that search engines use their contents as keywords for clients browsing and boosting ratings. It helps visually impaired users navigate your site. Finding meaningful code is easier than searching your lots of complicated excessive code. 

## What is Javascript?

- 1. Things that require JavaScript in the browser are User interactivity and the Console for developers.
- 2. You can add Javascript to an HTML document via internal javascript by putting it in the code directly or external javascript where you do the javascript in a seperate file and just link the file into your html.