# Charts

Charts can show profit data and other marketing skills can be used to figure out how to sell products. In this case it would be best to implement it into our Bus Mall lab.

You can script in a new chart into a html file or just use an exsisting JS file.

## Line Chart

To draw a line chart it needs to be done in html and accessed by DOM in JS.

### Canvas

Canvas is almost like a way for you to draw in javascript.

Example:<!--MDN Web Docs>
>function draw() {
>  var canvas = document.getElementById('canvas');
>  if (canvas.getContext) {
>    var ctx = canvas.getContext('2d');

>    ctx.fillRect(25, 25, 100, 100);
>    ctx.clearRect(45, 45, 60, 60);
>    ctx.strokeRect(50, 50, 50, 50);
>    }
>  }

beginPath()

Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.<!--MDN Web Docs>

Path methods

Methods to set different paths for objects.<!--MDN Web Docs>

closePath()

Adds a straight line to the path, going to the start of the current sub-path.<!--MDN Web Docs>

stroke()

Draws the shape by stroking its outline.<!--MDN Web Docs>

fill()

Draws a solid shape by filling the path's content area.<!--MDN Web Docs>

#### Styling Text 

font = value

The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.<!--MDN Web Docs>

textAlign = value

Text alignment setting. Possible values: start, end, left, right or center. The default value is start.<!--MDN Web Docs>

textBaseline = value

Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.<!--MDN Web Docs>

direction = value

Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.<!--MDN Web Docs>

[Back](https://cesardeltoroc.github.io/reading-notes/)
