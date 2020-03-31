## From the Duckett HTML book:

**Chapter 3: “Lists” (pp.62-73)**
3 Lists that are good to know!
1. Ordered List (like this list)
2. Unordered List
3. Definition Lists

*Ordered Lists* | *Unordered Lists*
---------- | -------------
<ol> | <ul>  
<li> | <li>  

*Definition Lists* | What it means  
-------- | --------  
<dl> |  definition list is created with this tag. Inside this tag you will see the dt and dd tags  
<dt> | This is to contain the term being defined  
<dd>  | Contains the definition  


![Ordered vs unordered](/uploads/media/default/0001/01/f79ee5dc2b2caadbea97e73eab152db65e868539.png)

Pro Tip:
> Nested Lists
>> ![nested](https://s3.amazonaws.com/webucator-how-tos/419.png)


## 
Chapter 13: “Boxes” (pp.300-329)
 One thing I read in this chapter was how it mentions that the CSS treats each HTML element as if it lives in its own box. That is a great way to think about it, in layers is how you design the look of the pages.

 box dimensions, every box has a width and a heigh
 there is also Limiting width. This comes into handy if users will be looking at your page on different devices. You can have a min-width, or a max-width and that will adjust your page on what the size of the device the user has

 I think the most important ones to know when it comes to boxes
 > Boarder, Margin and Padding.
 >> You can find these in the dev tools by inspecting a page and see what you want to change live.

 White space matters! Having good white space between elements could influence how the user percieves your page.

 - You can use CSS to control the dimensions of a box
 - you can hide elements using the display and visibility properties
 - CSS3 you can get fancy with the borders






# 

## From the Duckett JS book:

**Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)**
*Like what we used on day 2 of class the if and else statements check for a condition*
If the condition resolves as false then the else code block will be ran instead.

A Switch Statement starts with a variable called the switch value. Each case indicates a possible value for the variable and the code thats hould be run if the variable matches the value. Think of this in terms of games and you level up. case 1 could be level 1, case 2 could be level 2. Or a menu, if the user selects 3 then the case statement would execute case 3. 

![for loop](https://cdn.tutsplus.com/net/uploads/legacy/216_dom/img/for_loop.png)

Then there are Loops, Loop counters and looping.
Loops like a for loop, for while, while, do while loops are all ways to continuesly go through code a desired amount of times. Each loop is used for slightly different situations and most the time a good dev will keep in mind when to use what loop. 

![loop](https://i.ytimg.com/vi/E3WuOTyN0eQ/maxresdefault.jpg)

Loops check conditions, A for loop uses a counter as a condition. 
The difference between a while and a do ... while loop is that the statement comes *before* the condition. The do is run regardless if the condition is met and depending on where the while is, too.