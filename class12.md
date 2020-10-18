# CREATING CHARTS WITH CHARTS.JS :
A great way to create charts.js is to draw the graph on page . 
The first you have to download charts.js , copy the chart.min.js out of the unzipped folder and into the directory , then create html page and import script.

To draw a line chart you have to create a canvas element in our HTML and add it to the body of your HTML page , then add retrieve to the context of canvas and create your data inside it(with the line that begins ‘var buyers=’:)

Then :
-Canvas element( the -canvas- element has only two attributes, width and height. These are both optional and can also be set using DOM properties.)

-get context and instanitiate chart.(For example, we could provide a text description of the canvas content or provide a static image of the dynamically rendered content. )

# NOTE:Scripts can also check for support programmatically by simply testing for the presence of the getContext() method.

-create data.(value & color) add your options

Finally, let’s add  a bar chart to our page(same steps up)

The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.

# HOW TO DRAW ON CANVAS?
-first the grid which will tell you the coordinator (x.y) and how the translate to the origin differes.

-Drawing rectangles :
There are three functions that draw rectangles on the canvas:

fillRect(x, y, width, height)
Draws a filled rectangle.

strokeRect(x, y, width, height)
Draws a rectangular outline.

clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

The fillRect() function draws a large black square 100 pixels on each side. 
The clearRect() function then erases a 60x60 pixel square from the center, 
and then strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square.

-Drawing paths :
Here are the functions used to perform these steps:

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.

-Lines:

For drawing straight lines, use the lineTo() method.

lineTo(x, y)
Draws a line from the current drawing position to the position specified by x and y.

-Arces:
To draw arcs or circles, we use the arc() or arcTo() methods.

-Rectangles:
rect(x, y, width, height)
Draws a rectangle whose top-left corner is specified by (x, y) with the specified width and height.

# APPLYING STYLES:

-Colors:
fillStyle = color
Sets the style used when filling shapes.
strokeStyle = color
Sets the style for shapes' outlines

-Transparency:

In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

-Line dashes:
Using line dashes
The setLineDash method and the lineDashOffset property specify the dash pattern for lines.

-Patterns:
createPattern(image, type)
Creates and returns a new canvas pattern object. image is a CanvasImageSource (that is, an HTMLImageElement, another canvas, a video element, or the like. type is a string indicating how to use the image.


-Shadows:
shadowOffsetX = float
shadowOffsetY = float
shadowOffsetBlur = float
shadowColor = float


# DRAWING TEXT :
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

Styling Text :
font=value
textAlign= value
textBaseline = value
direction =value

-Advance text measurements :
measureText()
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.





