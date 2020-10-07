#IMAGES:
Adding image to your website you need to use the tag img it must carry the following two attributes:
1-src which tells the browser where it can find the img.
2-alt it provides a text description of the img which describes the img if you don't see it.
3-title you can use it to provide additional inforamtions.
4-height it specifies the height of img.
5-width which specifies the width of an img.

-Where img is placed will affect your code there is three places to place the img :
1-before a paragraph
2-inside the start of a paragraph
3-in the middle of a paragraph

We have another attribute which is used to indicate how the other parts of a page should flow around 
an img and this is called ALIGN.
it can be aligned vertically (top,middle,bottom).

3 rules for creating an img:
First you save the img in the right format.
2-save imgs at the right size.
3-use the correct resolution.

Images often come with captions. HTML5 has introduced a new <figure> element to contain images and 
their caption so that the two are associated. 
The <figcaption> element has been added to HTML5 in order to allow web page authors to add
a caption to an image.

#COLOR:
the color property allows you to specify the color using 3 different methods:
1-RGB values
2-HEX codes
3-color names

You can aslo specify background color with the same 3 methods for the color >
-Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.
When picking foreground and background colors, it is important to ensure that there is
enough contrast for the text to be legible.
for example text is harder to read when there is low contrast between background and colors.

we have something called the opacity property which allows you to
specify the opacity of an element and any of its child elements.
The value is a number between 0.0 and 1.0

another new and intuitive way to specify colors using hue, saturation,and lightness values.
HUE (represent a color cirle) , SATURATION(amount of grey in color) , LIGHTNESS (amount of white in color)


#TEXT:
Typeface(type of text) :
Serif fonts have extra details on the ends of the main strokes of the letters. 
Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
Every letter in a monospace (or fixed-width) font is the same
width. (Non-monospace fonts have different widths.)

We have different styles,weights and stretch of text.
IMPORTANT NOTE :When choosing
a typeface, it is important to understand that a browser will usually
only display it if it's installed on that user's computer.

The font-family property allows you to specify the typeface that should be used for
any text inside the element(s) to which a CSS rule applies.

The font-size property enables you to specify a size for the
font. There are several ways to specify the size of a font. The
most common are:Pixels and Percentages.

@font-face allows you to use a font, even if it is not installed
on the computer of the person browsing, by allowing you to
specify a path to a copy of the font, which will be downloaded if
it is not on the user's machine.

The font-weight property allows you to create bold text.
There are two values that this property commonly takes normal,bold.

The text-transform property is used to change the case of text giving it one of the following
values:uppercase , lowercase , capitalize .

Kerning is the term typographers use for the spacebetween each letter. You can
control the space between each letter with the letter-spacing property

The text-align property allows you to control the alignment of
text. The property can take one of four values: left, right , center and justify.

The text-shadow property is used to create a drop shadow, which is a dark version
of the word just behind it and slightly offset.
