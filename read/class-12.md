# Chart.js And Canvas


> Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.


* Setting up 
    * `<script src='Chart.min.js'></script>`

* Drawing a line chart 
    * `<canvas id="buyers" width="600" height="400"></canvas>`

* Drawing a pie chart 
    * `<script src='Chart.min.js'></script>`

* Drawing a bar chart 
    * `<canvas id="income" width="600" height="400"></canvas>`


## Basic usage of canvas:

* The `<canvas>` element
    * `<canvas id="tutorial" width="150" height="150"></canvas>`

* Fallback content
    * The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

Providing fallback content is very straightforward: just insert the alternate content inside the `<canvas>` element. Browsers that don't support `<canvas>` will ignore the container and render the fallback content inside it. Browsers that do support `<canvas>`> will ignore the content inside the container, and just render the canvas normally.    


# The grid
>Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.


# Applying styles and colors
>In the chapter about drawing shapes, we used only the default line and fill styles. Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.


# Drawing text
>Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
