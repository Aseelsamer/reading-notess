# TABLES:
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

The table element is used
to create a table. The contents
of the table are written out row
by row.

tr-You indicate the start of each row using the opening Tr tag. (The tr stands for table row.) It is followed by one or more td elements (one for each cell in that row).
At the end of the row you use a closing tr tag.
td Each cell of a table is represented using a td element. (The td stands for
table data.) At the end of each cell you use a
closing td tag.

The th element is used just like the td element but its purpose is to represent the heading for either a column or
a row.

There are three elements that help distinguish between the
main content of the table and the first and last rows 
1-thead
2-tbody
3-tfoot

The width attribute was used on the opening table tag to
indicate how wide that table should be and on some opening
th and td tags to specify the width of individual cells.
The value of this attribute is the width of the table or cell in pixels.

The border attribute was used on both the table and td
elements to indicate the width of the border in pixels.

# FUNCTIONS,METHODS & OBJECTS :
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function.

To declare a function you give it a name and then write the statements needed to achieve its task inside the curly braces braces.This is known as a function declaration.

Having declared the function,you can then execute all of the statements between its curly braces with just one line code. and this is called CALLING THE FUNCTION.
When you declare the function you give it parameters.
inside the function, the parameters act like variables.
When you call a function that has parameters, you specify the values it should use in the parantheses that follow its name. These values are called arugments and can be provided as values or variables.
Array is when you can return a function with more than one value.


OBJECT:Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 
If a variable is part of an object, it is called a
property but If a function is part of an object, it is called a method.

You access the properties of an object using dot notation. You can also access properties using square brackets.
The new keyword and the object constructor create a blank object , you can add properties and methods to the object.
Object construction can use a function as a template for creating objects were you first create the template with the object's properties and methods.
Construction function let you create instances numbers of objects.
The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates. 
When a function is defined inside an object, it becomes a method. In a method, this refers to the containing object. 
**If you want to access items via a property name or key, use an object If the order of the items is important, use an array. **

Arrays are actually a special type of object. they hold a related set of key/value pairs but the key for each value it its index number.
You can combine arrays and objects to create complex data structures were arrays can store series of objects , objects can also hold arrays.

-In order to work with dates, you create an instance of the data object. You can then specify the time and date that you want it to represent.

Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window. 

JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts. 