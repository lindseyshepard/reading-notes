## From the Duckett HTML book:

### Chapter 4: Ch.4 “Links” (pp.74-93)
The art of *Links*
This is how you move from one page to another. In my table of contents, to nagivate through my reading-notes I use a series of links.

using the a tag and an a closing link tag
> <a href="www.google.com"> click me </a>
>> Above is an example of an a tag being used.

**Directory Structure**
As mentioned in Duckett HTML & CSS book, larger websites usually organize code by placing the pages for each different section of the site into a new folder. Sometimes these folders are referred to as directories. 

*Structure*
The top-level is the root folder. The root folder will contain all the files and folders of the website. Sepertaing each page by a folder will help keep the developer organized.

*Relationships*
The relationship between files and folders on a website is described using the same terminology as a family tree. There is also a git command for this to help you see how your project is layed out.

*Homepages*
The main homepage will be written in html and is usually labled index.html


RELATIVE LINK TYPE | EXAMPLE  
----------------- | ----------------  
Same Folder: To link a file in the same folder, just use the file name. | To link to music reviews from the music homepage: <a href="reviews.html">Reviews</a>  
Child Folder: For a child folder, use the name of the child folder, followed by a forward slash, then the file name.  | To link to music listings from the homepage: <a href="music/listings.html">Listings</a>  
Grandchild Folder :Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash then the file name. | To link to DVD reviews from the homepage: <a href="movies/dvd/reviews.html">Reviews</a>  
Parent Folder: Use ../ to indicate the folder above the current one, then follow it with the file name.  |  To link to the homepage from the music reviews: <a href="../index.html">Home</a>  
GrandParent Folder: Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.  |  To link to the homepage from the DVD reviews: <a href="../../index.html">Home</a  


### Chapter 15: “Layout” (pp.358-404)


**Key Concepts in Positioning Elements** 
CSS treats each HTML element as if it is in its own box. This box will either be a block-kevel or an inline box. 
>Block level elements start on a new line. like H1, p, ul or li tags.

>Inline Elements flow in between surround text like the img, b, and i tags.


*Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors. *

Tip:
- Positioning schemes allow you to control the layout of the page using normal flow, relative positiing and absolute positioning. You can float these elements with a float property. 
- Box offset properties to tell the browser how far from the top or bottom and left or right it should be places 
- fixed positioning is a form of absolute
- floating elements allow you to take the element out of normal flow and position it to the far left or right of a containing box. Like when you have an image and a text box with **float** next to it.

> **Parents of floated elementsL PROBLEM**
- If a containing element only
contains floated elements, some
browsers will treat it as if it is
zero pixels tall.

> **Parents of floated element: SOLUTION**
- overflow property is given a value of auto
- the width property is set to 100% 


When I made a website before I had to take into consideration was screen sizing and how it would different from user to user. This is when you sould make you page dymanic and it will adjust to the device it is being viewed on. 

Chapter 15 Layout Summary: 
- <div> elements are often used as containing elements
to group together sections of a page.
- Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.



## Chapter 3 (first part): “Functions, Methods, and Objects”

*Function*
Functions allow you to put together a series of statements to do a task. If you design your functions well you can reuse functions instead of repeating statements.


**Declaring a function**
function sayHello() {

}

That is a function. It is not doing anything yet but it could. 

To call the function from above I would do:
sayHello();

Declaring functions that take in paramaters:
function getArea(width, height){
  return width * height;
}


When you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called arguments, and they can be provided as values or as variabled.

>Parameter and arguments have a small difference... be careful using them interchangably.


**Variable Scope** 
The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as variable scope.
> var and let





[Six Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

My Opinion:

I think this is great. Two sets of eyes on code is always better then one and not only are two people proof reading, this is also two different perspectives. This helps students and developers works together and think through problems. A huge part of my role as a dev is collaboration so being able to write code with someone and navigate through it together while expressing your ideas is a power move