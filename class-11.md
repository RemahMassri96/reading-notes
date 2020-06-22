
# canves & chart.js 

- Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

## Creating a Chart
 It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.
 
 
 The `<canvas>` element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas. When no styling rules are applied to the canvas it will initially be fully transparent
 
 - the `<canvas>` element requires the closing tag (</canvas>).
 
 Applying styles and colors on your next chart :
 
 Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

 fillStyle = color
Sets the style used when filling shapes.

strokeStyle = color
Sets the style for shapes' outlines.

Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

