# Charts

### Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

## setting up th charts
1. The first thing we need to do is download Chart.js.

2. Drawing a line chart:

* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.So add this to the body of our HTML page:

```<canvas id="buyers" width="600" height="400"></canvas>```

* Next, we need to write a script that will retrieve the context of the canvas,o add this to the foot of your body element:
```<script>```
    ```var buyers = document.getElementById('buyers').getContext('2d');```
    ```new Chart(buyers).Line(buyerData);```
```</script>```

* Inside the same script tags we need to create our data for ex.

var buyerData = {

	labels : ["January","February","March","April","May","June"],

	datasets : [

		{

			fillColor : "rgba(172,194,132,0.4)",

			strokeColor : "#ACC26D",
            
			pointColor : "#fff",
            
			pointStrokeColor : "#9DB86D",

			data : [203,156,99,251,305,247]

		}

	]

}

* * *

# the <canvas> element

### At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.


## The rendering context

The ```<canvas>``` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. 

## Checking for support

The fallback content is displayed in browsers which do not support ```<canvas>```. Scripts can also check for support programmatically by simply testing for the presence of the getContext() method.

# Applying styles and colors

* Colors

If we want to apply colors to a shape, there are two important properties we can use: **fillStyle** and **strokeStyle**.

fillStyle = color
Sets the style used when filling shapes.

strokeStyle = color
Sets the style for shapes' outlines.

* Transparency:

In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent). shapesThis is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

globalAlpha = transparencyValue

Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.

The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

# Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

* * *