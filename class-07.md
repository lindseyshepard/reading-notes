# Domain Modeling


Article: [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)


*Thoughts:*
>Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.


- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.


## From the Duckett HTML book:

#### Chapter 6: “Tables” (pp.126-145)

*Summary*
- The <table> element is used to add tabled to a web page.
- A table is drawn out row by row. Each row is created with the <tr> element.
- Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).
- You can make cells of a table span more than one row or column using the **rowspan** and **colspan** attributes
- For long tables you can split the table into <thead>, <tbody>, and <tfoot>




### From the Duckett JS Book:

#### Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

*Summary*
- Functions allow you to group a set of related statements together that represent a single task.
- Functions can take parameters (information required to do their job) and may return a value.
- An object is a series of variables and functions that represent something from the world around you
- In an object, variables are known as properties of the the ovjects; functions are known as methods of the object. 
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window
- JavaScript also has several built-in objects such a *String*, *Number*, *Math*, and *Date*. 
- Arrays and objects can be used to create complex data sets (and both can contain the other)

![object](https://images.slideplayer.com/33/10132887/slides/slide_15.jpg)