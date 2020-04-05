[Simple Programmer Article](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
## *Understand the problem domain is the hardest part of programming*

"The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint." - John Sonmez

One thing I took from this reading is if you want to be able to debug code and write code well you need to really understand the problem and be able to put together the jigsaw puzzel 'the code' together.


# From the Duckett JS book

## Chapter 3: “Object Literals” (pp.100-105)


![Object example](https://flaviocopes.com/how-to-remove-object-property-javascript/delete-object-property.png)

![Objects](https://image.slidesharecdn.com/javascriptoopcheatsheetv2-140125142421-phpapp02/95/javascript-object-oriented-programming-cheat-sheet-2-638.jpg?cb=1390659899)

Literal Notation is the easiest and the most popular way to create objects
>To access an object you use dot notation as show in the photo above.

![literal](src="https://images0.cnblogs.com/blog/496473/201410/010205101592797.png")


## Chapter 5: “Document Object Model” (pp.183-242)

### The DOM
![dom](https://cf.ppt-online.org/files/slide/l/lG6hjyFR8carDYH7oVAtPW3exEOg0sSpQ1JKfm/slide-4.jpg)

**Attribute Nodes**
The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.
- Attribute nodes are not *children* of the element that carries them; they are *part of* that element

**Text Nodes**
Once you bave accessed an elelemnt node, you can reach the text within that element. This is stored in its own text node.
- Text nodes cannot have children. If an element contains text and another *child* element, the child element is not a child of the text node but rather a child of the containing element. 


**Caching Dom Queries**

Methods that find elements in the DOM tree are called DOM queries. When you need to work with an element more than once, you should use a variable to store the result of this query.
-  built in functions

This chapter was exactly what I needed to read and understand when doing the CSS selector challenge. Everything is broken down to how different elements and are related to eachother.