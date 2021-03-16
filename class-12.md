# Charts:
 are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. 
 ![charts](https://canvasjs.com/wp-content/uploads/images/gallery/javascript-charts/overview/javascript-charts-graphs-index-data-label.png)

 * a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. 

 * At first sight a "canvas"looks like the "img"element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the "canvas" element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 

 * rendering contexts: which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. 

 *  Drawing shapes with canvas
 1. The grid (coordinate space): We should specify our reference.

 1. Drawing rectangles: "canvas" only supports two primitive shapes: rectangles and paths There are three functions that draw rectangles on the canvas:
fillRect(x, y, width, height) Draws a filled rectangle. strokeRect(x, y, width, height) Draws a rectangular outline. clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.


1. Drawing paths: A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. To make shapes using paths, we take some extra steps:
First, you create the path.
Then you use drawing commands to draw into the path.
Once the path has been created, you can stroke or fill the path to render it.


 1. Rectangles: To draw rectangular shapes directly to the canvas: rect(x, y, width, height)
Path2D objects: To simplify the code and to improve performance, the Path2D object, available in recent versions of browsers, lets you cache or record these drawing commands. You are able to play back your paths quickly.


* Colors
fillStyle = color Sets the style used when filling shapes. strokeStyle = color Sets the style for shapes’ outlines.

* Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

![canvas](https://blog.education-ecosystem.com/wp-content/uploads/2018/12/javascript1_ljdngh.png)