## Canvas:
An attribute used to create different types of charts the ```<canvas>``` element has only two attributes, width and height The ```<canvas>``` element can be styled just like any normal image (margin, border, background…). differs from an ```<img> ```tag in that, like for ```<video>```, ```<audio>```, or ```<picture> ```elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

# The rendering context:
To display something, a script first needs to access the rendering context and draw on it. The ```<canvas>``` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context and specify “2d” to get a CanvasRenderingContext2D. sample # Drawing Shapes: ```<canvas>``` only supports two primitive shapes: rectangles and paths, There are three functions that draw rectangles on the canvas:

* fillRect(x, y, width, height) to draw a filled rectangle.
* strokeRect(x, y, width, height) to draw rectangle outeline.
* clearRect(x, y, width, height) making it transparent. steps to draw path:
* beginPath() Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
* closePath() add straight line to path.
stroke() Draws the shape by stroking its outline.
* fill() Draws a solid shape by filling the path’s content area.
final and an optional step, is to call closePath(). This method tries to close the shape by drawing a straight line from the current point to the start. # Drawing text: two methods to render text: * fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. * strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. 
##  Drawing shapes with canvas
Drawing rectangles
There are three functions that draw rectangles on the canvas:

fillRect(x, y, width, height) Draws a filled rectangle.

strokeRect(x, y, width, height) Draws a rectangular outline.

clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent

# Applying styles and colors
# Color
there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color Sets the style used when filling shapes.

strokeStyle = color Sets the style for shapes' outlines.


#### Transparency
globalAlpha = transparencyValue Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.

#  Drawing text
### Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

### Styling text
There are some more properties which let you adjust the way the text gets displayed on the canvas:

font = value The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

textAlign = value Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

textBaseline = value Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

direction = value Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

# Advanced text measurements
measureText() Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.