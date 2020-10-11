# LAYOUT:
CSS treats each element as if it is in its own box. this box will either be a block-level box or inline box.
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

CSS has 3 following positioning schemes 
1- normal flow(In normal flow, each block-level
element sits on top of the next one.)
2-relative positioning(Relative positioning moves an
element in relation to where it would have been in normal flow)
3-absolute positioning(When the position property
is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page)

this all allow you to control the layout of a page, you can specify the positioning scheme using the position property in CSS. You can also float elements using float property.
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

You may need to use box offset to indicate where a box should be positioned and to tell the browser how far from the top or bottom and left or right it should be placed.

The clear property allows you to say that no element  should touch the left or righthand sides of a box. 

-Many web pages use multiple columns in their design. This is achieved by using a <div> element to represent each column. The following three CSS properties are used to position the columns next to each other:
-widht
-float
-margin

IMP:different viewers to your site will have different sized screens that show different amounts of informations so your design needs to be able to work on a range of different sized screens.
Resolution refers to a number of dots a screen shows per inch. some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on.
 


