## From the Duckett HTML book:

### Chapter 2: “Text” (pp.40-61)


**Structural markup:** the elements that you use that helps you understand what headings and or paragraphs are
**Semantic markup:** this is what give the user extra information. Example like if you have written a quote it could tell you who said it, if you used an acronym if could tell you what it stands for.
>Tags are know as markup. 

<em><strong>Beware:</strong> </em> of the strong and emphasis tags!
- HTMLelements are used to describe the structures of the page
- HTML elementscan also provide semantic information like my beware example above. Check out the code behind the scenes!

### Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)

HTML is the structure of the page but the CSS gives it the look that the designer is shooting for. You can specify the rules that the content will follow. This is where you change the background color, the margins, how you align the footer to the bottom of the page. How the page will be displayed to the end user - that will be determined here!

![pesticide example of css in chrome](https://lh3.googleusercontent.com/LPyTSVO7bdbOHvXyMLyVxf_-z1K7mRiXVESmmqG6XReGP9St8NDm3tYnVgXyva9ytEDhYOmlZQ=w640-h400-e365)

*If the image above displayed properly, you will see all the elements of a web page boxed by its different elements.*

Tips and Tricks
- CSS associates style rules with HTML elements
- CSS properties affect how elements are displayed

1. CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
2. Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
3. Different types of selectors allow you to target your
rules at different elements.
4. Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
5. CSS rules usually appear in a separate document,
although they may appear within an HTML page.
>page 251 of Jon Duckett (HTML and CSS design and build websites)

# 

## From the Duckett JS book:

### Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

> Scripts are a series of instructions that a computer can understand and follow 1 step at a time

- Comments are not visible to the end user but can be super helpful for the developer. It can leave descriptions about the code within the code so it is easier to read and understand by humans

**The Other Basics!**
How do you declare a variable?
> var nameThatVariable; 

How do you assign a value to a variable?
> var nameThatVariable = 3; 

What is a variable and a data type?
> A variable will be a **data type**. Datatypes could be a string 'A string are characters in queotes' or an integer which is a number. It could also be null or undefined or a boolean. But we will come to that later. A datatype is what JavaScript used to tell the difference between numbers, string and true/false values(boolean).


Arrays? Something tells me an Array has nothing to do with the ocean critter.
> That is because it doesn't! An array is a string of datatypes (a list of variables).
>> var list;
>> list = ['apples', 'bread', 'milk', 'eggs'];

Expressions and operators go hand in hand but another source to help with a visual,[Click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

*For the sake of keeping life simple, an **expression** results in a value. However there are two types of expression you can have.*
1. Expression that assign a value to a variable
> var name = 'Lindsey';
2. Expressions that use two or more values to return a single value
> var area = 7 * 7;


Operators!
> ![operators](http://4.bp.blogspot.com/-gvckZxbneSQ/TyYv6-iwsTI/AAAAAAAAAAc/BCmKTFbyeZw/s1600/Arithmetic+Operators.PNG) 

### Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)

Decisions are a huge part of writing code. Decisions help determine the output the user is looking for, or putting in. The decision that needs to be made within each step of code is planned during the design process of creating the program. Usually a flow chart will help the developer write which way the code will behave depending on decisions. With decision making comes evaluation conditional and conditional statements. This is a great example of the code coming to 'a fork in the road,' making a decison and continuring on the correct path. 
> ![if statement example](https://2.bp.blogspot.com/-aA2KSOpvhqk/VxGeGprmQKI/AAAAAAAACPs/roqt7RSUsAoK-ILhURBtiseh3-QKAgRVQCKgB/s640/php2.jpg)

Decisions in code need a way to be presented to the user. In the code conditional statements would be used to help decide the path of the data.
>![conditional statements](https://d1e4pidl3fu268.cloudfront.net/48295477-61ac-4b5e-a6dc-456acd3ab0a6/comparisonoperators.png)

**ThE StAtEmEnTs oF ChOiCe**
 You got to see an If statement example, what other statements can developers use?
 1. if
 2. if-else
 3. switch statements(but this one is for another day)


 Lets look at an if next to an if... else statement.
 ![compare](https://i1.wp.com/simplesnippets.tech/wp-content/uploads/2018/10/nested-if-statement-flow-diagram-in-javascript.jpg?resize=683%2C750&ssl=1)