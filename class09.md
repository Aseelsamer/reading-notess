# FORMS:
The best known form on the web is probably the search box that sits right in the middle of
Google's homepage.There are several types of form controls that you can use to collect information from visitors
to your site by ADDING TEXT , MAKING CHOICES ,SUBMITTING FORMS , UPLOADING FILES .


How forms work ? A user fills in a form and then pressed a button to submit the information to the server.
the server processes the information using a programming language , it may also store it in database.
A form may have several form controls, each gathering different information. The server needs to know which 
piece of inputted data corresponds with which form element.

Form controls live inside a -form-element. This element should always carry the action attribute
 and will usually have a method and id attribute too, every form element requires an action attributes.
its value is the URL for the page .
Forms can be sent using two forms : -With the get method 
-With the post method

The -input- element is used to create several different form controls. The value of the type
attribute determines what kind of input they will be creating.
The -textarea- element is used to create a mutli-line
text input. Unlike other input elements this is not an empty
element. It should therefore have an opening and a closing tag. 

A drop down list box allows users to select one option from a drop down list.
The -select- element is used to create a drop down list box. It contains two or more -option- elements. 
The -button- element was
introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.

#LISTS,TABLES AND FORMS :
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).
It can be used on rules that apply to the -ol-, -ul-, and -li- elements.
You can specify an image to act as a bullet point using the list-style-image property.

the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box.
As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. 
It is called list-style, and it allows you to express the markers' style, image and position properties in any order.

Table cells can have different borders and spacing in different browsers, but there are properties you can use to control 
them and make them more consistent(border-spacing , border-collapse).

The cursor property allows you to control the type of mouse cursor that should be displayed to users.

#EVENTS:
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling:
1-select the element.
2-indicate which event .
3-selevt the code you want to run .

Event listeners are a more recent approach to handling events.
They can deal with more than one function at a time but they are not supported in older browsers.
 
HTML elements nest inside other elements. if you hover or click on a link , you will also be hovering
or clicking on its parent elements.
the flow of events only really matters when your code has event handlers on an element and
one of its ancestor or descendant elements.

Note:Creating event listeners for a lot of elements can slow down a page
but event flow allows you to listen for an event on a parent element.

User interface CUI) events occur as a result of interaction with the
browser window rather than the HTML page contained within it,
e.g., a page having loaded or the browser window being resized. 

The EVENT object can tell you where the cursor was positioned when an event was trigged.
The most commonly used events are W3C DOMevents, although there are others in the HTMLS specification
 as well as browser-specific events. 
