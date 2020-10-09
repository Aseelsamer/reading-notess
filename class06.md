# WHAT IS AN OBJECT ?
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 

In an object variables become known as properties (if it is a part on an object it is called a property).
& Functions become known as methods .

The value of a property can be a string, number Boolean, array, or even another object. The value of a method is always a function. 
NOTE:An object can not have two keys(name) with the same name. this is because keys are used to access their corresponding values.

In JavaScript:
• Variables have a name and you can assign them a
value of a string, number, or Boolean.
• Arrays have a name and a group of values. (Each
item in an array is a name/value pair because it
has an index number and a value.)
• Named functions have a name and value that is a
set of statements to run if the function is called.
• Objects consist of a set of name/value pairs.

The object is the curly braces and their contents, seperate each key from its value using a colon , seperate each property and method with a comma.
To access a property or method of an object you use the name of the object followed by a period then the name of property you want to access --> this is known as dot notations.
You can also access the properties of an object using square brackets syntax.

# DOCUMENT OBJECT MODEL :
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 

Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser. 

The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree. 
Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node. 

Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 

The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element. 
Methods that find elements in the DOM tree are called DOM queries.When people talk about storing elements in variables, they are really storing the location of the elements within the DOM tree in a variable.
The properties and methods of that element node work on the variable.

DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 
If a method can return more than one node, it will
always return a Nodelist, which is a collection of
nodes (even if it only finds one matching element).
You then need to select the element you want from
this list using an index number (which means the
numbering starts at 0 like the items in an array). 

Methods that select individual elements are getElementyById and querySelector . Both used as a similar syntax.

There are two ways to select an element from a Nodelist: The item() method and array syntax.
Both require the index number of the element you want. 

Array syntax is perferred over the item method because it is faster but before selecting a node from the Nodelist, check that is contains nodes.and store it in a variable.

When you have a Nodelist, you can loop through each node in the collection and apply the same statements to each.

# ADDING OR REMOVING HTML CONTENT :
there are two different approaches to adding and removing content from a DOM tree: the innerHTML property and DOM manuipulation.

The innerHTML property contains:
-Approach(innerHTML can be used on any element node.)
-Adding content(Store new content or select the element whose content you want to replace)
-Removing content(to remove an element you set innerHTML to an empty string)

There are two ways to select an element from a Nodelist: The item() method and array syntax.
Both require the index number of the element you want. 
1-Store the element to be removed in a variable.
2-Store the parent of that element in a variable.
3-Remove the element from its containing element.

Updating HTML content :
document.write() is a simple way to add content that was not in the original source code.(ADV quick and easy way to show beginners how content can be added to a page)
element.innerHTML property let you get or update the entire content of any element(ADV faster than DOM ,simple way to remove all of the content from one element)

Once you have an element node, you can use other properties and methods on that element node to access and change its attributes.
There are two ways: Select the element node then use one of the methods to work with that element's attributes.



