#LISTS:
-Ordered list written between open tags and enging tags as -ol- .
Each item in the list is placed between opening and closing tags . The li tag stands for list item .
-Unordered list is created with ul element .

##DEFINITION LIST :
this list is created with d1 element and consist of series of terms and their definitions.

the dt is used to contain the term being defined.
the dd used to contain definition.

##NESTED LIST:
you can put second list inside an li element to create a sub-list or nested list.


#BOXES:
The most popular ways tospecify the size of a box are to use pixels, percentages, or ems.When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.

the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch.(this also for the height).

##OVERFLOW:
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself.
 It can have one of two values: 1-hidden(it hides any extra content)
  2-scroll(adds scrollbar to the box so users scroll and see missing content)

Every box has a margin , the margin separates the edge of one box from another.
Margin sit outside the edge of the border , Padding is the space between the border of a box and any content within it .
The padding and margin are very helpful in adding space between various items on the page.
##Border-width: the border width is used to control the width of border the value can be given by pixel or using - thin,medium,thick .

If you want to center a box on the page (or center it inside
the element that it sits in), you can set the left-margin and right-margin to auto.
The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.

The values of this can be : Inline,Block,Inline-block,None . The visibility property allows you to hide boxes from users but It leaves a space where the
element would have been. This property can take two values:hidden, visible.

The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.The box-shadow property allows you to add a drop shadow around a box. 

CSS3 introduces the ability to create rounded corners on any box, using a property called border-radius. The value indicates the size of the radius in pixels.

#ARRAYS:
An array is a special type of variable. It doesn't
just store one value; it stores a list of values. 
You should consider using an
array whenever you are working
with a list or a set of values that
are related to each other.
You create an array and give it
a name just like you would any
other variable (using the var
keyword followed by the name of
the array).
Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one). 
1-NUMBERING ITEMS IN
AN ARRAY 
2-ACCESSING ITEMS IN
AN ARRAY 
3-NUMBER OF ITEMS IN
AN ARRAY 

#IF..ELSE STATEMENTS:
the if else statement checks a condition. if it resolves to true the first code block is executed and the false means the second code block is run instead.


#SWITCH STATEMENT: 
this statement starts with a variable called the switch value. each case indicates a possible value for this variable.
Falsy values are treated as if they
are fa 1 se. 
Truthy values are treated as if
they are true.
A unary operator returns a
result with just one operand. 
Logical operators are processed left to right.
They short-circuit (stop) as soon as they have a
result - but they return the value that stopped
the processing (not necessarily true or fa 1 se). 

#LOOPS:
check condition if it returns true, a code block will run then the condition will be checked again and again it repeats until the condition returns false.

FOR used if you want to run code a specific number of items. for loop uses a counter as a condition , there is three statements(Intialization,Condition,Update) 
WHILE used when you do not know the number of times the loop will be repeated.
DO WHILE similar to while loop but has one difference it will always run the statement inside the curly braces at least once even if the condition false.

