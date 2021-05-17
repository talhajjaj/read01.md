**chart:** 
charts is easier to look at it and take data from it but its not easy to created ..
if you want to start creating a chart you should start with Chart.js, you can use all kinds of chart as ; bar,line,pie ..
let's start togather working on a chart ;

first download Chart.js..

how to draw aline chart?

copy the chart.min.js into the directory you’ll be working in. Then create a new html page and import the script to it .
then after that you need to creat canvas element in HTML copy the canvas element then past it in the body .
Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

Drawing a pie chart;

how to creat it ?

first you need to add the canvas element copy it from the site .
Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section.
then add the options its have a work first its remove the stroke from segments .

the canvas element ;
the canvas element its added to the HTML, it has only two attributes, width and height.
but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted,
specifying your width and height to avoid this issue.
the canvas element requires the closing tag /canvas. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

**Drawing shapes with canvas;**
- The grid:

Before we can start drawing,The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). 

- Drawing rectangles:

supports two primitive shapes: rectangles and paths,all other shapes must be created by combining one or more paths. 

and you can creat ;Lines,moving the pen,drawing a triangle, drawing paths.


**Applying styles and colors**

- Colors;  If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
color is a string representing a CSS,

-Transparency;
In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property .

- Line styles; 
There are several properties which allow us to style lines, here some of;

lineWidth = value
Sets the width of lines drawn in the future.
lineCap = type
Sets the appearance of the ends of lines.
lineJoin = type
Sets the appearance of the "corners" where lines meet.

- Drawing text;
The canvas rendering context provides two methods to render text:
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw .
Styling text;
There are some more properties which let you adjust the way the text gets displayed on the canvas:
font = value
textAlign = value
textBaseline = value