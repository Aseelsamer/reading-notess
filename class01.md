#HTML

HTML describes the structure of pages , to describe the structure of any web page we add code to the words we want to appear on the page and use elements too.
Those elements have an opening and closing tag  , Examples (<body></body ,      <h1></h1>)
##The tags act like containers which they tell you about the informations they are holding.
##Attributes : attributes provide additional informations about the content which they apear on the opening tag and made up of two parts : a **name** , a **value** seperated by equals sign.
The majority of attributes can only be used on certain elements.

##Creating a web page on a PC you will need 4 steps :
1-Start button -> All Programs -> Accessories -> Notepad 
2-Type any code 
3-Go to file menu and save the page as *ALL FILES*
4- Open browse and open your file.

On some stores or companie you might have boxes that allow you to enter a title for the product,a description of the product, its price, and the quantity available
The advantage of this approach is that people who do not know how to write web pages can add information to a website and it is also possible to change the presentation of something in the template, and it will automatically update every page that uses that template. 

Because there have been several versions of HTML, each web page should begin with a
DOCTYPE declaration to tell a browser which version of HTML the page is using .
##COMMENTS
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
<!-- comment goes here -->   It's a really good thind to add comments which will remind you later why you did thing.

##ID ATTRIBUTES:It is used to uniquely identify that element from other elements on the page.It is important that no two elements on the same page have the same value for their id attributes. 
##CLASS ATTRIBUTES:a way to identify several elements as being different from the
other elements on the page. The class attributes on any element can share the same value.
##BLOCK ELEMENTS:Some elements will always appear to start on a new line in the browser window. These are known as block level elements such as <p> <h1> <ul> .
##INLINE ELEMENTS:Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. such as <a> <img>  .

There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)
Therefore, if you want these characters to appear on your page you need to use what are termed "escape" characters For example, to write a left angled bracket, you can use either &lt; or &#60;

NEW ##HTML5 LAYOUT ELEMENTS :HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them.
The <header> and <footer> elements can be used for:
-The main header or footer that appears at the top or
bottom of every page on the site.
-A header or footer for an individual <article> or <section> within the page.
-The <nav> element is used to contain the major navigational
blocks on the site such as the primary site navigation.
-The <article> element acts as a container for any section of a
page that could stand alone and potentially be syndicated.
-The <section> element groups related content together, and
typically each section would have its own heading.

###Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
###To make HTML5 elements work in Internet Explorer 8, extra JavaScript is needed, which is available free from Google.

***DESIGING A WEBSITE***
Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to
understand who your target audience is.You should know who your visitors are and why they are coming  to develop your website.
Developing your website can start by doing a wareframe which is a sketch of how you want you site to look like , secound you need to start organizing the informations into sections or pages .
And then you should start with styling your website by chosing colors , sizes and adding images(you can use grouping and similarity to help simplify the information you present)

##JAVASCRIPT 

A script is a series of instructions that a computer can follow to achieve a goal. A browser may use different parts of the script depending on how the user interacts with the page.
To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. (1-Desing the goal 2-Design the script 3-Code each step , do this steps using a flowchart).
Those steps needs to be written in a language the computer will understand ( A JAVASCRIPT PROGRAMMING LANGUAGE).All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow.
 When you use JavaScript in the browser, there is a part of the browser that is called an interpreter (or scripting engine).The interpreter takes your instructions (in JavaScript) and translates them into instructions the browser can use to achieve
the tasks you want it to perform. 
When you want to use JavaScript with a web page, you use the HTML
<script> element to tell the browser it is coming across a script.
Its src attribute tells people where the JavaScript file is stored. 

HOW TO USE OBJECTS AND METHODS ? document.write('');

the document represents the entire web page.
the write('') method of the document object allows new content to be written in the page .
the script elemetn place can affect the loading time of page.









