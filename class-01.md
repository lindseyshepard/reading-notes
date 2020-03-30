[Return Home](https://lindseyshepard.github.io/reading-notes/)

Introduction (pp.2-11)
### HTML Chapter 1: “Structure” (pp.12-39)
- HTML uses elements to describe the structure of pages
- elements are contained in tags
> <p>I am a paragraph tag</p>
- attributes provide additional info about the contents of an elements page. They appear on the opening tag of an element and are made up of two parts. a **name** and a **value** seperated by equal signs
- tags ...often referred to as elements. 

### HTML Chapter 8: “Extra Markup” (p.176-199)
![ESCAPE Characteristics](https://cheatography.com/storage/thumb/davechild_html-character-entities.600.jpg) 

*If the image displayed correctly it will be a list of escape characteristics that are used in HTML*

Extra Markup Summary
- DOCTYPES tell the browser which version of HTML you are using
- You can add comments to your code between <!-- and --> (and) markers.
- The ID and class attributes allow you to identify particular elements
- the div and span elements allow you to group block-level and inline elements together.
- iframes cut windows into your web pages through which other pages can be displayed
- the meta tag allows you to supply all kinds of info about your web page
- Escape characters are used to include special characters in your pages such as < , > , and the c with a circle

### HTML Chapter 17: “HTML5 Layout” (pp.428-451)

*This is a great example of what an HTML page looks like behind the scenes.* 
The elements of this html page will you figure out the purpose of each part of the webpage. The new elements will make the code easier to read instead of using multiple div tags. Pages that are not HTML5 need to be told which elements are block elements. To help browsers figure these things out a lot of extra javascript is needed and it creates for a more confusing web design.

### HTML Chapter 18: “Process & Design” (pp.452-475)

*Straight to the point*
Process and design matters. It is the blue print to what you are creating and why. This could be deisnged with Flow charts, wire frames or site maps. Starting with a site map can help you lay out the web site and how you want people to navigate through your pages. The wireframe will break that down even further. A wireframe will show the hierarchy of information that will be displayed on the page. You get your informationour by using the design on the web page and this is done with a visual hierarchy. 

Introduction
JS Chapter 1: “The ABC of Programming” (pp.11-52)

*The Basics*
- A script is a series of instructions.
- designing a script is done by defining tasks and when you have your tasks you can move into planning steps to complete each task
- From steps you can move into code.
- Use a flow chart to scetch out what eash task needs to be
- The document object represents an HTML page
- Computers create models of the world using data
- The models use objects to represent physical things
- Programmers can write code to say when this event occurs run that code
- Web browsers use HTML markup to create a model of the web page
- To make web pages interactive you write code that uses the browser's model if tge web page

> document.write('Write something here') ; 
> ^ that is how you **call a method of an object**

>JavaScript runs where it is found in the HTML

Best Practice is to have JavaScript code in its own JavaScript file. index.js would be an index javascript file

the script element is what will be calling the javascript file in the html code

If you view the source code of the pahe in the browser the JavaScript will not have changed the HTML because the script works with the model of the web page that the browser has created
